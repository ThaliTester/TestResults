#### Test 4803725096f6929 Logs

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

Android  DEV5772 added : 2.053 sec., device count 1

got connection 

Android  DEV902 added : 2.549 sec., device count 2

got connection 

Android  DEV7671 added : 2.868 sec., device count 3

got connection 

Android  DEV6608 added : 3.114 sec., device count 4

got connection 

Android  DEV6470 added : 4.025 sec., device count 5

got connection 

Android  DEV7258 added : 4.278 sec., device count 6

got connection 

Android  DEV5153 added : 13.104 sec., device count 7

got connection 

Android  DEV4959 added : 13.23 sec., device count 8

got connection 

Android  DEV1299 added : 21.69 sec., device count 9

got connection 

Android  DEV4707 added : 23.894 sec., device count 10

got connection 

Android  DEV1878 added : 30.262 sec., device count 11

got connection 

Android  DEV3530 added : 47.392 sec., device count 12

got connection 

Android  DEV1854 added : 49.272 sec., device count 13

got connection 

Android  DEV8143 added : 52.562 sec., device count 14

got connection 

Android  DEV1517 added : 53.321 sec., device count 15

got connection 

Android  DEV5824 added : 87.347 sec., device count 16

got connection 

Android  DEV6011 added : 104.377 sec., device count 17

got connection 

Android  DEV3467 added : 152.483 sec., device count 18

got connection 

Android  DEV4165 added : 153.96 sec., device count 19

got connection 

Android  DEV7863 added : 155.39 sec., device count 20

got connection 

Android  DEV4230 added : 163.962 sec., device count 21

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 21 devices.

start test[0] with 21 devices.


 
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
,W/jxcore-log( 7799): Initializing JXcore engine
W/jxcore-log( 7799): JXcore engine is ready
,W/jxcore-log( 7799): Starting JXcore engine
,W/jxcore-log( 7799): Platform android
W/jxcore-log( 7799): 
W/jxcore-log( 7799): Process ARCH arm
W/jxcore-log( 7799): 
,I/jxcore-log( 7799): JXcore Cordova bridge is ready!
I/jxcore-log( 7799): 
W/jxcore-log( 7799): JXcore engine is started
,I/jxcore-log( 7799): Turning radios to true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): toggleBluetooth - 
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): toggleWiFi
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): my name is : DEV8143
I/jxcore-log( 7799): 
I/jxcore-log( 7799): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): attempting to connect to test coordinator
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): check test folder
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): found test : ./testFindPeers.js
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): found test : ./testReConnect.js
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): found test : ./testSendData.js
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Test app app.js loaded
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Client has connected to the server!
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Start now : testFindPeers.js
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): stop tests now !
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): serverPort is 8876
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): StartBroadcasting started ok
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): CoordinatorConnector disconnect called
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): The client has disconnected!
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): stop tests now !
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): stop current!
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): testFindPeers stopped
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): StopBroadcasting went ok
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): turning Radios off
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Turning radios to false
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): toggleBluetooth - 
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): toggleWiFi
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,I/jxcore-log( 7799): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7799): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-T232: 
--------- beginning of /dev/log/system
,--------- beginning of /dev/log/main
,W/jxcore-log(29033): Initializing JXcore engine
,W/jxcore-log(29033): JXcore engine is ready
,W/jxcore-log(29033): Starting JXcore engine
,W/jxcore-log(29033): Platform android
W/jxcore-log(29033): 
,W/jxcore-log(29033): Process ARCH arm
W/jxcore-log(29033): 
,I/jxcore-log(29033): JXcore Cordova bridge is ready!
I/jxcore-log(29033): 
,W/jxcore-log(29033): JXcore engine is started
,I/jxcore-log(29033): Turning radios to true
I/jxcore-log(29033): 
,I/jxcore-log(29033): toggleBluetooth - 
I/jxcore-log(29033): 
,I/jxcore-log(29033): toggleWiFi
I/jxcore-log(29033): 
,I/jxcore-log(29033): my name is : DEV7914
I/jxcore-log(29033): 
,I/jxcore-log(29033): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(29033): 
,I/jxcore-log(29033): attempting to connect to test coordinator
I/jxcore-log(29033): 
,I/jxcore-log(29033): check test folder
I/jxcore-log(29033): 
,I/jxcore-log(29033): found test : ./testFindPeers.js
I/jxcore-log(29033): 
,I/jxcore-log(29033): found test : ./testReConnect.js
I/jxcore-log(29033): 
,I/jxcore-log(29033): found test : ./testSendData.js
I/jxcore-log(29033): 
,I/jxcore-log(29033): Test app app.js loaded
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): LogCallback not set !!!!
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,I/jxcore-log(29033): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(29033): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-H815: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log( 9165): Initializing JXcore engine
W/jxcore-log( 9165): JXcore engine is ready
,W/jxcore-log( 9165): Starting JXcore engine
,W/jxcore-log( 9165): Platform android
W/jxcore-log( 9165): 
W/jxcore-log( 9165): Process ARCH arm
W/jxcore-log( 9165): 
,I/jxcore-log( 9165): JXcore Cordova bridge is ready!
I/jxcore-log( 9165): 
,W/jxcore-log( 9165): JXcore engine is started
,I/jxcore-log( 9165): Turning radios to true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): toggleBluetooth - 
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): toggleWiFi
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): my name is : DEV1517
I/jxcore-log( 9165): 
I/jxcore-log( 9165): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): attempting to connect to test coordinator
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): check test folder
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): found test : ./testFindPeers.js
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): found test : ./testReConnect.js
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): found test : ./testSendData.js
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Test app app.js loaded
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
I/jxcore-log( 9165): LogCallback not set !!!!
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Client has connected to the server!
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Start now : testFindPeers.js
I/jxcore-log( 9165): 
I/jxcore-log( 9165): stop tests now !
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): serverPort is 8876
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): StartBroadcasting started ok
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true,
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): CoordinatorConnector disconnect called
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): The client has disconnected!
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): stop tests now !
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): stop current!
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): testFindPeers stopped
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): StopBroadcasting went ok,
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): turning Radios off
I/jxcore-log( 9165): 
I/jxcore-log( 9165): Turning radios to false
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): toggleBluetooth - 
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): toggleWiFi
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,I/jxcore-log( 9165): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9165): 
,TIME-OUT KILL (timeout was 1800000ms)

HUAWEI-ALE-L21: 
int logctl_get(): open '/dev/hwlog_switch' fail -1, 13. Permission denied

Note: log switch off, only log_main and log_events will have logs!
--------- beginning of main
,W/jxcore-log(11080): Initializing JXcore engine
W/jxcore-log(11080): JXcore engine is ready
,W/jxcore-log(11080): Starting JXcore engine
,W/jxcore-log(11080): Platform android
W/jxcore-log(11080): 
W/jxcore-log(11080): Process ARCH arm
W/jxcore-log(11080): 
,I/jxcore-log(11080): JXcore Cordova bridge is ready!
I/jxcore-log(11080): 
W/jxcore-log(11080): JXcore engine is started
,I/jxcore-log(11080): Turning radios to true
I/jxcore-log(11080): 
,I/jxcore-log(11080): toggleBluetooth - 
I/jxcore-log(11080): 
,I/jxcore-log(11080): toggleWiFi
I/jxcore-log(11080): 
,I/jxcore-log(11080): my name is : DEV1854
I/jxcore-log(11080): 
I/jxcore-log(11080): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(11080): 
,I/jxcore-log(11080): attempting to connect to test coordinator
I/jxcore-log(11080): 
,I/jxcore-log(11080): check test folder
I/jxcore-log(11080): 
,I/jxcore-log(11080): found test : ./testFindPeers.js
I/jxcore-log(11080): 
,I/jxcore-log(11080): found test : ./testReConnect.js
I/jxcore-log(11080): 
,I/jxcore-log(11080): found test : ./testSendData.js
I/jxcore-log(11080): 
,I/jxcore-log(11080): Test app app.js loaded
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
I/jxcore-log(11080): LogCallback not set !!!!
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Client has connected to the server!
I/jxcore-log(11080): 
,I/jxcore-log(11080): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log(11080): 
,I/jxcore-log(11080): Start now : testFindPeers.js
I/jxcore-log(11080): 
I/jxcore-log(11080): stop tests now !
I/jxcore-log(11080): 
,I/jxcore-log(11080): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(11080): 
,I/jxcore-log(11080): serverPort is 8876
I/jxcore-log(11080): 
,I/jxcore-log(11080): StartBroadcasting started ok
I/jxcore-log(11080): 
,I/jxcore-log(11080): CoordinatorConnector disconnect called
I/jxcore-log(11080): 
I/jxcore-log(11080): The client has disconnected!
I/jxcore-log(11080): 
I/jxcore-log(11080): stop tests now !
I/jxcore-log(11080): 
I/jxcore-log(11080): stop current!
I/jxcore-log(11080): 
I/jxcore-log(11080): testFindPeers stopped
I/jxcore-log(11080): 
,I/jxcore-log(11080): StopBroadcasting went ok
I/jxcore-log(11080): 
,I/jxcore-log(11080): turning Radios off
I/jxcore-log(11080): 
,I/jxcore-log(11080): Turning radios to false
I/jxcore-log(11080): 
,I/jxcore-log(11080): toggleBluetooth - 
I/jxcore-log(11080): 
,I/jxcore-log(11080): toggleWiFi
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,I/jxcore-log(11080): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11080): 
,TIME-OUT KILL (timeout was 1800000ms)

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
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(11568): Initializing JXcore engine
W/jxcore-log(11568): JXcore engine is ready
,W/jxcore-log(11568): Starting JXcore engine
,W/jxcore-log(11568): Platform android
W/jxcore-log(11568): 
W/jxcore-log(11568): Process ARCH arm
W/jxcore-log(11568): 
,I/jxcore-log(11568): JXcore Cordova bridge is ready!
I/jxcore-log(11568): 
,W/jxcore-log(11568): JXcore engine is started
,I/jxcore-log(11568): Turning radios to true
I/jxcore-log(11568): 
,I/jxcore-log(11568): toggleBluetooth - 
I/jxcore-log(11568): 
,I/jxcore-log(11568): toggleWiFi
I/jxcore-log(11568): 
,I/jxcore-log(11568): my name is : DEV6011
I/jxcore-log(11568): 
I/jxcore-log(11568): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(11568): 
,I/jxcore-log(11568): attempting to connect to test coordinator
I/jxcore-log(11568): 
,I/jxcore-log(11568): check test folder
I/jxcore-log(11568): 
I/jxcore-log(11568): found test : ./testFindPeers.js
I/jxcore-log(11568): 
,I/jxcore-log(11568): found test : ./testReConnect.js
I/jxcore-log(11568): 
,I/jxcore-log(11568): found test : ./testSendData.js
I/jxcore-log(11568): 
,I/jxcore-log(11568): Test app app.js loaded
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Client has connected to the server!
I/jxcore-log(11568): 
,I/jxcore-log(11568): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log(11568): 
,I/jxcore-log(11568): Start now : testFindPeers.js
I/jxcore-log(11568): 
,I/jxcore-log(11568): stop tests now !
I/jxcore-log(11568): 
,I/jxcore-log(11568): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(11568): 
,I/jxcore-log(11568): serverPort is 8876
I/jxcore-log(11568): 
,I/jxcore-log(11568): StartBroadcasting started ok
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(11568): 
I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(11568): 
,I/jxcore-log(11568): CoordinatorConnector disconnect called
I/jxcore-log(11568): 
,I/jxcore-log(11568): The client has disconnected!
I/jxcore-log(11568): 
,I/jxcore-log(11568): stop tests now !
I/jxcore-log(11568): 
,I/jxcore-log(11568): stop current!
I/jxcore-log(11568): 
,I/jxcore-log(11568): testFindPeers stopped
I/jxcore-log(11568): 
,I/jxcore-log(11568): StopBroadcasting went ok
I/jxcore-log(11568): 
,I/jxcore-log(11568): turning Radios off
I/jxcore-log(11568): 
I/jxcore-log(11568): Turning radios to false
I/jxcore-log(11568): 
,I/jxcore-log(11568): toggleBluetooth - 
I/jxcore-log(11568): 
,I/jxcore-log(11568): toggleWiFi
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(11568): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(11568): 


LGE-LG-D722: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(20776): Initializing JXcore engine
W/jxcore-log(20776): JXcore engine is ready
,W/jxcore-log(20776): Starting JXcore engine
,W/jxcore-log(20776): Platform android
W/jxcore-log(20776): 
W/jxcore-log(20776): Process ARCH arm
W/jxcore-log(20776): 
,I/jxcore-log(20776): JXcore Cordova bridge is ready!
I/jxcore-log(20776): 
W/jxcore-log(20776): JXcore engine is started
,I/jxcore-log(20776): Turning radios to true
I/jxcore-log(20776): 
,I/jxcore-log(20776): toggleBluetooth - 
I/jxcore-log(20776): 
,I/jxcore-log(20776): toggleWiFi
I/jxcore-log(20776): 
,I/jxcore-log(20776): my name is : DEV6470
I/jxcore-log(20776): 
I/jxcore-log(20776): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(20776): 
I/jxcore-log(20776): attempting to connect to test coordinator
I/jxcore-log(20776): 
I/jxcore-log(20776): check test folder
I/jxcore-log(20776): 
I/jxcore-log(20776): found test : ./testFindPeers.js
I/jxcore-log(20776): 
I/jxcore-log(20776): found test : ./testReConnect.js
I/jxcore-log(20776): 
I/jxcore-log(20776): found test : ./testSendData.js
I/jxcore-log(20776): 
I/jxcore-log(20776): Test app app.js loaded
I/jxcore-log(20776): 
I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): ,
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(20776): 
I/jxcore-log(20776): Client has connected to the server!
I/jxcore-log(20776): 
,I/jxcore-log(20776): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20},
I/jxcore-log(20776): 
I/jxcore-log(20776): Start now : testFindPeers.js
I/jxcore-log(20776): 
,I/jxcore-log(20776): stop tests now !
I/jxcore-log(20776): 
I/jxcore-log(20776): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(20776): 
I/jxcore-log(20776): serverPort is 8876,
I/jxcore-log(20776): 
,I/jxcore-log(20776): StartBroadcasting started ok,
I/jxcore-log(20776): 
,I/jxcore-log(20776): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}],
I/jxcore-log(20776): 
,I/jxcore-log(20776): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(20776): 
,I/jxcore-log(20776): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log(20776): 
I/jxcore-log(20776): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(20776): 
,I/jxcore-log(20776): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}],
I/jxcore-log(20776): 
,I/jxcore-log(20776): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(20776): 
,I/jxcore-log(20776): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}],
I/jxcore-log(20776): 
,I/jxcore-log(20776): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(20776): 
,I/jxcore-log(20776): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}],
I/jxcore-log(20776): 
,I/jxcore-log(20776): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(20776): 
I/jxcore-log(20776): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log(20776): ,
I/jxcore-log(20776): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(20776): 
,I/jxcore-log(20776): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(20776): 
,I/jxcore-log(20776): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(20776): 
,I/jxcore-log(20776): CoordinatorConnector disconnect called
I/jxcore-log(20776): 
,I/jxcore-log(20776): The client has disconnected!
I/jxcore-log(20776): 
I/jxcore-log(20776): stop tests now !
I/jxcore-log(20776): 
I/jxcore-log(20776): stop current!
I/jxcore-log(20776): 
,I/jxcore-log(20776): testFindPeers stopped
I/jxcore-log(20776): 
,I/jxcore-log(20776): StopBroadcasting went ok
I/jxcore-log(20776): 
,I/jxcore-log(20776): turning Radios off
I/jxcore-log(20776): 
,I/jxcore-log(20776): Turning radios to false
I/jxcore-log(20776): 
,I/jxcore-log(20776): toggleBluetooth - 
I/jxcore-log(20776): 
,I/jxcore-log(20776): toggleWiFi
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
,I/jxcore-log(20776): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20776): 
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
,W/jxcore-log(31350): Initializing JXcore engine
,W/jxcore-log(31350): JXcore engine is ready
,W/jxcore-log(31350): Starting JXcore engine
,W/jxcore-log(31350): Platform android
W/jxcore-log(31350): 
,W/jxcore-log(31350): Process ARCH arm
W/jxcore-log(31350): 
,I/jxcore-log(31350): JXcore Cordova bridge is ready!
I/jxcore-log(31350): 
,W/jxcore-log(31350): JXcore engine is started
,I/jxcore-log(31350): Turning radios to true
I/jxcore-log(31350): 
,I/jxcore-log(31350): toggleBluetooth - 
I/jxcore-log(31350): 
,I/jxcore-log(31350): toggleWiFi
I/jxcore-log(31350): 
,I/jxcore-log(31350): my name is : DEV5824
I/jxcore-log(31350): 
,I/jxcore-log(31350): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(31350): 
,I/jxcore-log(31350): attempting to connect to test coordinator
I/jxcore-log(31350): 
,I/jxcore-log(31350): check test folder
I/jxcore-log(31350): 
,I/jxcore-log(31350): found test : ./testFindPeers.js
I/jxcore-log(31350): 
,I/jxcore-log(31350): found test : ./testReConnect.js
I/jxcore-log(31350): 
,I/jxcore-log(31350): found test : ./testSendData.js
I/jxcore-log(31350): 
,I/jxcore-log(31350): Test app app.js loaded
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Client has connected to the server!
I/jxcore-log(31350): 
,I/jxcore-log(31350): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log(31350): 
,I/jxcore-log(31350): Start now : testFindPeers.js
I/jxcore-log(31350): 
,I/jxcore-log(31350): stop tests now !
I/jxcore-log(31350): 
,I/jxcore-log(31350): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(31350): 
,I/jxcore-log(31350): serverPort is 8876
I/jxcore-log(31350): 
,I/jxcore-log(31350): StartBroadcasting started ok
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV902","peerIdentifier":"80:01:84:8A:B3:68","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV3530","peerIdentifier":"00:F4:6F:30:E0:6C","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV5772","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV4165","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV7671","peerIdentifier":"B4:CE:F6:AB:A4:6A","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV1517","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV1299","peerIdentifier":"34:FC:EF:9D:93:0B","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV6608","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV7258","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV8143","peerIdentifier":"10:D3:8A:FB:85:D4","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV5153","peerIdentifier":"E0:DB:10:1F:C9:5E","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV3467","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV6470","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV4707","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV7863","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV4230","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV6011","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV1878","peerIdentifier":"50:2E:6C:AC:21:50","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): peerAvailabilityChanged [{"peerName":"DEV4959","peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true}]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(31350): 
,I/jxcore-log(31350): CoordinatorConnector disconnect called
I/jxcore-log(31350): 
,I/jxcore-log(31350): The client has disconnected!
I/jxcore-log(31350): 
I/jxcore-log(31350): stop tests now !
I/jxcore-log(31350): 
,I/jxcore-log(31350): stop current!
I/jxcore-log(31350): 
,I/jxcore-log(31350): testFindPeers stopped
I/jxcore-log(31350): 
,I/jxcore-log(31350): StopBroadcasting went ok
I/jxcore-log(31350): 
,I/jxcore-log(31350): turning Radios off
I/jxcore-log(31350): 
,I/jxcore-log(31350): Turning radios to false
I/jxcore-log(31350): 
,I/jxcore-log(31350): toggleBluetooth - 
I/jxcore-log(31350): 
,I/jxcore-log(31350): toggleWiFi
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31350): 
,I/jxcore-log(31350): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31350): 
,TIME-OUT KILL (timeout was 1800000ms)

LGE-LG-D855: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(26707): Initializing JXcore engine,
W/jxcore-log(26707): JXcore engine is ready
,W/jxcore-log(26707): Starting JXcore engine,
,W/jxcore-log(26707): Platform android
W/jxcore-log(26707): 
,W/jxcore-log(26707): Process ARCH arm
W/jxcore-log(26707): 
,I/jxcore-log(26707): JXcore Cordova bridge is ready!
I/jxcore-log(26707): 
,W/jxcore-log(26707): JXcore engine is started
,I/jxcore-log(26707): Turning radios to true
I/jxcore-log(26707): 
,I/jxcore-log(26707): toggleBluetooth - 
I/jxcore-log(26707): 
,I/jxcore-log(26707): toggleWiFi
I/jxcore-log(26707): 
,I/jxcore-log(26707): my name is : DEV2353
I/jxcore-log(26707): 
I/jxcore-log(26707): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(26707): 
,I/jxcore-log(26707): attempting to connect to test coordinator
I/jxcore-log(26707): 
I/jxcore-log(26707): check test folder
I/jxcore-log(26707): 
I/jxcore-log(26707): found test : ./testFindPeers.js
I/jxcore-log(26707): 
,I/jxcore-log(26707): found test : ./testReConnect.js
I/jxcore-log(26707): 
I/jxcore-log(26707): found test : ./testSendData.js
I/jxcore-log(26707): 
,I/jxcore-log(26707): Test app app.js loaded
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
I/jxcore-log(26707): LogCallback not set !!!!
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): ,
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,I/jxcore-log(26707): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26707): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-G800F: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 3624): Initializing JXcore engine
,W/jxcore-log( 3624): JXcore engine is ready
,W/jxcore-log( 3624): Starting JXcore engine
,W/jxcore-log( 3624): Platform android
W/jxcore-log( 3624): 
,W/jxcore-log( 3624): Process ARCH arm
W/jxcore-log( 3624): 
,I/jxcore-log( 3624): JXcore Cordova bridge is ready!
I/jxcore-log( 3624): 
,W/jxcore-log( 3624): JXcore engine is started
,I/jxcore-log( 3624): Turning radios to true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): toggleBluetooth - 
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): toggleWiFi
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): my name is : DEV3530
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): attempting to connect to test coordinator
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): check test folder
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): found test : ./testFindPeers.js
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): found test : ./testReConnect.js
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): found test : ./testSendData.js
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Test app app.js loaded
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Client has connected to the server!
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Start now : testFindPeers.js
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): stop tests now !
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): serverPort is 8876
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): StartBroadcasting started ok
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV1299","peerIdentifier":"34:FC:EF:9D:93:0B","peerAvailable":true}]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV7671","peerIdentifier":"B4:CE:F6:AB:A4:6A","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV8143","peerIdentifier":"10:D3:8A:FB:85:D4","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV902","peerIdentifier":"80:01:84:8A:B3:68","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV1517","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true}]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV6608","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true}]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV5824","peerIdentifier":"F4:F1:E1:5C:3B:E2","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV3467","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true}]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV4707","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV5772","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV1878","peerIdentifier":"50:2E:6C:AC:21:50","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV4230","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true}]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV7258","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true}],
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Found peer : B0:C5:59:3F:75:69, peerAvailable: true,
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV7863","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV4165","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true}]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV6470","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV4959","peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): peerAvailabilityChanged [{"peerName":"DEV5153","peerIdentifier":"E0:DB:10:1F:C9:5E","peerAvailable":true}]
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): CoordinatorConnector disconnect called
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): The client has disconnected!
I/jxcore-log( 3624): 
I/jxcore-log( 3624): stop tests now !
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): stop current!
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): testFindPeers stopped
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): StopBroadcasting went ok
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): turning Radios off
I/jxcore-log( 3624): 
I/jxcore-log( 3624): Turning radios to false
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): toggleBluetooth - 
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): toggleWiFi
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
,I/jxcore-log( 3624): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 3624): 
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
,W/jxcore-log( 9473): Initializing JXcore engine
,W/jxcore-log( 9473): JXcore engine is ready
,W/jxcore-log( 9473): Starting JXcore engine
,W/jxcore-log( 9473): Platform android
W/jxcore-log( 9473): 
,W/jxcore-log( 9473): Process ARCH arm
W/jxcore-log( 9473): 
,I/jxcore-log( 9473): JXcore Cordova bridge is ready!
I/jxcore-log( 9473): 
W/jxcore-log( 9473): JXcore engine is started
,I/jxcore-log( 9473): Turning radios to true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): toggleBluetooth - 
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): toggleWiFi
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): my name is : DEV4230
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): attempting to connect to test coordinator
I/jxcore-log( 9473): 
I/jxcore-log( 9473): check test folder
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): found test : ./testFindPeers.js
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): found test : ./testReConnect.js
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): found test : ./testSendData.js
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Test app app.js loaded
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
I/jxcore-log( 9473): LogCallback not set !!!!
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Client has connected to the server!
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Start now : testFindPeers.js
I/jxcore-log( 9473): 
I/jxcore-log( 9473): stop tests now !
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): serverPort is 8876
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): StartBroadcasting started ok
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): CoordinatorConnector disconnect called
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): The client has disconnected!
I/jxcore-log( 9473): 
I/jxcore-log( 9473): stop tests now !
I/jxcore-log( 9473): 
I/jxcore-log( 9473): stop current!
I/jxcore-log( 9473): 
I/jxcore-log( 9473): testFindPeers stopped
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): StopBroadcasting went ok
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): turning Radios off
I/jxcore-log( 9473): 
I/jxcore-log( 9473): Turning radios to false
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): toggleBluetooth - 
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): toggleWiFi
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,I/jxcore-log( 9473): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 9473): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-N910C: 
--------- beginning of system
,--------- beginning of main
,W/jxcore-log(14934): Initializing JXcore engine
,W/jxcore-log(14934): JXcore engine is ready
,W/jxcore-log(14934): Starting JXcore engine
,W/jxcore-log(14934): Platform android
W/jxcore-log(14934): 
W/jxcore-log(14934): Process ARCH arm
W/jxcore-log(14934): 
,I/jxcore-log(14934): JXcore Cordova bridge is ready!
I/jxcore-log(14934): 
W/jxcore-log(14934): JXcore engine is started
,I/jxcore-log(14934): Turning radios to true
I/jxcore-log(14934): 
,I/jxcore-log(14934): toggleBluetooth - 
I/jxcore-log(14934): 
,I/jxcore-log(14934): toggleWiFi
I/jxcore-log(14934): 
,I/jxcore-log(14934): my name is : DEV7863
I/jxcore-log(14934): 
,I/jxcore-log(14934): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(14934): 
,I/jxcore-log(14934): attempting to connect to test coordinator
I/jxcore-log(14934): 
,I/jxcore-log(14934): check test folder
I/jxcore-log(14934): 
,I/jxcore-log(14934): found test : ./testFindPeers.js
I/jxcore-log(14934): 
,I/jxcore-log(14934): found test : ./testReConnect.js
I/jxcore-log(14934): 
,I/jxcore-log(14934): found test : ./testSendData.js
I/jxcore-log(14934): 
,I/jxcore-log(14934): Test app app.js loaded
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
I/jxcore-log(14934): LogCallback not set !!!!
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Client has connected to the server!
I/jxcore-log(14934): 
,I/jxcore-log(14934): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20},
I/jxcore-log(14934): 
,I/jxcore-log(14934): Start now : testFindPeers.js
I/jxcore-log(14934): 
,I/jxcore-log(14934): stop tests now !
I/jxcore-log(14934): 
,I/jxcore-log(14934): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(14934): 
,I/jxcore-log(14934): serverPort is 8876
I/jxcore-log(14934): 
,I/jxcore-log(14934): StartBroadcasting started ok
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(14934): 
,I/jxcore-log(14934): CoordinatorConnector disconnect called
I/jxcore-log(14934): 
,I/jxcore-log(14934): The client has disconnected!
I/jxcore-log(14934): 
,I/jxcore-log(14934): stop tests now !
I/jxcore-log(14934): 
,I/jxcore-log(14934): stop current!
I/jxcore-log(14934): 
,I/jxcore-log(14934): testFindPeers stopped
I/jxcore-log(14934): 
,I/jxcore-log(14934): StopBroadcasting went ok
I/jxcore-log(14934): 
,I/jxcore-log(14934): turning Radios off
I/jxcore-log(14934): 
,I/jxcore-log(14934): Turning radios to false
I/jxcore-log(14934): 
,I/jxcore-log(14934): toggleBluetooth - 
I/jxcore-log(14934): 
,I/jxcore-log(14934): toggleWiFi
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,I/jxcore-log(14934): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14934): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-A500FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(15421): Initializing JXcore engine
W/jxcore-log(15421): JXcore engine is ready
W/jxcore-log(15421): Starting JXcore engine
W/jxcore-log(15421): Platform android
W/jxcore-log(15421): 
W/jxcore-log(15421): Process ARCH arm
W/jxcore-log(15421): 
,I/jxcore-log(15421): JXcore Cordova bridge is ready!
I/jxcore-log(15421): 
W/jxcore-log(15421): JXcore engine is started
,I/jxcore-log(15421): Turning radios to true
I/jxcore-log(15421): 
,I/jxcore-log(15421): toggleBluetooth - 
I/jxcore-log(15421): 
,I/jxcore-log(15421): toggleWiFi
I/jxcore-log(15421): 
,I/jxcore-log(15421): my name is : DEV3467
I/jxcore-log(15421): 
I/jxcore-log(15421): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(15421): 
,I/jxcore-log(15421): attempting to connect to test coordinator,
I/jxcore-log(15421): 
,I/jxcore-log(15421): check test folder
I/jxcore-log(15421): 
,I/jxcore-log(15421): found test : ./testFindPeers.js,
I/jxcore-log(15421): 
,I/jxcore-log(15421): found test : ./testReConnect.js,
I/jxcore-log(15421): 
,I/jxcore-log(15421): found test : ./testSendData.js,
I/jxcore-log(15421): 
,I/jxcore-log(15421): Test app app.js loaded
I/jxcore-log(15421): 
,I/jxcore-log(15421): Client has connected to the server!
I/jxcore-log(15421): 
,I/jxcore-log(15421): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log(15421): 
,I/jxcore-log(15421): Start now : testFindPeers.js
I/jxcore-log(15421): 
I/jxcore-log(15421): stop tests now !
I/jxcore-log(15421): 
,I/jxcore-log(15421): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(15421): 
,I/jxcore-log(15421): serverPort is 8876
I/jxcore-log(15421): 
,I/jxcore-log(15421): StartBroadcasting started ok
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}],
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}],
I/jxcore-log(15421): 
I/jxcore-log(15421): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(15421): 
,I/jxcore-log(15421): CoordinatorConnector disconnect called,
I/jxcore-log(15421): 
I/jxcore-log(15421): The client has disconnected!
I/jxcore-log(15421): 
I/jxcore-log(15421): stop tests now !
I/jxcore-log(15421): 
I/jxcore-log(15421): stop current!
I/jxcore-log(15421): 
,I/jxcore-log(15421): testFindPeers stopped
I/jxcore-log(15421): 
,I/jxcore-log(15421): StopBroadcasting went ok
I/jxcore-log(15421): 
,I/jxcore-log(15421): turning Radios off
I/jxcore-log(15421): 
,I/jxcore-log(15421): Turning radios to false
I/jxcore-log(15421): 
,I/jxcore-log(15421): toggleBluetooth - 
I/jxcore-log(15421): 
,I/jxcore-log(15421): toggleWiFi
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(15421): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(15421): 


samsung-SM-G900F: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(26515): Initializing JXcore engine
W/jxcore-log(26515): JXcore engine is ready
,W/jxcore-log(26515): Starting JXcore engine
,W/jxcore-log(26515): Platform android
W/jxcore-log(26515): 
W/jxcore-log(26515): Process ARCH arm
W/jxcore-log(26515): 
,I/jxcore-log(26515): JXcore Cordova bridge is ready!
I/jxcore-log(26515): 
W/jxcore-log(26515): JXcore engine is started
I/jxcore-log(26515): Turning radios to true
I/jxcore-log(26515): 
I/jxcore-log(26515): toggleBluetooth - 
I/jxcore-log(26515): 
I/jxcore-log(26515): toggleWiFi
I/jxcore-log(26515): 
,I/jxcore-log(26515): my name is : DEV4165
I/jxcore-log(26515): 
I/jxcore-log(26515): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(26515): 
,I/jxcore-log(26515): attempting to connect to test coordinator
I/jxcore-log(26515): 
,I/jxcore-log(26515): check test folder
I/jxcore-log(26515): 
,I/jxcore-log(26515): found test : ./testFindPeers.js
I/jxcore-log(26515): 
,I/jxcore-log(26515): found test : ./testReConnect.js
I/jxcore-log(26515): 
,I/jxcore-log(26515): found test : ./testSendData.js
I/jxcore-log(26515): 
,I/jxcore-log(26515): Test app app.js loaded
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): LogCallback not set !!!!
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Client has connected to the server!
I/jxcore-log(26515): 
,I/jxcore-log(26515): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20},
,I/jxcore-log(26515): 
,I/jxcore-log(26515): Start now : testFindPeers.js
I/jxcore-log(26515): 
,I/jxcore-log(26515): stop tests now !
I/jxcore-log(26515): 
,I/jxcore-log(26515): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(26515): 
,I/jxcore-log(26515): serverPort is 8876
I/jxcore-log(26515): 
,I/jxcore-log(26515): StartBroadcasting started ok
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(26515): 
,I/jxcore-log(26515): CoordinatorConnector disconnect called,
,I/jxcore-log(26515): 
,I/jxcore-log(26515): The client has disconnected!
I/jxcore-log(26515): 
,I/jxcore-log(26515): stop tests now !
I/jxcore-log(26515): 
,I/jxcore-log(26515): stop current!
I/jxcore-log(26515): 
,I/jxcore-log(26515): testFindPeers stopped
I/jxcore-log(26515): 
,I/jxcore-log(26515): StopBroadcasting went ok
I/jxcore-log(26515): 
,I/jxcore-log(26515): turning Radios off
I/jxcore-log(26515): 
,I/jxcore-log(26515): Turning radios to false
I/jxcore-log(26515): 
,I/jxcore-log(26515): toggleBluetooth - 
I/jxcore-log(26515): 
,I/jxcore-log(26515): toggleWiFi
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,I/jxcore-log(26515): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26515): 
,TIME-OUT KILL (timeout was 1800000ms)

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
,W/jxcore-log( 5688): Initializing JXcore engine
W/jxcore-log( 5688): JXcore engine is ready
,W/jxcore-log( 5688): Starting JXcore engine
,W/jxcore-log( 5688): Platform android,
W/jxcore-log( 5688): 
W/jxcore-log( 5688): Process ARCH arm
W/jxcore-log( 5688): 
,I/jxcore-log( 5688): JXcore Cordova bridge is ready!,
I/jxcore-log( 5688): 
W/jxcore-log( 5688): JXcore engine is started
,I/jxcore-log( 5688): Turning radios to true,
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): toggleBluetooth - ,
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): toggleWiFi,
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): my name is : DEV1878,
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): attempting to connect to test coordinator,
I/jxcore-log( 5688): 
I/jxcore-log( 5688): check test folder
I/jxcore-log( 5688): 
I/jxcore-log( 5688): found test : ./testFindPeers.js
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): found test : ./testReConnect.js
I/jxcore-log( 5688): 
I/jxcore-log( 5688): found test : ./testSendData.js
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Test app app.js loaded,
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
I/jxcore-log( 5688): LogCallback not set !!!!
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Client has connected to the server!,
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Start now : testFindPeers.js
I/jxcore-log( 5688): 
I/jxcore-log( 5688): stop tests now !
I/jxcore-log( 5688): 
I/jxcore-log( 5688): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 5688): 
I/jxcore-log( 5688): serverPort is 8876
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): StartBroadcasting started ok,
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}],
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}],
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Found peer : 08:EC:A9:50:76:27, peerAvailable: true,
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}],
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}],
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}],
,I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Found peer : F8:95:C7:87:3C:51, peerAvailable: true,
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}],
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true,
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}],
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}],
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): CoordinatorConnector disconnect called,
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): The client has disconnected!
I/jxcore-log( 5688): 
I/jxcore-log( 5688): stop tests now !
I/jxcore-log( 5688): 
I/jxcore-log( 5688): stop current!
I/jxcore-log( 5688): 
I/jxcore-log( 5688): testFindPeers stopped,
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): StopBroadcasting went ok,
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): turning Radios off
I/jxcore-log( 5688): 
I/jxcore-log( 5688): Turning radios to false
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): toggleBluetooth - 
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): toggleWiFi
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): 
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 5688): ,
,I/jxcore-log( 5688): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log( 5688): ,
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-N9005: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(10454): Initializing JXcore engine
,W/jxcore-log(10454): JXcore engine is ready
,W/jxcore-log(10454): Starting JXcore engine
,W/jxcore-log(10454): Platform android
W/jxcore-log(10454): 
W/jxcore-log(10454): Process ARCH arm
W/jxcore-log(10454): 
,I/jxcore-log(10454): JXcore Cordova bridge is ready!
I/jxcore-log(10454): 
W/jxcore-log(10454): JXcore engine is started
,I/jxcore-log(10454): Turning radios to true
I/jxcore-log(10454): 
,I/jxcore-log(10454): toggleBluetooth - 
I/jxcore-log(10454): 
,I/jxcore-log(10454): toggleWiFi
I/jxcore-log(10454): 
,I/jxcore-log(10454): my name is : DEV5153
I/jxcore-log(10454): 
,I/jxcore-log(10454): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(10454): 
,I/jxcore-log(10454): attempting to connect to test coordinator
I/jxcore-log(10454): 
,I/jxcore-log(10454): check test folder
I/jxcore-log(10454): 
,I/jxcore-log(10454): found test : ./testFindPeers.js
I/jxcore-log(10454): 
,I/jxcore-log(10454): found test : ./testReConnect.js
I/jxcore-log(10454): 
,I/jxcore-log(10454): found test : ./testSendData.js
I/jxcore-log(10454): 
,I/jxcore-log(10454): Test app app.js loaded
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): LogCallback not set !!!!
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Client has connected to the server!
I/jxcore-log(10454): 
,I/jxcore-log(10454): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20},
I/jxcore-log(10454): 
,I/jxcore-log(10454): Start now : testFindPeers.js
I/jxcore-log(10454): 
,I/jxcore-log(10454): stop tests now !
I/jxcore-log(10454): 
,I/jxcore-log(10454): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(10454): 
,I/jxcore-log(10454): serverPort is 8876
I/jxcore-log(10454): 
,I/jxcore-log(10454): StartBroadcasting started ok
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(10454): 
,I/jxcore-log(10454): CoordinatorConnector disconnect called
I/jxcore-log(10454): 
,I/jxcore-log(10454): The client has disconnected!
I/jxcore-log(10454): 
,I/jxcore-log(10454): stop tests now !
I/jxcore-log(10454): 
,I/jxcore-log(10454): stop current!
I/jxcore-log(10454): 
,I/jxcore-log(10454): testFindPeers stopped
I/jxcore-log(10454): 
,I/jxcore-log(10454): StopBroadcasting went ok
I/jxcore-log(10454): 
,I/jxcore-log(10454): turning Radios off
I/jxcore-log(10454): 
,I/jxcore-log(10454): Turning radios to false
I/jxcore-log(10454): 
,I/jxcore-log(10454): toggleBluetooth - 
I/jxcore-log(10454): 
,I/jxcore-log(10454): toggleWiFi
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(10454): ,
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(10454): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10454): 


motorola-Nexus 6: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(26333): Initializing JXcore engine,
W/jxcore-log(26333): JXcore engine is ready
,W/jxcore-log(26333): Starting JXcore engine
,W/jxcore-log(26333): Platform android
W/jxcore-log(26333): 
,W/jxcore-log(26333): Process ARCH arm
W/jxcore-log(26333): 
,I/jxcore-log(26333): JXcore Cordova bridge is ready!
I/jxcore-log(26333): 
,W/jxcore-log(26333): JXcore engine is started
,I/jxcore-log(26333): Turning radios to true
I/jxcore-log(26333): 
,I/jxcore-log(26333): toggleBluetooth - 
I/jxcore-log(26333): 
,I/jxcore-log(26333): toggleWiFi
I/jxcore-log(26333): 
,I/jxcore-log(26333): my name is : DEV4959
I/jxcore-log(26333): 
,I/jxcore-log(26333): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(26333): 
,I/jxcore-log(26333): attempting to connect to test coordinator
I/jxcore-log(26333): 
,I/jxcore-log(26333): check test folder
I/jxcore-log(26333): 
,I/jxcore-log(26333): found test : ./testFindPeers.js
I/jxcore-log(26333): 
,I/jxcore-log(26333): found test : ./testReConnect.js
I/jxcore-log(26333): 
,I/jxcore-log(26333): found test : ./testSendData.js
I/jxcore-log(26333): 
,I/jxcore-log(26333): Test app app.js loaded
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Client has connected to the server!
I/jxcore-log(26333): 
,I/jxcore-log(26333): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log(26333): 
I/jxcore-log(26333): Start now : testFindPeers.js
I/jxcore-log(26333): 
I/jxcore-log(26333): stop tests now !
I/jxcore-log(26333): 
,I/jxcore-log(26333): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(26333): 
,I/jxcore-log(26333): serverPort is 8876
I/jxcore-log(26333): 
,I/jxcore-log(26333): StartBroadcasting started ok
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log(26333): 
I/jxcore-log(26333): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log(26333): 
I/jxcore-log(26333): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log(26333): 
I/jxcore-log(26333): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(26333): 
,I/jxcore-log(26333): CoordinatorConnector disconnect called
I/jxcore-log(26333): 
I/jxcore-log(26333): The client has disconnected!
I/jxcore-log(26333): 
I/jxcore-log(26333): stop tests now !
I/jxcore-log(26333): 
I/jxcore-log(26333): stop current!
I/jxcore-log(26333): 
I/jxcore-log(26333): testFindPeers stopped
I/jxcore-log(26333): 
,I/jxcore-log(26333): StopBroadcasting went ok
I/jxcore-log(26333): 
I/jxcore-log(26333): turning Radios off
I/jxcore-log(26333): 
,I/jxcore-log(26333): Turning radios to false
I/jxcore-log(26333): 
,I/jxcore-log(26333): toggleBluetooth - 
I/jxcore-log(26333): 
,I/jxcore-log(26333): toggleWiFi
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,I/jxcore-log(26333): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(26333): 
,TIME-OUT KILL (timeout was 1800000ms)

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
--------- beginning of system,
--------- beginning of main
,W/jxcore-log(31070): Initializing JXcore engine
,W/jxcore-log(31070): JXcore engine is ready
,W/jxcore-log(31070): Starting JXcore engine,
,W/jxcore-log(31070): Platform android,
W/jxcore-log(31070): 
W/jxcore-log(31070): Process ARCH arm
W/jxcore-log(31070): 
,I/jxcore-log(31070): JXcore Cordova bridge is ready!,
I/jxcore-log(31070): 
W/jxcore-log(31070): JXcore engine is started
,I/jxcore-log(31070): Turning radios to true,
I/jxcore-log(31070): 
,I/jxcore-log(31070): toggleBluetooth - ,
I/jxcore-log(31070): 
,I/jxcore-log(31070): toggleWiFi,
I/jxcore-log(31070): 
,I/jxcore-log(31070): my name is : DEV6046,
I/jxcore-log(31070): 
I/jxcore-log(31070): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(31070): 
,I/jxcore-log(31070): attempting to connect to test coordinator,
I/jxcore-log(31070): 
I/jxcore-log(31070): check test folder
I/jxcore-log(31070): 
,I/jxcore-log(31070): found test : ./testFindPeers.js,
I/jxcore-log(31070): 
,I/jxcore-log(31070): found test : ./testReConnect.js,
I/jxcore-log(31070): 
,I/jxcore-log(31070): found test : ./testSendData.js,
I/jxcore-log(31070): 
,I/jxcore-log(31070): Test app app.js loaded,
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(31070): ,
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(31070): ,
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
,I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): ,
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,I/jxcore-log(31070): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(31070): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-A300FU: 
--------- beginning of main
,--------- beginning of system
,W/jxcore-log(19525): Initializing JXcore engine
W/jxcore-log(19525): JXcore engine is ready
,W/jxcore-log(19525): Starting JXcore engine
,W/jxcore-log(19525): Platform android
W/jxcore-log(19525): 
W/jxcore-log(19525): Process ARCH arm
W/jxcore-log(19525): 
,I/jxcore-log(19525): JXcore Cordova bridge is ready!
I/jxcore-log(19525): 
,W/jxcore-log(19525): JXcore engine is started
,I/jxcore-log(19525): Turning radios to true
I/jxcore-log(19525): 
,I/jxcore-log(19525): toggleBluetooth - 
I/jxcore-log(19525): 
,I/jxcore-log(19525): toggleWiFi
I/jxcore-log(19525): ,
,I/jxcore-log(19525): my name is : DEV4707,
I/jxcore-log(19525): 
I/jxcore-log(19525): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(19525): 
,I/jxcore-log(19525): attempting to connect to test coordinator,
I/jxcore-log(19525): 
I/jxcore-log(19525): check test folder
I/jxcore-log(19525): 
,I/jxcore-log(19525): found test : ./testFindPeers.js
I/jxcore-log(19525): 
,I/jxcore-log(19525): found test : ./testReConnect.js,
I/jxcore-log(19525): 
,I/jxcore-log(19525): found test : ./testSendData.js,
I/jxcore-log(19525): 
,I/jxcore-log(19525): Test app app.js loaded,
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Client has connected to the server!
I/jxcore-log(19525): 
,I/jxcore-log(19525): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log(19525): 
,I/jxcore-log(19525): Start now : testFindPeers.js
I/jxcore-log(19525): 
,I/jxcore-log(19525): stop tests now !
I/jxcore-log(19525): 
,I/jxcore-log(19525): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(19525): 
,I/jxcore-log(19525): serverPort is 8876
I/jxcore-log(19525): 
,I/jxcore-log(19525): StartBroadcasting started ok
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true,
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(19525): 
,I/jxcore-log(19525): CoordinatorConnector disconnect called
I/jxcore-log(19525): 
,I/jxcore-log(19525): The client has disconnected!
I/jxcore-log(19525): 
I/jxcore-log(19525): stop tests now !
I/jxcore-log(19525): 
I/jxcore-log(19525): stop current!
I/jxcore-log(19525): 
I/jxcore-log(19525): testFindPeers stopped
I/jxcore-log(19525): 
,I/jxcore-log(19525): StopBroadcasting went ok
I/jxcore-log(19525): 
I/jxcore-log(19525): turning Radios off
I/jxcore-log(19525): 
I/jxcore-log(19525): Turning radios to false
I/jxcore-log(19525): 
I/jxcore-log(19525): toggleBluetooth - 
I/jxcore-log(19525): 
,I/jxcore-log(19525): toggleWiFi
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(19525): ,
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(19525): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(19525): 


LGE-LG-D802: 
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,W/jxcore-log(20988): Initializing JXcore engine,
,W/jxcore-log(20988): JXcore engine is ready
,W/jxcore-log(20988): Starting JXcore engine
,W/jxcore-log(20988): Platform android
W/jxcore-log(20988): 
,W/jxcore-log(20988): Process ARCH arm
W/jxcore-log(20988): 
,I/jxcore-log(20988): JXcore Cordova bridge is ready!
I/jxcore-log(20988): 
,W/jxcore-log(20988): JXcore engine is started
,I/jxcore-log(20988): Turning radios to true
I/jxcore-log(20988): 
,I/jxcore-log(20988): toggleBluetooth - 
I/jxcore-log(20988): 
,I/jxcore-log(20988): toggleWiFi
I/jxcore-log(20988): 
,I/jxcore-log(20988): my name is : DEV1299
I/jxcore-log(20988): 
,I/jxcore-log(20988): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(20988): 
,I/jxcore-log(20988): attempting to connect to test coordinator
I/jxcore-log(20988): 
,I/jxcore-log(20988): check test folder
I/jxcore-log(20988): 
,I/jxcore-log(20988): found test : ./testFindPeers.js
I/jxcore-log(20988): 
,I/jxcore-log(20988): found test : ./testReConnect.js
I/jxcore-log(20988): 
,I/jxcore-log(20988): found test : ./testSendData.js
I/jxcore-log(20988): 
,I/jxcore-log(20988): Test app app.js loaded
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): LogCallback not set !!!!
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Client has connected to the server!
I/jxcore-log(20988): 
,I/jxcore-log(20988): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log(20988): 
,I/jxcore-log(20988): Start now : testFindPeers.js
I/jxcore-log(20988): 
,I/jxcore-log(20988): stop tests now !
I/jxcore-log(20988): 
,I/jxcore-log(20988): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(20988): 
,I/jxcore-log(20988): serverPort is 8876
I/jxcore-log(20988): 
,I/jxcore-log(20988): StartBroadcasting started ok
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV3530","peerIdentifier":"00:F4:6F:30:E0:6C","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV7671","peerIdentifier":"B4:CE:F6:AB:A4:6A","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV8143","peerIdentifier":"10:D3:8A:FB:85:D4","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV5824","peerIdentifier":"F4:F1:E1:5C:3B:E2","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV902","peerIdentifier":"80:01:84:8A:B3:68","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV6011","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV1517","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV5153","peerIdentifier":"E0:DB:10:1F:C9:5E","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV4165","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV6608","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV7258","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV3467","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV5772","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV7863","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV1878","peerIdentifier":"50:2E:6C:AC:21:50","peerAvailable":true}]
I/jxcore-log(20988): 
I/jxcore-log(20988): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV4707","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV4959","peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV4230","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): peerAvailabilityChanged [{"peerName":"DEV6470","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true}]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(20988): 
,I/jxcore-log(20988): CoordinatorConnector disconnect called
I/jxcore-log(20988): 
,I/jxcore-log(20988): The client has disconnected!
I/jxcore-log(20988): 
,I/jxcore-log(20988): stop tests now !
I/jxcore-log(20988): 
,I/jxcore-log(20988): stop current!
I/jxcore-log(20988): 
,I/jxcore-log(20988): testFindPeers stopped
I/jxcore-log(20988): 
,I/jxcore-log(20988): StopBroadcasting went ok
I/jxcore-log(20988): 
,I/jxcore-log(20988): turning Radios off
I/jxcore-log(20988): 
,I/jxcore-log(20988): Turning radios to false
I/jxcore-log(20988): 
,I/jxcore-log(20988): toggleBluetooth - 
I/jxcore-log(20988): 
,I/jxcore-log(20988): toggleWiFi
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
,I/jxcore-log(20988): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(20988): 
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
,W/jxcore-log( 2958): Initializing JXcore engine
W/jxcore-log( 2958): JXcore engine is ready
,W/jxcore-log( 2958): Starting JXcore engine
,W/jxcore-log( 2958): Platform android
W/jxcore-log( 2958): 
W/jxcore-log( 2958): Process ARCH arm
W/jxcore-log( 2958): 
,I/jxcore-log( 2958): JXcore Cordova bridge is ready!
I/jxcore-log( 2958): 
,W/jxcore-log( 2958): JXcore engine is started
,I/jxcore-log( 2958): Turning radios to true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): toggleBluetooth - 
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): toggleWiFi,
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): my name is : DEV5772,
I/jxcore-log( 2958): 
I/jxcore-log( 2958): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): attempting to connect to test coordinator
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): check test folder
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): found test : ./testFindPeers.js
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): found test : ./testReConnect.js
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): found test : ./testSendData.js,
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Test app app.js loaded,
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Client has connected to the server!
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Start now : testFindPeers.js
I/jxcore-log( 2958): 
I/jxcore-log( 2958): stop tests now !
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): serverPort is 8876
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): StartBroadcasting started ok
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}],
I/jxcore-log( 2958): 
I/jxcore-log( 2958): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true,
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true,
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): CoordinatorConnector disconnect called
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): The client has disconnected!
I/jxcore-log( 2958): 
I/jxcore-log( 2958): stop tests now !
I/jxcore-log( 2958): 
I/jxcore-log( 2958): stop current!
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): testFindPeers stopped
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): StopBroadcasting went ok
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): turning Radios off,
I/jxcore-log( 2958): 
I/jxcore-log( 2958): Turning radios to false
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): toggleBluetooth - 
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): toggleWiFi
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,I/jxcore-log( 2958): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 2958): 
,TIME-OUT KILL (timeout was 1800000ms)

samsung-SM-G900F: 
--------- beginning of main
--------- beginning of system
,W/jxcore-log(14590): Initializing JXcore engine
W/jxcore-log(14590): JXcore engine is ready
,W/jxcore-log(14590): Starting JXcore engine
,W/jxcore-log(14590): Platform android
W/jxcore-log(14590): 
W/jxcore-log(14590): Process ARCH arm
W/jxcore-log(14590): 
,I/jxcore-log(14590): JXcore Cordova bridge is ready!
I/jxcore-log(14590): 
,W/jxcore-log(14590): JXcore engine is started
,I/jxcore-log(14590): Turning radios to true
I/jxcore-log(14590): 
,I/jxcore-log(14590): toggleBluetooth - 
I/jxcore-log(14590): 
,I/jxcore-log(14590): toggleWiFi
I/jxcore-log(14590): 
,I/jxcore-log(14590): my name is : DEV7258
I/jxcore-log(14590): 
I/jxcore-log(14590): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(14590): 
,I/jxcore-log(14590): attempting to connect to test coordinator
I/jxcore-log(14590): 
,I/jxcore-log(14590): check test folder
I/jxcore-log(14590): 
,I/jxcore-log(14590): found test : ./testFindPeers.js
I/jxcore-log(14590): 
,I/jxcore-log(14590): found test : ./testReConnect.js
I/jxcore-log(14590): 
,I/jxcore-log(14590): found test : ./testSendData.js
I/jxcore-log(14590): 
,I/jxcore-log(14590): Test app app.js loaded
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): LogCallback not set !!!!
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Client has connected to the server!
I/jxcore-log(14590): 
,I/jxcore-log(14590): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log(14590): 
,I/jxcore-log(14590): Start now : testFindPeers.js
I/jxcore-log(14590): 
,I/jxcore-log(14590): stop tests now !
I/jxcore-log(14590): 
I/jxcore-log(14590): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(14590): 
I/jxcore-log(14590): serverPort is 8876
I/jxcore-log(14590): 
,I/jxcore-log(14590): StartBroadcasting started ok
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:76:27","peerName":"DEV6608","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(14590): 
,I/jxcore-log(14590): CoordinatorConnector disconnect called
I/jxcore-log(14590): 
,I/jxcore-log(14590): The client has disconnected!
I/jxcore-log(14590): 
,I/jxcore-log(14590): stop tests now !
I/jxcore-log(14590): 
,I/jxcore-log(14590): stop current!
I/jxcore-log(14590): 
,I/jxcore-log(14590): testFindPeers stopped
I/jxcore-log(14590): 
,I/jxcore-log(14590): StopBroadcasting went ok
I/jxcore-log(14590): 
,I/jxcore-log(14590): turning Radios off
I/jxcore-log(14590): 
,I/jxcore-log(14590): Turning radios to false
I/jxcore-log(14590): 
,I/jxcore-log(14590): toggleBluetooth - 
I/jxcore-log(14590): 
,I/jxcore-log(14590): toggleWiFi
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object],
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log(14590): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(14590): 


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
--------- beginning of main,
--------- beginning of system
,W/jxcore-log(10337): Initializing JXcore engine
W/jxcore-log(10337): JXcore engine is ready
,W/jxcore-log(10337): Starting JXcore engine
,W/jxcore-log(10337): Platform android
W/jxcore-log(10337): 
W/jxcore-log(10337): Process ARCH arm
W/jxcore-log(10337): 
,I/jxcore-log(10337): JXcore Cordova bridge is ready!
I/jxcore-log(10337): 
,W/jxcore-log(10337): JXcore engine is started
,I/jxcore-log(10337): Turning radios to true
I/jxcore-log(10337): 
,I/jxcore-log(10337): toggleBluetooth - 
I/jxcore-log(10337): 
,I/jxcore-log(10337): toggleWiFi,
I/jxcore-log(10337): 
,I/jxcore-log(10337): my name is : DEV6608,
I/jxcore-log(10337): 
I/jxcore-log(10337): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(10337): 
,I/jxcore-log(10337): attempting to connect to test coordinator,
I/jxcore-log(10337): 
,I/jxcore-log(10337): check test folder
I/jxcore-log(10337): 
,I/jxcore-log(10337): found test : ./testFindPeers.js
I/jxcore-log(10337): 
,I/jxcore-log(10337): found test : ./testReConnect.js,
I/jxcore-log(10337): 
,I/jxcore-log(10337): found test : ./testSendData.js
I/jxcore-log(10337): 
,I/jxcore-log(10337): Test app app.js loaded
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): LogCallback not set !!!!
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Client has connected to the server!
I/jxcore-log(10337): 
,I/jxcore-log(10337): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log(10337): 
,I/jxcore-log(10337): Start now : testFindPeers.js
I/jxcore-log(10337): 
I/jxcore-log(10337): stop tests now !
I/jxcore-log(10337): 
,I/jxcore-log(10337): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(10337): 
,I/jxcore-log(10337): serverPort is 8876
I/jxcore-log(10337): 
,I/jxcore-log(10337): StartBroadcasting started ok
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:51:18:22","peerName":"DEV5772","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"80:01:84:8A:B3:68","peerName":"DEV902","peerAvailable":true}],
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : 80:01:84:8A:B3:68, peerAvailable: true,
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:9D:93:0B","peerName":"DEV1299","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"B4:CE:F6:AB:A4:6A","peerName":"DEV7671","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"F4:F1:E1:5C:3B:E2","peerName":"DEV5824","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"44:80:EB:7B:5A:05","peerName":"DEV4230","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"34:FC:EF:11:AE:67","peerName":"DEV6011","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:37:96:AB","peerName":"DEV3467","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"00:F4:6F:30:E0:6C","peerName":"DEV3530","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"10:D3:8A:FB:85:D4","peerName":"DEV8143","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:3C:51","peerName":"DEV1517","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"F8:CF:C5:D9:E5:61","peerName":"DEV4959","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:1F:C9:5E","peerName":"DEV5153","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"7C:F9:0E:34:8A:A0","peerName":"DEV4165","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"50:2E:6C:AC:21:50","peerName":"DEV1878","peerAvailable":true}],
I/jxcore-log(10337): 
I/jxcore-log(10337): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"08:EC:A9:50:75:41","peerName":"DEV4707","peerAvailable":true}]
I/jxcore-log(10337): 
I/jxcore-log(10337): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"F8:95:C7:87:85:54","peerName":"DEV6470","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"B0:C5:59:3F:75:69","peerName":"DEV7258","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): peerAvailabilityChanged [{"peerIdentifier":"E0:DB:10:14:E2:C0","peerName":"DEV7863","peerAvailable":true}]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(10337): 
,I/jxcore-log(10337): CoordinatorConnector disconnect called
I/jxcore-log(10337): 
I/jxcore-log(10337): The client has disconnected!
I/jxcore-log(10337): 
I/jxcore-log(10337): stop tests now !
I/jxcore-log(10337): 
I/jxcore-log(10337): stop current!
I/jxcore-log(10337): 
,I/jxcore-log(10337): testFindPeers stopped
I/jxcore-log(10337): 
,I/jxcore-log(10337): StopBroadcasting went ok
I/jxcore-log(10337): 
,I/jxcore-log(10337): turning Radios off
I/jxcore-log(10337): 
,I/jxcore-log(10337): Turning radios to false
I/jxcore-log(10337): 
,I/jxcore-log(10337): toggleBluetooth - ,
I/jxcore-log(10337): 
,I/jxcore-log(10337): toggleWiFi
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,I/jxcore-log(10337): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10337): 
,TIME-OUT KILL (timeout was 1800000ms)

HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log(10198): Initializing JXcore engine
,W/jxcore-log(10198): JXcore engine is ready
,W/jxcore-log(10198): Starting JXcore engine
,W/jxcore-log(10198): Platform android
W/jxcore-log(10198): 
,W/jxcore-log(10198): Process ARCH arm
W/jxcore-log(10198): 
,I/jxcore-log(10198): JXcore Cordova bridge is ready!
I/jxcore-log(10198): 
,W/jxcore-log(10198): JXcore engine is started
,I/jxcore-log(10198): Turning radios to true
I/jxcore-log(10198): 
,I/jxcore-log(10198): toggleBluetooth - 
I/jxcore-log(10198): 
,I/jxcore-log(10198): toggleWiFi
I/jxcore-log(10198): 
,I/jxcore-log(10198): my name is : DEV902
I/jxcore-log(10198): 
,I/jxcore-log(10198): Connect to  address : 192.168.1.150 type: override
I/jxcore-log(10198): 
,I/jxcore-log(10198): attempting to connect to test coordinator
I/jxcore-log(10198): 
,I/jxcore-log(10198): check test folder
I/jxcore-log(10198): 
,I/jxcore-log(10198): found test : ./testFindPeers.js
I/jxcore-log(10198): 
,I/jxcore-log(10198): found test : ./testReConnect.js
I/jxcore-log(10198): 
,I/jxcore-log(10198): found test : ./testSendData.js
I/jxcore-log(10198): 
,I/jxcore-log(10198): Test app app.js loaded
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): LogCallback not set !!!!
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Client has connected to the server!
I/jxcore-log(10198): 
,I/jxcore-log(10198): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log(10198): 
,I/jxcore-log(10198): Start now : testFindPeers.js
I/jxcore-log(10198): 
,I/jxcore-log(10198): stop tests now !
I/jxcore-log(10198): 
,I/jxcore-log(10198): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log(10198): 
,I/jxcore-log(10198): serverPort is 8876
I/jxcore-log(10198): 
,I/jxcore-log(10198): StartBroadcasting started ok
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV3530","peerIdentifier":"00:F4:6F:30:E0:6C","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV7671","peerIdentifier":"B4:CE:F6:AB:A4:6A","peerAvailable":true}]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Found peer : B4:CE:F6:AB:A4:6A, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV1299","peerIdentifier":"34:FC:EF:9D:93:0B","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV6608","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV5824","peerIdentifier":"F4:F1:E1:5C:3B:E2","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV8143","peerIdentifier":"10:D3:8A:FB:85:D4","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV1517","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV4707","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV6470","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV4230","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true}]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV4959","peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV7258","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true}]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV7863","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true}]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV5772","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV3467","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true}]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV1878","peerIdentifier":"50:2E:6C:AC:21:50","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV5153","peerIdentifier":"E0:DB:10:1F:C9:5E","peerAvailable":true}]
I/jxcore-log(10198): 
I/jxcore-log(10198): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): peerAvailabilityChanged [{"peerName":"DEV4165","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true}]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log(10198): 
,I/jxcore-log(10198): CoordinatorConnector disconnect called
I/jxcore-log(10198): 
,I/jxcore-log(10198): The client has disconnected!
I/jxcore-log(10198): 
I/jxcore-log(10198): stop tests now !
I/jxcore-log(10198): 
,I/jxcore-log(10198): stop current!
I/jxcore-log(10198): 
,I/jxcore-log(10198): testFindPeers stopped
I/jxcore-log(10198): 
,I/jxcore-log(10198): StopBroadcasting went ok
I/jxcore-log(10198): 
,I/jxcore-log(10198): turning Radios off
I/jxcore-log(10198): 
I/jxcore-log(10198): Turning radios to false
I/jxcore-log(10198): 
,I/jxcore-log(10198): toggleBluetooth - 
I/jxcore-log(10198): 
,I/jxcore-log(10198): toggleWiFi
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
,I/jxcore-log(10198): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log(10198): 
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
--------- beginning of /dev/log/main
,--------- beginning of /dev/log/system
,TIME-OUT KILL (timeout was 1800000ms)

HTC-HTC Desire 820: 
--------- beginning of /dev/log/main
--------- beginning of /dev/log/system
,W/jxcore-log( 7947): Initializing JXcore engine
,W/jxcore-log( 7947): JXcore engine is ready
,W/jxcore-log( 7947): Starting JXcore engine
,W/jxcore-log( 7947): Platform android
W/jxcore-log( 7947): 
,W/jxcore-log( 7947): Process ARCH arm
W/jxcore-log( 7947): 
,I/jxcore-log( 7947): JXcore Cordova bridge is ready!
I/jxcore-log( 7947): 
W/jxcore-log( 7947): JXcore engine is started
,I/jxcore-log( 7947): Turning radios to true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): toggleBluetooth - 
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): toggleWiFi
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): my name is : DEV7671
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Connect to  address : 192.168.1.150 type: override
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): attempting to connect to test coordinator
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): check test folder
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): found test : ./testFindPeers.js
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): found test : ./testReConnect.js
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): found test : ./testSendData.js
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Test app app.js loaded
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): LogCallback not set !!!!
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Client has connected to the server!
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): command received : {"command":"start","testName":"testFindPeers.js","testData":"{\"timeout\":\"1200000\",\"rounds\":\"1\",\"dataTimeout\":\"5000\",\"conReTryTimeout\":\"2000\",\"conReTryCount\":\"3\"}","devices":20}
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Start now : testFindPeers.js
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): stop tests now !
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): testFindPeers created {"timeout":"1200000","rounds":"1","dataTimeout":"5000","conReTryTimeout":"2000","conReTryCount":"3"}
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): serverPort is 8876
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): StartBroadcasting started ok
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV5772","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : 7C:F9:0E:51:18:22, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV5824","peerIdentifier":"F4:F1:E1:5C:3B:E2","peerAvailable":true}]
I/jxcore-log( 7947): 
I/jxcore-log( 7947): Found peer : F4:F1:E1:5C:3B:E2, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV1299","peerIdentifier":"34:FC:EF:9D:93:0B","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : 34:FC:EF:9D:93:0B, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV8143","peerIdentifier":"10:D3:8A:FB:85:D4","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : 10:D3:8A:FB:85:D4, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV3467","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true}]
I/jxcore-log( 7947): 
I/jxcore-log( 7947): Found peer : 7C:F9:0E:37:96:AB, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV902","peerIdentifier":"80:01:84:8A:B3:68","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : 80:01:84:8A:B3:68, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV6608","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true}]
I/jxcore-log( 7947): 
I/jxcore-log( 7947): Found peer : 08:EC:A9:50:76:27, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV3530","peerIdentifier":"00:F4:6F:30:E0:6C","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : 00:F4:6F:30:E0:6C, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV1517","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true}]
I/jxcore-log( 7947): 
I/jxcore-log( 7947): Found peer : F8:95:C7:87:3C:51, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV4959","peerIdentifier":"F8:CF:C5:D9:E5:61","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : F8:CF:C5:D9:E5:61, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV7258","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : B0:C5:59:3F:75:69, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV1878","peerIdentifier":"50:2E:6C:AC:21:50","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : 50:2E:6C:AC:21:50, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV4707","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : 08:EC:A9:50:75:41, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV6470","peerIdentifier":"F8:95:C7:87:85:54","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : F8:95:C7:87:85:54, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV4165","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : 7C:F9:0E:34:8A:A0, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV7863","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true}]
I/jxcore-log( 7947): 
I/jxcore-log( 7947): Found peer : E0:DB:10:14:E2:C0, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV4230","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : 44:80:EB:7B:5A:05, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV6011","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : 34:FC:EF:11:AE:67, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): peerAvailabilityChanged [{"peerName":"DEV5153","peerIdentifier":"E0:DB:10:1F:C9:5E","peerAvailable":true}]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Found peer : E0:DB:10:1F:C9:5E, peerAvailable: true
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): CoordinatorConnector disconnect called
I/jxcore-log( 7947): 
I/jxcore-log( 7947): The client has disconnected!
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): stop tests now !
I/jxcore-log( 7947): 
I/jxcore-log( 7947): stop current!
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): testFindPeers stopped
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): StopBroadcasting went ok
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): turning Radios off
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Turning radios to false
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): toggleBluetooth - 
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): toggleWiFi
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 
,TIME-OUT KILL (timeout was 1800000ms),I/jxcore-log( 7947): Error:{"type":"connect_error","data":{"type":"TransportError","description":503}} : connect_error : [object Object]
I/jxcore-log( 7947): 


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

Android  DEV5772 added : 2.053 sec., device count 1

got connection 

Android  DEV902 added : 2.549 sec., device count 2

got connection 

Android  DEV7671 added : 2.868 sec., device count 3

got connection 

Android  DEV6608 added : 3.114 sec., device count 4

got connection 

Android  DEV6470 added : 4.025 sec., device count 5

got connection 

Android  DEV7258 added : 4.278 sec., device count 6

got connection 

Android  DEV5153 added : 13.104 sec., device count 7

got connection 

Android  DEV4959 added : 13.23 sec., device count 8

got connection 

Android  DEV1299 added : 21.69 sec., device count 9

got connection 

Android  DEV4707 added : 23.894 sec., device count 10

got connection 

Android  DEV1878 added : 30.262 sec., device count 11

got connection 

Android  DEV3530 added : 47.392 sec., device count 12

got connection 

Android  DEV1854 added : 49.272 sec., device count 13

got connection 

Android  DEV8143 added : 52.562 sec., device count 14

got connection 

Android  DEV1517 added : 53.321 sec., device count 15

got connection 

Android  DEV5824 added : 87.347 sec., device count 16

got connection 

Android  DEV6011 added : 104.377 sec., device count 17

got connection 

Android  DEV3467 added : 152.483 sec., device count 18

got connection 

Android  DEV4165 added : 153.96 sec., device count 19

got connection 

Android  DEV7863 added : 155.39 sec., device count 20

got connection 

Android  DEV4230 added : 163.962 sec., device count 21

-------------- We got wait done, now starting the testing process ------------------

-----Android start testing now with 21 devices.

start test[0] with 21 devices.


 
Run IS script aborted
 
[0;31mexecution aborted
 [0m

```

