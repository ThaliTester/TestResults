#### Test (Success) 100332223 Build Logs


```


```

```
Updating 156f45b..8ff28b7
Fast-forward
 BtConnectorLib/btconnectorlib2/build.gradle        |    7 +-
 .../p2p/btconnectorlib/ConnectionManagerTest.java  |   79 +++----
 .../p2p/btconnectorlib/DiscoveryManagerTest.java   |   66 +++---
 .../p2p/btconnectorlib/ConnectionManager.java      |  100 ++++++---
 .../p2p/btconnectorlib/DiscoveryManager.java       |    9 +-
 .../btconnectorlib/DiscoveryManagerSettings.java   |   43 ++--
 .../p2p/btconnectorlib/PeerProperties.java         |  120 +++-------
 .../AbstractBluetoothConnectivityAgent.java        |  148 +++++-------
 .../internal/bluetooth/BluetoothClientThread.java  |    6 +-
 .../internal/bluetooth/BluetoothServerThread.java  |   42 ++--
 .../internal/bluetooth/BluetoothUtils.java         |   53 +++--
 .../internal/wifi/WifiServiceWatcher.java          |    9 +-
 .../utils/BluetoothSocketIoThread.java             |   32 +--
 .../p2p/btconnectorlib/utils/PeerModel.java        |    1 -
 .../ConnectionManagerSettingsTest.java             |   18 +-
 .../p2p/btconnectorlib/ConnectionManagerTest.java  |   13 ++
 .../p2p/btconnectorlib/DiscoveryManagerTest.java   |    8 +-
 .../p2p/btconnectorlib/PeerPropertiesTest.java     |  235 ++++++--------------
 BtConnectorLib/build.gradle                        |    4 +-
 .../gradle/wrapper/gradle-wrapper.properties       |    4 +-
 BtConnectorLib/settings.gradle                     |    2 +-
 21 files changed, 452 insertions(+), 547 deletions(-)

From https://github.com/thaliproject/Thali_CordovaPlugin_BtLibrary
   156f45b..8ff28b7  master     -> origin/master
 * [new branch]      evabishchevich_105 -> origin/evabishchevich_105
 * [new branch]      evabishchevich_1569 -> origin/evabishchevich_1569

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Already up-to-date.

Already on 'master'
Already on 'master'
Note: checking out 'fa010d0'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at fa010d0... Refactor run method

```

```
Downloading https://services.gradle.org/distributions/gradle-2.14.1-all.zip
...........................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................................
Unzipping /Users/thali/.gradle/wrapper/dists/gradle-2.14.1-all/4cj8p00t3e5ni9e8iofg8ghvk7/gradle-2.14.1-all.zip to /Users/thali/.gradle/wrapper/dists/gradle-2.14.1-all/4cj8p00t3e5ni9e8iofg8ghvk7
Set executable permissions for: /Users/thali/.gradle/wrapper/dists/gradle-2.14.1-all/4cj8p00t3e5ni9e8iofg8ghvk7/gradle-2.14.1/bin/gradle
Download https://jcenter.bintray.com/com/android/tools/build/gradle/2.2.3/gradle-2.2.3.pom
Download https://jcenter.bintray.com/com/github/dcendents/android-maven-gradle-plugin/1.4.1/android-maven-gradle-plugin-1.4.1.pom
Download https://jcenter.bintray.com/com/android/tools/build/gradle-core/2.2.3/gradle-core-2.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/build/builder/2.2.3/builder-2.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/lint/lint/25.2.3/lint-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/build/gradle-api/2.2.3/gradle-api-2.2.3.pom
Download https://jcenter.bintray.com/com/android/databinding/compilerCommon/2.2.3/compilerCommon-2.2.3.pom
Download https://jcenter.bintray.com/org/ow2/asm/asm/5.0.4/asm-5.0.4.pom
Download https://jcenter.bintray.com/org/ow2/asm/asm-parent/5.0.4/asm-parent-5.0.4.pom
Download https://jcenter.bintray.com/org/ow2/asm/asm-commons/5.0.4/asm-commons-5.0.4.pom
Download https://jcenter.bintray.com/org/jacoco/org.jacoco.core/0.7.5.201505241946/org.jacoco.core-0.7.5.201505241946.pom
Download https://jcenter.bintray.com/org/jacoco/org.jacoco.build/0.7.5.201505241946/org.jacoco.build-0.7.5.201505241946.pom
Download https://jcenter.bintray.com/org/jacoco/org.jacoco.report/0.7.5.201505241946/org.jacoco.report-0.7.5.201505241946.pom
Download https://jcenter.bintray.com/net/sf/jopt-simple/jopt-simple/4.9/jopt-simple-4.9.pom
Download https://jcenter.bintray.com/com/google/protobuf/protobuf-java/2.5.0/protobuf-java-2.5.0.pom
Download https://jcenter.bintray.com/com/google/google/1/google-1.pom
Download https://jcenter.bintray.com/com/android/tools/build/builder-model/2.2.3/builder-model-2.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/build/builder-test-api/2.2.3/builder-test-api-2.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/sdklib/25.2.3/sdklib-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/sdk-common/25.2.3/sdk-common-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/common/25.2.3/common-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/build/manifest-merger/25.2.3/manifest-merger-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/ddms/ddmlib/25.2.3/ddmlib-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/jack/jack-api/0.11.0/jack-api-0.11.0.pom
Download https://jcenter.bintray.com/com/android/tools/analytics-library/protos/25.2.3/protos-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/analytics-library/shared/25.2.3/shared-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/analytics-library/tracker/25.2.3/tracker-25.2.3.pom
Download https://jcenter.bintray.com/org/ow2/asm/asm-tree/5.0.4/asm-tree-5.0.4.pom
Download https://jcenter.bintray.com/com/android/tools/lint/lint-checks/25.2.3/lint-checks-25.2.3.pom
Download https://jcenter.bintray.com/org/eclipse/jdt/core/compiler/ecj/4.5.1/ecj-4.5.1.pom
Download https://jcenter.bintray.com/com/android/databinding/baseLibrary/2.2.3/baseLibrary-2.2.3.pom
Download https://jcenter.bintray.com/org/antlr/antlr4/4.5.3/antlr4-4.5.3.pom
Download https://jcenter.bintray.com/org/antlr/antlr4-master/4.5.3/antlr4-master-4.5.3.pom
Download https://jcenter.bintray.com/com/android/tools/layoutlib/layoutlib-api/25.2.3/layoutlib-api-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/dvlib/25.2.3/dvlib-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/repository/25.2.3/repository-25.2.3.pom
Download https://jcenter.bintray.com/com/android/tools/lint/lint-api/25.2.3/lint-api-25.2.3.pom
Download https://jcenter.bintray.com/org/ow2/asm/asm-analysis/5.0.4/asm-analysis-5.0.4.pom
Download https://jcenter.bintray.com/com/google/jimfs/jimfs/1.1/jimfs-1.1.pom
Download https://jcenter.bintray.com/com/google/jimfs/jimfs-parent/1.1/jimfs-parent-1.1.pom
Download https://jcenter.bintray.com/com/android/tools/external/com-intellij/uast/145.597.4/uast-145.597.4.pom
Download https://jcenter.bintray.com/com/android/tools/annotations/25.2.3/annotations-25.2.3.pom
Download https://jcenter.bintray.com/com/google/guava/guava/18.0/guava-18.0.pom
Download https://jcenter.bintray.com/com/google/guava/guava-parent/18.0/guava-parent-18.0.pom
Download https://jcenter.bintray.com/com/android/tools/build/gradle/2.2.3/gradle-2.2.3.jar
Download https://jcenter.bintray.com/com/github/dcendents/android-maven-gradle-plugin/1.4.1/android-maven-gradle-plugin-1.4.1.jar
Download https://jcenter.bintray.com/com/android/tools/build/gradle-core/2.2.3/gradle-core-2.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/build/builder/2.2.3/builder-2.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/lint/lint/25.2.3/lint-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/build/gradle-api/2.2.3/gradle-api-2.2.3.jar
Download https://jcenter.bintray.com/com/android/databinding/compilerCommon/2.2.3/compilerCommon-2.2.3.jar
Download https://jcenter.bintray.com/org/ow2/asm/asm/5.0.4/asm-5.0.4.jar
Download https://jcenter.bintray.com/org/ow2/asm/asm-commons/5.0.4/asm-commons-5.0.4.jar
Download https://jcenter.bintray.com/org/jacoco/org.jacoco.core/0.7.5.201505241946/org.jacoco.core-0.7.5.201505241946.jar
Download https://jcenter.bintray.com/org/jacoco/org.jacoco.report/0.7.5.201505241946/org.jacoco.report-0.7.5.201505241946.jar
Download https://jcenter.bintray.com/net/sf/jopt-simple/jopt-simple/4.9/jopt-simple-4.9.jar
Download https://jcenter.bintray.com/com/google/protobuf/protobuf-java/2.5.0/protobuf-java-2.5.0.jar
Download https://jcenter.bintray.com/com/android/tools/build/builder-model/2.2.3/builder-model-2.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/build/builder-test-api/2.2.3/builder-test-api-2.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/sdklib/25.2.3/sdklib-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/sdk-common/25.2.3/sdk-common-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/common/25.2.3/common-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/build/manifest-merger/25.2.3/manifest-merger-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/ddms/ddmlib/25.2.3/ddmlib-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/jack/jack-api/0.11.0/jack-api-0.11.0.jar
Download https://jcenter.bintray.com/com/android/tools/analytics-library/protos/25.2.3/protos-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/analytics-library/shared/25.2.3/shared-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/analytics-library/tracker/25.2.3/tracker-25.2.3.jar
Download https://jcenter.bintray.com/org/ow2/asm/asm-tree/5.0.4/asm-tree-5.0.4.jar
Download https://jcenter.bintray.com/com/android/tools/lint/lint-checks/25.2.3/lint-checks-25.2.3.jar
Download https://jcenter.bintray.com/org/eclipse/jdt/core/compiler/ecj/4.5.1/ecj-4.5.1.jar
Download https://jcenter.bintray.com/com/android/databinding/baseLibrary/2.2.3/baseLibrary-2.2.3.jar
Download https://jcenter.bintray.com/org/antlr/antlr4/4.5.3/antlr4-4.5.3.jar
Download https://jcenter.bintray.com/com/android/tools/layoutlib/layoutlib-api/25.2.3/layoutlib-api-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/dvlib/25.2.3/dvlib-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/repository/25.2.3/repository-25.2.3.jar
Download https://jcenter.bintray.com/com/android/tools/lint/lint-api/25.2.3/lint-api-25.2.3.jar
Download https://jcenter.bintray.com/org/ow2/asm/asm-analysis/5.0.4/asm-analysis-5.0.4.jar
Download https://jcenter.bintray.com/com/google/jimfs/jimfs/1.1/jimfs-1.1.jar
Download https://jcenter.bintray.com/com/android/tools/external/com-intellij/uast/145.597.4/uast-145.597.4.jar
Download https://jcenter.bintray.com/com/android/tools/annotations/25.2.3/annotations-25.2.3.jar
Download https://jcenter.bintray.com/com/google/guava/guava/18.0/guava-18.0.jar
Incremental java compilation is an incubating feature.
Download https://jcenter.bintray.com/org/mockito/mockito-core/1.9.5/mockito-core-1.9.5.pom
Download https://jcenter.bintray.com/org/objenesis/objenesis/1.0/objenesis-1.0.pom
Download https://jcenter.bintray.com/org/objenesis/objenesis/1.0/objenesis-1.0.jar
Download https://jcenter.bintray.com/org/mockito/mockito-core/1.9.5/mockito-core-1.9.5.jar
Download https://jcenter.bintray.com/com/google/dexmaker/dexmaker/1.2/dexmaker-1.2.pom
Download https://jcenter.bintray.com/com/google/dexmaker/dexmaker-parent/1.2/dexmaker-parent-1.2.pom
Download https://jcenter.bintray.com/com/google/dexmaker/dexmaker-mockito/1.2/dexmaker-mockito-1.2.pom
Download https://jcenter.bintray.com/com/google/dexmaker/dexmaker/1.2/dexmaker-1.2.jar
Download https://jcenter.bintray.com/com/google/dexmaker/dexmaker-mockito/1.2/dexmaker-mockito-1.2.jar
:btconnectorlib2:preBuild UP-TO-DATE
:btconnectorlib2:preReleaseBuild UP-TO-DATE
:btconnectorlib2:checkReleaseManifest
:btconnectorlib2:preDebugBuild UP-TO-DATE
:btconnectorlib2:preDebugUnitTestBuild UP-TO-DATE
:btconnectorlib2:preReleaseAndroidTestBuild UP-TO-DATE
:btconnectorlib2:preReleaseUnitTestBuild UP-TO-DATE
:btconnectorlib2:prepareComAndroidSupportAppcompatV72311Library
:btconnectorlib2:prepareComAndroidSupportSupportV42311Library
:btconnectorlib2:prepareReleaseDependencies
:btconnectorlib2:compileReleaseAidl
:btconnectorlib2:compileReleaseNdk UP-TO-DATE
:btconnectorlib2:compileLint
:btconnectorlib2:copyReleaseLint UP-TO-DATE
:btconnectorlib2:compileReleaseRenderscript
:btconnectorlib2:generateReleaseBuildConfig
:btconnectorlib2:generateReleaseResValues
:btconnectorlib2:generateReleaseResources
:btconnectorlib2:mergeReleaseResources
:btconnectorlib2:processReleaseManifest
:btconnectorlib2:processReleaseResources
:btconnectorlib2:generateReleaseSources
:btconnectorlib2:incrementalReleaseJavaCompilationSafeguard
:btconnectorlib2:compileReleaseJavaWithJavac
:btconnectorlib2:compileReleaseJavaWithJavac - is not incremental (e.g. outputs have changed, no previous execution, etc.).
:btconnectorlib2:extractReleaseAnnotations
:btconnectorlib2:mergeReleaseShaders
:btconnectorlib2:compileReleaseShaders
:btconnectorlib2:generateReleaseAssets
:btconnectorlib2:mergeReleaseAssets
:btconnectorlib2:mergeReleaseProguardFiles
:btconnectorlib2:packageReleaseRenderscript UP-TO-DATE
:btconnectorlib2:packageReleaseResources
:btconnectorlib2:processReleaseJavaRes UP-TO-DATE
:btconnectorlib2:transformResourcesWithMergeJavaResForRelease
:btconnectorlib2:transformClassesAndResourcesWithSyncLibJarsForRelease
:btconnectorlib2:mergeReleaseJniLibFolders
:btconnectorlib2:transformNative_libsWithMergeJniLibsForRelease
:btconnectorlib2:transformNative_libsWithSyncJniLibsForRelease
:btconnectorlib2:bundleRelease
:btconnectorlib2:compileReleaseSources
:btconnectorlib2:assembleRelease

BUILD SUCCESSFUL

Total time: 1 mins 17.11 secs

This build could be faster, please consider using the Gradle Daemon: https://docs.gradle.org/2.14.1/userguide/gradle_daemon.html
Incremental java compilation is an incubating feature.
:btconnectorlib2:preBuild UP-TO-DATE
:btconnectorlib2:preReleaseBuild UP-TO-DATE
:btconnectorlib2:checkReleaseManifest
:btconnectorlib2:preDebugBuild UP-TO-DATE
:btconnectorlib2:preDebugUnitTestBuild UP-TO-DATE
:btconnectorlib2:preReleaseAndroidTestBuild UP-TO-DATE
:btconnectorlib2:preReleaseUnitTestBuild UP-TO-DATE
:btconnectorlib2:prepareComAndroidSupportAppcompatV72311Library UP-TO-DATE
:btconnectorlib2:prepareComAndroidSupportSupportV42311Library UP-TO-DATE
:btconnectorlib2:prepareReleaseDependencies
:btconnectorlib2:compileReleaseAidl UP-TO-DATE
:btconnectorlib2:compileReleaseRenderscript UP-TO-DATE
:btconnectorlib2:generateReleaseBuildConfig UP-TO-DATE
:btconnectorlib2:generateReleaseResValues UP-TO-DATE
:btconnectorlib2:generateReleaseResources UP-TO-DATE
:btconnectorlib2:mergeReleaseResources UP-TO-DATE
:btconnectorlib2:processReleaseManifest UP-TO-DATE
:btconnectorlib2:processReleaseResources UP-TO-DATE
:btconnectorlib2:generateReleaseSources UP-TO-DATE
:btconnectorlib2:incrementalReleaseJavaCompilationSafeguard UP-TO-DATE
:btconnectorlib2:compileReleaseJavaWithJavac UP-TO-DATE
:btconnectorlib2:prepareComAndroidSupportTestExposedInstrumentationApiPublish05Library
:btconnectorlib2:prepareComAndroidSupportTestRules05Library
:btconnectorlib2:prepareComAndroidSupportTestRunner05Library
:btconnectorlib2:prepareReleaseAndroidTestDependencies
:btconnectorlib2:compileReleaseAndroidTestAidl
:btconnectorlib2:compileReleaseNdk UP-TO-DATE
:btconnectorlib2:compileLint UP-TO-DATE
:btconnectorlib2:copyReleaseLint UP-TO-DATE
:btconnectorlib2:extractReleaseAnnotations UP-TO-DATE
:btconnectorlib2:mergeReleaseShaders UP-TO-DATE
:btconnectorlib2:compileReleaseShaders UP-TO-DATE
:btconnectorlib2:generateReleaseAssets UP-TO-DATE
:btconnectorlib2:mergeReleaseAssets UP-TO-DATE
:btconnectorlib2:mergeReleaseProguardFiles UP-TO-DATE
:btconnectorlib2:packageReleaseRenderscript UP-TO-DATE
:btconnectorlib2:packageReleaseResources UP-TO-DATE
:btconnectorlib2:processReleaseJavaRes UP-TO-DATE
:btconnectorlib2:transformResourcesWithMergeJavaResForRelease UP-TO-DATE
:btconnectorlib2:transformClassesAndResourcesWithSyncLibJarsForRelease UP-TO-DATE
:btconnectorlib2:mergeReleaseJniLibFolders UP-TO-DATE
:btconnectorlib2:transformNative_libsWithMergeJniLibsForRelease UP-TO-DATE
:btconnectorlib2:transformNative_libsWithSyncJniLibsForRelease UP-TO-DATE
:btconnectorlib2:bundleRelease UP-TO-DATE
:btconnectorlib2:processReleaseAndroidTestManifest
:btconnectorlib2:compileReleaseAndroidTestRenderscript
:btconnectorlib2:generateReleaseAndroidTestBuildConfig
:btconnectorlib2:generateReleaseAndroidTestResValues
:btconnectorlib2:generateReleaseAndroidTestResources
:btconnectorlib2:mergeReleaseAndroidTestResources
:btconnectorlib2:processReleaseAndroidTestResources
:btconnectorlib2:generateReleaseAndroidTestSources
:btconnectorlib2:incrementalReleaseAndroidTestJavaCompilationSafeguard
:btconnectorlib2:compileReleaseAndroidTestJavaWithJavac
:btconnectorlib2:compileReleaseAndroidTestNdk UP-TO-DATE
:btconnectorlib2:compileReleaseAndroidTestSources
:btconnectorlib2:lintVitalReleaseAndroidTest
:btconnectorlib2:mergeReleaseAndroidTestShaders
:btconnectorlib2:compileReleaseAndroidTestShaders
:btconnectorlib2:generateReleaseAndroidTestAssets
:btconnectorlib2:mergeReleaseAndroidTestAssets
:btconnectorlib2:transformClassesWithDexForReleaseAndroidTest
:btconnectorlib2:mergeReleaseAndroidTestJniLibFolders
:btconnectorlib2:transformNative_libsWithMergeJniLibsForReleaseAndroidTest
:btconnectorlib2:processReleaseAndroidTestJavaRes UP-TO-DATE
:btconnectorlib2:transformResourcesWithMergeJavaResForReleaseAndroidTest
:btconnectorlib2:packageReleaseAndroidTest
:btconnectorlib2:assembleReleaseAndroidTest

BUILD SUCCESSFUL

Total time: 34.5 secs

This build could be faster, please consider using the Gradle Daemon: https://docs.gradle.org/2.14.1/userguide/gradle_daemon.html
Incremental java compilation is an incubating feature.
:btconnectorlib2:preBuild UP-TO-DATE
:btconnectorlib2:preReleaseBuild UP-TO-DATE
:btconnectorlib2:checkReleaseManifest
:btconnectorlib2:preDebugBuild UP-TO-DATE
:btconnectorlib2:preDebugUnitTestBuild UP-TO-DATE
:btconnectorlib2:preReleaseAndroidTestBuild UP-TO-DATE
:btconnectorlib2:preReleaseUnitTestBuild UP-TO-DATE
:btconnectorlib2:prepareComAndroidSupportAppcompatV72311Library UP-TO-DATE
:btconnectorlib2:prepareComAndroidSupportSupportV42311Library UP-TO-DATE
:btconnectorlib2:prepareReleaseDependencies
:btconnectorlib2:compileReleaseAidl UP-TO-DATE
:btconnectorlib2:compileReleaseRenderscript UP-TO-DATE
:btconnectorlib2:generateReleaseBuildConfig UP-TO-DATE
:btconnectorlib2:generateReleaseResValues UP-TO-DATE
:btconnectorlib2:generateReleaseResources UP-TO-DATE
:btconnectorlib2:mergeReleaseResources UP-TO-DATE
:btconnectorlib2:processReleaseManifest UP-TO-DATE
:btconnectorlib2:processReleaseResources UP-TO-DATE
:btconnectorlib2:generateReleaseSources UP-TO-DATE
:btconnectorlib2:incrementalReleaseJavaCompilationSafeguard UP-TO-DATE
:btconnectorlib2:compileReleaseJavaWithJavac UP-TO-DATE
:btconnectorlib2:incrementalReleaseUnitTestJavaCompilationSafeguard UP-TO-DATE
:btconnectorlib2:prepareReleaseUnitTestDependencies
:btconnectorlib2:compileReleaseUnitTestJavaWithJavac
:btconnectorlib2:processReleaseJavaRes UP-TO-DATE
:btconnectorlib2:processReleaseUnitTestJavaRes UP-TO-DATE
:btconnectorlib2:compileReleaseUnitTestSources
:btconnectorlib2:mockableAndroidJar
:btconnectorlib2:assembleReleaseUnitTest
:btconnectorlib2:testReleaseUnitTest

BUILD SUCCESSFUL

Total time: 29.782 secs

This build could be faster, please consider using the Gradle Daemon: https://docs.gradle.org/2.14.1/userguide/gradle_daemon.html

Note: Some input files use unchecked or unsafe operations.
Note: Recompile with -Xlint:unchecked for details.

```

```
 updating: META-INF/MANIFEST.MF
   adding: META-INF/ALIAS_NA.SF
   adding: META-INF/ALIAS_NA.RSA
  signing: AndroidManifest.xml
  signing: LICENSE-junit.txt
  signing: asm-license.txt
  signing: cglib-license.txt
  signing: classes.dex
  signing: junit/runner/logo.gif
  signing: junit/runner/smalllogo.gif
  signing: mockito-extensions/org.mockito.plugins.MockMaker
  signing: mockito-extensions/org.mockito.plugins.StackTraceCleanerProvider
  signing: org/mockito/internal/creation/jmock/jmock-license.txt
  signing: org/mockito/internal/matchers/apachecommons/commons-lang-license.txt
  signing: res/anim/abc_fade_in.xml
  signing: res/anim/abc_fade_out.xml
  signing: res/anim/abc_grow_fade_in_from_bottom.xml
  signing: res/anim/abc_popup_enter.xml
  signing: res/anim/abc_popup_exit.xml
  signing: res/anim/abc_shrink_fade_out_from_bottom.xml
  signing: res/anim/abc_slide_in_bottom.xml
  signing: res/anim/abc_slide_in_top.xml
  signing: res/anim/abc_slide_out_bottom.xml
  signing: res/anim/abc_slide_out_top.xml
  signing: res/color-v11/abc_background_cache_hint_selector_material_dark.xml
  signing: res/color-v11/abc_background_cache_hint_selector_material_light.xml
  signing: res/color-v23/abc_color_highlight_material.xml
  signing: res/color/abc_primary_text_disable_only_material_dark.xml
  signing: res/color/abc_primary_text_disable_only_material_light.xml
  signing: res/color/abc_primary_text_material_dark.xml
  signing: res/color/abc_primary_text_material_light.xml
  signing: res/color/abc_search_url_text.xml
  signing: res/color/abc_secondary_text_material_dark.xml
  signing: res/color/abc_secondary_text_material_light.xml
  signing: res/color/switch_thumb_material_dark.xml
  signing: res/color/switch_thumb_material_light.xml
  signing: res/drawable-hdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_btn_check_to_on_mtrl_000.png
  signing: res/drawable-hdpi-v4/abc_btn_check_to_on_mtrl_015.png
  signing: res/drawable-hdpi-v4/abc_btn_radio_to_on_mtrl_000.png
  signing: res/drawable-hdpi-v4/abc_btn_radio_to_on_mtrl_015.png
  signing: res/drawable-hdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png
  signing: res/drawable-hdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png
  signing: res/drawable-hdpi-v4/abc_cab_background_top_mtrl_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_clear_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_go_search_api_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_menu_share_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_search_api_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_list_divider_mtrl_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_list_focused_holo.9.png
  signing: res/drawable-hdpi-v4/abc_list_longpressed_holo.9.png
  signing: res/drawable-hdpi-v4/abc_list_pressed_holo_dark.9.png
  signing: res/drawable-hdpi-v4/abc_list_pressed_holo_light.9.png
  signing: res/drawable-hdpi-v4/abc_list_selector_disabled_holo_dark.9.png
  signing: res/drawable-hdpi-v4/abc_list_selector_disabled_holo_light.9.png
  signing: res/drawable-hdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png
  signing: res/drawable-hdpi-v4/abc_popup_background_mtrl_mult.9.png
  signing: res/drawable-hdpi-v4/abc_scrubber_control_off_mtrl_alpha.png
  signing: res/drawable-hdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png
  signing: res/drawable-hdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png
  signing: res/drawable-hdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_scrubber_track_mtrl_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_switch_track_mtrl_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_tab_indicator_mtrl_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_textfield_activated_mtrl_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_textfield_default_mtrl_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png
  signing: res/drawable-hdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png
  signing: res/drawable-ldrtl-hdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-hdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-hdpi-v4/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-ldrtl-hdpi-v4/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-ldrtl-mdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-mdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-mdpi-v4/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-ldrtl-mdpi-v4/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-ldrtl-xhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-ldrtl-xhdpi-v4/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-ldrtl-xxhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xxhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xxhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-ldrtl-xxhdpi-v4/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-ldrtl-xxxhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xxxhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xxxhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-ldrtl-xxxhdpi-v4/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_btn_check_to_on_mtrl_000.png
  signing: res/drawable-mdpi-v4/abc_btn_check_to_on_mtrl_015.png
  signing: res/drawable-mdpi-v4/abc_btn_radio_to_on_mtrl_000.png
  signing: res/drawable-mdpi-v4/abc_btn_radio_to_on_mtrl_015.png
  signing: res/drawable-mdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png
  signing: res/drawable-mdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png
  signing: res/drawable-mdpi-v4/abc_cab_background_top_mtrl_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_clear_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_go_search_api_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_menu_share_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_search_api_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_list_divider_mtrl_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_list_focused_holo.9.png
  signing: res/drawable-mdpi-v4/abc_list_longpressed_holo.9.png
  signing: res/drawable-mdpi-v4/abc_list_pressed_holo_dark.9.png
  signing: res/drawable-mdpi-v4/abc_list_pressed_holo_light.9.png
  signing: res/drawable-mdpi-v4/abc_list_selector_disabled_holo_dark.9.png
  signing: res/drawable-mdpi-v4/abc_list_selector_disabled_holo_light.9.png
  signing: res/drawable-mdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png
  signing: res/drawable-mdpi-v4/abc_popup_background_mtrl_mult.9.png
  signing: res/drawable-mdpi-v4/abc_scrubber_control_off_mtrl_alpha.png
  signing: res/drawable-mdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png
  signing: res/drawable-mdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png
  signing: res/drawable-mdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_scrubber_track_mtrl_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_switch_track_mtrl_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_tab_indicator_mtrl_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_textfield_activated_mtrl_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_textfield_default_mtrl_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png
  signing: res/drawable-mdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png
  signing: res/drawable-v21/abc_action_bar_item_background_material.xml
  signing: res/drawable-v21/abc_btn_colored_material.xml
  signing: res/drawable-v23/abc_control_background_material.xml
  signing: res/drawable-xhdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_btn_check_to_on_mtrl_000.png
  signing: res/drawable-xhdpi-v4/abc_btn_check_to_on_mtrl_015.png
  signing: res/drawable-xhdpi-v4/abc_btn_radio_to_on_mtrl_000.png
  signing: res/drawable-xhdpi-v4/abc_btn_radio_to_on_mtrl_015.png
  signing: res/drawable-xhdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png
  signing: res/drawable-xhdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png
  signing: res/drawable-xhdpi-v4/abc_cab_background_top_mtrl_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_clear_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_go_search_api_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_menu_share_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_search_api_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_list_divider_mtrl_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_list_focused_holo.9.png
  signing: res/drawable-xhdpi-v4/abc_list_longpressed_holo.9.png
  signing: res/drawable-xhdpi-v4/abc_list_pressed_holo_dark.9.png
  signing: res/drawable-xhdpi-v4/abc_list_pressed_holo_light.9.png
  signing: res/drawable-xhdpi-v4/abc_list_selector_disabled_holo_dark.9.png
  signing: res/drawable-xhdpi-v4/abc_list_selector_disabled_holo_light.9.png
  signing: res/drawable-xhdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png
  signing: res/drawable-xhdpi-v4/abc_popup_background_mtrl_mult.9.png
  signing: res/drawable-xhdpi-v4/abc_scrubber_control_off_mtrl_alpha.png
  signing: res/drawable-xhdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png
  signing: res/drawable-xhdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png
  signing: res/drawable-xhdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_scrubber_track_mtrl_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_switch_track_mtrl_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_tab_indicator_mtrl_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_textfield_activated_mtrl_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_textfield_default_mtrl_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png
  signing: res/drawable-xhdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_btn_check_to_on_mtrl_000.png
  signing: res/drawable-xxhdpi-v4/abc_btn_check_to_on_mtrl_015.png
  signing: res/drawable-xxhdpi-v4/abc_btn_radio_to_on_mtrl_000.png
  signing: res/drawable-xxhdpi-v4/abc_btn_radio_to_on_mtrl_015.png
  signing: res/drawable-xxhdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png
  signing: res/drawable-xxhdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png
  signing: res/drawable-xxhdpi-v4/abc_cab_background_top_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_clear_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_go_search_api_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_menu_share_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_search_api_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_list_divider_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_list_focused_holo.9.png
  signing: res/drawable-xxhdpi-v4/abc_list_longpressed_holo.9.png
  signing: res/drawable-xxhdpi-v4/abc_list_pressed_holo_dark.9.png
  signing: res/drawable-xxhdpi-v4/abc_list_pressed_holo_light.9.png
  signing: res/drawable-xxhdpi-v4/abc_list_selector_disabled_holo_dark.9.png
  signing: res/drawable-xxhdpi-v4/abc_list_selector_disabled_holo_light.9.png
  signing: res/drawable-xxhdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png
  signing: res/drawable-xxhdpi-v4/abc_popup_background_mtrl_mult.9.png
  signing: res/drawable-xxhdpi-v4/abc_scrubber_control_off_mtrl_alpha.png
  signing: res/drawable-xxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png
  signing: res/drawable-xxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png
  signing: res/drawable-xxhdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_scrubber_track_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_switch_track_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_tab_indicator_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_textfield_activated_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_textfield_default_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png
  signing: res/drawable-xxhdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png
  signing: res/drawable-xxxhdpi-v4/abc_btn_check_to_on_mtrl_000.png
  signing: res/drawable-xxxhdpi-v4/abc_btn_check_to_on_mtrl_015.png
  signing: res/drawable-xxxhdpi-v4/abc_btn_radio_to_on_mtrl_000.png
  signing: res/drawable-xxxhdpi-v4/abc_btn_radio_to_on_mtrl_015.png
  signing: res/drawable-xxxhdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png
  signing: res/drawable-xxxhdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png
  signing: res/drawable-xxxhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-xxxhdpi-v4/abc_ic_clear_mtrl_alpha.png
  signing: res/drawable-xxxhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-xxxhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-xxxhdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png
  signing: res/drawable-xxxhdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png
  signing: res/drawable-xxxhdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png
  signing: res/drawable-xxxhdpi-v4/abc_ic_menu_share_mtrl_alpha.png
  signing: res/drawable-xxxhdpi-v4/abc_ic_search_api_mtrl_alpha.png
  signing: res/drawable-xxxhdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png
  signing: res/drawable-xxxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png
  signing: res/drawable-xxxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png
  signing: res/drawable-xxxhdpi-v4/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-xxxhdpi-v4/abc_switch_track_mtrl_alpha.9.png
  signing: res/drawable-xxxhdpi-v4/abc_tab_indicator_mtrl_alpha.9.png
  signing: res/drawable/abc_btn_borderless_material.xml
  signing: res/drawable/abc_btn_check_material.xml
  signing: res/drawable/abc_btn_default_mtrl_shape.xml
  signing: res/drawable/abc_btn_radio_material.xml
  signing: res/drawable/abc_cab_background_internal_bg.xml
  signing: res/drawable/abc_cab_background_top_material.xml
  signing: res/drawable/abc_dialog_material_background_dark.xml
  signing: res/drawable/abc_dialog_material_background_light.xml
  signing: res/drawable/abc_edit_text_material.xml
  signing: res/drawable/abc_item_background_holo_dark.xml
  signing: res/drawable/abc_item_background_holo_light.xml
  signing: res/drawable/abc_list_selector_background_transition_holo_dark.xml
  signing: res/drawable/abc_list_selector_background_transition_holo_light.xml
  signing: res/drawable/abc_list_selector_holo_dark.xml
  signing: res/drawable/abc_list_selector_holo_light.xml
  signing: res/drawable/abc_ratingbar_full_material.xml
  signing: res/drawable/abc_seekbar_thumb_material.xml
  signing: res/drawable/abc_seekbar_track_material.xml
  signing: res/drawable/abc_spinner_textfield_background_material.xml
  signing: res/drawable/abc_switch_thumb_material.xml
  signing: res/drawable/abc_tab_indicator_material.xml
  signing: res/drawable/abc_text_cursor_material.xml
  signing: res/drawable/abc_textfield_search_material.xml
  signing: res/layout/abc_action_bar_title_item.xml
  signing: res/layout/abc_action_bar_up_container.xml
  signing: res/layout/abc_action_bar_view_list_nav_layout.xml
  signing: res/layout/abc_action_menu_item_layout.xml
  signing: res/layout/abc_action_menu_layout.xml
  signing: res/layout/abc_action_mode_bar.xml
  signing: res/layout/abc_action_mode_close_item_material.xml
  signing: res/layout/abc_activity_chooser_view.xml
  signing: res/layout/abc_activity_chooser_view_list_item.xml
  signing: res/layout/abc_alert_dialog_button_bar_material.xml
  signing: res/layout/abc_alert_dialog_material.xml
  signing: res/layout/abc_dialog_title_material.xml
  signing: res/layout/abc_expanded_menu_layout.xml
  signing: res/layout/abc_list_menu_item_checkbox.xml
  signing: res/layout/abc_list_menu_item_icon.xml
  signing: res/layout/abc_list_menu_item_layout.xml
  signing: res/layout/abc_list_menu_item_radio.xml
  signing: res/layout/abc_popup_menu_item_layout.xml
  signing: res/layout/abc_screen_content_include.xml
  signing: res/layout/abc_screen_simple.xml
  signing: res/layout/abc_screen_simple_overlay_action_mode.xml
  signing: res/layout/abc_screen_toolbar.xml
  signing: res/layout/abc_search_dropdown_item_icons_2line.xml
  signing: res/layout/abc_search_view.xml
  signing: res/layout/abc_select_dialog_material.xml
  signing: res/layout/notification_media_action.xml
  signing: res/layout/notification_media_cancel_action.xml
  signing: res/layout/notification_template_big_media.xml
  signing: res/layout/notification_template_big_media_narrow.xml
  signing: res/layout/notification_template_lines.xml
  signing: res/layout/notification_template_media.xml
  signing: res/layout/notification_template_part_chronometer.xml
  signing: res/layout/notification_template_part_time.xml
  signing: res/layout/select_dialog_item_material.xml
  signing: res/layout/select_dialog_multichoice_material.xml
  signing: res/layout/select_dialog_singlechoice_material.xml
  signing: res/layout/support_simple_spinner_dropdown_item.xml
  signing: resources.arsc
jar signed.

Warning: 
No -tsa or -tsacert is provided and this jar is not timestamped. Without a timestamp, users may not be able to validate this jar after the signer certificate's expiration date (2043-01-05) or after any future revocation date.
Verifying alignment of android.apk (4)...
      50 META-INF/MANIFEST.MF (OK - compressed)
    9679 META-INF/ALIAS_NA.SF (OK - compressed)
   19437 META-INF/ALIAS_NA.RSA (OK - compressed)
   20528 AndroidManifest.xml (OK - compressed)
   21615 LICENSE-junit.txt (OK - compressed)
   25867 asm-license.txt (OK - compressed)
   26751 cglib-license.txt (OK - compressed)
   30764 classes.dex (OK - compressed)
 1520905 junit/runner/logo.gif (OK - compressed)
 1521233 junit/runner/smalllogo.gif (OK - compressed)
 1521490 mockito-extensions/org.mockito.plugins.MockMaker (OK - compressed)
 1521648 mockito-extensions/org.mockito.plugins.StackTraceCleanerProvider (OK - compressed)
 1521795 org/mockito/internal/creation/jmock/jmock-license.txt (OK - compressed)
 1522688 org/mockito/internal/matchers/apachecommons/commons-lang-license.txt (OK - compressed)
 1526729 res/anim/abc_fade_in.xml (OK - compressed)
 1527028 res/anim/abc_fade_out.xml (OK - compressed)
 1527344 res/anim/abc_grow_fade_in_from_bottom.xml (OK - compressed)
 1527812 res/anim/abc_popup_enter.xml (OK - compressed)
 1528157 res/anim/abc_popup_exit.xml (OK - compressed)
 1528521 res/anim/abc_shrink_fade_out_from_bottom.xml (OK - compressed)
 1528992 res/anim/abc_slide_in_bottom.xml (OK - compressed)
 1529302 res/anim/abc_slide_in_top.xml (OK - compressed)
 1529616 res/anim/abc_slide_out_bottom.xml (OK - compressed)
 1529926 res/anim/abc_slide_out_top.xml (OK - compressed)
 1530273 res/color-v11/abc_background_cache_hint_selector_material_dark.xml (OK - compressed)
 1530627 res/color-v11/abc_background_cache_hint_selector_material_light.xml (OK - compressed)
 1530960 res/color-v23/abc_color_highlight_material.xml (OK - compressed)
 1531335 res/color/abc_primary_text_disable_only_material_dark.xml (OK - compressed)
 1531677 res/color/abc_primary_text_disable_only_material_light.xml (OK - compressed)
 1532005 res/color/abc_primary_text_material_dark.xml (OK - compressed)
 1532335 res/color/abc_primary_text_material_light.xml (OK - compressed)
 1532652 res/color/abc_search_url_text.xml (OK - compressed)
 1533009 res/color/abc_secondary_text_material_dark.xml (OK - compressed)
 1533342 res/color/abc_secondary_text_material_light.xml (OK - compressed)
 1533668 res/color/switch_thumb_material_dark.xml (OK - compressed)
 1533994 res/color/switch_thumb_material_light.xml (OK - compressed)
 1534336 res/drawable-hdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png (OK)
 1534716 res/drawable-hdpi-v4/abc_btn_check_to_on_mtrl_000.png (OK)
 1535036 res/drawable-hdpi-v4/abc_btn_check_to_on_mtrl_015.png (OK)
 1535532 res/drawable-hdpi-v4/abc_btn_radio_to_on_mtrl_000.png (OK)
 1536088 res/drawable-hdpi-v4/abc_btn_radio_to_on_mtrl_015.png (OK)
 1536752 res/drawable-hdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png (OK)
 1537804 res/drawable-hdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png (OK)
 1538536 res/drawable-hdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png (OK)
 1540184 res/drawable-hdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png (OK)
 1542032 res/drawable-hdpi-v4/abc_cab_background_top_mtrl_alpha.9.png (OK)
 1542356 res/drawable-hdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
 1542724 res/drawable-hdpi-v4/abc_ic_clear_mtrl_alpha.png (OK)
 1543104 res/drawable-hdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png (OK)
 1543372 res/drawable-hdpi-v4/abc_ic_go_search_api_mtrl_alpha.png (OK)
 1543584 res/drawable-hdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
 1543880 res/drawable-hdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
 1544384 res/drawable-hdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png (OK)
 1544616 res/drawable-hdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png (OK)
 1544940 res/drawable-hdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png (OK)
 1545256 res/drawable-hdpi-v4/abc_ic_menu_share_mtrl_alpha.png (OK)
 1545756 res/drawable-hdpi-v4/abc_ic_search_api_mtrl_alpha.png (OK)
 1546464 res/drawable-hdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png (OK)
 1546884 res/drawable-hdpi-v4/abc_list_divider_mtrl_alpha.9.png (OK)
 1547140 res/drawable-hdpi-v4/abc_list_focused_holo.9.png (OK)
 1547476 res/drawable-hdpi-v4/abc_list_longpressed_holo.9.png (OK)
 1547780 res/drawable-hdpi-v4/abc_list_pressed_holo_dark.9.png (OK)
 1548088 res/drawable-hdpi-v4/abc_list_pressed_holo_light.9.png (OK)
 1548404 res/drawable-hdpi-v4/abc_list_selector_disabled_holo_dark.9.png (OK)
 1548748 res/drawable-hdpi-v4/abc_list_selector_disabled_holo_light.9.png (OK)
 1549088 res/drawable-hdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png (OK)
 1550004 res/drawable-hdpi-v4/abc_popup_background_mtrl_mult.9.png (OK)
 1551360 res/drawable-hdpi-v4/abc_scrubber_control_off_mtrl_alpha.png (OK)
 1551692 res/drawable-hdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png (OK)
 1552016 res/drawable-hdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png (OK)
 1552444 res/drawable-hdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png (OK)
 1552756 res/drawable-hdpi-v4/abc_scrubber_track_mtrl_alpha.9.png (OK)
 1553048 res/drawable-hdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
 1553512 res/drawable-hdpi-v4/abc_switch_track_mtrl_alpha.9.png (OK)
 1554144 res/drawable-hdpi-v4/abc_tab_indicator_mtrl_alpha.9.png (OK)
 1554444 res/drawable-hdpi-v4/abc_textfield_activated_mtrl_alpha.9.png (OK)
 1554736 res/drawable-hdpi-v4/abc_textfield_default_mtrl_alpha.9.png (OK)
 1555048 res/drawable-hdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png (OK)
 1555336 res/drawable-hdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png (OK)
 1555616 res/drawable-ldrtl-hdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
 1555988 res/drawable-ldrtl-hdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
 1556284 res/drawable-ldrtl-hdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
 1556784 res/drawable-ldrtl-hdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
 1557252 res/drawable-ldrtl-mdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
 1557572 res/drawable-ldrtl-mdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
 1557800 res/drawable-ldrtl-mdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
 1558168 res/drawable-ldrtl-mdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
 1558612 res/drawable-ldrtl-xhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
 1559008 res/drawable-ldrtl-xhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
 1559292 res/drawable-ldrtl-xhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
 1559884 res/drawable-ldrtl-xhdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
 1560468 res/drawable-ldrtl-xxhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
 1560940 res/drawable-ldrtl-xxhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
 1561304 res/drawable-ldrtl-xxhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
 1562112 res/drawable-ldrtl-xxhdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
 1562808 res/drawable-ldrtl-xxxhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
 1563144 res/drawable-ldrtl-xxxhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
 1563572 res/drawable-ldrtl-xxxhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
 1564580 res/drawable-ldrtl-xxxhdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
 1565192 res/drawable-mdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png (OK)
 1565560 res/drawable-mdpi-v4/abc_btn_check_to_on_mtrl_000.png (OK)
 1565868 res/drawable-mdpi-v4/abc_btn_check_to_on_mtrl_015.png (OK)
 1566284 res/drawable-mdpi-v4/abc_btn_radio_to_on_mtrl_000.png (OK)
 1566704 res/drawable-mdpi-v4/abc_btn_radio_to_on_mtrl_015.png (OK)
 1567160 res/drawable-mdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png (OK)
 1568004 res/drawable-mdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png (OK)
 1568636 res/drawable-mdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png (OK)
 1569780 res/drawable-mdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png (OK)
 1571004 res/drawable-mdpi-v4/abc_cab_background_top_mtrl_alpha.9.png (OK)
 1571324 res/drawable-mdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
 1571636 res/drawable-mdpi-v4/abc_ic_clear_mtrl_alpha.png (OK)
 1571972 res/drawable-mdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png (OK)
 1572252 res/drawable-mdpi-v4/abc_ic_go_search_api_mtrl_alpha.png (OK)
 1572456 res/drawable-mdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
 1572680 res/drawable-mdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
 1573044 res/drawable-mdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png (OK)
 1573252 res/drawable-mdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png (OK)
 1573508 res/drawable-mdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png (OK)
 1573744 res/drawable-mdpi-v4/abc_ic_menu_share_mtrl_alpha.png (OK)
 1574112 res/drawable-mdpi-v4/abc_ic_search_api_mtrl_alpha.png (OK)
 1574620 res/drawable-mdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png (OK)
 1574948 res/drawable-mdpi-v4/abc_list_divider_mtrl_alpha.9.png (OK)
 1575204 res/drawable-mdpi-v4/abc_list_focused_holo.9.png (OK)
 1575520 res/drawable-mdpi-v4/abc_list_longpressed_holo.9.png (OK)
 1575824 res/drawable-mdpi-v4/abc_list_pressed_holo_dark.9.png (OK)
 1576128 res/drawable-mdpi-v4/abc_list_pressed_holo_light.9.png (OK)
 1576444 res/drawable-mdpi-v4/abc_list_selector_disabled_holo_dark.9.png (OK)
 1576776 res/drawable-mdpi-v4/abc_list_selector_disabled_holo_light.9.png (OK)
 1577104 res/drawable-mdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png (OK)
 1577792 res/drawable-mdpi-v4/abc_popup_background_mtrl_mult.9.png (OK)
 1578744 res/drawable-mdpi-v4/abc_scrubber_control_off_mtrl_alpha.png (OK)
 1579024 res/drawable-mdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png (OK)
 1579300 res/drawable-mdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png (OK)
 1579620 res/drawable-mdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png (OK)
 1579924 res/drawable-mdpi-v4/abc_scrubber_track_mtrl_alpha.9.png (OK)
 1580212 res/drawable-mdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
 1580648 res/drawable-mdpi-v4/abc_switch_track_mtrl_alpha.9.png (OK)
 1581172 res/drawable-mdpi-v4/abc_tab_indicator_mtrl_alpha.9.png (OK)
 1581464 res/drawable-mdpi-v4/abc_textfield_activated_mtrl_alpha.9.png (OK)
 1581748 res/drawable-mdpi-v4/abc_textfield_default_mtrl_alpha.9.png (OK)
 1582040 res/drawable-mdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png (OK)
 1582328 res/drawable-mdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png (OK)
 1582607 res/drawable-v21/abc_action_bar_item_background_material.xml (OK - compressed)
 1582879 res/drawable-v21/abc_btn_colored_material.xml (OK - compressed)
 1583580 res/drawable-v23/abc_control_background_material.xml (OK - compressed)
 1583888 res/drawable-xhdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png (OK)
 1584280 res/drawable-xhdpi-v4/abc_btn_check_to_on_mtrl_000.png (OK)
 1584656 res/drawable-xhdpi-v4/abc_btn_check_to_on_mtrl_015.png (OK)
 1585184 res/drawable-xhdpi-v4/abc_btn_radio_to_on_mtrl_000.png (OK)
 1585928 res/drawable-xhdpi-v4/abc_btn_radio_to_on_mtrl_015.png (OK)
 1586812 res/drawable-xhdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png (OK)
 1588344 res/drawable-xhdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png (OK)
 1589376 res/drawable-xhdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png (OK)
 1591736 res/drawable-xhdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png (OK)
 1594444 res/drawable-xhdpi-v4/abc_cab_background_top_mtrl_alpha.9.png (OK)
 1594772 res/drawable-xhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
 1595188 res/drawable-xhdpi-v4/abc_ic_clear_mtrl_alpha.png (OK)
 1595652 res/drawable-xhdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png (OK)
 1596000 res/drawable-xhdpi-v4/abc_ic_go_search_api_mtrl_alpha.png (OK)
 1596240 res/drawable-xhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
 1596520 res/drawable-xhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
 1597116 res/drawable-xhdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png (OK)
 1597372 res/drawable-xhdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png (OK)
 1597712 res/drawable-xhdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png (OK)
 1598000 res/drawable-xhdpi-v4/abc_ic_menu_share_mtrl_alpha.png (OK)
 1598592 res/drawable-xhdpi-v4/abc_ic_search_api_mtrl_alpha.png (OK)
 1599464 res/drawable-xhdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png (OK)
 1599976 res/drawable-xhdpi-v4/abc_list_divider_mtrl_alpha.9.png (OK)
 1600232 res/drawable-xhdpi-v4/abc_list_focused_holo.9.png (OK)
 1600568 res/drawable-xhdpi-v4/abc_list_longpressed_holo.9.png (OK)
 1600876 res/drawable-xhdpi-v4/abc_list_pressed_holo_dark.9.png (OK)
 1601184 res/drawable-xhdpi-v4/abc_list_pressed_holo_light.9.png (OK)
 1601504 res/drawable-xhdpi-v4/abc_list_selector_disabled_holo_dark.9.png (OK)
 1601864 res/drawable-xhdpi-v4/abc_list_selector_disabled_holo_light.9.png (OK)
 1602216 res/drawable-xhdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png (OK)
 1603436 res/drawable-xhdpi-v4/abc_popup_background_mtrl_mult.9.png (OK)
 1605324 res/drawable-xhdpi-v4/abc_scrubber_control_off_mtrl_alpha.png (OK)
 1605760 res/drawable-xhdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png (OK)
 1606192 res/drawable-xhdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png (OK)
 1606760 res/drawable-xhdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png (OK)
 1607076 res/drawable-xhdpi-v4/abc_scrubber_track_mtrl_alpha.9.png (OK)
 1607376 res/drawable-xhdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
 1607960 res/drawable-xhdpi-v4/abc_switch_track_mtrl_alpha.9.png (OK)
 1608796 res/drawable-xhdpi-v4/abc_tab_indicator_mtrl_alpha.9.png (OK)
 1609104 res/drawable-xhdpi-v4/abc_textfield_activated_mtrl_alpha.9.png (OK)
 1609404 res/drawable-xhdpi-v4/abc_textfield_default_mtrl_alpha.9.png (OK)
 1609712 res/drawable-xhdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png (OK)
 1610008 res/drawable-xhdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png (OK)
 1610296 res/drawable-xxhdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png (OK)
 1610696 res/drawable-xxhdpi-v4/abc_btn_check_to_on_mtrl_000.png (OK)
 1611100 res/drawable-xxhdpi-v4/abc_btn_check_to_on_mtrl_015.png (OK)
 1611788 res/drawable-xxhdpi-v4/abc_btn_radio_to_on_mtrl_000.png (OK)
 1612868 res/drawable-xxhdpi-v4/abc_btn_radio_to_on_mtrl_015.png (OK)
 1614180 res/drawable-xxhdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png (OK)
 1615964 res/drawable-xxhdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png (OK)
 1616956 res/drawable-xxhdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png (OK)
 1620812 res/drawable-xxhdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png (OK)
 1623720 res/drawable-xxhdpi-v4/abc_cab_background_top_mtrl_alpha.9.png (OK)
 1624060 res/drawable-xxhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
 1624564 res/drawable-xxhdpi-v4/abc_ic_clear_mtrl_alpha.png (OK)
 1625060 res/drawable-xxhdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png (OK)
 1625416 res/drawable-xxhdpi-v4/abc_ic_go_search_api_mtrl_alpha.png (OK)
 1625660 res/drawable-xxhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
 1626020 res/drawable-xxhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
 1626832 res/drawable-xxhdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png (OK)
 1627144 res/drawable-xxhdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png (OK)
 1627592 res/drawable-xxhdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png (OK)
 1627948 res/drawable-xxhdpi-v4/abc_ic_menu_share_mtrl_alpha.png (OK)
 1628768 res/drawable-xxhdpi-v4/abc_ic_search_api_mtrl_alpha.png (OK)
 1630208 res/drawable-xxhdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png (OK)
 1630892 res/drawable-xxhdpi-v4/abc_list_divider_mtrl_alpha.9.png (OK)
 1631152 res/drawable-xxhdpi-v4/abc_list_focused_holo.9.png (OK)
 1631492 res/drawable-xxhdpi-v4/abc_list_longpressed_holo.9.png (OK)
 1631808 res/drawable-xxhdpi-v4/abc_list_pressed_holo_dark.9.png (OK)
 1632124 res/drawable-xxhdpi-v4/abc_list_pressed_holo_light.9.png (OK)
 1632452 res/drawable-xxhdpi-v4/abc_list_selector_disabled_holo_dark.9.png (OK)
 1632864 res/drawable-xxhdpi-v4/abc_list_selector_disabled_holo_light.9.png (OK)
 1633272 res/drawable-xxhdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png (OK)
 1635152 res/drawable-xxhdpi-v4/abc_popup_background_mtrl_mult.9.png (OK)
 1638028 res/drawable-xxhdpi-v4/abc_scrubber_control_off_mtrl_alpha.png (OK)
 1638532 res/drawable-xxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png (OK)
 1639116 res/drawable-xxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png (OK)
 1639956 res/drawable-xxhdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png (OK)
 1640272 res/drawable-xxhdpi-v4/abc_scrubber_track_mtrl_alpha.9.png (OK)
 1640580 res/drawable-xxhdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
 1641272 res/drawable-xxhdpi-v4/abc_switch_track_mtrl_alpha.9.png (OK)
 1642428 res/drawable-xxhdpi-v4/abc_tab_indicator_mtrl_alpha.9.png (OK)
 1642740 res/drawable-xxhdpi-v4/abc_textfield_activated_mtrl_alpha.9.png (OK)
 1643044 res/drawable-xxhdpi-v4/abc_textfield_default_mtrl_alpha.9.png (OK)
 1643360 res/drawable-xxhdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png (OK)
 1643660 res/drawable-xxhdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png (OK)
 1643952 res/drawable-xxxhdpi-v4/abc_btn_check_to_on_mtrl_000.png (OK)
 1644332 res/drawable-xxxhdpi-v4/abc_btn_check_to_on_mtrl_015.png (OK)
 1644904 res/drawable-xxxhdpi-v4/abc_btn_radio_to_on_mtrl_000.png (OK)
 1645784 res/drawable-xxxhdpi-v4/abc_btn_radio_to_on_mtrl_015.png (OK)
 1646832 res/drawable-xxxhdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png (OK)
 1650456 res/drawable-xxxhdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png (OK)
 1654404 res/drawable-xxxhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
 1654732 res/drawable-xxxhdpi-v4/abc_ic_clear_mtrl_alpha.png (OK)
 1655396 res/drawable-xxxhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
 1655824 res/drawable-xxxhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
 1656844 res/drawable-xxxhdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png (OK)
 1657252 res/drawable-xxxhdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png (OK)
 1657816 res/drawable-xxxhdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png (OK)
 1658232 res/drawable-xxxhdpi-v4/abc_ic_menu_share_mtrl_alpha.png (OK)
 1659268 res/drawable-xxxhdpi-v4/abc_ic_search_api_mtrl_alpha.png (OK)
 1660348 res/drawable-xxxhdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png (OK)
 1661244 res/drawable-xxxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png (OK)
 1661868 res/drawable-xxxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png (OK)
 1662780 res/drawable-xxxhdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
 1663392 res/drawable-xxxhdpi-v4/abc_switch_track_mtrl_alpha.9.png (OK)
 1664516 res/drawable-xxxhdpi-v4/abc_tab_indicator_mtrl_alpha.9.png (OK)
 1664807 res/drawable/abc_btn_borderless_material.xml (OK - compressed)
 1665179 res/drawable/abc_btn_check_material.xml (OK - compressed)
 1665526 res/drawable/abc_btn_default_mtrl_shape.xml (OK - compressed)
 1666044 res/drawable/abc_btn_radio_material.xml (OK - compressed)
 1666395 res/drawable/abc_cab_background_internal_bg.xml (OK - compressed)
 1666695 res/drawable/abc_cab_background_top_material.xml (OK - compressed)
 1666995 res/drawable/abc_dialog_material_background_dark.xml (OK - compressed)
 1667440 res/drawable/abc_dialog_material_background_light.xml (OK - compressed)
 1667871 res/drawable/abc_edit_text_material.xml (OK - compressed)
 1668370 res/drawable/abc_item_background_holo_dark.xml (OK - compressed)
 1668812 res/drawable/abc_item_background_holo_light.xml (OK - compressed)
 1669272 res/drawable/abc_list_selector_background_transition_holo_dark.xml (OK - compressed)
 1669611 res/drawable/abc_list_selector_background_transition_holo_light.xml (OK - compressed)
 1669927 res/drawable/abc_list_selector_holo_dark.xml (OK - compressed)
 1670388 res/drawable/abc_list_selector_holo_light.xml (OK - compressed)
 1670847 res/drawable/abc_ratingbar_full_material.xml (OK - compressed)
 1671200 res/drawable/abc_seekbar_thumb_material.xml (OK - compressed)
 1671681 res/drawable/abc_seekbar_track_material.xml (OK - compressed)
 1672237 res/drawable/abc_spinner_textfield_background_material.xml (OK - compressed)
 1672770 res/drawable/abc_switch_thumb_material.xml (OK - compressed)
 1673117 res/drawable/abc_tab_indicator_material.xml (OK - compressed)
 1673465 res/drawable/abc_text_cursor_material.xml (OK - compressed)
 1673822 res/drawable/abc_textfield_search_material.xml (OK - compressed)
 1674228 res/layout/abc_action_bar_title_item.xml (OK - compressed)
 1674777 res/layout/abc_action_bar_up_container.xml (OK - compressed)
 1675138 res/layout/abc_action_bar_view_list_nav_layout.xml (OK - compressed)
 1675471 res/layout/abc_action_menu_item_layout.xml (OK - compressed)
 1675990 res/layout/abc_action_menu_layout.xml (OK - compressed)
 1676387 res/layout/abc_action_mode_bar.xml (OK - compressed)
 1676784 res/layout/abc_action_mode_close_item_material.xml (OK - compressed)
 1677223 res/layout/abc_activity_chooser_view.xml (OK - compressed)
 1677957 res/layout/abc_activity_chooser_view_list_item.xml (OK - compressed)
 1678612 res/layout/abc_alert_dialog_button_bar_material.xml (OK - compressed)
 1679376 res/layout/abc_alert_dialog_material.xml (OK - compressed)
 1680569 res/layout/abc_dialog_title_material.xml (OK - compressed)
 1681228 res/layout/abc_expanded_menu_layout.xml (OK - compressed)
 1681565 res/layout/abc_list_menu_item_checkbox.xml (OK - compressed)
 1681952 res/layout/abc_list_menu_item_icon.xml (OK - compressed)
 1682406 res/layout/abc_list_menu_item_layout.xml (OK - compressed)
 1683103 res/layout/abc_list_menu_item_radio.xml (OK - compressed)
 1683493 res/layout/abc_popup_menu_item_layout.xml (OK - compressed)
 1684260 res/layout/abc_screen_content_include.xml (OK - compressed)
 1684646 res/layout/abc_screen_simple.xml (OK - compressed)
 1685180 res/layout/abc_screen_simple_overlay_action_mode.xml (OK - compressed)
 1685675 res/layout/abc_screen_toolbar.xml (OK - compressed)
 1686489 res/layout/abc_search_dropdown_item_icons_2line.xml (OK - compressed)
 1687359 res/layout/abc_search_view.xml (OK - compressed)
 1688677 res/layout/abc_select_dialog_material.xml (OK - compressed)
 1689194 res/layout/notification_media_action.xml (OK - compressed)
 1689630 res/layout/notification_media_cancel_action.xml (OK - compressed)
 1690105 res/layout/notification_template_big_media.xml (OK - compressed)
 1690924 res/layout/notification_template_big_media_narrow.xml (OK - compressed)
 1691747 res/layout/notification_template_lines.xml (OK - compressed)
 1692701 res/layout/notification_template_media.xml (OK - compressed)
 1693391 res/layout/notification_template_part_chronometer.xml (OK - compressed)
 1693841 res/layout/notification_template_part_time.xml (OK - compressed)
 1694286 res/layout/select_dialog_item_material.xml (OK - compressed)
 1694741 res/layout/select_dialog_multichoice_material.xml (OK - compressed)
 1695296 res/layout/select_dialog_singlechoice_material.xml (OK - compressed)
 1695852 res/layout/support_simple_spinner_dropdown_item.xml (OK - compressed)
 1696228 resources.arsc (OK)
Verification succesful


```

```


```
