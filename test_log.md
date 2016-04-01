#### Test 648991491c812df Logs

#### Test Server Logs
```
IS Running:
Running 'jx install'
Skipping the log for NPM since the exitCode was 0
> jx index.js {"devices":{"ios":4,"android":4}}
2016-04-01T07:12:59.738Z - info: Require 3 ios devices

2016-04-01T07:12:59.756Z - info: Require 3 android devices

2016-04-01T07:12:59.815Z - info: listening on *:3000

2016-04-01T07:13:00.457Z - debug: Device presented: Apple-Iphone5-1 (889d6699-0a58-4690-9b28-d06886bb1cc9) - ios Version 9.1 (Build 13B143)

2016-04-01T07:13:00.734Z - debug: Device presented: LGE-Nexus 5 (3b7a4f0c-ca35-409e-be22-5aa916860cbe) - android 5.1.1

2016-04-01T07:13:01.317Z - debug: Device presented: Apple-IpadAir2-1 (c23e9dbc-3839-44c9-a02e-3cacfae18cf9) - ios Version 9.1 (Build 13B143)

2016-04-01T07:13:01.456Z - debug: Device presented: Apple-Iphone5-1 (889d6699-0a58-4690-9b28-d06886bb1cc9) - ios Version 9.1 (Build 13B143)

2016-04-01T07:13:01.458Z - info: Updating existing device: Apple-Iphone5-1 (889d6699-0a58-4690-9b28-d06886bb1cc9)

2016-04-01T07:13:01.765Z - debug: Device presented: LGE-Nexus 5 (3b7a4f0c-ca35-409e-be22-5aa916860cbe) - android 5.1.1

2016-04-01T07:13:01.766Z - info: Updating existing device: LGE-Nexus 5 (3b7a4f0c-ca35-409e-be22-5aa916860cbe)

2016-04-01T07:13:01.771Z - debug: Device presented: LGE-LG-H815 (1f1c544e-e7ca-4c77-bca7-de3db7fba437) - android 5.1

2016-04-01T07:13:02.295Z - debug: Device presented: Apple-IpadAir2-1 (c23e9dbc-3839-44c9-a02e-3cacfae18cf9) - ios Version 9.1 (Build 13B143)

2016-04-01T07:13:02.296Z - info: Updating existing device: Apple-IpadAir2-1 (c23e9dbc-3839-44c9-a02e-3cacfae18cf9)

2016-04-01T07:13:02.743Z - debug: Device presented: LGE-LG-H815 (1f1c544e-e7ca-4c77-bca7-de3db7fba437) - android 5.1

2016-04-01T07:13:02.744Z - info: Updating existing device: LGE-LG-H815 (1f1c544e-e7ca-4c77-bca7-de3db7fba437)

2016-04-01T07:13:03.593Z - debug: Device presented: Apple-Iphone5s-1 (041f376e-9979-4c72-b347-f741200f2779) - ios Version 9.1 (Build 13B143)

2016-04-01T07:13:04.613Z - debug: Device presented: Apple-Iphone5s-1 (041f376e-9979-4c72-b347-f741200f2779) - ios Version 9.1 (Build 13B143)

2016-04-01T07:13:04.615Z - info: Updating existing device: Apple-Iphone5s-1 (041f376e-9979-4c72-b347-f741200f2779)

2016-04-01T07:13:05.129Z - debug: Device presented: Apple-Iphone6-1 (85abda11-1e8a-424e-8415-735a2b4cc683) - ios Version 9.1 (Build 13B143)

2016-04-01T07:13:05.130Z - info: All 4 ios devices are present

2016-04-01T07:13:05.137Z - info: Starting unit test run on 4 ios devices

2016-04-01T07:13:06.084Z - info: Running on ios test: name

2016-04-01T07:13:06.105Z - debug: Device presented: Apple-Iphone6-1 (85abda11-1e8a-424e-8415-735a2b4cc683) - ios Version 9.1 (Build 13B143)

2016-04-01T07:13:06.106Z - info: Updating existing device: Apple-Iphone6-1 (85abda11-1e8a-424e-8415-735a2b4cc683)

2016-04-01T07:13:06.613Z - info: Test run on ios complete

2016-04-01T07:13:06.616Z - info: 

-== UNIT TEST RESULTS ==-

2016-04-01T07:13:06.617Z - info: PLATFORM: ios

2016-04-01T07:13:06.618Z - info: RESULT: PASS

2016-04-01T07:13:06.619Z - info: 1 of 1 tests completed

2016-04-01T07:13:06.621Z - info: 1/1 passed (0 failures)

2016-04-01T07:13:06.622Z - info: 

-== END ==-

2016-04-01T07:13:08.132Z - debug: Device presented: samsung-SM-N910C (399ae1f8-950a-4515-85c1-a6700178ca67) - android 5.1.1

2016-04-01T07:13:09.054Z - info: Socket to device Apple-Iphone6-1 disconnected: transport close

2016-04-01T07:13:09.124Z - info: Socket to device Apple-IpadAir2-1 disconnected: transport close

2016-04-01T07:13:09.394Z - info: Socket to device Apple-Iphone5s-1 disconnected: transport close

2016-04-01T07:13:09.841Z - info: Socket to device Apple-Iphone5-1 disconnected: transport close

2016-04-01T07:13:29.039Z - debug: Device presented: motorola-Nexus 6 (9d5a9407-2d59-4b27-9423-38feca34e61c) - android 5.1.1

2016-04-01T07:13:29.041Z - info: All 4 android devices are present
2016-04-01T07:13:29.042Z - info: Disqualifying device with unsupported hardware: LGE-Nexus 5

2016-04-01T07:13:29.046Z - info: Starting unit test run on 3 android devices

2016-04-01T07:13:29.426Z - info: Running on android test: name

2016-04-01T07:13:29.831Z - info: Socket to device LGE-Nexus 5 disconnected: transport close

2016-04-01T07:13:30.545Z - info: Test run on android complete

2016-04-01T07:13:30.546Z - info: 

-== UNIT TEST RESULTS ==-

2016-04-01T07:13:30.548Z - info: PLATFORM: android

2016-04-01T07:13:30.549Z - info: RESULT: PASS

2016-04-01T07:13:30.550Z - info: 1 of 1 tests completed

2016-04-01T07:13:30.552Z - info: 1/1 passed (0 failures)

2016-04-01T07:13:30.553Z - info: 

-== END ==-

2016-04-01T07:13:31.274Z - info: Socket to device motorola-Nexus 6 disconnected: transport close

2016-04-01T07:13:31.433Z - info: Socket to device LGE-LG-H815 disconnected: transport close

2016-04-01T07:13:31.440Z - info: Socket to device samsung-SM-N910C disconnected: transport close


 
Run IS script aborted
 
One or more Android tests are failed.
 [0m

```


Logs for system : 
```

ios : false

android : No Error
```


###iOS Logs
[IpadAir2-1](https://github.com/ThaliTester/TestResults/blob/648991491c812df_Test_CI_with_simple_test_vjrantal/iOS_IpadAir2-1.md)

[Iphone5s-1](https://github.com/ThaliTester/TestResults/blob/648991491c812df_Test_CI_with_simple_test_vjrantal/iOS_Iphone5s-1.md)

[Iphone5-1](https://github.com/ThaliTester/TestResults/blob/648991491c812df_Test_CI_with_simple_test_vjrantal/iOS_Iphone5-1.md)

[Iphone6-1](https://github.com/ThaliTester/TestResults/blob/648991491c812df_Test_CI_with_simple_test_vjrantal/iOS_Iphone6-1.md)


###Android Logs
####Node name: thali07
Console output:
```
STOP log received from  0c6a0f3c0bdb4e77 Test has  SUCCEEDED
Device test finished on 0c6a0f3c0bdb4e77 
STOP log received from  LGH8153b36be34 Test has  SUCCEEDED
Device test finished on LGH8153b36be34 
Android task is completed. [SUCCESS]
```
[LGE-Nexus 5](https://github.com/ThaliTester/TestResults/blob/648991491c812df_Test_CI_with_simple_test_vjrantal/thali07_LGE-Nexus 5.md)

[LGE-LG-H815](https://github.com/ThaliTester/TestResults/blob/648991491c812df_Test_CI_with_simple_test_vjrantal/thali07_LGE-LG-H815.md)

####Node name: thali08
Console output:
```
STOP log received from  ZX1G429CRK Test has  SUCCEEDED
STOP log received from  41006f95c8139173 Test has  SUCCEEDED
Device test finished on ZX1G429CRK 
Device test finished on 41006f95c8139173 
Android task is completed. [SUCCESS]
```
[samsung-SM-N910C](https://github.com/ThaliTester/TestResults/blob/648991491c812df_Test_CI_with_simple_test_vjrantal/thali08_samsung-SM-N910C.md)

[motorola-Nexus 6](https://github.com/ThaliTester/TestResults/blob/648991491c812df_Test_CI_with_simple_test_vjrantal/thali08_motorola-Nexus 6.md)


