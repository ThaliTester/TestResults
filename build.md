#### Test (Fail) 92301105 Build Logs


```


```

```
Already up-to-date.

From https://github.com/thaliproject/Thali_CordovaPlugin
   4d9ddc5..9df6c3a  iOS_squid48_897_13 -> origin/iOS_squid48_897_13

```

```
Your branch is up-to-date with 'origin/master'.
Branch iOS set up to track remote branch iOS from origin.
Auto-merging thali/NextGeneration/thaliMobileNativeWrapper.js
Auto-merging test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
Merge made by the 'recursive' strategy.
 build.sh                                           |  13 +-
 .../ThaliCore/ThaliCore.xcodeproj/project.pbxproj  |   2 +
 .../ApplicationStateNotificationsManager.swift     |  66 +-
 lib/ios/ThaliCore/ThaliCore/Core/Atomic.swift      | 114 +--
 .../ThaliCore/Core/Dictionary+KeyForValue.swift    |  12 +-
 lib/ios/ThaliCore/ThaliCore/Core/Peer.swift        | 170 ++--
 .../ThaliCore/Core/PeerAvailability.swift          |  46 +-
 .../ThaliCore/ThaliCore/Core/ThaliCoreError.swift  |  18 +-
 .../MultipeerConnectivity/Advertiser.swift         | 248 +++---
 .../MultipeerConnectivity/AdvertiserManager.swift  | 263 ++++--
 .../ThaliCore/MultipeerConnectivity/Browser.swift  | 285 ++++---
 .../MultipeerConnectivity/BrowserManager.swift     | 353 +++++---
 .../SocketConnection/AdvertiserRelay.swift         | 195 +++--
 .../ThaliCore/SocketConnection/BrowserRelay.swift  | 264 +++---
 .../ThaliCore/SocketConnection/Session.swift       | 226 +++--
 .../ThaliCore/SocketConnection/TCPClient.swift     |  96 +--
 .../ThaliCore/SocketConnection/TCPListener.swift   | 140 ++--
 .../ThaliCore/SocketConnection/VirtualSocket.swift | 256 +++---
 .../SocketConnection/VirtualSocketBuilder.swift    | 263 ++++--
 .../ThaliCoreCITests/TestRunner/TestRunner.swift   | 172 ++--
 .../AppStateNotificationsManagerTests.swift        |  58 +-
 .../ThaliCoreTests/CoreTests/AtomicTests.swift     | 109 +--
 .../ThaliCoreTests/CoreTests/PeerTests.swift       | 116 ++-
 .../AdvertiserManagerTests.swift                   | 326 +++++---
 .../AdvertiserTests.swift                          | 373 +++++----
 .../BrowserManagerTests.swift                      | 722 ++++++++--------
 .../MultipeerConnectivityTests/BrowserTests.swift  | 536 ++++++------
 .../ThaliCore/ThaliCoreTests/SimpleTestCase.swift  |   6 +-
 .../AdvertiserRelayTests.swift                     | 323 +++----
 .../SocketConnectionTests/BrowserRelayTests.swift  | 570 +++++++------
 .../Mocks/MCSessionMock.swift                      |  21 +-
 .../SocketConnectionTests/RelayTests.swift         | 355 ++++----
 .../SocketConnectionTests/SessionTests.swift       | 438 +++++-----
 .../SocketConnectionTests/TCPClientMock.swift      | 100 +--
 .../SocketConnectionTests/TCPClientTests.swift     | 294 ++++---
 .../SocketConnectionTests/TCPListenerTests.swift   | 926 +++++++++++----------
 .../SocketConnectionTests/TCPServerMock.swift      | 172 ++--
 .../VirtualSocketBuilderTests.swift                | 216 ++---
 .../SocketConnectionTests/VirtualSocketTests.swift | 210 ++---
 .../Utils/MultipeerConnectHelper.swift             |  49 +-
 .../ThaliCoreTests/Utils/String+Random.swift       | 252 +++---
 .../ThaliCoreTests/Utils/StringRandomTests.swift   | 180 ++--
 readme.md                                          |  10 +-
 .../java/io/jxcore/node/ConnectionHelper.java      |   1 -
 .../java/io/jxcore/node/ConnectivityMonitor.java   |  14 +-
 .../java/io/jxcore/node/JXcoreExtension.java       |  16 +-
 src/ios/AppContext.swift                           | 720 ++++++++--------
 src/ios/AppContextTests.swift                      | 733 ++++++++--------
 test/README.md                                     |  26 +-
 test/TestServer/TestFramework.js                   |   6 +-
 test/TestServer/UnitTestFramework.js               |   5 +-
 test/TestServer/index.js                           |   7 +-
 test/www/jxcore/UnitTest_app.js                    |  25 +-
 test/www/jxcore/bv_tests/testCreatePeerListener.js |  66 +-
 .../bv_tests/testLocalSeqManagerCoordinated.js     |   5 +-
 .../jxcore/bv_tests/testThaliManagerCoordinated.js |  26 +-
 test/www/jxcore/bv_tests/testThaliMobile.js        | 836 ++++++++++++++-----
 .../bv_tests/testThaliMobileNativeAndroid.js       |   1 -
 .../bv_tests/testThaliMobileNativeWrapper.js       |   8 +
 test/www/jxcore/bv_tests/testThaliNotification.js  |   9 +-
 .../jxcore/bv_tests/testThaliNotificationClient.js |   8 +
 test/www/jxcore/bv_tests/testThaliPeerAction.js    |  39 +-
 .../jxcore/bv_tests/testThaliPeerPoolOneAtATime.js | 582 +++++++++----
 ...liPullReplicationFromNotificationCoordinated.js |   7 +-
 .../bv_tests/testThaliReplicationPeerAction.js     |  42 +-
 .../testThaliReplicationPeerActionCoordinated.js   |  29 +-
 test/www/jxcore/installCustomPouchDB.js            |   2 +-
 test/www/jxcore/lib/CoordinatedClient.js           |  18 +-
 test/www/jxcore/lib/parsePlatformArg.js            |  17 +
 test/www/jxcore/lib/testUtils.js                   | 108 ++-
 test/www/jxcore/lib/thaliMobileNativeTestUtils.js  |   7 +-
 test/www/jxcore/lib/wifiBasedNativeMock.js         |   4 +-
 test/www/jxcore/meta_tests/testPouchDBAgent.js     |  73 ++
 test/www/jxcore/package.json                       |  12 +-
 test/www/jxcore/runCoordinatedTests.js             |  27 +-
 test/www/jxcore/runTests.js                        |  63 +-
 thali/NextGeneration/makeIntoCloseAllServer.js     |   2 +
 thali/NextGeneration/mux/createNativeListener.js   |  81 +-
 thali/NextGeneration/mux/createPeerListener.js     | 188 +++--
 thali/NextGeneration/mux/thaliTcpServersManager.js |  30 +
 .../notification/thaliNotificationClient.js        |  13 +-
 .../replication/thaliReplicationPeerAction.js      |  85 +-
 thali/NextGeneration/thaliConfig.js                |   2 +-
 thali/NextGeneration/thaliManager.js               |   6 +-
 thali/NextGeneration/thaliMobile.js                |  90 +-
 thali/NextGeneration/thaliMobileNativeWrapper.js   |  47 +-
 .../thaliPeerPool/thaliPeerAction.js               |  13 +
 .../thaliPeerPool/thaliPeerPoolInterface.js        |   1 +
 .../thaliPeerPool/thaliPeerPoolOneAtATime.js       | 108 ++-
 thali/NextGeneration/thaliWifiInfrastructure.js    |   1 +
 thali/install/SSDPReplacer/hook.js                 |   3 +-
 thali/install/setUpDesktop.sh                      |   9 +
 thali/package.json                                 |   6 +-
 93 files changed, 8043 insertions(+), 5748 deletions(-)
 create mode 100644 test/www/jxcore/lib/parsePlatformArg.js
 create mode 100644 test/www/jxcore/meta_tests/testPouchDBAgent.js

Already on 'master'
Switched to a new branch 'iOS'
Note: checking out '9df6c3a'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 9df6c3a... Fixed the typo

```

```
Cordova version:
6.3.1
Start setUpDesktop.sh
Setup TestServer
thali-test-server@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/test/TestServer
├── bluebird@3.4.6 
├─┬ express@4.13.3 
│ ├─┬ accepts@1.2.13 
│ │ ├─┬ mime-types@2.1.13 
│ │ │ └── mime-db@1.25.0 
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
│   ├── graceful-fs@4.1.10 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.5.4 
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

Install Thali Root
[33mPreparing NPM for JXcore (v0.3.1.6) for the first run[39m
[33mDownloading NPM for JXcore[39m
...
[33mextracting /Users/thali/.jx/npm.tar.gz[39m
NPM for JX is ready.
executing... please wait.

> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> "/usr/local/bin/jx" installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> "/usr/local/bin/jx" install/prePublishThaliCordovaPlugin.js

thali@2.1.0
│ /Users/thali/Github/Thali_CordovaPlugin/thali
│ Thali Cordova Plugin
│ git+https://github.com/thaliproject/Thali_CordovaPlugin.git
│ https://github.com/thaliproject/Thali_CordovaPlugin/tree/story_00#readme
├── bluebird@3.4.6 
│   Full featured Promises/A+ implementation with exceptionally good performance
│   git://github.com/petkaantonov/bluebird.git
│   https://github.com/petkaantonov/bluebird
├── body-parser@1.13.3 
│   Node.js body parsing middleware
│   git+https://github.com/expressjs/body-parser.git
│   https://github.com/expressjs/body-parser
├── express@4.13.3 
│   Fast, unopinionated, minimalist web framework
│   git+https://github.com/strongloop/express.git
│   http://expressjs.com/
├── forever-agent@0.6.1  (git+https://github.com/thaliproject/forever-agent.git#f1078b5095dfe00ad0d80779eba75e563b54608b)
│   HTTP Agent that keeps socket connections alive between keep-alive requests. Formerly part of mikeal/request, now a standalone module.
│   git+https://github.com/mikeal/forever-agent.git
│   https://github.com/mikeal/forever-agent#readme
│   git+https://github.com/thaliproject/forever-agent.git#f1078b5095dfe00ad0d80779eba75e563b54608b
├── ip@1.0.1 
│   IP address utilities for node.js
│   git+ssh://git@github.com/indutny/node-ip.git
│   https://github.com/indutny/node-ip
├── javascript-state-machine@2.3.5 
│   A simple finite state machine library
│   git://github.com/jakesgordon/javascript-state-machine.git
│   https://github.com/jakesgordon/javascript-state-machine
├── js-extend@1.0.1 
│   A simple extend function based on underscore
│   git://github.com/vmattos/js-extend.git
│   https://github.com/vmattos/js-extend
├── jsdoc@3.3.3 
│   An API documentation generator for JavaScript.
│   git+https://github.com/jsdoc3/jsdoc.git
│   https://github.com/jsdoc3/jsdoc#readme
├── lie@3.1.0 
│   A basic but performant promise implementation
│   git+https://github.com/calvinmetcalf/lie.git
│   https://github.com/calvinmetcalf/lie#readme
├── long@3.0.3 
│   A Long class for representing a 64-bit two's-complement integer value.
│   git+https://github.com/dcodeIO/long.js.git
│   https://github.com/dcodeIO/long.js#readme
├── multiplex@6.7.0 
│   A binary stream multiplexer. Stream multiple streams of binary data over a single binary stream.
│   git+https://github.com/maxogden/multiplex.git
│   https://github.com/maxogden/multiplex
├── node-ssdp@2.6.5  (git+https://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git+https://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd
├── request@2.64.0 
│   Simplified HTTP request client.
│   git+https://github.com/request/request.git
│   https://github.com/request/request#readme
├── salti@0.2.1  (git+https://github.com/thaliproject/salti.git#32abe64b9cd1a4213aed9012a94e26e06aa9c3ca)
│   Simple Authentication and Authorization for Thali IoT
│   git+https://github.com/thaliproject/salti.git
│   https://github.com/thaliproject/salti#readme
│   git+https://github.com/thaliproject/salti.git#master
├── urlsafe-base64@1.0.0 
│   URL Safe Base64 encoding
│   git+ssh://git@github.com/RGBboy/urlsafe-base64.git
│   https://github.com/RGBboy/urlsafe-base64
├── uuid@2.0.2 
│   Rigorous implementation of RFC4122 (v1 and v4) UUIDs.
│   git+https://github.com/shtylman/node-uuid.git
│   https://github.com/shtylman/node-uuid#readme
└── winston@2.2.0 
    A multi-transport async logging library for Node.js
    git+https://github.com/winstonjs/winston.git
    https://github.com/winstonjs/winston#readme


> thali@2.1.0 postinstall /Users/thali/Github/Thali_CordovaPlugin/thali
> node installCordovaPlugin.js

We believe we are in a clone of the GitHub Repo so we will not install Cordova dependencies

> thali@2.1.0 prepublish /Users/thali/Github/Thali_CordovaPlugin/thali
> node install/prePublishThaliCordovaPlugin.js

/usr/local/lib/node_modules/thali -> /Users/thali/Github/Thali_CordovaPlugin/thali
Install Thali Install Directory
install@0.0.1 /Users/thali/Github/Thali_CordovaPlugin/thali/install
├── bluebird@3.4.6 
├─┬ child-process-promise@1.1.0 
│ └── q@1.4.1 
├── end-with@1.0.2 
├── findit@2.0.0 
├─┬ fs-extra-promise@0.2.0 
│ ├── bluebird@2.11.0 
│ └─┬ fs-extra@0.21.0 
│   ├── graceful-fs@4.1.10 
│   ├── jsonfile@2.4.0 
│   └─┬ rimraf@2.5.4 
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
├─┬ jxc@1.0.14 
│ └─┬ jxtools@0.0.4  (git+https://github.com/ktrzeciaknubisa/jxtools.git#644cf31ea259cb65a97e5c3ed5ea1236dba298a3)
│   ├── adm-zip@0.4.7 
│   └── progress@1.1.8 
├─┬ lie@3.1.0 
│ └── immediate@3.0.6 
├── node-uuid@1.4.7 
├─┬ randomstring@1.1.5 
│ └── array-uniq@1.0.2 
├─┬ request@2.74.0 
│ ├── aws-sign2@0.6.0 
│ ├── aws4@1.5.0 
│ ├─┬ bl@1.1.2 
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
│ │ └─┬ async@2.1.2 
│ │   └── lodash@4.17.2 
│ ├─┬ har-validator@2.0.6 
│ │ ├─┬ chalk@1.1.3 
│ │ │ ├── ansi-styles@2.2.1 
│ │ │ ├── escape-string-regexp@1.0.5 
│ │ │ ├─┬ has-ansi@2.0.0 
│ │ │ │ └── ansi-regex@2.0.0 
│ │ │ ├── strip-ansi@3.0.1 
│ │ │ └── supports-color@2.0.0 
│ │ ├─┬ commander@2.9.0 
│ │ │ └── graceful-readlink@1.0.1 
│ │ ├─┬ is-my-json-valid@2.15.0 
│ │ │ ├── generate-function@2.0.0 
│ │ │ ├─┬ generate-object-property@1.2.0 
│ │ │ │ └── is-property@1.0.2 
│ │ │ ├── jsonpointer@4.0.0 
│ │ │ └── xtend@4.0.1 
│ │ └─┬ pinkie-promise@2.0.1 
│ │   └── pinkie@2.0.4 
│ ├─┬ hawk@3.1.3 
│ │ ├── boom@2.10.1 
│ │ ├── cryptiles@2.0.5 
│ │ ├── hoek@2.16.3 
│ │ └── sntp@1.0.9 
│ ├─┬ http-signature@1.1.1 
│ │ ├── assert-plus@0.2.0 
│ │ ├─┬ jsprim@1.3.1 
│ │ │ ├── extsprintf@1.0.2 
│ │ │ ├── json-schema@0.2.3 
│ │ │ └── verror@1.3.6 
│ │ └─┬ sshpk@1.10.1 
│ │   ├── asn1@0.2.3 
│ │   ├── assert-plus@1.0.0 
│ │   ├─┬ dashdash@1.14.0 
│ │   │ └── assert-plus@1.0.0 
│ │   └─┬ getpass@0.1.6 
│ │     └── assert-plus@1.0.0 
│ ├── is-typedarray@1.0.0 
│ ├── isstream@0.1.2 
│ ├── json-stringify-safe@5.0.1 
│ ├─┬ mime-types@2.1.13 
│ │ └── mime-db@1.25.0 
│ ├── oauth-sign@0.8.2 
│ ├── qs@6.2.1 
│ ├── stringstream@0.0.5 
│ ├─┬ tough-cookie@2.3.2 
│ │ └── punycode@1.4.1 
│ └── tunnel-agent@0.4.3 
├─┬ unzip@0.1.11 
│ ├─┬ binary@0.3.0 
│ │ ├── buffers@0.1.1 
│ │ └─┬ chainsaw@0.1.0 
│ │   └── traverse@0.3.9 
│ ├─┬ fstream@0.1.31 
│ │ ├─┬ graceful-fs@3.0.11 
│ │ │ └── natives@1.1.0 
│ │ ├── inherits@2.0.3 
│ │ └─┬ mkdirp@0.5.1 
│ │   └── minimist@0.0.8 
│ ├─┬ match-stream@0.0.2 
│ │ └─┬ readable-stream@1.0.34 
│ │   └── isarray@0.0.1 
│ ├─┬ pullstream@0.4.1 
│ │ ├── over@0.0.5 
│ │ ├─┬ readable-stream@1.0.34 
│ │ │ └── isarray@0.0.1 
│ │ └─┬ slice-stream@1.0.0 
│ │   └─┬ readable-stream@1.0.34 
│ │     └── isarray@0.0.1 
│ ├─┬ readable-stream@1.0.34 
│ │ ├── core-util-is@1.0.2 
│ │ ├── isarray@0.0.1 
│ │ └── string_decoder@0.10.31 
│ └── setimmediate@1.0.5 
└─┬ xcode@0.8.9 
  ├── pegjs@0.9.0 
  └─┬ simple-plist@0.1.4 
    ├─┬ bplist-creator@0.0.4 
    │ └── stream-buffers@0.2.6 
    ├── bplist-parser@0.0.6 
    └─┬ plist@1.2.0 
      ├── base64-js@0.0.8 
      ├─┬ xmlbuilder@4.0.0 
      │ └── lodash@3.10.1 
      └── xmldom@0.1.22 

Final Desktop Step
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
thali-cordova-plugin-jxcore@1.0.0
│ /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore
│ Thali Cordova Plugin JXCore
├── balanced-match@0.2.0 
│   Match balanced character pairs, like "{" and "}"
│   git://github.com/juliangruber/balanced-match.git
│   https://github.com/juliangruber/balanced-match
├── bluebird@3.4.6 
│   Full featured Promises/A+ implementation with exceptionally good performance
│   git://github.com/petkaantonov/bluebird.git
│   https://github.com/petkaantonov/bluebird
├── bn.js@4.10.0 
│   Big number implementation in pure javascript
│   git+ssh://git@github.com/indutny/bn.js.git
│   https://github.com/indutny/bn.js
├── body-parser@1.13.3 
│   Node.js body parsing middleware
│   git+https://github.com/expressjs/body-parser.git
│   https://github.com/expressjs/body-parser
├── child-process-promise@1.1.0 
│   Simple wrapper around the "child_process" module that makes use of promises
│   git+https://github.com/patrick-steele-idem/child-process-promise.git
│   https://github.com/patrick-steele-idem/child-process-promise
├── concat-map@0.0.1 
│   concatenative mapdashery
│   git://github.com/substack/node-concat-map.git
│   https://github.com/substack/node-concat-map
├── express@4.13.3 
│   Fast, unopinionated, minimalist web framework
│   git+https://github.com/strongloop/express.git
│   http://expressjs.com/
├── express-pouchdb@1.0.6-thali 
│   Express submodule with a CouchDB style REST interface to PouchDB.
│   git://github.com/pouchdb/express-pouchdb.git
│   https://github.com/pouchdb/express-pouchdb
├── forever-agent@0.6.1  (git+https://github.com/thaliproject/forever-agent.git#f1078b5095dfe00ad0d80779eba75e563b54608b)
│   HTTP Agent that keeps socket connections alive between keep-alive requests. Formerly part of mikeal/request, now a standalone module.
│   git+https://github.com/mikeal/forever-agent.git
│   https://github.com/mikeal/forever-agent#readme
│   git+https://github.com/thaliproject/forever-agent.git#f1078b5095dfe00ad0d80779eba75e563b54608b
├── fs-extra-promise@0.4.0
│   Node file system library and fs-extra module promisified with bluebird
│   git+https://github.com/overlookmotel/fs-extra-promise.git
│   https://github.com/overlookmotel/fs-extra-promise#readme
├── inherits@2.0.1 
│   Browser-friendly inheritance fully compatible with standard node.js inherits()
│   git://github.com/isaacs/inherits.git
│   https://github.com/isaacs/inherits#readme
├── is-property@1.0.2 
│   Tests if a JSON property can be accessed using . syntax
│   git://github.com/mikolalysenko/is-property.git
│   https://github.com/mikolalysenko/is-property
├── js-extend@1.0.1 
│   A simple extend function based on underscore
│   git://github.com/vmattos/js-extend.git
│   https://github.com/vmattos/js-extend
├── leveldown-mobile@1.1.1 
│   A Node.js LevelDB binding for Android, iOS and Windows UWP, primary backend for LevelUP
│   git+https://github.com/level/leveldown-mobile.git
│   https://github.com/level/leveldown-mobile
├── lie@3.0.4 
│   A basic but performant promise implementation
│   git+https://github.com/calvinmetcalf/lie.git
│   https://github.com/calvinmetcalf/lie#readme
├── long@3.0.3 
│   A Long class for representing a 64-bit two's-complement integer value.
│   git+https://github.com/dcodeIO/long.js.git
│   https://github.com/dcodeIO/long.js#readme
├── minimist@1.2.0 
│   parse argument options
│   git://github.com/substack/minimist.git
│   https://github.com/substack/minimist
├── multiplex@6.7.0 
│   A binary stream multiplexer. Stream multiple streams of binary data over a single binary stream.
│   git+https://github.com/maxogden/multiplex.git
│   https://github.com/maxogden/multiplex
├── nock@2.12.0 
│   HTTP Server mocking for Node.js
│   git+ssh://git@github.com/pgte/nock.git
│   https://github.com/pgte/nock
├── node-ssdp@2.6.5  (git+https://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd)
│   A node.js SSDP client and server library.
│   git+ssh://git@github.com/diversario/node-ssdp.git
│   https://github.com/diversario/node-ssdp#readme
│   git+https://github.com/thaliproject/node-ssdp.git#caf1a75aa54fb47a9e51b72bf4c902c366536cbd
├── node-uuid@1.4.7 
│   Rigorous implementation of RFC4122 (v1 and v4) UUIDs.
│   git+https://github.com/broofa/node-uuid.git
│   https://github.com/broofa/node-uuid
├── object-assign@4.1.0 
│   ES2015 Object.assign() ponyfill
│   git+https://github.com/sindresorhus/object-assign.git
│   https://github.com/sindresorhus/object-assign#readme
├── pouchdb@5.4.5 
│   PouchDB is a pocket-sized database
│   git+https://github.com/pouchdb/pouchdb.git
│   https://github.com/pouchdb/pouchdb#readme
├── pouchdb-size@1.2.2 
│   Adds disk_size to info()'s output for your leveldown backed PouchDB's.
│   git+https://github.com/marten-de-vries/pouchdb-size.git
│   https://github.com/marten-de-vries/pouchdb-size#readme
├── proxyquire@1.7.4 
│   Proxies nodejs require in order to allow overriding dependencies during testing.
│   git+https://github.com/thlorenz/proxyquire.git
│   https://github.com/thlorenz/proxyquire#readme
├── randomstring@1.1.5 
│   A module for generating random strings
│   git://github.com/klughammer/node-randomstring.git
│   https://github.com/klughammer/node-randomstring
├── request@2.64.0 
│   Simplified HTTP request client.
│   git+https://github.com/request/request.git
│   https://github.com/request/request#readme
├── request-promise@0.4.3 
│   The world-famous HTTP client 'Request' now Promises/A+ compliant. Powered by Bluebird.
│   git+https://github.com/request/request-promise.git
│   https://github.com/request/request-promise
├── salti@0.2.1  (git+https://github.com/thaliproject/salti.git#32abe64b9cd1a4213aed9012a94e26e06aa9c3ca)
│   Simple Authentication and Authorization for Thali IoT
│   git+https://github.com/thaliproject/salti.git
│   https://github.com/thaliproject/salti#readme
│   git+https://github.com/thaliproject/salti.git#master
├── sinon@1.17.3 
│   JavaScript test spies, stubs and mocks.
│   git+ssh://git@github.com/cjohansen/Sinon.JS.git
│   http://sinonjs.org/
├── socket.io-client@1.4.8 
│   [![Build Status](https://secure.travis-ci.org/socketio/socket.io-client.svg)](http://travis-ci.org/socketio/socket.io-client) [![Dependency Status](https://david-dm.org/socketio/socket.io-client.svg)](https://david-dm.org/socketio/socket.io-client) [![dev
│   git+https://github.com/Automattic/socket.io-client.git
│   https://github.com/Automattic/socket.io-client#readme
├── supertest@1.1.0 
│   Super-agent driven library for testing HTTP servers
│   git+https://github.com/visionmedia/supertest.git
│   https://github.com/visionmedia/supertest#readme
├── supertest-as-promised@2.0.2 
│   Supercharge supertest with a promise interface
│   git://github.com/WhoopInc/supertest-as-promised.git
│   https://github.com/WhoopInc/supertest-as-promised
├── tape@4.0.0 
│   tap-producing test harness for node and browsers
│   git://github.com/substack/tape.git
│   https://github.com/substack/tape
├── tape-catch@1.0.4 
│   a wrapper around tape that catches and reports exceptions
│   git+https://github.com/michaelrhodes/tape-catch.git
│   https://github.com/michaelrhodes/tape-catch
├── thali@2.1.0 -> /Users/thali/Github/Thali_CordovaPlugin/thali
│   Thali Cordova Plugin
│   git+https://github.com/thaliproject/Thali_CordovaPlugin.git
│   https://github.com/thaliproject/Thali_CordovaPlugin/tree/story_00#readme
├── tmp@0.0.28 
│   Temporary file and directory creator
│   git://github.com/raszi/node-tmp.git
│   http://github.com/raszi/node-tmp
├── urlsafe-base64@1.0.0 
│   URL Safe Base64 encoding
│   git+ssh://git@github.com/RGBboy/urlsafe-base64.git
│   https://github.com/RGBboy/urlsafe-base64
├── uuid@2.0.0 
│   Rigorous implementation of RFC4122 (v1 and v4) UUIDs.
│   git+https://github.com/shtylman/node-uuid.git
│   https://github.com/shtylman/node-uuid
└── uuid-validate@0.0.2 
    Javascript validator for UUID versions 1 through 5
    git+https://github.com/MCProHosting/uuid-validate.git
    https://github.com/MCProHosting/uuid-validate

End setUpDesktop.sh
2016-11-21 11:09:53 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
2016-11-21 11:09:53 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-21 11:09:53 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-21 11:09:53 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-21 11:09:53 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-21 11:09:53 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-21 11:09:53 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-21 11:09:53 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-21 11:09:54 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2016-11-21 11:09:54 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:09:54 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:09:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:09:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:09:54 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:09:54 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49650'
ok 1 Should throw
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49652'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 2 initial connection state should be CONNECTED
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 3 final connection state should be DISCONNECTED
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49655'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49659'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49664'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49668'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 14 we should not have gotten an error
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49672'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49676'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 20 we should not have gotten an error
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 21 Buffers are identical
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49680'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49732'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 31 we should not have gotten an error
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 32 Buffers are identical
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49736'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 38 we should not have gotten an error
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 39 Buffers are identical
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49741'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49744'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener (pleaseConnect === false)
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49747'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 49748'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 45 port must be in range
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49751'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 49752'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peerId'
2016-11-21 11:09:54 - WARN createPeerListener: 'callNative for peerId failed with Unknown Peer'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Unknown Peer" and peerIdentifier "peerId"'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Will try to recreate server for peerId'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peerId'
ok 46 should get error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 49753'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peerId and portNumber 49753'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49756'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49757'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 port values should be the same
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49760'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49761'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 48 Data should be of same length and content
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49766'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 49766'
ok 49 same peer ID
ok 50 different ports
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49769'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49770'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 51 Data should be of same length and content
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 49775'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 49775'
ok 52 same peer ID
ok 53 different ports
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# peerListener - forwardConnection, pleaseConnect === true - no native server
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49778'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49779'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 56 reason should be as expected
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49781'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49781'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49784'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49785'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 59 peerPort should not be nativePort
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - finish'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49788'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49788'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49791'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49792'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 64 Should get spontaneous connection
ok 65 peerPort != nativePort
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49796'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49797'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 68 peerPort != nativePort
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
ok 69 Should not get unexpected connection
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
# setup
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49802'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49803'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# createPeerListener is idempotent
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49809'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49810'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 74 Second call to existing peerListener returns existing port
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49813'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49814'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - WARN createPeerListener: 'callNative for peer1 failed with a nasty error'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: a nasty error" and peerIdentifier "peer1"'
ok 77 got our failed connection
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
ok 78 failed connection should reject with error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49815'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49815'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49818'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49819'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 81 promise should resolve
ok 82 Should get spontaneous connection
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - reverseConnection, pleaseConnect === true
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49823'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49824'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - WARN createPeerListener: 'was expecting a forward connection to be made'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 85 reason should be as expected
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49825'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49825'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49828'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49829'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 88 peerPort should not be nativePort
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'no mux found'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Incoming connection died" and peerIdentifier "peer1"'
ok 89 should not get event until connection is made
ok 90 reason should be as expected
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49831'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 49831'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49834'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49835'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'looking up mux for client port:  49837'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'looking up mux for client port:  49837'
ok 93 sent and received should be the same
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49840'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49841'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'looking up mux for client port:  49843'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'looking up mux for client port:  49843'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 96 should get routerPortConnectionFailed
2016-11-21 11:09:54 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49847'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49850'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect = false - test timeout
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49853'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect = true - test timeout
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49856'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - forward connection - wrong serverPort
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49859'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - forward connection - wrong clientPort
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49862'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - please connect = false, multiple connections out
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49865'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49868'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple parallel calls
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49871'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - we shouldn't create a dead pipe
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Creating Native Server'
ok 97 Can call startUpdateAdvertisingAndListening without error
ok 98 Can call startListeningForAdvertisements without error
2016-11-21 11:09:54 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'listening 49874'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 49875'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 99 peerPort != nativePort
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 100 Should not get unexpected connection
2016-11-21 11:09:54 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 49875'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
ok 101 passed
2016-11-21 11:09:54 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
# #_doImmediateSeqUpdate - server is not there
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:09:54 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-21 11:09:54 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 102 Got right error
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-11-21 11:09:54 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 103 Got socket hang up
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-11-21 11:09:54 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 104 Got 500 as expected
# teardown
2016-11-21 11:09:54 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 105 should be equal
ok 106 revs are equal
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 107 should be equal
ok 108 revs are equal
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 109 should be equal
ok 110 revs are equal
ok 111 should be equal
ok 112 revs are equal
ok 113 should be equal
ok 114 revs are equal
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2016-11-21 11:09:55 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 115 Our rev is old so we should fail
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 116 confirm stop caused failure
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-11-21 11:09:55 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 117 stop caused us to fail
ok 118 We specifically failed on a stop before put
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - fail if stop is called
ok 119 failed due to stop
ok 120 failed due to stop
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - set seq for first time
ok 121 should be equal
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - Fail on bad seq value
2016-11-21 11:09:55 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 122 Expected bad seq error
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we cancel timer properly on an immediate?
ok 123 Different promises
ok 124 Timer was cancelled
ok 125 should be equal
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we wait for blocked update
ok 126 One go and one blocked
ok 127 All blocked
ok 128 Still blocked
ok 129 should be equal
# teardown
2016-11-21 11:09:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we wait long enough
ok 130 We waited long enough
ok 131 should be equal
# teardown
2016-11-21 11:09:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we pick up new sequences while we wait
ok 132 Should have gotten same timer promise
ok 133 Still same timer promise
ok 134 We waited long enough
ok 135 should be equal
# teardown
2016-11-21 11:09:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# closeAll can close even when connections open
2016-11-21 11:09:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 136 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
2016-11-21 11:09:57 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 137 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
2016-11-21 11:09:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 138 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
2016-11-21 11:09:58 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 139 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 140 should be equal
ok 141 should be equal
ok 142 should be equal
# teardown
# setup
# test defaultAdapter
ok 143 should be equal
ok 144 should be equal
ok 145 should be equal
ok 146 should be equal
ok 147 should be equal
ok 148 should be equal
ok 149 should be equal
ok 150 should be equal
# teardown
# setup
# enqueue and run in order
ok 151 firstPromise setTimeout
ok 152 firstPromise result
ok 153 firstPromise testValue
ok 154 secondPromise setTimeout
ok 155 secondPromise result
ok 156 secondPromise testValue
ok 157 thirdPromise in promise
ok 158 thirdPromise result
ok 159 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 160 thirdPromise - first to run
ok 161 thirdPromise - in resolve
ok 162 secondPromise - second to run
ok 163 secondPromise - in catch
ok 164 firstPromise - third to run
ok 165 firstPromise - in then
ok 166 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 167 fourth
ok 168 fourth
ok 169 second
ok 170 secondPromise - in then
ok 171 first
ok 172 firstPromise - in catch
ok 173 third
ok 174 thirdPromise - in then
ok 175 testingPromises
# teardown
# setup
# queues handled independently
ok 176 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 177 sane
# teardown
# setup
# another
ok 178 sane
# teardown
# setup
# test thali manager spies
2016-11-21 11:10:00 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-21 11:10:00 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-21 11:10:00 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 179 expressPouchDB was called once
ok 180 expressPouchDB was called with 2 arguments
ok 181 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 182 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 183 PouchDB was called once
ok 184 PouchDB was called with 1 arguments
ok 185 PouchDB was called with 'dbName' as 1-st argument
ok 186 ThaliSendNotificationBasedOnReplication was called once
ok 187 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 188 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 189 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 190 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 191 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 192 ThaliPullReplicationFromNotification was called once
ok 193 ThaliPullReplicationFromNotification was called with 4 arguments
ok 194 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 195 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 196 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 197 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 198 Salti was called once
ok 199 Salti was called with 4 arguments
ok 200 Salti was called with 'dbName' as 1-st argument
ok 201 Salti was called with 'acl' as 2-st argument
ok 202 Salti was called with 'thaliIdCallback' as 3-st argument
ok 203 Salti was called with 'options' as 4-st argument
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-21 11:10:00 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-21 11:10:00 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-21 11:10:00 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-21 11:10:00 - DEBUG thaliWifiInfrastructure: 'listening 49953'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 204 ThaliMobile.start was called once
ok 205 ThaliMobile.start was called with 3 arguments
ok 206 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 207 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 208 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 209 ThaliMobile.startListeningForAdvertisements was called once
ok 210 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 211 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 212 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 213 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 214 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 216 ThaliPullReplicationFromNotification.prototype.start was called once
ok 217 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 218 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-21 11:10:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 219 ThaliMobile.stop was called once
ok 220 ThaliMobile.stop was called with 0 arguments
ok 221 ThaliMobile.stopListeningForAdvertisements was called once
ok 222 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 223 ThaliMobile.stopAdvertisingAndListening was called once
ok 224 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 225 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 226 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 227 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 228 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-11-21 11:10:00 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-21 11:10:00 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-21 11:10:00 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 229 expressPouchDB was called once
ok 230 expressPouchDB was called with 2 arguments
ok 231 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 232 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 233 PouchDB was called once
ok 234 PouchDB was called with 1 arguments
ok 235 PouchDB was called with 'dbName' as 1-st argument
ok 236 ThaliSendNotificationBasedOnReplication was called once
ok 237 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 238 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 239 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 240 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 241 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 242 ThaliPullReplicationFromNotification was called once
ok 243 ThaliPullReplicationFromNotification was called with 4 arguments
ok 244 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 245 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 246 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 247 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 248 Salti was called once
ok 249 Salti was called with 4 arguments
ok 250 Salti was called with 'dbName' as 1-st argument
ok 251 Salti was called with 'acl' as 2-st argument
ok 252 Salti was called with 'thaliIdCallback' as 3-st argument
ok 253 Salti was called with 'options' as 4-st argument
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-21 11:10:00 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-21 11:10:00 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-21 11:10:00 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-21 11:10:00 - DEBUG thaliWifiInfrastructure: 'listening 49954'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 254 ThaliMobile.start was called once
ok 255 ThaliMobile.start was called with 3 arguments
ok 256 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 257 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 258 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 259 ThaliMobile.startListeningForAdvertisements was called once
ok 260 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 261 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 262 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 263 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 264 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 265 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 266 ThaliPullReplicationFromNotification.prototype.start was called once
ok 267 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 268 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-21 11:10:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping ThaliMobile'
ok 269 ThaliMobile.stop was called once
ok 270 ThaliMobile.stop was called with 0 arguments
ok 271 ThaliMobile.stopListeningForAdvertisements was called once
ok 272 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 273 ThaliMobile.stopAdvertisingAndListening was called once
ok 274 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 275 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 276 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 277 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 278 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-21 11:10:00 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-21 11:10:00 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-21 11:10:00 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-21 11:10:00 - DEBUG thaliWifiInfrastructure: 'listening 49955'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-21 11:10:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-21 11:10:00 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-21 11:10:00 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-21 11:10:00 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-21 11:10:00 - DEBUG thaliWifiInfrastructure: 'listening 49956'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-21 11:10:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-21 11:10:00 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-21 11:10:00 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-21 11:10:00 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-21 11:10:00 - DEBUG thaliWifiInfrastructure: 'listening 49957'
2016-11-21 11:10:00 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 279 ThaliMobile.start was called once
ok 280 ThaliMobile.start was called with 3 arguments
ok 281 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 282 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 283 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 284 ThaliMobile.startListeningForAdvertisements was called once
ok 285 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 286 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 287 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 288 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 289 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 290 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 291 ThaliPullReplicationFromNotification.prototype.start was called once
ok 292 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 293 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-21 11:10:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-21 11:10:00 - DEBUG thaliManager: 'stopping ThaliMobile'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 294 specific error should be returned
# teardown
ok 295 error should be null
ok 296 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 297 specific error should be returned
# teardown
ok 298 error should be null
ok 299 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
ok 300 error should be null
ok 301 error should be null
ok 302 error should be null
ok 303 error should be null
# teardown
ok 304 error should be null
ok 305 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
ok 306 error should be null
ok 307 error should be null
ok 308 error should be null
ok 309 error should be null
# teardown
2016-11-21 11:10:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 310 error should be null
ok 311 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-21 11:10:00 - DEBUG thaliWifiInfrastructure: 'listening 49958'
ok 312 error should be null
ok 313 error should be null
ok 314 error should be null
ok 315 error should be null
# teardown
2016-11-21 11:10:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 316 error should be null
ok 317 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
ok 318 error should be null
ok 319 error should be null
ok 320 error should be null
ok 321 error should be null
# teardown
ok 322 error should be null
ok 323 error should be null
# setup
# #start - Causing native or wifi to fail will cause a promise reject 
2016-11-21 11:10:00 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
ok 324 This should not cause wifi to fail
ok 325 native router should be bad
# teardown
ok 326 error should be null
ok 327 error should be null
# setup
# #start should fail if called twice in a row
ok 328 first call should succeed
ok 329 first call should succeed
ok 330 specific error should be returned
# teardown
ok 331 error should be null
ok 332 error should be null
# setup
# #stop should clear watchers and change peers
2016-11-21 11:10:00 - DEBUG thaliMobileNativeWrapper: 'listening 49959'
2016-11-21 11:10:00 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:00 - DEBUG createNativeListener: 'listening 49960'
2016-11-21 11:10:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:00 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:5f562a52-4202-4108-9a1a-07fcdd3f8a13","peerAvailable":true,"pleaseConnect":false}'
2016-11-21 11:10:00 - DEBUG createPeerListener: 'creating new server for urn:uuid:5f562a52-4202-4108-9a1a-07fcdd3f8a13'
2016-11-21 11:10:00 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:5f562a52-4202-4108-9a1a-07fcdd3f8a13 listening on 49961'
2016-11-21 11:10:00 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:00 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:5f562a52-4202-4108-9a1a-07fcdd3f8a13","peerAvailable":true,"portNumber":49961}'
ok 333 Watchers have one entry for our connection type
ok 334 Peer availabilities has one entry for our connection type
2016-11-21 11:10:00 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:5f562a52-4202-4108-9a1a-07fcdd3f8a13","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-21 11:10:00 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:00 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:00 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:00 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:5f562a52-4202-4108-9a1a-07fcdd3f8a13'
2016-11-21 11:10:00 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 335 No watchers
ok 336 No peers
ok 337 No watchers
ok 338 No peers
ok 339 No watchers
ok 340 No peers
# teardown
ok 341 error should be null
ok 342 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-11-21 11:10:01 - DEBUG thaliWifiInfrastructure: 'listening 49962'
ok 343 called only once
ok 344 discovery state matches
ok 345 advertising state matches
# teardown
2016-11-21 11:10:01 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:01 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:01 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 346 error should be null
ok 347 error should be null
# setup
# does not send duplicate availability changes
ok 348 should be called once
ok 349 should not have been called more than once
# teardown
2016-11-21 11:10:02 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"7834c400-7803-4e59-bd73-1e76ba818769","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 350 error should be null
ok 351 error should be null
# setup
# can get the network status
ok 352 network status should have certain non-empty properties
# teardown
ok 353 error should be null
ok 354 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-11-21 11:10:02 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"ed920e93-8b98-4b49-926c-65008061cf16","generation":0,"hostAddress":"ea6eac61","portNumber":8080}'
ok 355 peer should be available
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ed920e93-8b98-4b49-926c-65008061cf16","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 356 peer should become unavailable
# teardown
2016-11-21 11:10:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 357 error should be null
ok 358 error should be null
# setup
# native peer should be removed if no availability updates were received during availability timeout
ok 359 peer is available
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"ad0d26c6-85a5-4be0-af74-c07cc8cc3a2d","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 360 peer is not availabel because it was too silent
# teardown
ok 361 error should be null
ok 362 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (native)
ok 363 we have not added peer to the cache yet
ok 364 peer should be available
ok 365 cache contains native peer
ok 366 peer should be unavailable
ok 367 peer has been removed from cache
# teardown
ok 368 error should be null
ok 369 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
ok 370 we have not added peer to the cache yet
ok 371 peer should be available
ok 372 cache contains wifi peer
ok 373 peer should be unavailable
ok 374 peer has been removed from cache
# teardown
ok 375 error should be null
ok 376 error should be null
# setup
# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
ok 377 first peer is available
ok 378 second peer is available
ok 379 first and second peers are different
# teardown
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d0d48958-3a39-4089-b376-d67239ec2387","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"bcf4ac7b-564d-4ad7-8827-7f3ab56e67c2","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 380 error should be null
ok 381 error should be null
# setup
# native available - new peer is cached
ok 382 should not be in cache at start
ok 383 peer is available
# teardown
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"d57e0d59-b795-4722-ad26-52bfc8e89bf7","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 384 error should be null
ok 385 error should be null
# setup
# native available - peer with same port and different generation is cached (BLUETOOTH)
ok 386 peer should be available
ok 387 peer should be available
ok 388 peer should be available
# teardown
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"99b1e424-ebac-424a-a373-12b827017a11","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 389 error should be null
ok 390 error should be null
# setup
# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
ok 391 peer should be available
ok 392 peer should be available
# teardown
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9adeb77f-b7c0-41d7-8684-6126ac4c4103","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 393 error should be null
ok 394 error should be null
# setup
# native available - peer with greater generation is cached (MPCF)
2016-11-21 11:10:03 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with greater generation is cached (MPCF)''
# teardown
ok 395 error should be null
ok 396 error should be null
# setup
# native available - peer with same or older generation is ignored (MPCF)
2016-11-21 11:10:03 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with same or older generation is ignored (MPCF)''
# teardown
ok 397 error should be null
ok 398 error should be null
# setup
# native unavailable - new peer is ignored
ok 399 NOT IMPLEMENTED # SKIP
# teardown
ok 400 error should be null
ok 401 error should be null
# setup
# native unavailable - cached peer is removed
ok 402 NOT IMPLEMENTED # SKIP
# teardown
ok 403 error should be null
ok 404 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for wifi peers
ok 405 first peer is expected to be available
ok 406 second peer is expected to be available
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c94d5cb1-fd1a-400c-a33a-dc9eeefbc1c0","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 407 peer became unavailable
ok 408 it was wifi peer
# teardown
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1d6cd078-6a62-4add-beb6-bc6db534c7e5","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 409 error should be null
ok 410 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
ok 411 first peer is expected to be available
ok 412 second peer is expected to be available
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1722859c-43f3-4473-a60b-1727cb7586e5","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 413 peer became unavailable
ok 414 it was a native peer
# teardown
2016-11-21 11:10:03 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"1e9f7337-ba70-4d04-afdc-8b0b9f97e747","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 415 error should be null
ok 416 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
2016-11-21 11:10:03 - DEBUG SimpleThaliTape: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''
# teardown
ok 417 error should be null
ok 418 error should be null
# setup
# multiconnect failure - new peer is ignored (MPCF)
2016-11-21 11:10:03 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
# teardown
ok 419 error should be null
ok 420 error should be null
# setup
# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
2016-11-21 11:10:03 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
# teardown
ok 421 error should be null
ok 422 error should be null
# setup
# newAddressPort field (TCP_NATIVE)
ok 423 peer discovered first time does not have new address
ok 424 address has not been changed
ok 425 new port handled correctly
ok 426 new host handled correctly
ok 427 newAddressPort is null for unavailable peers
# teardown
ok 428 error should be null
ok 429 error should be null
# setup
# newAddressPort field (BLUETOOTH)
ok 430 peer discovered first time does not have new address
ok 431 address has not been changed
ok 432 new port handled correctly
ok 433 newAddressPort is null for unavailable peers
# teardown
ok 434 error should be null
ok 435 error should be null
# setup
# newAddressPort field (MPCF)
2016-11-21 11:10:03 - DEBUG SimpleThaliTape: 'test was skipped, name: 'newAddressPort field (MPCF)''
# teardown
ok 436 error should be null
ok 437 error should be null
# setup
# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
ok 438 NOT IMPLEMENTED # SKIP
# teardown
ok 439 error should be null
ok 440 error should be null
# setup
# network changes emitted correctly
2016-11-21 11:10:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 441 wifi is off
2016-11-21 11:10:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 442 wifi is on
# teardown
ok 443 error should be null
ok 444 error should be null
# setup
# network changes not emitted in stopped state
ok 445 event was not emitted
2016-11-21 11:10:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:03 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
# teardown
ok 446 error should be null
ok 447 error should be null
# setup
# calls correct starts when network changes
2016-11-21 11:10:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
ok 448 specific error expected
ok 449 specific error expected
2016-11-21 11:10:03 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":true,"listening":true,"advertising":true,"networkType":"WIFI"})'
2016-11-21 11:10:03 - DEBUG thaliWifiInfrastructure: 'listening 49963'
ok 450 startListeningForAdvertisements should have been called
ok 451 startUpdateAdvertisingAndListening should have been called
# teardown
2016-11-21 11:10:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:03 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:03 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 452 error should be null
ok 453 error should be null
# setup
# We properly fire peer unavailable and then available when connection fails
2016-11-21 11:10:03 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails''
# teardown
ok 454 error should be null
ok 455 error should be null
# setup
# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
2016-11-21 11:10:03 - DEBUG SimpleThaliTape: 'test was skipped, name: 'If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen''
# teardown
ok 456 error should be null
ok 457 error should be null
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 458 peerIdentifier should be identifier
ok 459 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 460 good beacon
ok 461 good preAmble
ok 462 public keys match!
ok 463 must return null after successful call
ok 464 Once start returns the action should be in KILLED state
# teardown
2016-11-21 11:10:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test HTTP_BAD_RESPONSE locally
ok 465 Response should be HTTP_BAD_RESPONSE
ok 466 must return null after successful call
# teardown
2016-11-21 11:10:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test NETWORK_PROBLEM locally
ok 467 Response should be NETWORK_PROBLEM
ok 468 reject reason should be: Could not establish TCP connection
# teardown
2016-11-21 11:10:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the start two times
ok 469 Call start once
ok 470 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 471 must return null after successful call.
# teardown
2016-11-21 11:10:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill before calling the start
ok 472 Should be Killed
ok 473 Start after killed
# teardown
2016-11-21 11:10:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill immediately after the start
ok 474 Should be KILLED
ok 475 must return null after successful kill
# teardown
2016-11-21 11:10:03 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill while waiting a response from the server
ok 476 Should be KILLED
ok 477 must return null after successful kill
# teardown
2016-11-21 11:10:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test to exceed the max content size locally
ok 478 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 479 must return null after successful call
# teardown
2016-11-21 11:10:05 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
2016-11-21 11:10:07 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 480 Should be NETWORK_PROBLEM caused closing server socket
ok 481 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 482 Should be NETWORK_PROBLEM caused closing client socket
ok 483 Should be Could not establish TCP connection
# teardown
2016-11-21 11:10:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #generatePreambleAndBeacons bad args
ok 484 publicKeysToNotify cannot be null
ok 485 ecdh for local device cannot be null
ok 486 milliseconds cannot be less than 0
ok 487 milliseconds cannot be 0
ok 488 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 489 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 490 should be equal
ok 491 should be equal
ok 492 (unnamed assert)
ok 493 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 494 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 495 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 496 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 497 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 498 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 499 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 500 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 501 should be equal
ok 502 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 503 should be equal
ok 504 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 505 right number of calls to address book
ok 506 good preAmble
ok 507 good unencryptedKeyId
ok 508 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 509 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 510 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 511 Matching numbers
ok 512 We have an entry!
ok 513 keys match
ok 514 secrets match
ok 515 We have an entry!
ok 516 keys match
ok 517 secrets match
ok 518 We have an entry!
ok 519 keys match
ok 520 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 521 Streams have same length
ok 522 matching size
ok 523 keys match
ok 524 secrets match
# teardown
# setup
# Add two Peers.
ok 525 should be equal
ok 526 should be equal
ok 527 should be equal
ok 528 should be equal
ok 529 should be equal
# teardown
2016-11-21 11:10:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# TCP_NATIVE peer loses DNS
ok 530 should be equal
ok 531 should be equal
# teardown
2016-11-21 11:10:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Received beacons with no values for us
ok 532 entry exists
ok 533 entry is resolved
# teardown
2016-11-21 11:10:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Notification action killed with a superseded
ok 534 Action should be killed
ok 535 should be equal
# teardown
2016-11-21 11:10:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally
ok 536 Host address must match
ok 537 suggestedTCPTimeout must match
ok 538 connectionType must match
ok 539 portNumber must match
ok 540 peerIDs must match
# teardown
2016-11-21 11:10:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 541 Host address must match
ok 542 suggestedTCPTimeout must match
ok 543 connectionType must match
ok 544 portNumber must match
ok 545 peerIds must match
# teardown
2016-11-21 11:10:09 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Action fails because of a bad hostname.
2016-11-21 11:10:09 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 546 action should be resolved with NETWORK_PROBLEM error
2016-11-21 11:10:09 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 547 action should be resolved with NETWORK_PROBLEM error
2016-11-21 11:10:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 548 action should be resolved with NETWORK_PROBLEM error
2016-11-21 11:10:10 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 549 action should be resolved with NETWORK_PROBLEM error
ok 550 correct number of requests
ok 551 correct number of failures
ok 552 correct final peer state
# teardown
2016-11-21 11:10:10 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# hostaddress is removed when the action is running. 
2016-11-21 11:10:12 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 553 should be equal
# teardown
2016-11-21 11:10:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Client to server request locally
ok 554 secrets are equal
ok 555 Public key matches with the server key
ok 556 Host address must match
ok 557 suggestedTCPTimeout must match
ok 558 connectionType must match
ok 559 portNumber must match
# teardown
2016-11-21 11:10:12 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache clean and expiration
ok 560 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 561 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 562 All entries should be expired after 1 second
# teardown
2016-11-21 11:10:13 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 563 All keys need to be available in the cache
ok 564 All entries should be expired after 1 second
# teardown
2016-11-21 11:10:14 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache multiple entries
ok 565 Size of the cache should be 2
ok 566 Cache doesn't contain dictionary1
ok 567 Size of the cache should be 1
ok 568 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start and stop ThaliNotificationServer
ok 569 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 570 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 571 StartUpdateAdvertisingAndListening should not be called
ok 572 ThaliMobile.StopAdvertisingAndListening should be called once
ok 573 no error
ok 574 should be 204
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass a string to ThaliNotificationServer.start
ok 575 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 576 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons
ok 577 no error
ok 578 should be 200
ok 579 should be equal
ok 580 should be equal
ok 581 (unnamed assert)
ok 582 no error
ok 583 should be 204
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 584 error should be null
ok 585 should be 204
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 586 should be 404
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #testThaliPeerAction - test getters
ok 587 getPeerIdentifier
ok 588 getConnectionType
ok 589 getActionType
ok 590 getActionState
ok 591 getPskIdentity
ok 592 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 593 initial state
ok 594 after start
2016-11-21 11:10:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 595 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 596 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
2016-11-21 11:10:17 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 597 clean kill
ok 598 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 599 should not be equal
# teardown
# setup
# #testThaliPeerAction - check that forever agent can be destroyed
ok 600 forever agent should have it's own destroy method
ok 601 agent's destroy should be called
ok 602 agent's destroy should not be called again
ok 603 agent is destroyed
# teardown
# setup
# Test PeerConnectionInformation basics
ok 604 connection type works
ok 605 getHostAddress works
ok 606 getPortNumber works
ok 607 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 608 Entry counter must be 1
ok 609 Size must be 1
ok 610 Entry counter must be 2
ok 611 Size must be 2
ok 612 Entry2 should not be found
ok 613 Size must be 1
ok 614 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 615 Size must be100
ok 616 Entries between 20 and MAXSIZE + 20 should exist
ok 617 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 618 Entries between 6 and MAXSIZE + 4 should exist
ok 619 Size should be MAXSIZE
ok 620 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 621 WAITING state entry should not be removed
ok 622 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 623 Size should be MAXSIZE
ok 624 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 625 Kill should be called once
ok 626 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 627 is an agent
ok 628 enqueue is fine
ok 629 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 630 is an agent
ok 631 first enqueue is fine
ok 632 is an agent
ok 633 second enqueue is fine
ok 634 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 635 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 636 is an agent
ok 637 good enqueue
ok 638 Identity should match
2016-11-21 11:10:17 - DEBUG testUtils: 'Got response data'
2016-11-21 11:10:17 - DEBUG testUtils: 'Got end'
ok 639 Got expected response
ok 640 Got psk call back
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #ThaliPeerPoolDefault - stop
ok 641 is an agent
ok 642 enqueue worked
ok 643 is an agent
ok 644 enqueue 2 worked
ok 645 enqueue is not available when stopped
ok 646 start action is killed
ok 647 killed action is still killed
ok 648 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 649 good start
ok 650 good enqueue
ok 651 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 652 null arg
ok 653 wrong arg type
ok 654 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 655 good enqueue
ok 656 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 657 good enqueue
ok 658 2nd good enqueue
ok 659 we are in the pool
ok 660 We are out of the pool
ok 661 Action was killed
ok 662 The original kill was called too
ok 663 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 664 good enqueue
ok 665 first kill
ok 666 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 667 1st good enqueue
ok 668 2nd good enqueue
ok 669 1st action is in the pool
ok 670 2nd action is in the pool
ok 671 1st action is out of the pool
ok 672 2st action is out of the pool
ok 673 pool is empty
# teardown
# setup
# We reject unrecognized connection type
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 674 Got right error
ok 675 Start should not be called
ok 676 Kill should have been called at least once
# teardown
# setup
# We reject unrecognized action type
2016-11-21 11:10:17 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We reject unrecognized action type''
# teardown
# setup
# One action on bluetooth
2016-11-21 11:10:17 - DEBUG SimpleThaliTape: 'test was skipped, name: 'One action on bluetooth''
# teardown
# setup
# Two notification actions
2016-11-21 11:10:17 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Two notification actions''
# teardown
# setup
# replicateThroughProblems
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 677 should have gotten null
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 678 Should have stopped nicely
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 679 Still looking for null
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 680 Yup, another null
ok 681 We cloned!
# teardown
# setup
# Replication goes first
2016-11-21 11:10:17 - DEBUG SimpleThaliTape: 'test was skipped, name: 'Replication goes first''
# teardown
# setup
# wifi allows many parallel non-replication actions
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 606, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 682 is an agent
ok 683 First null
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 607, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 684 is an agent
ok 685 Second null
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 607, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 606, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
# setup
# wifi allows no more than 2 simultaneous replication actions for same peerID
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 608, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 686 is an agent
ok 687 First null
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 609, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 688 is an agent
ok 689 second null
ok 690 third null
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 608, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 609, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-21 11:10:17 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 691 equal keys
ok 692 not equal connection type
ok 693 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-11-21 11:10:17 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 694 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 695 second cleared dictionary
2016-11-21 11:10:17 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 696 First start and on called correctly
ok 697 First stop and removeListener called correctly
ok 698 first action kill called
ok 699 second action kill called
ok 700 first cleared dictionary
ok 701 first cleared pool
ok 702 second cleared dictionary
ok 703 second cleared pool
# teardown
# setup
# Simple peer event
2016-11-21 11:10:17 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 704 listener has been set
ok 705 peer dictionary has expected number of entries
ok 706 Dictionary and pool have same action
ok 707 ads match
ok 708 PouchDB matches
ok 709 DB Names match
ok 710 public keys match
ok 711 peer dictionary has expected number of entries
ok 712 Dictionary and pool have same action
ok 713 ads match
ok 714 PouchDB matches
ok 715 DB Names match
ok 716 public keys match
2016-11-21 11:10:17 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 717 start called once
ok 718 One entry left
ok 719 Dictionary and pool have same action
ok 720 Start never called
ok 721 Kill called once
ok 722 no entries left
ok 723 Third action is dead
ok 724 peer dictionary has expected number of entries
ok 725 Dictionary and pool have same action
ok 726 ads match
ok 727 PouchDB matches
ok 728 DB Names match
ok 729 public keys match
# teardown
# setup
# Server is not there
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:17 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
2016-11-21 11:10:17 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
ok 730 right error
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server accepts & closes connection
2016-11-21 11:10:17 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
2016-11-21 11:10:17 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
ok 731 right error
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 500
2016-11-21 11:10:17 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2016-11-21 11:10:17 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 732 Got error as expected
# teardown
2016-11-21 11:10:17 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 401
2016-11-21 11:10:18 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
2016-11-21 11:10:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 733 Got error as expected
# teardown
2016-11-21 11:10:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 403
2016-11-21 11:10:18 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
2016-11-21 11:10:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 734 Got error as expected
# teardown
2016-11-21 11:10:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure docs replicate
2016-11-21 11:10:18 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-21 11:10:18 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-21 11:10:18 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 735 should be equal
ok 736 All tests passed!
# teardown
2016-11-21 11:10:18 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do nothing and make sure we time out
2016-11-21 11:10:18 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-21 11:10:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-21 11:10:20 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 737 action should be killed
ok 738 Error should be timed out
ok 739 No doc found
# teardown
2016-11-21 11:10:20 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do something and make sure we time out
2016-11-21 11:10:20 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-21 11:10:20 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 740 should be equal
2016-11-21 11:10:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-21 11:10:22 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 741 action should be killed
ok 742 Error should be timed out
# teardown
2016-11-21 11:10:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start replicating and then catch error when server goes
ok 743 socket hung up
# teardown
2016-11-21 11:10:22 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure clone works
ok 744 same getPeerAdvertisesDataForUs
ok 745 Same pouchdB
ok 746 same dbName
ok 747 Same public key
# teardown
# setup
# compareBufferArrays
ok 748 should throw
ok 749 should throw
ok 750 (unnamed assert)
ok 751 (unnamed assert)
ok 752 (unnamed assert)
ok 753 (unnamed assert)
ok 754 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 755 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 756 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 757 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 758 should be equal
ok 759 should be equal
ok 760 should throw
# teardown
# setup
# Test TransientState
ok 761 should throw
ok 762 should throw
ok 763 should be equal
ok 764 should be equal
ok 765 should be equal
ok 766 should be equal
ok 767 (unnamed assert)
ok 768 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 769 verify failed
ok 770 constructor called once
ok 771 constructor called with right args
ok 772 match start arg
ok 773 start called once
ok 774 stop called once
ok 775 stop after start
# teardown
# setup
# One peer and empty DB
ok 776 verify failed
ok 777 constructor called once
ok 778 constructor called with right args
ok 779 match start arg
ok 780 start called once
ok 781 stop called once
ok 782 stop after start
2016-11-21 11:10:22 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set behind current seq
ok 783 verify failed
ok 784 constructor called once
ok 785 constructor called with right args
ok 786 match start arg
ok 787 start called once
ok 788 stop called once
ok 789 stop after start
2016-11-21 11:10:22 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set equal to current seq
ok 790 verify failed
ok 791 constructor called once
ok 792 constructor called with right args
ok 793 match start arg
ok 794 start called once
ok 795 stop called once
ok 796 stop after start
2016-11-21 11:10:22 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 797 verify failed
ok 798 constructor called once
ok 799 constructor called with right args
ok 800 match start arg
ok 801 start called once
ok 802 stop called once
ok 803 stop after start
2016-11-21 11:10:22 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 804 verify failed
ok 805 constructor called once
ok 806 constructor called with right args
ok 807 match start arg
ok 808 start called once
ok 809 stop called once
ok 810 stop after start
2016-11-21 11:10:22 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 811 verify failed
ok 812 constructor called once
ok 813 constructor called with right args
ok 814 match start arg
ok 815 start called once
ok 816 stop called once
ok 817 stop after start
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two peers with empty DB, update the doc
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 818 verify failed
ok 819 constructor called once
ok 820 constructor called with right args
ok 821 last start before stop
ok 822 empty first start
ok 823 full second start
ok 824 only 2 timers
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 825 verify failed
ok 826 constructor called once
ok 827 constructor called with right args
ok 828 start before stop
ok 829 We got at least 3 calls to start
ok 830 at least 3
ok 831 default 1
ok 832 1 run
ok 833 default 2
ok 834 2 run
ok 835 default 3
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# start and stop and start and stop
ok 836 start out null
ok 837 back to null
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 838 still null
ok 839 verify failed
ok 840 constructor called once
ok 841 constructor called with right args
ok 842 first start before first stop
ok 843 first stop before second start
ok 844 second start before second stop
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two identical starts in a row
ok 845 verify failed
ok 846 constructor called once
ok 847 constructor called with right args
ok 848 (unnamed assert)
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two different starts in a row
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 849 verify failed
ok 850 constructor called once
ok 851 constructor called with right args
ok 852 (unnamed assert)
ok 853 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 854 verify failed
ok 855 constructor called once
ok 856 constructor called with right args
ok 857 start before stop
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# we properly enqueue requests so no then needed
2016-11-21 11:10:23 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 858 verify failed
ok 859 constructor called once
ok 860 constructor called with right args
ok 861 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 862 should be equal
ok 863 should be equal
# teardown
# setup
# can create servers manager
ok 864 serversManager must not be null
ok 865 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 866 We need to call start first
# teardown
# setup
# can start/stop servers manager
2016-11-21 11:10:23 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:23 - DEBUG createNativeListener: 'listening 50079'
ok 867 port must be in range
# teardown
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:23 - DEBUG createNativeListener: 'Native Server - close'
# setup
# starting twice resolves with listening port
2016-11-21 11:10:23 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:23 - DEBUG createNativeListener: 'listening 50080'
ok 868 second start should return same port
# teardown
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:23 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminateIncomingConnection will terminate a connection
2016-11-21 11:10:23 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:23 - DEBUG createNativeListener: 'listening 50082'
2016-11-21 11:10:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:23 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 869 we should be connected
2016-11-21 11:10:23 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 870 now we are disconnected
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:23 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminate an Outgoing connection
2016-11-21 11:10:23 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 871 Passed bogus id
2016-11-21 11:10:23 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 872 Passed good id but bogus port
2016-11-21 11:10:23 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 873 Passed right context
ok 874 Right server
ok 875 No error should be set
ok 876 Retry should be false
ok 877 We called close server
# teardown
# setup
ok 878 should be in started state
# After #startListeningForAdvertisements call wifiPeerAvailabilityChanged events should be emitted
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"46dae770-8741-4348-ae64-b4d5a831e5e5","generation":0,"hostAddress":"15ddbeac","portNumber":8080}'
ok 879 peer identifier should match
ok 880 generation should be 0
ok 881 host address should match
ok 882 port should match
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'Emitting wifiPeerAvailabilityChanged {"peerIdentifier":"46dae770-8741-4348-ae64-b4d5a831e5e5","generation":0,"portNumber":null,"hostAddress":null}'
ok 883 generation should be 0
ok 884 host address should be null
ok 885 port should should be null
# teardown
ok 886 should not be in started state
# setup
ok 887 should be in started state
# #startUpdateAdvertisingAndListening correctly updates USN
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50084'
ok 888 first invocation sets 0 generation
ok 889 second invocation doesn’t change UUID but increments generation
ok 890 third invocation doesn’t change UUID but increments generation
# teardown
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 891 should not be in started state
# setup
ok 892 should be in started state
# #startUpdateAdvertisingAndListening generates new peerIdentifier after #stopAdvertisingAndListening has been called
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50085'
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50086'
ok 893 new UUID after advertising is stopped
# teardown
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 894 should not be in started state
# setup
ok 895 should be in started state
# #startUpdateAdvertisingAndListening sends correct requests
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50087'
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 896 advertise-alive fired with expected usn
ok 897 advertise-bye fired with expected usn
# teardown
ok 898 should not be in started state
# setup
ok 899 should be in started state
# messages with invalid location or USN should be ignored
2016-11-21 11:10:23 - WARN thaliWifiInfrastructure: 'Failed to parse a valid port number from location: http://foo.bar:90000'
ok 900 should not have emitted with invalid port
2016-11-21 11:10:23 - WARN thaliWifiInfrastructure: 'Invalid USN (expected "data:" prefix): foobar'
ok 901 should not have emitted with invalid USN
# teardown
ok 902 should not be in started state
# setup
ok 903 should be in started state
# Delayed own message are still ignored after advertisement has been toggled on and off several times
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50088'
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50089'
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50090'
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50091'
ok 904 all captured messages are not handled
# teardown
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 905 should not be in started state
# setup
ok 906 should be in started state
# verify that Thali-specific messages are filtered correctly
ok 907 messages with irrelevant NT should be ignored
ok 908 relevant messages should not be ignored
# teardown
ok 909 should not be in started state
# setup
ok 910 should be in started state
# #startListeningForAdvertisements should fail if start not called
ok 911 specific error should be returned
# teardown
ok 912 should not be in started state
# setup
ok 913 should be in started state
# #startUpdateAdvertisingAndListening should fail if start not called
ok 914 specific error should be returned
# teardown
ok 915 should not be in started state
# setup
ok 916 should be in started state
# #start should fail if called twice in a row
ok 917 specific error should be received
# teardown
ok 918 should not be in started state
# setup
ok 919 should be in started state
# should not be started after stop is called
ok 920 should not be started
ok 921 should not be listening
ok 922 should not target listening
ok 923 should not be advertising
ok 924 should not target advertising
# teardown
ok 925 should not be in started state
# setup
ok 926 should be in started state
# #startUpdateAdvertisingAndListening should fail invalid router has been passed
2016-11-21 11:10:23 - ERROR thaliWifiInfrastructure: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 927 specific error should be received
# teardown
ok 928 should not be in started state
# setup
ok 929 should be in started state
# #startUpdateAdvertisingAndListening should fail if router server starting fails
2016-11-21 11:10:23 - ERROR thaliWifiInfrastructure: 'Router server emitted an error: Error: listen EADDRINUSE'
ok 930 specific error expected
# teardown
ok 931 should not be in started state
# setup
ok 932 should be in started state
# #startUpdateAdvertisingAndListening should start hosting given router object
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50093'
ok 933 server should respond with code 200
# teardown
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 934 should not be in started state
# setup
ok 935 should be in started state
# #startUpdateAdvertisingAndListening bad psk should be rejected object
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50095'
ok 936 Connection should be rejected
# teardown
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 937 should not be in started state
# setup
ok 938 should be in started state
# #stop can be called multiple times in a row
ok 939 should be in stopped state
ok 940 should still be in stopped state
# teardown
ok 941 should not be in started state
# setup
ok 942 should be in started state
# #startListeningForAdvertisements can be called multiple times in a row
ok 943 should be in listening state
ok 944 should still be in listening state
# teardown
ok 945 should not be in started state
# setup
ok 946 should be in started state
# #stopListeningForAdvertisements can be called multiple times in a row
ok 947 should not be in listening state
ok 948 should still not be in listening state
# teardown
ok 949 should not be in started state
# setup
ok 950 should be in started state
# #stopAdvertisingAndListening can be called multiple times in a row
ok 951 should not be in advertising state
ok 952 should still not be in advertising state
# teardown
ok 953 should not be in started state
# setup
ok 954 should be in started state
# functions are run from a queue in the right order
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50097'
2016-11-21 11:10:23 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 955 call order must match
# teardown
ok 956 should not be in started state
# setup
ok 957 should be in started state
# does not get peer changes from self
2016-11-21 11:10:23 - DEBUG thaliWifiInfrastructure: 'listening 50098'
# teardown
2016-11-21 11:10:25 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 958 should not be in started state
# setup
# Correctly parses/stringifies USN
ok 959 correctly parses USN string
ok 960 throws if usn has invalid prefix
ok 961 throws if usn has invalid identifier format
ok 962 throws if usn has invalid generation
ok 963 correctly stringifies peer
# teardown
2016-11-21 11:10:25 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'android''
2016-11-21 11:10:25 - DEBUG SimpleThaliTape: 'skipped tests: '["native available - peer with greater generation is cached (MPCF)","native available - peer with same or older generation is ignored (MPCF)","networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)","multiconnect failure - new peer is ignored (MPCF)","multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)","newAddressPort field (MPCF)","We properly fire peer unavailable and then available when connection fails","If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen","We reject unrecognized action type","One action on bluetooth","Two notification actions","Replication goes first"]''
2016-11-21 11:10:25 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2016-11-21 11:10:25 - INFO runTests: 'Finished'

1..963
# tests 963
# pass  963

# ok

2016-11-21 11:10:27 - INFO runTests: 'Starting tests. Network type: NATIVE. Platform: android'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-21 11:10:27 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-21 11:10:28 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2016-11-21 11:10:28 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:28 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:28 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:28 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:28 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:28 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50100'
ok 1 Should throw
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50102'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 2 initial connection state should be CONNECTED
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 3 final connection state should be DISCONNECTED
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50105'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50109'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50114'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50118'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 14 we should not have gotten an error
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50122'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50126'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 20 we should not have gotten an error
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 21 Buffers are identical
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50130'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50182'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 31 we should not have gotten an error
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 32 Buffers are identical
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50186'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 38 we should not have gotten an error
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 39 Buffers are identical
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50191'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50194'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener (pleaseConnect === false)
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50197'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50198'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 45 port must be in range
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50201'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50202'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peerId'
2016-11-21 11:10:28 - WARN createPeerListener: 'callNative for peerId failed with Unknown Peer'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Unknown Peer" and peerIdentifier "peerId"'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Will try to recreate server for peerId'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peerId'
ok 46 should get error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50203'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peerId and portNumber 50203'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50206'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50207'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 port values should be the same
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50210'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50211'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 48 Data should be of same length and content
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50216'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50216'
ok 49 same peer ID
ok 50 different ports
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50219'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50220'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 51 Data should be of same length and content
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50225'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50225'
ok 52 same peer ID
ok 53 different ports
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# peerListener - forwardConnection, pleaseConnect === true - no native server
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50228'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50229'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 56 reason should be as expected
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50231'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50231'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50234'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50235'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 59 peerPort should not be nativePort
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - finish'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50238'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50238'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50241'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50242'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 64 peerPort != nativePort
ok 65 Should get spontaneous connection
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50246'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50247'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 68 peerPort != nativePort
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
ok 69 Should not get unexpected connection
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
# setup
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50252'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50253'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# createPeerListener is idempotent
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50259'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50260'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 74 Second call to existing peerListener returns existing port
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50263'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50264'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - WARN createPeerListener: 'callNative for peer1 failed with a nasty error'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: a nasty error" and peerIdentifier "peer1"'
ok 77 got our failed connection
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
ok 78 failed connection should reject with error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50265'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50265'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50268'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50269'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 81 Should get spontaneous connection
ok 82 promise should resolve
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - reverseConnection, pleaseConnect === true
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50273'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50274'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - WARN createPeerListener: 'was expecting a forward connection to be made'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 85 reason should be as expected
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50275'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50275'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50278'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50279'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 88 peerPort should not be nativePort
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'no mux found'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Incoming connection died" and peerIdentifier "peer1"'
ok 89 should not get event until connection is made
ok 90 reason should be as expected
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50281'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50281'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50284'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50285'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'looking up mux for client port:  50287'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'looking up mux for client port:  50287'
ok 93 sent and received should be the same
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50290'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50291'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'looking up mux for client port:  50293'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'looking up mux for client port:  50293'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 96 should get routerPortConnectionFailed
2016-11-21 11:10:28 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# createPeerListener - ask for new peer when we are at maximum and make sure we remove the right existing listener
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50297'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - ask for a new peer when we are not at maximum peers and make sure we do not remove any existing listeners
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50300'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect = false - test timeout
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50303'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect = true - test timeout
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50306'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - forward connection - wrong serverPort
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50309'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - forward connection - wrong clientPort
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50312'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - please connect = false, multiple connections out
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50315'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - please connect = false, multiple bi-directional connections
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50318'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - multiple parallel calls
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50321'
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - we shouldn't create a dead pipe
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Creating Native Server'
ok 97 Can call startUpdateAdvertisingAndListening without error
ok 98 Can call startListeningForAdvertisements without error
2016-11-21 11:10:28 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'listening 50324'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50325'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 99 peerPort != nativePort
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 100 Should not get unexpected connection
2016-11-21 11:10:28 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID peer1 with port 50325'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
ok 101 passed
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server is not there
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:28 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:10:28 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNREFUSED","errno":"ECONNREFUSED","syscall":"connect","status":500}'
ok 102 Got right error
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server accepts & closes connection
2016-11-21 11:10:28 - DEBUG localSeqManager: 'Got an error trying to update seq {"code":"ECONNRESET","status":500}'
ok 103 Got socket hang up
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - server always returns 500
2016-11-21 11:10:28 - DEBUG localSeqManager: 'Got an error trying to update seq []'
ok 104 Got 500 as expected
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - create new seq doc
ok 105 should be equal
ok 106 revs are equal
# teardown
2016-11-21 11:10:28 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - doc exists, need to get rev and update
ok 107 should be equal
ok 108 revs are equal
# teardown
2016-11-21 11:10:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - update seq three times
ok 109 should be equal
ok 110 revs are equal
ok 111 should be equal
ok 112 revs are equal
ok 113 should be equal
ok 114 revs are equal
# teardown
2016-11-21 11:10:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - rev got changed under us
2016-11-21 11:10:29 - DEBUG localSeqManager: 'Got an error trying to update seq {"error":"conflict","reason":"Document update conflict","name":"conflict","status":409,"message":"Document update conflict","ok":true}'
ok 115 Our rev is old so we should fail
# teardown
2016-11-21 11:10:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - fail if stop is called
ok 116 confirm stop caused failure
# teardown
2016-11-21 11:10:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #_doImmediateSeqUpdate - stop after get but before put fails right
2016-11-21 11:10:29 - DEBUG localSeqManager: 'Got an error trying to update seq {"onPut":true}'
ok 117 stop caused us to fail
ok 118 We specifically failed on a stop before put
# teardown
2016-11-21 11:10:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - fail if stop is called
ok 119 failed due to stop
ok 120 failed due to stop
# teardown
2016-11-21 11:10:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - set seq for first time
ok 121 should be equal
# teardown
2016-11-21 11:10:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - Fail on bad seq value
2016-11-21 11:10:29 - DEBUG localSeqManager: 'Got a bad seq, submitted seq 9, _nextSeqValueToSend: 10'
ok 122 Expected bad seq error
# teardown
2016-11-21 11:10:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we cancel timer properly on an immediate?
ok 123 Different promises
ok 124 Timer was cancelled
ok 125 should be equal
# teardown
2016-11-21 11:10:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - do we wait for blocked update
ok 126 One go and one blocked
ok 127 All blocked
ok 128 Still blocked
ok 129 should be equal
# teardown
2016-11-21 11:10:29 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we wait long enough
ok 130 We waited long enough
ok 131 should be equal
# teardown
2016-11-21 11:10:30 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #update - test that we pick up new sequences while we wait
ok 132 Should have gotten same timer promise
ok 133 Still same timer promise
ok 134 We waited long enough
ok 135 should be equal
# teardown
2016-11-21 11:10:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# closeAll can close even when connections open
2016-11-21 11:10:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 136 not possible to connect to the server anymore
# teardown
# setup
# closeAll with promise
2016-11-21 11:10:31 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 137 not possible to connect to the server anymore
# teardown
# setup
# closeAll properly throws when closing a non open server with eatNotRunning set to false
2016-11-21 11:10:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 138 Got the right error
# teardown
# setup
# closeAll works even with a server that is not listening yet witheatNotRunning set to true
2016-11-21 11:10:32 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# Call of onCheckpointReached handler on a single db change
# teardown
# setup
# Call of multiple onCheckpointReached handlers on a single db change
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are in the checkpoints plugin delay interval
ok 139 the checkpointReached handler should be called once. Called 1 time(s)
# teardown
# setup
# Call of onCheckpointReached handler on multiple db changes that are out of the checkpoints plugin delay interval
# teardown
# setup
# test defaultDirectory
ok 140 should be equal
ok 141 should be equal
ok 142 should be equal
# teardown
# setup
# test defaultAdapter
ok 143 should be equal
ok 144 should be equal
ok 145 should be equal
ok 146 should be equal
ok 147 should be equal
ok 148 should be equal
ok 149 should be equal
ok 150 should be equal
# teardown
# setup
# enqueue and run in order
ok 151 firstPromise setTimeout
ok 152 firstPromise result
ok 153 firstPromise testValue
ok 154 secondPromise setTimeout
ok 155 secondPromise result
ok 156 secondPromise testValue
ok 157 thirdPromise in promise
ok 158 thirdPromise result
ok 159 thirdPromise testValue
# teardown
# setup
# enqueueAtTop and run backwards
ok 160 thirdPromise - first to run
ok 161 thirdPromise - in resolve
ok 162 secondPromise - second to run
ok 163 secondPromise - in catch
ok 164 firstPromise - third to run
ok 165 firstPromise - in then
ok 166 testing promises
# teardown
# setup
# mix enqueue and enqueueAtTop
ok 167 fourth
ok 168 fourth
ok 169 second
ok 170 secondPromise - in then
ok 171 first
ok 172 firstPromise - in catch
ok 173 third
ok 174 thirdPromise - in then
ok 175 testingPromises
# teardown
# setup
# queues handled independently
ok 176 all short operations completed before the long resolves
# teardown
# setup
# basic
ok 177 sane
# teardown
# setup
# another
ok 178 sane
# teardown
# setup
# test thali manager spies
2016-11-21 11:10:35 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-21 11:10:35 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-21 11:10:35 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 179 expressPouchDB was called once
ok 180 expressPouchDB was called with 2 arguments
ok 181 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 182 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 183 PouchDB was called once
ok 184 PouchDB was called with 1 arguments
ok 185 PouchDB was called with 'dbName' as 1-st argument
ok 186 ThaliSendNotificationBasedOnReplication was called once
ok 187 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 188 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 189 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 190 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 191 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 192 ThaliPullReplicationFromNotification was called once
ok 193 ThaliPullReplicationFromNotification was called with 4 arguments
ok 194 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 195 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 196 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 197 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 198 Salti was called once
ok 199 Salti was called with 4 arguments
ok 200 Salti was called with 'dbName' as 1-st argument
ok 201 Salti was called with 'acl' as 2-st argument
ok 202 Salti was called with 'thaliIdCallback' as 3-st argument
ok 203 Salti was called with 'options' as 4-st argument
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-21 11:10:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50413'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50414'
2016-11-21 11:10:35 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-21 11:10:35 - DEBUG thaliWifiInfrastructure: 'listening 50416'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 204 ThaliMobile.start was called once
ok 205 ThaliMobile.start was called with 3 arguments
ok 206 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 207 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 208 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 209 ThaliMobile.startListeningForAdvertisements was called once
ok 210 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 211 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 212 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 213 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 214 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 215 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 216 ThaliPullReplicationFromNotification.prototype.start was called once
ok 217 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 218 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 219 ThaliMobile.stop was called once
ok 220 ThaliMobile.stop was called with 0 arguments
ok 221 ThaliMobile.stopListeningForAdvertisements was called once
ok 222 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 223 ThaliMobile.stopAdvertisingAndListening was called once
ok 224 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 225 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 226 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 227 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 228 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
# teardown
# setup
# test thali manager multiple starts and stops
2016-11-21 11:10:35 - DEBUG thaliManager: 'creating ThaliSendNotificationBasedOnReplication instance'
2016-11-21 11:10:35 - DEBUG thaliManager: 'creating ThaliPullReplicationFromNotification instance'
2016-11-21 11:10:35 - DEBUG thaliManager: 'creating express pouchdb instance'
ok 229 expressPouchDB was called once
ok 230 expressPouchDB was called with 2 arguments
ok 231 expressPouchDB was called with 'PouchDB' as 1-st argument
ok 232 expressPouchDB was called with 'expressPouchDB options' as 2-st argument
ok 233 PouchDB was called once
ok 234 PouchDB was called with 1 arguments
ok 235 PouchDB was called with 'dbName' as 1-st argument
ok 236 ThaliSendNotificationBasedOnReplication was called once
ok 237 ThaliSendNotificationBasedOnReplication was called with 4 arguments
ok 238 ThaliSendNotificationBasedOnReplication was called with 'express.Router instance' as 1-st argument
ok 239 ThaliSendNotificationBasedOnReplication was called with 'ecdhForLocalDevice' as 2-st argument
ok 240 ThaliSendNotificationBasedOnReplication was called with 'thaliConfig.BEACON_MILLISECONDS_TO_EXPIRE' as 3-st argument
ok 241 ThaliSendNotificationBasedOnReplication was called with 'PouchDB instance' as 4-st argument
ok 242 ThaliPullReplicationFromNotification was called once
ok 243 ThaliPullReplicationFromNotification was called with 4 arguments
ok 244 ThaliPullReplicationFromNotification was called with 'PouchDB' as 1-st argument
ok 245 ThaliPullReplicationFromNotification was called with 'dbName' as 2-st argument
ok 246 ThaliPullReplicationFromNotification was called with 'ThaliPeerPoolInterface instance' as 3-st argument
ok 247 ThaliPullReplicationFromNotification was called with 'ecdhForLocalDevice' as 4-st argument
ok 248 Salti was called once
ok 249 Salti was called with 4 arguments
ok 250 Salti was called with 'dbName' as 1-st argument
ok 251 Salti was called with 'acl' as 2-st argument
ok 252 Salti was called with 'thaliIdCallback' as 3-st argument
ok 253 Salti was called with 'options' as 4-st argument
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-21 11:10:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50417'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50418'
2016-11-21 11:10:35 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-21 11:10:35 - DEBUG thaliWifiInfrastructure: 'listening 50420'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 254 ThaliMobile.start was called once
ok 255 ThaliMobile.start was called with 3 arguments
ok 256 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 257 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 258 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 259 ThaliMobile.startListeningForAdvertisements was called once
ok 260 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 261 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 262 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 263 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 264 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 265 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 266 ThaliPullReplicationFromNotification.prototype.start was called once
ok 267 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 268 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 269 ThaliMobile.stop was called once
ok 270 ThaliMobile.stop was called with 0 arguments
ok 271 ThaliMobile.stopListeningForAdvertisements was called once
ok 272 ThaliMobile.stopListeningForAdvertisements was called with 0 arguments
ok 273 ThaliMobile.stopAdvertisingAndListening was called once
ok 274 ThaliMobile.stopAdvertisingAndListening was called with 0 arguments
ok 275 ThaliSendNotificationBasedOnReplication.prototype.stop was called once
ok 276 ThaliSendNotificationBasedOnReplication.prototype.stop was called with 0 arguments
ok 277 ThaliPullReplicationFromNotification.prototype.stop was called once
ok 278 ThaliPullReplicationFromNotification.prototype.stop was called with 0 arguments
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-21 11:10:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50421'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50422'
2016-11-21 11:10:35 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-21 11:10:35 - DEBUG thaliWifiInfrastructure: 'listening 50424'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-21 11:10:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50425'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50426'
2016-11-21 11:10:35 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-21 11:10:35 - DEBUG thaliWifiInfrastructure: 'listening 50428'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting thaliPullReplicationFromNotification'
2016-11-21 11:10:35 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting ThaliMobile'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50429'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50430'
2016-11-21 11:10:35 - DEBUG thaliManager: 'start listening for advertisements'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'start update advertising and listening'
2016-11-21 11:10:35 - DEBUG thaliWifiInfrastructure: 'listening 50432'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'starting thaliSendNotificationBasedOnReplication'
ok 279 ThaliMobile.start was called once
ok 280 ThaliMobile.start was called with 3 arguments
ok 281 ThaliMobile.start was called with 'express.Router instance' as 1-st argument
ok 282 ThaliMobile.start was called with 'getPskIdToSecret' as 2-st argument
ok 283 ThaliMobile.start was called with 'networkType' as 3-st argument
ok 284 ThaliMobile.startListeningForAdvertisements was called once
ok 285 ThaliMobile.startListeningForAdvertisements was called with 0 arguments
ok 286 ThaliMobile.startUpdateAdvertisingAndListening was called once
ok 287 ThaliMobile.startUpdateAdvertisingAndListening was called with 0 arguments
ok 288 ThaliSendNotificationBasedOnReplication.prototype.start was called once
ok 289 ThaliSendNotificationBasedOnReplication.prototype.start was called with 1 arguments
ok 290 ThaliSendNotificationBasedOnReplication.prototype.start was called with 'remoteKeys' as 1-st argument
ok 291 ThaliPullReplicationFromNotification.prototype.start was called once
ok 292 ThaliPullReplicationFromNotification.prototype.start was called with 1 arguments
ok 293 ThaliPullReplicationFromNotification.prototype.start was called with 'remoteKeys' as 1-st argument
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliPullReplicationFromNotification'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliSendNotificationBasedOnReplication'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping thaliPeerPoolInterface'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping advertising and listening'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping listening for advertisements'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliManager: 'stopping ThaliMobile'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 294 specific error should be returned
# teardown
ok 295 error should be null
ok 296 error should be null
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 297 specific error should be returned
# teardown
ok 298 error should be null
ok 299 error should be null
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50433'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50434'
ok 300 error should be null
ok 301 error should be null
ok 302 error should be null
ok 303 error should be null
# teardown
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 304 error should be null
ok 305 error should be null
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50435'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50436'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
ok 306 error should be null
ok 307 error should be null
ok 308 error should be null
ok 309 error should be null
# teardown
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 310 error should be null
ok 311 error should be null
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50437'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50438'
2016-11-21 11:10:35 - DEBUG thaliWifiInfrastructure: 'listening 50440'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
ok 312 error should be null
ok 313 error should be null
ok 314 error should be null
ok 315 error should be null
# teardown
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 316 error should be null
ok 317 error should be null
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50441'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50442'
ok 318 error should be null
ok 319 error should be null
ok 320 error should be null
ok 321 error should be null
# teardown
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 322 error should be null
ok 323 error should be null
# setup
# #start - Causing native or wifi to fail will cause a promise reject 
2016-11-21 11:10:35 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a Null'
ok 324 This should not cause wifi to fail
ok 325 native router should be bad
# teardown
ok 326 error should be null
ok 327 error should be null
# setup
# #start should fail if called twice in a row
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50443'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50444'
ok 328 first call should succeed
ok 329 first call should succeed
ok 330 specific error should be returned
# teardown
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 331 error should be null
ok 332 error should be null
# setup
# #stop should clear watchers and change peers
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50445'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50446'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"urn:uuid:054d3e70-468b-434c-b765-184d3c8db1f8","peerAvailable":true,"pleaseConnect":false}'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'creating new server for urn:uuid:054d3e70-468b-434c-b765-184d3c8db1f8'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for urn:uuid:054d3e70-468b-434c-b765-184d3c8db1f8 listening on 50447'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerAvailabilityChanged - Emitting {"peerIdentifier":"urn:uuid:054d3e70-468b-434c-b765-184d3c8db1f8","peerAvailable":true,"portNumber":50447}'
ok 333 Watchers have one entry for our connection type
ok 334 Peer availabilities has one entry for our connection type
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"urn:uuid:054d3e70-468b-434c-b765-184d3c8db1f8","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for urn:uuid:054d3e70-468b-434c-b765-184d3c8db1f8'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 335 No watchers
ok 336 No peers
ok 337 No watchers
ok 338 No peers
ok 339 No watchers
ok 340 No peers
# teardown
ok 341 error should be null
ok 342 error should be null
# setup
# does not emit duplicate discoveryAdvertisingStateUpdate
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'does not emit duplicate discoveryAdvertisingStateUpdate''
# teardown
ok 343 error should be null
ok 344 error should be null
# setup
# does not send duplicate availability changes
ok 345 should be called once
ok 346 should not have been called more than once
# teardown
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"42ec1c7d-e9ac-466b-942f-cc6f9aa71821","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 347 error should be null
ok 348 error should be null
# setup
# can get the network status
ok 349 network status should have certain non-empty properties
# teardown
ok 350 error should be null
ok 351 error should be null
# setup
# wifi peer is marked unavailable if announcements stop
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'wifi peer is marked unavailable if announcements stop''
# teardown
ok 352 error should be null
ok 353 error should be null
# setup
# native peer should be removed if no availability updates were received during availability timeout
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50448'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50449'
ok 354 peer is available
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"c4dfa18c-96c0-4aed-a082-12567b40f455","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 355 peer is not availabel because it was too silent
# teardown
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 356 error should be null
ok 357 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (native)
ok 358 we have not added peer to the cache yet
ok 359 peer should be available
ok 360 cache contains native peer
ok 361 peer should be unavailable
ok 362 peer has been removed from cache
# teardown
ok 363 error should be null
ok 364 error should be null
# setup
# peerAvailabilityChanged - peer added/removed to/from cache (wifi)
ok 365 we have not added peer to the cache yet
ok 366 peer should be available
ok 367 cache contains wifi peer
ok 368 peer should be unavailable
ok 369 peer has been removed from cache
# teardown
ok 370 error should be null
ok 371 error should be null
# setup
# peerAvailabilityChanged - peer with the same id, conn type, host, port and generation is ignored
ok 372 first peer is available
ok 373 second peer is available
ok 374 first and second peers are different
# teardown
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"584e7eb3-cfa4-4f3a-abd8-d205b662f141","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"8ce69314-a741-42e0-ba8a-3def57d04384","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 375 error should be null
ok 376 error should be null
# setup
# native available - new peer is cached
ok 377 should not be in cache at start
ok 378 peer is available
# teardown
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"a58458db-2f61-4f2e-bc86-71e6a995ea98","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 379 error should be null
ok 380 error should be null
# setup
# native available - peer with same port and different generation is cached (BLUETOOTH)
ok 381 peer should be available
ok 382 peer should be available
ok 383 peer should be available
# teardown
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"511224ac-0fb4-45e2-881e-7d07c50e10fc","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 384 error should be null
ok 385 error should be null
# setup
# native available - peer with the same port and generation but with enough time for generation to wrap around is cached (BLUETOOTH)
ok 386 peer should be available
ok 387 peer should be available
# teardown
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"14306b35-8291-47d1-8a9e-636d4fbe1de6","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 388 error should be null
ok 389 error should be null
# setup
# native available - peer with greater generation is cached (MPCF)
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with greater generation is cached (MPCF)''
# teardown
ok 390 error should be null
ok 391 error should be null
# setup
# native available - peer with same or older generation is ignored (MPCF)
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'native available - peer with same or older generation is ignored (MPCF)''
# teardown
ok 392 error should be null
ok 393 error should be null
# setup
# native unavailable - new peer is ignored
ok 394 NOT IMPLEMENTED # SKIP
# teardown
ok 395 error should be null
ok 396 error should be null
# setup
# native unavailable - cached peer is removed
ok 397 NOT IMPLEMENTED # SKIP
# teardown
ok 398 error should be null
ok 399 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for wifi peers
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50450'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50451'
ok 400 first peer is expected to be available
ok 401 second peer is expected to be available
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"0639b231-21c9-4514-bcdb-539f7de00cdb","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 402 peer became unavailable
ok 403 it was wifi peer
# teardown
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"6ad8a0e6-f0f9-4b82-b38d-5b0446df55c7","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 404 error should be null
ok 405 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (BLUETOOTH)
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50452'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50453'
ok 406 first peer is expected to be available
ok 407 second peer is expected to be available
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"9ca32060-969c-4d22-b395-f56dd9314668","connectionType":"AndroidBluetooth","peerAvailable":false,"generation":null,"newAddressPort":null}'
ok 408 peer became unavailable
ok 409 it was a native peer
# teardown
2016-11-21 11:10:35 - DEBUG thaliMobile: 'Emitting peerAvailabilityChanged from emitPeerUnavailable {"peerIdentifier":"21584c28-ebf1-43af-9ec0-5b0726e15c68","connectionType":"tcp","peerAvailable":false,"generation":null,"newAddressPort":null}'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 410 error should be null
ok 411 error should be null
# setup
# networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)''
# teardown
ok 412 error should be null
ok 413 error should be null
# setup
# multiconnect failure - new peer is ignored (MPCF)
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - new peer is ignored (MPCF)''
# teardown
ok 414 error should be null
ok 415 error should be null
# setup
# multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)''
# teardown
ok 416 error should be null
ok 417 error should be null
# setup
# newAddressPort field (TCP_NATIVE)
ok 418 peer discovered first time does not have new address
ok 419 address has not been changed
ok 420 new port handled correctly
ok 421 new host handled correctly
ok 422 newAddressPort is null for unavailable peers
# teardown
ok 423 error should be null
ok 424 error should be null
# setup
# newAddressPort field (BLUETOOTH)
ok 425 peer discovered first time does not have new address
ok 426 address has not been changed
ok 427 new port handled correctly
ok 428 newAddressPort is null for unavailable peers
# teardown
ok 429 error should be null
ok 430 error should be null
# setup
# newAddressPort field (MPCF)
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'newAddressPort field (MPCF)''
# teardown
ok 431 error should be null
ok 432 error should be null
# setup
# newAddressPort after listenerRecreatedAfterFailure event (BLUETOOTH)
ok 433 NOT IMPLEMENTED # SKIP
# teardown
ok 434 error should be null
ok 435 error should be null
# setup
# network changes emitted correctly
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'network changes emitted correctly''
# teardown
ok 436 error should be null
ok 437 error should be null
# setup
# network changes not emitted in stopped state
ok 438 event was not emitted
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"off","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:35 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
# teardown
ok 439 error should be null
ok 440 error should be null
# setup
# calls correct starts when network changes
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'calls correct starts when network changes''
# teardown
ok 441 error should be null
ok 442 error should be null
# setup
# We properly fire peer unavailable and then available when connection fails
2016-11-21 11:10:35 - DEBUG SimpleThaliTape: 'test was skipped, name: 'We properly fire peer unavailable and then available when connection fails''
# teardown
ok 443 error should be null
ok 444 error should be null
# setup
# If a peer is not available (and hence is not in the thaliMobile cache) but we already started trying to connect make sure recreate does not happen
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listening 50454'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:35 - DEBUG createNativeListener: 'listening 50455'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'creating new server for 83dff42e-3163-4518-8561-88b85ab8e215'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 83dff42e-3163-4518-8561-88b85ab8e215 listening on 50456'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 445 We should have connected
2016-11-21 11:10:35 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - 83dff42e-3163-4518-8561-88b85ab8e215 - 0 - got a new incoming connection'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'Issuing callNative for 83dff42e-3163-4518-8561-88b85ab8e215'
2016-11-21 11:10:35 - WARN createPeerListener: 'callNative for 83dff42e-3163-4518-8561-88b85ab8e215 failed with Connection could not be established'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - 83dff42e-3163-4518-8561-88b85ab8e215 - 0 - finish'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Connection could not be established" and peerIdentifier "83dff42e-3163-4518-8561-88b85ab8e215"'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"83dff42e-3163-4518-8561-88b85ab8e215","peerAvailable":false,"portNumber":null,"recreated":true}'
ok 446 Failed on right peer
2016-11-21 11:10:35 - DEBUG createPeerListener: 'Will try to recreate server for 83dff42e-3163-4518-8561-88b85ab8e215'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 83dff42e-3163-4518-8561-88b85ab8e215'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"83dff42e-3163-4518-8561-88b85ab8e215","peerAvailable":false,"generation":null,"portNumber":null,"recreated":true}'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'creating new server for 83dff42e-3163-4518-8561-88b85ab8e215'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for 83dff42e-3163-4518-8561-88b85ab8e215 listening on 50458'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:35 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier 83dff42e-3163-4518-8561-88b85ab8e215 and portNumber 50458'
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'listenerRecreatedAfterFailureHandler - We are emitting nonTCPPeerAvailabilityChangedEvent with peerIdentifier 83dff42e-3163-4518-8561-88b85ab8e215, generation undefined, and portNumber 50458'
ok 447 Peer still matches
ok 448 We got the connection error
2016-11-21 11:10:35 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - 83dff42e-3163-4518-8561-88b85ab8e215 - 0 - close'
# teardown
2016-11-21 11:10:35 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:35 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:35 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for 83dff42e-3163-4518-8561-88b85ab8e215'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 449 error should be null
ok 450 error should be null
# setup
# Can call start/stopListeningForAdvertisements
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 451 Can call startListeningForAdvertisements without error
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 452 Can call stopListeningForAdvertisements without error
# teardown
ok 453 Should be able to call stopListeningForAdvertisements in teardown
ok 454 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startListeningForAdvertisements twice is NOT an error
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 455 Can call startListeningForAdvertisements without error
ok 456 Can call startListeningForAdvertisements twice without error
# teardown
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 457 Should be able to call stopListeningForAdvertisements in teardown
ok 458 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling stopListeningForAdvertisements without calling start is NOT an error
ok 459 Can call stopListeningForAdvertisements without error
ok 460 Can call stopListeningForAdvertisements without error
# teardown
ok 461 Should be able to call stopListeningForAdvertisements in teardown
ok 462 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call start/stopUpdateAdvertisingAndListening
2016-11-21 11:10:36 - DEBUG thaliWifiInfrastructure: 'listening 50460'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 463 Can call startUpdateAdvertisingAndListening without error
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 464 Can call stopAdvertisingAndListening without error
# teardown
ok 465 Should be able to call stopListeningForAdvertisements in teardown
ok 466 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Calling startUpdateAdvertisingAndListening twice is NOT an error
2016-11-21 11:10:36 - DEBUG thaliWifiInfrastructure: 'listening 50462'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 467 Can call startUpdateAdvertisingAndListening without error
ok 468 Can call startUpdateAdvertisingAndListening twice without error
# teardown
ok 469 Should be able to call stopListeningForAdvertisements in teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 470 Should be able to call stopAdvertisingAndListening in teardown
# setup
# Can call stopUpdateAdvertisingAndListening twice without start and it is not an error
ok 471 Can call startUpdateAdvertisingAndListening without error
ok 472 Can call stopAdvertisingAndListening without error
# teardown
ok 473 Should be able to call stopListeningForAdvertisements in teardown
ok 474 Should be able to call stopAdvertisingAndListening in teardown
# setup
# cannot call connect when start listening for advertisements is not active
ok 475 got right error
# teardown
ok 476 Should be able to call stopListeningForAdvertisements in teardown
ok 477 Should be able to call stopAdvertisingAndListening in teardown
# setup
# #startListeningForAdvertisements should fail if start not called
ok 478 specific error should be returned
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 479 must be stopped
# setup
# #startUpdateAdvertisingAndListening should fail if start not called
ok 480 specific error should be returned
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 481 must be stopped
# setup
# should be able to call #stopListeningForAdvertisements many times
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'listening 50463'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'listening 50464'
ok 482 no errors
ok 483 still no errors
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 484 must be stopped
# setup
# should be able to call #startListeningForAdvertisements many times
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'listening 50465'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'listening 50466'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 485 no errors
ok 486 still no errors
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 487 must be stopped
# setup
# should be able to call #startUpdateAdvertisingAndListening many times
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'listening 50467'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'listening 50468'
2016-11-21 11:10:36 - DEBUG thaliWifiInfrastructure: 'listening 50470'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 488 no errors
ok 489 still no errors
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 490 must be stopped
# setup
# should be able to call #stopAdvertisingAndListening many times
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'listening 50471'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'listening 50472'
ok 491 no errors
ok 492 still no errors
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 493 must be stopped
# setup
# can get the network status before starting
ok 494 network status should have certain non-empty properties
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 495 must be stopped
# setup
# error returned with bad router
2016-11-21 11:10:36 - ERROR thaliMobileNativeWrapper: 'Unable to use the given router: TypeError: Router.use() requires middleware function but got a string'
ok 496 specific error expected
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 497 must be stopped
# setup
# all services are stopped when we call stop
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'listening 50473'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'listening 50474'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliWifiInfrastructure: 'listening 50476'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
ok 498 connection to servers manager should succeed after starting
2016-11-21 11:10:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
ok 499 connection to router server should succeed after starting
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 500 is stopped after calling stop
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
ok 501 connection to servers manager should fail after stopping
ok 502 connection to router server should fail after stopping
# teardown
ok 503 must be stopped
# setup
# make sure terminateConnection is properly hooked up
ok 504 called with right arguments
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 505 must be stopped
# setup
# make sure terminateConnection is return error if we get called on iOS
2016-11-21 11:10:36 - DEBUG SimpleThaliTape: 'test was skipped, name: 'make sure terminateConnection is return error if we get called on iOS''
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 506 must be stopped
# setup
# make sure terminateListener is properly hooked up
ok 507 called with right arguments
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 508 must be stopped
# setup
# make sure terminateListener is return error if we get called on iOS
2016-11-21 11:10:36 - DEBUG SimpleThaliTape: 'test was skipped, name: 'make sure terminateListener is return error if we get called on iOS''
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 509 must be stopped
# setup
# make sure we actually call kill connections properly
ok 510 specific error expected
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 511 must be stopped
# setup
# thaliMobileNativeWrapper is stopped when routerPortConnectionFailed is received
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'listening 50481'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'listening 50482'
2016-11-21 11:10:36 - INFO thaliMobileNativeWrapper: 'routerPortConnectionFailed - {"routerPort":50481,"error":{}}'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 512 failure reason is as expected
ok 513 error description is as expected
ok 514 must be stopped
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
ok 515 must be stopped
# setup
# We fire failedNativeConnection event when we get failedConnection from thaliTcpServersManager
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'listening 50483'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'listening 50484'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Received peer availability changed event with {"peerIdentifier":"some-identifier","peerAvailable":false,"portNumber":null}'
ok 516 peerIdentifier matches
ok 517 error description matches
ok 518 connection type is tcp
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'handlePeerUnavailable - Emitting {"peerIdentifier":"some-identifier","peerAvailable":false,"generation":null,"portNumber":null}'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 519 must be stopped
# setup
# we successfully receive and replay discoveryAdvertisingStateUpdate
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'listening 50485'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'listening 50486'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 520 discoveryActive matches
ok 521 advertisingActive matches
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 522 discoveryActive matches
ok 523 advertisingActive matches
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'listening 50487'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'listening 50488'
2016-11-21 11:10:36 - DEBUG thaliWifiInfrastructure: 'listening 50490'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 524 discoveryActive matches
ok 525 advertisingActive matches
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
ok 526 discoveryActive matches
ok 527 advertisingActive matches
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'listening 50491'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'listening 50492'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:36 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:36 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:36 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 528 must be stopped
# setup
# Test BEACONS_RETRIEVED_AND_PARSED locally
ok 529 peerIdentifier should be identifier
ok 530 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 531 good beacon
ok 532 good preAmble
ok 533 public keys match!
ok 534 must return null after successful call
ok 535 Once start returns the action should be in KILLED state
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test HTTP_BAD_RESPONSE locally
ok 536 Response should be HTTP_BAD_RESPONSE
ok 537 must return null after successful call
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test NETWORK_PROBLEM locally
ok 538 Response should be NETWORK_PROBLEM
ok 539 reject reason should be: Could not establish TCP connection
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the start two times
ok 540 Call start once
ok 541 Response should be BEACONS_RETRIEVED_AND_PARSED
ok 542 must return null after successful call.
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill before calling the start
ok 543 Should be Killed
ok 544 Start after killed
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill immediately after the start
ok 545 Should be KILLED
ok 546 must return null after successful kill
# teardown
2016-11-21 11:10:36 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Call the kill while waiting a response from the server
ok 547 Should be KILLED
ok 548 must return null after successful kill
# teardown
2016-11-21 11:10:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test to exceed the max content size locally
ok 549 HTTP_BAD_RESPONSE should be response when content size is exceeded
ok 550 must return null after successful call
# teardown
2016-11-21 11:10:38 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Close the server socket while the client is waiting a response from the server. Local test.
2016-11-21 11:10:40 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
ok 551 Should be NETWORK_PROBLEM caused closing server socket
ok 552 Should be Could not establish TCP connection
# teardown
# setup
# Close the client socket while the client is waiting a response from the server. Local test.
ok 553 Should be NETWORK_PROBLEM caused closing client socket
ok 554 Should be Could not establish TCP connection
# teardown
2016-11-21 11:10:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #generatePreambleAndBeacons bad args
ok 555 publicKeysToNotify cannot be null
ok 556 ecdh for local device cannot be null
ok 557 milliseconds cannot be less than 0
ok 558 milliseconds cannot be 0
ok 559 milliseconds cannot be greater than one_day
# teardown
# setup
# #generatePreambleAndBeacons empty keys to notify
ok 560 should be equal
# teardown
# setup
# #generatePreambleAndBeacons multiple keys to notify
ok 561 should be equal
ok 562 should be equal
ok 563 (unnamed assert)
ok 564 should be equal
# teardown
# setup
# #parseBeacons invalid ECDH public key in beaconStreamWithPreAmble
ok 565 should throw
# teardown
# setup
# #parseBeacons invalid expiration in beaconStreamWithPreAmble
ok 566 Preamble expiration must be a 64 bit integer
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 567 Expiration out of range
# teardown
# setup
# #parseBeacons expiration out of range lower
ok 568 Expiration out of range
# teardown
# setup
# #parseBeacons no beacons returns null
ok 569 should be equal
# teardown
# setup
# #parseBeacons invalid size for encryptedBeaconKeyId in  beaconStreamWithPreAmble
ok 570 Malformed encrypted beacon key ID
# teardown
# setup
# #parseBeacons addressBookCallback fails decrypt
ok 571 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns no matches
ok 572 should be equal
ok 573 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns spurious match
ok 574 should be equal
ok 575 should be equal
# teardown
# setup
# #parseBeacons addressBookCallback returns public key
ok 576 right number of calls to address book
ok 577 good preAmble
ok 578 good unencryptedKeyId
ok 579 good beacon
# teardown
# setup
# validate generatePskIdentityField
ok 580 decoded buffers match
# teardown
# setup
# validate generatePskSecret
ok 581 secrets match
# teardown
# setup
# validate generatePskSecrets
ok 582 Matching numbers
ok 583 We have an entry!
ok 584 keys match
ok 585 secrets match
ok 586 We have an entry!
ok 587 keys match
ok 588 secrets match
ok 589 We have an entry!
ok 590 keys match
ok 591 secrets match
# teardown
# setup
# validate generateBeaconStreamAndSecrets
ok 592 Streams have same length
ok 593 matching size
ok 594 keys match
ok 595 secrets match
# teardown
# setup
# Add two Peers.
ok 596 should be equal
ok 597 should be equal
ok 598 should be equal
ok 599 should be equal
ok 600 should be equal
# teardown
2016-11-21 11:10:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# TCP_NATIVE peer loses DNS
ok 601 should be equal
ok 602 should be equal
# teardown
2016-11-21 11:10:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Received beacons with no values for us
ok 603 entry exists
ok 604 entry is resolved
# teardown
2016-11-21 11:10:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Notification action killed with a superseded
ok 605 Action should be killed
ok 606 should be equal
# teardown
2016-11-21 11:10:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally
ok 607 Host address must match
ok 608 suggestedTCPTimeout must match
ok 609 connectionType must match
ok 610 portNumber must match
ok 611 peerIDs must match
# teardown
2016-11-21 11:10:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Resolves an action locally using ThaliPeerPoolDefault
ok 612 Host address must match
ok 613 suggestedTCPTimeout must match
ok 614 connectionType must match
ok 615 portNumber must match
ok 616 peerIds must match
# teardown
2016-11-21 11:10:42 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Action fails because of a bad hostname.
2016-11-21 11:10:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 617 action should be resolved with NETWORK_PROBLEM error
2016-11-21 11:10:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 618 action should be resolved with NETWORK_PROBLEM error
2016-11-21 11:10:42 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 619 action should be resolved with NETWORK_PROBLEM error
2016-11-21 11:10:43 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 620 action should be resolved with NETWORK_PROBLEM error
ok 621 correct number of requests
ok 622 correct number of failures
ok 623 correct final peer state
# teardown
2016-11-21 11:10:43 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# hostaddress is removed when the action is running. 
2016-11-21 11:10:45 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 624 should be equal
# teardown
2016-11-21 11:10:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Client to server request locally
ok 625 secrets are equal
ok 626 Public key matches with the server key
ok 627 Host address must match
ok 628 suggestedTCPTimeout must match
ok 629 connectionType must match
ok 630 portNumber must match
# teardown
2016-11-21 11:10:45 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache clean and expiration
ok 631 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE
ok 632 ThaliPskMapCache should not exceed MAX_NOTIFICATIONSERVER_PSK_MAP_CACHE_SIZE-1
ok 633 All entries should be expired after 1 second
# teardown
2016-11-21 11:10:46 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache getSecret and getPublic
ok 634 All keys need to be available in the cache
ok 635 All entries should be expired after 1 second
# teardown
2016-11-21 11:10:47 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Test ThaliPskMapCache multiple entries
ok 636 Size of the cache should be 2
ok 637 Cache doesn't contain dictionary1
ok 638 Size of the cache should be 1
ok 639 Cache doesn't contain beaconStreamAndSecretDictionary2
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start and stop ThaliNotificationServer
ok 640 ThaliMobile.StartUpdateAdvertisingAndListening should be called once
ok 641 ThaliMobile.StopAdvertisingAndListeningshould be called once
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty array to ThaliNotificationServer.start
ok 642 StartUpdateAdvertisingAndListening should not be called
ok 643 ThaliMobile.StopAdvertisingAndListening should be called once
ok 644 no error
ok 645 should be 204
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass a string to ThaliNotificationServer.start
ok 646 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Pass an empty parameter to ThaliNotificationServer.start
ok 647 StartUpdateAdvertisingAndListening should not be called
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons
ok 648 no error
ok 649 should be 200
ok 650 should be equal
ok 651 should be equal
ok 652 (unnamed assert)
ok 653 no error
ok 654 should be 204
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeacons (no keys)
ok 655 error should be null
ok 656 should be 204
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make an HTTP request to /NotificationBeaconsbefore calling start
ok 657 should be 404
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #testThaliPeerAction - test getters
ok 658 getPeerIdentifier
ok 659 getConnectionType
ok 660 getActionType
ok 661 getActionState
ok 662 getPskIdentity
ok 663 getPskKey
# teardown
# setup
# #testThaliPeerAction - start and kill
ok 664 initial state
ok 665 after start
2016-11-21 11:10:50 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 666 after kill
# teardown
# setup
# #testThaliPeerAction - double start
ok 667 should be equal
# teardown
# setup
# #testThaliPeerAction - start after kill
2016-11-21 11:10:50 - DEBUG thaliPeerAction: 'we couldn't destroy http agent explicitly'
ok 668 clean kill
ok 669 should be equal
# teardown
# setup
# #testThaliPeerAction - make sure ids are unique
ok 670 should not be equal
# teardown
# setup
# #testThaliPeerAction - check that forever agent can be destroyed
ok 671 forever agent should have it's own destroy method
ok 672 agent's destroy should be called
ok 673 agent's destroy should not be called again
ok 674 agent is destroyed
# teardown
# setup
# Test PeerConnectionInformation basics
ok 675 connection type works
ok 676 getHostAddress works
ok 677 getPortNumber works
ok 678 getSuggestedTCPTimeout works
# teardown
# setup
# Test PeerDictionary basic functionality
ok 679 Entry counter must be 1
ok 680 Size must be 1
ok 681 Entry counter must be 2
ok 682 Size must be 2
ok 683 Entry2 should not be found
ok 684 Size must be 1
ok 685 Size must be 0
# teardown
# setup
# Test PeerDictionary with multiple entries.
ok 686 Size must be100
ok 687 Entries between 20 and MAXSIZE + 20 should exist
ok 688 WAITING state entry should not be removed
# teardown
# setup
# RESOLVED entries are removed before WAITING state entry.
ok 689 Entries between 6 and MAXSIZE + 4 should exist
ok 690 Size should be MAXSIZE
ok 691 Size should be MAXSIZE+6
# teardown
# setup
# WAITING entries are removed before CONTROLLED_BY_POOL state entry.
ok 692 WAITING state entry should not be removed
ok 693 Waiting entries between 6 and MAXSIZE + 4 should exist
ok 694 Size should be MAXSIZE
ok 695 entryCounter should be MAXSIZE+6
# teardown
# setup
# When CONTROLLED_BY_POOL entry is removed and kill is called.
ok 696 Kill should be called once
ok 697 Size should be 100
# teardown
# setup
# #ThaliPeerPoolDefault - single action
ok 698 is an agent
ok 699 enqueue is fine
ok 700 Everything should be off the queue
# teardown
# setup
# #ThaliPeerPoolDefault - multiple actions
ok 701 is an agent
ok 702 first enqueue is fine
ok 703 is an agent
ok 704 second enqueue is fine
ok 705 everybody, even identical peers, get their own pool, although eventually we should make identical peers have a common pool.
ok 706 Queue is empty
# teardown
# setup
# #ThaliPeerPoolDefault - PSK Pool works
ok 707 is an agent
ok 708 good enqueue
ok 709 Identity should match
2016-11-21 11:10:50 - DEBUG testUtils: 'Got response data'
2016-11-21 11:10:50 - DEBUG testUtils: 'Got end'
ok 710 Got expected response
ok 711 Got psk call back
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# #ThaliPeerPoolDefault - stop
ok 712 is an agent
ok 713 enqueue worked
ok 714 is an agent
ok 715 enqueue 2 worked
ok 716 enqueue is not available when stopped
ok 717 start action is killed
ok 718 killed action is still killed
ok 719 inQueue is empty
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that start verifies queue length
ok 720 good start
ok 721 good enqueue
ok 722 queue is not empty
# teardown
# setup
# #ThaliPeerPoolInterface - bad enqueues
ok 723 null arg
ok 724 wrong arg type
ok 725 wrong arg type
# teardown
# setup
# #ThaliPeerPoolInterface - do not allow same object type
ok 726 good enqueue
ok 727 already enqueued
# teardown
# setup
# #ThaliPeerPoolInterface - make sure we catch kill and dequeue
ok 728 good enqueue
ok 729 2nd good enqueue
ok 730 we are in the pool
ok 731 We are out of the pool
ok 732 Action was killed
ok 733 The original kill was called too
ok 734 second item is still in queue
# teardown
# setup
# #ThaliPeerPoolInterface - make sure our changes to the action leave kill as idempotent
ok 735 good enqueue
ok 736 first kill
ok 737 second NOOP kill
# teardown
# setup
# #ThaliPeerPoolInterface - make sure that stop removes all actions
ok 738 1st good enqueue
ok 739 2nd good enqueue
ok 740 1st action is in the pool
ok 741 2nd action is in the pool
ok 742 1st action is out of the pool
ok 743 2st action is out of the pool
ok 744 pool is empty
# teardown
# setup
# We reject unrecognized connection type
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 745 Got right error
ok 746 Start should not be called
ok 747 Kill should have been called at least once
# teardown
# setup
# We reject unrecognized action type
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-21 11:10:50 - ERROR thaliPeerPoolOneAtATime: 'Got unsupported action type: blah'
ok 748 Got right error
ok 749 Start should not be called
ok 750 Kill should have been called at least once
# teardown
# setup
# One action on bluetooth
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 751 Got null
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 607, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 752 is an agent
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 607, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerID'
ok 753 Got killed at least once
# teardown
# setup
# Two notification actions
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 754 Got Null
ok 755 Got another null
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 608, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
ok 756 is an agent
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 608, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId1'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 609, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 757 is an agent
ok 758 Action 1 killed at least once
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 609, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: peerId2'
ok 759 Action 1 went first
ok 760 Action 2 killed at least once
# teardown
# setup
# replicateThroughProblems
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started success'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - success'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 761 should have gotten null
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started noActivityTimeOut'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: No activity time out - noActivityTimeOut'
ok 762 Should have stopped nicely
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButNotAvailable'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButNotAvailable'
ok 763 Still looking for null
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started failureButAvailable'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned with error from startError: eeeek! - failureButAvailable'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Replication action failed badly so we are going to retry'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started clone!'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - clone!'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
ok 764 Yup, another null
ok 765 We cloned!
# teardown
# setup
# Replication goes first
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
ok 766 Null 1
ok 767 (unnamed assert)
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 610, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 768 is an agent
ok 769 Null 3
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 610, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 611, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
ok 770 is an agent
ok 771 Replication not yet called
ok 772 Notification 2 not yet called
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 611, Action Type: ReplicationAction, Connection Type: AndroidBluetooth, Peer Identifier: replicationAction'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 612, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 773 is an agent
ok 774 Notification went first
ok 775 Notification 2 not called yet
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 612, Action Type: GetRequestBeacon, Connection Type: AndroidBluetooth, Peer Identifier: notificationAction'
ok 776 Notification finished
ok 777 Replication finished
# teardown
# setup
# wifi allows many parallel non-replication actions
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 613, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
ok 778 is an agent
ok 779 First null
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 614, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
ok 780 is an agent
ok 781 Second null
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 614, Action Type: foo, Connection Type: tcp, Peer Identifier: 2'
truetruefalsetrue
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 613, Action Type: foo, Connection Type: tcp, Peer Identifier: 1'
truetruetruetrue
# teardown
# setup
# wifi allows no more than 2 simultaneous replication actions for same peerID
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Start was called'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 615, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 782 is an agent
ok 783 First null
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Action Started Action ID: 616, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
ok 784 is an agent
ok 785 second null
ok 786 third null
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 615, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'action returned successfully from start - Action ID: 616, Action Type: ReplicationAction, Connection Type: tcp, Peer Identifier: 1'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
2016-11-21 11:10:50 - DEBUG thaliPeerPoolOneAtATime: 'Got a replication response with no error!'
# teardown
# setup
# Make sure peerDictionaryKey is reasonable
ok 787 equal keys
ok 788 not equal connection type
ok 789 same connection type, different buffer
# teardown
# setup
# Make sure start works
2016-11-21 11:10:50 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 790 First start and on called correctly
# teardown
# setup
# Make sure stop works
ok 791 second cleared dictionary
2016-11-21 11:10:50 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 792 First start and on called correctly
ok 793 First stop and removeListener called correctly
ok 794 first action kill called
ok 795 second action kill called
ok 796 first cleared dictionary
ok 797 first cleared pool
ok 798 second cleared dictionary
ok 799 second cleared pool
# teardown
# setup
# Simple peer event
2016-11-21 11:10:50 - DEBUG thaliPullReplicationFromNotification: 'starting thaliPeerPoolInterface'
ok 800 listener has been set
ok 801 peer dictionary has expected number of entries
ok 802 Dictionary and pool have same action
ok 803 ads match
ok 804 PouchDB matches
ok 805 DB Names match
ok 806 public keys match
ok 807 peer dictionary has expected number of entries
ok 808 Dictionary and pool have same action
ok 809 ads match
ok 810 PouchDB matches
ok 811 DB Names match
ok 812 public keys match
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 813 start called once
ok 814 One entry left
ok 815 Dictionary and pool have same action
ok 816 Start never called
ok 817 Kill called once
ok 818 no entries left
ok 819 Third action is dead
ok 820 peer dictionary has expected number of entries
ok 821 Dictionary and pool have same action
ok 822 ads match
ok 823 PouchDB matches
ok 824 DB Names match
ok 825 public keys match
# teardown
# setup
# Server is not there
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 connect ECONNREFUSED'
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: connect ECONNREFUSED  and it caused us to complete'
ok 826 right error
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server accepts & closes connection
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 socket hang up'
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: socket hang up  and it caused us to complete'
ok 827 right error
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 500
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  500 changes rejected'
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 828 Got error as expected
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 401
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  401 changes rejected'
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 829 Got error as expected
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Server always returns 403
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'Got error on replication -  403 changes rejected'
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: changes rejected  and it caused us to complete'
ok 830 Got error as expected
# teardown
2016-11-21 11:10:50 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure docs replicate
2016-11-21 11:10:50 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-21 11:10:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-21 11:10:51 - DEBUG thaliReplicationPeerAction: 'We called _complete with  and it caused us to complete'
ok 831 should be equal
ok 832 All tests passed!
# teardown
2016-11-21 11:10:51 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do nothing and make sure we time out
2016-11-21 11:10:51 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
2016-11-21 11:10:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-21 11:10:53 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 833 action should be killed
ok 834 Error should be timed out
ok 835 No doc found
# teardown
2016-11-21 11:10:53 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Do something and make sure we time out
2016-11-21 11:10:53 - DEBUG thaliReplicationPeerAction: 'Replication resumed'
2016-11-21 11:10:53 - DEBUG thaliReplicationPeerAction: 'Got paused with -  '
ok 836 should be equal
2016-11-21 11:10:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with error: No activity time out  and it caused us to complete'
2016-11-21 11:10:55 - DEBUG thaliReplicationPeerAction: 'We called _complete with  but this is a second call and so we ignored it'
ok 837 action should be killed
ok 838 Error should be timed out
# teardown
2016-11-21 11:10:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Start replicating and then catch error when server goes
ok 839 socket hung up
# teardown
2016-11-21 11:10:55 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# Make sure clone works
ok 840 same getPeerAdvertisesDataForUs
ok 841 Same pouchdB
ok 842 same dbName
ok 843 Same public key
# teardown
# setup
# compareBufferArrays
ok 844 should throw
ok 845 should throw
ok 846 (unnamed assert)
ok 847 (unnamed assert)
ok 848 (unnamed assert)
ok 849 (unnamed assert)
ok 850 (unnamed assert)
# teardown
# setup
# Call start twice and get error
ok 851 should throw
# teardown
# setup
# Start and make sure it runs
# teardown
# setup
# Make sure getTimeWhenRun is right after start
ok 852 (unnamed assert)
# teardown
# setup
# Make sure getTimeWhenRun is -1 after function is called
ok 853 should be equal
# teardown
# setup
# Make sure getTimeWhenRun is -2 when start has not been called and null if stop is called without running
ok 854 should be equal
ok 855 should be equal
ok 856 should throw
# teardown
# setup
# Test TransientState
ok 857 should throw
ok 858 should throw
ok 859 should be equal
ok 860 should be equal
ok 861 should be equal
ok 862 should be equal
ok 863 (unnamed assert)
ok 864 (unnamed assert)
# teardown
# setup
# No peers and empty database
ok 865 verify failed
ok 866 constructor called once
ok 867 constructor called with right args
ok 868 match start arg
ok 869 start called once
ok 870 stop called once
ok 871 stop after start
# teardown
# setup
# One peer and empty DB
ok 872 verify failed
ok 873 constructor called once
ok 874 constructor called with right args
ok 875 match start arg
ok 876 start called once
ok 877 stop called once
ok 878 stop after start
2016-11-21 11:10:55 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set behind current seq
ok 879 verify failed
ok 880 constructor called once
ok 881 constructor called with right args
ok 882 match start arg
ok 883 start called once
ok 884 stop called once
ok 885 stop after start
2016-11-21 11:10:55 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set equal to current seq
ok 886 verify failed
ok 887 constructor called once
ok 888 constructor called with right args
ok 889 match start arg
ok 890 start called once
ok 891 stop called once
ok 892 stop after start
2016-11-21 11:10:55 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# One peer with _Local set ahead of current seq (and no this should not happen)
ok 893 verify failed
ok 894 constructor called once
ok 895 constructor called with right args
ok 896 match start arg
ok 897 start called once
ok 898 stop called once
ok 899 stop after start
2016-11-21 11:10:55 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# Three peers, one not in DB, one behind and one ahead
ok 900 verify failed
ok 901 constructor called once
ok 902 constructor called with right args
ok 903 match start arg
ok 904 start called once
ok 905 stop called once
ok 906 stop after start
2016-11-21 11:10:55 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# More than maximum peers, make sure we only send maximum allowed
ok 907 verify failed
ok 908 constructor called once
ok 909 constructor called with right args
ok 910 match start arg
ok 911 start called once
ok 912 stop called once
ok 913 stop after start
2016-11-21 11:10:55 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two peers with empty DB, update the doc
2016-11-21 11:10:55 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 914 verify failed
ok 915 constructor called once
ok 916 constructor called with right args
ok 917 last start before stop
ok 918 empty first start
ok 919 full second start
ok 920 only 2 timers
2016-11-21 11:10:55 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# add doc and make sure tokens refresh when they expire
2016-11-21 11:10:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
2016-11-21 11:10:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 921 verify failed
ok 922 constructor called once
ok 923 constructor called with right args
ok 924 start before stop
ok 925 We got at least 3 calls to start
ok 926 at least 3
ok 927 default 1
ok 928 1 run
ok 929 default 2
ok 930 2 run
ok 931 default 3
2016-11-21 11:10:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# start and stop and start and stop
ok 932 start out null
ok 933 back to null
2016-11-21 11:10:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 934 still null
ok 935 verify failed
ok 936 constructor called once
ok 937 constructor called with right args
ok 938 first start before first stop
ok 939 first stop before second start
ok 940 second start before second stop
2016-11-21 11:10:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two identical starts in a row
ok 941 verify failed
ok 942 constructor called once
ok 943 constructor called with right args
ok 944 (unnamed assert)
2016-11-21 11:10:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# two different starts in a row
2016-11-21 11:10:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 945 verify failed
ok 946 constructor called once
ok 947 constructor called with right args
ok 948 (unnamed assert)
ok 949 (unnamed assert)
# teardown
# setup
# two stops and a start and two stops
ok 950 verify failed
ok 951 constructor called once
ok 952 constructor called with right args
ok 953 start before stop
2016-11-21 11:10:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
# teardown
# setup
# we properly enqueue requests so no then needed
2016-11-21 11:10:56 - DEBUG thaliSendNotificationBasedOnReplication: 'We must have stopped because we are complete -{"status":"cancelled"}'
ok 954 verify failed
ok 955 constructor called once
ok 956 constructor called with right args
ok 957 start before stop
# teardown
# setup
# test calculateSeqPointKeyId
ok 958 should be equal
ok 959 should be equal
# teardown
# setup
# can create servers manager
ok 960 serversManager must not be null
ok 961 serversManager must be an object
# teardown
# setup
# calling stop without start causes error
ok 962 We need to call start first
# teardown
# setup
# can start/stop servers manager
2016-11-21 11:10:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:56 - DEBUG createNativeListener: 'listening 50608'
ok 963 port must be in range
# teardown
2016-11-21 11:10:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:56 - DEBUG createNativeListener: 'Native Server - close'
# setup
# starting twice resolves with listening port
2016-11-21 11:10:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:56 - DEBUG createNativeListener: 'listening 50609'
ok 964 second start should return same port
# teardown
2016-11-21 11:10:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:56 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminateIncomingConnection will terminate a connection
2016-11-21 11:10:56 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:56 - DEBUG createNativeListener: 'listening 50611'
2016-11-21 11:10:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:56 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 965 we should be connected
2016-11-21 11:10:56 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 966 now we are disconnected
2016-11-21 11:10:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# teardown
2016-11-21 11:10:56 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:56 - DEBUG createNativeListener: 'Native Server - close'
# setup
# terminate an Outgoing connection
2016-11-21 11:10:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 32'
ok 967 Passed bogus id
2016-11-21 11:10:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 901'
ok 968 Passed good id but bogus port
2016-11-21 11:10:56 - DEBUG thaliTcpServersManager: 'Terminate outgoing connection called on peerID foo with port 900'
ok 969 Passed right context
ok 970 Right server
ok 971 No error should be set
ok 972 Retry should be false
ok 973 We called close server
# teardown
# setup
# Correctly parses/stringifies USN
ok 974 correctly parses USN string
ok 975 throws if usn has invalid prefix
ok 976 throws if usn has invalid identifier format
ok 977 throws if usn has invalid generation
ok 978 correctly stringifies peer
# teardown
2016-11-21 11:10:56 - DEBUG SimpleThaliTape: 'all unit tests succeeded, platformName: 'android''
2016-11-21 11:10:56 - DEBUG SimpleThaliTape: 'skipped tests: '["does not emit duplicate discoveryAdvertisingStateUpdate","wifi peer is marked unavailable if announcements stop","native available - peer with greater generation is cached (MPCF)","native available - peer with same or older generation is ignored (MPCF)","networkChanged - fires peerAvailabilityChanged event for native peers (MPCF)","multiconnect failure - new peer is ignored (MPCF)","multiconnect failure - cached peer fires peerAvailabilityChanged (MPCF)","newAddressPort field (MPCF)","network changes emitted correctly","calls correct starts when network changes","We properly fire peer unavailable and then available when connection fails","make sure terminateConnection is return error if we get called on iOS","make sure terminateListener is return error if we get called on iOS"]''
2016-11-21 11:10:56 - DEBUG SimpleThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****'
2016-11-21 11:10:56 - INFO runTests: 'Finished'

1..978
# tests 978
# pass  978

# ok

2016-11-21 11:10:58 - INFO runTests: 'Starting tests. Network type: BOTH. Platform: android'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreateNativeListener.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManager.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testNativeMethod.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPouchDBGenerator.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testPromiseQueue.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testTests.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManager.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobile.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNative.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotification.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationAction.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationClient.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationLocal.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliNotificationServer.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerAction.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerDictionary.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliTcpServersManager.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
2016-11-21 11:10:58 - INFO runTests: 'Test runner loading file: /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testUsn.js'
2016-11-21 11:10:59 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
2016-11-21 11:10:59 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
2016-11-21 11:10:59 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"wifi":"on","bluetooth":"on","bluetoothLowEnergy":"doNotCare","cellular":"doNotCare"}'
2016-11-21 11:10:59 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
2016-11-21 11:10:59 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
2016-11-21 11:10:59 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
TAP version 13
# setup
# calling createNativeListener directly rejects
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50614'
ok 1 Should throw
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits incomingConnectionState
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50616'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 2 initial connection state should be CONNECTED
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 3 final connection state should be DISCONNECTED
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
# setup
# emits routerPortConnectionFailed
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50619'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 4 tried to connect to right port
ok 5 failed due to refused connection
ok 6 routerPortConnectionFailed is emitted
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server connections all up
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50623'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
ok 7 Send/recvd #1 should be equal length
ok 8 Send/recvd #1 should be same
ok 9 Send/recvd #2 should be equal length
ok 10 Send/recvd #2 should be same
ok 11 Should be exactly 2 client sockets
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - closing incoming stream cleans outgoing socket
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50628'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
ok 12 socket shouldn't close until after stream
ok 13 incoming remains open
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing incoming connection cleans outgoing socket
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50632'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 14 we should not have gotten an error
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 15 socket shouldn't close until after incoming
ok 16 incoming is cleaned up
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# native server - closing outgoing socket cleans associated mux stream
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50636'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - finished'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
ok 17 stream was closed
ok 18 incoming should survive
ok 19 mux should have no streams
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# native server - closing the whole server cleans everything up
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50640'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 20 we should not have gotten an error
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 21 Buffers are identical
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 22 native server is nulled out
ok 23 native server should be closed
ok 24 incoming has been removed
ok 25 Incoming should be done
ok 26 The mux object should be closed
ok 27 The mux stream should be closed
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# native server - we can get a ton of connections and data through and still clean up the server completely
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50644'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - created'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 9 - close'
ok 28 native server is nulled out
ok 29 native server should be closed
ok 30 incoming has been removed
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 9 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 8 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 7 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 6 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 5 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 4 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 9 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 8 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 7 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 6 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 5 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 4 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 3 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 2 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 1 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 3 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 2 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 1 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# native server - simulate mux failure, make sure everything is cleaned up
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50696'
ok 31 we should not have gotten an error
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 32 Buffers are identical
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 33 server should be fine
ok 34 server should be open
ok 35 incoming has been removed
ok 36 The mux object should be closed
ok 37 The mux stream should be closed
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
# setup
# native server - timing out the incoming connection cleans everything up
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50700'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
ok 38 we should not have gotten an error
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 39 Buffers are identical
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - incoming socket timeout'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
ok 40 server should be fine
ok 41 server should be open
ok 42 incoming has been removed
ok 43 The mux object should be closed
ok 44 The mux stream should be closed
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
# setup
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# calling createPeerListener without calling start produces error
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50705'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener after calling stop produces error
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50708'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# can call createPeerListener (pleaseConnect === false)
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50711'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50712'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 45 port must be in range
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener (pleaseConnect === true) with unknown peer is error
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50715'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peerId'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50716'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peerId'
2016-11-21 11:10:59 - WARN createPeerListener: 'callNative for peerId failed with Unknown Peer'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Unknown Peer" and peerIdentifier "peerId"'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Will try to recreate server for peerId'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peerId'
ok 46 should get error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peerId listening on 50717'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peerId and portNumber 50717'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peerId'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# calling createPeerListener twice with same peerIdentifier should return the same port
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50720'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50721'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 47 port values should be the same
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - closing connection to native listener closes everything and triggers new listener
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50724'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50725'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 48 Data should be of same length and content
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50730'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50730'
ok 49 same peer ID
ok 50 different ports
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# createPeerListener - closing mux closes listener and triggers a new listener
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50733'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50734'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - got a new incoming connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer2'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer2 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer2'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 51 Data should be of same length and content
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer2 - 0 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer2 - finish'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer2 - 0 - close'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Outgoing closed, recreating connection" and peerIdentifier "peer2"'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Will try to recreate server for peer2'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer2 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer2'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer2 listening on 50739'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer2 and portNumber 50739'
ok 52 same peer ID
ok 53 different ports
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer2'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
# setup
# peerListener - forwardConnection, pleaseConnect === true - no native server
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 54 Can call startUpdateAdvertisingAndListening without error
ok 55 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50742'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50743'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 56 reason should be as expected
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50745'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50745'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - forwardConnection, pleaseConnect === false - no native server
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 57 Can call startUpdateAdvertisingAndListening without error
ok 58 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50748'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50749'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 59 peerPort should not be nativePort
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 60 Should not get event until connection is made
ok 61 reason should be as expected
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - finish'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50752'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50752'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - forwardConnection, pleaseConnect === true - with native server
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 62 Can call startUpdateAdvertisingAndListening without error
ok 63 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50755'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50756'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 64 peerPort != nativePort
ok 65 Should get spontaneous connection
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 66 Can call startUpdateAdvertisingAndListening without error
ok 67 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50760'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50761'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 68 peerPort != nativePort
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
ok 69 Should not get unexpected connection
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
# setup
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - forwardConnection, pleaseConnect === false - with native server and data transfer
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50766'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50767'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
ok 70 Data should be of same length and content
ok 71 Data should be of same length and content
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - closed'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - WARN createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 -  error Error: read ECONNRESET'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# setup
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# createPeerListener is idempotent
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 72 Can call startUpdateAdvertisingAndListening without error
ok 73 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50773'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50774'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 74 Second call to existing peerListener returns existing port
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, failed connection rejects promise
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 75 Can call startUpdateAdvertisingAndListening without error
ok 76 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50777'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50778'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - WARN createPeerListener: 'callNative for peer1 failed with a nasty error'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: a nasty error" and peerIdentifier "peer1"'
ok 77 got our failed connection
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
ok 78 failed connection should reject with error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50779'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50779'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# createPeerListener - pleaseConnect === true, connection resolves promise
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 79 Can call startUpdateAdvertisingAndListening without error
ok 80 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50782'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50783'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Creating outgoing connection to native layer for peerID peer1'
ok 81 Should get spontaneous connection
ok 82 promise should resolve
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# peerListener - reverseConnection, pleaseConnect === true
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 83 Can call startUpdateAdvertisingAndListening without error
ok 84 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50787'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50788'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= true'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:59 - WARN createPeerListener: 'was expecting a forward connection to be made'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Cannot Connect To Peer" and peerIdentifier "peer1"'
ok 85 reason should be as expected
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50789'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50789'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'outgoing - mux <-> outgoing TCP/IP client connection to Android  - peer1 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'mux - mux <-> outgoing TCP/IP client connection to Android - peer1 - finish'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no incoming
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 86 Can call startUpdateAdvertisingAndListening without error
ok 87 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50792'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50793'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
ok 88 peerPort should not be nativePort
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'looking up mux for client port:  0'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'no mux found'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Incoming connection died" and peerIdentifier "peer1"'
ok 89 should not get event until connection is made
ok 90 reason should be as expected
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50795'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50795'
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - with incoming
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 91 Can call startUpdateAdvertisingAndListening without error
ok 92 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50798'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50799'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'looking up mux for client port:  50801'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'looking up mux for client port:  50801'
ok 93 sent and received should be the same
# teardown
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incomingStream (mux) - Node TCP/IP client <-> Mux stream -  peer1 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'mux - incoming Android TCP/IP client connection <-> Mux - 0 - close'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0 - close'
# setup
# peerListener - reverseConnection, pleaseConnect === false - no server
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Creating Native Server'
ok 94 Can call startUpdateAdvertisingAndListening without error
ok 95 Can call startListeningForAdvertisements without error
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'listening 50804'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50805'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - got a new incoming connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Issuing callNative for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'callNative for peer1 connected'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'looking up mux for client port:  50807'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'timed out waiting for incoming connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'reverse connection'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'looking up mux for client port:  50807'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'no mux found'
2016-11-21 11:10:59 - DEBUG makeIntoCloseAllServer: 'closeAll called on server'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting failedConnection with error "Error: Incoming connection died" and peerIdentifier "peer1"'
not ok 96 connection shouldn't fail
  ---
    operator: fail
    at: ThaliTcpServersManager.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:776:9)
  ...
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Will try to recreate server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Closed Node TCP/IP listener (server) for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'creating new server for peer1'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client - is already closed'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'Node TCP/IP listener (server) for peer1 listening on 50808'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'pleaseConnect= false'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'We are emitting listenerRecreatedAfterFailure with peerIdentifier peer1 and portNumber 50808'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'incoming - incoming Android TCP/IP client connection <-> Mux - 0'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'Native Server - Creating Mux'
2016-11-21 11:10:59 - DEBUG createPeerListener: 'incoming (TCP) - Node TCP/IP client <-> Mux stream - peer1 - 0 - close'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'stream - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - created'
2016-11-21 11:10:59 - DEBUG createNativeListener: 'outgoing - mux stream <-> outgoing TCP/IP client connection to node - 0 - 0 - error Error: connect ECONNREFUSED'
ok 97 should get routerPortConnectionFailed
2016-11-21 11:10:59 - ERROR SimpleThaliTape: 'test failed, name: 'peerListener - reverseConnection, pleaseConnect === false - no server''
2016-11-21 11:10:59 - ERROR TestsProcess: 'uncaught promise rejection, error: 'Error: test failed, name: 'peerListener - reverseConnection, pleaseConnect === false - no server'', stack: 'Error: test failed, name: 'peerListener - reverseConnection, pleaseConnect === false - no server'
    at Test.endHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/lib/SimpleTape.js:139:20)
    at Test.g (events.js:160:16)
    at Test.emit (events.js:98:20)
    at Test.bound [as emit] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Test._end (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:145:27)
    at Test.bound [as _end] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at Test.end (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:133:10)
    at Test.bound [as end] (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/tape/lib/test.js:62:32)
    at ThaliTcpServersManager.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/bv_tests/testCreatePeerListener.js:783:9)
    at ThaliTcpServersManager.emit (events.js:82:17)
    at Socket.<anonymous> (/Users/thali/Github/Thali_CordovaPlugin/thali/NextGeneration/mux/createNativeListener.js:292:16)
    at Socket.emit (events.js:82:17)
    at net.js:398:14
    at process._tickCallback (node.js:924:13)''
2016-11-21 11:10:59 - ERROR TestsProcess: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
-e [0;31mjx runTests.js --networkType BOTH FAILED - build.sh failure[0m
./build.sh CI FAILED - build.sh failure[0m

npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
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
npm http 304 http://192.168.1.100:4873/statuses
npm http fetch GET http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
npm http fetch 200 http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
npm http 304 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
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
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http fetch GET http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/punycode
npm http 200 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
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
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/underscore
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/leveldown-mobile
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/randomstring
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/sinon
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/nock
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
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/raw-body
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
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/send
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
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http fetch GET http://192.168.1.100:4873/http-errors/-/http-errors-1.5.1.tgz
npm http fetch 200 http://192.168.1.100:4873/http-errors/-/http-errors-1.5.1.tgz
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http fetch GET http://192.168.1.100:4873/setprototypeof/-/setprototypeof-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/setprototypeof/-/setprototypeof-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/vuvuzela
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
npm http request GET http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/json-schema
npm http 304 http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
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
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
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
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
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
npm http 304 http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
gyp http GET https://jxcore.azureedge.net/jxb311.tar.gz
gyp http 200 https://jxcore.azureedge.net/jxb311.tar.gz
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
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)

```

Error: Command failed: npm WARN thali-test-server@0.0.1 No repository field.
npm WARN thali-test-server@0.0.1 No license field.
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/javascript-state-machine
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/lie
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/winston
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/request
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/ip
npm http 200 http://192.168.1.100:4873/javascript-state-machine
npm http 200 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/winston
npm http 200 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/long
npm http 200 http://192.168.1.100:4873/lie
npm http 200 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/js-extend
npm http 200 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/content-type
npm http request GET http://192.168.1.100:4873/debug
npm http request GET http://192.168.1.100:4873/bytes
npm http request GET http://192.168.1.100:4873/depd
npm http request GET http://192.168.1.100:4873/http-errors
npm http request GET http://192.168.1.100:4873/on-finished
npm http request GET http://192.168.1.100:4873/iconv-lite
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/raw-body
npm http request GET http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
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
npm http 304 http://192.168.1.100:4873/statuses
npm http fetch GET http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
npm http fetch 200 http://192.168.1.100:4873/statuses/-/statuses-1.3.1.tgz
npm http 304 http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/ee-first
npm http 304 http://192.168.1.100:4873/ee-first
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
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/send
npm http 304 http://192.168.1.100:4873/vary
npm http 304 http://192.168.1.100:4873/serve-static
npm http 304 http://192.168.1.100:4873/utils-merge
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
npm http request GET http://192.168.1.100:4873/immediate
npm http 200 http://192.168.1.100:4873/immediate
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/xtend
npm http 200 http://192.168.1.100:4873/duplexify
npm http 200 http://192.168.1.100:4873/varint
npm http fetch GET http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http fetch 200 http://192.168.1.100:4873/readable-stream/-/readable-stream-2.2.2.tgz
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 200 http://192.168.1.100:4873/end-of-stream
npm http 200 http://192.168.1.100:4873/stream-shift
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/wrappy
npm http 304 http://192.168.1.100:4873/wrappy
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/core-util-is
npm http request GET http://192.168.1.100:4873/string_decoder
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http 200 http://192.168.1.100:4873/core-util-is
npm http 304 http://192.168.1.100:4873/isarray
npm http 200 http://192.168.1.100:4873/string_decoder
npm http 200 http://192.168.1.100:4873/buffer-shims
npm http 200 http://192.168.1.100:4873/util-deprecate
npm http 200 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 200 http://192.168.1.100:4873/caseless
npm http 200 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/bl
npm http 200 http://192.168.1.100:4873/json-stringify-safe
npm http 200 http://192.168.1.100:4873/tunnel-agent
npm http 200 http://192.168.1.100:4873/oauth-sign
npm http 200 http://192.168.1.100:4873/http-signature
npm http 200 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/isstream
npm http 200 http://192.168.1.100:4873/stringstream
npm http 200 http://192.168.1.100:4873/combined-stream
npm http 200 http://192.168.1.100:4873/aws-sign2
npm http 200 http://192.168.1.100:4873/har-validator
npm http 200 http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 200 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 200 http://192.168.1.100:4873/lodash
npm http fetch GET http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http fetch 200 http://192.168.1.100:4873/lodash/-/lodash-4.17.2.tgz
npm http request GET http://192.168.1.100:4873/commander
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http 200 http://192.168.1.100:4873/commander
npm http 200 http://192.168.1.100:4873/chalk
npm http 200 http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/escape-string-regexp
npm http 200 http://192.168.1.100:4873/ansi-styles
npm http 200 http://192.168.1.100:4873/has-ansi
npm http 200 http://192.168.1.100:4873/strip-ansi
npm http 200 http://192.168.1.100:4873/supports-color
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 200 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/graceful-readlink
npm http 200 http://192.168.1.100:4873/graceful-readlink
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/jsonpointer
npm http 200 http://192.168.1.100:4873/generate-object-property
npm http 200 http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/is-property
npm http 200 http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/cryptiles
npm http 200 http://192.168.1.100:4873/boom
npm http 200 http://192.168.1.100:4873/sntp
npm http 200 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/ctype
npm http 200 http://192.168.1.100:4873/assert-plus
npm http 200 http://192.168.1.100:4873/asn1
npm http 200 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/punycode
npm http 200 http://192.168.1.100:4873/punycode
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/object-assign
npm http 200 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/colors
npm http request GET http://192.168.1.100:4873/cycle
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
npm http request GET http://192.168.1.100:4873/catharsis
npm http request GET http://192.168.1.100:4873/js2xmlparser
npm http request GET http://192.168.1.100:4873/marked
npm http request GET http://192.168.1.100:4873/esprima
npm http request GET http://192.168.1.100:4873/requizzle
npm http request GET http://192.168.1.100:4873/strip-json-comments
npm http request GET http://192.168.1.100:4873/underscore
npm http request GET http://192.168.1.100:4873/wrench
npm http fetch GET https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http 200 http://192.168.1.100:4873/js2xmlparser
npm http 200 http://192.168.1.100:4873/catharsis
npm http 200 http://192.168.1.100:4873/requizzle
npm http 200 http://192.168.1.100:4873/marked
npm http 200 http://192.168.1.100:4873/esprima
npm http 200 http://192.168.1.100:4873/wrench
npm http 200 http://192.168.1.100:4873/strip-json-comments
npm http 200 http://192.168.1.100:4873/underscore
npm WARN deprecated wrench@1.5.9: wrench.js is deprecated! You should check out fs-extra (https://github.com/jprichardson/node-fs-extra) for any operations you were using wrench for. Thanks for all the usage over the years.
npm http fetch 200 https://github.com/hegemonic/taffydb/tarball/7d100bcee0e997ee4977e273cdce60bd8933050e
npm http request GET http://192.168.1.100:4873/underscore-contrib
npm http 200 http://192.168.1.100:4873/underscore-contrib
npm WARN prefer global marked@0.3.6 should be installed with -g
npm WARN install@0.0.1 No repository field.
npm http request GET http://192.168.1.100:4873/balanced-match
npm http request GET http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/body-parser
npm http request GET http://192.168.1.100:4873/child-process-promise
npm http request GET http://192.168.1.100:4873/concat-map
npm http request GET http://192.168.1.100:4873/inherits
npm http request GET http://192.168.1.100:4873/is-property
npm http request GET http://192.168.1.100:4873/express
npm http request GET http://192.168.1.100:4873/bn.js
npm http request GET http://192.168.1.100:4873/js-extend
npm http request GET http://192.168.1.100:4873/express-pouchdb
npm http request GET http://192.168.1.100:4873/long
npm http request GET http://192.168.1.100:4873/multiplex
npm http request GET http://192.168.1.100:4873/leveldown-mobile
npm http request GET http://192.168.1.100:4873/node-uuid
npm http request GET http://192.168.1.100:4873/object-assign
npm http request GET http://192.168.1.100:4873/randomstring
npm http request GET http://192.168.1.100:4873/request
npm http request GET http://192.168.1.100:4873/pouchdb-size
npm http request GET http://192.168.1.100:4873/proxyquire
npm http request GET http://192.168.1.100:4873/nock
npm http request GET http://192.168.1.100:4873/pouchdb
npm http request GET http://192.168.1.100:4873/request-promise
npm http request GET http://192.168.1.100:4873/socket.io-client
npm http request GET http://192.168.1.100:4873/sinon
npm http request GET http://192.168.1.100:4873/supertest
npm http request GET http://192.168.1.100:4873/supertest-as-promised
npm http request GET http://192.168.1.100:4873/urlsafe-base64
npm http request GET http://192.168.1.100:4873/tape-catch
npm http request GET http://192.168.1.100:4873/tmp
npm http request GET http://192.168.1.100:4873/uuid
npm http request GET http://192.168.1.100:4873/tape
npm http request GET http://192.168.1.100:4873/uuid-validate
npm http 304 http://192.168.1.100:4873/balanced-match
npm http 304 http://192.168.1.100:4873/child-process-promise
npm http 304 http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/body-parser
npm http 304 http://192.168.1.100:4873/concat-map
npm http 304 http://192.168.1.100:4873/inherits
npm http 304 http://192.168.1.100:4873/is-property
npm http 304 http://192.168.1.100:4873/js-extend
npm http 304 http://192.168.1.100:4873/express
npm http 200 http://192.168.1.100:4873/bn.js
npm http 304 http://192.168.1.100:4873/multiplex
npm http 200 http://192.168.1.100:4873/express-pouchdb
npm http 304 http://192.168.1.100:4873/long
npm http 304 http://192.168.1.100:4873/node-uuid
npm http 304 http://192.168.1.100:4873/request
npm http 200 http://192.168.1.100:4873/leveldown-mobile
npm http fetch GET http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 304 http://192.168.1.100:4873/object-assign
npm http 304 http://192.168.1.100:4873/randomstring
npm http 200 http://192.168.1.100:4873/pouchdb-size
npm http 200 http://192.168.1.100:4873/proxyquire
npm http 304 http://192.168.1.100:4873/socket.io-client
npm http 200 http://192.168.1.100:4873/request-promise
npm http 200 http://192.168.1.100:4873/supertest
npm http 304 http://192.168.1.100:4873/urlsafe-base64
npm http 200 http://192.168.1.100:4873/supertest-as-promised
npm http 200 http://192.168.1.100:4873/pouchdb
npm http 304 http://192.168.1.100:4873/uuid
npm http 200 http://192.168.1.100:4873/sinon
npm http fetch 200 http://192.168.1.100:4873/express-pouchdb/-/express-pouchdb-1.0.6-thali.tgz
npm http 200 http://192.168.1.100:4873/tape-catch
npm http 200 http://192.168.1.100:4873/tmp
npm http 200 http://192.168.1.100:4873/uuid-validate
npm http 200 http://192.168.1.100:4873/tape
npm http 200 http://192.168.1.100:4873/nock
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
npm http 304 http://192.168.1.100:4873/content-type
npm http 304 http://192.168.1.100:4873/depd
npm http 304 http://192.168.1.100:4873/debug
npm http 304 http://192.168.1.100:4873/http-errors
npm http 304 http://192.168.1.100:4873/iconv-lite
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/on-finished
npm http 304 http://192.168.1.100:4873/type-is
npm http 304 http://192.168.1.100:4873/raw-body
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
npm http 304 http://192.168.1.100:4873/accepts
npm http 304 http://192.168.1.100:4873/cookie
npm http 304 http://192.168.1.100:4873/cookie-signature
npm http 304 http://192.168.1.100:4873/content-disposition
npm http 304 http://192.168.1.100:4873/array-flatten
npm http 304 http://192.168.1.100:4873/etag
npm http 304 http://192.168.1.100:4873/escape-html
npm http 304 http://192.168.1.100:4873/fresh
npm http 304 http://192.168.1.100:4873/merge-descriptors
npm http 304 http://192.168.1.100:4873/finalhandler
npm http 304 http://192.168.1.100:4873/methods
npm http 304 http://192.168.1.100:4873/parseurl
npm http 304 http://192.168.1.100:4873/range-parser
npm http 304 http://192.168.1.100:4873/proxy-addr
npm http 304 http://192.168.1.100:4873/path-to-regexp
npm http 304 http://192.168.1.100:4873/send
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
npm http 304 http://192.168.1.100:4873/mime
npm http 304 http://192.168.1.100:4873/destroy
npm http request GET http://192.168.1.100:4873/extend
npm http request GET http://192.168.1.100:4873/basic-auth
npm http request GET http://192.168.1.100:4873/compression
npm http request GET http://192.168.1.100:4873/cookie-parser
npm http request GET http://192.168.1.100:4873/header-case-normalizer
npm http request GET http://192.168.1.100:4873/multiparty
npm http request GET http://192.168.1.100:4873/pouchdb-all-dbs
npm http request GET http://192.168.1.100:4873/pouchdb-replicator
npm http request GET http://192.168.1.100:4873/pouchdb-auth
npm http request GET http://192.168.1.100:4873/pouchdb-list
npm http request GET http://192.168.1.100:4873/pouchdb-find
npm http request GET http://192.168.1.100:4873/pouchdb-rewrite
npm http request GET http://192.168.1.100:4873/pouchdb-security
npm http request GET http://192.168.1.100:4873/pouchdb-show
npm http request GET http://192.168.1.100:4873/pouchdb-update
npm http request GET http://192.168.1.100:4873/pouchdb-validation
npm http request GET http://192.168.1.100:4873/pouchdb-vhost
npm http request GET http://192.168.1.100:4873/pouchdb-wrappers
npm http 304 http://192.168.1.100:4873/extend
npm http 200 http://192.168.1.100:4873/cookie-parser
npm http 200 http://192.168.1.100:4873/basic-auth
npm http 200 http://192.168.1.100:4873/header-case-normalizer
npm http 200 http://192.168.1.100:4873/compression
npm http 200 http://192.168.1.100:4873/multiparty
npm http 200 http://192.168.1.100:4873/pouchdb-auth
npm http 200 http://192.168.1.100:4873/pouchdb-list
npm http 200 http://192.168.1.100:4873/pouchdb-replicator
npm http 200 http://192.168.1.100:4873/pouchdb-all-dbs
npm http 200 http://192.168.1.100:4873/pouchdb-find
npm http 200 http://192.168.1.100:4873/pouchdb-show
npm http 200 http://192.168.1.100:4873/pouchdb-rewrite
npm http 200 http://192.168.1.100:4873/pouchdb-update
npm http 200 http://192.168.1.100:4873/pouchdb-security
npm http 200 http://192.168.1.100:4873/pouchdb-validation
npm http 200 http://192.168.1.100:4873/pouchdb-wrappers
npm http 200 http://192.168.1.100:4873/pouchdb-vhost
npm http fetch GET http://192.168.1.100:4873/http-errors/-/http-errors-1.5.1.tgz
npm http fetch 200 http://192.168.1.100:4873/http-errors/-/http-errors-1.5.1.tgz
npm http request GET http://192.168.1.100:4873/setprototypeof
npm http 200 http://192.168.1.100:4873/setprototypeof
npm http fetch GET http://192.168.1.100:4873/setprototypeof/-/setprototypeof-1.0.2.tgz
npm http fetch 200 http://192.168.1.100:4873/setprototypeof/-/setprototypeof-1.0.2.tgz
npm http request GET http://192.168.1.100:4873/compressible
npm http request GET http://192.168.1.100:4873/on-headers
npm http 200 http://192.168.1.100:4873/compressible
npm http 200 http://192.168.1.100:4873/on-headers
npm http request GET http://192.168.1.100:4873/readable-stream
npm http request GET http://192.168.1.100:4873/stream-counter
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 200 http://192.168.1.100:4873/stream-counter
npm http request GET http://192.168.1.100:4873/es3ify
npm http request GET http://192.168.1.100:4873/argsarray
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/tiny-queue
npm http 304 http://192.168.1.100:4873/es3ify
npm http 200 http://192.168.1.100:4873/tiny-queue
npm http 200 http://192.168.1.100:4873/argsarray
npm http 200 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/jstransform
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/base62
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/base62
npm http 304 http://192.168.1.100:4873/source-map
npm http request GET http://192.168.1.100:4873/couchdb-calculate-session-id
npm http request GET http://192.168.1.100:4873/base64url
npm http request GET http://192.168.1.100:4873/crypto-lite
npm http request GET http://192.168.1.100:4873/pouchdb-plugin-error
npm http request GET http://192.168.1.100:4873/pouchdb-req-http-query
npm http request GET http://192.168.1.100:4873/secure-random
npm http request GET http://192.168.1.100:4873/pouchdb-system-db
npm http request GET http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http request GET http://192.168.1.100:4873/promise-nodify
npm http 200 http://192.168.1.100:4873/couchdb-calculate-session-id
npm http 200 http://192.168.1.100:4873/pouchdb-plugin-error
npm http 200 http://192.168.1.100:4873/base64url
npm http 200 http://192.168.1.100:4873/crypto-lite
npm http 200 http://192.168.1.100:4873/pouchdb-req-http-query
npm http 200 http://192.168.1.100:4873/secure-random
npm http 200 http://192.168.1.100:4873/pouchdb-system-db
npm http 200 http://192.168.1.100:4873/pouchdb-bulkdocs-wrapper
npm http 200 http://192.168.1.100:4873/promise-nodify
npm http request GET http://192.168.1.100:4873/concat-stream
npm http request GET http://192.168.1.100:4873/meow
npm http 200 http://192.168.1.100:4873/concat-stream
npm http 200 http://192.168.1.100:4873/meow
npm http request GET http://192.168.1.100:4873/typedarray
npm http 200 http://192.168.1.100:4873/typedarray
npm http request GET http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/camelcase-keys
npm http 200 http://192.168.1.100:4873/indent-string
npm http request GET http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/map-obj
npm http 200 http://192.168.1.100:4873/camelcase
npm http request GET http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/get-stdin
npm http 200 http://192.168.1.100:4873/repeating
npm http request GET http://192.168.1.100:4873/is-finite
npm http 200 http://192.168.1.100:4873/is-finite
npm http request GET http://192.168.1.100:4873/number-is-nan
npm http 200 http://192.168.1.100:4873/number-is-nan
npm http request GET http://192.168.1.100:4873/aproba
npm http 200 http://192.168.1.100:4873/aproba
npm http request GET http://192.168.1.100:4873/es6-promise-pool
npm http request GET http://192.168.1.100:4873/double-ended-queue
npm http request GET http://192.168.1.100:4873/level-write-stream
npm http request GET http://192.168.1.100:4873/fruitdown
npm http request GET http://192.168.1.100:4873/spark-md5
npm http request GET http://192.168.1.100:4873/through2
npm http request GET http://192.168.1.100:4873/sublevel-pouchdb
npm http request GET http://192.168.1.100:4873/localstorage-down
npm http request GET http://192.168.1.100:4873/memdown
npm http request GET http://192.168.1.100:4873/pouchdb-collate
npm http request GET http://192.168.1.100:4873/levelup
npm http request GET http://192.168.1.100:4873/scope-eval
npm http request GET http://192.168.1.100:4873/pouchdb-collections
npm http request GET http://192.168.1.100:4873/vuvuzela
npm http 200 http://192.168.1.100:4873/level-write-stream
npm http 200 http://192.168.1.100:4873/double-ended-queue
npm http 200 http://192.168.1.100:4873/fruitdown
npm http 200 http://192.168.1.100:4873/spark-md5
npm http 200 http://192.168.1.100:4873/es6-promise-pool
npm http 304 http://192.168.1.100:4873/through2
npm http 200 http://192.168.1.100:4873/sublevel-pouchdb
npm http 200 http://192.168.1.100:4873/pouchdb-collate
npm http 200 http://192.168.1.100:4873/localstorage-down
npm http 200 http://192.168.1.100:4873/memdown
npm http 200 http://192.168.1.100:4873/scope-eval
npm http 200 http://192.168.1.100:4873/pouchdb-collections
npm http 200 http://192.168.1.100:4873/vuvuzela
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
npm http request GET http://192.168.1.100:4873/semver
npm http request GET http://192.168.1.100:4873/deferred-leveldown
npm http request GET http://192.168.1.100:4873/level-codec
npm http request GET http://192.168.1.100:4873/level-errors
npm http request GET http://192.168.1.100:4873/level-iterator-stream
npm http request GET http://192.168.1.100:4873/prr
npm http 200 http://192.168.1.100:4873/deferred-leveldown
npm http 200 http://192.168.1.100:4873/level-codec
npm http 200 http://192.168.1.100:4873/level-iterator-stream
npm http 200 http://192.168.1.100:4873/level-errors
npm http 200 http://192.168.1.100:4873/semver
npm http 200 http://192.168.1.100:4873/prr
npm http request GET http://192.168.1.100:4873/errno
npm http 200 http://192.168.1.100:4873/errno
npm http request GET http://192.168.1.100:4873/humble-localstorage
npm http 200 http://192.168.1.100:4873/humble-localstorage
npm http request GET http://192.168.1.100:4873/has-localstorage
npm http request GET http://192.168.1.100:4873/localstorage-memory
npm http 200 http://192.168.1.100:4873/has-localstorage
npm http 200 http://192.168.1.100:4873/localstorage-memory
npm http request GET http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/functional-red-black-tree
npm http 200 http://192.168.1.100:4873/ltgt
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/aws4
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/caseless
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/form-data
npm http request GET http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/hawk
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/is-typedarray
npm http request GET http://192.168.1.100:4873/isstream
npm http request GET http://192.168.1.100:4873/json-stringify-safe
npm http request GET http://192.168.1.100:4873/oauth-sign
npm http request GET http://192.168.1.100:4873/stringstream
npm http request GET http://192.168.1.100:4873/tough-cookie
npm http request GET http://192.168.1.100:4873/tunnel-agent
npm http request GET http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/aws4
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/caseless
npm http 304 http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/hawk
npm http 304 http://192.168.1.100:4873/is-typedarray
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/json-stringify-safe
npm http 304 http://192.168.1.100:4873/isstream
npm http 304 http://192.168.1.100:4873/tough-cookie
npm http 304 http://192.168.1.100:4873/oauth-sign
npm http 304 http://192.168.1.100:4873/stringstream
npm WARN deprecated tough-cookie@2.2.2: ReDoS vulnerability parsing Set-Cookie https://nodesecurity.io/advisories/130
npm http 304 http://192.168.1.100:4873/tunnel-agent
npm http 304 http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/isarray
npm http request GET http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/isarray
npm http 304 http://192.168.1.100:4873/util-deprecate
npm http 304 http://192.168.1.100:4873/process-nextick-args
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/async
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/is-my-json-valid
npm http request GET http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/pinkie-promise
npm http 304 http://192.168.1.100:4873/is-my-json-valid
npm http 304 http://192.168.1.100:4873/chalk
npm http request GET http://192.168.1.100:4873/ansi-styles
npm http request GET http://192.168.1.100:4873/escape-string-regexp
npm http request GET http://192.168.1.100:4873/has-ansi
npm http request GET http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/ansi-styles
npm http 304 http://192.168.1.100:4873/has-ansi
npm http 304 http://192.168.1.100:4873/escape-string-regexp
npm http 304 http://192.168.1.100:4873/supports-color
npm http 304 http://192.168.1.100:4873/strip-ansi
npm http request GET http://192.168.1.100:4873/ansi-regex
npm http 304 http://192.168.1.100:4873/ansi-regex
npm http request GET http://192.168.1.100:4873/generate-function
npm http request GET http://192.168.1.100:4873/generate-object-property
npm http request GET http://192.168.1.100:4873/jsonpointer
npm http 304 http://192.168.1.100:4873/generate-object-property
npm http 304 http://192.168.1.100:4873/generate-function
npm http 304 http://192.168.1.100:4873/jsonpointer
npm http request GET http://192.168.1.100:4873/pinkie
npm http 304 http://192.168.1.100:4873/pinkie
npm http request GET http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/boom
npm http request GET http://192.168.1.100:4873/cryptiles
npm http request GET http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/sntp
npm http 304 http://192.168.1.100:4873/boom
npm http 304 http://192.168.1.100:4873/cryptiles
npm http 304 http://192.168.1.100:4873/hoek
npm http request GET http://192.168.1.100:4873/assert-plus
npm http request GET http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/assert-plus
npm http 304 http://192.168.1.100:4873/sshpk
npm http 304 http://192.168.1.100:4873/jsprim
npm http request GET http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/json-schema
npm http request GET http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/json-schema
npm http 304 http://192.168.1.100:4873/verror
npm http 304 http://192.168.1.100:4873/extsprintf
npm http request GET http://192.168.1.100:4873/asn1
npm http request GET http://192.168.1.100:4873/dashdash
npm http request GET http://192.168.1.100:4873/getpass
npm http 304 http://192.168.1.100:4873/dashdash
npm http 304 http://192.168.1.100:4873/asn1
npm http 304 http://192.168.1.100:4873/getpass
npm http request GET http://192.168.1.100:4873/pull-stream
npm http 200 http://192.168.1.100:4873/pull-stream
npm http request GET http://192.168.1.100:4873/pull-core
npm http 200 http://192.168.1.100:4873/pull-core
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
npm http request GET http://192.168.1.100:4873/pouchdb-promise
npm http 304 http://192.168.1.100:4873/pouchdb-promise
npm http request GET http://192.168.1.100:4873/couchdb-objects
npm http request GET http://192.168.1.100:4873/couchdb-eval
npm http request GET http://192.168.1.100:4873/random-uuid-v4
npm http 200 http://192.168.1.100:4873/couchdb-objects
npm http 200 http://192.168.1.100:4873/couchdb-eval
npm http 200 http://192.168.1.100:4873/random-uuid-v4
npm http request GET http://192.168.1.100:4873/is-empty
npm http 200 http://192.168.1.100:4873/is-empty
npm http request GET http://192.168.1.100:4873/is-array
npm http request GET http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/is-array
npm http 200 http://192.168.1.100:4873/pouchdb-upsert
npm http 200 http://192.168.1.100:4873/pouchdb-extend
npm http request GET http://192.168.1.100:4873/unreachable-branch-transform
npm http 304 http://192.168.1.100:4873/unreachable-branch-transform
npm http request GET http://192.168.1.100:4873/recast
npm http 304 http://192.168.1.100:4873/recast
npm http request GET http://192.168.1.100:4873/ast-types
npm http request GET http://192.168.1.100:4873/esprima-fb
npm http request GET http://192.168.1.100:4873/source-map
npm http 304 http://192.168.1.100:4873/ast-types
npm http 304 http://192.168.1.100:4873/esprima-fb
npm http 304 http://192.168.1.100:4873/source-map
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
npm http request GET http://192.168.1.100:4873/varint
npm http request GET http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/varint
npm http 304 http://192.168.1.100:4873/readable-stream
npm http 304 http://192.168.1.100:4873/duplexify
npm http request GET http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/stream-shift
npm http 304 http://192.168.1.100:4873/end-of-stream
npm http request GET http://192.168.1.100:4873/once
npm http 304 http://192.168.1.100:4873/once
npm http request GET http://192.168.1.100:4873/buffer-shims
npm http 304 http://192.168.1.100:4873/buffer-shims
npm http request GET http://192.168.1.100:4873/debug
npm WARN deprecated lodash@2.4.1: lodash@<3.0.0 is no longer maintained. Upgrade to lodash@^4.0.0.
npm http request GET http://192.168.1.100:4873/propagate
npm http request GET http://192.168.1.100:4873/deep-equal
npm http request GET http://192.168.1.100:4873/chai
npm http 304 http://192.168.1.100:4873/debug
npm http 200 http://192.168.1.100:4873/propagate
npm http 200 http://192.168.1.100:4873/deep-equal
npm http 200 http://192.168.1.100:4873/chai
npm http request GET http://192.168.1.100:4873/deep-eql
npm http request GET http://192.168.1.100:4873/assertion-error
npm http request GET http://192.168.1.100:4873/type-detect
npm http 200 http://192.168.1.100:4873/assertion-error
npm http 200 http://192.168.1.100:4873/deep-eql
npm http 200 http://192.168.1.100:4873/type-detect
npm http request GET http://192.168.1.100:4873/ms
npm http 304 http://192.168.1.100:4873/ms
npm http request GET http://192.168.1.100:4873/ip
npm http 304 http://192.168.1.100:4873/ip
npm http request GET http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/module-not-found-error
npm http 200 http://192.168.1.100:4873/fill-keys
npm http request GET http://192.168.1.100:4873/is-object
npm http 200 http://192.168.1.100:4873/is-object
npm http request GET http://192.168.1.100:4873/array-uniq
npm http 304 http://192.168.1.100:4873/array-uniq
npm http request GET http://192.168.1.100:4873/bl
npm http request GET http://192.168.1.100:4873/http-signature
npm http request GET http://192.168.1.100:4873/aws-sign2
npm http request GET http://192.168.1.100:4873/qs
npm http request GET http://192.168.1.100:4873/har-validator
npm http 304 http://192.168.1.100:4873/http-signature
npm http 304 http://192.168.1.100:4873/aws-sign2
npm http 304 http://192.168.1.100:4873/qs
npm http 304 http://192.168.1.100:4873/bl
npm http 304 http://192.168.1.100:4873/har-validator
npm http request GET http://192.168.1.100:4873/ctype
npm http 304 http://192.168.1.100:4873/ctype
npm http request GET http://192.168.1.100:4873/lodash
npm http 304 http://192.168.1.100:4873/lodash
npm http request GET http://192.168.1.100:4873/jsonschema
npm http 304 http://192.168.1.100:4873/jsonschema
npm http request GET http://192.168.1.100:4873/util
npm http request GET http://192.168.1.100:4873/samsam
npm http request GET http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/lolex
npm http 200 http://192.168.1.100:4873/samsam
npm http 200 http://192.168.1.100:4873/util
npm http 200 http://192.168.1.100:4873/formatio
npm http request GET http://192.168.1.100:4873/component-bind
npm http request GET http://192.168.1.100:4873/engine.io-client
npm http request GET http://192.168.1.100:4873/component-emitter
npm http request GET http://192.168.1.100:4873/object-component
npm http request GET http://192.168.1.100:4873/socket.io-parser
npm http request GET http://192.168.1.100:4873/has-binary
npm http request GET http://192.168.1.100:4873/indexof
npm http request GET http://192.168.1.100:4873/parseuri
npm http request GET http://192.168.1.100:4873/to-array
npm http request GET http://192.168.1.100:4873/backo2
npm http 304 http://192.168.1.100:4873/component-bind
npm http 304 http://192.168.1.100:4873/component-emitter
npm http 304 http://192.168.1.100:4873/socket.io-parser
npm http 304 http://192.168.1.100:4873/object-component
npm http 304 http://192.168.1.100:4873/engine.io-client
npm http 304 http://192.168.1.100:4873/has-binary
npm http 304 http://192.168.1.100:4873/indexof
npm http 304 http://192.168.1.100:4873/to-array
npm http 304 http://192.168.1.100:4873/parseuri
npm http 304 http://192.168.1.100:4873/backo2
npm http request GET http://192.168.1.100:4873/has-cors
npm http request GET http://192.168.1.100:4873/ws
npm http request GET http://192.168.1.100:4873/xmlhttprequest-ssl
npm http request GET http://192.168.1.100:4873/engine.io-parser
npm http request GET http://192.168.1.100:4873/parsejson
npm http request GET http://192.168.1.100:4873/parseqs
npm http request GET http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/ws
npm http 304 http://192.168.1.100:4873/xmlhttprequest-ssl
npm http 304 http://192.168.1.100:4873/engine.io-parser
npm http 304 http://192.168.1.100:4873/has-cors
npm http 304 http://192.168.1.100:4873/parsejson
npm http 304 http://192.168.1.100:4873/parseqs
npm http 304 http://192.168.1.100:4873/yeast
npm http 304 http://192.168.1.100:4873/component-inherit
npm http request GET http://192.168.1.100:4873/after
npm http request GET http://192.168.1.100:4873/arraybuffer.slice
npm http request GET http://192.168.1.100:4873/base64-arraybuffer
npm http request GET http://192.168.1.100:4873/blob
npm http request GET http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/after
npm http 304 http://192.168.1.100:4873/blob
npm http 304 http://192.168.1.100:4873/arraybuffer.slice
npm http 304 http://192.168.1.100:4873/utf8
npm http 304 http://192.168.1.100:4873/base64-arraybuffer
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
npm http 304 http://192.168.1.100:4873/benchmark
npm http 304 http://192.168.1.100:4873/json3
npm http request GET http://192.168.1.100:4873/superagent
npm http 200 http://192.168.1.100:4873/superagent
npm http request GET http://192.168.1.100:4873/formidable
npm http request GET http://192.168.1.100:4873/methods
npm http request GET http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/reduce-component
npm http request GET http://192.168.1.100:4873/form-data
npm http 304 http://192.168.1.100:4873/methods
npm http 200 http://192.168.1.100:4873/reduce-component
npm http 200 http://192.168.1.100:4873/formidable
npm http 304 http://192.168.1.100:4873/form-data
npm http 200 http://192.168.1.100:4873/cookiejar
npm http request GET http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/combined-stream
npm http request GET http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/combined-stream
npm http 304 http://192.168.1.100:4873/mime-types
npm http 304 http://192.168.1.100:4873/async
npm http request GET http://192.168.1.100:4873/delayed-stream
npm http 304 http://192.168.1.100:4873/delayed-stream
npm http request GET http://192.168.1.100:4873/mime-db
npm http 304 http://192.168.1.100:4873/mime-db
npm http request GET http://192.168.1.100:4873/bluebird
npm http 304 http://192.168.1.100:4873/bluebird
npm http request GET http://192.168.1.100:4873/defined
npm http request GET http://192.168.1.100:4873/glob
npm http request GET http://192.168.1.100:4873/resumer
npm http request GET http://192.168.1.100:4873/object-inspect
npm http 304 http://192.168.1.100:4873/glob
npm http 200 http://192.168.1.100:4873/resumer
npm http 304 http://192.168.1.100:4873/defined
npm http 200 http://192.168.1.100:4873/object-inspect
npm http request GET http://192.168.1.100:4873/os-tmpdir
npm http 200 http://192.168.1.100:4873/os-tmpdir
gyp JXcore NODE-GYP Using node-gyp bundled in npm coming from JXcore
gyp http GET https://jxcore.azureedge.net/jxb311.tar.gz
gyp http 200 https://jxcore.azureedge.net/jxb311.tar.gz
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
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:82:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
(node) warning: possible EventEmitter memory leak detected. 11 listeners added. Use emitter.setMaxListeners() to increase limit.
Trace
    at EventEmitter.addListener (events.js:140:15)
    at module.exports (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/pouchdb-all-dbs/lib/index.js:57:9)
    at /Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/lib/index.js:143:35
    at tryCatcher (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/util.js:16:23)
    at Promise._settlePromiseFromHandler (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:504:31)
    at Promise._settlePromise (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:561:18)
    at Promise._settlePromise0 (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:606:10)
    at Promise._settlePromises (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/promise.js:681:18)
    at Async._drainQueue (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:138:16)
    at Async._drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:148:10)
    at Async.drainQueues (/Users/thali/Github/Thali_CordovaPlugin/test/www/jxcore/node_modules/express-pouchdb/node_modules/bluebird/js/release/async.js:17:14)
    at process._tickCallback (node.js:924:13)
