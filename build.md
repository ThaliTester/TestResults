#### Test (Success) 99073715 Build Logs


```


```

```
Updating 6699516..d69c6ae
Fast-forward
 .../p2p/btconnectorlib/AdvertisementData.java      |   35 +++
 .../p2p/btconnectorlib/DiscoveryManager.java       |   56 +----
 .../btconnectorlib/DiscoveryManagerSettings.java   |  128 +++++-----
 .../p2p/btconnectorlib/PeerProperties.java         |   62 +++--
 .../btconnectorlib/internal/AbstractSettings.java  |    2 -
 .../internal/bluetooth/le/BleAdvertiser.java       |   18 +-
 .../internal/bluetooth/le/BlePeerDiscoverer.java   |  249 +++++++++++---------
 .../bluetooth/le/BlePeerDiscoveryUtils.java        |   34 +--
 .../internal/bluetooth/le/BleScanner.java          |   11 +-
 .../bluetooth/le/BluetoothGattManager.java         |  129 +++++-----
 .../bluetooth/le/PeerAdvertisementFactory.java     |   74 +++---
 .../internal/wifi/WifiServiceWatcher.java          |   20 +-
 .../ConnectionManagerSettingsTest.java             |    2 +
 .../internal/bluetooth/le/BleAdvertiserTest.java   |    2 +-
 .../bluetooth/le/BlePeerDiscovererTest.java        |   60 ++---
 .../internal/bluetooth/le/BleScannerTest.java      |    4 +-
 BtConnectorLib/settings.gradle                     |    2 +-
 17 files changed, 489 insertions(+), 399 deletions(-)
 create mode 100644 BtConnectorLib/btconnectorlib2/src/main/java/org/thaliproject/p2p/btconnectorlib/AdvertisementData.java

From https://github.com/thaliproject/Thali_CordovaPlugin_BtLibrary
   6699516..d69c6ae  master     -> origin/master
 * [new branch]      evabishchevich_101 -> origin/evabishchevich_101

```

```
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
Already up-to-date!
Merge made by the 'recursive' strategy.

Already on 'master'
Already on 'master'
Note: checking out '8e6f6eb'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by performing another checkout.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -b with the checkout command again. Example:

  git checkout -b <new-branch-name>

HEAD is now at 8e6f6eb... Reset singleton state in tests

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
Download https://jcenter.bintray.com/org/mockito/mockito-core/1.9.5/mockito-core-1.9.5.pom
Download https://jcenter.bintray.com/org/objenesis/objenesis/1.0/objenesis-1.0.pom
Download https://jcenter.bintray.com/org/objenesis/objenesis/1.0/objenesis-1.0.jar
Download https://jcenter.bintray.com/org/mockito/mockito-core/1.9.5/mockito-core-1.9.5.jar
Download https://jcenter.bintray.com/com/google/dexmaker/dexmaker/1.2/dexmaker-1.2.pom
Download https://jcenter.bintray.com/com/google/dexmaker/dexmaker-parent/1.2/dexmaker-parent-1.2.pom
Download https://jcenter.bintray.com/com/google/dexmaker/dexmaker-mockito/1.2/dexmaker-mockito-1.2.pom
Download https://jcenter.bintray.com/com/google/dexmaker/dexmaker/1.2/dexmaker-1.2.jar
Download https://jcenter.bintray.com/com/google/dexmaker/dexmaker-mockito/1.2/dexmaker-mockito-1.2.jar
:btconnectorlib2:compileLint
:btconnectorlib2:copyReleaseLint UP-TO-DATE
:btconnectorlib2:preBuild UP-TO-DATE
:btconnectorlib2:preReleaseBuild UP-TO-DATE
:btconnectorlib2:checkReleaseManifest
:btconnectorlib2:preDebugBuild UP-TO-DATE
:btconnectorlib2:preReleaseAndroidTestBuild UP-TO-DATE
:btconnectorlib2:prepareComAndroidSupportAppcompatV72311Library
:btconnectorlib2:prepareComAndroidSupportSupportV42311Library
:btconnectorlib2:prepareReleaseDependencies
:btconnectorlib2:compileReleaseAidl
:btconnectorlib2:compileReleaseRenderscript
:btconnectorlib2:generateReleaseBuildConfig
:btconnectorlib2:generateReleaseAssets UP-TO-DATE
:btconnectorlib2:mergeReleaseAssets
:btconnectorlib2:generateReleaseResValues
:btconnectorlib2:generateReleaseResources
:btconnectorlib2:mergeReleaseResources
:btconnectorlib2:processReleaseManifest
:btconnectorlib2:processReleaseResources
:btconnectorlib2:generateReleaseSources
:btconnectorlib2:compileReleaseJava
:btconnectorlib2:extractReleaseAnnotations
:btconnectorlib2:mergeReleaseProguardFiles
:btconnectorlib2:processReleaseJavaRes UP-TO-DATE
:btconnectorlib2:packageReleaseJar
:btconnectorlib2:compileReleaseNdk UP-TO-DATE
:btconnectorlib2:packageReleaseJniLibs UP-TO-DATE
:btconnectorlib2:packageReleaseLocalJar UP-TO-DATE
:btconnectorlib2:packageReleaseRenderscript UP-TO-DATE
:btconnectorlib2:packageReleaseResources
:btconnectorlib2:bundleRelease
:btconnectorlib2:assembleRelease

BUILD SUCCESSFUL

Total time: 1 mins 10.953 secs
:btconnectorlib2:preBuild UP-TO-DATE
:btconnectorlib2:preReleaseAndroidTestBuild UP-TO-DATE
:btconnectorlib2:preDebugBuild UP-TO-DATE
:btconnectorlib2:preReleaseBuild UP-TO-DATE
:btconnectorlib2:prepareComAndroidSupportAppcompatV72311Library UP-TO-DATE
:btconnectorlib2:prepareComAndroidSupportSupportV42311Library UP-TO-DATE
:btconnectorlib2:prepareComAndroidSupportTestExposedInstrumentationApiPublish04Library
:btconnectorlib2:prepareComAndroidSupportTestRules04Library
:btconnectorlib2:prepareComAndroidSupportTestRunner04Library
:btconnectorlib2:prepareReleaseAndroidTestDependencies
:btconnectorlib2:compileReleaseAndroidTestAidl
:btconnectorlib2:compileLint
:btconnectorlib2:copyReleaseLint UP-TO-DATE
:btconnectorlib2:checkReleaseManifest
:btconnectorlib2:prepareReleaseDependencies
:btconnectorlib2:compileReleaseAidl UP-TO-DATE
:btconnectorlib2:compileReleaseRenderscript UP-TO-DATE
:btconnectorlib2:generateReleaseBuildConfig UP-TO-DATE
:btconnectorlib2:generateReleaseAssets UP-TO-DATE
:btconnectorlib2:mergeReleaseAssets UP-TO-DATE
:btconnectorlib2:generateReleaseResValues UP-TO-DATE
:btconnectorlib2:generateReleaseResources UP-TO-DATE
:btconnectorlib2:mergeReleaseResources UP-TO-DATE
:btconnectorlib2:processReleaseManifest UP-TO-DATE
:btconnectorlib2:processReleaseResources UP-TO-DATE
:btconnectorlib2:generateReleaseSources UP-TO-DATE
:btconnectorlib2:compileReleaseJava UP-TO-DATE
:btconnectorlib2:extractReleaseAnnotations UP-TO-DATE
:btconnectorlib2:mergeReleaseProguardFiles UP-TO-DATE
:btconnectorlib2:processReleaseJavaRes UP-TO-DATE
:btconnectorlib2:packageReleaseJar UP-TO-DATE
:btconnectorlib2:compileReleaseNdk UP-TO-DATE
:btconnectorlib2:packageReleaseJniLibs UP-TO-DATE
:btconnectorlib2:packageReleaseLocalJar UP-TO-DATE
:btconnectorlib2:packageReleaseRenderscript UP-TO-DATE
:btconnectorlib2:packageReleaseResources UP-TO-DATE
:btconnectorlib2:bundleRelease UP-TO-DATE
:btconnectorlib2:assembleRelease UP-TO-DATE
:btconnectorlib2:processReleaseAndroidTestManifest
:btconnectorlib2:compileReleaseAndroidTestRenderscript
:btconnectorlib2:generateReleaseAndroidTestBuildConfig
:btconnectorlib2:generateReleaseAndroidTestAssets UP-TO-DATE
:btconnectorlib2:mergeReleaseAndroidTestAssets
:btconnectorlib2:generateReleaseAndroidTestResValues
:btconnectorlib2:generateReleaseAndroidTestResources
:btconnectorlib2:mergeReleaseAndroidTestResources
:btconnectorlib2:processReleaseAndroidTestResources
:btconnectorlib2:generateReleaseAndroidTestSources
:btconnectorlib2:compileReleaseAndroidTestJava
:btconnectorlib2:lintVitalReleaseAndroidTest
:btconnectorlib2:compileReleaseAndroidTestNdk UP-TO-DATE
:btconnectorlib2:preDexReleaseAndroidTest
:btconnectorlib2:dexReleaseAndroidTest
:btconnectorlib2:processReleaseAndroidTestJavaRes UP-TO-DATE
:btconnectorlib2:packageReleaseAndroidTest
:btconnectorlib2:assembleReleaseAndroidTest

BUILD SUCCESSFUL

Total time: 54.567 secs
:btconnectorlib2:preCompileReleaseUnitTestJava
:btconnectorlib2:compileReleaseUnitTestJava
:btconnectorlib2:compileReleaseUnitTestSources
:btconnectorlib2:mockableAndroidJar
:btconnectorlib2:assembleReleaseUnitTest
:btconnectorlib2:testRelease

BUILD SUCCESSFUL

Total time: 31.077 secs

Note: Some input files use unchecked or unsafe operations.
Note: Recompile with -Xlint:unchecked for details.

```

```
   adding: META-INF/MANIFEST.MF
   adding: META-INF/ALIAS_NA.SF
   adding: META-INF/ALIAS_NA.RSA
  signing: AndroidManifest.xml
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
  signing: res/color/abc_background_cache_hint_selector_material_dark.xml
  signing: res/color/abc_background_cache_hint_selector_material_light.xml
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
  signing: res/drawable-ldrtl-hdpi-v17/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-hdpi-v17/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-hdpi-v17/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-ldrtl-hdpi-v17/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-ldrtl-mdpi-v17/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-mdpi-v17/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-mdpi-v17/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-ldrtl-mdpi-v17/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-ldrtl-xhdpi-v17/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xhdpi-v17/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xhdpi-v17/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-ldrtl-xhdpi-v17/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-ldrtl-xxhdpi-v17/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xxhdpi-v17/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xxhdpi-v17/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-ldrtl-xxhdpi-v17/abc_spinner_mtrl_am_alpha.9.png
  signing: res/drawable-ldrtl-xxxhdpi-v17/abc_ic_ab_back_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xxxhdpi-v17/abc_ic_menu_copy_mtrl_am_alpha.png
  signing: res/drawable-ldrtl-xxxhdpi-v17/abc_ic_menu_cut_mtrl_alpha.png
  signing: res/drawable-ldrtl-xxxhdpi-v17/abc_spinner_mtrl_am_alpha.9.png
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
  signing: res/drawable/abc_btn_colored_material.xml
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
  signing: classes.dex
  signing: LICENSE.txt
  signing: junit/runner/smalllogo.gif
  signing: junit/runner/logo.gif
  signing: LICENSE-junit.txt
  signing: mockito-extensions/org.mockito.plugins.MockMaker
  signing: mockito-extensions/org.mockito.plugins.StackTraceCleanerProvider
  signing: LICENSE
  signing: NOTICE
  signing: asm-license.txt
  signing: cglib-license.txt
  signing: org/mockito/internal/creation/jmock/jmock-license.txt
  signing: org/mockito/internal/matchers/apachecommons/commons-lang-license.txt
jar signed.

Warning: 
No -tsa or -tsacert is provided and this jar is not timestamped. Without a timestamp, users may not be able to validate this jar after the signer certificate's expiration date (2043-01-05) or after any future revocation date.
Verifying alignment of android.apk (4)...
      50 META-INF/MANIFEST.MF (OK - compressed)
    9885 META-INF/ALIAS_NA.SF (OK - compressed)
   19855 META-INF/ALIAS_NA.RSA (OK - compressed)
   20940 AndroidManifest.xml (OK - compressed)
   22026 res/anim/abc_fade_in.xml (OK - compressed)
   22316 res/anim/abc_fade_out.xml (OK - compressed)
   22623 res/anim/abc_grow_fade_in_from_bottom.xml (OK - compressed)
   23081 res/anim/abc_popup_enter.xml (OK - compressed)
   23417 res/anim/abc_popup_exit.xml (OK - compressed)
   23772 res/anim/abc_shrink_fade_out_from_bottom.xml (OK - compressed)
   24233 res/anim/abc_slide_in_bottom.xml (OK - compressed)
   24534 res/anim/abc_slide_in_top.xml (OK - compressed)
   24839 res/anim/abc_slide_out_bottom.xml (OK - compressed)
   25140 res/anim/abc_slide_out_top.xml (OK - compressed)
   25478 res/color-v11/abc_background_cache_hint_selector_material_dark.xml (OK - compressed)
   25822 res/color-v11/abc_background_cache_hint_selector_material_light.xml (OK - compressed)
   26146 res/color-v23/abc_color_highlight_material.xml (OK - compressed)
   26517 res/color/abc_background_cache_hint_selector_material_dark.xml (OK - compressed)
   26808 res/color/abc_background_cache_hint_selector_material_light.xml (OK - compressed)
   27094 res/color/abc_primary_text_disable_only_material_dark.xml (OK - compressed)
   27427 res/color/abc_primary_text_disable_only_material_light.xml (OK - compressed)
   27746 res/color/abc_primary_text_material_dark.xml (OK - compressed)
   28066 res/color/abc_primary_text_material_light.xml (OK - compressed)
   28374 res/color/abc_search_url_text.xml (OK - compressed)
   28721 res/color/abc_secondary_text_material_dark.xml (OK - compressed)
   29044 res/color/abc_secondary_text_material_light.xml (OK - compressed)
   29360 res/color/switch_thumb_material_dark.xml (OK - compressed)
   29677 res/color/switch_thumb_material_light.xml (OK - compressed)
   30008 res/drawable-hdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png (OK)
   30380 res/drawable-hdpi-v4/abc_btn_check_to_on_mtrl_000.png (OK)
   30768 res/drawable-hdpi-v4/abc_btn_check_to_on_mtrl_015.png (OK)
   31400 res/drawable-hdpi-v4/abc_btn_radio_to_on_mtrl_000.png (OK)
   32104 res/drawable-hdpi-v4/abc_btn_radio_to_on_mtrl_015.png (OK)
   32948 res/drawable-hdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png (OK)
   34624 res/drawable-hdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png (OK)
   35768 res/drawable-hdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png (OK)
   37404 res/drawable-hdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png (OK)
   39244 res/drawable-hdpi-v4/abc_cab_background_top_mtrl_alpha.9.png (OK)
   39556 res/drawable-hdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
   40024 res/drawable-hdpi-v4/abc_ic_clear_mtrl_alpha.png (OK)
   40396 res/drawable-hdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png (OK)
   40708 res/drawable-hdpi-v4/abc_ic_go_search_api_mtrl_alpha.png (OK)
   40940 res/drawable-hdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
   41304 res/drawable-hdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
   41980 res/drawable-hdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png (OK)
   42256 res/drawable-hdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png (OK)
   42704 res/drawable-hdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png (OK)
   43056 res/drawable-hdpi-v4/abc_ic_menu_share_mtrl_alpha.png (OK)
   43932 res/drawable-hdpi-v4/abc_ic_search_api_mtrl_alpha.png (OK)
   45004 res/drawable-hdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png (OK)
   45628 res/drawable-hdpi-v4/abc_list_divider_mtrl_alpha.9.png (OK)
   45876 res/drawable-hdpi-v4/abc_list_focused_holo.9.png (OK)
   46204 res/drawable-hdpi-v4/abc_list_longpressed_holo.9.png (OK)
   46500 res/drawable-hdpi-v4/abc_list_pressed_holo_dark.9.png (OK)
   46796 res/drawable-hdpi-v4/abc_list_pressed_holo_light.9.png (OK)
   47104 res/drawable-hdpi-v4/abc_list_selector_disabled_holo_dark.9.png (OK)
   47440 res/drawable-hdpi-v4/abc_list_selector_disabled_holo_light.9.png (OK)
   47772 res/drawable-hdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png (OK)
   48676 res/drawable-hdpi-v4/abc_popup_background_mtrl_mult.9.png (OK)
   50024 res/drawable-hdpi-v4/abc_scrubber_control_off_mtrl_alpha.png (OK)
   50376 res/drawable-hdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png (OK)
   50744 res/drawable-hdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png (OK)
   51220 res/drawable-hdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png (OK)
   51520 res/drawable-hdpi-v4/abc_scrubber_track_mtrl_alpha.9.png (OK)
   51804 res/drawable-hdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
   52256 res/drawable-hdpi-v4/abc_switch_track_mtrl_alpha.9.png (OK)
   52880 res/drawable-hdpi-v4/abc_tab_indicator_mtrl_alpha.9.png (OK)
   53172 res/drawable-hdpi-v4/abc_textfield_activated_mtrl_alpha.9.png (OK)
   53456 res/drawable-hdpi-v4/abc_textfield_default_mtrl_alpha.9.png (OK)
   53756 res/drawable-hdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png (OK)
   54036 res/drawable-hdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png (OK)
   54308 res/drawable-ldrtl-hdpi-v17/abc_ic_ab_back_mtrl_am_alpha.png (OK)
   54784 res/drawable-ldrtl-hdpi-v17/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
   55152 res/drawable-ldrtl-hdpi-v17/abc_ic_menu_cut_mtrl_alpha.png (OK)
   55828 res/drawable-ldrtl-hdpi-v17/abc_spinner_mtrl_am_alpha.9.png (OK)
   56288 res/drawable-ldrtl-mdpi-v17/abc_ic_ab_back_mtrl_am_alpha.png (OK)
   56704 res/drawable-ldrtl-mdpi-v17/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
   56968 res/drawable-ldrtl-mdpi-v17/abc_ic_menu_cut_mtrl_alpha.png (OK)
   57440 res/drawable-ldrtl-mdpi-v17/abc_spinner_mtrl_am_alpha.9.png (OK)
   57876 res/drawable-ldrtl-xhdpi-v17/abc_ic_ab_back_mtrl_am_alpha.png (OK)
   58396 res/drawable-ldrtl-xhdpi-v17/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
   58724 res/drawable-ldrtl-xhdpi-v17/abc_ic_menu_cut_mtrl_alpha.png (OK)
   59504 res/drawable-ldrtl-xhdpi-v17/abc_spinner_mtrl_am_alpha.9.png (OK)
   60080 res/drawable-ldrtl-xxhdpi-v17/abc_ic_ab_back_mtrl_am_alpha.png (OK)
   60648 res/drawable-ldrtl-xxhdpi-v17/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
   61084 res/drawable-ldrtl-xxhdpi-v17/abc_ic_menu_cut_mtrl_alpha.png (OK)
   62108 res/drawable-ldrtl-xxhdpi-v17/abc_spinner_mtrl_am_alpha.9.png (OK)
   62796 res/drawable-ldrtl-xxxhdpi-v17/abc_ic_ab_back_mtrl_am_alpha.png (OK)
   63136 res/drawable-ldrtl-xxxhdpi-v17/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
   63628 res/drawable-ldrtl-xxxhdpi-v17/abc_ic_menu_cut_mtrl_alpha.png (OK)
   64900 res/drawable-ldrtl-xxxhdpi-v17/abc_spinner_mtrl_am_alpha.9.png (OK)
   65504 res/drawable-mdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png (OK)
   65864 res/drawable-mdpi-v4/abc_btn_check_to_on_mtrl_000.png (OK)
   66236 res/drawable-mdpi-v4/abc_btn_check_to_on_mtrl_015.png (OK)
   66748 res/drawable-mdpi-v4/abc_btn_radio_to_on_mtrl_000.png (OK)
   67260 res/drawable-mdpi-v4/abc_btn_radio_to_on_mtrl_015.png (OK)
   67844 res/drawable-mdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png (OK)
   69264 res/drawable-mdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png (OK)
   70336 res/drawable-mdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png (OK)
   71472 res/drawable-mdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png (OK)
   72688 res/drawable-mdpi-v4/abc_cab_background_top_mtrl_alpha.9.png (OK)
   72996 res/drawable-mdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
   73400 res/drawable-mdpi-v4/abc_ic_clear_mtrl_alpha.png (OK)
   73728 res/drawable-mdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png (OK)
   74076 res/drawable-mdpi-v4/abc_ic_go_search_api_mtrl_alpha.png (OK)
   74312 res/drawable-mdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
   74572 res/drawable-mdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
   75040 res/drawable-mdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png (OK)
   75284 res/drawable-mdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png (OK)
   75604 res/drawable-mdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png (OK)
   75872 res/drawable-mdpi-v4/abc_ic_menu_share_mtrl_alpha.png (OK)
   76500 res/drawable-mdpi-v4/abc_ic_search_api_mtrl_alpha.png (OK)
   77248 res/drawable-mdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png (OK)
   77736 res/drawable-mdpi-v4/abc_list_divider_mtrl_alpha.9.png (OK)
   77984 res/drawable-mdpi-v4/abc_list_focused_holo.9.png (OK)
   78288 res/drawable-mdpi-v4/abc_list_longpressed_holo.9.png (OK)
   78584 res/drawable-mdpi-v4/abc_list_pressed_holo_dark.9.png (OK)
   78880 res/drawable-mdpi-v4/abc_list_pressed_holo_light.9.png (OK)
   79184 res/drawable-mdpi-v4/abc_list_selector_disabled_holo_dark.9.png (OK)
   79504 res/drawable-mdpi-v4/abc_list_selector_disabled_holo_light.9.png (OK)
   79820 res/drawable-mdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png (OK)
   80496 res/drawable-mdpi-v4/abc_popup_background_mtrl_mult.9.png (OK)
   81436 res/drawable-mdpi-v4/abc_scrubber_control_off_mtrl_alpha.png (OK)
   81744 res/drawable-mdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png (OK)
   82044 res/drawable-mdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png (OK)
   82412 res/drawable-mdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png (OK)
   82708 res/drawable-mdpi-v4/abc_scrubber_track_mtrl_alpha.9.png (OK)
   82988 res/drawable-mdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
   83412 res/drawable-mdpi-v4/abc_switch_track_mtrl_alpha.9.png (OK)
   83928 res/drawable-mdpi-v4/abc_tab_indicator_mtrl_alpha.9.png (OK)
   84212 res/drawable-mdpi-v4/abc_textfield_activated_mtrl_alpha.9.png (OK)
   84488 res/drawable-mdpi-v4/abc_textfield_default_mtrl_alpha.9.png (OK)
   84772 res/drawable-mdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png (OK)
   85052 res/drawable-mdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png (OK)
   85322 res/drawable-v21/abc_action_bar_item_background_material.xml (OK - compressed)
   85585 res/drawable-v21/abc_btn_colored_material.xml (OK - compressed)
   86275 res/drawable-v23/abc_control_background_material.xml (OK - compressed)
   86572 res/drawable-xhdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png (OK)
   86956 res/drawable-xhdpi-v4/abc_btn_check_to_on_mtrl_000.png (OK)
   87396 res/drawable-xhdpi-v4/abc_btn_check_to_on_mtrl_015.png (OK)
   88036 res/drawable-xhdpi-v4/abc_btn_radio_to_on_mtrl_000.png (OK)
   88952 res/drawable-xhdpi-v4/abc_btn_radio_to_on_mtrl_015.png (OK)
   90040 res/drawable-xhdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png (OK)
   92304 res/drawable-xhdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png (OK)
   93916 res/drawable-xhdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png (OK)
   96264 res/drawable-xhdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png (OK)
   98964 res/drawable-xhdpi-v4/abc_cab_background_top_mtrl_alpha.9.png (OK)
   99284 res/drawable-xhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
   99788 res/drawable-xhdpi-v4/abc_ic_clear_mtrl_alpha.png (OK)
  100244 res/drawable-xhdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png (OK)
  100656 res/drawable-xhdpi-v4/abc_ic_go_search_api_mtrl_alpha.png (OK)
  100920 res/drawable-xhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
  101240 res/drawable-xhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
  102024 res/drawable-xhdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png (OK)
  102328 res/drawable-xhdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png (OK)
  102776 res/drawable-xhdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png (OK)
  103100 res/drawable-xhdpi-v4/abc_ic_menu_share_mtrl_alpha.png (OK)
  104104 res/drawable-xhdpi-v4/abc_ic_search_api_mtrl_alpha.png (OK)
  105288 res/drawable-xhdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png (OK)
  106092 res/drawable-xhdpi-v4/abc_list_divider_mtrl_alpha.9.png (OK)
  106340 res/drawable-xhdpi-v4/abc_list_focused_holo.9.png (OK)
  106668 res/drawable-xhdpi-v4/abc_list_longpressed_holo.9.png (OK)
  106968 res/drawable-xhdpi-v4/abc_list_pressed_holo_dark.9.png (OK)
  107268 res/drawable-xhdpi-v4/abc_list_pressed_holo_light.9.png (OK)
  107576 res/drawable-xhdpi-v4/abc_list_selector_disabled_holo_dark.9.png (OK)
  107928 res/drawable-xhdpi-v4/abc_list_selector_disabled_holo_light.9.png (OK)
  108272 res/drawable-xhdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png (OK)
  109484 res/drawable-xhdpi-v4/abc_popup_background_mtrl_mult.9.png (OK)
  111360 res/drawable-xhdpi-v4/abc_scrubber_control_off_mtrl_alpha.png (OK)
  111800 res/drawable-xhdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png (OK)
  112296 res/drawable-xhdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png (OK)
  112944 res/drawable-xhdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png (OK)
  113252 res/drawable-xhdpi-v4/abc_scrubber_track_mtrl_alpha.9.png (OK)
  113544 res/drawable-xhdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
  114120 res/drawable-xhdpi-v4/abc_switch_track_mtrl_alpha.9.png (OK)
  114948 res/drawable-xhdpi-v4/abc_tab_indicator_mtrl_alpha.9.png (OK)
  115248 res/drawable-xhdpi-v4/abc_textfield_activated_mtrl_alpha.9.png (OK)
  115536 res/drawable-xhdpi-v4/abc_textfield_default_mtrl_alpha.9.png (OK)
  115832 res/drawable-xhdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png (OK)
  116120 res/drawable-xhdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png (OK)
  116400 res/drawable-xxhdpi-v4/abc_ab_share_pack_mtrl_alpha.9.png (OK)
  116792 res/drawable-xxhdpi-v4/abc_btn_check_to_on_mtrl_000.png (OK)
  117248 res/drawable-xxhdpi-v4/abc_btn_check_to_on_mtrl_015.png (OK)
  118060 res/drawable-xxhdpi-v4/abc_btn_radio_to_on_mtrl_000.png (OK)
  119396 res/drawable-xxhdpi-v4/abc_btn_radio_to_on_mtrl_015.png (OK)
  120956 res/drawable-xxhdpi-v4/abc_btn_rating_star_off_mtrl_alpha.png (OK)
  123312 res/drawable-xxhdpi-v4/abc_btn_rating_star_on_mtrl_alpha.png (OK)
  124436 res/drawable-xxhdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png (OK)
  128284 res/drawable-xxhdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png (OK)
  131180 res/drawable-xxhdpi-v4/abc_cab_background_top_mtrl_alpha.9.png (OK)
  131512 res/drawable-xxhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
  132068 res/drawable-xxhdpi-v4/abc_ic_clear_mtrl_alpha.png (OK)
  132556 res/drawable-xxhdpi-v4/abc_ic_commit_search_api_mtrl_alpha.png (OK)
  132952 res/drawable-xxhdpi-v4/abc_ic_go_search_api_mtrl_alpha.png (OK)
  133216 res/drawable-xxhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
  133648 res/drawable-xxhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
  134676 res/drawable-xxhdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png (OK)
  135048 res/drawable-xxhdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png (OK)
  135648 res/drawable-xxhdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png (OK)
  136056 res/drawable-xxhdpi-v4/abc_ic_menu_share_mtrl_alpha.png (OK)
  137432 res/drawable-xxhdpi-v4/abc_ic_search_api_mtrl_alpha.png (OK)
  139348 res/drawable-xxhdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png (OK)
  140364 res/drawable-xxhdpi-v4/abc_list_divider_mtrl_alpha.9.png (OK)
  140616 res/drawable-xxhdpi-v4/abc_list_focused_holo.9.png (OK)
  140948 res/drawable-xxhdpi-v4/abc_list_longpressed_holo.9.png (OK)
  141256 res/drawable-xxhdpi-v4/abc_list_pressed_holo_dark.9.png (OK)
  141564 res/drawable-xxhdpi-v4/abc_list_pressed_holo_light.9.png (OK)
  141880 res/drawable-xxhdpi-v4/abc_list_selector_disabled_holo_dark.9.png (OK)
  142284 res/drawable-xxhdpi-v4/abc_list_selector_disabled_holo_light.9.png (OK)
  142680 res/drawable-xxhdpi-v4/abc_menu_hardkey_panel_mtrl_mult.9.png (OK)
  144548 res/drawable-xxhdpi-v4/abc_popup_background_mtrl_mult.9.png (OK)
  147416 res/drawable-xxhdpi-v4/abc_scrubber_control_off_mtrl_alpha.png (OK)
  147912 res/drawable-xxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png (OK)
  148600 res/drawable-xxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png (OK)
  149500 res/drawable-xxhdpi-v4/abc_scrubber_primary_mtrl_alpha.9.png (OK)
  149808 res/drawable-xxhdpi-v4/abc_scrubber_track_mtrl_alpha.9.png (OK)
  150104 res/drawable-xxhdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
  150788 res/drawable-xxhdpi-v4/abc_switch_track_mtrl_alpha.9.png (OK)
  151936 res/drawable-xxhdpi-v4/abc_tab_indicator_mtrl_alpha.9.png (OK)
  152240 res/drawable-xxhdpi-v4/abc_textfield_activated_mtrl_alpha.9.png (OK)
  152536 res/drawable-xxhdpi-v4/abc_textfield_default_mtrl_alpha.9.png (OK)
  152840 res/drawable-xxhdpi-v4/abc_textfield_search_activated_mtrl_alpha.9.png (OK)
  153132 res/drawable-xxhdpi-v4/abc_textfield_search_default_mtrl_alpha.9.png (OK)
  153416 res/drawable-xxxhdpi-v4/abc_btn_check_to_on_mtrl_000.png (OK)
  153796 res/drawable-xxxhdpi-v4/abc_btn_check_to_on_mtrl_015.png (OK)
  154432 res/drawable-xxxhdpi-v4/abc_btn_radio_to_on_mtrl_000.png (OK)
  155532 res/drawable-xxxhdpi-v4/abc_btn_radio_to_on_mtrl_015.png (OK)
  156848 res/drawable-xxxhdpi-v4/abc_btn_switch_to_on_mtrl_00001.9.png (OK)
  160464 res/drawable-xxxhdpi-v4/abc_btn_switch_to_on_mtrl_00012.9.png (OK)
  164404 res/drawable-xxxhdpi-v4/abc_ic_ab_back_mtrl_am_alpha.png (OK)
  164724 res/drawable-xxxhdpi-v4/abc_ic_clear_mtrl_alpha.png (OK)
  165380 res/drawable-xxxhdpi-v4/abc_ic_menu_copy_mtrl_am_alpha.png (OK)
  165864 res/drawable-xxxhdpi-v4/abc_ic_menu_cut_mtrl_alpha.png (OK)
  167128 res/drawable-xxxhdpi-v4/abc_ic_menu_moreoverflow_mtrl_alpha.png (OK)
  167572 res/drawable-xxxhdpi-v4/abc_ic_menu_paste_mtrl_am_alpha.png (OK)
  168328 res/drawable-xxxhdpi-v4/abc_ic_menu_selectall_mtrl_alpha.png (OK)
  168804 res/drawable-xxxhdpi-v4/abc_ic_menu_share_mtrl_alpha.png (OK)
  170448 res/drawable-xxxhdpi-v4/abc_ic_search_api_mtrl_alpha.png (OK)
  172056 res/drawable-xxxhdpi-v4/abc_ic_voice_search_api_mtrl_alpha.png (OK)
  173424 res/drawable-xxxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_000.png (OK)
  174188 res/drawable-xxxhdpi-v4/abc_scrubber_control_to_pressed_mtrl_005.png (OK)
  175232 res/drawable-xxxhdpi-v4/abc_spinner_mtrl_am_alpha.9.png (OK)
  175832 res/drawable-xxxhdpi-v4/abc_switch_track_mtrl_alpha.9.png (OK)
  176948 res/drawable-xxxhdpi-v4/abc_tab_indicator_mtrl_alpha.9.png (OK)
  177230 res/drawable/abc_btn_borderless_material.xml (OK - compressed)
  177593 res/drawable/abc_btn_check_material.xml (OK - compressed)
  177929 res/drawable/abc_btn_colored_material.xml (OK - compressed)
  178222 res/drawable/abc_btn_default_mtrl_shape.xml (OK - compressed)
  178729 res/drawable/abc_btn_radio_material.xml (OK - compressed)
  179071 res/drawable/abc_cab_background_internal_bg.xml (OK - compressed)
  179362 res/drawable/abc_cab_background_top_material.xml (OK - compressed)
  179653 res/drawable/abc_dialog_material_background_dark.xml (OK - compressed)
  180089 res/drawable/abc_dialog_material_background_light.xml (OK - compressed)
  180511 res/drawable/abc_edit_text_material.xml (OK - compressed)
  181001 res/drawable/abc_item_background_holo_dark.xml (OK - compressed)
  181434 res/drawable/abc_item_background_holo_light.xml (OK - compressed)
  181885 res/drawable/abc_list_selector_background_transition_holo_dark.xml (OK - compressed)
  182215 res/drawable/abc_list_selector_background_transition_holo_light.xml (OK - compressed)
  182522 res/drawable/abc_list_selector_holo_dark.xml (OK - compressed)
  182974 res/drawable/abc_list_selector_holo_light.xml (OK - compressed)
  183424 res/drawable/abc_ratingbar_full_material.xml (OK - compressed)
  183768 res/drawable/abc_seekbar_thumb_material.xml (OK - compressed)
  184240 res/drawable/abc_seekbar_track_material.xml (OK - compressed)
  184787 res/drawable/abc_spinner_textfield_background_material.xml (OK - compressed)
  185311 res/drawable/abc_switch_thumb_material.xml (OK - compressed)
  185649 res/drawable/abc_tab_indicator_material.xml (OK - compressed)
  185988 res/drawable/abc_text_cursor_material.xml (OK - compressed)
  186336 res/drawable/abc_textfield_search_material.xml (OK - compressed)
  186733 res/layout/abc_action_bar_title_item.xml (OK - compressed)
  187272 res/layout/abc_action_bar_up_container.xml (OK - compressed)
  187624 res/layout/abc_action_bar_view_list_nav_layout.xml (OK - compressed)
  187948 res/layout/abc_action_menu_item_layout.xml (OK - compressed)
  188458 res/layout/abc_action_menu_layout.xml (OK - compressed)
  188846 res/layout/abc_action_mode_bar.xml (OK - compressed)
  189234 res/layout/abc_action_mode_close_item_material.xml (OK - compressed)
  189664 res/layout/abc_activity_chooser_view.xml (OK - compressed)
  190389 res/layout/abc_activity_chooser_view_list_item.xml (OK - compressed)
  191035 res/layout/abc_alert_dialog_button_bar_material.xml (OK - compressed)
  191792 res/layout/abc_alert_dialog_material.xml (OK - compressed)
  192976 res/layout/abc_dialog_title_material.xml (OK - compressed)
  193626 res/layout/abc_expanded_menu_layout.xml (OK - compressed)
  193954 res/layout/abc_list_menu_item_checkbox.xml (OK - compressed)
  194331 res/layout/abc_list_menu_item_icon.xml (OK - compressed)
  194776 res/layout/abc_list_menu_item_layout.xml (OK - compressed)
  195464 res/layout/abc_list_menu_item_radio.xml (OK - compressed)
  195845 res/layout/abc_popup_menu_item_layout.xml (OK - compressed)
  196602 res/layout/abc_screen_content_include.xml (OK - compressed)
  196978 res/layout/abc_screen_simple.xml (OK - compressed)
  197503 res/layout/abc_screen_simple_overlay_action_mode.xml (OK - compressed)
  197990 res/layout/abc_screen_toolbar.xml (OK - compressed)
  198795 res/layout/abc_search_dropdown_item_icons_2line.xml (OK - compressed)
  199656 res/layout/abc_search_view.xml (OK - compressed)
  200966 res/layout/abc_select_dialog_material.xml (OK - compressed)
  201472 res/layout/notification_media_action.xml (OK - compressed)
  201899 res/layout/notification_media_cancel_action.xml (OK - compressed)
  202365 res/layout/notification_template_big_media.xml (OK - compressed)
  203175 res/layout/notification_template_big_media_narrow.xml (OK - compressed)
  203989 res/layout/notification_template_lines.xml (OK - compressed)
  204936 res/layout/notification_template_media.xml (OK - compressed)
  205617 res/layout/notification_template_part_chronometer.xml (OK - compressed)
  206058 res/layout/notification_template_part_time.xml (OK - compressed)
  206494 res/layout/select_dialog_item_material.xml (OK - compressed)
  206940 res/layout/select_dialog_multichoice_material.xml (OK - compressed)
  207487 res/layout/select_dialog_singlechoice_material.xml (OK - compressed)
  208035 res/layout/support_simple_spinner_dropdown_item.xml (OK - compressed)
  208400 resources.arsc (OK)
  395361 classes.dex (OK - compressed)
 1869149 LICENSE.txt (OK - compressed)
 1870022 junit/runner/smalllogo.gif (OK - compressed)
 1870243 junit/runner/logo.gif (OK - compressed)
 1870549 LICENSE-junit.txt (OK - compressed)
 1874825 mockito-extensions/org.mockito.plugins.MockMaker (OK - compressed)
 1874974 mockito-extensions/org.mockito.plugins.StackTraceCleanerProvider (OK - compressed)
 1875066 LICENSE (OK - compressed)
 1875754 NOTICE (OK - compressed)
 1875933 asm-license.txt (OK - compressed)
 1876808 cglib-license.txt (OK - compressed)
 1880854 org/mockito/internal/creation/jmock/jmock-license.txt (OK - compressed)
 1881738 org/mockito/internal/matchers/apachecommons/commons-lang-license.txt (OK - compressed)
Verification succesful


```

```


```
