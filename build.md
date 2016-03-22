#### Test (Fail) 63680118 Build Logs


```


```

```
Already up-to-date.


```

```
Your branch is up-to-date with 'origin/master'.
Branch vNext_vjrantal_500 set up to track remote branch vNext_vjrantal_500 from origin.
Auto-merging src/ios/MultipeerConnectivity/THEMultipeerManager.m
Auto-merging src/ios/MultipeerConnectivity/THEMultipeerClient.m
Removing src/android/java/io/jxcore/node/HandshakeHelper.java
Merge made by the 'recursive' strategy.
 appveyor.yml                                       |   2 +-
 build.sh                                           |   5 +-
 plugin.xml                                         |   2 +-
 src/android/JXcore.gradle                          |   2 +-
 .../java/io/jxcore/node/ConnectionHelper.java      |  99 ++---
 .../java/io/jxcore/node/ConnectionModel.java       |  24 +-
 .../java/io/jxcore/node/HandshakeHelper.java       | 362 -------------------
 .../java/io/jxcore/node/JXcoreExtension.java       |  23 ++
 .../java/io/jxcore/node/LifeCycleMonitor.java      | 137 +++++++
 .../java/io/jxcore/node/SocketThreadBase.java      |   3 +-
 src/ios/JXcoreExtension.m                          |  12 +-
 src/ios/MultipeerConnectivity/THEMultipeerClient.h |   2 +-
 src/ios/MultipeerConnectivity/THEMultipeerClient.m |   2 +-
 .../MultipeerConnectivity/THEMultipeerManager.h    |   2 +-
 .../MultipeerConnectivity/THEMultipeerManager.m    |   4 +-
 src/ios/THEAppContext.h                            |   2 +-
 src/ios/THEAppContext.m                            |   2 +-
 test/www/jxcore/UnitTest_app.js                    |  19 +-
 .../bv_tests/testThaliMobileNativeWrapper.js       | 400 +++++++++++++++------
 test/www/jxcore/lib/wifiBasedNativeMock.js         |  21 +-
 thali/NextGeneration/mux/createPeerListener.js     |   6 +-
 thali/NextGeneration/thaliMobileNativeWrapper.js   |  42 ++-
 22 files changed, 598 insertions(+), 575 deletions(-)
 delete mode 100644 src/android/java/io/jxcore/node/HandshakeHelper.java
 create mode 100644 src/android/java/io/jxcore/node/LifeCycleMonitor.java

Already on 'master'
Switched to a new branch 'vNext_vjrantal_500'
Note: checking out '508fffe'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 508fffe... Change data sending test to be x-platform

```

```


```

Error: Command failed: 