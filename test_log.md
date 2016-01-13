#### Test 55902202f27eba5 Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-13T15:39:17.705Z - info: listening on *:3000

2016-01-13T15:39:18.287Z - debug: Device presented: UNITTEST-0.7796064273821575 (android) unittest socket:0

2016-01-13T15:39:18.309Z - debug: Device presented: UNITTEST-0.12867984570626245 (ios) unittest socket:1

2016-01-13T15:39:18.480Z - debug: Device presented: UNITTEST-0.010120448013814953 (android) unittest socket:3

2016-01-13T15:39:18.482Z - info: Required number of android devices presented (2)

2016-01-13T15:39:18.486Z - info: Starting unit test run for platform: android

2016-01-13T15:39:18.522Z - debug: Device presented: UNITTEST-0.8576825590400943 (ios) unittest socket:2

2016-01-13T15:39:18.523Z - info: Required number of ios devices presented (2)

2016-01-13T15:39:18.524Z - info: Starting unit test run for platform: ios

2016-01-13T15:39:18.730Z - debug: Device presented: UNITTEST-0.834366402366305 (android) unittest socket:4

2016-01-13T15:39:18.731Z - info: Discarding surplus device: UNITTEST-0.834366402366305

2016-01-13T15:39:18.766Z - info: Running test: multiplex can send data

2016-01-13T15:39:18.772Z - info: Running test: multiplex can send data

2016-01-13T15:39:18.943Z - debug: Device presented: UNITTEST-0.6662962273126711 (ios) unittest socket:6

2016-01-13T15:39:18.944Z - info: Discarding surplus device: UNITTEST-0.6662962273126711

2016-01-13T15:39:18.949Z - debug: Device presented: UNITTEST-0.19651491292678192 (android) unittest socket:5

2016-01-13T15:39:18.950Z - info: Discarding surplus device: UNITTEST-0.19651491292678192

2016-01-13T15:39:19.007Z - debug: Device presented: UNITTEST-0.8062554511097881 (android) unittest socket:8

2016-01-13T15:39:19.008Z - info: Discarding surplus device: UNITTEST-0.8062554511097881

2016-01-13T15:39:19.043Z - debug: Device presented: UNITTEST-0.2962521393986217 (android) unittest socket:7

2016-01-13T15:39:19.044Z - info: Discarding surplus device: UNITTEST-0.2962521393986217

2016-01-13T15:39:19.425Z - debug: Device presented: UNITTEST-0.866420126926254 (android) unittest socket:9

2016-01-13T15:39:19.428Z - info: Discarding surplus device: UNITTEST-0.866420126926254

2016-01-13T15:39:19.802Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.19651491292678192)

2016-01-13T15:39:19.841Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.2962521393986217)

2016-01-13T15:39:19.864Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.834366402366305)

2016-01-13T15:39:19.949Z - debug: Device presented: UNITTEST-0.2563228855385732 (android) unittest socket:10

2016-01-13T15:39:19.950Z - info: Discarding surplus device: UNITTEST-0.2563228855385732

2016-01-13T15:39:20.038Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.8062554511097881)

2016-01-13T15:39:20.121Z - info: Running test: basic

2016-01-13T15:39:20.341Z - debug: Device presented: UNITTEST-0.5190590315822202 (android) unittest socket:11

2016-01-13T15:39:20.345Z - info: Discarding surplus device: UNITTEST-0.5190590315822202

2016-01-13T15:39:20.469Z - debug: Device presented: UNITTEST-0.70073089170683 (android) unittest socket:12

2016-01-13T15:39:20.470Z - info: Discarding surplus device: UNITTEST-0.70073089170683

2016-01-13T15:39:20.532Z - debug: Device presented: UNITTEST-0.7360217573489538 (android) unittest socket:13

2016-01-13T15:39:20.533Z - info: Discarding surplus device: UNITTEST-0.7360217573489538

2016-01-13T15:39:20.560Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.2563228855385732)

2016-01-13T15:39:20.576Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.866420126926254)

2016-01-13T15:39:20.856Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.5190590315822202)

2016-01-13T15:39:21.078Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.70073089170683)

2016-01-13T15:39:21.158Z - debug: Device presented: UNITTEST-0.6902832480393769 (android) unittest socket:14

2016-01-13T15:39:21.159Z - info: Discarding surplus device: UNITTEST-0.6902832480393769

2016-01-13T15:39:21.202Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.7360217573489538)

2016-01-13T15:39:21.503Z - debug: Device presented: UNITTEST-0.9700610321457124 (android) unittest socket:15

2016-01-13T15:39:21.504Z - info: Discarding surplus device: UNITTEST-0.9700610321457124

2016-01-13T15:39:21.605Z - debug: Device presented: UNITTEST-0.30050214071681036 (android) unittest socket:16

2016-01-13T15:39:21.606Z - info: Discarding surplus device: UNITTEST-0.30050214071681036

2016-01-13T15:39:21.848Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.6662962273126711)

2016-01-13T15:39:21.957Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.6902832480393769)

2016-01-13T15:39:22.324Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.9700610321457124)

2016-01-13T15:39:22.380Z - debug: Device presented: UNITTEST-0.6168426579998016 (android) unittest socket:17

2016-01-13T15:39:22.381Z - info: Discarding surplus device: UNITTEST-0.6168426579998016

2016-01-13T15:39:22.533Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.30050214071681036)

2016-01-13T15:39:22.588Z - debug: Device presented: UNITTEST-0.15438560912376298 (ios) unittest socket:19

2016-01-13T15:39:22.590Z - info: Discarding surplus device: UNITTEST-0.15438560912376298

2016-01-13T15:39:22.603Z - debug: Device presented: UNITTEST-0.03460916754772314 (android) unittest socket:18

2016-01-13T15:39:22.604Z - info: Discarding surplus device: UNITTEST-0.03460916754772314

2016-01-13T15:39:22.611Z - info: Running test: basic

2016-01-13T15:39:22.764Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.6168426579998016)

2016-01-13T15:39:23.275Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.03460916754772314)

2016-01-13T15:39:23.627Z - info: Running test: another

2016-01-13T15:39:23.791Z - info: Running test: another

2016-01-13T15:39:24.224Z - debug: Device presented: UNITTEST-0.4093359446414716 (android) unittest socket:20

2016-01-13T15:39:24.227Z - info: Discarding surplus device: UNITTEST-0.4093359446414716

2016-01-13T15:39:25.035Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.4093359446414716)

2016-01-13T15:39:25.044Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-13T15:39:25.125Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.15438560912376298)

2016-01-13T15:39:26.660Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-13T15:39:26.704Z - info: Running test: successfully create a new pkcs12 file and return hash value

2016-01-13T15:39:28.004Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-13T15:39:29.712Z - info: Running test: successfully read a previous pkcs12 file and return hash value

2016-01-13T15:39:32.584Z - info: Running test: failed to get mobile documents path

2016-01-13T15:39:32.746Z - debug: Device presented: UNITTEST-0.09025593766228202 (android) unittest socket:21

2016-01-13T15:39:32.747Z - info: Discarding surplus device: UNITTEST-0.09025593766228202

2016-01-13T15:39:32.789Z - info: Running test: failed to extract public key because of corrupt pkcs12 file

2016-01-13T15:39:34.064Z - debug: Socket disconnected: transport close 21 (UNITTEST-0.09025593766228202)

2016-01-13T15:39:34.645Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-13T15:39:36.225Z - info: Running test: #init should register the networkChanged event

2016-01-13T15:39:36.649Z - info: Running test: failed to get mobile documents path

2016-01-13T15:39:37.489Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-13T15:39:39.458Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-13T15:39:39.610Z - info: Running test: #init should register the peerAvailabilityChanged event

2016-01-13T15:39:40.784Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-13T15:39:42.206Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-13T15:39:43.293Z - info: Running test: #init should register the networkChanged event

2016-01-13T15:39:43.452Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-13T15:39:44.675Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-13T15:39:45.924Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-13T15:39:46.495Z - info: Running test: #startBroadcasting should throw on null device name

2016-01-13T15:39:47.124Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-13T15:39:48.355Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-13T15:39:49.615Z - info: Running test: #startBroadcasting should throw on empty string device name

2016-01-13T15:39:51.645Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-13T15:39:52.520Z - info: Running test: #startBroadcasting should throw on non-number port

2016-01-13T15:39:52.838Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-13T15:39:54.086Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-13T15:39:55.297Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-13T15:39:55.543Z - info: Running test: #startBroadcasting should throw on NaN port

2016-01-13T15:39:56.531Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-13T15:39:57.765Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-13T15:39:58.629Z - info: Running test: #startBroadcasting should throw on negative port

2016-01-13T15:40:01.696Z - info: Running test: #startBroadcasting should throw on too large port

2016-01-13T15:40:03.214Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-13T15:40:03.778Z - debug: Device presented: UNITTEST-0.5400676762470972 (android) unittest socket:22

2016-01-13T15:40:03.780Z - info: Discarding surplus device: UNITTEST-0.5400676762470972

2016-01-13T15:40:04.542Z - debug: Socket disconnected: transport close 22 (UNITTEST-0.5400676762470972)

2016-01-13T15:40:04.553Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") without an error

2016-01-13T15:40:05.259Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-13T15:40:07.239Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-13T15:40:07.638Z - info: Running test: #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

2016-01-13T15:40:08.922Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-13T15:40:11.732Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") without an error

2016-01-13T15:40:17.451Z - info: Running test: #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

2016-01-13T15:40:20.722Z - info: Running test: #connect should call Mobile("Connect") with a port and without an error

2016-01-13T15:40:24.063Z - info: Running test: #connect should call Mobile("Connect") and handle an error

2016-01-13T15:40:26.604Z - info: Running test: should call Mobile("Disconnect") without an error

2016-01-13T15:40:29.540Z - info: Running test: should call Mobile("Disconnect") and handle an error

2016-01-13T15:40:32.807Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-13T15:40:33.489Z - info: Running test: ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

2016-01-13T15:40:36.781Z - info: Running test: ThaliEmitter calls startBroadcasting twice with error

2016-01-13T15:40:40.039Z - info: Running test: ThaliEmitter throws on connection to bad peer

2016-01-13T15:40:44.723Z - info: Running test: ThaliEmitter throws on disconnect to bad peer

2016-01-13T15:40:48.596Z - info: Running test: ThaliEmitter can discover and connect to peers

2016-01-13T15:40:58.801Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double connect

2016-01-13T15:41:06.496Z - info: Running test: ThaliEmitter can discover and connect to peers and then fail on double disconnect

2016-01-13T15:41:14.036Z - info: Running test: ThaliEmitter can connect and send data

2016-01-13T15:41:22.996Z - info: Running test: ThaliEmitter handles socket disconnect correctly

2016-01-13T15:41:32.840Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.8576825590400943)

2016-01-13T16:01:47.250Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.12867984570626245)

2016-01-13T16:06:43.874Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.7796064273821575)

2016-01-13T16:07:22.364Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.010120448013814953)


 
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
ios: child process exited with code 254 on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
ios: child process exited with code null on device 605a17dff1a0ba7f312ea7b076f5923e29d8b1fe 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs
[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/iOS_Iphone5-1.md)

[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/iOS_IpadAir2-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/iOS_Iphone6-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/iOS_Iphone5s-1.md)

[server](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/iOS_server.md)


###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
STOP log received from  f56ad48d Test has  SUCCEEDED
Device test finished on f56ad48d 
Android task is completed. [SUCCESS]
```
[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali01_LGE-LG-H815.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali01_samsung-SM-A500FU.md)

####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```
[LGE-LG-D722](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali02_LGE-LG-D722.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali02_LGE-Nexus 5.md)

####Node name: thali03
Console output:
```
STOP log received from  LGD8553bed2d08 Test has  SUCCEEDED
Device test finished on LGD8553bed2d08 
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
Android task is completed. [SUCCESS]
```
[motorola-XT1039](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali03_motorola-XT1039.md)

[LGE-LG-D855](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali03_LGE-LG-D855.md)

[samsung-SM-G800F](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali03_samsung-SM-G800F.md)

####Node name: thali04
Console output:
```
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
STOP log received from  ZX1C223JKW Test has  SUCCEEDED
Device test finished on 41006f95c8139173 
Device test finished on ZX1C223JKW 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 0be0c6c6 app:com.test.thalitest code:null 
child process exited with code null on device 0be0c6c6 
Android task is completed. [FAILED]
```
[motorola-XT1072](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali04_motorola-XT1072.md)

[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali04_samsung-SM-N910C.md)

[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali04_samsung-SM-G900F.md)

####Node name: thali06
Console output:
```
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
Device test finished on 7970f88c 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:null 
child process exited with code null on device FA55PYS00566 
Android task is completed. [FAILED]
```
[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali06_samsung-SM-A300FU.md)

[HTC-HTC One M8s](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali06_HTC-HTC One M8s.md)

[LGE-LG-D802](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali06_LGE-LG-D802.md)

####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
STOP log received from  4db5c8cc Test has  SUCCEEDED
Device test finished on 4db5c8cc 
Device test finished on c5afcdcb 
Android task is completed. [SUCCESS]
```
[samsung-SM-G900F](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali07_samsung-SM-G900F.md)

[samsung-SM-A500FU](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali07_samsung-SM-A500FU.md)

####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Device test finished on HT574YC04723 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali08_HTC-HTC Desire 820.md)

[samsung-SM-A300FU](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali08_samsung-SM-A300FU.md)

####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```
[HTC-HTC Desire 820](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali09_HTC-HTC Desire 820.md)

[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/55902202f27eba5_Story001_fix_muxserverbridgetest_tobybrad/thali09_LGE-Nexus 5.md)




