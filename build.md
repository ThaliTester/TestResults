#### Test (Fail) 109247054 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   8a224d4..ba6e0c6  master_Swift3_migration -> origin/master_Swift3_migration

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Auto-merging .eslintrc.js
Merge made by the 'recursive' strategy.
 .eslintrc => .eslintrc.js                          |  33 ++++-
 test/www/jxcore/bv_tests/testSSDPServer.js         | 108 ++++++++-------
 test/www/jxcore/bv_tests/testThaliManager.js       |  25 ----
 .../jxcore/bv_tests/testThaliManagerCoordinated.js |   2 +-
 test/www/jxcore/bv_tests/testThaliMobileNative.js  |  94 ++++++-------
 .../jxcore/bv_tests/testThaliNotificationClient.js |  39 ++++++
 .../jxcore/bv_tests/testThaliPeerPoolDefault.js    |  11 +-
 .../jxcore/bv_tests/testThaliPeerPoolOneAtATime.js | 118 +++++++++-------
 .../testThaliPullReplicationFromNotification.js    |  52 +++++--
 .../jxcore/bv_tests/testThaliWifiInfrastructure.js |  88 ++++++++++++
 .../notification/thaliNotificationClient.js        |  32 ++---
 .../thaliPullReplicationFromNotification.js        |  61 ++++-----
 .../replication/thaliReplicationPeerAction.js      |  12 +-
 thali/NextGeneration/thaliManager.js               |  38 ++----
 thali/NextGeneration/thaliMobileNative.js          |  18 ---
 thali/NextGeneration/thaliMobileNativeWrapper.js   |   9 +-
 .../thaliPeerPool/thaliPeerAction.js               |  31 ++++-
 .../thaliPeerPool/thaliPeerPoolDefault.js          |   3 +-
 .../thaliPeerPool/thaliPeerPoolInterface.js        |  34 ++---
 .../thaliPeerPool/thaliPeerPoolOneAtATime.js       |  30 ++--
 thali/NextGeneration/thaliWifiInfrastructure.js    | 152 ++++++++++-----------
 21 files changed, 556 insertions(+), 434 deletions(-)
 rename .eslintrc => .eslintrc.js (72%)

Already on 'master'
Already on 'master'
Note: checking out 'ba6e0c6'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at ba6e0c6... Add phase that copies frameworks into iOS infrustructure dir to be able to build ThaliTest app.

```

```

start build.sh

-- Environment:
Cordova version: 6.4.0
Node version: v6.9.1
JXcore version: v0.3.1.10
JXcore engine: Google V8 v3.14.5.9
xcodebuild version: Xcode 8.2.1


start setUpDesktop.sh

start preparing TestServer
thali-test-server@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/test/TestServer
├── bluebird@3.4.6 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ ├─┬ mime-types@2.1.14 
│ │ │ └── mime-db@1.26.0 
│ │ └── negotiator@0.5.3 
│ ├── array-flatten@1.1.1 
│ ├── content-disposition@0.5.0 
│ ├── content-type@1.0.2 
│ ├── cookie@0.1.3 
│ ├── cookie-signature@1.0.6 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.0.1 
│ ├── escape-html@1.0.2 
│ ├── etag@1.7.0 
│ ├─┬ finalhandler@0.4.0 
│ │ └── unpipe@1.0.0 
│ ├── fresh@0.3.0 
│ ├── merge-descriptors@1.0.0 
│ ├── methods@1.1.2 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── parseurl@1.3.1 
│ ├── path-to-regexp@0.1.7 
│ ├─┬ proxy-addr@1.0.10 
│ │ ├── forwarded@0.1.0 
│ │ └── ipaddr.js@1.0.5 
│ ├── qs@4.0.0 
│ ├── range-parser@1.0.3 
│ ├─┬ send@0.13.0 
│ │ ├── destroy@1.0.3 
│ │ ├─┬ http-errors@1.3.1 
│ │ │ └── inherits@2.0.3 
│ │ ├── mime@1.3.4 
│ │ └── statuses@1.2.1 
│ ├─┬ serve-static@1.10.3 
│ │ ├── escape-html@1.0.3 
│ │ └─┬ send@0.13.2 
│ │   ├── depd@1.1.0 
│ │   └── destroy@1.0.4 
│ ├─┬ type-is@1.6.14 
│ │ └── media-typer@0.3.0 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.11 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.6.1 
│     └─┬ glob@7.1.1 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.6 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.3 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       ├── once@1.4.0 
│       └── path-is-absolute@1.0.1 
├── node-uuid@1.4.7 
├── object-assign@4.1.0 
├─┬ socket.io@1.4.8 
│ ├─┬ engine.io@1.6.11 
│ │ ├─┬ accepts@1.1.4 
│ │ │ ├─┬ mime-types@2.0.14 
│ │ │ │ └── mime-db@1.12.0 
│ │ │ └── negotiator@0.4.9 
│ │ ├── base64id@0.1.0 
│ │ ├─┬ engine.io-parser@1.2.4 
│ │ │ ├── after@0.8.1 
│ │ │ ├── arraybuffer.slice@0.0.6 
│ │ │ ├── base64-arraybuffer@0.1.2 
│ │ │ ├── blob@0.0.4 
│ │ │ ├── has-binary@0.1.6 
│ │ │ └── utf8@2.1.0 
│ │ └─┬ ws@1.1.0 
│ │   ├── options@0.0.6 
│ │   └── ultron@1.0.2 
│ ├─┬ has-binary@0.1.7 
│ │ └── isarray@0.0.1 
│ ├─┬ socket.io-adapter@0.4.0 
│ │ └─┬ socket.io-parser@2.2.2 
│ │   ├── debug@0.7.4 
│ │   └── json3@3.2.6 
│ ├─┬ socket.io-client@1.4.8 
│ │ ├── backo2@1.0.2 
│ │ ├── component-bind@1.0.0 
│ │ ├── component-emitter@1.2.0 
│ │ ├─┬ engine.io-client@1.6.11 
│ │ │ ├── component-inherit@0.0.3 
│ │ │ ├── has-cors@1.1.0 
│ │ │ ├── parsejson@0.0.1 
│ │ │ ├── parseqs@0.0.2 
│ │ │ ├── ws@1.0.1 
│ │ │ ├── xmlhttprequest-ssl@1.5.1 
│ │ │ └── yeast@0.1.2 
│ │ ├── indexof@0.0.1 
│ │ ├── object-component@0.0.3 
│ │ ├─┬ parseuri@0.0.4 
│ │ │ └─┬ better-assert@1.0.2 
│ │ │   └── callsite@1.0.0 
│ │ └── to-array@0.1.4 
│ └─┬ socket.io-parser@2.2.6 
│   ├── benchmark@1.0.0 
│   ├── component-emitter@1.1.2 
│   └── json3@3.3.2 
└─┬ winston@2.2.0 
  ├── async@1.0.0 
  ├── colors@1.0.3 
  ├── cycle@1.0.3 
  ├── eyes@0.1.8 
  ├── isstream@0.1.2 
  ├── pkginfo@0.3.1 
  └── stack-trace@0.0.9 

end preparing TestServer


start installing Thali root
[33mPreparing NPM for JXcore (v0.3.1.10) for the first run[39m
[33mDownloading NPM for JXcore[39m

[0;31merror: command 'jx npm install --no-optional' failed with code 1, file 'setUpDesktop.sh' on line 32[0m

[0;31merror: command 'thali/install/setUpDesktop.sh' failed with code 1, file 'build.sh' on line 48[0m
./build.sh CI FAILED - build.sh failure[0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.

node.js:934
            throw ee;
                  ^
Error: socket hang up
    at SecurePair.error (tls.js:949:23)
    at EncryptedStream.CryptoStream._done (tls.js:652:22)
    at CleartextStream.read [as _read] (tls.js:462:24)
    at CleartextStream.Readable.read (_stream_readable.js:308:10)
    at EncryptedStream.onCryptoStreamFinish (tls.js:274:47)
    at EncryptedStream.g (events.js:160:16)
    at EncryptedStream.emit (events.js:98:20)
    at finishMaybe (_stream_writable.js:398:12)
    at endWritable (_stream_writable.js:405:3)
    at EncryptedStream.Writable.end (_stream_writable.js:384:41)

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.

node.js:934
            throw ee;
                  ^
Error: socket hang up
    at SecurePair.error (tls.js:949:23)
    at EncryptedStream.CryptoStream._done (tls.js:652:22)
    at CleartextStream.read [as _read] (tls.js:462:24)
    at CleartextStream.Readable.read (_stream_readable.js:308:10)
    at EncryptedStream.onCryptoStreamFinish (tls.js:274:47)
    at EncryptedStream.g (events.js:160:16)
    at EncryptedStream.emit (events.js:98:20)
    at finishMaybe (_stream_writable.js:398:12)
    at endWritable (_stream_writable.js:405:3)
    at EncryptedStream.Writable.end (_stream_writable.js:384:41)
