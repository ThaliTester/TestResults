#### Test (Fail) 65430011 Build Logs


```


```

```
Already up-to-date.


```

```
commit 8cdd362e91bc03fe31b4bd1ba2d3950bb8ed30a2
Merge: 208133c ec57228
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 18 18:02:49 2016 +0200

    Merge pull request #55 from thaliproject/vNext_tompaana_hardening
    
    Fix for service data issue seen on some devices

commit ec57228d30ce75fa546f253c18d5537482527533
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 18 10:48:38 2016 +0200

    Commit to #608 (of Thali_CordovaPlugin): Added "don't care" option for advertisement data type.

commit 21f4ee0556e19a248e8b96e96cc4ecaf612b632f
Merge: 6f3fd3e e4c1518
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 18 08:38:41 2016 +0200

    Merge remote-tracking branch 'origin/vNext_tompaana_testing' into vNext_tompaana_hardening

commit 6f3fd3e8ad945e4b056aebfa248f6daed1bce4b6
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Mar 17 16:27:38 2016 +0200

    Added some more logging and removed possible errors.

commit 208133c087e1a689993677c7ab17721f6ae8aaa6
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Mar 16 16:38:18 2016 +0200

    Hot fix: Manufacturer data parsing was error prone when receiving e.g. beacon advertisements. Pushing this straight to master since manufacturer data is not used by default and thus, this will not - even in the worst case - break anything.

commit e4c151812809e09bc52bfae8fc53f29e4142aa21
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Mar 16 16:33:33 2016 +0200

    Minor change.

commit d982fbecabd4dc6872a6337b9faf772a4628b0f0
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Mar 16 16:30:40 2016 +0200

    Fixed manufacturer data parsing crash bug.

commit e8ae9e0afce5b5cb79305d44b69b24d3338cfd19
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Mar 16 15:09:04 2016 +0200

    Commit to #608 (of Thali_CordovaPlugin): Created a test version of the library, which by default uses manufacturer data for advertising and can handle both service and manufacturer data when scanning.

commit 43fc2226db00e53a3f0584db2b3b7b357624d334
Merge: 9181e61 91ee4b5
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Mar 16 14:25:28 2016 +0200

    Merge remote-tracking branch 'origin/master' into vNext_tompaana_testing

commit 91ee4b5ccddf35bf86c276a2c2c66f3e11039b40
Merge: c4cca7d 81683be
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Mar 16 06:34:21 2016 +0200

    Merge pull request #54 from thaliproject/vNext_tompaana
    
    Fixes and hardening, several issues addressed

commit 81683be7b0a8aae792f05f18af8271a3d339ea8b
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Mar 15 11:55:32 2016 +0200

    Commit to #622: Removed redundant Wi-Fi state and Bluetooth state events from DiscoveryManager interface.

commit 9181e617f51c47fd26a033334db2940f9bbacff2
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Mar 14 15:58:37 2016 +0200

    Updated the Bluetooth name and the simplified hanshake message to match the ones in Thali Cordova Plug-in unit test app.

commit 62c32217b889648a1a5c17bb65cd4bb2874303a4
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Mar 14 15:23:02 2016 +0200

    Changes for testing doze and standby modes
    
    Added the possibility to set the peer name in settings. When the peer name is empty, the library will use the simple handshake message whose length is only one byte. The received handshake message can be either the short, simple or the long one - both are validated the same. This is essential when testing together with the Thali Cordova Plug-in unit test app.

commit 67696c24bb54a57634064586212b418f61373cf5
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Sat Mar 12 13:07:23 2016 +0200

    Minor fix based on Yaron's review.

commit fc418b5802d8313d4b3d5012887c540f38c0e176
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 11 16:13:19 2016 +0200

    Minor change.

commit 3ab78ac9bd62f289d80b6711925c8aefcbefd94c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 11 16:12:14 2016 +0200

    Minor fix: The service data is now printed as hex string in the logs.

commit 0b0a4ab8dc13cbe5ac0c52b67863f053a6124533
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 11 15:58:50 2016 +0200

    Minor change.

commit b46af69e40a516468cbea113dac2aa3dbaf4a8ae
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 11 15:54:47 2016 +0200

    Several changes:
    * Possible fix to #49: Auto-connect shouldn't now happen when disconnected during closing of the app.
    * Possible fix to #51: Method calling `notifyDataSetChanged` in `PeerListFragment` are now synchronous.
    * Fixed #53: If the creation of Bluetooth server socket now fails consecutively 10 times, the connection manager is stopped.
    * Updated the BtConnectorLib version number from 0.2.6 to 0.2.7.

commit 335117e4c32e1b6c92bf8cd70651be3dbf0851f2
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 11 14:10:36 2016 +0200

    Commit to #50: Added @RoundSparrow's fix for int8ArrayToBluetoothAddress method.

commit c4cca7ddd01d3cab772eb562815a159c1cb5766a
Merge: b03bb8e 64fdf4a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 4 15:59:49 2016 +0200

    Merge pull request #48 from thaliproject/vNext_tompaana_herra_47
    
    Fix for issue #47: Outgoing connections can now be initiated even when we are not listening for incoming connections.

commit 64fdf4a2ad7aea1203e0dc9ca7609c305293bdda
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 4 15:58:24 2016 +0200

    Commit to #47: Fixes based on findings in Thali Cordova Plug-in unit tests; the connection manager state changes were not completely reliable.

commit b550ceac3a077461dc94984d773dd8af71272bb0
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 4 13:59:56 2016 +0200

    Commit to #47: Minor changes.

commit 67ae8e452886e4ceaa3ffb9056f688ac8af8b4af
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Mar 4 13:51:55 2016 +0200

    Commit to #47: Outgoing connection can now be initiated even when we are not listening for incoming connections.

commit b03bb8e14db1bb4ef5e5839450c492183509bada
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Mar 2 13:18:51 2016 +0200

    Commit to #576 of Thali_CordovaPlugin: Fixed a bug that was causing second attempts to connect after disconnecting to fail. The bug was caused by not closing the Bluetooth server socket after a connection was established.

commit 392b6cd58683776af1e3a7895f8290493a1b462e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Mar 1 23:01:42 2016 +0200

    Fixed a crash bug in Native Test app.

commit a86de96ec7595ef76cddce2b59dbe442fd97bd37
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Mar 1 15:24:41 2016 +0200

    Fix: The peers should be cleared when resetting.

commit e913edef59472b7fccb952115081e381bc215356
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Mar 1 11:58:21 2016 +0200

    Implemented Reset option. It recreates both connection and discovery managers.

commit d4032fe50df28066b1f05202de36d299e814dd08
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Feb 29 16:03:50 2016 +0200

    Fixed BLE scanner state: Was never changed to RUNNING - only STARTING.

commit 8c6069433b2f6b018fad12ce4ba2a2728a9f1a00
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 24 13:18:10 2016 +0200

    Updated the version number of the library.

commit e8685b4480fec180d4081834494a93c5584cb4a9
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Feb 23 17:20:00 2016 +0200

    Hot fix: WifiManager instance should be available without initialization of WifiDirectManager.

commit 033ded87fd0608eaa36561bdf6ca13e257f0046e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Feb 23 14:47:53 2016 +0200

    Hot fix: When Bluetooth is disabled, multi advertisement support check should return NOT_RESOLVED instead of NOT_SUPPORTED.

commit adc354434e3d4c7b1841d6124a943330de903306
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 17 18:25:29 2016 +0200

    Minor fixes to icons.

commit b607aa7e6b21dee12767a9d851ecf8e8b6cfdfdf
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 17 18:11:50 2016 +0200

    Added new icons.

commit fe800b7b9d2167c0144a2ab36115b748922c8864
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 17 17:18:17 2016 +0200

    Fixes to native test app.

commit 2a8ff090f9eb19e326ee4908c2a2e2ac54e8a6b5
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 17 12:34:44 2016 +0200

    Commit to #526: The legacy handshake is now disabled by default.

commit 639795356c673e9ed02934770dbef7f4e34e5f46
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Feb 16 12:24:52 2016 +0200

    Minor changes.

commit c5ca64f05c6f165e810431db7b8fe4d2b1f70b4e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Feb 15 18:31:59 2016 +0200

    Commit to #533: Extended the discovery manager interface.

commit 359eef4127111ba8bdf8d0b37bbb8651760e050e
Merge: 80c9f78 04afcde
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Feb 12 16:16:12 2016 +0200

    Merge pull request #44 from thaliproject/vNext_tompaana_397
    
    vNext compliance

commit 04afcdeff332a2f4922d125471a2c74b618f1e5f
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Feb 12 16:15:23 2016 +0200

    Minor fix.

commit 7b168d9edce0d40f9835716e8c774ca3141c66e4
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Feb 11 13:28:43 2016 +0200

    Updated the library version number for native test app.

commit c628214fd91478805d4fb787627226e3b6861704
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Feb 11 13:27:42 2016 +0200

    Commit to #397: Updated the version number due to changed interface.

commit 49ee997161d2fd44c1cf49a8f34a359611427a70
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Feb 11 13:19:02 2016 +0200

    Commit to #397: Fix based on Yaron's review.

commit 6bbfc6187f2f273cf1679d5c584aee028b80543c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Feb 11 12:16:16 2016 +0200

    Moved peer name to AbstractBluetoothConnectivityAgent.

commit badfa0c73d668ac0e1cd5cb93bfa607cc4859c4a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 10 15:39:48 2016 +0200

    Fixed few regressions.

commit eb9a9cf9a7c2f36675e95659429632aaa980f444
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 10 15:07:11 2016 +0200

    Minor fix.

commit d53bd997bfee0a27c50c414cd8dce13a8fa7298a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 10 15:00:10 2016 +0200

    Added possibility to add more than one listener to peer model. This way the model can be used by the client app too.

commit 63751996be221ea3d2aa04cfe7d4cc5e2764114d
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 10 14:54:29 2016 +0200

    Commit to #397: Manually merged fixes from #45 (Minor stuff).

commit 23cbfcb4f8e32948d4b9511bfb869dd80af6a275
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 10 14:43:44 2016 +0200

    Commit to #397: The library now offers a full support for starting/stopping discovery and advertising separately.

commit 0f343aeb970336d9df629927809cb81e61c05f03
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 10 14:17:01 2016 +0200

    Commit to #397: Implemented possibility to start advertising separately.

commit 23e7f0e25cc0903a4980e3a2c7b5942a2f554f6d
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 10 10:17:25 2016 +0200

    Commit to #397: Simplified identity string by removing peer ID.

commit f925694b7b471ccfcdeca9be1c3f173e7a4e0c15
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Feb 9 17:58:18 2016 +0200

    Commit to #397: Minor changes.

commit d3221561f745a105700c3be2a368d0aeca0fd5df
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Feb 9 15:16:10 2016 +0200

    Commit to #397: Several changes based on Yaron's review.

commit 753e0172f5a2547c29e304bb1b9e142950cd1304
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Feb 9 12:24:38 2016 +0200

    Commit to #397: Some fixes.

commit 4e5de148a1d630994cf933456afb67d9745dd796
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Feb 4 12:31:33 2016 +0200

    Commit to #397: Fixes based on Yaron's review.

commit a18957ce144a2e4826fa651788ff00bd914cfb77
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 3 18:04:14 2016 +0200

    Commit to #397: Fix to setting the discovery mode.

commit cf189a584457a748f89918f998e4c5eecfee4e8a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 3 15:53:58 2016 +0200

    Commit to #397: First candidate for peer review.

commit f578a4b88bb164bfba7ce23d4f8e6bd4f774dba5
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Feb 3 14:54:36 2016 +0200

    Commit to #397: Verified that the native tests work with the new service data based BLE peer discovery.

commit 33578f6271363c914f7cec855bfe19b64592abba
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Feb 2 18:00:11 2016 +0200

    Commit to #397: First commit with working service data based peer discovery.

commit de4fa43c26f0f36031f521171499f68ea1b20939
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Feb 2 14:28:24 2016 +0200

    Commit to #397: Changing from manufacturer data to service data (BLE peer discovery).

commit 80c9f786230e6cf35611c0529e9d17b599a28750
Merge: efbaac1 c07e8e4
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Feb 2 10:22:12 2016 +0200

    Merge pull request #43 from thaliproject/story_001_tompaana_36
    
    Story 001 tompaana 36

commit c07e8e483f94431b2a7866a291c262a300c66c70
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Sun Jan 31 14:31:08 2016 +0200

    Commit to #36: Fixed based on Yaron's review.

commit 1293c6317977e4ffe888e0761abacb62bb2524d3
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Jan 29 17:53:00 2016 +0200

    Minor fix: Used to get an invalid log message in ConnectionManagerSettings.setInsecureRfcommSocketPortNumber

commit 4079914f810551174685fc74c632ffd04f2d15c2
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Jan 29 16:25:01 2016 +0200

    Improved permission request process.

commit b73821382f5146c6e760a65e27ff8ae5d4f71133
Merge: 60bf0a6 af9efd2
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 28 13:06:20 2016 +0200

    Merge branch 'story_001_tompaana_36' of https://github.com/thaliproject/Thali_CordovaPlugin_BtLibrary into story_001_tompaana_36
    
    Conflicts:
    	LICENSE

commit 60bf0a6543dfed2d86f07e2d4e54780c71e56911
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 28 12:56:51 2016 +0200

    Commit to #36: Fixed native tests.

commit 5726ee7552bcf8062f3a93363d7cb61c1f8fa92b
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 27 18:06:33 2016 +0200

    Commit to #36: I still need to figure out how to fix the native tests.

commit aa12b80135efa057be61c092e1b86f41af119898
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 27 14:21:20 2016 +0200

    Commit to #36: Created a sub-class for DiscoveryManager to handle Bluetooth MAC address resolution.

commit 651a9b9f413752b274a16e88ee30e6888e5eb8e4
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 27 10:03:37 2016 +0200

    Commit to #36: Added Bluetooth MAC address hack for Marshmallow.

commit a3a755edcab93ca5ae53f09a43d5a95db83f82aa
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 26 19:20:02 2016 +0200

    Commit to #36: Minor change.

commit 9adf53eb9e9a78575e3d9bc11f060c3329441f9a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 26 18:27:08 2016 +0200

    Commit to #36: Marshmallows still provide fake addresses for each other.

commit f4236e0a930c1ce2cb4a2453984ff053f498d633
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 19:50:33 2016 +0200

    Commit to #36: Minor fixes.

commit 230918cb7b420ac60e6fa68a0da17bc979d4e1fc
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 19:10:49 2016 +0200

    Commit to #36: Minor change

commit 773f4c5d239be75c3f7cc43434c96addbbc07dc6
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 19:04:01 2016 +0200

    Commit to #36: Looks like the Bluetooth GATT works, but is just slow.

commit 5106ffdb7829242cc37c767994dae3221436efa0
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 17:43:54 2016 +0200

    Commit to #36: Another minor fix.

commit 29bf1870ec53c5f1b9f48844f005246a25843c88
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 17:34:23 2016 +0200

    Commit to #36: Minor fixes.

commit 53730a9ddaf6c59f4bb10573c86d7f46f566616c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 16:14:40 2016 +0200

    Commit to #36: Crash bug fix.

commit fe7aecec15b2dd02ae9adb692ead3184986775cd
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Sun Jan 24 16:35:34 2016 +0200

    Commit to #36: Added methods to start and stop receiving MAC address.

commit 98ed27955f5933658ebfa7a546766dd533e67ed2
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Jan 22 17:17:23 2016 +0200

    Commit to #36: A lot of cleaning up done and simplifying the state machine of BlePeerDiscoverer.

commit 3b857c0759d2f06c597d72907560d841f0fd751a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 21 19:56:46 2016 +0200

    Commit to #36: Minor fix

commit 9c5d86c4c714c05ecd49e76bb3fc1ed4dbdb23a6
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 21 19:37:30 2016 +0200

    Commit to #36: Some cleanup

commit f2718c3971886f9ca4deef0ef18be0d796410a0a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 21 15:59:32 2016 +0200

    Commit to #36: Bluetooth MAC address resolution via Bluetooth GATT characteristic finally working

commit 663d44ed480b3272923c69bf8bcae2b6e195e00e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 20 16:03:38 2016 +0200

    Commit to #36: Still working on GATT server.

commit d1c257f746017c8ffd37aac986098a24844cd572
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 19 17:23:35 2016 +0200

    Commit to #36: Reading a GATT characteristic is not yet finished, but getting very close.

commit 8d31576222c2c5e36e01e7e86e2f656b31a4a7d1
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 19 12:15:43 2016 +0200

    Commit to #36: Added BluetoothGattManager.java

commit 4f9fee8ad76eb54732d1727a0f77613f3231b35c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 19 07:27:57 2016 +0200

    Commit to #36: Minor changes

commit f6a804d25af693a60cdc4d5f65771f3e0f5a0955
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 18 17:17:23 2016 +0200

    Commit to #36: Fix to BLE advertisement support check.

commit 7ffccb781842f1cc10b1d90086a8207c56ac7620
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 18 16:25:11 2016 +0200

    Commit to #36: Implemented request IDs for "Bro mode". Added PeerModel.

commit 7d99e101a903fdcb214736c66e7de390c42840f0
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 14 18:10:51 2016 +0200

    Commit to #36: Minor clean up - Starting Bluetooth device discovery still breaks the app for second attempt.

commit 1ccf7583c4344cd5350656ac92322177486d027f
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 14 17:25:35 2016 +0200

    Commit to #36: Added automation to "bro mode" and added persistent settings to library. Noticed a weird BLE scanner bug - cannot start the second time the app is launched and on the third time I get a blank screen.

commit d90aa3e62044a2d95dea645c1cf41d1be7624fcc
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 14 15:28:29 2016 +0200

    Commit to #36: The Marshmallow workaround fixed and verified with Nexus 6. Needs some work still.

commit 005e2ba0bfdbfa07505693532e76376af2361330
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 14 10:46:46 2016 +0200

    Commit to #36: Changed minSdkVersion to 21 and implemented permission check request.

commit ad10a774a1113332ded0d53c1579f161f294ed60
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 13 11:06:44 2016 +0200

    Commit to #36: Some cleanup.

commit 29d0262f74203de63e2383b1a0959697ffd4b01b
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 13 11:02:04 2016 +0200

    Commit to #36: Added permission to app.

commit d4566e2fcfaa8db31565f7ec4b7e866b102c4a84
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 13 10:54:11 2016 +0200

    Commit to #36: Added permission ACCESS_COARSE_LOCATION to BtConnectorLib.

commit 89f3ebe75445a20818ce0c41f2977cecc761f010
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 12 18:30:08 2016 +0200

    Commit to #36: Minor change

commit ca33cf020017d810816eba4e11471e6fe8778834
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 12 18:18:54 2016 +0200

    Commit to #36: Implemented FindMyBluetoothAddressTest.

commit eba67eeb0e6af8b05ab47510bd21543a23ba32d8
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 12 15:53:53 2016 +0200

    Commit to #36: Implemented BluetoothDeviceDiscoverer and verified the functionality on Lollipop.

commit a3735fa3b018bde0e244b1cbabee8f6759c27be1
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 12 13:19:39 2016 +0200

    Commit to #36: Implemented simple test for finding peers to verify the functionality of the test engine.

commit 90b72974e23709e2155ce257b76fa929aad0d3d2
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 11 17:05:44 2016 +0200

    Commit to #36: Moved discovery manager mode to DiscoveryManagerSettings.

commit 59ec2b2a8acc6ef00165050f30b7aa93919a4a11
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 11 16:21:44 2016 +0200

    Commit to #36: Fixed settings issue with having two connection engines (the other one is the test engine).

commit 2e551a5af10f78dcc2dbb418b9a2f69f9afaf14a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 11 14:05:59 2016 +0200

    Commit to #36: Updated the package name in code files to fix the build errors.

commit 06aa263169339ae6bcc1d3804fd28162af32efd6
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 11 13:56:28 2016 +0200

    Commit to #36: Renamed the native sample to native test.

commit af9efd2585aab37352768fcc7f325d6c68084782
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 28 12:56:51 2016 +0200

    Commit to #36: Fixed native tests.

commit d49d53e0ff3144a38b02a7cd9a85d107ab1d0e86
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 27 18:06:33 2016 +0200

    Commit to #36: I still need to figure out how to fix the native tests.

commit cb674062b1ae02a090d32f119a34682da7778b96
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 27 14:21:20 2016 +0200

    Commit to #36: Created a sub-class for DiscoveryManager to handle Bluetooth MAC address resolution.

commit f2d905187fef57d9b220e8a52ea4b97af6f21fad
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 27 10:03:37 2016 +0200

    Commit to #36: Added Bluetooth MAC address hack for Marshmallow.

commit 1d53c4d745ac0e4c10866075080b659b613181e3
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 26 19:20:02 2016 +0200

    Commit to #36: Minor change.

commit fb4f250df46c839f552e2067730db081a3bfcb96
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 26 18:27:08 2016 +0200

    Commit to #36: Marshmallows still provide fake addresses for each other.

commit 65ca26891cf7e0a33c0f64d3eab0857dbd77e84b
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 19:50:33 2016 +0200

    Commit to #36: Minor fixes.

commit ea6789c72b27241b1b05b6860405151d1e11b39f
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 19:10:49 2016 +0200

    Commit to #36: Minor change

commit 753b4275615bd0b1560395c2cbda6ccec68f5239
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 19:04:01 2016 +0200

    Commit to #36: Looks like the Bluetooth GATT works, but is just slow.

commit ab080971320eed5df60ca1a6c7b3b03f9a0446a8
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 17:43:54 2016 +0200

    Commit to #36: Another minor fix.

commit f5cf7bbe3ed5ee5ae83250b44380b3e2406d219a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 17:34:23 2016 +0200

    Commit to #36: Minor fixes.

commit bd6ecce2ea509b03ccf749bff0e0591abbd0d51e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 25 16:14:40 2016 +0200

    Commit to #36: Crash bug fix.

commit 606352638900d40488b317f6f940bd5d39d85655
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Sun Jan 24 16:35:34 2016 +0200

    Commit to #36: Added methods to start and stop receiving MAC address.

commit a0db5cf6c1cc9e1a950e32029068948f12978aa5
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Jan 22 17:17:23 2016 +0200

    Commit to #36: A lot of cleaning up done and simplifying the state machine of BlePeerDiscoverer.

commit 7824fc32b548aa063a428691ee2bb4c5f7c4c6fe
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 21 19:56:46 2016 +0200

    Commit to #36: Minor fix

commit de3f30534b2eae3ef6a6a7ca4e1df78a6483c86a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 21 19:37:30 2016 +0200

    Commit to #36: Some cleanup

commit e085dffd6bd0df40e0589ce388c8cf1445c1bb8a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 21 15:59:32 2016 +0200

    Commit to #36: Bluetooth MAC address resolution via Bluetooth GATT characteristic finally working

commit d62e5942c8dd34c92453d5695374c5c37181142d
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 20 16:03:38 2016 +0200

    Commit to #36: Still working on GATT server.

commit 2c01d99c85d5b708d7b4ada7c0cefd9e51140db7
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 19 17:23:35 2016 +0200

    Commit to #36: Reading a GATT characteristic is not yet finished, but getting very close.

commit f0f99583ac11631808bee607ad0f25a4984835a5
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 19 12:15:43 2016 +0200

    Commit to #36: Added BluetoothGattManager.java

commit 2b668c9311bbcf42ce13fc92cbe9bd4302832e4d
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 19 07:27:57 2016 +0200

    Commit to #36: Minor changes

commit 93ecd3fc500e0e9fd5ae46a3f1e6f4958c6bd6c9
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 18 17:17:23 2016 +0200

    Commit to #36: Fix to BLE advertisement support check.

commit ae4bfa1865816af1c36b425202c995d443d31705
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 18 16:25:11 2016 +0200

    Commit to #36: Implemented request IDs for "Bro mode". Added PeerModel.

commit efbaac16530d133dd69bf56e39c49788379cff39
Author: Yaron Y Goland <yaronyg@users.noreply.github.com>
Date:   Thu Jan 14 10:06:35 2016 -0800

    Update LICENSE
    
    Added the MIT license header

commit 761b022112e07fa624ea3d6e3ea2af0221d68306
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 14 18:10:51 2016 +0200

    Commit to #36: Minor clean up - Starting Bluetooth device discovery still breaks the app for second attempt.

commit 7472d36f4761a8d8c4c285015adf9976abfb9a0e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 14 17:25:35 2016 +0200

    Commit to #36: Added automation to "bro mode" and added persistent settings to library. Noticed a weird BLE scanner bug - cannot start the second time the app is launched and on the third time I get a blank screen.

commit 8c0195e61581851c5dfb8c4fa4407032552cc608
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 14 15:28:29 2016 +0200

    Commit to #36: The Marshmallow workaround fixed and verified with Nexus 6. Needs some work still.

commit f40092288cb700e84d1cff28503352cd151d63ca
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 14 10:46:46 2016 +0200

    Commit to #36: Changed minSdkVersion to 21 and implemented permission check request.

commit 7a6c90f9cbfd1da95398ac930ce59ffbd3ae4d40
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 13 11:06:44 2016 +0200

    Commit to #36: Some cleanup.

commit 0e86814ab8513f6af44a8562b9b3aa959fbceefc
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 13 11:02:04 2016 +0200

    Commit to #36: Added permission to app.

commit ce97df2fcbf0030b65aa5289a1cc8330a4bda8d8
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Jan 13 10:54:11 2016 +0200

    Commit to #36: Added permission ACCESS_COARSE_LOCATION to BtConnectorLib.

commit 996ea556bcc53ac9b9323132b8d708bf2fe1ed21
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 12 18:30:08 2016 +0200

    Commit to #36: Minor change

commit 0e217fd59ce075aa2bb3da1c4409627ce459117e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 12 18:18:54 2016 +0200

    Commit to #36: Implemented FindMyBluetoothAddressTest.

commit 708f157ca7fe25f2a55180562b694301bc456813
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 12 15:53:53 2016 +0200

    Commit to #36: Implemented BluetoothDeviceDiscoverer and verified the functionality on Lollipop.

commit a73376ab4163e4297e75c3a72470e4ff26eb86ed
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 12 13:19:39 2016 +0200

    Commit to #36: Implemented simple test for finding peers to verify the functionality of the test engine.

commit 18c74fb712563f0bd32f2d101992f0d914316964
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 11 17:05:44 2016 +0200

    Commit to #36: Moved discovery manager mode to DiscoveryManagerSettings.

commit 256783152395756fe12319b0dd63695f61b47caf
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 11 16:21:44 2016 +0200

    Commit to #36: Fixed settings issue with having two connection engines (the other one is the test engine).

commit ac11c2375a2144b7cceed74b98328cb09d5fd8c7
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 11 14:05:59 2016 +0200

    Commit to #36: Updated the package name in code files to fix the build errors.

commit 6bf8b92db7dcf2d739ca0e065e92e99cb1ee64cf
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 11 13:56:28 2016 +0200

    Commit to #36: Renamed the native sample to native test.

commit 8d0e7c3fd70d3f0bf350c6ed2534f28b019e7875
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Jan 8 16:26:19 2016 +0200

    Hot fix: Changing the advertise and scan settings on the fly requires a restart.

commit dac95f0bc0f46860322b89b61d6ac4f50088326a
Merge: 554ff6f d46597c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 7 16:12:13 2016 +0200

    Merge pull request #35 from thaliproject/story_001_tompaana_34
    
    Merging as a hot fix.

commit d46597cd1d3c36ff32aca77f792bf3cd65854387
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 7 16:11:00 2016 +0200

    Commit to #34: Hot fix to DiscoveryManager class of the library.

commit 0dbdf0eb81abbae323e3eed27e6f8aa97bd7f0f3
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 7 11:35:49 2016 +0200

    Commit to #34: Changes to the options menu behavior.

commit 554ff6ff8f2c477136b824778ba51eef7214eac1
Merge: 91afb70 5500e08
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Jan 7 11:31:05 2016 +0200

    Merge pull request #31 from thaliproject/story_001_tompaana_30
    
    Merging Story 001 tompaana 30 to master

commit 5500e08c5163c73507398fd74cff520ec04a8b33
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 5 17:13:58 2016 +0200

    Commit to #30: Minor change I forgot to commit.

commit f9b088df803bebc8c92857e2baab2f1e346899a6
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Jan 5 15:37:46 2016 +0200

    Commit to #30: Added implementation to connect to multiple devices simultaneously.

commit 98b72318a9cf727cd78fccbaba51c90c55bc3937
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 4 19:10:02 2016 +0200

    Commit to #30: Minor fixes

commit ec21ffac306040561e6040b4fa5a8e0cf21216fc
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 4 17:38:31 2016 +0200

    Commit to #30: Switch default advertise and scan modes to balanced.

commit f823d8785d0c7ccf807da758387638541a0b570d
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 4 17:32:27 2016 +0200

    Commit to #30: Added ConnectionManagerSettings.

commit 5e1ec601902c2ea6a5ea9437335d8ec044694fe2
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Jan 4 16:47:29 2016 +0200

    Commit to #30: Exposed BLE settings and moved discovery manager settings into its own class, DiscoveryManagerSettings.

commit a04ff0656785932e6d6cf6c9029d427695d6d328
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Sat Jan 2 17:49:34 2016 +0200

    Commit to #30: Added icons connection icons and implemented the menus.

commit 38046f9292a5635355095c4bb62557a2f7a4c6c6
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Dec 30 19:44:27 2015 +0200

    Commit to #30: Implemented data sending feature.

commit d1721ceac3984132ab249fbc5a96bda7156bbf92
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Dec 30 16:10:56 2015 +0200

    Commit to 30: Added app settings.

commit c2f42cf76c3305db5f5f5dc8079d91b48890d52f
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 21 15:49:17 2015 +0200

    Commit to #30: Had to fix few peer discovery issues.

commit 9c9528ec2fc166a2967b7cc41e39527afd5dd3f3
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 18 18:21:58 2015 +0200

    Commit to #30: The peer name is updated, if discovered by Wi-Fi Direct.

commit 91afb70f7ea19dd2dfc5a4d8a20c385f8ee42bc6
Merge: 55b7c20 2e7a40b
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 18 15:00:48 2015 +0200

    Merge pull request #29 from thaliproject/story_001_tompaana_354
    
    Story 001 tompaana 354

commit 2e7a40b94744f08747001debd256fe32b2d9d1a9
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 18 14:52:27 2015 +0200

    Commit to #354: Typo fix.

commit a3bbc04dc212b81c757a2ad190993077565e409e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 17 15:41:01 2015 +0200

    Commit to #354: Minor change.

commit 72c83e661a767841c5b3142cf18c41cceb70dd13
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 17 15:36:04 2015 +0200

    Commit to #354: Modified peer expiration time.

commit db311b0963df6236d9f06f38d6d5d2eaee9181ee
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 17 15:24:23 2015 +0200

    Commit to #354: Fixed invalid ADVERTISEMENT_BYTE_COUNT value and disabled auto-restart from Wi-Fi Direct service advertiser.

commit e875ae4961e18ce13aed11b538a659b58ebb90ae
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 17 14:31:20 2015 +0200

    Commit to #354: Added check for scan result data length.

commit 6e8865c85f579651a13aeab6486175921464392a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 17 13:58:42 2015 +0200

    Commit to #354: Removed some magic numbers

commit c5a246a4c0163932506f940b9aee21cf8ba64468
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 17 13:26:41 2015 +0200

    Commit to #354: Hardened Wi-Fi Direct peer discovery and improved BLE peer discovery.

commit d2d9fc1138a26706ef5f21ba84246ae1b9a3cacd
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Dec 16 22:07:16 2015 +0200

    Commit to #354 (of Thali_CordovaPlugin): The first version of a working BLE peer discovery now implemented, but lacks peer name discovery.

commit 55b7c200ea12da8133dd8517f7c179e73e2e71ff
Merge: 98a0049 d432b6c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 16:54:34 2015 +0200

    Merge pull request #28 from thaliproject/story_001_tompaana_27
    
    Story 001 tompaana 27

commit d432b6cd4e00429746d99d8bee83efc30c6ef93d
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 15:21:09 2015 +0200

    Commit to #27: Fixed a crash bug

commit 9c97bffe8b36b13aca089bf9ec6fb56a498d07f4
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 14:40:38 2015 +0200

    Commit to #27: Fixed state change bug when disabling/enabling Bluetooth.

commit 1e744a63425d4ef982242e7d5a36b19654c23c87
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 14:26:17 2015 +0200

    Commit to #27: More minor logging related fixes.

commit ab32f27b599318714894004976f273a0851f9f17
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 14:03:41 2015 +0200

    Commit to #27: Minor logging related bug fix.

commit 4a329cefd96c5939fec5b0e2652223d595d4a961
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 13:51:54 2015 +0200

    Commit to #27: Fixed a stupid bug

commit 88d3f44a4f132395edc02ca7179ccfc85cdfddd5
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 13:46:52 2015 +0200

    Commit to #27: Added getter for socket port.

commit 1f0b610769d7551a4945f4a6ad629a773bb2afd7
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 13:35:52 2015 +0200

    Added a null check to DiscoveryManager.

commit f769dcb139413f0e185e806973d725443b50d928
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 13:28:31 2015 +0200

    Commit to #27: Added several modifiers for outgoing connection settings.

commit 98a0049ddc4b0e7c1c368fe2bae6e7374099545c
Merge: 42d6e49 b0803f7
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 10:16:50 2015 +0200

    Merge pull request #26 from thaliproject/story_001_tompaana_9
    
    Story 001 tompaana 9

commit b0803f7705eef798659a3803ab50c2377bd8e2e4
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 15 10:13:38 2015 +0200

    Fixed a crash bug.

commit eb882ed869c30e76bd37630ae99b8ed6d00f55bd
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 14 15:05:36 2015 +0200

    Commit to #9: Minor changes

commit 915848ec04ad4d0886bcb2d575d814e6150291f5
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 14 13:34:44 2015 +0200

    Updated the README.md

commit 8893f900f6beca204ae1566495371bd5d0bb646d
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 14 13:31:02 2015 +0200

    Updated the README.md

commit 14371a76be8f86807a1c42956d2a1c1761c574dc
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 14 13:01:52 2015 +0200

    Commit to #19: Implemented log fragment.

commit 76271050e7a82815b5d621af3c218298009fa4b7
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Sun Dec 13 17:52:44 2015 +0200

    Commit to #9: Hardened the management of the list of discovered peers.

commit 052b38b0ecdc40a7050085923c438aecad4352f0
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Sun Dec 13 16:39:15 2015 +0200

    Commit to #9: Added peer list management to DiscoveryManager.

commit 4972a8a8478b75c65c2554358d34f120b0159aea
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Sat Dec 12 15:56:02 2015 +0200

    Commit to #9 and #19: Refactored peer discovery and fixed crash bug in native app

commit 5af4598896bd3e071ec74df74c7db31a3233dab9
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 11 18:16:19 2015 +0200

    Commit to #19: Improved robustness of the native app.

commit a8751de3f3ab8f35dcd0bfacc82f80387cca8c4c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 11 17:24:58 2015 +0200

    Commit to #19: Minor improvements

commit 5818bf41aabff3d0c1697b78fc76567a5045ab74
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 11 16:26:41 2015 +0200

    Commit to #9: Fixed freezing issue when trying to abort connection.

commit ba4190bf067c0e6db8b501d3916739f93d770725
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 11 11:08:22 2015 +0200

    Commit to #19: Improvement to UI thread logic.

commit e9b4d88a6932e46d8123388d16a267e3395badd2
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 10 19:27:36 2015 +0200

    Commit to #19: Added simple tap to connect

commit fa37672fda35ed186cb61ec59e464dc9f6f2e30e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 10 14:53:39 2015 +0200

    Commit to #19: Added list view for peers.

commit d1b42aa879ccf6c4f5bd19c27583eea5266bd18c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Dec 9 19:18:36 2015 +0200

    Commit to #19: Added automated ping for all connections.

commit c86d48529289dd98e75fe846678750a43b9144fe
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Dec 9 17:57:19 2015 +0200

    Commit to #19 and #9:
    - Integrated the Bluetooth library to native test/sample app
    - Fixed found issues and the library and improved the interfaces

commit 1a678775448f94f4f7429f114946ed8bef3abf1c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Dec 9 15:55:16 2015 +0200

    Commit to #19: Added project template for native sample app.

commit 260c2bf44a8d1400ee7fe7d60bec0f1cd4f6c160
Merge: b16a2f6 4163289
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 8 18:06:25 2015 +0200

    Merge branch 'story_001_tompaana_9' of https://github.com/thaliproject/Thali_CordovaPlugin_BtLibrary into story_001_tompaana_9

commit b16a2f65f2f3697cf3a8cb2c84138d6e355a3b8d
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 3 18:02:27 2015 +0200

    Commit to #9: Added BleScanner placeholder.

commit b281c2d5d6d5850f52d2042e0e04f6d3c9b392e3
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 3 16:49:24 2015 +0200

    Commit to #9: Finished DiscoveryManager interface - at least for now

commit 46f4787cc09db5066ddb7ffa69cdd94bd2bc638c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 3 14:11:05 2015 +0200

    Commit to #9: Initial architectural preparations for adding BLE support: Separated the discovery from ConnectionManager into its own class, DiscoveryManager.

commit 42d6e492d5e3785246ae361702202a95e773edde
Merge: ec52c7c 03474a8
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 8 17:48:31 2015 +0200

    Merge pull request #25 from thaliproject/story_001_tompaana_22
    
    Merging Story 001 tompaana 22 to master.

commit 03474a8e3fcd5b4ef2dcfd5dd684eac0e033ee73
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Dec 8 13:32:05 2015 +0200

    Commit to #22: Refactored the socket creation/connect process. After this I'm done altering BluetoothClientThread.

commit 0de9d4f1c444c0ee8749ee554da51549b5724e6e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 7 21:23:12 2015 +0200

    Commit to #22: Last commit of the day: Minor fix.

commit 7a59d8eced70c429ff9cacc3dd3087d856eb3030
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 7 21:19:34 2015 +0200

    Commit to #22: Changed number of internal retries to 5.

commit f6d612a8ab5f48632fab8b839f5aea8dfd646c81
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 7 21:19:04 2015 +0200

    Commit to #22: Tried changing to rotating socket channel/port.

commit 30dfb569e80205116c63a312391b12230116e130
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 7 20:30:27 2015 +0200

    Commit to #22: Some more minor fixes.

commit 205eead159439ca4c29a48179c37c97419777e0f
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 7 19:56:37 2015 +0200

    Commit to #22: A bug fix for rare crash.

commit a9722cdea2f6acf5289a86c4eafc3bcf8bc74389
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 7 19:24:00 2015 +0200

    Commit to #22: Set a limit for internal connect retries.

commit feb4f311c588790720135db5f3c83b0b92c9e458
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 7 17:23:53 2015 +0200

    Commit to #22: First attempt to create a new BluetoothSocket via reflection by invoking a private constructor.

commit 2c9b72d5959ccf798240776f5ef854f713131268
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 7 16:19:36 2015 +0200

    Commit to #22: Changed connection timeout again.

commit 3b2d56f6086b7daba52dad5a2eaf57c9bc05799c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 7 15:17:01 2015 +0200

    Commit to #22: Minor adjustments.

commit 90e798e3cdf5140bbf025f22c532ae02f42ab43d
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Dec 7 13:50:21 2015 +0200

    Commit to #22: Adjusted connection timeout and socket connect retry delay.

commit 971101e1cfb07dcdad036c5688ec48d0504018c1
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 4 19:19:45 2015 +0200

    Commit to #22: Fixed a null pointer crash bug

commit 6a0dc9d976606085df558baa431d0b82e185b592
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 4 18:34:37 2015 +0200

    Commit to #22: Minor tweaks

commit 67695dcae604420bc704605519621991c0b95c21
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 4 18:21:29 2015 +0200

    Commit to #22: Fixed null pointer crash

commit a4721ceec15c503a6faea28b2312d73cf3ec916e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 4 18:06:39 2015 +0200

    Commit to #22: Got rid of all that timer nonsense.

commit ecfcbc573e8c7ebfdb9749247fe6d7350e4a4051
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 4 15:35:23 2015 +0200

    Commit to #22: Maybe I got the timer right this time.

commit d65234b3d1b43fd91a3702458d4881c96f51cd27
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 4 14:44:34 2015 +0200

    Commit to #22: Can't set the socket to null, if you want to use it as a base for the next one.

commit e309f8891fed59ebf89f7b3621bb1857285a003a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 4 14:36:33 2015 +0200

    Commit to #22: Fixed the timer issue

commit 0c01a7f6b539bb6c9de191c5798f64ed946b9909
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Dec 4 14:10:18 2015 +0200

    Commit to #22: Set the max channel to 30 and added a timer to close sockets that would otherwise block until connection timeout.

commit 332a3c80ba160a10033fed2a8a967b92cd39025e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 3 20:14:11 2015 +0200

    Commit to CordovaPlugin issue #298: Applied a workaround for socket connect failure.

commit 4163289f50bc994799ac02c09f9bbef83a7994c9
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 3 18:02:27 2015 +0200

    Commit to #9: Added BleScanner placeholder.

commit fe38064b0a2b93d9472270a061b921233727c921
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 3 16:49:24 2015 +0200

    Commit to #9: Finished DiscoveryManager interface - at least for now

commit 3a78a923c48fa96dbbbd76a4f34592e9390cd615
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Dec 3 14:11:05 2015 +0200

    Commit to #9: Initial architectural preparations for adding BLE support: Separated the discovery from ConnectionManager into its own class, DiscoveryManager.

commit ec52c7c65de499bab81921af2ecfb8bc0bb29532
Merge: 33225e2 c5ae6d3
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Dec 2 14:12:23 2015 +0200

    Merge pull request #20 from thaliproject/story_001_tompaana_17
    
    Merging story_001_tompaana_17 branch to master.

commit c5ae6d355351732c79e8e345f5ca9c491a5c0c57
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Nov 26 15:52:50 2015 +0200

    Commit to #17: Bug fix: Timer was starting itself instead of calling start() of the encapsulating class.

commit 3f62514de46567b6baf22682456bd1ddbfc01581
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Nov 26 15:32:34 2015 +0200

    Commit to #17: Added start delay to service watcher

commit 300ca75617eba916fb3c3d375913318dca827eaf
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Nov 26 14:13:17 2015 +0200

    Commit to #17: Bug fix for WifiServiceWatcher

commit bb7af073fc0724aed568ebce23d2824653695e84
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Thu Nov 26 11:44:22 2015 +0200

    Commit to #17: Added comments and improved logging.

commit ff05151d3eb302ef671cbbbde85c5cd87c6e531c
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Nov 25 13:03:43 2015 +0200

    Commit to #17: Minor change

commit a8782e60970083205388ca5260e56f27f88c1d38
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Wed Nov 25 12:37:06 2015 +0200

    Commit to #17: Possible bug fix

commit f6331786adb07905ac76e5c8842c6c79939e73a9
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Nov 24 18:03:11 2015 +0200

    Commit to #17: Updated the library version number.

commit 76283ba7d739b67501511043135c39115e6ca5a7
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Nov 24 13:56:04 2015 +0200

    Commit to #17: Minor fix and added comments to ConnectionManager.

commit a7894baf51c8d93e1e6c006da4be1ae24aa6559e
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Nov 24 13:33:52 2015 +0200

    Commit to #17: More or less finished refactoring

commit 436f4a861aae766529ff8ae94931af4ff8171de3
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Tue Nov 24 10:49:12 2015 +0200

    Commit for #17: Re-integrated Wi-Fi peer discovery to ConnectionManager

commit 36829643e9e7f76750488082b3633da567ed960a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Nov 23 18:21:45 2015 +0200

    Commit for #17:
    - Fixed compilation errors
    - Not yet finished though

commit 6c8fadd8c5a4fba091e3ac4cfb091b5571600c14
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Mon Nov 23 16:40:04 2015 +0200

    Commit for #17:
    - Finished refactoring the Bluetooth specific classes

commit 18c44b3131a8906d2ca3b7bbe609ec729b0581c2
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Sun Nov 22 21:40:19 2015 +0200

    Second commit for bug #17:
    - Work in progress, won't yet build
    - Renamed most of the Bluetooth related classes
    - More code cleanup

commit b3918137e04b32363a6f409162aef4e5fc44df7a
Author: Tomi Paananen <tomi.paananen@microsoft.com>
Date:   Fri Nov 20 17:15:10 2015 +0200

    Initial commit in respect to bug #17 (Handle technical dept)
    - Refactoring is still in progress and this commit will break the build
    - Refactoring of project structure is almost complete
    - The names of classes managing Wi-Fi are renamed
    - Renaming of classes managing Bluetooth is still pending
    - Approximately 40 % of code clean-up done

commit 33225e21ddf417f56b9b0de5b49d27858340f515
Merge: 01c4c62 96069cb
Author: Ville Rantala <ville.rantala@iki.fi>
Date:   Wed Nov 18 12:59:05 2015 +0200

    Merge pull request #14 from thaliproject/story_001
    
    Story 001

commit 96069cb390b8b1b090a1bdcade591299946b337a
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Fri Nov 13 12:52:36 2015 +0200

    removed double usage of setPeerAddress

commit 16e316deed7a372fb62cc3581a25bc0a27983dc9
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Wed Nov 11 09:42:44 2015 +0200

    missed the usage of changes constant in service discovery

commit c31cca4381d947c69bc2bdece5e8cd7d948cd6c9
Merge: f79a0bb 2dda223
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Wed Nov 11 09:38:45 2015 +0200

    Merge branch 'story_001' of https://github.com/thaliproject/Thali_CordovaPlugin_BtLibrary into story_001

commit f79a0bb07dd3faa2a313a1800f30ac142c86123a
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Wed Nov 11 09:38:32 2015 +0200

    first changes for the review

commit 2dda22336f7acb51b15d0c20e7a0a2d5a99a91fe
Author: Dr. Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Wed Nov 11 09:37:07 2015 +0200

    Rename BTHandShakeSocketTread.java to BTHandshakeSocketThread.java

commit 01c4c625f733259e08321f9ec1232c8f0b835418
Author: Dr. Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Wed Nov 11 09:36:31 2015 +0200

    Rename BTHandshakeSocketThread.java to BTHandShakeSocketTread.java

commit d9c5351873e8e5f627a19def802d5f1f468159e6
Author: Dr. Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Wed Nov 11 09:25:00 2015 +0200

    Rename BTHandShakeSocketTread.java to BTHandshakeSocketThread.java

commit d097e7cfdb9b3d11ba1518be3fe5bc6839c3d6ef
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Tue Nov 10 15:34:26 2015 +0200

    Tested & fixed issues. Now should be only re-doing the listener, if it gets exception.

commit f2b91375b3d7109eae198ca5d90bba5676c19ac8
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Fri Nov 6 11:35:48 2015 +0200

    Re-designed handshake & implemented array of handshake handlers with incoming connections to allow multiple connections to be processed simultaneously.

commit 87be412bab30e1294d2888c31a9f025dbd28c46b
Author: Yaron Y Goland <yaronyg@users.noreply.github.com>
Date:   Wed Aug 26 12:38:49 2015 -0700

    Ignore all .idea directories and all *.iml files

commit 496ad3e1cb21dc8a6b75cfc973d51052f699d5ce
Merge: 8e8849c 2c2196d
Author: Yaron Y Goland <yaronyg@users.noreply.github.com>
Date:   Wed Aug 26 12:36:28 2015 -0700

    Merge pull request #6 from thaliproject/story_0_juksilve
    
    Story 0 juksilve

commit 2c2196d1150b747c923b10b168cf2884d83c45e2
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Wed Aug 26 14:58:30 2015 +0300

    latest chage requests from code reviews are now included.

commit 49681d9ca7d4ba915f938b76a8fbf416776b0f29
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Tue Aug 25 18:50:49 2015 +0300

    updating with changes requested from code review on 24th august 2015

commit cefd0f75adca39f730be0b1934654725f9808736
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Thu Aug 20 22:17:56 2015 +0300

    changed serviceitem array readin with for loop to be implemented with while and the iterator.

commit 418931ce0a3b1a69a3ea32e52efbcabbfc025784
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Thu Aug 20 15:13:21 2015 +0300

    Changes suggested by IntelliJ incorporated into the codes.

commit 7e37dd7bc996be5f8dd325ff9ebf3a4da40172c9
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Wed Aug 19 14:39:49 2015 +0300

    updates to improve design according to code review feedback from Yaron

commit 2e06014ac8c2d36bb7134f3a018290df2a0ea13f
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Wed Aug 19 10:30:41 2015 +0300

    updates for story_0

commit 8e8849cb7e1783661cebe06b15a2e8f826b04066
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Thu Jul 16 09:16:11 2015 +0300

    Cleaned out the excryption stuff that was not used anymore

commit d32b788beb1695b9e34c6308fb5c75da02b6eb1a
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Wed Jun 24 15:42:44 2015 +0300

    Updated to work with latest API definition for the plugin

commit 000cfc464c3b22430286adedb6b219b2fddcd0c3
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Tue Jun 23 13:16:41 2015 +0300

    Added the incoming bt listening to start right after we have validated the current connection on handshake.
    
    Thus currently the Advertising & discovery is on all times, even when doing connections.
    
    Listening incoming BT connections is on all times, except, when we are doing handshake.

commit a5d3d40361ee6caf4a0174c5194e847a995424ea
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Mon Jun 22 15:40:03 2015 +0300

    Re-organized the Connector class in a way that the Discovery parts are separated from connectivity. Both parts are implemented in own classes handled by the connector class.

commit 0bbbd2843333799f683e2336a59da7bb1d58bb3e
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Thu Jun 11 14:01:49 2015 +0300

    Added already build local maven files with the whole folder structure present in the zip file

commit 79fc4f26b5eed532cc13940b6937383851086741
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Tue Jun 9 14:57:13 2015 +0300

    updated readme, and removed unnecessary files

commit 760ef22f523f9da88c3f47c9314d0848b2c0dd17
Author: Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Tue Jun 9 14:52:50 2015 +0300

    initial upload

commit 7253c2e8413a6079322eaa30de69bb1db3a082a4
Author: Dr. Jukka Silvennoinen <jukka.silvennoinen@microsoft.com>
Date:   Tue Jun 9 14:51:53 2015 +0300

    Initial commit
Your branch is up-to-date with 'origin/master'.
Your branch is up-to-date with 'origin/master'.
clone aborted
 [0m

Already on 'master'
Already on 'master'
error: pathspec 'bfa5bba' did not match any file(s) known to git.

```

Error: Command failed: Already on 'master'
Already on 'master'
error: pathspec 'bfa5bba' did not match any file(s) known to git.
