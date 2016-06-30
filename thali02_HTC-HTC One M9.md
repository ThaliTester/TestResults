#### Test 757892682551a10_thali02_HTC-HTC One M9 Logs


```
--------- beginning of main
06-30 13:52:34.424  8196  8196 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8196 dbg=false s=true
06-30 13:52:34.424  8196  8196 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
06-30 13:52:34.434  1115  3378 D Process : killProcessQuiet, pid=7812
06-30 13:52:34.434  1115  3378 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
--------- beginning of system
06-30 13:52:34.434  1115  3378 I ActivityManager: Start proc 8222:com.google.android.apps.docs/u0a91 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
06-30 13:52:34.434  1115  3378 I ActivityManager: Killing 7812:com.htc.calendar/u0a6 (adj 15): empty #17
06-30 13:52:34.444  8222  8222 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 13:52:34.444  8222  8222 W HTCLOG  : mask=0x18
06-30 13:52:34.454   561   561 I art     : Explicit concurrent mark sweep GC freed 8664(369KB) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 191us total 20.900ms
,06-30 13:52:34.474   561   561 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 187us total 14.698ms
06-30 13:52:34.484   561   561 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 183us total 14.828ms
06-30 13:52:34.524  1115  3380 I ActivityManager: Recipient 7812
06-30 13:52:34.564  1115  3766 D PMS     : acquireWL(be5dada): PARTIAL_WAKE_LOCK  Icing 0x1 3445 10019 null
06-30 13:52:34.594  1115  3164 D PMS     : releaseWL(be5dada): PARTIAL_WAKE_LOCK  Icing 0x1 null
06-30 13:52:34.594  1115  3766 D PMS     : acquireWL(33691094): PARTIAL_WAKE_LOCK  Icing 0x1 3445 10019 null
06-30 13:52:34.604  1115  3498 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 13:52:34.604  6502  8195 I ApplicationLogger: canRun() : Opted Out
06-30 13:52:34.604  6502  8195 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 270 ms] updated apps [took 270 ms] 
06-30 13:52:34.604  1115  3763 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 13:52:34.634  8243  8243 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
06-30 13:52:34.634  8243  8243 W HTCLOG  : mask=0x18
06-30 13:52:34.644  8222  8222 D DocsApplication: Plugin installer initialized.
06-30 13:52:34.644  1115  4152 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 13:52:34.654  8222  8222 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3d31da32 com.google.android.apps.docs}
06-30 13:52:34.674  8222  8222 D TAG     : onCreate()
06-30 13:52:34.684  8222  8222 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
06-30 13:52:34.694  1115  4154 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 13:52:34.774  3558  3951 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
06-30 13:52:34.774  3558  3951 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@34a76f7c +
06-30 13:52:34.774  3558  3951 I Prism.WidgetManager: onLoadItems() +
06-30 13:52:34.794  8243  8249 W HTCLOG  : use specified tag [cutils-trace], func [0].
06-30 13:52:34.804  8243  8249 W HTCLOG  : mask=0x18
06-30 13:52:34.804  8243  8249 E cutils-trace: Error opening trace file: Permission denied (13)
06-30 13:52:34.804  3558  3951 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
06-30 13:52:34.864  8243  8243 D CustomizationManager: ====startRecUseTime====
06-30 13:52:34.864  8243  8243 D htc.customization.log.level:  is 
06-30 13:52:34.864  8243  8243 W CustomizationLogLevel: Level value is invalid, use default level 2
06-30 13:52:34.944  8243  8243 D CustomizationManager:  Read ACC file spent 0.038 (s)
06-30 13:52:34.944  8243  8243 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
06-30 13:52:34.944  8243  8243 I CustomizationCIDLoader: Parsing tag category name = application
06-30 13:52:34.954  8243  8243 I CustomizationCIDLoader: Parsing tag category name = system
06-30 13:52:34.954  8243  8243 I CustomizationCIDLoader: Parsing tag category name = Settings
06-30 13:52:34.954  8243  8243 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-30 13:52:34.954  8243  8243 I CustomizationCIDLoader: Parsing tag category name = ACC
06-30 13:52:34.954  8243  8243 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
06-30 13:52:34.954  8243  8243 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
06-30 13:52:34.954  8243  8243 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
06-30 13:52:34.954  8243  8243 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-30 13:52:34.954  8243  8243 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-30 13:52:34.954  8243  8243 D CustomizationManager:  Read CID file spent 0.088 (s)
06-30 13:52:34.954  8243  8243 D CustomizationManager:  All configurations done spent 0.089 (s)
06-30 13:52:34.964  3528  4204 D PhoneApp: EVENT_QUERY_MO_PACKAGES
06-30 13:52:34.964  3528  4204 D PhoneApp: -- N1 =0
06-30 13:52:34.964  3528  4204 D PhoneApp: -- N2 =0
06-30 13:52:34.964  3528  4204 D PhoneApp: -- N3 =0
06-30 13:52:34.994  1115  3498 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8243 on display 0
06-30 13:52:34.994  1115  1164 D PMS     : acquireHCC(d41573d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1115 1000 null
06-30 13:52:34.994  1115  1164 D PMS     : acquireHCC(394eb32): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1115 1000 null
06-30 13:52:35.004  1115  3498 V WindowManager: addAppToken: AppWindowToken{23712a39 token=Token{1b10a200 ActivityRecord{bd9083 u0 com.test.thalitest/.MainActivity t43}}} to stack=1 task=43 at 0
06-30 13:52:35.014  1115  3498 I ActivityManager: Start proc 8262:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
06-30 13:52:35.014  3558  3951 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 13:52:35.014  8243  8243 W HTCLOG  : use specified tag [IPCThreadState], func [0].
06-30 13:52:35.014  8243  8243 W HTCLOG  : mask=0x18
06-30 13:52:35.024  8243  8260 W HTCLOG  : use specified tag [Vector], func [0].
06-30 13:52:35.024  8243  8260 W HTCLOG  : mask=0x18
06-30 13:52:35.024  8262  8262 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 13:52:35.024  8262  8262 W HTCLOG  : mask=0x18
06-30 13:52:35.034  1115  1115 V ActivityManager: Display changed displayId=0
06-30 13:52:35.034  3325  3325 D DotMatrix: [EventService]  onDisplayChanged: 0
06-30 13:52:35.034  3325  3325 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
06-30 13:52:35.044  1115  3380 D ActivityManager: screenshot for ActivityRecord{bd9083 u0 com.test.thalitest/.MainActivity t43}, bitmap=null, time = 0
06-30 13:52:35.064  3558  3558 I TrimMemoryManager: [trimMemory] 20
06-30 13:52:35.104  8262  8262 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
06-30 13:52:35.154  8262  8262 I LibraryLoader: Time to load native libraries: 29 ms (timestamps 649-678)
06-30 13:52:35.154  8262  8262 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:35.174  8262  8262 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3b1f677e}
06-30 13:52:35.174  8262  8262 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:35.174  8262  8262 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:52:35.174  3558  3951 I Prism.WidgetManager: onLoadItems() -
06-30 13:52:35.174  3558  3951 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@34a76f7c -
06-30 13:52:35.184  8262  8262 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 13:52:35.184  8262  8262 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:35.184  8262  8262 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 13:52:35.234  8262  8285 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,06-30 13:52:35.234  8262  8289 D BluetoothAdapter: 123446495: getState() :  mService = null. Returning STATE_OFF
06-30 13:52:35.244  8262  8262 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
06-30 13:52:35.244  8262  8262 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
06-30 13:52:35.244  8262  8262 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
06-30 13:52:35.254  8262  8262 W HTCLOG  : use specified tag [libEGL], func [3].
06-30 13:52:35.254  8262  8262 W HTCLOG  : mask=0x18
06-30 13:52:35.254  8262  8262 W HTCLOG  : use specified tag [libEGL], func [3].
06-30 13:52:35.254  8262  8262 W HTCLOG  : mask=0x18
06-30 13:52:35.254  8262  8262 I Adreno  : QUALCOMM build                   : 065751b, 
06-30 13:52:35.254  8262  8262 I Adreno  : Build Date                       : 04/15/15
06-30 13:52:35.254  8262  8262 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
06-30 13:52:35.254  8262  8262 I Adreno  : Local Branch                     : 
06-30 13:52:35.254  8262  8262 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
06-30 13:52:35.254  8262  8262 I Adreno  : Remote Branch                    : NONE
06-30 13:52:35.254  8262  8262 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
06-30 13:52:35.324  8262  8295 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
06-30 13:52:35.344  8262  8262 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:35.354  8262  8262 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 13:52:35.364  8262  8262 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
06-30 13:52:35.374  8262  8262 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:35.374  8262  8262 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:35.404  8262  8306 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 13:52:35.404  8262  8306 W HTCLOG  : mask=0x18
06-30 13:52:35.404  1115  3164 V WindowManager: Adding window Window{31b98ee1 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{37bc88fc u0 com.htc.launcher/com.htc.launcher.Launcher})
06-30 13:52:35.414  1115  3617 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
06-30 13:52:35.444  8262  8262 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
06-30 13:52:35.444  8262  8262 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
06-30 13:52:35.444  8262  8262 W HTCLOG  : mask=0x18
06-30 13:52:35.444  8262  8262 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 13:52:35.444  8262  8262 W HTCLOG  : mask=0x18
06-30 13:52:35.444  8262  8306 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 13:52:35.444  8262  8306 W HTCLOG  : mask=0x18
06-30 13:52:35.444  8262  8306 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 13:52:35.444  8262  8306 W HTCLOG  : mask=0x18
06-30 13:52:35.444  8262  8306 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 13:52:35.444  8262  8306 W HTCLOG  : mask=0x18
06-30 13:52:35.454  8262  8306 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 13:52:35.454  8262  8306 W HTCLOG  : mask=0x18
06-30 13:52:35.454  8262  8306 W HTCLOG  : use specified tag [Surface], func [3].
06-30 13:52:35.454  8262  8306 W HTCLOG  : mask=0x18
06-30 13:52:35.454  8262  8306 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
06-30 13:52:35.454  8262  8306 W HTCLOG  : mask=0x18
06-30 13:52:35.454  8262  8306 W HTCLOG  : use specified tag [qdmemalloc], func [0].
06-30 13:52:35.454  8262  8306 W HTCLOG  : mask=0x18
06-30 13:52:35.504  8222  8311 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 13:52:35.504  8222  8311 W HTCLOG  : mask=0x18
06-30 13:52:35.514  1115  1155 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +468ms (total +509ms)
06-30 13:52:35.554  1115  3498 I ActivityManager: Start proc 8316:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
06-30 13:52:35.554  1115  3498 D Process : killProcessQuiet, pid=7422
06-30 13:52:35.554  1115  3498 I ActivityManager: Killing 7422:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
06-30 13:52:35.554  1115  3498 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
06-30 13:52:35.554  8316  8316 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 13:52:35.554  8316  8316 W HTCLOG  : mask=0x18
06-30 13:52:35.564  8262  8262 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8262
06-30 13:52:35.604  1115  3380 I ActivityManager: Recipient 7422
06-30 13:52:35.604  3445  6727 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
06-30 13:52:35.614  8222  8222 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
06-30 13:52:35.624  8316  8316 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:52:35.644  3445  6727 D Icing   : Loaded CLD2 Version V2.0 - 20140131
06-30 13:52:35.654  8262  8262 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 13:52:35.664  3445  6727 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
06-30 13:52:35.674  1115  4164 D PMS     : releaseWL(33691094): PARTIAL_WAKE_LOCK  Icing 0x1 null
06-30 13:52:35.694  1115  3071 V AlarmManager: sending alarm PendingIntent{37ce4dd5: PendingIntentRecord{264c39ea android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=81982, Int=0
06-30 13:52:35.694  1115  3071 V AlarmManager: sending alarm PendingIntent{3d1624db: PendingIntentRecord{1e0a9b78 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1467287548917, Int=0
06-30 13:52:35.714  8262  8312 D jxcore_app_log: JniHelper::setJavaVM(0xab44bb70), pthread_self() = -1405153136
06-30 13:52:35.714  8262  8312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:52:35.714  8262  8312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:52:35.714  8262  8312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:52:35.714  8262  8312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:52:35.714  8262  8312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 13:52:35.714  8262  8312 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecb88ea added. We now have 1 listener(s)
06-30 13:52:35.714  1115  3878 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-30 13:52:35.714  8262  8312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
06-30 13:52:35.714  8262  8312 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
06-30 13:52:35.714  8262  8312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 13:52:35.714  8262  8312 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:52:35.724  8262  8312 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb9cd51 added. We now have 1 listener(s)
06-30 13:52:35.724  8262  8312 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 13:52:35.724  1115  3104 D WifiService: New client listening to asynchronous messages
06-30 13:52:35.724  8262  8312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 13:52:35.724  8262  8312 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 13:52:35.724  8262  8312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 13:52:35.724  8262  8312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 13:52:35.724  8262  8312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 13:52:35.724  8262  8312 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 13:52:35.724  8262  8312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 13:52:35.724  1115  1135 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-30 13:52:35.724  8262  8312 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
06-30 13:52:35.724  8262  8312 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 13:52:35.724  8262  8312 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:52:35.724  8262  8312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:52:35.724  8262  8312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 13:52:35.724  8262  8312 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:52:35.724  8262  8312 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:52:35.724  8262  8312 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:52:35.724  8262  8312 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:52:35.724  8262  8312 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:52:35.724  8262  8312 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:52:35.724  8262  8312 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 13:52:35.724  8262  8312 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 13:52:35.744  8262  8262 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
06-30 13:52:35.744  1115  1115 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
06-30 13:52:35.874  1115  4150 D PMS     : acquireWL(28816190): PARTIAL_WAKE_LOCK  AsyncService 0x1 8316 10128 null
06-30 13:52:35.884  1115  3378 D PMS     : releaseWL(28816190): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
06-30 13:52:35.904  7536  7536 D AlarmReceiver: ACTION_RESTART_INTENT
06-30 13:52:35.914  7536  7536 D LocalBluetoothProfile: getPriorityOnValue = 100
06-30 13:52:35.914  7536  7536 D LocalBluetoothProfile: getPriorityOffValue = 0
06-30 13:52:35.914  7536  7536 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
06-30 13:52:35.914  7536  7536 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
06-30 13:52:35.914  3925  3925 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
06-30 13:52:35.914  3925  3925 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,06-30 13:52:35.914  3925  3925 D c       : Getting all permits...
06-30 13:52:35.914  3925  3925 D a       : Opening database...
,06-30 13:52:35.924  3925  3925 D a       : Opening database auth.proximity.permit_store...
06-30 13:52:35.924  3925  3925 D a       : Closing database...
,06-30 13:52:35.924  3445  3445 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-30 13:52:35.934  1115  1115 D PMS     : acquireWL(3173e2af): PARTIAL_WAKE_LOCK  *backup* 0x1 1115 1000 null
06-30 13:52:35.934  1115  1115 D PMS     : releaseWL(1543231e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,06-30 13:52:35.934  7536  8357 D HtcModeClient: start the htcmodeservice thread
06-30 13:52:35.934  7536  8357 D HtcModeClient: initCanAgent
,06-30 13:52:35.944  7536  8357 I CANMesgAgentLocalSocket: CANAgent Id = 0
,06-30 13:52:35.944  3445  8356 D LocationInitializer: Restart initialization of location
,06-30 13:52:35.944  7536  8357 D HtcModeClient: sense info: version = none, id = 2
06-30 13:52:35.944  7536  8357 D HtcModeClient: display info: width = 1080, height = 1776
06-30 13:52:35.944  7536  8357 D HtcModeClient: display info: mode = 10
,06-30 13:52:35.944  1115  3173 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,06-30 13:52:35.944  1115  3173 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
06-30 13:52:35.944  1115  3173 D PMS     : releaseWL(3173e2af): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,06-30 13:52:35.994  1115  1164 D PMS     : releaseHCC(d41573d): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
06-30 13:52:35.994  1115  1164 D PMS     : releaseHCC(394eb32): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,06-30 13:52:36.044  7536  7536 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
06-30 13:52:36.044  7536  7536 D HtcModeClient: connectState: BT_TURNON_BYME = false
06-30 13:52:36.044  7536  7536 D HtcModeClient: connectState: CONNECTION_READY = false
06-30 13:52:36.044  7536  7536 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
,06-30 13:52:36.044  7536  7536 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
06-30 13:52:36.044  7536  7536 D HtcModeClient: connectState: PHONE_PULGIN = false
06-30 13:52:36.044  7536  7536 D HtcModeClient: connectState: Force_AWAKE = false
06-30 13:52:36.044  7536  7536 D HtcModeClient: connectState: PHONE_PULGIN = true
06-30 13:52:36.044  7536  7536 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,06-30 13:52:36.444  8262  8348 W jxcore-log: Initializing JXcore engine,
06-30 13:52:36.444  8262  8348 W jxcore-log: JXcore engine is ready,
,06-30 13:52:36.504  8262  8348 W jxcore-log: Starting JXcore engine
,06-30 13:52:36.574  1115  3766 D PMS     : releaseWL(38dc0ad1): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,06-30 13:52:36.604  8262  8348 W jxcore-log: Platform android
06-30 13:52:36.604  8262  8348 W jxcore-log: 
06-30 13:52:36.604  8262  8348 W jxcore-log: Process ARCH arm
06-30 13:52:36.604  8262  8348 W jxcore-log: 
,06-30 13:52:36.794  8262  8348 I jxcore-log: JXcore Cordova bridge is ready!,
06-30 13:52:36.794  8262  8348 I jxcore-log: 
06-30 13:52:36.794  8262  8348 W jxcore-log: JXcore engine is started
,06-30 13:52:36.804  8262  8312 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 13:52:36.804  8262  8262 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 13:52:36.814  8262  8348 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
06-30 13:52:36.814  8262  8348 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-30 13:52:36.824  8262  8262 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
06-30 13:52:36.824  8262  8262 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-30 13:52:36.834  8262  8262 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,06-30 13:52:36.834  8262  8262 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
06-30 13:52:36.834  8262  8262 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-30 13:52:36.834  8262  8262 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:52:36.834  8262  8262 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:52:36.834  8262  8262 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-30 13:52:36.834  8262  8262 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2ecb88ea removed from the list
06-30 13:52:36.834  8262  8262 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:52:36.834  8262  8262 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fb9cd51 removed from the list
06-30 13:52:36.834  8262  8262 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:52:36.834  8262  8262 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,06-30 13:52:36.844  8262  8262 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-30 13:52:36.994  8359  8359 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
,06-30 13:52:36.994  8359  8359 W HTCLOG  : mask=0x18
,06-30 13:52:37.174  8359  8363 W HTCLOG  : use specified tag [cutils-trace], func [0].,
06-30 13:52:37.174  8359  8363 W HTCLOG  : mask=0x18
06-30 13:52:37.174  8359  8363 E cutils-trace: Error opening trace file: Permission denied (13)
,06-30 13:52:37.234  8359  8359 D CustomizationManager: ====startRecUseTime====,
06-30 13:52:37.234  8359  8359 D htc.customization.log.level:  is 
06-30 13:52:37.234  8359  8359 W CustomizationLogLevel: Level value is invalid, use default level 2
,06-30 13:52:37.314  8359  8359 D CustomizationManager:  Read ACC file spent 0.043 (s),
,06-30 13:52:37.324  8359  8359 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml,
,06-30 13:52:37.324  8359  8359 I CustomizationCIDLoader: Parsing tag category name = application
,06-30 13:52:37.324  8359  8359 I CustomizationCIDLoader: Parsing tag category name = system,
,06-30 13:52:37.324  8359  8359 I CustomizationCIDLoader: Parsing tag category name = Settings
06-30 13:52:37.324  8359  8359 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome,
06-30 13:52:37.324  8359  8359 I CustomizationCIDLoader: Parsing tag category name = ACC
,06-30 13:52:37.324  8359  8359 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
06-30 13:52:37.324  8359  8359 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000,
06-30 13:52:37.324  8359  8359 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
06-30 13:52:37.324  8359  8359 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
,06-30 13:52:37.334  8359  8359 I CustomizationCIDLoader: Parsing tag category name = AudioService
,06-30 13:52:37.334  8359  8359 D CustomizationManager:  Read CID file spent 0.101 (s)
06-30 13:52:37.334  8359  8359 D CustomizationManager:  All configurations done spent 0.101 (s)
,06-30 13:52:37.384  1115  3766 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8359, uid=2000,
,06-30 13:52:37.384  1115  1145 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg,
,06-30 13:52:37.384  1115  1145 D Process : killProcessQuiet, pid=8262
06-30 13:52:37.384  1115  1145 I ActivityManager: Killing 8262:com.test.thalitest/u0a142 (adj 9): stop com.test.thalitest
,06-30 13:52:37.384  1115  1145 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
,06-30 13:52:37.474  1115  3763 I ActivityManager: Recipient 8262
06-30 13:52:37.474  1115  3104 D WifiService: Client connection lost with reason: 4
,06-30 13:52:37.484   530   530 W HTCLOG  : use specified tag [Vector], func [0].
06-30 13:52:37.484   530   530 W HTCLOG  : mask=0x18
,06-30 13:52:37.494  1115  3763 W ActivityManager: Spurious death for ProcessRecord{119778a7 8262:com.test.thalitest/u0a142}, curProc for 8262: null
,06-30 13:52:37.494  1115  1166 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed
,06-30 13:52:37.604  3325  3325 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
06-30 13:52:37.604  3325  3325 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
,06-30 13:52:37.604  1115  4154 D PMS     : acquireWL(1c6b7154): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4250 10019 null
06-30 13:52:37.614  3715  4147 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
06-30 13:52:37.614  4250  4444 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 13:52:37.614  1115  3878 D PMS     : releaseWL(1c6b7154): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,06-30 13:52:37.614  1115  3093 W SystemReader: Cannot find grip_rejection_width, use default value instead
06-30 13:52:37.614  3715  4147 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
06-30 13:52:37.624  1115  3099 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
06-30 13:52:37.624  1115  3098 D PMS     : acquireWL(103396ec): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1115 1000 null
,06-30 13:52:37.624  3445  3445 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
06-30 13:52:37.624  3715  4147 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
,06-30 13:52:37.634  3738  8377 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,06-30 13:52:37.644  6502  6502 I art     : Explicit concurrent mark sweep GC freed 12293(759KB) AllocSpace objects, 2(40KB) LOS objects, 34% free, 3MB/5MB, paused 465us total 53.297ms
06-30 13:52:37.644  1115  3766 D PMS     : acquireWL(205a1169): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 3445 10019 null
06-30 13:52:37.644  3715  4147 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,06-30 13:52:37.654  3715  4147 E ExternalAccountType: Unsupported attribute readOnly,
,06-30 13:52:37.654  1115  1144 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
06-30 13:52:37.654  1115  3098 D PMS     : releaseWL(103396ec): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
06-30 13:52:37.664  3925  3925 I ConfigService: onCreate
06-30 13:52:37.664  3925  3925 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
06-30 13:52:37.664  1115  3099 V NetworkPolicy: writePolicyLocked()
,06-30 13:52:37.664  3528  3528 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
06-30 13:52:37.664  3445  3445 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,06-30 13:52:37.674  1115  3099 D NetworkPolicy: notifyPoliciesChangeLocked: no change
,06-30 13:52:37.674  1115  3099 V NetworkPolicy: updateNetworkEnabledLocked()
,06-30 13:52:37.674  1115  3099 V NetworkPolicy: updateNotificationsLocked()
,06-30 13:52:37.674  1115  1115 W PackageManager: Unable to load service info ResolveInfo{3ca3566f com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
06-30 13:52:37.674  1115  1115 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
06-30 13:52:37.674  1115  1115 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
,06-30 13:52:37.674  1115  1115 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,06-30 13:52:37.674  1115  1115 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 13:52:37.674  1115  1115 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825),
06-30 13:52:37.674  3925  3925 I ConfigService: onBind returning update interface
,06-30 13:52:37.694  3925  3925 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START,
06-30 13:52:37.694  3925  3925 I ConfigService: onBind returning config service
,06-30 13:52:37.704  1115  1144 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,06-30 13:52:37.704  1115  1115 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,06-30 13:52:37.714  1115  1134 I ActivityManager: Start proc 8379:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver
,06-30 13:52:37.714  3925  3925 I ConfigService: onDestroy
06-30 13:52:37.714  8379  8379 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 13:52:37.714  8379  8379 W HTCLOG  : mask=0x18
,06-30 13:52:37.724  1115  4152 D PMS     : acquireWL(6a16247): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3925 10019 null
,06-30 13:52:37.734  1115  4152 D PMS     : releaseWL(6a16247): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
,06-30 13:52:37.744  3558  3951 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
,06-30 13:52:37.744  3558  3951 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
06-30 13:52:37.754  8379  8379 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 13:52:37.754  8379  8379 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 13:52:37.764  3558  3558 I Launcher: Deferring update until onResume
06-30 13:52:37.764  3558  3558 D Launcher: waitUntilResume // bindAppsRemoved
,06-30 13:52:37.764  8379  8379 I MultiDex: VM with version 2.1.0 has multidex support
06-30 13:52:37.764  8379  8379 I MultiDex: install
06-30 13:52:37.764  8379  8379 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 13:52:37.784  3558  3558 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
,06-30 13:52:37.784  8379  8379 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
06-30 13:52:37.784  3558  3558 I ThreadedRenderer: Defer allocateBuffers to drawing time
,06-30 13:52:37.794  8379  8379 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,06-30 13:52:37.804  3445  8403 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,06-30 13:52:37.804  3445  8403 D AccountUtils: Clearing selected account for com.test.thalitest
,06-30 13:52:37.814  1115  1166 I art     : Explicit concurrent mark sweep GC freed 35708(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 15MB/23MB, paused 1.834ms total 195.047ms,
06-30 13:52:37.814  1115  3798 I art     : WaitForGcToComplete blocked for 39.547ms for cause Explicit
,06-30 13:52:37.824  1115  4164 I ActivityManager: Start proc 8406:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver,
,06-30 13:52:37.834  3495  3495 D Nfc-Utils: isNxpCodebase: isNxp=false
,06-30 13:52:37.844  8406  8406 W HTCLOG  : use specified tag [FDManager], func [0].
,06-30 13:52:37.844  8406  8406 W HTCLOG  : mask=0x18
,06-30 13:52:37.854  8359  8359 I art     : System.exit called, status: 0,
06-30 13:52:37.854  8359  8359 W HTCLOG  : use specified tag [Vector], func [0].
06-30 13:52:37.854  8359  8359 W HTCLOG  : mask=0x18
06-30 13:52:37.864  7847  8430 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,06-30 13:52:37.904  1115  4152 D PMS     : acquireWL(d17036): PARTIAL_WAKE_LOCK  Icing 0x1 3445 10019 null
06-30 13:52:37.904  3445  8434 I PeopleContactsSync: CP2 sync disabled
,06-30 13:52:37.904  3445  6727 I Icing   : doRemovePackageData com.test.thalitest
,06-30 13:52:37.904  1115  3164 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=3445, uid=10019, userID:0
,06-30 13:52:37.914  1115  3766 D PMS     : releaseWL(d17036): PARTIAL_WAKE_LOCK  Icing 0x1 null,
,06-30 13:52:37.924  1115  3378 D Process : killProcessQuiet, pid=7501,
06-30 13:52:37.924  1115  3378 I ActivityManager: Killing 7501:com.htc.sdm/u0a61 (adj 15): empty #17
06-30 13:52:37.924  1115  3378 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,06-30 13:52:37.974  1115  3798 I art     : Explicit concurrent mark sweep GC freed 5680(303KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/22MB, paused 2.263ms total 159.483ms,
,06-30 13:52:38.004  1115  3573 I ActivityManager: Recipient 7501,
,06-30 13:52:38.034  3715  3715 E PackageActionReceiver: ACTION_PACKAGE_REMOVED
,06-30 13:52:38.044  3445  8433 W GmsApplication: Using Auth Proxy for data requests.
,06-30 13:52:38.044  3646  8438 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,06-30 13:52:38.054  7536  8357 I HtcModeClient: handler message = 4011
06-30 13:52:38.054  7536  8357 D HtcModeClient: getConnectionCheckCount first 0
06-30 13:52:38.054  7536  8357 D HtcModeClient: getConnectionCheckCount count = 7
06-30 13:52:38.054  7536  8357 E HtcModeClient: Check connection and retry 8 times.
,06-30 13:52:38.054  3445  8433 W GmsApplication: Using Auth Proxy for data requests.
,06-30 13:52:38.054  7536  8357 D HtcModeClient: setConnectionCheckCount count = 8
,06-30 13:52:38.054  7536  8357 D HtcModeClient: setupRestart delayedTime = 3000
,06-30 13:52:38.064  3646  8438 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed,
06-30 13:52:38.064  3558  3558 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED,
06-30 13:52:38.064  3558  3558 I ContextualWidget: package com.test.thalitest removed
,06-30 13:52:38.064  3558  3975 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
,06-30 13:52:38.074  7536  7536 D HtcModeClient: setBtPriority priority = on
06-30 13:52:38.074  7536  7536 D HtcModeClient: unbindBlueToothService
06-30 13:52:38.074  7536  7536 D HtcModeClient: Don't start project servcice
06-30 13:52:38.074  7536  7536 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
06-30 13:52:38.074  7536  7536 D HtcModeClient: connectState: CONNECTION_READY = false
06-30 13:52:38.074  7536  7536 D SilentMusic: call stop
06-30 13:52:38.074  7536  7536 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,06-30 13:52:38.074  7536  8358 W CANMesgAgentLocalSocket: read the terminate packet, so break
,06-30 13:52:38.074  3558  8439 I ContextualWidget: com.test.thalitest is not installed
06-30 13:52:38.084  3558  8439 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,06-30 13:52:38.084  1115  3878 I ActivityManager: Start proc 8440:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
,06-30 13:52:38.094  7536  7536 D HtcModeClient: onDestroy
,06-30 13:52:38.094  1115  1135 I ActivityManager: Killing 7673:com.google.android.gm/u0a97 (adj 15): empty #17
06-30 13:52:38.094  1115  1135 D Process : killProcessQuiet, pid=7673
,06-30 13:52:38.094  1115  1135 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 ,
06-30 13:52:38.094  8440  8440 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 13:52:38.094  8440  8440 W HTCLOG  : mask=0x18
,06-30 13:52:38.104  3558  3975 I ContextualWidget: MFU.onDownloadDataSetChanged
06-30 13:52:38.104  3558  3975 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
06-30 13:52:38.104  3558  3558 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId c359e85c-8616-4808-b323-1a584fca0bfb, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
06-30 13:52:38.104  3558  3558 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId c359e85c-8616-4808-b323-1a584fca0bfb, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,06-30 13:52:38.154  1115  3164 I ActivityManager: Recipient 7673,
,06-30 13:52:38.234  8081  8096 E AndroidHttpClient: Leak found
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 13:52:38.234  8081  8096 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,06-30 13:52:38.274  3445  8419 W DriveInitializer: Awaiting to be initialized
,06-30 13:52:38.274  3445  8463 W DriveInitializer: Background init thread started
,06-30 13:52:38.284  3445  8463 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock43] disk I/O error
,06-30 13:52:38.284  3445  8463 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
,06-30 13:52:38.284  3445  8463 W HTCLOG  : mask=0x18
06-30 13:52:38.284  3445  8463 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5598fc1e90
,06-30 13:52:38.284  3445  8463 E DocListDatabase: Failed to delete from ContentFileDeletionLock43
06-30 13:52:38.284  3445  8463 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 13:52:38.284  3445  8463 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 13:52:38.284  3445  8463 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
06-30 13:52:38.284  3445  8463 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 13:52:38.284  3445  8463 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 13:52:38.284  3445  8463 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
06-30 13:52:38.284  3445  8463 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
06-30 13:52:38.284  3445  8463 E DocListDatabase: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
06-30 13:52:38.284  3445  8463 E DocListDatabase: 	at com.google.android.gms.drive.v.run(SourceFile:69)
,06-30 13:52:38.284  3445  8463 W DriveInitializer: Background init thread ended
06-30 13:52:38.284  3445  8419 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
06-30 13:52:38.284  3445  8419 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x5598fc1e90
,06-30 13:52:38.284  3445  8419 E DriveAsyncService: disk I/O error (code 3850)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.m(SourceFile:501)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:495)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1406)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.ao.a(SourceFile:16)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.284  3445  8419 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.294  3445  8463 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
06-30 13:52:38.294  3445  8463 E AndroidRuntime: Process: com.google.android.gms, PID: 3445
06-30 13:52:38.294  3445  8463 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 13:52:38.294  3445  8463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 13:52:38.294  3445  8463 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
06-30 13:52:38.294  3445  8463 E AndroidRuntime: 	,at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 13:52:38.294  3445  8463 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
,06-30 13:52:38.294  3445  8463 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
06-30 13:52:38.294  3445  8463 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
06-30 13:52:38.294  3445  8463 E AndroidRuntime: 	,at com.google.android.gms.drive.database.d.i(SourceFile:1103)
06-30 13:52:38.294  3445  8463 E AndroidRuntime: 	at com.google.android.gms.drive.v.run(SourceFile:69)
,06-30 13:52:38.294  1115  3164 E ActivityManager: App crashed! Process: com.google.android.gms
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: Can't write: system_app_crash,
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.294  1115  8465 E DropBoxManagerService: 	... 5 more
06-30 13:52:38.294  3445  8463 D Process : killProcess, pid=3445
06-30 13:52:38.294  3445  8463 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
06-30 13:52:38.294  3445  8463 W HTCLOG  : use specified tag [Process], func [0].
06-30 13:52:38.294  3445  8463 W HTCLOG  : mask=0x18
,06-30 13:52:38.334  1115  3164 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
06-30 13:52:38.334  8440  8440 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
,06-30 13:52:38.334  8440  8440 D IdefixUninstallListener: package_removed = com.test.thalitest
,06-30 13:52:38.364  1115  4164 I ActivityManager: Recipient 3445
06-30 13:52:38.364  1115  3380 D PMS     : handleWLDeath(12fa6e54): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
,06-30 13:52:38.364  1115  1135 D PMS     : handleWLDeath(205a1169): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
06-30 13:52:38.364  1115  4164 I ActivityManager: Process com.google.android.gms (pid 3445) has died
06-30 13:52:38.364  1115  4164 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms
06-30 13:52:38.364  1115  4164 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
,06-30 13:52:38.374  8440  8440 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
06-30 13:52:38.374  8440  8440 W HTCLOG  : mask=0x18
,06-30 13:52:38.374  8440  8440 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.,
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752),
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54),
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43),
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: ,	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 13:52:38.374  8440  8440 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 13:52:38.374  8440  8440 W System.err: java.sql.SQLException: Getting a writable database from helper a@38988deb failed
,06-30 13:52:38.384  1115  4152 I ActivityManager: Killing 7373:com.google.android.music:main/u0a115 (adj 15): empty #17
06-30 13:52:38.374  8440  8440 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
06-30 13:52:38.374  8440  8440 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
,06-30 13:52:38.374  8440  8440 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
06-30 13:52:38.374  8440  8440 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
06-30 13:52:38.374  8440  8440 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
,06-30 13:52:38.374  8440  8440 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
06-30 13:52:38.374  8440  8440 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
,06-30 13:52:38.374  8440  8440 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 13:52:38.374  8440  8440 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,06-30 13:52:38.374  8440  8440 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:52:38.374  8440  8440 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 13:52:38.374  8440  8440 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 13:52:38.374  8440  8440 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.374  8440  8440 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219),
06-30 13:52:38.374  8440  8440 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.374  8440  8440 W System.err: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
,06-30 13:52:38.374  8440  8440 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.374  8440  8440 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.374  8440  8440 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
06-30 13:52:38.374  8440  8440 W System.err: 	... 15 more
06-30 13:52:38.384  1115  4152 D Process : killProcessQuiet, pid=7373
,06-30 13:52:38.384  1115  4152 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,06-30 13:52:38.434  3558  3880 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak,
,06-30 13:52:38.484  1115  4154 I ActivityManager: Recipient 7373
06-30 13:52:38.484  1115  3573 D MediaRouterService: Client com.google.android.music (pid 7373): Died!
,06-30 13:52:38.494  6502  8466 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE,
,06-30 13:52:38.524  1115  3164 I ActivityManager: Start proc 8467:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,06-30 13:52:38.534  8467  8467 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 13:52:38.534  8467  8467 W HTCLOG  : mask=0x18,
,06-30 13:52:38.544  6502  8466 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 13:52:38.544  6502  8466 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 13:52:38.544  6502  8466 W HTCLOG  : mask=0x18
06-30 13:52:38.544  6502  8466 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x5598de46f0
,06-30 13:52:38.554  6502  8466 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,06-30 13:52:38.554  6502  8466 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
06-30 13:52:38.554  6502  8466 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6502
06-30 13:52:38.554  6502  8466 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
,06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.554  6502  8466 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:52:38.554  1115  3571 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: Can't write: system_app_crash
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: 	,at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.564  1115  8489 E DropBoxManagerService: 	... 5 more
06-30 13:52:38.564  6502  8466 D Process : killProcess, pid=6502
06-30 13:52:38.564  6502  8466 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
06-30 13:52:38.564  6502  8466 W HTCLOG  : use specified tag [Process], func [0].
06-30 13:52:38.564  6502  8466 W HTCLOG  : mask=0x18
,06-30 13:52:38.574  8467  8467 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 ,
,06-30 13:52:38.584  1115  3380 D PMS     : acquireWL(2b5f9b10): PARTIAL_WAKE_LOCK  AsyncService 0x1 8316 10128 null
,06-30 13:52:38.594  8467  8491 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 13:52:38.594  8467  8491 W HTCLOG  : mask=0x18
06-30 13:52:38.594  8467  8491 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73]
06-30 13:52:38.594  8467  8491 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.android.keychain/databases/grants.db) - ,
06-30 13:52:38.594  8467  8491 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 13:52:38.594  8467  8491 W HTCLOG  : mask=0x18
06-30 13:52:38.594  8467  8491 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.android.keychain/databases/grants.db, flag: 6, ret: 14
06-30 13:52:38.594  8467  8491 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
,06-30 13:52:38.594  8467  8491 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.594  8467  8491 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.594  1115  1134 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 13:52:38.594  8467  8491 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
06-30 13:52:38.594  8467  8491 E AndroidRuntime: Process: com.android.keychain, PID: 8467
06-30 13:52:38.594  8467  8491 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468),
,06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
,06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
,06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
,06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.594  8467  8491 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 13:52:38.594  1115  3571 D PMS     : releaseWL(2b5f9b10): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
06-30 13:52:38.594  1115  1134 E ActivityManager: App crashed! Process: com.android.keychain
06-30 13:52:38.594  8196  8196 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
06-30 13:52:38.594  8196  8196 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
06-30 13:52:38.594  1115  1134 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.594  1115  1134 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,06-30 13:52:38.594  1115  1134 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.594  1115  1134 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.594  1115  1134 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.594  1115  1134 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 13:52:38.594  1115  1134 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 13:52:38.594  1115  1134 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 13:52:38.594  1115  1134 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
06-30 13:52:38.594  1115  1134 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 13:52:38.594  1115  1134 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 13:52:38.604  1115  1134 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 13:52:38.604  1115  1134 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 13:52:38.604  1115  1134 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 13:52:38.604  1115  1134 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 13:52:38.604  1115  1134 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:38.604  1115  1134 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.604  1115  1134 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.604  1115  1134 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.604  1115  1134 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.604  1115  1134 W System.err: 	... 14 more
06-30 13:52:38.604  1115  1134 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.604  1115  1134 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.604  1115  1134 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.604  1115  1134 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.604  1115  1134 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.604  1115  1134 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 13:52:38.604  1115  1134 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 13:52:38.614  1115  3164 I ActivityManager: Start proc 8493:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
06-30 13:52:38.604  1115  1134 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 13:52:38.604  1115  1134 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 13:52:38.604  1115  1134 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
,06-30 13:52:38.604  1115  1134 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 13:52:38.604  1115  1134 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 13:52:38.604  1115  1134 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 13:52:38.604  1115  1134 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 13:52:38.604  1115  1134 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 13:52:38.604  1115  1134 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:38.604  1115  1134 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.604  1115  1134 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.604  1115  1134 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.604  1115  1134 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.604  1115  1134 W System.err: 	... 14 more
06-30 13:52:38.604  8196  8196 I DeviceManagement: WorkflowService: Starting workflow service
06-30 13:52:38.604  8196  8492 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@397faffb] args=[Bundle[mParcelledData.dataSize=112]]
06-30 13:52:38.604  8196  8492 I DeviceManagement: PackageUpdateWorkflow: ==================================================
06-30 13:52:38.604  8196  8492 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
06-30 13:52:38.604  8196  8492 I DeviceManagement: PackageUpdateWorkflow: ==================================================
06-30 13:52:38.614  8196  8492 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
06-30 13:52:38.614  1115  3617 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.614  1115  3617 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.614  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.614  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.614  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.614  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 13:52:38.614  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 13:52:38.614  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 13:52:38.614  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 13:52:38.614  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 13:52:38.614  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 13:52:38.614  1115  3617 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.614  1115  3617 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.614  1115  3617 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.614  1115  3617 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.614  1115  3617 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.614  1115  3617 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.624  1115  8506 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 13:52:38.624  1115  8506 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467287558625.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 13:52:38.624  1115  8506 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.624  1115  8506 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.624  1115  8506 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:52:38.624  1115  8506 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 13:52:38.624  1115  8506 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:38.624  1115  8506 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.624  1115  8506 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.624  1115  8506 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.624  1115  8506 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.624  1115  8506 E ErrorReport: 	... 4 more
06-30 13:52:38.614  1115  3617 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.614  1115  3617 W System.err: 	... 12 more
06-30 13:52:38.624  8493  8493 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 13:52:38.624  8493  8493 W HTCLOG  : mask=0x18
06-30 13:52:38.624  8467  8491 D Process : killProcess, pid=8467
06-30 13:52:38.624  8467  8491 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 13:52:38.624  8467  8491 W HTCLOG  : use specified tag [Process], func [0].
06-30 13:52:38.624  8467  8491 W HTCLOG  : mask=0x18
06-30 13:52:38.634  1115  4154 I ActivityManager: Recipient 6502
06-30 13:52:38.634  1115  4154 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6502) has died
06-30 13:52:38.634  1115  3104 D WifiService: Client connection lost with reason: 4
06-30 13:52:38.634  1115  4154 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 20729ms
06-30 13:52:38.634  1115  4154 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 30729ms
06-30 13:52:38.644  8493  8493 W ContextImpl: Unable to create files subdir /data/data/com.android.documentsui/cache
06-30 13:52:38.644  8493  8493 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,06-30 13:52:38.644  8196  8492 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
06-30 13:52:38.654  8196  8515 I DeviceManagement: SessionStateController: Checking invariants...
06-30 13:52:38.684  8493  8493 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 13:52:38.684  1115  4150 I ActivityManager: Recipient 8467
06-30 13:52:38.684  8493  8493 W HTCLOG  : mask=0x18
06-30 13:52:38.684  1115  4150 I ActivityManager: Process com.android.keychain (pid 8467) has died
06-30 13:52:38.684  8493  8493 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73]
06-30 13:52:38.684  1115  4150 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 30684ms
06-30 13:52:38.684  8493  8493 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.android.documentsui/databases/recents.db) - 
06-30 13:52:38.684  8493  8493 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 13:52:38.684  8493  8493 W HTCLOG  : mask=0x18
06-30 13:52:38.684  8493  8493 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.android.documentsui/databases/recents.db, flag: 6, ret: 14
06-30 13:52:38.684  8493  8493 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at com.andr,oid.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 13:52:38.684  8493  8493 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,06-30 13:52:38.694  8493  8493 E AndroidRuntime: FATAL EXCEPTION: main
06-30 13:52:38.694  8493  8493 E AndroidRuntime: Process: com.android.documentsui, PID: 8493
06-30 13:52:38.694  8493  8493 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	,at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	,at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
,06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: ,	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 13:52:38.694  8493  8493 E AndroidRuntime: ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 13:52:38.694  8493  8493 E AndroidRuntime: 	... 9 more
06-30 13:52:38.694  1115  3378 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 13:52:38.694  1115  3378 E ActivityManager: App crashed! Process: com.android.documentsui
06-30 13:52:38.694  1115  8517 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 13:52:38.694  1115  8517 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467287558705.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 13:52:38.694  1115  8517 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.694  1115  8517 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.694  1115  8517 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:52:38.694  1115  8517 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 13:52:38.694  1115  8517 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:38.694  1115  8517 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.694  1115  8517 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.694  1115  8517 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.694  1115  8517 E ErrorReport: 	,at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.694  1115  8517 E ErrorReport: 	... 4 more
,06-30 13:52:38.694  1115  3378 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.704  1115  3498 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 13:52:38.694  1115  3378 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.694  1115  3378 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.714  1115  8518 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 13:52:38.714  1115  8518 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467287558717.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 13:52:38.714  1115  8518 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.714  1115  8518 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.714  1115  8518 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:52:38.714  1115  8518 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 13:52:38.714  1115  8518 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:38.714  1115  8518 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.714  1115  8518 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
,06-30 13:52:38.714  1115  8518 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.714  1115  8518 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.714  1115  8518 E ErrorReport: 	... 4 more
06-30 13:52:38.694  1115  3378 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,06-30 13:52:38.694  1115  3378 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
,06-30 13:52:38.694  1115  3378 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
,06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
,06-30 13:52:38.694  1115  3378 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 13:52:38.694  1115  3378 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,06-30 13:52:38.694  1115  3378 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.694  1115  3378 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.694  1115  3378 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.694  1115  3378 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.694  1115  3378 W System.err: 	... 14 more
06-30 13:52:38.694  1115  3378 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.694  1115  3378 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.694  1115  3378 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.694  1115  3378 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.694  1115  3378 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 13:52:38.694  1115  3378 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 13:52:38.694  1115  3378 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 13:52:38.694  1115  3378 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:38.694  1115  3378 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.694  1115  3378 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.694  1115  3378 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.694  1115  3378 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.694  1115  3378 W System.err: 	... 14 more
06-30 13:52:38.714  1115  3571 I ActivityManager: Recipient 8493
06-30 13:52:38.694  1115  3617 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.694  5617  5731 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
06-30 13:52:38.694  1115  3617 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.694  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.694  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.694  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.704  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 13:52:38.704  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPre,ference.java:86)
06-30 13:52:38.704  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 13:52:38.704  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 13:52:38.704  5617  5731 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 13:52:38.704  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 13:52:38.704  5617  5731 W HTCLOG  : mask=0x18
06-30 13:52:38.704  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 13:52:38.704  5617  5731 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x5598e02320
06-30 13:52:38.704  1115  3617 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.704  1115  3617 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.704  1115  3617 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.704  1115  3617 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.704  1115  3617 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.704  1115  3617 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.704  1115  3617 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.704  1115  3617 W System.err: 	... 12 more
06-30 13:52:38.704  8493  8493 D Process : killProcess, pid=8493
06-30 13:52:38.704  8493  8493 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 13:52:38.704  8493  8493 W HTCLOG  : use specified tag [Process], func [0].
06-30 13:52:38.704  8493  8493 W HTCLOG  : mask=0x18
06-30 13:52:38.704  5617  5731 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
06-30 13:52:38.704  5617  5731 E AndroidRuntime: Process: android.process.media, PID: 5617
06-30 13:52:38.704  5617  5731 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 13:52:38.704  5617  5731 E Androi,dRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.704  5617  5731 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.704  1115  3498 E ActivityManager: App crashed! Process: android.process.media
06-30 13:52:38.724  1115  1145 I ActivityManager: Start proc 8519:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
06-30 13:52:38.704  1115  3498 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.704  1115  3498 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.704  1115  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.704  1115  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.704  1115  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 13:52:38.704  1115  3498 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 13:52:38.704  1115  3498 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:38.704  1115  3498 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.704  1115  3498 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.704  1115  3498 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.704  1115  3498 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.704  1115  3498 W System.err: 	... 14 more
06-30 13:52:38.704  1115  3498 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.704  1115  3498 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.704  1115  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.704  1115  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.704  1115  3498 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 13:52:38.704  1115  3498 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 13:52:38.704  1115  3498 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 13:52:38.704  1115  3498 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:38.704  1115  3498 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.704  1115  3498 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.704  1115  3498 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.704  1115  3498 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.704  1115  3498 W System.err: 	... 14 more
06-30 13:52:38.704  1115  3617 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.714  1115  3617 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.714  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.714  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.714  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.714  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 13:52:38.714  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 13:52:38.714  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 13:52:38.714  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 13:52:38.714  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 13:52:38.714  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 13:52:38.714  1115  3617 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.714  1115  3617 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.714  1115  3617 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.714  1115  3617 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.714  1115  3617 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.714  1115  3617 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.714  1115  3617 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.714  1115  3617 W System.err: 	... 12 more
06-30 13:52:38.724  5617  5731 D Process : killProcess, pid=5617
06-30 13:52:38.724  5617  5731 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 13:52:38.724  5617  5731 W HTCLOG  : use specified tag [Process], func [0].
06-30 13:52:38.724  5617  5731 W HTCLOG  : mask=0x18
06-30 13:52:38.724  8519  8519 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 13:52:38.724  8519  8519 W HTCLOG  : mask=0x18
,06-30 13:52:38.764  8196  8515 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 13:52:38.764  8196  8515 W HTCLOG  : mask=0x18
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 13:52:38.764  8196  8515 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:38.774  1115  3571 I ActivityManager: Process com.android.documentsui (pid 8493) has died
06-30 13:52:38.774   492   492 E lowmemorykiller: Error writing /proc/5617/oom_score_adj; errno=22
06-30 13:52:38.774  1115  3571 W HTCLOG  : use specified tag [JavaBinder], func [0].
06-30 13:52:38.774  1115  3571 W HTCLOG  : mask=0x18
06-30 13:52:38.774  1115  3571 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
06-30 13:52:38.784  8196  8515 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.784  8196  8492 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.784  8196  8492 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.784  8196  8492 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.784  8196  8492 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@397faffb]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.784  8196  8492 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.784  8196  8196 I DeviceManagement: WorkflowService: Stopping workflow service
,06-30 13:52:38.804  8519  8519 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
06-30 13:52:38.814  1115  3878 I ActivityManager: Recipient 5617
06-30 13:52:38.814  1115  3878 I ActivityManager: Process android.process.media (pid 5617) has died
06-30 13:52:38.814  1115  3878 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 30553ms
06-30 13:52:38.814  3325  3351 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
06-30 13:52:38.814  3258  3258 I NotificationStackScrollLayout: setBlockTouchEnabled:false
06-30 13:52:38.824  8519  8541 D PowerUtils: getUserIdOfProcess, curUserId = 0
06-30 13:52:38.824  8519  8541 D PowerUtils: isRunningUnderOwner, isOwner = true
06-30 13:52:38.824  1115  3763 I ActivityManager: Start proc 8542:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
06-30 13:52:38.824  8519  8541 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
06-30 13:52:38.834  8542  8542 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 13:52:38.834  8542  8542 W HTCLOG  : mask=0x18
06-30 13:52:38.834  8519  8541 D PowerUsageService: removed uid = 10142
,06-30 13:52:38.834  8519  8541 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 13:52:38.834  8519  8541 W HTCLOG  : mask=0x18
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190),
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.844  8519  8541 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
06-30 13:52:38.844  8519  8541 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 8519
06-30 13:52:38.844  8519  8541 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.ja,va:223)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.844  8519  8541 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.844  1115  3164 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 13:52:38.844  1115  3164 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
06-30 13:52:38.844  1115  8563 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 13:52:38.844  1115  8563 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467287558855.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 13:52:38.844  1115  8563 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.844  1115  8563 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.844  1115  8563 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:52:38.844  1115  8563 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 13:52:38.844  1115  8563 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:38.844  1115  8563 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.844  1115  8563 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.844  1115  8563 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.844  1115  8563 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.844  1115  8563 E ErrorReport: 	... 4 more
06-30 13:52:38.844  1115  3164 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.844  1115  3164 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.844  1115  3164 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.844  1115  3164 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.844  1115  3164 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 13:52:3,8.844  1115  3164 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 13:52:38.844  1115  3164 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 13:52:38.844  1115  3164 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:38.844  1115  3164 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.844  1115  3164 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.844  1115  3164 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.844  1115  3164 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.844  1115  3164 W System.err: 	... 14 more
06-30 13:52:38.844  1115  3164 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.844  1115  3164 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.844  1115  3164 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.844  1115  3164 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.844  1115  3164 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 13:52:38.844  1115  3164 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 13:52:38.844  1115  3164 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 13:52:38.844  1115  3164 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:38.844  1115  3164 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.844  1115  3164 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.844  1115  3164 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.844  1115  3164 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.844  1115  3164 W System.err: 	... 14 more
06-30 13:52:38.844  1115  3617 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.844  1115  3617 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.844  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.844  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.844  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.844  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 13:52:38.844  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 13:52:38.844  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 13:52:38.844  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 13:52:38.844  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 13:52:38.844  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 13:52:38.844  1115  3617 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.844  1115  3617 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.844  1115  3617 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.844  1115  3617 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.854  1115  3617 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.854  1115  3617 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.854  1115  3617 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.854  1115  3617 W System.err: 	... 12 more
06-30 13:52:38.854  8519  8541 D Process : killProcess, pid=8519
06-30 13:52:38.854  8519  8541 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 13:52:38.854  8519  8541 W HTCLOG  : use specified tag [Process], func [0].
06-30 13:52:38.854  8519  8541 W HTCLOG  : mask=0x18
,06-30 13:52:38.894  8542  8564 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 13:52:38.894  8542  8564 W HTCLOG  : mask=0x18
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at com.htc.,updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: ,	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.904  8542  8564 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
06-30 13:52:38.904  8542  8564 E AndroidRuntime: Process: com.htc.updater, PID: 8542
06-30 13:52:38.904  8542  8564 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.904  8542  8564 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.904  1115  3378 I ActivityManager: Recipient 8519
06-30 13:52:38.904  1115  3763 E ActivityManager: App crashed! Process: com.htc.updater
06-30 13:52:38.904  1115  3378 I ActivityManager: Process com.htc.htcpowermanager:remote (pid 8519) has died
06-30 13:52:38.904  8542  8542 V UpdaterAPK | DownloadService: Service onStart
06-30 13:52:38.904  1115  3378 W ActivityManager: Scheduling restart of crashed service com.htc.htcpowermanager/.battery.PowerUsageService in 40463ms
06-30 13:52:38.904  1115  3763 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.904  1115  3763 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,06-30 13:52:38.904  1115  3763 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.914  1115  8567 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 13:52:38.914  1115  8567 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467287558917.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 13:52:38.914  1115  8567 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.914  1115  8567 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.914  1115  8567 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:52:38.914  1115  8567 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 13:52:38.914  1115  8567 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:38.914  1115  8567 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.914  1115  8567 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.914  1115  8567 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.914  1115  8567 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.914  1115  8567 E ErrorReport: 	... 4 more
,06-30 13:52:38.904  1115  3763 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.924  1115  3164 I ActivityManager: Start proc 8568:com.google.android.gms/u0a19 for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver
06-30 13:52:38.904  1115  3763 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.904  1115  3763 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
,06-30 13:52:38.904  1115  3763 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
,06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 13:52:38.904  1115  3763 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
,06-30 13:52:38.904  1115  3763 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:38.904  1115  3763 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.904  8542  8565 V UpdaterAPK | DownloadService: Updating for startId 1
06-30 13:52:38.904  1115  3763 W System.err: 	at libcore.io.Posix.open(Native Method)
,06-30 13:52:38.904  1115  3763 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.904  1115  3763 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.904  1115  3763 W System.err: 	... 14 more
06-30 13:52:38.904  1115  3763 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.904  1115  3763 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.904  1115  3763 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.904  1115  3763 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.904  1115  3763 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 13:52:38.904  1115  3763 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 13:52:38.904  1115  3763 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 13:52:38.904  1115  3763 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 13:52:38.904  1115  3763 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.904  1115  3763 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.904  1115  3763 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.904  1115  3763 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.904  1115  3763 W System.err: 	... 14 more
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.,904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:98)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.904  8542  8565 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: Couldn't open downloads.db for writing (will try read-only):
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelp,er.java:187)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:98)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.904  8542  8565 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.914  1115  3617 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 13:52:38.914  1115  3617 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:38.914  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:38.914  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 13:52:38.914  1115  3617 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 13:52:38.914  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 13:52:38.914  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 13:52:38.914  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 13:52:38.914  8542  8564 D Process : killProcess, pid=8542
06-30 13:52:38.914  8542  8564 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 13:52:38.914  8542  8564 W HTCLOG  : use specified tag [Process], func [0].
06-30 13:52:38.914  8542  8564 W HTCLOG  : mask=0x18
06-30 13:52:38.914  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 13:52:38.914  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 13:52:38.914  1115  3617 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 13:52:38.914  1115  3617 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:38.914  1115  3617 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 13:52:38.914  1115  3617 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 13:52:38.914  3925  3925 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
06-30 13:52:38.914  1115  3617 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:38.914  1115  3617 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:38.914  1115  3617 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:38.914  1115  3617 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:38.914  1115  3617 W System.err: 	... 12 more
06-30 13:52:38.934  8568  8568 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 13:52:38.934  8568  8568 W HTCLOG  : mask=0x18
06-30 13:52:38.944   560   560 I art     : Explicit concurrent mark sweep GC freed 8672(369KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 123us total 19.787ms
06-30 13:52:38.954  8568  8568 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 13:52:38.954  8568  8568 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
06-30 13:52:38.964   560   560 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 112us total 18.122ms
06-30 13:52:38.984  8568  8568 I MultiDex: VM with version 2.1.0 has multidex support
06-30 13:52:38.984  8568  8568 I MultiDex: install
06-30 13:52:38.984  8568  8568 I MultiDex: VM has multidex support, MultiDex support library is disabled.
06-30 13:52:38.984   560   560 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 104us total 16.794ms
,06-30 13:52:38.994  1115  4152 I ActivityManager: Recipient 8542
06-30 13:52:38.994  1115  4152 I ActivityManager: Process com.htc.updater (pid 8542) has died
06-30 13:52:38.994  1115  4152 W ActivityManager: Scheduling restart of crashed service com.htc.updater/.download.DownloadService in 1000ms
,06-30 13:52:39.044  8568  8568 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application',
,06-30 13:52:39.094  8568  8592 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,06-30 13:52:39.094  8568  8592 W HTCLOG  : mask=0x18
,06-30 13:52:39.094  8568  8592 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at c,om.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:225)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	,at com.google.android.gms.reminders.a.a.a(SourceFile:62)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:37)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
,06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,06-30 13:52:39.094  8568  8592 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: Couldn't open reminders.db for writing (will try read-only):
,06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
,06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
,06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelp,er: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:225)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.a.a(SourceFile:62)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:37)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 13:52:39.104  8568  8592 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,06-30 13:52:39.104  8568  8592 W SQLiteOpenHelper: Opened reminders.db in read-only mode
,06-30 13:52:39.114  8568  8594 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
,06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at com.go,ogle.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 13:52:39.114  8568  8594 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #2,
06-30 13:52:39.114  8568  8594 E AndroidRuntime: Process: com.google.android.gms, PID: 8568
06-30 13:52:39.114  8568  8594 E AndroidRuntime: java.lang.RuntimeException: An error occured while executing doInBackground()
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,06-30 13:52:39.114  8568  8594 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-30 13:52:39.114  8568  8594 E AndroidRuntime: 	... 4 more
06-30 13:52:39.124  1115  4154 E ActivityManager: App crashed! Process: com.google.android.gms
06-30 13:52:39.124  1115  4154 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
06-30 13:52:39.124  1115  4154 D Process : killProcessQuiet, pid=8568
06-30 13:52:39.124  1115  4154 I ActivityManager: Killing 8568:com.google.android.gms/u0a19 (adj 0): crash
06-30 13:52:39.124  1115  4154 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12158 
,06-30 13:52:39.134  1115  8596 E DropBoxManagerService: Can't write: system_app_crash
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
,06-30 13:52:39.134  1115  8596 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 13:52:39.134  1115  8596 E DropBoxManagerService: 	... 5 more
,06-30 13:52:39.244  3558  3951 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
```
