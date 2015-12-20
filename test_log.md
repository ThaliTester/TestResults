#### Test 506502785b2d2b2 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2015-12-20T02:44:38.009Z - info: listening on *:3000

2015-12-20T02:44:38.821Z - debug: Device presented: samsung-SM-A300FU_PT6052 (android) perftest socket:0

2015-12-20T02:44:38.827Z - info: Setting start timeout to: 120000 (android)

2015-12-20T02:44:38.834Z - debug: Device presented: samsung-SM-A500FU_PT2008 (android) perftest socket:1

2015-12-20T02:44:39.017Z - debug: Device presented: LGE-LG-D722_PT1450 (android) perftest socket:3

2015-12-20T02:44:39.035Z - debug: Device presented: LGE-LG-H815_PT8343 (android) perftest socket:5

2015-12-20T02:44:39.058Z - debug: Device presented: Apple-Iphone5-1_PT1975 (ios) perftest socket:4

2015-12-20T02:44:39.059Z - info: Setting start timeout to: 120000 (ios)

2015-12-20T02:44:39.100Z - debug: Device presented: Apple-IpadAir2-1_PT5083 (ios) perftest socket:2

2015-12-20T02:44:39.537Z - debug: Device presented: motorola-XT1072_PT5963 (android) perftest socket:6

2015-12-20T02:44:41.749Z - debug: Device presented: samsung-SM-N910C_PT2703 (android) perftest socket:7

2015-12-20T02:44:41.922Z - debug: Device presented: samsung-SM-G900F_PT6125 (android) perftest socket:8

2015-12-20T02:44:42.057Z - debug: Device presented: Apple-Iphone6-1_PT27 (ios) perftest socket:9

2015-12-20T02:44:42.243Z - debug: Device presented: samsung-SM-A500FU_PT9057 (android) perftest socket:10

2015-12-20T02:44:42.466Z - debug: Device presented: samsung-SM-G900F_PT1824 (android) perftest socket:11

2015-12-20T02:44:42.481Z - debug: Device presented: HTC-HTC One M8s_PT5335 (android) perftest socket:12

2015-12-20T02:44:42.644Z - debug: Device presented: Apple-Iphone5s-1_PT7946 (ios) perftest socket:13

2015-12-20T02:44:42.645Z - info: Required number of devices presented

2015-12-20T02:44:42.649Z - info: Starting perf test run for platform: ios

2015-12-20T02:44:42.650Z - info: Using devices:

2015-12-20T02:44:42.651Z - info: Apple-Iphone5-1_PT1975

2015-12-20T02:44:42.652Z - info: Apple-IpadAir2-1_PT5083

2015-12-20T02:44:42.654Z - info: Apple-Iphone6-1_PT27

2015-12-20T02:44:42.654Z - info: Apple-Iphone5s-1_PT7946

2015-12-20T02:44:42.658Z - info: Starting test: with 4 devices (ios)

2015-12-20T02:44:42.852Z - debug: Device presented: LGE-Nexus 5_PT3882 (android) perftest socket:14

2015-12-20T02:44:42.890Z - debug: Device presented: samsung-SM-A300FU_PT1380 (android) perftest socket:15

2015-12-20T02:44:42.952Z - debug: Device presented: LGE-LG-D855_PT8208 (android) perftest socket:16

2015-12-20T02:45:07.251Z - debug: Device presented: motorola-XT1039_PT2688 (android) perftest socket:17

2015-12-20T02:45:08.212Z - debug: Socket disconnected: transport close 17 (motorola-XT1039_PT2688)

2015-12-20T02:46:38.844Z - info: Start timeout elapsed for platform: android

2015-12-20T02:46:38.845Z - info: Starting perf test run for platform: android

2015-12-20T02:46:38.847Z - info: Using devices:

2015-12-20T02:46:38.848Z - info: samsung-SM-A300FU_PT6052

2015-12-20T02:46:38.849Z - info: samsung-SM-A500FU_PT2008

2015-12-20T02:46:38.850Z - info: LGE-LG-D722_PT1450

2015-12-20T02:46:38.851Z - info: LGE-LG-H815_PT8343

2015-12-20T02:46:38.852Z - info: motorola-XT1072_PT5963

2015-12-20T02:46:38.853Z - info: samsung-SM-N910C_PT2703

2015-12-20T02:46:38.855Z - info: samsung-SM-G900F_PT6125

2015-12-20T02:46:38.855Z - info: samsung-SM-A500FU_PT9057

2015-12-20T02:46:38.857Z - info: samsung-SM-G900F_PT1824

2015-12-20T02:46:38.858Z - info: HTC-HTC One M8s_PT5335

2015-12-20T02:46:38.859Z - info: LGE-Nexus 5_PT3882

2015-12-20T02:46:38.860Z - info: samsung-SM-A300FU_PT1380

2015-12-20T02:46:38.861Z - info: LGE-LG-D855_PT8208

2015-12-20T02:46:38.862Z - info: motorola-XT1039_PT2688

2015-12-20T02:46:38.864Z - info: Starting test: with 14 devices (android)

2015-12-20T02:46:39.083Z - info: Start timeout elapsed for platform: ios

2015-12-20T02:46:39.084Z - info: Tests for ios already running or completed

2015-12-20T02:48:35.675Z - debug: Socket disconnected: ping timeout 6 (motorola-XT1072_PT5963)

2015-12-20T02:49:28.064Z - debug: Socket disconnected: ping timeout 7 (samsung-SM-N910C_PT2703)

2015-12-20T02:49:50.754Z - debug: Socket disconnected: ping timeout 0 (samsung-SM-A300FU_PT6052)

2015-12-20T02:49:53.504Z - debug: Socket disconnected: ping timeout 10 (samsung-SM-A500FU_PT9057)

2015-12-20T02:50:03.380Z - debug: Socket disconnected: ping timeout 13 (Apple-Iphone5s-1_PT7946)

2015-12-20T02:50:29.857Z - debug: Socket disconnected: ping timeout 9 (Apple-Iphone6-1_PT27)

2015-12-20T02:50:54.485Z - debug: Device presented: Apple-Iphone6-1_PT27 (ios) perftest socket:18

2015-12-20T02:50:54.488Z - info: Updating existing device: Apple-Iphone6-1_PT27 (f7795c87-a1f7-41cf-b0e0-4aa33fb21fa2)

2015-12-20T02:51:56.135Z - debug: Socket disconnected: ping timeout 3 (LGE-LG-D722_PT1450)

2015-12-20T02:52:01.512Z - debug: Socket disconnected: ping timeout 12 (HTC-HTC One M8s_PT5335)

2015-12-20T02:53:13.977Z - debug: Socket disconnected: ping timeout 4 (Apple-Iphone5-1_PT1975)

2015-12-20T02:53:51.464Z - debug: Device presented: LGE-LG-D855_PT8208 (android) perftest socket:19

2015-12-20T02:53:51.466Z - info: Updating existing device: LGE-LG-D855_PT8208 (509095c4-edeb-4a3b-97fb-10206765d646)

2015-12-20T02:54:32.731Z - debug: Socket disconnected: ping timeout 16 (LGE-LG-D855_PT8208)

2015-12-20T03:01:22.928Z - info: Received results for {"name:":"Apple-Iphone6-1_PT27","time":999994,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone5-1_PT1975.nu3zFw==","time":3688,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT5083.BRI7qQ==","time":3383,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7946.2ECkqQ==","time":5012,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1_PT27 ios (4 left)

2015-12-20T03:01:22.960Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT5083","time":1000042,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone6-1_PT27.Ee1r/w==","time":4052,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT1975.nu3zFw==","time":3696,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7946.2ECkqQ==","time":3821,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1_PT5083 ios (3 left)

2015-12-20T03:03:19.102Z - info: Received results for {"name:":"samsung-SM-A300FU_PT1380","time":1000077,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":1634,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":29395,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":9804,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":71226,"result":"Connection to peer [58:3F:54:73:64:C0 LGE-LG-D855_PT8208] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"F8:95:C7:87:85:54","time":0,"result":"Fail"}]} samsung-SM-A300FU_PT1380 android (14 left)

2015-12-20T03:03:19.117Z - info: Received results for {"name:":"samsung-SM-A500FU_PT2008","time":1000087,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"}]} samsung-SM-A500FU_PT2008 android (13 left)

2015-12-20T03:03:19.296Z - info: Received results for {"name:":"samsung-SM-G900F_PT1824","time":1000189,"result":"TIMEOUT","sendList":[{"name":"90:E7:C4:F6:69:77","time":2825,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":2141,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":4670,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":30440,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":109983,"result":"Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"E0:DB:10:14:E2:C0","time":115345,"result":"Connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT2703] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:34:8A:A0","time":115341,"result":"Connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT6125] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"F8:95:C7:87:3C:51","time":115298,"result":"Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT8343] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"08:EC:A9:50:75:41","time":58849,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":7119,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":90718,"result":"Connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT3882] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0}]} samsung-SM-G900F_PT1824 android (12 left)

2015-12-20T03:03:19.570Z - info: Received results for {"name:":"LGE-LG-H815_PT8343","time":1000101,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":4125,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":5805,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3113,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":67038,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":100699,"result":"Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"}]} LGE-LG-H815_PT8343 android (11 left)

2015-12-20T03:03:19.720Z - info: Received results for {"name:":"LGE-Nexus 5_PT3882","time":1000179,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:34:8A:A0","time":3619,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":5608,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":5599,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":105278,"result":"Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT1450] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:37:96:AB","time":173546,"result":"Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT9057] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"08:EC:A9:50:76:27","time":112237,"result":"Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:51:18:22","time":4098,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":107048,"result":"Connection to peer [B0:C5:59:3F:75:69 B0:C5:59:3F:75:69] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0}]} LGE-Nexus 5_PT3882 android (10 left)

2015-12-20T03:03:21.317Z - info: Received results for {"name:":"LGE-LG-D855_PT8208","time":1000106,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":5751,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":2549,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":4304,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":4597,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":72372,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":5015,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":91636,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":6646,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":106664,"result":"Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"F8:95:C7:87:85:54","time":2179,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":85400,"result":"Connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT3882] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0}]} LGE-LG-D855_PT8208 android (9 left)

2015-12-20T03:03:21.932Z - info: Received results for {"name:":"samsung-SM-G900F_PT6125","time":1000163,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":1906,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":2115,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":3343,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":90024,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":87289,"result":"Connection to peer [34:FC:EF:11:AE:67 LGE-Nexus 5_PT3882] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"90:E7:C4:F6:69:77","time":6757,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":6131,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":115317,"result":"Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT6052] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"F8:95:C7:87:3C:51","time":29521,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":4607,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":115299,"result":"Connection to peer [B0:C5:59:3F:75:69 samsung-SM-G900F_PT1824] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0}]} samsung-SM-G900F_PT6125 android (8 left)

2015-12-20T03:04:42.668Z - info: server timeout for test: testSendData.js (ios)

2015-12-20T03:04:42.673Z - info: All test data retrieved for testSendData.js (ios)

2015-12-20T03:04:42.676Z - info: No results from [object Object]

2015-12-20T03:04:42.680Z - info: No results from [object Object]

2015-12-20T03:04:42.682Z - info: Continuing to next test: testFindPeers.js

2015-12-20T03:04:42.683Z - info: Starting test: with 4 devices (ios)

2015-12-20T03:04:43.896Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT5083","time":32,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT27.Ee1r/w==","peerAvailable":true,"time":31}]} Apple-IpadAir2-1_PT5083 ios (4 left)

2015-12-20T03:04:44.153Z - info: Received results for {"name:":"Apple-Iphone6-1_PT27","time":955,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1_PT1975.nu3zFw==","peerAvailable":true,"time":954}]} Apple-Iphone6-1_PT27 ios (3 left)

2015-12-20T03:06:38.866Z - info: server timeout for test: testSendData.js (android)

2015-12-20T03:06:38.868Z - info: All test data retrieved for testSendData.js (android)

2015-12-20T03:06:38.871Z - info: No results from [object Object]

2015-12-20T03:06:38.873Z - info: No results from [object Object]

2015-12-20T03:06:38.875Z - info: No results from [object Object]

2015-12-20T03:06:38.876Z - info: No results from [object Object]

2015-12-20T03:06:38.878Z - info: No results from [object Object]

2015-12-20T03:06:38.879Z - info: No results from [object Object]

2015-12-20T03:06:38.882Z - info: No results from [object Object]

2015-12-20T03:06:38.884Z - info: Continuing to next test: testFindPeers.js

2015-12-20T03:06:38.885Z - info: Starting test: with 14 devices (android)

2015-12-20T03:06:59.355Z - info: Received results for {"name:":"LGE-Nexus 5_PT3882","time":20232,"result":"OK","peersList":[{"peerName":"samsung-SM-G900F_PT1824","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":20226}]} LGE-Nexus 5_PT3882 android (14 left)

2015-12-20T03:07:09.214Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1_PT5083)

2015-12-20T03:07:09.226Z - debug: Socket disconnected: transport close 18 (Apple-Iphone6-1_PT27)

2015-12-20T03:10:51.542Z - debug: Socket disconnected: transport close 14 (LGE-Nexus 5_PT3882)

2015-12-20T03:10:55.297Z - debug: Socket disconnected: transport close 5 (LGE-LG-H815_PT8343)

2015-12-20T03:10:56.469Z - debug: Socket disconnected: transport close 11 (samsung-SM-G900F_PT1824)

2015-12-20T03:10:58.721Z - debug: Socket disconnected: transport close 1 (samsung-SM-A500FU_PT2008)

2015-12-20T03:11:56.248Z - debug: Socket disconnected: transport close 15 (samsung-SM-A300FU_PT1380)

2015-12-20T03:12:33.923Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F_PT6125)

2015-12-20T03:13:32.326Z - info: Received results for {"name:":"LGE-LG-D855_PT8208","time":412858,"result":"OK","peersList":[{"peerName":"samsung-SM-G900F_PT1824","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":false,"time":412856}]} LGE-LG-D855_PT8208 android (13 left)

2015-12-20T03:15:09.514Z - debug: Socket disconnected: transport close 19 (LGE-LG-D855_PT8208)


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : Error: Command failed: true
Getting the list of iOS devices 
Deploying iOS test app 
uninstalling the application 
installing the application 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGH8153b36be34 app:com.test.thalitest code:0 
child process exited with code 0 on device LGH8153b36be34 
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Error! Unexpected exit on device 09a9416e0297d102 app:com.test.thalitest code:0 
child process exited with code 0 on device 09a9416e0297d102 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device c5afcdcb app:com.test.thalitest code:null 
child process exited with code null on device c5afcdcb 
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:null 
child process exited with code null on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/506502785b2d2b2_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




