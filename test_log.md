#### Test 50650278161ce7f Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2015-12-19T01:34:56.490Z - info: listening on *:3000

2015-12-19T01:34:58.157Z - debug: Device presented: motorola-XT1072_PT8195 (android) perftest socket:0

2015-12-19T01:34:58.163Z - info: Setting start timeout to: 120000 (android)

2015-12-19T01:34:58.169Z - debug: Device presented: samsung-SM-A500FU_PT5260 (android) perftest socket:3

2015-12-19T01:34:58.202Z - debug: Device presented: Apple-IpadAir2-1_PT4132 (ios) perftest socket:2

2015-12-19T01:34:58.204Z - info: Setting start timeout to: 120000 (ios)

2015-12-19T01:34:58.277Z - debug: Device presented: Apple-Iphone6-1_PT3166 (ios) perftest socket:1

2015-12-19T01:34:58.708Z - debug: Device presented: samsung-SM-N910C_PT4591 (android) perftest socket:4

2015-12-19T01:34:58.826Z - debug: Device presented: samsung-SM-G900F_PT9642 (android) perftest socket:5

2015-12-19T01:34:58.883Z - debug: Device presented: samsung-SM-A500FU_PT4317 (android) perftest socket:6

2015-12-19T01:34:59.388Z - debug: Device presented: LGE-LG-D855_PT5943 (android) perftest socket:7

2015-12-19T01:34:59.552Z - debug: Device presented: LGE-LG-D722_PT317 (android) perftest socket:8

2015-12-19T01:34:59.807Z - debug: Device presented: LGE-Nexus 5_PT2713 (android) perftest socket:9

2015-12-19T01:35:00.089Z - debug: Device presented: HTC-HTC One M8s_PT8514 (android) perftest socket:10

2015-12-19T01:35:00.162Z - debug: Device presented: Apple-Iphone5-1_PT9897 (ios) perftest socket:11

2015-12-19T01:35:00.174Z - debug: Device presented: samsung-SM-A300FU_PT7958 (android) perftest socket:12

2015-12-19T01:35:00.718Z - debug: Device presented: LGE-LG-H815_PT9326 (android) perftest socket:14

2015-12-19T01:35:00.769Z - debug: Device presented: Apple-Iphone5s-1_PT9396 (ios) perftest socket:13

2015-12-19T01:35:00.770Z - info: Required number of devices presented

2015-12-19T01:35:00.774Z - info: Starting perf test run for platform: ios

2015-12-19T01:35:00.775Z - info: Using devices:

2015-12-19T01:35:00.777Z - info: Apple-IpadAir2-1_PT4132

2015-12-19T01:35:00.778Z - info: Apple-Iphone6-1_PT3166

2015-12-19T01:35:00.779Z - info: Apple-Iphone5-1_PT9897

2015-12-19T01:35:00.780Z - info: Apple-Iphone5s-1_PT9396

2015-12-19T01:35:00.784Z - info: Starting test: with 4 devices (ios)

2015-12-19T01:35:01.308Z - debug: Device presented: samsung-SM-A300FU_PT5261 (android) perftest socket:15

2015-12-19T01:35:01.669Z - debug: Device presented: samsung-SM-G900F_PT9541 (android) perftest socket:16

2015-12-19T01:35:08.849Z - debug: Device presented: motorola-XT1039_PT3652 (android) perftest socket:17

2015-12-19T01:35:12.110Z - debug: Socket disconnected: transport close 17 (motorola-XT1039_PT3652)

2015-12-19T01:36:50.672Z - debug: Socket disconnected: ping timeout 13 (Apple-Iphone5s-1_PT9396)

2015-12-19T01:36:58.178Z - info: Start timeout elapsed for platform: android

2015-12-19T01:36:58.179Z - info: Starting perf test run for platform: android

2015-12-19T01:36:58.180Z - info: Using devices:

2015-12-19T01:36:58.181Z - info: motorola-XT1072_PT8195

2015-12-19T01:36:58.182Z - info: samsung-SM-A500FU_PT5260
2015-12-19T01:36:58.183Z - info: samsung-SM-N910C_PT4591

2015-12-19T01:36:58.184Z - info: samsung-SM-G900F_PT9642

2015-12-19T01:36:58.185Z - info: samsung-SM-A500FU_PT4317

2015-12-19T01:36:58.186Z - info: LGE-LG-D855_PT5943

2015-12-19T01:36:58.187Z - info: LGE-LG-D722_PT317
2015-12-19T01:36:58.188Z - info: LGE-Nexus 5_PT2713

2015-12-19T01:36:58.189Z - info: HTC-HTC One M8s_PT8514

2015-12-19T01:36:58.190Z - info: samsung-SM-A300FU_PT7958

2015-12-19T01:36:58.191Z - info: LGE-LG-H815_PT9326

2015-12-19T01:36:58.192Z - info: samsung-SM-A300FU_PT5261

2015-12-19T01:36:58.193Z - info: samsung-SM-G900F_PT9541

2015-12-19T01:36:58.194Z - info: motorola-XT1039_PT3652

2015-12-19T01:36:58.195Z - info: Starting test: with 14 devices (android)

2015-12-19T01:36:58.238Z - info: Start timeout elapsed for platform: ios

2015-12-19T01:36:58.240Z - info: Tests for ios already running or completed

2015-12-19T01:37:35.693Z - debug: Socket disconnected: transport close 19 (undefined)

2015-12-19T01:37:35.754Z - debug: Socket disconnected: transport close 18 (undefined)

2015-12-19T01:37:49.520Z - debug: Device presented: Apple-Iphone5s-1_PT9396 (ios) perftest socket:20

2015-12-19T01:37:49.521Z - info: Updating existing device: Apple-Iphone5s-1_PT9396 (d2ce359d-769b-45ae-a74b-4696501fc381)

2015-12-19T01:39:14.522Z - debug: Socket disconnected: ping timeout 20 (Apple-Iphone5s-1_PT9396)

2015-12-19T01:39:33.401Z - debug: Socket disconnected: ping timeout 11 (Apple-Iphone5-1_PT9897)

2015-12-19T01:40:11.972Z - debug: Socket disconnected: ping timeout 4 (samsung-SM-N910C_PT4591)

2015-12-19T01:41:03.160Z - debug: Device presented: HTC-HTC One M8s_PT8514 (android) perftest socket:21

2015-12-19T01:41:03.162Z - info: Updating existing device: HTC-HTC One M8s_PT8514 (2e5f12d8-ab15-4680-a862-9ececd97fca2)

2015-12-19T01:41:27.595Z - debug: Socket disconnected: ping timeout 10 (HTC-HTC One M8s_PT8514)

2015-12-19T01:42:39.301Z - debug: Socket disconnected: ping timeout 0 (motorola-XT1072_PT8195)

2015-12-19T01:43:18.582Z - debug: Socket disconnected: ping timeout 1 (Apple-Iphone6-1_PT3166)

2015-12-19T01:44:07.011Z - debug: Socket disconnected: ping timeout 15 (samsung-SM-A300FU_PT5261)

2015-12-19T01:44:08.441Z - debug: Device presented: Apple-Iphone6-1_PT3166 (ios) perftest socket:22

2015-12-19T01:44:08.442Z - info: Updating existing device: Apple-Iphone6-1_PT3166 (64d86d3d-2c3d-4786-ac30-bd5fd629af3d)

2015-12-19T01:45:34.124Z - debug: Socket disconnected: ping timeout 21 (HTC-HTC One M8s_PT8514)

2015-12-19T01:51:41.089Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT4132","time":1000051,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone5-1_PT9897.wDmYaQ==","time":3651,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT9396.+XAJIw==","time":4430,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT3166.5e8qRw==","time":3081,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1_PT4132 ios (4 left)

2015-12-19T01:51:46.101Z - info: Received results for {"name:":"Apple-Iphone6-1_PT3166","time":999997,"result":"TIMEOUT","sendList":[{"name":"Apple-IpadAir2-1_PT4132.HrCdVA==","time":3872,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT9396.+XAJIw==","time":4118,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT9897.wDmYaQ==","time":3454,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1_PT3166 ios (3 left)

2015-12-19T01:53:38.540Z - info: Received results for {"name:":"LGE-LG-H815_PT9326","time":1000093,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":16997,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":12307,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":12020,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":28701,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":6436,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":4055,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":81887,"result":"Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:51:18:22","time":4410,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":3080,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":6258,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":69032,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":5841,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-H815_PT9326 android (14 left)

2015-12-19T01:53:38.554Z - info: Received results for {"name:":"samsung-SM-A500FU_PT4317","time":1000094,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":2023,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":4225,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":6508,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":8588,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":44345,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":77518,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":83018,"result":"Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"08:EC:A9:50:75:41","time":115069,"result":"Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"F8:95:C7:87:85:54","time":112304,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":3466,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":4117,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A500FU_PT4317 android (13 left)

2015-12-19T01:53:38.595Z - info: Received results for {"name:":"samsung-SM-A500FU_PT5260","time":1000082,"result":"TIMEOUT","sendList":[{"name":"B0:C5:59:3F:75:69","time":10933,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":4035,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":4947,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":101787,"result":"Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT9326] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"F8:95:C7:87:85:54","time":55526,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":10083,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":16414,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":81647,"result":"Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"E0:DB:10:14:E2:C0","time":95791,"result":"Connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"}]} samsung-SM-A500FU_PT5260 android (12 left)

2015-12-19T01:53:38.718Z - info: Received results for {"name:":"LGE-Nexus 5_PT2713","time":1000061,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":2607,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":4218,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":9445,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":8222,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":39410,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":77221,"result":"Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"B0:C5:59:3F:75:69","time":4551,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":5058,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":6541,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":4499,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":2595,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-Nexus 5_PT2713 android (11 left)

2015-12-19T01:53:38.739Z - info: Received results for {"name:":"samsung-SM-G900F_PT9642","time":1000144,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":86298,"result":"Connection to peer [7C:F9:0E:51:18:22 samsung-SM-A500FU_PT5260] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:37:96:AB","time":104051,"result":"Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"F8:95:C7:87:3C:51","time":100832,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":8481,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":117092,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":50214,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":50853,"result":"Connection to peer [44:80:EB:7B:5A:05 motorola-XT1072_PT8195] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"58:3F:54:73:64:C0","time":3533,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":4908,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":4342,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":5754,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3396,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT9642 android (10 left)

2015-12-19T01:53:38.764Z - info: Received results for {"name:":"samsung-SM-G900F_PT9541","time":1000153,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":33395,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":34443,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":28479,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":25351,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":106927,"result":"Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"E0:DB:10:14:E2:C0","time":14552,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":16246,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":4104,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":28227,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":26648,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":12954,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3255,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT9541 android (9 left)

2015-12-19T01:53:38.805Z - info: Received results for {"name:":"samsung-SM-A300FU_PT7958","time":1000081,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":5601,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":10041,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":25285,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":8060,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":109083,"result":"Connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT4591] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:37:96:AB","time":122648,"result":"Connection to peer [7C:F9:0E:37:96:AB samsung-SM-A500FU_PT4317] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"90:E7:C4:F6:69:77","time":116002,"result":"Connection to peer [90:E7:C4:F6:69:77 HTC-HTC One M8s_PT8514] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"F8:95:C7:87:3C:51","time":59485,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":6225,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":3780,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A300FU_PT7958 android (8 left)

2015-12-19T01:53:39.219Z - info: Received results for {"name:":"LGE-LG-D722_PT317","time":1000346,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":3456,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":40025,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":12866,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":86566,"result":"Connection to peer [08:EC:A9:50:75:41 samsung-SM-A300FU_PT7958] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:51:18:22","time":10885,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":93139,"result":"Connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"}]} LGE-LG-D722_PT317 android (7 left)

2015-12-19T01:53:39.655Z - info: Received results for {"name:":"LGE-LG-D855_PT5943","time":1000106,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":7809,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":12701,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":6528,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":4663,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":54311,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":48410,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":93972,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":6117,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":56224,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":85217,"result":"Connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT9642] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"34:FC:EF:11:AE:67","time":2364,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D855_PT5943 android (6 left)

2015-12-19T01:55:00.786Z - info: server timeout for test: testSendData.js (ios)

2015-12-19T01:55:00.789Z - info: All test data retrieved for testSendData.js (ios)

2015-12-19T01:55:00.794Z - info: No results from [object Object]

2015-12-19T01:55:00.795Z - info: No results from [object Object]

2015-12-19T01:55:00.797Z - info: Continuing to next test: testFindPeers.js

2015-12-19T01:55:00.798Z - info: Starting test: with 4 devices (ios)

2015-12-19T01:55:01.090Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT4132","time":34,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1_PT9897.wDmYaQ==","peerAvailable":true,"time":33}]} Apple-IpadAir2-1_PT4132 ios (4 left)

2015-12-19T01:55:02.135Z - info: Received results for {"name:":"Apple-Iphone6-1_PT3166","time":484,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT3166.5e8qRw==","peerAvailable":true,"time":482}]} Apple-Iphone6-1_PT3166 ios (3 left)

2015-12-19T01:56:58.198Z - info: server timeout for test: testSendData.js (android)

2015-12-19T01:56:58.199Z - info: All test data retrieved for testSendData.js (android)

2015-12-19T01:56:58.200Z - info: No results from [object Object]

2015-12-19T01:56:58.202Z - info: No results from [object Object]

2015-12-19T01:56:58.207Z - info: No results from [object Object]

2015-12-19T01:56:58.210Z - info: No results from [object Object]

2015-12-19T01:56:58.212Z - info: No results from [object Object]

2015-12-19T01:56:58.213Z - info: Continuing to next test: testFindPeers.js

2015-12-19T01:56:58.214Z - info: Starting test: with 14 devices (android)

2015-12-19T01:57:09.068Z - info: Received results for {"name:":"LGE-Nexus 5_PT2713","time":10342,"result":"OK","peersList":[{"peerName":"samsung-SM-A500FU_PT4317","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":10339}]} LGE-Nexus 5_PT2713 android (14 left)

2015-12-19T01:57:28.583Z - debug: Socket disconnected: transport close 2 (Apple-IpadAir2-1_PT4132)

2015-12-19T01:57:28.605Z - debug: Socket disconnected: transport close 22 (Apple-Iphone6-1_PT3166)

2015-12-19T02:01:10.022Z - debug: Socket disconnected: transport close 8 (LGE-LG-D722_PT317)

2015-12-19T02:01:11.865Z - debug: Socket disconnected: transport close 9 (LGE-Nexus 5_PT2713)

2015-12-19T02:01:16.859Z - debug: Socket disconnected: transport close 16 (samsung-SM-G900F_PT9541)

2015-12-19T02:01:17.344Z - debug: Socket disconnected: transport close 14 (LGE-LG-H815_PT9326)

2015-12-19T02:01:18.775Z - debug: Socket disconnected: transport close 6 (samsung-SM-A500FU_PT4317)

2015-12-19T02:01:19.754Z - debug: Socket disconnected: transport close 3 (samsung-SM-A500FU_PT5260)

2015-12-19T02:02:14.543Z - debug: Socket disconnected: transport close 12 (samsung-SM-A300FU_PT7958)

2015-12-19T02:02:52.247Z - debug: Socket disconnected: transport close 5 (samsung-SM-G900F_PT9642)

2015-12-19T02:03:06.147Z - info: Received results for {"name:":"LGE-LG-D855_PT5943","time":361991,"result":"OK","peersList":[{"peerName":"LGE-Nexus 5_PT2713","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":false,"time":361988}]} LGE-LG-D855_PT5943 android (13 left)

2015-12-19T02:05:13.426Z - debug: Socket disconnected: transport close 7 (LGE-LG-D855_PT5943)


 
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
ios: child process exited with code null on device 2a65f58f9902a701b5c9a55b2befb18672927474 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

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
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Error! Unexpected exit on device 4325e43f app:com.test.thalitest code:null 
child process exited with code null on device 4325e43f 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278161ce7f_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




