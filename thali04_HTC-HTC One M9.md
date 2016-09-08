#### Test 845006541145c7f_thali04_HTC-HTC One M9 Logs


```
--------- beginning of system
,09-08 21:19:34.146  1129  3979 I ActivityManager: Recipient 7519
--------- beginning of main
09-08 21:19:34.246  6573  8321 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-08 21:19:34.256  1129  3485 I ActivityManager: Start proc 8322:com.htc.cs.dm/u0a89 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
09-08 21:19:34.276  8322  8322 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:34.276  8322  8322 W HTCLOG  : mask=0x18
09-08 21:19:34.276  6573  8321 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
09-08 21:19:34.276  6573  8321 W HTCLOG  : mask=0x18
09-08 21:19:34.346  8322  8322 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8322 dbg=false s=true
09-08 21:19:34.346  8322  8322 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
09-08 21:19:34.366  1129  1148 I ActivityManager: Start proc 8346:com.google.android.apps.docs/u0a91 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
09-08 21:19:34.366  8346  8346 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:34.366  8346  8346 W HTCLOG  : mask=0x18
09-08 21:19:34.366  1129  1148 I ActivityManager: Killing 7892:com.google.android.talk/u0a103 (adj 15): empty #17
09-08 21:19:34.366  1129  1148 D Process : killProcessQuiet, pid=7892
09-08 21:19:34.366  1129  1148 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
09-08 21:19:34.446  8343  8343 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
09-08 21:19:34.446  8343  8343 W HTCLOG  : mask=0x18
09-08 21:19:34.476  1129  3485 I ActivityManager: Recipient 7892
09-08 21:19:34.586  1129  1129 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
09-08 21:19:34.606  3574  3893 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
09-08 21:19:34.606  3574  3893 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2ac888b8 +
09-08 21:19:34.606  3574  3893 I Prism.WidgetManager: onLoadItems() +
09-08 21:19:34.606  1129  3506 D PMS     : acquireWL(29d60cc5): PARTIAL_WAKE_LOCK  Icing 0x1 5242 10019 null
09-08 21:19:34.616  8343  8371 W HTCLOG  : use specified tag [cutils-trace], func [0].
09-08 21:19:34.616  8343  8371 W HTCLOG  : mask=0x18
09-08 21:19:34.616  8343  8371 E cutils-trace: Error opening trace file: Permission denied (13)
09-08 21:19:34.626  3574  3893 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
09-08 21:19:34.646  6573  8321 I ApplicationLogger: canRun() : Opted Out
09-08 21:19:34.646  6573  8321 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 399 ms] updated apps [took 399 ms] 
09-08 21:19:34.656  1129  3573 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
09-08 21:19:34.666  1129  3506 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
09-08 21:19:34.686  8343  8343 D CustomizationManager: ====startRecUseTime====
09-08 21:19:34.686  8343  8343 D htc.customization.log.level:  is 
09-08 21:19:34.686  8343  8343 W CustomizationLogLevel: Level value is invalid, use default level 2
09-08 21:19:34.706  7681  8145 I HtcModeClient: handler message = 4011
09-08 21:19:34.706  7681  8145 D HtcModeClient: getConnectionCheckCount first 0
09-08 21:19:34.706  7681  8145 D HtcModeClient: getConnectionCheckCount count = 7
09-08 21:19:34.706  7681  8145 E HtcModeClient: Check connection and retry 8 times.
09-08 21:19:34.706  8346  8346 D DocsApplication: Plugin installer initialized.
09-08 21:19:34.706  1129  3494 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
09-08 21:19:34.706  7681  8145 D HtcModeClient: setConnectionCheckCount count = 8
09-08 21:19:34.706  7681  8145 D HtcModeClient: setupRestart delayedTime = 3000
09-08 21:19:34.716  7681  7681 D HtcModeClient: setBtPriority priority = on
09-08 21:19:34.716  7681  7681 D HtcModeClient: unbindBlueToothService
09-08 21:19:34.716  7681  7681 D HtcModeClient: Don't start project servcice
09-08 21:19:34.716  7681  7681 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
09-08 21:19:34.716  7681  7681 D HtcModeClient: connectState: CONNECTION_READY = false
09-08 21:19:34.716  7681  7681 D SilentMusic: call stop
09-08 21:19:34.716  7681  7681 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
09-08 21:19:34.716  7681  8146 W CANMesgAgentLocalSocket: read the terminate packet, so break
09-08 21:19:34.736  7681  7681 D HtcModeClient: onDestroy
09-08 21:19:34.736  3543  4279 D PhoneApp: EVENT_QUERY_MO_PACKAGES
09-08 21:19:34.736  1129  1148 D Process : killProcessQuiet, pid=7505
09-08 21:19:34.736  1129  1148 I ActivityManager: Killing 7505:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
09-08 21:19:34.736  1129  1148 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
09-08 21:19:34.736  3543  4279 D PhoneApp: -- N1 =0
09-08 21:19:34.736  3543  4279 D PhoneApp: -- N2 =0
09-08 21:19:34.736  3543  4279 D PhoneApp: -- N3 =0
09-08 21:19:34.736  8346  8346 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{ce54925 com.google.android.apps.docs}
09-08 21:19:34.756  8346  8346 D TAG     : onCreate()
09-08 21:19:34.766  8346  8346 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
09-08 21:19:34.766  8343  8343 D CustomizationManager:  Read ACC file spent 0.038 (s)
09-08 21:19:34.766  8343  8343 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
09-08 21:19:34.766  8343  8343 I CustomizationCIDLoader: Parsing tag category name = application
09-08 21:19:34.766  8343  8343 I CustomizationCIDLoader: Parsing tag category name = system
09-08 21:19:34.776  8343  8343 I CustomizationCIDLoader: Parsing tag category name = Settings
09-08 21:19:34.776  8343  8343 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
09-08 21:19:34.776  8343  8343 I CustomizationCIDLoader: Parsing tag category name = ACC
09-08 21:19:34.776  8343  8343 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
09-08 21:19:34.776  8343  8343 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
09-08 21:19:34.776  8343  8343 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
09-08 21:19:34.776  8343  8343 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
09-08 21:19:34.776  8343  8343 I CustomizationCIDLoader: Parsing tag category name = AudioService
09-08 21:19:34.776  8343  8343 D CustomizationManager:  Read CID file spent 0.088 (s)
09-08 21:19:34.776  8343  8343 D CustomizationManager:  All configurations done spent 0.088 (s)
09-08 21:19:34.806  1129  3091 I ActivityManager: Recipient 7505
09-08 21:19:34.816  3574  3893 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 21:19:34.836  1129  3494 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8343 on display 0
09-08 21:19:34.836  1129  3519 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
09-08 21:19:34.846  1129  1178 D PMS     : acquireHCC(182809e6): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1129 1000 null
09-08 21:19:34.846  1129  1178 D PMS     : acquireHCC(9f47b27): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1129 1000 null
09-08 21:19:34.856  1129  3494 V WindowManager: addAppToken: AppWindowToken{1d5ade72 token=Token{37e60f7d ActivityRecord{21c881d4 u0 com.test.thalitest/.MainActivity t2}}} to stack=1 task=2 at 0
09-08 21:19:34.866  1129  3494 I ActivityManager: Start proc 8387:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
09-08 21:19:34.866  8343  8343 W HTCLOG  : use specified tag [IPCThreadState], func [0].
09-08 21:19:34.866  8343  8343 W HTCLOG  : mask=0x18
09-08 21:19:34.866  8343  8385 W HTCLOG  : use specified tag [Vector], func [0].
09-08 21:19:34.866  8343  8385 W HTCLOG  : mask=0x18
09-08 21:19:34.866  8387  8387 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:34.866  8387  8387 W HTCLOG  : mask=0x18
09-08 21:19:34.886  3318  3318 D DotMatrix: [EventService]  onDisplayChanged: 0
09-08 21:19:34.886  1129  1129 V ActivityManager: Display changed displayId=0
09-08 21:19:34.886  3318  3318 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
09-08 21:19:34.896  1129  1149 D ActivityManager: screenshot for ActivityRecord{21c881d4 u0 com.test.thalitest/.MainActivity t2}, bitmap=null, time = 0
09-08 21:19:34.916  3574  3574 I TrimMemoryManager: [trimMemory] 20
09-08 21:19:34.946  8387  8387 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
09-08 21:19:34.976  3574  3893 I Prism.WidgetManager: onLoadItems() -
09-08 21:19:34.976  3574  3893 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2ac888b8 -
09-08 21:19:35.006  8387  8387 I LibraryLoader: Time to load native libraries: 36 ms (timestamps 2439-2475)
09-08 21:19:35.006  8387  8387 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 21:19:35.016  8387  8387 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {dc652a1}
09-08 21:19:35.016  8387  8387 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 21:19:35.026  8387  8387 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 21:19:35.026  8387  8387 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 21:19:35.036  8387  8387 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 21:19:35.036  8387  8387 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 21:19:35.076  8387  8411 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,09-08 21:19:35.086  5569  5636 D BluetoothAdapterService(525424811): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@735b57c
09-08 21:19:35.096  8387  8387 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
09-08 21:19:35.096  8387  8387 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
09-08 21:19:35.096  8387  8387 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
09-08 21:19:35.106  8387  8387 W HTCLOG  : use specified tag [libEGL], func [3].
09-08 21:19:35.106  8387  8387 W HTCLOG  : mask=0x18
09-08 21:19:35.106  8387  8387 W HTCLOG  : use specified tag [libEGL], func [3].
09-08 21:19:35.106  8387  8387 W HTCLOG  : mask=0x18
09-08 21:19:35.106  8387  8387 I Adreno  : QUALCOMM build                   : 065751b, 
09-08 21:19:35.106  8387  8387 I Adreno  : Build Date                       : 04/15/15
09-08 21:19:35.106  8387  8387 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
09-08 21:19:35.106  8387  8387 I Adreno  : Local Branch                     : 
09-08 21:19:35.106  8387  8387 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
09-08 21:19:35.106  8387  8387 I Adreno  : Remote Branch                    : NONE
09-08 21:19:35.106  8387  8387 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
09-08 21:19:35.176  8387  8421 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
09-08 21:19:35.196  8387  8387 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 21:19:35.206  8387  8387 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-08 21:19:35.216  8387  8387 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
09-08 21:19:35.216  8387  8387 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 21:19:35.216  8387  8387 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 21:19:35.246  1129  3967 D PMS     : releaseWL(2f1281b5): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
09-08 21:19:35.256  8387  8432 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
09-08 21:19:35.256  8387  8432 W HTCLOG  : mask=0x18
09-08 21:19:35.256  1129  3091 V WindowManager: Adding window Window{2c0a397a u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{375ccb19 u0 com.htc.launcher/com.htc.launcher.Launcher})
09-08 21:19:35.266  1129  3637 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
09-08 21:19:35.296  8387  8387 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
09-08 21:19:35.296  8387  8387 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
09-08 21:19:35.296  8387  8387 W HTCLOG  : mask=0x18
09-08 21:19:35.296  8387  8387 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
09-08 21:19:35.296  8387  8387 W HTCLOG  : mask=0x18
09-08 21:19:35.306  8387  8432 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
09-08 21:19:35.306  8387  8432 W HTCLOG  : mask=0x18
09-08 21:19:35.306  8387  8432 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
09-08 21:19:35.306  8387  8432 W HTCLOG  : mask=0x18
09-08 21:19:35.306  8387  8432 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
09-08 21:19:35.306  8387  8432 W HTCLOG  : mask=0x18
09-08 21:19:35.306  8387  8432 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
09-08 21:19:35.306  8387  8432 W HTCLOG  : mask=0x18
09-08 21:19:35.306  8387  8432 W HTCLOG  : use specified tag [Surface], func [3].
09-08 21:19:35.306  8387  8432 W HTCLOG  : mask=0x18
09-08 21:19:35.306  8387  8432 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
09-08 21:19:35.306  8387  8432 W HTCLOG  : mask=0x18
09-08 21:19:35.306  8387  8432 W HTCLOG  : use specified tag [qdmemalloc], func [0].
09-08 21:19:35.306  8387  8432 W HTCLOG  : mask=0x18
09-08 21:19:35.366  1129  1169 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +470ms (total +511ms)
09-08 21:19:35.406  8387  8387 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8387
09-08 21:19:35.466  8387  8387 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-08 21:19:35.506  8387  8435 D jxcore_app_log: JniHelper::setJavaVM(0xab5b9b70), pthread_self() = -1403653568
09-08 21:19:35.506  1129  3040 D PMS     : acquireWL(26d27dd2): PARTIAL_WAKE_LOCK  *alarm* 0x1 1129 1000 WorkSource{10019}
09-08 21:19:35.506  1129  3040 V AlarmManager: sending alarm PendingIntent{c61bea3: PendingIntentRecord{316ccc64 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=78873, Int=0
09-08 21:19:35.506  1129  3040 V AlarmManager: sending alarm PendingIntent{22c605a0: PendingIntentRecord{1dc75559 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=81325, Int=0
09-08 21:19:35.506  1129  3040 V AlarmManager: sending alarm PendingIntent{5b6a51e: PendingIntentRecord{2847a1ff android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1473362366833, Int=0
09-08 21:19:35.506  8387  8435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 21:19:35.506  8387  8435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 21:19:35.506  8387  8435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 21:19:35.506  8387  8435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 21:19:35.506  8387  8435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-08 21:19:35.506  8387  8435 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@342d3814 added. We now have 1 listener(s)
09-08 21:19:35.506  1129  1148 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
09-08 21:19:35.516  8387  8435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
09-08 21:19:35.516  8387  8435 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
09-08 21:19:35.516  8387  8435 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 21:19:35.516  8387  8435 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-08 21:19:35.516  8387  8435 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ef7e03 added. We now have 1 listener(s)
09-08 21:19:35.516  8387  8435 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 21:19:35.516  1129  3052 D WifiService: New client listening to asynchronous messages
09-08 21:19:35.516  8387  8435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 21:19:35.516  8387  8435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 21:19:35.516  8387  8435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 21:19:35.516  8387  8435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 21:19:35.516  8387  8435 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-08 21:19:35.526  8387  8435 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 21:19:35.526  1129  3506 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
09-08 21:19:35.526  8387  8435 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
09-08 21:19:35.526  5569  5635 D BluetoothAdapterService(525424811): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@735b57c
09-08 21:19:35.526  8387  8435 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-08 21:19:35.526  8387  8435 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:19:35.526  8387  8435 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:19:35.526  8387  8435 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:19:35.526  8387  8435 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:19:35.526  8387  8435 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:19:35.526  8387  8435 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 21:19:35.526  8387  8435 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 21:19:35.526  8387  8435 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 21:19:35.526  8387  8435 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 21:19:35.526  8387  8435 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 21:19:35.526  8387  8435 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 21:19:35.526  8387  8387 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 21:19:35.556  8346  8444 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
09-08 21:19:35.556  8346  8444 W HTCLOG  : mask=0x18
09-08 21:19:35.576  8387  8387 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
09-08 21:19:35.606  1129  3503 I ActivityManager: Start proc 8448:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
09-08 21:19:35.606  1129  3503 D Process : killProcessQuiet, pid=7581
09-08 21:19:35.606  1129  3503 I ActivityManager: Killing 7581:com.htc.sdm/u0a61 (adj 15): empty #17
09-08 21:19:35.606  1129  3503 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
09-08 21:19:35.606  8448  8448 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:35.606  8448  8448 W HTCLOG  : mask=0x18
09-08 21:19:35.646  5242  6785 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
09-08 21:19:35.766  1129  3485 I ActivityManager: Recipient 7581
09-08 21:19:35.816  8346  8346 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
09-08 21:19:35.826  8448  8448 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 21:19:35.836  1129  1178 D PMS     : releaseHCC(182809e6): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
09-08 21:19:35.836  1129  1178 D PMS     : releaseHCC(9f47b27): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
09-08 21:19:35.866  5242  6785 D Icing   : Loaded CLD2 Version V2.0 - 20140131
,09-08 21:19:35.906  5242  6785 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5,
,09-08 21:19:35.916  1129  3573 D PMS     : releaseWL(29d60cc5): PARTIAL_WAKE_LOCK  Icing 0x1 null
,09-08 21:19:36.106  1129  3485 D PMS     : acquireWL(b8f9693): PARTIAL_WAKE_LOCK  AsyncService 0x1 8448 10128 null,
,09-08 21:19:36.126  1129  1149 D PMS     : releaseWL(b8f9693): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,09-08 21:19:36.126  8387  8443 W jxcore-log: Initializing JXcore engine,
09-08 21:19:36.126  8387  8443 W jxcore-log: JXcore engine is ready
,09-08 21:19:36.166  3973  3973 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE,
,09-08 21:19:36.176  3973  3973 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,09-08 21:19:36.176  3973  3973 D c       : Getting all permits...
,09-08 21:19:36.176  3973  3973 D a       : Opening database...
,09-08 21:19:36.176  3973  3973 D a       : Opening database auth.proximity.permit_store...
,09-08 21:19:36.186  3973  3973 D a       : Closing database...
,09-08 21:19:36.186  5242  5242 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,09-08 21:19:36.186  8387  8443 W jxcore-log: Starting JXcore engine
,09-08 21:19:36.206  1129  3996 D PMS     : acquireWL(215b46c9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 3973 10019 null,
09-08 21:19:36.206  1129  1129 D PMS     : acquireWL(be491ce): PARTIAL_WAKE_LOCK  *backup* 0x1 1129 1000 null
09-08 21:19:36.206  1129  1129 D PMS     : releaseWL(26d27dd2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,09-08 21:19:36.206  5242  8479 D LocationInitializer: Restart initialization of location
,09-08 21:19:36.206  1129  3121 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
09-08 21:19:36.206  3973  8480 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
09-08 21:19:36.206  1129  3121 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
,09-08 21:19:36.206  3973  8480 D libc    : [NET] android_getaddrinfofornet-, err=8
09-08 21:19:36.206  1129  3121 D PMS     : releaseWL(be491ce): PARTIAL_WAKE_LOCK  *backup* 0x1 null
09-08 21:19:36.206  3973  8480 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
09-08 21:19:36.206  3973  8480 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
09-08 21:19:36.206  3973  8480 D libc    : [NET] android_getaddrinfo_proxy+
09-08 21:19:36.206  3973  8480 D libc    : [NET] android_getaddrinfo_proxy get netid:0
09-08 21:19:36.206   513  8481 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
09-08 21:19:36.206   513  8481 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
09-08 21:19:36.216   513  8481 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
09-08 21:19:36.216  1129  1148 D PMS     : releaseWL(215b46c9): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
09-08 21:19:36.216   513  8481 D libc    : [NET] android_getaddrinfofornet-, err=7
09-08 21:19:36.216  3973  8480 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,09-08 21:19:36.276  8387  8443 W jxcore-log: Platform android,
09-08 21:19:36.276  8387  8443 W jxcore-log: 
09-08 21:19:36.276  8387  8443 W jxcore-log: Process ARCH arm
09-08 21:19:36.276  8387  8443 W jxcore-log: 
,09-08 21:19:36.516  8387  8443 I jxcore-log: JXcore Cordova bridge is ready!,
09-08 21:19:36.516  8387  8443 I jxcore-log: 
09-08 21:19:36.516  8387  8443 W jxcore-log: JXcore engine is started
,09-08 21:19:36.526  8387  8435 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,09-08 21:19:36.526  8387  8387 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-08 21:19:36.536  8387  8443 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
09-08 21:19:36.536  8387  8443 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,09-08 21:19:36.546  8387  8387 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
09-08 21:19:36.546  8387  8387 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,09-08 21:19:36.556  1129  3967 I ActivityManager: Killing 7936:com.htc.calendar/u0a6 (adj 15): empty #17
09-08 21:19:36.556  1129  3967 D Process : killProcessQuiet, pid=7936
09-08 21:19:36.556  1129  3967 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityStack.destroyActivityLocked:3407 
,09-08 21:19:36.726  1129  3519 I ActivityManager: Recipient 7936,
,09-08 21:19:36.766  8387  8435 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 222ms. Plugin should use CordovaInterface.getThreadPool().,
,09-08 21:19:36.766  8387  8387 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 21:19:36.776  8387  8387 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,09-08 21:19:36.776  8387  8387 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:19:36.776  8387  8387 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:19:36.776  8387  8387 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:19:36.776  8387  8387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 21:19:36.776  8387  8387 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@342d3814 removed from the list
09-08 21:19:36.776  8387  8387 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:19:36.776  8387  8387 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@21ef7e03 removed from the list
09-08 21:19:36.776  8387  8387 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:19:36.776  8387  8387 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,09-08 21:19:36.776  8387  8387 I io.jxcore.node.LifeCycleMonitor: stop: OK,
09-08 21:19:36.776  8482  8482 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
09-08 21:19:36.776  8482  8482 W HTCLOG  : mask=0x18
,09-08 21:19:36.946  8482  8486 W HTCLOG  : use specified tag [cutils-trace], func [0].
09-08 21:19:36.946  8482  8486 W HTCLOG  : mask=0x18
09-08 21:19:36.946  8482  8486 E cutils-trace: Error opening trace file: Permission denied (13)
,09-08 21:19:36.996  8482  8482 D CustomizationManager: ====startRecUseTime====,
09-08 21:19:36.996  8482  8482 D htc.customization.log.level:  is 
09-08 21:19:36.996  8482  8482 W CustomizationLogLevel: Level value is invalid, use default level 2
,09-08 21:19:37.086  8482  8482 D CustomizationManager:  Read ACC file spent 0.041 (s),
,09-08 21:19:37.086  8482  8482 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml,
09-08 21:19:37.096  8482  8482 I CustomizationCIDLoader: Parsing tag category name = application
,09-08 21:19:37.096  8482  8482 I CustomizationCIDLoader: Parsing tag category name = system
,09-08 21:19:37.096  8482  8482 I CustomizationCIDLoader: Parsing tag category name = Settings
09-08 21:19:37.096  8482  8482 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome,
09-08 21:19:37.096  8482  8482 I CustomizationCIDLoader: Parsing tag category name = ACC
,09-08 21:19:37.096  8482  8482 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
09-08 21:19:37.096  8482  8482 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
09-08 21:19:37.096  8482  8482 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005,
09-08 21:19:37.096  8482  8482 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
,09-08 21:19:37.096  8482  8482 I CustomizationCIDLoader: Parsing tag category name = AudioService
09-08 21:19:37.096  8482  8482 D CustomizationManager:  Read CID file spent 0.097 (s)
09-08 21:19:37.096  8482  8482 D CustomizationManager:  All configurations done spent 0.098 (s),
,09-08 21:19:37.146  1129  3494 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8482, uid=2000,
09-08 21:19:37.146  1129  1161 D Process : killProcessQuiet, pid=8387
09-08 21:19:37.146  1129  1161 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
09-08 21:19:37.146  1129  1161 I ActivityManager: Killing 8387:com.test.thalitest/u0a142 (adj 9): stop com.test.thalitest
09-08 21:19:37.146  1129  1161 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
,09-08 21:19:37.216  1129  3996 I ActivityManager: Recipient 8387
09-08 21:19:37.216  1129  3052 D WifiService: Client connection lost with reason: 4
,09-08 21:19:37.236   524   524 W HTCLOG  : use specified tag [Vector], func [0].
,09-08 21:19:37.236   524   524 W HTCLOG  : mask=0x18
,09-08 21:19:37.256  1129  3996 W ActivityManager: Spurious death for ProcessRecord{81308ef 8387:com.test.thalitest/u0a142}, curProc for 8387: null
,09-08 21:19:37.256  1129  1180 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed
,09-08 21:19:37.286  3318  3318 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest,
09-08 21:19:37.286  3318  3318 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,09-08 21:19:37.296  1129  3043 W SystemReader: Cannot find grip_rejection_width, use default value instead
09-08 21:19:37.296  1129  3049 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
09-08 21:19:37.296  1129  3048 D PMS     : acquireWL(14adcffc): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1129 1000 null
09-08 21:19:37.306  1129  3506 D PMS     : acquireWL(33bbfcda): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4298 10019 null
,09-08 21:19:37.306  3708  4155 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
09-08 21:19:37.316  4298  4635 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 21:19:37.316  1129  3979 D PMS     : releaseWL(33bbfcda): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
09-08 21:19:37.316  6573  6573 I art     : Explicit concurrent mark sweep GC freed 12297(759KB) AllocSpace objects, 2(48KB) LOS objects, 34% free, 3MB/5MB, paused 484us total 45.849ms
09-08 21:19:37.326  5242  5242 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
09-08 21:19:37.326  3708  4155 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
,09-08 21:19:37.326  1129  3503 D PMS     : acquireWL(524d400): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 5242 10019 null
09-08 21:19:37.326  1129  1160 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
09-08 21:19:37.336  1129  3048 D PMS     : releaseWL(14adcffc): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null,
,09-08 21:19:37.336  3757  8500 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest,
,09-08 21:19:37.346  1129  3049 V NetworkPolicy: writePolicyLocked(),
,09-08 21:19:37.356  3708  4155 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
,09-08 21:19:37.356  3973  3973 I ConfigService: onCreate
09-08 21:19:37.356  3973  3973 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
09-08 21:19:37.356  5242  5242 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,09-08 21:19:37.366  3708  4155 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,09-08 21:19:37.376  1129  1129 W PackageManager: Unable to load service info ResolveInfo{3b47c51 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
09-08 21:19:37.376  1129  1129 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
09-08 21:19:37.376  1129  1129 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method),
09-08 21:19:37.376  1129  1129 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:37.376  1129  1129 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:37.376  3574  3574 I art     : Explicit concurrent mark sweep GC freed 43386(2MB) AllocSpace objects, 39(2MB) LOS objects, 40% free, 22MB/37MB, paused 1.506ms total 103.648ms
09-08 21:19:37.386  1129  3049 V NetworkPolicy: updateNetworkEnabledLocked()
09-08 21:19:37.386  1129  3049 D NetworkPolicy: notifyPoliciesChangeLocked: no change
09-08 21:19:37.386  1129  3049 V NetworkPolicy: updateNotificationsLocked()
09-08 21:19:37.396  3973  3973 I ConfigService: onBind returning update interface
09-08 21:19:37.396  1129  3967 D PMS     : acquireWL(c36556d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3973 10019 null
09-08 21:19:37.396  3973  3973 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
09-08 21:19:37.396  3973  3973 I ConfigService: onBind returning config service
09-08 21:19:37.396  3543  3543 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
09-08 21:19:37.396  3973  3973 I ConfigService: onDestroy
09-08 21:19:37.406  1129  1129 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 21:19:37.396  3708  4155 E ExternalAccountType: Unsupported attribute readOnly
,09-08 21:19:37.416  1129  3091 I ActivityManager: Start proc 8502:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver
,09-08 21:19:37.426  8502  8502 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:37.426  1129  3506 D PMS     : releaseWL(c36556d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,09-08 21:19:37.426  8502  8502 W HTCLOG  : mask=0x18
09-08 21:19:37.426  3574  3893 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false,
09-08 21:19:37.426  3574  3893 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
09-08 21:19:37.436  3574  3574 I Launcher: Deferring update until onResume
09-08 21:19:37.436  3574  3574 D Launcher: waitUntilResume // bindAppsRemoved
,09-08 21:19:37.456  8502  8502 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
09-08 21:19:37.456  8502  8502 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-08 21:19:37.476  8502  8502 I MultiDex: VM with version 2.1.0 has multidex support,
09-08 21:19:37.476  8502  8502 I MultiDex: install
09-08 21:19:37.476  8502  8502 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-08 21:19:37.486  8502  8502 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application',
09-08 21:19:37.486  3574  3574 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
09-08 21:19:37.486  3574  3574 I ThreadedRenderer: Defer allocateBuffers to drawing time
09-08 21:19:37.496  1129  1180 I art     : Explicit concurrent mark sweep GC freed 37626(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 15MB/23MB, paused 2.160ms total 224.670ms
09-08 21:19:37.496  8502  8502 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-08 21:19:37.516  5242  8526 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-08 21:19:37.516  5242  8526 D AccountUtils: Clearing selected account for com.test.thalitest
,09-08 21:19:37.526  1129  3091 I ActivityManager: Start proc 8529:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver
,09-08 21:19:37.536  8482  8482 I art     : System.exit called, status: 0
09-08 21:19:37.536  8482  8482 W HTCLOG  : use specified tag [Vector], func [0].
09-08 21:19:37.536  8482  8482 W HTCLOG  : mask=0x18
09-08 21:19:37.536  3480  3480 D Nfc-Utils: isNxpCodebase: isNxp=false
09-08 21:19:37.536  8529  8529 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:37.536  8529  8529 W HTCLOG  : mask=0x18
,09-08 21:19:37.556  1129  1161 W ProcessCpuTracker: Skipping unknown process pid 8482
,09-08 21:19:37.576  7965  8556 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,09-08 21:19:37.576  5242  8557 I PeopleContactsSync: CP2 sync disabled
,09-08 21:19:37.586  1129  3091 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=5242, uid=10019, userID:0
,09-08 21:19:37.586  1129  3091 D PMS     : acquireWL(3ea473dd): PARTIAL_WAKE_LOCK  Icing 0x1 5242 10019 null,
,09-08 21:19:37.586  5242  6785 I Icing   : doRemovePackageData com.test.thalitest
,09-08 21:19:37.586  1129  1148 D PMS     : releaseWL(3ea473dd): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,09-08 21:19:37.606  1129  3996 I ActivityManager: Killing 7786:com.google.android.gm/u0a97 (adj 15): empty #17
09-08 21:19:37.606  1129  3996 D Process : killProcessQuiet, pid=7786
,09-08 21:19:37.606  1129  3996 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,09-08 21:19:37.716  1129  3573 I ActivityManager: Recipient 7786
,09-08 21:19:37.816  3708  3708 E PackageActionReceiver: ACTION_PACKAGE_REMOVED
09-08 21:19:37.816  1129  3040 D PMS     : acquireWL(140db52): PARTIAL_WAKE_LOCK  *alarm* 0x1 1129 1000 WorkSource{10027}
09-08 21:19:37.816  1129  3040 V AlarmManager: sending alarm PendingIntent{3edc8e23: PendingIntentRecord{2c36067 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=95180, Int=0
,09-08 21:19:37.816  1129  3040 V AlarmManager: sending alarm PendingIntent{30d989c4: PendingIntentRecord{263190ad android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=94895, Int=0
,09-08 21:19:37.826  3644  8562 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest,
09-08 21:19:37.826  3644  8562 E SQLiteLog: (3850) statement aborts at 41: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
,09-08 21:19:37.826  3644  8562 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
09-08 21:19:37.826  3644  8562 W HTCLOG  : mask=0x18
09-08 21:19:37.826  3644  8562 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.sense.hsp/databases/registry.db, handle: 0x55c593cf70
,09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: provider may killed!
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762),
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	,at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65),
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:37.836  3644  8562 W [PluginManager]RegisterService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 21:19:37.836  5242  8553 W GmsApplication: Using Auth Proxy for data requests.
,09-08 21:19:37.846  3644  8562 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed,
09-08 21:19:37.846  3574  3574 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
09-08 21:19:37.846  3574  3574 I ContextualWidget: package com.test.thalitest removed
,09-08 21:19:37.846  3574  3909 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
,09-08 21:19:37.856  5242  8553 W GmsApplication: Using Auth Proxy for data requests.,
09-08 21:19:37.856  3574  8563 I ContextualWidget: com.test.thalitest is not installed
09-08 21:19:37.856  3574  8563 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0}),
,09-08 21:19:37.866  3574  8563 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
09-08 21:19:37.866  3574  8563 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
09-08 21:19:37.866  3574  8563 W HTCLOG  : mask=0x18
09-08 21:19:37.866  3574  8563 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xac212c10
09-08 21:19:37.866  3574  8563 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
09-08 21:19:37.866  3574  8563 E AndroidRuntime: Process: com.htc.launcher, PID: 3574
09-08 21:19:37.866  3574  8563 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.removeItemsFromDownloadListIfNeed(MFUDataManager.java:2133)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageRemoved(HtcContextualWidgetService.java:277)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:184)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:37.866  3574  8563 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61),
09-08 21:19:37.876  1129  3996 I ActivityManager: Start proc 8564:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
09-08 21:19:37.876  1129  3494 E ActivityManager: App crashed! Process: com.htc.launcher
09-08 21:19:37.876  1129  3494 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at com.google.android.gms.common.e.a.delete(SourceFile:258)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:37.876  5242  8553 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: Runtime exception while performing operation
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at com.google.android.gms.common.e.a.delete(SourceFile:258)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:37.876  5242  8553 E ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: Can't write: system_app_wtf
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:37.886  1129  8578 E DropBoxManagerService: 	... 5 more
09-08 21:19:37.876  1129  3494 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:37.886  1129  8584 E ErrorReport: HtcErrorReportManager.Error in dumping error information
09-08 21:19:37.886  1129  8584 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1473362377900.dbox_tmp: open failed: EROFS (Read-only file system)
09-08 21:19:37.886  1129  8584 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:37.886  1129  8584 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:37.886  1129  8584 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:37.886  1129  8584 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
09-08 21:19:37.886  1129  8584 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:19:37.886  1129  8584 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:37.886  1129  8584 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:37.886  1129  8584 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:37.886  1129  8584 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:37.886  1129  8584 E ErrorReport: 	... 4 more
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at com.google.android.gms.common.e.a.delete(SourceFile:258)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:37.876  5242  8553 F ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:37.886  1129  3494 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
09-08 21:19:37.876  1129  3494 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:37.876  1129  3494 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:37.876  1129  3494 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:37.876  1129  3494 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:37.876  1129  3494 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:37.876  1129  3494 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:37.876  1129  3494 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
09-08 21:19:37.876  1129  3494 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
09-08 21:19:37.876  1129  3494 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:37.876  1129  3494 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:37.876  1129  3494 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:37.876  1129  3494 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:37.876  1129  3494 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:37.876  1129  3494 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:37.876  1129  3494 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:37.886  1129  3494 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:37.886  1129  3494 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:37.886  1129  3494 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:37.886  1129  3494 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:37.886  1129  3494 W System.err: 	... 14 more
09-08 21:19:37.886  1129  3494 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:37.886  1129  3494 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:37.886  1129  3494 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:37.886  1129  3494 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:37.886  1129  3494 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:37.886  1129  3494 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:37.886  1129  3494 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:37.886  1129  3494 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
09-08 21:19:37.886  1129  3494 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
09-08 21:19:37.886  1129  3494 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:37.886  1129  3494 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:37.886  1129  3494 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:37.886  1129  3494 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:37.886  1129  3494 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:37.886  1129  3494 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:37.886  1129  3494 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:37.886  1129  3494 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:37.886  8564  8564 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:37.886  8564  8564 W HTCLOG  : mask=0x18
09-08 21:19:37.886  1129  3494 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:37.886  1129  3494 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:37.886  1129  3494 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:37.886  1129  3494 W System.err: 	... 14 more
09-08 21:19:37.896  1129  3637 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
09-08 21:19:37.896  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:37.896  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:37.896  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:37.896  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:37.896  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
09-08 21:19:37.896  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
09-08 21:19:37.896  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
09-08 21:19:37.896  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
09-08 21:19:37.896  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
09-08 21:19:37.896  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
09-08 21:19:37.896  1129  3637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:37.896  1129  3637 W System.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:37.896  1129  3637 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:37.896  1129  3637 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:37.896  1129  3637 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:37.896  1129  3637 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:37.896  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:37.896  1129  3637 W System.err: 	... 12 more
09-08 21:19:37.896  3574  3574 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@177db581 for type 0
09-08 21:19:37.896  3574  8563 D Process : killProcess, pid=3574
09-08 21:19:37.896  3574  8563 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
09-08 21:19:37.896  3574  8563 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:37.896  3574  8563 W HTCLOG  : mask=0x18
09-08 21:19:37.926  1129  3042 W InputDispatcher: channel '375ccb19 com.htc.launcher.Launcher (s)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-08 21:19:37.926  1129  3042 I WindowManager: WINDOW DIED Window{375ccb19 u0 com.htc.launcher/com.htc.launcher.Launcher}
09-08 21:19:37.926  1129  3042 E InputDispatcher: channel '375ccb19 com.htc.launcher.Launcher (s)' ~ Channel is unrecoverably broken and will be disposed!
09-08 21:19:37.926  1129  3967 I ActivityManager: Recipient 3574
09-08 21:19:37.926  1129  3042 W InputDispatcher: Attempted to unregister already unregistered input channel '375ccb19 com.htc.launcher.Launcher (s)'
,09-08 21:19:37.946  5242  5257 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-08 21:19:37.946  5242  5257 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
09-08 21:19:37.946  5242  5257 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-08 21:19:37.976  1129  3967 I ActivityManager: Process com.htc.launcher (pid 3574) has died
09-08 21:19:37.976  1129  3967 W ActivityManager: Scheduling restart of crashed service com.htc.launcher/.htcwidget.HtcContextualWidgetService in 1000ms
,09-08 21:19:37.986  1129  3967 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
09-08 21:19:37.986  1129  3967 V WindowManager: addAppToken: AppWindowToken{15354d4c token=Token{c5fe97f ActivityRecord{386d5a9e u0 com.htc.launcher/.Launcher t3}}} to stack=0 task=3 at 0
,09-08 21:19:37.996  1129  3967 I ActivityManager: Start proc 8590:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,09-08 21:19:38.006  8590  8590 W HTCLOG  : use specified tag [FDManager], func [0].,
09-08 21:19:38.006  8590  8590 W HTCLOG  : mask=0x18
,09-08 21:19:38.016  1129  1149 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
,09-08 21:19:38.016  8564  8564 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
,09-08 21:19:38.026  8564  8564 D IdefixUninstallListener: package_removed = com.test.thalitest
,09-08 21:19:38.026  8203  8218 E AndroidHttpClient: Leak found
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.026  8203  8218 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,09-08 21:19:38.056  8564  8564 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
09-08 21:19:38.056  1129  3091 I ActivityManager: Killing 7430:com.google.android.music:main/u0a115 (adj 15): empty #17
09-08 21:19:38.056  8564  8564 W HTCLOG  : mask=0x18
09-08 21:19:38.056  5242  8542 W DriveInitializer: Awaiting to be initialized
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
,09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.056  8564  8564 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.056  8564  8564 W System.err: java.sql.SQLException: Getting a writable database from helper a@3388124d failed
09-08 21:19:38.056  8564  8564 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
09-08 21:19:38.056  8564  8564 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
09-08 21:19:38.056  8564  8564 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
09-08 21:19:38.056  8564  8564 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
09-08 21:19:38.056  8564  8564 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
09-08 21:19:38.056  8564  8564 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
09-08 21:19:38.056  8564  8564 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
,09-08 21:19:38.056  8564  8564 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
09-08 21:19:38.056  8564  8564 W System.err: ,	,at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
,09-08 21:19:38.056  8564  8564 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.056  8564  8564 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.056  8564  8564 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.056  8564  8564 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825),
09-08 21:19:38.056  8564  8564 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.056  8564  8564 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.056  8564  8564 W System.err: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
,09-08 21:19:38.056  8564  8564 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
,09-08 21:19:38.056  8564  8564 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
,09-08 21:19:38.056  8564  8564 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.056  8564  8564 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
09-08 21:19:38.056  8564  8564 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.056  8564  8564 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
09-08 21:19:38.056  8564  8564 W System.err: 	... 15 more
,09-08 21:19:38.056  1129  3091 D Process : killProcessQuiet, pid=7430
09-08 21:19:38.056  5242  8611 W DriveInitializer: Background init thread started
09-08 21:19:38.056  8590  8590 I MultiDex: VM with version 2.1.0 has multidex support
09-08 21:19:38.056  1129  3091 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
09-08 21:19:38.056  8590  8590 I MultiDex: install
09-08 21:19:38.056  8590  8590 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-08 21:19:38.066  5242  8611 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock43] disk I/O error
09-08 21:19:38.066  5242  8611 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
09-08 21:19:38.066  5242  8611 W HTCLOG  : mask=0x18
09-08 21:19:38.066  5242  8611 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55c5a009e0
09-08 21:19:38.066  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : null
09-08 21:19:38.076  8590  8590 D FaceDetectTask: checkIsOmronEnable start
09-08 21:19:38.076  5242  8611 E DocListDatabase: Failed to delete from ContentFileDeletionLock43
09-08 21:19:38.076  5242  8611 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:19:38.076  5242  8611 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 21:19:38.076  5242  8611 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
09-08 21:19:38.076  5242  8611 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 21:19:38.076  5242  8611 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 21:19:38.076  5242  8611 E DocListDatabase: 	,at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
09-08 21:19:38.076  5242  8611 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
09-08 21:19:38.076  5242  8611 E DocListDatabase: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
09-08 21:19:38.076  5242  8611 E DocListDatabase: 	at com.google.android.gms.drive.v.run(SourceFile:69)
09-08 21:19:38.076  5242  8611 W DriveInitializer: Background init thread ended
09-08 21:19:38.076  5242  8542 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-08 21:19:38.076  5242  8542 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55c5a009e0
09-08 21:19:38.076  5242  8611 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
09-08 21:19:38.076  5242  8611 E AndroidRuntime: Process: com.google.android.gms, PID: 5242
09-08 21:19:38.076  5242  8611 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:19:38.076  5242  8611 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 21:19:38.076  5242  8611 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
09-08 21:19:38.076  5242  8611 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 21:19:38.076  5242  8611 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 21:19:38.076  5242  8611 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598),
09-08 21:19:38.076  5242  8611 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
09-08 21:19:38.076  5242  8611 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
09-08 21:19:38.076  5242  8611 E AndroidRuntime: 	at com.google.android.gms.drive.v.run(SourceFile:69)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: disk I/O error (code 3850)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.m(SourceFile:501)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:495)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1406)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.ao.a(SourceFile:16)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.076  5242  8542 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.076  8590  8590 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
09-08 21:19:38.076  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.076  8590  8590 D FaceDetectTask: IsOmronEnable : true
09-08 21:19:38.076  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.076  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : null
09-08 21:19:38.076  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.076  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.076  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.076  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,09-08 21:19:38.076  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.076  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.076  8590  8590 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.086  8590  8590 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
09-08 21:19:38.086  8590  8590 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
09-08 21:19:38.086  8590  8590 W HTCLOG  : mask=0x18
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
,09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.086  8590  8590 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,09-08 21:19:38.086  8590  8590 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
,09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,09-08 21:19:38.086  8590  8590 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.086  8590  8590 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
09-08 21:19:38.086  8590  8590 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
,09-08 21:19:38.086  8590  8590 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.086  8590  8590 W System.err: 	at android.os.Looper.loop(Looper.java:155)
,09-08 21:19:38.086  8590  8590 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.086  8590  8590 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.086  8590  8590 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.086  8590  8590 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.086  8590  8590 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,09-08 21:19:38.096  8590  8590 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.096  8590  8590 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,09-08 21:19:38.096  8590  8590 E AndroidRuntime: FATAL EXCEPTION: main
09-08 21:19:38.096  8590  8590 E AndroidRuntime: Process: com.htc.launcher, PID: 8590
09-08 21:19:38.096  8590  8590 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.096  8590  8590 E AndroidRuntime: 	... 11 more
,09-08 21:19:38.206  1129  1149 I ActivityManager: Recipient 7430
09-08 21:19:38.206  1129  3364 D MediaRouterService: Client com.google.android.music (pid 7430): Died!
,09-08 21:19:38.276  1129  3519 E ActivityManager: App crashed! Process: com.htc.launcher
09-08 21:19:38.276  1129  3485 E ActivityManager: App crashed! Process: com.google.android.gms
09-08 21:19:38.286  1129  3519 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.286  1129  3519 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
09-08 21:19:38.286  1129  3519 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.286  1129  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.286  1129  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.286  1129  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.286  1129  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.286  1129  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.286  1129  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
09-08 21:19:38.286  1129  3519 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
09-08 21:19:38.286  1129  3519 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.286  1129  3519 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.286  1129  3519 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.286  1129  3519 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.286  1129  3519 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.286  1129  3519 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.286  1129  3519 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.286  1129  3519 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.286  1129  3519 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.286  1129  3519 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.286  1129  3519 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.286  1129  3519 W System.err: 	... 14 more
,09-08 21:19:38.296  5242  8611 D Process : killProcess, pid=5242,
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: Can't write: system_app_crash
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,09-08 21:19:38.306  1129  8620 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
,09-08 21:19:38.306  1129  8620 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: ,	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: 	,at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.306  1129  8620 E DropBoxManagerService: 	... 5 more
09-08 21:19:38.306  5242  8611 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
09-08 21:19:38.306  1129  3519 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
,09-08 21:19:38.306  5242  8611 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:38.306  1129  8621 E ErrorReport: HtcErrorReportManager.Error in dumping error information
09-08 21:19:38.306  1129  8621 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1473362378318.dbox_tmp: open failed: EROFS (Read-only file system)
09-08 21:19:38.306  1129  8621 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.306  1129  8621 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.306  1129  8621 E ErrorReport: ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:38.306  1129  8621 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
09-08 21:19:38.306  1129  8621 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:19:38.306  1129  8621 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.306  1129  8621 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.306  1129  8621 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.306  1129  8621 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.306  1129  8621 E ErrorReport: 	... 4 more
09-08 21:19:38.306  5242  8611 W HTCLOG  : mask=0x18
09-08 21:19:38.306  1129  3519 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.306  1129  3519 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,09-08 21:19:38.306  1129  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.306  1129  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.306  1129  3519 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.306  1129  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.306  1129  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.306  1129  3519 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
09-08 21:19:38.306  1129  3519 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
09-08 21:19:38.306  1129  3519 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.306  1129  3519 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.306  1129  3519 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.306  1129  3519 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.306  1129  3519 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.306  1129  3519 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.306  1129  3519 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.306  1129  3519 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.306  1129  3519 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.306  1129  3519 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.306  1129  3519 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.306  1129  3519 W System.err: 	... 14 more
09-08 21:19:38.316  1129  3637 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.316  8590  8590 D Process : killProcess, pid=8590
09-08 21:19:38.316  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.316  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.316  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.316  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.316  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
09-08 21:19:38.316  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
09-08 21:19:38.316  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
09-08 21:19:38.316  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
09-08 21:19:38.316  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
09-08 21:19:38.316  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
09-08 21:19:38.316  1129  3637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.316  8590  8590 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
09-08 21:19:38.316  1129  3637 W S,ystem.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.316  1129  3637 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.316  1129  3637 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.316  1129  3637 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.316  1129  3637 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.316  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.316  1129  3637 W System.err: 	... 12 more
09-08 21:19:38.316  8590  8590 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:38.316  8590  8590 W HTCLOG  : mask=0x18
09-08 21:19:38.326  6573  8622 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-08 21:19:38.326   491   491 E lowmemorykiller: Error writing /proc/5242/oom_score_adj; errno=22
,09-08 21:19:38.346  8623  8623 W HTCLOG  : use specified tag [FDManager], func [0].
,09-08 21:19:38.346  8623  8623 W HTCLOG  : mask=0x18
,09-08 21:19:38.356  1129  3364 I ActivityManager: Start proc 8623:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,09-08 21:19:38.376  6573  8622 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-08 21:19:38.376  6573  8622 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
09-08 21:19:38.376  6573  8622 W HTCLOG  : mask=0x18
,09-08 21:19:38.376  6573  8622 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55c58de100
,09-08 21:19:38.386  6573  8622 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,09-08 21:19:38.386  6573  8622 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
09-08 21:19:38.386  6573  8622 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6573,
09-08 21:19:38.386  6573  8622 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	,at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.386  6573  8622 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.386  1129  3506 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
09-08 21:19:38.386  6573  8622 D Process : killProcess, pid=6573
09-08 21:19:38.386  8623  8623 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: Can't write: system_app_crash
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: 	,at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.386  1129  8645 E DropBoxManagerService: 	... 5 more
09-08 21:19:38.386  6573  8622 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
09-08 21:19:38.396  6573  8622 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:38.396  6573  8622 W HTCLOG  : mask=0x18
,09-08 21:19:38.396  8623  8646 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,09-08 21:19:38.406  8623  8646 W HTCLOG  : mask=0x18
,09-08 21:19:38.406  8623  8646 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.406  8623  8646 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
09-08 21:19:38.406  8623  8646 E AndroidRuntime: Process: com.android.keychain, PID: 8623
09-08 21:19:38.406  8623  8646 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.406  8623  8646 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.406  1129  3575 I ActivityManager: Recipient 8590
09-08 21:19:38.406  1129  3091 I ActivityManager: Recipient 5242
09-08 21:19:38.406  1129  3573 D PMS     : acquireWL(280ff238): PARTIAL_WAKE_LOCK  AsyncService 0x1 8448 10128 null
09-08 21:19:38.406  1129  3979 D PMS     : handleWLDeath(524d400): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
09-08 21:19:38.406  1129  3494 D PMS     : handleWLDeath(3d9d81a6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
09-08 21:19:38.406  1129  3575 I ActivityManager: Process com.htc.launcher (pid 8590) has died
09-08 21:19:38.406  1129  3575 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
09-08 21:19:38.406  1129  3506 D PMS     : releaseWL(280ff238): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,09-08 21:19:38.406  1129  3575 V WindowManager: addAppToken: AppWindowToken{35838977 token=Token{118c1f76 ActivityRecord{39e76211 u0 com.htc.launcher/.Launcher t4}}} to stack=0 task=4 at 0
,09-08 21:19:38.426  1129  3575 I ActivityManager: Start proc 8648:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher,
,09-08 21:19:38.426  1129  1149 E ActivityManager: App crashed! Process: com.android.keychain
09-08 21:19:38.426  1129  3091 I ActivityManager: Process com.google.android.gms (pid 5242) has died
09-08 21:19:38.426  8648  8648 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:38.426  1129  3091 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
09-08 21:19:38.426  8648  8648 W HTCLOG  : mask=0x18
09-08 21:19:38.426  1129  3091 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
09-08 21:19:38.426  1129  3637 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,09-08 21:19:38.426   491   491 E lowmemorykiller: Error writing /proc/6573/oom_score_adj; errno=22
,09-08 21:19:38.426   491   491 E lowmemorykiller: Error writing /proc/6573/oom_score_adj; errno=22
09-08 21:19:38.426  1129  1149 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
09-08 21:19:38.426  1129  3519 I ActivityManager: Recipient 6573
09-08 21:19:38.436  1129  1149 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.426  1129  3052 D WifiService: Client connection lost with reason: 4
09-08 21:19:38.436  1129  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.436  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.436  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.436  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.436  1129  1149 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.436  1129  1149 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.436  1129  1149 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.436  1129  1149 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.436  1129  1149 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.436  1129  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.436  1129  1149 W System.err: 	... 14 more
09-08 21:19:38.436  1129  1149 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.436  1129  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.436  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.436  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.436  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
,09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.436  1129  1149 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.436  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.436  1129  1149 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.436  1129  1149 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.436  1129  1149 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.436  1129  1149 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.436  1129  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.436  1129  1149 W System.err: 	... 14 more
,09-08 21:19:38.486  1129  3519 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6573) has died,
09-08 21:19:38.486  1129  3519 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10940ms
09-08 21:19:38.486  1129  3519 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20940ms
,09-08 21:19:38.496  8322  8322 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest],
,09-08 21:19:38.496  8322  8322 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
09-08 21:19:38.496  1129  8669 E ErrorReport: HtcErrorReportManager.Error in dumping error information
09-08 21:19:38.496  1129  8669 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1473362378504.dbox_tmp: open failed: EROFS (Read-only file system)
09-08 21:19:38.496  1129  8669 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,09-08 21:19:38.496  1129  8669 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.496  1129  8669 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:38.496  1129  8669 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
09-08 21:19:38.496  1129  8669 E ErrorReport: ,	at java.lang.Thread.run(Thread.java:818)
09-08 21:19:38.496  1129  8669 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.496  1129  8669 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.496  1129  8669 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.496  1129  8669 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.496  1129  8669 E ErrorReport: 	... 4 more
,09-08 21:19:38.496  1129  3637 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.496  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.496  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.496  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.496  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.496  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
09-08 21:19:38.496  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
09-08 21:19:38.496  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
09-08 21:19:38.496  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
09-08 21:19:38.496  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
09-08 21:19:38.496  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
09-08 21:19:38.496  1129  3637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.496  1129  3637 W System.err: 	,at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.496  1129  3637 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.496  1129  3637 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.496  1129  3637 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.496  1129  3637 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.496  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.496  1129  3637 W System.err: 	... 12 more
,09-08 21:19:38.506  8623  8646 D Process : killProcess, pid=8623
09-08 21:19:38.506  8623  8646 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
09-08 21:19:38.506  8623  8646 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:38.506  8623  8646 W HTCLOG  : mask=0x18
09-08 21:19:38.506  8322  8322 I DeviceManagement: WorkflowService: Starting workflow service
09-08 21:19:38.506  8322  8670 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@15477dd] args=[Bundle[mParcelledData.dataSize=112]]
09-08 21:19:38.506  8322  8670 I DeviceManagement: PackageUpdateWorkflow: ==================================================
09-08 21:19:38.506  8322  8670 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
09-08 21:19:38.506  8322  8670 I DeviceManagement: PackageUpdateWorkflow: ==================================================
09-08 21:19:38.516  8322  8670 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
09-08 21:19:38.516  1129  3494 I ActivityManager: Start proc 8671:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
09-08 21:19:38.526  8648  8648 I MultiDex: VM with version 2.1.0 has multidex support
09-08 21:19:38.526  8648  8648 I MultiDex: install
09-08 21:19:38.526  8648  8648 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-08 21:19:38.526  8671  8671 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:38.526  8671  8671 W HTCLOG  : mask=0x18
,09-08 21:19:38.536  8322  8670 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest,
09-08 21:19:38.536  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : null
09-08 21:19:38.536  8648  8648 D FaceDetectTask: checkIsOmronEnable start
,09-08 21:19:38.546  8648  8648 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
09-08 21:19:38.546  1129  1149 I ActivityManager: Recipient 8623
09-08 21:19:38.546  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.546  8648  8648 D FaceDetectTask: IsOmronEnable : true
09-08 21:19:38.546  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.546  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : null
09-08 21:19:38.546  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.546  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.546  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.546  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.546  8322  8692 I DeviceManagement: SessionStateController: Checking invariants...
,09-08 21:19:38.546  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.546  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,09-08 21:19:38.546  1129  1149 I ActivityManager: Process com.android.keychain (pid 8623) has died
09-08 21:19:38.546  1129  1149 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20876ms
09-08 21:19:38.546  8648  8648 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,09-08 21:19:38.556  8648  8648 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
09-08 21:19:38.556  8648  8648 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
09-08 21:19:38.556  8648  8648 W HTCLOG  : mask=0x18
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java,:1030)
09-08 21:19:38.556  8648  8648 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.556  8648  8648 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.556  8648  8648 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
09-08 21:19:38.556  8648  8648 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.556  8648  8648 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.556  8648  8648 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.556  8648  8648 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.556  8648  8648 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.556  8648  8648 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the da,tabase in read/write mode.
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.566  8648  8648 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: FATAL EXCEPTION: main
09-08 21:19:38.566  8648  8648 E AndroidRuntime: Process: com.htc.launcher, PID: 8648
09-08 21:19:38.566  8648  8648 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.566  8648  8648 E AndroidRuntime: 	... 11 more
09-08 21:19:38.566  1129  3575 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
09-08 21:19:38.566  1129  3575 E ActivityManager: App crashed! Process: com.htc.launcher
09-08 21:19:38.566  1129  3575 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.566  1129  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.566  1129  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.566  1129  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.566  1129  3575 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
09-08 21:19:38.566  1129  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.566  1129  8701 E ErrorReport: HtcErrorReportManager.Error in dumping error information
09-08 21:19:38.566  1129  8701 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1473362378579.dbox_tmp: open failed: EROFS (Read-only file system)
09-08 21:19:38.566  1129  8701 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.566  1129  8701 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.566  1129  8701 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:38.566  1129  8701 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
09-08 21:19:38.566  1129  8701 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:19:38.566  1129  8701 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.566  1129  8701 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.566  1129  8701 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.566  1129  8701 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.566  1129  8701 E ErrorReport: 	... 4 more
09-08 21:19:38.566  1129  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.566  1129  3575 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.566  1129  3575 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.566  1129  3575 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.566  1129  3575 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.566  1129  3575 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.566  1129  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.566  1129  3575 W System.err: 	... 14 more
09-08 21:19:38.566  1129  3575 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.566  1129  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.566  1129  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.566  1129  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.566  1129  3575 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.566  1129  3575 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.566  1129  3575 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.566  1129  3575 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.566  1129  3575 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.566  1129  3575 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.566  1129  3575 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.566  1129  3575 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.566  1129  3575 W System.err: 	... 14 more
09-08 21:19:38.566  8648  8648 D Process : killProcess, pid=8648
09-08 21:19:38.566  8648  8648 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
09-08 21:19:38.566  8648  8648 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:38.566  8648  8648 W HTCLOG  : mask=0x18
09-08 21:19:38.566  1129  3637 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.566  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.566  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.566  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.566  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.566  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
09-08 21:19:38.566  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
09-08 21:19:38.566  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
09-08 21:19:38.566  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
09-08 21:19:38.566  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
09-08 21:19:38.566  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
09-08 21:19:38.566  1129  3637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.566  1129  3637 W System.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.566  1129  3637 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.566  1129  3637 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.576  1129  3637 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.576  1129  3637 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.576  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.576  1129  3637 W System.err: 	... 12 more
09-08 21:19:38.596  8671  8671 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,09-08 21:19:38.596  8671  8671 W HTCLOG  : mask=0x18
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.596  8671  8671 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: FATAL EXCEPTION: main
09-08 21:19:38.596  8671  8671 E AndroidRuntime: Process: com.android.documentsui, PID: 8671
09-08 21:19:38.596  8671  8671 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
09-08 21:19:38.596  8671  8671 E AndroidRuntime: 	... 9 more
09-08 21:19:38.596  1129  1149 E ActivityManager: App crashed! Process: com.android.documentsui
09-08 21:19:38.596  1129  1149 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
09-08 21:19:38.596  1129  1149 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.596  1129  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.596  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.596  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.596  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.596  1129  1149 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.596  1129  1149 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.596  1129  1149 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.596  1129  1149 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.596  1129  1149 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.596  1129  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.596  1129  1149 W System.err: 	... 14 more
09-08 21:19:38.596  1129  1149 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.596  1129  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.596  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.596  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.596  1129  1149 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.596  1129  1149 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.596  1129  1149 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.596  1129  1149 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.596  1129  1149 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.606  1129  1149 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.606  1129  1149 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.606  1129  1149 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.606  1129  1148 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
09-08 21:19:38.606  1129  1149 W System.err: 	... 14 more
09-08 21:19:38.606  5640  5801 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
09-08 21:19:38.606  5640  5801 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
09-08 21:19:38.606  5640  5801 W HTCLOG  : mask=0x18
09-08 21:19:38.606  5640  5801 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x55c5889bd0
09-08 21:19:38.606  8671  8671 D Process : killProcess, pid=8671
09-08 21:19:38.606  8671  8671 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
09-08 21:19:38.606  5640  5801 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
09-08 21:19:38.606  5640  5801 E AndroidRuntime: Process: android.process.media, PID: 5640
09-08 21:19:38.606  5640  5801 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.606  5640  5801 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.606  8671  8671 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:38.606  1129  8703 E ErrorReport: HtcErrorReportManager.Error in dumping error information
09-08 21:19:38.606  1129  8703 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1473362378618.dbox_tmp: open failed: EROFS (Read-only file system)
09-08 21:19:38.606  1129  8703 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.606  1129  8703 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.606  1129  8703 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:38.606  1129  8703 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
09-08 21:19:38.606  1129  8703 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:19:38.606  1129  8703 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.606  1129  8703 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.606  1129  8703 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.606  1129  8703 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.606  1129  8703 E ErrorReport: 	... 4 more
09-08 21:19:38.606  8671  8671 W HTCLOG  : mask=0x18
09-08 21:19:38.606  1129  3637 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.606  1129  1148 E ActivityManager: App crashed! Process: android.process.media
09-08 21:19:38.606  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.606  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.606  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.606  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.606  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
09-08 21:19:38.606  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
09-08 21:19:38.606  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
09-08 21:19:38.606  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
09-08 21:19:38.606  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
09-08 21:19:38.606  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
09-08 21:19:38.606  1129  3637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.606  1129  3637 W System.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.606  1129  3637 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.606  1129  3637 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.606  1129  3637 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.606  1129  3637 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.606  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.606  1129  3637 W System.err: 	... 12 more
09-08 21:19:38.606  1129  1148 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.606  1129  1148 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.616  1129  8704 E ErrorReport: HtcErrorReportManager.Error in dumping error information
09-08 21:19:38.616  1129  8704 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1473362378623.dbox_tmp: open failed: EROFS (Read-only file system)
09-08 21:19:38.616  1129  8704 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.616  1129  8704 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.616  1129  8704 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:38.616  1129  8704 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
09-08 21:19:38.616  1129  8704 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:19:38.616  1129  8704 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.616  1129  8704 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.616  1129  8704 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.616  1129  8704 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.616  1129  8704 E ErrorReport: 	... 4 more
09-08 21:19:38.606  1129  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.606  1129  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.606  1129  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.606  1129  1148 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.606  1129  1148 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.606  1129  1148 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.606  1129  1148 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.606  1129  1148 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.606  1129  1148 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.606  1129  1148 W System.err: 	... 14 more
09-08 21:19:38.606  1129  1148 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.606  1129  1148 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.606  1129  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.606  1129  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.606  1129  1148 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.606  1129  1148 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.606  1129  1148 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.606  1129  1148 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.606  1129  1148 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.606  1129  1148 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.606  1129  1148 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.606  1129  1148 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.606  1129  1148 W System.err: 	... 14 more
09-08 21:19:38.616  5640  5801 D Process : killProcess, pid=5640
09-08 21:19:38.616  5640  5801 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
09-08 21:19:38.616  5640  5801 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:38.616  5640  5801 W HTCLOG  : mask=0x18
09-08 21:19:38.616  1129  3637 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.616  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.616  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.616  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.616  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.616  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
09-08 21:19:38.616  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
09-08 21:19:38.616  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
09-08 21:19:38.616  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
09-08 21:19:38.616  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
09-08 21:19:38.616  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
09-08 21:19:38.616  1129  3637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.616  1129  3637 W System.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.616  1129  3637 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.616  1129  3637 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.616  1129  3637 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.616  1129  3637 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.616  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.616  1129  3637 W System.err: 	... 12 more
09-08 21:19:38.626  1129  3979 I ActivityManager: Recipient 5640
09-08 21:19:38.626  1129  3503 I ActivityManager: Recipient 8648
09-08 21:19:38.636  1129  1161 I ActivityManager: Start proc 8705:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
,09-08 21:19:38.636  8705  8705 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:38.636  8705  8705 W HTCLOG  : mask=0x18
09-08 21:19:38.656   544   544 I art     : Explicit concurrent mark sweep GC freed 8663(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 125us total 19.197ms
09-08 21:19:38.676   544   544 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 210us total 17.118ms
09-08 21:19:38.676  8322  8692 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
09-08 21:19:38.676  8322  8692 W HTCLOG  : mask=0x18
,09-08 21:19:38.676  8322  8692 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182),
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976),
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	,at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
,09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147),
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
,09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	,at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
,09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-08 21:19:38.676  8322  8692 E SQLiteDatabase: ,	at java.lang.Thread.run(Thread.java:818)
09-08 21:19:38.686  1129  3979 I ActivityManager: Process android.process.media (pid 5640) has died
09-08 21:19:38.686  1129  3979 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 20737ms
09-08 21:19:38.686  1129  3979 W HTCLOG  : use specified tag [JavaBinder], func [0].
09-08 21:19:38.686  1129  3979 W HTCLOG  : mask=0x18
09-08 21:19:38.686  1129  3979 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-08 21:19:38.686   544   544 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 120us total 16.971ms
09-08 21:19:38.686  1129  3573 I ActivityManager: Recipient 8671
,09-08 21:19:38.696  3318  4203 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
,09-08 21:19:38.696  1129  3979 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
,09-08 21:19:38.696  1129  3979 V WindowManager: addAppToken: AppWindowToken{32bcba05 token=Token{134ca17c ActivityRecord{2c8c306f u0 com.htc.launcher/.Launcher t5}}} to stack=0 task=5 at 0
09-08 21:19:38.706  3206  3206 I NotificationStackScrollLayout: setBlockTouchEnabled:false
09-08 21:19:38.706  1129  3503 I ActivityManager: Process com.htc.launcher (pid 8648) has died
,09-08 21:19:38.716  1129  3503 I ActivityManager: Start proc 8727:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,09-08 21:19:38.716  1129  3637 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,09-08 21:19:38.716  1129  3573 I ActivityManager: Process com.android.documentsui (pid 8671) has died
09-08 21:19:38.716  8322  8692 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.716  8322  8670 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.716  8322  8670 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
,09-08 21:19:38.726  8322  8670 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	,at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
,09-08 21:19:38.726  8322  8670 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.726  8322  8670 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@15477dd]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.util.workflow.Workfl,owService.executeWorkflow(WorkflowService.java:321)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.726  8322  8670 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.726  8727  8727 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:38.726  8727  8727 W HTCLOG  : mask=0x18
09-08 21:19:38.726  8322  8322 I DeviceManagement: WorkflowService: Stopping workflow service
,09-08 21:19:38.756  8705  8705 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
,09-08 21:19:38.756  8705  8748 D PowerUtils: getUserIdOfProcess, curUserId = 0
,09-08 21:19:38.756  8705  8748 D PowerUtils: isRunningUnderOwner, isOwner = true
,09-08 21:19:38.766  8727  8727 I MultiDex: VM with version 2.1.0 has multidex support,
09-08 21:19:38.766  8727  8727 I MultiDex: install
09-08 21:19:38.766  8727  8727 I MultiDex: VM has multidex support, MultiDex support library is disabled.
09-08 21:19:38.766  8749  8749 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:38.766  8749  8749 W HTCLOG  : mask=0x18
,09-08 21:19:38.776  1129  3506 I ActivityManager: Start proc 8749:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
,09-08 21:19:38.786  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : null
09-08 21:19:38.786  8727  8727 D FaceDetectTask: checkIsOmronEnable start
,09-08 21:19:38.786  8727  8727 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so,
09-08 21:19:38.786  8705  8748 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,09-08 21:19:38.786  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
09-08 21:19:38.786  8727  8727 D FaceDetectTask: IsOmronEnable : true
09-08 21:19:38.786  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.786  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,09-08 21:19:38.786  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.786  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.786  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.786  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
09-08 21:19:38.786  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,09-08 21:19:38.796  8705  8748 D PowerUsageService: removed uid = 10142
,09-08 21:19:38.796  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,09-08 21:19:38.796  8727  8727 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,09-08 21:19:38.796  8705  8748 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
09-08 21:19:38.796  8705  8748 W HTCLOG  : mask=0x18
,09-08 21:19:38.796  8727  8727 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
,09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.796  8705  8748 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
09-08 21:19:38.796  8705  8748 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 8705
09-08 21:19:38.796  8705  8748 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.796  8705  8748 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 21:19:38.796  1129  3485 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
09-08 21:19:38.796  1129  3485 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
09-08 21:19:38.796  1129  3485 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.796  1129  3485 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.796  1129  3485 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.796  1129  3485 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.796  1129  3485 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
09-08 21:19:38.806  1129  8778 E ErrorReport: HtcErrorReportManager.Error in dumping error information
09-08 21:19:38.806  1129  8778 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1473362378815.dbox_tmp: open failed: EROFS (Read-only file system)
09-08 21:19:38.806  1129  8778 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.806  1129  8778 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.806  1129  8778 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:38.806  1129  8778 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
09-08 21:19:38.806  1129  8778 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:19:38.806  1129  8778 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.806  1129  8778 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.806  1129  8778 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.806  1129  8778 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.806  1129  8778 E ErrorReport: 	... 4 more
09-08 21:19:38.796  1129  3485 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.796  1129  3485 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.796  1129  3485 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.796  1129  3485 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.796  1129  3485 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.796  1129  3485 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.796  1129  3485 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.796  1129  3485 W System.er,r: 	... 14 more
09-08 21:19:38.796  1129  3485 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.796  1129  3485 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.796  1129  3485 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.796  1129  3485 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.796  1129  3485 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
09-08 21:19:38.796  1129  3485 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
09-08 21:19:38.806  1129  3485 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.806  1129  3485 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.806  1129  3485 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.806  1129  3485 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.806  1129  3485 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.806  1129  3485 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.806  1129  3485 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.806  1129  3485 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.806  1129  3485 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.806  1129  3485 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.806  1129  3485 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
,09-08 21:19:38.806  1129  3485 W System.err: 	... 14 more
09-08 21:19:38.806  8705  8748 D Process : killProcess, pid=8705
09-08 21:19:38.806  8705  8748 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
09-08 21:19:38.806  1129  3637 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.816  1129  3506 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
09-08 21:19:38.806  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,09-08 21:19:38.806  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.806  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.806  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.806  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
09-08 21:19:38.806  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
09-08 21:19:38.806  8705  8748 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:38.806  8705  8748 W HTCLOG  : mask=0x18
09-08 21:19:38.806  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
09-08 21:19:38.806  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
09-08 21:19:38.806  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
09-08 21:19:38.806  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
09-08 21:19:38.806  1129  3637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.806  1129  3637 W System.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.806  1129  3637 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.806  1129  3637 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.806  1129  3637 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.806  1129  3637 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.806  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.806  1129  3637 W System.err: 	... 12 more
09-08 21:19:38.806  8727  8727 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
09-08 21:19:38.806  8727  8727 W HTCLOG  : mask=0x18
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenH,elper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.806  8727  8727 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.806  8727  8727 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.816  1129  3506 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.826  1129  8779 E ErrorReport: HtcErrorReportManager.Error in dumping error information
09-08 21:19:38.826  1129  8779 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1473362378830.dbox_tmp: open failed: EROFS (Read-only file system)
09-08 21:19:38.826  1129  8779 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.826  1129  8779 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.826  1129  8779 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:38.826  1129  8779 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
09-08 21:19:38.826  1129  8779 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:19:38.826  1129  8779 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.826  1129  8779 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.826  1,129  8779 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.826  1129  8779 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.826  1129  8779 E ErrorReport: 	... 4 more
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.806  8727  8727 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
09-08 21:19:38.806  8727  8727 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.806  8727  8727 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.806  8727  8727 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.806  8727  8727 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.806  8727  8727 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.806  8727  8727 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.816  8727  8727 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: FATAL EXCEPTION: main
09-08 21:19:38.816  8727  8727 E AndroidRuntime: Process: com.htc.launcher, PID: 8727
09-08 21:19:38.816  8727  8727 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
09-08 21:19:38.816  8727  8727 E AndroidRuntime: 	... 11 more
09-08 21:19:38.816  1129  3506 E ActivityManager: App crashed! Process: com.htc.launcher
09-08 21:19:38.816  1129  3506 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.816  1129  3506 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.816  1129  3506 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.816  1129  3506 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.816  1129  3506 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.816  1129  3506 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.816  1129  3506 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.816  1129  3506 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.816  1129  3506 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.816  1129  3506 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.816  1129  3506 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.816  1129  3506 W System.err: 	... 14 more
09-08 21:19:38.816  1129  3506 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.816  1129  3506 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.816  1129  3506 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.816  1129  3506 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.816  1129  3506 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.816  1129  3506 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.816  1129  3506 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.816  1129  3506 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.816  1129  3506 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.816  1129  3506 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.816  1129  3506 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.816  1129  3506 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.816  1129  3506 W System.err: 	... 14 more
09-08 21:19:38.816  8727  8727 D Process : killProcess, pid=8727
09-08 21:19:38.816  8727  8727 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
09-08 21:19:38.816  8727  8727 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:38.816  8727  8727 W HTCLOG  : mask=0x18
09-08 21:19:38.826  1129  3637 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.826  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.826  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.826  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.826  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.826  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
09-08 21:19:38.826  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
09-08 21:19:38.826  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
09-08 21:19:38.826  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
09-08 21:19:38.826  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
09-08 21:19:38.826  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
09-08 21:19:38.826  1129  3637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.826  1129  3637 W System.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.826  1129  3637 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.826  1129  3637 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.826  1129  3637 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.826  1129  3637 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.826  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.826  1129  3637 W System.err: 	... 12 more
09-08 21:19:38.856  1129  3364 I ActivityManager: Recipient 8705
09-08 21:19:38.856  1129  3364 I ActivityManager: Process com.htc.htcpowermanager:remote (pid 8705) has died
09-08 21:19:38.856  1129  3364 W ActivityManager: Scheduling restart of crashed service com.htc.htcpowermanager/.battery.PowerUsageService in 30570ms
09-08 21:19:38.856  8749  8780 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
09-08 21:19:38.856  8749  8780 W HTCLOG  : mask=0x18
,09-08 21:19:38.856  8749  8780 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.856  8749  8780 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
09-08 21:19:38.856  8749  8780 E AndroidRuntime: Process: com.htc.updater, PID: 8749
09-08 21:19:38.856  8749  8780 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.856  8749  8780 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.866  1129  3364 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
09-08 21:19:38.866  8749  8749 V UpdaterAPK | DownloadService: Service onStart
09-08 21:19:38.866  1129  3364 V WindowManager: addAppToken: AppWindowToken{1ecd24bd token=Token{36b5a414 ActivityRecord{3a33be67 u0 com.htc.launcher/.Launcher t6}}} to stack=0 task=6 at 0
09-08 21:19:38.866  1129  3573 E ActivityManager: App crashed! Process: com.htc.updater
09-08 21:19:38.866  1129  3573 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
09-08 21:19:38.866  8749  8781 V UpdaterAPK | DownloadService: Updating for startId 1
09-08 21:19:38.866  1129  3573 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.866  1129  3573 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.866  1129  3573 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.866  1129  3573 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.866  1129  3573 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.866  1129  3573 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.866  1129  3573 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.866  1129  3573 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.866  1129  3573 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.866  1129  3573 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.866  1129  3573 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.866  1129  3573 W System.err: 	... 14 more
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:98)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.866  8749  8781 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.866  1129  3573 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.876  1129  8783 E ErrorReport: HtcErrorReportManager.Error in dumping error information
09-08 21:19:38.876  1129  8783 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1473362378884.dbox_tmp: open failed: EROFS (Read-only file system)
09-08 21:19:38.876  1129  8783 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.876  1129  8783 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.876  1129  8783 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 21:19:38.876  1129  8783 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
09-08 21:19:38.876  1129  8783 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
09-08 21:19:38.876  1129  8783 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.876  1129  8783 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.876  1129  8783 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.876  1129  8783 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.876  1129  8783 E ErrorReport: 	... 4 more
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: Couldn't open downloads.db for writing (will try read-only):
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:98)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.866  8749  8781 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.866  1129  3573 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.866  1129  3573 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.866  1129  3573 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.866  1129  3573 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
09-08 21:19:38.866  1129  3573 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
09-08 21:19:38.866  1129  3573 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
09-08 21:19:38.866  1129  3573 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
09-08 21:19:38.866  1129  3573 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.866  1129  3573 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.866  1129  3573 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.886  1129  3967 I ActivityManager: Recipient 8727
09-08 21:19:38.866  1129  3573 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.866  1129  3573 W System.err: 	... 14 more
09-08 21:19:38.866  8749  8781 W SQLiteOpenHelper: Opened downloads.db in read-only mode
09-08 21:19:38.866  8749  8781 V UpdaterAPK | DownloadProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
09-08 21:19:38.876  1129  3637 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
09-08 21:19:38.876  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-08 21:19:38.876  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 21:19:38.876  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
09-08 21:19:38.876  1129  3637 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
09-08 21:19:38.876  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
09-08 21:19:38.876  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
09-08 21:19:38.876  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
09-08 21:19:38.876  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
09-08 21:19:38.876  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
09-08 21:19:38.876  1129  3637 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
09-08 21:19:38.876  1129  3637 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:19:38.876  1129  3637 W System.err: 	at android.os.Looper.loop(Looper.java:155)
09-08 21:19:38.876  1129  3637 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 21:19:38.876  8749  8781 V UpdaterAPK | DownloadProvider: created cursor android.database.sqlite.SQLiteCursor@1f6a8f52 on behalf of 8749
09-08 21:19:38.876  8749  8780 D Process : killProcess, pid=8749
09-08 21:19:38.876  8749  8780 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
09-08 21:19:38.876  8749  8780 W HTCLOG  : use specified tag [Process], func [0].
09-08 21:19:38.876  8749  8780 W HTCLOG  : mask=0x18
09-08 21:19:38.876  1129  3637 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 21:19:38.876  3973  3973 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
09-08 21:19:38.876  1129  3637 W System.err: 	at libcore.io.Posix.open(Native Method)
09-08 21:19:38.876  1129  3637 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 21:19:38.876  1129  3637 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-08 21:19:38.876  1129  3637 W System.err: 	... 12 more
09-08 21:19:38.886  1129  3485 I ActivityManager: Start proc 8784:com.google.android.gms/u0a19 for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver
09-08 21:19:38.886  1129  3967 I ActivityManager: Process com.htc.launcher (pid 8727) has died
,09-08 21:19:38.906  8784  8784 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:38.906  1129  3967 I ActivityManager: Start proc 8794:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
09-08 21:19:38.906  8784  8784 W HTCLOG  : mask=0x18
09-08 21:19:38.906  1129  3637 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
09-08 21:19:38.906  8794  8794 W HTCLOG  : use specified tag [FDManager], func [0].
09-08 21:19:38.906  8794  8794 W HTCLOG  : mask=0x18

```
