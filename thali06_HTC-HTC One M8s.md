#### Test 6275440391a6bae_thali06_HTC-HTC One M8s Logs


```
--------- beginning of system
,03-15 20:38:03.208   924  1140 D PMS     : acquireWL(15ccbe2d): PARTIAL_WAKE_LOCK  *alarm* 0x1 924 1000 WorkSource{1000}
03-15 20:38:03.208   924  1140 V AlarmManager: sending alarm PendingIntent{2decdf62: PendingIntentRecord{21b728f3 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1458070648597, Int=0
03-15 20:38:03.208   924  1140 V AlarmManager: sending alarm PendingIntent{38a2eeee: PendingIntentRecord{3c406f8f android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=199655, Int=0
03-15 20:38:03.208   924   924 D PMS     : acquireWL(868a9b0): PARTIAL_WAKE_LOCK  *backup* 0x1 924 1000 null
03-15 20:38:03.208   924  1140 V AlarmManager: sending alarm PendingIntent{26641029: PendingIntentRecord{3e3d8fae android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=202871, Int=0
03-15 20:38:03.208   924  1140 V AlarmManager: sending alarm PendingIntent{1091614f: PendingIntentRecord{2ba6b0dc com.google.android.gms broadcastIntent}}, i=com.google.android.gms.gcm.ACTION_CHECK_QUEUE, t=2, cnt=1, w=189921, Int=0
03-15 20:38:03.218   924  1164 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
03-15 20:38:03.218   924  1628 D PMS     : acquireWL(60485e5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.218   924  1164 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
03-15 20:38:03.218   924  1164 D PMS     : releaseWL(868a9b0): PARTIAL_WAKE_LOCK  *backup* 0x1 null
03-15 20:38:03.238   924   924 D PMS     : releaseWL(15ccbe2d): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
--------- beginning of main
03-15 20:38:03.238  1222  2483 D WeatherUtility: Weather sync is On
03-15 20:38:03.238  1222  2483 W WeatherTimeKeeper: [refreshWeatherData] no weather data
03-15 20:38:03.248   924  2342 D PMS     : acquireWL(24d6f8ba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.268   924   980 D PMS     : releaseWL(60485e5): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.288  1825  1825 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-15 20:38:03.318   924  1627 D PMS     : releaseWL(24d6f8ba): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.318   924  1389 D PMS     : acquireWL(33963f74): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.328   924  1609 D PMS     : releaseWL(33963f74): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.328   924  1628 D PMS     : acquireWL(6068c9d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.338   924  1160 D PMS     : releaseWL(6068c9d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.338   924  1609 D PMS     : acquireWL(2e0fe512): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.398   924  1160 D PMS     : acquireWL(327c34e3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.458   924  2342 D PMS     : acquireWL(3e445599): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.478  6900  6906 E cutils-trace: Error opening trace file: Permission denied (13)
03-15 20:38:03.478   924  1627 D PMS     : releaseWL(2e0fe512): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.488  1825  6912 I VacuumService: Vacuum at: now=1458070683499 tag=VacuumService
03-15 20:38:03.508   924  1616 D PMS     : releaseWL(3e445599): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.508   924  1389 D PMS     : acquireWL(16333c3f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.518   924   981 D PMS     : releaseWL(327c34e3): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.558   924  2342 D PMS     : releaseWL(16333c3f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.558   924  1389 D PMS     : acquireWL(27e6090c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.608  6900  6900 D CustomizationManager: ====startRecUseTime====
03-15 20:38:03.608   924  1160 D PMS     : releaseWL(27e6090c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.608  6900  6900 D htc.customization.log.level:  is 
03-15 20:38:03.608   924  1609 D PMS     : acquireWL(1efbb255): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.608  6900  6900 W CustomizationLogLevel: Level value is invalid, use default level 2
03-15 20:38:03.618   924  1626 D PMS     : releaseWL(1efbb255): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
03-15 20:38:03.698  6900  6900 D CustomizationManager:  Read ACC file spent 0.053 (s)
03-15 20:38:03.708  6900  6900 D CIDMapFileReader: Parsing tag item name = HTC__001
03-15 20:38:03.708  6900  6900 D CIDMapFileReader: Parsing tag item name = HTC__102
03-15 20:38:03.708  6900  6900 D CIDMapFileReader: Parsing tag item name = HTC__Y13
03-15 20:38:03.708  6900  6900 D CIDMapFileReader: Parsing tag item name = HTC__032
03-15 20:38:03.708  6900  6900 D CIDMapFileReader: Parsing tag item name = HTC__M27
03-15 20:38:03.708  6900  6900 D CIDMapFileReader: Parsing tag item name = HTC__002
03-15 20:38:03.708  6900  6900 D CIDMapFileReader: Parsing tag item name = HTC__031
03-15 20:38:03.708  6900  6900 V CustomizationCIDLoader: full path : /system/customize/CID/HTC__102.xml
03-15 20:38:03.708  6900  6900 I CustomizationCIDLoader: Parsing tag category name = system
03-15 20:38:03.708  6900  6900 I CustomizationCIDLoader: Parsing tag category name = application
03-15 20:38:03.708  6900  6900 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: Parsing tag category name = AudioService
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: Parsing tag category name = Settings
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: Parsing tag category name = ACC
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 42507
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 21902
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 26006:26001.26002.26003
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23420
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 22299
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 24002
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23210
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23205
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23806
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23430
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23408
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 27205
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 42507:C:1:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 21902:C:1:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 26006:D:1:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23420:D:0:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 22299:D:0:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 24002:D:0:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23210:D:2:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23205:D:0:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23806:D:0:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23430:C:1:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 23408:C:1:0
03-15 20:38:03.718  6900  6900 I CustomizationCIDLoader: add string-array item, value = 27205:C:1:0
03-15 20:38:03.718  6900  6900 D CustomizationManager:  Read CID file spent 0.107 (s)
03-15 20:38:03.718  6900  6900 D CustomizationManager:  All configurations done spent 0.107 (s)
03-15 20:38:03.798   924  1597 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 6900 on display 0
03-15 20:38:03.798   924  1059 D PMS     : acquireHCC(243f046a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 924 1000 null
03-15 20:38:03.798   924  1059 D PMS     : acquireHCC(36295d5b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 924 1000 null
03-15 20:38:03.808   924  1597 W asset   : Copying FileAsset 0x55974550d0 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
03-15 20:38:03.828   924  1597 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6922 uid=10195 gids={50195, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-15 20:38:03.858  1326  1326 D DotMatrix: [EventService]  onDisplayChanged: 0
03-15 20:38:03.858   924   924 V ActivityManager: Display changed displayId=0
03-15 20:38:03.858  1326  1326 D DotMatrix: [EventService] mbHDMIConnect: false, mCoverOn:false
03-15 20:38:03.888  6922  6922 W asset   : Copying FileAsset 0xac4c3e48 (zip:/data/app/com.test.thalitest-1/base.apk:/resources.arsc) to buffer size 2468 to make it aligned.
03-15 20:38:03.908  1595  1595 I TrimMemoryManager: [trimMemory] 20
03-15 20:38:04.018  6922  6922 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311750)
,03-15 20:38:04.058  6922  6922 I LibraryLoader: Time to load native libraries: 10 ms (timestamps 3719-3729)
,03-15 20:38:04.068  6922  6922 I LibraryLoader: Expected native library version number "",actual native library version number "",
,03-15 20:38:04.078  6922  6922 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e45b08e},
03-15 20:38:04.078  6922  6922 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 20:38:04.078  6922  6922 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
,03-15 20:38:04.098  6922  6922 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,03-15 20:38:04.098  6922  6922 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:38:04.098  6922  6922 E SysUtils: ApplicationContext is null in ApplicationStatus,
,03-15 20:38:04.158  6922  6922 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty(),
,03-15 20:38:04.158  6922  6922 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-15 20:38:04.158  6922  6922 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-15 20:38:04.158  6922  6922 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: LNXBUILD_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006+PATCH[ES]_msm8916_64_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006__release_ENGG (Iba0e932ba2)
03-15 20:38:04.158  6922  6922 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.01
03-15 20:38:04.158  6922  6922 I Adreno-EGL: Build Date: 03/09/15 Mon
03-15 20:38:04.158  6922  6922 I Adreno-EGL: Local Branch: 
03-15 20:38:04.158  6922  6922 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.00.031.006
03-15 20:38:04.158  6922  6922 I Adreno-EGL: Local Patches: 7ff34bcc0bbd0887eacd18980e911eb61bd8f4e0 es20: fix apilog_close calling sequence in context_delete
03-15 20:38:04.158  6922  6922 I Adreno-EGL:                  d74aa161a12b9c6fc6332151
,03-15 20:38:04.208   924   980 W System.err: java.lang.Throwable: stack dump
,03-15 20:38:04.208   924   980 W System.err: 	at java.lang.Thread.dumpStack(Thread.java:490)
03-15 20:38:04.208   924   980 W System.err: 	at com.android.server.BluetoothManagerService.registerAdapter(BluetoothManagerService.java:448)
03-15 20:38:04.208   924   980 W System.err: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:55)
03-15 20:38:04.208   924   980 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
03-15 20:38:04.208   924  1047 D BluetoothManagerService: Message: MESSAGE_REGISTER_ADAPTER
,03-15 20:38:04.208   924  1047 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a39b32f:true
,03-15 20:38:04.208  6922  6957 D BluetoothAdapter: 586172314: getState(). Returning 12
,03-15 20:38:04.278  6922  6922 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:38:04.288  6922  6922 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-15 20:38:04.298  6922  6922 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
,03-15 20:38:04.308  6922  6922 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 20:38:04.308  6922  6922 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:38:04.348   924  1644 W HtcSystemUPManager: HtcSystemUPHandler The policy is disabled. AppId: activity_history, category: launch
,03-15 20:38:04.358  6922  6955 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-15 20:38:04.378   924  1046 D StatusBarManagerService: setSystemUiVisibility(0xc0000600)
,03-15 20:38:04.378   924  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 20:38:04.378   924  1046 D StatusBarManagerService: hiding MENU key
03-15 20:38:04.378   924  1046 D StatusBarManagerService: setSystemUiVisibility(0x8600)
03-15 20:38:04.378   924  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 20:38:04.378   924  1046 D StatusBarManagerService: hiding MENU key
,03-15 20:38:04.398  6922  6922 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-15 20:38:04.498  6922  6922 I InputMethodManager: [startInputInner] EditorInfo { packageName=com.test.thalitest, inputType=0xa1, imeOptions=0x12000000, privateImeOptions=null }, windowGainingFocus=android.view.ViewRootImpl$W@426d797, mServedView=org.apache.cordova.engine.SystemWebView{3003fd84 VFEDH.C. .F...... 0,0-1080,1701 #64}, mServedInputConnectionWrapper=android.view.inputmethod.InputMethodManager$ControlledInputConnectionWrapper@109596d
,03-15 20:38:04.508  1222  1222 I PhoneStatusBar: setImeWindowStatus(false,false)
03-15 20:38:04.508   924  1160 I InputMethodManagerService: Disable input method client, pid=1595
03-15 20:38:04.508   924  1160 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,03-15 20:38:04.518  6922  6922 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,03-15 20:38:04.528   924  1048 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +660ms (total +706ms)
,03-15 20:38:04.558  6922  6922 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6922
,03-15 20:38:04.638  6922  6922 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode,
,03-15 20:38:04.718  6922  6972 D jxcore_app_log: JniHelper::setJavaVM(0xab3588f8), pthread_self() = -1402402128
,03-15 20:38:04.728  6922  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-15 20:38:04.728  6922  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-15 20:38:04.728  6922  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-15 20:38:04.728  6922  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-15 20:38:04.728  6922  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-15 20:38:04.728  6922  6972 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@15f252a1 added. We now have 1 listener(s)
,03-15 20:38:04.728   924  1628 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,03-15 20:38:04.728  6922  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:F6:69:77
03-15 20:38:04.728  6922  6972 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
03-15 20:38:04.728  6922  6972 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"90:E7:C4:F6:69:77"}
03-15 20:38:04.728  6922  6972 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-15 20:38:04.728  6922  6972 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:F6:69:77
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1,
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38a3cfb4 added. We now have 1 listener(s)
03-15 20:38:04.738  6922  6972 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-15 20:38:04.738   924  1152 D WifiService: New client listening to asynchronous messages
03-15 20:38:04.738   924   924 E WifiTrafficPoller: ADD_CLIENT: 8
,03-15 20:38:04.738  6922  6972 D BluetoothAdapter: 586172314: getState(). Returning 12
03-15 20:38:04.738  6922  6972 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-15 20:38:04.738  6922  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-15 20:38:04.738  6922  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-15 20:38:04.738  6922  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-15 20:38:04.738  6922  6972 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-15 20:38:04.748  6922  6972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-15 20:38:04.748   924   981 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-15 20:38:04.748  6922  6972 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:F6:69:77
,03-15 20:38:04.748  6922  6972 D BluetoothAdapter: 586172314: getState(). Returning 12
,03-15 20:38:04.748  6922  6972 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-15 20:38:04.748  6922  6972 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-15 20:38:04.748  6922  6972 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-15 20:38:04.748  6922  6972 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-15 20:38:04.748  6922  6972 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-15 20:38:04.748  6922  6972 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-15 20:38:04.748  6922  6972 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-15 20:38:04.748  6922  6972 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-15 20:38:04.748  6922  6972 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-15 20:38:04.748  6922  6972 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-15 20:38:04.758  6922  6922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 20:38:04.758  6922  6922 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 20:38:04.778  6922  6922 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-15 20:38:05.588  6922  6979 W jxcore-log: Initializing JXcore engine,
03-15 20:38:05.588  6922  6979 W jxcore-log: JXcore engine is ready
,03-15 20:38:05.638  6922  6979 W jxcore-log: Starting JXcore engine
,03-15 20:38:05.728  6922  6979 W jxcore-log: Platform android
03-15 20:38:05.728  6922  6979 W jxcore-log: 
03-15 20:38:05.728  6922  6979 W jxcore-log: Process ARCH arm
03-15 20:38:05.728  6922  6979 W jxcore-log: 
,03-15 20:38:05.798   924  1059 D PMS     : releaseHCC(243f046a): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
03-15 20:38:05.798   924  1059 D PMS     : releaseHCC(36295d5b): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,03-15 20:38:06.098  6922  6979 I jxcore-log: JXcore Cordova bridge is ready!
03-15 20:38:06.098  6922  6979 I jxcore-log: 
,03-15 20:38:06.098  6922  6979 W jxcore-log: JXcore engine is started
,03-15 20:38:06.108  6922  6972 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,03-15 20:38:06.118  6922  6979 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
03-15 20:38:06.118  6922  6979 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-15 20:38:06.128  6922  6922 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54),
,03-15 20:38:06.148   924  1627 I ActivityManager: Killing 5493:com.htc.mediamanager/u0a28 (adj 15): empty #17,
03-15 20:38:06.148   924  1627 D Process : killProcessQuiet, pid=5493
,03-15 20:38:06.148   924  1627 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityStack.destroyActivityLocked:3422 
,03-15 20:38:06.258   924  1609 I ActivityManager: Recipient 5493,
,03-15 20:38:06.368  6922  6972 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 234ms. Plugin should use CordovaInterface.getThreadPool().,
,03-15 20:38:06.428  6922  6922 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@204077dd that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:38:06.428  6922  6922 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@204077dd that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1749)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:488)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	,at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
03-15 20:38:06.428  6922  6922 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 20:38:06.438  6922  6922 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@31e68f52 that was originally registered here. Are you missing a call to unregisterReceiver()?,
03-15 20:38:06.438  6922  6922 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@31e68f52 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:1003)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:767)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:1775)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1755)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1749)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
,03-15 20:38:06.438  6922  6922 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123),
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at android.os.Looper.loop(Looper.java:155)
03-15 20:38:06.438  6922  6922 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 20:38:11.198  1222  2505 D HtcUPManager: HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app,
,03-15 20:38:11.198  1222  2505 D HtcUPManager: HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED
03-15 20:38:11.198  1659  1659 D HtcAppUPService: HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@5841e5a
,03-15 20:38:11.198   924   981 D Process : killProcessQuiet, pid=6689
03-15 20:38:11.198   924   981 I ActivityManager: Killing 6689:com.google.android.setupwizard/u0a77 (adj 15): empty #17
03-15 20:38:11.198   924   981 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-15 20:38:11.298   924  1597 I ActivityManager: Recipient 6689
,03-15 20:38:29.358   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-15 20:38:32.038   924  1389 D PMS     : acquireWL(1ac1be22): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 924 1000 null
03-15 20:38:32.038   924  1389 I BatteryService: n_update end
03-15 20:38:32.038   924  1389 D PMS     : releaseWL(1ac1be22): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 20:38:32.048   924   924 D UsbnetService: BroadcastReceiver::onReceive+
03-15 20:38:32.048   924   924 D NotificationService: plugged=true pluggin=true
03-15 20:38:32.048   924   924 D UsbnetService: onReceive BATTERY_CHANGED
03-15 20:38:32.048   924  1152 D WifiController: battery changed pluggedType: 2,
03-15 20:38:32.048   924   924 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 20:38:32.048   924   924 D UsbnetService: BroadcastReceiver::onReceive-
03-15 20:38:32.048   924  1152 D WifiController: handleMessage: E msg.what=155652
03-15 20:38:32.048   924  1152 D WifiController: processMsg: DeviceActiveState
03-15 20:38:32.048   924  1152 D WifiController: processMsg: StaEnabledState
03-15 20:38:32.048   924  1152 D WifiController: processMsg: DefaultState
03-15 20:38:32.048   924  1152 D WifiController: handleMessage: X
03-15 20:38:32.048  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:38:32.048  1222  1222 D PowerUI : closing low battery warning: level=100
,03-15 20:38:32.048  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
03-15 20:38:32.048   924  1055 D HtcPowerSaver: updateBatteryInfo
03-15 20:38:32.048  1326  1326 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 20:38:32.048   924   924 D PMS     : runPSCheck
03-15 20:38:32.048  1222  1533 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 20:38:32.048   924   924 D HtcPowerSaver: Checking...
03-15 20:38:32.048   924   924 I HtcPowerSaver: >> updateStatus
03-15 20:38:32.058  3018  3132 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:38:32.048  1222  1222 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,03-15 20:38:32.058   924   924 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 20:38:32.058   924   924 I HtcPowerSaver: << updateStatus
,03-15 20:38:32.098  1222  1222 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-15 20:38:39.368   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-15 20:38:54.368   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-15 20:39:14.378   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
03-15 20:39:35.498   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e]
03-15 20:39:35.498   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-BSS-REMOVED 0 f0:f2:6d:22:99:3e
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 3 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
03-15 20:39:35.498   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0]
03-15 20:39:35.498   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: CTRL-EVENT-BSS-REMOVED 3 00:1f:27:54:70:c0
,03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 2 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 4 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 9 BSSID 00:1f:27:54:e0:40 SSID '\x00' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 10 BSSID 00:1f:27:54:e0:44 SSID '\x00' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 11 BSSID 00:22:0d:46:1c:a0 SSID '\x00' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 13 BSSID 00:22:0d:46:1c:a2 SSID '\x00' due to wpa_bss_flush_by_age
,03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 12 BSSID 00:22:0d:46:1c:a4 SSID '\x00' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 5 BSSID 00:16:a6:1e:e0:a4 SSID '' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 14 BSSID 00:22:0d:47:49:80 SSID '\x00' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 15 BSSID 00:22:0d:47:49:84 SSID '\x00' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 6 BSSID 00:1f:27:54:dd:e3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 8 BSSID 00:22:0d:46:1c:a3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
03-15 20:39:35.498  1317  1317 D wpa_supplicant: wlan0: BSS: Remove id 7 BSSID 00:1f:27:54:e0:43 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
03-15 20:39:35.498   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1]
03-15 20:39:35.498   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-BSS-REMOVED 2 00:1f:27:54:70:c1
03-15 20:39:35.498   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 4 00:16:a6:1f:06:5c]
03-15 20:39:35.498   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-BSS-REMOVED 4 00:16:a6:1f:06:5c
03-15 20:39:35.498   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:e0:40]
03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: CTRL-EVENT-BSS-REMOVED 9 00:1f:27:54:e0:40
03-15 20:39:35.508   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 10 00:1f:27:54:e0:44]
03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-BSS-REMOVED 10 00:1f:27:54:e0:44
03-15 20:39:35.508   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 11 00:22:0d:46:1c:a0]
03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-BSS-REMOVED 11 00:22:0d:46:1c:a0,
03-15 20:39:35.508   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 13 00:22:0d:46:1c:a2]
03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-BSS-REMOVED 13 00:22:0d:46:1c:a2
03-15 20:39:35.508   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 12 00:22:0d:46:1c:a4]
03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-BSS-REMOVED 12 00:22:0d:46:1c:a4
03-15 20:39:35.508   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 5 00:16:a6:1e:e0:a4]
03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-BSS-REMOVED 5 00:16:a6:1e:e0:a4
03-15 20:39:35.508   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 14 00:22:0d:47:49:80]
03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-BSS-REMOVED 14 00:22:0d:47:49:80
03-15 20:39:35.508   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 15 00:22:0d:47:49:84]
03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: CTRL-EVENT-BSS-REMOVED 15 00:22:0d:47:49:84
03-15 20:39:35.508   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e3]
03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-BSS-REMOVED 6 00:1f:27:54:dd:e3
03-15 20:39:35.508   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 8 00:22:0d:46:1c:a3]
03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-BSS-REMOVED 8 00:22:0d:46:1c:a3
03-15 20:39:35.508   924  1764 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:e0:43]
,03-15 20:39:35.508   924  1764 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: CTRL-EVENT-BSS-REMOVED 7 00:1f:27:54:e0:43
,03-15 20:39:39.388   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-15 20:40:19.418   924  1140 D PMS     : acquireWL(1cb880b3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 924 1000 WorkSource{1000}
03-15 20:40:19.428   924  1140 V AlarmManager: sending alarm PendingIntent{38a2eeee: PendingIntentRecord{3c406f8f android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=259655, Int=0
,03-15 20:40:19.428   924  1140 V AlarmManager: sending alarm PendingIntent{2f378670: PendingIntentRecord{303a8de9 com.google.android.gms broadcastIntent}}, i=null, t=0, cnt=1, w=1458070781736, Int=1800000
,03-15 20:40:19.428   924  1140 V AlarmManager: sending alarm PendingIntent{34b0750f: PendingIntentRecord{b66999c com.htc.backup startService}}, i=resume, t=0, cnt=1, w=1458070819431, Int=0
,03-15 20:40:19.438   924  1597 D PMS     : acquireWL(8251fa5): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 4386 10024 WorkSource{10024 com.google.android.gms}
,03-15 20:40:19.458   924   924 D PMS     : releaseWL(1cb880b3): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
03-15 20:40:19.458  1222  2483 D WeatherUtility: Weather sync is On
03-15 20:40:19.458  1222  2483 W WeatherTimeKeeper: [refreshWeatherData] no weather data
03-15 20:40:19.468   924  1628 D PMS     : acquireWL(1089532b): PARTIAL_WAKE_LOCK  Event Log Service 0x1 4386 10024 WorkSource{10024 com.google.android.gms}
,03-15 20:40:19.468   924  1160 D PMS     : releaseWL(8251fa5): PARTIAL_WAKE_LOCK  Event Log Handoff 0x1 WorkSource{10024 com.google.android.gms},
,03-15 20:40:19.498  4386  6982 I EventLogService: Aggregate from 1458070578314 (log), 1458068981675 (data),
,03-15 20:40:19.548   924  1616 D PMS     : releaseWL(1089532b): PARTIAL_WAKE_LOCK  Event Log Service 0x1 WorkSource{10024 com.google.android.gms}
,03-15 20:40:24.388   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,03-15 20:40:34.388   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-15 20:40:49.398   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-15 20:40:54.608  1825  1825 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-15 20:40:54.658  1825  6215 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.android.vending, service: androidmarket
03-15 20:40:54.658  1825  6215 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> androidmarket without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-15 20:40:54.668  1825  6215 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 20:40:54.668  1825  6215 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-15 20:40:54.668  1825  6215 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService },
,03-15 20:40:54.758  1222  1222 I RemoteViews: reapply : com.google.android.gms 3 40
03-15 20:40:54.758  1326  1358 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
03-15 20:40:54.758  1825  6215 W GLSActivity: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-15 20:40:54.758  1825  6215 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-15 20:40:54.758  1825  6215 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-15 20:40:54.758  1825  6215 W GLSActivity: 	at com.google.android.gms.auth.be.r.getAuthToken(SourceFile:173)
03-15 20:40:54.758  1825  6215 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:196)
03-15 20:40:54.758  1825  6215 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
03-15 20:40:54.758  1825  6215 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:454)
03-15 20:40:54.758  1326  1358 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,03-15 20:40:54.768  6041  6080 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
03-15 20:40:54.768  6041  6080 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
03-15 20:40:54.768  6041  6080 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:1889)
03-15 20:40:54.768  6041  6080 E PlayEventLogger: 	at android.accounts.AccountManager.access$400(AccountManager.java:144)
03-15 20:40:54.768  6041  6080 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1732)
03-15 20:40:54.768  6041  6080 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
03-15 20:40:54.768  6041  6080 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:454)
,03-15 20:40:54.828  6041  6080 W System  : Ignoring header User-Agent because its value was null.
,03-15 20:40:54.838  6041  6080 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4,
03-15 20:40:54.838  6041  6080 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-15 20:40:54.838  6041  6080 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-15 20:40:54.838  6041  6080 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-15 20:40:54.838  6041  6080 D libc    : [NET] android_getaddrinfo_proxy+
03-15 20:40:54.838  6041  6080 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-15 20:40:54.838   398  6984 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
,03-15 20:40:54.838   398  6984 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-15 20:40:56.938   924  1140 D PMS     : acquireWL(185d0eb8): PARTIAL_WAKE_LOCK  *alarm* 0x1 924 1000 WorkSource{1000}
03-15 20:40:56.938   924  1140 V AlarmManager: sending alarm PendingIntent{2146bb0d: PendingIntentRecord{3129cac2 android broadcastIntent}}, i=android.content.syncmanager.SYNC_ALARM, t=2, cnt=1, w=376601, Int=0
03-15 20:40:56.938   924   924 D PMS     : acquireWL(146b8491): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 924 1000 null,
03-15 20:40:56.938   924  1026 D PMS     : acquireWL(d51cff6): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 924 1000 null
,03-15 20:40:56.938   924   924 D PMS     : releaseWL(185d0eb8): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,03-15 20:40:56.938   924  1026 D PMS     : releaseWL(146b8491): PARTIAL_WAKE_LOCK  SyncManagerHandleSyncAlarm 0x1 null,
,03-15 20:40:56.948   924  1026 D PMS     : releaseWL(d51cff6): PARTIAL_WAKE_LOCK  SyncLoopWakeLock 0x1 null
,03-15 20:40:59.848   398  6984 D libc    : [NET]Querying server xid =db32 (# 1) address = 192.168.1.1 (try=1,nscount=1,v_circuit=0),
03-15 20:40:59.848   398  6984 D libc    : before statp->options=0x800002C3)
,03-15 20:41:00.358   398  6984 D libc    : after statp->options=0x800002C1)
03-15 20:41:00.358   398  6984 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-15 20:41:00.358   398  6984 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,03-15 20:41:00.358  6041  6080 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-15 20:41:09.408   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-15 20:41:32.508   924  2342 D PMS     : acquireWL(2776aff7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 924 1000 null
03-15 20:41:32.508   924  2342 I BatteryService: n_update end
03-15 20:41:32.508   924  2342 D PMS     : releaseWL(2776aff7): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 20:41:32.508   924  1055 D HtcPowerSaver: updateBatteryInfo
03-15 20:41:32.518   924   924 D UsbnetService: BroadcastReceiver::onReceive+
03-15 20:41:32.518   924   924 D UsbnetService: onReceive BATTERY_CHANGED
03-15 20:41:32.518   924   924 D NotificationService: plugged=true pluggin=true
03-15 20:41:32.518   924   924 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 20:41:32.518   924   924 D PMS     : runPSCheck
,03-15 20:41:32.518   924   924 D UsbnetService: BroadcastReceiver::onReceive-
03-15 20:41:32.518   924   924 D HtcPowerSaver: Checking...
03-15 20:41:32.518   924  1152 D WifiController: handleMessage: E msg.what=155652
03-15 20:41:32.518   924   924 I HtcPowerSaver: >> updateStatus
03-15 20:41:32.518   924  1152 D WifiController: processMsg: DeviceActiveState
03-15 20:41:32.518   924  1152 D WifiController: battery changed pluggedType: 2
03-15 20:41:32.518   924  1152 D WifiController: processMsg: StaEnabledState
03-15 20:41:32.518  1222  1222 D PowerUI : closing low battery warning: level=100
03-15 20:41:32.518   924  1152 D WifiController: processMsg: DefaultState
03-15 20:41:32.518   924   924 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 20:41:32.518   924  1152 D WifiController: handleMessage: X
03-15 20:41:32.518   924   924 I HtcPowerSaver: << updateStatus
03-15 20:41:32.518  1222  1533 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 20:41:32.528  1222  1222 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 20:41:32.518  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:41:32.528  3018  3132 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 20:41:32.528  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:41:32.528  1326  1326 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,03-15 20:41:32.568  1222  1222 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-15 20:41:34.408   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,03-15 20:42:24.418   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,03-15 20:42:32.668   924  1609 D PMS     : acquireWL(7305e64): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 924 1000 null,
03-15 20:42:32.668   924  1609 I BatteryService: n_update end
,03-15 20:42:32.668   924  1609 D PMS     : releaseWL(7305e64): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-15 20:42:32.668   924  1055 D HtcPowerSaver: updateBatteryInfo
03-15 20:42:32.678   924   924 D UsbnetService: BroadcastReceiver::onReceive+
03-15 20:42:32.678   924   924 D UsbnetService: onReceive BATTERY_CHANGED
03-15 20:42:32.678   924   924 D NotificationService: plugged=true pluggin=true
03-15 20:42:32.678   924   924 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 20:42:32.678   924   924 D PMS     : runPSCheck
03-15 20:42:32.678   924   924 D UsbnetService: BroadcastReceiver::onReceive-
03-15 20:42:32.678   924   924 D HtcPowerSaver: Checking...
03-15 20:42:32.678   924   924 I HtcPowerSaver: >> updateStatus
,03-15 20:42:32.678   924   924 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 20:42:32.678   924  1152 D WifiController: handleMessage: E msg.what=155652
03-15 20:42:32.678   924   924 I HtcPowerSaver: << updateStatus
03-15 20:42:32.678   924  1152 D WifiController: processMsg: DeviceActiveState
03-15 20:42:32.678   924  1152 D WifiController: processMsg: StaEnabledState
,03-15 20:42:32.678   924  1152 D WifiController: processMsg: DefaultState
03-15 20:42:32.678   924  1152 D WifiController: battery changed pluggedType: 2
03-15 20:42:32.678   924  1152 D WifiController: handleMessage: X
,03-15 20:42:32.688  1222  1533 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false),
03-15 20:42:32.688  1222  1222 D PowerUI : closing low battery warning: level=100
03-15 20:42:32.688  3018  3132 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 20:42:32.688  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:42:32.688  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
,03-15 20:42:32.688  1326  1326 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 20:42:32.688  1222  1222 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,03-15 20:42:32.738  1222  1222 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-15 20:42:34.418   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,03-15 20:42:49.418   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-15 20:43:09.428   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,03-15 20:43:32.838   924  1616 D PMS     : acquireWL(31b2d8cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 924 1000 null
03-15 20:43:32.838   924  1616 I BatteryService: n_update end
03-15 20:43:32.838   924  1616 D PMS     : releaseWL(31b2d8cd): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 20:43:32.838  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:43:32.838   924  1055 D HtcPowerSaver: updateBatteryInfo
03-15 20:43:32.838  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3,
03-15 20:43:32.838  1222  1222 D PowerUI : closing low battery warning: level=100
03-15 20:43:32.838  1326  1326 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 20:43:32.838   924   924 D NotificationService: plugged=true pluggin=true
03-15 20:43:32.838  1222  1533 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 20:43:32.838   924   924 D PMS     : runPSCheck
03-15 20:43:32.838  3018  3132 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:43:32.838   924   924 D HtcPowerSaver: Checking...
03-15 20:43:32.838   924   924 D UsbnetService: BroadcastReceiver::onReceive+
03-15 20:43:32.838   924   924 I HtcPowerSaver: >> updateStatus
03-15 20:43:32.838   924   924 D UsbnetService: onReceive BATTERY_CHANGED
03-15 20:43:32.848   924  1152 D WifiController: battery changed pluggedType: 2
03-15 20:43:32.838   924   924 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 20:43:32.848  1222  1222 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 20:43:32.838   924   924 D UsbnetService: BroadcastReceiver::onReceive-
03-15 20:43:32.848   924  1152 D WifiController: handleMessage: E msg.what=155652
03-15 20:43:32.848   924   924 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 20:43:32.848   924  1152 D WifiController: processMsg: DeviceActiveState
03-15 20:43:32.848   924   924 I HtcPowerSaver: << updateStatus
03-15 20:43:32.848   924  1152 D WifiController: processMsg: StaEnabledState
03-15 20:43:32.848   924  1152 D WifiController: processMsg: DefaultState
,03-15 20:43:32.848   924  1152 D WifiController: handleMessage: X
,03-15 20:43:32.888  1222  1222 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-15 20:43:34.428   469   469 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,03-15 20:44:47.078   388   400 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,03-15 20:45:08.218  1543  1762 D ContactMessageStore: MSG_CHECK_DELETION >>
03-15 20:45:08.218  1543  1762 D ContactMessageStore: mDeleteTask = null, bDeleting = false
03-15 20:45:08.218  1543  1762 D AccFlag : sku_id=118
03-15 20:45:08.218  1543  1762 D ContactMessageStore: MSG_CHECK_DELETION <<
,03-15 20:45:08.218  1543  6986 D ContactMessageStore: start background delete task...
,03-15 20:45:08.228  1543  6986 D ContactMessageStore: size: 0 , 0
,03-15 20:45:08.228  1543  6986 D ContactMessageStore: Background delete complete
,03-15 20:45:33.158  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:45:33.158   924  1389 D PMS     : acquireWL(22c2f582): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 924 1000 null
03-15 20:45:33.158  1222  1533 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 20:45:33.158   924  1389 I BatteryService: n_update end
03-15 20:45:33.158  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:45:33.158   924  1389 D PMS     : releaseWL(22c2f582): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-15 20:45:33.158  1326  1326 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
03-15 20:45:33.158  1222  1222 D PowerUI : closing low battery warning: level=100
03-15 20:45:33.158  3018  3132 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 20:45:33.158   924  1055 D HtcPowerSaver: updateBatteryInfo
03-15 20:45:33.158   924   924 D UsbnetService: BroadcastReceiver::onReceive+
03-15 20:45:33.158  1222  1222 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 20:45:33.158   924   924 D UsbnetService: onReceive BATTERY_CHANGED
03-15 20:45:33.158   924   924 D NotificationService: plugged=true pluggin=true
03-15 20:45:33.158   924   924 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 20:45:33.158   924   924 D PMS     : runPSCheck
03-15 20:45:33.158   924   924 D UsbnetService: BroadcastReceiver::onReceive-
03-15 20:45:33.158   924   924 D HtcPowerSaver: Checking...
03-15 20:45:33.158   924   924 I HtcPowerSaver: >> updateStatus
03-15 20:45:33.168   924  1152 D WifiController: handleMessage: E msg.what=155652
03-15 20:45:33.168   924  1152 D WifiController: processMsg: DeviceActiveState
03-15 20:45:33.168   924  1152 D WifiController: battery changed pluggedType: 2
03-15 20:45:33.168   924  1152 D WifiController: processMsg: StaEnabledState
03-15 20:45:33.168   924  1152 D WifiController: processMsg: DefaultState
03-15 20:45:33.168   924  1152 D WifiController: handleMessage: X
,03-15 20:45:33.168   924   924 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 20:45:33.168   924   924 I HtcPowerSaver: << updateStatus
,03-15 20:45:33.208  1222  1222 I BatteryController: status:5 level:100 unsupport:false plugged:true
,03-15 20:47:33.478   924  1597 D PMS     : acquireWL(185c5493): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 924 1000 null
03-15 20:47:33.478   924  1597 I BatteryService: n_update end
03-15 20:47:33.478   924  1597 D PMS     : releaseWL(185c5493): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 20:47:33.478  1222  1533 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 20:47:33.478  1222  1222 D PowerUI : closing low battery warning: level=98
03-15 20:47:33.478   924  1055 D HtcPowerSaver: updateBatteryInfo
03-15 20:47:33.488  3018  3132 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 20:47:33.478  1222  1222 D PowerUI : plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 20:47:33.488  1326  1326 D DotMatrix: [EventService] reorderNotification, total:1
03-15 20:47:33.488  3018  3132 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=4
03-15 20:47:33.488   924   924 D NotificationService: plugged=true pluggin=true
03-15 20:47:33.488  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
03-15 20:47:33.488  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
03-15 20:47:33.488  1326  1326 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
03-15 20:47:33.488   924   924 D PMS     : runPSCheck
03-15 20:47:33.488  3018  3132 D HeadsetStateMachine: Disconnected process message: 11, size: 0
03-15 20:47:33.488   924   924 D HtcPowerSaver: Checking...
03-15 20:47:33.488   924   924 D UsbnetService: BroadcastReceiver::onReceive+
03-15 20:47:33.488   924   924 I HtcPowerSaver: >> updateStatus
03-15 20:47:33.488   924   924 D UsbnetService: onReceive BATTERY_CHANGED
03-15 20:47:33.488   924  1152 D WifiController: battery changed pluggedType: 2
03-15 20:47:33.488   924   924 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 20:47:33.488   924   924 D UsbnetService: BroadcastReceiver::onReceive-
03-15 20:47:33.488   924  1152 D WifiController: handleMessage: E msg.what=155652
03-15 20:47:33.488   924  1152 D WifiController: processMsg: DeviceActiveState
03-15 20:47:33.488   924  1152 D WifiController: processMsg: StaEnabledState
03-15 20:47:33.488   924  1152 D WifiController: processMsg: DefaultState
03-15 20:47:33.488   924  1152 D WifiController: handleMessage: X
,03-15 20:47:33.498   924   924 I HtcPowerSaver: updateStatus (8000,98,-1,false,false,false,-1)
03-15 20:47:33.498   924   924 I HtcPowerSaver: << updateStatus
,03-15 20:47:33.518  6422  6422 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse,
03-15 20:47:33.518  6422  6422 D         : Cust_ConnectToPC   : Internet_Sharing>true
03-15 20:47:33.518  6422  6422 D         : Cust_ConnectToPC   : Modem_Link>false
03-15 20:47:33.518  6422  6422 D         : Cust_ConnectToPC   : spcsc>false
03-15 20:47:33.518  6422  6422 D         : Cust_ConnectToPC   : IPT>true
03-15 20:47:33.518  6422  6422 D         : Cust_ConnectToPC   : Singel_USB>false
,03-15 20:47:33.518  6422  6422 D SmartNS_NSReceiver: project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
03-15 20:47:33.518  6422  6422 D SmartNS_NSReceiver: Index of the first 1 = -1
,03-15 20:47:33.528  1222  1222 I BatteryController: status:2 level:98 unsupport:false plugged:true
03-15 20:47:33.528  6422  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 
,03-15 20:47:33.538  6422  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
,03-15 20:47:33.538  6422  6422 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.,
03-15 20:47:33.538  6422  6422 E SmartNS_Utility: hasRemovableStorageSlot: true
03-15 20:47:33.538  6422  6422 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
03-15 20:47:33.538  6422  6422 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,03-15 20:47:33.558  6422  6422 D SmartNS_Utility: [ACC]android_networking:tethering_guard_support=false,
03-15 20:47:33.558  6422  6422 W SystemReader: Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,03-15 20:47:54.858   924  1597 D PMS     : acquireWL(7a134c9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 924 1000 null,
03-15 20:47:54.858   924  1597 I BatteryService: n_update end
03-15 20:47:54.858   924  1597 D PMS     : releaseWL(7a134c9): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
03-15 20:47:54.858   924  1055 D HtcPowerSaver: updateBatteryInfo
03-15 20:47:54.868   924   924 D UsbnetService: BroadcastReceiver::onReceive+
03-15 20:47:54.868   924   924 D UsbnetService: onReceive BATTERY_CHANGED
,03-15 20:47:54.868   924   924 D NotificationService: plugged=true pluggin=true
03-15 20:47:54.868   924   924 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 20:47:54.868   924   924 D PMS     : runPSCheck
03-15 20:47:54.868   924   924 D UsbnetService: BroadcastReceiver::onReceive-
03-15 20:47:54.868   924   924 D HtcPowerSaver: Checking...
03-15 20:47:54.868   924   924 I HtcPowerSaver: >> updateStatus
03-15 20:47:54.868  1222  1222 D PowerUI : closing low battery warning: level=98
03-15 20:47:54.868  1222  1533 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 20:47:54.868  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
03-15 20:47:54.868  1326  1326 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
03-15 20:47:54.868  1222  1222 D PowerUI : plugged = true, health = 2, mBatteryLevel = 98, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 20:47:54.868  3018  3132 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,03-15 20:47:54.868   924   924 I HtcPowerSaver: updateStatus (8000,98,-1,false,false,false,-1)
03-15 20:47:54.868   924   924 I HtcPowerSaver: << updateStatus
03-15 20:47:54.878   924  1152 D WifiController: handleMessage: E msg.what=155652
03-15 20:47:54.878   924  1152 D WifiController: processMsg: DeviceActiveState
03-15 20:47:54.878   924  1152 D WifiController: battery changed pluggedType: 2
03-15 20:47:54.878   924  1152 D WifiController: processMsg: StaEnabledState
03-15 20:47:54.878   924  1152 D WifiController: processMsg: DefaultState
03-15 20:47:54.878   924  1152 D WifiController: handleMessage: X
,03-15 20:47:54.918  1222  1222 I BatteryController: status:2 level:98 unsupport:false plugged:true,
,03-15 20:50:18.998  3018  3204 I bt-btm  : Received oneshot timer event complete
03-15 20:50:18.998   924  1140 D PMS     : acquireWL(3a2ee7ce): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 924 1000 WorkSource{1000}
03-15 20:50:18.998   924  1140 V AlarmManager: sending alarm PendingIntent{38a2eeee: PendingIntentRecord{3c406f8f android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=379655, Int=0
03-15 20:50:19.008  3018  3204 I bt-btm  : btm_ble_timeout
03-15 20:50:18.998   924  1140 V AlarmManager: sending alarm PendingIntent{27eda6ef: PendingIntentRecord{34e715fc com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=938663, Int=0
03-15 20:50:19.008  3018  3204 I bt-btm  : btm_gen_resolvable_private_addr
,03-15 20:50:19.008   924  1628 D PMS     : acquireWL(2bff5485): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 3018 1002 null
,03-15 20:50:19.018  3018  3204 D bt-btm  : btm_ble_rand_enc_complete,
,03-15 20:50:19.018  3018  3204 I bt-btm  : btm_gen_resolve_paddr_low
03-15 20:50:19.018  3018  3204 D bt-smp  : smp_encrypt_data
03-15 20:50:19.018   924   924 D PMS     : releaseWL(3a2ee7ce): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,03-15 20:50:19.018  3018  3204 W bt-smp  : Key(LSB ~ MSB) = c1 27 a2 17 c8 d1 ec 50 bf b8 af d2 f7 e3 e0 31 
,03-15 20:50:19.018  3018  3204 W bt-smp  : Plain text(LSB ~ MSB) = c7 4b 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
,03-15 20:50:19.018  3018  3204 W bt-smp  : Encrypted text(LSB ~ MSB) = 4f 4f d4 f2 57 74 11 e2 f1 47 5c 26 4c 3e 77 47 
03-15 20:50:19.018  3018  3204 I bt-btm  : btm_gen_resolve_paddr_cmpl
03-15 20:50:19.018  3018  3204 W bt-btm  : Stopping oneshot timer
03-15 20:50:19.018  3018  3204 D bt-btm  : Starting oneshot timer type:103 timeout:900s
03-15 20:50:19.028  1222  2483 D WeatherUtility: Weather sync is On
03-15 20:50:19.028  1222  2483 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-15 20:50:20.018   924   980 D PMS     : releaseWL(2bff5485): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null,
,03-15 20:50:47.488   924  1140 D PMS     : acquireWL(2b55b2da): PARTIAL_WAKE_LOCK  *alarm* 0x1 924 1000 WorkSource{10024}
03-15 20:50:47.488   924  1140 V AlarmManager: sending alarm PendingIntent{3e97c30b: PendingIntentRecord{98d95e8 com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=936506, Int=0
,03-15 20:50:47.518   924  1140 I ActivityManager: Start proc com.htc.cs.pns for service com.htc.cs.pns/com.htc.lib1.cs.push.service.UpdateRegistrationService: pid=6992 uid=10071 gids={50071, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-15 20:50:47.518   924  1140 V AlarmManager: sending alarm PendingIntent{e65b401: PendingIntentRecord{17ec22a6 com.htc.cs.pns startService}}, i=null, t=1, cnt=1, w=1458071258628, Int=0
03-15 20:50:47.518   924  1140 V AlarmManager: sending alarm PendingIntent{3398b6b0: PendingIntentRecord{3bcf9929 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=804375, Int=0
03-15 20:50:47.518   924  1140 V AlarmManager: sending alarm PendingIntent{147d84e7: PendingIntentRecord{e028c7b com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1458071447498, Int=0,
,03-15 20:50:47.528   924   981 D PMS     : acquireWL(299a2894): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 1825 10024 WorkSource{10024 com.google.android.gms},
,03-15 20:50:47.528   924  1597 D PMS     : releaseWL(299a2894): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 WorkSource{10024 com.google.android.gms}
,03-15 20:50:47.538   924  1628 D PMS     : acquireWL(25788f3d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,03-15 20:50:47.548  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:13 android.app.ActivityThread.handleReceiver:2712 
,03-15 20:50:47.548   924   924 D PMS     : releaseWL(2b55b2da): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000},
,03-15 20:50:47.558  6815  7010 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,03-15 20:50:47.578  6815  7010 D PowerUsageService: repeat time = 1458072347583
,03-15 20:50:47.618   924  2342 D PMS     : acquireWL(1f3b3a00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms},
,03-15 20:50:47.628   924   981 D PMS     : releaseWL(25788f3d): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-15 20:50:47.638   924  1046 D StatusBarManagerService: setSystemUiVisibility(0x8700)
03-15 20:50:47.638   924  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 20:50:47.648  1825  7014 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
03-15 20:50:47.638   924  1046 D StatusBarManagerService: hiding MENU key
03-15 20:50:47.638   924  1046 D StatusBarManagerService: setSystemUiVisibility(0xc0000700)
03-15 20:50:47.638   924  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 20:50:47.638   924  1046 D StatusBarManagerService: hiding MENU key
03-15 20:50:47.648  1595  1595 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,03-15 20:50:47.658  1595  1595 I ThreadedRenderer: Defer allocateBuffers to drawing time,
,03-15 20:50:47.658   924  1599 I InputMethodManagerService: Disable input method client, pid=6922
,03-15 20:50:47.658   924  1599 D StatusBarManagerService: swetImeWindowStatus vis=0 backDisposition=0
,03-15 20:50:47.658  6922  6922 W IInputConnectionWrapper: Do restartInputUnchecked, ic=null
03-15 20:50:47.658  6922  6922 I InputMethodManager: com.test.thalitest called restartInputUnchecked(msg=100) from com.android.internal.view.IInputConnectionWrapper.executeMessage(IInputConnectionWrapper.java:213)
03-15 20:50:47.658  6922  6922 W IInputConnectionWrapper: reportFullscreenMode on inactive InputConnection
,03-15 20:50:47.668  1825  7014 W Uploader: No account for auth token provided,
,03-15 20:50:47.668  1222  1222 I PhoneStatusBar: setImeWindowStatus(false,false)
,03-15 20:50:47.678  6815  7010 I PowerUsageList:PowerUsageHelper: PowerProfile::POWER_SCREEN_FULL = 154.8
,03-15 20:50:47.678  1825  7014 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-15 20:50:47.678  1825  7014 D libc    : [NET] android_getaddrinfofornet-, err=8
03-15 20:50:47.678  1825  7014 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-15 20:50:47.678  1825  7014 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
03-15 20:50:47.678  1825  7014 D libc    : [NET] android_getaddrinfo_proxy+
03-15 20:50:47.678  1825  7014 D libc    : [NET] android_getaddrinfo_proxy get netid:0
03-15 20:50:47.678   398  7017 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 1024
03-15 20:50:47.678   398  7017 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,03-15 20:50:47.688  6815  7010 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,03-15 20:50:47.698  6815  7010 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
03-15 20:50:47.698  6815  7010 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,03-15 20:50:47.708  7018  7018 E cutils-trace: Error opening trace file: Permission denied (13)
03-15 20:50:47.708  7018  7018 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.htc.cs.pns/app_push_lib/plugin-deploy.jar --oat-fd=22 --oat-location=/data/data/com.htc.cs.pns/app_push_dex/plugin-deploy.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
03-15 20:50:47.708  7018  7018 I dex2oat : dex2oat: override thread count:4
,03-15 20:50:47.718  6815  7010 D PowerUsageService: calcPower(), no data
,03-15 20:50:47.718  1825  2900 D GCM     : Message class com.google.f.a.a.i
03-15 20:50:47.718   924  1609 D PMS     : acquireWL(211768f5): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:50:47.718   924   980 D PMS     : releaseWL(211768f5): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 WorkSource{10024 com.google.android.gms}
,03-15 20:50:47.758   398  7017 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
03-15 20:50:47.758   398  7017 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
03-15 20:50:47.758  1825  7014 D libc    : [NET] android_getaddrinfo_proxy-, success
,03-15 20:50:48.128  1825  7014 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-15 20:50:48.128  1825  7014 D libc    : [NET] android_getaddrinfofornet-, err=8
03-15 20:50:48.138  1825  7014 D libc    : [NET] android_getaddrinfofornet+,hn 19(0x706c61792e676f),sn(),hints(known),family 0,flags 4
03-15 20:50:48.138  1825  7014 D libc    : [NET] android_getaddrinfofornet-, err=8
,03-15 20:50:48.308  1825  7014 W Uploader: No account for auth token provided
,03-15 20:50:48.468  1825  7014 W Uploader: No account for auth token provided
,03-15 20:50:48.498  7018  7018 I dex2oat : dex2oat took 793.238ms (threads: 4)
,03-15 20:50:48.538  6992  6992 I PushClient: ApplicationMonitor {22f0479a}: logBasicAppInfo(): PackageName:             com.htc.cs.pns
,03-15 20:50:48.548  6992  6992 I PushClient: ApplicationMonitor {22f0479a}: logBasicAppInfo(): ProcessName:             com.htc.cs.pns,
03-15 20:50:48.548  6992  6992 I PushClient: ApplicationMonitor {22f0479a}: logBasicAppInfo(): VersionName:             1.2.853019
03-15 20:50:48.548  6992  6992 I PushClient: ApplicationMonitor {22f0479a}: logBasicAppInfo(): VersionCode:             148001224
,03-15 20:50:48.548  6992  6992 I PushClient: ApplicationMonitor {22f0479a}: logBasicAppInfo(): ApplicationPath:         /system/priv-app/PNSClient/PNSClient.apk
,03-15 20:50:48.548  6992  6992 I PushClient: ApplicationMonitor {22f0479a}: logBasicAppInfo(): AppFileDataPath:         /data/data/com.htc.cs.pns/files
03-15 20:50:48.548  6992  6992 I PushClient: ApplicationMonitor {22f0479a}: logBasicAppInfo(): Htc_SECURITY_DEBUG_flag: false
,03-15 20:50:48.548  6992  6992 I PushClient: ApplicationMonitor {22f0479a}: logBasicAppInfo(): Htc_DEBUG_flag:          false,
03-15 20:50:48.548  6992  6992 I PushClient: ApplicationMonitor {22f0479a}: logBasicAppInfo(): BuildConfig.DEBUG:       false
,03-15 20:50:48.558  6992  7023 I PushClient: PnsModel {1484445}: update(): Update registration caused by: alarm
,03-15 20:50:48.588  1825  7014 W Uploader:  no longer exists, so no auth token.
,03-15 20:50:48.588  6992  7023 I PushClient: PnsConfigModel {289354c0}: <init>(): Use dm-client for provisioning.
,03-15 20:50:48.618  6992  7023 W System.err: SLF4J: Failed to load class "org.slf4j.impl.StaticLoggerBinder".
,03-15 20:50:48.618  6992  7023 W System.err: SLF4J: Defaulting to no-operation (NOP) logger implementation
,03-15 20:50:48.618  6992  7023 W System.err: SLF4J: See http://www.slf4j.org/codes.html#StaticLoggerBinder for further details.
,03-15 20:50:48.648  6992  7023 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.htc.cs.dm.intent.action.BIND_CORE_SERVICE } android.content.ContextWrapper.bindService:538 com.htc.cs.util.service.BoundServiceTask.bind:134 com.htc.cs.dm.config.ConfigManager.getConfig:408 
,03-15 20:50:48.678   924  1626 I ActivityManager: Start proc com.htc.cs.dm for service com.htc.cs.dm/.config.service.ConfigManagerBoundService: pid=7025 uid=10099 gids={50099, 9997, 3003} abi=arm64-v8a
,03-15 20:50:48.708  1825  7014 W Uploader: No account for auth token provided
,03-15 20:50:48.788  7025  7025 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;2.2.848686;250001208] pid=7025 dbg=false s=true
,03-15 20:50:48.808  7025  7045 I DeviceManagement: ConfigManagerBoundService: *** getConfig: appID=com.htc.cs.pns options=Bundle[EMPTY_PARCEL]
03-15 20:50:48.808  7025  7045 I DeviceManagement: ConfigManagerBoundService: Caller: uid=com.htc.cs.pns (10071) packages=[com.htc.cs.pns]
,03-15 20:50:48.818  7025  7047 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow] args=[Bundle[{options=Bundle[EMPTY_PARCEL], appID=com.htc.cs.pns}]]
03-15 20:50:48.818  1825  7014 W Uploader: No account for auth token provided
,03-15 20:50:48.828  7025  7025 I DeviceManagement: WorkflowService: Starting workflow service
,03-15 20:50:48.838  7025  7048 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1082ecbc] args=[Bundle[mParcelledData.dataSize=88]]
,03-15 20:50:48.838  7025  7048 I DeviceManagement: ConfigManagerServiceWorkflow: *** Invoke: com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow, args=Bundle[mParcelledData.dataSize=88]
,03-15 20:50:48.848  7025  7048 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,03-15 20:50:48.898  7025  7048 I DeviceManagement: ConfigManagerController: *** getConfig: appID=com.htc.cs.pns includeMeta=false
,03-15 20:50:48.908  7025  7049 I DeviceManagement: SessionStateController: Checking invariants...
,03-15 20:50:48.968  1825  7014 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-30791>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cclog,
03-15 20:50:48.968  1825  7014 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-30791> oauth2:https://www.googleapis.com/auth/cclog without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-15 20:50:48.968  1825  7014 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 20:50:48.968  1825  7014 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-15 20:50:48.978  1825  7014 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:50:48.998  1825  7014 E Uploader: Failed to get auth token: User intervention required. Notification has been pushed.,
03-15 20:50:48.998  1825  7014 E Uploader: com.google.android.gms.auth.ae: User intervention required. Notification has been pushed.
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.auth.p.e(SourceFile:1268)
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.auth.p.d(SourceFile:599)
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.auth.p.c(SourceFile:550)
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.auth.p.b(SourceFile:477)
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:508)
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:337)
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:263)
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.playlog.uploader.e.a(SourceFile:235)
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.b(SourceFile:125)
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.playlog.uploader.UploaderService.a(SourceFile:78)
03-15 20:50:48.998  1825  7014 E Uploader: 	at com.google.android.gms.gcm.am.run(SourceFile:135)
,03-15 20:50:49.008  1326  1388 D DotMatrix: [NotificationService] onNotificationPosted, pkgName: com.google.android.gms, id: 1, tag: null, isClearable: true
03-15 20:50:49.008  1326  1388 D DotMatrix: [EventService] get3rdNotificationByPkgName, com.google.android.gms does not support DotMatrix
,03-15 20:50:49.008  1222  1222 I RemoteViews: reapply : com.google.android.gms 2 40
,03-15 20:50:49.068  7025  7049 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.dm includeMeta=true,
,03-15 20:50:49.118  1825  7014 W Uploader: No account for auth token provided,
,03-15 20:50:49.128  7025  7048 I DeviceManagement: SessionStateController: Checking invariants...,
,03-15 20:50:49.228  7025  7048 I DeviceManagement: ConfigManagerController: Retrieving config content from cache: appID=com.htc.cs.pns includeMeta=false
,03-15 20:50:49.238   924  1389 D PMS     : releaseWL(1f3b3a00): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-15 20:50:49.238  7025  7048 I DeviceManagement: WorkflowService: Workflow complete: workflow=[com.htc.cs.dm.config.service.ConfigManagerServiceGetConfigWorkflow@1082ecbc]
03-15 20:50:49.248  7025  7025 I DeviceManagement: WorkflowService: Stopping workflow service
03-15 20:50:49.248   924  1160 D PMS     : acquireWL(b1ec06): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
03-15 20:50:49.248   924  1389 I ActivityManager: Killing 6644:com.google.android.gms.unstable/u0a24 (adj 15): empty #17
03-15 20:50:49.248   924  1389 D Process : killProcessQuiet, pid=6644
,03-15 20:50:49.258   924  1389 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-15 20:50:49.278   924  1160 D PMS     : releaseWL(b1ec06): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms},
,03-15 20:50:49.278   924  1597 D PMS     : acquireWL(144f82c7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 1825 10024 WorkSource{10024 com.google.android.gms}
,03-15 20:50:49.338   924  1609 I ActivityManager: Recipient 6644
,03-15 20:50:49.368   924  2342 D PMS     : releaseWL(144f82c7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10024 com.google.android.gms}
,03-15 20:50:49.388  6992  7023 I PushClient: PnsModel {1484445}: update(): The registration record has not expired yet. No need to update.
,03-15 20:50:49.398   924  1628 I ActivityManager: Killing 6715:com.htc.mms.backupagent/u0a76 (adj 15): empty #17
,03-15 20:50:49.398   924  1628 D Process : killProcessQuiet, pid=6715
,03-15 20:50:49.398   924  1628 D Process : com.android.server.am.ProcessRecord.kill:573 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18857 com.android.server.am.ActivityManagerService.updateOomAdjLocked:18700 
,03-15 20:50:49.538   924  1609 I ActivityManager: Recipient 6715
,03-15 20:50:55.228   924  1597 D PMS     : acquireWL(c9d80f4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 924 1000 null,
03-15 20:50:55.228   924  1597 I BatteryService: n_update end
03-15 20:50:55.238   924  1597 D PMS     : releaseWL(c9d80f4): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 20:50:55.238   924   924 D UsbnetService: BroadcastReceiver::onReceive+
03-15 20:50:55.238   924   924 D NotificationService: plugged=true pluggin=true
03-15 20:50:55.238   924   924 D UsbnetService: onReceive BATTERY_CHANGED
03-15 20:50:55.238  1222  1533 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 20:50:55.238   924   924 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 20:50:55.238   924   924 D UsbnetService: BroadcastReceiver::onReceive-
03-15 20:50:55.238   924  1152 D WifiController: handleMessage: E msg.what=155652
03-15 20:50:55.238  3018  3132 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 20:50:55.238  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 30, version:1.3
03-15 20:50:55.238  1326  1326 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
03-15 20:50:55.238   924  1152 D WifiController: processMsg: DeviceActiveState
03-15 20:50:55.238   924  1152 D WifiController: processMsg: StaEnabledState
03-15 20:50:55.238   924  1152 D WifiController: processMsg: DefaultState
03-15 20:50:55.238   924  1152 D WifiController: battery changed pluggedType: 2
03-15 20:50:55.238   924  1152 D WifiController: handleMessage: X
03-15 20:50:55.238  1222  1222 D PowerUI : closing low battery warning: level=99
03-15 20:50:55.238   924  1055 D HtcPowerSaver: updateBatteryInfo
03-15 20:50:55.248   924   924 D PMS     : runPSCheck
03-15 20:50:55.248   924   924 D HtcPowerSaver: Checking...
03-15 20:50:55.248   924   924 I HtcPowerSaver: >> updateStatus
,03-15 20:50:55.248  1222  1222 D PowerUI : plugged = true, health = 2, mBatteryLevel = 99, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,03-15 20:50:55.248   924   924 I HtcPowerSaver: updateStatus (8000,99,-1,false,false,false,-1)
,03-15 20:50:55.248   924   924 I HtcPowerSaver: << updateStatus
,03-15 20:50:55.288  1222  1222 I BatteryController: status:2 level:99 unsupport:false plugged:true,
,03-15 20:51:31.858   924  1140 D PMS     : acquireWL(d12701d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 924 1000 WorkSource{1000}
,03-15 20:51:31.858   924  1140 V AlarmManager: sending alarm PendingIntent{38a2eeee: PendingIntentRecord{3c406f8f android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=979655, Int=0
03-15 20:51:31.858   924  1140 V AlarmManager: sending alarm PendingIntent{270c292: PendingIntentRecord{34378463 com.htc.htcpowermanager broadcastIntent}}, i=SMARTSYNC_SERVICE_BROADCAST_SCREEN_OFF_TIME, t=0, cnt=1, w=1458071491869, Int=0
,03-15 20:51:31.868  6815  6815 D SmartSyncUtils: isEpsOn(), nState = 0
,03-15 20:51:31.878   924  1627 D PMS     : acquireWL(2d8bb860): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 6815 1000 null
,03-15 20:51:31.878  6815  7053 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] bManual = false,
03-15 20:51:31.878  6815  7053 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
03-15 20:51:31.888   924   924 D PMS     : releaseWL(d12701d): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,03-15 20:51:31.888  6815  7053 D SmartSyncScreenOnOffTimeReceiver: AlarmOnTime = -1
,03-15 20:51:31.888  6815  7053 D SmartSyncScreenOnOffTimeReceiver: SettingOnTime = 1458108000000, randomSettingOnTime = 1458105476000
03-15 20:51:31.888  6815  7053 D SmartSyncScreenOnOffTimeReceiver: SettingOffTime = 1458086400000, randomSettingOffTime = 1458093414000
03-15 20:51:31.888  1222  2483 D WeatherUtility: Weather sync is On
03-15 20:51:31.888  1222  2483 W WeatherTimeKeeper: [refreshWeatherData] no weather data
03-15 20:51:31.888  6815  7053 D SmartSyncScreenOnOffTimeReceiver: bDayMode = false
,03-15 20:51:31.888  6815  7053 D SmartSyncScreenOnOffTimeReceiver: bNightMode = true
03-15 20:51:31.898  6815  7053 D SmartSyncScreenOnOffTimeReceiver: bNightModeTurnOffOnce = false,
,03-15 20:51:31.898   924  1616 D PMS     : releaseWL(2d8bb860): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,03-15 20:53:53.738   924  1140 D PMS     : acquireWL(30eaf119): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 924 1000 WorkSource{1000}
03-15 20:53:53.738   924  1140 V AlarmManager: sending alarm PendingIntent{38a2eeee: PendingIntentRecord{3c406f8f android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=1039655, Int=0
03-15 20:53:53.738   924  1140 V AlarmManager: sending alarm PendingIntent{3bd475de: PendingIntentRecord{3d1403bf android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=1153403, Int=0
,03-15 20:53:53.738   924  1644 D HtcSystemUPManager: UPAlarmListener onAlarmArrival
03-15 20:53:53.748   924  1644 D HtcSystemUPManager: UPAlarmListener [SYSTEM_UP_FLUSH] cur = 1458071633755, last = 1458050033745, freq = 21600000
,03-15 20:53:53.748   924  1646 D HtcSystemUPManager: AlarmScheduler_INEXACT [onReceive] end
03-15 20:53:53.748   924  1646 D HtcSystemUPManager: com.htc.upm.AlarmScheduler$SchedulerBase$1@8e42adb
,03-15 20:53:53.758   924   924 D PMS     : releaseWL(30eaf119): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000},
,03-15 20:53:53.768  1222  2483 D WeatherUtility: Weather sync is On
,03-15 20:53:53.768  1222  2483 W WeatherTimeKeeper: [refreshWeatherData] no weather data
,03-15 20:53:53.778   924  1644 D HtcSystemUPManager: HtcSystemUPHandler sendService() has been called
03-15 20:53:53.778   924  1644 D HtcSystemUPManager: HtcSystemUPDataStore [sendToService] No data needs to be sent to service
03-15 20:53:53.778   924  1644 D HtcSystemUPManager: HtcSystemUPHandler send to UPService takes: 2 ms
,03-15 20:53:55.708   924  1628 D PMS     : acquireWL(3f63fa8c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 924 1000 null
,03-15 20:53:55.708   924  1628 I BatteryService: n_update end
03-15 20:53:55.708   924  1628 D PMS     : releaseWL(3f63fa8c): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 20:53:55.718  1326  1326 D DotMatrix: [EventService] reorderNotification, total:0
03-15 20:53:55.718  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:53:55.718   924  1055 D HtcPowerSaver: updateBatteryInfo
03-15 20:53:55.718  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:53:55.718  1326  1326 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:true, mCoverOn:false
03-15 20:53:55.718  1222  1533 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 20:53:55.718  3018  3132 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 20:53:55.718  1222  1222 D PowerUI : closing low battery warning: level=100
03-15 20:53:55.718  3018  3132 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
03-15 20:53:55.718   924   924 D NotificationService: plugged=true pluggin=true
03-15 20:53:55.718  3018  3132 D HeadsetStateMachine: Disconnected process message: 11, size: 0
03-15 20:53:55.718  1222  1222 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 20:53:55.718   924   924 D UsbnetService: BroadcastReceiver::onReceive+
03-15 20:53:55.718   924   924 D PMS     : runPSCheck
03-15 20:53:55.718   924   924 D UsbnetService: onReceive BATTERY_CHANGED
03-15 20:53:55.728   924  1152 D WifiController: battery changed pluggedType: 2
03-15 20:53:55.718   924   924 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 20:53:55.728   924   924 D HtcPowerSaver: Checking...
03-15 20:53:55.718   924   924 D UsbnetService: BroadcastReceiver::onReceive-
03-15 20:53:55.728   924   924 I HtcPowerSaver: >> updateStatus
03-15 20:53:55.718   924  1152 D WifiController: handleMessage: E msg.what=155652
03-15 20:53:55.728  6815  6815 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1824 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.htc.htcpowermanager.extremepowersaver.ExtremePowerSaverReceiver.onReceive:67 android.app.ActivityThread.handleReceiver:2712 
03-15 20:53:55.728   924  1152 D WifiController: processMsg: DeviceActiveState
03-15 20:53:55.728   924  1152 D WifiController: processMsg: StaEnabledState
03-15 20:53:55.728   924  1152 D WifiController: processMsg: DefaultState
03-15 20:53:55.728   924  1152 D WifiController: handleMessage: X
03-15 20:53:55.728   924   924 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,03-15 20:53:55.728   924   924 I HtcPowerSaver: << updateStatus
,03-15 20:53:55.738  6422  6422 D TetherSettings: CustomizedNS:true CustomizedML:false CustomizedSPCSC:false CustomizedIPT:true CustomizedSingleUSBfalse
03-15 20:53:55.738  6422  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1830 android.content.ContextWrapper.stopService:520 android.content.ContextWrapper.stopService:520 com.android.settings.NSReceiver.onReceive:192 android.app.ActivityThread.handleReceiver:2712 ,
03-15 20:53:55.738  6422  6422 D         : Cust_ConnectToPC   : Internet_Sharing>true
03-15 20:53:55.738  6422  6422 D         : Cust_ConnectToPC   : Modem_Link>false
03-15 20:53:55.738  6422  6422 D         : Cust_ConnectToPC   : spcsc>false
03-15 20:53:55.738  6422  6422 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1459 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.android.settings.NSReceiver.onReceive:194 android.app.ActivityThread.handleReceiver:2712 
03-15 20:53:55.738  6422  6422 D         : Cust_ConnectToPC   : IPT>true
03-15 20:53:55.738  6422  6422 D         : Cust_ConnectToPC   : Singel_USB>false
,03-15 20:53:55.738  6422  6422 D SmartNS_NSReceiver: project = Verizon, plugged = 2, support_extension = 0, unsupport_charger = false overheat:false
03-15 20:53:55.738  6422  6422 D SmartNS_NSReceiver: Index of the first 1 = -1
03-15 20:53:55.748  6422  6422 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
03-15 20:53:55.748  6422  6422 E SmartNS_Utility: hasRemovableStorageSlot: true
03-15 20:53:55.748  6422  6422 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
,03-15 20:53:55.748  6422  6422 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,03-15 20:53:55.768  1222  1222 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-15 20:54:47.078   388   400 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory)
,03-15 20:54:55.878   924  2342 D PMS     : acquireWL(1d2e11ea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 924 1000 null
03-15 20:54:55.878   924  2342 I BatteryService: n_update end
03-15 20:54:55.878   924  2342 D PMS     : releaseWL(1d2e11ea): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,03-15 20:54:55.878   924   924 D UsbnetService: BroadcastReceiver::onReceive+
03-15 20:54:55.878   924   924 D NotificationService: plugged=true pluggin=true
03-15 20:54:55.878   924   924 D UsbnetService: onReceive BATTERY_CHANGED
03-15 20:54:55.878   924  1152 D WifiController: battery changed pluggedType: 2
03-15 20:54:55.878   924   924 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
03-15 20:54:55.878   924  1055 D HtcPowerSaver: updateBatteryInfo,
03-15 20:54:55.878   924   924 D UsbnetService: BroadcastReceiver::onReceive-
03-15 20:54:55.878   924   924 D PMS     : runPSCheck
03-15 20:54:55.878   924  1152 D WifiController: handleMessage: E msg.what=155652
03-15 20:54:55.878   924   924 D HtcPowerSaver: Checking...
03-15 20:54:55.878   924  1152 D WifiController: processMsg: DeviceActiveState
03-15 20:54:55.878   924   924 I HtcPowerSaver: >> updateStatus
03-15 20:54:55.878   924  1152 D WifiController: processMsg: StaEnabledState
03-15 20:54:55.878  1222  1222 D PowerUI : closing low battery warning: level=100
03-15 20:54:55.878   924  1152 D WifiController: processMsg: DefaultState
03-15 20:54:55.878   924  1152 D WifiController: handleMessage: X
03-15 20:54:55.888  1222  1533 I IntentController: receive(android.intent.action.BATTERY_CHANGED,1,false)
03-15 20:54:55.888  3018  3132 D HeadsetStateMachine: Disconnected process message: 10, size: 0
03-15 20:54:55.888  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:54:55.888  1326  1326 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:1.3
03-15 20:54:55.888  1222  1222 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
03-15 20:54:55.888  1326  1326 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false
,03-15 20:54:55.888   924   924 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
03-15 20:54:55.888   924   924 I HtcPowerSaver: << updateStatus
,03-15 20:54:55.938  1222  1222 I BatteryController: status:5 level:100 unsupport:false plugged:true,
,03-15 20:55:02.758   924  1026 I UsageStatsService: User[0] Flushing usage stats to disk
,TIME-OUT KILL (timeout was 1400000ms)
```
