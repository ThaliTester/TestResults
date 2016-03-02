#### Test (Fail) 60124347 Build Logs


```
Your branch is up-to-date with 'origin/master'.
Branch vNext set up to track remote branch vNext from origin.
Removing thali/NextGeneration/thaliSendNotificationBasedOnReplication.js
Auto-merging thali/NextGeneration/thaliPeerPool/thaliPeerPoolInterface.js
Auto-merging thali/NextGeneration/thaliPeerPool/thaliPeerPoolDefault.js
Auto-merging thali/NextGeneration/thaliPeerPool/thaliPeerAction.js
Removing thali/NextGeneration/thaliNotificationServer.js
Auto-merging thali/NextGeneration/notification/thaliNotificationBeacons.js
Removing src/android/java/io/jxcore/node/LifeCycleMonitor.java
Removing src/android/java/io/jxcore/node/ConnectivityMonitor.java
Removing src/android/java/io/jxcore/node/ConnectionStatusListener.java
Auto-merging src/android/java/io/jxcore/node/ConnectionModel.java
Merge made by the 'recursive' strategy.
 .editorconfig                                      |   4 +
 .jshintrc                                          |   3 +-
 plugin.xml                                         |  13 +-
 src/android/JXcore.gradle                          |   2 +-
 .../java/io/jxcore/node/ConnectionHelper.java      | 850 ++++++++++++---------
 ...ndConnectionModel.java => ConnectionModel.java} | 178 ++---
 .../io/jxcore/node/ConnectionStatusListener.java   |  37 -
 .../java/io/jxcore/node/ConnectivityInfo.java      | 188 +++++
 .../java/io/jxcore/node/ConnectivityMonitor.java   |  93 ---
 .../java/io/jxcore/node/HandshakeHelper.java       | 345 +++++++++
 .../java/io/jxcore/node/IncomingSocketThread.java  |  24 +-
 .../java/io/jxcore/node/JXcoreExtension.java       | 788 +++++++++++++------
 .../java/io/jxcore/node/JXcoreThaliCallback.java   |  41 +
 .../java/io/jxcore/node/LifeCycleMonitor.java      |  79 --
 .../jxcore/node/ListenerOrIncomingConnection.java  |  97 +++
 .../java/io/jxcore/node/OutgoingSocketThread.java  |  34 +-
 .../java/io/jxcore/node/SocketThreadBase.java      |  61 +-
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
 test/www/jxcore/bv_tests/testThaliMobileNative.js  |  18 +-
 .../bv_tests/testThaliNotificationBeacons.js       |   2 +-
 .../jxcore/bv_tests/testThaliNotificationServer.js | 289 +++++++
 test/www/jxcore/bv_tests/testThaliPeerAction.js    |  97 +++
 .../jxcore/bv_tests/testThaliPeerPoolInterface.js  |  87 +++
 .../bv_tests/testThaliReplicationUtilities.js      | 148 ++++
 .../testThaliSendNotificationBasedOnReplication.js | 665 ++++++++++++++++
 .../jxcore/bv_tests/testThaliWifiInfrastructure.js |  17 +
 test/www/jxcore/lib/httpTester.js                  |  23 +
 test/www/jxcore/lib/testUtils.js                   |  83 +-
 test/www/jxcore/lib/thali-tape.js                  | 173 +++--
 test/www/jxcore/lib/wifiBasedNativeMock.js         |  10 +-
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
 .../thaliSendNotificationBasedOnReplication.js     | 537 +++++++++++++
 thali/NextGeneration/replication/utilities.js      | 136 ++++
 thali/NextGeneration/{ => security}/hkdf.js        |   0
 .../NextGeneration/{ => security}/thaliACLLayer.js |   0
 thali/NextGeneration/thaliConfig.js                |   4 +
 thali/NextGeneration/thaliMobile.js                | 319 +++++---
 thali/NextGeneration/thaliMobileNative.js          |   4 +-
 thali/NextGeneration/thaliMobileNativeWrapper.js   |  45 +-
 thali/NextGeneration/thaliNotificationServer.js    |  89 ---
 .../{ => thaliPeerPool}/thaliPeerAction.js         | 122 ++-
 .../{ => thaliPeerPool}/thaliPeerPoolDefault.js    |   3 +
 .../{ => thaliPeerPool}/thaliPeerPoolInterface.js  |  55 +-
 thali/NextGeneration/thaliReplicationManager.js    |  10 +-
 .../thaliSendNotificationBasedOnReplication.js     | 184 -----
 thali/NextGeneration/thaliWifiInfrastructure.js    |  26 +-
 www/android/thaliPermissions.js                    | 108 +--
 68 files changed, 5290 insertions(+), 1860 deletions(-)
 rename src/android/java/io/jxcore/node/{PeerAndConnectionModel.java => ConnectionModel.java} (68%)
 delete mode 100644 src/android/java/io/jxcore/node/ConnectionStatusListener.java
 create mode 100644 src/android/java/io/jxcore/node/ConnectivityInfo.java
 delete mode 100644 src/android/java/io/jxcore/node/ConnectivityMonitor.java
 create mode 100644 src/android/java/io/jxcore/node/HandshakeHelper.java
 create mode 100644 src/android/java/io/jxcore/node/JXcoreThaliCallback.java
 delete mode 100644 src/android/java/io/jxcore/node/LifeCycleMonitor.java
 create mode 100644 src/android/java/io/jxcore/node/ListenerOrIncomingConnection.java
 create mode 100644 test/www/jxcore/bv_tests/testThaliNotificationServer.js
 create mode 100644 test/www/jxcore/bv_tests/testThaliPeerAction.js
 create mode 100644 test/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
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
 rename thali/NextGeneration/{ => thaliPeerPool}/thaliPeerAction.js (69%)
 rename thali/NextGeneration/{ => thaliPeerPool}/thaliPeerPoolDefault.js (94%)
 rename thali/NextGeneration/{ => thaliPeerPool}/thaliPeerPoolInterface.js (60%)
 delete mode 100644 thali/NextGeneration/thaliSendNotificationBasedOnReplication.js

Already on 'master'
Switched to a new branch 'vNext'
Note: checking out '0083d9b'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 0083d9b... Make the whole lastActive thing work

```

```


```

Error: Command failed: 