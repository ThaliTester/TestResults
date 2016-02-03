#### Test 5813565532fb33b_iOS_IpadAir2-1 Logs


```
[100%] Installed package /Users/thali/Github/CI/builder/builds/5813565532fb33b/build_ios/ThaliTest.app
,------ Debug phase ------
,Starting debug of J81AP 'IpadAir2-1' (605a17dff1a0ba7f312ea7b076f5923e29d8b1fe) connected through USB...
,[  0%] Looking up developer disk image
,[ 95%] Developer disk image mounted successfully
,[100%] Connecting to remote debug server
-------------------------
,Skipping iPhone 6 (GSM) 'Iphone6-1' (2a65f58f9902a701b5c9a55b2befb18672927474).
,Skipping iPhone 5 (GSM) 'Iphone5-1' (17df3859480c382d3b761fa2643dde395ced1bd8).
,(lldb) command source -s 0 '/tmp/4C5882D2-3993-4DAA-910A-7F569D0EE549/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'
,Executing commands in '/tmp/4C5882D2-3993-4DAA-910A-7F569D0EE549/fruitstrap-lldb-prep-cmds-605a17dff1a0ba7f312ea7b076f5923e29d8b1fe'.
(lldb)     platform select remote-ios --sysroot '/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols'
,  Platform: remote-ios
 Connected: no
  SDK Path: "/Users/thali/Library/Developer/Xcode/iOS DeviceSupport/9.1 (13B143)/Symbols"
(lldb)     target create "/Users/thali/Github/CI/builder/builds/5813565532fb33b/build_ios/ThaliTest.app"
,Current executable set to '/Users/thali/Github/CI/builder/builds/5813565532fb33b/build_ios/ThaliTest.app' (armv7).
(lldb)     script fruitstrap_device_app="/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app"
,(lldb)     script fruitstrap_connect_url="connect://127.0.0.1:49415"
,(lldb)     command script import "/tmp/4C5882D2-3993-4DAA-910A-7F569D0EE549/fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.py"
,(lldb)     command script add -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.connect_command connect
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.run_command run
(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.autoexit_command autoexit
,(lldb)     command script add -s asynchronous -f fruitstrap_605a17dff1a0ba7f312ea7b076f5923e29d8b1fe.safequit_command safequit
,(lldb)     connect
,(lldb)     run
,success
,(lldb)     autoexit
,2016-02-03 20:28:36.284 ThaliTest[579:868825] DiskCookieStorage changing policy from 2 to 0, cookie file: file:///private/var/mobile/Containers/Data/Application/7EB93C90-8BD8-4067-8A15-478427AF97A4/Library/Cookies/Cookies.binarycookies
,2016-02-03 20:28:36.699 ThaliTest[579:868825] Apache Cordova native platform version 3.9.2 is starting.
,2016-02-03 20:28:36.700 ThaliTest[579:868825] Multi-tasking -> Device: YES, App: YES
,2016-02-03 20:28:36.709 ThaliTest[579:868825] Unlimited access to network resources
,2016-02-03 20:28:36.718 ThaliTest[579:868825] 

Started backup to iCloud! Please be careful.
Your application might be rejected by Apple if you store too much data.
For more information please read "iOS Data Storage Guidelines" at:
https://developer.apple.com/icloud/documentation/data-storage/
To disable web storage backup to iCloud, set the BackupWebStorage preference to "local" in the Cordova config.xml file

,2016-02-03 20:28:46.576 ThaliTest[579:868825] Resetting plugins due to page load.
,2016-02-03 20:28:50.488 ThaliTest[579:868825] Finished load of: file:///var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/index.html
,2016-02-03 20:28:50.651 ThaliTest[579:868825] JXcore Cordova plugin initializing
,2016-02-03 20:28:50.651 ThaliTest[579:869103] JXcore instance initializing
,Initializing JXcore engine
JXcore engine is ready
,Starting JXcore engine
,Platform ios

Process ARCH arm

,JXcore Cordova bridge is ready!

,JXcore engine is started
,My device name is: Apple-IpadAir2-1

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/bv_tests/testMultiplex.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/bv_tests/testPromiseQueue.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/bv_tests/testTests.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/bv_tests/testThaliCryptoManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/bv_tests/testThaliEmitter.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/bv_tests/testThaliNativeLayer.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/bv_tests/testThaliReplicationManager.js

,Test runner loading file: /private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/bv_tests/testThaliWifiInfrastructure.js

,Test app app.js loaded

,TAP version 13

,# setup

,not ok 1 ReferenceError: _name is not defined

  ---

,    operator: error

,    expected: |-

,      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# multiplex can send data

,not ok 2 ReferenceError: _name is not defined

  ---

,    operator: error

,    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 3 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

    actual: |-
,
,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 4 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

,      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

    stack: |-
,
,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# enqueue and run in order

,not ok 5 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 6 ReferenceError: _name is not defined

,  ---

    operator: error

    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# setup

,not ok 7 ReferenceError: _name is not defined

,  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# basic

,not ok 8 ReferenceError: _name is not defined

,  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 9 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
,  ...

,# setup

,not ok 10 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-
,
      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# another

,not ok 11 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-
,
,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 12 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...
,
,# setup

,not ok 13 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

    stack: |-
,
,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# successfully create a new pkcs12 file and return hash value

,not ok 14 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 15 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
  ...

,# setup

,not ok 16 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

  ...

,# successfully read a previous pkcs12 file and return hash value

,not ok 17 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-
,
,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 18 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 19 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# failed to extract public key because of corrupt pkcs12 file

,not ok 20 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
,  ...

,# teardown

,not ok 21 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 22 ReferenceError: _name is not defined

  ---
,
    operator: error

    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...
,
,# failed to get mobile documents path

,not ok 23 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 24 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# setup

,not ok 25 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# #init should register the peerAvailabilityChanged event

,not ok 26 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-
,
,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 27 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# setup

,not ok 28 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined
,
    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# #init should register the networkChanged event

,not ok 29 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

      undefined
,
    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 30 ReferenceError: _name is not defined

  ---

,    operator: error

,    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# setup

,not ok 31 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# #startBroadcasting should throw on null device name

,not ok 32 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1
,
,      

,  ...

,# teardown

,not ok 33 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      
,
,  ...

,# setup

,not ok 34 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# #startBroadcasting should throw on empty string device name

,not ok 35 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# teardown

,not ok 36 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
,  ...

,# setup

,not ok 37 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]
,
    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# #startBroadcasting should throw on non-number port

,not ok 38 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 39 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined
,
    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      
,
  ...

,# setup

,not ok 40 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-
,
      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      
,
,  ...

,# #startBroadcasting should throw on NaN port

,not ok 41 ReferenceError: _name is not defined

  ---
,
    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
,  ...

,# teardown

,not ok 42 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
,  ...

,# setup

,not ok 43 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# #startBroadcasting should throw on negative port

,not ok 44 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

    actual: |-

      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 45 ReferenceError: _name is not defined

,  ---

    operator: error

,    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# setup

,not ok 46 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      
,
,  ...

,# #startBroadcasting should throw on too large port

,not ok 47 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 48 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
,  ...

,# setup

,not ok 49 ReferenceError: _name is not defined

  ---
,
,    operator: error

,    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# #startBroadcasting should call Mobile("StartBroadcasting") without an error

,not ok 50 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 51 ReferenceError: _name is not defined

  ---

,    operator: error

,    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# setup

,      undefined

not ok 52 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# #startBroadcasting should call Mobile("StartBroadcasting") and handle an error

,not ok 53 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]
,
    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# teardown

,not ok 54 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 55 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# #stopBroadcasting should call Mobile("StopBroadcasting") without an error

,not ok 56 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined
,
,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 57 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
  ...

,# setup

,not ok 58 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# #stopBroadcasting should call Mobile("StopBroadcasting") and handle an error

,not ok 59 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

  ...

,# teardown

,not ok 60 ReferenceError: _name is not defined

,  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# setup

,not ok 61 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# #connect should call Mobile("Connect") with a port and without an error

,not ok 62 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 63 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...
,
,# setup

,not ok 64 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# #connect should call Mobile("Connect") and handle an error

,not ok 65 ReferenceError: _name is not defined

  ---
,
    operator: error

,    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

  ...

,# teardown

,not ok 66 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-
,
,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

  ...

,# setup

,not ok 67 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

,      undefined
,
    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      
,
  ...

,# should call Mobile("Disconnect") without an error

,not ok 68 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined
,
    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 69 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# setup

,    operator: error

not ok 70 ReferenceError: _name is not defined

  ---

,    expected: |-

      undefined

    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD,-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

  ...

# should call Mobile("Disconnect") and handle an error

not ok 71 ReferenceError: _name is not defined

  ---

,    operator: error

,    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 72 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13
,
      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 73 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# ThaliEmitter can call repeatedly startBroadcasting and stopBroadcasting without error

,not ok 74 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]
,
,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 75 ReferenceError: _name is not defined

  ---

,    operator: error

,    expected: |-

,      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 76 ReferenceError: _name is not defined

  ---

,      undefined
    operator: error

    expected: |-


    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# ThaliEmitter calls startBroadcasting twice with error

,not ok 77 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 78 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 79 ReferenceError: _name is not defined

  ---
,
,    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# ThaliEmitter throws on connection to bad peer

,not ok 80 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 81 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

  ...

,# setup

,not ok 82 ReferenceError: _name is not defined

  ---

    operator: error
,
,    expected: |-

,      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

  ...

,# ThaliEmitter throws on disconnect to bad peer

,not ok 83 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

,      undefined

,    actual: |-

      [ReferenceError: _name is not defined]
,
,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

  ...

,# teardown

,not ok 84 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# setup

,not ok 85 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# ThaliEmitter can discover and connect to peers

,not ok 86 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined
,
,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 87 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
  ...

,# setup

,not ok 88 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# ThaliEmitter can discover and connect to peers and then fail on double connect

,not ok 89 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5
,
,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 90 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 91 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# ThaliEmitter can discover and connect to peers and then fail on double disconnect

,not ok 92 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
  ...

,# teardown

,not ok 93 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      
,
,  ...

,# setup

,not ok 94 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

  ...

,# ThaliEmitter can connect and send data

,not ok 95 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]
,
    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
,  ...

,# teardown

,not ok 96 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# setup

,not ok 97 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

  ...

,# ThaliEmitter handles socket disconnect correctly

,not ok 98 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
,  ...

,# teardown

,not ok 99 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

  ...

,# setup

,not ok 100 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
,  ...

,# ThaliReplicationManager can call start without error

,not ok 101 ReferenceError: _name is not defined

,  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 102 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# setup

,not ok 103 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# ThaliReplicationManager receives identity

,not ok 104 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]
,
,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 105 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# setup

,not ok 106 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      
,
,  ...

,# ThaliReplicationManager replicates database

,not ok 107 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 108 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 109 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

,      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted

,not ok 110 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 111 ReferenceError: _name is not defined

,  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

  ...

,# setup

,not ok 112 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5
,
,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...
,
,# #startUpdateAdvertisingAndListening should use different USN after every invocation

,not ok 113 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 114 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# setup

,not ok 115 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# messages with invalid location or USN should be ignored

,not ok 116 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
,  ...

,# teardown

,not ok 117 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# setup

,not ok 118 ReferenceError: _name is not defined

  ---

,    operator: error

    expected: |-

,      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# verify that Thali-specific messages are filtered correctly

,not ok 119 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-
,
,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 120 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# setup

,not ok 121 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

  ...

,# #start should fail if called twice in a row

,not ok 122 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# teardown

,not ok 123 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 124 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# #startUpdateAdvertisingAndListening should fail invalid router has been passed

,not ok 125 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

  ...

,# teardown

,not ok 126 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 127 ReferenceError: _name is not defined

,  ---

    operator: error

    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-
,
,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

  ...

,# #startUpdateAdvertisingAndListening should fail if router server starting fails

,not ok 128 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      
,
,  ...

,# teardown

,not ok 129 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# setup

,not ok 130 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      
,
  ...

,# #startUpdateAdvertisingAndListening should start hosting given router object

,not ok 131 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 132 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 133 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      
,
,  ...

,# #stop can be called multiple times in a row

,not ok 134 ReferenceError: _name is not defined

  ---

    operator: error
,
,    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 135 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# setup

,not ok 136 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      
,
  ...

,# #startListeningForAdvertisements can be called multiple times in a row

,not ok 137 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 138 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# setup

,not ok 139 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# #stopListeningForAdvertisements can be called multiple times in a row

,not ok 140 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-
,
,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

,  ...

,# teardown

,not ok 141 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

      undefined

,    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,# setup

,not ok 142 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

  ...

,# #stopAdvertisingAndListening can be called multiple times in a row

,not ok 143 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

      
,
,  ...

,# teardown

,not ok 144 ReferenceError: _name is not defined

  ---

    operator: error

,    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

      

  ...

,# setup

,not ok 145 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

      undefined

,    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:61:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

  ...

,# functions are run from a queue in the right order

,not ok 146 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

      [ReferenceError: _name is not defined]

,    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:84:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

,      $v@timers.js:363:1

,      

,  ...

,# teardown

,not ok 147 ReferenceError: _name is not defined

  ---

    operator: error

    expected: |-

,      undefined

    actual: |-

,      [ReferenceError: _name is not defined]

    stack: |-

,      declareTest/<@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/lib/thali-tape.js:92:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      exports.Test.prototype.run@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape-catch/index.js:17:5

,      bound@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/test.js:61:28

,      next@/private/var/mobile/Containers/Bundle/Application/07DA8AFD-67D0-4E46-917B-A1A8470F21DA/ThaliTest.app/www/jxcore/node_modules/tape/lib/results.js:70:13

      $v@timers.js:363:1

,      

,  ...

,Tests Complete


```
