#### Test (Fail) 93987156 Build Logs


```


```

```
Updating d2b8f69..756cf20
Fast-forward
 BtConnectorLib/btconnectorlib2/build.gradle        |    2 +-
 .../p2p/btconnectorlib/ConnectionManager.java      |    5 +
 .../p2p/btconnectorlib/DiscoveryManager.java       |  141 ++++++------
 .../internal/bluetooth/BluetoothClientThread.java  |   62 ++++--
 .../internal/bluetooth/BluetoothConnector.java     |   10 +-
 .../internal/bluetooth/BluetoothManager.java       |   12 +-
 .../internal/bluetooth/BluetoothServerThread.java  |   19 +-
 .../internal/bluetooth/le/BleAdvertiser.java       |   88 ++++++--
 .../internal/bluetooth/le/BlePeerDiscoverer.java   |  228 ++++++++++++--------
 .../bluetooth/le/BlePeerDiscoveryUtils.java        |   49 +++--
 .../internal/bluetooth/le/BleScanner.java          |  103 ++++++---
 .../utils/BluetoothSocketIoThread.java             |    4 +
 .../p2p/btconnectorlib/utils/PeerModel.java        |    9 +-
 .../p2p/btconnectorlib/utils/ThreadUtils.java      |   22 ++
 .../internal/bluetooth/BluetoothConnectorTest.java |    1 +
 .../internal/bluetooth/le/BleAdvertiserTest.java   |    5 +
 .../internal/bluetooth/le/BleScannerTest.java      |    6 +
 .../p2p/btconnectorlib/utils/PeerModelTest.java    |    1 +
 BtConnectorLib/build.gradle                        |    2 +-
 BtConnectorLib/settings.gradle                     |    2 +-
 NativeTestApp/app/build.gradle                     |    2 +-
 .../nativetest/app/ConnectionEngine.java           |    4 +
 22 files changed, 515 insertions(+), 262 deletions(-)
 create mode 100644 BtConnectorLib/btconnectorlib2/src/main/java/org/thaliproject/p2p/btconnectorlib/utils/ThreadUtils.java

From https://github.com/thaliproject/Thali_CordovaPlugin_BtLibrary
   d2b8f69..756cf20  master     -> origin/master
 * [new branch]      evabishchevich_97 -> origin/evabishchevich_97
 * [new tag]         0.3.5      -> 0.3.5

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Already up-to-date.

Already on 'master'
Already on 'master'
Note: checking out '4b659b1'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 4b659b1... Inform listeners via main looper. Fixed #97

```

```
Downloading https://services.gradle.org/distributions/gradle-2.2.1-all.zip
..................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................
Unzipping /Users/thali/.gradle/wrapper/dists/gradle-2.2.1-all/6dibv5rcnnqlfbq9klf8imrndn/gradle-2.2.1-all.zip to /Users/thali/.gradle/wrapper/dists/gradle-2.2.1-all/6dibv5rcnnqlfbq9klf8imrndn
Set executable permissions for: /Users/thali/.gradle/wrapper/dists/gradle-2.2.1-all/6dibv5rcnnqlfbq9klf8imrndn/gradle-2.2.1/bin/gradle
Download https://jcenter.bintray.com/com/android/tools/build/gradle/1.1.2/gradle-1.1.2.pom
Download https://jcenter.bintray.com/com/github/dcendents/android-maven-plugin/1.2/android-maven-plugin-1.2.pom
Download https://jcenter.bintray.com/com/android/tools/build/gradle-core/1.1.2/gradle-core-1.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/build/builder/1.1.2/builder-1.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/lint/lint/24.1.2/lint-24.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/build/builder-model/1.1.2/builder-model-1.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/build/builder-test-api/1.1.2/builder-test-api-1.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/sdklib/24.1.2/sdklib-24.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/sdk-common/24.1.2/sdk-common-24.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/common/24.1.2/common-24.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/build/manifest-merger/24.1.2/manifest-merger-24.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/ddms/ddmlib/24.1.2/ddmlib-24.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/lint/lint-checks/24.1.2/lint-checks-24.1.2.pom
Download https://jcenter.bintray.com/org/eclipse/jdt/core/compiler/ecj/4.4/ecj-4.4.pom
Download https://jcenter.bintray.com/com/android/tools/annotations/24.1.2/annotations-24.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/layoutlib/layoutlib-api/24.1.2/layoutlib-api-24.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/dvlib/24.1.2/dvlib-24.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/lint/lint-api/24.1.2/lint-api-24.1.2.pom
Download https://jcenter.bintray.com/com/android/tools/build/gradle/1.1.2/gradle-1.1.2.jar
Download https://jcenter.bintray.com/com/github/dcendents/android-maven-plugin/1.2/android-maven-plugin-1.2.jar
Download https://jcenter.bintray.com/com/android/tools/build/gradle-core/1.1.2/gradle-core-1.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/build/builder/1.1.2/builder-1.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/lint/lint/24.1.2/lint-24.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/build/builder-model/1.1.2/builder-model-1.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/build/builder-test-api/1.1.2/builder-test-api-1.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/sdklib/24.1.2/sdklib-24.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/sdk-common/24.1.2/sdk-common-24.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/common/24.1.2/common-24.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/build/manifest-merger/24.1.2/manifest-merger-24.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/ddms/ddmlib/24.1.2/ddmlib-24.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/lint/lint-checks/24.1.2/lint-checks-24.1.2.jar
Download https://jcenter.bintray.com/org/eclipse/jdt/core/compiler/ecj/4.4/ecj-4.4.jar
Download https://jcenter.bintray.com/com/android/tools/annotations/24.1.2/annotations-24.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/layoutlib/layoutlib-api/24.1.2/layoutlib-api-24.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/dvlib/24.1.2/dvlib-24.1.2.jar
Download https://jcenter.bintray.com/com/android/tools/lint/lint-api/24.1.2/lint-api-24.1.2.jar

BUILD FAILED

Total time: 57.506 secs
-e [0;31mcompilation aborted
 [0m
./build.sh CI FAILED - build.sh failure[0m


FAILURE: Build failed with an exception.

* What went wrong:
A problem occurred configuring project ':btconnectorlib2'.
> failed to find Build Tools revision 23.0.3

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.

```

Error: Command failed: 
FAILURE: Build failed with an exception.

* What went wrong:
A problem occurred configuring project ':btconnectorlib2'.
> failed to find Build Tools revision 23.0.3

* Try:
Run with --stacktrace option to get the stack trace. Run with --info or --debug option to get more log output.
