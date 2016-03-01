#### Test (Fail) 60124347 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   0180a63..95f274b  vNext      -> origin/vNext
   1281f3a..7fe97b0  vNext_tobe_issue358 -> origin/vNext_tobe_issue358

```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext set up to track remote branch vNext from origin.
Removing thali/NextGeneration/thaliSendNotificationBasedOnReplication.js
Removing thali/NextGeneration/thaliNotificationServer.js
Auto-merging thali/NextGeneration/notification/thaliNotificationBeacons.js
Removing src/android/java/io/jxcore/node/LifeCycleMonitor.java
Removing src/android/java/io/jxcore/node/ConnectivityMonitor.java
Removing src/android/java/io/jxcore/node/ConnectionStatusListener.java
Auto-merging src/android/java/io/jxcore/node/ConnectionModel.java
Merge made by the 'recursive' strategy.
 .editorconfig                                      |   4 +
 .jshintrc                                          |   3 +-
 plugin.xml                                         |  12 +-
 src/android/JXcore.gradle                          |   2 +-
 .../java/io/jxcore/node/ConnectionHelper.java      | 791 +++++++++++----------
 ...ndConnectionModel.java => ConnectionModel.java} | 178 +++--
 .../io/jxcore/node/ConnectionStatusListener.java   |  37 -
 .../java/io/jxcore/node/ConnectivityInfo.java      | 188 +++++
 .../java/io/jxcore/node/ConnectivityMonitor.java   |  93 ---
 .../java/io/jxcore/node/IncomingSocketThread.java  |  24 +-
 .../java/io/jxcore/node/JXcoreExtension.java       | 788 ++++++++++++++------
 .../java/io/jxcore/node/JXcoreThaliCallback.java   |  41 ++
 .../java/io/jxcore/node/LifeCycleMonitor.java      |  79 --
 .../jxcore/node/ListenerOrIncomingConnection.java  |  97 +++
 .../java/io/jxcore/node/OutgoingSocketThread.java  |  34 +-
 .../java/io/jxcore/node/SocketThreadBase.java      |  69 +-
 .../java/io/jxcore/node/StreamCopyingThread.java   |  71 +-
 .../org/thaliproject/p2p/ThaliPermissions.java     |  48 +-
 test/README.md                                     |   4 +-
 test/TestServer/UnitTestFramework.js               | 132 ++--
 test/TestServer/index.js                           |  65 +-
 test/www/js/thali_main.js                          |  33 +-
 test/www/jxcore/PerfTest_app.js                    |  42 +-
 test/www/jxcore/UnitTest_app.js                    |  14 +-
 .../bv_tests/disabled/testThaliCryptoManager.js    |   4 +-
 .../disabled/testThaliReplicationManager.js        |   1 -
 test/www/jxcore/bv_tests/testPromiseQueue.js       | 151 ++++
 test/www/jxcore/bv_tests/testThaliMobile.js        | 223 ++++--
 test/www/jxcore/bv_tests/testThaliMobileNative.js  |  11 +-
 .../bv_tests/testThaliNotificationBeacons.js       |   2 +-
 .../jxcore/bv_tests/testThaliNotificationServer.js | 289 ++++++++
 .../bv_tests/testThaliReplicationUtilities.js      | 148 ++++
 .../testThaliSendNotificationBasedOnReplication.js | 665 +++++++++++++++++
 .../jxcore/bv_tests/testThaliWifiInfrastructure.js |  17 +
 test/www/jxcore/lib/httpTester.js                  |  23 +
 test/www/jxcore/lib/testUtils.js                   |  83 ++-
 test/www/jxcore/lib/thali-tape.js                  | 173 +++--
 test/www/jxcore/lib/wifiBasedNativeMock.js         |   6 +-
 test/www/jxcore/package.json                       |   2 +-
 .../jxcore/perf_tests/PerfTestFrameworkClient.js   |   2 -
 test/www/jxcore/runCoordinatedTests.js             |   5 +-
 .../{ => notification}/thaliNotificationAction.js  |   0
 .../{ => notification}/thaliNotificationBeacons.js |   2 +-
 .../{ => notification}/thaliNotificationClient.js  |   0
 .../notification/thaliNotificationServer.js        | 186 +++++
 .../{ => notification}/thaliPeerDictionary.js      |   0
 thali/NextGeneration/promiseQueue.js               |  74 +-
 .../thaliPullReplicationFromNotification.js        |   0
 .../thaliReplicationPeerAction.js                  |   0
 .../thaliSendNotificationBasedOnReplication.js     | 537 ++++++++++++++
 thali/NextGeneration/replication/utilities.js      | 136 ++++
 thali/NextGeneration/{ => security}/hkdf.js        |   0
 .../NextGeneration/{ => security}/thaliACLLayer.js |   0
 thali/NextGeneration/thaliConfig.js                |   4 +
 thali/NextGeneration/thaliMobile.js                | 319 ++++++---
 thali/NextGeneration/thaliMobileNative.js          |   4 +-
 thali/NextGeneration/thaliMobileNativeWrapper.js   |  45 +-
 thali/NextGeneration/thaliNotificationServer.js    |  89 ---
 .../{ => thaliPeerPool}/thaliPeerAction.js         |   0
 .../{ => thaliPeerPool}/thaliPeerPoolDefault.js    |   0
 .../{ => thaliPeerPool}/thaliPeerPoolInterface.js  |   0
 thali/NextGeneration/thaliReplicationManager.js    |  10 +-
 .../thaliSendNotificationBasedOnReplication.js     | 184 -----
 thali/NextGeneration/thaliWifiInfrastructure.js    |  26 +-
 www/android/thaliPermissions.js                    | 108 +--
 65 files changed, 4570 insertions(+), 1808 deletions(-)
 rename src/android/java/io/jxcore/node/{PeerAndConnectionModel.java => ConnectionModel.java} (68%)
 delete mode 100644 src/android/java/io/jxcore/node/ConnectionStatusListener.java
 create mode 100644 src/android/java/io/jxcore/node/ConnectivityInfo.java
 delete mode 100644 src/android/java/io/jxcore/node/ConnectivityMonitor.java
 create mode 100644 src/android/java/io/jxcore/node/JXcoreThaliCallback.java
 delete mode 100644 src/android/java/io/jxcore/node/LifeCycleMonitor.java
 create mode 100644 src/android/java/io/jxcore/node/ListenerOrIncomingConnection.java
 create mode 100644 test/www/jxcore/bv_tests/testThaliNotificationServer.js
 create mode 100644 test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
 create mode 100644 test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
 create mode 100644 test/www/jxcore/lib/httpTester.js
 rename thali/NextGeneration/{ => notification}/thaliNotificationAction.js (100%)
 rename thali/NextGeneration/{ => notification}/thaliNotificationBeacons.js (99%)
 rename thali/NextGeneration/{ => notification}/thaliNotificationClient.js (100%)
 create mode 100644 thali/NextGeneration/notification/thaliNotificationServer.js
 rename thali/NextGeneration/{ => notification}/thaliPeerDictionary.js (100%)
 rename thali/NextGeneration/{ => replication}/thaliPullReplicationFromNotification.js (100%)
 rename thali/NextGeneration/{ => replication}/thaliReplicationPeerAction.js (100%)
 create mode 100644 thali/NextGeneration/replication/thaliSendNotificationBasedOnReplication.js
 create mode 100644 thali/NextGeneration/replication/utilities.js
 rename thali/NextGeneration/{ => security}/hkdf.js (100%)
 rename thali/NextGeneration/{ => security}/thaliACLLayer.js (100%)
 delete mode 100644 thali/NextGeneration/thaliNotificationServer.js
 rename thali/NextGeneration/{ => thaliPeerPool}/thaliPeerAction.js (100%)
 rename thali/NextGeneration/{ => thaliPeerPool}/thaliPeerPoolDefault.js (100%)
 rename thali/NextGeneration/{ => thaliPeerPool}/thaliPeerPoolInterface.js (100%)
 delete mode 100644 thali/NextGeneration/thaliSendNotificationBasedOnReplication.js

Already on 'master'
Switched to a new branch 'vNext'
Note: checking out '7fe97b0'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 7fe97b0... Latest round of fixes

```

```
/usr/local/bin/cordova -> /usr/local/lib/node_modules/cordova/bin/cordova
cordova@6.0.0 /usr/local/lib/node_modules/cordova
├── ansi@0.3.1
├── underscore@1.7.0
├── q@1.0.1
├── nopt@3.0.1 (abbrev@1.0.7)
├── update-notifier@0.5.0 (is-npm@1.0.0, semver-diff@2.1.0, string-length@1.0.1, repeating@1.1.3, chalk@1.1.1, configstore@1.4.0, latest-version@1.0.1)
└── cordova-lib@6.0.0 (valid-identifier@0.0.1, opener@1.4.1, properties-parser@0.2.3, semver@4.3.6, shelljs@0.3.0, nopt@3.0.6, dep-graph@1.1.0, xcode@0.8.0, npmconf@2.1.2, aliasify@1.9.0, cordova-app-hello-world@3.10.0, request@2.47.0, tar@1.0.2, init-package-json@1.9.3, cordova-serve@1.0.0, npm@2.14.21, cordova-js@4.1.3)
6.0.0
node-uuid@1.4.7 node_modules/node-uuid

tape@1.1.1 node_modules/tape
├── deep-equal@0.0.0
├── defined@0.0.0
├── jsonify@0.0.0
└── through@2.3.8

express@4.13.4 node_modules/express
├── escape-html@1.0.3
├── array-flatten@1.1.1
├── utils-merge@1.0.0
├── cookie-signature@1.0.6
├── merge-descriptors@1.0.1
├── fresh@0.3.0
├── methods@1.1.2
├── range-parser@1.0.3
├── vary@1.0.1
├── path-to-regexp@0.1.7
├── cookie@0.1.5
├── parseurl@1.3.1
├── content-type@1.0.1
├── etag@1.7.0
├── content-disposition@0.5.1
├── serve-static@1.10.2
├── depd@1.1.0
├── qs@4.0.0
├── debug@2.2.0 (ms@0.7.1)
├── on-finished@2.3.0 (ee-first@1.1.1)
├── finalhandler@0.4.1 (unpipe@1.0.0)
├── proxy-addr@1.0.10 (forwarded@0.1.0, ipaddr.js@1.0.5)
├── accepts@1.2.13 (negotiator@0.5.3, mime-types@2.1.10)
├── type-is@1.6.12 (media-typer@0.3.0, mime-types@2.1.10)
└── send@0.13.1 (destroy@1.0.4, statuses@1.2.1, ms@0.7.1, mime@1.3.4, http-errors@1.3.1)

winston@2.2.0 node_modules/winston
├── cycle@1.0.3
├── stack-trace@0.0.9
├── eyes@0.1.8
├── isstream@0.1.2
├── pkginfo@0.3.1
├── async@1.0.0
└── colors@1.0.3

socket.io@1.4.5 node_modules/socket.io
├── has-binary@0.1.7 (isarray@0.0.1)
├── debug@2.2.0 (ms@0.7.1)
├── socket.io-parser@2.2.6 (isarray@0.0.1, component-emitter@1.1.2, json3@3.3.2, benchmark@1.0.0)
├── socket.io-adapter@0.4.0 (socket.io-parser@2.2.2)
└── engine.io@1.6.8 (base64id@0.1.0, engine.io-parser@1.2.4, accepts@1.1.4, ws@1.0.1)

socket.io-client@1.4.5 node_modules/socket.io-client
├── indexof@0.0.1
├── to-array@0.1.4
├── component-emitter@1.2.0
├── component-bind@1.0.0
├── backo2@1.0.2
├── object-component@0.0.3
├── debug@2.2.0 (ms@0.7.1)
├── has-binary@0.1.7 (isarray@0.0.1)
├── socket.io-parser@2.2.6 (isarray@0.0.1, component-emitter@1.1.2, json3@3.3.2, benchmark@1.0.0)
├── parseuri@0.0.4 (better-assert@1.0.2)
└── engine.io-client@1.6.8 (yeast@0.1.2, has-cors@1.1.0, component-inherit@0.0.3, component-emitter@1.1.2, xmlhttprequest-ssl@1.5.1, parsejson@0.0.1, ws@1.0.1, parseqs@0.0.2, engine.io-parser@1.2.4)

lie@3.0.2 node_modules/lie
├── immediate@3.0.5
├── inline-process-browser@1.0.0 (through2@0.6.5, falafel@1.2.0)
├── unreachable-branch-transform@0.3.0 (esmangle-evaluator@1.0.0, through2@0.6.5, recast@0.10.43)
└── es3ify@0.1.4 (through@2.3.8, esprima-fb@3001.1.0-dev-harmony-fb, jstransform@3.0.0)

fs-extra-promise@0.2.1 node_modules/fs-extra-promise
├── bluebird@2.10.2
└── fs-extra@0.24.0 (path-is-absolute@1.0.0, jsonfile@2.2.3, graceful-fs@4.1.3, rimraf@2.5.2)

> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> jx install/prePublishThaliCordovaPlugin.js

urlsafe-base64@1.0.0 node_modules/urlsafe-base64

ip@1.1.0 node_modules/ip

node-uuid@1.4.7 node_modules/node-uuid

node-ssdp@2.6.5 node_modules/node-ssdp

long@3.0.3 node_modules/long

javascript-state-machine@2.3.5 node_modules/javascript-state-machine

winston@1.1.2 node_modules/winston
├── cycle@1.0.3
├── stack-trace@0.0.9
├── eyes@0.1.8
├── isstream@0.1.2
├── pkginfo@0.3.1
├── async@1.0.0
└── colors@1.0.3

multiplex@6.6.1 node_modules/multiplex
├── varint@4.0.0
├── xtend@4.0.1
├── readable-stream@2.0.5 (isarray@0.0.1, process-nextick-args@1.0.6, util-deprecate@1.0.2, string_decoder@0.10.31, inherits@2.0.1, core-util-is@1.0.2)
└── duplexify@3.4.3 (inherits@2.0.1, end-of-stream@1.0.0)

body-parser@1.15.0 node_modules/body-parser
├── bytes@2.2.0
├── content-type@1.0.1
├── depd@1.1.0
├── on-finished@2.3.0 (ee-first@1.1.1)
├── raw-body@2.1.5 (unpipe@1.0.0)
├── http-errors@1.4.0 (inherits@2.0.1, statuses@1.2.1)
├── qs@6.1.0
├── debug@2.2.0 (ms@0.7.1)
├── iconv-lite@0.4.13
└── type-is@1.6.12 (media-typer@0.3.0, mime-types@2.1.10)

express@4.13.3 node_modules/express
├── escape-html@1.0.2
├── array-flatten@1.1.1
├── merge-descriptors@1.0.0
├── utils-merge@1.0.0
├── cookie-signature@1.0.6
├── cookie@0.1.3
├── fresh@0.3.0
├── methods@1.1.2
├── range-parser@1.0.3
├── vary@1.0.1
├── path-to-regexp@0.1.7
├── parseurl@1.3.1
├── content-type@1.0.1
├── etag@1.7.0
├── content-disposition@0.5.0
├── depd@1.0.1
├── on-finished@2.3.0 (ee-first@1.1.1)
├── finalhandler@0.4.0 (unpipe@1.0.0)
├── qs@4.0.0
├── proxy-addr@1.0.10 (forwarded@0.1.0, ipaddr.js@1.0.5)
├── serve-static@1.10.2 (escape-html@1.0.3, send@0.13.1)
├── debug@2.2.0 (ms@0.7.1)
├── send@0.13.0 (destroy@1.0.3, statuses@1.2.1, ms@0.7.1, mime@1.3.4, http-errors@1.3.1)
├── type-is@1.6.12 (media-typer@0.3.0, mime-types@2.1.10)
└── accepts@1.2.13 (negotiator@0.5.3, mime-types@2.1.10)

lie@3.0.2 node_modules/lie
├── immediate@3.0.5
├── inline-process-browser@1.0.0 (through2@0.6.5, falafel@1.2.0)
├── unreachable-branch-transform@0.3.0 (esmangle-evaluator@1.0.0, through2@0.6.5, recast@0.10.43)
└── es3ify@0.1.4 (through@2.3.8, jstransform@3.0.0, esprima-fb@3001.1.0-dev-harmony-fb)

request@2.69.0 node_modules/request
├── is-typedarray@1.0.0
├── aws-sign2@0.6.0
├── forever-agent@0.6.1
├── stringstream@0.0.5
├── caseless@0.11.0
├── tunnel-agent@0.4.2
├── oauth-sign@0.8.1
├── isstream@0.1.2
├── json-stringify-safe@5.0.1
├── extend@3.0.0
├── combined-stream@1.0.5 (delayed-stream@1.0.0)
├── qs@6.0.2
├── mime-types@2.1.10 (mime-db@1.22.0)
├── tough-cookie@2.2.1
├── form-data@1.0.0-rc3 (async@1.5.2)
├── bl@1.0.3 (readable-stream@2.0.5)
├── aws4@1.3.1 (lru-cache@4.0.0)
├── hawk@3.1.3 (cryptiles@2.0.5, sntp@1.0.9, boom@2.10.1, hoek@2.16.3)
├── http-signature@1.1.1 (assert-plus@0.2.0, jsprim@1.2.2, sshpk@1.7.4)
└── har-validator@2.0.6 (pinkie-promise@2.0.0, commander@2.9.0, chalk@1.1.1, is-my-json-valid@2.13.1)

jsdoc@3.4.0 node_modules/jsdoc
├── escape-string-regexp@1.0.5
├── strip-json-comments@1.0.4
├── async@1.4.2
├── taffydb@2.6.2
├── underscore@1.8.3
├── wrench@1.5.8
├── marked@0.3.5
├── js2xmlparser@1.0.0
├── espree@2.2.5
├── requizzle@0.2.1 (underscore@1.6.0)
├── bluebird@2.9.34
└── catharsis@0.8.7 (underscore-contrib@0.3.0)

> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> jx install/prePublishThaliCordovaPlugin.js

/usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali
fs-extra-promise@0.2.1 node_modules/fs-extra-promise
├── bluebird@2.10.2
└── fs-extra@0.24.0 (path-is-absolute@1.0.0, jsonfile@2.2.3, graceful-fs@4.1.3, rimraf@2.5.2)

unzip@0.1.11 node_modules/unzip
├── setimmediate@1.0.4
├── readable-stream@1.0.33 (isarray@0.0.1, inherits@2.0.1, string_decoder@0.10.31, core-util-is@1.0.2)
├── pullstream@0.4.1 (slice-stream@1.0.0, over@0.0.5)
├── match-stream@0.0.2 (buffers@0.1.1)
├── fstream@0.1.31 (inherits@2.0.1, graceful-fs@3.0.8, mkdirp@0.5.1, rimraf@2.5.2)
└── binary@0.3.0 (buffers@0.1.1, chainsaw@0.1.0)

lie@3.0.2 node_modules/lie
├── immediate@3.0.5
├── inline-process-browser@1.0.0 (through2@0.6.5, falafel@1.2.0)
├── unreachable-branch-transform@0.3.0 (esmangle-evaluator@1.0.0, through2@0.6.5, recast@0.10.43)
└── es3ify@0.1.4 (through@2.3.8, jstransform@3.0.0, esprima-fb@3001.1.0-dev-harmony-fb)

request@2.69.0 node_modules/request
├── is-typedarray@1.0.0
├── aws-sign2@0.6.0
├── forever-agent@0.6.1
├── caseless@0.11.0
├── stringstream@0.0.5
├── tunnel-agent@0.4.2
├── oauth-sign@0.8.1
├── isstream@0.1.2
├── json-stringify-safe@5.0.1
├── extend@3.0.0
├── node-uuid@1.4.7
├── qs@6.0.2
├── tough-cookie@2.2.1
├── combined-stream@1.0.5 (delayed-stream@1.0.0)
├── mime-types@2.1.10 (mime-db@1.22.0)
├── form-data@1.0.0-rc3 (async@1.5.2)
├── bl@1.0.3 (readable-stream@2.0.5)
├── aws4@1.3.1 (lru-cache@4.0.0)
├── hawk@3.1.3 (cryptiles@2.0.5, sntp@1.0.9, boom@2.10.1, hoek@2.16.3)
├── har-validator@2.0.6 (pinkie-promise@2.0.0, commander@2.9.0, chalk@1.1.1, is-my-json-valid@2.13.1)
└── http-signature@1.1.1 (assert-plus@0.2.0, jsprim@1.2.2, sshpk@1.7.4)

jxc@1.0.13 node_modules/jxc
└── jxtools@0.0.4 (progress@1.1.8, adm-zip@0.4.7)

> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/thali
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies
/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/thali -> /usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali

> leveldown-mobile@1.1.1 install /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/leveldown-mobile
> node-gyp rebuild

Target arch x64
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/db_impl.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/db_iter.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/filename.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/dbformat.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/log_reader.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/log_writer.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/memtable.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/repair.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/table_cache.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/version_edit.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/version_set.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/db/write_batch.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/helpers/memenv/memenv.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/block.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/block_builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/filter_block.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/format.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/iterator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/merger.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/table.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/table_builder.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/table/two_level_iterator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/arena.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/bloom.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/cache.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/coding.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/comparator.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/crc32c.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/env.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/filter_policy.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/hash.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/logging.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/options.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/status.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/port/port_posix.o
  CXX(target) Release/obj.target/leveldb/deps/leveldb/leveldb-1.17.0/util/env_posix.o
  LIBTOOL-STATIC Release/leveldb.a
  CXX(target) Release/obj.target/snappy/deps/snappy/snappy-1.1.1/snappy-sinksource.o
  CXX(target) Release/obj.target/snappy/deps/snappy/snappy-1.1.1/snappy-stubs-internal.o
  CXX(target) Release/obj.target/snappy/deps/snappy/snappy-1.1.1/snappy.o
  LIBTOOL-STATIC Release/snappy.a
  CXX(target) Release/obj.target/leveldown/src/batch.o
  CXX(target) Release/obj.target/leveldown/src/batch_async.o
  CXX(target) Release/obj.target/leveldown/src/database.o
  CXX(target) Release/obj.target/leveldown/src/database_async.o
  CXX(target) Release/obj.target/leveldown/src/iterator.o
  CXX(target) Release/obj.target/leveldown/src/iterator_async.o
  CXX(target) Release/obj.target/leveldown/src/leveldown.o
  CXX(target) Release/obj.target/leveldown/src/leveldown_async.o
  SOLINK_MODULE(target) Release/leveldown.node
  SOLINK_MODULE(target) Release/leveldown.node: Finished
wrapping-tape@0.0.3 node_modules/wrapping-tape

urlsafe-base64@1.0.0 node_modules/urlsafe-base64

is-property@1.0.2 node_modules/is-property

concat-map@0.0.1 node_modules/concat-map

balanced-match@0.2.1 node_modules/balanced-match

tape-catch@1.0.4 node_modules/tape-catch

uuid@2.0.1 node_modules/uuid

node-uuid@1.4.7 node_modules/node-uuid

minimist@1.2.0 node_modules/minimist

bn.js@4.10.5 node_modules/bn.js

long@3.0.3 node_modules/long

tmp@0.0.28 node_modules/tmp
└── os-tmpdir@1.0.1

node-ssdp@2.6.5 node_modules/node-ssdp
└── ip@1.1.0

randomstring@1.1.4 node_modules/randomstring
└── array-uniq@1.0.2

proxyquire@1.7.4 node_modules/proxyquire
├── module-not-found-error@1.0.1
└── fill-keys@1.0.2 (merge-descriptors@1.0.1, is-object@1.0.1)

multiplex@6.6.1 node_modules/multiplex
├── varint@4.0.0
├── xtend@4.0.1
├── readable-stream@2.0.5 (isarray@0.0.1, process-nextick-args@1.0.6, util-deprecate@1.0.2, string_decoder@0.10.31, core-util-is@1.0.2, inherits@2.0.1)
└── duplexify@3.4.3 (inherits@2.0.1, end-of-stream@1.0.0)

supertest-as-promised@2.0.2 node_modules/supertest-as-promised
├── methods@1.1.2
└── bluebird@2.10.2

fs-extra-promise@0.2.1 node_modules/fs-extra-promise
├── bluebird@2.10.2
└── fs-extra@0.24.0 (path-is-absolute@1.0.0, jsonfile@2.2.3, graceful-fs@4.1.3, rimraf@2.5.2)

body-parser@1.15.0 node_modules/body-parser
├── bytes@2.2.0
├── content-type@1.0.1
├── depd@1.1.0
├── on-finished@2.3.0 (ee-first@1.1.1)
├── raw-body@2.1.5 (unpipe@1.0.0)
├── http-errors@1.4.0 (statuses@1.2.1, inherits@2.0.1)
├── debug@2.2.0 (ms@0.7.1)
├── qs@6.1.0
├── iconv-lite@0.4.13
└── type-is@1.6.12 (media-typer@0.3.0, mime-types@2.1.10)

socket.io-client@1.4.5 node_modules/socket.io-client
├── to-array@0.1.4
├── indexof@0.0.1
├── component-emitter@1.2.0
├── component-bind@1.0.0
├── backo2@1.0.2
├── object-component@0.0.3
├── has-binary@0.1.7 (isarray@0.0.1)
├── parseuri@0.0.4 (better-assert@1.0.2)
├── debug@2.2.0 (ms@0.7.1)
├── socket.io-parser@2.2.6 (isarray@0.0.1, component-emitter@1.1.2, json3@3.3.2, benchmark@1.0.0)
└── engine.io-client@1.6.8 (yeast@0.1.2, component-inherit@0.0.3, has-cors@1.1.0, component-emitter@1.1.2, xmlhttprequest-ssl@1.5.1, parsejson@0.0.1, parseqs@0.0.2, ws@1.0.1, engine.io-parser@1.2.4)

request@2.69.0 node_modules/request
├── is-typedarray@1.0.0
├── aws-sign2@0.6.0
├── forever-agent@0.6.1
├── caseless@0.11.0
├── stringstream@0.0.5
├── tunnel-agent@0.4.2
├── oauth-sign@0.8.1
├── isstream@0.1.2
├── json-stringify-safe@5.0.1
├── extend@3.0.0
├── combined-stream@1.0.5 (delayed-stream@1.0.0)
├── qs@6.0.2
├── mime-types@2.1.10 (mime-db@1.22.0)
├── tough-cookie@2.2.1
├── form-data@1.0.0-rc3 (async@1.5.2)
├── aws4@1.3.1 (lru-cache@4.0.0)
├── bl@1.0.3 (readable-stream@2.0.5)
├── har-validator@2.0.6 (pinkie-promise@2.0.0, commander@2.9.0, chalk@1.1.1, is-my-json-valid@2.13.1)
├── http-signature@1.1.1 (assert-plus@0.2.0, jsprim@1.2.2, sshpk@1.7.4)
└── hawk@3.1.3 (cryptiles@2.0.5, sntp@1.0.9, boom@2.10.1, hoek@2.16.3)

express@4.13.4 node_modules/express
├── escape-html@1.0.3
├── array-flatten@1.1.1
├── utils-merge@1.0.0
├── cookie-signature@1.0.6
├── merge-descriptors@1.0.1
├── fresh@0.3.0
├── methods@1.1.2
├── range-parser@1.0.3
├── vary@1.0.1
├── path-to-regexp@0.1.7
├── cookie@0.1.5
├── parseurl@1.3.1
├── etag@1.7.0
├── content-disposition@0.5.1
├── serve-static@1.10.2
├── content-type@1.0.1
├── qs@4.0.0
├── on-finished@2.3.0 (ee-first@1.1.1)
├── depd@1.1.0
├── finalhandler@0.4.1 (unpipe@1.0.0)
├── proxy-addr@1.0.10 (forwarded@0.1.0, ipaddr.js@1.0.5)
├── send@0.13.1 (destroy@1.0.4, statuses@1.2.1, ms@0.7.1, mime@1.3.4, http-errors@1.3.1)
├── debug@2.2.0 (ms@0.7.1)
├── accepts@1.2.13 (negotiator@0.5.3, mime-types@2.1.10)
└── type-is@1.6.12 (media-typer@0.3.0, mime-types@2.1.10)

tape@4.4.0 node_modules/tape
├── inherits@2.0.1
├── has@1.0.1
├── defined@1.0.0
├── resumer@0.0.0
├── deep-equal@1.0.1
├── function-bind@1.0.2
├── object-inspect@1.0.2
├── through@2.3.8
├── resolve@1.1.7
├── glob@5.0.15 (path-is-absolute@1.0.0, once@1.3.3, inflight@1.0.4, minimatch@3.0.0)
└── string.prototype.trim@1.1.2 (define-properties@1.1.2, es-abstract@1.5.0)

supertest@1.2.0 node_modules/supertest
├── methods@1.1.2
└── superagent@1.8.0-beta.2 (component-emitter@1.2.0, cookiejar@2.0.6, reduce-component@1.0.1, extend@3.0.0, mime@1.3.4, formidable@1.0.17, qs@2.3.3, debug@2.2.0, readable-stream@1.0.27-1, form-data@1.0.0-rc3)

lie@3.0.2 node_modules/lie
├── immediate@3.0.5
├── inline-process-browser@1.0.0 (through2@0.6.5, falafel@1.2.0)
├── unreachable-branch-transform@0.3.0 (esmangle-evaluator@1.0.0, through2@0.6.5, recast@0.10.43)
└── es3ify@0.1.4 (through@2.3.8, jstransform@3.0.0, esprima-fb@3001.1.0-dev-harmony-fb)

request-promise@0.4.3 node_modules/request-promise
├── chalk@1.1.1 (escape-string-regexp@1.0.5, supports-color@2.0.0, strip-ansi@3.0.1, has-ansi@2.0.0, ansi-styles@2.2.0)
├── bluebird@2.10.2
└── lodash@3.10.1

nock@2.18.2 node_modules/nock
├── propagate@0.3.1
├── deep-equal@1.0.1
├── lodash@2.4.1
├── mkdirp@0.5.1 (minimist@0.0.8)
├── debug@1.0.4 (ms@0.6.2)
└── chai@3.5.0 (assertion-error@1.0.1, type-detect@1.0.0, deep-eql@0.1.3)

sinon@1.17.3 node_modules/sinon
├── formatio@1.1.1
├── samsam@1.1.2
├── lolex@1.3.2
└── util@0.10.3 (inherits@2.0.1)

pouchdb@5.2.1 node_modules/pouchdb
├── pouchdb-collections@1.0.1
├── scope-eval@0.0.3
├── inherits@2.0.1
├── js-extend@1.0.1
├── argsarray@0.0.1
├── double-ended-queue@2.0.0-0
├── vuvuzela@1.0.2
├── debug@2.2.0 (ms@0.7.1)
├── pouchdb-collate@1.2.0
├── spark-md5@2.0.0
├── memdown@1.1.2 (ltgt@1.0.2, functional-red-black-tree@1.0.1, abstract-leveldown@2.4.1)
├── fruitdown@1.0.1 (d64@1.0.0, tiny-queue@0.2.0, abstract-leveldown@0.12.3)
├── through2@2.0.0 (xtend@4.0.1, readable-stream@2.0.5)
├── level-write-stream@1.0.0 (end-stream@0.1.0)
├── levelup@1.3.1 (prr@1.0.1, level-codec@6.1.0, xtend@4.0.1, semver@5.1.0, level-iterator-stream@1.3.1, deferred-leveldown@1.2.1, level-errors@1.0.4)
├── localstorage-down@0.6.6 (d64@1.0.0, tiny-queue@0.2.0, abstract-leveldown@0.12.3, humble-localstorage@1.4.2)
├── request@2.67.0 (is-typedarray@1.0.0, aws-sign2@0.6.0, forever-agent@0.6.1, caseless@0.11.0, stringstream@0.0.5, tunnel-agent@0.4.2, oauth-sign@0.8.1, isstream@0.1.2, json-stringify-safe@5.0.1, extend@3.0.0, qs@5.2.0, combined-stream@1.0.5, tough-cookie@2.2.1, bl@1.0.3, mime-types@2.1.10, form-data@1.0.0-rc3, har-validator@2.0.6, http-signature@1.1.1, hawk@3.1.3)
├── level-sublevel@6.5.4 (typewiselite@1.0.0, ltgt@2.1.2, xtend@4.0.1, pull-stream@2.21.0, bytewise@1.1.0, levelup@0.19.1)
└── es3ify@0.2.0 (through@2.3.8, esprima@2.7.2, jstransform@3.0.0)

leveldown-mobile@1.1.1 node_modules/leveldown-mobile
├── bindings@1.2.1
├── fast-future@1.0.1
└── abstract-leveldown@2.1.4 (xtend@4.0.1)

express-pouchdb@1.0.2 node_modules/express-pouchdb
├── header-case-normalizer@1.0.3
├── basic-auth@1.0.3
├── extend@1.3.0
├── node-uuid@1.4.1
├── on-finished@2.3.0 (ee-first@1.1.1)
├── cookie-parser@1.4.1 (cookie-signature@1.0.6, cookie@0.2.3)
├── pouchdb-wrappers@1.3.6 (promise-nodify@1.0.2)
├── bluebird@2.10.2
├── pouchdb-vhost@1.0.2 (promise-nodify@1.0.2, pouchdb-route@1.0.3)
├── pouchdb-size@1.2.2 (promise-nodify@1.0.2, get-folder-size@0.1.1)
├── raw-body@1.3.4 (bytes@1.0.0, iconv-lite@0.4.8)
├── compression@1.6.1 (on-headers@1.0.1, vary@1.1.0, bytes@2.2.0, compressible@2.0.7, debug@2.2.0, accepts@1.3.1)
├── multiparty@3.3.2 (stream-counter@0.2.0, readable-stream@1.1.13)
├── pouchdb-validation@1.2.1 (pouchdb-plugin-error@1.0.1, random-uuid-v4@0.0.4, pouchdb-bulkdocs-wrapper@1.0.2, couchdb-eval@1.0.6, couchdb-objects@1.0.7, pouchdb-promise@0.0.0)
├── pouchdb-update@1.0.8 (couchdb-eval@1.0.6, pouchdb-plugin-error@1.0.1, promise-nodify@1.0.2, couchdb-resp-completer@1.0.3, couchdb-objects@1.0.7, pouchdb-req-http-query@1.0.3, pouchdb-promise@0.0.0)
├── pouchdb-security@1.2.6 (pouchdb-changeslike-wrapper@1.0.1, pouchdb-bulkdocs-wrapper@1.0.2, pouchdb-plugin-error@1.0.1, promise-nodify@1.0.2, pouchdb-req-http-query@1.0.3, pouchdb-promise@0.0.0)
├── pouchdb-list@1.1.0 (pouchdb-plugin-error@1.0.1, promise-nodify@1.0.2, extend@3.0.0, couchdb-objects@1.0.7, couchdb-render@1.0.1, pouchdb-req-http-query@1.0.3, pouchdb-promise@0.0.0)
├── pouchdb-replicator@2.1.3 (pouchdb-plugin-error@1.0.1, random-uuid-v4@0.0.4, promise-nodify@1.0.2, pouchdb-system-db@1.0.4, equals@1.0.1, pouchdb-promise@0.0.0)
├── pouchdb-rewrite@1.0.7 (pouchdb-route@1.0.3, promise-nodify@1.0.2, pouchdb-plugin-error@1.0.1, pouchdb-req-http-query@1.0.3, couchdb-objects@1.0.7)
├── pouchdb-show@1.0.8 (promise-nodify@1.0.2, pouchdb-plugin-error@1.0.1, couchdb-render@1.0.1, couchdb-objects@1.0.7, pouchdb-req-http-query@1.0.3, pouchdb-promise@0.0.0)
├── pouchdb-all-dbs@1.0.1 (inherits@2.0.1, tiny-queue@0.2.1, argsarray@0.0.1, es3ify@0.1.4, lie@2.9.1)
├── pouchdb-auth@1.0.5 (pouchdb-plugin-error@1.0.1, promise-nodify@1.0.2, pouchdb-bulkdocs-wrapper@1.0.2, secure-random@1.1.1, pouchdb-system-db@1.0.4, crypto-lite@0.0.4, pouchdb-req-http-query@1.0.3, pouchdb-promise@0.0.0)
└── pouchdb-find@0.1.0 (inherits@2.0.1, argsarray@0.0.1, pouchdb-extend@0.1.2, pouchdb-upsert@1.1.3, spark-md5@0.0.5, pouchdb-collate@1.2.0, pouchdb-abstract-mapreduce@0.2.2, debug@2.2.0, es3ify@0.1.4, lie@2.9.1, jshint@2.9.1)

> thali-cordova-plugin-jxcore@1.0.0 test /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js

Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMultiplex.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTCPServersManager.js
Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
TAP version 13
# setup
# closeAll can close even when connections open
INFO thaliMobileNativeWrapper Method peerAvailabilityChanged registered to native
ok 1 expect a specific error when the connection is closed
ok 2 not possible to connect to the server anymore
INFO thaliMobileNativeWrapper Method discoveryAdvertisingStateUpdateNonTCP registered to native
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobileNativeWrapper Method networkChanged registered to native
INFO thaliMobileNativeWrapper Method incomingConnectionToPortNumberFailed registered to native
# teardown
# setup
# multiplex can send data
ok 3 String should be length:200
# teardown
# setup
# enqueue and run in order
ok 4 firstPromise setTimeout
ok 5 firstPromise result
ok 6 firstPromise testValue
ok 7 secondPromise setTimeout
ok 8 secondPromise result
ok 9 secondPromise testValue
ok 10 thirdPromise in promise
ok 11 thirdPromise result
ok 12 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 13 thirdPromise - first to run
ok 14 thirdPromise - in resolve
ok 15 secondPromise - second to run
ok 16 secondPromise - in catch
ok 17 firstPromise - third to run
ok 18 firstPromise - in then
ok 19 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 20 fourth
ok 21 fourth
ok 22 second
ok 23 secondPromise - in then
ok 24 first
ok 25 firstPromise - in catch
ok 26 third
ok 27 thirdPromise - in then
ok 28 testingPromises
# teardown
# setup
# queues handled independently
ok 29 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 30 sane
# teardown
# setup
# another
ok 31 sane
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 32 specific error should be returned
# teardown
ok 33 error should be null
ok 34 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 35 specific error should be returned
# teardown
ok 36 error should be null
ok 37 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
ok 38 error should be null
ok 39 error should be null
ok 40 error should be null
ok 41 error should be null
# teardown
ok 42 error should be null
ok 43 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
ok 44 error should be null
ok 45 error should be null
ok 46 error should be null
ok 47 error should be null
# teardown
INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 48 error should be null
ok 49 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
ok 50 error should be null
ok 51 error should be null
ok 52 error should be null
ok 53 error should be null
# teardown
INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 54 error should be null
ok 55 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
ok 56 error should be null
ok 57 error should be null
ok 58 error should be null
ok 59 error should be null
# teardown
ok 60 error should be null
ok 61 error should be null
# setup
# #start should fail if called twice in a row
ok 62 first call should succeed
ok 63 first call should succeed
ok 64 specific error should be returned
# teardown
ok 65 error should be null
ok 66 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
ok 67 called only once
ok 68 discovery state matches
ok 69 advertising state matches
# teardown
INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 70 error should be null
ok 71 error should be null
# setup
# does not send duplicate availability changes
ok 72 should be called once
ok 73 should not have been called more than once
# teardown
ok 74 error should be null
ok 75 error should be null
# setup
# can get the network status
ok 76 network status should have certain non-empty properties
# teardown
ok 77 error should be null
ok 78 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
ok 79 host address should match
ok 80 port should match
ok 81 host address should be null
ok 82 port should should be null
# teardown
INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 83 error should be null
ok 84 error should be null
# setup
# network changes emitted correctly
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 85 wifi is off
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 86 wifi is on
# teardown
ok 87 error should be null
ok 88 error should be null
# setup
# network changes not emitted in stopped state
ok 89 event was not emitted
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
ok 90 error should be null
ok 91 error should be null
# setup
# calls correct starts when network changes
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 92 specific error expected
ok 93 specific error expected
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}
ok 94 startListeningForAdvertisements should have been called
ok 95 startUpdateAdvertisingAndListening should have been called
# teardown
INFO thaliMobile Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}
INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
INFO thaliMobile Filtered out discoveryAdvertisingStateUpdate (was in stopped state).
ok 96 error should be null
ok 97 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
INFO testUtils Toggling radios to: false
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 98 host address should be null
ok 99 port number should be null
INFO testUtils Toggling radios to: true
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# teardown
ok 100 error should be null
ok 101 error should be null
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
# setup
# Can call start/stopListeningForAdvertisements
ok 102 Can call startListeningForAdvertisements without error
ok 103 Can call stopListeningForAdvertisements without error
# teardown
ok 104 Should be able to call stopListeningForAdvertisments in teardown
ok 105 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is an error
ok 106 Can call startListeningForAdvertisements without error
ok 107 Calling start twice is an error
ok 108 Error must be "Call Stop!"
# teardown
ok 109 Should be able to call stopListeningForAdvertisments in teardown
ok 110 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
ok 111 Can call startUpdateAdvertisingAndListening without error
ok 112 Can call stopAdvertisingAndListening without error
# teardown
ok 113 Should be able to call stopListeningForAdvertisments in teardown
ok 114 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT and error
ok 115 Can call startUpdateAdvertisingAndListening without error
ok 116 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 117 Should be able to call stopListeningForAdvertisments in teardown
ok 118 Should be able to call stopAdvertisingAndListening in teardown
# setup
# can get the network status before starting
ok 119 network status should have certain non-empty properties
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 120 publicKeysToNotify cannot be null
ok 121 ecdh for local device cannot be null
ok 122 milliseconds cannot be less than 0
ok 123 milliseconds cannot be 0
ok 124 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 125 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 126 should be equal
ok 127 should be equal
ok 128 (unnamed assert)
ok 129 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 130 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 131 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 132 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 133 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 134 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 135 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 136 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 137 should be equal
ok 138 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 139 should be equal
ok 140 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 141 should be equal
ok 142 (unnamed assert)
# teardown
# setup
# #parseBeacons with beacons both for and not for the user
ok 143 should be equal
ok 144 (unnamed assert)
# teardown
# setup
# Start and stop ThaliNotificationServer
ok 145 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 146 ThaliMobile.StopAdvertisingAndListening should be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 147 StartUpdateAdvertisingAndListening should not be called
ok 148 ThaliMobile.StopAdvertisingAndListening should be called once
ok 149 no error
ok 150 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 151 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 152 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 153 no error
ok 154 should be 200
ok 155 should be equal
ok 156 should be equal
ok 157 (unnamed assert)
ok 158 no error
ok 159 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 160 error should be null
ok 161 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons before calling start
ok 162 should be 404
# teardown
# setup
# compareBufferArrays
ok 163 should throw
ok 164 should throw
ok 165 (unnamed assert)
ok 166 (unnamed assert)
ok 167 (unnamed assert)
ok 168 (unnamed assert)
ok 169 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 170 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 171 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 172 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 173 should be equal
ok 174 should be equal
ok 175 should throw
# teardown
# setup
# Test TransientState
ok 176 should throw
ok 177 should throw
ok 178 should be equal
ok 179 should be equal
ok 180 should be equal
ok 181 should be equal
ok 182 (unnamed assert)
ok 183 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 184 verify failed
ok 185 constructor called once
ok 186 constructor called with right args
ok 187 match start arg
ok 188 start called once
ok 189 stop called once
ok 190 stop after start
# teardown
# setup
# One peer and empty DB
ok 191 verify failed
ok 192 constructor called once
ok 193 constructor called with right args
ok 194 match start arg
ok 195 start called once
ok 196 stop called once
ok 197 stop after start
# teardown
# setup
# One peer with _Local set behind current seq
ok 198 verify failed
ok 199 constructor called once
ok 200 constructor called with right args
ok 201 match start arg
ok 202 start called once
ok 203 stop called once
ok 204 stop after start
# teardown
# setup
# One peer with _Local set equal to current seq
ok 205 verify failed
ok 206 constructor called once
ok 207 constructor called with right args
ok 208 match start arg
ok 209 start called once
ok 210 stop called once
ok 211 stop after start
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 212 verify failed
ok 213 constructor called once
ok 214 constructor called with right args
ok 215 match start arg
ok 216 start called once
ok 217 stop called once
ok 218 stop after start
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 219 verify failed
ok 220 constructor called once
ok 221 constructor called with right args
ok 222 match start arg
ok 223 start called once
ok 224 stop called once
ok 225 stop after start
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 226 verify failed
ok 227 constructor called once
ok 228 constructor called with right args
ok 229 match start arg
ok 230 start called once
ok 231 stop called once
ok 232 stop after start
# teardown
# setup
# two peers with empty DB, update the doc
ok 233 verify failed
ok 234 constructor called once
ok 235 constructor called with right args
ok 236 last start before stop
ok 237 empty first start
ok 238 full second start
ok 239 only 2 timers
# teardown
# setup
# add doc and make sure tokens refresh when they expire
ok 240 verify failed
ok 241 constructor called once
ok 242 constructor called with right args
ok 243 start before stop
ok 244 We got at least 3 calls to start
ok 245 at least 3
ok 246 default 1
ok 247 1 run
ok 248 default 2
ok 249 2 run
ok 250 default 3
# teardown
# setup
# start and stop and start and stop
ok 251 start out null
ok 252 back to null
ok 253 still null
ok 254 verify failed
ok 255 constructor called once
ok 256 constructor called with right args
ok 257 first start before first stop
ok 258 first stop before second start
ok 259 second start before second stop
# teardown
# setup
# two identical starts in a row
ok 260 verify failed
ok 261 constructor called once
ok 262 constructor called with right args
ok 263 (unnamed assert)
# teardown
# setup
# two different starts in a row
ok 264 verify failed
ok 265 constructor called once
ok 266 constructor called with right args
ok 267 (unnamed assert)
ok 268 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 269 verify failed
ok 270 constructor called once
ok 271 constructor called with right args
ok 272 start before stop
# teardown
# setup
# we properly enqueue requests so no then needed
ok 273 verify failed
ok 274 constructor called once
ok 275 constructor called with right args
ok 276 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 277 should be equal
ok 278 should be equal
# teardown
# setup
# can create servers manager
ok 279 manager must not be null
ok 280 manager must be an object
# teardown
# setup
# can start/stop servers manager
ok 281 port must be in range
# teardown
# setup
# starting twice resolves with listening port
ok 282 second start should return same port
# teardown
# setup
# calling startNativeListener directly throws
ok 283 Should throw
# teardown
# setup
# emits incomingConnectionState
ok 284 initial connection state should be CONNECTED
ok 285 final connection state should be DISCONNECTED
# teardown
# setup
# emits routerPortConnectionFailed
WARN tcpServersManager { [Error: connect ECONNREFUSED]
  code: 'ECONNREFUSED',
  errno: 'ECONNREFUSED',
  syscall: 'connect' } undefined
ok 286 routerPortConnectionFailed is emitted
# teardown
# setup
# native server connections all up
ok 287 Send/recvd #1 should be equal length
ok 288 Send/recvd #1 should be same
ok 289 Send/recvd #2 should be equal length
ok 290 Send/recvd #2 should be same
ok 291 Should be exactly 2 client sockets
# teardown
# setup
# can call createPeerListener (pleaseConnect == false)
ok 292 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect == true) with unknown peer is error
WARN tcpServersManager Unknown peer
ok 293 should get error
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect == true - no native server
ok 294 Can call startUpdateAdvertisingAndListening without error
ok 295 Can call startListeningForAdvertisements without error
WARN tcpServersManager outgoing socket - Error: connect ECONNREFUSED
ok 296 reason should be as expected
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect == false - no native server
ok 297 Can call startUpdateAdvertisingAndListening without error
ok 298 Can call startListeningForAdvertisements without error
ok 299 peerPort should not be nativePort
WARN tcpServersManager 
ok 300 Should not get event until connection is made
ok 301 reason should be as expected
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect == true - with native server
ok 302 Can call startUpdateAdvertisingAndListening without error
ok 303 Can call startListeningForAdvertisements without error
ok 304 Should get spontaneous connection
ok 305 peerPort != nativePort
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect == false - with native server
ok 306 Can call startUpdateAdvertisingAndListening without error
ok 307 Can call startListeningForAdvertisements without error
ok 308 peerPort != nativePort
ok 309 Should not get unexpected connection
ok 310 Should get connection
# teardown
# setup
# createPeerListener is idempotent
ok 311 Can call startUpdateAdvertisingAndListening without error
ok 312 Can call startListeningForAdvertisements without error
ok 313 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect == true, failed connection rejects promise
ok 314 Can call startUpdateAdvertisingAndListening without error
ok 315 Can call startListeningForAdvertisements without error
WARN tcpServersManager a nasty error
ok 316 failed connection should reject with error
# teardown
# setup
# createPeerListener - pleaseConnect == true, connection resolves promise
ok 317 Can call startUpdateAdvertisingAndListening without error
ok 318 Can call startListeningForAdvertisements without error
ok 319 promise should resolve
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect == true
ok 320 Can call startUpdateAdvertisingAndListening without error
ok 321 Can call startListeningForAdvertisements without error
WARN tcpServersManager was expecting a forward connection to be made
ok 322 reason should be as expected
WARN tcpServersManager outgoing socket - Error: read ECONNRESET
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect == false - no incoming
ok 323 Can call startUpdateAdvertisingAndListening without error
ok 324 Can call startListeningForAdvertisements without error
ok 325 peerPort should not be nativePort
ok 326 should not get event until connection is made
ok 327 reason should be as expected
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect == false - with incoming
ok 328 Can call startUpdateAdvertisingAndListening without error
ok 329 Can call startListeningForAdvertisements without error
ok 330 sent and received should be the same
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect == false - no server
ok 331 Can call startUpdateAdvertisingAndListening without error
ok 332 Can call startListeningForAdvertisements without error
WARN tcpServersManager { [Error: connect ECONNREFUSED]
  code: 'ECONNREFUSED',
  errno: 'ECONNREFUSED',
  syscall: 'connect' } undefined
ok 333 should get routerPortConnectionFailed
# teardown
# setup
# native server - closing incoming stream cleans outgoing socket
ok 334 socket shouldn't close until after stream
ok 335 socket gets closed when stream is
ok 336 incoming remains open
# teardown
# setup
# native server - closing incoming stream cleans outgoing socket
ok 337 stream was closed
ok 338 incoming should survive
ok 339 mux should have no streams
# teardown
# setup
ok 340 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 341 peer identifier should match
ok 342 host address should match
ok 343 port should match
ok 344 host address should be null
ok 345 port should should be null
# teardown
ok 346 should not be in started state
# setup
ok 347 should be in started state
# #startUpdateAdvertisingAndListening should use different USN after every invocation
ok 348 USN should have changed from the first one
ok 349 when receiving the second byebye, the first USN should be already set
# teardown
ok 350 should not be in started state
# setup
ok 351 should be in started state
# messages with invalid location or USN should be ignored
WARN thaliWifiInfrastructure Failed to parse a valid port number from location: http://foo.bar:90000
ok 352 should not have emitted with invalid port
WARN thaliWifiInfrastructure Received an invalid USN value: 
ok 353 should not have emitted with invalid USN
# teardown
ok 354 should not be in started state
# setup
ok 355 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 356 irrelevant messages should be ignored
ok 357 relevant messages should not be ignored
ok 358 messages from this device should be ignored
# teardown
ok 359 should not be in started state
# setup
ok 360 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 361 specific error should be returned
# teardown
ok 362 should not be in started state
# setup
ok 363 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 364 specific error should be returned
# teardown
ok 365 should not be in started state
# setup
ok 366 should be in started state
# #start should fail if called twice in a row
ok 367 specific error should be received
# teardown
ok 368 should not be in started state
# setup
ok 369 should be in started state
# should not be started after stop is called
ok 370 should not be started
ok 371 should not be listening
ok 372 should not target listening
ok 373 should not be advertising
ok 374 should not target advertising
# teardown
ok 375 should not be in started state
# setup
ok 376 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
ok 377 specific error should be received
# teardown
ok 378 should not be in started state
# setup
ok 379 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
ok 380 specific error expected
# teardown
ok 381 should not be in started state
# setup
ok 382 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
ok 383 server should respond with code 200
# teardown
ok 384 should not be in started state
# setup
ok 385 should be in started state
# #stop can be called multiple times in a row
ok 386 should be in stopped state
ok 387 should still be in stopped state
# teardown
ok 388 should not be in started state
# setup
ok 389 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 390 should be in listening state
ok 391 should still be in listening state
# teardown
ok 392 should not be in started state
# setup
ok 393 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 394 should not be in listening state
ok 395 should still not be in listening state
# teardown
ok 396 should not be in started state
# setup
ok 397 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 398 should not be in advertising state
ok 399 should still not be in advertising state
# teardown
ok 400 should not be in started state
# setup
ok 401 should be in started state
# functions are run from a queue in the right order
ok 402 call order must match
# teardown
ok 403 should not be in started state
# setup
ok 404 should be in started state
# network changes are ignored while stopping
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 405 should not be called
# teardown
ok 406 should not be in started state
# setup
ok 407 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 408 wifi should be off
ok 409 specific error expected
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 410 discoveryActive should be true
# teardown
ok 411 should not be in started state
# setup
ok 412 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 413 wifi should be off
ok 414 specific error expected
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 415 advertisingActive should be true
# teardown
ok 416 should not be in started state
# setup
ok 417 should be in started state
# when wifi is enabled discovery is activated and peers become available
INFO thaliMobileNativeWrapper networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}
ok 418 wifi should be off
Uncaught Exception: Error: addMembership ENOMEM
Error: addMembership ENOMEM
    at new errnoException (dgram.js:387:11)
    at Socket.addMembership (dgram.js:339:11)
    at addMembership (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/node-ssdp/lib/index.js:190:19)
    at Socket.onSocketListening (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/node-ssdp/lib/index.js:186:5)
    at Socket.emit (events.js:98:20)
    at startListening (dgram.js:109:10)
    at dgram.js:181:7
    at dns.js:49:18
    at process._tickCallback (node.js:917:13)
****TEST TOOK:  ms ****
****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm http GET https://registry.npmjs.org/cordova
npm http 200 https://registry.npmjs.org/cordova
npm http GET https://registry.npmjs.org/cordova/-/cordova-6.0.0.tgz
npm http 200 https://registry.npmjs.org/cordova/-/cordova-6.0.0.tgz
npm http GET https://registry.npmjs.org/ansi
npm http GET https://registry.npmjs.org/update-notifier
npm http GET https://registry.npmjs.org/cordova-lib
npm http GET https://registry.npmjs.org/q
npm http GET https://registry.npmjs.org/nopt
npm http GET https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/ansi
npm http 200 https://registry.npmjs.org/nopt
npm http GET https://registry.npmjs.org/nopt/-/nopt-3.0.1.tgz
npm http GET https://registry.npmjs.org/ansi/-/ansi-0.3.1.tgz
npm http 200 https://registry.npmjs.org/cordova-lib
npm http GET https://registry.npmjs.org/cordova-lib/-/cordova-lib-6.0.0.tgz
npm http 200 https://registry.npmjs.org/underscore
npm http GET https://registry.npmjs.org/underscore/-/underscore-1.7.0.tgz
npm http 200 https://registry.npmjs.org/q
npm http GET https://registry.npmjs.org/q/-/q-1.0.1.tgz
npm http 200 https://registry.npmjs.org/nopt/-/nopt-3.0.1.tgz
npm http 200 https://registry.npmjs.org/cordova-lib/-/cordova-lib-6.0.0.tgz
npm http 200 https://registry.npmjs.org/ansi/-/ansi-0.3.1.tgz
npm http 200 https://registry.npmjs.org/underscore/-/underscore-1.7.0.tgz
npm http 200 https://registry.npmjs.org/q/-/q-1.0.1.tgz
npm http 200 https://registry.npmjs.org/update-notifier
npm http GET https://registry.npmjs.org/update-notifier/-/update-notifier-0.5.0.tgz
npm http 200 https://registry.npmjs.org/update-notifier/-/update-notifier-0.5.0.tgz
npm http GET https://registry.npmjs.org/is-npm
npm http GET https://registry.npmjs.org/latest-version
npm http GET https://registry.npmjs.org/repeating
npm http GET https://registry.npmjs.org/semver-diff
npm http GET https://registry.npmjs.org/string-length
npm http GET https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/configstore
npm http GET https://registry.npmjs.org/abbrev
npm http 200 https://registry.npmjs.org/is-npm
npm http 200 https://registry.npmjs.org/semver-diff
npm http 200 https://registry.npmjs.org/string-length
npm http 200 https://registry.npmjs.org/repeating
npm http GET https://registry.npmjs.org/is-npm/-/is-npm-1.0.0.tgz
npm http GET https://registry.npmjs.org/semver-diff/-/semver-diff-2.1.0.tgz
npm http GET https://registry.npmjs.org/string-length/-/string-length-1.0.1.tgz
npm http GET https://registry.npmjs.org/repeating/-/repeating-1.1.3.tgz
npm http 200 https://registry.npmjs.org/abbrev
npm http 200 https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/chalk/-/chalk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/semver-diff/-/semver-diff-2.1.0.tgz
npm http 200 https://registry.npmjs.org/is-npm/-/is-npm-1.0.0.tgz
npm http 200 https://registry.npmjs.org/string-length/-/string-length-1.0.1.tgz
npm http 200 https://registry.npmjs.org/configstore
npm http 200 https://registry.npmjs.org/repeating/-/repeating-1.1.3.tgz
npm http GET https://registry.npmjs.org/configstore/-/configstore-1.4.0.tgz
npm http 200 https://registry.npmjs.org/latest-version
npm http GET https://registry.npmjs.org/latest-version/-/latest-version-1.0.1.tgz
npm http 200 https://registry.npmjs.org/chalk/-/chalk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/configstore/-/configstore-1.4.0.tgz
npm http 200 https://registry.npmjs.org/latest-version/-/latest-version-1.0.1.tgz
npm http GET https://registry.npmjs.org/object-assign
npm http GET https://registry.npmjs.org/os-tmpdir
npm http GET https://registry.npmjs.org/uuid
npm http GET https://registry.npmjs.org/write-file-atomic
npm http GET https://registry.npmjs.org/xdg-basedir
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/osenv
npm http GET https://registry.npmjs.org/mkdirp
npm http GET https://registry.npmjs.org/graceful-fs
npm http GET https://registry.npmjs.org/semver
npm http GET https://registry.npmjs.org/package-json
npm http GET https://registry.npmjs.org/is-finite
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/write-file-atomic
npm http 200 https://registry.npmjs.org/xdg-basedir
npm http 200 https://registry.npmjs.org/os-tmpdir
npm http GET https://registry.npmjs.org/xdg-basedir/-/xdg-basedir-2.0.0.tgz
npm http GET https://registry.npmjs.org/os-tmpdir/-/os-tmpdir-1.0.1.tgz
npm http GET https://registry.npmjs.org/write-file-atomic/-/write-file-atomic-1.1.4.tgz
npm http GET https://registry.npmjs.org/cordova-app-hello-world
npm http GET https://registry.npmjs.org/aliasify
npm http GET https://registry.npmjs.org/cordova-js
npm http GET https://registry.npmjs.org/cordova-serve
npm http GET https://registry.npmjs.org/dep-graph
npm http GET https://registry.npmjs.org/opener
npm http GET https://registry.npmjs.org/init-package-json
npm http GET https://registry.npmjs.org/npmconf
npm http GET https://registry.npmjs.org/semver
npm http GET https://registry.npmjs.org/properties-parser
npm http GET https://registry.npmjs.org/request
npm http GET https://registry.npmjs.org/tar
npm http GET https://registry.npmjs.org/shelljs
npm http GET https://registry.npmjs.org/valid-identifier
npm http GET https://registry.npmjs.org/npm
npm http GET https://registry.npmjs.org/xcode
npm http 200 https://registry.npmjs.org/object-assign
npm http 200 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/osenv
npm http GET https://registry.npmjs.org/nopt/-/nopt-3.0.6.tgz
npm http GET https://registry.npmjs.org/osenv/-/osenv-0.1.3.tgz
npm http GET https://registry.npmjs.org/strip-ansi/-/strip-ansi-3.0.1.tgz
npm http GET https://registry.npmjs.org/object-assign/-/object-assign-4.0.1.tgz
npm http 200 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/uuid
npm http GET https://registry.npmjs.org/uuid/-/uuid-2.0.1.tgz
npm http 200 https://registry.npmjs.org/is-finite
npm http GET https://registry.npmjs.org/is-finite/-/is-finite-1.0.1.tgz
npm http 200 https://registry.npmjs.org/package-json
npm http 200 https://registry.npmjs.org/graceful-fs
npm http GET https://registry.npmjs.org/package-json/-/package-json-1.2.0.tgz
npm http GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.3.tgz
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/write-file-atomic/-/write-file-atomic-1.1.4.tgz
npm http GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.0.tgz
npm http 200 https://registry.npmjs.org/os-tmpdir/-/os-tmpdir-1.0.1.tgz
npm http 200 https://registry.npmjs.org/semver
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/osenv/-/osenv-0.1.3.tgz
npm http 200 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/strip-ansi/-/strip-ansi-3.0.1.tgz
npm http 200 https://registry.npmjs.org/object-assign/-/object-assign-4.0.1.tgz
npm http GET https://registry.npmjs.org/semver/-/semver-5.1.0.tgz
npm http GET https://registry.npmjs.org/has-ansi/-/has-ansi-2.0.0.tgz
npm http GET https://registry.npmjs.org/supports-color/-/supports-color-2.0.0.tgz
npm http 200 https://registry.npmjs.org/cordova-app-hello-world
npm http GET https://registry.npmjs.org/cordova-app-hello-world/-/cordova-app-hello-world-3.10.0.tgz
npm http GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/package-json/-/package-json-1.2.0.tgz
npm http 200 https://registry.npmjs.org/uuid/-/uuid-2.0.1.tgz
npm http 200 https://registry.npmjs.org/is-finite/-/is-finite-1.0.1.tgz
npm http 200 https://registry.npmjs.org/cordova-serve
npm http GET https://registry.npmjs.org/cordova-serve/-/cordova-serve-1.0.0.tgz
npm http 304 https://registry.npmjs.org/dep-graph
npm http GET https://registry.npmjs.org/got
npm http GET https://registry.npmjs.org/registry-url
npm http GET https://registry.npmjs.org/number-is-nan
npm http 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.0.tgz
npm http 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.3.tgz
npm http 200 https://registry.npmjs.org/aliasify
npm http 200 https://registry.npmjs.org/opener
npm http GET https://registry.npmjs.org/opener/-/opener-1.4.1.tgz
npm http GET https://registry.npmjs.org/aliasify/-/aliasify-1.9.0.tgz
npm http 200 https://registry.npmjs.org/semver/-/semver-5.1.0.tgz
npm http 200 https://registry.npmjs.org/supports-color/-/supports-color-2.0.0.tgz
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.5.tgz
npm http 200 https://registry.npmjs.org/cordova-js
npm http 200 https://registry.npmjs.org/cordova-app-hello-world/-/cordova-app-hello-world-3.10.0.tgz
npm http GET https://registry.npmjs.org/cordova-js/-/cordova-js-4.1.3.tgz
npm http 200 https://registry.npmjs.org/xdg-basedir/-/xdg-basedir-2.0.0.tgz
npm http 200 https://registry.npmjs.org/has-ansi/-/has-ansi-2.0.0.tgz
npm http 200 https://registry.npmjs.org/semver
npm http GET https://registry.npmjs.org/os-homedir
npm http GET https://registry.npmjs.org/imurmurhash
npm http GET https://registry.npmjs.org/slide
npm http GET https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/opener/-/opener-1.4.1.tgz
npm http 200 https://registry.npmjs.org/cordova-serve/-/cordova-serve-1.0.0.tgz
npm http 200 https://registry.npmjs.org/aliasify/-/aliasify-1.9.0.tgz
npm http 200 https://registry.npmjs.org/init-package-json
npm http GET https://registry.npmjs.org/init-package-json/-/init-package-json-1.9.3.tgz
npm http 200 https://registry.npmjs.org/cordova-js/-/cordova-js-4.1.3.tgz
npm http 200 https://registry.npmjs.org/properties-parser
npm http GET https://registry.npmjs.org/properties-parser/-/properties-parser-0.2.3.tgz
npm http 200 https://registry.npmjs.org/nopt/-/nopt-3.0.6.tgz
npm http 200 https://registry.npmjs.org/npmconf
npm http 304 https://registry.npmjs.org/valid-identifier
npm http 200 https://registry.npmjs.org/properties-parser/-/properties-parser-0.2.3.tgz
npm WARN deprecated npmconf@2.1.2: this package has been reintegrated into npm and is now out of date with respect to npm
npm http 200 https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.5.tgz
npm http GET https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/tar
npm http GET https://registry.npmjs.org/tar/-/tar-1.0.2.tgz
npm http 200 https://registry.npmjs.org/init-package-json/-/init-package-json-1.9.3.tgz
npm http 200 https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/ansi-regex/-/ansi-regex-2.0.0.tgz
npm http 200 https://registry.npmjs.org/xcode
npm http GET https://registry.npmjs.org/xcode/-/xcode-0.8.0.tgz
npm http 200 https://registry.npmjs.org/registry-url
npm http GET https://registry.npmjs.org/registry-url/-/registry-url-3.0.3.tgz
npm http 200 https://registry.npmjs.org/number-is-nan
npm http 200 https://registry.npmjs.org/shelljs
npm http GET https://registry.npmjs.org/number-is-nan/-/number-is-nan-1.0.0.tgz
npm http GET https://registry.npmjs.org/shelljs/-/shelljs-0.3.0.tgz
npm http 200 https://registry.npmjs.org/os-homedir
npm http GET https://registry.npmjs.org/os-homedir/-/os-homedir-1.0.1.tgz
npm http 200 https://registry.npmjs.org/slide
npm http GET https://registry.npmjs.org/slide/-/slide-1.1.6.tgz
npm http 200 https://registry.npmjs.org/got
npm http GET https://registry.npmjs.org/got/-/got-3.3.1.tgz
npm http 200 https://registry.npmjs.org/request
npm http GET https://registry.npmjs.org/request/-/request-2.47.0.tgz
npm http 200 https://registry.npmjs.org/minimist
npm http GET https://registry.npmjs.org/minimist/-/minimist-0.0.8.tgz
npm http 200 https://registry.npmjs.org/color-convert
npm http GET https://registry.npmjs.org/color-convert/-/color-convert-1.0.0.tgz
npm http 200 https://registry.npmjs.org/imurmurhash
npm http GET https://registry.npmjs.org/imurmurhash/-/imurmurhash-0.1.4.tgz
npm http 200 https://registry.npmjs.org/registry-url/-/registry-url-3.0.3.tgz
npm http 200 https://registry.npmjs.org/ansi-regex/-/ansi-regex-2.0.0.tgz
npm http 200 https://registry.npmjs.org/tar/-/tar-1.0.2.tgz
npm http 200 https://registry.npmjs.org/number-is-nan/-/number-is-nan-1.0.0.tgz
npm http 200 https://registry.npmjs.org/xcode/-/xcode-0.8.0.tgz
npm http 200 https://registry.npmjs.org/os-homedir/-/os-homedir-1.0.1.tgz
npm http 200 https://registry.npmjs.org/shelljs/-/shelljs-0.3.0.tgz
npm http 200 https://registry.npmjs.org/slide/-/slide-1.1.6.tgz
npm http 200 https://registry.npmjs.org/got/-/got-3.3.1.tgz
npm http 200 https://registry.npmjs.org/request/-/request-2.47.0.tgz
npm http GET https://registry.npmjs.org/rc
npm http GET https://registry.npmjs.org/is-redirect
npm http GET https://registry.npmjs.org/is-stream
npm http GET https://registry.npmjs.org/lowercase-keys
npm http GET https://registry.npmjs.org/nested-error-stacks
npm http GET https://registry.npmjs.org/prepend-http
npm http GET https://registry.npmjs.org/read-all-stream
npm http GET https://registry.npmjs.org/timed-out
npm http GET https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/infinity-agent
npm http GET https://registry.npmjs.org/object-assign/-/object-assign-3.0.0.tgz
npm http 200 https://registry.npmjs.org/color-convert/-/color-convert-1.0.0.tgz
npm http 200 https://registry.npmjs.org/minimist/-/minimist-0.0.8.tgz
npm http 200 https://registry.npmjs.org/imurmurhash/-/imurmurhash-0.1.4.tgz
npm http 200 https://registry.npmjs.org/object-assign/-/object-assign-3.0.0.tgz
npm http 200 https://registry.npmjs.org/is-stream
npm http 200 https://registry.npmjs.org/is-redirect
npm http GET https://registry.npmjs.org/is-redirect/-/is-redirect-1.0.0.tgz
npm http GET https://registry.npmjs.org/is-stream/-/is-stream-1.0.1.tgz
npm http 200 https://registry.npmjs.org/lowercase-keys
npm http GET https://registry.npmjs.org/lowercase-keys/-/lowercase-keys-1.0.0.tgz
npm http 200 https://registry.npmjs.org/prepend-http
npm http 200 https://registry.npmjs.org/nested-error-stacks
npm http GET https://registry.npmjs.org/prepend-http/-/prepend-http-1.0.3.tgz
npm http GET https://registry.npmjs.org/nested-error-stacks/-/nested-error-stacks-1.0.2.tgz
npm http 200 https://registry.npmjs.org/timed-out
npm http GET https://registry.npmjs.org/timed-out/-/timed-out-2.0.0.tgz
npm http 200 https://registry.npmjs.org/read-all-stream
npm http 200 https://registry.npmjs.org/infinity-agent
npm http GET https://registry.npmjs.org/read-all-stream/-/read-all-stream-3.1.0.tgz
npm http GET https://registry.npmjs.org/infinity-agent/-/infinity-agent-2.0.3.tgz
npm http 200 https://registry.npmjs.org/rc
npm http 200 https://registry.npmjs.org/is-stream/-/is-stream-1.0.1.tgz
npm http GET https://registry.npmjs.org/rc/-/rc-1.1.6.tgz
npm http 200 https://registry.npmjs.org/prepend-http/-/prepend-http-1.0.3.tgz
npm http 200 https://registry.npmjs.org/nested-error-stacks/-/nested-error-stacks-1.0.2.tgz
npm http 200 https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/duplexify/-/duplexify-3.4.3.tgz
npm http 200 https://registry.npmjs.org/timed-out/-/timed-out-2.0.0.tgz
npm http 200 https://registry.npmjs.org/read-all-stream/-/read-all-stream-3.1.0.tgz
npm http 200 https://registry.npmjs.org/infinity-agent/-/infinity-agent-2.0.3.tgz
npm http 200 https://registry.npmjs.org/rc/-/rc-1.1.6.tgz
npm http GET https://registry.npmjs.org/ini
npm http GET https://registry.npmjs.org/strip-json-comments
npm http GET https://registry.npmjs.org/deep-extend
npm http GET https://registry.npmjs.org/minimist/-/minimist-1.2.0.tgz
npm http 200 https://registry.npmjs.org/duplexify/-/duplexify-3.4.3.tgz
npm http 200 https://registry.npmjs.org/lowercase-keys/-/lowercase-keys-1.0.0.tgz
npm http 200 https://registry.npmjs.org/minimist/-/minimist-1.2.0.tgz
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 200 https://registry.npmjs.org/ini
npm http GET https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-1.0.4.tgz
npm http 200 https://registry.npmjs.org/is-redirect/-/is-redirect-1.0.0.tgz
npm http 200 https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-1.0.4.tgz
npm http GET https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/end-of-stream
npm http GET https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/deep-extend
npm http GET https://registry.npmjs.org/deep-extend/-/deep-extend-0.4.1.tgz
npm http 200 https://registry.npmjs.org/end-of-stream
npm http GET https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.0.0.tgz
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.0.tgz
npm http 200 https://registry.npmjs.org/deep-extend/-/deep-extend-0.4.1.tgz
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"v0.10.40","npm":"1.4.14"})
npm http 200 https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/readable-stream/-/readable-stream-2.0.5.tgz
npm http 200 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.0.0.tgz
npm http 200 https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.0.tgz
npm http 200 https://registry.npmjs.org/readable-stream/-/readable-stream-2.0.5.tgz
npm http GET https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/once/-/once-1.3.3.tgz
npm http 200 https://registry.npmjs.org/pinkie
npm http 200 https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/isarray/-/isarray-0.0.1.tgz
npm http GET https://registry.npmjs.org/pinkie/-/pinkie-2.0.4.tgz
npm http GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.6.tgz
npm http 200 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz
npm http GET https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz
npm http 200 https://registry.npmjs.org/once/-/once-1.3.3.tgz
npm http GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz
npm http 200 https://registry.npmjs.org/isarray/-/isarray-0.0.1.tgz
npm http 200 https://registry.npmjs.org/pinkie/-/pinkie-2.0.4.tgz
npm http 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.6.tgz
npm http 200 https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz
npm http 200 https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/npm
npm http GET https://registry.npmjs.org/npm/-/npm-2.14.21.tgz
npm http 200 https://registry.npmjs.org/npm/-/npm-2.14.21.tgz
npm WARN engine cordova-serve@1.0.0: wanted: {"node":">= 0.12.0","npm":">= 2.5.1"} (current: {"node":"v0.10.40","npm":"1.4.14"})
npm http GET https://registry.npmjs.org/browserify-transform-tools
npm http GET https://registry.npmjs.org/compression
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/q
npm http GET https://registry.npmjs.org/underscore
npm http GET https://registry.npmjs.org/abbrev
npm http GET https://registry.npmjs.org/promzard
npm http GET https://registry.npmjs.org/read
npm http GET https://registry.npmjs.org/read-package-json
npm http GET https://registry.npmjs.org/validate-npm-package-license
npm http GET https://registry.npmjs.org/validate-npm-package-name
npm http GET https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/npm-package-arg
npm http GET https://registry.npmjs.org/pegjs
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/ini
npm http GET https://registry.npmjs.org/mkdirp
npm http GET https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/osenv
npm http GET https://registry.npmjs.org/uid-number
npm http GET https://registry.npmjs.org/config-chain
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/block-stream
npm http GET https://registry.npmjs.org/fstream
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/underscore
npm http 304 https://registry.npmjs.org/abbrev
npm http 200 https://registry.npmjs.org/promzard
npm http 200 https://registry.npmjs.org/browserify-transform-tools
npm http 200 https://registry.npmjs.org/read
npm http GET https://registry.npmjs.org/browserify-transform-tools/-/browserify-transform-tools-1.5.3.tgz
npm http GET https://registry.npmjs.org/read/-/read-1.0.7.tgz
npm http 200 https://registry.npmjs.org/compression
npm http 304 https://registry.npmjs.org/validate-npm-package-name
npm http 200 https://registry.npmjs.org/validate-npm-package-license
npm http GET https://registry.npmjs.org/browserify
npm http GET https://registry.npmjs.org/compression/-/compression-1.6.1.tgz
npm http GET https://registry.npmjs.org/validate-npm-package-license/-/validate-npm-package-license-3.0.1.tgz
npm http 200 https://registry.npmjs.org/read-package-json
npm http GET https://registry.npmjs.org/read-package-json/-/read-package-json-2.0.3.tgz
npm http 200 https://registry.npmjs.org/pegjs
npm http GET https://registry.npmjs.org/pegjs/-/pegjs-0.6.2.tgz
npm http 304 https://registry.npmjs.org/ini
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/compression/-/compression-1.6.1.tgz
npm http 200 https://registry.npmjs.org/validate-npm-package-license/-/validate-npm-package-license-3.0.1.tgz
npm http 200 https://registry.npmjs.org/read/-/read-1.0.7.tgz
npm http GET https://registry.npmjs.org/node-uuid/-/node-uuid-1.3.3.tgz
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/browserify-transform-tools/-/browserify-transform-tools-1.5.3.tgz
npm http 200 https://registry.npmjs.org/npm-package-arg
npm http 200 https://registry.npmjs.org/pegjs/-/pegjs-0.6.2.tgz
npm http 304 https://registry.npmjs.org/osenv
npm http 304 https://registry.npmjs.org/uid-number
npm http 200 https://registry.npmjs.org/read-package-json/-/read-package-json-2.0.3.tgz
npm http GET https://registry.npmjs.org/npm-package-arg/-/npm-package-arg-4.1.0.tgz
npm http 304 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/glob/-/glob-6.0.4.tgz
npm http 200 https://registry.npmjs.org/node-uuid/-/node-uuid-1.3.3.tgz
npm http 200 https://registry.npmjs.org/config-chain
npm http GET https://registry.npmjs.org/config-chain/-/config-chain-1.1.10.tgz
npm http 200 https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/forever-agent
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/bl/-/bl-0.9.5.tgz
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/glob/-/glob-6.0.4.tgz
npm http GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.2.tgz
npm http 200 https://registry.npmjs.org/npm-package-arg/-/npm-package-arg-4.1.0.tgz
npm http 200 https://registry.npmjs.org/config-chain/-/config-chain-1.1.10.tgz
npm http 200 https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.7.tgz
npm http 200 https://registry.npmjs.org/bl/-/bl-0.9.5.tgz
npm http 200 https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/mute-stream
npm http GET https://registry.npmjs.org/spdx-expression-parse
npm http GET https://registry.npmjs.org/spdx-correct
npm http 200 https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/builtins
npm http GET https://registry.npmjs.org/os-homedir
npm http GET https://registry.npmjs.org/os-tmpdir
npm http GET https://registry.npmjs.org/hosted-git-info
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/proto-list
npm http 200 https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/minimist
npm http GET https://registry.npmjs.org/json-parse-helpfulerror
npm http GET https://registry.npmjs.org/normalize-package-data
npm http GET https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/aws-sign2
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.2.1.tgz
npm http 200 https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.7.tgz
npm http 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.2.tgz
npm http 200 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/block-stream
npm http GET https://registry.npmjs.org/stringstream/-/stringstream-0.0.5.tgz
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/fstream
npm http GET https://registry.npmjs.org/fstream/-/fstream-1.0.8.tgz
npm http 200 https://registry.npmjs.org/stringstream/-/stringstream-0.0.5.tgz
npm http 200 https://registry.npmjs.org/falafel
npm http 200 https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.2.1.tgz
npm http GET https://registry.npmjs.org/falafel/-/falafel-1.2.0.tgz
npm http 200 https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/hawk/-/hawk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/mute-stream
npm http GET https://registry.npmjs.org/mute-stream/-/mute-stream-0.0.6.tgz
npm http 200 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/spdx-correct
npm http 200 https://registry.npmjs.org/spdx-expression-parse
npm http GET https://registry.npmjs.org/spdx-correct/-/spdx-correct-1.0.2.tgz
npm http GET https://registry.npmjs.org/spdx-expression-parse/-/spdx-expression-parse-1.0.2.tgz
npm http 200 https://registry.npmjs.org/fstream/-/fstream-1.0.8.tgz
npm http 200 https://registry.npmjs.org/falafel/-/falafel-1.2.0.tgz
npm http 200 https://registry.npmjs.org/builtins
npm http 304 https://registry.npmjs.org/os-homedir
npm http GET https://registry.npmjs.org/builtins/-/builtins-0.0.7.tgz
npm http 200 https://registry.npmjs.org/spdx-correct/-/spdx-correct-1.0.2.tgz
npm http 304 https://registry.npmjs.org/hosted-git-info
npm http 304 https://registry.npmjs.org/os-tmpdir
npm http 200 https://registry.npmjs.org/spdx-expression-parse/-/spdx-expression-parse-1.0.2.tgz
npm http 200 https://registry.npmjs.org/inflight
npm http 200 https://registry.npmjs.org/hawk/-/hawk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/mute-stream/-/mute-stream-0.0.6.tgz
npm http 200 https://registry.npmjs.org/builtins/-/builtins-0.0.7.tgz
npm http 304 https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/spdx-license-ids
npm http 304 https://registry.npmjs.org/proto-list
npm http GET https://registry.npmjs.org/spdx-exceptions
npm http GET https://registry.npmjs.org/spdx-license-ids
npm http 304 https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/json-parse-helpfulerror
npm http 200 https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/minimatch/-/minimatch-3.0.0.tgz
npm http GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/foreach/-/foreach-2.0.5.tgz
npm http 304 https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/minimatch/-/minimatch-3.0.0.tgz
npm http 200 https://registry.npmjs.org/normalize-package-data
npm http 200 https://registry.npmjs.org/foreach/-/foreach-2.0.5.tgz
npm http GET https://registry.npmjs.org/normalize-package-data/-/normalize-package-data-2.3.5.tgz
npm http 200 https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/ctype
npm http GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.9.tgz
npm http 200 https://registry.npmjs.org/spdx-license-ids
npm http 200 https://registry.npmjs.org/spdx-exceptions
npm http GET https://registry.npmjs.org/spdx-license-ids/-/spdx-license-ids-1.2.0.tgz
npm http GET https://registry.npmjs.org/spdx-exceptions/-/spdx-exceptions-1.0.4.tgz
npm http GET https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 200 https://registry.npmjs.org/spdx-license-ids
npm http GET https://registry.npmjs.org/sntp
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/spdx-license-ids/-/spdx-license-ids-1.2.0.tgz
npm http 200 https://registry.npmjs.org/spdx-exceptions/-/spdx-exceptions-1.0.4.tgz
npm http 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.9.tgz
npm http 200 https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/express/-/express-4.13.4.tgz
npm http 304 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/normalize-package-data/-/normalize-package-data-2.3.5.tgz
npm http 200 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/rimraf/-/rimraf-2.5.2.tgz
npm http GET https://registry.npmjs.org/asn1/-/asn1-0.1.11.tgz
npm http GET https://registry.npmjs.org/jju
npm http 200 https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.3.tgz
npm http GET https://registry.npmjs.org/is-builtin-module
npm http 200 https://registry.npmjs.org/ctype
npm http GET https://registry.npmjs.org/ctype/-/ctype-0.5.3.tgz
npm http 200 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/rimraf/-/rimraf-2.5.2.tgz
npm http 200 https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/glob/-/glob-7.0.0.tgz
npm http 200 https://registry.npmjs.org/express/-/express-4.13.4.tgz
npm http 200 https://registry.npmjs.org/asn1/-/asn1-0.1.11.tgz
npm http 200 https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.3.tgz
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/compressible
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/on-headers
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/concat-map
npm http GET https://registry.npmjs.org/balanced-match
npm http 200 https://registry.npmjs.org/ctype/-/ctype-0.5.3.tgz
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/jju
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/qs/-/qs-4.0.0.tgz
npm http GET https://registry.npmjs.org/jju/-/jju-1.3.0.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/is-builtin-module
npm http 304 https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/is-builtin-module/-/is-builtin-module-1.0.0.tgz
npm http 200 https://registry.npmjs.org/glob/-/glob-7.0.0.tgz
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/is-builtin-module/-/is-builtin-module-1.0.0.tgz
npm http 200 https://registry.npmjs.org/jju/-/jju-1.3.0.tgz
npm http GET https://registry.npmjs.org/builtin-modules
npm http 200 https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/accepts/-/accepts-1.3.1.tgz
npm http 200 https://registry.npmjs.org/bytes
npm http 200 https://registry.npmjs.org/qs/-/qs-4.0.0.tgz
npm http GET https://registry.npmjs.org/bytes/-/bytes-2.2.0.tgz
npm http 200 https://registry.npmjs.org/on-headers
npm http 200 https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/on-headers/-/on-headers-1.0.1.tgz
npm http GET https://registry.npmjs.org/vary/-/vary-1.1.0.tgz
npm http 200 https://registry.npmjs.org/concat-map
npm http GET https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz
npm http 200 https://registry.npmjs.org/compressible
npm http 200 https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/compressible/-/compressible-2.0.7.tgz
npm http GET https://registry.npmjs.org/debug/-/debug-2.2.0.tgz
npm http 200 https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.3.0.tgz
npm http 200 https://registry.npmjs.org/accepts/-/accepts-1.3.1.tgz
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/array-flatten/-/array-flatten-1.1.1.tgz
npm http GET https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.1.tgz
npm http 200 https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/content-type/-/content-type-1.0.1.tgz
npm http 200 https://registry.npmjs.org/compressible/-/compressible-2.0.7.tgz
npm http 200 https://registry.npmjs.org/vary/-/vary-1.1.0.tgz
npm http 200 https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.0.6.tgz
npm http 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.3.0.tgz
npm http 200 https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz
npm http 200 https://registry.npmjs.org/debug/-/debug-2.2.0.tgz
npm http 200 https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/accepts/-/accepts-1.2.13.tgz
npm http 200 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/array-flatten/-/array-flatten-1.1.1.tgz
npm http 200 https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.1.tgz
npm http GET https://registry.npmjs.org/cookie/-/cookie-0.1.5.tgz
npm http 200 https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.0.6.tgz
npm http 200 https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/etag/-/etag-1.7.0.tgz
npm http 200 https://registry.npmjs.org/fresh
npm http 200 https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz
npm http 200 https://registry.npmjs.org/content-type/-/content-type-1.0.1.tgz
npm http GET https://registry.npmjs.org/fresh/-/fresh-0.3.0.tgz
npm http GET https://registry.npmjs.org/depd/-/depd-1.1.0.tgz
npm http 200 https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.1.tgz
npm http 200 https://registry.npmjs.org/bytes/-/bytes-2.2.0.tgz
npm http 200 https://registry.npmjs.org/accepts/-/accepts-1.2.13.tgz
npm http 200 https://registry.npmjs.org/cookie/-/cookie-0.1.5.tgz
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.1.tgz
npm http 200 https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/methods/-/methods-1.1.2.tgz
npm http 200 https://registry.npmjs.org/fresh/-/fresh-0.3.0.tgz
npm http 200 https://registry.npmjs.org/depd/-/depd-1.1.0.tgz
npm http 200 https://registry.npmjs.org/etag/-/etag-1.7.0.tgz
npm http 200 https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/parseurl/-/parseurl-1.3.1.tgz
npm http 200 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.1.tgz
npm http 200 https://registry.npmjs.org/methods/-/methods-1.1.2.tgz
npm http 200 https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.1.tgz
npm http GET https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz
npm http 200 https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/range-parser/-/range-parser-1.0.3.tgz
npm http 200 https://registry.npmjs.org/parseurl/-/parseurl-1.3.1.tgz
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/on-headers/-/on-headers-1.0.1.tgz
npm http GET https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.0.10.tgz
npm http 200 https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz
npm http GET https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/mime-types/-/mime-types-2.1.10.tgz
npm http GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz
npm http GET https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-0.1.7.tgz
npm http 200 https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/utils-merge/-/utils-merge-1.0.0.tgz
npm http 200 https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.0.10.tgz
npm http 200 https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/type-is/-/type-is-1.6.12.tgz
npm http 200 https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/mime-types/-/mime-types-2.1.10.tgz
npm http GET https://registry.npmjs.org/vary/-/vary-1.0.1.tgz
npm http 304 https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/builtin-modules
npm http 200 https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/send/-/send-0.13.1.tgz
npm http GET https://registry.npmjs.org/serve-static/-/serve-static-1.10.2.tgz
npm http GET https://registry.npmjs.org/builtin-modules/-/builtin-modules-1.1.1.tgz
npm http 200 https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-0.1.7.tgz
npm http 200 https://registry.npmjs.org/utils-merge/-/utils-merge-1.0.0.tgz
npm http 200 https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/ms/-/ms-0.7.1.tgz
npm http 200 https://registry.npmjs.org/send/-/send-0.13.1.tgz
npm http 200 https://registry.npmjs.org/serve-static/-/serve-static-1.10.2.tgz
npm http 200 https://registry.npmjs.org/type-is/-/type-is-1.6.12.tgz
npm http 200 https://registry.npmjs.org/vary/-/vary-1.0.1.tgz
npm http 200 https://registry.npmjs.org/ms/-/ms-0.7.1.tgz
npm http 200 https://registry.npmjs.org/builtin-modules/-/builtin-modules-1.1.1.tgz
npm http 200 https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/negotiator/-/negotiator-0.6.0.tgz
npm http 200 https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/mime-db/-/mime-db-1.22.0.tgz
npm http 200 https://registry.npmjs.org/negotiator/-/negotiator-0.6.0.tgz
npm http 200 https://registry.npmjs.org/range-parser/-/range-parser-1.0.3.tgz
npm http 200 https://registry.npmjs.org/mime-db/-/mime-db-1.22.0.tgz
npm http 200 https://registry.npmjs.org/browserify
npm http GET https://registry.npmjs.org/browserify/-/browserify-10.1.3.tgz
npm http GET https://registry.npmjs.org/unpipe
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/negotiator/-/negotiator-0.5.3.tgz
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/browserify/-/browserify-10.1.3.tgz
npm http 200 https://registry.npmjs.org/media-typer
npm http 200 https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz
npm http GET https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz
npm http 200 https://registry.npmjs.org/negotiator/-/negotiator-0.5.3.tgz
npm http 200 https://registry.npmjs.org/unpipe
npm http GET https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz
npm http 200 https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/destroy/-/destroy-1.0.4.tgz
npm http 200 https://registry.npmjs.org/ipaddr.js
npm http 200 https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz
npm http GET https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.0.5.tgz
npm http 200 https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/forwarded/-/forwarded-0.1.0.tgz
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz
npm http GET https://registry.npmjs.org/statuses/-/statuses-1.2.1.tgz
npm http 200 https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/http-errors/-/http-errors-1.3.1.tgz
npm http 200 https://registry.npmjs.org/destroy/-/destroy-1.0.4.tgz
npm http 200 https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.0.5.tgz
npm http 200 https://registry.npmjs.org/forwarded/-/forwarded-0.1.0.tgz
npm http 200 https://registry.npmjs.org/http-errors/-/http-errors-1.3.1.tgz
npm http 200 https://registry.npmjs.org/statuses/-/statuses-1.2.1.tgz
npm http 200 https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/browser-pack
npm http GET https://registry.npmjs.org/browser-resolve
npm http GET https://registry.npmjs.org/browserify-zlib
npm http GET https://registry.npmjs.org/buffer
npm http GET https://registry.npmjs.org/builtins
npm http GET https://registry.npmjs.org/commondir
npm http GET https://registry.npmjs.org/concat-stream
npm http GET https://registry.npmjs.org/console-browserify
npm http GET https://registry.npmjs.org/constants-browserify
npm http GET https://registry.npmjs.org/crypto-browserify
npm http GET https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/defined
npm http GET https://registry.npmjs.org/deps-sort
npm http GET https://registry.npmjs.org/domain-browser
npm http GET https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/duplexer2
npm http GET https://registry.npmjs.org/events
npm http GET https://registry.npmjs.org/has
npm http GET https://registry.npmjs.org/htmlescape
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/http-browserify
npm http GET https://registry.npmjs.org/https-browserify
npm http GET https://registry.npmjs.org/insert-module-globals
npm http GET https://registry.npmjs.org/labeled-stream-splicer
npm http GET https://registry.npmjs.org/os-browserify
npm http GET https://registry.npmjs.org/module-deps
npm http GET https://registry.npmjs.org/path-browserify
npm http GET https://registry.npmjs.org/parents
npm http GET https://registry.npmjs.org/process
npm http GET https://registry.npmjs.org/punycode
npm http GET https://registry.npmjs.org/querystring-es3
npm http GET https://registry.npmjs.org/read-only-stream
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/shallow-copy
npm http GET https://registry.npmjs.org/shasum
npm http GET https://registry.npmjs.org/resolve
npm http GET https://registry.npmjs.org/shell-quote
npm http GET https://registry.npmjs.org/stream-browserify
npm http GET https://registry.npmjs.org/subarg
npm http GET https://registry.npmjs.org/syntax-error
npm http GET https://registry.npmjs.org/timers-browserify
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/tty-browserify
npm http GET https://registry.npmjs.org/url
npm http GET https://registry.npmjs.org/util
npm http GET https://registry.npmjs.org/vm-browserify
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/assert
npm http GET https://registry.npmjs.org/JSONStream
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/builtins
npm http 200 https://registry.npmjs.org/commondir
npm http GET https://registry.npmjs.org/commondir/-/commondir-0.0.1.tgz
npm http 304 https://registry.npmjs.org/browserify-zlib
npm http 304 https://registry.npmjs.org/console-browserify
npm http 200 https://registry.npmjs.org/browser-pack
npm http 304 https://registry.npmjs.org/constants-browserify
npm http 200 https://registry.npmjs.org/concat-stream
npm http 200 https://registry.npmjs.org/browser-resolve
npm http 200 https://registry.npmjs.org/buffer
npm http 304 https://registry.npmjs.org/defined
npm http GET https://registry.npmjs.org/browser-resolve/-/browser-resolve-1.11.1.tgz
npm http GET https://registry.npmjs.org/buffer/-/buffer-3.6.0.tgz
npm http 200 https://registry.npmjs.org/domain-browser
npm http 304 https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/deps-sort
npm http 200 https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/domain-browser/-/domain-browser-1.1.7.tgz
npm http GET https://registry.npmjs.org/glob/-/glob-4.5.3.tgz
npm http GET https://registry.npmjs.org/deep-equal/-/deep-equal-1.0.1.tgz
npm http 200 https://registry.npmjs.org/crypto-browserify
npm http GET https://registry.npmjs.org/crypto-browserify/-/crypto-browserify-3.11.0.tgz
npm http 200 https://registry.npmjs.org/duplexer2
npm http 200 https://registry.npmjs.org/events
npm http 200 https://registry.npmjs.org/has
npm http 200 https://registry.npmjs.org/htmlescape
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/http-browserify
npm http 200 https://registry.npmjs.org/labeled-stream-splicer
npm http 200 https://registry.npmjs.org/commondir/-/commondir-0.0.1.tgz
npm http 200 https://registry.npmjs.org/browser-resolve/-/browser-resolve-1.11.1.tgz
npm http 304 https://registry.npmjs.org/path-browserify
npm http 200 https://registry.npmjs.org/deep-equal/-/deep-equal-1.0.1.tgz
npm http 304 https://registry.npmjs.org/parents
npm http 200 https://registry.npmjs.org/os-browserify
npm http 200 https://registry.npmjs.org/glob/-/glob-4.5.3.tgz
npm http 200 https://registry.npmjs.org/crypto-browserify/-/crypto-browserify-3.11.0.tgz
npm http 200 https://registry.npmjs.org/buffer/-/buffer-3.6.0.tgz
npm http 200 https://registry.npmjs.org/process
npm http 200 https://registry.npmjs.org/punycode
npm http GET https://registry.npmjs.org/punycode/-/punycode-1.4.0.tgz
npm http GET https://registry.npmjs.org/process/-/process-0.11.2.tgz
npm http 200 https://registry.npmjs.org/insert-module-globals
npm http 200 https://registry.npmjs.org/read-only-stream
npm http GET https://registry.npmjs.org/insert-module-globals/-/insert-module-globals-6.6.3.tgz
npm http 304 https://registry.npmjs.org/querystring-es3
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/shallow-copy
npm http 200 https://registry.npmjs.org/shasum
npm http 200 https://registry.npmjs.org/domain-browser/-/domain-browser-1.1.7.tgz
npm http GET https://registry.npmjs.org/shasum/-/shasum-1.0.2.tgz
npm http 304 https://registry.npmjs.org/shell-quote
npm http 200 https://registry.npmjs.org/https-browserify
npm http GET https://registry.npmjs.org/https-browserify/-/https-browserify-0.0.1.tgz
npm http 200 https://registry.npmjs.org/process/-/process-0.11.2.tgz
npm http 200 https://registry.npmjs.org/module-deps
npm http 200 https://registry.npmjs.org/syntax-error
npm http 304 https://registry.npmjs.org/subarg
npm http GET https://registry.npmjs.org/module-deps/-/module-deps-3.9.1.tgz
npm http GET https://registry.npmjs.org/syntax-error/-/syntax-error-1.1.5.tgz
npm http 200 https://registry.npmjs.org/shasum/-/shasum-1.0.2.tgz
npm http 304 https://registry.npmjs.org/tty-browserify
npm http 200 https://registry.npmjs.org/insert-module-globals/-/insert-module-globals-6.6.3.tgz
npm http 200 https://registry.npmjs.org/url
npm http 200 https://registry.npmjs.org/timers-browserify
npm http 200 https://registry.npmjs.org/syntax-error/-/syntax-error-1.1.5.tgz
npm http GET https://registry.npmjs.org/timers-browserify/-/timers-browserify-1.4.2.tgz
npm http 200 https://registry.npmjs.org/punycode/-/punycode-1.4.0.tgz
npm http 304 https://registry.npmjs.org/vm-browserify
npm http 200 https://registry.npmjs.org/util
npm http 200 https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/assert
npm http 200 https://registry.npmjs.org/resolve
npm http 200 https://registry.npmjs.org/stream-browserify
npm http GET https://registry.npmjs.org/resolve/-/resolve-1.1.7.tgz
npm http 200 https://registry.npmjs.org/module-deps/-/module-deps-3.9.1.tgz
npm http 200 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/timers-browserify/-/timers-browserify-1.4.2.tgz
npm http 200 https://registry.npmjs.org/https-browserify/-/https-browserify-0.0.1.tgz
npm http 200 https://registry.npmjs.org/resolve/-/resolve-1.1.7.tgz
npm http 200 https://registry.npmjs.org/JSONStream
npm http GET https://registry.npmjs.org/JSONStream/-/JSONStream-1.0.7.tgz
npm http 200 https://registry.npmjs.org/JSONStream/-/JSONStream-1.0.7.tgz
npm http GET https://registry.npmjs.org/typedarray
npm http GET https://registry.npmjs.org/function-bind
npm http GET https://registry.npmjs.org/minimist
npm http GET https://registry.npmjs.org/json-stable-stringify
npm http GET https://registry.npmjs.org/sha.js
npm http GET https://registry.npmjs.org/path-platform
npm http GET https://registry.npmjs.org/readable-wrap
npm http GET https://registry.npmjs.org/date-now
npm http GET https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/typedarray
npm http GET https://registry.npmjs.org/stream-splicer
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/path-platform
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/Base64
npm http GET https://registry.npmjs.org/querystring
npm http 304 https://registry.npmjs.org/readable-wrap
npm http 200 https://registry.npmjs.org/function-bind
npm http GET https://registry.npmjs.org/umd
npm http GET https://registry.npmjs.org/combine-source-map
npm http 304 https://registry.npmjs.org/minimist
npm http GET https://registry.npmjs.org/function-bind/-/function-bind-1.1.0.tgz
npm http GET https://registry.npmjs.org/browserify-cipher
npm http GET https://registry.npmjs.org/browserify-sign
npm http GET https://registry.npmjs.org/create-ecdh
npm http GET https://registry.npmjs.org/create-hash
npm http GET https://registry.npmjs.org/create-hmac
npm http GET https://registry.npmjs.org/diffie-hellman
npm http GET https://registry.npmjs.org/pbkdf2
npm http GET https://registry.npmjs.org/public-encrypt
npm http GET https://registry.npmjs.org/randombytes
npm http GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/indexof
npm http GET https://registry.npmjs.org/is-buffer
npm http GET https://registry.npmjs.org/combine-source-map
npm http GET https://registry.npmjs.org/lexical-scope
npm http 200 https://registry.npmjs.org/json-stable-stringify
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/pako
npm http GET https://registry.npmjs.org/base64-js
npm http GET https://registry.npmjs.org/ieee754
npm http GET https://registry.npmjs.org/isarray/-/isarray-1.0.0.tgz
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/acorn
npm http 200 https://registry.npmjs.org/stream-splicer
npm http 304 https://registry.npmjs.org/Base64
npm http GET https://registry.npmjs.org/acorn/-/acorn-2.7.0.tgz
npm http 200 https://registry.npmjs.org/function-bind/-/function-bind-1.1.0.tgz
npm http GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/querystring
npm http 304 https://registry.npmjs.org/umd
npm http 304 https://registry.npmjs.org/combine-source-map
npm http GET https://registry.npmjs.org/querystring/-/querystring-0.2.0.tgz
npm http GET https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/inline-source-map
npm http GET https://registry.npmjs.org/convert-source-map
npm http GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/create-hash
npm http 200 https://registry.npmjs.org/create-ecdh
npm http 200 https://registry.npmjs.org/sha.js
npm http GET https://registry.npmjs.org/create-hash/-/create-hash-1.1.2.tgz
npm http GET https://registry.npmjs.org/create-ecdh/-/create-ecdh-4.0.0.tgz
npm http GET https://registry.npmjs.org/sha.js/-/sha.js-2.4.5.tgz
npm http 200 https://registry.npmjs.org/isarray/-/isarray-1.0.0.tgz
npm http 200 https://registry.npmjs.org/pbkdf2
npm http 200 https://registry.npmjs.org/create-hmac
npm http 200 https://registry.npmjs.org/browserify-sign
npm http GET https://registry.npmjs.org/create-hmac/-/create-hmac-1.1.4.tgz
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/jsonparse
npm http GET https://registry.npmjs.org/browserify-sign/-/browserify-sign-4.0.0.tgz
npm http GET https://registry.npmjs.org/stream-combiner2
npm http GET https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/diffie-hellman
npm http 200 https://registry.npmjs.org/sha.js/-/sha.js-2.4.5.tgz
npm http 200 https://registry.npmjs.org/public-encrypt
npm http GET https://registry.npmjs.org/diffie-hellman/-/diffie-hellman-5.0.2.tgz
npm http 200 https://registry.npmjs.org/acorn/-/acorn-2.7.0.tgz
npm http GET https://registry.npmjs.org/public-encrypt/-/public-encrypt-4.0.0.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/querystring/-/querystring-0.2.0.tgz
npm http 200 https://registry.npmjs.org/randombytes
npm http GET https://registry.npmjs.org/randombytes/-/randombytes-2.0.2.tgz
npm http 200 https://registry.npmjs.org/browserify-cipher
npm http GET https://registry.npmjs.org/browserify-cipher/-/browserify-cipher-1.0.0.tgz
npm http GET https://registry.npmjs.org/jsonify
npm http 304 https://registry.npmjs.org/combine-source-map
npm http 200 https://registry.npmjs.org/create-hmac/-/create-hmac-1.1.4.tgz
npm http 200 https://registry.npmjs.org/is-buffer
npm http GET https://registry.npmjs.org/is-buffer/-/is-buffer-1.1.2.tgz
npm http 200 https://registry.npmjs.org/browserify-sign/-/browserify-sign-4.0.0.tgz
npm http 304 https://registry.npmjs.org/ieee754
npm http 200 https://registry.npmjs.org/diffie-hellman/-/diffie-hellman-5.0.2.tgz
npm http 304 https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/create-hash/-/create-hash-1.1.2.tgz
npm http 200 https://registry.npmjs.org/base64-js
npm http 304 https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/pako
npm http GET https://registry.npmjs.org/base64-js/-/base64-js-0.0.8.tgz
npm http GET https://registry.npmjs.org/pako/-/pako-0.2.8.tgz
npm http 200 https://registry.npmjs.org/randombytes/-/randombytes-2.0.2.tgz
npm http GET https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/concat-map
npm http 200 https://registry.npmjs.org/is-buffer/-/is-buffer-1.1.2.tgz
npm http 304 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/public-encrypt/-/public-encrypt-4.0.0.tgz
npm http 200 https://registry.npmjs.org/browserify-cipher/-/browserify-cipher-1.0.0.tgz
npm http 200 https://registry.npmjs.org/base64-js/-/base64-js-0.0.8.tgz
npm http 200 https://registry.npmjs.org/lexical-scope
npm http GET https://registry.npmjs.org/lexical-scope/-/lexical-scope-1.2.0.tgz
npm http 200 https://registry.npmjs.org/jsonparse
npm http 200 https://registry.npmjs.org/pako/-/pako-0.2.8.tgz
npm http GET https://registry.npmjs.org/jsonparse/-/jsonparse-1.2.0.tgz
npm http 200 https://registry.npmjs.org/stream-combiner2
npm http 304 https://registry.npmjs.org/jsonify
npm http 200 https://registry.npmjs.org/detective
npm http GET https://registry.npmjs.org/detective/-/detective-4.3.1.tgz
npm http 200 https://registry.npmjs.org/create-ecdh/-/create-ecdh-4.0.0.tgz
npm http 304 https://registry.npmjs.org/balanced-match
npm http 200 https://registry.npmjs.org/inline-source-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 200 https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/evp_bytestokey
npm http GET https://registry.npmjs.org/browserify-des
npm http GET https://registry.npmjs.org/bn.js
npm http GET https://registry.npmjs.org/elliptic
npm http GET https://registry.npmjs.org/browserify-aes
npm http GET https://registry.npmjs.org/cipher-base
npm http GET https://registry.npmjs.org/ripemd160
npm http 200 https://registry.npmjs.org/convert-source-map
npm http GET https://registry.npmjs.org/miller-rabin
npm http GET https://registry.npmjs.org/bn.js
npm http GET https://registry.npmjs.org/browserify-rsa
npm http GET https://registry.npmjs.org/parse-asn1
npm http 200 https://registry.npmjs.org/jsonparse/-/jsonparse-1.2.0.tgz
npm http 200 https://registry.npmjs.org/detective/-/detective-4.3.1.tgz
npm http 200 https://registry.npmjs.org/evp_bytestokey
npm http 200 https://registry.npmjs.org/lexical-scope/-/lexical-scope-1.2.0.tgz
npm http 200 https://registry.npmjs.org/browserify-des
npm http GET https://registry.npmjs.org/browserify-des/-/browserify-des-1.0.0.tgz
npm http GET https://registry.npmjs.org/evp_bytestokey/-/evp_bytestokey-1.0.0.tgz
npm http 200 https://registry.npmjs.org/cipher-base
npm http 304 https://registry.npmjs.org/ripemd160
npm http GET https://registry.npmjs.org/cipher-base/-/cipher-base-1.0.2.tgz
npm http GET https://registry.npmjs.org/lodash.memoize
npm http 200 https://registry.npmjs.org/miller-rabin
npm http GET https://registry.npmjs.org/convert-source-map/-/convert-source-map-1.1.3.tgz
npm http GET https://registry.npmjs.org/miller-rabin/-/miller-rabin-4.0.0.tgz
npm http 200 https://registry.npmjs.org/browserify-aes
npm http GET https://registry.npmjs.org/browserify-aes/-/browserify-aes-1.0.6.tgz
npm http 200 https://registry.npmjs.org/bn.js
npm http 200 https://registry.npmjs.org/browserify-des/-/browserify-des-1.0.0.tgz
npm http 200 https://registry.npmjs.org/evp_bytestokey/-/evp_bytestokey-1.0.0.tgz
npm http 200 https://registry.npmjs.org/browserify-rsa
npm http GET https://registry.npmjs.org/bn.js/-/bn.js-4.10.5.tgz
npm http GET https://registry.npmjs.org/browserify-rsa/-/browserify-rsa-4.0.1.tgz
npm http 200 https://registry.npmjs.org/bn.js
npm http 200 https://registry.npmjs.org/elliptic
npm http 200 https://registry.npmjs.org/browserify-aes/-/browserify-aes-1.0.6.tgz
npm http GET https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/elliptic/-/elliptic-6.2.3.tgz
npm http 200 https://registry.npmjs.org/cipher-base/-/cipher-base-1.0.2.tgz
npm http GET https://registry.npmjs.org/des.js
npm http GET https://registry.npmjs.org/astw
npm http 200 https://registry.npmjs.org/parse-asn1
npm http 200 https://registry.npmjs.org/lodash.memoize
npm http 200 https://registry.npmjs.org/browserify-rsa/-/browserify-rsa-4.0.1.tgz
npm http GET https://registry.npmjs.org/parse-asn1/-/parse-asn1-5.0.0.tgz
npm http GET https://registry.npmjs.org/buffer-xor
npm http 200 https://registry.npmjs.org/miller-rabin/-/miller-rabin-4.0.0.tgz
npm http 200 https://registry.npmjs.org/convert-source-map/-/convert-source-map-1.1.3.tgz
npm http 200 https://registry.npmjs.org/bn.js/-/bn.js-4.10.5.tgz
npm http 200 https://registry.npmjs.org/elliptic/-/elliptic-6.2.3.tgz
npm http GET https://registry.npmjs.org/brorand
npm http 200 https://registry.npmjs.org/parse-asn1/-/parse-asn1-5.0.0.tgz
npm http 200 https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/hash.js
npm http GET https://registry.npmjs.org/asn1.js
npm http 200 https://registry.npmjs.org/des.js
npm http GET https://registry.npmjs.org/des.js/-/des.js-1.0.0.tgz
npm http 304 https://registry.npmjs.org/astw
npm http 304 https://registry.npmjs.org/brorand
npm http 200 https://registry.npmjs.org/buffer-xor
npm http GET https://registry.npmjs.org/buffer-xor/-/buffer-xor-1.0.3.tgz
npm http 200 https://registry.npmjs.org/asn1.js
npm http GET https://registry.npmjs.org/asn1.js/-/asn1.js-4.5.1.tgz
npm http 304 https://registry.npmjs.org/hash.js
npm http 200 https://registry.npmjs.org/des.js/-/des.js-1.0.0.tgz
npm http 200 https://registry.npmjs.org/buffer-xor/-/buffer-xor-1.0.3.tgz
npm http GET https://registry.npmjs.org/minimalistic-assert
npm http 200 https://registry.npmjs.org/asn1.js/-/asn1.js-4.5.1.tgz
npm http 304 https://registry.npmjs.org/minimalistic-assert
npm WARN package.json thali-test-server@0.0.1 No repository field.
npm http GET https://registry.npmjs.org/fs-extra-promise
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/socket.io
npm http GET https://registry.npmjs.org/winston
npm http GET https://registry.npmjs.org/socket.io-client
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http GET https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.1.tgz
npm http 304 https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/lie/-/lie-3.0.2.tgz
npm http 200 https://registry.npmjs.org/socket.io-client
npm http GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.5.tgz
npm http 200 https://registry.npmjs.org/winston
npm http GET https://registry.npmjs.org/winston/-/winston-2.2.0.tgz
npm http 200 https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.1.tgz
npm http 200 https://registry.npmjs.org/winston/-/winston-2.2.0.tgz
npm http 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.5.tgz
npm http 200 https://registry.npmjs.org/tape
npm http GET https://registry.npmjs.org/tape/-/tape-1.1.1.tgz
npm http 200 https://registry.npmjs.org/lie/-/lie-3.0.2.tgz
npm http 200 https://registry.npmjs.org/tape/-/tape-1.1.1.tgz
npm http 200 https://registry.npmjs.org/socket.io
npm http GET https://registry.npmjs.org/socket.io/-/socket.io-1.4.5.tgz
npm http 200 https://registry.npmjs.org/socket.io/-/socket.io-1.4.5.tgz
npm http GET https://registry.npmjs.org/fs-extra
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/engine.io
npm http GET https://registry.npmjs.org/socket.io-parser
npm http GET https://registry.npmjs.org/socket.io-adapter
npm http GET https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/jsonify
npm http GET https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/defined
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/engine.io-client
npm http GET https://registry.npmjs.org/component-bind
npm http GET https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/object-component
npm http GET https://registry.npmjs.org/parseuri
npm http GET https://registry.npmjs.org/to-array
npm http GET https://registry.npmjs.org/backo2
npm http GET https://registry.npmjs.org/indexof
npm http GET https://registry.npmjs.org/colors
npm http GET https://registry.npmjs.org/cycle
npm http GET https://registry.npmjs.org/eyes
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/pkginfo
npm http GET https://registry.npmjs.org/stack-trace
npm http GET https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/socket.io-parser
npm http GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.6.tgz
npm http 200 https://registry.npmjs.org/socket.io-adapter
npm http GET https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.4.0.tgz
npm http 200 https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.7.tgz
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/es3ify/-/es3ify-0.1.4.tgz
npm http 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.6.tgz
npm http 200 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.4.0.tgz
npm http GET https://registry.npmjs.org/fs-extra/-/fs-extra-0.24.0.tgz
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/inline-process-browser/-/inline-process-browser-1.0.0.tgz
npm http 200 https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/immediate/-/immediate-3.0.5.tgz
npm http 304 https://registry.npmjs.org/jsonify
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/deep-equal/-/deep-equal-0.0.0.tgz
npm http 304 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/engine.io
npm http 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.7.tgz
npm http GET https://registry.npmjs.org/engine.io/-/engine.io-1.6.8.tgz
npm http 304 https://registry.npmjs.org/content-type
npm http 200 https://registry.npmjs.org/deep-equal/-/deep-equal-0.0.0.tgz
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/fs-extra/-/fs-extra-0.24.0.tgz
npm http 200 https://registry.npmjs.org/immediate/-/immediate-3.0.5.tgz
npm http 200 https://registry.npmjs.org/inline-process-browser/-/inline-process-browser-1.0.0.tgz
npm http 200 https://registry.npmjs.org/es3ify/-/es3ify-0.1.4.tgz
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 200 https://registry.npmjs.org/engine.io/-/engine.io-1.6.8.tgz
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.2.tgz
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/benchmark
npm http GET https://registry.npmjs.org/engine.io-parser
npm http GET https://registry.npmjs.org/base64id
npm http GET https://registry.npmjs.org/ws
npm http GET https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/send
npm http 200 https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/bluebird/-/bluebird-2.10.2.tgz
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/array-flatten
npm http GET https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.3.0.tgz
npm http 200 https://registry.npmjs.org/component-bind
npm http GET https://registry.npmjs.org/component-bind/-/component-bind-1.0.0.tgz
npm http 200 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/parseuri
npm http 200 https://registry.npmjs.org/component-emitter
npm http 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.2.tgz
npm http GET https://registry.npmjs.org/object-component/-/object-component-0.0.3.tgz
npm http GET https://registry.npmjs.org/parseuri/-/parseuri-0.0.4.tgz
npm http GET https://registry.npmjs.org/component-emitter/-/component-emitter-1.2.0.tgz
npm http 200 https://registry.npmjs.org/to-array
npm http GET https://registry.npmjs.org/to-array/-/to-array-0.1.4.tgz
npm http 304 https://registry.npmjs.org/indexof
npm http 200 https://registry.npmjs.org/backo2
npm http 200 https://registry.npmjs.org/cycle
npm http GET https://registry.npmjs.org/unpipe
npm http 200 https://registry.npmjs.org/eyes
npm http GET https://registry.npmjs.org/backo2/-/backo2-1.0.2.tgz
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/cycle/-/cycle-1.0.3.tgz
npm http GET https://registry.npmjs.org/eyes/-/eyes-0.1.8.tgz
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/bluebird/-/bluebird-2.10.2.tgz
npm http GET https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz
npm http GET https://registry.npmjs.org/pkginfo/-/pkginfo-0.3.1.tgz
npm http GET https://registry.npmjs.org/colors/-/colors-1.0.3.tgz
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/debug/-/debug-0.7.4.tgz
npm http 304 https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.3.0.tgz
npm http GET https://registry.npmjs.org/async/-/async-1.0.0.tgz
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/component-emitter/-/component-emitter-1.1.2.tgz
npm http 200 https://registry.npmjs.org/component-bind/-/component-bind-1.0.0.tgz
npm http 200 https://registry.npmjs.org/parseuri/-/parseuri-0.0.4.tgz
npm http 200 https://registry.npmjs.org/component-emitter/-/component-emitter-1.2.0.tgz
npm http 200 https://registry.npmjs.org/object-component/-/object-component-0.0.3.tgz
npm http 200 https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/json3/-/json3-3.3.2.tgz
npm http 200 https://registry.npmjs.org/to-array/-/to-array-0.1.4.tgz
npm http 200 https://registry.npmjs.org/backo2/-/backo2-1.0.2.tgz
npm http 200 https://registry.npmjs.org/cycle/-/cycle-1.0.3.tgz
npm http 200 https://registry.npmjs.org/eyes/-/eyes-0.1.8.tgz
npm http 200 https://registry.npmjs.org/benchmark
npm http GET https://registry.npmjs.org/benchmark/-/benchmark-1.0.0.tgz
npm http 200 https://registry.npmjs.org/base64id
npm http GET https://registry.npmjs.org/base64id/-/base64id-0.1.0.tgz
npm http 200 https://registry.npmjs.org/engine.io-parser
npm http GET https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.4.tgz
npm http 200 https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz
npm http 200 https://registry.npmjs.org/engine.io-client
npm http 200 https://registry.npmjs.org/pkginfo/-/pkginfo-0.3.1.tgz
npm http 200 https://registry.npmjs.org/debug/-/debug-0.7.4.tgz
npm http GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.8.tgz
npm http 304 https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/accepts/-/accepts-1.1.4.tgz
npm http 200 https://registry.npmjs.org/stack-trace
npm http GET https://registry.npmjs.org/stack-trace/-/stack-trace-0.0.9.tgz
npm http 304 https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/ee-first
npm http 200 https://registry.npmjs.org/colors/-/colors-1.0.3.tgz
npm http 200 https://registry.npmjs.org/component-emitter/-/component-emitter-1.1.2.tgz
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/json3/-/json3-3.3.2.tgz
npm http 200 https://registry.npmjs.org/async/-/async-1.0.0.tgz
npm http 304 https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/base64id/-/base64id-0.1.0.tgz
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/ws
npm http 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.8.tgz
npm http 200 https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.4.tgz
npm http 200 https://registry.npmjs.org/benchmark/-/benchmark-1.0.0.tgz
npm http GET https://registry.npmjs.org/through2/-/through2-0.6.5.tgz
npm http GET https://registry.npmjs.org/ws/-/ws-1.0.1.tgz
npm http 304 https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/json3/-/json3-3.2.6.tgz
npm http 200 https://registry.npmjs.org/accepts/-/accepts-1.1.4.tgz
npm http 304 https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/stack-trace/-/stack-trace-0.0.9.tgz
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/through2/-/through2-0.6.5.tgz
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/jstransform/-/jstransform-3.0.0.tgz
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/ws/-/ws-1.0.1.tgz
npm http 200 https://registry.npmjs.org/json3/-/json3-3.2.6.tgz
npm http GET https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.0.tgz
npm http GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-3001.0001.0000-dev-harmony-fb.tgz
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/negotiator/-/negotiator-0.4.9.tgz
npm http GET https://registry.npmjs.org/mime-types/-/mime-types-2.0.14.tgz
npm http GET https://registry.npmjs.org/arraybuffer.slice
npm http GET https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/blob
npm http GET https://registry.npmjs.org/utf8
npm http GET https://registry.npmjs.org/after
npm http GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.6.tgz
npm http 304 https://registry.npmjs.org/acorn
npm http 200 https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.0.tgz
npm http GET https://registry.npmjs.org/options
npm http GET https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/jstransform/-/jstransform-3.0.0.tgz
npm http 200 https://registry.npmjs.org/mime-types/-/mime-types-2.0.14.tgz
npm http 200 https://registry.npmjs.org/negotiator/-/negotiator-0.4.9.tgz
npm http 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-3001.0001.0000-dev-harmony-fb.tgz
npm http 200 https://registry.npmjs.org/utf8
npm http GET https://registry.npmjs.org/utf8/-/utf8-2.1.0.tgz
npm http 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.6.tgz
npm http 200 https://registry.npmjs.org/after
npm http 200 https://registry.npmjs.org/blob
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/after/-/after-0.8.1.tgz
npm http GET https://registry.npmjs.org/blob/-/blob-0.0.4.tgz
npm http 200 https://registry.npmjs.org/base64-arraybuffer
npm http 200 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/arraybuffer.slice
npm http GET https://registry.npmjs.org/base64-arraybuffer/-/base64-arraybuffer-0.1.2.tgz
npm http GET https://registry.npmjs.org/arraybuffer.slice/-/arraybuffer.slice-0.0.6.tgz
npm http GET https://registry.npmjs.org/options/-/options-0.0.6.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/better-assert
npm http GET https://registry.npmjs.org/mime-db/-/mime-db-1.12.0.tgz
npm http 200 https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/recast/-/recast-0.10.43.tgz
npm http 200 https://registry.npmjs.org/utf8/-/utf8-2.1.0.tgz
npm http 200 https://registry.npmjs.org/blob/-/blob-0.0.4.tgz
npm http 200 https://registry.npmjs.org/after/-/after-0.8.1.tgz
npm http 200 https://registry.npmjs.org/ultron
npm http GET https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/base64-arraybuffer/-/base64-arraybuffer-0.1.2.tgz
npm http 200 https://registry.npmjs.org/arraybuffer.slice/-/arraybuffer.slice-0.0.6.tgz
npm http GET https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/rimraf
npm http GET https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/options/-/options-0.0.6.tgz
npm http GET https://registry.npmjs.org/ultron/-/ultron-1.0.2.tgz
npm http 200 https://registry.npmjs.org/mime-db/-/mime-db-1.12.0.tgz
npm http 200 https://registry.npmjs.org/better-assert
npm http 200 https://registry.npmjs.org/recast/-/recast-0.10.43.tgz
npm http GET https://registry.npmjs.org/better-assert/-/better-assert-1.0.2.tgz
npm http GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http GET https://registry.npmjs.org/parsejson
npm http GET https://registry.npmjs.org/parseqs
npm http GET https://registry.npmjs.org/component-inherit
npm http GET https://registry.npmjs.org/yeast
npm http GET https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/ultron/-/ultron-1.0.2.tgz
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/jsonfile
npm http GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.2.3.tgz
npm http 200 https://registry.npmjs.org/parsejson
npm http 200 https://registry.npmjs.org/better-assert/-/better-assert-1.0.2.tgz
npm http 200 https://registry.npmjs.org/parseqs
npm http 200 https://registry.npmjs.org/component-inherit
npm http GET https://registry.npmjs.org/parsejson/-/parsejson-0.0.1.tgz
npm http GET https://registry.npmjs.org/component-inherit/-/component-inherit-0.0.3.tgz
npm http GET https://registry.npmjs.org/parseqs/-/parseqs-0.0.2.tgz
npm http GET https://registry.npmjs.org/callsite
npm http 200 https://registry.npmjs.org/has-cors
npm http 200 https://registry.npmjs.org/yeast
npm http GET https://registry.npmjs.org/yeast/-/yeast-0.1.2.tgz
npm http GET https://registry.npmjs.org/has-cors/-/has-cors-1.1.0.tgz
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1001.0-dev-harmony-fb.tgz
npm http 200 https://registry.npmjs.org/xmlhttprequest-ssl
npm http GET https://registry.npmjs.org/xmlhttprequest-ssl/-/xmlhttprequest-ssl-1.5.1.tgz
npm http 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.2.3.tgz
npm http GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/parsejson/-/parsejson-0.0.1.tgz
npm http 200 https://registry.npmjs.org/callsite
npm http 200 https://registry.npmjs.org/yeast/-/yeast-0.1.2.tgz
npm http GET https://registry.npmjs.org/callsite/-/callsite-1.0.0.tgz
npm http 200 https://registry.npmjs.org/component-inherit/-/component-inherit-0.0.3.tgz
npm http 200 https://registry.npmjs.org/parseqs/-/parseqs-0.0.2.tgz
npm http 200 https://registry.npmjs.org/has-cors/-/has-cors-1.1.0.tgz
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/callsite/-/callsite-1.0.0.tgz
npm http 200 https://registry.npmjs.org/xmlhttprequest-ssl/-/xmlhttprequest-ssl-1.5.1.tgz
npm http GET https://registry.npmjs.org/source-map/-/source-map-0.5.3.tgz
npm http 200 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1001.0-dev-harmony-fb.tgz
npm http GET https://registry.npmjs.org/private/-/private-0.1.6.tgz
npm http GET https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map/-/source-map-0.1.31.tgz
npm http 200 https://registry.npmjs.org/private/-/private-0.1.6.tgz
npm http 200 https://registry.npmjs.org/source-map/-/source-map-0.5.3.tgz
npm http 304 https://registry.npmjs.org/has-binary
npm http 200 https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/ast-types/-/ast-types-0.8.15.tgz
npm http GET https://registry.npmjs.org/base62/-/base62-0.1.1.tgz
npm http 304 https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/ast-types/-/ast-types-0.8.15.tgz
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/source-map/-/source-map-0.1.31.tgz
npm http 200 https://registry.npmjs.org/base62/-/base62-0.1.1.tgz
npm http GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm WARN package.json thali@2.1.0 No README data
npm http GET https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/javascript-state-machine
npm http GET https://registry.npmjs.org/long
npm http GET https://registry.npmjs.org/multiplex
npm http GET https://registry.npmjs.org/node-ssdp
npm http GET https://registry.npmjs.org/urlsafe-base64
npm http GET https://registry.npmjs.org/jsdoc
npm http GET https://registry.npmjs.org/body-parser
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/winston
npm http GET https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/ip/-/ip-1.1.0.tgz
npm http 200 https://registry.npmjs.org/node-ssdp
npm http 200 https://registry.npmjs.org/long
npm http GET https://registry.npmjs.org/long/-/long-3.0.3.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http GET https://registry.npmjs.org/javascript-state-machine/-/javascript-state-machine-2.3.5.tgz
npm http 200 https://registry.npmjs.org/urlsafe-base64
npm http GET https://registry.npmjs.org/urlsafe-base64/-/urlsafe-base64-1.0.0.tgz
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/multiplex
npm http GET https://registry.npmjs.org/express/-/express-4.13.3.tgz
npm http GET https://registry.npmjs.org/multiplex/-/multiplex-6.6.1.tgz
npm http 304 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/winston/-/winston-1.1.2.tgz
npm http 304 https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/ip/-/ip-1.1.0.tgz
npm http GET https://registry.npmjs.org/request/-/request-2.69.0.tgz
npm http 200 https://registry.npmjs.org/jsdoc
npm http GET https://registry.npmjs.org/jsdoc/-/jsdoc-3.4.0.tgz
npm http 200 https://registry.npmjs.org/multiplex/-/multiplex-6.6.1.tgz
npm http 200 https://registry.npmjs.org/long/-/long-3.0.3.tgz
npm http 200 https://registry.npmjs.org/urlsafe-base64/-/urlsafe-base64-1.0.0.tgz
npm http 200 https://registry.npmjs.org/body-parser
npm http 200 https://registry.npmjs.org/javascript-state-machine/-/javascript-state-machine-2.3.5.tgz
npm http GET https://registry.npmjs.org/body-parser/-/body-parser-1.15.0.tgz
npm http 200 https://registry.npmjs.org/winston/-/winston-1.1.2.tgz
npm http 200 https://registry.npmjs.org/express/-/express-4.13.3.tgz
npm http 200 https://registry.npmjs.org/request/-/request-2.69.0.tgz
npm http 200 https://registry.npmjs.org/jsdoc/-/jsdoc-3.4.0.tgz
npm http 200 https://registry.npmjs.org/body-parser/-/body-parser-1.15.0.tgz
npm http GET https://registry.npmjs.org/varint
npm http GET https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/iconv-lite
npm http GET https://registry.npmjs.org/raw-body
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http GET https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/har-validator
npm http GET https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/aws4
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/colors
npm http GET https://registry.npmjs.org/cycle
npm http GET https://registry.npmjs.org/eyes
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/pkginfo
npm http GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/bytes
npm http 200 https://registry.npmjs.org/varint
npm http GET https://registry.npmjs.org/varint/-/varint-4.0.0.tgz
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/http-errors/-/http-errors-1.4.0.tgz
npm http 200 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.5.tgz
npm http GET https://registry.npmjs.org/qs/-/qs-6.1.0.tgz
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/varint/-/varint-4.0.0.tgz
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.0.tgz
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/http-errors/-/http-errors-1.4.0.tgz
npm http 304 https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie/-/cookie-0.1.3.tgz
npm http GET https://registry.npmjs.org/end-of-stream
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.5.tgz
npm http 304 https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/escape-html/-/escape-html-1.0.2.tgz
npm http 304 https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/depd/-/depd-1.0.1.tgz
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.0.tgz
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/qs/-/qs-6.1.0.tgz
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.0.tgz
npm http 304 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/iconv-lite
npm http GET https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.13.tgz
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.0.tgz
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.0.tgz
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.0.tgz
npm http 304 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/cookie/-/cookie-0.1.3.tgz
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/send/-/send-0.13.0.tgz
npm http GET https://registry.npmjs.org/catharsis
npm http GET https://registry.npmjs.org/espree
npm http GET https://registry.npmjs.org/js2xmlparser
npm http GET https://registry.npmjs.org/marked
npm http GET https://registry.npmjs.org/requizzle
npm http 304 https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/wrench
npm http GET https://registry.npmjs.org/strip-json-comments
npm http GET https://registry.npmjs.org/underscore
npm http GET https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/escape-html/-/escape-html-1.0.2.tgz
npm http 304 https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/bl/-/bl-1.0.3.tgz
npm http 304 https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/caseless/-/caseless-0.11.0.tgz
npm http 200 https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/is-typedarray/-/is-typedarray-1.0.0.tgz
npm http 304 https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/forever-agent/-/forever-agent-0.6.1.tgz
npm http 304 https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/form-data/-/form-data-1.0.0-rc3.tgz
npm http 304 https://registry.npmjs.org/http-signature
npm http 200 https://registry.npmjs.org/send/-/send-0.13.0.tgz
npm http GET https://registry.npmjs.org/http-signature/-/http-signature-1.1.1.tgz
npm http 304 https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.13.tgz
npm http GET https://registry.npmjs.org/hawk/-/hawk-3.1.3.tgz
npm http 200 https://registry.npmjs.org/caseless/-/caseless-0.11.0.tgz
npm http 304 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/is-typedarray/-/is-typedarray-1.0.0.tgz
npm http 200 https://registry.npmjs.org/forever-agent/-/forever-agent-0.6.1.tgz
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/form-data/-/form-data-1.0.0-rc3.tgz
npm http 304 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/bl/-/bl-1.0.3.tgz
npm http 200 https://registry.npmjs.org/http-signature/-/http-signature-1.1.1.tgz
npm http 200 https://registry.npmjs.org/hawk/-/hawk-3.1.3.tgz
npm http 304 https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.1.tgz
npm http 304 https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/qs/-/qs-6.0.2.tgz
npm http 304 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/aws4
npm http GET https://registry.npmjs.org/aws4/-/aws4-1.3.1.tgz
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/aws-sign2/-/aws-sign2-0.6.0.tgz
npm http GET https://registry.npmjs.org/har-validator/-/har-validator-2.0.6.tgz
npm http 304 https://registry.npmjs.org/async
npm http 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.1.tgz
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/extend/-/extend-3.0.0.tgz
npm http 200 https://registry.npmjs.org/aws4/-/aws4-1.3.1.tgz
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/qs/-/qs-6.0.2.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/aws-sign2/-/aws-sign2-0.6.0.tgz
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 200 https://registry.npmjs.org/har-validator/-/har-validator-2.0.6.tgz
npm http 304 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/extend/-/extend-3.0.0.tgz
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-1.0.0.tgz
npm http 200 https://registry.npmjs.org/depd/-/depd-1.0.1.tgz
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/unpipe
npm http 200 https://registry.npmjs.org/catharsis
npm http 200 https://registry.npmjs.org/requizzle
npm http 200 https://registry.npmjs.org/marked
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/underscore
npm http 304 https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/requizzle/-/requizzle-0.2.1.tgz
npm http GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.7.tgz
npm http GET https://registry.npmjs.org/marked/-/marked-0.3.5.tgz
npm http 200 https://registry.npmjs.org/espree
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/wrench
npm http 304 https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/underscore/-/underscore-1.8.3.tgz
npm http GET https://registry.npmjs.org/async/-/async-1.4.2.tgz
npm http 200 https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-1.0.0.tgz
npm http 304 https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/espree/-/espree-2.2.5.tgz
npm http 200 https://registry.npmjs.org/async/-/async-1.4.2.tgz
npm http GET https://registry.npmjs.org/bluebird/-/bluebird-2.9.34.tgz
npm http GET https://registry.npmjs.org/wrench/-/wrench-1.5.8.tgz
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/async/-/async-1.5.2.tgz
npm http 200 https://registry.npmjs.org/espree/-/espree-2.2.5.tgz
npm http 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.7.tgz
npm http 200 https://registry.npmjs.org/marked/-/marked-0.3.5.tgz
npm http 200 https://registry.npmjs.org/underscore/-/underscore-1.8.3.tgz
npm http 200 https://registry.npmjs.org/wrench/-/wrench-1.5.8.tgz
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/lru-cache
npm http 200 https://registry.npmjs.org/async/-/async-1.5.2.tgz
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/bluebird/-/bluebird-2.9.34.tgz
npm http GET https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/jsprim
npm http GET https://registry.npmjs.org/sshpk
npm http 200 https://registry.npmjs.org/requizzle/-/requizzle-0.2.1.tgz
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/commander
npm http GET https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/lru-cache
npm http 200 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/assert-plus
npm http 200 https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/lru-cache/-/lru-cache-4.0.0.tgz
npm http GET https://registry.npmjs.org/jsprim/-/jsprim-1.2.2.tgz
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/destroy/-/destroy-1.0.3.tgz
npm http GET https://registry.npmjs.org/assert-plus/-/assert-plus-0.2.0.tgz
npm http GET https://registry.npmjs.org/sshpk/-/sshpk-1.7.4.tgz
npm http 200 https://registry.npmjs.org/jsprim/-/jsprim-1.2.2.tgz
npm http 200 https://registry.npmjs.org/lru-cache/-/lru-cache-4.0.0.tgz
npm http 200 https://registry.npmjs.org/assert-plus/-/assert-plus-0.2.0.tgz
npm http GET https://registry.npmjs.org/underscore/-/underscore-1.6.0.tgz
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/commander/-/commander-2.9.0.tgz
npm http GET https://registry.npmjs.org/is-my-json-valid/-/is-my-json-valid-2.13.1.tgz
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/sshpk/-/sshpk-1.7.4.tgz
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/destroy/-/destroy-1.0.3.tgz
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 200 https://registry.npmjs.org/commander/-/commander-2.9.0.tgz
npm http 304 https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/json-schema
npm http GET https://registry.npmjs.org/verror
npm http GET https://registry.npmjs.org/pseudomap
npm http GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/pseudomap
npm http 200 https://registry.npmjs.org/underscore/-/underscore-1.6.0.tgz
npm http GET https://registry.npmjs.org/pseudomap/-/pseudomap-1.0.2.tgz
npm http 200 https://registry.npmjs.org/is-my-json-valid/-/is-my-json-valid-2.13.1.tgz
npm http 200 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/yallist/-/yallist-2.0.0.tgz
npm http GET https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/json-schema
npm http 200 https://registry.npmjs.org/verror
npm http GET https://registry.npmjs.org/json-schema/-/json-schema-0.2.2.tgz
npm http GET https://registry.npmjs.org/verror/-/verror-1.3.6.tgz
npm http 200 https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/extsprintf/-/extsprintf-1.0.2.tgz
npm http 304 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/pseudomap/-/pseudomap-1.0.2.tgz
npm http GET https://registry.npmjs.org/graceful-readlink
npm http GET https://registry.npmjs.org/dashdash
npm http GET https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/extsprintf/-/extsprintf-1.0.2.tgz
npm http 304 https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/hoek/-/hoek-2.16.3.tgz
npm http GET https://registry.npmjs.org/boom/-/boom-2.10.1.tgz
npm http 304 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/yallist/-/yallist-2.0.0.tgz
npm http GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/graceful-readlink
npm http GET https://registry.npmjs.org/cryptiles/-/cryptiles-2.0.5.tgz
npm http GET https://registry.npmjs.org/sntp/-/sntp-1.0.9.tgz
npm http GET https://registry.npmjs.org/graceful-readlink/-/graceful-readlink-1.0.1.tgz
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/pinkie
npm http 200 https://registry.npmjs.org/json-schema/-/json-schema-0.2.2.tgz
npm http GET https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/asn1/-/asn1-0.2.3.tgz
npm http 200 https://registry.npmjs.org/verror/-/verror-1.3.6.tgz
npm http GET https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/hoek/-/hoek-2.16.3.tgz
npm http 200 https://registry.npmjs.org/sntp/-/sntp-1.0.9.tgz
npm http 200 https://registry.npmjs.org/dashdash
npm http GET https://registry.npmjs.org/dashdash/-/dashdash-1.13.0.tgz
npm http 200 https://registry.npmjs.org/boom/-/boom-2.10.1.tgz
npm http 200 https://registry.npmjs.org/cryptiles/-/cryptiles-2.0.5.tgz
npm http 200 https://registry.npmjs.org/graceful-readlink/-/graceful-readlink-1.0.1.tgz
npm http 200 https://registry.npmjs.org/asn1/-/asn1-0.2.3.tgz
npm http GET https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/jsonpointer
npm http GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/dashdash/-/dashdash-1.13.0.tgz
npm http 304 https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/underscore-contrib
npm http GET https://registry.npmjs.org/generate-object-property/-/generate-object-property-1.2.0.tgz
npm http GET https://registry.npmjs.org/underscore-contrib/-/underscore-contrib-0.3.0.tgz
npm http 200 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/jsonpointer/-/jsonpointer-2.0.0.tgz
npm http 200 https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/assert-plus/-/assert-plus-1.0.0.tgz
npm http GET https://registry.npmjs.org/generate-function/-/generate-function-2.0.0.tgz
npm http 200 https://registry.npmjs.org/generate-object-property/-/generate-object-property-1.2.0.tgz
npm http 200 https://registry.npmjs.org/underscore-contrib/-/underscore-contrib-0.3.0.tgz
npm http 200 https://registry.npmjs.org/generate-function/-/generate-function-2.0.0.tgz
npm http 200 https://registry.npmjs.org/jsonpointer/-/jsonpointer-2.0.0.tgz
npm http 200 https://registry.npmjs.org/assert-plus/-/assert-plus-1.0.0.tgz
npm http GET https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/is-property
npm http GET https://registry.npmjs.org/is-property/-/is-property-1.0.2.tgz
npm http 200 https://registry.npmjs.org/is-property/-/is-property-1.0.2.tgz
npm http GET https://registry.npmjs.org/node-ssdp
npm http 304 https://registry.npmjs.org/node-ssdp
npm WARN package.json install@0.0.1 No repository field.
npm WARN package.json install@0.0.1 No README data
npm http GET https://registry.npmjs.org/jxc
npm http GET https://registry.npmjs.org/unzip
npm http GET https://registry.npmjs.org/fs-extra-promise
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/unzip
npm http GET https://registry.npmjs.org/unzip/-/unzip-0.1.11.tgz
npm http 200 https://registry.npmjs.org/jxc
npm http GET https://registry.npmjs.org/jxc/-/jxc-1.0.13.tgz
npm http 200 https://registry.npmjs.org/unzip/-/unzip-0.1.11.tgz
npm http 200 https://registry.npmjs.org/jxc/-/jxc-1.0.13.tgz
npm http GET https://registry.npmjs.org/fs-extra
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/pullstream
npm http GET https://registry.npmjs.org/binary
npm http GET https://registry.npmjs.org/setimmediate
npm http GET https://registry.npmjs.org/match-stream
npm http GET https://registry.npmjs.org/fstream
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/har-validator
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/setimmediate
npm http GET https://registry.npmjs.org/setimmediate/-/setimmediate-1.0.4.tgz
npm http GET https://registry.npmjs.org/graceful-fs
npm http GET https://registry.npmjs.org/jsonfile
npm http GET https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/pullstream
npm http 200 https://registry.npmjs.org/binary
npm http GET https://registry.npmjs.org/binary/-/binary-0.3.0.tgz
npm http GET https://registry.npmjs.org/pullstream/-/pullstream-0.4.1.tgz
npm http 304 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/fstream/-/fstream-0.1.31.tgz
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/setimmediate/-/setimmediate-1.0.4.tgz
npm http 200 https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/match-stream/-/match-stream-0.0.2.tgz
npm http 304 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/pullstream/-/pullstream-0.4.1.tgz
npm http 304 https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/binary/-/binary-0.3.0.tgz
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/fstream/-/fstream-0.1.31.tgz
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 200 https://registry.npmjs.org/match-stream/-/match-stream-0.0.2.tgz
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/over
npm http GET https://registry.npmjs.org/slice-stream
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/buffers
npm http GET https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/jsprim
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/mkdirp
npm WARN deprecated graceful-fs@3.0.8: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
npm http 200 https://registry.npmjs.org/over
npm http 200 https://registry.npmjs.org/slice-stream
npm http GET https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/over/-/over-0.0.5.tgz
npm http GET https://registry.npmjs.org/commander
npm http GET https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/slice-stream/-/slice-stream-1.0.0.tgz
npm http GET https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/buffers
npm http GET https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/buffers/-/buffers-0.1.1.tgz
npm http 304 https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/slice-stream/-/slice-stream-1.0.0.tgz
npm http 200 https://registry.npmjs.org/over/-/over-0.0.5.tgz
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/chainsaw/-/chainsaw-0.1.0.tgz
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/buffers/-/buffers-0.1.1.tgz
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/json-schema
npm http GET https://registry.npmjs.org/verror
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/pseudomap
npm http GET https://registry.npmjs.org/yallist
npm http GET https://registry.npmjs.org/graceful-readlink
npm http 200 https://registry.npmjs.org/chainsaw/-/chainsaw-0.1.0.tgz
npm http GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/pseudomap
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/sntp
npm http GET https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/minimist
npm http GET https://registry.npmjs.org/traverse
npm http GET https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/color-convert
npm http GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/jsbn
npm http GET https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/jodid25519
npm http GET https://registry.npmjs.org/ecc-jsbn
npm http GET https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/color-convert
npm http 304 https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/adm-zip
npm http GET https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/jsbn
npm http 200 https://registry.npmjs.org/ecc-jsbn
npm http 200 https://registry.npmjs.org/jodid25519
npm http 200 https://registry.npmjs.org/traverse
npm http GET https://registry.npmjs.org/jsbn/-/jsbn-0.1.0.tgz
npm http GET https://registry.npmjs.org/ecc-jsbn/-/ecc-jsbn-0.1.1.tgz
npm http GET https://registry.npmjs.org/jodid25519/-/jodid25519-1.0.2.tgz
npm http GET https://registry.npmjs.org/traverse/-/traverse-0.3.9.tgz
npm http GET https://registry.npmjs.org/jsonpointer
npm http GET https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/progress
npm http GET https://registry.npmjs.org/progress/-/progress-1.1.8.tgz
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 200 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.14.1.tgz
npm http 200 https://registry.npmjs.org/adm-zip
npm http GET https://registry.npmjs.org/adm-zip/-/adm-zip-0.4.7.tgz
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/jodid25519/-/jodid25519-1.0.2.tgz
npm http 200 https://registry.npmjs.org/ecc-jsbn/-/ecc-jsbn-0.1.1.tgz
npm http 200 https://registry.npmjs.org/jsbn/-/jsbn-0.1.0.tgz
npm http 200 https://registry.npmjs.org/traverse/-/traverse-0.3.9.tgz
npm http 200 https://registry.npmjs.org/progress/-/progress-1.1.8.tgz
npm http 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.14.1.tgz
npm http 200 https://registry.npmjs.org/adm-zip/-/adm-zip-0.4.7.tgz
npm http 304 https://registry.npmjs.org/is-property
npm WARN package.json thali-cordova-plugin-jxcore@1.0.0 No repository field.
npm http GET https://registry.npmjs.org/express-pouchdb
npm http GET https://registry.npmjs.org/nock
npm http GET https://registry.npmjs.org/bn.js
npm http GET https://registry.npmjs.org/body-parser
npm http GET https://registry.npmjs.org/pouchdb
npm http GET https://registry.npmjs.org/proxyquire
npm http GET https://registry.npmjs.org/randomstring
npm http GET https://registry.npmjs.org/request-promise
npm http GET https://registry.npmjs.org/sinon
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/fs-extra-promise
npm http GET https://registry.npmjs.org/supertest
npm http GET https://registry.npmjs.org/supertest-as-promised
npm http GET https://registry.npmjs.org/tape-catch
npm http GET https://registry.npmjs.org/tmp
npm http GET https://registry.npmjs.org/wrapping-tape
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/leveldown-mobile
npm http GET https://registry.npmjs.org/long
npm http GET https://registry.npmjs.org/multiplex
npm http GET https://registry.npmjs.org/node-ssdp
npm http GET https://registry.npmjs.org/request
npm http GET https://registry.npmjs.org/socket.io-client
npm http GET https://registry.npmjs.org/urlsafe-base64
npm http GET https://registry.npmjs.org/tape
npm http GET https://registry.npmjs.org/uuid
npm http GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.2.1.tgz
npm http 304 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/body-parser
npm http 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.2.1.tgz
npm http 200 https://registry.npmjs.org/express-pouchdb
npm http GET https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb
npm http GET https://registry.npmjs.org/pouchdb/-/pouchdb-5.2.1.tgz
npm http 200 https://registry.npmjs.org/proxyquire
npm http GET https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.4.tgz
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/request-promise
npm http GET https://registry.npmjs.org/request-promise/-/request-promise-0.4.3.tgz
npm http 200 https://registry.npmjs.org/randomstring
npm http GET https://registry.npmjs.org/randomstring/-/randomstring-1.1.4.tgz
npm http 200 https://registry.npmjs.org/sinon
npm http 200 https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.2.tgz
npm http 200 https://registry.npmjs.org/supertest-as-promised
npm http GET https://registry.npmjs.org/sinon/-/sinon-1.17.3.tgz
npm http GET https://registry.npmjs.org/supertest-as-promised/-/supertest-as-promised-2.0.2.tgz
npm http 200 https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb/-/pouchdb-5.2.1.tgz
npm http 200 https://registry.npmjs.org/supertest
npm http GET https://registry.npmjs.org/supertest/-/supertest-1.2.0.tgz
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/tape-catch
npm http GET https://registry.npmjs.org/tape-catch/-/tape-catch-1.0.4.tgz
npm http 200 https://registry.npmjs.org/request-promise/-/request-promise-0.4.3.tgz
npm http 304 https://registry.npmjs.org/long
npm http 200 https://registry.npmjs.org/randomstring/-/randomstring-1.1.4.tgz
npm http 200 https://registry.npmjs.org/sinon/-/sinon-1.17.3.tgz
npm http 200 https://registry.npmjs.org/supertest-as-promised/-/supertest-as-promised-2.0.2.tgz
npm http 304 https://registry.npmjs.org/multiplex
npm http 200 https://registry.npmjs.org/supertest/-/supertest-1.2.0.tgz
npm http 200 https://registry.npmjs.org/tape-catch/-/tape-catch-1.0.4.tgz
npm http 304 https://registry.npmjs.org/node-ssdp
npm http 304 https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/tmp
npm http GET https://registry.npmjs.org/tmp/-/tmp-0.0.28.tgz
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 200 https://registry.npmjs.org/wrapping-tape
npm http 304 https://registry.npmjs.org/tape
npm http GET https://registry.npmjs.org/wrapping-tape/-/wrapping-tape-0.0.3.tgz
npm http GET https://registry.npmjs.org/tape/-/tape-4.4.0.tgz
npm http 304 https://registry.npmjs.org/uuid
npm http 200 https://registry.npmjs.org/leveldown-mobile
npm http GET https://registry.npmjs.org/leveldown-mobile/-/leveldown-mobile-1.1.1.tgz
npm http 200 https://registry.npmjs.org/wrapping-tape/-/wrapping-tape-0.0.3.tgz
npm http 200 https://registry.npmjs.org/tmp/-/tmp-0.0.28.tgz
npm http 200 https://registry.npmjs.org/leveldown-mobile/-/leveldown-mobile-1.1.1.tgz
npm http 200 https://registry.npmjs.org/tape/-/tape-4.4.0.tgz
npm http 200 https://registry.npmjs.org/nock
npm http GET https://registry.npmjs.org/nock/-/nock-2.18.2.tgz
npm http 200 https://registry.npmjs.org/nock/-/nock-2.18.2.tgz
npm http GET https://registry.npmjs.org/fs-extra
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/varint
npm http GET https://registry.npmjs.org/array-uniq
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/lodash
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/iconv-lite
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/raw-body
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/superagent
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/os-tmpdir
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/array-uniq
npm http 304 https://registry.npmjs.org/varint
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/har-validator
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/aws4
npm http GET https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/socket.io-parser
npm http GET https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/indexof
npm http GET https://registry.npmjs.org/parseuri
npm http GET https://registry.npmjs.org/to-array
npm http GET https://registry.npmjs.org/backo2
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/engine.io-client
npm http GET https://registry.npmjs.org/component-bind
npm http GET https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/object-component
npm http GET https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/module-not-found-error
npm http GET https://registry.npmjs.org/array-uniq/-/array-uniq-1.0.2.tgz
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/lodash/-/lodash-3.10.1.tgz
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/end-of-stream
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/os-tmpdir
npm http 304 https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/string.prototype.trim
npm http GET https://registry.npmjs.org/has
npm http GET https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/resolve
npm http GET https://registry.npmjs.org/object-inspect
npm http GET https://registry.npmjs.org/resumer
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/defined
npm http GET https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/graceful-fs
npm http GET https://registry.npmjs.org/rimraf
npm http GET https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/superagent
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/superagent/-/superagent-1.8.0-beta.2.tgz
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/array-uniq/-/array-uniq-1.0.2.tgz
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/lodash/-/lodash-3.10.1.tgz
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/superagent/-/superagent-1.8.0-beta.2.tgz
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/fill-keys
npm http 200 https://registry.npmjs.org/module-not-found-error
npm http 304 https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/has
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/fill-keys/-/fill-keys-1.0.2.tgz
npm http GET https://registry.npmjs.org/module-not-found-error/-/module-not-found-error-1.0.1.tgz
npm http 200 https://registry.npmjs.org/object-inspect
npm http 304 https://registry.npmjs.org/resumer
npm http 200 https://registry.npmjs.org/string.prototype.trim
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/glob/-/glob-5.0.15.tgz
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/object-inspect/-/object-inspect-1.0.2.tgz
npm http GET https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/string.prototype.trim/-/string.prototype.trim-1.1.2.tgz
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/fill-keys/-/fill-keys-1.0.2.tgz
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/module-not-found-error/-/module-not-found-error-1.0.1.tgz
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/string.prototype.trim/-/string.prototype.trim-1.1.2.tgz
npm http 304 https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/object-inspect/-/object-inspect-1.0.2.tgz
npm http 200 https://registry.npmjs.org/glob/-/glob-5.0.15.tgz
npm http GET https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/unpipe
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/better-assert
npm http GET https://registry.npmjs.org/unpipe
npm http GET https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/jsprim
npm http GET https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 200 https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/benchmark
npm http GET https://registry.npmjs.org/commander
npm http GET https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/is-object/-/is-object-1.0.1.tgz
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/json3
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/is-object/-/is-object-1.0.1.tgz
npm http GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/define-properties
npm http GET https://registry.npmjs.org/es-abstract
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/json-schema
npm http GET https://registry.npmjs.org/verror
npm http GET https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/callsite
npm http GET https://registry.npmjs.org/define-properties/-/define-properties-1.1.2.tgz
npm http 200 https://registry.npmjs.org/es-abstract
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.0.tgz
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/color-convert
npm http GET https://registry.npmjs.org/pseudomap
npm http GET https://registry.npmjs.org/yallist
npm http 200 https://registry.npmjs.org/define-properties/-/define-properties-1.1.2.tgz
npm http 304 https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/graceful-readlink
npm http 200 https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.0.tgz
npm http 304 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http GET https://registry.npmjs.org/engine.io-parser
npm http GET https://registry.npmjs.org/parsejson
npm http GET https://registry.npmjs.org/parseqs
npm http GET https://registry.npmjs.org/component-inherit
npm http GET https://registry.npmjs.org/yeast
npm http GET https://registry.npmjs.org/has-cors
npm http GET https://registry.npmjs.org/ws
npm http GET https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/dashdash
npm http GET https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/arraybuffer.slice
npm http GET https://registry.npmjs.org/base64-arraybuffer
npm http GET https://registry.npmjs.org/blob
npm http GET https://registry.npmjs.org/utf8
npm http GET https://registry.npmjs.org/after
npm http GET https://registry.npmjs.org/is-callable
npm http GET https://registry.npmjs.org/es-to-primitive
npm http GET https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/sntp
npm http GET https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/es-to-primitive
npm http GET https://registry.npmjs.org/es-to-primitive/-/es-to-primitive-1.1.1.tgz
npm http 200 https://registry.npmjs.org/is-regex
npm http GET https://registry.npmjs.org/is-regex/-/is-regex-1.0.3.tgz
npm http 304 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/formidable
npm http GET https://registry.npmjs.org/options
npm http GET https://registry.npmjs.org/ultron
npm http GET https://registry.npmjs.org/cookiejar
npm http GET https://registry.npmjs.org/reduce-component
npm http GET https://registry.npmjs.org/is-callable/-/is-callable-1.1.3.tgz
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/formidable
npm http 200 https://registry.npmjs.org/cookiejar
npm http 200 https://registry.npmjs.org/es-to-primitive/-/es-to-primitive-1.1.1.tgz
npm http 304 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/reduce-component
npm http 200 https://registry.npmjs.org/is-regex/-/is-regex-1.0.3.tgz
npm http GET https://registry.npmjs.org/cookiejar/-/cookiejar-2.0.6.tgz
npm http GET https://registry.npmjs.org/formidable/-/formidable-1.0.17.tgz
npm http GET https://registry.npmjs.org/reduce-component/-/reduce-component-1.0.1.tgz
npm http GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.27-1.tgz
npm http 200 https://registry.npmjs.org/is-callable/-/is-callable-1.1.3.tgz
npm http 200 https://registry.npmjs.org/formidable/-/formidable-1.0.17.tgz
npm http 200 https://registry.npmjs.org/cookiejar/-/cookiejar-2.0.6.tgz
npm http 200 https://registry.npmjs.org/reduce-component/-/reduce-component-1.0.1.tgz
npm http 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.27-1.tgz
npm http GET https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/is-date-object
npm http GET https://registry.npmjs.org/is-symbol
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/combined-stream
npm http 200 https://registry.npmjs.org/is-symbol
npm http 200 https://registry.npmjs.org/is-date-object
npm http 304 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/is-symbol/-/is-symbol-1.0.1.tgz
npm http GET https://registry.npmjs.org/is-date-object/-/is-date-object-1.0.1.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/is-date-object/-/is-date-object-1.0.1.tgz
npm http 200 https://registry.npmjs.org/is-symbol/-/is-symbol-1.0.1.tgz
npm http GET https://registry.npmjs.org/chai
npm http GET https://registry.npmjs.org/propagate
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/lodash
npm http GET https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/mkdirp
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http GET https://registry.npmjs.org/lodash/-/lodash-2.4.1.tgz
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/propagate
npm http GET https://registry.npmjs.org/debug/-/debug-1.0.4.tgz
npm http GET https://registry.npmjs.org/propagate/-/propagate-0.3.1.tgz
npm http 200 https://registry.npmjs.org/chai
npm http GET https://registry.npmjs.org/chai/-/chai-3.5.0.tgz
npm http 200 https://registry.npmjs.org/debug/-/debug-1.0.4.tgz
npm http 200 https://registry.npmjs.org/propagate/-/propagate-0.3.1.tgz
npm http 200 https://registry.npmjs.org/lodash/-/lodash-2.4.1.tgz
npm http GET https://registry.npmjs.org/basic-auth
npm http 200 https://registry.npmjs.org/chai/-/chai-3.5.0.tgz
npm http GET https://registry.npmjs.org/cookie-parser
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/header-case-normalizer
npm http GET https://registry.npmjs.org/multiparty
npm http GET https://registry.npmjs.org/pouchdb-all-dbs
npm http GET https://registry.npmjs.org/pouchdb-auth
npm http GET https://registry.npmjs.org/pouchdb-find
npm http GET https://registry.npmjs.org/pouchdb-list
npm http GET https://registry.npmjs.org/pouchdb-replicator
npm http GET https://registry.npmjs.org/pouchdb-rewrite
npm http GET https://registry.npmjs.org/pouchdb-security
npm http GET https://registry.npmjs.org/compression
npm http GET https://registry.npmjs.org/pouchdb-show
npm http GET https://registry.npmjs.org/pouchdb-size
npm http GET https://registry.npmjs.org/pouchdb-update
npm http GET https://registry.npmjs.org/pouchdb-validation
npm http GET https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/pouchdb-vhost
npm http GET https://registry.npmjs.org/pouchdb-wrappers
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/raw-body
npm http GET https://registry.npmjs.org/argsarray
npm http GET https://registry.npmjs.org/double-ended-queue
npm http GET https://registry.npmjs.org/fruitdown
npm http GET https://registry.npmjs.org/js-extend
npm http GET https://registry.npmjs.org/level-sublevel
npm http GET https://registry.npmjs.org/level-write-stream
npm http GET https://registry.npmjs.org/levelup
npm http GET https://registry.npmjs.org/localstorage-down
npm http GET https://registry.npmjs.org/memdown
npm http GET https://registry.npmjs.org/pouchdb-collate
npm http GET https://registry.npmjs.org/pouchdb-collections
npm http GET https://registry.npmjs.org/scope-eval
npm http GET https://registry.npmjs.org/spark-md5
npm http GET https://registry.npmjs.org/vuvuzela
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/request
npm http GET https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/basic-auth
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/cookie-parser
npm http GET https://registry.npmjs.org/bindings
npm http GET https://registry.npmjs.org/abstract-leveldown
npm http GET https://registry.npmjs.org/fast-future
npm http GET https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.3.tgz
npm http GET https://registry.npmjs.org/cookie-parser/-/cookie-parser-1.4.1.tgz
npm http 200 https://registry.npmjs.org/multiparty
npm http 200 https://registry.npmjs.org/pouchdb-auth
npm http 200 https://registry.npmjs.org/header-case-normalizer
npm http GET https://registry.npmjs.org/multiparty/-/multiparty-3.3.2.tgz
npm http GET https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-1.0.5.tgz
npm http GET https://registry.npmjs.org/header-case-normalizer/-/header-case-normalizer-1.0.3.tgz
npm http GET https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/pouchdb-find
npm http 200 https://registry.npmjs.org/pouchdb-list
npm http GET https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.1.0.tgz
npm http GET https://registry.npmjs.org/pouchdb-list/-/pouchdb-list-1.1.0.tgz
npm http 200 https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.3.tgz
npm http 200 https://registry.npmjs.org/cookie-parser/-/cookie-parser-1.4.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/compression
npm http GET https://registry.npmjs.org/pouchdb-rewrite/-/pouchdb-rewrite-1.0.7.tgz
npm http 200 https://registry.npmjs.org/multiparty/-/multiparty-3.3.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb-list/-/pouchdb-list-1.1.0.tgz
npm http 200 https://registry.npmjs.org/header-case-normalizer/-/header-case-normalizer-1.0.3.tgz
npm http 200 https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-1.0.5.tgz
npm http 200 https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.1.0.tgz
npm http GET https://registry.npmjs.org/type-detect
npm http GET https://registry.npmjs.org/assertion-error
npm http GET https://registry.npmjs.org/deep-eql
npm http 200 https://registry.npmjs.org/pouchdb-size
npm http GET https://registry.npmjs.org/pouchdb-size/-/pouchdb-size-1.2.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb-rewrite/-/pouchdb-rewrite-1.0.7.tgz
npm http 200 https://registry.npmjs.org/pouchdb-replicator
npm http GET https://registry.npmjs.org/pouchdb-replicator/-/pouchdb-replicator-2.1.3.tgz
npm http 200 https://registry.npmjs.org/pouchdb-all-dbs
npm http 200 https://registry.npmjs.org/pouchdb-show
npm http GET https://registry.npmjs.org/formatio
npm http GET https://registry.npmjs.org/lolex
npm http GET https://registry.npmjs.org/samsam
npm http GET https://registry.npmjs.org/util
npm http GET https://registry.npmjs.org/pouchdb-show/-/pouchdb-show-1.0.8.tgz
npm http GET https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-security
npm http GET https://registry.npmjs.org/pouchdb-security/-/pouchdb-security-1.2.6.tgz
npm http 304 https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/extend/-/extend-1.3.0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-validation
npm http GET https://registry.npmjs.org/pouchdb-validation/-/pouchdb-validation-1.2.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.1.tgz
npm http GET https://registry.npmjs.org/pouchdb-vhost/-/pouchdb-vhost-1.0.2.tgz
npm http 304 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/pouchdb-update
npm http GET https://registry.npmjs.org/pouchdb-update/-/pouchdb-update-1.0.8.tgz
npm http 304 https://registry.npmjs.org/raw-body
npm http GET https://registry.npmjs.org/raw-body/-/raw-body-1.3.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-replicator/-/pouchdb-replicator-2.1.3.tgz
npm http 200 https://registry.npmjs.org/pouchdb-wrappers
npm http GET https://registry.npmjs.org/pouchdb-wrappers/-/pouchdb-wrappers-1.3.6.tgz
npm http 200 https://registry.npmjs.org/pouchdb-show/-/pouchdb-show-1.0.8.tgz
npm http 200 https://registry.npmjs.org/double-ended-queue
npm http GET https://registry.npmjs.org/double-ended-queue/-/double-ended-queue-2.0.0-0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-security/-/pouchdb-security-1.2.6.tgz
npm http 200 https://registry.npmjs.org/extend/-/extend-1.3.0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-validation/-/pouchdb-validation-1.2.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-vhost/-/pouchdb-vhost-1.0.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb-size/-/pouchdb-size-1.2.2.tgz
npm http 200 https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-update/-/pouchdb-update-1.0.8.tgz
npm http 200 https://registry.npmjs.org/fruitdown
npm http GET https://registry.npmjs.org/fruitdown/-/fruitdown-1.0.1.tgz
npm http 200 https://registry.npmjs.org/js-extend
npm http GET https://registry.npmjs.org/js-extend/-/js-extend-1.0.1.tgz
npm http 200 https://registry.npmjs.org/raw-body/-/raw-body-1.3.4.tgz
npm http 200 https://registry.npmjs.org/level-write-stream
npm http GET https://registry.npmjs.org/level-write-stream/-/level-write-stream-1.0.0.tgz
npm http 200 https://registry.npmjs.org/js-extend/-/js-extend-1.0.1.tgz
npm http 200 https://registry.npmjs.org/argsarray
npm http GET https://registry.npmjs.org/argsarray/-/argsarray-0.0.1.tgz
npm http 200 https://registry.npmjs.org/level-write-stream/-/level-write-stream-1.0.0.tgz
npm http 200 https://registry.npmjs.org/memdown
npm http 200 https://registry.npmjs.org/double-ended-queue/-/double-ended-queue-2.0.0-0.tgz
npm http 200 https://registry.npmjs.org/fruitdown/-/fruitdown-1.0.1.tgz
npm http GET https://registry.npmjs.org/memdown/-/memdown-1.1.2.tgz
npm http 200 https://registry.npmjs.org/argsarray/-/argsarray-0.0.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-wrappers/-/pouchdb-wrappers-1.3.6.tgz
npm http 200 https://registry.npmjs.org/pouchdb-collections
npm http GET https://registry.npmjs.org/pouchdb-collections/-/pouchdb-collections-1.0.1.tgz
npm http 200 https://registry.npmjs.org/localstorage-down
npm http GET https://registry.npmjs.org/localstorage-down/-/localstorage-down-0.6.6.tgz
npm http 200 https://registry.npmjs.org/scope-eval
npm http 200 https://registry.npmjs.org/levelup
npm http 200 https://registry.npmjs.org/level-sublevel
npm http 200 https://registry.npmjs.org/memdown/-/memdown-1.1.2.tgz
npm http GET https://registry.npmjs.org/scope-eval/-/scope-eval-0.0.3.tgz
npm http GET https://registry.npmjs.org/levelup/-/levelup-1.3.1.tgz
npm http GET https://registry.npmjs.org/level-sublevel/-/level-sublevel-6.5.4.tgz
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/es3ify/-/es3ify-0.2.0.tgz
npm http GET https://registry.npmjs.org/request/-/request-2.67.0.tgz
npm http 304 https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/through2/-/through2-2.0.0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-collections/-/pouchdb-collections-1.0.1.tgz
npm http 200 https://registry.npmjs.org/localstorage-down/-/localstorage-down-0.6.6.tgz
npm http 200 https://registry.npmjs.org/bindings
npm http 200 https://registry.npmjs.org/vuvuzela
npm http GET https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.2.tgz
npm http 304 https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/es3ify/-/es3ify-0.2.0.tgz
npm http GET https://registry.npmjs.org/ms/-/ms-0.6.2.tgz
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 200 https://registry.npmjs.org/pouchdb-collate
npm http GET https://registry.npmjs.org/pouchdb-collate/-/pouchdb-collate-1.2.0.tgz
npm http 200 https://registry.npmjs.org/levelup/-/levelup-1.3.1.tgz
npm http 200 https://registry.npmjs.org/level-sublevel/-/level-sublevel-6.5.4.tgz
npm http 304 https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/scope-eval/-/scope-eval-0.0.3.tgz
npm http 200 https://registry.npmjs.org/type-detect
npm http GET https://registry.npmjs.org/type-detect/-/type-detect-1.0.0.tgz
npm http 200 https://registry.npmjs.org/request/-/request-2.67.0.tgz
npm http 200 https://registry.npmjs.org/ms/-/ms-0.6.2.tgz
npm http 200 https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/deep-eql
npm http GET https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.1.tgz
npm http GET https://registry.npmjs.org/deep-eql/-/deep-eql-0.1.3.tgz
npm http 200 https://registry.npmjs.org/spark-md5
npm http GET https://registry.npmjs.org/spark-md5/-/spark-md5-2.0.0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-collate/-/pouchdb-collate-1.2.0.tgz
npm http 200 https://registry.npmjs.org/formatio
npm http GET https://registry.npmjs.org/formatio/-/formatio-1.1.1.tgz
npm http 200 https://registry.npmjs.org/through2/-/through2-2.0.0.tgz
npm http 200 https://registry.npmjs.org/samsam
npm http 200 https://registry.npmjs.org/lolex
npm http 200 https://registry.npmjs.org/type-detect/-/type-detect-1.0.0.tgz
npm http GET https://registry.npmjs.org/samsam/-/samsam-1.1.2.tgz
npm http GET https://registry.npmjs.org/lolex/-/lolex-1.3.2.tgz
npm http 200 https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.1.tgz
npm http 200 https://registry.npmjs.org/deep-eql/-/deep-eql-0.1.3.tgz
npm http 200 https://registry.npmjs.org/fast-future
npm http 304 https://registry.npmjs.org/util
npm http 200 https://registry.npmjs.org/spark-md5/-/spark-md5-2.0.0.tgz
npm http GET https://registry.npmjs.org/type-detect/-/type-detect-0.1.1.tgz
npm http GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.2.tgz
npm http 200 https://registry.npmjs.org/samsam/-/samsam-1.1.2.tgz
npm http 200 https://registry.npmjs.org/type-detect/-/type-detect-0.1.1.tgz
npm http GET https://registry.npmjs.org/end-stream
npm http GET https://registry.npmjs.org/ltgt
npm http GET https://registry.npmjs.org/functional-red-black-tree
npm http 200 https://registry.npmjs.org/formatio/-/formatio-1.1.1.tgz
npm http 200 https://registry.npmjs.org/lolex/-/lolex-1.3.2.tgz
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-2.4.1.tgz
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/esprima
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/d64
npm http GET https://registry.npmjs.org/humble-localstorage
npm http GET https://registry.npmjs.org/tiny-queue
npm http GET https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-0.12.3.tgz
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/through
In file included from ../src/batch.cc:4:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/batch.cc:4:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:8:
In file included from ../src/batch_async.h:15:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Batch, Clear) {
^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
16 warnings generated.
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
15 warnings generated.
In file included from ../src/database.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/database.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:18:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/database.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Database, New) {
^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/database.cc:130:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
16 warnings generated.
In file included from ../src/database_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/database_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
13 warnings generated.
In file included from ../src/iterator.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/iterator.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/iterator.cc:178:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, Next) {
^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:195:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, End) {
^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:222:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
17 warnings generated.
In file included from ../src/iterator_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/iterator_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
14 warnings generated.
In file included from ../src/leveldown.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/leveldown.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:13:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:59:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(leveldown, LeveldownWrap) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:70:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(LeveldownWrap, New) {
^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
In file included from ../src/leveldown.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
17 warnings generated.
In file included from ../src/leveldown_async.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/leveldown_async.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
14 warnings generated.
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/functional-red-black-tree
npm http GET https://registry.npmjs.org/functional-red-black-tree/-/functional-red-black-tree-1.0.1.tgz
npm http 200 https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-2.4.1.tgz
npm http 200 https://registry.npmjs.org/esprima
npm http 200 https://registry.npmjs.org/d64
npm http GET https://registry.npmjs.org/esprima/-/esprima-2.7.2.tgz
npm http GET https://registry.npmjs.org/d64/-/d64-1.0.0.tgz
npm http GET https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/end-stream
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/tiny-queue
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/har-validator
npm http GET https://registry.npmjs.org/tiny-queue/-/tiny-queue-0.2.0.tgz
npm http GET https://registry.npmjs.org/end-stream/-/end-stream-0.1.0.tgz
npm http GET https://registry.npmjs.org/pull-stream
npm http GET https://registry.npmjs.org/ltgt
npm http GET https://registry.npmjs.org/bytewise
npm http GET https://registry.npmjs.org/typewiselite
npm http 200 https://registry.npmjs.org/ltgt
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/levelup/-/levelup-0.19.1.tgz
npm http 200 https://registry.npmjs.org/humble-localstorage
npm http GET https://registry.npmjs.org/ltgt/-/ltgt-1.0.2.tgz
npm http GET https://registry.npmjs.org/humble-localstorage/-/humble-localstorage-1.4.2.tgz
npm http GET https://registry.npmjs.org/deferred-leveldown
npm http GET https://registry.npmjs.org/level-codec
npm http GET https://registry.npmjs.org/level-errors
npm http GET https://registry.npmjs.org/level-iterator-stream
npm http GET https://registry.npmjs.org/prr
npm http GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/qs/-/qs-5.2.0.tgz
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/functional-red-black-tree/-/functional-red-black-tree-1.0.1.tgz
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 200 https://registry.npmjs.org/tiny-queue/-/tiny-queue-0.2.0.tgz
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/end-stream/-/end-stream-0.1.0.tgz
npm http GET https://registry.npmjs.org/write-stream
npm http 200 https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-0.12.3.tgz
npm http 200 https://registry.npmjs.org/ltgt/-/ltgt-1.0.2.tgz
npm http 200 https://registry.npmjs.org/levelup/-/levelup-0.19.1.tgz
npm http 200 https://registry.npmjs.org/d64/-/d64-1.0.0.tgz
npm http 200 https://registry.npmjs.org/esprima/-/esprima-2.7.2.tgz
npm http 200 https://registry.npmjs.org/qs/-/qs-5.2.0.tgz
npm http 200 https://registry.npmjs.org/typewiselite
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/typewiselite/-/typewiselite-1.0.0.tgz
npm http GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/deferred-leveldown
npm http 200 https://registry.npmjs.org/ltgt
npm http GET https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/ltgt/-/ltgt-2.1.2.tgz
npm http GET https://registry.npmjs.org/deferred-leveldown/-/deferred-leveldown-1.2.1.tgz
npm http 200 https://registry.npmjs.org/pull-stream
npm http 200 https://registry.npmjs.org/level-iterator-stream
npm http 200 https://registry.npmjs.org/prr
npm http GET https://registry.npmjs.org/pull-stream/-/pull-stream-2.21.0.tgz
npm http GET https://registry.npmjs.org/level-iterator-stream/-/level-iterator-stream-1.3.1.tgz
npm http GET https://registry.npmjs.org/prr/-/prr-1.0.1.tgz
npm http 304 https://registry.npmjs.org/semver
npm http 200 https://registry.npmjs.org/typewiselite/-/typewiselite-1.0.0.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/level-errors
npm http 304 https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/level-errors/-/level-errors-1.0.4.tgz
npm http 200 https://registry.npmjs.org/bytewise
npm http GET https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/jsprim
npm http GET https://registry.npmjs.org/bytewise/-/bytewise-1.1.0.tgz
npm http GET https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/commander
npm http GET https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/level-codec
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/level-codec/-/level-codec-6.1.0.tgz
npm http 200 https://registry.npmjs.org/humble-localstorage/-/humble-localstorage-1.4.2.tgz
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 200 https://registry.npmjs.org/level-iterator-stream/-/level-iterator-stream-1.3.1.tgz
npm http 200 https://registry.npmjs.org/prr/-/prr-1.0.1.tgz
npm http GET https://registry.npmjs.org/write-stream/-/write-stream-0.4.3.tgz
npm http 304 https://registry.npmjs.org/assert-plus
npm http 200 https://registry.npmjs.org/level-errors/-/level-errors-1.0.4.tgz
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/bytewise/-/bytewise-1.1.0.tgz
npm http 200 https://registry.npmjs.org/ltgt/-/ltgt-2.1.2.tgz
npm http 200 https://registry.npmjs.org/pull-stream/-/pull-stream-2.21.0.tgz
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/write-stream/-/write-stream-0.4.3.tgz
npm http 200 https://registry.npmjs.org/level-codec/-/level-codec-6.1.0.tgz
npm http 200 https://registry.npmjs.org/deferred-leveldown/-/deferred-leveldown-1.2.1.tgz
npm http GET https://registry.npmjs.org/couchdb-objects
npm http GET https://registry.npmjs.org/couchdb-eval
npm http GET https://registry.npmjs.org/pouchdb-promise
npm http GET https://registry.npmjs.org/random-uuid-v4
npm http GET https://registry.npmjs.org/pouchdb-plugin-error
npm http GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http GET https://registry.npmjs.org/promise-nodify
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/iconv-lite
npm http GET https://registry.npmjs.org/get-folder-size
npm http GET https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/compressible
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/on-headers
npm http GET https://registry.npmjs.org/promise-nodify
npm http GET https://registry.npmjs.org/pouchdb-route
npm http GET https://registry.npmjs.org/secure-random
npm http GET https://registry.npmjs.org/crypto-lite
npm http GET https://registry.npmjs.org/pouchdb-req-http-query
npm http GET https://registry.npmjs.org/pouchdb-system-db
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/pouchdb-req-http-query
npm http GET https://registry.npmjs.org/couchdb-resp-completer
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/couchdb-render
npm http GET https://registry.npmjs.org/equals
npm http GET https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/json-schema
npm http GET https://registry.npmjs.org/verror
npm http GET https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http GET https://registry.npmjs.org/errno
npm http GET https://registry.npmjs.org/readable-stream/-/readable-stream-0.0.4.tgz
npm http GET https://registry.npmjs.org/stream-counter
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/bytewise-core
npm http GET https://registry.npmjs.org/typewise
npm http GET https://registry.npmjs.org/graceful-readlink
npm http GET https://registry.npmjs.org/has-localstorage
npm http GET https://registry.npmjs.org/localstorage-memory
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/tiny-queue/-/tiny-queue-0.2.1.tgz
npm http 200 https://registry.npmjs.org/couchdb-eval
npm http 200 https://registry.npmjs.org/couchdb-objects
npm http 200 https://registry.npmjs.org/pouchdb-promise
npm http GET https://registry.npmjs.org/couchdb-eval/-/couchdb-eval-1.0.6.tgz
npm http GET https://registry.npmjs.org/couchdb-objects/-/couchdb-objects-1.0.7.tgz
npm http GET https://registry.npmjs.org/pull-core
npm http GET https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-0.0.0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-plugin-error
npm http 200 https://registry.npmjs.org/readable-stream/-/readable-stream-0.0.4.tgz
npm http 200 https://registry.npmjs.org/random-uuid-v4
npm http GET https://registry.npmjs.org/pouchdb-plugin-error/-/pouchdb-plugin-error-1.0.1.tgz
npm http GET https://registry.npmjs.org/random-uuid-v4/-/random-uuid-v4-0.0.4.tgz
npm http 304 https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie/-/cookie-0.2.3.tgz
npm http 304 https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/dashdash
npm http 200 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 200 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 200 https://registry.npmjs.org/pouchdb-plugin-error/-/pouchdb-plugin-error-1.0.1.tgz
npm http GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper/-/pouchdb-bulkdocs-wrapper-1.0.2.tgz
npm http GET https://registry.npmjs.org/promise-nodify/-/promise-nodify-1.0.2.tgz
npm http GET https://registry.npmjs.org/bytes/-/bytes-1.0.0.tgz
npm http GET https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.8.tgz
npm http GET https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/compressible
npm http 200 https://registry.npmjs.org/random-uuid-v4/-/random-uuid-v4-0.0.4.tgz
npm http 304 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/tiny-queue/-/tiny-queue-0.2.1.tgz
npm http GET https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/couchdb-objects/-/couchdb-objects-1.0.7.tgz
npm http 304 https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/couchdb-eval/-/couchdb-eval-1.0.6.tgz
npm http 200 https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-0.0.0.tgz
npm http 304 https://registry.npmjs.org/on-headers
npm http 200 https://registry.npmjs.org/cookie/-/cookie-0.2.3.tgz
npm http 200 https://registry.npmjs.org/promise-nodify
npm http 200 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper/-/pouchdb-bulkdocs-wrapper-1.0.2.tgz
npm http 200 https://registry.npmjs.org/bytes/-/bytes-1.0.0.tgz
npm http 200 https://registry.npmjs.org/promise-nodify/-/promise-nodify-1.0.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb-route
npm http 200 https://registry.npmjs.org/get-folder-size
npm http 200 https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.8.tgz
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/pouchdb-route/-/pouchdb-route-1.0.3.tgz
npm http 200 https://registry.npmjs.org/pouchdb-req-http-query
npm http GET https://registry.npmjs.org/get-folder-size/-/get-folder-size-0.1.1.tgz
npm http GET https://registry.npmjs.org/is-empty
npm http GET https://registry.npmjs.org/pouchdb-req-http-query/-/pouchdb-req-http-query-1.0.3.tgz
npm http 200 https://registry.npmjs.org/crypto-lite
npm http GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/secure-random
npm http GET https://registry.npmjs.org/crypto-lite/-/crypto-lite-0.0.4.tgz
npm http GET https://registry.npmjs.org/secure-random/-/secure-random-1.1.1.tgz
npm http GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/prr/-/prr-0.0.0.tgz
npm http GET https://registry.npmjs.org/deferred-leveldown/-/deferred-leveldown-0.2.0.tgz
npm http GET https://registry.npmjs.org/bl/-/bl-0.8.2.tgz
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/couchdb-render
npm http GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/pouchdb-system-db
npm http GET https://registry.npmjs.org/color-convert
npm http GET https://registry.npmjs.org/couchdb-render/-/couchdb-render-1.0.1.tgz
npm http GET https://registry.npmjs.org/pouchdb-system-db/-/pouchdb-system-db-1.0.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-req-http-query
npm http 200 https://registry.npmjs.org/get-folder-size/-/get-folder-size-0.1.1.tgz
npm http 200 https://registry.npmjs.org/equals
npm http GET https://registry.npmjs.org/equals/-/equals-1.0.1.tgz
npm http GET https://registry.npmjs.org/minimist/-/minimist-0.1.0.tgz
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 200 https://registry.npmjs.org/secure-random/-/secure-random-1.1.1.tgz
npm http 304 https://registry.npmjs.org/verror
npm http 200 https://registry.npmjs.org/stream-counter
npm http 200 https://registry.npmjs.org/errno
npm http 200 https://registry.npmjs.org/prr/-/prr-0.0.0.tgz
npm http 200 https://registry.npmjs.org/deferred-leveldown/-/deferred-leveldown-0.2.0.tgz
npm http GET https://registry.npmjs.org/stream-counter/-/stream-counter-0.2.0.tgz
npm http GET https://registry.npmjs.org/errno/-/errno-0.1.4.tgz
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/couchdb-render/-/couchdb-render-1.0.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-route/-/pouchdb-route-1.0.3.tgz
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http 200 https://registry.npmjs.org/crypto-lite/-/crypto-lite-0.0.4.tgz
npm http GET https://registry.npmjs.org/pouchdb-changeslike-wrapper/-/pouchdb-changeslike-wrapper-1.0.1.tgz
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http 200 https://registry.npmjs.org/pouchdb-system-db/-/pouchdb-system-db-1.0.4.tgz
npm http 200 https://registry.npmjs.org/equals/-/equals-1.0.1.tgz
npm http 200 https://registry.npmjs.org/bytewise-core
npm http 200 https://registry.npmjs.org/minimist/-/minimist-0.1.0.tgz
npm http GET https://registry.npmjs.org/bytewise-core/-/bytewise-core-1.2.3.tgz
npm http 200 https://registry.npmjs.org/stream-counter/-/stream-counter-0.2.0.tgz
npm http 200 https://registry.npmjs.org/errno/-/errno-0.1.4.tgz
npm http 200 https://registry.npmjs.org/has-localstorage
npm http 200 https://registry.npmjs.org/pouchdb-changeslike-wrapper/-/pouchdb-changeslike-wrapper-1.0.1.tgz
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/bytewise-core/-/bytewise-core-1.2.3.tgz
npm http 200 https://registry.npmjs.org/typewise
npm http 200 https://registry.npmjs.org/couchdb-resp-completer
npm http 200 https://registry.npmjs.org/localstorage-memory
npm http GET https://registry.npmjs.org/has-localstorage/-/has-localstorage-1.0.1.tgz
npm http GET https://registry.npmjs.org/lie/-/lie-2.9.1.tgz
npm http GET https://registry.npmjs.org/typewise/-/typewise-1.0.3.tgz
npm http GET https://registry.npmjs.org/couchdb-resp-completer/-/couchdb-resp-completer-1.0.3.tgz
npm http GET https://registry.npmjs.org/localstorage-memory/-/localstorage-memory-1.0.2.tgz
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/bl/-/bl-0.8.2.tgz
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/generate-function
npm http 200 https://registry.npmjs.org/pull-core
npm http GET https://registry.npmjs.org/jkroso-type
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/couchdb-resp-completer/-/couchdb-resp-completer-1.0.3.tgz
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/pull-core/-/pull-core-1.0.0.tgz
npm http 304 https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/pouchdb-req-http-query/-/pouchdb-req-http-query-1.0.3.tgz
npm http 304 https://registry.npmjs.org/color-convert
npm http GET https://registry.npmjs.org/lie/-/lie-2.7.7.tgz
npm http GET https://registry.npmjs.org/bluebird/-/bluebird-1.2.4.tgz
npm http 200 https://registry.npmjs.org/is-empty
npm http 200 https://registry.npmjs.org/jkroso-type
npm http 200 https://registry.npmjs.org/localstorage-memory/-/localstorage-memory-1.0.2.tgz
npm http 200 https://registry.npmjs.org/typewise/-/typewise-1.0.3.tgz
npm http 200 https://registry.npmjs.org/has-localstorage/-/has-localstorage-1.0.1.tgz
npm http 200 https://registry.npmjs.org/pull-core/-/pull-core-1.0.0.tgz
npm http GET https://registry.npmjs.org/is-empty/-/is-empty-0.0.1.tgz
npm http GET https://registry.npmjs.org/jkroso-type/-/jkroso-type-1.1.1.tgz
npm http 200 https://registry.npmjs.org/lie/-/lie-2.7.7.tgz
npm http 200 https://registry.npmjs.org/lie/-/lie-2.9.1.tgz
npm http 200 https://registry.npmjs.org/bluebird/-/bluebird-1.2.4.tgz
npm http 200 https://registry.npmjs.org/is-empty/-/is-empty-0.0.1.tgz
npm http 200 https://registry.npmjs.org/jkroso-type/-/jkroso-type-1.1.1.tgz
npm http GET https://registry.npmjs.org/xmlhttprequest-cookie
npm http GET https://registry.npmjs.org/abstract-leveldown
npm http GET https://registry.npmjs.org/typewise-core
npm http 200 https://registry.npmjs.org/xmlhttprequest-cookie
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http GET https://registry.npmjs.org/xmlhttprequest-cookie/-/xmlhttprequest-cookie-0.9.4.tgz
npm http GET https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-0.12.4.tgz
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/typewise-core
npm http 200 https://registry.npmjs.org/typewise-core
npm http GET https://registry.npmjs.org/typewise-core/-/typewise-core-1.2.0.tgz
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/xmlhttprequest-cookie/-/xmlhttprequest-cookie-0.9.4.tgz
npm http 304 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-0.12.4.tgz
npm http 200 https://registry.npmjs.org/typewise-core
npm http GET https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/typewise-core/-/typewise-core-1.2.0.tgz
npm http GET https://registry.npmjs.org/xmlhttprequest
npm http 304 https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/immediate/-/immediate-3.2.2.tgz
npm http 200 https://registry.npmjs.org/xmlhttprequest
npm http GET https://registry.npmjs.org/xmlhttprequest/-/xmlhttprequest-1.8.0.tgz
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/inline-process-browser
npm http 200 https://registry.npmjs.org/immediate/-/immediate-3.2.2.tgz
npm http 200 https://registry.npmjs.org/xmlhttprequest/-/xmlhttprequest-1.8.0.tgz
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.2.3.tgz
npm http 200 https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.2.3.tgz
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/jshint
npm http GET https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http GET https://registry.npmjs.org/pouchdb-extend
npm http GET https://registry.npmjs.org/pouchdb-upsert
npm http GET https://registry.npmjs.org/pouchdb-collate
npm http GET https://registry.npmjs.org/spark-md5
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/argsarray
npm http GET https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/foreach
npm http 200 https://registry.npmjs.org/pouchdb-extend
npm http GET https://registry.npmjs.org/pouchdb-extend/-/pouchdb-extend-0.1.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/spark-md5
npm http GET https://registry.npmjs.org/spark-md5/-/spark-md5-0.0.5.tgz
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http 304 https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/pouchdb-abstract-mapreduce/-/pouchdb-abstract-mapreduce-0.2.2.tgz
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/pouchdb-upsert
npm http 304 https://registry.npmjs.org/argsarray
npm http GET https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-1.1.3.tgz
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/pouchdb-extend/-/pouchdb-extend-0.1.2.tgz
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/jshint
npm http GET https://registry.npmjs.org/jshint/-/jshint-2.9.1.tgz
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/spark-md5/-/spark-md5-0.0.5.tgz
npm http 304 https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-1.1.3.tgz
npm http 200 https://registry.npmjs.org/pouchdb-abstract-mapreduce/-/pouchdb-abstract-mapreduce-0.2.2.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/jshint/-/jshint-2.9.1.tgz
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/cli
npm http GET https://registry.npmjs.org/exit
npm http GET https://registry.npmjs.org/htmlparser2
npm http GET https://registry.npmjs.org/console-browserify
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/shelljs
npm http GET https://registry.npmjs.org/strip-json-comments
npm http GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/console-browserify
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/shelljs
npm http 304 https://registry.npmjs.org/lodash
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/lodash/-/lodash-3.7.0.tgz
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http GET https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/exit
npm http GET https://registry.npmjs.org/exit/-/exit-0.1.2.tgz
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/htmlparser2
npm http 200 https://registry.npmjs.org/lodash/-/lodash-3.7.0.tgz
npm http GET https://registry.npmjs.org/htmlparser2/-/htmlparser2-3.8.3.tgz
npm http 200 https://registry.npmjs.org/exit/-/exit-0.1.2.tgz
npm http 200 https://registry.npmjs.org/cli
npm http GET https://registry.npmjs.org/cli/-/cli-0.6.6.tgz
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/htmlparser2/-/htmlparser2-3.8.3.tgz
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/cli/-/cli-0.6.6.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/domhandler
npm http GET https://registry.npmjs.org/domutils
npm http GET https://registry.npmjs.org/domelementtype
npm http GET https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/domelementtype
npm http 200 https://registry.npmjs.org/entities
npm http GET https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/domelementtype/-/domelementtype-1.3.0.tgz
npm http GET https://registry.npmjs.org/entities/-/entities-1.0.0.tgz
npm http 200 https://registry.npmjs.org/domutils
npm http GET https://registry.npmjs.org/domutils/-/domutils-1.5.1.tgz
npm http GET https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/sigmund
npm http 200 https://registry.npmjs.org/domhandler
npm http GET https://registry.npmjs.org/domhandler/-/domhandler-2.3.0.tgz
npm http 200 https://registry.npmjs.org/domelementtype/-/domelementtype-1.3.0.tgz
npm http 200 https://registry.npmjs.org/domutils/-/domutils-1.5.1.tgz
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/lru-cache/-/lru-cache-2.7.3.tgz
npm http 200 https://registry.npmjs.org/entities/-/entities-1.0.0.tgz
npm http 304 https://registry.npmjs.org/sigmund
npm http 200 https://registry.npmjs.org/domhandler/-/domhandler-2.3.0.tgz
npm http GET https://registry.npmjs.org/dom-serializer
npm http 200 https://registry.npmjs.org/lru-cache/-/lru-cache-2.7.3.tgz
npm http 200 https://registry.npmjs.org/dom-serializer
npm http GET https://registry.npmjs.org/dom-serializer/-/dom-serializer-0.1.0.tgz
npm http 200 https://registry.npmjs.org/dom-serializer/-/dom-serializer-0.1.0.tgz
npm http GET https://registry.npmjs.org/domelementtype/-/domelementtype-1.1.3.tgz
npm http GET https://registry.npmjs.org/entities/-/entities-1.1.1.tgz
npm http 200 https://registry.npmjs.org/domelementtype/-/domelementtype-1.1.3.tgz
npm http 200 https://registry.npmjs.org/entities/-/entities-1.1.1.tgz
ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
npm ERR! Test failed.  See above for more details.
npm ERR! not ok code 0

```

Error: Command failed: npm http GET https://registry.npmjs.org/cordova
npm http 200 https://registry.npmjs.org/cordova
npm http GET https://registry.npmjs.org/cordova/-/cordova-6.0.0.tgz
npm http 200 https://registry.npmjs.org/cordova/-/cordova-6.0.0.tgz
npm http GET https://registry.npmjs.org/ansi
npm http GET https://registry.npmjs.org/update-notifier
npm http GET https://registry.npmjs.org/cordova-lib
npm http GET https://registry.npmjs.org/q
npm http GET https://registry.npmjs.org/nopt
npm http GET https://registry.npmjs.org/underscore
npm http 200 https://registry.npmjs.org/ansi
npm http 200 https://registry.npmjs.org/nopt
npm http GET https://registry.npmjs.org/nopt/-/nopt-3.0.1.tgz
npm http GET https://registry.npmjs.org/ansi/-/ansi-0.3.1.tgz
npm http 200 https://registry.npmjs.org/cordova-lib
npm http GET https://registry.npmjs.org/cordova-lib/-/cordova-lib-6.0.0.tgz
npm http 200 https://registry.npmjs.org/underscore
npm http GET https://registry.npmjs.org/underscore/-/underscore-1.7.0.tgz
npm http 200 https://registry.npmjs.org/q
npm http GET https://registry.npmjs.org/q/-/q-1.0.1.tgz
npm http 200 https://registry.npmjs.org/nopt/-/nopt-3.0.1.tgz
npm http 200 https://registry.npmjs.org/cordova-lib/-/cordova-lib-6.0.0.tgz
npm http 200 https://registry.npmjs.org/ansi/-/ansi-0.3.1.tgz
npm http 200 https://registry.npmjs.org/underscore/-/underscore-1.7.0.tgz
npm http 200 https://registry.npmjs.org/q/-/q-1.0.1.tgz
npm http 200 https://registry.npmjs.org/update-notifier
npm http GET https://registry.npmjs.org/update-notifier/-/update-notifier-0.5.0.tgz
npm http 200 https://registry.npmjs.org/update-notifier/-/update-notifier-0.5.0.tgz
npm http GET https://registry.npmjs.org/is-npm
npm http GET https://registry.npmjs.org/latest-version
npm http GET https://registry.npmjs.org/repeating
npm http GET https://registry.npmjs.org/semver-diff
npm http GET https://registry.npmjs.org/string-length
npm http GET https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/configstore
npm http GET https://registry.npmjs.org/abbrev
npm http 200 https://registry.npmjs.org/is-npm
npm http 200 https://registry.npmjs.org/semver-diff
npm http 200 https://registry.npmjs.org/string-length
npm http 200 https://registry.npmjs.org/repeating
npm http GET https://registry.npmjs.org/is-npm/-/is-npm-1.0.0.tgz
npm http GET https://registry.npmjs.org/semver-diff/-/semver-diff-2.1.0.tgz
npm http GET https://registry.npmjs.org/string-length/-/string-length-1.0.1.tgz
npm http GET https://registry.npmjs.org/repeating/-/repeating-1.1.3.tgz
npm http 200 https://registry.npmjs.org/abbrev
npm http 200 https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/chalk/-/chalk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/semver-diff/-/semver-diff-2.1.0.tgz
npm http 200 https://registry.npmjs.org/is-npm/-/is-npm-1.0.0.tgz
npm http 200 https://registry.npmjs.org/string-length/-/string-length-1.0.1.tgz
npm http 200 https://registry.npmjs.org/configstore
npm http 200 https://registry.npmjs.org/repeating/-/repeating-1.1.3.tgz
npm http GET https://registry.npmjs.org/configstore/-/configstore-1.4.0.tgz
npm http 200 https://registry.npmjs.org/latest-version
npm http GET https://registry.npmjs.org/latest-version/-/latest-version-1.0.1.tgz
npm http 200 https://registry.npmjs.org/chalk/-/chalk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/configstore/-/configstore-1.4.0.tgz
npm http 200 https://registry.npmjs.org/latest-version/-/latest-version-1.0.1.tgz
npm http GET https://registry.npmjs.org/object-assign
npm http GET https://registry.npmjs.org/os-tmpdir
npm http GET https://registry.npmjs.org/uuid
npm http GET https://registry.npmjs.org/write-file-atomic
npm http GET https://registry.npmjs.org/xdg-basedir
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/osenv
npm http GET https://registry.npmjs.org/mkdirp
npm http GET https://registry.npmjs.org/graceful-fs
npm http GET https://registry.npmjs.org/semver
npm http GET https://registry.npmjs.org/package-json
npm http GET https://registry.npmjs.org/is-finite
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/write-file-atomic
npm http 200 https://registry.npmjs.org/xdg-basedir
npm http 200 https://registry.npmjs.org/os-tmpdir
npm http GET https://registry.npmjs.org/xdg-basedir/-/xdg-basedir-2.0.0.tgz
npm http GET https://registry.npmjs.org/os-tmpdir/-/os-tmpdir-1.0.1.tgz
npm http GET https://registry.npmjs.org/write-file-atomic/-/write-file-atomic-1.1.4.tgz
npm http GET https://registry.npmjs.org/cordova-app-hello-world
npm http GET https://registry.npmjs.org/aliasify
npm http GET https://registry.npmjs.org/cordova-js
npm http GET https://registry.npmjs.org/cordova-serve
npm http GET https://registry.npmjs.org/dep-graph
npm http GET https://registry.npmjs.org/opener
npm http GET https://registry.npmjs.org/init-package-json
npm http GET https://registry.npmjs.org/npmconf
npm http GET https://registry.npmjs.org/semver
npm http GET https://registry.npmjs.org/properties-parser
npm http GET https://registry.npmjs.org/request
npm http GET https://registry.npmjs.org/tar
npm http GET https://registry.npmjs.org/shelljs
npm http GET https://registry.npmjs.org/valid-identifier
npm http GET https://registry.npmjs.org/npm
npm http GET https://registry.npmjs.org/xcode
npm http 200 https://registry.npmjs.org/object-assign
npm http 200 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/osenv
npm http GET https://registry.npmjs.org/nopt/-/nopt-3.0.6.tgz
npm http GET https://registry.npmjs.org/osenv/-/osenv-0.1.3.tgz
npm http GET https://registry.npmjs.org/strip-ansi/-/strip-ansi-3.0.1.tgz
npm http GET https://registry.npmjs.org/object-assign/-/object-assign-4.0.1.tgz
npm http 200 https://registry.npmjs.org/mkdirp
npm http 200 https://registry.npmjs.org/uuid
npm http GET https://registry.npmjs.org/uuid/-/uuid-2.0.1.tgz
npm http 200 https://registry.npmjs.org/is-finite
npm http GET https://registry.npmjs.org/is-finite/-/is-finite-1.0.1.tgz
npm http 200 https://registry.npmjs.org/package-json
npm http 200 https://registry.npmjs.org/graceful-fs
npm http GET https://registry.npmjs.org/package-json/-/package-json-1.2.0.tgz
npm http GET https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.3.tgz
npm http 200 https://registry.npmjs.org/ansi-styles
npm http 200 https://registry.npmjs.org/write-file-atomic/-/write-file-atomic-1.1.4.tgz
npm http GET https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.0.tgz
npm http 200 https://registry.npmjs.org/os-tmpdir/-/os-tmpdir-1.0.1.tgz
npm http 200 https://registry.npmjs.org/semver
npm http 200 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/osenv/-/osenv-0.1.3.tgz
npm http 200 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/strip-ansi/-/strip-ansi-3.0.1.tgz
npm http 200 https://registry.npmjs.org/object-assign/-/object-assign-4.0.1.tgz
npm http GET https://registry.npmjs.org/semver/-/semver-5.1.0.tgz
npm http GET https://registry.npmjs.org/has-ansi/-/has-ansi-2.0.0.tgz
npm http GET https://registry.npmjs.org/supports-color/-/supports-color-2.0.0.tgz
npm http 200 https://registry.npmjs.org/cordova-app-hello-world
npm http GET https://registry.npmjs.org/cordova-app-hello-world/-/cordova-app-hello-world-3.10.0.tgz
npm http GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/package-json/-/package-json-1.2.0.tgz
npm http 200 https://registry.npmjs.org/uuid/-/uuid-2.0.1.tgz
npm http 200 https://registry.npmjs.org/is-finite/-/is-finite-1.0.1.tgz
npm http 200 https://registry.npmjs.org/cordova-serve
npm http GET https://registry.npmjs.org/cordova-serve/-/cordova-serve-1.0.0.tgz
npm http 304 https://registry.npmjs.org/dep-graph
npm http GET https://registry.npmjs.org/got
npm http GET https://registry.npmjs.org/registry-url
npm http GET https://registry.npmjs.org/number-is-nan
npm http 200 https://registry.npmjs.org/ansi-styles/-/ansi-styles-2.2.0.tgz
npm http 200 https://registry.npmjs.org/graceful-fs/-/graceful-fs-4.1.3.tgz
npm http 200 https://registry.npmjs.org/aliasify
npm http 200 https://registry.npmjs.org/opener
npm http GET https://registry.npmjs.org/opener/-/opener-1.4.1.tgz
npm http GET https://registry.npmjs.org/aliasify/-/aliasify-1.9.0.tgz
npm http 200 https://registry.npmjs.org/semver/-/semver-5.1.0.tgz
npm http 200 https://registry.npmjs.org/supports-color/-/supports-color-2.0.0.tgz
npm http 200 https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.5.tgz
npm http 200 https://registry.npmjs.org/cordova-js
npm http 200 https://registry.npmjs.org/cordova-app-hello-world/-/cordova-app-hello-world-3.10.0.tgz
npm http GET https://registry.npmjs.org/cordova-js/-/cordova-js-4.1.3.tgz
npm http 200 https://registry.npmjs.org/xdg-basedir/-/xdg-basedir-2.0.0.tgz
npm http 200 https://registry.npmjs.org/has-ansi/-/has-ansi-2.0.0.tgz
npm http 200 https://registry.npmjs.org/semver
npm http GET https://registry.npmjs.org/os-homedir
npm http GET https://registry.npmjs.org/imurmurhash
npm http GET https://registry.npmjs.org/slide
npm http GET https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/opener/-/opener-1.4.1.tgz
npm http 200 https://registry.npmjs.org/cordova-serve/-/cordova-serve-1.0.0.tgz
npm http 200 https://registry.npmjs.org/aliasify/-/aliasify-1.9.0.tgz
npm http 200 https://registry.npmjs.org/init-package-json
npm http GET https://registry.npmjs.org/init-package-json/-/init-package-json-1.9.3.tgz
npm http 200 https://registry.npmjs.org/cordova-js/-/cordova-js-4.1.3.tgz
npm http 200 https://registry.npmjs.org/properties-parser
npm http GET https://registry.npmjs.org/properties-parser/-/properties-parser-0.2.3.tgz
npm http 200 https://registry.npmjs.org/nopt/-/nopt-3.0.6.tgz
npm http 200 https://registry.npmjs.org/npmconf
npm http 304 https://registry.npmjs.org/valid-identifier
npm http 200 https://registry.npmjs.org/properties-parser/-/properties-parser-0.2.3.tgz
npm WARN deprecated npmconf@2.1.2: this package has been reintegrated into npm and is now out of date with respect to npm
npm http 200 https://registry.npmjs.org/escape-string-regexp/-/escape-string-regexp-1.0.5.tgz
npm http GET https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/tar
npm http GET https://registry.npmjs.org/tar/-/tar-1.0.2.tgz
npm http 200 https://registry.npmjs.org/init-package-json/-/init-package-json-1.9.3.tgz
npm http 200 https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/ansi-regex/-/ansi-regex-2.0.0.tgz
npm http 200 https://registry.npmjs.org/xcode
npm http GET https://registry.npmjs.org/xcode/-/xcode-0.8.0.tgz
npm http 200 https://registry.npmjs.org/registry-url
npm http GET https://registry.npmjs.org/registry-url/-/registry-url-3.0.3.tgz
npm http 200 https://registry.npmjs.org/number-is-nan
npm http 200 https://registry.npmjs.org/shelljs
npm http GET https://registry.npmjs.org/number-is-nan/-/number-is-nan-1.0.0.tgz
npm http GET https://registry.npmjs.org/shelljs/-/shelljs-0.3.0.tgz
npm http 200 https://registry.npmjs.org/os-homedir
npm http GET https://registry.npmjs.org/os-homedir/-/os-homedir-1.0.1.tgz
npm http 200 https://registry.npmjs.org/slide
npm http GET https://registry.npmjs.org/slide/-/slide-1.1.6.tgz
npm http 200 https://registry.npmjs.org/got
npm http GET https://registry.npmjs.org/got/-/got-3.3.1.tgz
npm http 200 https://registry.npmjs.org/request
npm http GET https://registry.npmjs.org/request/-/request-2.47.0.tgz
npm http 200 https://registry.npmjs.org/minimist
npm http GET https://registry.npmjs.org/minimist/-/minimist-0.0.8.tgz
npm http 200 https://registry.npmjs.org/color-convert
npm http GET https://registry.npmjs.org/color-convert/-/color-convert-1.0.0.tgz
npm http 200 https://registry.npmjs.org/imurmurhash
npm http GET https://registry.npmjs.org/imurmurhash/-/imurmurhash-0.1.4.tgz
npm http 200 https://registry.npmjs.org/registry-url/-/registry-url-3.0.3.tgz
npm http 200 https://registry.npmjs.org/ansi-regex/-/ansi-regex-2.0.0.tgz
npm http 200 https://registry.npmjs.org/tar/-/tar-1.0.2.tgz
npm http 200 https://registry.npmjs.org/number-is-nan/-/number-is-nan-1.0.0.tgz
npm http 200 https://registry.npmjs.org/xcode/-/xcode-0.8.0.tgz
npm http 200 https://registry.npmjs.org/os-homedir/-/os-homedir-1.0.1.tgz
npm http 200 https://registry.npmjs.org/shelljs/-/shelljs-0.3.0.tgz
npm http 200 https://registry.npmjs.org/slide/-/slide-1.1.6.tgz
npm http 200 https://registry.npmjs.org/got/-/got-3.3.1.tgz
npm http 200 https://registry.npmjs.org/request/-/request-2.47.0.tgz
npm http GET https://registry.npmjs.org/rc
npm http GET https://registry.npmjs.org/is-redirect
npm http GET https://registry.npmjs.org/is-stream
npm http GET https://registry.npmjs.org/lowercase-keys
npm http GET https://registry.npmjs.org/nested-error-stacks
npm http GET https://registry.npmjs.org/prepend-http
npm http GET https://registry.npmjs.org/read-all-stream
npm http GET https://registry.npmjs.org/timed-out
npm http GET https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/infinity-agent
npm http GET https://registry.npmjs.org/object-assign/-/object-assign-3.0.0.tgz
npm http 200 https://registry.npmjs.org/color-convert/-/color-convert-1.0.0.tgz
npm http 200 https://registry.npmjs.org/minimist/-/minimist-0.0.8.tgz
npm http 200 https://registry.npmjs.org/imurmurhash/-/imurmurhash-0.1.4.tgz
npm http 200 https://registry.npmjs.org/object-assign/-/object-assign-3.0.0.tgz
npm http 200 https://registry.npmjs.org/is-stream
npm http 200 https://registry.npmjs.org/is-redirect
npm http GET https://registry.npmjs.org/is-redirect/-/is-redirect-1.0.0.tgz
npm http GET https://registry.npmjs.org/is-stream/-/is-stream-1.0.1.tgz
npm http 200 https://registry.npmjs.org/lowercase-keys
npm http GET https://registry.npmjs.org/lowercase-keys/-/lowercase-keys-1.0.0.tgz
npm http 200 https://registry.npmjs.org/prepend-http
npm http 200 https://registry.npmjs.org/nested-error-stacks
npm http GET https://registry.npmjs.org/prepend-http/-/prepend-http-1.0.3.tgz
npm http GET https://registry.npmjs.org/nested-error-stacks/-/nested-error-stacks-1.0.2.tgz
npm http 200 https://registry.npmjs.org/timed-out
npm http GET https://registry.npmjs.org/timed-out/-/timed-out-2.0.0.tgz
npm http 200 https://registry.npmjs.org/read-all-stream
npm http 200 https://registry.npmjs.org/infinity-agent
npm http GET https://registry.npmjs.org/read-all-stream/-/read-all-stream-3.1.0.tgz
npm http GET https://registry.npmjs.org/infinity-agent/-/infinity-agent-2.0.3.tgz
npm http 200 https://registry.npmjs.org/rc
npm http 200 https://registry.npmjs.org/is-stream/-/is-stream-1.0.1.tgz
npm http GET https://registry.npmjs.org/rc/-/rc-1.1.6.tgz
npm http 200 https://registry.npmjs.org/prepend-http/-/prepend-http-1.0.3.tgz
npm http 200 https://registry.npmjs.org/nested-error-stacks/-/nested-error-stacks-1.0.2.tgz
npm http 200 https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/duplexify/-/duplexify-3.4.3.tgz
npm http 200 https://registry.npmjs.org/timed-out/-/timed-out-2.0.0.tgz
npm http 200 https://registry.npmjs.org/read-all-stream/-/read-all-stream-3.1.0.tgz
npm http 200 https://registry.npmjs.org/infinity-agent/-/infinity-agent-2.0.3.tgz
npm http 200 https://registry.npmjs.org/rc/-/rc-1.1.6.tgz
npm http GET https://registry.npmjs.org/ini
npm http GET https://registry.npmjs.org/strip-json-comments
npm http GET https://registry.npmjs.org/deep-extend
npm http GET https://registry.npmjs.org/minimist/-/minimist-1.2.0.tgz
npm http 200 https://registry.npmjs.org/duplexify/-/duplexify-3.4.3.tgz
npm http 200 https://registry.npmjs.org/lowercase-keys/-/lowercase-keys-1.0.0.tgz
npm http 200 https://registry.npmjs.org/minimist/-/minimist-1.2.0.tgz
npm http 200 https://registry.npmjs.org/strip-json-comments
npm http 200 https://registry.npmjs.org/ini
npm http GET https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-1.0.4.tgz
npm http 200 https://registry.npmjs.org/is-redirect/-/is-redirect-1.0.0.tgz
npm http 200 https://registry.npmjs.org/strip-json-comments/-/strip-json-comments-1.0.4.tgz
npm http GET https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/end-of-stream
npm http GET https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/deep-extend
npm http GET https://registry.npmjs.org/deep-extend/-/deep-extend-0.4.1.tgz
npm http 200 https://registry.npmjs.org/end-of-stream
npm http GET https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.0.0.tgz
npm http 200 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.0.tgz
npm http 200 https://registry.npmjs.org/deep-extend/-/deep-extend-0.4.1.tgz
npm WARN engine deep-extend@0.4.1: wanted: {"node":">=0.12.0","iojs":">=1.0.0"} (current: {"node":"v0.10.40","npm":"1.4.14"})
npm http 200 https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/readable-stream/-/readable-stream-2.0.5.tgz
npm http 200 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/end-of-stream/-/end-of-stream-1.0.0.tgz
npm http 200 https://registry.npmjs.org/pinkie-promise/-/pinkie-promise-2.0.0.tgz
npm http 200 https://registry.npmjs.org/readable-stream/-/readable-stream-2.0.5.tgz
npm http GET https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/once/-/once-1.3.3.tgz
npm http 200 https://registry.npmjs.org/pinkie
npm http 200 https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/isarray/-/isarray-0.0.1.tgz
npm http GET https://registry.npmjs.org/pinkie/-/pinkie-2.0.4.tgz
npm http GET https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.6.tgz
npm http 200 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz
npm http GET https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz
npm http 200 https://registry.npmjs.org/once/-/once-1.3.3.tgz
npm http GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/util-deprecate/-/util-deprecate-1.0.2.tgz
npm http 200 https://registry.npmjs.org/isarray/-/isarray-0.0.1.tgz
npm http 200 https://registry.npmjs.org/pinkie/-/pinkie-2.0.4.tgz
npm http 200 https://registry.npmjs.org/process-nextick-args/-/process-nextick-args-1.0.6.tgz
npm http 200 https://registry.npmjs.org/core-util-is/-/core-util-is-1.0.2.tgz
npm http 200 https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/npm
npm http GET https://registry.npmjs.org/npm/-/npm-2.14.21.tgz
npm http 200 https://registry.npmjs.org/npm/-/npm-2.14.21.tgz
npm WARN engine cordova-serve@1.0.0: wanted: {"node":">= 0.12.0","npm":">= 2.5.1"} (current: {"node":"v0.10.40","npm":"1.4.14"})
npm http GET https://registry.npmjs.org/browserify-transform-tools
npm http GET https://registry.npmjs.org/compression
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/q
npm http GET https://registry.npmjs.org/underscore
npm http GET https://registry.npmjs.org/abbrev
npm http GET https://registry.npmjs.org/promzard
npm http GET https://registry.npmjs.org/read
npm http GET https://registry.npmjs.org/read-package-json
npm http GET https://registry.npmjs.org/validate-npm-package-license
npm http GET https://registry.npmjs.org/validate-npm-package-name
npm http GET https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/npm-package-arg
npm http GET https://registry.npmjs.org/pegjs
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/ini
npm http GET https://registry.npmjs.org/mkdirp
npm http GET https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/osenv
npm http GET https://registry.npmjs.org/uid-number
npm http GET https://registry.npmjs.org/config-chain
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/block-stream
npm http GET https://registry.npmjs.org/fstream
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/q
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/underscore
npm http 304 https://registry.npmjs.org/abbrev
npm http 200 https://registry.npmjs.org/promzard
npm http 200 https://registry.npmjs.org/browserify-transform-tools
npm http 200 https://registry.npmjs.org/read
npm http GET https://registry.npmjs.org/browserify-transform-tools/-/browserify-transform-tools-1.5.3.tgz
npm http GET https://registry.npmjs.org/read/-/read-1.0.7.tgz
npm http 200 https://registry.npmjs.org/compression
npm http 304 https://registry.npmjs.org/validate-npm-package-name
npm http 200 https://registry.npmjs.org/validate-npm-package-license
npm http GET https://registry.npmjs.org/browserify
npm http GET https://registry.npmjs.org/compression/-/compression-1.6.1.tgz
npm http GET https://registry.npmjs.org/validate-npm-package-license/-/validate-npm-package-license-3.0.1.tgz
npm http 200 https://registry.npmjs.org/read-package-json
npm http GET https://registry.npmjs.org/read-package-json/-/read-package-json-2.0.3.tgz
npm http 200 https://registry.npmjs.org/pegjs
npm http GET https://registry.npmjs.org/pegjs/-/pegjs-0.6.2.tgz
npm http 304 https://registry.npmjs.org/ini
npm http 200 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/compression/-/compression-1.6.1.tgz
npm http 200 https://registry.npmjs.org/validate-npm-package-license/-/validate-npm-package-license-3.0.1.tgz
npm http 200 https://registry.npmjs.org/read/-/read-1.0.7.tgz
npm http GET https://registry.npmjs.org/node-uuid/-/node-uuid-1.3.3.tgz
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/browserify-transform-tools/-/browserify-transform-tools-1.5.3.tgz
npm http 200 https://registry.npmjs.org/npm-package-arg
npm http 200 https://registry.npmjs.org/pegjs/-/pegjs-0.6.2.tgz
npm http 304 https://registry.npmjs.org/osenv
npm http 304 https://registry.npmjs.org/uid-number
npm http 200 https://registry.npmjs.org/read-package-json/-/read-package-json-2.0.3.tgz
npm http GET https://registry.npmjs.org/npm-package-arg/-/npm-package-arg-4.1.0.tgz
npm http 304 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/glob/-/glob-6.0.4.tgz
npm http 200 https://registry.npmjs.org/node-uuid/-/node-uuid-1.3.3.tgz
npm http 200 https://registry.npmjs.org/config-chain
npm http GET https://registry.npmjs.org/config-chain/-/config-chain-1.1.10.tgz
npm http 200 https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/forever-agent
npm http 200 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/bl/-/bl-0.9.5.tgz
npm http 200 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/glob/-/glob-6.0.4.tgz
npm http GET https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.2.tgz
npm http 200 https://registry.npmjs.org/npm-package-arg/-/npm-package-arg-4.1.0.tgz
npm http 200 https://registry.npmjs.org/config-chain/-/config-chain-1.1.10.tgz
npm http 200 https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.7.tgz
npm http 200 https://registry.npmjs.org/bl/-/bl-0.9.5.tgz
npm http 200 https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/mute-stream
npm http GET https://registry.npmjs.org/spdx-expression-parse
npm http GET https://registry.npmjs.org/spdx-correct
npm http 200 https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/builtins
npm http GET https://registry.npmjs.org/os-homedir
npm http GET https://registry.npmjs.org/os-tmpdir
npm http GET https://registry.npmjs.org/hosted-git-info
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/proto-list
npm http 200 https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/minimist
npm http GET https://registry.npmjs.org/json-parse-helpfulerror
npm http GET https://registry.npmjs.org/normalize-package-data
npm http GET https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/aws-sign2
npm http 200 https://registry.npmjs.org/oauth-sign
npm http 200 https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.2.1.tgz
npm http 200 https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.7.tgz
npm http 200 https://registry.npmjs.org/tunnel-agent/-/tunnel-agent-0.4.2.tgz
npm http 200 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/block-stream
npm http GET https://registry.npmjs.org/stringstream/-/stringstream-0.0.5.tgz
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/fstream
npm http GET https://registry.npmjs.org/fstream/-/fstream-1.0.8.tgz
npm http 200 https://registry.npmjs.org/stringstream/-/stringstream-0.0.5.tgz
npm http 200 https://registry.npmjs.org/falafel
npm http 200 https://registry.npmjs.org/tough-cookie/-/tough-cookie-2.2.1.tgz
npm http GET https://registry.npmjs.org/falafel/-/falafel-1.2.0.tgz
npm http 200 https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/hawk/-/hawk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/mute-stream
npm http GET https://registry.npmjs.org/mute-stream/-/mute-stream-0.0.6.tgz
npm http 200 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/spdx-correct
npm http 200 https://registry.npmjs.org/spdx-expression-parse
npm http GET https://registry.npmjs.org/spdx-correct/-/spdx-correct-1.0.2.tgz
npm http GET https://registry.npmjs.org/spdx-expression-parse/-/spdx-expression-parse-1.0.2.tgz
npm http 200 https://registry.npmjs.org/fstream/-/fstream-1.0.8.tgz
npm http 200 https://registry.npmjs.org/falafel/-/falafel-1.2.0.tgz
npm http 200 https://registry.npmjs.org/builtins
npm http 304 https://registry.npmjs.org/os-homedir
npm http GET https://registry.npmjs.org/builtins/-/builtins-0.0.7.tgz
npm http 200 https://registry.npmjs.org/spdx-correct/-/spdx-correct-1.0.2.tgz
npm http 304 https://registry.npmjs.org/hosted-git-info
npm http 304 https://registry.npmjs.org/os-tmpdir
npm http 200 https://registry.npmjs.org/spdx-expression-parse/-/spdx-expression-parse-1.0.2.tgz
npm http 200 https://registry.npmjs.org/inflight
npm http 200 https://registry.npmjs.org/hawk/-/hawk-1.1.1.tgz
npm http 200 https://registry.npmjs.org/mute-stream/-/mute-stream-0.0.6.tgz
npm http 200 https://registry.npmjs.org/builtins/-/builtins-0.0.7.tgz
npm http 304 https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/spdx-license-ids
npm http 304 https://registry.npmjs.org/proto-list
npm http GET https://registry.npmjs.org/spdx-exceptions
npm http GET https://registry.npmjs.org/spdx-license-ids
npm http 304 https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/json-parse-helpfulerror
npm http 200 https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/minimatch/-/minimatch-3.0.0.tgz
npm http GET https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/foreach/-/foreach-2.0.5.tgz
npm http 304 https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/minimatch/-/minimatch-3.0.0.tgz
npm http 200 https://registry.npmjs.org/normalize-package-data
npm http 200 https://registry.npmjs.org/foreach/-/foreach-2.0.5.tgz
npm http GET https://registry.npmjs.org/normalize-package-data/-/normalize-package-data-2.3.5.tgz
npm http 200 https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/ctype
npm http GET https://registry.npmjs.org/object-keys/-/object-keys-1.0.9.tgz
npm http 200 https://registry.npmjs.org/spdx-license-ids
npm http 200 https://registry.npmjs.org/spdx-exceptions
npm http GET https://registry.npmjs.org/spdx-license-ids/-/spdx-license-ids-1.2.0.tgz
npm http GET https://registry.npmjs.org/spdx-exceptions/-/spdx-exceptions-1.0.4.tgz
npm http GET https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 200 https://registry.npmjs.org/spdx-license-ids
npm http GET https://registry.npmjs.org/sntp
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/spdx-license-ids/-/spdx-license-ids-1.2.0.tgz
npm http 200 https://registry.npmjs.org/spdx-exceptions/-/spdx-exceptions-1.0.4.tgz
npm http 200 https://registry.npmjs.org/object-keys/-/object-keys-1.0.9.tgz
npm http 200 https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/express/-/express-4.13.4.tgz
npm http 304 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/normalize-package-data/-/normalize-package-data-2.3.5.tgz
npm http 200 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/rimraf/-/rimraf-2.5.2.tgz
npm http GET https://registry.npmjs.org/asn1/-/asn1-0.1.11.tgz
npm http GET https://registry.npmjs.org/jju
npm http 200 https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.3.tgz
npm http GET https://registry.npmjs.org/is-builtin-module
npm http 200 https://registry.npmjs.org/ctype
npm http GET https://registry.npmjs.org/ctype/-/ctype-0.5.3.tgz
npm http 200 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/rimraf/-/rimraf-2.5.2.tgz
npm http 200 https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/glob/-/glob-7.0.0.tgz
npm http 200 https://registry.npmjs.org/express/-/express-4.13.4.tgz
npm http 200 https://registry.npmjs.org/asn1/-/asn1-0.1.11.tgz
npm http 200 https://registry.npmjs.org/brace-expansion/-/brace-expansion-1.1.3.tgz
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/compressible
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/on-headers
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/concat-map
npm http GET https://registry.npmjs.org/balanced-match
npm http 200 https://registry.npmjs.org/ctype/-/ctype-0.5.3.tgz
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/jju
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/qs/-/qs-4.0.0.tgz
npm http GET https://registry.npmjs.org/jju/-/jju-1.3.0.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/is-builtin-module
npm http 304 https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/is-builtin-module/-/is-builtin-module-1.0.0.tgz
npm http 200 https://registry.npmjs.org/glob/-/glob-7.0.0.tgz
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/is-builtin-module/-/is-builtin-module-1.0.0.tgz
npm http 200 https://registry.npmjs.org/jju/-/jju-1.3.0.tgz
npm http GET https://registry.npmjs.org/builtin-modules
npm http 200 https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/accepts/-/accepts-1.3.1.tgz
npm http 200 https://registry.npmjs.org/bytes
npm http 200 https://registry.npmjs.org/qs/-/qs-4.0.0.tgz
npm http GET https://registry.npmjs.org/bytes/-/bytes-2.2.0.tgz
npm http 200 https://registry.npmjs.org/on-headers
npm http 200 https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/on-headers/-/on-headers-1.0.1.tgz
npm http GET https://registry.npmjs.org/vary/-/vary-1.1.0.tgz
npm http 200 https://registry.npmjs.org/concat-map
npm http GET https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz
npm http 200 https://registry.npmjs.org/compressible
npm http 200 https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/compressible/-/compressible-2.0.7.tgz
npm http GET https://registry.npmjs.org/debug/-/debug-2.2.0.tgz
npm http 200 https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.3.0.tgz
npm http 200 https://registry.npmjs.org/accepts/-/accepts-1.3.1.tgz
npm http 200 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/array-flatten/-/array-flatten-1.1.1.tgz
npm http GET https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.1.tgz
npm http 200 https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/content-type/-/content-type-1.0.1.tgz
npm http 200 https://registry.npmjs.org/compressible/-/compressible-2.0.7.tgz
npm http 200 https://registry.npmjs.org/vary/-/vary-1.1.0.tgz
npm http 200 https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.0.6.tgz
npm http 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.3.0.tgz
npm http 200 https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz
npm http 200 https://registry.npmjs.org/debug/-/debug-2.2.0.tgz
npm http 200 https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/accepts/-/accepts-1.2.13.tgz
npm http 200 https://registry.npmjs.org/cookie
npm http 200 https://registry.npmjs.org/array-flatten/-/array-flatten-1.1.1.tgz
npm http 200 https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.1.tgz
npm http GET https://registry.npmjs.org/cookie/-/cookie-0.1.5.tgz
npm http 200 https://registry.npmjs.org/cookie-signature/-/cookie-signature-1.0.6.tgz
npm http 200 https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/etag/-/etag-1.7.0.tgz
npm http 200 https://registry.npmjs.org/fresh
npm http 200 https://registry.npmjs.org/depd
npm http 200 https://registry.npmjs.org/escape-html/-/escape-html-1.0.3.tgz
npm http 200 https://registry.npmjs.org/content-type/-/content-type-1.0.1.tgz
npm http GET https://registry.npmjs.org/fresh/-/fresh-0.3.0.tgz
npm http GET https://registry.npmjs.org/depd/-/depd-1.1.0.tgz
npm http 200 https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.1.tgz
npm http 200 https://registry.npmjs.org/bytes/-/bytes-2.2.0.tgz
npm http 200 https://registry.npmjs.org/accepts/-/accepts-1.2.13.tgz
npm http 200 https://registry.npmjs.org/cookie/-/cookie-0.1.5.tgz
npm http 200 https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.1.tgz
npm http 200 https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/methods/-/methods-1.1.2.tgz
npm http 200 https://registry.npmjs.org/fresh/-/fresh-0.3.0.tgz
npm http 200 https://registry.npmjs.org/depd/-/depd-1.1.0.tgz
npm http 200 https://registry.npmjs.org/etag/-/etag-1.7.0.tgz
npm http 200 https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/parseurl/-/parseurl-1.3.1.tgz
npm http 200 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.1.tgz
npm http 200 https://registry.npmjs.org/methods/-/methods-1.1.2.tgz
npm http 200 https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.1.tgz
npm http GET https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz
npm http 200 https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/range-parser/-/range-parser-1.0.3.tgz
npm http 200 https://registry.npmjs.org/parseurl/-/parseurl-1.3.1.tgz
npm http 200 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/on-headers/-/on-headers-1.0.1.tgz
npm http GET https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.0.10.tgz
npm http 200 https://registry.npmjs.org/concat-map/-/concat-map-0.0.1.tgz
npm http GET https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/mime-types/-/mime-types-2.1.10.tgz
npm http GET https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/on-finished/-/on-finished-2.3.0.tgz
npm http GET https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-0.1.7.tgz
npm http 200 https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/utils-merge/-/utils-merge-1.0.0.tgz
npm http 200 https://registry.npmjs.org/proxy-addr/-/proxy-addr-1.0.10.tgz
npm http 200 https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/type-is/-/type-is-1.6.12.tgz
npm http 200 https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/mime-types/-/mime-types-2.1.10.tgz
npm http GET https://registry.npmjs.org/vary/-/vary-1.0.1.tgz
npm http 304 https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/builtin-modules
npm http 200 https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/send/-/send-0.13.1.tgz
npm http GET https://registry.npmjs.org/serve-static/-/serve-static-1.10.2.tgz
npm http GET https://registry.npmjs.org/builtin-modules/-/builtin-modules-1.1.1.tgz
npm http 200 https://registry.npmjs.org/path-to-regexp/-/path-to-regexp-0.1.7.tgz
npm http 200 https://registry.npmjs.org/utils-merge/-/utils-merge-1.0.0.tgz
npm http 200 https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/ms/-/ms-0.7.1.tgz
npm http 200 https://registry.npmjs.org/send/-/send-0.13.1.tgz
npm http 200 https://registry.npmjs.org/serve-static/-/serve-static-1.10.2.tgz
npm http 200 https://registry.npmjs.org/type-is/-/type-is-1.6.12.tgz
npm http 200 https://registry.npmjs.org/vary/-/vary-1.0.1.tgz
npm http 200 https://registry.npmjs.org/ms/-/ms-0.7.1.tgz
npm http 200 https://registry.npmjs.org/builtin-modules/-/builtin-modules-1.1.1.tgz
npm http 200 https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/negotiator/-/negotiator-0.6.0.tgz
npm http 200 https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/mime-db/-/mime-db-1.22.0.tgz
npm http 200 https://registry.npmjs.org/negotiator/-/negotiator-0.6.0.tgz
npm http 200 https://registry.npmjs.org/range-parser/-/range-parser-1.0.3.tgz
npm http 200 https://registry.npmjs.org/mime-db/-/mime-db-1.22.0.tgz
npm http 200 https://registry.npmjs.org/browserify
npm http GET https://registry.npmjs.org/browserify/-/browserify-10.1.3.tgz
npm http GET https://registry.npmjs.org/unpipe
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/negotiator/-/negotiator-0.5.3.tgz
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/browserify/-/browserify-10.1.3.tgz
npm http 200 https://registry.npmjs.org/media-typer
npm http 200 https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz
npm http GET https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz
npm http 200 https://registry.npmjs.org/negotiator/-/negotiator-0.5.3.tgz
npm http 200 https://registry.npmjs.org/unpipe
npm http GET https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz
npm http 200 https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/destroy/-/destroy-1.0.4.tgz
npm http 200 https://registry.npmjs.org/ipaddr.js
npm http 200 https://registry.npmjs.org/ee-first/-/ee-first-1.1.1.tgz
npm http GET https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.0.5.tgz
npm http 200 https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/forwarded/-/forwarded-0.1.0.tgz
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/statuses
npm http 200 https://registry.npmjs.org/unpipe/-/unpipe-1.0.0.tgz
npm http GET https://registry.npmjs.org/statuses/-/statuses-1.2.1.tgz
npm http 200 https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/http-errors/-/http-errors-1.3.1.tgz
npm http 200 https://registry.npmjs.org/destroy/-/destroy-1.0.4.tgz
npm http 200 https://registry.npmjs.org/ipaddr.js/-/ipaddr.js-1.0.5.tgz
npm http 200 https://registry.npmjs.org/forwarded/-/forwarded-0.1.0.tgz
npm http 200 https://registry.npmjs.org/http-errors/-/http-errors-1.3.1.tgz
npm http 200 https://registry.npmjs.org/statuses/-/statuses-1.2.1.tgz
npm http 200 https://registry.npmjs.org/media-typer/-/media-typer-0.3.0.tgz
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/browser-pack
npm http GET https://registry.npmjs.org/browser-resolve
npm http GET https://registry.npmjs.org/browserify-zlib
npm http GET https://registry.npmjs.org/buffer
npm http GET https://registry.npmjs.org/builtins
npm http GET https://registry.npmjs.org/commondir
npm http GET https://registry.npmjs.org/concat-stream
npm http GET https://registry.npmjs.org/console-browserify
npm http GET https://registry.npmjs.org/constants-browserify
npm http GET https://registry.npmjs.org/crypto-browserify
npm http GET https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/defined
npm http GET https://registry.npmjs.org/deps-sort
npm http GET https://registry.npmjs.org/domain-browser
npm http GET https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/duplexer2
npm http GET https://registry.npmjs.org/events
npm http GET https://registry.npmjs.org/has
npm http GET https://registry.npmjs.org/htmlescape
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/http-browserify
npm http GET https://registry.npmjs.org/https-browserify
npm http GET https://registry.npmjs.org/insert-module-globals
npm http GET https://registry.npmjs.org/labeled-stream-splicer
npm http GET https://registry.npmjs.org/os-browserify
npm http GET https://registry.npmjs.org/module-deps
npm http GET https://registry.npmjs.org/path-browserify
npm http GET https://registry.npmjs.org/parents
npm http GET https://registry.npmjs.org/process
npm http GET https://registry.npmjs.org/punycode
npm http GET https://registry.npmjs.org/querystring-es3
npm http GET https://registry.npmjs.org/read-only-stream
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/shallow-copy
npm http GET https://registry.npmjs.org/shasum
npm http GET https://registry.npmjs.org/resolve
npm http GET https://registry.npmjs.org/shell-quote
npm http GET https://registry.npmjs.org/stream-browserify
npm http GET https://registry.npmjs.org/subarg
npm http GET https://registry.npmjs.org/syntax-error
npm http GET https://registry.npmjs.org/timers-browserify
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/tty-browserify
npm http GET https://registry.npmjs.org/url
npm http GET https://registry.npmjs.org/util
npm http GET https://registry.npmjs.org/vm-browserify
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/assert
npm http GET https://registry.npmjs.org/JSONStream
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/builtins
npm http 200 https://registry.npmjs.org/commondir
npm http GET https://registry.npmjs.org/commondir/-/commondir-0.0.1.tgz
npm http 304 https://registry.npmjs.org/browserify-zlib
npm http 304 https://registry.npmjs.org/console-browserify
npm http 200 https://registry.npmjs.org/browser-pack
npm http 304 https://registry.npmjs.org/constants-browserify
npm http 200 https://registry.npmjs.org/concat-stream
npm http 200 https://registry.npmjs.org/browser-resolve
npm http 200 https://registry.npmjs.org/buffer
npm http 304 https://registry.npmjs.org/defined
npm http GET https://registry.npmjs.org/browser-resolve/-/browser-resolve-1.11.1.tgz
npm http GET https://registry.npmjs.org/buffer/-/buffer-3.6.0.tgz
npm http 200 https://registry.npmjs.org/domain-browser
npm http 304 https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/deps-sort
npm http 200 https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/domain-browser/-/domain-browser-1.1.7.tgz
npm http GET https://registry.npmjs.org/glob/-/glob-4.5.3.tgz
npm http GET https://registry.npmjs.org/deep-equal/-/deep-equal-1.0.1.tgz
npm http 200 https://registry.npmjs.org/crypto-browserify
npm http GET https://registry.npmjs.org/crypto-browserify/-/crypto-browserify-3.11.0.tgz
npm http 200 https://registry.npmjs.org/duplexer2
npm http 200 https://registry.npmjs.org/events
npm http 200 https://registry.npmjs.org/has
npm http 200 https://registry.npmjs.org/htmlescape
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/http-browserify
npm http 200 https://registry.npmjs.org/labeled-stream-splicer
npm http 200 https://registry.npmjs.org/commondir/-/commondir-0.0.1.tgz
npm http 200 https://registry.npmjs.org/browser-resolve/-/browser-resolve-1.11.1.tgz
npm http 304 https://registry.npmjs.org/path-browserify
npm http 200 https://registry.npmjs.org/deep-equal/-/deep-equal-1.0.1.tgz
npm http 304 https://registry.npmjs.org/parents
npm http 200 https://registry.npmjs.org/os-browserify
npm http 200 https://registry.npmjs.org/glob/-/glob-4.5.3.tgz
npm http 200 https://registry.npmjs.org/crypto-browserify/-/crypto-browserify-3.11.0.tgz
npm http 200 https://registry.npmjs.org/buffer/-/buffer-3.6.0.tgz
npm http 200 https://registry.npmjs.org/process
npm http 200 https://registry.npmjs.org/punycode
npm http GET https://registry.npmjs.org/punycode/-/punycode-1.4.0.tgz
npm http GET https://registry.npmjs.org/process/-/process-0.11.2.tgz
npm http 200 https://registry.npmjs.org/insert-module-globals
npm http 200 https://registry.npmjs.org/read-only-stream
npm http GET https://registry.npmjs.org/insert-module-globals/-/insert-module-globals-6.6.3.tgz
npm http 304 https://registry.npmjs.org/querystring-es3
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/shallow-copy
npm http 200 https://registry.npmjs.org/shasum
npm http 200 https://registry.npmjs.org/domain-browser/-/domain-browser-1.1.7.tgz
npm http GET https://registry.npmjs.org/shasum/-/shasum-1.0.2.tgz
npm http 304 https://registry.npmjs.org/shell-quote
npm http 200 https://registry.npmjs.org/https-browserify
npm http GET https://registry.npmjs.org/https-browserify/-/https-browserify-0.0.1.tgz
npm http 200 https://registry.npmjs.org/process/-/process-0.11.2.tgz
npm http 200 https://registry.npmjs.org/module-deps
npm http 200 https://registry.npmjs.org/syntax-error
npm http 304 https://registry.npmjs.org/subarg
npm http GET https://registry.npmjs.org/module-deps/-/module-deps-3.9.1.tgz
npm http GET https://registry.npmjs.org/syntax-error/-/syntax-error-1.1.5.tgz
npm http 200 https://registry.npmjs.org/shasum/-/shasum-1.0.2.tgz
npm http 304 https://registry.npmjs.org/tty-browserify
npm http 200 https://registry.npmjs.org/insert-module-globals/-/insert-module-globals-6.6.3.tgz
npm http 200 https://registry.npmjs.org/url
npm http 200 https://registry.npmjs.org/timers-browserify
npm http 200 https://registry.npmjs.org/syntax-error/-/syntax-error-1.1.5.tgz
npm http GET https://registry.npmjs.org/timers-browserify/-/timers-browserify-1.4.2.tgz
npm http 200 https://registry.npmjs.org/punycode/-/punycode-1.4.0.tgz
npm http 304 https://registry.npmjs.org/vm-browserify
npm http 200 https://registry.npmjs.org/util
npm http 200 https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/assert
npm http 200 https://registry.npmjs.org/resolve
npm http 200 https://registry.npmjs.org/stream-browserify
npm http GET https://registry.npmjs.org/resolve/-/resolve-1.1.7.tgz
npm http 200 https://registry.npmjs.org/module-deps/-/module-deps-3.9.1.tgz
npm http 200 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/timers-browserify/-/timers-browserify-1.4.2.tgz
npm http 200 https://registry.npmjs.org/https-browserify/-/https-browserify-0.0.1.tgz
npm http 200 https://registry.npmjs.org/resolve/-/resolve-1.1.7.tgz
npm http 200 https://registry.npmjs.org/JSONStream
npm http GET https://registry.npmjs.org/JSONStream/-/JSONStream-1.0.7.tgz
npm http 200 https://registry.npmjs.org/JSONStream/-/JSONStream-1.0.7.tgz
npm http GET https://registry.npmjs.org/typedarray
npm http GET https://registry.npmjs.org/function-bind
npm http GET https://registry.npmjs.org/minimist
npm http GET https://registry.npmjs.org/json-stable-stringify
npm http GET https://registry.npmjs.org/sha.js
npm http GET https://registry.npmjs.org/path-platform
npm http GET https://registry.npmjs.org/readable-wrap
npm http GET https://registry.npmjs.org/date-now
npm http GET https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/typedarray
npm http GET https://registry.npmjs.org/stream-splicer
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/path-platform
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/Base64
npm http GET https://registry.npmjs.org/querystring
npm http 304 https://registry.npmjs.org/readable-wrap
npm http 200 https://registry.npmjs.org/function-bind
npm http GET https://registry.npmjs.org/umd
npm http GET https://registry.npmjs.org/combine-source-map
npm http 304 https://registry.npmjs.org/minimist
npm http GET https://registry.npmjs.org/function-bind/-/function-bind-1.1.0.tgz
npm http GET https://registry.npmjs.org/browserify-cipher
npm http GET https://registry.npmjs.org/browserify-sign
npm http GET https://registry.npmjs.org/create-ecdh
npm http GET https://registry.npmjs.org/create-hash
npm http GET https://registry.npmjs.org/create-hmac
npm http GET https://registry.npmjs.org/diffie-hellman
npm http GET https://registry.npmjs.org/pbkdf2
npm http GET https://registry.npmjs.org/public-encrypt
npm http GET https://registry.npmjs.org/randombytes
npm http GET https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/indexof
npm http GET https://registry.npmjs.org/is-buffer
npm http GET https://registry.npmjs.org/combine-source-map
npm http GET https://registry.npmjs.org/lexical-scope
npm http 200 https://registry.npmjs.org/json-stable-stringify
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/pako
npm http GET https://registry.npmjs.org/base64-js
npm http GET https://registry.npmjs.org/ieee754
npm http GET https://registry.npmjs.org/isarray/-/isarray-1.0.0.tgz
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/acorn
npm http 200 https://registry.npmjs.org/stream-splicer
npm http 304 https://registry.npmjs.org/Base64
npm http GET https://registry.npmjs.org/acorn/-/acorn-2.7.0.tgz
npm http 200 https://registry.npmjs.org/function-bind/-/function-bind-1.1.0.tgz
npm http GET https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/querystring
npm http 304 https://registry.npmjs.org/umd
npm http 304 https://registry.npmjs.org/combine-source-map
npm http GET https://registry.npmjs.org/querystring/-/querystring-0.2.0.tgz
npm http GET https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/inline-source-map
npm http GET https://registry.npmjs.org/convert-source-map
npm http GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/create-hash
npm http 200 https://registry.npmjs.org/create-ecdh
npm http 200 https://registry.npmjs.org/sha.js
npm http GET https://registry.npmjs.org/create-hash/-/create-hash-1.1.2.tgz
npm http GET https://registry.npmjs.org/create-ecdh/-/create-ecdh-4.0.0.tgz
npm http GET https://registry.npmjs.org/sha.js/-/sha.js-2.4.5.tgz
npm http 200 https://registry.npmjs.org/isarray/-/isarray-1.0.0.tgz
npm http 200 https://registry.npmjs.org/pbkdf2
npm http 200 https://registry.npmjs.org/create-hmac
npm http 200 https://registry.npmjs.org/browserify-sign
npm http GET https://registry.npmjs.org/create-hmac/-/create-hmac-1.1.4.tgz
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/jsonparse
npm http GET https://registry.npmjs.org/browserify-sign/-/browserify-sign-4.0.0.tgz
npm http GET https://registry.npmjs.org/stream-combiner2
npm http GET https://registry.npmjs.org/detective
npm http 200 https://registry.npmjs.org/diffie-hellman
npm http 200 https://registry.npmjs.org/sha.js/-/sha.js-2.4.5.tgz
npm http 200 https://registry.npmjs.org/public-encrypt
npm http GET https://registry.npmjs.org/diffie-hellman/-/diffie-hellman-5.0.2.tgz
npm http 200 https://registry.npmjs.org/acorn/-/acorn-2.7.0.tgz
npm http GET https://registry.npmjs.org/public-encrypt/-/public-encrypt-4.0.0.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/querystring/-/querystring-0.2.0.tgz
npm http 200 https://registry.npmjs.org/randombytes
npm http GET https://registry.npmjs.org/randombytes/-/randombytes-2.0.2.tgz
npm http 200 https://registry.npmjs.org/browserify-cipher
npm http GET https://registry.npmjs.org/browserify-cipher/-/browserify-cipher-1.0.0.tgz
npm http GET https://registry.npmjs.org/jsonify
npm http 304 https://registry.npmjs.org/combine-source-map
npm http 200 https://registry.npmjs.org/create-hmac/-/create-hmac-1.1.4.tgz
npm http 200 https://registry.npmjs.org/is-buffer
npm http GET https://registry.npmjs.org/is-buffer/-/is-buffer-1.1.2.tgz
npm http 200 https://registry.npmjs.org/browserify-sign/-/browserify-sign-4.0.0.tgz
npm http 304 https://registry.npmjs.org/ieee754
npm http 200 https://registry.npmjs.org/diffie-hellman/-/diffie-hellman-5.0.2.tgz
npm http 304 https://registry.npmjs.org/wrappy
npm http 200 https://registry.npmjs.org/create-hash/-/create-hash-1.1.2.tgz
npm http 200 https://registry.npmjs.org/base64-js
npm http 304 https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/pako
npm http GET https://registry.npmjs.org/base64-js/-/base64-js-0.0.8.tgz
npm http GET https://registry.npmjs.org/pako/-/pako-0.2.8.tgz
npm http 200 https://registry.npmjs.org/randombytes/-/randombytes-2.0.2.tgz
npm http GET https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/concat-map
npm http 200 https://registry.npmjs.org/is-buffer/-/is-buffer-1.1.2.tgz
npm http 304 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/public-encrypt/-/public-encrypt-4.0.0.tgz
npm http 200 https://registry.npmjs.org/browserify-cipher/-/browserify-cipher-1.0.0.tgz
npm http 200 https://registry.npmjs.org/base64-js/-/base64-js-0.0.8.tgz
npm http 200 https://registry.npmjs.org/lexical-scope
npm http GET https://registry.npmjs.org/lexical-scope/-/lexical-scope-1.2.0.tgz
npm http 200 https://registry.npmjs.org/jsonparse
npm http 200 https://registry.npmjs.org/pako/-/pako-0.2.8.tgz
npm http GET https://registry.npmjs.org/jsonparse/-/jsonparse-1.2.0.tgz
npm http 200 https://registry.npmjs.org/stream-combiner2
npm http 304 https://registry.npmjs.org/jsonify
npm http 200 https://registry.npmjs.org/detective
npm http GET https://registry.npmjs.org/detective/-/detective-4.3.1.tgz
npm http 200 https://registry.npmjs.org/create-ecdh/-/create-ecdh-4.0.0.tgz
npm http 304 https://registry.npmjs.org/balanced-match
npm http 200 https://registry.npmjs.org/inline-source-map
npm http 304 https://registry.npmjs.org/concat-map
npm http 200 https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/evp_bytestokey
npm http GET https://registry.npmjs.org/browserify-des
npm http GET https://registry.npmjs.org/bn.js
npm http GET https://registry.npmjs.org/elliptic
npm http GET https://registry.npmjs.org/browserify-aes
npm http GET https://registry.npmjs.org/cipher-base
npm http GET https://registry.npmjs.org/ripemd160
npm http 200 https://registry.npmjs.org/convert-source-map
npm http GET https://registry.npmjs.org/miller-rabin
npm http GET https://registry.npmjs.org/bn.js
npm http GET https://registry.npmjs.org/browserify-rsa
npm http GET https://registry.npmjs.org/parse-asn1
npm http 200 https://registry.npmjs.org/jsonparse/-/jsonparse-1.2.0.tgz
npm http 200 https://registry.npmjs.org/detective/-/detective-4.3.1.tgz
npm http 200 https://registry.npmjs.org/evp_bytestokey
npm http 200 https://registry.npmjs.org/lexical-scope/-/lexical-scope-1.2.0.tgz
npm http 200 https://registry.npmjs.org/browserify-des
npm http GET https://registry.npmjs.org/browserify-des/-/browserify-des-1.0.0.tgz
npm http GET https://registry.npmjs.org/evp_bytestokey/-/evp_bytestokey-1.0.0.tgz
npm http 200 https://registry.npmjs.org/cipher-base
npm http 304 https://registry.npmjs.org/ripemd160
npm http GET https://registry.npmjs.org/cipher-base/-/cipher-base-1.0.2.tgz
npm http GET https://registry.npmjs.org/lodash.memoize
npm http 200 https://registry.npmjs.org/miller-rabin
npm http GET https://registry.npmjs.org/convert-source-map/-/convert-source-map-1.1.3.tgz
npm http GET https://registry.npmjs.org/miller-rabin/-/miller-rabin-4.0.0.tgz
npm http 200 https://registry.npmjs.org/browserify-aes
npm http GET https://registry.npmjs.org/browserify-aes/-/browserify-aes-1.0.6.tgz
npm http 200 https://registry.npmjs.org/bn.js
npm http 200 https://registry.npmjs.org/browserify-des/-/browserify-des-1.0.0.tgz
npm http 200 https://registry.npmjs.org/evp_bytestokey/-/evp_bytestokey-1.0.0.tgz
npm http 200 https://registry.npmjs.org/browserify-rsa
npm http GET https://registry.npmjs.org/bn.js/-/bn.js-4.10.5.tgz
npm http GET https://registry.npmjs.org/browserify-rsa/-/browserify-rsa-4.0.1.tgz
npm http 200 https://registry.npmjs.org/bn.js
npm http 200 https://registry.npmjs.org/elliptic
npm http 200 https://registry.npmjs.org/browserify-aes/-/browserify-aes-1.0.6.tgz
npm http GET https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/elliptic/-/elliptic-6.2.3.tgz
npm http 200 https://registry.npmjs.org/cipher-base/-/cipher-base-1.0.2.tgz
npm http GET https://registry.npmjs.org/des.js
npm http GET https://registry.npmjs.org/astw
npm http 200 https://registry.npmjs.org/parse-asn1
npm http 200 https://registry.npmjs.org/lodash.memoize
npm http 200 https://registry.npmjs.org/browserify-rsa/-/browserify-rsa-4.0.1.tgz
npm http GET https://registry.npmjs.org/parse-asn1/-/parse-asn1-5.0.0.tgz
npm http GET https://registry.npmjs.org/buffer-xor
npm http 200 https://registry.npmjs.org/miller-rabin/-/miller-rabin-4.0.0.tgz
npm http 200 https://registry.npmjs.org/convert-source-map/-/convert-source-map-1.1.3.tgz
npm http 200 https://registry.npmjs.org/bn.js/-/bn.js-4.10.5.tgz
npm http 200 https://registry.npmjs.org/elliptic/-/elliptic-6.2.3.tgz
npm http GET https://registry.npmjs.org/brorand
npm http 200 https://registry.npmjs.org/parse-asn1/-/parse-asn1-5.0.0.tgz
npm http 200 https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/hash.js
npm http GET https://registry.npmjs.org/asn1.js
npm http 200 https://registry.npmjs.org/des.js
npm http GET https://registry.npmjs.org/des.js/-/des.js-1.0.0.tgz
npm http 304 https://registry.npmjs.org/astw
npm http 304 https://registry.npmjs.org/brorand
npm http 200 https://registry.npmjs.org/buffer-xor
npm http GET https://registry.npmjs.org/buffer-xor/-/buffer-xor-1.0.3.tgz
npm http 200 https://registry.npmjs.org/asn1.js
npm http GET https://registry.npmjs.org/asn1.js/-/asn1.js-4.5.1.tgz
npm http 304 https://registry.npmjs.org/hash.js
npm http 200 https://registry.npmjs.org/des.js/-/des.js-1.0.0.tgz
npm http 200 https://registry.npmjs.org/buffer-xor/-/buffer-xor-1.0.3.tgz
npm http GET https://registry.npmjs.org/minimalistic-assert
npm http 200 https://registry.npmjs.org/asn1.js/-/asn1.js-4.5.1.tgz
npm http 304 https://registry.npmjs.org/minimalistic-assert
npm WARN package.json thali-test-server@0.0.1 No repository field.
npm http GET https://registry.npmjs.org/fs-extra-promise
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/socket.io
npm http GET https://registry.npmjs.org/winston
npm http GET https://registry.npmjs.org/socket.io-client
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/tape
npm http 200 https://registry.npmjs.org/fs-extra-promise
npm http GET https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.1.tgz
npm http 304 https://registry.npmjs.org/express
npm http 200 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/lie/-/lie-3.0.2.tgz
npm http 200 https://registry.npmjs.org/socket.io-client
npm http GET https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.5.tgz
npm http 200 https://registry.npmjs.org/winston
npm http GET https://registry.npmjs.org/winston/-/winston-2.2.0.tgz
npm http 200 https://registry.npmjs.org/fs-extra-promise/-/fs-extra-promise-0.2.1.tgz
npm http 200 https://registry.npmjs.org/winston/-/winston-2.2.0.tgz
npm http 200 https://registry.npmjs.org/socket.io-client/-/socket.io-client-1.4.5.tgz
npm http 200 https://registry.npmjs.org/tape
npm http GET https://registry.npmjs.org/tape/-/tape-1.1.1.tgz
npm http 200 https://registry.npmjs.org/lie/-/lie-3.0.2.tgz
npm http 200 https://registry.npmjs.org/tape/-/tape-1.1.1.tgz
npm http 200 https://registry.npmjs.org/socket.io
npm http GET https://registry.npmjs.org/socket.io/-/socket.io-1.4.5.tgz
npm http 200 https://registry.npmjs.org/socket.io/-/socket.io-1.4.5.tgz
npm http GET https://registry.npmjs.org/fs-extra
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/engine.io
npm http GET https://registry.npmjs.org/socket.io-parser
npm http GET https://registry.npmjs.org/socket.io-adapter
npm http GET https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/jsonify
npm http GET https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/defined
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/engine.io-client
npm http GET https://registry.npmjs.org/component-bind
npm http GET https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/object-component
npm http GET https://registry.npmjs.org/parseuri
npm http GET https://registry.npmjs.org/to-array
npm http GET https://registry.npmjs.org/backo2
npm http GET https://registry.npmjs.org/indexof
npm http GET https://registry.npmjs.org/colors
npm http GET https://registry.npmjs.org/cycle
npm http GET https://registry.npmjs.org/eyes
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/pkginfo
npm http GET https://registry.npmjs.org/stack-trace
npm http GET https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/socket.io-parser
npm http GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.6.tgz
npm http 200 https://registry.npmjs.org/socket.io-adapter
npm http GET https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.4.0.tgz
npm http 200 https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.7.tgz
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/es3ify/-/es3ify-0.1.4.tgz
npm http 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.6.tgz
npm http 200 https://registry.npmjs.org/fs-extra
npm http 200 https://registry.npmjs.org/socket.io-adapter/-/socket.io-adapter-0.4.0.tgz
npm http GET https://registry.npmjs.org/fs-extra/-/fs-extra-0.24.0.tgz
npm http 200 https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/inline-process-browser/-/inline-process-browser-1.0.0.tgz
npm http 200 https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/immediate/-/immediate-3.0.5.tgz
npm http 304 https://registry.npmjs.org/jsonify
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/deep-equal/-/deep-equal-0.0.0.tgz
npm http 304 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/engine.io
npm http 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.7.tgz
npm http GET https://registry.npmjs.org/engine.io/-/engine.io-1.6.8.tgz
npm http 304 https://registry.npmjs.org/content-type
npm http 200 https://registry.npmjs.org/deep-equal/-/deep-equal-0.0.0.tgz
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http 200 https://registry.npmjs.org/fs-extra/-/fs-extra-0.24.0.tgz
npm http 200 https://registry.npmjs.org/immediate/-/immediate-3.0.5.tgz
npm http 200 https://registry.npmjs.org/inline-process-browser/-/inline-process-browser-1.0.0.tgz
npm http 200 https://registry.npmjs.org/es3ify/-/es3ify-0.1.4.tgz
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 200 https://registry.npmjs.org/engine.io/-/engine.io-1.6.8.tgz
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.2.tgz
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/benchmark
npm http GET https://registry.npmjs.org/engine.io-parser
npm http GET https://registry.npmjs.org/base64id
npm http GET https://registry.npmjs.org/ws
npm http GET https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/send
npm http 200 https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/bluebird/-/bluebird-2.10.2.tgz
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/array-flatten
npm http GET https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.3.0.tgz
npm http 200 https://registry.npmjs.org/component-bind
npm http GET https://registry.npmjs.org/component-bind/-/component-bind-1.0.0.tgz
npm http 200 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/parseuri
npm http 200 https://registry.npmjs.org/component-emitter
npm http 200 https://registry.npmjs.org/socket.io-parser/-/socket.io-parser-2.2.2.tgz
npm http GET https://registry.npmjs.org/object-component/-/object-component-0.0.3.tgz
npm http GET https://registry.npmjs.org/parseuri/-/parseuri-0.0.4.tgz
npm http GET https://registry.npmjs.org/component-emitter/-/component-emitter-1.2.0.tgz
npm http 200 https://registry.npmjs.org/to-array
npm http GET https://registry.npmjs.org/to-array/-/to-array-0.1.4.tgz
npm http 304 https://registry.npmjs.org/indexof
npm http 200 https://registry.npmjs.org/backo2
npm http 200 https://registry.npmjs.org/cycle
npm http GET https://registry.npmjs.org/unpipe
npm http 200 https://registry.npmjs.org/eyes
npm http GET https://registry.npmjs.org/backo2/-/backo2-1.0.2.tgz
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/cycle/-/cycle-1.0.3.tgz
npm http GET https://registry.npmjs.org/eyes/-/eyes-0.1.8.tgz
npm http 200 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/bluebird/-/bluebird-2.10.2.tgz
npm http GET https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz
npm http GET https://registry.npmjs.org/pkginfo/-/pkginfo-0.3.1.tgz
npm http GET https://registry.npmjs.org/colors/-/colors-1.0.3.tgz
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/debug/-/debug-0.7.4.tgz
npm http 304 https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/isarray
npm http 200 https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.3.0.tgz
npm http GET https://registry.npmjs.org/async/-/async-1.0.0.tgz
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/component-emitter/-/component-emitter-1.1.2.tgz
npm http 200 https://registry.npmjs.org/component-bind/-/component-bind-1.0.0.tgz
npm http 200 https://registry.npmjs.org/parseuri/-/parseuri-0.0.4.tgz
npm http 200 https://registry.npmjs.org/component-emitter/-/component-emitter-1.2.0.tgz
npm http 200 https://registry.npmjs.org/object-component/-/object-component-0.0.3.tgz
npm http 200 https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/json3/-/json3-3.3.2.tgz
npm http 200 https://registry.npmjs.org/to-array/-/to-array-0.1.4.tgz
npm http 200 https://registry.npmjs.org/backo2/-/backo2-1.0.2.tgz
npm http 200 https://registry.npmjs.org/cycle/-/cycle-1.0.3.tgz
npm http 200 https://registry.npmjs.org/eyes/-/eyes-0.1.8.tgz
npm http 200 https://registry.npmjs.org/benchmark
npm http GET https://registry.npmjs.org/benchmark/-/benchmark-1.0.0.tgz
npm http 200 https://registry.npmjs.org/base64id
npm http GET https://registry.npmjs.org/base64id/-/base64id-0.1.0.tgz
npm http 200 https://registry.npmjs.org/engine.io-parser
npm http GET https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.4.tgz
npm http 200 https://registry.npmjs.org/isstream/-/isstream-0.1.2.tgz
npm http 200 https://registry.npmjs.org/engine.io-client
npm http 200 https://registry.npmjs.org/pkginfo/-/pkginfo-0.3.1.tgz
npm http 200 https://registry.npmjs.org/debug/-/debug-0.7.4.tgz
npm http GET https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.8.tgz
npm http 304 https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/accepts/-/accepts-1.1.4.tgz
npm http 200 https://registry.npmjs.org/stack-trace
npm http GET https://registry.npmjs.org/stack-trace/-/stack-trace-0.0.9.tgz
npm http 304 https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/ee-first
npm http 200 https://registry.npmjs.org/colors/-/colors-1.0.3.tgz
npm http 200 https://registry.npmjs.org/component-emitter/-/component-emitter-1.1.2.tgz
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/json3/-/json3-3.3.2.tgz
npm http 200 https://registry.npmjs.org/async/-/async-1.0.0.tgz
npm http 304 https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/http-errors
npm http 200 https://registry.npmjs.org/base64id/-/base64id-0.1.0.tgz
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/ws
npm http 200 https://registry.npmjs.org/engine.io-client/-/engine.io-client-1.6.8.tgz
npm http 200 https://registry.npmjs.org/engine.io-parser/-/engine.io-parser-1.2.4.tgz
npm http 200 https://registry.npmjs.org/benchmark/-/benchmark-1.0.0.tgz
npm http GET https://registry.npmjs.org/through2/-/through2-0.6.5.tgz
npm http GET https://registry.npmjs.org/ws/-/ws-1.0.1.tgz
npm http 304 https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/json3/-/json3-3.2.6.tgz
npm http 200 https://registry.npmjs.org/accepts/-/accepts-1.1.4.tgz
npm http 304 https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/stack-trace/-/stack-trace-0.0.9.tgz
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/through2/-/through2-0.6.5.tgz
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/jstransform/-/jstransform-3.0.0.tgz
npm http 200 https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/ws/-/ws-1.0.1.tgz
npm http 200 https://registry.npmjs.org/json3/-/json3-3.2.6.tgz
npm http GET https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.0.tgz
npm http GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-3001.0001.0000-dev-harmony-fb.tgz
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/negotiator/-/negotiator-0.4.9.tgz
npm http GET https://registry.npmjs.org/mime-types/-/mime-types-2.0.14.tgz
npm http GET https://registry.npmjs.org/arraybuffer.slice
npm http GET https://registry.npmjs.org/base64-arraybuffer
npm http 304 https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/blob
npm http GET https://registry.npmjs.org/utf8
npm http GET https://registry.npmjs.org/after
npm http GET https://registry.npmjs.org/has-binary/-/has-binary-0.1.6.tgz
npm http 304 https://registry.npmjs.org/acorn
npm http 200 https://registry.npmjs.org/esmangle-evaluator/-/esmangle-evaluator-1.0.0.tgz
npm http GET https://registry.npmjs.org/options
npm http GET https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/jstransform/-/jstransform-3.0.0.tgz
npm http 200 https://registry.npmjs.org/mime-types/-/mime-types-2.0.14.tgz
npm http 200 https://registry.npmjs.org/negotiator/-/negotiator-0.4.9.tgz
npm http 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-3001.0001.0000-dev-harmony-fb.tgz
npm http 200 https://registry.npmjs.org/utf8
npm http GET https://registry.npmjs.org/utf8/-/utf8-2.1.0.tgz
npm http 200 https://registry.npmjs.org/has-binary/-/has-binary-0.1.6.tgz
npm http 200 https://registry.npmjs.org/after
npm http 200 https://registry.npmjs.org/blob
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/after/-/after-0.8.1.tgz
npm http GET https://registry.npmjs.org/blob/-/blob-0.0.4.tgz
npm http 200 https://registry.npmjs.org/base64-arraybuffer
npm http 200 https://registry.npmjs.org/options
npm http 200 https://registry.npmjs.org/arraybuffer.slice
npm http GET https://registry.npmjs.org/base64-arraybuffer/-/base64-arraybuffer-0.1.2.tgz
npm http GET https://registry.npmjs.org/arraybuffer.slice/-/arraybuffer.slice-0.0.6.tgz
npm http GET https://registry.npmjs.org/options/-/options-0.0.6.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/better-assert
npm http GET https://registry.npmjs.org/mime-db/-/mime-db-1.12.0.tgz
npm http 200 https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/recast/-/recast-0.10.43.tgz
npm http 200 https://registry.npmjs.org/utf8/-/utf8-2.1.0.tgz
npm http 200 https://registry.npmjs.org/blob/-/blob-0.0.4.tgz
npm http 200 https://registry.npmjs.org/after/-/after-0.8.1.tgz
npm http 200 https://registry.npmjs.org/ultron
npm http GET https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/base64-arraybuffer/-/base64-arraybuffer-0.1.2.tgz
npm http 200 https://registry.npmjs.org/arraybuffer.slice/-/arraybuffer.slice-0.0.6.tgz
npm http GET https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/rimraf
npm http GET https://registry.npmjs.org/graceful-fs
npm http 200 https://registry.npmjs.org/options/-/options-0.0.6.tgz
npm http GET https://registry.npmjs.org/ultron/-/ultron-1.0.2.tgz
npm http 200 https://registry.npmjs.org/mime-db/-/mime-db-1.12.0.tgz
npm http 200 https://registry.npmjs.org/better-assert
npm http 200 https://registry.npmjs.org/recast/-/recast-0.10.43.tgz
npm http GET https://registry.npmjs.org/better-assert/-/better-assert-1.0.2.tgz
npm http GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http GET https://registry.npmjs.org/parsejson
npm http GET https://registry.npmjs.org/parseqs
npm http GET https://registry.npmjs.org/component-inherit
npm http GET https://registry.npmjs.org/yeast
npm http GET https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/ultron/-/ultron-1.0.2.tgz
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 200 https://registry.npmjs.org/jsonfile
npm http GET https://registry.npmjs.org/jsonfile/-/jsonfile-2.2.3.tgz
npm http 200 https://registry.npmjs.org/parsejson
npm http 200 https://registry.npmjs.org/better-assert/-/better-assert-1.0.2.tgz
npm http 200 https://registry.npmjs.org/parseqs
npm http 200 https://registry.npmjs.org/component-inherit
npm http GET https://registry.npmjs.org/parsejson/-/parsejson-0.0.1.tgz
npm http GET https://registry.npmjs.org/component-inherit/-/component-inherit-0.0.3.tgz
npm http GET https://registry.npmjs.org/parseqs/-/parseqs-0.0.2.tgz
npm http GET https://registry.npmjs.org/callsite
npm http 200 https://registry.npmjs.org/has-cors
npm http 200 https://registry.npmjs.org/yeast
npm http GET https://registry.npmjs.org/yeast/-/yeast-0.1.2.tgz
npm http GET https://registry.npmjs.org/has-cors/-/has-cors-1.1.0.tgz
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1001.0-dev-harmony-fb.tgz
npm http 200 https://registry.npmjs.org/xmlhttprequest-ssl
npm http GET https://registry.npmjs.org/xmlhttprequest-ssl/-/xmlhttprequest-ssl-1.5.1.tgz
npm http 200 https://registry.npmjs.org/jsonfile/-/jsonfile-2.2.3.tgz
npm http GET https://registry.npmjs.org/glob
npm http 200 https://registry.npmjs.org/parsejson/-/parsejson-0.0.1.tgz
npm http 200 https://registry.npmjs.org/callsite
npm http 200 https://registry.npmjs.org/yeast/-/yeast-0.1.2.tgz
npm http GET https://registry.npmjs.org/callsite/-/callsite-1.0.0.tgz
npm http 200 https://registry.npmjs.org/component-inherit/-/component-inherit-0.0.3.tgz
npm http 200 https://registry.npmjs.org/parseqs/-/parseqs-0.0.2.tgz
npm http 200 https://registry.npmjs.org/has-cors/-/has-cors-1.1.0.tgz
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/callsite/-/callsite-1.0.0.tgz
npm http 200 https://registry.npmjs.org/xmlhttprequest-ssl/-/xmlhttprequest-ssl-1.5.1.tgz
npm http GET https://registry.npmjs.org/source-map/-/source-map-0.5.3.tgz
npm http 200 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/esprima-fb/-/esprima-fb-15001.1001.0-dev-harmony-fb.tgz
npm http GET https://registry.npmjs.org/private/-/private-0.1.6.tgz
npm http GET https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map/-/source-map-0.1.31.tgz
npm http 200 https://registry.npmjs.org/private/-/private-0.1.6.tgz
npm http 200 https://registry.npmjs.org/source-map/-/source-map-0.5.3.tgz
npm http 304 https://registry.npmjs.org/has-binary
npm http 200 https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/ast-types/-/ast-types-0.8.15.tgz
npm http GET https://registry.npmjs.org/base62/-/base62-0.1.1.tgz
npm http 304 https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/ast-types/-/ast-types-0.8.15.tgz
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/source-map/-/source-map-0.1.31.tgz
npm http 200 https://registry.npmjs.org/base62/-/base62-0.1.1.tgz
npm http GET https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/concat-map
npm WARN package.json thali@2.1.0 No README data
npm http GET https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/javascript-state-machine
npm http GET https://registry.npmjs.org/long
npm http GET https://registry.npmjs.org/multiplex
npm http GET https://registry.npmjs.org/node-ssdp
npm http GET https://registry.npmjs.org/urlsafe-base64
npm http GET https://registry.npmjs.org/jsdoc
npm http GET https://registry.npmjs.org/body-parser
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/winston
npm http GET https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/ip/-/ip-1.1.0.tgz
npm http 200 https://registry.npmjs.org/node-ssdp
npm http 200 https://registry.npmjs.org/long
npm http GET https://registry.npmjs.org/long/-/long-3.0.3.tgz
npm http 200 https://registry.npmjs.org/javascript-state-machine
npm http GET https://registry.npmjs.org/javascript-state-machine/-/javascript-state-machine-2.3.5.tgz
npm http 200 https://registry.npmjs.org/urlsafe-base64
npm http GET https://registry.npmjs.org/urlsafe-base64/-/urlsafe-base64-1.0.0.tgz
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/multiplex
npm http GET https://registry.npmjs.org/express/-/express-4.13.3.tgz
npm http GET https://registry.npmjs.org/multiplex/-/multiplex-6.6.1.tgz
npm http 304 https://registry.npmjs.org/winston
npm http 304 https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/winston/-/winston-1.1.2.tgz
npm http 304 https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/ip/-/ip-1.1.0.tgz
npm http GET https://registry.npmjs.org/request/-/request-2.69.0.tgz
npm http 200 https://registry.npmjs.org/jsdoc
npm http GET https://registry.npmjs.org/jsdoc/-/jsdoc-3.4.0.tgz
npm http 200 https://registry.npmjs.org/multiplex/-/multiplex-6.6.1.tgz
npm http 200 https://registry.npmjs.org/long/-/long-3.0.3.tgz
npm http 200 https://registry.npmjs.org/urlsafe-base64/-/urlsafe-base64-1.0.0.tgz
npm http 200 https://registry.npmjs.org/body-parser
npm http 200 https://registry.npmjs.org/javascript-state-machine/-/javascript-state-machine-2.3.5.tgz
npm http GET https://registry.npmjs.org/body-parser/-/body-parser-1.15.0.tgz
npm http 200 https://registry.npmjs.org/winston/-/winston-1.1.2.tgz
npm http 200 https://registry.npmjs.org/express/-/express-4.13.3.tgz
npm http 200 https://registry.npmjs.org/request/-/request-2.69.0.tgz
npm http 200 https://registry.npmjs.org/jsdoc/-/jsdoc-3.4.0.tgz
npm http 200 https://registry.npmjs.org/body-parser/-/body-parser-1.15.0.tgz
npm http GET https://registry.npmjs.org/varint
npm http GET https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/iconv-lite
npm http GET https://registry.npmjs.org/raw-body
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http GET https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/har-validator
npm http GET https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/aws4
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/colors
npm http GET https://registry.npmjs.org/cycle
npm http GET https://registry.npmjs.org/eyes
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/pkginfo
npm http GET https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/bytes
npm http 200 https://registry.npmjs.org/varint
npm http GET https://registry.npmjs.org/varint/-/varint-4.0.0.tgz
npm http 304 https://registry.npmjs.org/content-type
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/http-errors/-/http-errors-1.4.0.tgz
npm http 200 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/on-finished
npm http 304 https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/raw-body/-/raw-body-2.1.5.tgz
npm http GET https://registry.npmjs.org/qs/-/qs-6.1.0.tgz
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/varint/-/varint-4.0.0.tgz
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.0.tgz
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/cookie-signature
npm http 200 https://registry.npmjs.org/http-errors/-/http-errors-1.4.0.tgz
npm http 304 https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie/-/cookie-0.1.3.tgz
npm http GET https://registry.npmjs.org/end-of-stream
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/raw-body/-/raw-body-2.1.5.tgz
npm http 304 https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/escape-html/-/escape-html-1.0.2.tgz
npm http 304 https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/depd/-/depd-1.0.1.tgz
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.0.tgz
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/qs/-/qs-6.1.0.tgz
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 304 https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.0.tgz
npm http 304 https://registry.npmjs.org/methods
npm http 200 https://registry.npmjs.org/iconv-lite
npm http GET https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.13.tgz
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/finalhandler/-/finalhandler-0.4.0.tgz
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 200 https://registry.npmjs.org/content-disposition/-/content-disposition-0.5.0.tgz
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/serve-static
npm http 200 https://registry.npmjs.org/merge-descriptors/-/merge-descriptors-1.0.0.tgz
npm http 304 https://registry.npmjs.org/type-is
npm http 200 https://registry.npmjs.org/cookie/-/cookie-0.1.3.tgz
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/send/-/send-0.13.0.tgz
npm http GET https://registry.npmjs.org/catharsis
npm http GET https://registry.npmjs.org/espree
npm http GET https://registry.npmjs.org/js2xmlparser
npm http GET https://registry.npmjs.org/marked
npm http GET https://registry.npmjs.org/requizzle
npm http 304 https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/wrench
npm http GET https://registry.npmjs.org/strip-json-comments
npm http GET https://registry.npmjs.org/underscore
npm http GET https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/array-flatten
npm http 200 https://registry.npmjs.org/escape-html/-/escape-html-1.0.2.tgz
npm http 304 https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/bl/-/bl-1.0.3.tgz
npm http 304 https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/caseless/-/caseless-0.11.0.tgz
npm http 200 https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/is-typedarray/-/is-typedarray-1.0.0.tgz
npm http 304 https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/forever-agent/-/forever-agent-0.6.1.tgz
npm http 304 https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/form-data/-/form-data-1.0.0-rc3.tgz
npm http 304 https://registry.npmjs.org/http-signature
npm http 200 https://registry.npmjs.org/send/-/send-0.13.0.tgz
npm http GET https://registry.npmjs.org/http-signature/-/http-signature-1.1.1.tgz
npm http 304 https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.13.tgz
npm http GET https://registry.npmjs.org/hawk/-/hawk-3.1.3.tgz
npm http 200 https://registry.npmjs.org/caseless/-/caseless-0.11.0.tgz
npm http 304 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/is-typedarray/-/is-typedarray-1.0.0.tgz
npm http 200 https://registry.npmjs.org/forever-agent/-/forever-agent-0.6.1.tgz
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 200 https://registry.npmjs.org/form-data/-/form-data-1.0.0-rc3.tgz
npm http 304 https://registry.npmjs.org/mime-types
npm http 200 https://registry.npmjs.org/bl/-/bl-1.0.3.tgz
npm http 200 https://registry.npmjs.org/http-signature/-/http-signature-1.1.1.tgz
npm http 200 https://registry.npmjs.org/hawk/-/hawk-3.1.3.tgz
npm http 304 https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.1.tgz
npm http 304 https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/qs/-/qs-6.0.2.tgz
npm http 304 https://registry.npmjs.org/stringstream
npm http 200 https://registry.npmjs.org/aws4
npm http GET https://registry.npmjs.org/aws4/-/aws4-1.3.1.tgz
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 200 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/aws-sign2/-/aws-sign2-0.6.0.tgz
npm http GET https://registry.npmjs.org/har-validator/-/har-validator-2.0.6.tgz
npm http 304 https://registry.npmjs.org/async
npm http 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 304 https://registry.npmjs.org/colors
npm http 200 https://registry.npmjs.org/oauth-sign/-/oauth-sign-0.8.1.tgz
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/eyes
npm http 304 https://registry.npmjs.org/cycle
npm http 304 https://registry.npmjs.org/pkginfo
npm http 200 https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/extend/-/extend-3.0.0.tgz
npm http 200 https://registry.npmjs.org/aws4/-/aws4-1.3.1.tgz
npm http 304 https://registry.npmjs.org/stack-trace
npm http 304 https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/qs/-/qs-6.0.2.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/aws-sign2/-/aws-sign2-0.6.0.tgz
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 200 https://registry.npmjs.org/har-validator/-/har-validator-2.0.6.tgz
npm http 304 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/extend/-/extend-3.0.0.tgz
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/js2xmlparser
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-1.0.0.tgz
npm http 200 https://registry.npmjs.org/depd/-/depd-1.0.1.tgz
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/unpipe
npm http 200 https://registry.npmjs.org/catharsis
npm http 200 https://registry.npmjs.org/requizzle
npm http 200 https://registry.npmjs.org/marked
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http 304 https://registry.npmjs.org/underscore
npm http 304 https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/requizzle/-/requizzle-0.2.1.tgz
npm http GET https://registry.npmjs.org/catharsis/-/catharsis-0.8.7.tgz
npm http GET https://registry.npmjs.org/marked/-/marked-0.3.5.tgz
npm http 200 https://registry.npmjs.org/espree
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/once
npm http 200 https://registry.npmjs.org/wrench
npm http 304 https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/underscore/-/underscore-1.8.3.tgz
npm http GET https://registry.npmjs.org/async/-/async-1.4.2.tgz
npm http 200 https://registry.npmjs.org/js2xmlparser/-/js2xmlparser-1.0.0.tgz
npm http 304 https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/espree/-/espree-2.2.5.tgz
npm http 200 https://registry.npmjs.org/async/-/async-1.4.2.tgz
npm http GET https://registry.npmjs.org/bluebird/-/bluebird-2.9.34.tgz
npm http GET https://registry.npmjs.org/wrench/-/wrench-1.5.8.tgz
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/async/-/async-1.5.2.tgz
npm http 200 https://registry.npmjs.org/espree/-/espree-2.2.5.tgz
npm http 200 https://registry.npmjs.org/catharsis/-/catharsis-0.8.7.tgz
npm http 200 https://registry.npmjs.org/marked/-/marked-0.3.5.tgz
npm http 200 https://registry.npmjs.org/underscore/-/underscore-1.8.3.tgz
npm http 200 https://registry.npmjs.org/wrench/-/wrench-1.5.8.tgz
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/lru-cache
npm http 200 https://registry.npmjs.org/async/-/async-1.5.2.tgz
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/negotiator
npm http 200 https://registry.npmjs.org/bluebird/-/bluebird-2.9.34.tgz
npm http GET https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/jsprim
npm http GET https://registry.npmjs.org/sshpk
npm http 200 https://registry.npmjs.org/requizzle/-/requizzle-0.2.1.tgz
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/commander
npm http GET https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/chalk
npm http 200 https://registry.npmjs.org/lru-cache
npm http 200 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/assert-plus
npm http 200 https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/lru-cache/-/lru-cache-4.0.0.tgz
npm http GET https://registry.npmjs.org/jsprim/-/jsprim-1.2.2.tgz
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 304 https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/destroy/-/destroy-1.0.3.tgz
npm http GET https://registry.npmjs.org/assert-plus/-/assert-plus-0.2.0.tgz
npm http GET https://registry.npmjs.org/sshpk/-/sshpk-1.7.4.tgz
npm http 200 https://registry.npmjs.org/jsprim/-/jsprim-1.2.2.tgz
npm http 200 https://registry.npmjs.org/lru-cache/-/lru-cache-4.0.0.tgz
npm http 200 https://registry.npmjs.org/assert-plus/-/assert-plus-0.2.0.tgz
npm http GET https://registry.npmjs.org/underscore/-/underscore-1.6.0.tgz
npm http 200 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/commander/-/commander-2.9.0.tgz
npm http GET https://registry.npmjs.org/is-my-json-valid/-/is-my-json-valid-2.13.1.tgz
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/sshpk/-/sshpk-1.7.4.tgz
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/destroy/-/destroy-1.0.3.tgz
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 200 https://registry.npmjs.org/commander/-/commander-2.9.0.tgz
npm http 304 https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/json-schema
npm http GET https://registry.npmjs.org/verror
npm http GET https://registry.npmjs.org/pseudomap
npm http GET https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/pseudomap
npm http 200 https://registry.npmjs.org/underscore/-/underscore-1.6.0.tgz
npm http GET https://registry.npmjs.org/pseudomap/-/pseudomap-1.0.2.tgz
npm http 200 https://registry.npmjs.org/is-my-json-valid/-/is-my-json-valid-2.13.1.tgz
npm http 200 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/yallist/-/yallist-2.0.0.tgz
npm http GET https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/json-schema
npm http 200 https://registry.npmjs.org/verror
npm http GET https://registry.npmjs.org/json-schema/-/json-schema-0.2.2.tgz
npm http GET https://registry.npmjs.org/verror/-/verror-1.3.6.tgz
npm http 200 https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/extsprintf/-/extsprintf-1.0.2.tgz
npm http 304 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/pseudomap/-/pseudomap-1.0.2.tgz
npm http GET https://registry.npmjs.org/graceful-readlink
npm http GET https://registry.npmjs.org/dashdash
npm http GET https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/supports-color
npm http 200 https://registry.npmjs.org/extsprintf/-/extsprintf-1.0.2.tgz
npm http 304 https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/hoek/-/hoek-2.16.3.tgz
npm http GET https://registry.npmjs.org/boom/-/boom-2.10.1.tgz
npm http 304 https://registry.npmjs.org/cryptiles
npm http 200 https://registry.npmjs.org/yallist/-/yallist-2.0.0.tgz
npm http GET https://registry.npmjs.org/underscore-contrib
npm http 304 https://registry.npmjs.org/sntp
npm http 200 https://registry.npmjs.org/graceful-readlink
npm http GET https://registry.npmjs.org/cryptiles/-/cryptiles-2.0.5.tgz
npm http GET https://registry.npmjs.org/sntp/-/sntp-1.0.9.tgz
npm http GET https://registry.npmjs.org/graceful-readlink/-/graceful-readlink-1.0.1.tgz
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/pinkie
npm http 200 https://registry.npmjs.org/json-schema/-/json-schema-0.2.2.tgz
npm http GET https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/asn1/-/asn1-0.2.3.tgz
npm http 200 https://registry.npmjs.org/verror/-/verror-1.3.6.tgz
npm http GET https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/hoek/-/hoek-2.16.3.tgz
npm http 200 https://registry.npmjs.org/sntp/-/sntp-1.0.9.tgz
npm http 200 https://registry.npmjs.org/dashdash
npm http GET https://registry.npmjs.org/dashdash/-/dashdash-1.13.0.tgz
npm http 200 https://registry.npmjs.org/boom/-/boom-2.10.1.tgz
npm http 200 https://registry.npmjs.org/cryptiles/-/cryptiles-2.0.5.tgz
npm http 200 https://registry.npmjs.org/graceful-readlink/-/graceful-readlink-1.0.1.tgz
npm http 200 https://registry.npmjs.org/asn1/-/asn1-0.2.3.tgz
npm http GET https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/jsonpointer
npm http GET https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/generate-object-property
npm http 200 https://registry.npmjs.org/dashdash/-/dashdash-1.13.0.tgz
npm http 304 https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/underscore-contrib
npm http GET https://registry.npmjs.org/generate-object-property/-/generate-object-property-1.2.0.tgz
npm http GET https://registry.npmjs.org/underscore-contrib/-/underscore-contrib-0.3.0.tgz
npm http 200 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/jsonpointer/-/jsonpointer-2.0.0.tgz
npm http 200 https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/assert-plus/-/assert-plus-1.0.0.tgz
npm http GET https://registry.npmjs.org/generate-function/-/generate-function-2.0.0.tgz
npm http 200 https://registry.npmjs.org/generate-object-property/-/generate-object-property-1.2.0.tgz
npm http 200 https://registry.npmjs.org/underscore-contrib/-/underscore-contrib-0.3.0.tgz
npm http 200 https://registry.npmjs.org/generate-function/-/generate-function-2.0.0.tgz
npm http 200 https://registry.npmjs.org/jsonpointer/-/jsonpointer-2.0.0.tgz
npm http 200 https://registry.npmjs.org/assert-plus/-/assert-plus-1.0.0.tgz
npm http GET https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/is-property
npm http GET https://registry.npmjs.org/is-property/-/is-property-1.0.2.tgz
npm http 200 https://registry.npmjs.org/is-property/-/is-property-1.0.2.tgz
npm http GET https://registry.npmjs.org/node-ssdp
npm http 304 https://registry.npmjs.org/node-ssdp
npm WARN package.json install@0.0.1 No repository field.
npm WARN package.json install@0.0.1 No README data
npm http GET https://registry.npmjs.org/jxc
npm http GET https://registry.npmjs.org/unzip
npm http GET https://registry.npmjs.org/fs-extra-promise
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/lie
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/unzip
npm http GET https://registry.npmjs.org/unzip/-/unzip-0.1.11.tgz
npm http 200 https://registry.npmjs.org/jxc
npm http GET https://registry.npmjs.org/jxc/-/jxc-1.0.13.tgz
npm http 200 https://registry.npmjs.org/unzip/-/unzip-0.1.11.tgz
npm http 200 https://registry.npmjs.org/jxc/-/jxc-1.0.13.tgz
npm http GET https://registry.npmjs.org/fs-extra
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/pullstream
npm http GET https://registry.npmjs.org/binary
npm http GET https://registry.npmjs.org/setimmediate
npm http GET https://registry.npmjs.org/match-stream
npm http GET https://registry.npmjs.org/fstream
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/har-validator
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/es3ify
npm http 200 https://registry.npmjs.org/setimmediate
npm http GET https://registry.npmjs.org/setimmediate/-/setimmediate-1.0.4.tgz
npm http GET https://registry.npmjs.org/graceful-fs
npm http GET https://registry.npmjs.org/jsonfile
npm http GET https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/rimraf
npm http 200 https://registry.npmjs.org/pullstream
npm http 200 https://registry.npmjs.org/binary
npm http GET https://registry.npmjs.org/binary/-/binary-0.3.0.tgz
npm http GET https://registry.npmjs.org/pullstream/-/pullstream-0.4.1.tgz
npm http 304 https://registry.npmjs.org/fstream
npm http 304 https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/fstream/-/fstream-0.1.31.tgz
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/setimmediate/-/setimmediate-1.0.4.tgz
npm http 200 https://registry.npmjs.org/match-stream
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/match-stream/-/match-stream-0.0.2.tgz
npm http 304 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/pullstream/-/pullstream-0.4.1.tgz
npm http 304 https://registry.npmjs.org/hawk
npm http 200 https://registry.npmjs.org/binary/-/binary-0.3.0.tgz
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/node-uuid
npm http 200 https://registry.npmjs.org/fstream/-/fstream-0.1.31.tgz
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 200 https://registry.npmjs.org/match-stream/-/match-stream-0.0.2.tgz
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/over
npm http GET https://registry.npmjs.org/slice-stream
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/buffers
npm http GET https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/jsprim
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/mkdirp
npm WARN deprecated graceful-fs@3.0.8: graceful-fs version 3 and before will fail on newer node releases. Please update to graceful-fs@^4.0.0 as soon as possible.
npm http 200 https://registry.npmjs.org/over
npm http 200 https://registry.npmjs.org/slice-stream
npm http GET https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/over/-/over-0.0.5.tgz
npm http GET https://registry.npmjs.org/commander
npm http GET https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/slice-stream/-/slice-stream-1.0.0.tgz
npm http GET https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/buffers
npm http GET https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/buffers/-/buffers-0.1.1.tgz
npm http 304 https://registry.npmjs.org/lru-cache
npm http 304 https://registry.npmjs.org/foreach
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/slice-stream/-/slice-stream-1.0.0.tgz
npm http 200 https://registry.npmjs.org/over/-/over-0.0.5.tgz
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/chainsaw
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/chainsaw/-/chainsaw-0.1.0.tgz
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/buffers/-/buffers-0.1.1.tgz
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/json-schema
npm http GET https://registry.npmjs.org/verror
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/pseudomap
npm http GET https://registry.npmjs.org/yallist
npm http GET https://registry.npmjs.org/graceful-readlink
npm http 200 https://registry.npmjs.org/chainsaw/-/chainsaw-0.1.0.tgz
npm http GET https://registry.npmjs.org/minimist
npm http 304 https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http 304 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/pseudomap
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/sntp
npm http GET https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/minimist
npm http GET https://registry.npmjs.org/traverse
npm http GET https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/color-convert
npm http GET https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/jsbn
npm http GET https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/jodid25519
npm http GET https://registry.npmjs.org/ecc-jsbn
npm http GET https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/color-convert
npm http 304 https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/adm-zip
npm http GET https://registry.npmjs.org/progress
npm http 200 https://registry.npmjs.org/jsbn
npm http 200 https://registry.npmjs.org/ecc-jsbn
npm http 200 https://registry.npmjs.org/jodid25519
npm http 200 https://registry.npmjs.org/traverse
npm http GET https://registry.npmjs.org/jsbn/-/jsbn-0.1.0.tgz
npm http GET https://registry.npmjs.org/ecc-jsbn/-/ecc-jsbn-0.1.1.tgz
npm http GET https://registry.npmjs.org/jodid25519/-/jodid25519-1.0.2.tgz
npm http GET https://registry.npmjs.org/traverse/-/traverse-0.3.9.tgz
npm http GET https://registry.npmjs.org/jsonpointer
npm http GET https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/progress
npm http GET https://registry.npmjs.org/progress/-/progress-1.1.8.tgz
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-function
npm http 200 https://registry.npmjs.org/tweetnacl
npm http 304 https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.14.1.tgz
npm http 200 https://registry.npmjs.org/adm-zip
npm http GET https://registry.npmjs.org/adm-zip/-/adm-zip-0.4.7.tgz
npm http 304 https://registry.npmjs.org/concat-map
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/is-property
npm http 200 https://registry.npmjs.org/jodid25519/-/jodid25519-1.0.2.tgz
npm http 200 https://registry.npmjs.org/ecc-jsbn/-/ecc-jsbn-0.1.1.tgz
npm http 200 https://registry.npmjs.org/jsbn/-/jsbn-0.1.0.tgz
npm http 200 https://registry.npmjs.org/traverse/-/traverse-0.3.9.tgz
npm http 200 https://registry.npmjs.org/progress/-/progress-1.1.8.tgz
npm http 200 https://registry.npmjs.org/tweetnacl/-/tweetnacl-0.14.1.tgz
npm http 200 https://registry.npmjs.org/adm-zip/-/adm-zip-0.4.7.tgz
npm http 304 https://registry.npmjs.org/is-property
npm WARN package.json thali-cordova-plugin-jxcore@1.0.0 No repository field.
npm http GET https://registry.npmjs.org/express-pouchdb
npm http GET https://registry.npmjs.org/nock
npm http GET https://registry.npmjs.org/bn.js
npm http GET https://registry.npmjs.org/body-parser
npm http GET https://registry.npmjs.org/pouchdb
npm http GET https://registry.npmjs.org/proxyquire
npm http GET https://registry.npmjs.org/randomstring
npm http GET https://registry.npmjs.org/request-promise
npm http GET https://registry.npmjs.org/sinon
npm http GET https://registry.npmjs.org/express
npm http GET https://registry.npmjs.org/fs-extra-promise
npm http GET https://registry.npmjs.org/supertest
npm http GET https://registry.npmjs.org/supertest-as-promised
npm http GET https://registry.npmjs.org/tape-catch
npm http GET https://registry.npmjs.org/tmp
npm http GET https://registry.npmjs.org/wrapping-tape
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/leveldown-mobile
npm http GET https://registry.npmjs.org/long
npm http GET https://registry.npmjs.org/multiplex
npm http GET https://registry.npmjs.org/node-ssdp
npm http GET https://registry.npmjs.org/request
npm http GET https://registry.npmjs.org/socket.io-client
npm http GET https://registry.npmjs.org/urlsafe-base64
npm http GET https://registry.npmjs.org/tape
npm http GET https://registry.npmjs.org/uuid
npm http GET https://registry.npmjs.org/balanced-match/-/balanced-match-0.2.1.tgz
npm http 304 https://registry.npmjs.org/bn.js
npm http 304 https://registry.npmjs.org/body-parser
npm http 200 https://registry.npmjs.org/balanced-match/-/balanced-match-0.2.1.tgz
npm http 200 https://registry.npmjs.org/express-pouchdb
npm http GET https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb
npm http GET https://registry.npmjs.org/pouchdb/-/pouchdb-5.2.1.tgz
npm http 200 https://registry.npmjs.org/proxyquire
npm http GET https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.4.tgz
npm http 304 https://registry.npmjs.org/express
npm http 304 https://registry.npmjs.org/fs-extra-promise
npm http 200 https://registry.npmjs.org/request-promise
npm http GET https://registry.npmjs.org/request-promise/-/request-promise-0.4.3.tgz
npm http 200 https://registry.npmjs.org/randomstring
npm http GET https://registry.npmjs.org/randomstring/-/randomstring-1.1.4.tgz
npm http 200 https://registry.npmjs.org/sinon
npm http 200 https://registry.npmjs.org/express-pouchdb/-/express-pouchdb-1.0.2.tgz
npm http 200 https://registry.npmjs.org/supertest-as-promised
npm http GET https://registry.npmjs.org/sinon/-/sinon-1.17.3.tgz
npm http GET https://registry.npmjs.org/supertest-as-promised/-/supertest-as-promised-2.0.2.tgz
npm http 200 https://registry.npmjs.org/proxyquire/-/proxyquire-1.7.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb/-/pouchdb-5.2.1.tgz
npm http 200 https://registry.npmjs.org/supertest
npm http GET https://registry.npmjs.org/supertest/-/supertest-1.2.0.tgz
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/tape-catch
npm http GET https://registry.npmjs.org/tape-catch/-/tape-catch-1.0.4.tgz
npm http 200 https://registry.npmjs.org/request-promise/-/request-promise-0.4.3.tgz
npm http 304 https://registry.npmjs.org/long
npm http 200 https://registry.npmjs.org/randomstring/-/randomstring-1.1.4.tgz
npm http 200 https://registry.npmjs.org/sinon/-/sinon-1.17.3.tgz
npm http 200 https://registry.npmjs.org/supertest-as-promised/-/supertest-as-promised-2.0.2.tgz
npm http 304 https://registry.npmjs.org/multiplex
npm http 200 https://registry.npmjs.org/supertest/-/supertest-1.2.0.tgz
npm http 200 https://registry.npmjs.org/tape-catch/-/tape-catch-1.0.4.tgz
npm http 304 https://registry.npmjs.org/node-ssdp
npm http 304 https://registry.npmjs.org/request
npm http 200 https://registry.npmjs.org/tmp
npm http GET https://registry.npmjs.org/tmp/-/tmp-0.0.28.tgz
npm http 304 https://registry.npmjs.org/socket.io-client
npm http 304 https://registry.npmjs.org/urlsafe-base64
npm http 200 https://registry.npmjs.org/wrapping-tape
npm http 304 https://registry.npmjs.org/tape
npm http GET https://registry.npmjs.org/wrapping-tape/-/wrapping-tape-0.0.3.tgz
npm http GET https://registry.npmjs.org/tape/-/tape-4.4.0.tgz
npm http 304 https://registry.npmjs.org/uuid
npm http 200 https://registry.npmjs.org/leveldown-mobile
npm http GET https://registry.npmjs.org/leveldown-mobile/-/leveldown-mobile-1.1.1.tgz
npm http 200 https://registry.npmjs.org/wrapping-tape/-/wrapping-tape-0.0.3.tgz
npm http 200 https://registry.npmjs.org/tmp/-/tmp-0.0.28.tgz
npm http 200 https://registry.npmjs.org/leveldown-mobile/-/leveldown-mobile-1.1.1.tgz
npm http 200 https://registry.npmjs.org/tape/-/tape-4.4.0.tgz
npm http 200 https://registry.npmjs.org/nock
npm http GET https://registry.npmjs.org/nock/-/nock-2.18.2.tgz
npm http 200 https://registry.npmjs.org/nock/-/nock-2.18.2.tgz
npm http GET https://registry.npmjs.org/fs-extra
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/duplexify
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/varint
npm http GET https://registry.npmjs.org/array-uniq
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/lodash
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/http-errors
npm http GET https://registry.npmjs.org/iconv-lite
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/raw-body
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/depd
npm http GET https://registry.npmjs.org/superagent
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/inline-process-browser
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/os-tmpdir
npm http GET https://registry.npmjs.org/content-disposition
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/escape-html
npm http GET https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/finalhandler
npm http GET https://registry.npmjs.org/fresh
npm http GET https://registry.npmjs.org/merge-descriptors
npm http GET https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/parseurl
npm http GET https://registry.npmjs.org/path-to-regexp
npm http GET https://registry.npmjs.org/proxy-addr
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/range-parser
npm http GET https://registry.npmjs.org/send
npm http GET https://registry.npmjs.org/serve-static
npm http GET https://registry.npmjs.org/type-is
npm http GET https://registry.npmjs.org/utils-merge
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/fs-extra
npm http 304 https://registry.npmjs.org/duplexify
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/array-uniq
npm http 304 https://registry.npmjs.org/varint
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/methods
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/form-data
npm http GET https://registry.npmjs.org/har-validator
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/aws4
npm http GET https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/http-errors
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 304 https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/socket.io-parser
npm http GET https://registry.npmjs.org/has-binary
npm http GET https://registry.npmjs.org/indexof
npm http GET https://registry.npmjs.org/parseuri
npm http GET https://registry.npmjs.org/to-array
npm http GET https://registry.npmjs.org/backo2
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/engine.io-client
npm http GET https://registry.npmjs.org/component-bind
npm http GET https://registry.npmjs.org/component-emitter
npm http GET https://registry.npmjs.org/object-component
npm http GET https://registry.npmjs.org/fill-keys
npm http 304 https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/module-not-found-error
npm http GET https://registry.npmjs.org/array-uniq/-/array-uniq-1.0.2.tgz
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/raw-body
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/depd
npm http 304 https://registry.npmjs.org/content-type
npm http GET https://registry.npmjs.org/lodash/-/lodash-3.10.1.tgz
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/end-of-stream
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/os-tmpdir
npm http 304 https://registry.npmjs.org/ip
npm http GET https://registry.npmjs.org/string.prototype.trim
npm http GET https://registry.npmjs.org/has
npm http GET https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/resolve
npm http GET https://registry.npmjs.org/object-inspect
npm http GET https://registry.npmjs.org/resumer
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/defined
npm http GET https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/content-disposition
npm http 304 https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/escape-html
npm http 304 https://registry.npmjs.org/etag
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/path-is-absolute
npm http GET https://registry.npmjs.org/graceful-fs
npm http GET https://registry.npmjs.org/rimraf
npm http GET https://registry.npmjs.org/jsonfile
npm http 200 https://registry.npmjs.org/superagent
npm http 304 https://registry.npmjs.org/cookie
npm http 304 https://registry.npmjs.org/finalhandler
npm http 304 https://registry.npmjs.org/fresh
npm http 304 https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/superagent/-/superagent-1.8.0-beta.2.tgz
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/methods
npm http 304 https://registry.npmjs.org/parseurl
npm http 304 https://registry.npmjs.org/merge-descriptors
npm http 200 https://registry.npmjs.org/array-uniq/-/array-uniq-1.0.2.tgz
npm http 304 https://registry.npmjs.org/proxy-addr
npm http 304 https://registry.npmjs.org/path-to-regexp
npm http 200 https://registry.npmjs.org/lodash/-/lodash-3.10.1.tgz
npm http 304 https://registry.npmjs.org/send
npm http 304 https://registry.npmjs.org/range-parser
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/serve-static
npm http 304 https://registry.npmjs.org/type-is
npm http 304 https://registry.npmjs.org/array-flatten
npm http 304 https://registry.npmjs.org/utils-merge
npm http 304 https://registry.npmjs.org/vary
npm http 304 https://registry.npmjs.org/accepts
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/har-validator
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/isstream
npm http 200 https://registry.npmjs.org/superagent/-/superagent-1.8.0-beta.2.tgz
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/aws4
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/caseless
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/parseuri
npm http 304 https://registry.npmjs.org/has-binary
npm http 304 https://registry.npmjs.org/socket.io-parser
npm http 304 https://registry.npmjs.org/indexof
npm http 304 https://registry.npmjs.org/to-array
npm http 304 https://registry.npmjs.org/component-bind
npm http 304 https://registry.npmjs.org/backo2
npm http 304 https://registry.npmjs.org/debug
npm http 304 https://registry.npmjs.org/engine.io-client
npm http 304 https://registry.npmjs.org/component-emitter
npm http 304 https://registry.npmjs.org/object-component
npm http 200 https://registry.npmjs.org/fill-keys
npm http 200 https://registry.npmjs.org/module-not-found-error
npm http 304 https://registry.npmjs.org/end-of-stream
npm http 304 https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/has
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/resolve
npm http 304 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/fill-keys/-/fill-keys-1.0.2.tgz
npm http GET https://registry.npmjs.org/module-not-found-error/-/module-not-found-error-1.0.1.tgz
npm http 200 https://registry.npmjs.org/object-inspect
npm http 304 https://registry.npmjs.org/resumer
npm http 200 https://registry.npmjs.org/string.prototype.trim
npm http 304 https://registry.npmjs.org/through
npm http 304 https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/glob/-/glob-5.0.15.tgz
npm http 304 https://registry.npmjs.org/defined
npm http 304 https://registry.npmjs.org/function-bind
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/object-inspect/-/object-inspect-1.0.2.tgz
npm http GET https://registry.npmjs.org/mime-db
npm http GET https://registry.npmjs.org/string.prototype.trim/-/string.prototype.trim-1.1.2.tgz
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/util-deprecate
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/path-is-absolute
npm http 304 https://registry.npmjs.org/rimraf
npm http 304 https://registry.npmjs.org/graceful-fs
npm http 304 https://registry.npmjs.org/jsonfile
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/async
npm http 304 https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/fill-keys/-/fill-keys-1.0.2.tgz
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/jstransform
npm http 200 https://registry.npmjs.org/module-not-found-error/-/module-not-found-error-1.0.1.tgz
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/string.prototype.trim/-/string.prototype.trim-1.1.2.tgz
npm http 304 https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/object-inspect/-/object-inspect-1.0.2.tgz
npm http 200 https://registry.npmjs.org/glob/-/glob-5.0.15.tgz
npm http GET https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/unpipe
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/forwarded
npm http GET https://registry.npmjs.org/ipaddr.js
npm http GET https://registry.npmjs.org/media-typer
npm http GET https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/better-assert
npm http GET https://registry.npmjs.org/unpipe
npm http GET https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/once
npm http GET https://registry.npmjs.org/destroy
npm http GET https://registry.npmjs.org/mime
npm http GET https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/statuses
npm http 304 https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/forwarded
npm http 304 https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/ipaddr.js
npm http 304 https://registry.npmjs.org/media-typer
npm http 304 https://registry.npmjs.org/better-assert
npm http 304 https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/unpipe
npm http 304 https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/jsprim
npm http GET https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/once
npm http 304 https://registry.npmjs.org/destroy
npm http 304 https://registry.npmjs.org/mime
npm http 304 https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/statuses
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http 304 https://registry.npmjs.org/assert-plus
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/jsprim
npm http 200 https://registry.npmjs.org/is-object
npm http 304 https://registry.npmjs.org/has-ansi
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/json3
npm http GET https://registry.npmjs.org/benchmark
npm http GET https://registry.npmjs.org/commander
npm http GET https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/is-object/-/is-object-1.0.1.tgz
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/object-keys
npm http 304 https://registry.npmjs.org/json3
npm http 304 https://registry.npmjs.org/commander
npm http 304 https://registry.npmjs.org/benchmark
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 200 https://registry.npmjs.org/is-object/-/is-object-1.0.1.tgz
npm http GET https://registry.npmjs.org/wrappy
npm http 304 https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/callsite
npm http 304 https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/inflight
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/define-properties
npm http GET https://registry.npmjs.org/es-abstract
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/wrappy
npm http GET https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/json-schema
npm http GET https://registry.npmjs.org/verror
npm http GET https://registry.npmjs.org/ansi-regex
npm http GET https://registry.npmjs.org/color-convert
npm http 200 https://registry.npmjs.org/define-properties
npm http 304 https://registry.npmjs.org/callsite
npm http GET https://registry.npmjs.org/define-properties/-/define-properties-1.1.2.tgz
npm http 200 https://registry.npmjs.org/es-abstract
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/inflight
npm http 304 https://registry.npmjs.org/json-schema
npm http 304 https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.0.tgz
npm http 304 https://registry.npmjs.org/verror
npm http 304 https://registry.npmjs.org/ansi-regex
npm http 304 https://registry.npmjs.org/color-convert
npm http GET https://registry.npmjs.org/pseudomap
npm http GET https://registry.npmjs.org/yallist
npm http 200 https://registry.npmjs.org/define-properties/-/define-properties-1.1.2.tgz
npm http 304 https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/graceful-readlink
npm http 200 https://registry.npmjs.org/es-abstract/-/es-abstract-1.5.0.tgz
npm http 304 https://registry.npmjs.org/yallist
npm http 304 https://registry.npmjs.org/pseudomap
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/xmlhttprequest-ssl
npm http GET https://registry.npmjs.org/engine.io-parser
npm http GET https://registry.npmjs.org/parsejson
npm http GET https://registry.npmjs.org/parseqs
npm http GET https://registry.npmjs.org/component-inherit
npm http GET https://registry.npmjs.org/yeast
npm http GET https://registry.npmjs.org/has-cors
npm http GET https://registry.npmjs.org/ws
npm http GET https://registry.npmjs.org/ast-types
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/brace-expansion
npm http 304 https://registry.npmjs.org/engine.io-parser
npm http 304 https://registry.npmjs.org/parsejson
npm http 304 https://registry.npmjs.org/parseqs
npm http 304 https://registry.npmjs.org/component-inherit
npm http 304 https://registry.npmjs.org/xmlhttprequest-ssl
npm http 304 https://registry.npmjs.org/yeast
npm http 304 https://registry.npmjs.org/has-cors
npm http 304 https://registry.npmjs.org/ws
npm http 304 https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/private
npm http 304 https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/dashdash
npm http GET https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/arraybuffer.slice
npm http GET https://registry.npmjs.org/base64-arraybuffer
npm http GET https://registry.npmjs.org/blob
npm http GET https://registry.npmjs.org/utf8
npm http GET https://registry.npmjs.org/after
npm http GET https://registry.npmjs.org/is-callable
npm http GET https://registry.npmjs.org/es-to-primitive
npm http GET https://registry.npmjs.org/is-regex
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/blob
npm http 304 https://registry.npmjs.org/utf8
npm http 304 https://registry.npmjs.org/after
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/sntp
npm http GET https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/boom
npm http 200 https://registry.npmjs.org/es-to-primitive
npm http GET https://registry.npmjs.org/es-to-primitive/-/es-to-primitive-1.1.1.tgz
npm http 200 https://registry.npmjs.org/is-regex
npm http GET https://registry.npmjs.org/is-regex/-/is-regex-1.0.3.tgz
npm http 304 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/is-callable
npm http 304 https://registry.npmjs.org/generate-function
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/formidable
npm http GET https://registry.npmjs.org/options
npm http GET https://registry.npmjs.org/ultron
npm http GET https://registry.npmjs.org/cookiejar
npm http GET https://registry.npmjs.org/reduce-component
npm http GET https://registry.npmjs.org/is-callable/-/is-callable-1.1.3.tgz
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/base64-arraybuffer
npm http GET https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/arraybuffer.slice
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/hoek
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/options
npm http 304 https://registry.npmjs.org/ultron
npm http 200 https://registry.npmjs.org/formidable
npm http 200 https://registry.npmjs.org/cookiejar
npm http 200 https://registry.npmjs.org/es-to-primitive/-/es-to-primitive-1.1.1.tgz
npm http 304 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/reduce-component
npm http 200 https://registry.npmjs.org/is-regex/-/is-regex-1.0.3.tgz
npm http GET https://registry.npmjs.org/cookiejar/-/cookiejar-2.0.6.tgz
npm http GET https://registry.npmjs.org/formidable/-/formidable-1.0.17.tgz
npm http GET https://registry.npmjs.org/reduce-component/-/reduce-component-1.0.1.tgz
npm http GET https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.27-1.tgz
npm http 200 https://registry.npmjs.org/is-callable/-/is-callable-1.1.3.tgz
npm http 200 https://registry.npmjs.org/formidable/-/formidable-1.0.17.tgz
npm http 200 https://registry.npmjs.org/cookiejar/-/cookiejar-2.0.6.tgz
npm http 200 https://registry.npmjs.org/reduce-component/-/reduce-component-1.0.1.tgz
npm http 200 https://registry.npmjs.org/readable-stream/-/readable-stream-1.0.27-1.tgz
npm http GET https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/is-date-object
npm http GET https://registry.npmjs.org/is-symbol
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/inherits
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/combined-stream
npm http 200 https://registry.npmjs.org/is-symbol
npm http 200 https://registry.npmjs.org/is-date-object
npm http 304 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/is-symbol/-/is-symbol-1.0.1.tgz
npm http GET https://registry.npmjs.org/is-date-object/-/is-date-object-1.0.1.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/is-date-object/-/is-date-object-1.0.1.tgz
npm http 200 https://registry.npmjs.org/is-symbol/-/is-symbol-1.0.1.tgz
npm http GET https://registry.npmjs.org/chai
npm http GET https://registry.npmjs.org/propagate
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/deep-equal
npm http GET https://registry.npmjs.org/lodash
npm http GET https://registry.npmjs.org/mkdirp
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 304 https://registry.npmjs.org/deep-equal
npm http 304 https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/mkdirp
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http GET https://registry.npmjs.org/lodash/-/lodash-2.4.1.tgz
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/propagate
npm http GET https://registry.npmjs.org/debug/-/debug-1.0.4.tgz
npm http GET https://registry.npmjs.org/propagate/-/propagate-0.3.1.tgz
npm http 200 https://registry.npmjs.org/chai
npm http GET https://registry.npmjs.org/chai/-/chai-3.5.0.tgz
npm http 200 https://registry.npmjs.org/debug/-/debug-1.0.4.tgz
npm http 200 https://registry.npmjs.org/propagate/-/propagate-0.3.1.tgz
npm http 200 https://registry.npmjs.org/lodash/-/lodash-2.4.1.tgz
npm http GET https://registry.npmjs.org/basic-auth
npm http 200 https://registry.npmjs.org/chai/-/chai-3.5.0.tgz
npm http GET https://registry.npmjs.org/cookie-parser
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/header-case-normalizer
npm http GET https://registry.npmjs.org/multiparty
npm http GET https://registry.npmjs.org/pouchdb-all-dbs
npm http GET https://registry.npmjs.org/pouchdb-auth
npm http GET https://registry.npmjs.org/pouchdb-find
npm http GET https://registry.npmjs.org/pouchdb-list
npm http GET https://registry.npmjs.org/pouchdb-replicator
npm http GET https://registry.npmjs.org/pouchdb-rewrite
npm http GET https://registry.npmjs.org/pouchdb-security
npm http GET https://registry.npmjs.org/compression
npm http GET https://registry.npmjs.org/pouchdb-show
npm http GET https://registry.npmjs.org/pouchdb-size
npm http GET https://registry.npmjs.org/pouchdb-update
npm http GET https://registry.npmjs.org/pouchdb-validation
npm http GET https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/pouchdb-vhost
npm http GET https://registry.npmjs.org/pouchdb-wrappers
npm http GET https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/on-finished
npm http GET https://registry.npmjs.org/raw-body
npm http GET https://registry.npmjs.org/argsarray
npm http GET https://registry.npmjs.org/double-ended-queue
npm http GET https://registry.npmjs.org/fruitdown
npm http GET https://registry.npmjs.org/js-extend
npm http GET https://registry.npmjs.org/level-sublevel
npm http GET https://registry.npmjs.org/level-write-stream
npm http GET https://registry.npmjs.org/levelup
npm http GET https://registry.npmjs.org/localstorage-down
npm http GET https://registry.npmjs.org/memdown
npm http GET https://registry.npmjs.org/pouchdb-collate
npm http GET https://registry.npmjs.org/pouchdb-collections
npm http GET https://registry.npmjs.org/scope-eval
npm http GET https://registry.npmjs.org/spark-md5
npm http GET https://registry.npmjs.org/vuvuzela
npm http GET https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/request
npm http GET https://registry.npmjs.org/through2
npm http 200 https://registry.npmjs.org/basic-auth
npm http 304 https://registry.npmjs.org/bluebird
npm http 200 https://registry.npmjs.org/cookie-parser
npm http GET https://registry.npmjs.org/bindings
npm http GET https://registry.npmjs.org/abstract-leveldown
npm http GET https://registry.npmjs.org/fast-future
npm http GET https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.3.tgz
npm http GET https://registry.npmjs.org/cookie-parser/-/cookie-parser-1.4.1.tgz
npm http 200 https://registry.npmjs.org/multiparty
npm http 200 https://registry.npmjs.org/pouchdb-auth
npm http 200 https://registry.npmjs.org/header-case-normalizer
npm http GET https://registry.npmjs.org/multiparty/-/multiparty-3.3.2.tgz
npm http GET https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-1.0.5.tgz
npm http GET https://registry.npmjs.org/header-case-normalizer/-/header-case-normalizer-1.0.3.tgz
npm http GET https://registry.npmjs.org/ms
npm http GET https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/pouchdb-find
npm http 200 https://registry.npmjs.org/pouchdb-list
npm http GET https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.1.0.tgz
npm http GET https://registry.npmjs.org/pouchdb-list/-/pouchdb-list-1.1.0.tgz
npm http 200 https://registry.npmjs.org/basic-auth/-/basic-auth-1.0.3.tgz
npm http 200 https://registry.npmjs.org/cookie-parser/-/cookie-parser-1.4.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-rewrite
npm http 304 https://registry.npmjs.org/compression
npm http GET https://registry.npmjs.org/pouchdb-rewrite/-/pouchdb-rewrite-1.0.7.tgz
npm http 200 https://registry.npmjs.org/multiparty/-/multiparty-3.3.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb-list/-/pouchdb-list-1.1.0.tgz
npm http 200 https://registry.npmjs.org/header-case-normalizer/-/header-case-normalizer-1.0.3.tgz
npm http 200 https://registry.npmjs.org/pouchdb-auth/-/pouchdb-auth-1.0.5.tgz
npm http 200 https://registry.npmjs.org/pouchdb-find/-/pouchdb-find-0.1.0.tgz
npm http GET https://registry.npmjs.org/type-detect
npm http GET https://registry.npmjs.org/assertion-error
npm http GET https://registry.npmjs.org/deep-eql
npm http 200 https://registry.npmjs.org/pouchdb-size
npm http GET https://registry.npmjs.org/pouchdb-size/-/pouchdb-size-1.2.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb-rewrite/-/pouchdb-rewrite-1.0.7.tgz
npm http 200 https://registry.npmjs.org/pouchdb-replicator
npm http GET https://registry.npmjs.org/pouchdb-replicator/-/pouchdb-replicator-2.1.3.tgz
npm http 200 https://registry.npmjs.org/pouchdb-all-dbs
npm http 200 https://registry.npmjs.org/pouchdb-show
npm http GET https://registry.npmjs.org/formatio
npm http GET https://registry.npmjs.org/lolex
npm http GET https://registry.npmjs.org/samsam
npm http GET https://registry.npmjs.org/util
npm http GET https://registry.npmjs.org/pouchdb-show/-/pouchdb-show-1.0.8.tgz
npm http GET https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-security
npm http GET https://registry.npmjs.org/pouchdb-security/-/pouchdb-security-1.2.6.tgz
npm http 304 https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/extend/-/extend-1.3.0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-validation
npm http GET https://registry.npmjs.org/pouchdb-validation/-/pouchdb-validation-1.2.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-vhost
npm http 304 https://registry.npmjs.org/node-uuid
npm http GET https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.1.tgz
npm http GET https://registry.npmjs.org/pouchdb-vhost/-/pouchdb-vhost-1.0.2.tgz
npm http 304 https://registry.npmjs.org/on-finished
npm http 200 https://registry.npmjs.org/pouchdb-update
npm http GET https://registry.npmjs.org/pouchdb-update/-/pouchdb-update-1.0.8.tgz
npm http 304 https://registry.npmjs.org/raw-body
npm http GET https://registry.npmjs.org/raw-body/-/raw-body-1.3.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-replicator/-/pouchdb-replicator-2.1.3.tgz
npm http 200 https://registry.npmjs.org/pouchdb-wrappers
npm http GET https://registry.npmjs.org/pouchdb-wrappers/-/pouchdb-wrappers-1.3.6.tgz
npm http 200 https://registry.npmjs.org/pouchdb-show/-/pouchdb-show-1.0.8.tgz
npm http 200 https://registry.npmjs.org/double-ended-queue
npm http GET https://registry.npmjs.org/double-ended-queue/-/double-ended-queue-2.0.0-0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-security/-/pouchdb-security-1.2.6.tgz
npm http 200 https://registry.npmjs.org/extend/-/extend-1.3.0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-all-dbs/-/pouchdb-all-dbs-1.0.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-validation/-/pouchdb-validation-1.2.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-vhost/-/pouchdb-vhost-1.0.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb-size/-/pouchdb-size-1.2.2.tgz
npm http 200 https://registry.npmjs.org/node-uuid/-/node-uuid-1.4.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-update/-/pouchdb-update-1.0.8.tgz
npm http 200 https://registry.npmjs.org/fruitdown
npm http GET https://registry.npmjs.org/fruitdown/-/fruitdown-1.0.1.tgz
npm http 200 https://registry.npmjs.org/js-extend
npm http GET https://registry.npmjs.org/js-extend/-/js-extend-1.0.1.tgz
npm http 200 https://registry.npmjs.org/raw-body/-/raw-body-1.3.4.tgz
npm http 200 https://registry.npmjs.org/level-write-stream
npm http GET https://registry.npmjs.org/level-write-stream/-/level-write-stream-1.0.0.tgz
npm http 200 https://registry.npmjs.org/js-extend/-/js-extend-1.0.1.tgz
npm http 200 https://registry.npmjs.org/argsarray
npm http GET https://registry.npmjs.org/argsarray/-/argsarray-0.0.1.tgz
npm http 200 https://registry.npmjs.org/level-write-stream/-/level-write-stream-1.0.0.tgz
npm http 200 https://registry.npmjs.org/memdown
npm http 200 https://registry.npmjs.org/double-ended-queue/-/double-ended-queue-2.0.0-0.tgz
npm http 200 https://registry.npmjs.org/fruitdown/-/fruitdown-1.0.1.tgz
npm http GET https://registry.npmjs.org/memdown/-/memdown-1.1.2.tgz
npm http 200 https://registry.npmjs.org/argsarray/-/argsarray-0.0.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-wrappers/-/pouchdb-wrappers-1.3.6.tgz
npm http 200 https://registry.npmjs.org/pouchdb-collections
npm http GET https://registry.npmjs.org/pouchdb-collections/-/pouchdb-collections-1.0.1.tgz
npm http 200 https://registry.npmjs.org/localstorage-down
npm http GET https://registry.npmjs.org/localstorage-down/-/localstorage-down-0.6.6.tgz
npm http 200 https://registry.npmjs.org/scope-eval
npm http 200 https://registry.npmjs.org/levelup
npm http 200 https://registry.npmjs.org/level-sublevel
npm http 200 https://registry.npmjs.org/memdown/-/memdown-1.1.2.tgz
npm http GET https://registry.npmjs.org/scope-eval/-/scope-eval-0.0.3.tgz
npm http GET https://registry.npmjs.org/levelup/-/levelup-1.3.1.tgz
npm http GET https://registry.npmjs.org/level-sublevel/-/level-sublevel-6.5.4.tgz
npm http 304 https://registry.npmjs.org/request
npm http 304 https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/es3ify/-/es3ify-0.2.0.tgz
npm http GET https://registry.npmjs.org/request/-/request-2.67.0.tgz
npm http 304 https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/through2/-/through2-2.0.0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-collections/-/pouchdb-collections-1.0.1.tgz
npm http 200 https://registry.npmjs.org/localstorage-down/-/localstorage-down-0.6.6.tgz
npm http 200 https://registry.npmjs.org/bindings
npm http 200 https://registry.npmjs.org/vuvuzela
npm http GET https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.2.tgz
npm http 304 https://registry.npmjs.org/ms
npm http 200 https://registry.npmjs.org/es3ify/-/es3ify-0.2.0.tgz
npm http GET https://registry.npmjs.org/ms/-/ms-0.6.2.tgz
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http 200 https://registry.npmjs.org/pouchdb-collate
npm http GET https://registry.npmjs.org/pouchdb-collate/-/pouchdb-collate-1.2.0.tgz
npm http 200 https://registry.npmjs.org/levelup/-/levelup-1.3.1.tgz
npm http 200 https://registry.npmjs.org/level-sublevel/-/level-sublevel-6.5.4.tgz
npm http 304 https://registry.npmjs.org/minimist
npm http 200 https://registry.npmjs.org/scope-eval/-/scope-eval-0.0.3.tgz
npm http 200 https://registry.npmjs.org/type-detect
npm http GET https://registry.npmjs.org/type-detect/-/type-detect-1.0.0.tgz
npm http 200 https://registry.npmjs.org/request/-/request-2.67.0.tgz
npm http 200 https://registry.npmjs.org/ms/-/ms-0.6.2.tgz
npm http 200 https://registry.npmjs.org/assertion-error
npm http 200 https://registry.npmjs.org/deep-eql
npm http GET https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.1.tgz
npm http GET https://registry.npmjs.org/deep-eql/-/deep-eql-0.1.3.tgz
npm http 200 https://registry.npmjs.org/spark-md5
npm http GET https://registry.npmjs.org/spark-md5/-/spark-md5-2.0.0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-collate/-/pouchdb-collate-1.2.0.tgz
npm http 200 https://registry.npmjs.org/formatio
npm http GET https://registry.npmjs.org/formatio/-/formatio-1.1.1.tgz
npm http 200 https://registry.npmjs.org/through2/-/through2-2.0.0.tgz
npm http 200 https://registry.npmjs.org/samsam
npm http 200 https://registry.npmjs.org/lolex
npm http 200 https://registry.npmjs.org/type-detect/-/type-detect-1.0.0.tgz
npm http GET https://registry.npmjs.org/samsam/-/samsam-1.1.2.tgz
npm http GET https://registry.npmjs.org/lolex/-/lolex-1.3.2.tgz
npm http 200 https://registry.npmjs.org/assertion-error/-/assertion-error-1.0.1.tgz
npm http 200 https://registry.npmjs.org/deep-eql/-/deep-eql-0.1.3.tgz
npm http 200 https://registry.npmjs.org/fast-future
npm http 304 https://registry.npmjs.org/util
npm http 200 https://registry.npmjs.org/spark-md5/-/spark-md5-2.0.0.tgz
npm http GET https://registry.npmjs.org/type-detect/-/type-detect-0.1.1.tgz
npm http GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/vuvuzela/-/vuvuzela-1.0.2.tgz
npm http 200 https://registry.npmjs.org/samsam/-/samsam-1.1.2.tgz
npm http 200 https://registry.npmjs.org/type-detect/-/type-detect-0.1.1.tgz
npm http GET https://registry.npmjs.org/end-stream
npm http GET https://registry.npmjs.org/ltgt
npm http GET https://registry.npmjs.org/functional-red-black-tree
npm http 200 https://registry.npmjs.org/formatio/-/formatio-1.1.1.tgz
npm http 200 https://registry.npmjs.org/lolex/-/lolex-1.3.2.tgz
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-2.4.1.tgz
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/esprima
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/d64
npm http GET https://registry.npmjs.org/humble-localstorage
npm http GET https://registry.npmjs.org/tiny-queue
npm http GET https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-0.12.3.tgz
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/through
In file included from ../src/batch.cc:4:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/batch.cc:4:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:8:
In file included from ../src/batch_async.h:15:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Batch, Clear) {
^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
16 warnings generated.
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
15 warnings generated.
In file included from ../src/database.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/database.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:18:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/database.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Database, New) {
^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/database.cc:130:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
16 warnings generated.
In file included from ../src/database_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/database_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
13 warnings generated.
In file included from ../src/iterator.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/iterator.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/iterator.cc:178:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, Next) {
^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:195:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, End) {
^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:222:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
17 warnings generated.
In file included from ../src/iterator_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/iterator_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
14 warnings generated.
In file included from ../src/leveldown.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/leveldown.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:13:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:59:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(leveldown, LeveldownWrap) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:70:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(LeveldownWrap, New) {
^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
In file included from ../src/leveldown.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
17 warnings generated.
In file included from ../src/leveldown_async.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/commons.h:34:
In file included from /Users/thali/.node-gyp/jxb310/src/jx/btree_map.h:31:
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: warning: class 'btree_internal_locate_plain_compare' was previously declared as a struct [-Wmismatched-tags]
  friend class btree_internal_locate_plain_compare;
         ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:893:8: note: previous use is here
struct btree_internal_locate_plain_compare {
       ^
/Users/thali/.node-gyp/jxb310/src/jx/btree.h:919:10: note: did you mean struct here?
  friend class btree_internal_locate_plain_compare;
         ^~~~~
         struct
In file included from ../src/leveldown_async.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb310/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb310/src/jx/commons.h:334:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb310/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
14 warnings generated.
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/functional-red-black-tree
npm http GET https://registry.npmjs.org/functional-red-black-tree/-/functional-red-black-tree-1.0.1.tgz
npm http 200 https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-2.4.1.tgz
npm http 200 https://registry.npmjs.org/esprima
npm http 200 https://registry.npmjs.org/d64
npm http GET https://registry.npmjs.org/esprima/-/esprima-2.7.2.tgz
npm http GET https://registry.npmjs.org/d64/-/d64-1.0.0.tgz
npm http GET https://registry.npmjs.org/bl
npm http GET https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/forever-agent
npm http GET https://registry.npmjs.org/form-data
npm http 200 https://registry.npmjs.org/end-stream
npm http GET https://registry.npmjs.org/json-stringify-safe
npm http GET https://registry.npmjs.org/mime-types
npm http GET https://registry.npmjs.org/qs
npm http GET https://registry.npmjs.org/tunnel-agent
npm http 304 https://registry.npmjs.org/inherits
npm http 200 https://registry.npmjs.org/tiny-queue
npm http GET https://registry.npmjs.org/tough-cookie
npm http GET https://registry.npmjs.org/oauth-sign
npm http GET https://registry.npmjs.org/http-signature
npm http GET https://registry.npmjs.org/hawk
npm http GET https://registry.npmjs.org/aws-sign2
npm http GET https://registry.npmjs.org/stringstream
npm http GET https://registry.npmjs.org/combined-stream
npm http GET https://registry.npmjs.org/isstream
npm http GET https://registry.npmjs.org/is-typedarray
npm http GET https://registry.npmjs.org/har-validator
npm http GET https://registry.npmjs.org/tiny-queue/-/tiny-queue-0.2.0.tgz
npm http GET https://registry.npmjs.org/end-stream/-/end-stream-0.1.0.tgz
npm http GET https://registry.npmjs.org/pull-stream
npm http GET https://registry.npmjs.org/ltgt
npm http GET https://registry.npmjs.org/bytewise
npm http GET https://registry.npmjs.org/typewiselite
npm http 200 https://registry.npmjs.org/ltgt
npm http 304 https://registry.npmjs.org/bl
npm http 304 https://registry.npmjs.org/forever-agent
npm http 304 https://registry.npmjs.org/caseless
npm http GET https://registry.npmjs.org/levelup/-/levelup-0.19.1.tgz
npm http 200 https://registry.npmjs.org/humble-localstorage
npm http GET https://registry.npmjs.org/ltgt/-/ltgt-1.0.2.tgz
npm http GET https://registry.npmjs.org/humble-localstorage/-/humble-localstorage-1.4.2.tgz
npm http GET https://registry.npmjs.org/deferred-leveldown
npm http GET https://registry.npmjs.org/level-codec
npm http GET https://registry.npmjs.org/level-errors
npm http GET https://registry.npmjs.org/level-iterator-stream
npm http GET https://registry.npmjs.org/prr
npm http GET https://registry.npmjs.org/semver
npm http 304 https://registry.npmjs.org/form-data
npm http 304 https://registry.npmjs.org/json-stringify-safe
npm http 304 https://registry.npmjs.org/mime-types
npm http 304 https://registry.npmjs.org/qs
npm http 304 https://registry.npmjs.org/tunnel-agent
npm http GET https://registry.npmjs.org/qs/-/qs-5.2.0.tgz
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/process-nextick-args
npm http GET https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/util-deprecate
npm http 200 https://registry.npmjs.org/functional-red-black-tree/-/functional-red-black-tree-1.0.1.tgz
npm http 304 https://registry.npmjs.org/tough-cookie
npm http 304 https://registry.npmjs.org/http-signature
npm http 304 https://registry.npmjs.org/hawk
npm http 304 https://registry.npmjs.org/oauth-sign
npm http 304 https://registry.npmjs.org/aws-sign2
npm http 200 https://registry.npmjs.org/tiny-queue/-/tiny-queue-0.2.0.tgz
npm http 304 https://registry.npmjs.org/is-typedarray
npm http 304 https://registry.npmjs.org/stringstream
npm http 304 https://registry.npmjs.org/combined-stream
npm http 304 https://registry.npmjs.org/isstream
npm http 304 https://registry.npmjs.org/har-validator
npm http 200 https://registry.npmjs.org/end-stream/-/end-stream-0.1.0.tgz
npm http GET https://registry.npmjs.org/write-stream
npm http 200 https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-0.12.3.tgz
npm http 200 https://registry.npmjs.org/ltgt/-/ltgt-1.0.2.tgz
npm http 200 https://registry.npmjs.org/levelup/-/levelup-0.19.1.tgz
npm http 200 https://registry.npmjs.org/d64/-/d64-1.0.0.tgz
npm http 200 https://registry.npmjs.org/esprima/-/esprima-2.7.2.tgz
npm http 200 https://registry.npmjs.org/qs/-/qs-5.2.0.tgz
npm http 200 https://registry.npmjs.org/typewiselite
npm http GET https://registry.npmjs.org/delayed-stream
npm http GET https://registry.npmjs.org/typewiselite/-/typewiselite-1.0.0.tgz
npm http GET https://registry.npmjs.org/mime-db
npm http 200 https://registry.npmjs.org/deferred-leveldown
npm http 200 https://registry.npmjs.org/ltgt
npm http GET https://registry.npmjs.org/async
npm http GET https://registry.npmjs.org/ltgt/-/ltgt-2.1.2.tgz
npm http GET https://registry.npmjs.org/deferred-leveldown/-/deferred-leveldown-1.2.1.tgz
npm http 200 https://registry.npmjs.org/pull-stream
npm http 200 https://registry.npmjs.org/level-iterator-stream
npm http 200 https://registry.npmjs.org/prr
npm http GET https://registry.npmjs.org/pull-stream/-/pull-stream-2.21.0.tgz
npm http GET https://registry.npmjs.org/level-iterator-stream/-/level-iterator-stream-1.3.1.tgz
npm http GET https://registry.npmjs.org/prr/-/prr-1.0.1.tgz
npm http 304 https://registry.npmjs.org/semver
npm http 200 https://registry.npmjs.org/typewiselite/-/typewiselite-1.0.0.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 200 https://registry.npmjs.org/level-errors
npm http 304 https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/level-errors/-/level-errors-1.0.4.tgz
npm http 200 https://registry.npmjs.org/bytewise
npm http GET https://registry.npmjs.org/sshpk
npm http GET https://registry.npmjs.org/assert-plus
npm http GET https://registry.npmjs.org/jsprim
npm http GET https://registry.npmjs.org/bytewise/-/bytewise-1.1.0.tgz
npm http GET https://registry.npmjs.org/chalk
npm http GET https://registry.npmjs.org/commander
npm http GET https://registry.npmjs.org/is-my-json-valid
npm http GET https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/level-codec
npm http 304 https://registry.npmjs.org/string_decoder
npm http 304 https://registry.npmjs.org/process-nextick-args
npm http 304 https://registry.npmjs.org/util-deprecate
npm http GET https://registry.npmjs.org/level-codec/-/level-codec-6.1.0.tgz
npm http 200 https://registry.npmjs.org/humble-localstorage/-/humble-localstorage-1.4.2.tgz
npm http 304 https://registry.npmjs.org/sshpk
npm http 304 https://registry.npmjs.org/async
npm http 200 https://registry.npmjs.org/write-stream
npm http 304 https://registry.npmjs.org/mime-db
npm http 304 https://registry.npmjs.org/delayed-stream
npm http 200 https://registry.npmjs.org/level-iterator-stream/-/level-iterator-stream-1.3.1.tgz
npm http 200 https://registry.npmjs.org/prr/-/prr-1.0.1.tgz
npm http GET https://registry.npmjs.org/write-stream/-/write-stream-0.4.3.tgz
npm http 304 https://registry.npmjs.org/assert-plus
npm http 200 https://registry.npmjs.org/level-errors/-/level-errors-1.0.4.tgz
npm http 304 https://registry.npmjs.org/is-my-json-valid
npm http 304 https://registry.npmjs.org/chalk
npm http 304 https://registry.npmjs.org/jsprim
npm http 304 https://registry.npmjs.org/commander
npm http 200 https://registry.npmjs.org/bytewise/-/bytewise-1.1.0.tgz
npm http 200 https://registry.npmjs.org/ltgt/-/ltgt-2.1.2.tgz
npm http 200 https://registry.npmjs.org/pull-stream/-/pull-stream-2.21.0.tgz
npm http 304 https://registry.npmjs.org/pinkie-promise
npm http 200 https://registry.npmjs.org/write-stream/-/write-stream-0.4.3.tgz
npm http 200 https://registry.npmjs.org/level-codec/-/level-codec-6.1.0.tgz
npm http 200 https://registry.npmjs.org/deferred-leveldown/-/deferred-leveldown-1.2.1.tgz
npm http GET https://registry.npmjs.org/couchdb-objects
npm http GET https://registry.npmjs.org/couchdb-eval
npm http GET https://registry.npmjs.org/pouchdb-promise
npm http GET https://registry.npmjs.org/random-uuid-v4
npm http GET https://registry.npmjs.org/pouchdb-plugin-error
npm http GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http GET https://registry.npmjs.org/promise-nodify
npm http GET https://registry.npmjs.org/ee-first
npm http GET https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/iconv-lite
npm http GET https://registry.npmjs.org/get-folder-size
npm http GET https://registry.npmjs.org/pinkie
npm http GET https://registry.npmjs.org/accepts
npm http GET https://registry.npmjs.org/bytes
npm http GET https://registry.npmjs.org/compressible
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/vary
npm http GET https://registry.npmjs.org/on-headers
npm http GET https://registry.npmjs.org/promise-nodify
npm http GET https://registry.npmjs.org/pouchdb-route
npm http GET https://registry.npmjs.org/secure-random
npm http GET https://registry.npmjs.org/crypto-lite
npm http GET https://registry.npmjs.org/pouchdb-req-http-query
npm http GET https://registry.npmjs.org/pouchdb-system-db
npm http GET https://registry.npmjs.org/strip-ansi
npm http GET https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/ansi-styles
npm http GET https://registry.npmjs.org/escape-string-regexp
npm http GET https://registry.npmjs.org/pouchdb-req-http-query
npm http GET https://registry.npmjs.org/couchdb-resp-completer
npm http GET https://registry.npmjs.org/has-ansi
npm http GET https://registry.npmjs.org/couchdb-render
npm http GET https://registry.npmjs.org/equals
npm http GET https://registry.npmjs.org/extend
npm http GET https://registry.npmjs.org/extsprintf
npm http GET https://registry.npmjs.org/json-schema
npm http GET https://registry.npmjs.org/verror
npm http GET https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http GET https://registry.npmjs.org/errno
npm http GET https://registry.npmjs.org/readable-stream/-/readable-stream-0.0.4.tgz
npm http GET https://registry.npmjs.org/stream-counter
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/source-map
npm http GET https://registry.npmjs.org/bytewise-core
npm http GET https://registry.npmjs.org/typewise
npm http GET https://registry.npmjs.org/graceful-readlink
npm http GET https://registry.npmjs.org/has-localstorage
npm http GET https://registry.npmjs.org/localstorage-memory
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/tiny-queue/-/tiny-queue-0.2.1.tgz
npm http 200 https://registry.npmjs.org/couchdb-eval
npm http 200 https://registry.npmjs.org/couchdb-objects
npm http 200 https://registry.npmjs.org/pouchdb-promise
npm http GET https://registry.npmjs.org/couchdb-eval/-/couchdb-eval-1.0.6.tgz
npm http GET https://registry.npmjs.org/couchdb-objects/-/couchdb-objects-1.0.7.tgz
npm http GET https://registry.npmjs.org/pull-core
npm http GET https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-0.0.0.tgz
npm http 200 https://registry.npmjs.org/pouchdb-plugin-error
npm http 200 https://registry.npmjs.org/readable-stream/-/readable-stream-0.0.4.tgz
npm http 200 https://registry.npmjs.org/random-uuid-v4
npm http GET https://registry.npmjs.org/pouchdb-plugin-error/-/pouchdb-plugin-error-1.0.1.tgz
npm http GET https://registry.npmjs.org/random-uuid-v4/-/random-uuid-v4-0.0.4.tgz
npm http 304 https://registry.npmjs.org/ee-first
npm http 304 https://registry.npmjs.org/cookie
npm http GET https://registry.npmjs.org/cookie/-/cookie-0.2.3.tgz
npm http 304 https://registry.npmjs.org/cookie-signature
npm http GET https://registry.npmjs.org/asn1
npm http GET https://registry.npmjs.org/dashdash
npm http 200 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper
npm http 200 https://registry.npmjs.org/promise-nodify
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/iconv-lite
npm http 200 https://registry.npmjs.org/pouchdb-plugin-error/-/pouchdb-plugin-error-1.0.1.tgz
npm http GET https://registry.npmjs.org/pouchdb-bulkdocs-wrapper/-/pouchdb-bulkdocs-wrapper-1.0.2.tgz
npm http GET https://registry.npmjs.org/promise-nodify/-/promise-nodify-1.0.2.tgz
npm http GET https://registry.npmjs.org/bytes/-/bytes-1.0.0.tgz
npm http GET https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.8.tgz
npm http GET https://registry.npmjs.org/hoek
npm http GET https://registry.npmjs.org/boom
npm http GET https://registry.npmjs.org/cryptiles
npm http GET https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/bytes
npm http 304 https://registry.npmjs.org/pinkie
npm http 304 https://registry.npmjs.org/compressible
npm http 200 https://registry.npmjs.org/random-uuid-v4/-/random-uuid-v4-0.0.4.tgz
npm http 304 https://registry.npmjs.org/accepts
npm http 200 https://registry.npmjs.org/tiny-queue/-/tiny-queue-0.2.1.tgz
npm http GET https://registry.npmjs.org/generate-function
npm http GET https://registry.npmjs.org/generate-object-property
npm http GET https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/couchdb-objects/-/couchdb-objects-1.0.7.tgz
npm http 304 https://registry.npmjs.org/vary
npm http 200 https://registry.npmjs.org/couchdb-eval/-/couchdb-eval-1.0.6.tgz
npm http 200 https://registry.npmjs.org/pouchdb-promise/-/pouchdb-promise-0.0.0.tgz
npm http 304 https://registry.npmjs.org/on-headers
npm http 200 https://registry.npmjs.org/cookie/-/cookie-0.2.3.tgz
npm http 200 https://registry.npmjs.org/promise-nodify
npm http 200 https://registry.npmjs.org/pouchdb-bulkdocs-wrapper/-/pouchdb-bulkdocs-wrapper-1.0.2.tgz
npm http 200 https://registry.npmjs.org/bytes/-/bytes-1.0.0.tgz
npm http 200 https://registry.npmjs.org/promise-nodify/-/promise-nodify-1.0.2.tgz
npm http 200 https://registry.npmjs.org/pouchdb-route
npm http 200 https://registry.npmjs.org/get-folder-size
npm http 200 https://registry.npmjs.org/iconv-lite/-/iconv-lite-0.4.8.tgz
npm http GET https://registry.npmjs.org/lie
npm http GET https://registry.npmjs.org/bluebird
npm http GET https://registry.npmjs.org/pouchdb-route/-/pouchdb-route-1.0.3.tgz
npm http 200 https://registry.npmjs.org/pouchdb-req-http-query
npm http GET https://registry.npmjs.org/get-folder-size/-/get-folder-size-0.1.1.tgz
npm http GET https://registry.npmjs.org/is-empty
npm http GET https://registry.npmjs.org/pouchdb-req-http-query/-/pouchdb-req-http-query-1.0.3.tgz
npm http 200 https://registry.npmjs.org/crypto-lite
npm http GET https://registry.npmjs.org/negotiator
npm http 304 https://registry.npmjs.org/strip-ansi
npm http 200 https://registry.npmjs.org/secure-random
npm http GET https://registry.npmjs.org/crypto-lite/-/crypto-lite-0.0.4.tgz
npm http GET https://registry.npmjs.org/secure-random/-/secure-random-1.1.1.tgz
npm http GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/supports-color
npm http GET https://registry.npmjs.org/prr/-/prr-0.0.0.tgz
npm http GET https://registry.npmjs.org/deferred-leveldown/-/deferred-leveldown-0.2.0.tgz
npm http GET https://registry.npmjs.org/bl/-/bl-0.8.2.tgz
npm http 304 https://registry.npmjs.org/ansi-styles
npm http 304 https://registry.npmjs.org/escape-string-regexp
npm http 304 https://registry.npmjs.org/has-ansi
npm http 200 https://registry.npmjs.org/couchdb-render
npm http GET https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/pouchdb-system-db
npm http GET https://registry.npmjs.org/color-convert
npm http GET https://registry.npmjs.org/couchdb-render/-/couchdb-render-1.0.1.tgz
npm http GET https://registry.npmjs.org/pouchdb-system-db/-/pouchdb-system-db-1.0.4.tgz
npm http 200 https://registry.npmjs.org/pouchdb-req-http-query
npm http 200 https://registry.npmjs.org/get-folder-size/-/get-folder-size-0.1.1.tgz
npm http 200 https://registry.npmjs.org/equals
npm http GET https://registry.npmjs.org/equals/-/equals-1.0.1.tgz
npm http GET https://registry.npmjs.org/minimist/-/minimist-0.1.0.tgz
npm http 304 https://registry.npmjs.org/extend
npm http 304 https://registry.npmjs.org/extsprintf
npm http 304 https://registry.npmjs.org/json-schema
npm http 200 https://registry.npmjs.org/secure-random/-/secure-random-1.1.1.tgz
npm http 304 https://registry.npmjs.org/verror
npm http 200 https://registry.npmjs.org/stream-counter
npm http 200 https://registry.npmjs.org/errno
npm http 200 https://registry.npmjs.org/prr/-/prr-0.0.0.tgz
npm http 200 https://registry.npmjs.org/deferred-leveldown/-/deferred-leveldown-0.2.0.tgz
npm http GET https://registry.npmjs.org/stream-counter/-/stream-counter-0.2.0.tgz
npm http GET https://registry.npmjs.org/errno/-/errno-0.1.4.tgz
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 200 https://registry.npmjs.org/couchdb-render/-/couchdb-render-1.0.1.tgz
npm http 200 https://registry.npmjs.org/pouchdb-route/-/pouchdb-route-1.0.3.tgz
npm http 304 https://registry.npmjs.org/source-map
npm http 200 https://registry.npmjs.org/pouchdb-changeslike-wrapper
npm http 200 https://registry.npmjs.org/crypto-lite/-/crypto-lite-0.0.4.tgz
npm http GET https://registry.npmjs.org/pouchdb-changeslike-wrapper/-/pouchdb-changeslike-wrapper-1.0.1.tgz
npm http 304 https://registry.npmjs.org/graceful-readlink
npm http 200 https://registry.npmjs.org/pouchdb-system-db/-/pouchdb-system-db-1.0.4.tgz
npm http 200 https://registry.npmjs.org/equals/-/equals-1.0.1.tgz
npm http 200 https://registry.npmjs.org/bytewise-core
npm http 200 https://registry.npmjs.org/minimist/-/minimist-0.1.0.tgz
npm http GET https://registry.npmjs.org/bytewise-core/-/bytewise-core-1.2.3.tgz
npm http 200 https://registry.npmjs.org/stream-counter/-/stream-counter-0.2.0.tgz
npm http 200 https://registry.npmjs.org/errno/-/errno-0.1.4.tgz
npm http 200 https://registry.npmjs.org/has-localstorage
npm http 200 https://registry.npmjs.org/pouchdb-changeslike-wrapper/-/pouchdb-changeslike-wrapper-1.0.1.tgz
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/bytewise-core/-/bytewise-core-1.2.3.tgz
npm http 200 https://registry.npmjs.org/typewise
npm http 200 https://registry.npmjs.org/couchdb-resp-completer
npm http 200 https://registry.npmjs.org/localstorage-memory
npm http GET https://registry.npmjs.org/has-localstorage/-/has-localstorage-1.0.1.tgz
npm http GET https://registry.npmjs.org/lie/-/lie-2.9.1.tgz
npm http GET https://registry.npmjs.org/typewise/-/typewise-1.0.3.tgz
npm http GET https://registry.npmjs.org/couchdb-resp-completer/-/couchdb-resp-completer-1.0.3.tgz
npm http GET https://registry.npmjs.org/localstorage-memory/-/localstorage-memory-1.0.2.tgz
npm http 304 https://registry.npmjs.org/asn1
npm http 304 https://registry.npmjs.org/dashdash
npm http 304 https://registry.npmjs.org/boom
npm http 304 https://registry.npmjs.org/hoek
npm http 200 https://registry.npmjs.org/bl/-/bl-0.8.2.tgz
npm http 304 https://registry.npmjs.org/sntp
npm http 304 https://registry.npmjs.org/cryptiles
npm http 304 https://registry.npmjs.org/generate-object-property
npm http 304 https://registry.npmjs.org/generate-function
npm http 200 https://registry.npmjs.org/pull-core
npm http GET https://registry.npmjs.org/jkroso-type
npm http 304 https://registry.npmjs.org/jsonpointer
npm http 304 https://registry.npmjs.org/lie
npm http 200 https://registry.npmjs.org/couchdb-resp-completer/-/couchdb-resp-completer-1.0.3.tgz
npm http 304 https://registry.npmjs.org/bluebird
npm http 304 https://registry.npmjs.org/negotiator
npm http GET https://registry.npmjs.org/pull-core/-/pull-core-1.0.0.tgz
npm http 304 https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/ansi-regex
npm http 200 https://registry.npmjs.org/pouchdb-req-http-query/-/pouchdb-req-http-query-1.0.3.tgz
npm http 304 https://registry.npmjs.org/color-convert
npm http GET https://registry.npmjs.org/lie/-/lie-2.7.7.tgz
npm http GET https://registry.npmjs.org/bluebird/-/bluebird-1.2.4.tgz
npm http 200 https://registry.npmjs.org/is-empty
npm http 200 https://registry.npmjs.org/jkroso-type
npm http 200 https://registry.npmjs.org/localstorage-memory/-/localstorage-memory-1.0.2.tgz
npm http 200 https://registry.npmjs.org/typewise/-/typewise-1.0.3.tgz
npm http 200 https://registry.npmjs.org/has-localstorage/-/has-localstorage-1.0.1.tgz
npm http 200 https://registry.npmjs.org/pull-core/-/pull-core-1.0.0.tgz
npm http GET https://registry.npmjs.org/is-empty/-/is-empty-0.0.1.tgz
npm http GET https://registry.npmjs.org/jkroso-type/-/jkroso-type-1.1.1.tgz
npm http 200 https://registry.npmjs.org/lie/-/lie-2.7.7.tgz
npm http 200 https://registry.npmjs.org/lie/-/lie-2.9.1.tgz
npm http 200 https://registry.npmjs.org/bluebird/-/bluebird-1.2.4.tgz
npm http 200 https://registry.npmjs.org/is-empty/-/is-empty-0.0.1.tgz
npm http 200 https://registry.npmjs.org/jkroso-type/-/jkroso-type-1.1.1.tgz
npm http GET https://registry.npmjs.org/xmlhttprequest-cookie
npm http GET https://registry.npmjs.org/abstract-leveldown
npm http GET https://registry.npmjs.org/typewise-core
npm http 200 https://registry.npmjs.org/xmlhttprequest-cookie
npm http 304 https://registry.npmjs.org/abstract-leveldown
npm http GET https://registry.npmjs.org/xmlhttprequest-cookie/-/xmlhttprequest-cookie-0.9.4.tgz
npm http GET https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-0.12.4.tgz
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/typewise-core
npm http 200 https://registry.npmjs.org/typewise-core
npm http GET https://registry.npmjs.org/typewise-core/-/typewise-core-1.2.0.tgz
npm http 304 https://registry.npmjs.org/jstransform
npm http 304 https://registry.npmjs.org/through
npm http 200 https://registry.npmjs.org/xmlhttprequest-cookie/-/xmlhttprequest-cookie-0.9.4.tgz
npm http 304 https://registry.npmjs.org/inherits
npm http GET https://registry.npmjs.org/immediate
npm http 200 https://registry.npmjs.org/abstract-leveldown/-/abstract-leveldown-0.12.4.tgz
npm http 200 https://registry.npmjs.org/typewise-core
npm http GET https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/typewise-core/-/typewise-core-1.2.0.tgz
npm http GET https://registry.npmjs.org/xmlhttprequest
npm http 304 https://registry.npmjs.org/amdefine
npm http 304 https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/immediate/-/immediate-3.2.2.tgz
npm http 200 https://registry.npmjs.org/xmlhttprequest
npm http GET https://registry.npmjs.org/xmlhttprequest/-/xmlhttprequest-1.8.0.tgz
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/inline-process-browser
npm http 200 https://registry.npmjs.org/immediate/-/immediate-3.2.2.tgz
npm http 200 https://registry.npmjs.org/xmlhttprequest/-/xmlhttprequest-1.8.0.tgz
npm http 304 https://registry.npmjs.org/inline-process-browser
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.2.3.tgz
npm http 200 https://registry.npmjs.org/unreachable-branch-transform/-/unreachable-branch-transform-0.2.3.tgz
npm http GET https://registry.npmjs.org/falafel
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/jshint
npm http GET https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http GET https://registry.npmjs.org/pouchdb-extend
npm http GET https://registry.npmjs.org/pouchdb-upsert
npm http GET https://registry.npmjs.org/pouchdb-collate
npm http GET https://registry.npmjs.org/spark-md5
npm http GET https://registry.npmjs.org/debug
npm http GET https://registry.npmjs.org/argsarray
npm http GET https://registry.npmjs.org/es3ify
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/falafel
npm http 304 https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/xtend
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/object-keys
npm http GET https://registry.npmjs.org/acorn
npm http GET https://registry.npmjs.org/foreach
npm http 200 https://registry.npmjs.org/pouchdb-extend
npm http GET https://registry.npmjs.org/pouchdb-extend/-/pouchdb-extend-0.1.2.tgz
npm http 304 https://registry.npmjs.org/pouchdb-collate
npm http GET https://registry.npmjs.org/private
npm http GET https://registry.npmjs.org/ast-types
npm http 304 https://registry.npmjs.org/spark-md5
npm http GET https://registry.npmjs.org/spark-md5/-/spark-md5-0.0.5.tgz
npm http 304 https://registry.npmjs.org/debug
npm http 200 https://registry.npmjs.org/pouchdb-abstract-mapreduce
npm http 304 https://registry.npmjs.org/es3ify
npm http GET https://registry.npmjs.org/pouchdb-abstract-mapreduce/-/pouchdb-abstract-mapreduce-0.2.2.tgz
npm http 304 https://registry.npmjs.org/readable-stream
npm http 304 https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/pouchdb-upsert
npm http 304 https://registry.npmjs.org/argsarray
npm http GET https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-1.1.3.tgz
npm http 304 https://registry.npmjs.org/isarray
npm http 304 https://registry.npmjs.org/object-keys
npm http 200 https://registry.npmjs.org/pouchdb-extend/-/pouchdb-extend-0.1.2.tgz
npm http 304 https://registry.npmjs.org/acorn
npm http 304 https://registry.npmjs.org/foreach
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/jshint
npm http GET https://registry.npmjs.org/jshint/-/jshint-2.9.1.tgz
npm http 304 https://registry.npmjs.org/private
npm http 200 https://registry.npmjs.org/spark-md5/-/spark-md5-0.0.5.tgz
npm http 304 https://registry.npmjs.org/ast-types
npm http 200 https://registry.npmjs.org/pouchdb-upsert/-/pouchdb-upsert-1.1.3.tgz
npm http 200 https://registry.npmjs.org/pouchdb-abstract-mapreduce/-/pouchdb-abstract-mapreduce-0.2.2.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/jshint/-/jshint-2.9.1.tgz
npm http GET https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/esprima-fb
npm http GET https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/through
npm http GET https://registry.npmjs.org/immediate
npm http 304 https://registry.npmjs.org/esprima-fb
npm http 304 https://registry.npmjs.org/ms
npm http 304 https://registry.npmjs.org/jstransform
npm http GET https://registry.npmjs.org/base62
npm http GET https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/immediate
npm http GET https://registry.npmjs.org/unreachable-branch-transform
npm http GET https://registry.npmjs.org/cli
npm http GET https://registry.npmjs.org/exit
npm http GET https://registry.npmjs.org/htmlparser2
npm http GET https://registry.npmjs.org/console-browserify
npm http GET https://registry.npmjs.org/minimatch
npm http GET https://registry.npmjs.org/shelljs
npm http GET https://registry.npmjs.org/strip-json-comments
npm http GET https://registry.npmjs.org/lodash
npm http 304 https://registry.npmjs.org/source-map
npm http 304 https://registry.npmjs.org/base62
npm http 304 https://registry.npmjs.org/console-browserify
npm http 304 https://registry.npmjs.org/unreachable-branch-transform
npm http 304 https://registry.npmjs.org/minimatch
npm http 304 https://registry.npmjs.org/shelljs
npm http 304 https://registry.npmjs.org/lodash
npm http GET https://registry.npmjs.org/through2
npm http GET https://registry.npmjs.org/esmangle-evaluator
npm http GET https://registry.npmjs.org/recast
npm http GET https://registry.npmjs.org/lodash/-/lodash-3.7.0.tgz
npm http 304 https://registry.npmjs.org/strip-json-comments
npm http GET https://registry.npmjs.org/amdefine
npm http 200 https://registry.npmjs.org/exit
npm http GET https://registry.npmjs.org/exit/-/exit-0.1.2.tgz
npm http 304 https://registry.npmjs.org/esmangle-evaluator
npm http 304 https://registry.npmjs.org/through2
npm http 304 https://registry.npmjs.org/recast
npm http 304 https://registry.npmjs.org/amdefine
npm http GET https://registry.npmjs.org/readable-stream
npm http GET https://registry.npmjs.org/xtend
npm http 200 https://registry.npmjs.org/htmlparser2
npm http 200 https://registry.npmjs.org/lodash/-/lodash-3.7.0.tgz
npm http GET https://registry.npmjs.org/htmlparser2/-/htmlparser2-3.8.3.tgz
npm http 200 https://registry.npmjs.org/exit/-/exit-0.1.2.tgz
npm http 200 https://registry.npmjs.org/cli
npm http GET https://registry.npmjs.org/cli/-/cli-0.6.6.tgz
npm http 304 https://registry.npmjs.org/xtend
npm http 304 https://registry.npmjs.org/readable-stream
npm http 200 https://registry.npmjs.org/htmlparser2/-/htmlparser2-3.8.3.tgz
npm http GET https://registry.npmjs.org/core-util-is
npm http GET https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/string_decoder
npm http 200 https://registry.npmjs.org/cli/-/cli-0.6.6.tgz
npm http 304 https://registry.npmjs.org/core-util-is
npm http 304 https://registry.npmjs.org/isarray
npm http GET https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/string_decoder
npm http GET https://registry.npmjs.org/brace-expansion
npm http GET https://registry.npmjs.org/glob
npm http GET https://registry.npmjs.org/domhandler
npm http GET https://registry.npmjs.org/domutils
npm http GET https://registry.npmjs.org/domelementtype
npm http GET https://registry.npmjs.org/entities
npm http 304 https://registry.npmjs.org/glob
npm http 304 https://registry.npmjs.org/date-now
npm http 304 https://registry.npmjs.org/brace-expansion
npm http 200 https://registry.npmjs.org/domelementtype
npm http 200 https://registry.npmjs.org/entities
npm http GET https://registry.npmjs.org/balanced-match
npm http GET https://registry.npmjs.org/domelementtype/-/domelementtype-1.3.0.tgz
npm http GET https://registry.npmjs.org/entities/-/entities-1.0.0.tgz
npm http 200 https://registry.npmjs.org/domutils
npm http GET https://registry.npmjs.org/domutils/-/domutils-1.5.1.tgz
npm http GET https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/sigmund
npm http 200 https://registry.npmjs.org/domhandler
npm http GET https://registry.npmjs.org/domhandler/-/domhandler-2.3.0.tgz
npm http 200 https://registry.npmjs.org/domelementtype/-/domelementtype-1.3.0.tgz
npm http 200 https://registry.npmjs.org/domutils/-/domutils-1.5.1.tgz
npm http 304 https://registry.npmjs.org/balanced-match
npm http 304 https://registry.npmjs.org/lru-cache
npm http GET https://registry.npmjs.org/lru-cache/-/lru-cache-2.7.3.tgz
npm http 200 https://registry.npmjs.org/entities/-/entities-1.0.0.tgz
npm http 304 https://registry.npmjs.org/sigmund
npm http 200 https://registry.npmjs.org/domhandler/-/domhandler-2.3.0.tgz
npm http GET https://registry.npmjs.org/dom-serializer
npm http 200 https://registry.npmjs.org/lru-cache/-/lru-cache-2.7.3.tgz
npm http 200 https://registry.npmjs.org/dom-serializer
npm http GET https://registry.npmjs.org/dom-serializer/-/dom-serializer-0.1.0.tgz
npm http 200 https://registry.npmjs.org/dom-serializer/-/dom-serializer-0.1.0.tgz
npm http GET https://registry.npmjs.org/domelementtype/-/domelementtype-1.1.3.tgz
npm http GET https://registry.npmjs.org/entities/-/entities-1.1.1.tgz
npm http 200 https://registry.npmjs.org/domelementtype/-/domelementtype-1.1.3.tgz
npm http 200 https://registry.npmjs.org/entities/-/entities-1.1.1.tgz
ERROR thaliWifiInfrastructure Unable to use the given router: TypeError: Router.use() requires middleware function but got a string
ERROR thaliWifiInfrastructure Router server emitted an error: Error: listen EADDRINUSE
npm ERR! Test failed.  See above for more details.
npm ERR! not ok code 0
