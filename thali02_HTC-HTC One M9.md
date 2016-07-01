#### Test 757892680c366d1_thali02_HTC-HTC One M9 Logs


```
--------- beginning of system
07-01 12:08:25.214  1131  3479 D PMS     : releaseWL(1b4f9b80): PARTIAL_WAKE_LOCK  Icing 0x1 null
07-01 12:08:25.214  1131  3558 D PMS     : acquireWL(265dc0a): PARTIAL_WAKE_LOCK  Icing 0x1 3409 10019 null
--------- beginning of main
07-01 12:08:25.224  6415  8087 I ApplicationLogger: canRun() : Opted Out
07-01 12:08:25.224  6415  8087 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 307 ms] updated apps [took 307 ms] 
07-01 12:08:25.234  1131  3408 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
07-01 12:08:25.234  1131  4558 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
07-01 12:08:25.264  8110  8110 D DocsApplication: Plugin installer initialized.
07-01 12:08:25.264  1131  3502 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
07-01 12:08:25.284  8110  8110 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{b1aab0c com.google.android.apps.docs}
,07-01 12:08:25.294  8110  8110 D TAG     : onCreate()
07-01 12:08:25.304  8110  8110 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-01 12:08:25.314  1131  3504 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
07-01 12:08:25.464  8137  8137 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-01 12:08:25.464  8137  8137 W HTCLOG  : mask=0x18
07-01 12:08:25.494  1131  3019 D PMS     : acquireWL(825ec7b): PARTIAL_WAKE_LOCK  *alarm* 0x1 1131 1000 WorkSource{10027}
07-01 12:08:25.494  1131  3019 V AlarmManager: sending alarm PendingIntent{28555a98: PendingIntentRecord{2352d83e com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=86866, Int=0
07-01 12:08:25.614  8137  8140 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-01 12:08:25.614  8137  8140 W HTCLOG  : mask=0x18
07-01 12:08:25.614  8137  8140 E cutils-trace: Error opening trace file: Permission denied (13)
07-01 12:08:25.664  8137  8137 D CustomizationManager: ====startRecUseTime====
07-01 12:08:25.664  8137  8137 D htc.customization.log.level:  is 
07-01 12:08:25.664  8137  8137 W CustomizationLogLevel: Level value is invalid, use default level 2
07-01 12:08:25.714  3517  3894 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-01 12:08:25.714  3517  3894 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@59450e8 +
07-01 12:08:25.714  3517  3894 I Prism.WidgetManager: onLoadItems() +
07-01 12:08:25.744  3517  3894 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-01 12:08:25.754  8137  8137 D CustomizationManager:  Read ACC file spent 0.039 (s)
07-01 12:08:25.754  8137  8137 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
07-01 12:08:25.754  8137  8137 I CustomizationCIDLoader: Parsing tag category name = application
07-01 12:08:25.754  8137  8137 I CustomizationCIDLoader: Parsing tag category name = system
07-01 12:08:25.754  8137  8137 I CustomizationCIDLoader: Parsing tag category name = Settings
07-01 12:08:25.754  8137  8137 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-01 12:08:25.754  8137  8137 I CustomizationCIDLoader: Parsing tag category name = ACC
07-01 12:08:25.754  8137  8137 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
07-01 12:08:25.754  8137  8137 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
07-01 12:08:25.754  8137  8137 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
07-01 12:08:25.754  8137  8137 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-01 12:08:25.754  8137  8137 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-01 12:08:25.754  8137  8137 D CustomizationManager:  Read CID file spent 0.089 (s)
07-01 12:08:25.754  8137  8137 D CustomizationManager:  All configurations done spent 0.089 (s)
07-01 12:08:25.794  1131  4065 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8137 on display 0
07-01 12:08:25.794  1131  1178 D PMS     : acquireHCC(178212f1): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1131 1000 null
07-01 12:08:25.794  1131  1178 D PMS     : acquireHCC(3b8daed6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1131 1000 null
07-01 12:08:25.804  1131  4065 V WindowManager: addAppToken: AppWindowToken{2d13ed2d token=Token{b918844 ActivityRecord{161cd557 u0 com.test.thalitest/.MainActivity t45}}} to stack=1 task=45 at 0
07-01 12:08:25.824  1131  4065 I ActivityManager: Start proc 8154:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
07-01 12:08:25.824  8137  8137 W HTCLOG  : use specified tag [IPCThreadState], func [0].
07-01 12:08:25.824  8137  8137 W HTCLOG  : mask=0x18
07-01 12:08:25.824  8137  8152 W HTCLOG  : use specified tag [Vector], func [0].
07-01 12:08:25.824  8137  8152 W HTCLOG  : mask=0x18
07-01 12:08:25.834  8154  8154 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:08:25.834  8154  8154 W HTCLOG  : mask=0x18
07-01 12:08:25.844  3485  4078 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-01 12:08:25.844  3485  4078 D PhoneApp: -- N1 =0
07-01 12:08:25.844  3485  4078 D PhoneApp: -- N2 =0
07-01 12:08:25.844  3485  4078 D PhoneApp: -- N3 =0
07-01 12:08:25.854  1131  1131 V ActivityManager: Display changed displayId=0
07-01 12:08:25.854  3275  3275 D DotMatrix: [EventService]  onDisplayChanged: 0
07-01 12:08:25.854  3275  3275 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
07-01 12:08:25.854  1131  3502 D ActivityManager: screenshot for ActivityRecord{161cd557 u0 com.test.thalitest/.MainActivity t45}, bitmap=null, time = 0
07-01 12:08:25.874  3517  3517 I TrimMemoryManager: [trimMemory] 20
07-01 12:08:25.904  8154  8154 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
07-01 12:08:25.904  3517  3894 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 12:08:25.954  8154  8154 I LibraryLoader: Time to load native libraries: 29 ms (timestamps 9299-9328)
07-01 12:08:25.954  8154  8154 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:08:25.964  8154  8154 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {384d6bf8}
07-01 12:08:25.964  8154  8154 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 12:08:25.974  8154  8154 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 12:08:25.974  8154  8154 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 12:08:25.984  8154  8154 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:25.984  8154  8154 E SysUtils: ApplicationContext is null in ApplicationStatus
07-01 12:08:26.014  8154  8177 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
07-01 12:08:26.014  8154  8181 D BluetoothAdapter: 162314449: getState() :  mService = null. Returning STATE_OFF
07-01 12:08:26.024  8154  8154 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-01 12:08:26.024  8154  8154 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
07-01 12:08:26.024  8154  8154 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
,07-01 12:08:26.034  3517  3894 I Prism.WidgetManager: onLoadItems() -
07-01 12:08:26.034  3517  3894 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@59450e8 -
07-01 12:08:26.034  8154  8154 W HTCLOG  : use specified tag [libEGL], func [3].
07-01 12:08:26.034  8154  8154 W HTCLOG  : mask=0x18
07-01 12:08:26.034  8154  8154 W HTCLOG  : use specified tag [libEGL], func [3].
07-01 12:08:26.034  8154  8154 W HTCLOG  : mask=0x18
07-01 12:08:26.034  8154  8154 I Adreno  : QUALCOMM build                   : 065751b, 
07-01 12:08:26.034  8154  8154 I Adreno  : Build Date                       : 04/15/15
07-01 12:08:26.034  8154  8154 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
07-01 12:08:26.034  8154  8154 I Adreno  : Local Branch                     : 
07-01 12:08:26.034  8154  8154 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
07-01 12:08:26.034  8154  8154 I Adreno  : Remote Branch                    : NONE
07-01 12:08:26.034  8154  8154 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
07-01 12:08:26.104  8154  8187 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
07-01 12:08:26.114  8154  8154 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:26.124  8154  8154 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-01 12:08:26.134  8154  8154 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
07-01 12:08:26.134  8154  8154 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:26.134  8154  8154 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 12:08:26.164  8154  8198 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:08:26.164  8154  8198 W HTCLOG  : mask=0x18
07-01 12:08:26.164  1131  1150 V WindowManager: Adding window Window{b3b8155 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{3e66f279 u0 com.htc.launcher/com.htc.launcher.Launcher})
07-01 12:08:26.174  1131  3579 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-01 12:08:26.204  8154  8154 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
07-01 12:08:26.204  8154  8154 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
07-01 12:08:26.204  8154  8154 W HTCLOG  : mask=0x18
07-01 12:08:26.204  8154  8154 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:08:26.204  8154  8154 W HTCLOG  : mask=0x18
07-01 12:08:26.204  8154  8198 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:08:26.204  8154  8198 W HTCLOG  : mask=0x18
07-01 12:08:26.204  8154  8198 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:08:26.204  8154  8198 W HTCLOG  : mask=0x18
07-01 12:08:26.204  8154  8198 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:08:26.204  8154  8198 W HTCLOG  : mask=0x18
07-01 12:08:26.204  8154  8198 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 12:08:26.204  8154  8198 W HTCLOG  : mask=0x18
07-01 12:08:26.214  8154  8198 W HTCLOG  : use specified tag [Surface], func [3].
07-01 12:08:26.214  8154  8198 W HTCLOG  : mask=0x18
07-01 12:08:26.214  8154  8198 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
07-01 12:08:26.214  8154  8198 W HTCLOG  : mask=0x18
07-01 12:08:26.214  8154  8198 W HTCLOG  : use specified tag [qdmemalloc], func [0].
07-01 12:08:26.214  8154  8198 W HTCLOG  : mask=0x18
07-01 12:08:26.214  8110  8201 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 12:08:26.214  8110  8201 W HTCLOG  : mask=0x18
07-01 12:08:26.224  3409  6635 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
07-01 12:08:26.254  3409  6635 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-01 12:08:26.264  1131  1151 I ActivityManager: Start proc 8207:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
07-01 12:08:26.264  1131  1151 D Process : killProcessQuiet, pid=7311
07-01 12:08:26.264  1131  1151 I ActivityManager: Killing 7311:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
07-01 12:08:26.264  1131  1151 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
07-01 12:08:26.264   565   565 I art     : Explicit concurrent mark sweep GC freed 8678(369KB) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 108us total 9.650ms
07-01 12:08:26.274  8207  8207 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:08:26.274  8207  8207 W HTCLOG  : mask=0x18
07-01 12:08:26.274   565   565 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 85us total 6.687ms
07-01 12:08:26.284   565   565 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 182us total 14.657ms
07-01 12:08:26.314  8154  8154 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8154
07-01 12:08:26.344  1131  4055 I ActivityManager: Recipient 7311
07-01 12:08:26.364  1131  1169 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +508ms (total +557ms)
07-01 12:08:26.374  8110  8110 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-01 12:08:26.374  8154  8154 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-01 12:08:26.374  3409  6635 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
07-01 12:08:26.374  8207  8207 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 12:08:26.374  1131  4559 D PMS     : releaseWL(265dc0a): PARTIAL_WAKE_LOCK  Icing 0x1 null
07-01 12:08:26.424  8154  8224 D jxcore_app_log: JniHelper::setJavaVM(0xab6c1b70), pthread_self() = -1402774544
07-01 12:08:26.424  8154  8224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 12:08:26.424  8154  8224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 12:08:26.424  8154  8224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 12:08:26.424  8154  8224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 12:08:26.424  8154  8224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 12:08:26.424  8154  8224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26d7004 added. We now have 1 listener(s)
07-01 12:08:26.424  1131  3558 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-01 12:08:26.424  8154  8224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
07-01 12:08:26.424  8154  8224 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
07-01 12:08:26.424  8154  8224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-01 12:08:26.424  8154  8224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 12:08:26.434  8154  8224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e9b4ab3 added. We now have 1 listener(s)
07-01 12:08:26.434  8154  8224 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 12:08:26.434  1131  3062 D WifiService: New client listening to asynchronous messages
07-01 12:08:26.434  8154  8224 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-01 12:08:26.434  8154  8224 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-01 12:08:26.434  8154  8224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-01 12:08:26.434  8154  8224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 12:08:26.434  8154  8224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-01 12:08:26.434  8154  8224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-01 12:08:26.434  8154  8224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 12:08:26.434  1131  1151 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-01 12:08:26.434  8154  8224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
07-01 12:08:26.434  8154  8224 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-01 12:08:26.434  8154  8224 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 12:08:26.434  8154  8224 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 12:08:26.434  8154  8224 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-01 12:08:26.434  8154  8224 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 12:08:26.434  8154  8224 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 12:08:26.434  8154  8224 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 12:08:26.434  8154  8224 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 12:08:26.434  8154  8224 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 12:08:26.434  8154  8224 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 12:08:26.434  8154  8224 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 12:08:26.434  8154  8224 I io.jxcore.node.LifeCycleMonitor: start: OK
07-01 12:08:26.494  8154  8154 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-01 12:08:26.604  1131  1150 D PMS     : acquireWL(2fb1fa4b): PARTIAL_WAKE_LOCK  AsyncService 0x1 8207 10128 null
07-01 12:08:26.614  1131  4558 D PMS     : releaseWL(2fb1fa4b): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-01 12:08:26.644  3908  3908 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-01 12:08:26.644  3908  3908 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
07-01 12:08:26.644  3908  3908 D c       : Getting all permits...
07-01 12:08:26.644  3908  3908 D a       : Opening database...
07-01 12:08:26.644  3908  3908 D a       : Opening database auth.proximity.permit_store...
07-01 12:08:26.644  3908  3908 D a       : Closing database...
07-01 12:08:26.644  3409  3409 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
07-01 12:08:26.654  7422  7422 D AlarmReceiver: ACTION_RESTART_INTENT
07-01 12:08:26.654  7422  7422 D LocalBluetoothProfile: getPriorityOnValue = 100
07-01 12:08:26.654  1131  1131 D PMS     : releaseWL(825ec7b): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
07-01 12:08:26.654  7422  7422 D LocalBluetoothProfile: getPriorityOffValue = 0
07-01 12:08:26.654  7422  7422 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
07-01 12:08:26.654  7422  7422 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
07-01 12:08:26.654  3409  8245 D LocationInitializer: Restart initialization of location
07-01 12:08:26.684  1131  3019 D PMS     : acquireWL(2423f027): PARTIAL_WAKE_LOCK  *alarm* 0x1 1131 1000 WorkSource{1000}
07-01 12:08:26.684  1131  3019 V AlarmManager: sending alarm PendingIntent{3ba352d4: PendingIntentRecord{bbf0c7d android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=81972, Int=0
07-01 12:08:26.684  1131  3019 V AlarmManager: sending alarm PendingIntent{1bd49772: PendingIntentRecord{33d567c3 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1467367701219, Int=0
07-01 12:08:26.684  1131  1131 D PMS     : acquireWL(1b4cc840): PARTIAL_WAKE_LOCK  *backup* 0x1 1131 1000 null
07-01 12:08:26.684  1131  1131 D PMS     : releaseWL(2423f027): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
07-01 12:08:26.684  1131  3131 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
07-01 12:08:26.684  1131  3131 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
07-01 12:08:26.694  1131  3131 D PMS     : releaseWL(1b4cc840): PARTIAL_WAKE_LOCK  *backup* 0x1 null
07-01 12:08:26.704  7422  8247 D HtcModeClient: start the htcmodeservice thread
07-01 12:08:26.704  7422  8247 D HtcModeClient: initCanAgent
07-01 12:08:26.704  7422  8247 I CANMesgAgentLocalSocket: CANAgent Id = 0
07-01 12:08:26.704  7422  8247 D HtcModeClient: sense info: version = none, id = 2
07-01 12:08:26.704  7422  8247 D HtcModeClient: display info: width = 1080, height = 1776
07-01 12:08:26.704  7422  8247 D HtcModeClient: display info: mode = 10
07-01 12:08:26.704  7422  7422 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
07-01 12:08:26.704  7422  7422 D HtcModeClient: connectState: BT_TURNON_BYME = false
07-01 12:08:26.704  7422  7422 D HtcModeClient: connectState: CONNECTION_READY = false
07-01 12:08:26.704  7422  7422 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
07-01 12:08:26.704  7422  7422 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
07-01 12:08:26.704  7422  7422 D HtcModeClient: connectState: PHONE_PULGIN = false
07-01 12:08:26.704  7422  7422 D HtcModeClient: connectState: Force_AWAKE = false
07-01 12:08:26.704  7422  7422 D HtcModeClient: connectState: PHONE_PULGIN = true
07-01 12:08:26.704  7422  7422 D HtcModeClient: connectState: POWERCONNECTED_READY = true
07-01 12:08:26.794  1131  1178 D PMS     : releaseHCC(178212f1): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
07-01 12:08:26.794  1131  1178 D PMS     : releaseHCC(3b8daed6): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
07-01 12:08:26.854  8154  8238 W jxcore-log: Initializing JXcore engine
07-01 12:08:26.854  8154  8238 W jxcore-log: JXcore engine is ready
,07-01 12:08:26.904  8154  8238 W jxcore-log: Starting JXcore engine,
,07-01 12:08:27.004  8154  8238 W jxcore-log: Platform android
07-01 12:08:27.004  8154  8238 W jxcore-log: 
,07-01 12:08:27.004  8154  8238 W jxcore-log: Process ARCH arm,
07-01 12:08:27.004  8154  8238 W jxcore-log: 
,07-01 12:08:27.184  8154  8238 I jxcore-log: JXcore Cordova bridge is ready!,
07-01 12:08:27.184  8154  8238 I jxcore-log: 
,07-01 12:08:27.184  8154  8238 W jxcore-log: JXcore engine is started
,07-01 12:08:27.194  8154  8224 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,07-01 12:08:27.194  8154  8154 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,07-01 12:08:27.204  8154  8238 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
07-01 12:08:27.204  8154  8238 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-01 12:08:27.214  8154  8154 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
07-01 12:08:27.224  8154  8154 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-01 12:08:27.234  8154  8154 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-01 12:08:27.234  8154  8154 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED,
07-01 12:08:27.234  8154  8154 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-01 12:08:27.234  8154  8154 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-01 12:08:27.234  8154  8154 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 12:08:27.234  8154  8154 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-01 12:08:27.234  8154  8154 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26d7004 removed from the list
07-01 12:08:27.234  8154  8154 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 12:08:27.234  8154  8154 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e9b4ab3 removed from the list
07-01 12:08:27.234  8154  8154 D io.jxcore.node.ConnectivityMonitor: stop
07-01 12:08:27.234  8154  8154 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-01 12:08:27.234  8154  8154 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-01 12:08:27.404  8250  8250 W HTCLOG  : use specified tag [AndroidRuntime], func [0].,
07-01 12:08:27.404  8250  8250 W HTCLOG  : mask=0x18
,07-01 12:08:27.564  8250  8253 W HTCLOG  : use specified tag [cutils-trace], func [0].,
07-01 12:08:27.564  8250  8253 W HTCLOG  : mask=0x18
07-01 12:08:27.564  8250  8253 E cutils-trace: Error opening trace file: Permission denied (13)
,07-01 12:08:27.624  8250  8250 D CustomizationManager: ====startRecUseTime====,
07-01 12:08:27.624  8250  8250 D htc.customization.log.level:  is 
07-01 12:08:27.624  8250  8250 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-01 12:08:27.714  8250  8250 D CustomizationManager:  Read ACC file spent 0.045 (s),
,07-01 12:08:27.724  8250  8250 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml,
07-01 12:08:27.724  8250  8250 I CustomizationCIDLoader: Parsing tag category name = application,
07-01 12:08:27.724  8250  8250 I CustomizationCIDLoader: Parsing tag category name = system
,07-01 12:08:27.724  8250  8250 I CustomizationCIDLoader: Parsing tag category name = Settings
07-01 12:08:27.724  8250  8250 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-01 12:08:27.724  8250  8250 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-01 12:08:27.724  8250  8250 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240,
07-01 12:08:27.724  8250  8250 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
07-01 12:08:27.724  8250  8250 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
07-01 12:08:27.724  8250  8250 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider,
07-01 12:08:27.724  8250  8250 I CustomizationCIDLoader: Parsing tag category name = AudioService
,07-01 12:08:27.724  8250  8250 D CustomizationManager:  Read CID file spent 0.100 (s)
07-01 12:08:27.724  8250  8250 D CustomizationManager:  All configurations done spent 0.101 (s)
,07-01 12:08:27.784  1131  1151 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8250, uid=2000
,07-01 12:08:27.784  1131  1161 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
07-01 12:08:27.784  1131  1161 I ActivityManager: Killing 8154:com.test.thalitest/u0a142 (adj 9): stop com.test.thalitest
07-01 12:08:27.784  1131  1161 D Process : killProcessQuiet, pid=8154
07-01 12:08:27.784  1131  1161 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
,07-01 12:08:27.864   525   525 W HTCLOG  : use specified tag [Vector], func [0].
07-01 12:08:27.864   525   525 W HTCLOG  : mask=0x18
,07-01 12:08:27.874  1131  4065 I ActivityManager: Recipient 8154,
07-01 12:08:27.874  1131  3062 D WifiService: Client connection lost with reason: 4
,07-01 12:08:27.894  1131  4065 W ActivityManager: Spurious death for ProcessRecord{207c98b1 8154:com.test.thalitest/u0a142}, curProc for 8154: null,
07-01 12:08:27.894  1131  3019 D PMS     : acquireWL(13b35f58): PARTIAL_WAKE_LOCK  *alarm* 0x1 1131 1000 WorkSource{10019}
07-01 12:08:27.894  1131  3019 V AlarmManager: sending alarm PendingIntent{15792196: PendingIntentRecord{e73368c com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=91201, Int=0
07-01 12:08:27.894  1131  1183 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed
07-01 12:08:27.894  1131  3408 D PMS     : acquireWL(1cd33117): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 3908 10019 null
,07-01 12:08:27.914  3908  8267 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4,
07-01 12:08:27.914  3908  8267 D libc    : [NET] android_getaddrinfofornet-, err=8
,07-01 12:08:27.914  3908  8267 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
07-01 12:08:27.914  3908  8267 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
,07-01 12:08:27.914  3908  8267 D libc    : [NET] android_getaddrinfo_proxy+
07-01 12:08:27.924  3275  3275 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-01 12:08:27.924  1131  3028 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
07-01 12:08:27.924  3275  3275 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-01 12:08:27.924  1131  3028 V NetworkPolicy: writePolicyLocked()
,07-01 12:08:27.934  3908  8267 D libc    : [NET] android_getaddrinfo_proxy get netid:0,
07-01 12:08:27.934   516  8268 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024,
07-01 12:08:27.934   516  8268 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
07-01 12:08:27.934   516  8268 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
07-01 12:08:27.934   516  8268 D libc    : [NET] android_getaddrinfofornet-, err=7
,07-01 12:08:27.934  3908  8267 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
,07-01 12:08:27.944  1131  3027 D PMS     : acquireWL(2dab1904): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1131 1000 null,
,07-01 12:08:27.954  1131  1160 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,07-01 12:08:27.954  1131  3022 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-01 12:08:27.954  6415  6415 I art     : Explicit concurrent mark sweep GC freed 12291(759KB) AllocSpace objects, 2(40KB) LOS objects, 34% free, 3MB/5MB, paused 464us total 51.633ms
,07-01 12:08:27.964  1131  3027 D PMS     : releaseWL(2dab1904): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,07-01 12:08:27.974  1131  1160 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-01 12:08:27.974  1131  3028 D NetworkPolicy: notifyPoliciesChangeLocked: no change
07-01 12:08:27.974  1131  3028 V NetworkPolicy: updateNetworkEnabledLocked()
07-01 12:08:27.974  1131  3028 V NetworkPolicy: updateNotificationsLocked()
,07-01 12:08:27.984  1131  1131 W PackageManager: Unable to load service info ResolveInfo{45e35a6 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-01 12:08:27.984  1131  1131 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-01 12:08:27.984  1131  1131 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
07-01 12:08:27.984  1131  1131 W PackageManager: 	,at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 12:08:27.984  1131  1131 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,07-01 12:08:27.994  3517  3517 I art     : Explicit concurrent mark sweep GC freed 75193(5MB) AllocSpace objects, 61(3MB) LOS objects, 39% free, 22MB/36MB, paused 1.116ms total 81.567ms
,07-01 12:08:27.994  4256  4531 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-01 12:08:27.994  1131  4559 D PMS     : acquireWL(181deaa9): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4256 10019 null
07-01 12:08:27.994  3517  3894 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,07-01 12:08:27.994  1131  1151 D PMS     : releaseWL(181deaa9): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null,
07-01 12:08:27.994  3517  3894 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
,07-01 12:08:27.994  1131  4558 D PMS     : releaseWL(1cd33117): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
07-01 12:08:27.994  3642  4081 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-01 12:08:28.004  1131  1131 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-01 12:08:28.004  3517  3517 I Launcher: Deferring update until onResume
07-01 12:08:28.014  1131  1131 D PMS     : releaseWL(13b35f58): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10019}
07-01 12:08:28.004  3517  3517 D Launcher: waitUntilResume // bindAppsRemoved
07-01 12:08:28.014  1131  3523 D PMS     : acquireWL(1633c9eb): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 3409 10019 null
07-01 12:08:28.014  3642  4081 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
07-01 12:08:28.014  3409  3409 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,07-01 12:08:28.024  1131  3558 D PMS     : acquireWL(1254c348): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3908 10019 null
,07-01 12:08:28.034  3485  3485 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
07-01 12:08:28.034  3642  4081 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
07-01 12:08:28.034  3670  8269 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-01 12:08:28.034  1131  3502 I ActivityManager: Start proc 8270:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver
07-01 12:08:28.044  3642  4081 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
07-01 12:08:28.044  1131  3504 D PMS     : releaseWL(1254c348): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
07-01 12:08:28.054  3908  3908 I ConfigService: onCreate
07-01 12:08:28.054  8270  8270 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:08:28.054  1131  1131 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
07-01 12:08:28.054  8270  8270 W HTCLOG  : mask=0x18
07-01 12:08:28.054  3908  3908 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
07-01 12:08:28.054  3409  3409 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
07-01 12:08:28.054  3642  4081 E ExternalAccountType: Unsupported attribute readOnly,
,07-01 12:08:28.084  3908  3908 I ConfigService: onBind returning update interface,
,07-01 12:08:28.084  3908  3908 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-01 12:08:28.084  3908  3908 I ConfigService: onBind returning config service
,07-01 12:08:28.084  3908  3908 I ConfigService: onDestroy
,07-01 12:08:28.104  8270  8270 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
07-01 12:08:28.104  8270  8270 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 12:08:28.124  8270  8270 I MultiDex: VM with version 2.1.0 has multidex support,
07-01 12:08:28.124  8270  8270 I MultiDex: install
07-01 12:08:28.124  8270  8270 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-01 12:08:28.124  3517  3517 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
07-01 12:08:28.124  3517  3517 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-01 12:08:28.134  8270  8270 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-01 12:08:28.144  8270  8270 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,07-01 12:08:28.144  1131  1183 I art     : Explicit concurrent mark sweep GC freed 35607(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 15MB/23MB, paused 1.671ms total 243.140ms
07-01 12:08:28.154  1131  5574 I art     : WaitForGcToComplete blocked for 96.137ms for cause Explicit
,07-01 12:08:28.164  3409  8298 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
07-01 12:08:28.164  3409  8298 D AccountUtils: Clearing selected account for com.test.thalitest
,07-01 12:08:28.184  1131  4558 I ActivityManager: Start proc 8300:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver
,07-01 12:08:28.184  3455  3455 D Nfc-Utils: isNxpCodebase: isNxp=false,
,07-01 12:08:28.194  8300  8300 W HTCLOG  : use specified tag [FDManager], func [0].,
07-01 12:08:28.194  8300  8300 W HTCLOG  : mask=0x18
07-01 12:08:28.204  8250  8250 I art     : System.exit called, status: 0,
07-01 12:08:28.204  8250  8250 W HTCLOG  : use specified tag [Vector], func [0].,
07-01 12:08:28.204  8250  8250 W HTCLOG  : mask=0x18
,07-01 12:08:28.224  7712  8325 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id),
,07-01 12:08:28.254  1131  3479 I ActivityManager: Delay finish: com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver,
,07-01 12:08:28.254  1131  3479 D Process : killProcessQuiet, pid=7388
07-01 12:08:28.254  1131  3479 I ActivityManager: Killing 7388:com.htc.sdm/u0a61 (adj 15): empty #17
07-01 12:08:28.254  1131  3479 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
,07-01 12:08:28.264  3409  8328 I PeopleContactsSync: CP2 sync disabled
,07-01 12:08:28.264  1131  4065 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=3409, uid=10019, userID:0
,07-01 12:08:28.314  1131  5574 I art     : Explicit concurrent mark sweep GC freed 7095(405KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/22MB, paused 1.669ms total 165.303ms
,07-01 12:08:28.334  1131  3558 I ActivityManager: Recipient 7388
,07-01 12:08:28.354  1131  3502 I ActivityManager: Resuming delayed broadcast
07-01 12:08:28.364  3642  3642 E PackageActionReceiver: ACTION_PACKAGE_REMOVED
,07-01 12:08:28.364  1131  3070 D PMS     : acquireWL(3b7f7742): PARTIAL_WAKE_LOCK  Icing 0x1 3409 10019 null
,07-01 12:08:28.374  3589  8332 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,07-01 12:08:28.374  3409  6635 I Icing   : doRemovePackageData com.test.thalitest
,07-01 12:08:28.374  1131  4558 D PMS     : releaseWL(3b7f7742): PARTIAL_WAKE_LOCK  Icing 0x1 null
,07-01 12:08:28.374  3589  8332 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,07-01 12:08:28.394  3409  8327 W GmsApplication: Using Auth Proxy for data requests.
,07-01 12:08:28.394  3517  3517 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
,07-01 12:08:28.394  3517  3517 I ContextualWidget: package com.test.thalitest removed
07-01 12:08:28.394  3517  3903 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
,07-01 12:08:28.404  3409  8327 W GmsApplication: Using Auth Proxy for data requests.
07-01 12:08:28.404  3517  8333 I ContextualWidget: com.test.thalitest is not installed
,07-01 12:08:28.404  3517  8333 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,07-01 12:08:28.424  1131  3479 I ActivityManager: Start proc 8334:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
,07-01 12:08:28.434  8334  8334 W HTCLOG  : use specified tag [FDManager], func [0].,
07-01 12:08:28.434  8334  8334 W HTCLOG  : mask=0x18
,07-01 12:08:28.444  3517  3903 I ContextualWidget: MFU.onDownloadDataSetChanged
07-01 12:08:28.444  3517  3903 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
,07-01 12:08:28.444  3517  3517 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId 119cb369-b70e-4907-84a0-aa6b836daf14, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
,07-01 12:08:28.444  3517  3517 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId 119cb369-b70e-4907-84a0-aa6b836daf14, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,07-01 12:08:28.494  3409  8315 W DriveInitializer: Awaiting to be initialized,
,07-01 12:08:28.494  3409  8356 W DriveInitializer: Background init thread started
,07-01 12:08:28.504  3409  8356 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock43] disk I/O error,
07-01 12:08:28.504  3409  8356 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 12:08:28.504  3409  8356 W HTCLOG  : mask=0x18
07-01 12:08:28.504  3409  8356 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x559174ed20
,07-01 12:08:28.504  3409  8356 E DocListDatabase: Failed to delete from ContentFileDeletionLock43
07-01 12:08:28.504  3409  8356 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:08:28.504  3409  8356 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-01 12:08:28.504  3409  8356 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-01 12:08:28.504  3409  8356 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-01 12:08:28.504  3409  8356 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-01 12:08:28.504  3409  8356 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-01 12:08:28.504  3409  8356 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
07-01 12:08:28.504  3409  8356 E DocListDatabase: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
07-01 12:08:28.504  3409  8356 E DocListDatabase: 	,at com.google.android.gms.drive.v.run(SourceFile:69)
07-01 12:08:28.514  3409  8356 W DriveInitializer: Background init thread ended
07-01 12:08:28.514  3409  8315 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-01 12:08:28.514  3409  8315 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x559174ed20
,07-01 12:08:28.514  3409  8356 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread,
07-01 12:08:28.514  3409  8356 E AndroidRuntime: Process: com.google.android.gms, PID: 3409
07-01 12:08:28.514  3409  8356 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:08:28.514  3409  8356 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-01 12:08:28.514  3409  8356 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-01 12:08:28.514  3409  8356 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-01 12:08:28.514  3409  8356 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-01 12:08:28.514  3409  8356 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-01 12:08:28.514  3409  8356 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
07-01 12:08:28.514  3409  8356 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
07-01 12:08:28.514  3409  8356 E AndroidRuntime: 	at com.google.android.gms.drive.v.run(SourceFile:69)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: disk I/O error (code 3850)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.m(SourceFile:501)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:495)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1406)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.ao.a(SourceFile:16)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:28.514  3409  8315 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:28.514  1131  4055 E ActivityManager: App crashed! Process: com.google.android.gms
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: Can't write: system_app_crash
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService,.add(DropBoxManagerService.java:220)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:28.524  1131  8358 E DropBoxManagerService: 	... 5 more
07-01 12:08:28.514  3409  8356 D Process : killProcess, pid=3409
07-01 12:08:28.514  3409  8356 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
07-01 12:08:28.514  3409  8356 W HTCLOG  : use specified tag [Process], func [0].
07-01 12:08:28.514  3409  8356 W HTCLOG  : mask=0x18
,07-01 12:08:28.564  1131  4559 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
,07-01 12:08:28.564  8334  8334 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
,07-01 12:08:28.574  8334  8334 D IdefixUninstallListener: package_removed = com.test.thalitest,
,07-01 12:08:28.604  8334  8334 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,07-01 12:08:28.604  1131  3558 I ActivityManager: Recipient 3409
07-01 12:08:28.604  8334  8334 W HTCLOG  : mask=0x18
07-01 12:08:28.604  1131  4064 D PMS     : handleWLDeath(9bd66a8): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
,07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 12:08:28.604  8334  8334 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 12:08:28.604  1131  4558 D PMS     : handleWLDeath(1633c9eb): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
07-01 12:08:28.604  8334  8334 W System.err: java.sql.SQLException: Getting a writable database from helper a@2011e9d4 failed
07-01 12:08:28.604  1131  3502 D PMS     : handleWLDeath(2d477f09): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
07-01 12:08:28.604  8334  8334 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
07-01 12:08:28.604  1131  3558 I ActivityManager: Process com.google.android.gms (pid 3409) has died
07-01 12:08:28.604  8334  8334 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
07-01 12:08:28.604  1131  3558 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
07-01 12:08:28.604  8334  8334 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
07-01 12:08:28.604  1131  3558 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
07-01 12:08:28.604  8334  8334 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
07-01 12:08:28.604  8334  8334 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
07-01 12:08:28.604  8334  8334 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
07-01 12:08:28.604  8334  8334 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-01 12:08:28.614  1131  4055 I ActivityManager: Killing 7535:com.google.android.gm/u0a97 (adj 15): empty #17
07-01 12:08:28.604  8334  8334 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
,07-01 12:08:28.604  8334  8334 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.os.Looper.loop(Looper.java:155)
,07-01 12:08:28.604  8334  8334 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 12:08:28.604  8334  8334 W System.err: 	,at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:28.604  8334  8334 W System.err: ,	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:28.604  8334  8334 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
,07-01 12:08:28.604  8334  8334 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 12:08:28.604  8334  8334 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:28.604  8334  8334 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method),
07-01 12:08:28.604  8334  8334 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:28.604  8334  8334 W System.err: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190),
07-01 12:08:28.604  8334  8334 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:28.604  8334  8334 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
07-01 12:08:28.604  8334  8334 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:28.604  8334  8334 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
07-01 12:08:28.604  8334  8334 W System.err: 	... 15 more
07-01 12:08:28.614  1131  4055 D Process : killProcessQuiet, pid=7535
07-01 12:08:28.614  1131  4055 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,07-01 12:08:28.714  7422  8247 I HtcModeClient: handler message = 4011,
07-01 12:08:28.714  7422  8247 D HtcModeClient: getConnectionCheckCount first 0
07-01 12:08:28.714  7422  8247 D HtcModeClient: getConnectionCheckCount count = 7
07-01 12:08:28.714  7422  8247 E HtcModeClient: Check connection and retry 8 times.
07-01 12:08:28.714  7422  8247 D HtcModeClient: setConnectionCheckCount count = 8
07-01 12:08:28.714  7422  8247 D HtcModeClient: setupRestart delayedTime = 3000
,07-01 12:08:28.724  7422  7485 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
,07-01 12:08:28.724  3517  3828 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak,
,07-01 12:08:28.784  1131  3523 I ActivityManager: Recipient 7535,
,07-01 12:08:28.894  7422  7422 D HtcModeClient: setBtPriority priority = on
,07-01 12:08:28.894  7422  7422 D HtcModeClient: unbindBlueToothService,
,07-01 12:08:28.894  7422  7422 D HtcModeClient: Don't start project servcice
07-01 12:08:28.894  7422  7422 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
07-01 12:08:28.894  6415  8361 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,07-01 12:08:28.914  1131  4558 I ActivityManager: Start proc 8362:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver,
,07-01 12:08:28.914  7422  7422 D HtcModeClient: connectState: CONNECTION_READY = false
07-01 12:08:28.914  7422  7422 D SilentMusic: call stop
07-01 12:08:28.914  7422  7422 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
07-01 12:08:28.914  7422  8248 W CANMesgAgentLocalSocket: read the terminate packet, so break
,07-01 12:08:28.924  7422  7422 D HtcModeClient: onDestroy
,07-01 12:08:28.924  1131  1150 D Process : killProcessQuiet, pid=7240
07-01 12:08:28.924  1131  1150 I ActivityManager: Killing 7240:com.google.android.music:main/u0a115 (adj 15): empty #17
07-01 12:08:28.924  1131  1150 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
07-01 12:08:28.924  8362  8362 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:08:28.924  8362  8362 W HTCLOG  : mask=0x18
,07-01 12:08:28.934  6415  8361 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,07-01 12:08:28.934  6415  8361 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 12:08:28.934  6415  8361 W HTCLOG  : mask=0x18
07-01 12:08:28.934  6415  8361 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x559163e250
,07-01 12:08:29.054  1131  4559 I ActivityManager: Recipient 7240,
07-01 12:08:29.054  1131  4065 D MediaRouterService: Client com.google.android.music (pid 7240): Died!
,07-01 12:08:29.164  6415  8361 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
,07-01 12:08:29.164  6415  8361 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService],
07-01 12:08:29.164  6415  8361 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6415
07-01 12:08:29.164  6415  8361 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	,at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.164  6415  8361 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 12:08:29.164  1131  3516 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: Can't write: system_app_crash
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system),
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: 	,at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.164  1131  8384 E DropBoxManagerService: 	... 5 more
,07-01 12:08:29.174  6415  8361 D Process : killProcess, pid=6415
07-01 12:08:29.174  8362  8362 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 
07-01 12:08:29.174  6415  8361 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
,07-01 12:08:29.174  6415  8361 W HTCLOG  : use specified tag [Process], func [0].
07-01 12:08:29.174  6415  8361 W HTCLOG  : mask=0x18
,07-01 12:08:29.184  8362  8385 W HTCLOG  : use specified tag [SQLiteDBG], func [0].,
07-01 12:08:29.184  8362  8385 W HTCLOG  : mask=0x18
07-01 12:08:29.184  8362  8385 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73],
07-01 12:08:29.194  1131  1151 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 12:08:29.184  8362  8385 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.android.keychain/databases/grants.db) - 
07-01 12:08:29.184  8362  8385 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
07-01 12:08:29.184  8362  8385 W HTCLOG  : mask=0x18
07-01 12:08:29.184  8362  8385 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.android.keychain/databases/grants.db, flag: 6, ret: 14
07-01 12:08:29.184  8362  8385 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory,
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402),
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	,at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.184  8362  8385 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
07-01 12:08:29.184  8362  8385 E AndroidRuntime: Process: com.android.keychain, PID: 8362
07-01 12:08:29.184  8362  8385 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: ,	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.184  8362  8385 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.194  1131  1151 E ActivityManager: App crashed! Process: com.android.keychain
07-01 12:08:29.204  1131  3504 D PMS     : acquireWL(155989bc): PARTIAL_WAKE_LOCK  AsyncService 0x1 8207 10128 null
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: Leak found
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:29.194  7973  7988 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 12:08:29.194  ,7973  7988 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 12:08:29.194  1131  1151 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.194  1131  1151 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.194  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.194  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.194  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.194  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:08:29.194  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:08:29.194  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 12:08:29.194  1131  1151 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-01 12:08:29.194  1131  1151 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:08:29.194  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:08:29.194  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:08:29.194  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:08:29.194  1131  1151 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:08:29.194  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:08:29.194  1131  1151 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:08:29.194  1131  1151 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system),
07-01 12:08:29.194  1131  1151 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.194  1131  1151 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.194  1131  1151 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.194  1131  1151 W System.err: 	... 14 more
07-01 12:08:29.204  1131  1151 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.204  1131  1151 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.204  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.204  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.204  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.204  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:08:29.204  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:08:29.204  1131  8387 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 12:08:29.204  1131  8387 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467367709214.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 12:08:29.204  1131  8387 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.204  1131  8387 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.204  1131  8387 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:08:29.204  1131  8387 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 12:08:29.204  1131  8387 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:08:29.204  1131  8387 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.204  1131  8387 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.204  1131  8387 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.204  1131  8387 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.204  1131  8387 E ErrorReport: 	... 4 more
07-01 12:08:29.204  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-01 12:08:29.204  1131  1151 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 12:08:29.204  1131  1151 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:08:29.204  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:08:29.204  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:08:29.204  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:08:29.204  1131  1151 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:08:29.204  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:08:29.204  1131  1151 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:08:29.214  1131  4559 D PMS     : releaseWL(155989bc): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-01 12:08:29.204  1131  1151 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.204  1131  1151 W System.err: 	at libcore.io.Posix.open(Native Method)
07,-01 12:08:29.204  1131  1151 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.204  1131  1151 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.204  1131  1151 W System.err: 	... 14 more
07-01 12:08:29.204  1131  3579 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.204  8362  8385 D Process : killProcess, pid=8362
07-01 12:08:29.204  1131  3579 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.204  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.204  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.204  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.204  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 12:08:29.204  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 12:08:29.204  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 12:08:29.204  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 12:08:29.204  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 12:08:29.204  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 12:08:29.204  1131  3579 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.204  1131  3579 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.204  1131  3579 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.204  8362  8385 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 12:08:29.204  1131  3579 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.204  1131  3579 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.204  1131  3579 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.204  1131  3579 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.204  1131  3579 W System.err: 	... 12 more
07-01 12:08:29.204  8362  8385 W HTCLOG  : use specified tag [Process], func [0].
07-01 12:08:29.204  8362  8385 W HTCLOG  : mask=0x18
07-01 12:08:29.214  8088  8088 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
07-01 12:08:29.214  8088  8088 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
07-01 12:08:29.214  8088  8088 I DeviceManagement: WorkflowService: Starting workflow service
07-01 12:08:29.214  1131  4065 I ActivityManager: Recipient 8362
07-01 12:08:29.224  8088  8388 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@13e94fa4] args=[Bundle[mParcelledData.dataSize=112]]
07-01 12:08:29.224  8088  8388 I DeviceManagement: PackageUpdateWorkflow: ==================================================
07-01 12:08:29.224  8088  8388 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
07-01 12:08:29.224  8088  8388 I DeviceManagement: PackageUpdateWorkflow: ==================================================
07-01 12:08:29.224  8088  8388 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
07-01 12:08:29.224  1131  3523 I ActivityManager: Start proc 8389:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
07-01 12:08:29.234  8389  8389 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:08:29.234  8389  8389 W HTCLOG  : mask=0x18
07-01 12:08:29.244  1131  3408 I ActivityManager: Recipient 6415
07-01 12:08:29.244  1131  3062 D WifiService: Client connection lost with reason: 4
07-01 12:08:29.254  8088  8388 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,07-01 12:08:29.254  8088  8410 I DeviceManagement: SessionStateController: Checking invariants...
07-01 12:08:29.254  1131  4065 I ActivityManager: Process com.android.keychain (pid 8362) has died
07-01 12:08:29.254  1131  4065 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20353ms
07-01 12:08:29.254  1131  3408 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6415) has died
07-01 12:08:29.254  1131  3408 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10351ms
07-01 12:08:29.254  1131  3408 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10351ms
07-01 12:08:29.274  8389  8389 W ContextImpl: Unable to create files subdir /data/data/com.android.documentsui/cache
07-01 12:08:29.274  8389  8389 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-01 12:08:29.304  8389  8389 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
,07-01 12:08:29.304  8389  8389 W HTCLOG  : mask=0x18
07-01 12:08:29.304  8389  8389 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73]
07-01 12:08:29.304  8389  8389 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.android.documentsui/databases/recents.db) - 
07-01 12:08:29.304  8389  8389 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 12:08:29.304  8389  8389 W HTCLOG  : mask=0x18
07-01 12:08:29.304  8389  8389 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.android.documentsui/databases/recents.db, flag: 6, ret: 14
07-01 12:08:29.304  8389  8389 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
,07-01 12:08:29.304  8389  8389 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: ,	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 12:08:29.304  8389  8389 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: FATAL EXCEPTION: main
07-01 12:08:29.304  8389  8389 E AndroidRuntime: Process: com.android.documentsui, PID: 8389
07-01 12:08:29.304  8389  8389 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java,:268)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-01 12:08:29.304  8389  8389 E AndroidRuntime: 	... 9 more
07-01 12:08:29.304  1131  3504 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 12:08:29.304  1131  3504 E ActivityManager: App crashed! Process: com.android.documentsui
07-01 12:08:29.304  1131  3504 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.304  1131  3504 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.304  1131  3504 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.304  1131  3504 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.304  1131  3504 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
,07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:08:29.304  1131  3504 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:08:29.304  1131  3504 W System.err: 	,at android.os.Binder.execTransact(Binder.java:454)
07-01 12:08:29.304  1131  3504 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.304  1131  3504 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.304  1131  3504 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.304  1131  3504 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
,07-01 12:08:29.304  1131  3504 W System.err: 	... 14 more
07-01 12:08:29.304  1131  3504 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.304  1131  3504 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.304  1131  3504 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.304  1131  3504 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,07-01 12:08:29.304  1131  3504 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,07-01 12:08:29.304  1131  3504 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142),
07-01 12:08:29.314  1131  3070 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 12:08:29.304  1131  3504 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:08:29.314  1131  8412 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 12:08:29.314  1131  8412 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467367709325.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 12:08:29.314  1131  8412 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.314  1131  8412 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.314  1131  8412 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:08:29.314  1131  8412 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 12:08:29.314  1131  8412 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:08:29.314  1131  8412 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.314  1131  8412 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.314  1131  8412 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.314  1131  8412 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.314  1131  8412 E ErrorReport: 	... 4 more
07-01 12:08:29.304  1131  3504 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:08:29.304  1131  3504 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:08:29.324  1131  8413 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 12:08:29.324  1131  8413 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467367709330.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 12:08:29.324  1131  8413 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.324  1131  8413 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.324  1131  8413 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:08:29.324  1131  8413 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 12:08:29.324  1131  8413 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:08:29.324  1131  8413 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.324  1131  8413 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.324  1131  8413 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.324  1131  8413 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.324  1131  8413 E ErrorReport: 	... 4 more
07-01 12:08:29.304  1131  3504 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
,07-01 12:08:29.304  1131  3504 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:08:29.304  1131  3504 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.304  1131  3504 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.304  1131  3504 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.304  1131  3504 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.304  1131  3504 W System.err: 	... 14 more
07-01 12:08:29.314  5524  5646 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
07-01 12:08:29.314  5524  5646 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 12:08:29.314  5524  5646 W HTCLOG  : mask=0x18
07-01 12:08:29.314  5524  5646 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x5591603bc0
07-01 12:08:29.314  5524  5646 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
07-01 12:08:29.314  5524  5646 E AndroidRuntime: Process: android.process.media, PID: 5524
07-01 12:08:29.314  5524  5646 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.314  5524  5646 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.314  1131  3070 E ActivityManager: App crashed! Process: android.process.media
07-01 12:08:29.314  1131  3070 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.314  1131  3070 W System.err: 	,at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.314  1131  3070 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.314  1131  3070 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.314  1131  3070 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.314  1131  3070 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:08:29.314  1131  3070 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:08:29.314  1131  3070 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 12:08:29.314  1131  3070 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-01 12:08:29.314  1131  3070 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:08:29.314  1131  3070 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:08:29.314  1131  3070 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:08:29.314  1131  3070 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:08:29.314  1131  3070 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:08:29.314  1131  3070 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:08:29.314  1131  3070 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:08:29.314  1131  3070 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.314  1131  3070 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.314  1131  3070 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.314  1131  3070 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.314  1131  3070 W System.err: 	... 14 more
07-01 12:08:29.314  1131  3579 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.314  1131  3579 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.314  8389  8389 D Process : killProcess, pid=8389
07-01 12:08:29.314  8389  8389 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 12:08:29.324  8389  8389 W HTCLOG  : use specified tag [Process], func [0].
07-01 12:08:29.324  8389  8389 W HTCLOG  : mask=0x18
07-01 12:08:29.324  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.324  1131  3070 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.324  1131  3070 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.324  1131  3070 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.324  1131  3070 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.324  1131  3070 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.324  1131  3070 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:08:29.324  1131  3070 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:08:29.324  1131  3070 W System.err: 	at, com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-01 12:08:29.324  1131  3070 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 12:08:29.324  1131  3070 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:08:29.324  1131  3070 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:08:29.324  1131  3070 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:08:29.324  1131  3070 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:08:29.324  1131  3070 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:08:29.324  1131  3070 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:08:29.324  1131  3070 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:08:29.324  1131  3070 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.324  1131  3070 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.324  1131  3070 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.324  1131  3070 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.324  1131  3070 W System.err: 	... 14 more
07-01 12:08:29.324  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.324  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 12:08:29.334  1131  1161 I ActivityManager: Start proc 8414:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 12:08:29.324  1131  3579 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.324  1131  3579 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.324  1131  3579 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.324  1131  3579 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.324  1131  3579 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.324  1131  3579 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.324  1131  3579 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.324  1131  3579 W System.err: 	... 12 more
07-01 12:08:29.324  1131  3579 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.324  1131  3579 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.324  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.324  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.324  1131  35,79 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 12:08:29.324  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 12:08:29.324  1131  3579 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.324  1131  3579 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.324  1131  3579 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.324  1131  3579 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.324  1131  3579 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.324  1131  3579 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.324  1131  3579 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.324  1131  3579 W System.err: 	... 12 more
07-01 12:08:29.334  5524  5646 D Process : killProcess, pid=5524
07-01 12:08:29.334  5524  5646 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 12:08:29.334  5524  5646 W HTCLOG  : use specified tag [Process], func [0].
07-01 12:08:29.334  5524  5646 W HTCLOG  : mask=0x18
07-01 12:08:29.354  8414  8414 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:08:29.354  8414  8414 W HTCLOG  : mask=0x18
07-01 12:08:29.364   495   495 E lowmemorykiller: Error writing /proc/5524/oom_score_adj; errno=22
07-01 12:08:29.364  1131  3558 W HTCLOG  : use specified tag [JavaBinder], func [0].
07-01 12:08:29.364  1131  3558 W HTCLOG  : mask=0x18
07-01 12:08:29.364  1131  3558 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
07-01 12:08:29.374  1131  1151 I ActivityManager: Recipient 8389
07-01 12:08:29.374  1131  1151 I ActivityManager: Process com.android.documentsui (pid 8389) has died
07-01 12:08:29.384  1131  3516 I ActivityManager: Recipient 5524,
07-01 12:08:29.384  1131  3516 I ActivityManager: Process android.process.media (pid 5524) has died
07-01 12:08:29.384  8088  8410 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 12:08:29.384  8088  8410 W HTCLOG  : mask=0x18
07-01 12:08:29.384  1131  3516 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 20226ms
,07-01 12:08:29.384  8088  8410 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	,at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	,at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 12:08:29.384  8088  8410 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:08:29.384  8088  8410 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:29.394  8414  8414 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
07-01 12:08:29.384  3275  3724 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
07-01 12:08:29.384  8088  8388 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:29.384  8088  8388 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
07-01 12:08:29.394  3185  3185 I NotificationStackScrollLayout: setBlockTouchEnabled:false
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.content.ContextWra,pper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.394  8088  8388 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.394  8088  8388 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@13e94fa4]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.394  8088  8388 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.394  8088  8088 I DeviceManagement: WorkflowService: Stopping workflow service
07-01 12:08:29.404  8414  8436 D PowerUtils: getUserIdOfProcess, curUserId = 0
07-01 12:08:29.404  8414  8436 D PowerUtils: isRunningUnderOwner, isOwner = true
07-01 12:08:29.404  1131  1150 I ActivityManager: Start proc 8437:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
07-01 12:08:29.414  8414  8436 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
07-01 12:08:29.414  8414  8436 D PowerUsageService: removed uid = 10142
07-01 12:08:29.414  8437  8437 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:08:29.414  8437  8437 W HTCLOG  : mask=0x18
07-01 12:08:29.424  8414  8436 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 12:08:29.424  8414  8436 W HTCLOG  : mask=0x18
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.424  8414  8436 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
07-01 12:08:29.424  8414  8436 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 8414
07-01 12:08:29.424  8414  8436 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelpe,r.java:163)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.424  8414  8436 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.424  1131  1151 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
07-01 12:08:29.424  1131  1151 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 12:08:29.424  1131  1151 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.424  1131  1151 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.434  1131  8458 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 12:08:29.434  1131  8458 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467367709441.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 12:08:29.434  1131  8458 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.434  1131  8458 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.434  1131  8458 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:08:29.434  1131  8458 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 12:08:29.434  1131  8458 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:08:29.434  1131  8458 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.434  1131  8458 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.434  1131  8458 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.434  1131  8458 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.434  1131  8458 E ErrorReport: 	... 4 more
07-01 12:08:29.424  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.424  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.424  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.424  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:08:29.424  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:08:29.424  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 12:08:29.424  1131  1151 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-01 12:08:29.424  1131  1151 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:08:29.424  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:08:29.424  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:08:29.424  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:08:29.424  1131  1151 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:08:29.424  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:08:29.424  1131  1151 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:08:29.424  1131  1151 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.424  1131  1151 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.424  1131  1151 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.424  1131  1151 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.424  1131  1151 W System.err: 	... 14 more
07-01 12:08:29.434  1131  1151 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.434  1131  1151 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.434  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.434  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.434  1131  1151 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.434  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:08:29.434  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:08:29.434  1131  1151 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-01 12:08:29.434  1131  1151 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 12:08:29.434  1131  1151 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:08:29.434  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:08:29.434  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:08:29.434  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:08:29.434  1131  1151 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:08:29.434  1131  1151 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:08:29.434  1131  1151 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:08:29.434  1131  1151 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.434  1131  1151 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.434  1131  1151 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.434  1131  1151 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.434  1131  1151 W System.err: 	... 14 more
07-01 12:08:29.434  1131  3579 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.434  1131  3579 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.434  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.434  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.434  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.434  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 12:08:29.434  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 12:08:29.434  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 12:08:29.434  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 12:08:29.434  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 12:08:29.434  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 12:08:29.434  1131  3579 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.434  1131  3579 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.434  1131  3579 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.434  1131  3579 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.434  1131  3579 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.434  1131  3579 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.434  1131  3579 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.434  1131  3579 W System.err: 	... 12 more
07-01 12:08:29.444  8414  8436 D Process : killProcess, pid=8414
07-01 12:08:29.444  8414  8436 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 12:08:29.444  8414  8436 W HTCLOG  : use specified tag [Process], func [0].
07-01 12:08:29.444  8414  8436 W HTCLOG  : mask=0x18
,07-01 12:08:29.484  8437  8459 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,07-01 12:08:29.484  8437  8459 W HTCLOG  : mask=0x18
,07-01 12:08:29.494  8437  8459 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163),
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.494  8437  8459 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
07-01 12:08:29.494  8437  8459 E AndroidRuntime: Process: com.htc.updater, PID: 8437
07-01 12:08:29.494  8437  8459 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
,07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.494  8437  8459 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.494  1131  4055 E ActivityManager: App crashed! Process: com.htc.updater
07-01 12:08:29.494  1131  4055 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 12:08:29.494  1131  4055 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.494  1131  4055 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.494  1131  4055 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.494  1131  4055 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,07-01 12:08:29.494  1131  4055 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:08:29.494  1131  4055 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:08:29.494  1131  4055 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:08:29.494  3517  3894 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-01 12:08:29.494  3517  3894 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@59450e8 +
07-01 12:08:29.494  1131  4055 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.504  1131  4559 I ActivityManager: Recipient 8414
07-01 12:08:29.494  3517  3894 I Prism.WidgetManager: onLoadItems() +
07-01 12:08:29.494  1131  4055 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.494  1131  4055 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.494  1131  4055 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.494  1131  4055 W System.err: 	... 14 more
,07-01 12:08:29.494  1131  4055 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 12:08:29.494  1131  4055 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.494  1131  4055 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.494  1131  4055 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.494  1131  4055 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
,07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 12:08:29.494  1131  4055 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
,07-01 12:08:29.494  1131  4055 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 12:08:29.494  1131  4055 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 12:08:29.494  1131  4055 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.494  1131  4055 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.494  1131  4055 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.494  1131  4055 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.494  1131  4055 W System.err: 	... 14 more
,07-01 12:08:29.504  8437  8437 V UpdaterAPK | DownloadService: Service onStart
07-01 12:08:29.504  8437  8460 V UpdaterAPK | DownloadService: Updating for startId 1
,07-01 12:08:29.504  1131  4559 I ActivityManager: Process com.htc.htcpowermanager:remote (pid 8414) has died
,07-01 12:08:29.504  1131  4559 W ActivityManager: Scheduling restart of crashed service com.htc.htcpowermanager/.battery.PowerUsageService in 30100ms
07-01 12:08:29.504  1131  8462 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 12:08:29.504  1131  8462 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467367709517.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 12:08:29.504  1131  8462 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.504  1131  8462 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.504  1131  8462 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 12:08:29.504  1131  8462 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 12:08:29.504  1131  8462 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 12:08:29.504  1131  8462 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
,07-01 12:08:29.504  1131  8462 E ErrorReport: 	at libcore.io.Posix.open(Native Method),
07-01 12:08:29.504  1131  8462 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.504  1131  8462 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.504  1131  8462 E ErrorReport: 	... 4 more
07-01 12:08:29.514  1131  3579 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
,07-01 12:08:29.514  1131  3579 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 12:08:29.514  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 12:08:29.514  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 12:08:29.514  1131  3579 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 12:08:29.514  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 12:08:29.514  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 12:08:29.514  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
,07-01 12:08:29.514  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 12:08:29.514  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 12:08:29.514  1131  3579 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 12:08:29.514  1131  3579 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 12:08:29.514  1131  3579 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 12:08:29.514  1131  3579 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 12:08:29.514  8437  8459 D Process : killProcess, pid=8437
07-01 12:08:29.514  8437  8459 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 12:08:29.514  8437  8459 W HTCLOG  : use specified tag [Process], func [0].
07-01 12:08:29.514  8437  8459 W HTCLOG  : mask=0x18
07-01 12:08:29.514  1131  3579 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 12:08:29.514  3908  3908 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-01 12:08:29.524  1131  3579 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 12:08:29.524  3517  3894 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,07-01 12:08:29.524  1131  3579 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 12:08:29.524  1131  3579 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 12:08:29.524  1131  3579 W System.err: 	... 12 more
07-01 12:08:29.524  1131  3558 I ActivityManager: Start proc 8463:com.google.android.gms/u0a19 for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver
,07-01 12:08:29.544  8463  8463 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 12:08:29.544  8463  8463 W HTCLOG  : mask=0x18
,07-01 12:08:29.574  8463  8463 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
07-01 12:08:29.574  8463  8463 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 12:08:29.574  1131  3504 I ActivityManager: Recipient 8437
07-01 12:08:29.574  1131  3504 I ActivityManager: Process com.htc.updater (pid 8437) has died
07-01 12:08:29.574  1131  3504 W ActivityManager: Scheduling restart of crashed service com.htc.updater/.download.DownloadService in 40037ms

```
