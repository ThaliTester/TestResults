#### Test 55311151a2306df Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-07T08:41:44.867Z - info: listening on *:3000

2016-01-07T08:41:45.469Z - debug: Device presented: XT1072 (android) perftest socket:0

2016-01-07T08:41:45.475Z - info: Setting start timeout to: 120000 (android)

2016-01-07T08:41:45.527Z - debug: Device presented: Note4-1 (android) perftest socket:2

2016-01-07T08:41:45.871Z - debug: Device presented: Thali Test (Galaxy A5) (android) perftest socket:3

2016-01-07T08:41:46.123Z - debug: Device presented: Apple-Iphone5s-1 (ios) perftest socket:1

2016-01-07T08:41:46.125Z - info: Setting start timeout to: 120000 (ios)

2016-01-07T08:41:46.478Z - debug: Device presented: G3-1 (android) perftest socket:4

2016-01-07T08:41:46.606Z - debug: Device presented: Nexus 5 (android) perftest socket:5

2016-01-07T08:41:46.654Z - debug: Device presented: Thali Test (Galaxy A3) (android) perftest socket:7

2016-01-07T08:41:46.681Z - debug: Device presented: Apple-IpadAir2-1 (ios) perftest socket:8

2016-01-07T08:41:46.686Z - debug: Device presented: S5-1 (android) perftest socket:6

2016-01-07T08:41:46.889Z - debug: Device presented: HTC One M8s (android) perftest socket:9

2016-01-07T08:41:47.556Z - debug: Device presented: A3-1 (android) perftest socket:10

2016-01-07T08:41:48.511Z - debug: Device presented: A5-1 (android) perftest socket:11

2016-01-07T08:41:49.277Z - debug: Device presented: Apple-Iphone5-1 (ios) perftest socket:13

2016-01-07T08:41:49.314Z - debug: Device presented: Thali Test (Galaxy S5) (android) perftest socket:12

2016-01-07T08:41:49.551Z - debug: Device presented: Apple-Iphone6-1 (ios) perftest socket:14

2016-01-07T08:41:49.551Z - info: Required number of devices presented

2016-01-07T08:41:49.556Z - info: Starting perf test run for platform: ios

2016-01-07T08:41:49.556Z - info: Using devices:

2016-01-07T08:41:49.558Z - info: Apple-Iphone5s-1

2016-01-07T08:41:49.559Z - info: Apple-IpadAir2-1

2016-01-07T08:41:49.560Z - info: Apple-Iphone5-1

2016-01-07T08:41:49.563Z - info: Apple-Iphone6-1

2016-01-07T08:41:49.569Z - info: Starting test: with 4 devices (ios)

2016-01-07T08:41:49.696Z - debug: Device presented: G4-1 (android) perftest socket:15

2016-01-07T08:41:56.865Z - debug: Device presented: S5mini-1 (android) perftest socket:16

2016-01-07T08:41:57.704Z - debug: Socket disconnected: transport close 16 (S5mini-1)

2016-01-07T08:43:29.792Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":100029,"result":"TIMEOUT","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.Xe0AvA==","peerAvailable":true,"time":1084},{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.qqPEfA==","peerAvailable":true,"time":2126},{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.TWDlRQ==","peerAvailable":true,"time":2291}]} Apple-IpadAir2-1 ios (4 left)

2016-01-07T08:43:29.859Z - info: Received results for {"name:":"Apple-Iphone6-1","time":100030,"result":"TIMEOUT","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-Iphone5-1.Xe0AvA==","peerAvailable":true,"time":1265},{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.ujszBw==","peerAvailable":true,"time":1718},{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.TWDlRQ==","peerAvailable":true,"time":3288}]} Apple-Iphone6-1 ios (3 left)

2016-01-07T08:43:29.873Z - info: Received results for {"name:":"Apple-Iphone5-1","time":100024,"result":"TIMEOUT","peersList":[{"peerName":"(null)","peerIdentifier":"Apple-IpadAir2-1.ujszBw==","peerAvailable":true,"time":3202},{"peerName":"(null)","peerIdentifier":"Apple-Iphone5s-1.TWDlRQ==","peerAvailable":false,"time":89805},{"peerName":"(null)","peerIdentifier":"Apple-Iphone6-1.qqPEfA==","peerAvailable":true,"time":4741}]} Apple-Iphone5-1 ios (2 left)

2016-01-07T08:43:36.301Z - debug: Socket disconnected: ping timeout 1 (Apple-Iphone5s-1)

2016-01-07T08:43:45.495Z - info: Start timeout elapsed for platform: android

2016-01-07T08:43:45.499Z - info: Starting perf test run for platform: android

2016-01-07T08:43:45.500Z - info: Using devices:

2016-01-07T08:43:45.501Z - info: XT1072
2016-01-07T08:43:45.502Z - info: Note4-1

2016-01-07T08:43:45.503Z - info: Thali Test (Galaxy A5)
2016-01-07T08:43:45.503Z - info: G3-1
2016-01-07T08:43:45.504Z - info: Nexus 5

2016-01-07T08:43:45.505Z - info: Thali Test (Galaxy A3)
2016-01-07T08:43:45.505Z - info: S5-1

2016-01-07T08:43:45.506Z - info: HTC One M8s
2016-01-07T08:43:45.507Z - info: A3-1

2016-01-07T08:43:45.507Z - info: A5-1
2016-01-07T08:43:45.508Z - info: Thali Test (Galaxy S5)

2016-01-07T08:43:45.509Z - info: G4-1
2016-01-07T08:43:45.509Z - info: S5mini-1

2016-01-07T08:43:45.510Z - info: Starting test: with 13 devices (android)

2016-01-07T08:43:46.161Z - info: Start timeout elapsed for platform: ios
2016-01-07T08:43:46.162Z - info: Tests for ios already running or completed

2016-01-07T08:43:49.572Z - info: server timeout for test: testFindPeers.js (ios)

2016-01-07T08:43:49.576Z - info: All test data retrieved for testFindPeers.js (ios)

2016-01-07T08:43:49.579Z - info: No results from Apple-Iphone5s-1

2016-01-07T08:43:49.584Z - info: Remaining tests: %s ios=[testSendData.js], android=[testFindPeers.js, testSendData.js]

2016-01-07T08:43:49.589Z - info: Continuing to next test: testSendData.js
2016-01-07T08:43:49.590Z - info: Starting test: with 4 devices (ios)

2016-01-07T08:45:25.791Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100078,"result":"TIMEOUT","peersList":[{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":40003},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":40027},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":40148},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":40352},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":90367}]} Thali Test (Galaxy A3) android (13 left)

2016-01-07T08:45:25.828Z - info: Received results for {"name:":"HTC One M8s","time":100069,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":false,"time":63910},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":40774},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":40926},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":78024},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":79412}]} HTC One M8s android (12 left)

2016-01-07T08:45:25.950Z - info: Received results for {"name:":"Nexus 5","time":100071,"result":"TIMEOUT","peersList":[{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":57946},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":58125},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":74323},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":75544}]} Nexus 5 android (11 left)

2016-01-07T08:45:26.043Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100074,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3240},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":41041},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":41141},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":41167},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":41245},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":78876},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":86077},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":91389},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":95932}]} Thali Test (Galaxy A5) android (10 left)

2016-01-07T08:45:26.199Z - info: Received results for {"name:":"XT1072","time":100166,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":false,"time":62890},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":3272},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":3399},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":39256},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":39410}]} XT1072 android (9 left)

2016-01-07T08:45:26.229Z - info: Received results for {"name:":"G3-1","time":100078,"result":"TIMEOUT","peersList":[{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":14517},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":14549},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":26291},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":39426},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":39609},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":39679},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":40839},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":53734},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":90678}]} G3-1 android (8 left)

2016-01-07T08:45:26.234Z - info: Received results for {"name:":"Note4-1","time":100069,"result":"TIMEOUT","peersList":[{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":53814},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":73620},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":73941},{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":75138},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":76182},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":80606},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":82677},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":90239}]} Note4-1 android (7 left)

2016-01-07T08:45:26.245Z - info: Received results for {"name:":"A3-1","time":100081,"result":"TIMEOUT","peersList":[{"peerName":"Nexus 5","peerIdentifier":"34:FC:EF:11:AE:67","peerAvailable":true,"time":3147},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":3190},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":3280},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":3654},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":3755},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":9337},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":14736},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":18769},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":36237},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":36765},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":40580}]} A3-1 android (6 left)

2016-01-07T08:45:26.683Z - info: Received results for {"name:":"G4-1","time":100230,"result":"TIMEOUT","peersList":[{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":23200},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":31313},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":31359},{"peerName":"S5-1","peerIdentifier":"7C:F9:0E:34:8A:A0","peerAvailable":true,"time":47713},{"peerName":"A5-1","peerIdentifier":"7C:F9:0E:37:96:AB","peerAvailable":true,"time":53746},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":79050},{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":79159}]} G4-1 android (5 left)

2016-01-07T08:45:26.694Z - info: Received results for {"name:":"A5-1","time":100065,"result":"TIMEOUT","peersList":[{"peerName":"XT1072","peerIdentifier":"44:80:EB:7B:5A:05","peerAvailable":true,"time":3565},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":3721},{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":3779},{"peerName":"A3-1","peerIdentifier":"08:EC:A9:50:75:41","peerAvailable":true,"time":4064},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":4305},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":96920},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":53672},{"peerName":"Thali Test (Galaxy S5)","peerIdentifier":"B0:C5:59:3F:75:69","peerAvailable":true,"time":91932},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":93225}]} A5-1 android (4 left)

2016-01-07T08:45:26.948Z - info: Received results for {"name:":"S5-1","time":100104,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":3784},{"peerName":"HTC One M8s","peerIdentifier":"90:E7:C4:F6:69:77","peerAvailable":true,"time":3838},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":33919}]} S5-1 android (3 left)

2016-01-07T08:45:28.600Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100127,"result":"TIMEOUT","peersList":[{"peerName":"Thali Test (Galaxy A3)","peerIdentifier":"08:EC:A9:50:76:27","peerAvailable":true,"time":3762},{"peerName":"G4-1","peerIdentifier":"F8:95:C7:87:3C:51","peerAvailable":true,"time":17034},{"peerName":"Note4-1","peerIdentifier":"E0:DB:10:14:E2:C0","peerAvailable":true,"time":82789},{"peerName":"Thali Test (Galaxy A5)","peerIdentifier":"7C:F9:0E:51:18:22","peerAvailable":true,"time":94315},{"peerName":"G3-1","peerIdentifier":"58:3F:54:73:64:C0","peerAvailable":true,"time":97200}]} Thali Test (Galaxy S5) android (2 left)

2016-01-07T08:45:29.869Z - info: Received results for {"name:":"Apple-IpadAir2-1","time":100054,"result":"TIMEOUT","sendList":[{"connections":1,"name":"","time":0,"result":"Fail"},{"connections":0,"name":"","time":0,"result":"Fail"}]} Apple-IpadAir2-1 ios (4 left)

2016-01-07T08:45:30.282Z - info: Received results for {"name:":"Apple-Iphone5-1","time":100056,"result":"TIMEOUT","sendList":[{"connections":1,"name":"","time":0,"result":"Fail"},{"connections":0,"name":"","time":0,"result":"Fail"}]} Apple-Iphone5-1 ios (3 left)

2016-01-07T08:45:30.917Z - info: Received results for {"name:":"Apple-Iphone6-1","time":100065,"result":"TIMEOUT","sendList":[{"connections":1,"name":"","time":0,"result":"Fail"},{"connections":0,"name":"","time":0,"result":"Fail"}]} Apple-Iphone6-1 ios (2 left)

2016-01-07T08:45:45.520Z - info: server timeout for test: testFindPeers.js (android)

2016-01-07T08:45:45.521Z - info: All test data retrieved for testFindPeers.js (android)

2016-01-07T08:45:45.541Z - info: No results from S5mini-1

2016-01-07T08:45:45.542Z - info: Remaining tests: %s ios=[testSendData.js], android=[testSendData.js]

2016-01-07T08:45:45.546Z - info: Continuing to next test: testSendData.js

2016-01-07T08:45:45.547Z - info: Starting test: with 13 devices (android)

2016-01-07T08:45:49.614Z - info: server timeout for test: testSendData.js (ios)
2016-01-07T08:45:49.615Z - info: All test data retrieved for testSendData.js (ios)

2016-01-07T08:45:49.618Z - info: No results from Apple-Iphone5s-1

2016-01-07T08:45:49.622Z - info: Remaining tests: %s ios=[], android=[testSendData.js]

2016-01-07T08:45:49.625Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 100029,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.Xe0AvA==',
       peerAvailable: true,
       time: 1084 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.qqPEfA==',
       peerAvailable: true,
       time: 2126 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.TWDlRQ==',
       peerAvailable: true,
       time: 2291 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 100024,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.ujszBw==',
       peerAvailable: true,
       time: 3202 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.TWDlRQ==',
       peerAvailable: false,
       time: 89805 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.qqPEfA==',
       peerAvailable: true,
       time: 4741 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100030,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.Xe0AvA==',
       peerAvailable: true,
       time: 1265 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.ujszBw==',
       peerAvailable: true,
       time: 1718 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.TWDlRQ==',
       peerAvailable: true,
       time: 3288 } ] }

{ 'name:': 'XT1072',
  time: 100166,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: false,
       time: 62890 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3272 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 3399 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 39256 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 39410 } ] }

{ 'name:': 'Note4-1',
  time: 100069,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 53814 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 73620 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 73941 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 75138 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 76182 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 80606 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 82677 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 90239 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100074,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3240 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 41041 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 41141 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 41167 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 41245 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 78876 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 86077 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 91389 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 95932 } ] }

{ 'name:': 'G3-1',
  time: 100078,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 14517 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 14549 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 26291 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 39426 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 39609 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 39679 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 40839 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 53734 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 90678 } ] }

{ 'name:': 'Nexus 5',
  time: 100071,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 57946 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 58125 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 74323 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 75544 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100078,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 40003 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 40027 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 40148 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 40352 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 90367 } ] }

{ 'name:': 'S5-1',
  time: 100104,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3784 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 3838 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 33919 } ] }

{ 'name:': 'HTC One M8s',
  time: 100069,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: false,
       time: 63910 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 40774 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 40926 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 78024 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 79412 } ] }

{ 'name:': 'A3-1',
  time: 100081,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3147 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3190 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3280 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 3654 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3755 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 9337 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 14736 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 18769 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 36237 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 36765 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 40580 } ] }

{ 'name:': 'A5-1',
  time: 100065,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 3565 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 3721 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3779 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 4064 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 4305 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 96920 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 53672 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 91932 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 93225 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100127,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3762 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 17034 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 82789 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 94315 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 97200 } ] }

{ 'name:': 'G4-1',
  time: 100230,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 23200 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 31313 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 31359 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 47713 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 53746 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 79050 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 79159 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 100054,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1, name: '', time: 0, result: 'Fail' },
     { connections: 0, name: '', time: 0, result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 100056,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1, name: '', time: 0, result: 'Fail' },
     { connections: 0, name: '', time: 0, result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100065,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1, name: '', time: 0, result: 'Fail' },
     { connections: 0, name: '', time: 0, result: 'Fail' } ] }

--------------- test report ---------------------

--------------- Apple-IpadAir2-1 --------------------- : 1

Find peers : 100% : 2291 ms, 99% : 2291 ms, 95 : 2291 ms, 90% : 2291 ms.

Result count 3, range 1084 ms to  2291 ms.

No send data results!

--------------- Apple-Iphone5-1 --------------------- : 2

Find peers : 100% : 89805 ms, 99% : 89805 ms, 95 : 89805 ms, 90% : 89805 ms.

Result count 3, range 3202 ms to  89805 ms.

No send data results!

--------------- Apple-Iphone6-1 --------------------- : 3

Find peers : 100% : 3288 ms, 99% : 3288 ms, 95 : 3288 ms, 90% : 3288 ms.

Result count 3, range 1265 ms to  3288 ms.

No send data results!

--------------- XT1072 --------------------- : 4

Find peers : 100% : 62890 ms, 99% : 62890 ms, 95 : 62890 ms, 90% : 62890 ms.

Result count 5, range 3272 ms to  62890 ms.

--------------- Note4-1 --------------------- : 5

Find peers : 100% : 90239 ms, 99% : 90239 ms, 95 : 90239 ms, 90% : 82677 ms.

Result count 8, range 53814 ms to  90239 ms.
--------------- Thali Test (Galaxy A5) --------------------- : 6
Find peers : 100% : 95932 ms, 99% : 95932 ms, 95 : 95932 ms, 90% : 91389 ms.
Result count 9, range 3240 ms to  95932 ms.
--------------- G3-1 --------------------- : 7
Find peers : 100% : 90678 ms, 99% : 90678 ms, 95 : 90678 ms, 90% : 53734 ms.
Result count 9, range 14517 ms to  90678 ms.
--------------- Nexus 5 --------------------- : 8
Find peers : 100% : 75544 ms, 99% : 75544 ms, 95 : 75544 ms, 90% : 75544 ms.
Result count 4, range 57946 ms to  75544 ms.
--------------- Thali Test (Galaxy A3) --------------------- : 9
Find peers : 100% : 90367 ms, 99% : 90367 ms, 95 : 90367 ms, 90% : 90367 ms.
Result count 5, range 40003 ms to  90367 ms.
--------------- S5-1 --------------------- : 10
Find peers : 100% : 33919 ms, 99% : 33919 ms, 95 : 33919 ms, 90% : 33919 ms.
Result count 3, range 3784 ms to  33919 ms.
--------------- HTC One M8s --------------------- : 11
Find peers : 100% : 79412 ms, 99% : 79412 ms, 95 : 79412 ms, 90% : 79412 ms.
Result count 5, range 40774 ms to  79412 ms.
--------------- A3-1 --------------------- : 12
Find peers : 100% : 40580 ms, 99% : 40580 ms, 95 : 36765 ms, 90% : 36765 ms.
Result count 11, range 3147 ms to  40580 ms.
--------------- A5-1 --------------------- : 13
Find peers : 100% : 96920 ms, 99% : 96920 ms, 95 : 96920 ms, 90% : 93225 ms.
Result count 9, range 3565 ms to  96920 ms.

--------------- Thali Test (Galaxy S5) --------------------- : 14

Find peers : 100% : 97200 ms, 99% : 97200 ms, 95 : 97200 ms, 90% : 97200 ms.

Result count 5, range 3762 ms to  97200 ms.

--------------- G4-1 --------------------- : 15
Find peers : 100% : 79159 ms, 99% : 79159 ms, 95 : 79159 ms, 90% : 79050 ms.
Result count 7, range 23200 ms to  79159 ms.
--------------- Combined ---------------------
Find peers : 100% : 97200 ms, 99% : 96920 ms, 95 : 93225 ms, 90% : 90239 ms.
--------------- end of test report ---------------------

2016-01-07T08:45:49.943Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.Xe0AvA==, peerAvailable=true, time=1084, peerName=(null), peerIdentifier=Apple-Iphone6-1.qqPEfA==, peerAvailable=true, time=2126, peerName=(null), peerIdentifier=Apple-Iphone5s-1.TWDlRQ==, peerAvailable=true, time=2291], sendList=[], failedPeer=[connections=1, name=, time=0, result=Fail], notTriedList=[connections=0, name=, time=0, result=Fail], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.ujszBw==, peerAvailable=true, time=3202, peerName=(null), peerIdentifier=Apple-Iphone6-1.qqPEfA==, peerAvailable=true, time=4741, peerName=(null), peerIdentifier=Apple-Iphone5s-1.TWDlRQ==, peerAvailable=false, time=89805], sendList=[], failedPeer=[connections=1, name=, time=0, result=Fail], notTriedList=[connections=0, name=, time=0, result=Fail], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.Xe0AvA==, peerAvailable=true, time=1265, peerName=(null), peerIdentifier=Apple-IpadAir2-1.ujszBw==, peerAvailable=true, time=1718, peerName=(null), peerIdentifier=Apple-Iphone5s-1.TWDlRQ==, peerAvailable=true, time=3288], sendList=[], failedPeer=[connections=1, name=, time=0, result=Fail], notTriedList=[connections=0, name=, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3272, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=3399, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=39256, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=39410, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=false, time=62890], peersList=[peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=53814, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=73620, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=73941, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=75138, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=76182, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=80606, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=82677, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=90239], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3240, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=41041, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=41141, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=41167, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=41245, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=78876, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=86077, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=91389, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=95932], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=14517, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=14549, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=26291, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=39426, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=39609, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=39679, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=40839, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=53734, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=90678], peersList=[peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=57946, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=58125, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=74323, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=75544], peersList=[peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=40003, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=40027, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=40148, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=40352, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=90367], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3784, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=3838, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=33919], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=40774, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=40926, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=false, time=63910, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=78024, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=79412], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3147, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=3190, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3280, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=3654, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3755, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=9337, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=14736, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=18769, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=36237, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=36765, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=40580], peersList=[peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=3565, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=3721, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3779, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=4064, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=4305, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=53672, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=91932, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=93225, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=96920], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3762, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=17034, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=82789, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=94315, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=97200], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=23200, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=31313, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=31359, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=47713, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=53746, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=79050, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=79159]

2016-01-07T08:45:49.966Z - debug: end to Apple-Iphone5s-1

2016-01-07T08:45:49.970Z - debug: end to Apple-IpadAir2-1

2016-01-07T08:45:49.972Z - debug: end to Apple-Iphone5-1
2016-01-07T08:45:49.983Z - debug: end to Apple-Iphone6-1

2016-01-07T08:45:52.555Z - debug: Socket disconnected: transport close 8 (Apple-IpadAir2-1)

2016-01-07T08:45:52.668Z - debug: Socket disconnected: transport close 14 (Apple-Iphone6-1)

2016-01-07T08:45:53.144Z - debug: Socket disconnected: transport close 13 (Apple-Iphone5-1)

2016-01-07T08:47:25.871Z - info: Received results for {"name:":"Thali Test (Galaxy S5)","time":100105,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":33711,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"7C:F9:0E:34:8A:A0","time":15429,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"F8:95:C7:87:3C:51","time":13546,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"34:FC:EF:11:AE:67","time":5275,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"}]} Thali Test (Galaxy S5) android (13 left)

2016-01-07T08:47:25.896Z - info: Received results for {"name:":"XT1072","time":100071,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:76:27","time":66048,"result":"OK","connections":4,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"}]} XT1072 android (12 left)

2016-01-07T08:47:25.963Z - info: Received results for {"name:":"Note4-1","time":100114,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":36414,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"90:E7:C4:F6:69:77","time":12643,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"}]} Note4-1 android (11 left)

2016-01-07T08:47:25.972Z - info: Received results for {"name:":"S5-1","time":100093,"result":"TIMEOUT","sendList":[{"name":"08:EC:A9:50:75:41","time":57017,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"E0:DB:10:14:E2:C0","time":17333,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"}]} S5-1 android (10 left)

2016-01-07T08:47:26.532Z - info: Received results for {"name:":"Nexus 5","time":100049,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":29229,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"}]} Nexus 5 android (9 left)

2016-01-07T08:47:27.637Z - info: Received results for {"name:":"Thali Test (Galaxy A3)","time":100080,"result":"TIMEOUT","sendList":[{"name":"44:80:EB:7B:5A:05","time":9786,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"B0:C5:59:3F:75:69","time":19417,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"}]} Thali Test (Galaxy A3) android (8 left)

2016-01-07T08:47:27.989Z - info: Received results for {"name:":"A5-1","time":100082,"result":"TIMEOUT","sendList":[{"name":"58:3F:54:73:64:C0","time":35648,"result":"OK","connections":2,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"}]} A5-1 android (7 left)

2016-01-07T08:47:28.462Z - info: Received results for {"name:":"G4-1","time":100071,"result":"TIMEOUT","sendList":[{"name":"B0:C5:59:3F:75:69","time":7935,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"name":"08:EC:A9:50:76:27","time":68000,"result":"OK","connections":4,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"}]} G4-1 android (6 left)

2016-01-07T08:47:30.401Z - info: Received results for {"name:":"Thali Test (Galaxy A5)","time":100075,"result":"TIMEOUT","sendList":[{"connections":1,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":1,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"}]} Thali Test (Galaxy A5) android (5 left)

2016-01-07T08:47:30.778Z - info: Received results for {"name:":"A3-1","time":100075,"result":"TIMEOUT","sendList":[{"name":"34:FC:EF:11:AE:67","time":9552,"result":"OK","connections":1,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:51:18:22","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"},{"connections":0,"name":"58:3F:54:73:64:C0","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"}]} A3-1 android (4 left)

2016-01-07T08:47:45.550Z - info: server timeout for test: testSendData.js (android)

2016-01-07T08:47:45.551Z - info: All test data retrieved for testSendData.js (android)

2016-01-07T08:47:45.556Z - info: No results from G3-1

2016-01-07T08:47:45.560Z - info: No results from HTC One M8s

2016-01-07T08:47:45.567Z - info: No results from S5mini-1

2016-01-07T08:47:45.568Z - info: Remaining tests: %s ios=[], android=[]

2016-01-07T08:47:45.569Z - info: ALL DONE !!!

{ 'name:': 'Apple-IpadAir2-1',
  time: 100029,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.Xe0AvA==',
       peerAvailable: true,
       time: 1084 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.qqPEfA==',
       peerAvailable: true,
       time: 2126 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.TWDlRQ==',
       peerAvailable: true,
       time: 2291 } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 100024,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.ujszBw==',
       peerAvailable: true,
       time: 3202 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone6-1.qqPEfA==',
       peerAvailable: true,
       time: 4741 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.TWDlRQ==',
       peerAvailable: false,
       time: 89805 } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100030,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5-1.Xe0AvA==',
       peerAvailable: true,
       time: 1265 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-IpadAir2-1.ujszBw==',
       peerAvailable: true,
       time: 1718 },
     { peerName: '(null)',
       peerIdentifier: 'Apple-Iphone5s-1.TWDlRQ==',
       peerAvailable: true,
       time: 3288 } ] }

{ 'name:': 'XT1072',
  time: 100166,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3272 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 3399 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 39256 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 39410 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: false,
       time: 62890 } ] }

{ 'name:': 'Note4-1',
  time: 100069,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 53814 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 73620 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 73941 },
     { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 75138 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 76182 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 80606 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 82677 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 90239 } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100074,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3240 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 41041 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 41141 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 41167 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 41245 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 78876 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 86077 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 91389 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 95932 } ] }

{ 'name:': 'G3-1',
  time: 100078,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 14517 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 14549 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 26291 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 39426 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 39609 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 39679 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 40839 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 53734 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 90678 } ] }

{ 'name:': 'Nexus 5',
  time: 100071,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 57946 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 58125 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 74323 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 75544 } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100078,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 40003 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 40027 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 40148 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 40352 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 90367 } ] }

{ 'name:': 'S5-1',
  time: 100104,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3784 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 3838 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 33919 } ] }

{ 'name:': 'HTC One M8s',
  time: 100069,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 40774 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 40926 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: false,
       time: 63910 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 78024 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 79412 } ] }

{ 'name:': 'A3-1',
  time: 100081,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Nexus 5',
       peerIdentifier: '34:FC:EF:11:AE:67',
       peerAvailable: true,
       time: 3147 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 3190 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3280 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 3654 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 3755 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 9337 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 14736 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 18769 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 36237 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 36765 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 40580 } ] }

{ 'name:': 'A5-1',
  time: 100065,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 3565 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 3721 },
     { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3779 },
     { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 4064 },
     { peerName: 'HTC One M8s',
       peerIdentifier: '90:E7:C4:F6:69:77',
       peerAvailable: true,
       time: 4305 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 53672 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 91932 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 93225 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 96920 } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100127,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'Thali Test (Galaxy A3)',
       peerIdentifier: '08:EC:A9:50:76:27',
       peerAvailable: true,
       time: 3762 },
     { peerName: 'G4-1',
       peerIdentifier: 'F8:95:C7:87:3C:51',
       peerAvailable: true,
       time: 17034 },
     { peerName: 'Note4-1',
       peerIdentifier: 'E0:DB:10:14:E2:C0',
       peerAvailable: true,
       time: 82789 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 94315 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 97200 } ] }

{ 'name:': 'G4-1',
  time: 100230,
  result: 'TIMEOUT',
  peersList: 
   [ { peerName: 'A3-1',
       peerIdentifier: '08:EC:A9:50:75:41',
       peerAvailable: true,
       time: 23200 },
     { peerName: 'G3-1',
       peerIdentifier: '58:3F:54:73:64:C0',
       peerAvailable: true,
       time: 31313 },
     { peerName: 'Thali Test (Galaxy S5)',
       peerIdentifier: 'B0:C5:59:3F:75:69',
       peerAvailable: true,
       time: 31359 },
     { peerName: 'S5-1',
       peerIdentifier: '7C:F9:0E:34:8A:A0',
       peerAvailable: true,
       time: 47713 },
     { peerName: 'A5-1',
       peerIdentifier: '7C:F9:0E:37:96:AB',
       peerAvailable: true,
       time: 53746 },
     { peerName: 'Thali Test (Galaxy A5)',
       peerIdentifier: '7C:F9:0E:51:18:22',
       peerAvailable: true,
       time: 79050 },
     { peerName: 'XT1072',
       peerIdentifier: '44:80:EB:7B:5A:05',
       peerAvailable: true,
       time: 79159 } ] }

{ 'name:': 'Apple-IpadAir2-1',
  time: 100054,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1, name: '', time: 0, result: 'Fail' },
     { connections: 0, name: '', time: 0, result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone5-1',
  time: 100056,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1, name: '', time: 0, result: 'Fail' },
     { connections: 0, name: '', time: 0, result: 'Fail' } ] }

{ 'name:': 'Apple-Iphone6-1',
  time: 100065,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1, name: '', time: 0, result: 'Fail' },
     { connections: 0, name: '', time: 0, result: 'Fail' } ] }

{ 'name:': 'XT1072',
  time: 100071,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 66048,
       result: 'OK',
       connections: 4,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Note4-1',
  time: 100114,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 36414,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '90:E7:C4:F6:69:77',
       time: 12643,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A5)',
  time: 100075,
  result: 'TIMEOUT',
  sendList: 
   [ { connections: 1,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 1,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Nexus 5',
  time: 100049,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '44:80:EB:7B:5A:05',
       time: 29229,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy A3)',
  time: 100080,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '44:80:EB:7B:5A:05',
       time: 9786,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'B0:C5:59:3F:75:69',
       time: 19417,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'S5-1',
  time: 100093,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:75:41',
       time: 57017,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'E0:DB:10:14:E2:C0',
       time: 17333,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A3-1',
  time: 100075,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '34:FC:EF:11:AE:67',
       time: 9552,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'A5-1',
  time: 100082,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '58:3F:54:73:64:C0',
       time: 35648,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'B0:C5:59:3F:75:69',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'F8:95:C7:87:3C:51',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:76:27',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'Thali Test (Galaxy S5)',
  time: 100105,
  result: 'TIMEOUT',
  sendList: 
   [ { name: '08:EC:A9:50:76:27',
       time: 33711,
       result: 'OK',
       connections: 2,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '7C:F9:0E:34:8A:A0',
       time: 15429,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: 'F8:95:C7:87:3C:51',
       time: 13546,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '34:FC:EF:11:AE:67',
       time: 5275,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' } ] }

{ 'name:': 'G4-1',
  time: 100071,
  result: 'TIMEOUT',
  sendList: 
   [ { name: 'B0:C5:59:3F:75:69',
       time: 7935,
       result: 'OK',
       connections: 1,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { name: '08:EC:A9:50:76:27',
       time: 68000,
       result: 'OK',
       connections: 4,
       tryCount: 1,
       doneRounds: 1,
       dataAmount: 100000,
       dataReceived: 100000 },
     { connections: 1,
       name: '58:3F:54:73:64:C0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '44:80:EB:7B:5A:05',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '00:F4:6F:30:E0:6C',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '08:EC:A9:50:75:41',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:51:18:22',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '34:FC:EF:11:AE:67',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:34:8A:A0',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '90:E7:C4:F6:69:77',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: '7C:F9:0E:37:96:AB',
       time: 0,
       result: 'Fail' },
     { connections: 0,
       name: 'E0:DB:10:14:E2:C0',
       time: 0,
       result: 'Fail' } ] }

--------------- test report ---------------------
--------------- Apple-IpadAir2-1 --------------------- : 1
Find peers : 100% : 2291 ms, 99% : 2291 ms, 95 : 2291 ms, 90% : 2291 ms.
Result count 3, range 1084 ms to  2291 ms.

No send data results!
--------------- Apple-Iphone5-1 --------------------- : 2

Find peers : 100% : 89805 ms, 99% : 89805 ms, 95 : 89805 ms, 90% : 89805 ms.
Result count 3, range 3202 ms to  89805 ms.

No send data results!
--------------- Apple-Iphone6-1 --------------------- : 3
Find peers : 100% : 3288 ms, 99% : 3288 ms, 95 : 3288 ms, 90% : 3288 ms.
Result count 3, range 1265 ms to  3288 ms.

No send data results!
--------------- XT1072 --------------------- : 4
Find peers : 100% : 62890 ms, 99% : 62890 ms, 95 : 62890 ms, 90% : 62890 ms.
Result count 5, range 3272 ms to  62890 ms.

Send data : 100% : 66048 ms, 99% : 66048 ms, 95 : 66048 ms, 90% : 66048 ms.

Average data rate: 0.002 MB/s

Result count 1, range 66048 ms to  66048 ms.

Send data failed peers count : 1 [50 %]

- Peer ID : 58:3F:54:73:64:C0, Tried : 1

Send data never tried peers count : 10 [83.33333333333333 %]
- Peer ID : 00:F4:6F:30:E0:6C

- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 90:E7:C4:F6:69:77

- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:51:18:22
--------------- Note4-1 --------------------- : 5
Find peers : 100% : 90239 ms, 99% : 90239 ms, 95 : 90239 ms, 90% : 82677 ms.
Result count 8, range 53814 ms to  90239 ms.
Send data : 100% : 36414 ms, 99% : 36414 ms, 95 : 36414 ms, 90% : 36414 ms.
Average data rate: 0.004 MB/s
Result count 2, range 12643 ms to  36414 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 9 [75 %]
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0
--------------- Thali Test (Galaxy A5) --------------------- : 6
Find peers : 100% : 95932 ms, 99% : 95932 ms, 95 : 95932 ms, 90% : 91389 ms.
Result count 9, range 3240 ms to  95932 ms.
No send data results!
--------------- G3-1 --------------------- : 7
Find peers : 100% : 90678 ms, 99% : 90678 ms, 95 : 90678 ms, 90% : 53734 ms.
Result count 9, range 14517 ms to  90678 ms.
--------------- Nexus 5 --------------------- : 8
Find peers : 100% : 75544 ms, 99% : 75544 ms, 95 : 75544 ms, 90% : 75544 ms.
Result count 4, range 57946 ms to  75544 ms.
Send data : 100% : 29229 ms, 99% : 29229 ms, 95 : 29229 ms, 90% : 29229 ms.
Average data rate: 0.003 MB/s
Result count 1, range 29229 ms to  29229 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
Send data never tried peers count : 10 [83.33333333333333 %]
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 08:EC:A9:50:76:27
--------------- Thali Test (Galaxy A3) --------------------- : 9
Find peers : 100% : 90367 ms, 99% : 90367 ms, 95 : 90367 ms, 90% : 90367 ms.
Result count 5, range 40003 ms to  90367 ms.
Send data : 100% : 19417 ms, 99% : 19417 ms, 95 : 19417 ms, 90% : 19417 ms.
Average data rate: 0.007 MB/s
Result count 2, range 9786 ms to  19417 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 00:F4:6F:30:E0:6C, Tried : 1
Send data never tried peers count : 9 [75 %]
- Peer ID : 08:EC:A9:50:75:41

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 34:FC:EF:11:AE:67
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 58:3F:54:73:64:C0
--------------- S5-1 --------------------- : 10
Find peers : 100% : 33919 ms, 99% : 33919 ms, 95 : 33919 ms, 90% : 33919 ms.

Result count 3, range 3784 ms to  33919 ms.
Send data : 100% : 57017 ms, 99% : 57017 ms, 95 : 57017 ms, 90% : 57017 ms.
Average data rate: 0.003 MB/s
Result count 2, range 17333 ms to  57017 ms.

Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
Send data never tried peers count : 9 [75 %]
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 44:80:EB:7B:5A:05

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 7C:F9:0E:51:18:22
--------------- HTC One M8s --------------------- : 11
Find peers : 100% : 79412 ms, 99% : 79412 ms, 95 : 79412 ms, 90% : 79412 ms.
Result count 5, range 40774 ms to  79412 ms.
--------------- A3-1 --------------------- : 12
Find peers : 100% : 40580 ms, 99% : 40580 ms, 95 : 36765 ms, 90% : 36765 ms.
Result count 11, range 3147 ms to  40580 ms.
Send data : 100% : 9552 ms, 99% : 9552 ms, 95 : 9552 ms, 90% : 9552 ms.
Average data rate: 0.01 MB/s
Result count 1, range 9552 ms to  9552 ms.
Send data failed peers count : 1 [50 %]
- Peer ID : 08:EC:A9:50:76:27, Tried : 1
Send data never tried peers count : 10 [83.33333333333333 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : F8:95:C7:87:3C:51
- Peer ID : 7C:F9:0E:37:96:AB

- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 58:3F:54:73:64:C0
- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 00:F4:6F:30:E0:6C
--------------- A5-1 --------------------- : 13
Find peers : 100% : 96920 ms, 99% : 96920 ms, 95 : 96920 ms, 90% : 93225 ms.
Result count 9, range 3565 ms to  96920 ms.

Send data : 100% : 35648 ms, 99% : 35648 ms, 95 : 35648 ms, 90% : 35648 ms.
Average data rate: 0.003 MB/s
Result count 1, range 35648 ms to  35648 ms.

Send data failed peers count : 1 [50 %]
- Peer ID : E0:DB:10:14:E2:C0, Tried : 1
Send data never tried peers count : 10 [83.33333333333333 %]
- Peer ID : B0:C5:59:3F:75:69
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : F8:95:C7:87:3C:51

- Peer ID : 08:EC:A9:50:76:27
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:34:8A:A0

--------------- Thali Test (Galaxy S5) --------------------- : 14
Find peers : 100% : 97200 ms, 99% : 97200 ms, 95 : 97200 ms, 90% : 97200 ms.
Result count 5, range 3762 ms to  97200 ms.

Send data : 100% : 33711 ms, 99% : 33711 ms, 95 : 33711 ms, 90% : 33711 ms.
Average data rate: 0.006 MB/s
Result count 4, range 5275 ms to  33711 ms.
Send data failed peers count : 1 [20 %]

- Peer ID : 58:3F:54:73:64:C0, Tried : 1
Send data never tried peers count : 7 [58.333333333333336 %]
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : E0:DB:10:14:E2:C0

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:75:41
--------------- G4-1 --------------------- : 15
Find peers : 100% : 79159 ms, 99% : 79159 ms, 95 : 79159 ms, 90% : 79050 ms.
Result count 7, range 23200 ms to  79159 ms.
Send data : 100% : 68000 ms, 99% : 68000 ms, 95 : 68000 ms, 90% : 68000 ms.
Average data rate: 0.003 MB/s

Result count 2, range 7935 ms to  68000 ms.
Send data failed peers count : 1 [33.333333333333336 %]
- Peer ID : 58:3F:54:73:64:C0, Tried : 1
Send data never tried peers count : 9 [75 %]

- Peer ID : 44:80:EB:7B:5A:05
- Peer ID : 00:F4:6F:30:E0:6C
- Peer ID : 08:EC:A9:50:75:41
- Peer ID : 7C:F9:0E:51:18:22
- Peer ID : 34:FC:EF:11:AE:67

- Peer ID : 7C:F9:0E:34:8A:A0
- Peer ID : 90:E7:C4:F6:69:77
- Peer ID : 7C:F9:0E:37:96:AB
- Peer ID : E0:DB:10:14:E2:C0

--------------- Combined ---------------------

Find peers : 100% : 97200 ms, 99% : 96920 ms, 95 : 93225 ms, 90% : 90239 ms.

Send data : 100% : 68000 ms, 99% : 68000 ms, 95 : 66048 ms, 90% : 57017 ms.
Average data rate: 0.004 MB/s
--------------- end of test report ---------------------

2016-01-07T08:47:45.997Z - info:  peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.Xe0AvA==, peerAvailable=true, time=1084, peerName=(null), peerIdentifier=Apple-Iphone6-1.qqPEfA==, peerAvailable=true, time=2126, peerName=(null), peerIdentifier=Apple-Iphone5s-1.TWDlRQ==, peerAvailable=true, time=2291], sendList=[], failedPeer=[connections=1, name=, time=0, result=Fail], notTriedList=[connections=0, name=, time=0, result=Fail], peersList=[peerName=(null), peerIdentifier=Apple-IpadAir2-1.ujszBw==, peerAvailable=true, time=3202, peerName=(null), peerIdentifier=Apple-Iphone6-1.qqPEfA==, peerAvailable=true, time=4741, peerName=(null), peerIdentifier=Apple-Iphone5s-1.TWDlRQ==, peerAvailable=false, time=89805], sendList=[], failedPeer=[connections=1, name=, time=0, result=Fail], notTriedList=[connections=0, name=, time=0, result=Fail], peersList=[peerName=(null), peerIdentifier=Apple-Iphone5-1.Xe0AvA==, peerAvailable=true, time=1265, peerName=(null), peerIdentifier=Apple-IpadAir2-1.ujszBw==, peerAvailable=true, time=1718, peerName=(null), peerIdentifier=Apple-Iphone5s-1.TWDlRQ==, peerAvailable=true, time=3288], sendList=[], failedPeer=[connections=1, name=, time=0, result=Fail], notTriedList=[connections=0, name=, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3272, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=3399, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=39256, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=39410, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=false, time=62890], sendList=[name=08:EC:A9:50:76:27, time=66048, result=OK, connections=4, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=58:3F:54:73:64:C0, time=0, result=Fail], notTriedList=[connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail], peersList=[peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=53814, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=73620, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=73941, peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=75138, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=76182, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=80606, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=82677, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=90239], sendList=[name=90:E7:C4:F6:69:77, time=12643, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=58:3F:54:73:64:C0, time=36414, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3240, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=41041, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=41141, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=41167, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=41245, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=78876, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=86077, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=91389, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=95932], sendList=[], failedPeer=[connections=1, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=1, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], notTriedList=[connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail], peersList=[peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=14517, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=14549, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=26291, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=39426, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=39609, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=39679, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=40839, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=53734, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=90678], peersList=[peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=57946, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=58125, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=74323, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=75544], sendList=[name=44:80:EB:7B:5A:05, time=29229, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=58:3F:54:73:64:C0, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail], peersList=[peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=40003, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=40027, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=40148, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=40352, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=90367], sendList=[name=44:80:EB:7B:5A:05, time=9786, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=B0:C5:59:3F:75:69, time=19417, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=00:F4:6F:30:E0:6C, time=0, result=Fail], notTriedList=[connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3784, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=3838, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=33919], sendList=[name=E0:DB:10:14:E2:C0, time=17333, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:75:41, time=57017, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=58:3F:54:73:64:C0, time=0, result=Fail], notTriedList=[connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail], peersList=[peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=40774, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=40926, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=false, time=63910, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=78024, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=79412], peersList=[peerName=Nexus 5, peerIdentifier=34:FC:EF:11:AE:67, peerAvailable=true, time=3147, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=3190, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3280, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=3654, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=3755, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=9337, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=14736, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=18769, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=36237, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=36765, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=40580], sendList=[name=34:FC:EF:11:AE:67, time=9552, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=08:EC:A9:50:76:27, time=0, result=Fail], notTriedList=[connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=58:3F:54:73:64:C0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail], peersList=[peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=3565, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=3721, peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3779, peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=4064, peerName=HTC One M8s, peerIdentifier=90:E7:C4:F6:69:77, peerAvailable=true, time=4305, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=53672, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=91932, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=93225, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=96920], sendList=[name=58:3F:54:73:64:C0, time=35648, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=E0:DB:10:14:E2:C0, time=0, result=Fail], notTriedList=[connections=0, name=B0:C5:59:3F:75:69, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=F8:95:C7:87:3C:51, time=0, result=Fail, connections=0, name=08:EC:A9:50:76:27, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail], peersList=[peerName=Thali Test (Galaxy A3), peerIdentifier=08:EC:A9:50:76:27, peerAvailable=true, time=3762, peerName=G4-1, peerIdentifier=F8:95:C7:87:3C:51, peerAvailable=true, time=17034, peerName=Note4-1, peerIdentifier=E0:DB:10:14:E2:C0, peerAvailable=true, time=82789, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=94315, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=97200], sendList=[name=34:FC:EF:11:AE:67, time=5275, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=F8:95:C7:87:3C:51, time=13546, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=7C:F9:0E:34:8A:A0, time=15429, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=33711, result=OK, connections=2, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=58:3F:54:73:64:C0, time=0, result=Fail], notTriedList=[connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail, connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail], peersList=[peerName=A3-1, peerIdentifier=08:EC:A9:50:75:41, peerAvailable=true, time=23200, peerName=G3-1, peerIdentifier=58:3F:54:73:64:C0, peerAvailable=true, time=31313, peerName=Thali Test (Galaxy S5), peerIdentifier=B0:C5:59:3F:75:69, peerAvailable=true, time=31359, peerName=S5-1, peerIdentifier=7C:F9:0E:34:8A:A0, peerAvailable=true, time=47713, peerName=A5-1, peerIdentifier=7C:F9:0E:37:96:AB, peerAvailable=true, time=53746, peerName=Thali Test (Galaxy A5), peerIdentifier=7C:F9:0E:51:18:22, peerAvailable=true, time=79050, peerName=XT1072, peerIdentifier=44:80:EB:7B:5A:05, peerAvailable=true, time=79159], sendList=[name=B0:C5:59:3F:75:69, time=7935, result=OK, connections=1, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000, name=08:EC:A9:50:76:27, time=68000, result=OK, connections=4, tryCount=1, doneRounds=1, dataAmount=100000, dataReceived=100000], failedPeer=[connections=1, name=58:3F:54:73:64:C0, time=0, result=Fail], notTriedList=[connections=0, name=44:80:EB:7B:5A:05, time=0, result=Fail, connections=0, name=00:F4:6F:30:E0:6C, time=0, result=Fail, connections=0, name=08:EC:A9:50:75:41, time=0, result=Fail, connections=0, name=7C:F9:0E:51:18:22, time=0, result=Fail, connections=0, name=34:FC:EF:11:AE:67, time=0, result=Fail, connections=0, name=7C:F9:0E:34:8A:A0, time=0, result=Fail, connections=0, name=90:E7:C4:F6:69:77, time=0, result=Fail, connections=0, name=7C:F9:0E:37:96:AB, time=0, result=Fail, connections=0, name=E0:DB:10:14:E2:C0, time=0, result=Fail]

2016-01-07T08:47:46.041Z - debug: end to XT1072

2016-01-07T08:47:46.043Z - debug: end to Note4-1

2016-01-07T08:47:46.046Z - debug: end to Thali Test (Galaxy A5)

2016-01-07T08:47:46.047Z - debug: end to G3-1

2016-01-07T08:47:46.049Z - debug: end to Nexus 5

2016-01-07T08:47:46.050Z - debug: end to Thali Test (Galaxy A3)

2016-01-07T08:47:46.052Z - debug: end to S5-1

2016-01-07T08:47:46.056Z - debug: end to HTC One M8s

2016-01-07T08:47:46.057Z - debug: end to A3-1

2016-01-07T08:47:46.058Z - debug: end to A5-1

2016-01-07T08:47:46.060Z - debug: end to Thali Test (Galaxy S5)

2016-01-07T08:47:46.061Z - debug: end to G4-1

2016-01-07T08:47:46.062Z - debug: end to S5mini-1

2016-01-07T08:47:46.647Z - debug: Socket disconnected: transport close 5 (Nexus 5)

2016-01-07T08:47:46.806Z - debug: Socket disconnected: transport close 7 (Thali Test (Galaxy A3))

2016-01-07T08:47:47.088Z - debug: Socket disconnected: transport close 3 (Thali Test (Galaxy A5))

2016-01-07T08:47:47.126Z - debug: Socket disconnected: transport close 15 (G4-1)

2016-01-07T08:47:47.185Z - debug: Socket disconnected: transport close 10 (A3-1)

2016-01-07T08:47:48.086Z - debug: Socket disconnected: transport close 12 (Thali Test (Galaxy S5))

2016-01-07T08:47:48.321Z - debug: Socket disconnected: transport close 11 (A5-1)

2016-01-07T08:47:48.827Z - debug: Socket disconnected: transport close 2 (Note4-1)

2016-01-07T08:47:48.915Z - debug: Socket disconnected: transport close 6 (S5-1)

2016-01-07T08:47:50.226Z - debug: Socket disconnected: transport close 0 (XT1072)

2016-01-07T08:48:17.279Z - debug: Socket disconnected: ping timeout 9 (HTC One M8s)

2016-01-07T08:48:22.540Z - debug: Socket disconnected: ping timeout 4 (G3-1)

2016-01-07T08:48:24.586Z - debug: Device presented: G3-1 (android) perftest socket:17

2016-01-07T08:48:24.588Z - info: Updating existing device: G3-1 (2551ca9c-2313-438e-9851-08767a8fe4ea)

2016-01-07T08:48:24.620Z - info: Received results for {"name:":"G3-1","time":100101,"result":"TIMEOUT","sendList":[{"name":"7C:F9:0E:51:18:22","time":54168,"result":"OK","connections":3,"tryCount":1,"doneRounds":1,"dataAmount":100000,"dataReceived":100000},{"connections":1,"name":"08:EC:A9:50:76:27","time":0,"result":"Fail"},{"connections":0,"name":"44:80:EB:7B:5A:05","time":0,"result":"Fail"},{"connections":0,"name":"00:F4:6F:30:E0:6C","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:37:96:AB","time":0,"result":"Fail"},{"connections":0,"name":"90:E7:C4:F6:69:77","time":0,"result":"Fail"},{"connections":0,"name":"34:FC:EF:11:AE:67","time":0,"result":"Fail"},{"connections":0,"name":"F8:95:C7:87:3C:51","time":0,"result":"Fail"},{"connections":0,"name":"B0:C5:59:3F:75:69","time":0,"result":"Fail"},{"connections":0,"name":"08:EC:A9:50:75:41","time":0,"result":"Fail"},{"connections":0,"name":"E0:DB:10:14:E2:C0","time":0,"result":"Fail"},{"connections":0,"name":"7C:F9:0E:34:8A:A0","time":0,"result":"Fail"}]} G3-1 android (3 left)

2016-01-07T09:11:58.309Z - debug: Socket disconnected: transport close 17 (G3-1)


 
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
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD7228ee9cf5b app:com.test.thalitest code:0 
child process exited with code 0 on device LGD7228ee9cf5b 
Android task is completed. [FAILED]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali02_LGE-Nexus 5.md)

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
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  0be0c6c6 Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on 0be0c6c6 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device ZX1C223JKW app:com.test.thalitest code:0 
child process exited with code 0 on device ZX1C223JKW 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Error! Unexpected exit on device 022678fb504e29b0 app:com.test.thalitest code:0 
child process exited with code 0 on device 022678fb504e29b0 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  4db5c8cc Test has  SUCCEEDED
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device HT574YC04723 app:com.test.thalitest code:0 
child process exited with code 0 on device HT574YC04723 
Android task is completed. [FAILED]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali08_samsung-SM-A300FU.md)

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
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55311151a2306df_Fix_an_inaccuracy_with_data_rate_reporting_vjrantal/thali09_LGE-Nexus 5.md)




