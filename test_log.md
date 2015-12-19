#### Test 5065027869d93ea Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2015-12-19T00:26:51.309Z - info: listening on *:3000

2015-12-19T00:26:51.828Z - debug: Device presented: HTC-HTC One M8s_PT6420 (android) perftest socket:0

2015-12-19T00:26:51.836Z - info: Setting start timeout to: 120000 (android)

2015-12-19T00:26:51.843Z - debug: Device presented: samsung-SM-A500FU_PT7600 (android) perftest socket:2

2015-12-19T00:26:51.878Z - debug: Device presented: Apple-Iphone5-1_PT7806 (ios) perftest socket:3

2015-12-19T00:26:51.879Z - info: Setting start timeout to: 120000 (ios)

2015-12-19T00:26:51.949Z - debug: Device presented: LGE-LG-D722_PT2457 (android) perftest socket:4

2015-12-19T00:26:52.323Z - debug: Device presented: Apple-Iphone5s-1_PT7601 (ios) perftest socket:1

2015-12-19T00:26:52.838Z - debug: Device presented: LGE-Nexus 5_PT6618 (android) perftest socket:5

2015-12-19T00:26:52.882Z - debug: Device presented: LGE-LG-H815_PT2685 (android) perftest socket:6

2015-12-19T00:26:53.088Z - debug: Device presented: LGE-LG-D855_PT7127 (android) perftest socket:7

2015-12-19T00:26:53.225Z - debug: Device presented: samsung-SM-G900F_PT838 (android) perftest socket:8

2015-12-19T00:26:54.413Z - debug: Device presented: samsung-SM-N910C_PT3595 (android) perftest socket:9

2015-12-19T00:26:54.475Z - debug: Device presented: samsung-SM-A300FU_PT2588 (android) perftest socket:10

2015-12-19T00:26:55.093Z - debug: Device presented: Apple-Iphone6-1_PT3810 (ios) perftest socket:11

2015-12-19T00:26:55.202Z - debug: Device presented: samsung-SM-G900F_PT6107 (android) perftest socket:12

2015-12-19T00:26:55.573Z - debug: Device presented: motorola-XT1072_PT5534 (android) perftest socket:13

2015-12-19T00:26:55.804Z - debug: Device presented: samsung-SM-A300FU_PT5596 (android) perftest socket:14

2015-12-19T00:26:56.088Z - debug: Device presented: Apple-IpadAir2-1_PT6779 (ios) perftest socket:15

2015-12-19T00:26:56.089Z - info: Required number of devices presented

2015-12-19T00:26:56.094Z - info: Starting perf test run for platform: ios

2015-12-19T00:26:56.095Z - info: Using devices:

2015-12-19T00:26:56.096Z - info: Apple-Iphone5-1_PT7806

2015-12-19T00:26:56.097Z - info: Apple-Iphone5s-1_PT7601

2015-12-19T00:26:56.098Z - info: Apple-Iphone6-1_PT3810

2015-12-19T00:26:56.099Z - info: Apple-IpadAir2-1_PT6779

2015-12-19T00:26:56.103Z - info: Setting: (ios) 4

2015-12-19T00:26:56.267Z - debug: Device presented: samsung-SM-A500FU_PT6283 (android) perftest socket:16

2015-12-19T00:27:05.516Z - debug: Device presented: samsung-SM-G800F_PT3996 (android) perftest socket:17

2015-12-19T00:27:06.358Z - debug: Device presented: motorola-XT1039_PT9867 (android) perftest socket:18

2015-12-19T00:27:06.804Z - debug: Socket disconnected: transport close 17 (samsung-SM-G800F_PT3996)

2015-12-19T00:27:08.832Z - debug: Socket disconnected: transport close 18 (motorola-XT1039_PT9867)

2015-12-19T00:28:51.853Z - info: Start timeout elapsed for platform: android

2015-12-19T00:28:51.854Z - info: Starting perf test run for platform: android

2015-12-19T00:28:51.855Z - info: Using devices:

2015-12-19T00:28:51.857Z - info: HTC-HTC One M8s_PT6420

2015-12-19T00:28:51.858Z - info: samsung-SM-A500FU_PT7600

2015-12-19T00:28:51.858Z - info: LGE-LG-D722_PT2457

2015-12-19T00:28:51.859Z - info: LGE-Nexus 5_PT6618
2015-12-19T00:28:51.860Z - info: LGE-LG-H815_PT2685

2015-12-19T00:28:51.861Z - info: LGE-LG-D855_PT7127

2015-12-19T00:28:51.862Z - info: samsung-SM-G900F_PT838

2015-12-19T00:28:51.863Z - info: samsung-SM-N910C_PT3595
2015-12-19T00:28:51.864Z - info: samsung-SM-A300FU_PT2588

2015-12-19T00:28:51.865Z - info: samsung-SM-G900F_PT6107

2015-12-19T00:28:51.866Z - info: motorola-XT1072_PT5534

2015-12-19T00:28:51.867Z - info: samsung-SM-A300FU_PT5596

2015-12-19T00:28:51.868Z - info: samsung-SM-A500FU_PT6283

2015-12-19T00:28:51.869Z - info: samsung-SM-G800F_PT3996

2015-12-19T00:28:51.870Z - info: motorola-XT1039_PT9867

2015-12-19T00:28:51.871Z - info: Setting: (android) 15

2015-12-19T00:28:51.904Z - info: Start timeout elapsed for platform: ios

2015-12-19T00:28:51.905Z - info: Tests for ios already running or completed

2015-12-19T00:30:25.865Z - debug: Socket disconnected: ping timeout 1 (Apple-Iphone5s-1_PT7601)

2015-12-19T00:30:52.790Z - debug: Socket disconnected: ping timeout 11 (Apple-Iphone6-1_PT3810)

2015-12-19T00:30:57.617Z - debug: Socket disconnected: ping timeout 3 (Apple-Iphone5-1_PT7806)

2015-12-19T00:31:14.852Z - debug: Socket disconnected: ping timeout 2 (samsung-SM-A500FU_PT7600)

2015-12-19T00:31:40.011Z - debug: Socket disconnected: ping timeout 9 (samsung-SM-N910C_PT3595)

2015-12-19T00:32:32.805Z - debug: Socket disconnected: ping timeout 16 (samsung-SM-A500FU_PT6283)

2015-12-19T00:32:32.988Z - debug: Socket disconnected: transport close 20 (undefined)

2015-12-19T00:32:35.014Z - debug: Socket disconnected: transport close 19 (undefined)

2015-12-19T00:32:37.169Z - debug: Socket disconnected: transport close 21 (undefined)

2015-12-19T00:32:37.423Z - debug: Device presented: Apple-Iphone5-1_PT7806 (ios) perftest socket:22

2015-12-19T00:32:37.424Z - info: Updating existing device: Apple-Iphone5-1_PT7806 (e4abfbee-ee9d-437a-a0be-e172093d94af)

2015-12-19T00:33:16.127Z - debug: Socket disconnected: ping timeout 14 (samsung-SM-A300FU_PT5596)

2015-12-19T00:33:30.147Z - debug: Socket disconnected: ping timeout 13 (motorola-XT1072_PT5534)

2015-12-19T00:35:40.086Z - debug: Socket disconnected: ping timeout 0 (HTC-HTC One M8s_PT6420)

2015-12-19T00:43:36.251Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT6779","time":1000036,"result":"TIMEOUT","sendList":[{"name":"Apple-Iphone5-1_PT7806.b8v14g==","time":3597,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT3810.9x5b9w==","time":3319,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7601.1oUnQA==","time":3671,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-IpadAir2-1_PT6779 ios (4 left)

2015-12-19T00:43:36.353Z - info: Received results for {"name:":"Apple-Iphone5-1_PT7806","time":1000033,"result":"TIMEOUT","sendList":[{"name":"Apple-IpadAir2-1_PT6779.RtEaKg==","time":3672,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone5s-1_PT7601.1oUnQA==","time":3712,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"Apple-Iphone6-1_PT3810.9x5b9w==","time":3444,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} Apple-Iphone5-1_PT7806 ios (3 left)

2015-12-19T00:45:32.310Z - info: Received results for {"name:":"samsung-SM-G900F_PT6107","time":1000171,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":97391,"result":"Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"58:3F:54:73:64:C0","time":5404,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":49795,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":83390,"result":"Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"7C:F9:0E:34:8A:A0","time":4434,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":3939,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":7625,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":7786,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":2539,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":27280,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":2946,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":2552,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT6107 android (15 left)

2015-12-19T00:45:32.361Z - info: Received results for {"name:":"LGE-LG-D722_PT2457","time":1000279,"result":"TIMEOUT","sendList":[{"name":"90:E7:C4:F6:69:77","time":2422,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":10768,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":8197,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":4292,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":70230,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":41550,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":19308,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":55038,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":24282,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":106362,"result":"Connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] timed out","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"34:FC:EF:11:AE:67","time":93534,"result":"OK","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D722_PT2457 android (14 left)

2015-12-19T00:45:32.565Z - info: Received results for {"name:":"LGE-Nexus 5_PT6618","time":1000074,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":3284,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":10868,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":3366,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":3504,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":6460,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":3288,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":2775,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":3089,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":3826,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":5211,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":5670,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-Nexus 5_PT6618 android (13 left)

2015-12-19T00:45:32.620Z - info: Received results for {"name:":"samsung-SM-A300FU_PT2588","time":1000090,"result":"TIMEOUT","sendList":[{"name":"90:E7:C4:F6:69:77","time":21073,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":2963,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":22987,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":104066,"result":"Connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"F8:95:C7:87:85:54","time":62932,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":70212,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":96163,"result":"Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"}]} samsung-SM-A300FU_PT2588 android (12 left)

2015-12-19T00:45:32.781Z - info: Received results for {"name:":"samsung-SM-G900F_PT838","time":1000145,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":52903,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":12122,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":14864,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":7452,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":30579,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":70291,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":2670,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":12381,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":95785,"result":"Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"90:E7:C4:F6:69:77","time":35688,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":22733,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2966,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} samsung-SM-G900F_PT838 android (11 left)

2015-12-19T00:45:32.792Z - info: Received results for {"name:":"LGE-LG-H815_PT2685","time":1000254,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":25016,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":5284,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"44:80:EB:7B:5A:05","time":5955,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":81201,"result":"Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed","connections":5,"doneRounds":1,"dataAmount":100000,"dataReceived":0},{"name":"34:FC:EF:11:AE:67","time":10058,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"58:3F:54:73:64:C0","time":6484,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":58396,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":63424,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":13221,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":67249,"result":"OK","connections":4,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":7425,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":21377,"result":"OK","connections":2,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-H815_PT2685 android (10 left)

2015-12-19T00:45:34.171Z - info: Received results for {"name:":"LGE-LG-D855_PT7127","time":1000091,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":2345,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":5327,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":5767,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":10782,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:37:96:AB","time":7378,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":4709,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:85:54","time":2009,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":8530,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:75:41","time":41165,"result":"OK","connections":3,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:51:18:22","time":7556,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":2441,"result":"OK","connections":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000}]} LGE-LG-D855_PT7127 android (9 left)

2015-12-19T00:46:56.109Z - info: server timeout for test: testSendData.js (ios)

2015-12-19T00:46:56.113Z - info: All test data retrieved for testSendData.js (ios)

2015-12-19T00:46:56.117Z - info: No results from [object Object]

2015-12-19T00:46:56.118Z - info: No results from [object Object]

2015-12-19T00:46:56.121Z - info: Continuing to next test: testFindPeers.js

2015-12-19T00:46:56.122Z - info: Setting: (ios) 4

2015-12-19T00:46:57.511Z - info: Received results for {"name:":"Apple-IpadAir2-1_PT6779","time":977,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1_PT7601.1oUnQA==","peerAvailable":true,"time":975}]} Apple-IpadAir2-1_PT6779 ios (4 left)

2015-12-19T00:46:58.011Z - info: Received results for {"name:":"Apple-Iphone5-1_PT7806","time":962,"result":"OK","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1_PT7806.b8v14g==","peerAvailable":true,"time":961}]} Apple-Iphone5-1_PT7806 ios (3 left)

2015-12-19T00:48:51.876Z - info: server timeout for test: testSendData.js (android)

2015-12-19T00:48:51.878Z - info: All test data retrieved for testSendData.js (android)

2015-12-19T00:48:51.881Z - info: No results from [object Object]

2015-12-19T00:48:51.882Z - info: No results from [object Object]

2015-12-19T00:48:51.886Z - info: No results from [object Object]

2015-12-19T00:48:51.888Z - info: No results from [object Object]

2015-12-19T00:48:51.889Z - info: No results from [object Object]

2015-12-19T00:48:51.889Z - info: No results from [object Object]
2015-12-19T00:48:51.890Z - info: No results from [object Object]

2015-12-19T00:48:51.891Z - info: No results from [object Object]
2015-12-19T00:48:51.892Z - info: ALL DONE !!!

{ 'name:': 'Apple-Iphone5-1_PT7806',
  time: 1000033,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-IpadAir2-1_PT6779.RtEaKg==',
       time: 3672,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7601.1oUnQA==',
       time: 3712,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3810.9x5b9w==',
       time: 3444,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'Apple-IpadAir2-1_PT6779',
  time: 1000036,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'Apple-Iphone5-1_PT7806.b8v14g==',
       time: 3597,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone6-1_PT3810.9x5b9w==',
       time: 3319,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'Apple-Iphone5s-1_PT7601.1oUnQA==',
       time: 3671,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-D722_PT2457',
  time: 1000279,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '90:E7:C4:F6:69:77',
       time: 2422,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 10768,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 8197,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 4292,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 70230,
       result: 'OK',
       connections: 4,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 41550,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 19308,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 55038,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 24282,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 106362,
       result: 'Connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] timed out',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: '34:FC:EF:11:AE:67',
       time: 93534,
       result: 'OK',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-Nexus 5_PT6618',
  time: 1000074,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 3284,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '90:E7:C4:F6:69:77',
       time: 10868,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 3366,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 3504,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 6460,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 3288,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 2775,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 3089,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 3826,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 5211,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 5670,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-H815_PT2685',
  time: 1000254,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '7C:F9:0E:51:18:22',
       time: 25016,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '90:E7:C4:F6:69:77',
       time: 5284,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 5955,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:76:27',
       time: 81201,
       result: 'Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: '34:FC:EF:11:AE:67',
       time: 10058,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 6484,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 58396,
       result: 'OK',
       connections: 4,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 63424,
       result: 'OK',
       connections: 4,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 13221,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 67249,
       result: 'OK',
       connections: 4,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 7425,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 21377,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'LGE-LG-D855_PT7127',
  time: 1000091,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 2345,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 5327,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 5767,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 10782,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 7378,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 4709,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 2009,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '90:E7:C4:F6:69:77',
       time: 8530,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 41165,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 7556,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 2441,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-G900F_PT838',
  time: 1000145,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 52903,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 12122,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 14864,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 7452,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 30579,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 70291,
       result: 'OK',
       connections: 4,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 2670,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '58:3F:54:73:64:C0',
       time: 12381,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 95785,
       result: 'Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] failed',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: '90:E7:C4:F6:69:77',
       time: 35688,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 22733,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 2966,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

{ 'name:': 'samsung-SM-A300FU_PT2588',
  time: 1000090,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '90:E7:C4:F6:69:77',
       time: 21073,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 2963,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 22987,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 104066,
       result: 'Connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] failed',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: 'F8:95:C7:87:85:54',
       time: 62932,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 70212,
       result: 'OK',
       connections: 4,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 96163,
       result: 'Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] failed',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: '08:EC:A9:50:76:27', time: 0, result: 'Fail' } ] }

{ 'name:': 'samsung-SM-G900F_PT6107',
  time: 1000171,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 97391,
       result: 'Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] failed',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: '58:3F:54:73:64:C0',
       time: 5404,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '44:80:EB:7B:5A:05',
       time: 49795,
       result: 'OK',
       connections: 3,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:85:54',
       time: 83390,
       result: 'Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] failed',
       connections: 5,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 0 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 4434,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:37:96:AB',
       time: 3939,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 7625,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 7786,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:75:41',
       time: 2539,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:51:18:22',
       time: 27280,
       result: 'OK',
       connections: 2,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 2946,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '90:E7:C4:F6:69:77',
       time: 2552,
       result: 'OK',
       connections: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 } ] }

--------------- test report ---------------------
--------------- Apple-Iphone5-1_PT7806 --------------------- : 1

sendList : 100% : 3712 ms, 99% : 3712 ms, 95 : 3712 ms, 90% : 3712 ms.

Average data rate: 0.028 MB/s

Result count 3, range 3444 ms to  3712 ms.

sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- Apple-IpadAir2-1_PT6779 --------------------- : 2

sendList : 100% : 3671 ms, 99% : 3671 ms, 95 : 3671 ms, 90% : 3671 ms.
Average data rate: 0.028 MB/s
Result count 3, range 3319 ms to  3671 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]

--------------- LGE-LG-D722_PT2457 --------------------- : 3
sendList : 100% : 93534 ms, 99% : 93534 ms, 95 : 93534 ms, 90% : 70230 ms.
Average data rate: 0.003 MB/s
Result count 10, range 2422 ms to  93534 ms.
sendList failed peers count : 1 [9.090909090909092 %]

- Peer ID : 7C:F9:0E:34:8A:A0, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- LGE-Nexus 5_PT6618 --------------------- : 4

sendList : 100% : 10868 ms, 99% : 10868 ms, 95 : 6460 ms, 90% : 6460 ms.
Average data rate: 0.021 MB/s
Result count 11, range 2775 ms to  10868 ms.
sendList failed peers count : 0 [0 %]

sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-H815_PT2685 --------------------- : 5
sendList : 100% : 67249 ms, 99% : 67249 ms, 95 : 63424 ms, 90% : 63424 ms.
Average data rate: 0.004 MB/s
Result count 11, range 5284 ms to  67249 ms.

sendList failed peers count : 1 [8.333333333333334 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- LGE-LG-D855_PT7127 --------------------- : 6
sendList : 100% : 41165 ms, 99% : 41165 ms, 95 : 10782 ms, 90% : 10782 ms.
Average data rate: 0.011 MB/s
Result count 11, range 2009 ms to  41165 ms.
sendList failed peers count : 0 [0 %]
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-G900F_PT838 --------------------- : 7
sendList : 100% : 70291 ms, 99% : 70291 ms, 95 : 52903 ms, 90% : 52903 ms.
Average data rate: 0.004 MB/s
Result count 11, range 2670 ms to  70291 ms.
sendList failed peers count : 1 [8.333333333333334 %]
- Peer ID : F8:95:C7:87:3C:51, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- samsung-SM-A300FU_PT2588 --------------------- : 8
sendList : 100% : 70212 ms, 99% : 70212 ms, 95 : 70212 ms, 90% : 70212 ms.
Average data rate: 0.003 MB/s
Result count 5, range 2963 ms to  70212 ms.
sendList failed peers count : 2 [28.571428571428573 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 5
- Peer ID : F8:95:C7:87:3C:51, Tried : 5
sendList never tried peers count : 1 [12.5 %]
- Peer ID : 08:EC:A9:50:76:27
--------------- samsung-SM-G900F_PT6107 --------------------- : 9
sendList : 100% : 49795 ms, 99% : 49795 ms, 95 : 49795 ms, 90% : 27280 ms.
Average data rate: 0.009 MB/s
Result count 10, range 2539 ms to  49795 ms.
sendList failed peers count : 2 [16.666666666666668 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 5
- Peer ID : F8:95:C7:87:85:54, Tried : 5
sendList never tried peers count : 0 [0 %]
--------------- Combined ---------------------
sendList : 100% : 93534 ms, 99% : 70291 ms, 95 : 67249 ms, 90% : 58396 ms.
Average data rate: 0.006 MB/s
--------------- end of test report ---------------------

2015-12-19T00:48:52.102Z - info:  sendList=[name=Apple-Iphone6-1_PT3810.9x5b9w==, time=3444, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-IpadAir2-1_PT6779.RtEaKg==, time=3672, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1_PT7601.1oUnQA==, time=3712, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], sendList=[name=Apple-Iphone6-1_PT3810.9x5b9w==, time=3319, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5-1_PT7806.b8v14g==, time=3597, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=Apple-Iphone5s-1_PT7601.1oUnQA==, time=3671, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], sendList=[name=90:E7:C4:F6:69:77, time=2422, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=4292, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=8197, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=10768, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=19308, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=24282, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=41550, result=OK, connections=3, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=55038, result=OK, connections=3, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=70230, result=OK, connections=4, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=93534, result=OK, connections=5, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=7C:F9:0E:34:8A:A0, time=106362, result=Connection to peer [7C:F9:0E:34:8A:A0 samsung-SM-G900F_PT838] timed out, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], sendList=[name=58:3F:54:73:64:C0, time=2775, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=3089, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=3284, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=3288, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=3366, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=3504, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=3826, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=5211, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=5670, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=6460, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=90:E7:C4:F6:69:77, time=10868, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], sendList=[name=90:E7:C4:F6:69:77, time=5284, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=5955, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=6484, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=7425, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=10058, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=13221, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=21377, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=25016, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=58396, result=OK, connections=4, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=63424, result=OK, connections=4, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=67249, result=OK, connections=4, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=08:EC:A9:50:76:27, time=81201, result=Connection to peer [08:EC:A9:50:76:27 08:EC:A9:50:76:27] failed, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], sendList=[name=F8:95:C7:87:85:54, time=2009, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=2345, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=2441, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=4709, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=5327, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=5767, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=7378, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=7556, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=90:E7:C4:F6:69:77, time=8530, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=10782, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=41165, result=OK, connections=3, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[], notTriedList=[], sendList=[name=7C:F9:0E:37:96:AB, time=2670, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=2966, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=7452, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=12122, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=12381, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=14864, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=22733, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=30579, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=90:E7:C4:F6:69:77, time=35688, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=52903, result=OK, connections=3, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=70291, result=OK, connections=4, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=F8:95:C7:87:3C:51, time=95785, result=Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] failed, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[], sendList=[name=7C:F9:0E:37:96:AB, time=2963, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=90:E7:C4:F6:69:77, time=21073, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=22987, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:85:54, time=62932, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=70212, result=OK, connections=4, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=E0:DB:10:14:E2:C0, time=104066, result=Connection to peer [E0:DB:10:14:E2:C0 samsung-SM-N910C_PT3595] failed, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, name=F8:95:C7:87:3C:51, time=96163, result=Connection to peer [F8:95:C7:87:3C:51 LGE-LG-H815_PT2685] failed, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[name=08:EC:A9:50:76:27, time=0, result=Fail], sendList=[name=08:EC:A9:50:75:41, time=2539, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=90:E7:C4:F6:69:77, time=2552, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=E0:DB:10:14:E2:C0, time=2946, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:37:96:AB, time=3939, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=4434, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=5404, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=7625, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=34:FC:EF:11:AE:67, time=7786, result=OK, connections=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:51:18:22, time=27280, result=OK, connections=2, doneRounds=1, dataAmount=100000, dataReceived=100000, name=44:80:EB:7B:5A:05, time=49795, result=OK, connections=3, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[name=08:EC:A9:50:76:27, time=97391, result=Connection to peer [08:EC:A9:50:76:27 samsung-SM-A300FU_PT5596] failed, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0, name=F8:95:C7:87:85:54, time=83390, result=Connection to peer [F8:95:C7:87:85:54 LGE-LG-D722_PT2457] failed, connections=5, doneRounds=1, dataAmount=100000, dataReceived=0], notTriedList=[]

2015-12-19T00:48:52.128Z - debug: end to HTC-HTC One M8s_PT6420
2015-12-19T00:48:52.130Z - debug: end to samsung-SM-A500FU_PT7600
2015-12-19T00:48:52.131Z - debug: end to LGE-LG-D722_PT2457
2015-12-19T00:48:52.132Z - debug: end to LGE-Nexus 5_PT6618
2015-12-19T00:48:52.134Z - debug: end to LGE-LG-H815_PT2685
2015-12-19T00:48:52.135Z - debug: end to LGE-LG-D855_PT7127
2015-12-19T00:48:52.136Z - debug: end to samsung-SM-G900F_PT838
2015-12-19T00:48:52.137Z - debug: end to samsung-SM-N910C_PT3595
2015-12-19T00:48:52.138Z - debug: end to samsung-SM-A300FU_PT2588
2015-12-19T00:48:52.140Z - debug: end to samsung-SM-G900F_PT6107

2015-12-19T00:48:52.141Z - debug: end to motorola-XT1072_PT5534

2015-12-19T00:48:52.142Z - debug: end to samsung-SM-A300FU_PT5596

2015-12-19T00:48:52.143Z - debug: end to samsung-SM-A500FU_PT6283
2015-12-19T00:48:52.144Z - debug: end to samsung-SM-G800F_PT3996
2015-12-19T00:48:52.145Z - debug: end to motorola-XT1039_PT9867

2015-12-19T00:48:52.975Z - debug: Socket disconnected: transport close 5 (LGE-Nexus 5_PT6618)

2015-12-19T00:48:53.075Z - debug: Socket disconnected: transport close 12 (samsung-SM-G900F_PT6107)

2015-12-19T00:48:53.370Z - debug: Socket disconnected: transport close 4 (LGE-LG-D722_PT2457)

2015-12-19T00:48:53.511Z - debug: Socket disconnected: transport close 6 (LGE-LG-H815_PT2685)

2015-12-19T00:48:53.831Z - debug: Socket disconnected: transport close 10 (samsung-SM-A300FU_PT2588)

2015-12-19T00:48:54.354Z - debug: Socket disconnected: transport close 8 (samsung-SM-G900F_PT838)

2015-12-19T00:48:57.180Z - debug: Socket disconnected: transport close 7 (LGE-LG-D855_PT7127)

2015-12-19T00:49:13.811Z - debug: Socket disconnected: transport close 15 (Apple-IpadAir2-1_PT6779)

2015-12-19T00:49:13.852Z - debug: Socket disconnected: transport close 22 (Apple-Iphone5-1_PT7806)


 
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
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device f56ad48d app:com.test.thalitest code:null 
child process exited with code null on device f56ad48d 
Android task is completed. [FAILED]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Device test finished on LGD7228ee9cf5b 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device TA4750HV7I app:com.test.thalitest code:0 
child process exited with code 0 on device TA4750HV7I 
Error! Unexpected exit on device 320414cd475f91e3 app:com.test.thalitest code:null 
child process exited with code null on device 320414cd475f91e3 
Android task is completed. [FAILED]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Error! Unexpected exit on device 41006f95c8139173 app:com.test.thalitest code:null 
child process exited with code null on device 41006f95c8139173 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:null 
child process exited with code null on device 4db5c8cc 
Android task is completed. [FAILED]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali07_samsung-SM-A500FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/5065027869d93ea_Enable_UnitTest_tobybrad/thali09_LGE-Nexus 5.md)




