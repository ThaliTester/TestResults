#### Test 48037250d07ed06 Logs

Status: 
```

server : IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":25}}
Star Android tests : performance tests, start tests with timer

Test[0]: testFindPeers.js, timeout : 700000, data : {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
Star iOs tests : performance tests, start tests with timer
Test[0]: testFindPeers.js, timeout : 700000, data : {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}

listening on *:3000

got connection 

Android  DEV5731 added : 1.182 sec., device count 1

got connection 

got connection 

got connection 

Android  DEV4792 added : 1.515 sec., device count 2

Android  DEV9615 added : 1.561 sec., device count 3

Android  DEV9958 added : 1.661 sec., device count 4

got connection 

Android  DEV3665 added : 3.203 sec., device count 5

got connection 

Android  DEV4169 added : 3.542 sec., device count 6

got connection 

Android  DEV1994 added : 4.099 sec., device count 7

got connection 

Android  DEV6513 added : 15.179 sec., device count 8

got connection 

got connection 

Android  DEV7041 added : 19.884 sec., device count 9

Android  DEV9027 added : 19.909 sec., device count 10

got connection 

Android  DEV714 added : 21.753 sec., device count 11

got connection 

Android  DEV5151 added : 43.574 sec., device count 12

got connection 

got connection 

Android  DEV2807 added : 47.611 sec., device count 13

Android  DEV4442 added : 47.81 sec., device count 14

got connection 

Android  DEV6441 added : 48.819 sec., device count 15

got connection 

Android  DEV8510 added : 49.537 sec., device count 16

got connection 

Android  DEV6348 added : 50.203 sec., device count 17

got connection 

Android  DEV6153 added : 70.789 sec., device count 18

got connection 

Android  DEV9290 added : 158.783 sec., device count 19

got connection 

Android  DEV6349 added : 159.94 sec., device count 20

got connection 

Android  DEV7246 added : 161.169 sec., device count 21

got connection 

Android  DEV7384 added : 164.369 sec., device count 22

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 22 devices.

start test[0] with 22 devices.


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m


android : Error: Command failed: Error: Command failed: run_.sh aborted
 [0m


TIMEOUT REACHED!
```
###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 03157df360a1882a app:com.test.thalitest code:null 
child process exited with code null on device 03157df360a1882a 
Error! Unexpected exit on device 30049d9501da2100 app:com.test.thalitest code:null 
child process exited with code null on device 30049d9501da2100 
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:null 
child process exited with code null on device LGH8153b36be34 
Error! Unexpected exit on device W3D7N15428022572 app:com.test.thalitest code:null 
child process exited with code null on device W3D7N15428022572 
Android task is completed 
```

Logcat output:
```
samsung-SM-G920F: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(20518): Initializing JXcore engine
W/jxcore-log(20518): JXcore engine is ready
,W/jxcore-log(20518): Starting JXcore engine
,W/jxcore-log(20518): Platform android
W/jxcore-log(20518): 
W/jxcore-log(20518): Process ARCH arm
W/jxcore-log(20518): 
,I/jxcore-log(20518): JXcore Cordova bridge is ready!
I/jxcore-log(20518): 
W/jxcore-log(20518): JXcore engine is started
,I/jxcore-log(20518): Turning radios to true
I/jxcore-log(20518): 
,I/jxcore-log(20518): toggleBluetooth - 
I/jxcore-log(20518): 
,I/jxcore-log(20518): toggleWiFi
I/jxcore-log(20518): 
,I/jxcore-log(20518): my name is : DEV6441
I/jxcore-log(20518): 
I/jxcore-log(20518): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(20518): 
,I/jxcore-log(20518): attempting to connect to test coordinator
I/jxcore-log(20518): 
,I/jxcore-log(20518): check test folder
I/jxcore-log(20518): 
,I/jxcore-log(20518): found test : ./testFindPeers.js
I/jxcore-log(20518): 
,I/jxcore-log(20518): found test : ./testReConnect.js
I/jxcore-log(20518): 
,I/jxcore-log(20518): found test : ./testSendData.js
I/jxcore-log(20518): 
,I/jxcore-log(20518): Test app app.js loaded
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Client has connected to the server!
I/jxcore-log(20518): 
,I/jxcore-log(20518): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(20518): 
,I/jxcore-log(20518): Start now : testFindPeers.js
I/jxcore-log(20518): 
,I/jxcore-log(20518): stop tests now !
I/jxcore-log(20518): 
,I/jxcore-log(20518): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(20518): 
,I/jxcore-log(20518): serverPort is 8876
I/jxcore-log(20518): 
,I/jxcore-log(20518): StartBroadcasting started ok
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}],
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV1994","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(20518): 
,I/jxcore-log(20518): CoordinatorConnector disconnect called
I/jxcore-log(20518): 
,I/jxcore-log(20518): The client has disconnected!
I/jxcore-log(20518): 
,I/jxcore-log(20518): stop tests now !
I/jxcore-log(20518): 
,I/jxcore-log(20518): stop current!
I/jxcore-log(20518): 
,I/jxcore-log(20518): testFindPeers stopped
I/jxcore-log(20518): 
,I/jxcore-log(20518): StopBroadcasting went ok
I/jxcore-log(20518): 
,I/jxcore-log(20518): turning Radios off
I/jxcore-log(20518): 
,I/jxcore-log(20518): Turning radios to false
I/jxcore-log(20518): 
,I/jxcore-log(20518): toggleBluetooth - 
I/jxcore-log(20518): 
,I/jxcore-log(20518): toggleWiFi
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,I/jxcore-log(20518): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20518): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(28169): Initializing JXcore engine,
,W/jxcore-log(28169): JXcore engine is ready,
,W/jxcore-log(28169): Starting JXcore engine
,W/jxcore-log(28169): Platform android
W/jxcore-log(28169): 
,W/jxcore-log(28169): Process ARCH arm
W/jxcore-log(28169): 
,I/jxcore-log(28169): JXcore Cordova bridge is ready!
I/jxcore-log(28169): 
,W/jxcore-log(28169): JXcore engine is started
,I/jxcore-log(28169): Turning radios to true
I/jxcore-log(28169): 
,I/jxcore-log(28169): toggleBluetooth - 
I/jxcore-log(28169): 
,I/jxcore-log(28169): toggleWiFi
I/jxcore-log(28169): 
,I/jxcore-log(28169): my name is : DEV2249
I/jxcore-log(28169): 
,I/jxcore-log(28169): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(28169): 
,I/jxcore-log(28169): attempting to connect to test coordinator
I/jxcore-log(28169): 
,I/jxcore-log(28169): check test folder
I/jxcore-log(28169): 
,I/jxcore-log(28169): found test : ./testFindPeers.js
I/jxcore-log(28169): 
,I/jxcore-log(28169): found test : ./testReConnect.js
I/jxcore-log(28169): 
,I/jxcore-log(28169): found test : ./testSendData.js
I/jxcore-log(28169): 
,I/jxcore-log(28169): Test app app.js loaded
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): LogCallback not set !!!!
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,I/jxcore-log(28169): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(28169): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(31258): Initializing JXcore engine
W/jxcore-log(31258): JXcore engine is ready
W/jxcore-log(31258): Starting JXcore engine
W/jxcore-log(31258): Platform android
W/jxcore-log(31258): 
W/jxcore-log(31258): Process ARCH arm
W/jxcore-log(31258): 
,I/jxcore-log(31258): JXcore Cordova bridge is ready!
I/jxcore-log(31258): 
,W/jxcore-log(31258): JXcore engine is started
,I/jxcore-log(31258): Turning radios to true
I/jxcore-log(31258): 
,I/jxcore-log(31258): toggleBluetooth - 
I/jxcore-log(31258): 
,I/jxcore-log(31258): toggleWiFi
I/jxcore-log(31258): 
,I/jxcore-log(31258): my name is : DEV6348
I/jxcore-log(31258): 
I/jxcore-log(31258): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(31258): 
,I/jxcore-log(31258): attempting to connect to test coordinator
I/jxcore-log(31258): 
,I/jxcore-log(31258): check test folder
I/jxcore-log(31258): 
,I/jxcore-log(31258): found test : ./testFindPeers.js
I/jxcore-log(31258): 
,I/jxcore-log(31258): found test : ./testReConnect.js
I/jxcore-log(31258): 
,I/jxcore-log(31258): found test : ./testSendData.js
I/jxcore-log(31258): 
,I/jxcore-log(31258): Test app app.js loaded
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
I/jxcore-log(31258): LogCallback not set !!!!
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Client has connected to the server!
I/jxcore-log(31258): 
,I/jxcore-log(31258): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(31258): 
,I/jxcore-log(31258): Start now : testFindPeers.js
I/jxcore-log(31258): 
,I/jxcore-log(31258): stop tests now !
I/jxcore-log(31258): 
,I/jxcore-log(31258): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(31258): 
,I/jxcore-log(31258): serverPort is 8876
I/jxcore-log(31258): 
,I/jxcore-log(31258): StartBroadcasting started ok
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(31258): 
,I/jxcore-log(31258): CoordinatorConnector disconnect called
I/jxcore-log(31258): 
I/jxcore-log(31258): The client has disconnected!
I/jxcore-log(31258): 
,I/jxcore-log(31258): stop tests now !
I/jxcore-log(31258): 
I/jxcore-log(31258): stop current!
I/jxcore-log(31258): 
I/jxcore-log(31258): testFindPeers stopped
I/jxcore-log(31258): 
,I/jxcore-log(31258): StopBroadcasting went ok
I/jxcore-log(31258): 
,I/jxcore-log(31258): turning Radios off
I/jxcore-log(31258): 
,I/jxcore-log(31258): Turning radios to false
I/jxcore-log(31258): 
,I/jxcore-log(31258): toggleBluetooth - 
I/jxcore-log(31258): 
,I/jxcore-log(31258): toggleWiFi
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,I/jxcore-log(31258): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31258): 
,TIME-OUT KILL (timeout was 1800000ms)

HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log(31673): Initializing JXcore engine
W/jxcore-log(31673): JXcore engine is ready
W/jxcore-log(31673): Starting JXcore engine
W/jxcore-log(31673): Platform android
W/jxcore-log(31673): 
W/jxcore-log(31673): Process ARCH arm
W/jxcore-log(31673): 
,I/jxcore-log(31673): JXcore Cordova bridge is ready!
I/jxcore-log(31673): 
W/jxcore-log(31673): JXcore engine is started
,I/jxcore-log(31673): Turning radios to true
I/jxcore-log(31673): 
,I/jxcore-log(31673): toggleBluetooth - 
I/jxcore-log(31673): 
,I/jxcore-log(31673): toggleWiFi
I/jxcore-log(31673): 
,I/jxcore-log(31673): my name is : DEV2807
I/jxcore-log(31673): 
I/jxcore-log(31673): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(31673): 
,I/jxcore-log(31673): attempting to connect to test coordinator
I/jxcore-log(31673): 
,I/jxcore-log(31673): check test folder
I/jxcore-log(31673): 
I/jxcore-log(31673): found test : ./testFindPeers.js
I/jxcore-log(31673): 
I/jxcore-log(31673): found test : ./testReConnect.js
I/jxcore-log(31673): 
,I/jxcore-log(31673): found test : ./testSendData.js
I/jxcore-log(31673): 
,I/jxcore-log(31673): Test app app.js loaded
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
I/jxcore-log(31673): LogCallback not set !!!!
I/jxcore-log(31673): 
,I/jxcore-log(31673): Client has connected to the server!
I/jxcore-log(31673): 
,I/jxcore-log(31673): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(31673): 
,I/jxcore-log(31673): Start now : testFindPeers.js
I/jxcore-log(31673): 
I/jxcore-log(31673): stop tests now !
I/jxcore-log(31673): 
,I/jxcore-log(31673): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(31673): 
,I/jxcore-log(31673): serverPort is 8876
I/jxcore-log(31673): 
,I/jxcore-log(31673): StartBroadcasting started ok
I/jxcore-log(31673): 
,I/jxcore-log(31673): CoordinatorConnector disconnect called
I/jxcore-log(31673): 
I/jxcore-log(31673): The client has disconnected!
I/jxcore-log(31673): 
I/jxcore-log(31673): stop tests now !
I/jxcore-log(31673): 
I/jxcore-log(31673): stop current!
I/jxcore-log(31673): 
I/jxcore-log(31673): testFindPeers stopped
I/jxcore-log(31673): 
,I/jxcore-log(31673): StopBroadcasting went ok
I/jxcore-log(31673): 
,I/jxcore-log(31673): turning Radios off
I/jxcore-log(31673): 
,I/jxcore-log(31673): Turning radios to false
I/jxcore-log(31673): 
,I/jxcore-log(31673): toggleBluetooth - 
I/jxcore-log(31673): 
,I/jxcore-log(31673): toggleWiFi
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 
I/jxcore-log(31673): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31673): 


```

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:null 
child process exited with code null on device 09a9416e0297d102 
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:null 
child process exited with code null on device LGD7228ee9cf5b 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 9054): Initializing JXcore engine
W/jxcore-log( 9054): JXcore engine is ready
W/jxcore-log( 9054): Starting JXcore engine
,W/jxcore-log( 9054): Platform android
W/jxcore-log( 9054): 
W/jxcore-log( 9054): Process ARCH arm
W/jxcore-log( 9054): 
,I/jxcore-log( 9054): JXcore Cordova bridge is ready!
I/jxcore-log( 9054): 
,W/jxcore-log( 9054): JXcore engine is started
,I/jxcore-log( 9054): Turning radios to true
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): toggleBluetooth - 
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): toggleWiFi
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): my name is : DEV1994
I/jxcore-log( 9054): 
I/jxcore-log( 9054): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): attempting to connect to test coordinator
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): check test folder
I/jxcore-log( 9054): 
I/jxcore-log( 9054): found test : ./testFindPeers.js
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): found test : ./testReConnect.js
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): found test : ./testSendData.js
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Test app app.js loaded
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Client has connected to the server!
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Start now : testFindPeers.js
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): stop tests now !
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): serverPort is 8876
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): StartBroadcasting started ok
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log( 9054): 
I/jxcore-log( 9054): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): CoordinatorConnector disconnect called
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): The client has disconnected!
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): stop tests now !
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): stop current!
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): testFindPeers stopped
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): StopBroadcasting went ok
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): turning Radios off
I/jxcore-log( 9054): 
I/jxcore-log( 9054): Turning radios to false
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): toggleBluetooth - 
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): toggleWiFi
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,I/jxcore-log( 9054): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9054): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(14369): Initializing JXcore engine
W/jxcore-log(14369): JXcore engine is ready
,W/jxcore-log(14369): Starting JXcore engine
,W/jxcore-log(14369): Platform android
W/jxcore-log(14369): 
W/jxcore-log(14369): Process ARCH arm
W/jxcore-log(14369): 
,I/jxcore-log(14369): JXcore Cordova bridge is ready!
I/jxcore-log(14369): 
,W/jxcore-log(14369): JXcore engine is started
,I/jxcore-log(14369): Turning radios to true
I/jxcore-log(14369): 
,I/jxcore-log(14369): toggleBluetooth - 
I/jxcore-log(14369): 
,I/jxcore-log(14369): toggleWiFi
I/jxcore-log(14369): 
,I/jxcore-log(14369): my name is : DEV4792
I/jxcore-log(14369): 
I/jxcore-log(14369): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(14369): 
,I/jxcore-log(14369): attempting to connect to test coordinator
I/jxcore-log(14369): 
I/jxcore-log(14369): check test folder
I/jxcore-log(14369): 
I/jxcore-log(14369): found test : ./testFindPeers.js
I/jxcore-log(14369): 
,I/jxcore-log(14369): found test : ./testReConnect.js
I/jxcore-log(14369): 
,I/jxcore-log(14369): found test : ./testSendData.js
I/jxcore-log(14369): 
,I/jxcore-log(14369): Test app app.js loaded
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(14369): 
,I/jxcore-log(14369): Client has connected to the server!,
I/jxcore-log(14369): 
,I/jxcore-log(14369): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(14369): 
I/jxcore-log(14369): Start now : testFindPeers.js
I/jxcore-log(14369): 
I/jxcore-log(14369): stop tests now !
I/jxcore-log(14369): 
I/jxcore-log(14369): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(14369): 
I/jxcore-log(14369): serverPort is 8876
I/jxcore-log(14369): 
I/jxcore-log(14369): StartBroadcasting started ok
I/jxcore-log(14369): 
,I/jxcore-log(14369): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log(14369): 
I/jxcore-log(14369): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(14369): 
,I/jxcore-log(14369): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log(14369): 
I/jxcore-log(14369): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(14369): 
,I/jxcore-log(14369): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(14369): 
I/jxcore-log(14369): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log(14369): 
I/jxcore-log(14369): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(14369): 
I/jxcore-log(14369): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log(14369): 
I/jxcore-log(14369): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(14369): 
,I/jxcore-log(14369): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(14369): 
,I/jxcore-log(14369): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(14369): 
I/jxcore-log(14369): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(14369): 
,I/jxcore-log(14369): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(14369): 
,I/jxcore-log(14369): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(14369): 
,I/jxcore-log(14369): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(14369): 
,I/jxcore-log(14369): CoordinatorConnector disconnect called
I/jxcore-log(14369): 
,I/jxcore-log(14369): The client has disconnected!
I/jxcore-log(14369): 
I/jxcore-log(14369): stop tests now !
I/jxcore-log(14369): 
I/jxcore-log(14369): stop current!
I/jxcore-log(14369): 
,I/jxcore-log(14369): testFindPeers stopped
I/jxcore-log(14369): 
,I/jxcore-log(14369): StopBroadcasting went ok
I/jxcore-log(14369): 
,I/jxcore-log(14369): turning Radios off
I/jxcore-log(14369): 
,I/jxcore-log(14369): Turning radios to false
I/jxcore-log(14369): 
,I/jxcore-log(14369): toggleBluetooth - 
I/jxcore-log(14369): 
,I/jxcore-log(14369): toggleWiFi
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,I/jxcore-log(14369): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14369): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:null 
child process exited with code null on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:null 
child process exited with code null on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed 
```

Logcat output:
```
motorola-XT1039: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(27690): Initializing JXcore engine
,W/jxcore-log(27690): JXcore engine is ready
,W/jxcore-log(27690): Starting JXcore engine
,W/jxcore-log(27690): Platform android
W/jxcore-log(27690): 
,W/jxcore-log(27690): Process ARCH arm
W/jxcore-log(27690): 
,I/jxcore-log(27690): JXcore Cordova bridge is ready!
I/jxcore-log(27690): 
,W/jxcore-log(27690): JXcore engine is started
,I/jxcore-log(27690): Turning radios to true
I/jxcore-log(27690): 
,I/jxcore-log(27690): toggleBluetooth - 
I/jxcore-log(27690): 
,I/jxcore-log(27690): toggleWiFi
I/jxcore-log(27690): 
,I/jxcore-log(27690): my name is : DEV4442
I/jxcore-log(27690): 
,I/jxcore-log(27690): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(27690): 
,I/jxcore-log(27690): attempting to connect to test coordinator
I/jxcore-log(27690): 
,I/jxcore-log(27690): check test folder
I/jxcore-log(27690): 
,I/jxcore-log(27690): found test : ./testFindPeers.js
I/jxcore-log(27690): 
,I/jxcore-log(27690): found test : ./testReConnect.js
I/jxcore-log(27690): 
,I/jxcore-log(27690): found test : ./testSendData.js
I/jxcore-log(27690): 
,I/jxcore-log(27690): Test app app.js loaded
I/jxcore-log(27690): 
,I/jxcore-log(27690): Client has connected to the server!
I/jxcore-log(27690): 
,I/jxcore-log(27690): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(27690): 
,I/jxcore-log(27690): Start now : testFindPeers.js
I/jxcore-log(27690): 
I/jxcore-log(27690): stop tests now !
I/jxcore-log(27690): 
,I/jxcore-log(27690): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(27690): 
,I/jxcore-log(27690): serverPort is 8876
I/jxcore-log(27690): 
,I/jxcore-log(27690): StartBroadcasting started ok
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV3665","peerIdentifier":"B4:CE:F6:AB:A4:6A","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV714","peerIdentifier":"34:FC:EF:9D:93:0B","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV9958","peerIdentifier":"80:01:84:8A:B3:68","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV6441","peerIdentifier":"10:D3:8A:FB:85:D4","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV5151","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV8510","peerIdentifier":"00:F4:6F:30:E0:6C","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV6348","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV4169","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV9027","peerIdentifier":"E0:DB:10:1F:C9:5E","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV5731","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV7246","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV7041","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true}]
I/jxcore-log(27690): 
I/jxcore-log(27690): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV6513","peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV7384","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV9290","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV6153","peerIdentifier":"50:2E:6C:AC:21:50","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV6349","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV9615","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): peerAvailabilityChanged [{"peerName":"DEV4792","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true}]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(27690): 
,I/jxcore-log(27690): CoordinatorConnector disconnect called
I/jxcore-log(27690): 
,I/jxcore-log(27690): The client has disconnected!
I/jxcore-log(27690): 
I/jxcore-log(27690): stop tests now !
I/jxcore-log(27690): 
,I/jxcore-log(27690): stop current!
I/jxcore-log(27690): 
,I/jxcore-log(27690): testFindPeers stopped
I/jxcore-log(27690): 
,I/jxcore-log(27690): StopBroadcasting went ok
I/jxcore-log(27690): 
,I/jxcore-log(27690): turning Radios off
I/jxcore-log(27690): 
,I/jxcore-log(27690): Turning radios to false
I/jxcore-log(27690): 
,I/jxcore-log(27690): toggleBluetooth - 
I/jxcore-log(27690): 
,I/jxcore-log(27690): toggleWiFi
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,I/jxcore-log(27690): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(27690): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(16141): Initializing JXcore engine
W/jxcore-log(16141): JXcore engine is ready
W/jxcore-log(16141): Starting JXcore engine
W/jxcore-log(16141): Platform android
W/jxcore-log(16141): 
W/jxcore-log(16141): Process ARCH arm
W/jxcore-log(16141): 
,I/jxcore-log(16141): JXcore Cordova bridge is ready!
I/jxcore-log(16141): 
,W/jxcore-log(16141): JXcore engine is started
,I/jxcore-log(16141): Turning radios to true
I/jxcore-log(16141): 
,I/jxcore-log(16141): toggleBluetooth - 
I/jxcore-log(16141): 
,I/jxcore-log(16141): toggleWiFi
I/jxcore-log(16141): 
,I/jxcore-log(16141): my name is : DEV5151
I/jxcore-log(16141): 
,I/jxcore-log(16141): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(16141): 
,I/jxcore-log(16141): attempting to connect to test coordinator
I/jxcore-log(16141): 
,I/jxcore-log(16141): check test folder
I/jxcore-log(16141): 
I/jxcore-log(16141): found test : ./testFindPeers.js
I/jxcore-log(16141): 
,I/jxcore-log(16141): found test : ./testReConnect.js
I/jxcore-log(16141): 
,I/jxcore-log(16141): found test : ./testSendData.js
I/jxcore-log(16141): 
,I/jxcore-log(16141): Test app app.js loaded
I/jxcore-log(16141): 
,I/jxcore-log(16141): Client has connected to the server!
I/jxcore-log(16141): 
,I/jxcore-log(16141): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(16141): 
I/jxcore-log(16141): Start now : testFindPeers.js
I/jxcore-log(16141): 
I/jxcore-log(16141): stop tests now !
I/jxcore-log(16141): 
,I/jxcore-log(16141): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(16141): 
I/jxcore-log(16141): serverPort is 8876
I/jxcore-log(16141): 
,I/jxcore-log(16141): StartBroadcasting started ok
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(16141): 
I/jxcore-log(16141): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log(16141): 
I/jxcore-log(16141): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log(16141): 
I/jxcore-log(16141): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log(16141): 
I/jxcore-log(16141): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log(16141): 
I/jxcore-log(16141): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log(16141): 
I/jxcore-log(16141): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log(16141): 
I/jxcore-log(16141): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(16141): 
,I/jxcore-log(16141): CoordinatorConnector disconnect called
I/jxcore-log(16141): 
I/jxcore-log(16141): The client has disconnected!
I/jxcore-log(16141): 
I/jxcore-log(16141): stop tests now !
I/jxcore-log(16141): 
I/jxcore-log(16141): stop current!
I/jxcore-log(16141): 
I/jxcore-log(16141): testFindPeers stopped
I/jxcore-log(16141): 
,I/jxcore-log(16141): StopBroadcasting went ok
I/jxcore-log(16141): 
,I/jxcore-log(16141): turning Radios off
I/jxcore-log(16141): 
I/jxcore-log(16141): Turning radios to false
I/jxcore-log(16141): 
,I/jxcore-log(16141): toggleBluetooth - 
I/jxcore-log(16141): 
,I/jxcore-log(16141): toggleWiFi
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(16141): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16141): 


samsung-SM-G800F: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 1887): Initializing JXcore engine
,W/jxcore-log( 1887): JXcore engine is ready
,W/jxcore-log( 1887): Starting JXcore engine
,W/jxcore-log( 1887): Platform android
W/jxcore-log( 1887): 
,W/jxcore-log( 1887): Process ARCH arm
W/jxcore-log( 1887): 
,I/jxcore-log( 1887): JXcore Cordova bridge is ready!
I/jxcore-log( 1887): 
,W/jxcore-log( 1887): JXcore engine is started
,I/jxcore-log( 1887): Turning radios to true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): toggleBluetooth - 
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): toggleWiFi
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): my name is : DEV8510
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): attempting to connect to test coordinator
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): check test folder
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): found test : ./testFindPeers.js
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): found test : ./testReConnect.js
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): found test : ./testSendData.js
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Test app app.js loaded
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Client has connected to the server!
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Start now : testFindPeers.js
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): stop tests now !
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): serverPort is 8876
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): StartBroadcasting started ok
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV4442","peerIdentifier":"F4:F1:E1:5C:3B:E2","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV6348","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true}]
I/jxcore-log( 1887): 
I/jxcore-log( 1887): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV9958","peerIdentifier":"80:01:84:8A:B3:68","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV6441","peerIdentifier":"10:D3:8A:FB:85:D4","peerAvailable":true}]
I/jxcore-log( 1887): 
I/jxcore-log( 1887): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV714","peerIdentifier":"34:FC:EF:9D:93:0B","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV5151","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV9027","peerIdentifier":"E0:DB:10:1F:C9:5E","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV6513","peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV7041","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV4792","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true}]
I/jxcore-log( 1887): 
I/jxcore-log( 1887): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV4169","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV7246","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true}]
I/jxcore-log( 1887): 
I/jxcore-log( 1887): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV7384","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true}]
I/jxcore-log( 1887): 
I/jxcore-log( 1887): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV5731","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true}]
I/jxcore-log( 1887): 
I/jxcore-log( 1887): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV9290","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true}]
I/jxcore-log( 1887): 
I/jxcore-log( 1887): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV6349","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV6153","peerIdentifier":"50:2E:6C:AC:21:50","peerAvailable":true}]
I/jxcore-log( 1887): 
I/jxcore-log( 1887): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV9615","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV1994","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true}]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): peerAvailabilityChanged [{"peerName":"DEV3665","peerIdentifier":"B4:CE:F6:AB:A4:6A","peerAvailable":true}]
I/jxcore-log( 1887): 
I/jxcore-log( 1887): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): CoordinatorConnector disconnect called
I/jxcore-log( 1887): 
I/jxcore-log( 1887): The client has disconnected!
I/jxcore-log( 1887): 
I/jxcore-log( 1887): stop tests now !
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): stop current!
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): testFindPeers stopped
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): StopBroadcasting went ok
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): turning Radios off
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Turning radios to false
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): toggleBluetooth - 
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): toggleWiFi
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,I/jxcore-log( 1887): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 1887): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:null 
child process exited with code null on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed 
```

Logcat output:
```
motorola-XT1072: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 2985): Initializing JXcore engine
,W/jxcore-log( 2985): JXcore engine is ready
,W/jxcore-log( 2985): Starting JXcore engine
,W/jxcore-log( 2985): Platform android
W/jxcore-log( 2985): 
W/jxcore-log( 2985): Process ARCH arm
W/jxcore-log( 2985): 
,I/jxcore-log( 2985): JXcore Cordova bridge is ready!
I/jxcore-log( 2985): 
W/jxcore-log( 2985): JXcore engine is started
,I/jxcore-log( 2985): Turning radios to true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): toggleBluetooth - 
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): toggleWiFi
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): my name is : DEV7384
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): attempting to connect to test coordinator
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): check test folder
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): found test : ./testFindPeers.js
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): found test : ./testReConnect.js
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): found test : ./testSendData.js
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Test app app.js loaded
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Client has connected to the server!
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Start now : testFindPeers.js
I/jxcore-log( 2985): 
I/jxcore-log( 2985): stop tests now !
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): serverPort is 8876
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): StartBroadcasting started ok
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV1994","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): CoordinatorConnector disconnect called
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): The client has disconnected!
I/jxcore-log( 2985): 
I/jxcore-log( 2985): stop tests now !
I/jxcore-log( 2985): 
I/jxcore-log( 2985): stop current!
I/jxcore-log( 2985): 
I/jxcore-log( 2985): testFindPeers stopped
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): StopBroadcasting went ok
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): turning Radios off
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Turning radios to false
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): toggleBluetooth - 
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): toggleWiFi
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,I/jxcore-log( 2985): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2985): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(  982): Initializing JXcore engine
W/jxcore-log(  982): JXcore engine is ready
W/jxcore-log(  982): Starting JXcore engine
,W/jxcore-log(  982): Platform android
W/jxcore-log(  982): 
W/jxcore-log(  982): Process ARCH arm
W/jxcore-log(  982): 
,I/jxcore-log(  982): JXcore Cordova bridge is ready!
I/jxcore-log(  982): 
W/jxcore-log(  982): JXcore engine is started
,I/jxcore-log(  982): Turning radios to true
I/jxcore-log(  982): 
,I/jxcore-log(  982): toggleBluetooth - 
I/jxcore-log(  982): 
,I/jxcore-log(  982): toggleWiFi
I/jxcore-log(  982): 
,I/jxcore-log(  982): my name is : DEV7246
I/jxcore-log(  982): 
I/jxcore-log(  982): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(  982): 
,I/jxcore-log(  982): attempting to connect to test coordinator
I/jxcore-log(  982): 
,I/jxcore-log(  982): check test folder
I/jxcore-log(  982): 
,I/jxcore-log(  982): found test : ./testFindPeers.js
I/jxcore-log(  982): 
,I/jxcore-log(  982): found test : ./testReConnect.js
I/jxcore-log(  982): 
,I/jxcore-log(  982): found test : ./testSendData.js
I/jxcore-log(  982): 
,I/jxcore-log(  982): Test app app.js loaded
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): LogCallback not set !!!!
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Client has connected to the server!
I/jxcore-log(  982): 
,I/jxcore-log(  982): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21},
I/jxcore-log(  982): 
,I/jxcore-log(  982): Start now : testFindPeers.js
I/jxcore-log(  982): 
,I/jxcore-log(  982): stop tests now !
I/jxcore-log(  982): 
,I/jxcore-log(  982): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(  982): 
,I/jxcore-log(  982): serverPort is 8876
I/jxcore-log(  982): 
,I/jxcore-log(  982): StartBroadcasting started ok
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(  982): 
,I/jxcore-log(  982): CoordinatorConnector disconnect called
I/jxcore-log(  982): 
,I/jxcore-log(  982): The client has disconnected!
I/jxcore-log(  982): 
I/jxcore-log(  982): stop tests now !
I/jxcore-log(  982): 
,I/jxcore-log(  982): stop current!
I/jxcore-log(  982): 
,I/jxcore-log(  982): testFindPeers stopped
I/jxcore-log(  982): 
,I/jxcore-log(  982): StopBroadcasting went ok
I/jxcore-log(  982): 
,I/jxcore-log(  982): turning Radios off
I/jxcore-log(  982): 
,I/jxcore-log(  982): Turning radios to false
I/jxcore-log(  982): 
,I/jxcore-log(  982): toggleBluetooth - 
I/jxcore-log(  982): 
,I/jxcore-log(  982): toggleWiFi
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(  982): ,
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(  982): ,
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,I/jxcore-log(  982): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(  982): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(26761): Initializing JXcore engine
W/jxcore-log(26761): JXcore engine is ready
W/jxcore-log(26761): Starting JXcore engine
W/jxcore-log(26761): Platform android
W/jxcore-log(26761): 
W/jxcore-log(26761): Process ARCH arm
W/jxcore-log(26761): 
,I/jxcore-log(26761): JXcore Cordova bridge is ready!,
I/jxcore-log(26761): 
W/jxcore-log(26761): JXcore engine is started
,I/jxcore-log(26761): Turning radios to true
I/jxcore-log(26761): 
,I/jxcore-log(26761): toggleBluetooth - 
I/jxcore-log(26761): 
,I/jxcore-log(26761): toggleWiFi
I/jxcore-log(26761): 
,I/jxcore-log(26761): my name is : DEV6349,
I/jxcore-log(26761): 
I/jxcore-log(26761): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(26761): 
,I/jxcore-log(26761): attempting to connect to test coordinator,
I/jxcore-log(26761): 
,I/jxcore-log(26761): check test folder
I/jxcore-log(26761): 
,I/jxcore-log(26761): found test : ./testFindPeers.js,
I/jxcore-log(26761): 
,I/jxcore-log(26761): found test : ./testReConnect.js
I/jxcore-log(26761): 
,I/jxcore-log(26761): found test : ./testSendData.js
I/jxcore-log(26761): 
,I/jxcore-log(26761): Test app app.js loaded,
I/jxcore-log(26761): 
,I/jxcore-log(26761): Client has connected to the server!
I/jxcore-log(26761): 
,I/jxcore-log(26761): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(26761): 
,I/jxcore-log(26761): Start now : testFindPeers.js
I/jxcore-log(26761): 
I/jxcore-log(26761): stop tests now !
I/jxcore-log(26761): 
,I/jxcore-log(26761): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(26761): 
,I/jxcore-log(26761): serverPort is 8876
I/jxcore-log(26761): 
,I/jxcore-log(26761): StartBroadcasting started ok
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}],
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : B0:C5:59:3F:75:69, peerAvailable: true,
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV1994","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}],
I/jxcore-log(26761): 
I/jxcore-log(26761): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(26761): 
,I/jxcore-log(26761): CoordinatorConnector disconnect called
I/jxcore-log(26761): 
,I/jxcore-log(26761): The client has disconnected!
I/jxcore-log(26761): 
,I/jxcore-log(26761): stop tests now !
I/jxcore-log(26761): 
I/jxcore-log(26761): stop current!
I/jxcore-log(26761): 
I/jxcore-log(26761): testFindPeers stopped
I/jxcore-log(26761): 
,I/jxcore-log(26761): StopBroadcasting went ok
I/jxcore-log(26761): 
,I/jxcore-log(26761): turning Radios off
I/jxcore-log(26761): 
,I/jxcore-log(26761): Turning radios to false
I/jxcore-log(26761): 
,I/jxcore-log(26761): toggleBluetooth - 
I/jxcore-log(26761): 
,I/jxcore-log(26761): toggleWiFi
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,I/jxcore-log(26761): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26761): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-G900F: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(21252): Initializing JXcore engine
W/jxcore-log(21252): JXcore engine is ready
,W/jxcore-log(21252): Starting JXcore engine
,W/jxcore-log(21252): Platform android
W/jxcore-log(21252): 
W/jxcore-log(21252): Process ARCH arm
W/jxcore-log(21252): 
,I/jxcore-log(21252): JXcore Cordova bridge is ready!
I/jxcore-log(21252): 
W/jxcore-log(21252): JXcore engine is started
I/jxcore-log(21252): Turning radios to true
I/jxcore-log(21252): 
I/jxcore-log(21252): toggleBluetooth - 
I/jxcore-log(21252): 
I/jxcore-log(21252): toggleWiFi
I/jxcore-log(21252): 
,I/jxcore-log(21252): my name is : DEV9290
I/jxcore-log(21252): 
I/jxcore-log(21252): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(21252): 
,I/jxcore-log(21252): attempting to connect to test coordinator
I/jxcore-log(21252): 
,I/jxcore-log(21252): check test folder
I/jxcore-log(21252): 
,I/jxcore-log(21252): found test : ./testFindPeers.js
I/jxcore-log(21252): 
,I/jxcore-log(21252): found test : ./testReConnect.js
I/jxcore-log(21252): 
,I/jxcore-log(21252): found test : ./testSendData.js
I/jxcore-log(21252): 
,I/jxcore-log(21252): Test app app.js loaded
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): LogCallback not set !!!!
I/jxcore-log(21252): 
,I/jxcore-log(21252): Client has connected to the server!
I/jxcore-log(21252): 
,I/jxcore-log(21252): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21},
I/jxcore-log(21252): ,
,I/jxcore-log(21252): Start now : testFindPeers.js
I/jxcore-log(21252): 
,I/jxcore-log(21252): stop tests now !
I/jxcore-log(21252): 
,I/jxcore-log(21252): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(21252): 
,I/jxcore-log(21252): serverPort is 8876
I/jxcore-log(21252): 
,I/jxcore-log(21252): StartBroadcasting started ok
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}],
I/jxcore-log(21252): ,
,I/jxcore-log(21252): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV1994","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(21252): 
,I/jxcore-log(21252): CoordinatorConnector disconnect called
I/jxcore-log(21252): 
,I/jxcore-log(21252): The client has disconnected!
I/jxcore-log(21252): 
,I/jxcore-log(21252): stop tests now !
I/jxcore-log(21252): 
,I/jxcore-log(21252): stop current!
I/jxcore-log(21252): 
,I/jxcore-log(21252): testFindPeers stopped
I/jxcore-log(21252): 
,I/jxcore-log(21252): StopBroadcasting went ok
I/jxcore-log(21252): 
,I/jxcore-log(21252): turning Radios off
I/jxcore-log(21252): 
,I/jxcore-log(21252): Turning radios to false
I/jxcore-log(21252): 
,I/jxcore-log(21252): toggleBluetooth - 
I/jxcore-log(21252): 
,I/jxcore-log(21252): toggleWiFi
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(21252): ,
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 
I/jxcore-log(21252): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21252): 


```

####Node name: thali05
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device SH47FWM00508 app:com.test.thalitest code:null 
child process exited with code null on device SH47FWM00508 
Error! Unexpected exit on device 1d6a772d app:com.test.thalitest code:null 
child process exited with code null on device 1d6a772d 
Error! Unexpected exit on device ZX1G429CRK app:com.test.thalitest code:null 
child process exited with code null on device ZX1G429CRK 
Android task is completed 
```

Logcat output:
```
HTC-HTC One_M8: 
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(32042): Initializing JXcore engine,
W/jxcore-log(32042): JXcore engine is ready
,W/jxcore-log(32042): Starting JXcore engine,
,W/jxcore-log(32042): Platform android,
W/jxcore-log(32042): 
W/jxcore-log(32042): Process ARCH arm
W/jxcore-log(32042): 
,I/jxcore-log(32042): JXcore Cordova bridge is ready!,
I/jxcore-log(32042): 
W/jxcore-log(32042): JXcore engine is started
,I/jxcore-log(32042): Turning radios to true
I/jxcore-log(32042): 
,I/jxcore-log(32042): toggleBluetooth - ,
I/jxcore-log(32042): 
,I/jxcore-log(32042): toggleWiFi,
,I/jxcore-log(32042): 
,I/jxcore-log(32042): my name is : DEV6153
I/jxcore-log(32042): 
I/jxcore-log(32042): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(32042): 
,I/jxcore-log(32042): attempting to connect to test coordinator
I/jxcore-log(32042): 
,I/jxcore-log(32042): check test folder
I/jxcore-log(32042): 
,I/jxcore-log(32042): found test : ./testFindPeers.js
I/jxcore-log(32042): 
,I/jxcore-log(32042): found test : ./testReConnect.js
I/jxcore-log(32042): 
,I/jxcore-log(32042): found test : ./testSendData.js
I/jxcore-log(32042): 
,I/jxcore-log(32042): Test app app.js loaded
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Client has connected to the server!,
I/jxcore-log(32042): 
,I/jxcore-log(32042): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21},
,I/jxcore-log(32042): 
I/jxcore-log(32042): Start now : testFindPeers.js
I/jxcore-log(32042): 
I/jxcore-log(32042): stop tests now !
I/jxcore-log(32042): 
I/jxcore-log(32042): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(32042): ,
I/jxcore-log(32042): serverPort is 8876
I/jxcore-log(32042): 
,I/jxcore-log(32042): StartBroadcasting started ok,
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}],
I/jxcore-log(32042): ,
I/jxcore-log(32042): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Found peer : 08:EC:A9:50:75:41, peerAvailable: true,
,I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(32042): ,
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}],
I/jxcore-log(32042): 
I/jxcore-log(32042): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(32042): 
,I/jxcore-log(32042): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true,
I/jxcore-log(32042): 
,I/jxcore-log(32042): CoordinatorConnector disconnect called,
,I/jxcore-log(32042): 
I/jxcore-log(32042): The client has disconnected!
I/jxcore-log(32042): 
I/jxcore-log(32042): stop tests now !
I/jxcore-log(32042): 
I/jxcore-log(32042): stop current!,
I/jxcore-log(32042): 
I/jxcore-log(32042): testFindPeers stopped
I/jxcore-log(32042): 
,I/jxcore-log(32042): StopBroadcasting went ok,
I/jxcore-log(32042): 
I/jxcore-log(32042): turning Radios off
I/jxcore-log(32042): 
I/jxcore-log(32042): Turning radios to false
I/jxcore-log(32042): 
,I/jxcore-log(32042): toggleBluetooth - ,
I/jxcore-log(32042): 
,I/jxcore-log(32042): toggleWiFi,
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): ,
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,I/jxcore-log(32042): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(32042): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-N9005: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log( 3601): Initializing JXcore engine,
W/jxcore-log( 3601): JXcore engine is ready
,W/jxcore-log( 3601): Starting JXcore engine
,W/jxcore-log( 3601): Platform android
W/jxcore-log( 3601): 
W/jxcore-log( 3601): Process ARCH arm
W/jxcore-log( 3601): 
,I/jxcore-log( 3601): JXcore Cordova bridge is ready!
I/jxcore-log( 3601): 
,W/jxcore-log( 3601): JXcore engine is started
,I/jxcore-log( 3601): Turning radios to true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): toggleBluetooth - 
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): toggleWiFi
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): my name is : DEV9027
I/jxcore-log( 3601): 
I/jxcore-log( 3601): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): attempting to connect to test coordinator
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): check test folder
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): found test : ./testFindPeers.js
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): found test : ./testReConnect.js
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): found test : ./testSendData.js
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Test app app.js loaded
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): LogCallback not set !!!!
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Client has connected to the server!
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21},
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Start now : testFindPeers.js
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): stop tests now !
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): serverPort is 8876
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): StartBroadcasting started ok
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
,I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV1994","peerAvailable":true}]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): CoordinatorConnector disconnect called
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): The client has disconnected!
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): stop tests now !
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): stop current!
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): testFindPeers stopped
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): StopBroadcasting went ok
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): turning Radios off
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Turning radios to false
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): toggleBluetooth - 
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): toggleWiFi
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 3601): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3601): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(16643): Initializing JXcore engine
,W/jxcore-log(16643): JXcore engine is ready
,W/jxcore-log(16643): Starting JXcore engine
,W/jxcore-log(16643): Platform android
W/jxcore-log(16643): 
,W/jxcore-log(16643): Process ARCH arm
W/jxcore-log(16643): 
,I/jxcore-log(16643): JXcore Cordova bridge is ready!
I/jxcore-log(16643): 
W/jxcore-log(16643): JXcore engine is started
,I/jxcore-log(16643): Turning radios to true
I/jxcore-log(16643): 
,I/jxcore-log(16643): toggleBluetooth - 
I/jxcore-log(16643): 
,I/jxcore-log(16643): toggleWiFi
I/jxcore-log(16643): 
,I/jxcore-log(16643): my name is : DEV6513
I/jxcore-log(16643): 
I/jxcore-log(16643): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(16643): 
,I/jxcore-log(16643): attempting to connect to test coordinator
I/jxcore-log(16643): 
I/jxcore-log(16643): check test folder
I/jxcore-log(16643): 
I/jxcore-log(16643): found test : ./testFindPeers.js
I/jxcore-log(16643): 
,I/jxcore-log(16643): found test : ./testReConnect.js
I/jxcore-log(16643): 
,I/jxcore-log(16643): found test : ./testSendData.js
I/jxcore-log(16643): 
,I/jxcore-log(16643): Test app app.js loaded
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Client has connected to the server!
I/jxcore-log(16643): 
,I/jxcore-log(16643): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(16643): 
I/jxcore-log(16643): Start now : testFindPeers.js
I/jxcore-log(16643): 
,I/jxcore-log(16643): stop tests now !
I/jxcore-log(16643): 
I/jxcore-log(16643): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(16643): 
,I/jxcore-log(16643): serverPort is 8876
I/jxcore-log(16643): 
,I/jxcore-log(16643): StartBroadcasting started ok
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}],
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
,I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log(16643): 
I/jxcore-log(16643): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(16643): 
I/jxcore-log(16643): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log(16643): 
I/jxcore-log(16643): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}],
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log(16643): 
I/jxcore-log(16643): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}],
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log(16643): 
I/jxcore-log(16643): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV1994","peerAvailable":true}]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(16643): 
,I/jxcore-log(16643): CoordinatorConnector disconnect called
I/jxcore-log(16643): 
I/jxcore-log(16643): The client has disconnected!
I/jxcore-log(16643): 
I/jxcore-log(16643): stop tests now !
I/jxcore-log(16643): 
I/jxcore-log(16643): stop current!
I/jxcore-log(16643): 
I/jxcore-log(16643): testFindPeers stopped
I/jxcore-log(16643): 
,I/jxcore-log(16643): StopBroadcasting went ok
I/jxcore-log(16643): 
,I/jxcore-log(16643): turning Radios off
I/jxcore-log(16643): 
I/jxcore-log(16643): Turning radios to false
I/jxcore-log(16643): 
,I/jxcore-log(16643): toggleBluetooth - 
I/jxcore-log(16643): 
,I/jxcore-log(16643): toggleWiFi
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): ,
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(16643): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(16643): 


```

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:null 
child process exited with code null on device 022678fb504e29b0 
Android task is completed 
```

Logcat output:
```
HTC-HTC One M8s: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(29851): Initializing JXcore engine
,W/jxcore-log(29851): JXcore engine is ready
,W/jxcore-log(29851): Starting JXcore engine,
,W/jxcore-log(29851): Platform android
W/jxcore-log(29851): 
,W/jxcore-log(29851): Process ARCH arm
W/jxcore-log(29851): 
,I/jxcore-log(29851): JXcore Cordova bridge is ready!,
I/jxcore-log(29851): 
W/jxcore-log(29851): JXcore engine is started
,I/jxcore-log(29851): Turning radios to true
I/jxcore-log(29851): 
,I/jxcore-log(29851): toggleBluetooth - ,
I/jxcore-log(29851): 
,I/jxcore-log(29851): toggleWiFi,
I/jxcore-log(29851): 
,I/jxcore-log(29851): my name is : DEV3582,
I/jxcore-log(29851): 
I/jxcore-log(29851): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(29851): 
,I/jxcore-log(29851): attempting to connect to test coordinator,
I/jxcore-log(29851): 
I/jxcore-log(29851): check test folder
I/jxcore-log(29851): 
,I/jxcore-log(29851): found test : ./testFindPeers.js
I/jxcore-log(29851): 
,I/jxcore-log(29851): found test : ./testReConnect.js,
I/jxcore-log(29851): 
,I/jxcore-log(29851): found test : ./testSendData.js,
I/jxcore-log(29851): 
,I/jxcore-log(29851): Test app app.js loaded,
I/jxcore-log(29851): 
I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
I/jxcore-log(29851): LogCallback not set !!!!
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): ,
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): ,
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,I/jxcore-log(29851): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29851): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(30885): Initializing JXcore engine
W/jxcore-log(30885): JXcore engine is ready
,W/jxcore-log(30885): Starting JXcore engine
,W/jxcore-log(30885): Platform android
W/jxcore-log(30885): 
W/jxcore-log(30885): Process ARCH arm
W/jxcore-log(30885): 
,I/jxcore-log(30885): JXcore Cordova bridge is ready!
I/jxcore-log(30885): 
,W/jxcore-log(30885): JXcore engine is started
,I/jxcore-log(30885): Turning radios to true
I/jxcore-log(30885): 
,I/jxcore-log(30885): toggleBluetooth - 
I/jxcore-log(30885): 
,I/jxcore-log(30885): toggleWiFi
I/jxcore-log(30885): 
,I/jxcore-log(30885): my name is : DEV7041
I/jxcore-log(30885): 
I/jxcore-log(30885): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(30885): 
,I/jxcore-log(30885): attempting to connect to test coordinator
I/jxcore-log(30885): 
,I/jxcore-log(30885): check test folder
I/jxcore-log(30885): 
,I/jxcore-log(30885): found test : ./testFindPeers.js
I/jxcore-log(30885): 
,I/jxcore-log(30885): found test : ./testReConnect.js
I/jxcore-log(30885): 
,I/jxcore-log(30885): found test : ./testSendData.js,
I/jxcore-log(30885): 
,I/jxcore-log(30885): Test app app.js loaded,
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Client has connected to the server!
I/jxcore-log(30885): 
,I/jxcore-log(30885): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(30885): 
,I/jxcore-log(30885): Start now : testFindPeers.js
I/jxcore-log(30885): 
,I/jxcore-log(30885): stop tests now !
I/jxcore-log(30885): 
,I/jxcore-log(30885): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"},
I/jxcore-log(30885): 
I/jxcore-log(30885): serverPort is 8876,
I/jxcore-log(30885): 
,I/jxcore-log(30885): StartBroadcasting started ok
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}],
I/jxcore-log(30885): 
I/jxcore-log(30885): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}],
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}],
I/jxcore-log(30885): 
I/jxcore-log(30885): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV1994","peerAvailable":true}]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(30885): 
,I/jxcore-log(30885): CoordinatorConnector disconnect called
I/jxcore-log(30885): 
,I/jxcore-log(30885): The client has disconnected!
I/jxcore-log(30885): 
,I/jxcore-log(30885): stop tests now !
I/jxcore-log(30885): 
I/jxcore-log(30885): stop current!
I/jxcore-log(30885): 
,I/jxcore-log(30885): testFindPeers stopped
I/jxcore-log(30885): 
,I/jxcore-log(30885): StopBroadcasting went ok
I/jxcore-log(30885): 
,I/jxcore-log(30885): turning Radios off
I/jxcore-log(30885): 
,I/jxcore-log(30885): Turning radios to false
I/jxcore-log(30885): 
,I/jxcore-log(30885): toggleBluetooth - 
I/jxcore-log(30885): 
,I/jxcore-log(30885): toggleWiFi
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,I/jxcore-log(30885): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(30885): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 8479): Initializing JXcore engine
,W/jxcore-log( 8479): JXcore engine is ready
,W/jxcore-log( 8479): Starting JXcore engine
,W/jxcore-log( 8479): Platform android
W/jxcore-log( 8479): 
,W/jxcore-log( 8479): Process ARCH arm
W/jxcore-log( 8479): 
,I/jxcore-log( 8479): JXcore Cordova bridge is ready!
I/jxcore-log( 8479): 
,W/jxcore-log( 8479): JXcore engine is started
,I/jxcore-log( 8479): Turning radios to true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): toggleBluetooth - 
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): toggleWiFi
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): my name is : DEV714
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): attempting to connect to test coordinator
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): check test folder
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): found test : ./testFindPeers.js
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): found test : ./testReConnect.js
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): found test : ./testSendData.js
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Test app app.js loaded
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Client has connected to the server!
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Start now : testFindPeers.js
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): stop tests now !
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): serverPort is 8876
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): StartBroadcasting started ok
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV4442","peerIdentifier":"F4:F1:E1:5C:3B:E2","peerAvailable":true}]
I/jxcore-log( 8479): 
I/jxcore-log( 8479): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV9958","peerIdentifier":"80:01:84:8A:B3:68","peerAvailable":true}]
I/jxcore-log( 8479): 
I/jxcore-log( 8479): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV5731","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV9027","peerIdentifier":"E0:DB:10:1F:C9:5E","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV8510","peerIdentifier":"00:F4:6F:30:E0:6C","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV3665","peerIdentifier":"B4:CE:F6:AB:A4:6A","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV5151","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV6441","peerIdentifier":"10:D3:8A:FB:85:D4","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV4169","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV7246","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV6348","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV6513","peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV4792","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV9615","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV9290","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV7041","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV6349","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV7384","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV6153","peerIdentifier":"50:2E:6C:AC:21:50","peerAvailable":true}]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): peerAvailabilityChanged [{"peerName":"DEV1994","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true}]
I/jxcore-log( 8479): 
I/jxcore-log( 8479): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): CoordinatorConnector disconnect called
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): The client has disconnected!
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): stop tests now !
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): stop current!
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): testFindPeers stopped
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): StopBroadcasting went ok
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): turning Radios off
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Turning radios to false
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): toggleBluetooth - 
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): toggleWiFi
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,I/jxcore-log( 8479): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 8479): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Android task is completed 
```

Logcat output:
```
samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(13528): Initializing JXcore engine
,W/jxcore-log(13528): JXcore engine is ready
,W/jxcore-log(13528): Starting JXcore engine
,W/jxcore-log(13528): Platform android
W/jxcore-log(13528): 
W/jxcore-log(13528): Process ARCH arm
W/jxcore-log(13528): 
,I/jxcore-log(13528): JXcore Cordova bridge is ready!
I/jxcore-log(13528): 
,W/jxcore-log(13528): JXcore engine is started
,I/jxcore-log(13528): Turning radios to true
I/jxcore-log(13528): 
,I/jxcore-log(13528): toggleBluetooth - 
I/jxcore-log(13528): 
,I/jxcore-log(13528): toggleWiFi,
I/jxcore-log(13528): 
,I/jxcore-log(13528): my name is : DEV5731,
I/jxcore-log(13528): 
I/jxcore-log(13528): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(13528): 
,I/jxcore-log(13528): attempting to connect to test coordinator,
I/jxcore-log(13528): 
I/jxcore-log(13528): check test folder,
I/jxcore-log(13528): 
,I/jxcore-log(13528): found test : ./testFindPeers.js,
I/jxcore-log(13528): 
,I/jxcore-log(13528): found test : ./testReConnect.js,
I/jxcore-log(13528): 
,I/jxcore-log(13528): found test : ./testSendData.js,
I/jxcore-log(13528): 
,I/jxcore-log(13528): Test app app.js loaded,
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Client has connected to the server!
I/jxcore-log(13528): 
,I/jxcore-log(13528): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(13528): 
,I/jxcore-log(13528): Start now : testFindPeers.js
I/jxcore-log(13528): 
I/jxcore-log(13528): stop tests now !
I/jxcore-log(13528): 
,I/jxcore-log(13528): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(13528): 
,I/jxcore-log(13528): serverPort is 8876
I/jxcore-log(13528): 
,I/jxcore-log(13528): StartBroadcasting started ok
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}],
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}],
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV1994","peerAvailable":true}]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(13528): 
,I/jxcore-log(13528): CoordinatorConnector disconnect called
I/jxcore-log(13528): 
,I/jxcore-log(13528): The client has disconnected!
I/jxcore-log(13528): 
I/jxcore-log(13528): stop tests now !
I/jxcore-log(13528): 
,I/jxcore-log(13528): stop current!
I/jxcore-log(13528): 
I/jxcore-log(13528): testFindPeers stopped
I/jxcore-log(13528): 
,I/jxcore-log(13528): StopBroadcasting went ok
I/jxcore-log(13528): 
,I/jxcore-log(13528): turning Radios off
I/jxcore-log(13528): 
I/jxcore-log(13528): Turning radios to false
I/jxcore-log(13528): 
,I/jxcore-log(13528): toggleBluetooth - 
I/jxcore-log(13528): 
,I/jxcore-log(13528): toggleWiFi
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(13528): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(13528): 


samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log( 6965): Initializing JXcore engine,
W/jxcore-log( 6965): JXcore engine is ready,
W/jxcore-log( 6965): Starting JXcore engine
,W/jxcore-log( 6965): Platform android
W/jxcore-log( 6965): 
,W/jxcore-log( 6965): Process ARCH arm
W/jxcore-log( 6965): 
,I/jxcore-log( 6965): JXcore Cordova bridge is ready!
I/jxcore-log( 6965): 
W/jxcore-log( 6965): JXcore engine is started
,I/jxcore-log( 6965): Turning radios to true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): toggleBluetooth - 
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): toggleWiFi
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): my name is : DEV9615
I/jxcore-log( 6965): 
I/jxcore-log( 6965): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): attempting to connect to test coordinator
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): check test folder
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): found test : ./testFindPeers.js
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): found test : ./testReConnect.js
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): found test : ./testSendData.js
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Test app app.js loaded
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): LogCallback not set !!!!
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Client has connected to the server!
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21},
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Start now : testFindPeers.js
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): stop tests now !
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): serverPort is 8876
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): StartBroadcasting started ok
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV1994","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV4169","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): CoordinatorConnector disconnect called
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): The client has disconnected!
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): stop tests now !
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): stop current!
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): testFindPeers stopped
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): StopBroadcasting went ok
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): turning Radios off
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Turning radios to false
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): toggleBluetooth - 
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): toggleWiFi
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 6965): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 6965): 


```

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Android task is completed 
```

Logcat output:
```
samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(21652): Initializing JXcore engine
W/jxcore-log(21652): JXcore engine is ready
,W/jxcore-log(21652): Starting JXcore engine
,W/jxcore-log(21652): Platform android
W/jxcore-log(21652): 
W/jxcore-log(21652): Process ARCH arm
W/jxcore-log(21652): 
,I/jxcore-log(21652): JXcore Cordova bridge is ready!,
I/jxcore-log(21652): 
W/jxcore-log(21652): JXcore engine is started
,I/jxcore-log(21652): Turning radios to true
I/jxcore-log(21652): 
,I/jxcore-log(21652): toggleBluetooth - 
I/jxcore-log(21652): 
,I/jxcore-log(21652): toggleWiFi
I/jxcore-log(21652): 
,I/jxcore-log(21652): my name is : DEV4169,
I/jxcore-log(21652): 
I/jxcore-log(21652): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(21652): 
,I/jxcore-log(21652): attempting to connect to test coordinator,
I/jxcore-log(21652): 
I/jxcore-log(21652): check test folder
I/jxcore-log(21652): 
,I/jxcore-log(21652): found test : ./testFindPeers.js,
I/jxcore-log(21652): 
,I/jxcore-log(21652): found test : ./testReConnect.js,
I/jxcore-log(21652): 
,I/jxcore-log(21652): found test : ./testSendData.js,
I/jxcore-log(21652): 
,I/jxcore-log(21652): Test app app.js loaded,
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): LogCallback not set !!!!
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Client has connected to the server!
I/jxcore-log(21652): 
,I/jxcore-log(21652): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log(21652): 
,I/jxcore-log(21652): Start now : testFindPeers.js
I/jxcore-log(21652): 
,I/jxcore-log(21652): stop tests now !
I/jxcore-log(21652): 
,I/jxcore-log(21652): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(21652): 
,I/jxcore-log(21652): serverPort is 8876
I/jxcore-log(21652): 
,I/jxcore-log(21652): StartBroadcasting started ok
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV6153","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV6441","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV9958","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV3665","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV7041","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7246","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV7384","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV8510","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"58:3F:54:73:64:C0","peerName":"DEV5151","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV714","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV4442","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV6348","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV4792","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5731","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV1994","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV9290","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV6349","peerAvailable":true}],
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true,
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV9615","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV9027","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV6513","peerAvailable":true}]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(21652): 
,I/jxcore-log(21652): CoordinatorConnector disconnect called
I/jxcore-log(21652): 
,I/jxcore-log(21652): The client has disconnected!
I/jxcore-log(21652): 
,I/jxcore-log(21652): stop tests now !
I/jxcore-log(21652): 
I/jxcore-log(21652): stop current!
I/jxcore-log(21652): 
,I/jxcore-log(21652): testFindPeers stopped
I/jxcore-log(21652): 
,I/jxcore-log(21652): StopBroadcasting went ok
I/jxcore-log(21652): 
,I/jxcore-log(21652): turning Radios off
I/jxcore-log(21652): 
,I/jxcore-log(21652): Turning radios to false
I/jxcore-log(21652): 
,I/jxcore-log(21652): toggleBluetooth - 
I/jxcore-log(21652): 
,I/jxcore-log(21652): toggleWiFi
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,I/jxcore-log(21652): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(21652): 
,TIME-OUT KILL (timeout was 1800000ms)

HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log( 7739): Initializing JXcore engine
,W/jxcore-log( 7739): JXcore engine is ready
,W/jxcore-log( 7739): Starting JXcore engine
,W/jxcore-log( 7739): Platform android
W/jxcore-log( 7739): 
,W/jxcore-log( 7739): Process ARCH arm
W/jxcore-log( 7739): 
,I/jxcore-log( 7739): JXcore Cordova bridge is ready!
I/jxcore-log( 7739): 
W/jxcore-log( 7739): JXcore engine is started
,I/jxcore-log( 7739): Turning radios to true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): toggleBluetooth - 
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): toggleWiFi
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): my name is : DEV9958
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): attempting to connect to test coordinator
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): check test folder
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): found test : ./testFindPeers.js
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): found test : ./testReConnect.js
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): found test : ./testSendData.js
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Test app app.js loaded
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): LogCallback not set !!!!
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Client has connected to the server!
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Start now : testFindPeers.js
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): stop tests now !
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): serverPort is 8876
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): StartBroadcasting started ok
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV714","peerIdentifier":"34:FC:EF:9D:93:0B","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV8510","peerIdentifier":"00:F4:6F:30:E0:6C","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV4442","peerIdentifier":"F4:F1:E1:5C:3B:E2","peerAvailable":true}]
I/jxcore-log( 7739): 
I/jxcore-log( 7739): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV3665","peerIdentifier":"B4:CE:F6:AB:A4:6A","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV7246","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true}]
I/jxcore-log( 7739): 
I/jxcore-log( 7739): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV6348","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true}]
I/jxcore-log( 7739): 
I/jxcore-log( 7739): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV6441","peerIdentifier":"10:D3:8A:FB:85:D4","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV7041","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV9027","peerIdentifier":"E0:DB:10:1F:C9:5E","peerAvailable":true}]
I/jxcore-log( 7739): 
I/jxcore-log( 7739): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV5151","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV9290","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV7384","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true}]
I/jxcore-log( 7739): 
I/jxcore-log( 7739): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV4792","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true}]
I/jxcore-log( 7739): 
I/jxcore-log( 7739): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV6153","peerIdentifier":"50:2E:6C:AC:21:50","peerAvailable":true}]
I/jxcore-log( 7739): 
I/jxcore-log( 7739): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV4169","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV9615","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV6349","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true}]
I/jxcore-log( 7739): 
I/jxcore-log( 7739): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV6513","peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV5731","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true}]
I/jxcore-log( 7739): 
I/jxcore-log( 7739): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): peerAvailabilityChanged [{"peerName":"DEV1994","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true}]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): CoordinatorConnector disconnect called
I/jxcore-log( 7739): 
I/jxcore-log( 7739): The client has disconnected!
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): stop tests now !
I/jxcore-log( 7739): 
I/jxcore-log( 7739): stop current!
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): testFindPeers stopped
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): StopBroadcasting went ok
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): turning Radios off
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Turning radios to false
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): toggleBluetooth - 
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): toggleWiFi
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,I/jxcore-log( 7739): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7739): 
,TIME-OUT KILL (timeout was 1800000ms)

```

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:null 
child process exited with code null on device 0c6a0f3c0bdb4e77 
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Android task is completed 
```

Logcat output:
```
LGE-Nexus 5: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,TIME-OUT KILL (timeout was 1800000ms)

HTC-HTC Desire 820: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log( 5139): Initializing JXcore engine
,W/jxcore-log( 5139): JXcore engine is ready
,W/jxcore-log( 5139): Starting JXcore engine
,W/jxcore-log( 5139): Platform android
W/jxcore-log( 5139): 
,W/jxcore-log( 5139): Process ARCH arm
W/jxcore-log( 5139): 
,I/jxcore-log( 5139): JXcore Cordova bridge is ready!
I/jxcore-log( 5139): 
W/jxcore-log( 5139): JXcore engine is started
,I/jxcore-log( 5139): Turning radios to true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): toggleBluetooth - 
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): toggleWiFi
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): my name is : DEV3665
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): attempting to connect to test coordinator
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): check test folder
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): found test : ./testFindPeers.js
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): found test : ./testReConnect.js
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): found test : ./testSendData.js
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Test app app.js loaded
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): LogCallback not set !!!!
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Client has connected to the server!
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":21}
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Start now : testFindPeers.js
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): stop tests now !
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): serverPort is 8876
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): StartBroadcasting started ok
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV9958","peerIdentifier":"80:01:84:8A:B3:68","peerAvailable":true}]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV8510","peerIdentifier":"00:F4:6F:30:E0:6C","peerAvailable":true}]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV4442","peerIdentifier":"F4:F1:E1:5C:3B:E2","peerAvailable":true}]
I/jxcore-log( 5139): 
I/jxcore-log( 5139): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV7246","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true}]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV714","peerIdentifier":"34:FC:EF:9D:93:0B","peerAvailable":true}]
I/jxcore-log( 5139): 
I/jxcore-log( 5139): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV5151","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true}]
I/jxcore-log( 5139): 
I/jxcore-log( 5139): Found peer : 58:3F:54:73:64:C0, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV6441","peerIdentifier":"10:D3:8A:FB:85:D4","peerAvailable":true}]
I/jxcore-log( 5139): 
I/jxcore-log( 5139): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV6513","peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true}]
I/jxcore-log( 5139): 
I/jxcore-log( 5139): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV7041","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true}]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV6153","peerIdentifier":"50:2E:6C:AC:21:50","peerAvailable":true}]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV4169","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true}]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV6348","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true}]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV5731","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true}]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV4792","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true}]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV9290","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true}]
I/jxcore-log( 5139): 
I/jxcore-log( 5139): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV9615","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true}]
I/jxcore-log( 5139): 
I/jxcore-log( 5139): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV6349","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true}]
I/jxcore-log( 5139): 
I/jxcore-log( 5139): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV7384","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true}]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): peerAvailabilityChanged [{"peerName":"DEV9027","peerIdentifier":"E0:DB:10:1F:C9:5E","peerAvailable":true}]
I/jxcore-log( 5139): 
I/jxcore-log( 5139): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): CoordinatorConnector disconnect called
I/jxcore-log( 5139): 
I/jxcore-log( 5139): The client has disconnected!
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): stop tests now !
I/jxcore-log( 5139): 
I/jxcore-log( 5139): stop current!
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): testFindPeers stopped
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): StopBroadcasting went ok
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): turning Radios off
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Turning radios to false
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): toggleBluetooth - 
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): toggleWiFi
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 5139): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5139): 


```




#### Integration Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"android":25}}
Star Android tests : performance tests, start tests with timer

Test[0]: testFindPeers.js, timeout : 700000, data : {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
Star iOs tests : performance tests, start tests with timer
Test[0]: testFindPeers.js, timeout : 700000, data : {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}

listening on *:3000

got connection 

Android  DEV5731 added : 1.182 sec., device count 1

got connection 

got connection 

got connection 

Android  DEV4792 added : 1.515 sec., device count 2

Android  DEV9615 added : 1.561 sec., device count 3

Android  DEV9958 added : 1.661 sec., device count 4

got connection 

Android  DEV3665 added : 3.203 sec., device count 5

got connection 

Android  DEV4169 added : 3.542 sec., device count 6

got connection 

Android  DEV1994 added : 4.099 sec., device count 7

got connection 

Android  DEV6513 added : 15.179 sec., device count 8

got connection 

got connection 

Android  DEV7041 added : 19.884 sec., device count 9

Android  DEV9027 added : 19.909 sec., device count 10

got connection 

Android  DEV714 added : 21.753 sec., device count 11

got connection 

Android  DEV5151 added : 43.574 sec., device count 12

got connection 

got connection 

Android  DEV2807 added : 47.611 sec., device count 13

Android  DEV4442 added : 47.81 sec., device count 14

got connection 

Android  DEV6441 added : 48.819 sec., device count 15

got connection 

Android  DEV8510 added : 49.537 sec., device count 16

got connection 

Android  DEV6348 added : 50.203 sec., device count 17

got connection 

Android  DEV6153 added : 70.789 sec., device count 18

got connection 

Android  DEV9290 added : 158.783 sec., device count 19

got connection 

Android  DEV6349 added : 159.94 sec., device count 20

got connection 

Android  DEV7246 added : 161.169 sec., device count 21

got connection 

Android  DEV7384 added : 164.369 sec., device count 22

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 22 devices.

start test[0] with 22 devices.


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```

