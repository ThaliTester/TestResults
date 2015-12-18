#### Test 50650278bcecc5c Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2015-12-18T17:56:20.809Z - info: listening on *:3000

2015-12-18T17:56:21.525Z - debug: Device presented: HTC-HTC One M8s_PT3565 (android) perftest socket:1

2015-12-18T17:56:21.530Z - info: Setting start timeout to: 120000 (android)

2015-12-18T17:56:21.933Z - debug: Device presented: samsung-SM-N910C_PT6460 (android) perftest socket:3

2015-12-18T17:56:21.986Z - debug: Device presented: LGE-Nexus 5_PT5924 (android) perftest socket:4

2015-12-18T17:56:21.990Z - debug: Device presented: samsung-SM-G900F_PT8280 (android) perftest socket:2

2015-12-18T17:56:22.897Z - debug: Device presented: samsung-SM-G900F_PT633 (android) perftest socket:5

2015-12-18T17:56:23.082Z - debug: Device presented: samsung-SM-A300FU_PT5572 (android) perftest socket:6

2015-12-18T17:56:23.346Z - debug: Device presented: samsung-SM-A500FU_PT1532 (android) perftest socket:8

2015-12-18T17:56:23.385Z - debug: Device presented: Apple-Iphone5-1_PT4784 (ios) perftest socket:7

2015-12-18T17:56:23.387Z - info: Setting start timeout to: 120000 (ios)

2015-12-18T17:56:23.672Z - debug: Device presented: Apple-Iphone5s-1_PT7811 (ios) perftest socket:0

2015-12-18T17:56:24.118Z - debug: Device presented: motorola-XT1072_PT598 (android) perftest socket:9

2015-12-18T17:56:24.173Z - debug: Device presented: samsung-SM-A300FU_PT8506 (android) perftest socket:10

2015-12-18T17:56:24.586Z - debug: Device presented: LGE-LG-H815_PT9219 (android) perftest socket:11

2015-12-18T17:56:24.773Z - debug: Device presented: samsung-SM-A500FU_PT3826 (android) perftest socket:12

2015-12-18T17:56:25.080Z - debug: Device presented: LGE-LG-D722_PT8213 (android) perftest socket:13

2015-12-18T17:56:25.336Z - debug: Device presented: LGE-LG-D855_PT589 (android) perftest socket:14

2015-12-18T17:56:25.394Z - debug: Device presented: Apple-Iphone6-1_PT892 (ios) perftest socket:15

2015-12-18T17:56:25.947Z - debug: Device presented: Apple-IpadAir2-1_PT9737 (ios) perftest socket:16

2015-12-18T17:56:25.948Z - info: Required number of devices presented

2015-12-18T17:56:25.952Z - info: Starting perf test run for platform: ios

2015-12-18T17:56:25.953Z - info: Using devices:

2015-12-18T17:56:25.954Z - info: Apple-Iphone5-1_PT4784

2015-12-18T17:56:25.956Z - info: Apple-Iphone5s-1_PT7811

2015-12-18T17:56:25.957Z - info: Apple-Iphone6-1_PT892

2015-12-18T17:56:25.957Z - info: Apple-IpadAir2-1_PT9737

2015-12-18T17:56:25.961Z - info: Setting: (ios) 4

2015-12-18T17:56:25.963Z - debug:  name=testSendData.js, serverTimeout=1200000, timeout=1000000, rounds=1, dataTimeout=20000, dataAmount=100000, conReTryTimeout=5000, conReTryCount=5, peerCount=4

2015-12-18T17:56:29.813Z - debug: Device presented: samsung-SM-G800F_PT5309 (android) perftest socket:17

2015-12-18T17:56:30.562Z - debug: Socket disconnected: transport close 17 (samsung-SM-G800F_PT5309)

2015-12-18T17:57:10.877Z - debug: Device presented: motorola-XT1039_PT5743 (android) perftest socket:18

2015-12-18T17:57:11.735Z - debug: Socket disconnected: transport close 18 (motorola-XT1039_PT5743)

2015-12-18T17:58:21.545Z - info: Start timeout elapsed for platform: android

2015-12-18T17:58:21.549Z - info: Starting perf test run for platform: android

2015-12-18T17:58:21.550Z - info: Using devices:

2015-12-18T17:58:21.551Z - info: HTC-HTC One M8s_PT3565

2015-12-18T17:58:21.552Z - info: samsung-SM-N910C_PT6460

2015-12-18T17:58:21.553Z - info: LGE-Nexus 5_PT5924

2015-12-18T17:58:21.554Z - info: samsung-SM-G900F_PT8280

2015-12-18T17:58:21.555Z - info: samsung-SM-G900F_PT633

2015-12-18T17:58:21.556Z - info: samsung-SM-A300FU_PT5572

2015-12-18T17:58:21.557Z - info: samsung-SM-A500FU_PT1532

2015-12-18T17:58:21.558Z - info: motorola-XT1072_PT598

2015-12-18T17:58:21.559Z - info: samsung-SM-A300FU_PT8506

2015-12-18T17:58:21.561Z - info: LGE-LG-H815_PT9219

2015-12-18T17:58:21.562Z - info: samsung-SM-A500FU_PT3826

2015-12-18T17:58:21.563Z - info: LGE-LG-D722_PT8213

2015-12-18T17:58:21.564Z - info: LGE-LG-D855_PT589

2015-12-18T17:58:21.565Z - info: samsung-SM-G800F_PT5309
2015-12-18T17:58:21.566Z - info: motorola-XT1039_PT5743

2015-12-18T17:58:21.568Z - info: Setting: (android) 15

2015-12-18T17:58:21.569Z - debug:  name=testSendData.js, serverTimeout=1200000, timeout=1000000, rounds=1, dataTimeout=20000, dataAmount=100000, conReTryTimeout=5000, conReTryCount=5, peerCount=15

2015-12-18T17:58:23.420Z - info: Start timeout elapsed for platform: ios

2015-12-18T17:58:23.421Z - info: Tests for ios already running or completed

2015-12-18T18:00:17.239Z - debug: Socket disconnected: ping timeout 3 (samsung-SM-N910C_PT6460)

2015-12-18T18:00:52.380Z - debug: Socket disconnected: ping timeout 15 (Apple-Iphone6-1_PT892)

2015-12-18T18:01:48.433Z - debug: Socket disconnected: ping timeout 14 (LGE-LG-D855_PT589)

2015-12-18T18:01:53.109Z - debug: Socket disconnected: transport close 11 (LGE-LG-H815_PT9219)

2015-12-18T18:01:53.458Z - debug: Device presented: LGE-LG-H815_PT9219 (android) perftest socket:19

2015-12-18T18:01:53.461Z - info: Updating existing device: LGE-LG-H815_PT9219 (7e089d3a-f253-4c16-897f-dfad5876acdd)

2015-12-18T18:01:59.811Z - debug: Socket disconnected: ping timeout 9 (motorola-XT1072_PT598)

2015-12-18T18:02:03.166Z - debug: Device presented: LGE-LG-D855_PT589 (android) perftest socket:20

2015-12-18T18:02:03.169Z - info: Updating existing device: LGE-LG-D855_PT589 (2c9476e8-17be-4bfa-9b17-612fc6b8fae4)

2015-12-18T18:02:26.027Z - debug: Socket disconnected: ping timeout 1 (HTC-HTC One M8s_PT3565)

2015-12-18T18:02:52.539Z - debug: Socket disconnected: ping timeout 10 (samsung-SM-A300FU_PT8506)

2015-12-18T18:02:56.757Z - debug: Socket disconnected: ping timeout 0 (Apple-Iphone5s-1_PT7811)

2015-12-18T18:13:06.261Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT9737","time":1000045,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone6-1_PT892.v2mOqA==","time":4614,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7811.xvr6/w==","time":3352,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT4784.tBG+yQ==","time":3204,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1_PT9737 ios (4 left)

2015-12-18T18:13:06.268Z - info: Received results for {"name:":"Apple-Iphone5-1_PT4784","time":1000047,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone6-1_PT892.v2mOqA==","time":4786,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT9737.0QrSBA==","time":4468,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7811.xvr6/w==","time":3720,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1_PT4784 ios (3 left)

2015-12-18T18:15:02.013Z - info: Received results for {"name:":"LGE-LG-H815_PT9219","time":1000262,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":11767,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":9330,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":4383,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":12598,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":25849,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":87760,"result":"Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT1532] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"E0:DB:10:14:E2:C0","time":6349,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":24552,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":43712,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":1292,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2220,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-H815_PT9219 android (15 left)

2015-12-18T18:15:02.358Z - info: Received results for {"name:":"LGE-LG-D722_PT8213","time":1000283,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":2379,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":4491,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":6648,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":2135,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":4095,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":2443,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":3627,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":5984,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":5175,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":2989,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":1594,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D722_PT8213 android (14 left)

2015-12-18T18:15:02.364Z - info: Received results for {"name:":"LGE-Nexus 5_PT5924","time":1000082,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":4468,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":2899,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":4179,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":11190,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":53340,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":3840,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":3631,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":4392,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":3825,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":6069,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":4484,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-Nexus 5_PT5924 android (13 left)

2015-12-18T18:15:02.377Z - info: Received results for {"name:":"samsung-SM-A500FU_PT3826","time":1000084,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":4679,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":11110,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":8224,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":2535,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":30775,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":13865,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":7653,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":1838,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":13855,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":59851,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":7042,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":3199,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A500FU_PT3826 android (12 left)

2015-12-18T18:15:02.468Z - info: Received results for {"name:":"samsung-SM-A500FU_PT1532","time":1000091,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":4996,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":3990,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":13125,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":70406,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":98239,"result":"Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT8506] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"B0:C5:59:3F:75:69","time":66124,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":3801,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":7610,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":4783,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2892,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":4635,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":3248,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A500FU_PT1532 android (11 left)

2015-12-18T18:15:02.663Z - info: Received results for {"name:":"samsung-SM-G900F_PT8280","time":1000131,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":4990,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":4230,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":8069,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":6179,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":9600,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":28643,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":6065,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":44453,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":47361,"result":"Connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT598] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"E0:DB:10:14:E2:C0","time":5417,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":7129,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2936,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT8280 android (10 left)

2015-12-18T18:15:02.824Z - info: Received results for {"name:":"samsung-SM-A300FU_PT5572","time":1000091,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":3132,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":9647,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":46467,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":26553,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":6732,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":4676,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":4114,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":49668,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":3470,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":29248,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2258,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A300FU_PT5572 android (9 left)

2015-12-18T18:15:04.077Z - info: Received results for {"name:":"samsung-SM-G900F_PT633","time":1000174,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":5382,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":19636,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":6267,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":3062,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":1620,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":11656,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":19194,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":33595,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":6496,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":7738,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":4075,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3927,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT633 android (8 left)

2015-12-18T18:15:07.165Z - info: Received results for {"name:":"LGE-LG-D855_PT589","time":1000099,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:34:8A:A0","time":6958,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":99368,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":10760,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":51976,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":5249,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":18029,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":1634,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":1884,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2750,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":2361,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D855_PT589 android (7 left)

2015-12-18T18:16:25.969Z - info: server timeout for test: testSendData.js (ios)

2015-12-18T18:16:25.972Z - info: All test data retrieved for testSendData.js (ios)

2015-12-18T18:16:25.975Z - info: No results from [object Object]

2015-12-18T18:16:25.976Z - info: No results from [object Object]

2015-12-18T18:16:25.980Z - info: Continuing to next test: testFindPeers.js

2015-12-18T18:16:25.981Z - info: Setting: (ios) 4

2015-12-18T18:16:25.982Z - debug:  name=testFindPeers.js, serverTimeout=1200000, timeout=1000000, rounds=1, dataTimeout=10000, dataAmount=100000, conReTryTimeout=5000, conReTryCount=5, peerCount=4

2015-12-18T18:16:27.188Z - info: Received results for {"name:":"Apple-Iphone5-1_PT4784","time":48,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1_PT7811.xvr6/w==","peerAvailable":true,"time":45}]} Apple-Iphone5-1_PT4784 ios (4 left)

2015-12-18T18:16:27.550Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT9737","time":26,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT892.v2mOqA==","peerAvailable":true,"time":25}]} Apple-IpadAir2-1_PT9737 ios (3 left)

2015-12-18T18:18:21.573Z - info: server timeout for test: testSendData.js (android)

2015-12-18T18:18:21.574Z - info: All test data retrieved for testSendData.js (android)

2015-12-18T18:18:21.575Z - info: No results from [object Object]

2015-12-18T18:18:21.576Z - info: No results from [object Object]

2015-12-18T18:18:21.581Z - info: No results from [object Object]

2015-12-18T18:18:21.582Z - info: No results from [object Object]

2015-12-18T18:18:21.586Z - info: No results from [object Object]

2015-12-18T18:18:21.587Z - info: No results from [object Object]

2015-12-18T18:18:21.588Z - info: Continuing to next test: testReConnect.js

2015-12-18T18:18:21.589Z - info: Setting: (android) 15

2015-12-18T18:18:21.590Z - debug:  name=testReConnect.js, serverTimeout=1200000, timeout=1000000, rounds=1, dataTimeout=10000, dataAmount=100000, conReTryTimeout=5000, conReTryCount=5, peerCount=15

2015-12-18T18:18:37.779Z - debug: Socket disconnected: transport close 16 (Apple-IpadAir2-1_PT9737)

2015-12-18T18:18:37.790Z - debug: Socket disconnected: transport close 7 (Apple-Iphone5-1_PT4784)

2015-12-18T18:22:20.505Z - debug: Socket disconnected: transport close 19 (LGE-LG-H815_PT9219)

2015-12-18T18:22:20.510Z - debug: Socket disconnected: transport close 13 (LGE-LG-D722_PT8213)

2015-12-18T18:22:21.767Z - debug: Socket disconnected: transport close 8 (samsung-SM-A500FU_PT1532)

2015-12-18T18:22:22.370Z - debug: Socket disconnected: transport close 4 (LGE-Nexus 5_PT5924)

2015-12-18T18:22:23.870Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F_PT633)

2015-12-18T18:22:26.110Z - debug: Socket disconnected: transport close 12 (samsung-SM-A500FU_PT3826)

2015-12-18T18:23:32.468Z - debug: Socket disconnected: transport close 6 (samsung-SM-A300FU_PT5572)

2015-12-18T18:24:02.756Z - debug: Socket disconnected: transport close 2 (samsung-SM-G900F_PT8280)

2015-12-18T18:27:13.698Z - debug: Socket disconnected: transport close 20 (LGE-LG-D855_PT589)


 
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
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:0 
child process exited with code 0 on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:null 
child process exited with code null on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:0 
child process exited with code 0 on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device CC51WYC03425 app:com.test.thalitest code:0 
child process exited with code 0 on device CC51WYC03425 
Error! Unexpected exit on device 0c6a0f3c0bdb4e77 app:com.test.thalitest code:0 
child process exited with code 0 on device 0c6a0f3c0bdb4e77 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278bcecc5c_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




