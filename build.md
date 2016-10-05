#### Test (Fail) 87966432 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   6122c63..c4e001b  vNext_aaladev_1231 -> origin/vNext_aaladev_1231

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Removing src/android/test/io/jxcore/node/OutgoingSocketThreadMockWithLatch.java
Auto-merging src/android/test/io/jxcore/node/IncomingSocketThreadTest.java
Removing src/android/test/io/jxcore/node/IncomingSocketThreadMockWithLatch.java
Removing src/android/test/io/jxcore/node/CITestClass.java
Merge made by the 'recursive' strategy.
 build.sh                                           |   2 +-
 .../java/io/jxcore/node/StreamCopyingThread.java   |   5 -
 src/android/test/build-extras.gradle               |  11 +-
 .../test/com/test/thalitest/RegisterExecuteUT.java |  48 +-
 .../test/com/test/thalitest/ThaliTestRunner.java   |  91 +---
 src/android/test/io/jxcore/node/CITestClass.java   |  15 -
 .../test/io/jxcore/node/ConnectionHelperTest.java  | 501 ++++++++------------
 .../test/io/jxcore/node/ConnectionModelTest.java   | 129 +++--
 .../io/jxcore/node/ConnectivityMonitorTest.java    | 522 +++++++++++----------
 .../io/jxcore/node/IncomingSocketThreadMock.java   |   7 +-
 .../node/IncomingSocketThreadMockWithLatch.java    |  28 --
 .../io/jxcore/node/IncomingSocketThreadTest.java   | 239 +++-------
 .../io/jxcore/node/JXcoreThaliCallbackMock.java    |   2 +-
 .../test/io/jxcore/node/LifeCycleMonitorTest.java  |  57 +--
 src/android/test/io/jxcore/node/ListenerMock.java  |   2 +-
 .../node/ListenerOrIncomingConnectionTest.java     |  94 ++--
 .../io/jxcore/node/OutgoingSocketThreadMock.java   |  11 +-
 .../node/OutgoingSocketThreadMockWithLatch.java    |  27 --
 .../io/jxcore/node/OutgoingSocketThreadTest.java   | 241 ++++------
 .../test/io/jxcore/node/SocketThreadBaseMock.java  |   2 +-
 .../test/io/jxcore/node/SocketThreadBaseTest.java  |  69 ++-
 .../jxcore/node/StartStopOperationHandlerTest.java | 272 ++++-------
 .../io/jxcore/node/StartStopOperationTest.java     |  27 +-
 .../io/jxcore/node/StreamCopyingThreadTest.java    |  99 +---
 24 files changed, 943 insertions(+), 1558 deletions(-)
 delete mode 100644 src/android/test/io/jxcore/node/CITestClass.java
 delete mode 100644 src/android/test/io/jxcore/node/IncomingSocketThreadMockWithLatch.java
 delete mode 100644 src/android/test/io/jxcore/node/OutgoingSocketThreadMockWithLatch.java

Already on 'master'
Already on 'master'
Note: checking out '6122c63'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 6122c63... cosmetics
bash: shell_session_update: command not found

```

```
Cordova version:
6.3.1
thali-test-server@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/test/TestServer
├── bluebird@3.4.6 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ ├─┬ mime-types@2.1.12 
│ │ │ └── mime-db@1.24.0 
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
│ ├─┬ type-is@1.6.13 
│ │ └── media-typer@0.3.0 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.9 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.1.0 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.3 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       ├── once@1.4.0 
│       └── path-is-absolute@1.0.1 
├── node-uuid@1.4.7 
├─┬ nssocket@0.6.0 
│ ├── eventemitter2@0.4.14 
│ └── lazy@1.0.11 
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


> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> jx install/prePublishThaliCordovaPlugin.js

thali@2.1.0 /Users/thali/Github/Thali_CordovaPlugin/thali
├─┬ body-parser@1.13.3 
│ ├── bytes@2.1.0 
│ ├── content-type@1.0.2 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.0.1 
│ ├─┬ http-errors@1.3.1 
│ │ └── statuses@1.3.0 
│ ├── iconv-lite@0.4.11 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── qs@4.0.0 
│ ├─┬ raw-body@2.1.7 
│ │ ├── bytes@2.4.0 
│ │ ├── iconv-lite@0.4.13 
│ │ └── unpipe@1.0.0 
│ └─┬ type-is@1.6.13 
│   └── media-typer@0.3.0 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ └── negotiator@0.5.3 
│ ├── array-flatten@1.1.1 
│ ├── content-disposition@0.5.0 
│ ├── cookie@0.1.3 
│ ├── cookie-signature@1.0.6 
│ ├── escape-html@1.0.2 
│ ├── etag@1.7.0 
│ ├── finalhandler@0.4.0 
│ ├── fresh@0.3.0 
│ ├── merge-descriptors@1.0.0 
│ ├── methods@1.1.2 
│ ├── parseurl@1.3.1 
│ ├── path-to-regexp@0.1.7 
│ ├─┬ proxy-addr@1.0.10 
│ │ ├── forwarded@0.1.0 
│ │ └── ipaddr.js@1.0.5 
│ ├── range-parser@1.0.3 
│ ├─┬ send@0.13.0 
│ │ ├── destroy@1.0.3 
│ │ ├── mime@1.3.4 
│ │ └── statuses@1.2.1 
│ ├─┬ serve-static@1.10.3 
│ │ ├── escape-html@1.0.3 
│ │ └─┬ send@0.13.2 
│ │   ├── depd@1.1.0 
│ │   ├── destroy@1.0.4 
│ │   └── statuses@1.2.1 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├── forever-agent@0.6.1 
├── ip@1.0.1 
├── javascript-state-machine@2.3.5 
├── js-extend@1.0.1 
├─┬ jsdoc@3.3.3 
│ ├── async@0.9.2 
│ ├─┬ catharsis@0.8.8 
│ │ └─┬ underscore-contrib@0.3.0 
│ │   └── underscore@1.6.0 
│ ├── escape-string-regexp@1.0.5 
│ ├── esprima@1.2.5 
│ ├── js2xmlparser@0.1.9 
│ ├── marked@0.3.6 
│ ├─┬ requizzle@0.2.1 
│ │ └── underscore@1.6.0 
│ ├── strip-json-comments@1.0.4 
│ ├── taffydb@2.6.2 
│ ├── underscore@1.7.0 
│ └── wrench@1.5.9 
├─┬ lie@3.0.4 
│ ├─┬ es3ify@0.2.2 
│ │ ├── esprima@2.7.3 
│ │ ├─┬ jstransform@11.0.3 
│ │ │ ├── base62@1.1.1 
│ │ │ ├─┬ commoner@0.10.4 
│ │ │ │ ├─┬ detective@4.3.1 
│ │ │ │ │ └── defined@1.0.0 
│ │ │ │ ├─┬ glob@5.0.15 
│ │ │ │ │ ├── inflight@1.0.5 
│ │ │ │ │ ├─┬ minimatch@3.0.3 
│ │ │ │ │ │ └─┬ brace-expansion@1.1.6 
│ │ │ │ │ │   ├── balanced-match@0.4.2 
│ │ │ │ │ │   └── concat-map@0.0.1 
│ │ │ │ │ ├── once@1.4.0 
│ │ │ │ │ └── path-is-absolute@1.0.1 
│ │ │ │ ├── graceful-fs@4.1.9 
│ │ │ │ ├─┬ mkdirp@0.5.1 
│ │ │ │ │ └── minimist@0.0.8 
│ │ │ │ └── q@1.4.1 
│ │ │ ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │ │ ├── object-assign@2.1.1 
│ │ │ └─┬ source-map@0.4.4 
│ │ │   └── amdefine@1.0.0 
│ │ └── through@2.3.8 
│ ├── immediate@3.0.6 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ ├── isarray@0.0.1 
│ │ │ └── object-keys@1.0.11 
│ │ └─┬ through2@0.6.5 
│ │   └── readable-stream@1.0.34 
│ └─┬ unreachable-branch-transform@0.3.0 
│   ├── esmangle-evaluator@1.0.1 
│   └─┬ recast@0.10.43 
│     ├── ast-types@0.8.15 
│     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│     ├── private@0.1.6 
│     └── source-map@0.5.6 
├── long@3.0.3 
├─┬ multiplex@6.7.0 
│ ├─┬ duplexify@3.4.5 
│ │ ├─┬ end-of-stream@1.0.0 
│ │ │ └─┬ once@1.3.3 
│ │ │   └── wrappy@1.0.2 
│ │ ├─┬ readable-stream@2.1.5 
│ │ │ └── isarray@1.0.0 
│ │ └── stream-shift@1.0.0 
│ ├── inherits@2.0.3 
│ ├─┬ readable-stream@2.1.5 
│ │ ├── buffer-shims@1.0.0 
│ │ ├── core-util-is@1.0.2 
│ │ ├── isarray@1.0.0 
│ │ ├── process-nextick-args@1.0.7 
│ │ ├── string_decoder@0.10.31 
│ │ └── util-deprecate@1.0.2 
│ ├── varint@4.0.1 
│ └── xtend@4.0.1 
├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
├─┬ request@2.64.0 
│ ├── aws-sign2@0.5.0 
│ ├─┬ bl@1.0.3 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├─┬ form-data@1.0.1 
│ │ └─┬ async@2.0.1 
│ │   └── lodash@4.16.3 
│ ├─┬ har-validator@1.8.0 
│ │ ├── bluebird@2.11.0 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ └── ansi-regex@2.0.0 
│ │ │ ├── strip-ansi@3.0.1 
│ │ │ └── supports-color@2.0.0 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ └─┬ is-my-json-valid@2.15.0 
│ │   ├── generate-function@2.0.0 
│ │   ├─┬ generate-object-property@1.2.0 
│ │   │ └── is-property@1.0.2 
│ │   └── jsonpointer@4.0.0 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@0.11.0 
│ │ ├── asn1@0.1.11 
│ │ ├── assert-plus@0.1.5 
│ │ └── ctype@0.5.3 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.12 
│ │ └── mime-db@1.24.0 
│ ├── node-uuid@1.4.7 
│ ├── oauth-sign@0.8.2 
│ ├── qs@5.1.0 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.3.1 
│ └── tunnel-agent@0.4.3 
├─┬ salti@0.2.1  (git+https://github.com/thaliproject/salti.git#32abe64b9cd1a4213aed9012a94e26e06aa9c3ca)
│ ├── jsonschema@1.1.0 
│ └── object-assign@4.1.0 
├── urlsafe-base64@1.0.0 
├── uuid@2.0.2 
└─┬ winston@2.2.0 
  ├── async@1.0.0 
  ├── colors@1.0.3 
  ├── cycle@1.0.3 
  ├── eyes@0.1.8 
  ├── pkginfo@0.3.1 
  └── stack-trace@0.0.9 


> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> jx installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> jx install/prePublishThaliCordovaPlugin.js

/usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali
install@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/thali/install
├── bluebird@3.4.6 
├── end-with@1.0.2 
├── findit@2.0.0 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.9 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.5.4 
│     └─┬ glob@7.1.0 
│       ├── fs.realpath@1.0.0 
│       ├─┬ inflight@1.0.5 
│       │ └── wrappy@1.0.2 
│       ├─┬ minimatch@3.0.3 
│       │ └─┬ brace-expansion@1.1.6 
│       │   ├── balanced-match@0.4.2 
│       │   └── concat-map@0.0.1 
│       ├── once@1.4.0 
│       └── path-is-absolute@1.0.1 
├─┬ jxc@1.0.14 
│ └─┬ jxtools@0.0.4  (git+https://github.com/ktrzeciaknubisa/jxtools.git#644cf31ea259cb65a97e5c3ed5ea1236dba298a3)
│   ├── adm-zip@0.4.7 
│   └── progress@1.1.8 
├─┬ lie@3.0.4 
│ ├─┬ es3ify@0.2.2 
│ │ ├── esprima@2.7.3 
│ │ ├─┬ jstransform@11.0.3 
│ │ │ ├── base62@1.1.1 
│ │ │ ├─┬ commoner@0.10.4 
│ │ │ │ ├─┬ detective@4.3.1 
│ │ │ │ │ └── defined@1.0.0 
│ │ │ │ ├── glob@5.0.15 
│ │ │ │ ├── iconv-lite@0.4.13 
│ │ │ │ └── q@1.4.1 
│ │ │ ├── esprima-fb@15001.1.0-dev-harmony-fb 
│ │ │ ├── object-assign@2.1.1 
│ │ │ └─┬ source-map@0.4.4 
│ │ │   └── amdefine@1.0.0 
│ │ └── through@2.3.8 
│ ├── immediate@3.0.6 
│ ├─┬ inline-process-browser@1.0.0 
│ │ ├─┬ falafel@1.2.0 
│ │ │ ├── acorn@1.2.2 
│ │ │ ├── foreach@2.0.5 
│ │ │ └── object-keys@1.0.11 
│ │ └─┬ through2@0.6.5 
│ │   └── xtend@4.0.1 
│ └─┬ unreachable-branch-transform@0.3.0 
│   ├── esmangle-evaluator@1.0.1 
│   └─┬ recast@0.10.43 
│     ├── ast-types@0.8.15 
│     ├── esprima-fb@15001.1001.0-dev-harmony-fb 
│     ├── private@0.1.6 
│     └── source-map@0.5.6 
├── node-uuid@1.4.7 
├─┬ randomstring@1.1.5 
│ └── array-uniq@1.0.2 
├─┬ request@2.64.0 
│ ├── aws-sign2@0.5.0 
│ ├─┬ bl@1.0.3 
│ │ └─┬ readable-stream@2.0.6 
│ │   ├── isarray@1.0.0 
│ │   ├── process-nextick-args@1.0.7 
│ │   └── util-deprecate@1.0.2 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├── forever-agent@0.6.1 
│ ├─┬ form-data@1.0.1 
│ │ └─┬ async@2.0.1 
│ │   └── lodash@4.16.3 
│ ├─┬ har-validator@1.8.0 
│ │ ├── bluebird@2.11.0 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ ├── escape-string-regexp@1.0.5 
│ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ └── ansi-regex@2.0.0 
│ │ │ ├── strip-ansi@3.0.1 
│ │ │ └── supports-color@2.0.0 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ └─┬ is-my-json-valid@2.15.0 
│ │   ├── generate-function@2.0.0 
│ │   ├─┬ generate-object-property@1.2.0 
│ │   │ └── is-property@1.0.2 
│ │   └── jsonpointer@4.0.0 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@0.11.0 
│ │ ├── asn1@0.1.11 
│ │ ├── assert-plus@0.1.5 
│ │ └── ctype@0.5.3 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.12 
│ │ └── mime-db@1.24.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@5.1.0 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.3.1 
│ └── tunnel-agent@0.4.3 
└─┬ unzip@0.1.11 
  ├─┬ binary@0.3.0 
  │ ├── buffers@0.1.1 
  │ └─┬ chainsaw@0.1.0 
  │   └── traverse@0.3.9 
  ├─┬ fstream@0.1.31 
  │ ├─┬ graceful-fs@3.0.11 
  │ │ └── natives@1.1.0 
  │ ├── inherits@2.0.3 
  │ └─┬ mkdirp@0.5.1 
  │   └── minimist@0.0.8 
  ├── match-stream@0.0.2 
  ├─┬ pullstream@0.4.1 
  │ ├── over@0.0.5 
  │ └── slice-stream@1.0.0 
  ├─┬ readable-stream@1.0.34 
  │ ├── core-util-is@1.0.2 
  │ ├── isarray@0.0.1 
  │ └── string_decoder@0.10.31 
  └── setimmediate@1.0.5 

/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/thali -> /usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali

> leveldown-mobile@1.1.1 install /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/leveldown-mobile
> "/usr/local/bin/jx" /Users/thali/.jx/npm/node_modules/node-gyp/bin/node-gyp.js rebuild

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
thali-cordova-plugin-jxcore@1.0.0 /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
├── balanced-match@0.2.0 
├── bluebird@3.4.6 
├── bn.js@4.10.0 
├─┬ body-parser@1.13.3 
│ ├── bytes@2.1.0 
│ ├── content-type@1.0.2 
│ ├─┬ debug@2.2.0 
│ │ └── ms@0.7.1 
│ ├── depd@1.0.1 
│ ├─┬ http-errors@1.3.1 
│ │ └── statuses@1.3.0 
│ ├── iconv-lite@0.4.11 
│ ├─┬ on-finished@2.3.0 
│ │ └── ee-first@1.1.1 
│ ├── qs@4.0.0 
│ ├─┬ raw-body@2.1.7 
│ │ ├── bytes@2.4.0 
│ │ └── unpipe@1.0.0 
│ └─┬ type-is@1.6.13 
│   └── media-typer@0.3.0 
├── concat-map@0.0.1 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ └── negotiator@0.5.3 
│ ├── array-flatten@1.1.1 
│ ├── content-disposition@0.5.0 
│ ├── cookie@0.1.3 
│ ├── cookie-signature@1.0.6 
│ ├── escape-html@1.0.2 
│ ├── etag@1.7.0 
│ ├── finalhandler@0.4.0 
│ ├── fresh@0.3.0 
│ ├── merge-descriptors@1.0.0 
│ ├── methods@1.1.2 
│ ├── parseurl@1.3.1 
│ ├── path-to-regexp@0.1.7 
│ ├─┬ proxy-addr@1.0.10 
│ │ ├── forwarded@0.1.0 
│ │ └── ipaddr.js@1.0.5 
│ ├── range-parser@1.0.3 
│ ├─┬ send@0.13.0 
│ │ ├── destroy@1.0.3 
│ │ ├── mime@1.3.4 
│ │ └── statuses@1.2.1 
│ ├─┬ serve-static@1.10.3 
│ │ ├── escape-html@1.0.3 
│ │ └─┬ send@0.13.2 
│ │   ├── depd@1.1.0 
│ │   ├── destroy@1.0.4 
│ │   └── statuses@1.2.1 
│ ├── utils-merge@1.0.0 
│ └── vary@1.0.1 
├─┬ express-pouchdb@1.0.5-thali 
│ ├── basic-auth@1.0.4 
│ ├── bluebird@3.4.1 
│ ├─┬ body-parser@1.15.2 
│ │ ├── bytes@2.4.0 
│ │ ├── depd@1.1.0 
│ │ ├─┬ http-errors@1.5.0 
│ │ │ └── setprototypeof@1.0.1 
│ │ └── qs@6.2.0 
│ ├─┬ compression@1.6.2 
│ │ ├─┬ accepts@1.3.3 
│ │ │ └── negotiator@0.6.1 
│ │ ├── bytes@2.3.0 
│ │ ├── compressible@2.0.8 
│ │ ├── on-headers@1.0.1 
│ │ └── vary@1.1.0 
│ ├─┬ cookie-parser@1.4.1 
│ │ └── cookie@0.2.3 
│ ├── extend@1.3.0 
│ ├── header-case-normalizer@1.0.3 
│ ├─┬ multiparty@3.3.2 
│ │ ├── readable-stream@1.1.14 
│ │ └─┬ stream-counter@0.2.0 
│ │   └── readable-stream@1.1.14 
│ ├── node-uuid@1.4.1 
│ ├─┬ pouchdb-all-dbs@1.0.2 
│ │ ├─┬ es3ify@0.1.4 
│ │ │ ├── esprima-fb@3001.1.0-dev-harmony-fb 
│ │ │ └─┬ jstransform@3.0.0 
│ │ │   ├── base62@0.1.1 
│ │ │   └── source-map@0.1.31 
│ │ ├── pouchdb-promise@5.4.3 
│ │ └── tiny-queue@0.2.1 
│ ├─┬ pouchdb-auth@2.1.0 
│ │ ├─┬ base64url@1.0.6 
│ │ │ ├─┬ concat-stream@1.4.10 
│ │ │ │ ├── readable-stream@1.1.14 
│ │ │ │ └── typedarray@0.0.6 
│ │ │ └─┬ meow@2.0.0 
│ │ │   ├─┬ camelcase-keys@1.0.0 
│ │ │   │ ├── camelcase@1.2.1 
│ │ │   │ └── map-obj@1.0.1 
│ │ │   ├─┬ indent-string@1.2.2 
│ │ │   │ ├── get-stdin@4.0.1 
│ │ │   │ └─┬ repeating@1.1.3 
│ │ │   │   └─┬ is-finite@1.0.2 
│ │ │   │     └── number-is-nan@1.0.1 
│ │ │   └── object-assign@1.0.0 
│ │ ├─┬ couchdb-calculate-session-id@1.1.0 
│ │ │ └── aproba@1.0.4 
│ │ ├── crypto-lite@0.1.0 
│ │ ├─┬ pouchdb-bulkdocs-wrapper@1.0.2 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├── pouchdb-plugin-error@1.0.1 
│ │ ├─┬ pouchdb-req-http-query@1.0.3 
│ │ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ │ ├── bluebird@1.2.4 
│ │ │ │ └── lie@2.7.7 
│ │ │ └─┬ xmlhttprequest-cookie@0.9.4 
│ │ │   └── xmlhttprequest@1.8.0 
│ │ ├── pouchdb-system-db@1.0.4 
│ │ └── secure-random@1.1.1 
│ ├─┬ pouchdb-find@0.10.2 
│ │ ├── is-array@1.0.1 
│ │ ├─┬ lie@2.9.1 
│ │ │ └── unreachable-branch-transform@0.2.3 
│ │ ├── pouchdb-extend@0.1.2 
│ │ ├─┬ pouchdb-promise@5.4.0 
│ │ │ └─┬ lie@3.0.4 
│ │ │   └── unreachable-branch-transform@0.3.0 
│ │ ├── pouchdb-upsert@2.0.2 
│ │ └── spark-md5@0.0.5 
│ ├─┬ pouchdb-list@1.1.0 
│ │ ├─┬ couchdb-objects@1.0.7 
│ │ │ ├── is-empty@0.0.1 
│ │ │ └─┬ pouchdb-promise@0.0.0 
│ │ │   ├── bluebird@1.2.4 
│ │ │   └── lie@2.7.7 
│ │ ├── couchdb-render@1.0.1 
│ │ ├── extend@3.0.0 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├─┬ pouchdb-replicator@2.1.3 
│ │ ├─┬ equals@1.0.5 
│ │ │ └── jkroso-type@1.1.1 
│ │ ├─┬ pouchdb-promise@0.0.0 
│ │ │ ├── bluebird@1.2.4 
│ │ │ └── lie@2.7.7 
│ │ └── random-uuid-v4@0.0.4 
│ ├─┬ pouchdb-rewrite@1.0.7 
│ │ └── pouchdb-route@1.0.3 
│ ├─┬ pouchdb-security@1.2.6 
│ │ ├── pouchdb-changeslike-wrapper@1.0.1 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├─┬ pouchdb-show@1.0.8 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├─┬ pouchdb-update@1.0.8 
│ │ ├── couchdb-eval@1.0.6 
│ │ ├── couchdb-resp-completer@1.0.3 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├─┬ pouchdb-validation@1.2.1 
│ │ └─┬ pouchdb-promise@0.0.0 
│ │   ├── bluebird@1.2.4 
│ │   └── lie@2.7.7 
│ ├── pouchdb-vhost@1.0.2 
│ └── pouchdb-wrappers@1.3.6 
├── forever-agent@0.6.1 
├─┬ fs-extra-promise@0.4.0
│ └── bluebird@3.4.6 
├── inherits@2.0.1 
├── is-property@1.0.2 
├── js-extend@1.0.1 
├─┬ leveldown-mobile@1.1.1 
│ ├── abstract-leveldown@2.1.4 
│ ├── bindings@1.2.1 
│ └── fast-future@1.0.1 
├─┬ lie@3.0.4 
│ ├─┬ es3ify@0.2.2
│ │ └─┬ jstransform@11.0.3
│ │   └─┬ commoner@0.10.4
│ │     └── glob@5.0.15 
│ └── unreachable-branch-transform@0.3.0 
├── long@3.0.3 
├── minimist@1.2.0 
├─┬ multiplex@6.7.0 
│ ├─┬ duplexify@3.4.5 
│ │ ├─┬ end-of-stream@1.0.0 
│ │ │ └── once@1.3.3 
│ │ ├─┬ readable-stream@2.1.5 
│ │ │ └── isarray@1.0.0 
│ │ └── stream-shift@1.0.0 
│ ├─┬ readable-stream@2.1.5 
│ │ ├── buffer-shims@1.0.0 
│ │ ├── isarray@1.0.0 
│ │ ├── process-nextick-args@1.0.7 
│ │ └── util-deprecate@1.0.2 
│ └── varint@4.0.1 
├─┬ nock@2.12.0 
│ ├─┬ chai@3.5.0 
│ │ ├── assertion-error@1.0.2 
│ │ ├─┬ deep-eql@0.1.3 
│ │ │ └── type-detect@0.1.1 
│ │ └── type-detect@1.0.0 
│ ├─┬ debug@1.0.4 
│ │ └── ms@0.6.2 
│ ├── deep-equal@1.0.1 
│ ├── lodash@2.4.1 
│ └── propagate@0.3.1 
├─┬ node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
│ └── ip@1.1.3 
├── node-uuid@1.4.7 
├─┬ nssocket@0.6.0 
│ ├── eventemitter2@0.4.14 
│ └── lazy@1.0.11 
├── object-assign@4.1.0 
├─┬ pouchdb@5.4.5 
│ ├── argsarray@0.0.1 
│ ├── double-ended-queue@2.0.0-0 
│ ├── es6-promise-pool@2.4.2 
│ ├─┬ fruitdown@1.0.2 
│ │ ├─┬ abstract-leveldown@0.12.3 
│ │ │ └── xtend@3.0.0 
│ │ ├── d64@1.0.0 
│ │ └── tiny-queue@0.2.0 
│ ├── js-extend@0.0.1 
│ ├─┬ level-write-stream@1.0.0 
│ │ └─┬ end-stream@0.1.0 
│ │   └─┬ write-stream@0.4.3 
│ │     └── readable-stream@0.0.4 
│ ├─┬ levelup@1.3.2 
│ │ ├─┬ deferred-leveldown@1.2.1 
│ │ │ └── abstract-leveldown@2.4.1 
│ │ ├── level-codec@6.1.0 
│ │ ├── level-errors@1.0.4 
│ │ ├── level-iterator-stream@1.3.1 
│ │ ├── prr@1.0.1 
│ │ └── semver@5.1.1 
│ ├─┬ localstorage-down@0.6.6 
│ │ ├─┬ humble-localstorage@1.4.2 
│ │ │ ├── has-localstorage@1.0.1 
│ │ │ └── localstorage-memory@1.0.2 
│ │ └── tiny-queue@0.2.0 
│ ├─┬ memdown@1.1.2 
│ │ ├── abstract-leveldown@2.6.1 
│ │ ├── functional-red-black-tree@1.0.1 
│ │ └── ltgt@1.0.2 
│ ├── pouchdb-collate@1.2.0 
│ ├── pouchdb-collections@1.0.1 
│ ├─┬ request@2.72.0 
│ │ ├── aws-sign2@0.6.0 
│ │ ├── aws4@1.4.1 
│ │ ├─┬ bl@1.1.2 
│ │ │ └─┬ readable-stream@2.0.6 
│ │ │   └── isarray@1.0.0 
│ │ ├── extend@3.0.0 
│ │ ├─┬ har-validator@2.0.6 
│ │ │ └─┬ pinkie-promise@2.0.1 
│ │ │   └── pinkie@2.0.4 
│ │ ├─┬ http-signature@1.1.1 
│ │ │ ├── assert-plus@0.2.0 
│ │ │ ├─┬ jsprim@1.3.1 
│ │ │ │ ├── extsprintf@1.0.2 
│ │ │ │ ├── json-schema@0.2.3 
│ │ │ │ └── verror@1.3.6 
│ │ │ └─┬ sshpk@1.10.1 
│ │ │   ├── asn1@0.2.3 
│ │ │   ├── assert-plus@1.0.0 
│ │ │   ├─┬ dashdash@1.14.0 
│ │ │   │ └── assert-plus@1.0.0 
│ │ │   └─┬ getpass@0.1.6 
│ │ │     └── assert-plus@1.0.0 
│ │ ├── is-typedarray@1.0.0 
│ │ └── qs@6.1.0 
│ ├── scope-eval@0.0.3 
│ ├── spark-md5@2.0.2 
│ ├─┬ sublevel-pouchdb@1.0.1 
│ │ ├─┬ errno@0.1.4 
│ │ │ └── prr@0.0.0 
│ │ ├── ltgt@2.1.2 
│ │ ├─┬ pull-stream@2.21.0 
│ │ │ └── pull-core@1.0.0 
│ │ └── readable-stream@1.0.33 
│ ├─┬ through2@2.0.1 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ └── vuvuzela@1.0.3 
├─┬ pouchdb-size@1.2.2 
│ ├── bluebird@2.11.0 
│ ├─┬ get-folder-size@0.1.1 
│ │ ├── async@0.9.2 
│ │ └── minimist@0.1.0 
│ └── promise-nodify@1.0.2 
├─┬ proxyquire@1.7.4 
│ ├─┬ fill-keys@1.0.2 
│ │ └── is-object@1.0.1 
│ └── module-not-found-error@1.0.1 
├─┬ randomstring@1.1.5 
│ └── array-uniq@1.0.2 
├─┬ request@2.64.0 
│ ├── aws-sign2@0.5.0 
│ ├─┬ bl@1.0.3 
│ │ └─┬ readable-stream@2.0.6 
│ │   └── isarray@1.0.0 
│ ├── caseless@0.11.0 
│ ├─┬ combined-stream@1.0.5 
│ │ └── delayed-stream@1.0.0 
│ ├── extend@3.0.0 
│ ├─┬ form-data@1.0.1 
│ │ └─┬ async@2.0.1 
│ │   └── lodash@4.16.3 
│ ├─┬ har-validator@1.8.0 
│ │ ├── bluebird@2.11.0 
│ │ └─┬ is-my-json-valid@2.15.0 
│ │   ├── generate-function@2.0.0 
│ │   ├── generate-object-property@1.2.0 
│ │   └── jsonpointer@4.0.0 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@0.11.0 
│ │ ├── asn1@0.1.11 
│ │ ├── assert-plus@0.1.5 
│ │ └── ctype@0.5.3 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.12 
│ │ └── mime-db@1.24.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@5.1.0 
│ ├── stringstream@0.0.5 
│ ├── tough-cookie@2.2.2 
│ └── tunnel-agent@0.4.3 
├─┬ request-promise@0.4.3 
│ ├── bluebird@2.11.0 
│ ├─┬ chalk@1.1.3 
│ │ ├── ansi-styles@2.2.1 
│ │ ├── escape-string-regexp@1.0.5 
│ │ ├─┬ has-ansi@2.0.0 
│ │ │ └── ansi-regex@2.0.0 
│ │ ├── strip-ansi@3.0.1 
│ │ └── supports-color@2.0.0 
│ └── lodash@3.10.1 
├─┬ salti@0.2.1  (git+https://github.com/thaliproject/salti.git#32abe64b9cd1a4213aed9012a94e26e06aa9c3ca)
│ └── jsonschema@1.1.0 
├─┬ sinon@1.17.3 
│ ├── formatio@1.1.1 
│ ├── lolex@1.3.2 
│ ├── samsam@1.1.2 
│ └── util@0.10.3 
├─┬ socket.io-client@1.4.8 
│ ├── backo2@1.0.2 
│ ├── component-bind@1.0.0 
│ ├── component-emitter@1.2.0 
│ ├─┬ engine.io-client@1.6.11 
│ │ ├── component-emitter@1.1.2 
│ │ ├── component-inherit@0.0.3 
│ │ ├─┬ engine.io-parser@1.2.4 
│ │ │ ├── after@0.8.1 
│ │ │ ├── arraybuffer.slice@0.0.6 
│ │ │ ├── base64-arraybuffer@0.1.2 
│ │ │ ├── blob@0.0.4 
│ │ │ ├── has-binary@0.1.6 
│ │ │ └── utf8@2.1.0 
│ │ ├── has-cors@1.1.0 
│ │ ├── parsejson@0.0.1 
│ │ ├── parseqs@0.0.2 
│ │ ├─┬ ws@1.0.1 
│ │ │ ├── options@0.0.6 
│ │ │ └── ultron@1.0.2 
│ │ ├── xmlhttprequest-ssl@1.5.1 
│ │ └── yeast@0.1.2 
│ ├── has-binary@0.1.7 
│ ├── indexof@0.0.1 
│ ├── object-component@0.0.3 
│ ├─┬ parseuri@0.0.4 
│ │ └─┬ better-assert@1.0.2 
│ │   └── callsite@1.0.0 
│ ├─┬ socket.io-parser@2.2.6 
│ │ ├── benchmark@1.0.0 
│ │ ├── component-emitter@1.1.2 
│ │ └── json3@3.3.2 
│ └── to-array@0.1.4 
├─┬ supertest@1.1.0 
│ └─┬ superagent@1.3.0 
│   ├── component-emitter@1.1.2 
│   ├── cookiejar@2.0.1 
│   ├── extend@1.2.1 
│   ├─┬ form-data@0.2.0 
│   │ ├── async@0.9.2 
│   │ ├─┬ combined-stream@0.0.7 
│   │ │ └── delayed-stream@0.0.5 
│   │ └─┬ mime-types@2.0.14 
│   │   └── mime-db@1.12.0 
│   ├── formidable@1.0.14 
│   ├── methods@1.0.1 
│   ├── qs@2.3.3 
│   ├── readable-stream@1.0.27-1 
│   └── reduce-component@1.0.1 
├─┬ supertest-as-promised@2.0.2 
│ └── bluebird@2.11.0 
├─┬ tape@4.0.0 
│ ├── defined@0.0.0 
│ ├─┬ glob@5.0.15 
│ │ └─┬ minimatch@3.0.3
│ │   └─┬ brace-expansion@1.1.6
│ │     └── concat-map@0.0.1 
│ ├── object-inspect@1.0.2 
│ └── resumer@0.0.0 
├── tape-catch@1.0.4 
├─┬ thali@2.1.0 -> /Users/thali/Github/Thali_CordovaPlugin/thali
│ ├─┬ body-parser@1.13.3 
│ │ ├── bytes@2.1.0 
│ │ ├── content-type@1.0.2 
│ │ ├─┬ debug@2.2.0 
│ │ │ └── ms@0.7.1 
│ │ ├── depd@1.0.1 
│ │ ├─┬ http-errors@1.3.1 
│ │ │ └── statuses@1.3.0 
│ │ ├── iconv-lite@0.4.11 
│ │ ├─┬ on-finished@2.3.0 
│ │ │ └── ee-first@1.1.1 
│ │ ├── qs@4.0.0 
│ │ ├─┬ raw-body@2.1.7 
│ │ │ ├── bytes@2.4.0 
│ │ │ └── unpipe@1.0.0 
│ │ └─┬ type-is@1.6.13 
│ │   └── media-typer@0.3.0 
│ ├─┬ express@4.13.3 
│ │ ├─┬ accepts@1.2.13 
│ │ │ └── negotiator@0.5.3 
│ │ ├── array-flatten@1.1.1 
│ │ ├── content-disposition@0.5.0 
│ │ ├── cookie@0.1.3 
│ │ ├── cookie-signature@1.0.6 
│ │ ├── escape-html@1.0.2 
│ │ ├── etag@1.7.0 
│ │ ├── finalhandler@0.4.0 
│ │ ├── fresh@0.3.0 
│ │ ├── merge-descriptors@1.0.0 
│ │ ├── methods@1.1.2 
│ │ ├── parseurl@1.3.1 
│ │ ├── path-to-regexp@0.1.7 
│ │ ├─┬ proxy-addr@1.0.10 
│ │ │ ├── forwarded@0.1.0 
│ │ │ └── ipaddr.js@1.0.5 
│ │ ├── range-parser@1.0.3 
│ │ ├─┬ send@0.13.0 
│ │ │ ├── destroy@1.0.3 
│ │ │ ├── mime@1.3.4 
│ │ │ └── statuses@1.2.1 
│ │ ├─┬ serve-static@1.10.3 
│ │ │ ├── escape-html@1.0.3 
│ │ │ └─┬ send@0.13.2 
│ │ │   ├── depd@1.1.0 
│ │ │   ├── destroy@1.0.4 
│ │ │   └── statuses@1.2.1 
│ │ ├── utils-merge@1.0.0 
│ │ └── vary@1.0.1 
│ ├── forever-agent@0.6.1 
│ ├── js-extend@1.0.1 
│ ├─┬ jsdoc@3.3.3
│ │ ├── async@0.9.2 
│ │ └── escape-string-regexp@1.0.5 
│ ├─┬ lie@3.0.4 
│ │ ├─┬ es3ify@0.2.2
│ │ │ └─┬ jstransform@11.0.3
│ │ │   └─┬ commoner@0.10.4
│ │ │     └─┬ glob@5.0.15 
│ │ │       └─┬ minimatch@3.0.3
│ │ │         └─┬ brace-expansion@1.1.6
│ │ │           └── concat-map@0.0.1 
│ │ └── unreachable-branch-transform@0.3.0 
│ ├── long@3.0.3 
│ ├─┬ multiplex@6.7.0 
│ │ ├─┬ duplexify@3.4.5 
│ │ │ ├─┬ end-of-stream@1.0.0 
│ │ │ │ └── once@1.3.3 
│ │ │ ├─┬ readable-stream@2.1.5 
│ │ │ │ └── isarray@1.0.0 
│ │ │ └── stream-shift@1.0.0 
│ │ ├─┬ readable-stream@2.1.5 
│ │ │ ├── buffer-shims@1.0.0 
│ │ │ ├── isarray@1.0.0 
│ │ │ ├── process-nextick-args@1.0.7 
│ │ │ └── util-deprecate@1.0.2 
│ │ └── varint@4.0.1 
│ ├── node-ssdp@2.6.5  (git://github.com/thaliproject/node-ssdp.git#fcc5d403f6cc5e667572fba059332908c3cc822e)
│ ├─┬ request@2.64.0 
│ │ ├── aws-sign2@0.5.0 
│ │ ├─┬ bl@1.0.3 
│ │ │ └─┬ readable-stream@2.0.6 
│ │ │   └── isarray@1.0.0 
│ │ ├── caseless@0.11.0 
│ │ ├─┬ combined-stream@1.0.5 
│ │ │ └── delayed-stream@1.0.0 
│ │ ├── extend@3.0.0 
│ │ ├─┬ form-data@1.0.1 
│ │ │ └─┬ async@2.0.1 
│ │ │   └── lodash@4.16.3 
│ │ ├─┬ har-validator@1.8.0 
│ │ │ ├── bluebird@2.11.0 
│ │ │ ├─┬ chalk@1.1.3 
│ │ │ │ ├── ansi-styles@2.2.1 
│ │ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ │ └── ansi-regex@2.0.0 
│ │ │ │ ├── strip-ansi@3.0.1 
│ │ │ │ └── supports-color@2.0.0 
│ │ │ └─┬ is-my-json-valid@2.15.0 
│ │ │   ├── generate-function@2.0.0 
│ │ │   ├─┬ generate-object-property@1.2.0 
│ │ │   │ └── is-property@1.0.2 
│ │ │   └── jsonpointer@4.0.0 
│ │ ├─┬ hawk@3.1.3 
│ │ │ ├── boom@2.10.1 
│ │ │ ├── cryptiles@2.0.5 
│ │ │ ├── hoek@2.16.3 
│ │ │ └── sntp@1.0.9 
│ │ ├─┬ http-signature@0.11.0 
│ │ │ ├── asn1@0.1.11 
│ │ │ ├── assert-plus@0.1.5 
│ │ │ └── ctype@0.5.3 
│ │ ├── isstream@0.1.2 
│ │ ├── json-stringify-safe@5.0.1 
│ │ ├─┬ mime-types@2.1.12 
│ │ │ └── mime-db@1.24.0 
│ │ ├── node-uuid@1.4.7 
│ │ ├── oauth-sign@0.8.2 
│ │ ├── qs@5.1.0 
│ │ ├── stringstream@0.0.5 
│ │ └── tunnel-agent@0.4.3 
│ ├─┬ salti@0.2.1  (git+https://github.com/thaliproject/salti.git#32abe64b9cd1a4213aed9012a94e26e06aa9c3ca)
│ │ ├── jsonschema@1.1.0 
│ │ └── object-assign@4.1.0 
│ └── urlsafe-base64@1.0.0 
├─┬ tmp@0.0.28 
│ └── os-tmpdir@1.0.2 
├── urlsafe-base64@1.0.0 
├── uuid@2.0.0 
└── uuid-validate@0.0.2 


> thali-cordova-plugin-jxcore@1.0.0 test /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js

2016-10-05 17:12:57 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-10-05 17:12:57 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-10-05 17:12:57 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-10-05 17:12:57 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-10-05 17:12:57 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-10-05 17:12:57 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-10-05 17:12:57 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-10-05 17:12:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-10-05 17:12:58 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:12:58 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:12:58 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:12:58 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:12:58 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49830'
ok 1 Should throw
# teardown
# setup
# emits incomingConnectionState
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49832'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
ok 2 initial connection state should be CONNECTED
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
ok 3 final connection state should be DISCONNECTED
# teardown
# setup
# emits routerPortConnectionFailed
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49835'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server connections all up
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49839'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49844'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing incoming connection cleans outgoing socket
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49848'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
ok 14 we should not have gotten an error
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
# setup
# native server - closing outgoing socket cleans associated mux stream
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49852'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
# setup
# native server - closing the whole server cleans everything up
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49856'
ok 20 we should not have gotten an error
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
ok 21 Buffers are identical
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
# teardown
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49860'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
# teardown
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49912'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
ok 31 we should not have gotten an error
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
ok 32 Buffers are identical
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
# teardown
# setup
# native server - timing out the incoming connection cleans everything up
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49916'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
ok 38 we should not have gotten an error
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
ok 39 Buffers are identical
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket timeout'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
# setup
# calling createPeerListener without calling start produces error
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49921'
# teardown
# setup
# calling createPeerListener after calling stop produces error
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49924'
# teardown
# setup
# can call createPeerListener (pleaseConnect === false)
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49927'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49928'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 45 port must be in range
# teardown
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49931'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49932'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - WARN createPeerListener: ' Error: Unknown Peer
    at /Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:255:23
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:100:7)
    at Object.callNative (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/MockMobile.js:28:12)
    at /Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:252:23
    at tryToUnwrap (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:171:5)
    at tryCatch (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:183:17)
    at safelyResolveThenable (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:174:16)
    at new Promise (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:32:5)
    at connectToRemotePeer (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:247:10)
    at Server.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:619:29)
    at Server.g (events.js:160:16)
    at Server.emit (events.js:79:17)
    at net.js:989:10
    at process._tickCallback (node.js:917:13)'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'failedConnection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'Recreating listener'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
ok 46 should get error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49933'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49936'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49937'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 port values should be the same
# teardown
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49940'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49941'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'forward connection'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
ok 48 Data should be of same length and content
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'Recreating listener'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49946'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 49 same peer ID
ok 50 different ports
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
# teardown
# setup
# createPeerListener - closing mux closes listener and triggers a new listener
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49949'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49950'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'forward connection'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
ok 51 Data should be of same length and content
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'Recreating listener'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49955'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 52 same peer ID
ok 53 different ports
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - no native server
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49958'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49959'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'forward connection'
2016-10-05 17:12:58 - WARN createPeerListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 56 reason should be as expected
2016-10-05 17:12:58 - DEBUG createPeerListener: 'Recreating listener'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49961'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49964'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49965'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 59 peerPort should not be nativePort
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'forward connection'
2016-10-05 17:12:58 - WARN createPeerListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
2016-10-05 17:12:58 - DEBUG createPeerListener: 'Recreating listener'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'failed incoming connection because of mux promise failure - undefined'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49968'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49971'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49972'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'forward connection'
ok 64 Should get spontaneous connection
ok 65 peerPort != nativePort
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49976'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49977'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 68 peerPort != nativePort
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'forward connection'
ok 69 Should not get unexpected connection
# teardown
# setup
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49982'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49983'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'forward connection'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:12:58 - WARN createPeerListener: ' Error: read ECONNRESET
    at errnoException (net.js:837:11)
    at TCP.onread (net.js:519:19)'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'Got error on outgoing to native - Error: read ECONNRESET'
# setup
# createPeerListener is idempotent
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49989'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49990'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 74 Second call to existing peerListener returns existing port
# teardown
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49993'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49994'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - WARN createPeerListener: ' Error: a nasty error
    at /Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:255:23
    at Object.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:589:7)
    at Object.callNative (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/MockMobile.js:28:12)
    at /Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:252:23
    at tryToUnwrap (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:171:5)
    at tryCatch (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:183:17)
    at safelyResolveThenable (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:174:16)
    at new Promise (/Users/thali/Github/Thali_CordovaPlugin/thali/node_modules/lie/lib/index.js:32:5)
    at connectToRemotePeer (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:247:10)
    at Server.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createPeerListener.js:619:29)
    at Server.g (events.js:160:16)
    at Server.emit (events.js:79:17)
    at net.js:989:10
    at process._tickCallback (node.js:917:13)'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'failedConnection'
ok 77 got our failed connection
2016-10-05 17:12:58 - DEBUG createPeerListener: 'Recreating listener'
ok 78 failed connection should reject with error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49995'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 49998'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 49999'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'forward connection'
ok 81 Should get spontaneous connection
ok 82 promise should resolve
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === true
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50003'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 50004'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - WARN createPeerListener: 'was expecting a forward connection to be made'
ok 85 reason should be as expected
2016-10-05 17:12:58 - DEBUG createPeerListener: 'Recreating listener'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 50005'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50008'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 50009'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 88 peerPort should not be nativePort
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'reverse connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'no mux found'
ok 89 should not get event until connection is made
ok 90 reason should be as expected
2016-10-05 17:12:58 - DEBUG createPeerListener: 'Recreating listener'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'failed incoming connection because of mux promise failure - AssertionError: server._mux must exist by now'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 50011'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
# teardown
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50014'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 50015'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'looking up mux for client port:  50017'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'reverse connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'looking up mux for client port:  50017'
ok 93 sent and received should be the same
# teardown
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
2016-10-05 17:12:58 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50020'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'listening 50021'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'looking up mux for client port:  50023'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'reverse connection'
2016-10-05 17:12:58 - DEBUG createPeerListener: 'looking up mux for client port:  50023'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:12:58 - DEBUG createNativeListener: 'new outgoing socket'
2016-10-05 17:12:58 - DEBUG createNativeListener: ' Error: connect ECONNREFUSED
    at errnoException (net.js:837:11)
    at Object.afterConnect [as oncomplete] (net.js:829:19)'
ok 96 should get routerPortConnectionFailed
2016-10-05 17:12:58 - DEBUG createNativeListener: 'stream close:'
# teardown
2016-10-05 17:12:58 - DEBUG createNativeListener: 'mux close'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'incoming socket close'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50027'
# teardown
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50030'
# teardown
# setup
# createPeerListener - pleaseConnect = false - test timeout
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50033'
# teardown
# setup
# createPeerListener - pleaseConnect = true - test timeout
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50036'
# teardown
# setup
# createPeerListener - forward connection - wrong serverPort
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50039'
# teardown
# setup
# createPeerListener - forward connection - wrong clientPort
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50042'
# teardown
# setup
# createPeerListener - please connect = false, multiple connections out
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50045'
# teardown
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50048'
# teardown
# setup
# createPeerListener - multiple parallel calls
2016-10-05 17:12:58 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:12:58 - DEBUG createNativeListener: 'listening 50051'
# teardown
# setup
# #_doImmediateSeqUpdate - server is not there
2016-10-05 17:12:58 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 97 Got right error
# teardown
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-10-05 17:12:58 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 98 Got socket hang up
# teardown
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-10-05 17:12:58 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 99 Got 500 as expected
# teardown
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 100 should be equal
ok 101 revs are equal
# teardown
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 102 should be equal
ok 103 revs are equal
# teardown
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 104 should be equal
ok 105 revs are equal
ok 106 should be equal
ok 107 revs are equal
ok 108 should be equal
ok 109 revs are equal
# teardown
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2016-10-05 17:12:59 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 110 Our rev is old so we should fail
# teardown
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 111 confirm stop caused failure
# teardown
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-10-05 17:12:59 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 112 stop caused us to fail
ok 113 We specifically failed on a stop before put
# teardown
# setup
# #update - fail if stop is called
ok 114 failed due to stop
ok 115 failed due to stop
# teardown
# setup
# #update - set seq for first time
ok 116 should be equal
# teardown
# setup
# #update - Fail on bad seq value
2016-10-05 17:12:59 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 117 Expected bad seq error
# teardown
# setup
# #update - do we cancel timer properly on an immediate?
ok 118 Different promises
ok 119 Timer was cancelled
ok 120 should be equal
# teardown
# setup
# #update - do we wait for blocked update
ok 121 One go and one blocked
ok 122 All blocked
ok 123 Still blocked
ok 124 should be equal
# teardown
# setup
# #update - test that we wait long enough
ok 125 We waited long enough
ok 126 should be equal
# teardown
# setup
# #update - test that we pick up new sequences while we wait
ok 127 Should have gotten same timer promise
ok 128 Still same timer promise
ok 129 We waited long enough
ok 130 should be equal
# teardown
# setup
# closeAll can close even when connections open
ok 131 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
ok 132 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
ok 133 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 134 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 135 should be equal
ok 136 should be equal
ok 137 should be equal
# teardown
# setup
# test defaultAdapter
ok 138 should be equal
ok 139 should be equal
ok 140 should be equal
ok 141 should be equal
ok 142 should be equal
ok 143 should be equal
ok 144 should be equal
ok 145 should be equal
# teardown
# setup
# enqueue and run in order
ok 146 firstPromise setTimeout
ok 147 firstPromise result
ok 148 firstPromise testValue
ok 149 secondPromise setTimeout
ok 150 secondPromise result
ok 151 secondPromise testValue
ok 152 thirdPromise in promise
ok 153 thirdPromise result
ok 154 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 155 thirdPromise - first to run
ok 156 thirdPromise - in resolve
ok 157 secondPromise - second to run
ok 158 secondPromise - in catch
ok 159 firstPromise - third to run
ok 160 firstPromise - in then
ok 161 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 162 fourth
ok 163 fourth
ok 164 second
ok 165 secondPromise - in then
ok 166 first
ok 167 firstPromise - in catch
ok 168 third
ok 169 thirdPromise - in then
ok 170 testingPromises
# teardown
# setup
# queues handled independently
ok 171 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 172 sane
# teardown
# setup
# another
ok 173 sane
# teardown
# setup
# test thali manager spies
2016-10-05 17:13:04 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-10-05 17:13:04 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-05 17:13:04 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 174 expressPouchDB was called once
ok 175 expressPouchDB was called with 2 arguments
ok 176 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 177 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 178 PouchDB was called once
ok 179 PouchDB was called with 1 arguments
ok 180 PouchDB was called with 'dbName' as 1-st argument
ok 181 ThaliSendNotificationBasedOnReplication was called once
ok 182 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 183 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 184 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 185 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 186 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 187 ThaliPullReplicationFromNotification was called once
ok 188 ThaliPullReplicationFromNotification was called with 4 arguments
ok 189 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 190 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 191 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 192 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 193 Salti was called once
ok 194 Salti was called with 4 arguments
ok 195 Salti was called with 'dbName' as 1-st argument
ok 196 Salti was called with 'acl' as 2-st argument
ok 197 Salti was called with 'thaliIdCallback' as 3-st argument
ok 198 Salti was called with 'options' as 4-st argument
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-05 17:13:04 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50127'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50128'
2016-10-05 17:13:04 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50129'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50131'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 199 ThaliMobile.start was called once
ok 200 ThaliMobile.start was called with 3 arguments
ok 201 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 202 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 203 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 204 ThaliMobile.startListeningForAdvertisements was called once
ok 205 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 206 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 207 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 208 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 209 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 210 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 211 ThaliPullReplicationFromNotification.prototype.start was called once
ok 212 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 213 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 214 ThaliMobile.stop was called once
ok 215 ThaliMobile.stop was called with 0 arguments
ok 216 ThaliMobile.stopListeningForAdvertisements was called once
ok 217 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 218 ThaliMobile.stopAdvertisingAndListening was called once
ok 219 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 220 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 221 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 222 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 223 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-10-05 17:13:04 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-10-05 17:13:04 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-10-05 17:13:04 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 224 expressPouchDB was called once
ok 225 expressPouchDB was called with 2 arguments
ok 226 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 227 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 228 PouchDB was called once
ok 229 PouchDB was called with 1 arguments
ok 230 PouchDB was called with 'dbName' as 1-st argument
ok 231 ThaliSendNotificationBasedOnReplication was called once
ok 232 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 233 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 234 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 235 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 236 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 237 ThaliPullReplicationFromNotification was called once
ok 238 ThaliPullReplicationFromNotification was called with 4 arguments
ok 239 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 240 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 241 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 242 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 243 Salti was called once
ok 244 Salti was called with 4 arguments
ok 245 Salti was called with 'dbName' as 1-st argument
ok 246 Salti was called with 'acl' as 2-st argument
ok 247 Salti was called with 'thaliIdCallback' as 3-st argument
ok 248 Salti was called with 'options' as 4-st argument
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-05 17:13:04 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50132'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50133'
2016-10-05 17:13:04 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50134'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50136'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 249 ThaliMobile.start was called once
ok 250 ThaliMobile.start was called with 3 arguments
ok 251 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 252 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 253 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 254 ThaliMobile.startListeningForAdvertisements was called once
ok 255 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 256 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 257 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 258 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 259 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 260 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 261 ThaliPullReplicationFromNotification.prototype.start was called once
ok 262 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 263 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 264 ThaliMobile.stop was called once
ok 265 ThaliMobile.stop was called with 0 arguments
ok 266 ThaliMobile.stopListeningForAdvertisements was called once
ok 267 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 268 ThaliMobile.stopAdvertisingAndListening was called once
ok 269 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 270 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 271 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 272 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 273 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-05 17:13:04 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50137'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50138'
2016-10-05 17:13:04 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50139'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50141'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-05 17:13:04 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50142'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50143'
2016-10-05 17:13:04 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50144'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50146'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-10-05 17:13:04 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting ThaliMobile'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50147'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50148'
2016-10-05 17:13:04 - DEBUG thaliManager: 'start listening for advertisements'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'start update advertising and listening'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50149'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50151'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 274 ThaliMobile.start was called once
ok 275 ThaliMobile.start was called with 3 arguments
ok 276 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 277 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 278 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 279 ThaliMobile.startListeningForAdvertisements was called once
ok 280 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 281 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 282 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 283 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 284 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 285 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 286 ThaliPullReplicationFromNotification.prototype.start was called once
ok 287 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 288 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping advertising and listening'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliManager: 'stopping ThaliMobile'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 289 specific error should be returned
# teardown
ok 290 error should be null
ok 291 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 292 specific error should be returned
# teardown
ok 293 error should be null
ok 294 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50152'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50153'
ok 295 error should be null
ok 296 error should be null
ok 297 error should be null
ok 298 error should be null
# teardown
ok 299 error should be null
ok 300 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50154'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50155'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 301 error should be null
ok 302 error should be null
ok 303 error should be null
ok 304 error should be null
# teardown
2016-10-05 17:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 305 error should be null
ok 306 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50156'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50157'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50158'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50160'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 307 error should be null
ok 308 error should be null
ok 309 error should be null
ok 310 error should be null
# teardown
2016-10-05 17:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 311 error should be null
ok 312 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50161'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50162'
ok 313 error should be null
ok 314 error should be null
ok 315 error should be null
ok 316 error should be null
# teardown
ok 317 error should be null
ok 318 error should be null
# setup
# #start should fail if called twice in a row
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50163'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50164'
ok 319 first call should succeed
ok 320 first call should succeed
ok 321 specific error should be returned
# teardown
ok 322 error should be null
ok 323 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'listening 50165'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:04 - DEBUG createNativeListener: 'listening 50166'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50167'
2016-10-05 17:13:04 - DEBUG thaliWifiInfrastructure: 'listening 50169'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-05 17:13:04 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":false,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-05 17:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 324 called only once
ok 325 discovery state matches
ok 326 advertising state matches
2016-10-05 17:13:04 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":false,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-05 17:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
# teardown
2016-10-05 17:13:04 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-05 17:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-05 17:13:04 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:04 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 327 error should be null
ok 328 error should be null
# setup
# does not send duplicate availability changes
ok 329 should be called once
ok 330 should not have been called more than once
# teardown
ok 331 error should be null
ok 332 error should be null
# setup
# can get the network status
ok 333 network status should have certain non-empty properties
# teardown
ok 334 error should be null
ok 335 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-10-05 17:13:04 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a undefined'
ok 336 host address should match
ok 337 port should match
ok 338 host address should be null
ok 339 port should should be null
# teardown
2016-10-05 17:13:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 340 error should be null
ok 341 error should be null
# setup
# network changes emitted correctly
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50170'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50171'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 342 wifi is off
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 343 wifi is on
# teardown
ok 344 error should be null
ok 345 error should be null
# setup
# network changes not emitted in stopped state
ok 346 event was not emitted
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# teardown
ok 347 error should be null
ok 348 error should be null
# setup
# calls correct starts when network changes
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50172'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50173'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 349 specific error expected
2016-10-05 17:13:08 - DEBUG thaliWifiInfrastructure: 'listening 50175'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 350 specific error expected
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":true,"advertisingActive":true}'
2016-10-05 17:13:08 - DEBUG thaliWifiInfrastructure: 'listening 50176'
ok 351 startListeningForAdvertisements should have been called
ok 352 startUpdateAdvertisingAndListening should have been called
# teardown
2016-10-05 17:13:08 - INFO thaliMobile: 'Received state did not match with target: {"nonTCPDiscoveryActive":true,"nonTCPAdvertisingActive":true,"wifiDiscoveryActive":true,"wifiAdvertisingActive":false,"discoveryActive":false,"advertisingActive":false}'
2016-10-05 17:13:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-05 17:13:08 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 353 error should be null
ok 354 error should be null
# setup
# peer is marked unavailable if port number changes
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50177'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50178'
ok 355 peer should have a non-empty identifier
ok 356 peer should have a non-empty host address
ok 357 peer should have port number
ok 358 peer should have suggested timeout
ok 359 peer should have a connection type
ok 360 connection type should match one of the pre-defined types
ok 361 peer should have a non-empty identifier
ok 362 host address should be null
ok 363 port number should be null
ok 364 peer should have suggested timeout
ok 365 peer should have a connection type
ok 366 connection type should match one of the pre-defined types
ok 367 port number must match
ok 368 peer should have a non-empty identifier
ok 369 peer should have a non-empty host address
ok 370 peer should have port number
ok 371 peer should have suggested timeout
ok 372 peer should have a connection type
ok 373 connection type should match one of the pre-defined types
# teardown
ok 374 error should be null
ok 375 error should be null
# setup
# when network connection is lost a peer should be marked unavailable
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50179'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50180'
2016-10-05 17:13:08 - INFO testUtils: 'Toggling radios to: false'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"off","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 376 peer should have a non-empty identifier
ok 377 host address should be null
ok 378 port number should be null
ok 379 peer should have suggested timeout
ok 380 peer should have a connection type
ok 381 connection type should match one of the pre-defined types
2016-10-05 17:13:08 - INFO testUtils: 'Toggling radios to: true'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# teardown
ok 382 error should be null
ok 383 error should be null
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
# setup
# Can call start/stopListeningForAdvertisements
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 384 Can call startListeningForAdvertisements without error
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 385 Can call stopListeningForAdvertisements without error
# teardown
ok 386 Should be able to call stopListeningForAdvertisements in teardown
ok 387 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 388 Can call startListeningForAdvertisements without error
ok 389 Can call startListeningForAdvertisements twice without error
# teardown
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 390 Should be able to call stopListeningForAdvertisements in teardown
ok 391 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 392 Can call stopListeningForAdvertisements without error
ok 393 Can call stopListeningForAdvertisements without error
# teardown
ok 394 Should be able to call stopListeningForAdvertisements in teardown
ok 395 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
2016-10-05 17:13:08 - DEBUG thaliWifiInfrastructure: 'listening 50182'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 396 Can call startUpdateAdvertisingAndListening without error
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 397 Can call stopAdvertisingAndListening without error
# teardown
ok 398 Should be able to call stopListeningForAdvertisements in teardown
ok 399 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
2016-10-05 17:13:08 - DEBUG thaliWifiInfrastructure: 'listening 50184'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 400 Can call startUpdateAdvertisingAndListening without error
ok 401 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 402 Should be able to call stopListeningForAdvertisements in teardown
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 403 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 404 Can call startUpdateAdvertisingAndListening without error
ok 405 Can call stopAdvertisingAndListening without error
# teardown
ok 406 Should be able to call stopListeningForAdvertisements in teardown
ok 407 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 408 got right error
# teardown
ok 409 Should be able to call stopListeningForAdvertisements in teardown
ok 410 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 411 specific error should be returned
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 412 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 413 specific error should be returned
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 414 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50185'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50186'
ok 415 no errors
ok 416 still no errors
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 417 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50187'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50188'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 418 no errors
ok 419 still no errors
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 420 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50189'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50190'
2016-10-05 17:13:08 - DEBUG thaliWifiInfrastructure: 'listening 50192'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 421 no errors
ok 422 still no errors
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 423 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50193'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50194'
ok 424 no errors
ok 425 still no errors
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 426 must be stopped
# setup
# can get the network status before starting
ok 427 network status should have certain non-empty properties
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 428 must be stopped
# setup
# error returned with bad router
2016-10-05 17:13:08 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 429 specific error expected
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 430 must be stopped
# setup
# all services are stopped when we call stop
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50195'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50196'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:08 - DEBUG thaliWifiInfrastructure: 'listening 50198'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
ok 431 connection to servers manager should succeed after starting
2016-10-05 17:13:08 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
ok 432 connection to router server should succeed after starting
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'incoming socket close'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 433 is stopped after calling stop
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
ok 434 connection to servers manager should fail after stopping
ok 435 connection to router server should fail after stopping
# teardown
ok 436 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 437 called with right arguments
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 438 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 439 called with right arguments
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 440 must be stopped
# setup
# make sure we actually call kill connections properly
ok 441 specific error expected
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 442 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50203'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50204'
2016-10-05 17:13:08 - INFO thaliMobileNativeWrapper: 'routerPortConnectionFailed - {"routerPort":50203,"error":{}}'
ok 443 failure reason is as expected
ok 444 error description is as expected
ok 445 must be stopped
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 446 must be stopped
# setup
# We repeat failedConnection event when we get it from thaliTcpServersManager
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50205'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50206'
ok 447 peerIdentifier matches
ok 448 error description matches
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 449 must be stopped
# setup
# can do HTTP requests between peers without coordinator
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50207'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50208'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:08 - DEBUG thaliWifiInfrastructure: 'listening 50210'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50211'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:13:08 - DEBUG testUtils: 'We got a peer {"peerIdentifier":"foo","portNumber":50211,"hostAddress":"127.0.0.1"}'
2016-10-05 17:13:08 - WARN testUtils: 'Retry count for getSamePeerWithRetry is 1'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'first connection'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'new mux'
2016-10-05 17:13:08 - DEBUG wifiBasedNativeMock: 'proxy socket connected'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'forward connection'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'new stream: '
2016-10-05 17:13:08 - DEBUG createNativeListener: 'new outgoing socket'
ok 450 Should only get expected id
ok 451 response body should match testData
# teardown
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'stream close:'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'mux close'
ok 452 must be stopped
2016-10-05 17:13:08 - DEBUG createNativeListener: 'incoming socket close'
# setup
# make sure bad PSK connections fail
ok 453 FIX ME, PLEASE!!!
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 454 must be stopped
# setup
# peer changes handled from a queue
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50218'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50219'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50220'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50221'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50222'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50223'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50224'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50225'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50226'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50227'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50228'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'createPeerListener creating new server'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'listening 50229'
2016-10-05 17:13:08 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 455 peers were handled in the right order
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 456 must be stopped
# setup
# relaying discoveryAdvertisingStateUpdateNonTCP
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50230'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50231'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
ok 457 discovery is active
ok 458 advertising is active
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 459 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when incomingConnectionToPortNumberFailed is received
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50232'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50233'
2016-10-05 17:13:08 - DEBUG thaliWifiInfrastructure: 'listening 50235'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-10-05 17:13:08 - INFO thaliMobileNativeWrapper: 'incomingConnectionToPortNumberFailed: 50233'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 460 right error reason
ok 461 Stop should be fine
ok 462 same port
ok 463 we should be off
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 464 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50236'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50237'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 465 discoveryActive matches
ok 466 advertisingActive matches
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 467 discoveryActive matches
ok 468 advertisingActive matches
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50238'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50239'
2016-10-05 17:13:08 - DEBUG thaliWifiInfrastructure: 'listening 50241'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 469 discoveryActive matches
ok 470 advertisingActive matches
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
ok 471 discoveryActive matches
ok 472 advertisingActive matches
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'listening 50242'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:08 - DEBUG createNativeListener: 'listening 50243'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-10-05 17:13:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 473 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 474 peerIdentifier should be identifier
ok 475 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 476 good beacon
ok 477 good preAmble
ok 478 public keys match!
ok 479 must return null after successful call
ok 480 Once start returns the action should be in KILLED state
# teardown
# setup
# Test HTTP_BAD_RESPONSE locally
ok 481 Response should be HTTP_BAD_RESPONSE
ok 482 must return null after successful call
# teardown
# setup
# Test NETWORK_PROBLEM locally
ok 483 Response should be NETWORK_PROBLEM
ok 484 reject reason should be: Could not establish TCP connection
# teardown
# setup
# Call the start two times
ok 485 Call start once
ok 486 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 487 must return null after successful call.
# teardown
# setup
# Call the kill before calling the start
ok 488 Should be Killed
ok 489 Start after killed
# teardown
# setup
# Call the kill immediately after the start
ok 490 Should be KILLED
ok 491 must return null after successful kill
# teardown
# setup
# Call the kill while waiting a response from the server
ok 492 Should be KILLED
ok 493 must return null after successful kill
# teardown
# setup
# Test to exceed the max content size locally
ok 494 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 495 must return null after successful call
# teardown
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
ok 496 Should be NETWORK_PROBLEM caused closing server socket
ok 497 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 498 Should be NETWORK_PROBLEM caused closing client socket
ok 499 Should be Could not establish TCP connection
# teardown
# setup
# #generatePreambleAndBeacons bad args
ok 500 publicKeysToNotify cannot be null
ok 501 ecdh for local device cannot be null
ok 502 milliseconds cannot be less than 0
ok 503 milliseconds cannot be 0
ok 504 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 505 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 506 should be equal
ok 507 should be equal
ok 508 (unnamed assert)
ok 509 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 510 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 511 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 512 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 513 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 514 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 515 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 516 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 517 should be equal
ok 518 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 519 should be equal
ok 520 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 521 right number of calls to address book
ok 522 good preAmble
ok 523 good unencryptedKeyId
ok 524 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 525 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 526 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 527 Matching numbers
ok 528 We have an entry!
ok 529 keys match
ok 530 secrets match
ok 531 We have an entry!
ok 532 keys match
ok 533 secrets match
ok 534 We have an entry!
ok 535 keys match
ok 536 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 537 Streams have same length
ok 538 matching size
ok 539 keys match
ok 540 secrets match
# teardown
# setup
# Add two Peers.
ok 541 should be equal
ok 542 should be equal
ok 543 should be equal
ok 544 should be equal
ok 545 should be equal
# teardown
# setup
# TCP_NATIVE peer loses DNS
ok 546 should be equal
ok 547 should be equal
# teardown
# setup
# Received beacons with no values for us
ok 548 entry exists
ok 549 entry is resolved
# teardown
# setup
# Resolves an action locally
ok 550 Host address must match
ok 551 suggestedTCPTimeout must match
ok 552 connectionType must match
ok 553 portNumber must match
# teardown
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 554 Host address must match
ok 555 suggestedTCPTimeout must match
ok 556 connectionType must match
ok 557 portNumber must match
# teardown
# setup
# Action fails because of a bad hostname.
ok 558 action should be resolved with NETWORK_PROBLEM error
ok 559 action should be resolved with NETWORK_PROBLEM error
ok 560 action should be resolved with NETWORK_PROBLEM error
ok 561 action should be resolved with NETWORK_PROBLEM error
ok 562 correct number of requests
ok 563 correct number of failures
ok 564 correct final peer state
# teardown
# setup
# hostaddress is removed when the action is running. 
ok 565 should be equal
# teardown
# setup
# Client to server request locally
ok 566 secrets are equal
ok 567 Public key matches with the server key
ok 568 Host address must match
ok 569 suggestedTCPTimeout must match
ok 570 connectionType must match
ok 571 portNumber must match
# teardown
# setup
# Test ThaliPskMapCache clean and expiration
ok 572 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 573 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 574 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 575 All keys need to be available in the cache
ok 576 All entries should be expired after 1 second
# teardown
# setup
# Test ThaliPskMapCache multiple entries
ok 577 Size of the cache should be 2
ok 578 Cache doesn't contain dictionary1
ok 579 Size of the cache should be 1
ok 580 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
# setup
# Start and stop ThaliNotificationServer
ok 581 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 582 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 583 StartUpdateAdvertisingAndListening should not be called
ok 584 ThaliMobile.StopAdvertisingAndListening should be called once
ok 585 no error
ok 586 should be 204
# teardown
# setup
# Pass a string to ThaliNotificationServer.start
ok 587 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 588 StartUpdateAdvertisingAndListening should not be called
# teardown
# setup
# Make an HTTP request to /NotificationBeacons
ok 589 no error
ok 590 should be 200
ok 591 should be equal
ok 592 should be equal
ok 593 (unnamed assert)
ok 594 no error
ok 595 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 596 error should be null
ok 597 should be 204
# teardown
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 598 should be 404
# teardown
# setup
# #testThaliPeerAction - test getters
ok 599 getPeerIdentifier
ok 600 getConnectionType
ok 601 getActionType
ok 602 getActionState
ok 603 getPskIdentity
ok 604 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 605 initial state
ok 606 after start
ok 607 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 608 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
ok 609 clean kill
ok 610 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 611 should not be equal
# teardown
# setup
# Test PeerConnectionInformation basics
ok 612 connection type works
ok 613 getHostAddress works
ok 614 getPortNumber works
ok 615 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 616 Entry counter must be 1
ok 617 Size must be 1
ok 618 Entry counter must be 2
ok 619 Size must be 2
ok 620 Entry2 should not be found
ok 621 Size must be 1
ok 622 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 623 Size must be100
ok 624 Entries between 20 and MAXSIZE + 20 should exist
ok 625 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 626 Entries between 6 and MAXSIZE + 4 should exist
ok 627 Size should be MAXSIZE
ok 628 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 629 WAITING state entry should not be removed
ok 630 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 631 Size should be MAXSIZE
ok 632 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 633 Kill should be called once
ok 634 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 635 is an agent
ok 636 enqueue is fine
ok 637 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 638 is an agent
ok 639 first enqueue is fine
ok 640 is an agent
ok 641 second enqueue is fine
ok 642 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 643 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 644 is an agent
ok 645 good enqueue
ok 646 Identity should match
ok 647 Got expected response
ok 648 Got psk call back
# teardown
# setup
# #ThaliPeerPoolDefault - stop
ok 649 is an agent
ok 650 enqueue worked
ok 651 is an agent
ok 652 enqueue 2 worked
ok 653 enqueue is not available when stopped
ok 654 start action is killed
ok 655 killed action is still killed
ok 656 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 657 good start
ok 658 good enqueue
ok 659 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 660 null arg
ok 661 wrong arg type
ok 662 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 663 good enqueue
ok 664 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 665 good enqueue
ok 666 2nd good enqueue
ok 667 we are in the pool
ok 668 We are out of the pool
ok 669 Action was killed
ok 670 The original kill was called too
ok 671 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 672 good enqueue
ok 673 first kill
ok 674 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 675 1st good enqueue
ok 676 2nd good enqueue
ok 677 1st action is in the pool
ok 678 2nd action is in the pool
ok 679 1st action is out of the pool
ok 680 2st action is out of the pool
ok 681 pool is empty
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 682 equal keys
ok 683 not equal connection type
ok 684 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-10-05 17:13:23 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 685 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 686 second cleared dictionary
2016-10-05 17:13:23 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 687 First start and on called correctly
ok 688 First stop and removeListener called correctly
ok 689 first action kill called
ok 690 second action kill called
ok 691 first cleared dictionary
ok 692 first cleared pool
ok 693 second cleared dictionary
ok 694 second cleared pool
# teardown
# setup
# Simple peer event
2016-10-05 17:13:23 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 695 listener has been set
ok 696 peer dictionary has expected number of entries
ok 697 Dictionary and pool have same action
ok 698 ads match
ok 699 PouchDB matches
ok 700 DB Names match
ok 701 public keys match
ok 702 peer dictionary has expected number of entries
ok 703 Dictionary and pool have same action
ok 704 ads match
ok 705 PouchDB matches
ok 706 DB Names match
ok 707 public keys match
ok 708 start called once
ok 709 One entry left
ok 710 Dictionary and pool have same action
ok 711 Start never called
ok 712 Kill called once
ok 713 no entries left
ok 714 Third action is dead
ok 715 peer dictionary has expected number of entries
ok 716 Dictionary and pool have same action
ok 717 ads match
ok 718 PouchDB matches
ok 719 DB Names match
ok 720 public keys match
# teardown
# setup
# Server is not there
2016-10-05 17:13:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
ok 721 right error
# teardown
# setup
# Server accepts & closes connection
2016-10-05 17:13:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
ok 722 right error
# teardown
# setup
# Server always returns 500
2016-10-05 17:13:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
ok 723 Got error as expected
# teardown
# setup
# Server always returns 401
2016-10-05 17:13:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
ok 724 Got error as expected
# teardown
# setup
# Server always returns 403
2016-10-05 17:13:23 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
ok 725 Got error as expected
# teardown
# setup
# Make sure docs replicate
2016-10-05 17:13:23 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-10-05 17:13:23 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 726 should be equal
ok 727 All tests passed!
# teardown
# setup
# Do nothing and make sure we time out
2016-10-05 17:13:23 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 728 action should be killed
ok 729 Error should be timed out
ok 730 No doc found
# teardown
# setup
# Do something and make sure we time out
2016-10-05 17:13:26 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-10-05 17:13:26 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 731 should be equal
ok 732 action should be killed
ok 733 Error should be timed out
# teardown
# setup
# Start replicating and then catch error when server goes
ok 734 socket hung up
# teardown
# setup
# compareBufferArrays
ok 735 should throw
ok 736 should throw
ok 737 (unnamed assert)
ok 738 (unnamed assert)
ok 739 (unnamed assert)
ok 740 (unnamed assert)
ok 741 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 742 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 743 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 744 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 745 should be equal
ok 746 should be equal
ok 747 should throw
# teardown
# setup
# Test TransientState
ok 748 should throw
ok 749 should throw
ok 750 should be equal
ok 751 should be equal
ok 752 should be equal
ok 753 should be equal
ok 754 (unnamed assert)
ok 755 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 756 verify failed
ok 757 constructor called once
ok 758 constructor called with right args
ok 759 match start arg
ok 760 start called once
ok 761 stop called once
ok 762 stop after start
# teardown
# setup
# One peer and empty DB
ok 763 verify failed
ok 764 constructor called once
ok 765 constructor called with right args
ok 766 match start arg
ok 767 start called once
ok 768 stop called once
ok 769 stop after start
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set behind current seq
ok 770 verify failed
ok 771 constructor called once
ok 772 constructor called with right args
ok 773 match start arg
ok 774 start called once
ok 775 stop called once
ok 776 stop after start
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set equal to current seq
ok 777 verify failed
ok 778 constructor called once
ok 779 constructor called with right args
ok 780 match start arg
ok 781 start called once
ok 782 stop called once
ok 783 stop after start
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 784 verify failed
ok 785 constructor called once
ok 786 constructor called with right args
ok 787 match start arg
ok 788 start called once
ok 789 stop called once
ok 790 stop after start
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 791 verify failed
ok 792 constructor called once
ok 793 constructor called with right args
ok 794 match start arg
ok 795 start called once
ok 796 stop called once
ok 797 stop after start
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 798 verify failed
ok 799 constructor called once
ok 800 constructor called with right args
ok 801 match start arg
ok 802 start called once
ok 803 stop called once
ok 804 stop after start
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two peers with empty DB, update the doc
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 805 verify failed
ok 806 constructor called once
ok 807 constructor called with right args
ok 808 last start before stop
ok 809 empty first start
ok 810 full second start
ok 811 only 2 timers
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 812 verify failed
ok 813 constructor called once
ok 814 constructor called with right args
ok 815 start before stop
ok 816 We got at least 3 calls to start
ok 817 at least 3
ok 818 default 1
ok 819 1 run
ok 820 default 2
ok 821 2 run
ok 822 default 3
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# start and stop and start and stop
ok 823 start out null
ok 824 back to null
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 825 still null
ok 826 verify failed
ok 827 constructor called once
ok 828 constructor called with right args
ok 829 first start before first stop
ok 830 first stop before second start
ok 831 second start before second stop
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two identical starts in a row
ok 832 verify failed
ok 833 constructor called once
ok 834 constructor called with right args
ok 835 (unnamed assert)
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two different starts in a row
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 836 verify failed
ok 837 constructor called once
ok 838 constructor called with right args
ok 839 (unnamed assert)
ok 840 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 841 verify failed
ok 842 constructor called once
ok 843 constructor called with right args
ok 844 start before stop
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# we properly enqueue requests so no then needed
2016-10-05 17:13:28 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 845 verify failed
ok 846 constructor called once
ok 847 constructor called with right args
ok 848 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 849 should be equal
ok 850 should be equal
# teardown
# setup
# can create servers manager
ok 851 serversManager must not be null
ok 852 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 853 We need to call start first
# teardown
# setup
# can start/stop servers manager
2016-10-05 17:13:28 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:28 - DEBUG createNativeListener: 'listening 50358'
ok 854 port must be in range
# teardown
# setup
# starting twice resolves with listening port
2016-10-05 17:13:28 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:28 - DEBUG createNativeListener: 'listening 50359'
ok 855 second start should return same port
# teardown
# setup
# terminateIncomingConnection will terminate a connection
2016-10-05 17:13:28 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:28 - DEBUG createNativeListener: 'listening 50361'
2016-10-05 17:13:28 - DEBUG createNativeListener: 'new incoming socket'
2016-10-05 17:13:28 - DEBUG createNativeListener: 'creating incoming mux'
2016-10-05 17:13:28 - DEBUG createNativeListener: 'new mux'
ok 856 we should be connected
2016-10-05 17:13:28 - DEBUG createNativeListener: 'incoming socket close'
ok 857 now we are disconnected
# teardown
# setup
# terminate an Outgoing connection will terminate the server
2016-10-05 17:13:28 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:28 - DEBUG createNativeListener: 'listening 50363'
# teardown
# setup
# terminate an Outgoing connection with wrong arguments is not harmful
2016-10-05 17:13:28 - DEBUG createNativeListener: 'creating native server'
2016-10-05 17:13:28 - DEBUG createNativeListener: 'listening 50364'
# teardown
# setup
ok 858 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
ok 859 peer identifier should match
ok 860 host address should match
ok 861 port should match
ok 862 host address should be null
ok 863 port should should be null
# teardown
ok 864 should not be in started state
# setup
ok 865 should be in started state
# #startUpdateAdvertisingAndListening should use different USN after every invocation
2016-10-05 17:13:28 - DEBUG thaliWifiInfrastructure: 'listening 50365'
ok 866 USN should have changed from the first one
ok 867 when receiving the second byebye, the first USN should be already set
# teardown
ok 868 should not be in started state
# setup
ok 869 should be in started state
# messages with invalid location or USN should be ignored
2016-10-05 17:13:28 - WARN thaliWifiInfrastructure: 'Failed to parse a valid port number from location: http://foo.bar:90000'
ok 870 should not have emitted with invalid port
2016-10-05 17:13:28 - WARN thaliWifiInfrastructure: 'Received an invalid USN value: '
ok 871 should not have emitted with invalid USN
# teardown
ok 872 should not be in started state
# setup
ok 873 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 874 irrelevant messages should be ignored
ok 875 relevant messages should not be ignored
ok 876 messages from this device should be ignored
# teardown
ok 877 should not be in started state
# setup
ok 878 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 879 specific error should be returned
# teardown
ok 880 should not be in started state
# setup
ok 881 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 882 specific error should be returned
# teardown
ok 883 should not be in started state
# setup
ok 884 should be in started state
# #start should fail if called twice in a row
ok 885 specific error should be received
# teardown
ok 886 should not be in started state
# setup
ok 887 should be in started state
# should not be started after stop is called
ok 888 should not be started
ok 889 should not be listening
ok 890 should not target listening
ok 891 should not be advertising
ok 892 should not target advertising
# teardown
ok 893 should not be in started state
# setup
ok 894 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
2016-10-05 17:13:28 - ERROR thaliWifiInfrastructure: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 895 specific error should be received
# teardown
ok 896 should not be in started state
# setup
ok 897 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
2016-10-05 17:13:28 - ERROR thaliWifiInfrastructure: 'Router server emitted an error: Error: listen EADDRINUSE'
ok 898 specific error expected
# teardown
ok 899 should not be in started state
# setup
ok 900 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
2016-10-05 17:13:28 - DEBUG thaliWifiInfrastructure: 'listening 50367'
ok 901 server should respond with code 200
# teardown
ok 902 should not be in started state
# setup
ok 903 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
2016-10-05 17:13:28 - DEBUG thaliWifiInfrastructure: 'listening 50369'
ok 904 Connection should be rejected
# teardown
ok 905 should not be in started state
# setup
ok 906 should be in started state
# #stop can be called multiple times in a row
ok 907 should be in stopped state
ok 908 should still be in stopped state
# teardown
ok 909 should not be in started state
# setup
ok 910 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 911 should be in listening state
ok 912 should still be in listening state
# teardown
ok 913 should not be in started state
# setup
ok 914 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 915 should not be in listening state
ok 916 should still not be in listening state
# teardown
ok 917 should not be in started state
# setup
ok 918 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 919 should not be in advertising state
ok 920 should still not be in advertising state
# teardown
ok 921 should not be in started state
# setup
ok 922 should be in started state
# functions are run from a queue in the right order
2016-10-05 17:13:28 - DEBUG thaliWifiInfrastructure: 'listening 50371'
ok 923 call order must match
# teardown
ok 924 should not be in started state
# setup
ok 925 should be in started state
# does not get peer changes from self
2016-10-05 17:13:28 - DEBUG thaliWifiInfrastructure: 'listening 50372'
ok 926 USN must have changed again
# teardown
ok 927 should not be in started state
# setup
ok 928 should be in started state
# network changes are ignored while stopping
2016-10-05 17:13:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 929 should not be called
# teardown
ok 930 should not be in started state
# setup
ok 931 should be in started state
# #startListeningForAdvertisements returns error if wifi is off and fires event when on
2016-10-05 17:13:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 932 wifi should be off
ok 933 specific error expected
2016-10-05 17:13:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 934 discoveryActive should be true
# teardown
ok 935 should not be in started state
# setup
ok 936 should be in started state
# #startUpdateAdvertisingAndListening returns error if wifi is off and fires event when on
2016-10-05 17:13:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 937 wifi should be off
ok 938 specific error expected
2016-10-05 17:13:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-10-05 17:13:30 - DEBUG thaliWifiInfrastructure: 'listening 50373'
ok 939 advertisingActive should be true
# teardown
ok 940 should not be in started state
# setup
ok 941 should be in started state
# when wifi is enabled discovery is activated and peers become available
2016-10-05 17:13:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 942 wifi should be off
ok 943 specific error expected
2016-10-05 17:13:30 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 944 peer identifier should match
ok 945 host address should match
ok 946 port should match
# teardown
ok 947 should not be in started state
2016-10-05 17:13:31 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'desktop''
2016-10-05 17:13:31 - DEBUG SimpleThaliTape: 'skipped tests: '[]''
2016-10-05 17:13:31 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'

1..947
# tests 947
# pass  947

# ok


> thali-cordova-plugin-jxcore@1.0.0 test-meta /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
> jx runTests.js meta_tests

2016-10-05 17:13:34 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testCanBeSkipped.js'
2016-10-05 17:13:34 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testInstall.js'
2016-10-05 17:13:34 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testResultsProcessor.js'
2016-10-05 17:13:34 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testSync.js'
2016-10-05 17:13:34 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testTestSendData.js'
2016-10-05 17:13:34 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testTestUtils.js'
2016-10-05 17:13:34 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/meta_tests/testUnitTestFramework.js'
TAP version 13
# setup
# we should not skip test without 'canBeSkipped' function
ok 1 passed
# teardown
# setup
# we should not skip test with 'canBeSkipped' returned false
ok 2 passed
# teardown
# setup
# we should not skip test with 'canBeSkipped' returned promise with false
ok 3 passed
# teardown
# setup
# we should skip test with 'canBeSkipped' returned true
2016-10-05 17:13:34 - DEBUG SimpleThaliTape: 'test was skipped, name: 'we should skip test with 'canBeSkipped' returned true''
# teardown
# setup
# we should skip test with 'canBeSkipped' returned promise with true
2016-10-05 17:13:34 - DEBUG SimpleThaliTape: 'test was skipped, name: 'we should skip test with 'canBeSkipped' returned promise with true''
# teardown
# setup
# two required plugins should get installed
Trying to install jxcore-cordova version: 0.1.4
[36mDownloading:[39m [32mhttp://jxcore.azureedge.net/jxcore-cordova/0.1.4/release/io.jxcore.node.jx
[39m

[1A[K
Attempt 1 / 3

[1A[K


[1A[K
[36mProgress:[39m [32mDone[39m

[32mExtracting plugin package...[39m

[32mDone.[39m

[32mRemoving plugin from project...[39m

[1A[K
[31mRemoving plugin from project...[39m

[32mAdding plugin to project...[39m

[32mCleaning up...[39m

[32mDone.[39m

Starting to download Thali Cordova plugin from: https://codeload.github.com/thaliproject/Thali_CordovaPlugin/zip/master
2016-10-05 17:14:15 - ERROR TestsProcess: 'uncaught exception, error: 'Error: stream.push() after EOF', stack: 'Error: stream.push() after EOF
    at readableAddChunk (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_readable.js:168:15)
    at SliceStream.Readable.push (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_readable.js:149:10)
    at SliceStream.Transform.push (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_transform.js:145:32)
    at SliceStream.sliceFn (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/pullstream/pullstream.js:81:14)
    at SliceStream._transform (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/slice-stream/slicestream.js:28:10)
    at SliceStream.Transform._read (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_transform.js:184:10)
    at SliceStream.Transform._write (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_transform.js:172:12)
    at doWrite (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_writable.js:237:10)
    at clearBuffer (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_writable.js:316:5)
    at onwrite (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_writable.js:274:7)
    at WritableState.onwrite (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_writable.js:106:5)
    at afterTransform (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_transform.js:104:5)
    at TransformState.afterTransform (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_transform.js:79:12)
    at SliceStream._transform (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/slice-stream/slicestream.js:29:5)
    at SliceStream.Transform._read (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_transform.js:184:10)
    at SliceStream.Readable.read (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_readable.js:362:10)
    at flow (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_readable.js:629:52)
    at InflateRaw.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/thali/install/node_modules/readable-stream/lib/_stream_readable.js:613:7)
    at InflateRaw.emit (events.js:79:17)
    at onwriteDrain (_stream_writable.js:306:12)
    at afterWrite (_stream_writable.js:295:5)
    at onwrite (_stream_writable.js:288:7)
    at WritableState.onwrite (_stream_writable.js:81:5)
    at afterTransform (_stream_transform.js:76:11)
    at TransformState.afterTransform (_stream_transform.js:53:12)
    at Zlib.callback (zlib.js:420:5)''
2016-10-05 17:14:15 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
-e [0;31mcompilation aborted
 [0m
build aborted
 [0m

npm http request GET http://192.168.1.100:4873/nssocket
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/nssocket
npm http fetch GET http://192.168.1.100:4873/nssocket/-/nssocket-0.6.0.tgz
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http fetch 200 http://192.168.1.100:4873/nssocket/-/nssocket-0.6.0.tgz
npm http 200 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/mime-types
npm http 200 http://192.168.1.100:4873/mime-types
npm http 200 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/mime-db
npm http 200 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/unpipe
npm http 200 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/rimraf
npm http fetch GET http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.9.tgz
npm http fetch 200 http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.9.tgz
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/minimatch
npm http fetch GET http://192.168.1.100:4873/path-is-absolute/-/path-is-absolute-1.0.1.tgz
npm http 200 http://192.168.1.100:4873/once
npm http fetch 200 http://192.168.1.100:4873/path-is-absolute/-/path-is-absolute-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/eventemitter2
npm http request GET http://192.168.1.100:4873/lazy
npm http 200 http://192.168.1.100:4873/eventemitter2
npm http 200 http://192.168.1.100:4873/lazy
npm http fetch GET http://192.168.1.100:4873/eventemitter2/-/eventemitter2-0.4.14.tgz
npm http fetch GET http://192.168.1.100:4873/lazy/-/lazy-1.0.11.tgz
npm http fetch 200 http://192.168.1.100:4873/eventemitter2/-/eventemitter2-0.4.14.tgz
npm http fetch 200 http://192.168.1.100:4873/lazy/-/lazy-1.0.11.tgz
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/async
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 200 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.16.3.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.16.3.tgz
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http fetch GET http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http fetch GET http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/wrench
npm http 304 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/end-with
npm http request GET http://192.168.1.100:4873/findit
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/end-with
npm http 200 http://192.168.1.100:4873/findit
npm http 200 http://192.168.1.100:4873/jxc
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/unzip
npm http 200 http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/jsonfile
npm http 304 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/pullstream
npm http request GET http://192.168.1.100:4873/binary
npm http request GET http://192.168.1.100:4873/match-stream
npm http request GET http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/match-stream
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/setimmediate
npm http request GET http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/buffers
npm http 200 http://192.168.1.100:4873/buffers
npm http 200 http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/traverse
npm http 200 http://192.168.1.100:4873/traverse
npm http request GET http://192.168.1.100:4873/natives
npm http 200 http://192.168.1.100:4873/natives
npm http request GET http://192.168.1.100:4873/over
npm http request GET http://192.168.1.100:4873/slice-stream
npm http 200 http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/slice-stream
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/nssocket
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/js-extend
npm http fetch GET http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http 304 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/nssocket
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http fetch 200 http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http fetch GET http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http fetch GET http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http request GET http://192.168.1.100:4873/ltgt
npm http fetch GET http://192.168.1.100:4873/abstract-leveldown/-/abstract-leveldown-2.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/abstract-leveldown/-/abstract-leveldown-2.6.1.tgz
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/pinkie
npm http 200 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/sshpk
npm http 200 http://192.168.1.100:4873/jsprim
npm http fetch GET http://192.168.1.100:4873/sshpk/-/sshpk-1.10.1.tgz
npm http fetch 200 http://192.168.1.100:4873/sshpk/-/sshpk-1.10.1.tgz
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/getpass
npm http 200 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/couchdb-resp-completer
npm http 200 http://192.168.1.100:4873/couchdb-resp-completer
npm http request GET http://192.168.1.100:4873/equals
npm http 200 http://192.168.1.100:4873/equals
npm http request GET http://192.168.1.100:4873/jkroso-type
npm http 200 http://192.168.1.100:4873/jkroso-type
npm http request GET http://192.168.1.100:4873/pouchdb-route
npm http 200 http://192.168.1.100:4873/pouchdb-route
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/eventemitter2
npm http request GET http://192.168.1.100:4873/lazy
npm http 304 http://192.168.1.100:4873/lazy
npm http 304 http://192.168.1.100:4873/eventemitter2
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/yeast
npm http 200 http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
npm http fetch GET http://192.168.1.100:4873/os-tmpdir/-/os-tmpdir-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/os-tmpdir/-/os-tmpdir-1.0.2.tgz
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
In file included from ../src/batch.cc:4:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:8:
In file included from ../src/batch_async.h:15:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Batch, Clear) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
15 warnings generated.
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
14 warnings generated.
In file included from ../src/database.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:18:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/database.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Database, New) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/database.cc:130:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
15 warnings generated.
In file included from ../src/database_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
12 warnings generated.
In file included from ../src/iterator.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/iterator.cc:178:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, Next) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:195:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, End) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:222:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
16 warnings generated.
In file included from ../src/iterator_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
13 warnings generated.
In file included from ../src/leveldown.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:13:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:59:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(leveldown, LeveldownWrap) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:70:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(LeveldownWrap, New) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
In file included from ../src/leveldown.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
16 warnings generated.
In file included from ../src/leveldown_async.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
13 warnings generated.
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }

npm ERR! Darwin 15.6.0
npm ERR! argv "/usr/local/bin/jx" "/Users/thali/.jx/npm/bin/npm-cli.js" "--loglevel" "http" "--color" "true" "run" "test-meta"
npm ERR! node v0.10.40
npm ERR! npm  v3.3.12
npm ERR! code ELIFECYCLE
npm ERR! thali-cordova-plugin-jxcore@1.0.0 test-meta: `jx runTests.js meta_tests`
npm ERR! Exit status 1
npm ERR! 
npm ERR! Failed at the thali-cordova-plugin-jxcore@1.0.0 test-meta script 'jx runTests.js meta_tests'.
npm ERR! Make sure you have the latest version of node.js and npm installed.
npm ERR! If you do, this is most likely a problem with the thali-cordova-plugin-jxcore package,
npm ERR! not with npm itself.
npm ERR! Tell the author that this fails on your system:
npm ERR!     jx runTests.js meta_tests
npm ERR! You can get their info via:
npm ERR!     npm owner ls thali-cordova-plugin-jxcore
npm ERR! There is likely additional logging output above.

npm ERR! Please include the following file with any support request:
npm ERR!     /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/npm-debug.log
bash: shell_session_update: command not found

```

Error: Command failed: npm http request GET http://192.168.1.100:4873/nssocket
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/socket.io
npm http request GET http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/nssocket
npm http fetch GET http://192.168.1.100:4873/nssocket/-/nssocket-0.6.0.tgz
npm http 200 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/fs-extra-promise
npm http fetch 200 http://192.168.1.100:4873/nssocket/-/nssocket-0.6.0.tgz
npm http 200 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/socket.io
npm http 200 http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/accepts
npm http 200 http://192.168.1.100:4873/content-type
npm http 200 http://192.168.1.100:4873/content-disposition
npm http 200 http://192.168.1.100:4873/cookie
npm http 200 http://192.168.1.100:4873/array-flatten
npm http 200 http://192.168.1.100:4873/escape-html
npm http 200 http://192.168.1.100:4873/cookie-signature
npm http 200 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/etag
npm http 200 http://192.168.1.100:4873/depd
npm http 200 http://192.168.1.100:4873/finalhandler
npm http 200 http://192.168.1.100:4873/fresh
npm http 200 http://192.168.1.100:4873/merge-descriptors
npm http 200 http://192.168.1.100:4873/on-finished
npm http 200 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/parseurl
npm http 200 http://192.168.1.100:4873/qs
npm http 200 http://192.168.1.100:4873/proxy-addr
npm http 200 http://192.168.1.100:4873/range-parser
npm http 200 http://192.168.1.100:4873/path-to-regexp
npm http 200 http://192.168.1.100:4873/send
npm http 200 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/utils-merge
npm http 200 http://192.168.1.100:4873/vary
npm http 200 http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/mime-types
npm http 200 http://192.168.1.100:4873/mime-types
npm http 200 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/mime-db
npm http 200 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/ms
npm http 200 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/unpipe
npm http 200 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/ipaddr.js
npm http 200 http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/statuses
npm http 200 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/mime
npm http 200 http://192.168.1.100:4873/destroy
npm http 200 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/media-typer
npm http 200 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 200 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 200 http://192.168.1.100:4873/jsonfile
npm http 200 http://192.168.1.100:4873/graceful-fs
npm http 200 http://192.168.1.100:4873/rimraf
npm http fetch GET http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.9.tgz
npm http fetch 200 http://192.168.1.100:4873/graceful-fs/-/graceful-fs-4.1.9.tgz
npm http request GET http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/minimatch
npm http 200 http://192.168.1.100:4873/fs.realpath
npm http 200 http://192.168.1.100:4873/inflight
npm http 200 http://192.168.1.100:4873/path-is-absolute
npm http 200 http://192.168.1.100:4873/minimatch
npm http fetch GET http://192.168.1.100:4873/path-is-absolute/-/path-is-absolute-1.0.1.tgz
npm http 200 http://192.168.1.100:4873/once
npm http fetch 200 http://192.168.1.100:4873/path-is-absolute/-/path-is-absolute-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/wrappy
npm http 200 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 200 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/concat-map
npm http 200 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/eventemitter2
npm http request GET http://192.168.1.100:4873/lazy
npm http 200 http://192.168.1.100:4873/eventemitter2
npm http 200 http://192.168.1.100:4873/lazy
npm http fetch GET http://192.168.1.100:4873/eventemitter2/-/eventemitter2-0.4.14.tgz
npm http fetch GET http://192.168.1.100:4873/lazy/-/lazy-1.0.11.tgz
npm http fetch 200 http://192.168.1.100:4873/eventemitter2/-/eventemitter2-0.4.14.tgz
npm http fetch 200 http://192.168.1.100:4873/lazy/-/lazy-1.0.11.tgz
npm http request GET http://192.168.1.100:4873/engine.io
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/socket.io-adapter
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/socket.io-adapter
npm http 200 http://192.168.1.100:4873/has-binary
npm http 200 http://192.168.1.100:4873/engine.io
npm http 200 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/base64id
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/ws
npm http 200 http://192.168.1.100:4873/engine.io-parser
npm http 200 http://192.168.1.100:4873/base64id
npm http 200 http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/arraybuffer.slice
npm http 200 http://192.168.1.100:4873/utf8
npm http 200 http://192.168.1.100:4873/blob
npm http 200 http://192.168.1.100:4873/base64-arraybuffer
npm http 200 http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 200 http://192.168.1.100:4873/options
npm http 200 http://192.168.1.100:4873/ultron
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/benchmark
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 200 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http 200 http://192.168.1.100:4873/indexof
npm http 200 http://192.168.1.100:4873/parseuri
npm http 200 http://192.168.1.100:4873/to-array
npm http 200 http://192.168.1.100:4873/object-component
npm http 200 http://192.168.1.100:4873/component-bind
npm http 200 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 200 http://192.168.1.100:4873/has-cors
npm http 200 http://192.168.1.100:4873/parsejson
npm http 200 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 200 http://192.168.1.100:4873/parseqs
npm http 200 http://192.168.1.100:4873/component-inherit
npm http 200 http://192.168.1.100:4873/yeast
npm http request GET http://192.168.1.100:4873/better-assert
npm http 200 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 200 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/eyes
npm http 200 http://192.168.1.100:4873/cycle
npm http 200 http://192.168.1.100:4873/colors
npm http 200 http://192.168.1.100:4873/pkginfo
npm http 200 http://192.168.1.100:4873/stack-trace
npm http 200 http://192.168.1.100:4873/async
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No repository field.
npm WARN EPACKAGEJSON thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/forever-agent
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/body-parser
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/type-is
npm http request GET http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/http-errors
npm http 200 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/iconv-lite
npm http 200 http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/ee-first
npm http 200 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/inline-process-browser
npm http 200 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/unreachable-branch-transform
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/through
npm http 200 http://192.168.1.100:4873/jstransform
npm http 200 http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/base62
npm http 200 http://192.168.1.100:4873/commoner
npm http 200 http://192.168.1.100:4873/source-map
npm http 200 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/mkdirp
npm http 200 http://192.168.1.100:4873/detective
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/private
npm http 200 http://192.168.1.100:4873/q
npm http 200 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/minimist
npm http 200 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 200 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 200 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/falafel
npm http 200 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/foreach
npm http 200 http://192.168.1.100:4873/object-keys
npm http request GET http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 200 http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 200 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/hawk
npm http 200 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.16.3.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.16.3.tgz
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/bluebird
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/chalk
npm http fetch GET http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http fetch 200 http://192.168.1.100:4873/is-my-json-valid/-/is-my-json-valid-2.15.0.tgz
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http fetch GET http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonpointer/-/jsonpointer-4.0.0.tgz
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/sntp
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http fetch GET http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http fetch 200 http://192.168.1.100:4873/jsonschema/-/jsonschema-1.1.0.tgz
npm http request GET http://192.168.1.100:4873/cycle
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/eyes
npm http request GET http://192.168.1.100:4873/pkginfo
npm http request GET http://192.168.1.100:4873/stack-trace
npm http 304 http://192.168.1.100:4873/cycle
npm http 304 http://192.168.1.100:4873/colors
npm http 304 http://192.168.1.100:4873/pkginfo
npm http 304 http://192.168.1.100:4873/eyes
npm http 304 http://192.168.1.100:4873/stack-trace
npm http request GET http://192.168.1.100:4873/jsdoc
npm http 200 http://192.168.1.100:4873/jsdoc
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/wrench
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/wrench
npm http 304 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/underscore
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/fs-extra-promise
npm http request GET http://192.168.1.100:4873/end-with
npm http request GET http://192.168.1.100:4873/findit
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/jxc
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/unzip
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/fs-extra-promise
npm http 304 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/end-with
npm http 200 http://192.168.1.100:4873/findit
npm http 200 http://192.168.1.100:4873/jxc
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/unzip
npm http 200 http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/fs-extra
npm http 304 http://192.168.1.100:4873/fs-extra
npm http request GET http://192.168.1.100:4873/graceful-fs
npm http request GET http://192.168.1.100:4873/jsonfile
npm http request GET http://192.168.1.100:4873/rimraf
npm http 304 http://192.168.1.100:4873/graceful-fs
npm http 304 http://192.168.1.100:4873/jsonfile
npm http 304 http://192.168.1.100:4873/rimraf
npm http request GET http://192.168.1.100:4873/glob
npm http 304 http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/fs.realpath
npm http request GET http://192.168.1.100:4873/inflight
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/minimatch
npm http request GET http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/path-is-absolute
npm http 304 http://192.168.1.100:4873/fs.realpath
npm http 304 http://192.168.1.100:4873/inflight
npm http 304 http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/minimatch
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/path-is-absolute
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/brace-expansion
npm http 304 http://192.168.1.100:4873/brace-expansion
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/adm-zip
npm http 200 http://192.168.1.100:4873/progress
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/inline-process-browser
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/es3ify
npm http 304 http://192.168.1.100:4873/inline-process-browser
npm http 304 http://192.168.1.100:4873/immediate
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/through
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima
npm http 304 http://192.168.1.100:4873/through
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/commoner
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/commoner
npm http 304 http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/detective
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/mkdirp
npm http request GET http://192.168.1.100:4873/private
npm http request GET http://192.168.1.100:4873/q
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/private
npm http 304 http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/mkdirp
npm http 304 http://192.168.1.100:4873/detective
npm http 304 http://192.168.1.100:4873/q
npm http 304 http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 304 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/acorn
npm http 304 http://192.168.1.100:4873/defined
npm http 304 http://192.168.1.100:4873/acorn
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/amdefine
npm http 304 http://192.168.1.100:4873/amdefine
npm http request GET http://192.168.1.100:4873/falafel
npm http request GET http://192.168.1.100:4873/through2
npm http 304 http://192.168.1.100:4873/falafel
npm http 304 http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/object-keys
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/foreach
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/string_decoder
npm http 304 http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/esmangle-evaluator
npm http 304 http://192.168.1.100:4873/esmangle-evaluator
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 200 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/extend
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/stringstream
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/fstream
npm http request GET http://192.168.1.100:4873/pullstream
npm http request GET http://192.168.1.100:4873/binary
npm http request GET http://192.168.1.100:4873/match-stream
npm http request GET http://192.168.1.100:4873/setimmediate
npm http 200 http://192.168.1.100:4873/fstream
npm http 200 http://192.168.1.100:4873/match-stream
npm http 200 http://192.168.1.100:4873/pullstream
npm http 200 http://192.168.1.100:4873/binary
npm http 200 http://192.168.1.100:4873/setimmediate
npm http request GET http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/buffers
npm http 200 http://192.168.1.100:4873/buffers
npm http 200 http://192.168.1.100:4873/chainsaw
npm http request GET http://192.168.1.100:4873/traverse
npm http 200 http://192.168.1.100:4873/traverse
npm http request GET http://192.168.1.100:4873/natives
npm http 200 http://192.168.1.100:4873/natives
npm http request GET http://192.168.1.100:4873/over
npm http request GET http://192.168.1.100:4873/slice-stream
npm http 200 http://192.168.1.100:4873/over
npm http 200 http://192.168.1.100:4873/slice-stream
npm WARN EPACKAGEJSON install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/forever-agent
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/nssocket
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tmp
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/js-extend
npm http fetch GET http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http 304 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/forever-agent
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/inherits
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 304 http://192.168.1.100:4873/multiplex
npm http 304 http://192.168.1.100:4873/randomstring
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/nock
npm http 304 http://192.168.1.100:4873/leveldown-mobile
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 304 http://192.168.1.100:4873/nssocket
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http fetch 200 http://192.168.1.100:4873/uuid-validate/-/uuid-validate-0.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.5-thali.tgz
npm http 200 http://192.168.1.100:4873/sinon
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/bytes
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/raw-body
npm http 304 http://192.168.1.100:4873/type-is
npm http 200 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/statuses
npm http 304 http://192.168.1.100:4873/statuses
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
npm http request GET http://192.168.1.100:4873/unpipe
npm http 304 http://192.168.1.100:4873/unpipe
npm http request GET http://192.168.1.100:4873/media-typer
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/media-typer
npm http 304 http://192.168.1.100:4873/mime-types
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/accepts
npm http request GET http://192.168.1.100:4873/array-flatten
npm http request GET http://192.168.1.100:4873/content-disposition
npm http request GET http://192.168.1.100:4873/cookie
npm http request GET http://192.168.1.100:4873/cookie-signature
npm http request GET http://192.168.1.100:4873/escape-html
npm http request GET http://192.168.1.100:4873/etag
npm http request GET http://192.168.1.100:4873/finalhandler
npm http request GET http://192.168.1.100:4873/fresh
npm http request GET http://192.168.1.100:4873/merge-descriptors
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/parseurl
npm http request GET http://192.168.1.100:4873/path-to-regexp
npm http request GET http://192.168.1.100:4873/proxy-addr
npm http request GET http://192.168.1.100:4873/range-parser
npm http request GET http://192.168.1.100:4873/send
npm http request GET http://192.168.1.100:4873/serve-static
npm http request GET http://192.168.1.100:4873/utils-merge
npm http request GET http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/utils-merge
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/vary
npm http request GET http://192.168.1.100:4873/negotiator
npm http 304 http://192.168.1.100:4873/negotiator
npm http request GET http://192.168.1.100:4873/forwarded
npm http request GET http://192.168.1.100:4873/ipaddr.js
npm http 304 http://192.168.1.100:4873/forwarded
npm http 304 http://192.168.1.100:4873/ipaddr.js
npm http request GET http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http 304 http://192.168.1.100:4873/mime
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http request GET http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/jstransform
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http request GET http://192.168.1.100:4873/indent-string
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http 200 http://192.168.1.100:4873/map-obj
npm http request GET http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/repeating
npm http 200 http://192.168.1.100:4873/get-stdin
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http fetch GET http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/is-finite/-/is-finite-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http fetch GET http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http fetch 200 http://192.168.1.100:4873/number-is-nan/-/number-is-nan-1.0.1.tgz
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/levelup
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/d64
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/d64
npm http 200 http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/xtend
npm http 304 http://192.168.1.100:4873/xtend
npm http request GET http://192.168.1.100:4873/end-stream
npm http 200 http://192.168.1.100:4873/end-stream
npm http request GET http://192.168.1.100:4873/write-stream
npm http 200 http://192.168.1.100:4873/write-stream
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http request GET http://192.168.1.100:4873/ltgt
npm http fetch GET http://192.168.1.100:4873/abstract-leveldown/-/abstract-leveldown-2.6.1.tgz
npm http fetch 200 http://192.168.1.100:4873/abstract-leveldown/-/abstract-leveldown-2.6.1.tgz
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/tough-cookie
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http 304 http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/pinkie-promise
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/pinkie
npm http 200 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/hoek
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/sshpk
npm http 200 http://192.168.1.100:4873/jsprim
npm http fetch GET http://192.168.1.100:4873/sshpk/-/sshpk-1.10.1.tgz
npm http fetch 200 http://192.168.1.100:4873/sshpk/-/sshpk-1.10.1.tgz
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/extsprintf
npm http 200 http://192.168.1.100:4873/verror
npm http 200 http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/getpass
npm http 200 http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/xmlhttprequest-cookie
npm http 200 http://192.168.1.100:4873/xmlhttprequest-cookie
npm http request GET http://192.168.1.100:4873/xmlhttprequest
npm http 200 http://192.168.1.100:4873/xmlhttprequest
npm http request GET http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http 200 http://192.168.1.100:4873/pouchdb-changeslike-wrapper
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/couchdb-render
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/couchdb-render
npm http request GET http://192.168.1.100:4873/couchdb-resp-completer
npm http 200 http://192.168.1.100:4873/couchdb-resp-completer
npm http request GET http://192.168.1.100:4873/equals
npm http 200 http://192.168.1.100:4873/equals
npm http request GET http://192.168.1.100:4873/jkroso-type
npm http 200 http://192.168.1.100:4873/jkroso-type
npm http request GET http://192.168.1.100:4873/pouchdb-route
npm http 200 http://192.168.1.100:4873/pouchdb-route
npm http request GET http://192.168.1.100:4873/get-folder-size
npm http 200 http://192.168.1.100:4873/get-folder-size
npm http request GET http://192.168.1.100:4873/minimist
npm http 304 http://192.168.1.100:4873/minimist
npm http request GET http://192.168.1.100:4873/abstract-leveldown
npm http request GET http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/fast-future
npm http 304 http://192.168.1.100:4873/abstract-leveldown
npm http 200 http://192.168.1.100:4873/fast-future
npm http 200 http://192.168.1.100:4873/bindings
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/duplexify
npm http 304 http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/eventemitter2
npm http request GET http://192.168.1.100:4873/lazy
npm http 304 http://192.168.1.100:4873/lazy
npm http 304 http://192.168.1.100:4873/eventemitter2
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 200 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/lolex
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/formatio
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 200 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/backo2
npm http 200 http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/yeast
npm http 200 http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/utf8
npm http request GET http://192.168.1.100:4873/better-assert
npm http 304 http://192.168.1.100:4873/better-assert
npm http request GET http://192.168.1.100:4873/callsite
npm http 304 http://192.168.1.100:4873/callsite
npm http request GET http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/ultron
npm http 304 http://192.168.1.100:4873/options
npm http request GET http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http 304 http://192.168.1.100:4873/benchmark
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/cookiejar
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
npm http fetch GET http://192.168.1.100:4873/os-tmpdir/-/os-tmpdir-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/os-tmpdir/-/os-tmpdir-1.0.2.tgz
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
In file included from ../src/batch.cc:4:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:5:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:7:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch.cc:8:
In file included from ../src/batch_async.h:15:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/batch.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Batch, Clear) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
15 warnings generated.
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/batch_async.cc:9:
In file included from ../src/batch.h:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
14 warnings generated.
In file included from ../src/database.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database.cc:18:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/database.cc:118:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Database, New) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/database.cc:130:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
15 warnings generated.
In file included from ../src/database_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:10:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/database_async.cc:15:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
12 warnings generated.
In file included from ../src/iterator.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/iterator.cc:178:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, Next) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:195:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(Iterator, End) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
../src/iterator.cc:222:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  JS_DEFINE_STATE_MARKER(com);
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
16 warnings generated.
In file included from ../src/iterator_async.cc:9:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/iterator_async.cc:11:
In file included from ../src/database.h:19:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
13 warnings generated.
In file included from ../src/leveldown.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:13:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
In file included from ../src/iterator.h:17:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:11:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown.cc:13:
../src/batch.h:20:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Batch, Batch) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:59:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(leveldown, LeveldownWrap) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
../src/leveldown.cc:70:1: warning: unused variable '__contextORisolate' [-Wunused-variable]
JS_METHOD(LeveldownWrap, New) {
^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:54:3: note: expanded from macro 'JS_METHOD'
  __JS_METHOD_BEGIN_COM()
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:47:3: note: expanded from macro '__JS_METHOD_BEGIN_COM'
  JS_DEFINE_STATE_MARKER_(p___args.GetIsolate()); \
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:94:53: note: expanded from macro 'JS_DEFINE_STATE_MARKER_'
#define JS_DEFINE_STATE_MARKER_(x) JS_ENGINE_MARKER __contextORisolate = x
                                                    ^
In file included from ../src/leveldown.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
16 warnings generated.
In file included from ../src/leveldown_async.cc:10:
In file included from ../src/leveldown.h:11:
In file included from /Users/thali/.node-gyp/jxb311/src/node_buffer.h:8:
/Users/thali/.node-gyp/jxb311/src/jx/commons.h:328:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(this);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:215:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:224:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:239:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:270:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:278:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:290:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:302:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com_);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:12:
../src/nan.h:320:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
In file included from ../src/database.h:20:
../src/iterator.h:29:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Iterator, Iterator) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
In file included from ../src/async.h:13:
../src/database.h:55:3: warning: unused variable '__contextORisolate' [-Wunused-variable]
  INIT_NAMED_CLASS_MEMBERS(Database, Database) {
  ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/PMacro.h:138:5: note: expanded from macro 'INIT_NAMED_CLASS_MEMBERS'
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:11:
In file included from ../src/leveldown_async.h:12:
../src/async.h:26:5: warning: unused variable '__contextORisolate' [-Wunused-variable]
    JS_DEFINE_STATE_MARKER(com);
    ^
/Users/thali/.node-gyp/jxb311/src/jx/Proxy/V8_3_14/V8Environment.h:92:20: note: expanded from macro 'JS_DEFINE_STATE_MARKER'
  JS_ENGINE_MARKER __contextORisolate = \
                   ^
In file included from ../src/leveldown_async.cc:10:
../src/leveldown.h:51:13: warning: unused function 'DisposeStringOrBufferFromSlice' [-Wunused-function]
static void DisposeStringOrBufferFromSlice(JS_LOCAL_VALUE handle,
            ^
13 warnings generated.
npm WARN EPACKAGEJSON thali-cordova-plugin-jxcore@1.0.0 No repository field.
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }
{ [conflict: Document update conflict]
  status: 409,
  name: 'conflict',
  message: 'Document update conflict',
  error: true }

npm ERR! Darwin 15.6.0
npm ERR! argv "/usr/local/bin/jx" "/Users/thali/.jx/npm/bin/npm-cli.js" "--loglevel" "http" "--color" "true" "run" "test-meta"
npm ERR! node v0.10.40
npm ERR! npm  v3.3.12
npm ERR! code ELIFECYCLE
npm ERR! thali-cordova-plugin-jxcore@1.0.0 test-meta: `jx runTests.js meta_tests`
npm ERR! Exit status 1
npm ERR! 
npm ERR! Failed at the thali-cordova-plugin-jxcore@1.0.0 test-meta script 'jx runTests.js meta_tests'.
npm ERR! Make sure you have the latest version of node.js and npm installed.
npm ERR! If you do, this is most likely a problem with the thali-cordova-plugin-jxcore package,
npm ERR! not with npm itself.
npm ERR! Tell the author that this fails on your system:
npm ERR!     jx runTests.js meta_tests
npm ERR! You can get their info via:
npm ERR!     npm owner ls thali-cordova-plugin-jxcore
npm ERR! There is likely additional logging output above.

npm ERR! Please include the following file with any support request:
npm ERR!     /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/npm-debug.log
bash: shell_session_update: command not found
