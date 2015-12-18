#### Test 50650278d76d9c3 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2015-12-18T18:38:05.101Z - info: listening on *:3000

2015-12-18T18:38:05.928Z - debug: Device presented: samsung-SM-A300FU_PT1294 (android) perftest socket:0

2015-12-18T18:38:05.935Z - info: Setting start timeout to: 120000 (android)

2015-12-18T18:38:05.952Z - debug: Device presented: LGE-Nexus 5_PT491 (android) perftest socket:1

2015-12-18T18:38:06.101Z - debug: Device presented: motorola-XT1072_PT7387 (android) perftest socket:2

2015-12-18T18:38:06.361Z - debug: Device presented: samsung-SM-N910C_PT3591 (android) perftest socket:3

2015-12-18T18:38:06.487Z - debug: Device presented: Apple-Iphone6-1_PT6353 (ios) perftest socket:4

2015-12-18T18:38:06.488Z - info: Setting start timeout to: 120000 (ios)

2015-12-18T18:38:06.656Z - debug: Device presented: Apple-IpadAir2-1_PT9191 (ios) perftest socket:5

2015-12-18T18:38:06.994Z - debug: Device presented: LGE-LG-D855_PT7178 (android) perftest socket:7

2015-12-18T18:38:07.034Z - debug: Device presented: samsung-SM-G900F_PT6677 (android) perftest socket:6

2015-12-18T18:38:07.071Z - debug: Device presented: samsung-SM-A500FU_PT7601 (android) perftest socket:8

2015-12-18T18:38:07.511Z - debug: Device presented: samsung-SM-A500FU_PT2896 (android) perftest socket:9

2015-12-18T18:38:07.718Z - debug: Device presented: samsung-SM-G900F_PT1691 (android) perftest socket:10

2015-12-18T18:38:08.668Z - debug: Device presented: Apple-Iphone5s-1_PT9213 (ios) perftest socket:11

2015-12-18T18:38:08.696Z - debug: Device presented: Apple-Iphone5-1_PT3434 (ios) perftest socket:12

2015-12-18T18:38:08.697Z - info: Required number of devices presented

2015-12-18T18:38:08.701Z - info: Starting perf test run for platform: ios

2015-12-18T18:38:08.702Z - info: Using devices:

2015-12-18T18:38:08.704Z - info: Apple-Iphone6-1_PT6353

2015-12-18T18:38:08.705Z - info: Apple-IpadAir2-1_PT9191

2015-12-18T18:38:08.706Z - info: Apple-Iphone5s-1_PT9213

2015-12-18T18:38:08.707Z - info: Apple-Iphone5-1_PT3434

2015-12-18T18:38:08.714Z - info: Setting: (ios) 4

2015-12-18T18:38:09.148Z - debug: Device presented: samsung-SM-A300FU_PT3141 (android) perftest socket:13

2015-12-18T18:38:09.708Z - debug: Device presented: LGE-LG-H815_PT1864 (android) perftest socket:14

2015-12-18T18:38:10.218Z - debug: Device presented: LGE-LG-D722_PT7096 (android) perftest socket:15

2015-12-18T18:38:10.225Z - debug: Device presented: HTC-HTC One M8s_PT6122 (android) perftest socket:16

2015-12-18T18:38:10.689Z - debug: Device presented: samsung-SM-G800F_PT5707 (android) perftest socket:17

2015-12-18T18:38:11.262Z - debug: Device presented: motorola-XT1039_PT6240 (android) perftest socket:18

2015-12-18T18:38:12.706Z - debug: Socket disconnected: transport close 17 (samsung-SM-G800F_PT5707)

2015-12-18T18:38:13.463Z - debug: Socket disconnected: transport close 18 (motorola-XT1039_PT6240)

2015-12-18T18:40:05.950Z - info: Start timeout elapsed for platform: android

2015-12-18T18:40:05.952Z - info: Starting perf test run for platform: android

2015-12-18T18:40:05.953Z - info: Using devices:

2015-12-18T18:40:05.954Z - info: samsung-SM-A300FU_PT1294

2015-12-18T18:40:05.955Z - info: LGE-Nexus 5_PT491

2015-12-18T18:40:05.956Z - info: motorola-XT1072_PT7387

2015-12-18T18:40:05.958Z - info: samsung-SM-N910C_PT3591

2015-12-18T18:40:05.959Z - info: LGE-LG-D855_PT7178

2015-12-18T18:40:05.960Z - info: samsung-SM-G900F_PT6677

2015-12-18T18:40:05.961Z - info: samsung-SM-A500FU_PT7601

2015-12-18T18:40:05.962Z - info: samsung-SM-A500FU_PT2896

2015-12-18T18:40:05.963Z - info: samsung-SM-G900F_PT1691

2015-12-18T18:40:05.964Z - info: samsung-SM-A300FU_PT3141

2015-12-18T18:40:05.965Z - info: LGE-LG-H815_PT1864

2015-12-18T18:40:05.969Z - info: LGE-LG-D722_PT7096

2015-12-18T18:40:05.970Z - info: HTC-HTC One M8s_PT6122

2015-12-18T18:40:05.971Z - info: samsung-SM-G800F_PT5707

2015-12-18T18:40:05.972Z - info: motorola-XT1039_PT6240
2015-12-18T18:40:05.974Z - info: Setting: (android) 15

2015-12-18T18:40:06.518Z - info: Start timeout elapsed for platform: ios

2015-12-18T18:40:06.519Z - info: Tests for ios already running or completed

2015-12-18T18:41:41.227Z - debug: Socket disconnected: ping timeout 16 (HTC-HTC One M8s_PT6122)

2015-12-18T18:41:44.814Z - debug: Socket disconnected: ping timeout 11 (Apple-Iphone5s-1_PT9213)

2015-12-18T18:42:27.419Z - debug: Socket disconnected: ping timeout 8 (samsung-SM-A500FU_PT7601)

2015-12-18T18:42:31.018Z - debug: Socket disconnected: ping timeout 13 (samsung-SM-A300FU_PT3141)

2015-12-18T18:42:31.989Z - debug: Socket disconnected: ping timeout 12 (Apple-Iphone5-1_PT3434)

2015-12-18T18:42:36.640Z - debug: Device presented: Apple-Iphone5-1_PT3434 (ios) perftest socket:19

2015-12-18T18:42:36.642Z - info: Updating existing device: Apple-Iphone5-1_PT3434 (f5261002-8ff1-482c-af95-dddc2760e178)

2015-12-18T18:42:52.260Z - debug: Socket disconnected: ping timeout 2 (motorola-XT1072_PT7387)

2015-12-18T18:43:18.255Z - debug: Socket disconnected: ping timeout 4 (Apple-Iphone6-1_PT6353)

2015-12-18T18:43:21.571Z - debug: Socket disconnected: ping timeout 10 (samsung-SM-G900F_PT1691)

2015-12-18T18:43:28.881Z - debug: Device presented: Apple-Iphone6-1_PT6353 (ios) perftest socket:20

2015-12-18T18:43:28.882Z - info: Updating existing device: Apple-Iphone6-1_PT6353 (7fb1187d-ac38-4d94-81b3-cecd7a37e49a)

2015-12-18T18:54:48.836Z - info: Received results for {"name:":"Apple-Iphone5-1_PT3434","time":999967,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone6-1_PT6353.xIoHCA==","time":3874,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT9213.s950ig==","time":4967,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT9191.y0m4Ag==","time":4232,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1_PT3434 ios (4 left)

2015-12-18T18:54:49.003Z - info: Received results for {"name:":"Apple-Iphone6-1_PT6353","time":1000000,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone5-1_PT3434.MiytEA==","time":3740,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-IpadAir2-1_PT9191.y0m4Ag==","time":3063,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT9213.s950ig==","time":3601,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone6-1_PT6353 ios (3 left)

2015-12-18T18:54:49.007Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT9191","time":1000034,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone5s-1_PT9213.s950ig==","time":4238,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT6353.xIoHCA==","time":3547,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5-1_PT3434.MiytEA==","time":4315,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1_PT9191 ios (2 left)

2015-12-18T18:56:46.418Z - info: Received results for {"name:":"LGE-Nexus 5_PT491","time":1000072,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":3385,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":5255,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":1929,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":17877,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":8185,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":2946,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":5917,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":4595,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3410,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":90546,"result":"Connection to peer [7C:F9:0E:37:96:AB 7C:F9:0E:37:96:AB] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0}]} LGE-Nexus 5_PT491 android (15 left)

2015-12-18T18:56:46.626Z - info: Received results for {"name:":"LGE-LG-D722_PT7096","time":1000172,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:3C:51","time":5137,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":4077,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":4519,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":4585,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":9425,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":4604,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2159,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":4742,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":1550,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D722_PT7096 android (14 left)

2015-12-18T18:56:46.685Z - info: Received results for {"name:":"samsung-SM-A300FU_PT1294","time":1000100,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":10151,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":66245,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"}]} samsung-SM-A300FU_PT1294 android (13 left)

2015-12-18T18:56:46.779Z - info: Received results for {"name:":"LGE-LG-D855_PT7178","time":1000128,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":6709,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":8004,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":64945,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":8932,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":85975,"result":"Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT3141] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:34:8A:A0","time":6949,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":96903,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":4642,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":4011,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":5165,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":50414,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D855_PT7178 android (12 left)

2015-12-18T18:56:47.349Z - info: Received results for {"name:":"samsung-SM-A500FU_PT2896","time":1000094,"result":"TIMEOUT","sendList":[{"name":"E0:DB:10:14:E2:C0","time":4246,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":92099,"result":"Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT3141] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:51:18:22","time":43506,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":115069,"result":"Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT1864] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"58:3F:54:73:64:C0","time":57523,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":3738,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":2001,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":3024,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2031,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3176,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-A500FU_PT2896 android (11 left)

2015-12-18T18:56:48.024Z - info: Received results for {"name:":"samsung-SM-N910C_PT3591","time":1000104,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:37:96:AB","time":1908,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":32238,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":25785,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":7108,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":7935,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":8138,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":3765,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":5846,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":4433,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":8647,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":6166,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-N910C_PT3591 android (10 left)

2015-12-18T18:56:48.304Z - info: Received results for {"name:":"samsung-SM-G900F_PT6677","time":1000142,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":8740,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":4445,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":3344,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":45234,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":8600,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2733,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":18380,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":29056,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":5824,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":2601,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT6677 android (9 left)

2015-12-18T18:56:48.442Z - info: Received results for {"name:":"LGE-LG-H815_PT1864","time":1000240,"result":"TIMEOUT","sendList":[{"name":"F8:95:C7:87:85:54","time":2397,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":84974,"result":"Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT3141] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"08:EC:A9:50:75:41","time":23001,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":48985,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2520,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":13530,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":4968,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":8172,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":6195,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":4870,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-H815_PT1864 android (8 left)

2015-12-18T18:58:08.719Z - info: server timeout for test: testSendData.js (ios)

2015-12-18T18:58:08.722Z - info: All test data retrieved for testSendData.js (ios)

2015-12-18T18:58:08.727Z - info: No results from [object Object]

2015-12-18T18:58:08.729Z - info: Continuing to next test: testFindPeers.js

2015-12-18T18:58:08.730Z - info: Setting: (ios) 4

2015-12-18T18:58:10.415Z - info: Received results for {"name:":"Apple-Iphone5-1_PT3434","time":957,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1_PT6353.xIoHCA==","peerAvailable":true,"time":955}]} Apple-Iphone5-1_PT3434 ios (4 left)

2015-12-18T18:58:10.688Z - info: Received results for {"name:":"Apple-Iphone6-1_PT6353","time":363,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1_PT9213.s950ig==","peerAvailable":true,"time":362}]} Apple-Iphone6-1_PT6353 ios (3 left)

2015-12-18T18:58:11.436Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT9191","time":1028,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1_PT9191.y0m4Ag==","peerAvailable":true,"time":1026}]} Apple-IpadAir2-1_PT9191 ios (2 left)

2015-12-18T19:00:05.978Z - info: server timeout for test: testSendData.js (android)

2015-12-18T19:00:05.979Z - info: All test data retrieved for testSendData.js (android)

2015-12-18T19:00:05.983Z - info: No results from [object Object]

2015-12-18T19:00:05.988Z - info: No results from [object Object]

2015-12-18T19:00:05.990Z - info: No results from [object Object]

2015-12-18T19:00:05.991Z - info: No results from [object Object]

2015-12-18T19:00:05.994Z - info: No results from [object Object]

2015-12-18T19:00:05.995Z - info: No results from [object Object]

2015-12-18T19:00:05.996Z - info: No results from [object Object]

2015-12-18T19:00:05.998Z - info: Continuing to next test: testReConnect.js

2015-12-18T19:00:05.999Z - info: Setting: (android) 15

2015-12-18T19:00:15.457Z - debug: Socket disconnected: transport close 5 (Apple-IpadAir2-1_PT9191)

2015-12-18T19:00:15.467Z - debug: Socket disconnected: transport close 20 (Apple-Iphone6-1_PT6353)

2015-12-18T19:00:15.554Z - debug: Socket disconnected: transport close 19 (Apple-Iphone5-1_PT3434)

2015-12-18T19:04:00.359Z - debug: Socket disconnected: transport close 14 (LGE-LG-H815_PT1864)

2015-12-18T19:04:00.425Z - debug: Socket disconnected: transport close 15 (LGE-LG-D722_PT7096)

2015-12-18T19:04:01.745Z - debug: Socket disconnected: transport close 9 (samsung-SM-A500FU_PT2896)

2015-12-18T19:04:02.403Z - debug: Socket disconnected: transport close 1 (LGE-Nexus 5_PT491)

2015-12-18T19:05:01.195Z - debug: Socket disconnected: transport close 0 (samsung-SM-A300FU_PT1294)

2015-12-18T19:05:37.808Z - debug: Socket disconnected: transport close 3 (samsung-SM-N910C_PT3591)

2015-12-18T19:05:40.369Z - debug: Socket disconnected: transport close 6 (samsung-SM-G900F_PT6677)

2015-12-18T19:08:20.353Z - debug: Socket disconnected: transport close 7 (LGE-LG-D855_PT7178)


 
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
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/iOS_server.md)


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
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

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
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Android task is completed. [FAILED]
```
[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

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
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 7970f88c app:com.test.thalitest code:null 
child process exited with code null on device 7970f88c 
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

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
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/50650278d76d9c3_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




