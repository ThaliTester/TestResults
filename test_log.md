#### Test 55864105c0db81b Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":19}}
2016-01-13T08:07:33.118Z - info: listening on *:3000

2016-01-13T08:07:33.751Z - debug: Device presented: UNITTEST-0.3549185845949039 (android) unittest socket:0

2016-01-13T08:07:33.761Z - debug: Device presented: UNITTEST-0.34695305995564685 (ios) unittest socket:1

2016-01-13T08:07:33.779Z - debug: Device presented: UNITTEST-0.8737185097437203 (android) unittest socket:2

2016-01-13T08:07:33.782Z - info: Required number of android devices presented (2)

2016-01-13T08:07:33.785Z - info: Starting unit test run for platform: android

2016-01-13T08:07:33.806Z - debug: Device presented: UNITTEST-0.23281231286787507 (android) unittest socket:3

2016-01-13T08:07:33.808Z - info: Discarding surplus device: UNITTEST-0.23281231286787507

2016-01-13T08:07:33.845Z - debug: Device presented: UNITTEST-0.01822679988425091 (ios) unittest socket:4

2016-01-13T08:07:33.847Z - info: Required number of ios devices presented (2)

2016-01-13T08:07:33.848Z - info: Starting unit test run for platform: ios

2016-01-13T08:07:34.047Z - info: Running test: multiplex can send data

2016-01-13T08:07:34.109Z - info: Running test: multiplex can send data

2016-01-13T08:07:34.259Z - info: Running test: muxServerBridge

2016-01-13T08:07:34.281Z - info: Running test: muxServerBridge

2016-01-13T08:07:34.341Z - debug: Device presented: UNITTEST-0.7809616694352756 (android) unittest socket:5

2016-01-13T08:07:34.342Z - info: Discarding surplus device: UNITTEST-0.7809616694352756

2016-01-13T08:07:34.714Z - debug: Socket disconnected: transport close 3 (UNITTEST-0.23281231286787507)

2016-01-13T08:07:34.944Z - debug: Device presented: UNITTEST-0.8098846810600041 (android) unittest socket:6

2016-01-13T08:07:34.945Z - info: Discarding surplus device: UNITTEST-0.8098846810600041

2016-01-13T08:07:35.007Z - debug: Socket disconnected: transport close 5 (UNITTEST-0.7809616694352756)

2016-01-13T08:07:35.406Z - debug: Device presented: UNITTEST-0.9707715354564743 (android) unittest socket:7

2016-01-13T08:07:35.407Z - info: Discarding surplus device: UNITTEST-0.9707715354564743

2016-01-13T08:07:35.530Z - debug: Device presented: UNITTEST-0.776828731707025 (android) unittest socket:8

2016-01-13T08:07:35.533Z - info: Discarding surplus device: UNITTEST-0.776828731707025

2016-01-13T08:07:35.702Z - debug: Device presented: UNITTEST-0.5965658821480881 (android) unittest socket:9

2016-01-13T08:07:35.703Z - info: Discarding surplus device: UNITTEST-0.5965658821480881

2016-01-13T08:07:35.770Z - debug: Socket disconnected: transport close 6 (UNITTEST-0.8098846810600041)

2016-01-13T08:07:35.901Z - debug: Socket disconnected: transport close 7 (UNITTEST-0.9707715354564743)

2016-01-13T08:07:36.417Z - debug: Device presented: UNITTEST-0.48091299873665405 (android) unittest socket:10

2016-01-13T08:07:36.418Z - info: Discarding surplus device: UNITTEST-0.48091299873665405

2016-01-13T08:07:36.514Z - debug: Socket disconnected: transport close 8 (UNITTEST-0.776828731707025)

2016-01-13T08:07:36.588Z - debug: Device presented: UNITTEST-0.5079508551729961 (android) unittest socket:11

2016-01-13T08:07:36.589Z - info: Discarding surplus device: UNITTEST-0.5079508551729961

2016-01-13T08:07:36.797Z - debug: Socket disconnected: transport close 9 (UNITTEST-0.5965658821480881)

2016-01-13T08:07:36.877Z - debug: Device presented: UNITTEST-0.8725318982753084 (android) unittest socket:12

2016-01-13T08:07:36.880Z - info: Discarding surplus device: UNITTEST-0.8725318982753084

2016-01-13T08:07:37.220Z - debug: Device presented: UNITTEST-0.041754293329011816 (ios) unittest socket:13

2016-01-13T08:07:37.221Z - info: Discarding surplus device: UNITTEST-0.041754293329011816

2016-01-13T08:07:37.226Z - debug: Socket disconnected: transport close 10 (UNITTEST-0.48091299873665405)

2016-01-13T08:07:37.233Z - debug: Socket disconnected: transport close 11 (UNITTEST-0.5079508551729961)

2016-01-13T08:07:37.451Z - debug: Device presented: UNITTEST-0.5924668394068723 (android) unittest socket:15

2016-01-13T08:07:37.452Z - info: Discarding surplus device: UNITTEST-0.5924668394068723

2016-01-13T08:07:37.458Z - debug: Device presented: UNITTEST-0.9143064643098703 (android) unittest socket:14

2016-01-13T08:07:37.459Z - info: Discarding surplus device: UNITTEST-0.9143064643098703

2016-01-13T08:07:37.582Z - debug: Device presented: UNITTEST-0.6078572344915403 (android) unittest socket:16

2016-01-13T08:07:37.583Z - info: Discarding surplus device: UNITTEST-0.6078572344915403

2016-01-13T08:07:37.647Z - debug: Socket disconnected: transport close 12 (UNITTEST-0.8725318982753084)

2016-01-13T08:07:37.850Z - debug: Device presented: UNITTEST-0.6492970021975304 (android) unittest socket:17

2016-01-13T08:07:37.851Z - info: Discarding surplus device: UNITTEST-0.6492970021975304

2016-01-13T08:07:37.984Z - debug: Device presented: UNITTEST-0.35808683295311317 (ios) unittest socket:18

2016-01-13T08:07:37.985Z - info: Discarding surplus device: UNITTEST-0.35808683295311317

2016-01-13T08:07:38.031Z - debug: Socket disconnected: transport close 15 (UNITTEST-0.5924668394068723)

2016-01-13T08:07:38.604Z - debug: Socket disconnected: transport close 16 (UNITTEST-0.6078572344915403)

2016-01-13T08:07:38.666Z - debug: Socket disconnected: transport close 17 (UNITTEST-0.6492970021975304)

2016-01-13T08:07:38.739Z - debug: Socket disconnected: transport close 14 (UNITTEST-0.9143064643098703)

2016-01-13T08:07:39.717Z - debug: Socket disconnected: transport close 13 (UNITTEST-0.041754293329011816)

2016-01-13T08:07:40.525Z - debug: Socket disconnected: transport close 18 (UNITTEST-0.35808683295311317)

2016-01-13T08:07:45.739Z - debug: Device presented: UNITTEST-0.42262175498464627 (android) unittest socket:19

2016-01-13T08:07:45.740Z - info: Discarding surplus device: UNITTEST-0.42262175498464627

2016-01-13T08:07:46.886Z - debug: Socket disconnected: transport close 19 (UNITTEST-0.42262175498464627)

2016-01-13T08:08:00.343Z - debug: Device presented: UNITTEST-0.28219639153261245 (android) unittest socket:20

2016-01-13T08:08:00.345Z - info: Discarding surplus device: UNITTEST-0.28219639153261245

2016-01-13T08:08:01.272Z - debug: Socket disconnected: transport close 20 (UNITTEST-0.28219639153261245)

2016-01-13T08:30:03.476Z - debug: Socket disconnected: transport close 4 (UNITTEST-0.01822679988425091)

2016-01-13T08:30:03.487Z - debug: Socket disconnected: transport close 1 (UNITTEST-0.34695305995564685)

2016-01-13T08:35:37.815Z - debug: Socket disconnected: transport close 2 (UNITTEST-0.8737185097437203)

2016-01-13T08:37:54.355Z - debug: Socket disconnected: transport close 0 (UNITTEST-0.3549185845949039)


 
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
ios: child process exited with code null on device 17df3859480c382d3b761fa2643dde395ced1bd8 
ios: child process exited with code null on device 00b2e2c1b30013159b62125fe7f097bdcc055c10 
true


android : Error: Command failed: Error: Command failed: Android testing process has failed
 [0m


```
###iOS Logs


Couldn't parse the iOS logs
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/55864105c0db81b_Fix_running_tests_when_`userConfig`_isn_t_given__vjrantal/iOS_Iphone5-1.md'```

###Android Logs
####Node name: thali01
Console output:
```
STOP log received from  f56ad48d Test has  SUCCEEDED
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on f56ad48d 
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```


Couldn't parse the device logs for thali01
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/55864105c0db81b_Fix_running_tests_when_`userConfig`_isn_t_given__vjrantal/thali01_LGE-LG-H815.md'```
####Node name: thali02
Console output:
```
STOP log received from  LGD7228ee9cf5b Test has  SUCCEEDED
STOP log received from  09a9416e0297d102 Test has  SUCCEEDED
Device test finished on LGD7228ee9cf5b 
Device test finished on 09a9416e0297d102 
Android task is completed. [SUCCESS]
```


Couldn't parse the device logs for thali02
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/55864105c0db81b_Fix_running_tests_when_`userConfig`_isn_t_given__vjrantal/thali02_LGE-LG-D722.md'```
####Node name: thali03
Console output:
```
STOP log received from  320414cd475f91e3 Test has  SUCCEEDED
Device test finished on 320414cd475f91e3 
STOP log received from  TA4750HV7I Test has  SUCCEEDED
Device test finished on TA4750HV7I 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device LGD8553bed2d08 app:com.test.thalitest code:0 
child process exited with code 0 on device LGD8553bed2d08 
Android task is completed. [FAILED]
```


Couldn't parse the device logs for thali03
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/55864105c0db81b_Fix_running_tests_when_`userConfig`_isn_t_given__vjrantal/thali03_motorola-XT1039.md'```
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


Couldn't parse the device logs for thali04
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/55864105c0db81b_Fix_running_tests_when_`userConfig`_isn_t_given__vjrantal/thali04_motorola-XT1072.md'```
####Node name: thali06
Console output:
```
STOP log received from  7970f88c Test has  SUCCEEDED
Device test finished on 7970f88c 
STOP log received from  022678fb504e29b0 Test has  SUCCEEDED
Device test finished on 022678fb504e29b0 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device FA55PYS00566 app:com.test.thalitest code:0 
child process exited with code 0 on device FA55PYS00566 
Android task is completed. [FAILED]
```


Couldn't parse the device logs for thali06
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/55864105c0db81b_Fix_running_tests_when_`userConfig`_isn_t_given__vjrantal/thali06_samsung-SM-A300FU.md'```
####Node name: thali07
Console output:
```
STOP log received from  c5afcdcb Test has  SUCCEEDED
Device test finished on c5afcdcb 
TIMEOUT REACHED. KILLING the APPS
Error! Unexpected exit on device 4db5c8cc app:com.test.thalitest code:0 
child process exited with code 0 on device 4db5c8cc 
Android task is completed. [FAILED]
```


Couldn't parse the device logs for thali07
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/55864105c0db81b_Fix_running_tests_when_`userConfig`_isn_t_given__vjrantal/thali07_samsung-SM-G900F.md'```
####Node name: thali08
Console output:
```
STOP log received from  HT574YC04723 Test has  SUCCEEDED
Device test finished on HT574YC04723 
STOP log received from  4325e43f Test has  SUCCEEDED
Device test finished on 4325e43f 
Android task is completed. [SUCCESS]
```


Couldn't parse the device logs for thali08
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/55864105c0db81b_Fix_running_tests_when_`userConfig`_isn_t_given__vjrantal/thali08_HTC-HTC Desire 820.md'```
####Node name: thali09
Console output:
```
STOP log received from  CC51WYC03425 Test has  SUCCEEDED
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
Device test finished on CC51WYC03425 
Android task is completed. [SUCCESS]
```


Couldn't parse the device logs for thali09
````Error: ENOENT, no such file or directory '/Users/thali/Github/CI/TMP/55864105c0db81b_Fix_running_tests_when_`userConfig`_isn_t_given__vjrantal/thali09_HTC-HTC Desire 820.md'```



