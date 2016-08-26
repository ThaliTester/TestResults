#### Test 8286536244f8192_thali04_HTC-HTC One M9 Logs


```
--------- beginning of main
08-26 15:03:41.817  3568  3978 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
08-26 15:03:41.817  3568  3978 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1e542b11 +
08-26 15:03:41.817  3568  3978 I Prism.WidgetManager: onLoadItems() +
08-26 15:03:41.927  4007  6919 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
08-26 15:03:41.987  4007  6919 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-26 15:03:42.017  3547  3735 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
08-26 15:03:42.017  3547  3735 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
08-26 15:03:42.027  3547  4195 D PhoneApp: EVENT_QUERY_MO_PACKAGES
08-26 15:03:42.027  3547  4195 D PhoneApp: -- N1 =0
08-26 15:03:42.027  3547  4195 D PhoneApp: -- N2 =0
08-26 15:03:42.027  3547  4195 D PhoneApp: -- N3 =0
08-26 15:03:42.047  4007  6919 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
--------- beginning of system
08-26 15:03:42.057  1111  3519 D PMS     : releaseWL(1ba5524f): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-26 15:03:42.057  3568  3978 E Prism.WidgetManager: The same lists. No need to update. skip it.
08-26 15:03:42.057  3568  3978 I Prism.WidgetManager: onLoadItems() -
08-26 15:03:42.057  3568  3978 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@1e542b11 -
08-26 15:03:42.327  8977  9009 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-26 15:03:42.327  8977  9009 W HTCLOG  : mask=0x18
,08-26 15:03:42.407  8977  8977 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-26 15:03:42.407  1111  3494 D PMS     : acquireWL(8b87c74): PARTIAL_WAKE_LOCK  AsyncService 0x1 8681 10128 null
08-26 15:03:42.417  1111  5330 D PMS     : releaseWL(8b87c74): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-26 15:03:42.527  9019  9019 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-26 15:03:42.527  9019  9019 W HTCLOG  : mask=0x18
08-26 15:03:42.687  9019  9023 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-26 15:03:42.687  9019  9023 W HTCLOG  : mask=0x18
08-26 15:03:42.687  9019  9023 E cutils-trace: Error opening trace file: Permission denied (13)
08-26 15:03:42.737  1111  3033 D PMS     : acquireWL(bccea12): PARTIAL_WAKE_LOCK  *alarm* 0x1 1111 1000 WorkSource{10027}
08-26 15:03:42.737  1111  3033 V AlarmManager: sending alarm PendingIntent{117d55e3: PendingIntentRecord{37f7ae15 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=86189, Int=0
08-26 15:03:42.737  1111  3033 V AlarmManager: sending alarm PendingIntent{331aebe0: PendingIntentRecord{594de99 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=81791, Int=0
08-26 15:03:42.737  1111  3033 V AlarmManager: sending alarm PendingIntent{3f8b955e: PendingIntentRecord{3aa56d3f android broadcastIntent}}, i=com.htc.intent.action.UPM_REGULAR_ALARM_INEXACT, t=3, cnt=1, w=82420, Int=0
08-26 15:03:42.747  8715  8715 D AlarmReceiver: ACTION_RESTART_INTENT
08-26 15:03:42.747  9019  9019 D CustomizationManager: ====startRecUseTime====
08-26 15:03:42.747  9019  9019 D htc.customization.log.level:  is 
08-26 15:03:42.747  9019  9019 W CustomizationLogLevel: Level value is invalid, use default level 2
08-26 15:03:42.757  8715  8715 D LocalBluetoothProfile: getPriorityOnValue = 100
08-26 15:03:42.757  8715  8715 D LocalBluetoothProfile: getPriorityOffValue = 0
08-26 15:03:42.757  8715  8715 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-26 15:03:42.757  8715  8715 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-26 15:03:42.757  1111  3634 D HtcSystemUPManager: AlarmScheduler_INEXACT [onReceive] end
08-26 15:03:42.757  1111  3634 D HtcSystemUPManager: com.htc.upm.AlarmScheduler$SchedulerBase$1@3157cc1e
08-26 15:03:42.757  1111  1111 D PMS     : releaseWL(bccea12): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
08-26 15:03:42.757  1111  3632 D HtcSystemUPManager: UPAlarmListener onAlarmArrival
08-26 15:03:42.757  1111  3632 D HtcSystemUPManager: UPAlarmListener [SYSTEM_UP_FLUSH] cur = 1472216622767, last = 1472194834625, freq = 21600000
08-26 15:03:42.767  1111  3632 D HtcSystemUPManager: HtcSystemUPHandler sendService() has been called
08-26 15:03:42.777  1111  3632 I HtcSystemUPManager: HtcSystemUPDataStore Flushing UP data to system_up_store_0 completely.
08-26 15:03:42.777  1111  3632 D HtcSystemUPManager: HtcSystemUPDataStore Reach end of store: system_up_store_0
08-26 15:03:42.777  3641  3664 D HtcAppUPService: HtcUPDataProvider bulkInsert() has been called.
08-26 15:03:42.777  8715  9037 D HtcModeClient: start the htcmodeservice thread
08-26 15:03:42.777  8715  9037 D HtcModeClient: initCanAgent
08-26 15:03:42.777  8715  9037 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-26 15:03:42.787  3641  3664 D HtcAppUPService: HtcUPServiceStore Store Version: 1 Data version: 1 File total length: 9 bytes.  Data length: 0bytes
08-26 15:03:42.787  8715  9037 D HtcModeClient: sense info: version = none, id = 2
08-26 15:03:42.787  8715  9037 D HtcModeClient: display info: width = 1080, height = 1776
08-26 15:03:42.787  8715  9037 D HtcModeClient: display info: mode = 10
08-26 15:03:42.787  3641  3641 D HtcAppUPService: HtcUPService onStartCommand(), flags = 0, startId = 2, intent = Intent { act=com.htc.upservice.action.SYSTEM_UP_NOTIFY cmp=com.htc.sense.hsp/.upservice.HtcUPService }, this = com.htc.sense.hsp.upservice.HtcUPService@7d80a06
08-26 15:03:42.787  3641  5085 D HtcAppUPService: HtcUPServiceHandler.onHandleIntent() intent is com.htc.upservice.action.SYSTEM_UP_NOTIFY
08-26 15:03:42.787  1111  3632 D HtcSystemUPManager: HtcSystemUPHandler send to UPService takes: 18 ms
08-26 15:03:42.787  3641  5085 D HtcAppUPService: Utils getType(): 1, getSubtype: 0
08-26 15:03:42.787  3641  5085 D HtcAppUPService: Utils isNetworkAllowed: true, isTypeWifiAccepted: true, isType2GAccepted: false, isTypeOthersAccepted: false, isWifiAllowed: true, is2GAllowed: false, isOthersAllowed: false
08-26 15:03:42.797  3641  5085 D HtcAppUPService: ReportUploader Start upload resuming queue files. file count: 0
08-26 15:03:42.797  1111  3753 D PMS     : acquireWL(235f7dd3): PARTIAL_WAKE_LOCK  Icing 0x1 4007 10019 null
08-26 15:03:42.807  3641  5085 D HtcAppUPService: HtcUPServiceHandler Set resume upload cache time: 1472216622814
08-26 15:03:42.807  3641  5085 D HtcAppUPService: HtcUPServiceHandler [##] send STOPSELF message, startId = 2, return true
08-26 15:03:42.807  3641  5085 D HtcAppUPService: HtcUPServiceHandler call stopSelfResult() startId = 2, reurn true
08-26 15:03:42.827  1111  3348 D PMS     : releaseWL(235f7dd3): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-26 15:03:42.827  9019  9019 D CustomizationManager:  Read ACC file spent 0.042 (s)
08-26 15:03:42.827  9019  9019 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-26 15:03:42.837  9019  9019 I CustomizationCIDLoader: Parsing tag category name = application
08-26 15:03:42.837  9019  9019 I CustomizationCIDLoader: Parsing tag category name = system
08-26 15:03:42.837  1111  3753 D PMS     : acquireWL(39f6120e): PARTIAL_WAKE_LOCK  Icing 0x1 4007 10019 null
08-26 15:03:42.837  9019  9019 I CustomizationCIDLoader: Parsing tag category name = Settings
08-26 15:03:42.837  9019  9019 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-26 15:03:42.837  9019  9019 I CustomizationCIDLoader: Parsing tag category name = ACC
08-26 15:03:42.837  9019  9019 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-26 15:03:42.837  9019  9019 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-26 15:03:42.837  9019  9019 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-26 15:03:42.837  9019  9019 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-26 15:03:42.837  9019  9019 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-26 15:03:42.837  9019  9019 D CustomizationManager:  Read CID file spent 0.090 (s)
08-26 15:03:42.837  9019  9019 D CustomizationManager:  All configurations done spent 0.090 (s)
08-26 15:03:42.877  1111  3084 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 9019 on display 0
08-26 15:03:42.877  1111  1181 D PMS     : acquireHCC(281733c5): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1111 1000 null
08-26 15:03:42.887  8715  8715 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-26 15:03:42.877  1111  1181 D PMS     : acquireHCC(3305411a): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1111 1000 null
08-26 15:03:42.887  8715  8715 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-26 15:03:42.877  1111  3084 V WindowManager: addAppToken: AppWindowToken{1f3c4741 token=Token{10a16e28 ActivityRecord{72ed44b u0 com.test.thalitest/.MainActivity t451}}} to stack=1 task=451 at 0
08-26 15:03:42.887  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false
08-26 15:03:42.887  8715  8715 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-26 15:03:42.887  8715  8715 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-26 15:03:42.887  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = false
08-26 15:03:42.887  8715  8715 D HtcModeClient: connectState: Force_AWAKE = false
08-26 15:03:42.887  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = true
08-26 15:03:42.887  8715  8715 D HtcModeClient: connectState: POWERCONNECTED_READY = true
08-26 15:03:42.897  1111  3084 I ActivityManager: Start proc 9047:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-26 15:03:42.897  9019  9019 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-26 15:03:42.897  9019  9019 W HTCLOG  : mask=0x18
08-26 15:03:42.897  9019  9045 W HTCLOG  : use specified tag [Vector], func [0].
08-26 15:03:42.897  9019  9046 W HTCLOG  : use specified tag [Vector], func [0].
08-26 15:03:42.897  9019  9046 W HTCLOG  : mask=0x18
08-26 15:03:42.897  9019  9045 W HTCLOG  : mask=0x18
08-26 15:03:42.897  9047  9047 W HTCLOG  : use specified tag [FDManager], func [0].
08-26 15:03:42.897  9047  9047 W HTCLOG  : mask=0x18
08-26 15:03:42.907  1111  3084 D PMS     : releaseWL(39f6120e): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-26 15:03:42.917  3319  3319 D DotMatrix: [EventService]  onDisplayChanged: 0
08-26 15:03:42.917  1111  1111 V ActivityManager: Display changed displayId=0
08-26 15:03:42.917  3319  3319 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-26 15:03:42.917  1111  3490 D ActivityManager: screenshot for ActivityRecord{72ed44b u0 com.test.thalitest/.MainActivity t451}, bitmap=null, time = 0
08-26 15:03:42.957  3568  3568 I TrimMemoryManager: [trimMemory] 20
08-26 15:03:42.967  9047  9047 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-26 15:03:43.027  9047  9047 I LibraryLoader: Time to load native libraries: 27 ms (timestamps 6852-6879)
08-26 15:03:43.027  9047  9047 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 15:03:43.027  9047  9047 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2b0bf86e}
08-26 15:03:43.027  9047  9047 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 15:03:43.037  9047  9047 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-26 15:03:43.037  9047  9047 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-26 15:03:43.037  9047  9047 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:03:43.047  9047  9047 E SysUtils: ApplicationContext is null in ApplicationStatus
08-26 15:03:43.087  5627  6080 D BluetoothAdapterService(391591024): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23418ecd
08-26 15:03:43.097  9047  9047 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-26 15:03:43.097  9047  9047 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
08-26 15:03:43.097  9047  9047 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
08-26 15:03:43.097  9047  9047 W HTCLOG  : use specified tag [libEGL], func [3].
08-26 15:03:43.097  9047  9047 W HTCLOG  : mask=0x18
08-26 15:03:43.107  9047  9047 W HTCLOG  : use specified tag [libEGL], func [3].
08-26 15:03:43.107  9047  9047 W HTCLOG  : mask=0x18
08-26 15:03:43.107  9047  9047 I Adreno  : QUALCOMM build                   : 065751b, 
08-26 15:03:43.107  9047  9047 I Adreno  : Build Date                       : 04/15/15
08-26 15:03:43.107  9047  9047 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-26 15:03:43.107  9047  9047 I Adreno  : Local Branch                     : 
08-26 15:03:43.107  9047  9047 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-26 15:03:43.107  9047  9047 I Adreno  : Remote Branch                    : NONE
08-26 15:03:43.107  9047  9047 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,08-26 15:03:43.167  9047  9082 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,08-26 15:03:43.187  9047  9047 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,08-26 15:03:43.197  9047  9047 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-26 15:03:43.207  9047  9047 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,08-26 15:03:43.207  9047  9047 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-26 15:03:43.207  9047  9047 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 15:03:43.237  9047  9093 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-26 15:03:43.237  9047  9093 W HTCLOG  : mask=0x18
,08-26 15:03:43.237  1111  3084 V WindowManager: Adding window Window{2b17af6e u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{178a3ed0 u0 com.htc.launcher/com.htc.launcher.Launcher})
,08-26 15:03:43.247  1111  3632 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,08-26 15:03:43.277  9047  9047 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
08-26 15:03:43.277  9047  9047 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-26 15:03:43.277  9047  9047 W HTCLOG  : mask=0x18
08-26 15:03:43.277  9047  9047 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-26 15:03:43.277  9047  9047 W HTCLOG  : mask=0x18
,08-26 15:03:43.287  9047  9093 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].,
08-26 15:03:43.287  9047  9093 W HTCLOG  : mask=0x18
08-26 15:03:43.287  9047  9093 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-26 15:03:43.287  9047  9093 W HTCLOG  : mask=0x18
08-26 15:03:43.287  9047  9093 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-26 15:03:43.287  9047  9093 W HTCLOG  : mask=0x18
,08-26 15:03:43.287  9047  9093 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-26 15:03:43.287  9047  9093 W HTCLOG  : mask=0x18
,08-26 15:03:43.287  9047  9093 W HTCLOG  : use specified tag [Surface], func [3].
08-26 15:03:43.287  9047  9093 W HTCLOG  : mask=0x18
,08-26 15:03:43.287  9047  9093 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-26 15:03:43.287  9047  9093 W HTCLOG  : mask=0x18
08-26 15:03:43.287  9047  9093 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-26 15:03:43.287  9047  9093 W HTCLOG  : mask=0x18
,08-26 15:03:43.327   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-26 15:03:43.337  1111  1170 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +412ms (total +450ms),
,08-26 15:03:43.367  9047  9047 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 9047,
,08-26 15:03:43.427  9047  9047 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 15:03:43.467  9047  9096 D jxcore_app_log: JniHelper::setJavaVM(0xaab8ab70), pthread_self() = -1414567112
,08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: ,
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3deeca85 added. We now have 1 listener(s)
,08-26 15:03:43.477  1111  1132 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
,08-26 15:03:43.477  9047  9096 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF,
08-26 15:03:43.477  9047  9096 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
08-26 15:03:43.477  9047  9096 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 15:03:43.477  9047  9096 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
,08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 15:03:43.477  9047  9096 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@308403e8 added. We now have 1 listener(s)
08-26 15:03:43.477  9047  9096 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 15:03:43.487  1111  3076 D WifiService: New client listening to asynchronous messages
,08-26 15:03:43.487  9047  9096 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 15:03:43.487  9047  9096 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 15:03:43.487  9047  9096 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-26 15:03:43.487  9047  9096 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 15:03:43.487  9047  9096 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 15:03:43.487  9047  9096 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 15:03:43.487  1111  3493 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-26 15:03:43.487  9047  9096 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
,08-26 15:03:43.497  5627  6080 D BluetoothAdapterService(391591024): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23418ecd
,08-26 15:03:43.497  9047  9096 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-26 15:03:43.497  9047  9096 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:03:43.497  9047  9096 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:03:43.497  9047  9096 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:03:43.497  9047  9096 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:03:43.497  9047  9096 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:03:43.497  9047  9096 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:03:43.497  9047  9096 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:03:43.497  9047  9096 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 15:03:43.497  9047  9096 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 15:03:43.497  9047  9096 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 15:03:43.497  9047  9096 I io.jxcore.node.LifeCycleMonitor: start: OK
08-26 15:03:43.497  9047  9047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:03:43.497  9047  9047 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 15:03:43.537  9047  9047 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 15:03:43.867  9047  9102 W jxcore-log: Initializing JXcore engine
,08-26 15:03:43.867  9047  9102 W jxcore-log: JXcore engine is ready
,08-26 15:03:43.877  1111  1181 D PMS     : releaseHCC(281733c5): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
08-26 15:03:43.877  1111  1181 D PMS     : releaseHCC(3305411a): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,08-26 15:03:43.927  9047  9102 W jxcore-log: Starting JXcore engine,
,08-26 15:03:44.027  9047  9102 W jxcore-log: Platform android,
08-26 15:03:44.027  9047  9102 W jxcore-log: 
08-26 15:03:44.027  9047  9102 W jxcore-log: Process ARCH arm
08-26 15:03:44.027  9047  9102 W jxcore-log: 
,08-26 15:03:44.217  9047  9102 I jxcore-log: JXcore Cordova bridge is ready!,
08-26 15:03:44.217  9047  9102 I jxcore-log: 
08-26 15:03:44.217  9047  9102 W jxcore-log: JXcore engine is started
,08-26 15:03:44.227  9047  9096 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-26 15:03:44.237  9047  9047 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 15:03:44.897  8715  9037 I HtcModeClient: handler message = 4011
,08-26 15:03:44.897  8715  9037 D HtcModeClient: getConnectionCheckCount first 0
08-26 15:03:44.897  8715  9037 D HtcModeClient: getConnectionCheckCount count = 6
,08-26 15:03:44.897  8715  9037 E HtcModeClient: Check connection and retry 7 times.
,08-26 15:03:44.897  8715  9037 D HtcModeClient: setConnectionCheckCount count = 7
08-26 15:03:44.897  8715  9037 D HtcModeClient: setupRestart delayedTime = 3000
,08-26 15:03:44.907  8715  8715 D HtcModeClient: setBtPriority priority = on
08-26 15:03:44.907  8715  8715 D HtcModeClient: unbindBlueToothService
08-26 15:03:44.907  8715  8715 D HtcModeClient: Don't start project servcice
,08-26 15:03:44.907  8715  8715 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-26 15:03:44.907  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false
,08-26 15:03:44.907  8715  8715 D SilentMusic: call stop
08-26 15:03:44.907  8715  8715 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-26 15:03:44.907  8715  9038 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-26 15:03:44.917  8715  8715 D HtcModeClient: onDestroy
,08-26 15:03:46.347  8977  8977 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-26 15:03:46.347  1111  3493 I ActivityManager: Killing 8463:com.google.android.setupwizard/u0a59 (adj 15): empty #17
08-26 15:03:46.347  1111  3493 D Process : killProcessQuiet, pid=8463
,08-26 15:03:46.347  1111  3493 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-26 15:03:46.507  1111  3490 I ActivityManager: Recipient 8463,
,08-26 15:03:47.287  8977  9008 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-26 15:03:49.097  1111  1111 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,08-26 15:03:49.897  1111  3494 D PMS     : releaseWL(1f3d15a6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,08-26 15:03:49.907  1111  3033 D PMS     : acquireWL(34ed1da3): PARTIAL_WAKE_LOCK  *alarm* 0x1 1111 1000 WorkSource{10027}
08-26 15:03:49.907  1111  3033 V AlarmManager: sending alarm PendingIntent{170f78a0: PendingIntentRecord{37f7ae15 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=91758, Int=0
08-26 15:03:49.907  8715  8715 D AlarmReceiver: ACTION_RESTART_INTENT
08-26 15:03:49.917  1111  1111 D PMS     : releaseWL(34ed1da3): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-26 15:03:49.917  8715  8715 D LocalBluetoothProfile: getPriorityOnValue = 100
08-26 15:03:49.917  8715  8715 D LocalBluetoothProfile: getPriorityOffValue = 0
08-26 15:03:49.917  8715  8715 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-26 15:03:49.917  8715  8715 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-26 15:03:49.937  8715  9110 D HtcModeClient: start the htcmodeservice thread
,08-26 15:03:49.937  8715  9110 D HtcModeClient: initCanAgent
,08-26 15:03:49.937  8715  9110 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-26 15:03:49.947  8715  9110 D HtcModeClient: sense info: version = none, id = 2
,08-26 15:03:49.947  8715  9110 D HtcModeClient: display info: width = 1080, height = 1776
08-26 15:03:49.947  8715  9110 D HtcModeClient: display info: mode = 10
,08-26 15:03:50.037  8715  8715 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-26 15:03:50.047  8715  8715 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-26 15:03:50.047  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false
08-26 15:03:50.047  8715  8715 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-26 15:03:50.047  8715  8715 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-26 15:03:50.047  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = false
08-26 15:03:50.047  8715  8715 D HtcModeClient: connectState: Force_AWAKE = false
08-26 15:03:50.047  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = true
08-26 15:03:50.047  8715  8715 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-26 15:03:52.057  8715  9110 I HtcModeClient: handler message = 4011,
08-26 15:03:52.057  8715  9110 D HtcModeClient: getConnectionCheckCount first 0
08-26 15:03:52.057  8715  9110 D HtcModeClient: getConnectionCheckCount count = 7
08-26 15:03:52.057  8715  9110 E HtcModeClient: Check connection and retry 8 times.
,08-26 15:03:52.057  8715  9110 D HtcModeClient: setConnectionCheckCount count = 8
,08-26 15:03:52.057  8715  9110 D HtcModeClient: setupRestart delayedTime = 3000
,08-26 15:03:52.067  8715  8715 D HtcModeClient: setBtPriority priority = on
08-26 15:03:52.067  8715  8715 D HtcModeClient: unbindBlueToothService
08-26 15:03:52.067  8715  8715 D HtcModeClient: Don't start project servcice
,08-26 15:03:52.067  8715  8715 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-26 15:03:52.067  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false
08-26 15:03:52.067  8715  8715 D SilentMusic: call stop
08-26 15:03:52.067  8715  8715 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-26 15:03:52.067  8715  9111 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-26 15:03:52.067  8715  8715 D HtcModeClient: onDestroy
,08-26 15:03:53.757  1111  3516 D PMS     : acquireWL(2f752d91): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
,08-26 15:03:53.757  1111  3516 I BatteryService: n_update end
08-26 15:03:53.767  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false),
08-26 15:03:53.767  1111  3516 D PMS     : releaseWL(2f752d91): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:03:53.767  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:03:53.767  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:03:53.767  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:03:53.767  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:03:53.767  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:03:53.767  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:03:53.767  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:03:53.767  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:03:53.767  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:03:53.767  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:03:53.767  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:03:53.767  1111  1111 D HtcPowerSaver: Checking...
08-26 15:03:53.767  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:03:53.767  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:03:53.767  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:03:53.767  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:03:53.767  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:03:53.767  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:03:53.767  1111  3076 D WifiController: handleMessage: X
,08-26 15:03:53.777  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-26 15:03:53.777  1111  1111 I HtcPowerSaver: << updateStatus
,08-26 15:03:53.817  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-26 15:03:53.817  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:03:53.817  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:03:53.817  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-26 15:03:53.827  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:03:55.107  1111  1159 I ActivityManager: Waited long enough for: ServiceRecord{3bf88f66 u0 com.google.android.gms/.wearable.service.WearableService},
,08-26 15:03:57.087  1111  3033 I ActivityManager: Start proc 9112:com.htc.mms.backupagent/u0a58 for service com.htc.mms.backupagent/.SMSBackupAgentService
,08-26 15:03:57.087  1111  3033 D PMS     : acquireWL(37ecc4f6): PARTIAL_WAKE_LOCK  *alarm* 0x1 1111 1000 WorkSource{10058}
08-26 15:03:57.087  1111  3033 V AlarmManager: sending alarm PendingIntent{1700f7: PendingIntentRecord{220db64 com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1472216634755, Int=60000
,08-26 15:03:57.097  1111  3033 V AlarmManager: sending alarm PendingIntent{14983a82: PendingIntentRecord{2930b593 com.android.vending startService}}, i=null, t=0, cnt=1, w=1472216635233, Int=0,
08-26 15:03:57.097  8715  8715 D AlarmReceiver: ACTION_RESTART_INTENT
08-26 15:03:57.097  1111  3033 V AlarmManager: sending alarm PendingIntent{23c249d0: PendingIntentRecord{37f7ae15 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=98920, Int=0
08-26 15:03:57.097  9112  9112 W HTCLOG  : use specified tag [FDManager], func [0].
08-26 15:03:57.097  9112  9112 W HTCLOG  : mask=0x18
08-26 15:03:57.117  8715  8715 D LocalBluetoothProfile: getPriorityOnValue = 100
08-26 15:03:57.117  1111  1111 D PMS     : releaseWL(37ecc4f6): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-26 15:03:57.117  8715  8715 D LocalBluetoothProfile: getPriorityOffValue = 0
08-26 15:03:57.117  8715  8715 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-26 15:03:57.117  8715  8715 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-26 15:03:57.137  8715  9134 D HtcModeClient: start the htcmodeservice thread,
08-26 15:03:57.137  8715  9134 D HtcModeClient: initCanAgent
08-26 15:03:57.147  9112  9135 D SMSBackup: SMSBackupAgentService started
08-26 15:03:57.147  9112  9135 D SMSBackup: Checking restore status
08-26 15:03:57.147  8715  9134 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-26 15:03:57.147  8715  9134 D HtcModeClient: sense info: version = none, id = 2
08-26 15:03:57.147  9112  9135 D SMSBackup: Restore complete
08-26 15:03:57.147  9112  9135 D SMSBackup: cancelCheckAlarm
08-26 15:03:57.147  8715  9134 D HtcModeClient: display info: width = 1080, height = 1776
08-26 15:03:57.147  8715  9134 D HtcModeClient: display info: mode = 10
08-26 15:03:57.147  9112  9135 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
,08-26 15:03:57.247  8715  8715 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-26 15:03:57.247  8715  8715 D HtcModeClient: connectState: BT_TURNON_BYME = false,
08-26 15:03:57.247  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false
08-26 15:03:57.247  8715  8715 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-26 15:03:57.247  8715  8715 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-26 15:03:57.247  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = false
08-26 15:03:57.247  8715  8715 D HtcModeClient: connectState: Force_AWAKE = false
08-26 15:03:57.247  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = true
08-26 15:03:57.247  8715  8715 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-26 15:03:57.377  8610  8610 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-26 15:03:59.257  8715  9134 I HtcModeClient: handler message = 4011,
08-26 15:03:59.257  8715  9134 D HtcModeClient: getConnectionCheckCount first 0
08-26 15:03:59.257  8715  9134 D HtcModeClient: getConnectionCheckCount count = 8
08-26 15:03:59.257  8715  9134 E HtcModeClient: Check connection and retry 9 times.
,08-26 15:03:59.257  8715  9134 D HtcModeClient: setConnectionCheckCount count = 9
,08-26 15:03:59.257  8715  9134 D HtcModeClient: setupRestart delayedTime = 3000
,08-26 15:03:59.267  8715  8715 D HtcModeClient: setBtPriority priority = on
,08-26 15:03:59.267  8715  8715 D HtcModeClient: unbindBlueToothService
08-26 15:03:59.267  8715  8715 D HtcModeClient: Don't start project servcice
,08-26 15:03:59.267  8715  8715 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-26 15:03:59.267  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false
08-26 15:03:59.267  8715  8715 D SilentMusic: call stop
,08-26 15:03:59.267  8715  8715 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-26 15:03:59.267  8715  9136 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-26 15:03:59.287  8715  8715 D HtcModeClient: onDestroy
,08-26 15:03:59.287  1111  3084 D Process : killProcessQuiet, pid=8091
08-26 15:03:59.287  1111  3084 I ActivityManager: Killing 8091:com.google.android.apps.photos/u0a126 (adj 15): empty #17
08-26 15:03:59.287  1111  3084 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-26 15:03:59.357  1111  3753 I ActivityManager: Recipient 8091,
,08-26 15:04:02.987  9047  9102 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-26 15:04:02.987  9047  9102 I jxcore-log: 
,08-26 15:04:02.997  9047  9102 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 15:04:02.997  9047  9102 I jxcore-log: 
,08-26 15:04:03.007  5627  5660 D BluetoothAdapterService(391591024): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23418ecd
,08-26 15:04:03.007  9047  9102 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 15:04:03.007  9047  9102 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 15:04:03.007  9047  9102 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 15:04:03.007  9047  9102 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 15:04:03.007  9047  9102 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 15:04:03.007  9047  9102 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 15:04:03.007  9047  9102 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 15:04:03.007  9047  9102 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 15:04:03.007  5627  5673 D BluetoothAdapterService(391591024): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23418ecd
08-26 15:04:03.007  9047  9102 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 15:04:03.017  9047  9102 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 15:04:03.017  9047  9102 I jxcore-log: 
,08-26 15:04:03.017  9047  9102 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 15:04:03.017  9047  9102 I jxcore-log: 
,08-26 15:04:03.517  9047  9102 I jxcore-log: Running unit tests
08-26 15:04:03.517  9047  9102 I jxcore-log: 
08-26 15:04:03.517  9047  9102 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-26 15:04:03.517  9047  9102 I jxcore-log: Failed to execute UT.
08-26 15:04:03.517  9047  9102 I jxcore-log: 
,08-26 15:04:03.517  9047  9102 I jxcore-log: Unit Test app is loaded
08-26 15:04:03.517  9047  9102 I jxcore-log: 
,08-26 15:04:03.527  9047  9102 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 15:04:03.527  9047  9102 I jxcore-log: 
,08-26 15:04:03.537  9047  9102 I jxcore-log: My device name is: HTC-HTC One M9
08-26 15:04:03.537  9047  9102 I jxcore-log: 
08-26 15:04:03.537  9047  9047 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68),
08-26 15:04:03.537  9047  9102 I jxcore-log: WARN testUtils: myNameCallback not set!
08-26 15:04:03.537  9047  9102 I jxcore-log: 
,08-26 15:04:04.177  9047  9102 W jxcore-log: !!! js_ReportOverRecursed called !!!,
,08-26 15:04:04.227  9138  9138 W google-breakpad: -----BEGIN BREAKPAD MICRODUMP-----,
08-26 15:04:04.227  9138  9138 W google-breakpad: O A arm 08 aarch64 3.10.49-perf-g428d9d4 #1 SMP PREEMPT Tue Dec 15 22:44:23 CST 2015
,08-26 15:04:04.227  9138  9138 W google-breakpad: S 0 DA188008 DA188000 00008000,
,08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188000 7417C0DA3C8018DA070000000000000068B3C3AB90B8E0E6C0CE9DC385FFFFFFE01DF1DA100EB5ABC08018DA6C8018DA448018DA85FFFFFF648018DA202E85DAC0CE9DC3E01DF1DA00000000308118DA6C8018DAC08018DA7417C0DAC0CE9DC38C8018DA58D7A6DA64D0D4AD000000000000000082FFFFFFC08018DA308118DAB08018DA100EB5ABF48018DA1C6B9FDAE4D8BFDA50DCBFDA58DBD5DA2200000064D0D4AD4CD0D4AD00000000C48018DAC0CE9DC385FFFFFF100EB5AB00000000C0CE9DC385FFFFFF788118DA488218DA18C1D6DA408118DA0000000001000000308118DA208118DA22000000100EB5AB848218DA2894A2DA20D0D4AD00000000100EB5AB108118DA02000000588118DAE03CD3C3788118DA507298C388FFFFFF0000000082FFFFFF00000000000100000000000082FFFFFF100EB5AB0000000000000000100EB5AB01000000A88218DAB88218DA0100000020D0D4AD07000000070000000100000030CD9DC300000000100EB5AB000000000000000006000000
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188180 3CC1D6DA3CC1D6DA0600000018C1D6DA00000000FFFFFFFF0000000030D0D4AD2200000038CD9DC30700000000000000010000001800F0DA786AF7AC81FFFFFFE48118DAE0AA8FDA0700000030CD9DC3100EB5AB000000001000F0DAF08118DA248218DAE8EC8FDA0000000000000000000000000CF468DD588218DA0100000000000000D07698C3E01BF1DA30CD9DC300000000FFFFFFFF786AF7AC81FFFFFFC08218DAB0F468DD188318DA348218DA808218DA000000000000000078F468DD4003000001000000FFFFFFFF81FFFFFF30CD9DC385FFFFFF1000F0DA85FFFFFF00000000604966C488FFFFFF883CCCDD00000000FFFFFFFFE86AF7AC81FFFFFFC08218DA383FC4DD00000000948218DA8C49C4DD0000000000000000883CCCDD4202000001000000604966C488FFFFFF00EA62C488FFFFFF30CD9DC385FFFFFF1C8318DAE86AF7AC883CCCDD0105000030CD9DC385FFFFFF00EA62C488FFFFFF604966C488FFFFFF0000000082FFFFFF0000000028616ADD4002000000000000
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188300 5000000030BD62C4F0D9F1DA85FFFFFF4C8318DA648318DA00000000408318DA8C49C4DD82010000808666C4010000000000000082FFFFFF30CD9DC385FFFFFFEC8318DAC0C2DEAB2CBCC8DD010A000030CD9DC385FFFFFF0000000082FFFFFF808666C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007F0DA85FFFFFFF0D9F1DA85FFFFFF82FFFFFF5818DFDAF0FBF1DAEC6A60DDA000000030BD62C40000000083FFFFFFE86B60DD0200000000000000188418DA8C49C4DD02020000C04C66C402000000A0C665C488FFFFFF30CD9DC385FFFFFF60E9ABC388FFFFFF8C8418DAA8E720ADBCAC60DD81060000F0D9F1DA85FFFFFF30CD9DC385FFFFFFA0C665C488FFFFFFC04C66C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000708418DA0000000083FFFFFF6800000060CA12C238CD9DC301000000
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188480 3000000060CA12C200000000B08418DA8C49C4DD82010000E016E8C2010000000000000082FFFFFF30CD9DC385FFFFFF348518DA406971ACFCA460DD8107000030CD9DC385FFFFFF0000000082FFFFFFE016E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF508518DA488518DA408518DAB48518DA7800000060CA12C2000000000E474CAC58DBD5DA100EB5AB00000000588518DA8C49C4DD820100002017E8C2010000000000000082FFFFFF30CD9DC385FFFFFFC48518DAB042C9ADDC9A60DD0106000030CD9DC385FFFFFF0000000082FFFFFF2017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000D08518DAE88518DA040000006000000060CA12C2084AC9AD81FFFFFF548618DAF8FFC3DD00000000E88518DA8C49C4DD820100004017E8C2010000000000000082FFFFFF30CD9DC385FFFFFF548618DAA83DC9ADE09160DD0106000030CD9DC385FFFFFF
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188600 0000000082FFFFFF4017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000707698C300000000E038EDC260000000A07698C304000000E86B60DD648618DA780472DA04000000788618DA8C49C4DD820100006017E8C2010000000000000082FFFFFF707698C388FFFFFFF48618DAB048C9ADF48860DD01070000707698C388FFFFFF0000000082FFFFFF6017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013F1DA85FFFFFF30CD9DC385FFFFFF00000000E88618DAE48618DA88FFFFFF70000000407698C3C0EE9EC384E184DA000000000000000004000000188718DA8C49C4DD82010000E017E8C20100000070E33BC488FFFFFFB07298C388FFFFFF748718DAA81EE2AD608260DD01050000B07298C388FFFFFF70E33BC488FFFFFFE017E8C288FFFFFFC0D3F1DA85FFFFFFC0EE9EC301000000A48718DABC8718DA50000000509E4AC20200000048D27DAD948718DAC80372DA00000000A88718DADC7DC7DD82020000
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188780 2078EFC3030000000000000082FFFFFFB07298C388FFFFFF0000000081FFFFFFC0EE9EC388FFFFFF448818DAA06C2CADE87266DD01090000C0EE9EC388FFFFFF0000000081FFFFFFB07298C388FFFFFF0000000082FFFFFF2078EFC388FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF10C5F7C288FFFFFF0000000082FFFFFF0900000081FFFFFFC0EE9EC388FFFFFF10EF9EC300000000748818DAC0D662C49000000020C062C4E86B60DD02000000E8E885AD81FFFFFF00000000688818DA8C49C4DD82010000B00263C401000000C0EE9EC388FFFFFF2078EFC388FFFFFFEC8818DAC8F485ADD07B60DD810700002078EFC388FFFFFFC0EE9EC388FFFFFFB00263C488FFFFFF10EF9EC388FFFFFFC0D662C488FFFFFFC0D062C488FFFFFF0000000082FFFFFF10EF9EC388FFFFFF0000000082FFFFFF108918DA383FC4DD00000000D48818DA78000000509E4AC200000000247260DD420300000300000000000000188918DA8C49C4DD020200004078EFC302000000
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188900 7069D7C188FFFFFFE03CD3C388FFFFFFC0EE9EC388FFFFFF848918DA808C8AADF07660DD01060000C0EE9EC388FFFFFFE03CD3C388FFFFFF7069D7C188FFFFFF4078EFC388FFFFFF0000000082FFFFFF0000000082FFFFFF488918DAA03564C460CE9DC34011F1DA60000000509E4AC285FFFFFFDCA66ADD85FFFFFF848918DA00000000003764C4E8B16ADD800B00008078EFC302000000003764C488FFFFFFE03CD3C388FFFFFFD0E89EC388FFFFFF70CE9DC385FFFFFF70EE9EC388FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFD07398C3D0E89EC3A03564C490E99AC38A000000807598C370CE9DC370EE9EC3D0E89EC3A03564C460CE9DC38018F0DAF0E99AC30900000000E9ABC3D0B062C4D0B062C4D0E89EC388FFFFFF090000004011F1DA09000000003764C4E03CD3C3807298C300E9ABC388FFFFFF00000000642DA7DD082FA7DD00040000803664C401000000003764C488FFFFFFE03CD3C388FFFFFF0000000082FFFFFFF02ADFDAE03CD3C3
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188A80 507298C3207298C30000000087FFFFFFA00F63C4F07198C3207298C3E0E8ABC3E0FD68DD80020000C03664C4020000000000000082FFFFFFA00F63C488FFFFFFF07198C388FFFFFF008B18DAF07198C3907198C3C07198C3FC2069DD80020000003764C400000000907198C388FFFFFF30C598C38A0000000700000040C598C3100EB5AB40B062C480E99AC3003764C42078C3DD03020000603F67C40100000040B062C488FFFFFF80E99AC385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100EB5ABE4ED64F7D88C18DA0100000081FFFFFF308C18DA9C8C18DA14C477DA603F67C40000000000000000008C18DAB48B18DA3877C3DD58DBD5DA100EB5ABA8B3BDAB1C9D18DA00000000000000000000000001000000049418DA100EB5AB0001000000000000B01F69DD00000000603F67C4909018DA02000000010000000000000000000000
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188C00 0100000081FFFFFF0000000000000000689018DAF6FFFFFF1C0EB5AB01000000100EB5AB308C18DA000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000D88C18DA100EB5AB783BDFDA80826AC40000000078CBD4AD9C8C18DA44AF6D0700000000100EB5ABD88C18DAA08C18DA603F67C480826AC40000000078CBD4ADC48C18DA2C6595DA000000000000000000000000E4ED64F701000000100EB5AB989018DAD08C18DA4C9018DA246695DAA25F93AC4B6193AC989018DA01000000E80CD5DA0100000080826AC4D08C18DA00000000006293AC0200000002000000010000000000000080BAD4DA5C0000000600000000000000089C18DA000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188D80 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000505793AC0000000000000000010000000200000040E8ABC380836AC4B546DEAB000000000000000044AF6D0700000000E4ED64F700000000100EB5ABC8BA87DA688E18DAE49118DAA86695DA0000000000000000889218DA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA188F00 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000044AF6D07E4ED64F7889018DA100EB5AB389118DA989018DA78CBD4ADF49018DAE46A95DA00000000000000000000000040B062C4989018DA01000000789D18DAF6FFFFFF1C0EB5AB00000000100EB5AB889018DA
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA189080 0300000008000000603F67C488FFFFFF40B062C488FFFFFF80E99AC385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000001000000044AF6D0770CBD4AD100EB5AB489118DA389118DA409118DA349118DA82FFFFFF70CBD4AD249118DA385585DA70CBD4AD409118DA40B062C488FFFFFF849118DAB89118DA989218DA01000000509118DA00000000849118DA20EBA6DA409118DA000000000000000040B062C4603F67C488FFFFFF0000000082FFFFFF0100000070CBD4AD0000000082FFFFFF100EB5AB000000006C17C0DAB89118DAA89118DAF0C37DAB88C67DAB100EB5AB989218DA6C17C0DAF49118DAB8FA9DDAB89118DA089218DA4843C5AC27F561F74843C5ACC0AD64F724CBD4AD0000000040B062C488FFFFFF100EB5AB0000000080E99AC385FFFFFF100EB5AB00000000089218DA1870C1DA45CBD4AD289218DA989218DA189218DA100EB5AB0C9218DA22000000F0C37DAB5C9218DAEC6A9FDAE4D8BFDA50DCBFDA
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA189200 58DBD5DA2200000024CBD4AD0CCBD4AD000000002C9218DA2200000000000000B09318DA00000000449218DA14355DDAE09218DAB09318DA18C1D6DAA89218DA0000000001000000989218DA889218DA22000000100EB5ABEC9318DA2894A2DAE0CAD4AD00000000100EB5AB789218DA02000000C09218DA903CD3C3E09218DAD0CC92C388FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000100EB5AB01000000109418DA209418DA01000000E0CAD4AD07000000070000000100000020E89AC300000000100EB5AB0000000000000000060000003CC1D6DA3CC1D6DA0600000018C1D6DA00000000FFFFFFFF00000000F0CAD4AD2200000028E89AC30700000000000000010000001800F0DA786AF7AC81FFFFFF4C9318DAE0AA8FDA0700000020E89AC3100EB5AB000000001000F0DA589318DA8C9318DAE8EC8FDA0000000000000000000000000CF468DDC09318DA0100000000000000607198C3E01BF1DA20E89AC300000000FFFFFFFF
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA189380 786AF7AC81FFFFFF289418DAB0F468DD809418DA9C9318DAE89318DA000000000000000078F468DD4003000001000000FFFFFFFF81FFFFFF20E89AC385FFFFFF1000F0DA85FFFFFF00000000604966C488FFFFFF883CCCDD00000000FFFFFFFFE86AF7AC81FFFFFF289418DA383FC4DD00000000FC9318DA8C49C4DD0000000000000000883CCCDD4202000001000000604966C488FFFFFF00EA62C488FFFFFF20E89AC385FFFFFF849418DAE86AF7AC883CCCDD0105000020E89AC385FFFFFF00EA62C488FFFFFF604966C488FFFFFF0000000082FFFFFF0000000028616ADD40020000000000005000000030BD62C4F0D9F1DA85FFFFFFB49418DACC9418DA00000000A89418DA8C49C4DD82010000808666C4010000000000000082FFFFFF20E89AC385FFFFFF549518DAC0C2DEAB2CBCC8DD010A000020E89AC385FFFFFF0000000082FFFFFF808666C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA189500 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007F0DA85FFFFFFF0D9F1DA85FFFFFF82FFFFFF5818DFDAF0FBF1DAEC6A60DDA000000030BD62C40000000083FFFFFFE86B60DD0200000000000000809518DA8C49C4DD02020000C04C66C402000000A0C665C488FFFFFF20E89AC385FFFFFFC0E8ABC388FFFFFFF49518DAA8E720ADBCAC60DD81060000F0D9F1DA85FFFFFF20E89AC385FFFFFFA0C665C488FFFFFFC04C66C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000D89518DA0000000083FFFFFF6800000060CA12C228E89AC3010000003000000060CA12C200000000189618DA8C49C4DD82010000E016E8C2010000000000000082FFFFFF20E89AC385FFFFFF9C9618DA406971ACFCA460DD8107000020E89AC385FFFFFF0000000082FFFFFFE016E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFB89618DAB09618DAA89618DA1C9718DA
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA189680 7800000060CA12C2000000000E474CAC58DBD5DA100EB5AB00000000C09618DA8C49C4DD820100002017E8C2010000000000000082FFFFFF20E89AC385FFFFFF2C9718DAB042C9ADDC9A60DD0106000020E89AC385FFFFFF0000000082FFFFFF2017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000389718DA509718DA040000006000000060CA12C2084AC9AD81FFFFFFBC9718DAF8FFC3DD00000000509718DA8C49C4DD820100004017E8C2010000000000000082FFFFFF20E89AC385FFFFFFBC9718DAA83DC9ADE09160DD0106000020E89AC385FFFFFF0000000082FFFFFF4017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000007198C300000000E038EDC260000000307198C304000000E86B60DDCC9718DA780472DA04000000E09718DA8C49C4DD820100006017E8C2010000000000000082FFFFFF007198C388FFFFFF5C9818DAB048C9ADF48860DD01070000007198C388FFFFFF0000000082FFFFFF
08-26 15:04:04.237  9138  9138 W google-breakpad: S DA189800 6017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013F1DA85FFFFFF20E89AC385FFFFFF00000000509818DA4C9818DA88FFFFFF70000000D07098C330E89EC384E184DA000000000000000004000000809818DA8C49C4DD82010000E017E8C20100000070E33BC488FFFFFF30CD92C388FFFFFFDC9818DAA81EE2AD608260DD0105000030CD92C388FFFFFF70E33BC488FFFFFFE017E8C288FFFFFFC0D3F1DA85FFFFFF30E89EC3010000000C9918DA249918DA50000000509E4AC20200000048D27DADFC9818DAC80372DA00000000109918DADC7DC7DD820200002078EFC3030000000000000082FFFFFF30CD92C388FFFFFF0000000081FFFFFF30E89EC388FFFFFFAC9918DAA06C2CADE87266DD0109000030E89EC388FFFFFF0000000081FFFFFF30CD92C388FFFFFF0000000082FFFFFF2078EFC388FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF30C4F7C288FFFFFF0000000082FFFFFF0900000081FFFFFF30E89EC388FFFFFF
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA189980 80E89EC300000000DC9918DAC0D662C49000000020C062C4E86B60DD02000000E8E885AD81FFFFFF00000000D09918DA8C49C4DD82010000B00263C40100000030E89EC388FFFFFF2078EFC388FFFFFF549A18DAC8F485ADD07B60DD810700002078EFC388FFFFFF30E89EC388FFFFFFB00263C488FFFFFF80E89EC388FFFFFFC0D662C488FFFFFFC0D062C488FFFFFF0000000082FFFFFF80E89EC388FFFFFF0000000082FFFFFF789A18DA383FC4DD000000003C9A18DA78000000509E4AC200000000247260DD420300000300000000000000809A18DA8C49C4DD020200004078EFC3020000007069D7C188FFFFFF903CD3C388FFFFFF30E89EC388FFFFFFEC9A18DA808C8AADF07660DD0106000030E89EC388FFFFFF903CD3C388FFFFFF7069D7C188FFFFFF4078EFC388FFFFFF0000000082FFFFFF0000000082FFFFFFB09A18DAA03564C450E99AC34011F1DA60000000509E4AC285FFFFFFDCA66ADD85FFFFFFEC9A18DA00000000003764C4E8B16ADD800B00008078EFC302000000,
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA189B00 003764C488FFFFFF903CD3C388FFFFFF40E29EC388FFFFFF60E99AC385FFFFFFE0E79EC388FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF50CE92C340E29EC3A03564C430C598C38A000000107098C360E99AC3E0E79EC340E29EC3A03564C450E99AC38018F0DA90C598C30900000060E8ABC3D0B062C4D0B062C440E29EC388FFFFFF090000004011F1DA09000000003764C4903CD3C300CD92C360E8ABC388FFFFFF00000000642DA7DD082FA7DD00040000803664C401000000003764C488FFFFFF903CD3C388FFFFFF0000000082FFFFFFF02ADFDA903CD3C3D0CC92C3A0CC92C30000000087FFFFFFA00F63C470CC92C3A0CC92C340E8ABC3E0FD68DD80020000C03664C4020000000000000082FFFFFFA00F63C488FFFFFF70CC92C388FFFFFF689C18DA70CC92C310CC92C340CC92C3FC2069DD80020000003764C40000000010CC92C388FFFFFF80119EC38A0000000700000090119EC3100EB5AB40B062C420C598C3003764C42078C3DD03020000
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA189C80 603F67C40100000040B062C488FFFFFF20C598C385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100EB5ABE4ED64F7409E18DA0100000081FFFFFF989D18DA049E18DA14C477DA603F67C40000000000000000689D18DA1C9D18DA3877C3DD58DBD5DA100EB5ABA8B3BDAB84AE18DA000000000000000000000000010000006CA518DA100EB5AB0001000000000000B01F69DD00000000603F67C4F8A118DA020000000100000000000000000000000100000081FFFFFF0000000000000000D0A118DAF6FFFFFF1C0EB5AB01000000100EB5AB989D18DA000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000409E18DA100EB5AB783BDFDA80826AC40000000038C6D4AD049E18DA44AF6D0700000000100EB5AB409E18DA089E18DA603F67C480826AC40000000038C6D4AD
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA189E00 2C9E18DA2C6595DA000000000000000000000000E4ED64F701000000100EB5AB00A218DA389E18DAB4A118DA246695DAA25F93AC4B6193AC00A218DA01000000E80CD5DA0100000080826AC4389E18DA00000000006293AC0200000002000000010000000000000080BAD4DA5C000000060000000000000070AD18DA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000505793AC
,08-26 15:04:04.247  9138  9138 W google-breakpad: S DA189F80 00000000000000000100000002000000A0E7ABC380836AC4B546DEAB000000000000000044AF6D0700000000E4ED64F700000000100EB5ABC8BA87DAD09F18DA4CA318DAA86695DA0000000000000000F0A318DA000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18A100 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000044AF6D07E4ED64F7F0A118DA100EB5ABA0A218DA00A218DA38C6D4AD5CA218DAE46A95DA00000000000000000000000040B062C400A218DA01000000E0AE18DAF6FFFFFF1C0EB5AB00000000100EB5ABF0A118DA0300000008000000603F67C488FFFFFF40B062C488FFFFFF20C598C385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000001000000044AF6D0730C6D4AD100EB5ABB0A218DAA0A218DAA8A218DA9CA218DA82FFFFFF30C6D4AD8CA218DA385585DA30C6D4ADA8A218DA40B062C488FFFFFFECA218DA20A318DA00A418DA01000000
,08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18A280 B8A218DA00000000ECA218DA20EBA6DAA8A218DA000000000000000040B062C4603F67C488FFFFFF0000000082FFFFFF0100000030C6D4AD0000000082FFFFFF100EB5AB000000006C17C0DA20A318DA10A318DAF0C37DAB88C67DAB100EB5AB00A418DA6C17C0DA5CA318DAB8FA9DDA20A318DA70A318DA4843C5AC27F561F74843C5ACC0AD64F7E4C5D4AD0000000040B062C488FFFFFF100EB5AB0000000020C598C385FFFFFF100EB5AB0000000070A318DA1870C1DA05C6D4AD90A318DA00A418DA80A318DA100EB5AB74A318DA22000000F0C37DABC4A318DAEC6A9FDAE4D8BFDA50DCBFDA58DBD5DA22000000E4C5D4ADCCC5D4AD0000000094A318DA220000000000000018A518DA00000000ACA318DA14355DDA48A418DA18A518DA18C1D6DA10A418DA000000000100000000A418DAF0A318DA22000000100EB5AB54A518DA2894A2DAA0C5D4AD00000000100EB5ABE0A318DA0200000028A418DA403CD3C348A418DA60C792C388FFFFFF0000000082FFFFFF0000000000010000,
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18A400 2200000000000000000000000000000000000000100EB5AB0100000078A518DA88A518DA01000000A0C5D4AD070000000700000001000000C0C398C300000000100EB5AB0000000000000000060000003CC1D6DA3CC1D6DA0600000018C1D6DA00000000FFFFFFFF00000000B0C5D4AD22000000C8C398C30700000000000000010000001800F0DA786AF7AC81FFFFFFB4A418DAE0AA8FDA07000000C0C398C3100EB5AB000000001000F0DAC0A418DAF4A418DAE8EC8FDA0000000000000000000000000CF468DD28A518DA0100000000000000E0CB92C3E01BF1DAC0C398C300000000FFFFFFFF786AF7AC81FFFFFF90A518DAB0F468DDE8A518DA04A518DA50A518DA000000000000000078F468DD4003000001000000FFFFFFFF81FFFFFFC0C398C385FFFFFF1000F0DA85FFFFFF00000000604966C488FFFFFF883CCCDD00000000FFFFFFFFE86AF7AC81FFFFFF90A518DA383FC4DD0000000064A518DA8C49C4DD0000000000000000883CCCDD4202000001000000604966C488FFFFFF
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18A580 00EA62C488FFFFFFC0C398C385FFFFFFECA518DAE86AF7AC883CCCDD01050000C0C398C385FFFFFF00EA62C488FFFFFF604966C488FFFFFF0000000082FFFFFF0000000028616ADD40020000000000005000000030BD62C4F0D9F1DA85FFFFFF1CA618DA34A618DA0000000010A618DA8C49C4DD82010000808666C4010000000000000082FFFFFFC0C398C385FFFFFFBCA618DAC0C2DEAB2CBCC8DD010A0000C0C398C385FFFFFF0000000082FFFFFF808666C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007F0DA85FFFFFFF0D9F1DA85FFFFFF82FFFFFF5818DFDAF0FBF1DAEC6A60DDA000000030BD62C40000000083FFFFFFE86B60DD0200000000000000E8A618DA8C49C4DD02020000C04C66C402000000A0C665C488FFFFFFC0C398C385FFFFFF20E8ABC388FFFFFF5CA718DAA8E720ADBCAC60DD81060000F0D9F1DA85FFFFFF
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18A700 C0C398C385FFFFFFA0C665C488FFFFFFC04C66C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000040A718DA0000000083FFFFFF6800000060CA12C2C8C398C3010000003000000060CA12C20000000080A718DA8C49C4DD82010000E016E8C2010000000000000082FFFFFFC0C398C385FFFFFF04A818DA406971ACFCA460DD81070000C0C398C385FFFFFF0000000082FFFFFFE016E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF20A818DA18A818DA10A818DA84A818DA7800000060CA12C2000000000E474CAC58DBD5DA100EB5AB0000000028A818DA8C49C4DD820100002017E8C2010000000000000082FFFFFFC0C398C385FFFFFF94A818DAB042C9ADDC9A60DD01060000C0C398C385FFFFFF0000000082FFFFFF2017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A0A818DAB8A818DA040000006000000060CA12C2
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18A880 084AC9AD81FFFFFF24A918DAF8FFC3DD00000000B8A818DA8C49C4DD820100004017E8C2010000000000000082FFFFFFC0C398C385FFFFFF24A918DAA83DC9ADE09160DD01060000C0C398C385FFFFFF0000000082FFFFFF4017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000080CB92C300000000E038EDC260000000B0CB92C304000000E86B60DD34A918DA780472DA0400000048A918DA8C49C4DD820100006017E8C2010000000000000082FFFFFF80CB92C388FFFFFFC4A918DAB048C9ADF48860DD0107000080CB92C388FFFFFF0000000082FFFFFF6017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013F1DA85FFFFFFC0C398C385FFFFFF00000000B8A918DAB4A918DA88FFFFFF7000000050CB92C3A0E19EC384E184DA000000000000000004000000E8A918DA8C49C4DD82010000E017E8C20100000070E33BC488FFFFFFC0C792C388FFFFFF44AA18DAA81EE2AD608260DD01050000C0C792C388FFFFFF
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18AA00 70E33BC488FFFFFFE017E8C288FFFFFFC0D3F1DA85FFFFFFA0E19EC30100000074AA18DA8CAA18DA50000000509E4AC20200000048D27DAD64AA18DAC80372DA0000000078AA18DADC7DC7DD820200002078EFC3030000000000000082FFFFFFC0C792C388FFFFFF0000000081FFFFFFA0E19EC388FFFFFF14AB18DAA06C2CADE87266DD01090000A0E19EC388FFFFFF0000000081FFFFFFC0C792C388FFFFFF0000000082FFFFFF2078EFC388FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFC0C3F7C288FFFFFF0000000082FFFFFF0900000081FFFFFFA0E19EC388FFFFFFF0E19EC30000000044AB18DAC0D662C49000000020C062C4E86B60DD02000000E8E885AD81FFFFFF0000000038AB18DA8C49C4DD82010000B00263C401000000A0E19EC388FFFFFF2078EFC388FFFFFFBCAB18DAC8F485ADD07B60DD810700002078EFC388FFFFFFA0E19EC388FFFFFFB00263C488FFFFFFF0E19,EC388FFFFFFC0D662C488FFFFFFC0D062C488FFFFFF0000000082FFFFFF
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18AB80 F0E19EC388FFFFFF0000000082FFFFFFE0AB18DA383FC4DD00000000A4AB18DA78000000509E4AC200000000247260DD420300000300000000000000E8AB18DA8C49C4DD020200004078EFC3020000007069D7C188FFFFFF403CD3C388FFFFFFA0E19EC388FFFFFF54AC18DA808C8AADF07660DD01060000A0E19EC388FFFFFF403CD3C388FFFFFF7069D7C188FFFFFF4078EFC388FFFFFF0000000082FFFFFF0000000082FFFFFF18AC18DAA03564C4F0C498C34011F1DA60000000509E4AC285FFFFFFDCA66ADD85FFFFFF54AC18DA00000000003764C4E8B16ADD800B00008078EFC302000000003764C488FFFFFF403CD3C388FFFFFFA04B9BC388FFFFFF00C598C385FFFFFF50E19EC388FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFFE0C892C3A04B9BC3A03564C480119EC38A00000090CA92C300C598C350E19EC3A04B9BC3A03564C4F0C498C38018F0DAE0119EC309000000C0E7ABC3D0B062C4D0B062C4A04B9BC388FFFFFF090000004011F1DA
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18AD00 09000000003764C4403CD3C390C792C3C0E7ABC388FFFFFF00000000642DA7DD082FA7DD00040000803664C401000000003764C488FFFFFF403CD3C388FFFFFF0000000082FFFFFFF02ADFDA403CD3C360C792C330C792C30000000087FFFFFFA00F63C400C792C330C792C3A0E7ABC3E0FD68DD80020000C03664C4020000000000000082FFFFFFA00F63C488FFFFFF00C792C388FFFFFFD0AD18DA00C792C3A0C692C3D0C692C3FC2069DD80020000003764C400000000A0C692C388FFFFFF701E90C38A00000007000000801E90C3100EB5AB40B062C470119EC3003764C42078C3DD03020000603F67C40100000040B062C488FFFFFF70119EC385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100EB5ABE4ED64F7A8AF18DA0100000081FFFFFF00AF18DA6CAF18DA14C477DA603F67C40000000000000000D0AE18DA84AE18DA3877C3DD
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18AE80 58DBD5DA100EB5ABA8B3BDABECBF18DA00000000000000000000000001000000D4B618DA100EB5AB000118DA00000000B01F69DD00000000603F67C460B318DA0200000001000000F4AE18DA000000000100000081FFFFFF00B118DA0000000538B318DAF6FFFFFF1C0EB5AB01000000100EB5AB00AF18DA000000000800000024AF18DA14A49BDA0000800020000000A8B118DAF87B6AC4000010000000000074AF18DA01000000A8AF18DA100EB5AB783BDFDA80826AC400000000F8C0D4AD6CAF18DA44AF6D0700000000100EB5ABA8AF18DA70AF18DA603F67C480826AC400000000F8C0D4AD94AF18DA2C6595DA00000000B4089DDA02000000E4ED64F701000000100EB5AB68B318DAA0AF18DA1CB318DA246695DAACAF18DA0C099DDA68B318DA01000000E80CD5DA0100000080826AC4A0AF18DA00000000009B9BDA02000000380000002CA860AC2C9A9BDA11AF18DA38000000A0B318DA11B118DA3C000000000000E0E4ED64F7A8B118DA40B018DAF87B6AC4F03BD3C300000000
,08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18B000 FCA760ACF0B79BDA40A860AC1CB018DA010000002CB018DA2CB018DAFFFFFF00010000003CB018DA0800000044A860AC18A860AC4CB860DD58B860DD20809BDA30B860DDF0FFFFFFFFFFFFFF00000000A8B118DADC579F532400000060B860DDA8B118DA84B018DA1000000084B018DA54B118DAA8B018DA54B118DA88B018DAA4B018DAE0067BDA40B860DD58B860DD54B118DA54B118DA707E63C2D8B018DA60A760AC01000000F8BB91AC100EB5AB88BFD4AD01000000F8BB91AC100EB5AB90BFD4AD27F561F790BFD4ADC0AD64F7A8B118DA01000000F8BB91AC100EB5ABF03BD3C3015560F7A0B218DA2CC367DAD8B818DAA8B118DA0CB118DA246B76DA00000000E4ED64F794BC18DA5C3D7BDA80AE91ACBCC0C0DA0D000000C46199AC03000000000000000000000000AB7BDA80AE91AC64C3C0DA18C56ADDA8B118DA0100000080AE91AC60B118DAF87B6AC4F03BD3C328CBD3DA41B062C408B16ADD10000000280000001C0000002C00000000000000F8BB91AC0D000000C46199AC
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18B180 03000000000000000D000000CC7A9BDA0200000001000000A8B118DA000000000000000000000000B8B118DA0000000000000000000000000000000000000000D0B118DA0000000000000000000000000000000000000000E8B118DA000000000000000000000000000000000000000000B218DA00000000000000000000000010B218DA00000000010000000000000020B218DA000000000000000000000000080000000000000038B218DA00000000080000000000000048B218DA00000000080000000000000058B218DA00000000080000000000000068B218DA00000000000000000000000078B218DA00000000000000000500000088B218DA000000000000000002000000020000000000000090BFD4AD0100000001000000000000000000000000000000B8B218DA0000000000000000000000002000000000000000D0B218DA00000000200000000000000001B218DA00000000E8B218DA050000000100000005000000F8B218DA0200000001000000D000000008B318DA44AF6D07
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18B300 E4ED64F758B318DA100EB5AB08B418DA68B318DAF8C0D4ADC4B318DAE46A95DA30B318DA000000000100000040B062C468B318DA0100000048C018DAF6FFFFFF1C0EB5AB00000000100EB5AB58B318DA0300000008000000603F67C488FFFFFF40B062C488FFFFFF70119EC385FFFFFF200000000000000001B318DA00000000702AD3DA18A860AC01AC60AC000060AC702AD3DA18A860AC1000000044AF6D07F0C0D4AD100EB5AB18B418DA08B418DA10B418DA04B418DA82FFFFFFF0C0D4ADF4B318DA385585DAF0C0D4AD10B418DA40B062C488FFFFFF54B418DA88B418DA68B518DA0100000020B418DA0000000054B418DA20EBA6DA10B418DA08000000B8B460AC40B062C4603F67C488FFFFFF0000000082FFFFFF01000000F0C0D4AD0000000082FFFFFF100EB5AB000000006C17C0DA88B418DA78B418DAF0C37DAB88C67DAB100EB5AB68B518DA6C17C0DAC4B418DAB8FA9DDA88B418DAD8B418DA4843C5AC27F561F74843C5ACC0AD64F7A4C0D4AD0000000040B062C488FFFFFF
,08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18B480 100EB5AB0000000070119EC385FFFFFF100EB5AB00000000D8B418DA1870C1DAC5C0D4ADF8B418DA68B518DAE8B418DA100EB5ABDCB418DA22000000F0C37DAB2CB518DAEC6A9FDAE4D8BFDA50DCBFDA58DBD5DA22000000A4C0D4AD8CC0D4AD00000000FCB418DA220000000000000080B618DA0000000014B518DA14355DDAB0B518DA80B618DA18C1D6DA78B518DA000000000100000068B518DA58B518DA22000000100EB5ABBCB618DA2894A2DA60C0D4AD00000000100EB5AB48B518DA0200000090B518DAF03BD3C3B0B518DAF0C192C388FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000100EB5AB01000000E0B618DAF0B618DA0100000060C0D4AD07000000070000000100000010109EC300000000100EB5AB0000000000000000060000003CC1D6DA3CC1D6DA0600000018C1D6DA00000000FFFFFFFF0000000070C0D4AD2200000018109EC30700000000000000010000001800F0DA786AF7AC81FFFFFF1CB618DAE0AA8FDA
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18B600 0700000010109EC3100EB5AB000000001000F0DA28B618DA5CB618DAE8EC8FDA0000000000000000000000000CF468DD90B618DA010000000000000070C692C3E01BF1DA10109EC300000000FFFFFFFF786AF7AC81FFFFFFF8B618DAB0F468DD50B718DA6CB618DAB8B618DA000000000000000078F468DD4003000001000000FFFFFFFF81FFFFFF10109EC385FFFFFF1000F0DA85FFFFFF00000000604966C488FFFFFF883CCCDD00000000FFFFFFFFE86AF7AC81FFFFFFF8B618DA383FC4DD00000000CCB618DA8C49C4DD0000000000000000883CCCDD4202000001000000604966C488FFFFFF00EA62C488FFFFFF10109EC385FFFFFF54B718DAE86AF7AC883CCCDD0105000010109EC385FFFFFF00EA62C488FFFFFF604966C488FFFFFF0000000082FFFFFF0000000028616ADD40020000000000005000000030BD62C4F0D9F1DA85FFFFFF84B718DA9CB718DA0000000078B718DA8C49C4DD82010000808666C4010000000000000082FFFFFF10109EC385FFFFFF24B818DAC0C2DEAB
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18B780 2CBCC8DD010A000010109EC385FFFFFF0000000082FFFFFF808666C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007F0DA85FFFFFFF0D9F1DA85FFFFFF82FFFFFF5818DFDAF0FBF1DAEC6A60DDA000000030BD62C40000000083FFFFFFE86B60DD020000000000000050B818DA8C49C4DD02020000C04C66C402000000A0C665C488FFFFFF10109EC385FFFFFF80E7ABC388FFFFFFC4B818DAA8E720ADBCAC60DD81060000F0D9F1DA85FFFFFF10109EC385FFFFFFA0C665C488FFFFFFC04C66C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000A8B818DA0000000083FFFFFF6800000060CA12C218109EC3010000003000000060CA12C200000000E8B818DA8C49C4DD82010000E016E8C2010000000000000082FFFFFF10109EC385FFFFFF6CB918DA406971ACFCA460DD8107000010109EC385FFFFFF
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18B900 0000000082FFFFFFE016E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF88B918DA80B918DA78B918DAECB918DA7800000060CA12C2000000000E474CAC58DBD5DA100EB5AB0000000090B918DA8C49C4DD820100002017E8C2010000000000000082FFFFFF10109EC385FFFFFFFCB918DAB042C9ADDC9A60DD0106000010109EC385FFFFFF0000000082FFFFFF2017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000008BA18DA20BA18DA040000006000000060CA12C2084AC9AD81FFFFFF8CBA18DAF8FFC3DD0000000020BA18DA8C49C4DD820100004017E8C2010000000000000082FFFFFF10109EC385FFFFFF8CBA18DAA83DC9ADE09160DD0106000010109EC385FFFFFF0000000082FFFFFF4017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000010C692C300000000E038EDC26000000040C692C304000000E86B60DD
08-26 15:04:04.247  9138  9138 W google-breakpad: S DA18BA80 9CBA18DA780472DA04000000B0BA18DA8C49C4DD820100006017E8C2010000000000000082FFFFFF10C692C388FFFFFF2CBB18DAB048C9ADF48860DD0107000010C692C388FFFFFF0000000082FFFFFF6017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013F1DA85FFFFFF10109EC385FFFFFF0000000020BB18DA1CBB18DA88FFFFFF70000000E0C592C3004B9BC384E184DA00000000000000000400000050BB18DA8C49C4DD82010000E017E8C20100000070E33BC488FFFFFF50C292C388FFFFFFACBB18DAA81EE2AD608260DD0105000050C292C388FFFFFF70E33BC488FFFFFFE017E8C288FFFFFFC0D3F1DA85FFFFFF004B9BC301000000DCBB18DAF4BB18DA50000000509E4AC20200000048D27DADCCBB18DAC80372DA00000000E0BB18DADC7DC7DD820200002078EFC3030000000000000082FFFFFF50C292C388FFFFFF0000000081FFFFFF004B9BC388FFFFFF7CBC18D,AA06C2CADE87266DD01090000004B9BC388FFFFFF0000000081FFFFFF
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18BC00 50C292C388FFFFFF0000000082FFFFFF2078EFC388FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF50C3F7C288FFFFFF0000000082FFFFFF0900000081FFFFFF004B9BC388FFFFFF504B9BC300000000ACBC18DAC0D662C49000000020C062C4E86B60DD02000000E8E885AD81FFFFFF00000000A0BC18DA8C49C4DD82010000B00263C401000000004B9BC388FFFFFF2078EFC388FFFFFF24BD18DAC8F485ADD07B60DD810700002078EFC388FFFFFF004B9BC388FFFFFFB00263C488FFFFFF504B9BC388FFFFFFC0D662C488FFFFFFC0D062C488FFFFFF0000000082FFFFFF504B9BC388FFFFFF0000000082FFFFFF48BD18DA383FC4DD000000000CBD18DA78000000509E4AC200000000247260DD42030000030000000000000050BD18DA8C49C4DD020200004078EFC3020000007069D7C188FFFFFFF03BD3C388FFFFFF004B9BC388FFFFFFBCBD18DA808C8AADF07660DD01060000004B9BC388FFFFFFF03BD3C388FFFFFF7069D7C188FFFFFF4078EFC388FFFFFF
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18BD80 0000000082FFFFFF0000000082FFFFFF80BD18DAA03564C440119EC34011F1DA60000000509E4AC285FFFFFFDCA66ADD85FFFFFFBCBD18DA00000000003764C4E8B16ADD800B00008078EFC302000000003764C488FFFFFFF03BD3C388FFFFFF10459BC388FFFFFF50119EC385FFFFFFB04A9BC388FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF81FFFFFF70C392C310459BC3A03564C4701E90C38A00000020C592C350119EC3B04A9BC310459BC3A03564C440119EC38018F0DAD01E90C30900000020E7ABC3D0B062C4D0B062C410459BC388FFFFFF090000004011F1DA09000000003764C4F03BD3C320C292C320E7ABC388FFFFFF00000000642DA7DD082FA7DD00040000803664C401000000003764C488FFFFFFF03BD3C388FFFFFF0000000082FFFFFFF02ADFDAF03BD3C3F0C192C3C0C192C30000000087FFFFFFA00F63C490C192C3C0C192C300E7ABC3E0FD68DD80020000C03664C4020000000000000082FFFFFFA00F63C488FFFFFF90C192C388FFFFFF
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18BF00 6CC018DA90C192C330C192C360C192C3FC2069DD80020000003764C40000000030C192C388FFFFFF00C918DA4800000044BF18DA10C718DA4800000040B062C4601E90C3003764C42078C3DD03020000603F67C40100000040B062C488FFFFFF601E90C385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100EB5ABE4ED64F710C118DA0100000081FFFFFF68C018DAD4C018DA14C477DA603F67C4000000000000000038C018DAECBF18DA3877C3DD58DBD5DA100EB5ABA8B3BDAB54D118DA000000000000000000000000010000003CC818DA100EB5AB0001D5AD00000000B01F69DD00000000603F67C4C8C418DA020000000100000088F5D6AD000000000100000081FFFFFF00AF7DDA786C99ACA0C418DAF6FFFFFF1C0EB5AB01000000100EB5AB68C018DA000000000800000050F7D4AD30F7D4ADD8F5D6AD9A010000C8EBD6AD30F7D4AD
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18C080 80659FAD100DE2ADE4ED64F70100000010C118DA100EB5AB783BDFDA80826AC400000000B8BBD4ADD4C018DA44AF6D0700000000100EB5AB10C118DAD8C018DA603F67C480826AC400000000B8BBD4ADFCC018DA2C6595DA00000000406D99AC00000000E4ED64F701000000100EB5ABD0C418DA08C118DA84C418DA246695DAA25F93AC4B6193ACD0C418DA01000000E80CD5DA0100000080826AC408C118DA00000000006293AC0200000002000000010000000000000080BAD4DA5C000000060000000000000040D018DA000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18C200 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000505793AC0000000000000000010000000200000060E6ABC380836AC4B546DEAB000000000000000044AF6D0700000000E4ED64F700000000100EB5ABC8BA87DAA0C218DA1CC618DAA86695DA0000000000000000C0C618DA000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000,00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18C380 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000044AF6D07E4ED64F7C0C418DA100EB5AB70C518DAD0C418DAB8BBD4AD2CC518DAE46A95DA00000000000000000000000040B062C4D0C418DA01000000B0D118DAF6FFFFFF1C0EB5AB00000000100EB5ABC0C418DA0300000008000000603F67C488FFFFFF40B062C488FFFFFF601E90C385FFFFFF00000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18C500 1000000044AF6D07B0BBD4AD100EB5AB80C518DA70C518DA78C518DA6CC518DA82FFFFFFB0BBD4AD5CC518DA385585DAB0BBD4AD78C518DA40B062C488FFFFFFBCC518DAF0C518DAD0C618DA0100000088C518DA00000000BCC518DA20EBA6DA78C518DA000000000000000040B062C4603F67C488FFFFFF0000000082FFFFFF01000000B0BBD4AD0000000082FFFFFF100EB5AB000000006C17C0DAF0C518DAE0C518DAF0C37DAB88C67DAB100EB5ABD0C618DA6C17C0DA2CC618DAB8FA9DDAF0C518DA40C618DA4843C5AC27F561F74843C5ACC0AD64F764BBD4AD0000000040B062C488FFFFFF100EB5AB00000000601E90C385FFFFFF100EB5AB0000000040C618DA1870C1DA85BBD4AD60C618DAD0C618DA50C618DA100EB5AB44C618DA22000000F0C37DAB94C618DAEC6A9FDAE4D8BFDA50DCBFDA58DBD5DA2200000064BBD4AD4CBBD4AD0000000064C618DA2200000000000000E8C718DA000000007CC618DA14355DDA18C718DAE8C718DA18C1D6DAE0C618DA0000000001000000
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18C680 D0C618DAC0C618DA22000000100EB5AB24C818DA2894A2DA20BBD4AD00000000382B73AC0000000000000000F8C618DA14C718DA18C718DA30C718DA000000000000000082FFFFFF00000000000100002200000000000000000000000000000000C618DA100EB5AB0100000048C818DA58C818DA01D3F1DA20BBD4AD070000000700000001000000001D90C300000020100EB5ABC4C018DAC8731FAC060000003CC1D6DA3CC1D6DA0600000018C1D6DA00000000FFFFFFFF0000000030BBD4AD22000000081D90C30700000000000000010000001800F0DA786AF7AC0100000084C718DAE0AA8FDA07000000001D90C3100EB5AB000000001000F0DA90C718DAC4C718DAE8EC8FDA58D825ADB0D825AD08D925AD0CF468DDF8C718DA0100000068DA25AD00C192C3E01BF1DA001D90C300000000FFFFFFFF786AF7AC0100000060C818DAB0F468DDB8C818DAD4C718DA20C818DA000000000000000078F468DD4003000001000000FFFFFFFF81FFFFFF001D90C385FFFFFF1000F0DA85FFFFFF
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18C800 A8E225AD604966C488FFFFFF883CCCDD00000000FFFFFFFFE86AF7AC0100000060C818DA383FC4DD0000000034C818DA8C49C4DD0000000000000000883CCCDD4202000001000000604966C488FFFFFF00EA62C488FFFFFF001D90C385FFFFFFBCC818DAE86AF7AC883CCCDD01050000001D90C385FFFFFF00EA62C488FFFFFF604966C488FFFFFF0000000082FFFFFF0000000028616ADD40020000000000005000000030BD62C4F0D9F1DA85FFFFFFECC818DA04C918DA00000000E0C818DA8C49C4DD82010000808666C4010000000000000082FFFFFF001D90C385FFFFFF8CC918DAC0C2DEAB2CBCC8DD010A0000001D90C385FFFFFF0000000082FFFFFF808666C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007F0DA85FFFFFFF0D9F1DA85FFFFFF82FFFFFF5818DFDAF0FBF1DAEC6A60DDA000000030BD62C40000000083FFFFFF
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18C980 A01F97C30302000000000000B8C918DA8C49C4DD02020000C04C66C402000000A0C665C488FFFFFF001D90C385FFFFFFE0E6ABC388FFFFFF2CCA18DAA8E720ADBCAC60DD81060000F0D9F1DA85FFFFFF001D90C385FFFFFFA0C665C488FFFFFFC04C66C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000010CA18DA0000000083FFFFFF6800000060CA12C2081D90C3010000003000000060CA12C20000000050CA18DA8C49C4DD82010000E016E8C2010000000000000082FFFFFF001D90C385FFFFFFD4CA18DA406971ACFCA460DD81070000001D90C385FFFFFF0000000082FFFFFFE016E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFF0CA18DAE8CA18DAE0CA18DA54CB18DA7800000060CA12C2000000000E474CAC58DBD5DA100EB5AB00000000F8CA18DA8C49C4DD820100002017E8C2010000000000000082FFFFFF001D90C385FFFFFF64CB18DAB042C9AD
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18CB00 DC9A60DD01060000001D90C385FFFFFF0000000082FFFFFF2017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000070CB18DA88CB18DA040000006000000060CA12C2084AC9AD01000000F4CB18DAF8FFC3DD0000000088CB18DA8C49C4DD820100004017E8C2010000000000000082FFFFFF001D90C385FFFFFFF4CB18DAA83DC9ADE09160DD01060000001D90C385FFFFFF0000000082FFFFFF4017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A0C092C300000000E038EDC260000000D0C092C304000000A01F97C304CC18DA780472DA0400000018CC18DA8C49C4DD820100006017E8C2010000000000000082FFFFFFA0C092C388FFFFFF94CC18DAB048C9ADF48860DD01070000A0C092C388FFFFFF0000000082FFFFFF6017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013F1DA85FFFFFF001D90C385FFFFFF0000000088CC18DA84CC18DA88FFFFFF7000000070C092C3
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18CC80 70449BC384E184DA000000000000000004000000B8CC18DA8C49C4DD82010000E017E8C20100000070E33BC488FFFFFFD01C97C388FFFFFF14CD18DAA81EE2AD608260DD01050000D01C97C388FFFFFF70E33BC488FFFFFFE017E8C288FFFFFFC0D3F1DA85FFFFFF70449BC30100000044CD18DA5CCD18DA50000000509E4AC20302000048D27DAD34CD18DAC80372DA0000000048CD18DADC7DC7DD820200002078EFC3030000000000000082FFFFFFD01C97C388FFFFFF0000000081FFFFFF70449BC388FFFFFFE4CD18DAA06C2CADE87266DD0109000070449BC388FFFFFF0000000081FFFFFFD01C97C388FFFFFF0000000082FFFFFF2078EFC388FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFFE0C2F7C288FFFFFF0000000082FFFFFF0900000081FFFFFF70449BC388FFFFFFC0449BC30000000014CE18DAC0D662C49000000020C062C4A01F97C303020000E8E885AD010000000000000008CE18DA8C49C4DD82010000B00263C40100000070449BC388FFFFFF
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18CE00 2078EFC388FFFFFF8CCE18DAC8F485ADD07B60DD810700002078EFC388FFFFFF70449BC388FFFFFFB00263C488FFFFFFC0449BC388FFFFFFC0D662C488FFFFFFC0D062C488FFFFFF0000000082FFFFFFC0449BC388FFFFFF0000000082FFFFFFB0CE18DA383FC4DD0000000074CE18DA78000000509E4AC200000000247260DD420300000300000000000000B8CE18DA8C49C4DD020200004078EFC3020000007069D7C188FFFFFFA03BD3C388FFFFFF70449BC388FFFFFF24CF18DA808C8AADF07660DD0106000070449BC388FFFFFFA03BD3C388FFFFFF7069D7C188FFFFFF4078EFC388FFFFFF0000000082FFFFFF0000000082FFFFFFCC61C4DD6CCF18DA70CF18DA0000000060000000509E4AC258CF18DA00000000A01F97C3030200000000000050CF18DA8C49C4DD020200008078EFC302000000003764C488FFFFFFA03BD3C388FFFFFF702E97C388FFFFFFECCF18DAE81FE8ACFC74CBDD01090000702E97C388FFFFFFA03BD3C388FFFFFF003764C488FFFFFF8078EFC388FFFFFF
08-26 15:04:04.267  1111  3033 D PMS     : acquireWL(1dae57a6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1111 1000 WorkSource{1000}
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18CF80 0000000082FFFFFF0000000082FFFFFF401E90C385FFFFFF20449BC388FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF80E6ABC388FFFFFFA01F97C388FFFFFF603F67C40100000090000000A01C97C3F4CF18DAE4CF18DA0825DFDA00000000040000003CD218DA082FA7DD00040000803664C401000000003764C488FFFFFFA03BD3C388FFFFFF0000000082FFFFFFF02ADFDAA03BD3C3701C97C3401C97C30000000087FFFFFFA00F63C4101C97C3401C97C360E6ABC3E0FD68DD80020000C03664C4020000000000000082FFFFFFA00F63C488FFFFFF101C97C388FFFFFFA0D018DA101C97C3B01B97C3E01B97C3FC2069DD80020000003764C400000000B01B97C388FFFFFF80AA95C38A0000000700000090AA95C3100EB5AB40B062C4103C90C3003764C42078C3DD03020000603F67C40100000040B062C488FFFFFF103C90C385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.267  1111  3033 V AlarmManager: sending alarm PendingIntent{42e2a0f: PendingIntentRecord{2f12aa9c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=103850, Int=0
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18D100 000000000000000000000000000000000000000000000000100EB5ABE4ED64F778D218DA0100000081FFFFFFD0D118DA3CD218DA14C477DA603F67C40000000000000000A0D118DA54D118DA3877C3DD58DBD5DA100EB5ABA8B3BDABBCE218DA00000000000000000000000001000000A4D918DA100EB5AB0001000000000000B01F69DD00000000603F67C430D618DA020000000100000000000000000000000100000081FFFFFF000000000000000008D618DAF6FFFFFF1C0EB5AB01000000100EB5ABD0D118DA00000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000078D218DA100EB5AB783BDFDA80826AC400000000A0649FAD3CD218DA44AF6D0700000000100EB5AB78D218DA40D218DA603F67C480826AC400000000A0649FAD64D218DA2C6595DA000000000000000000000000E4ED64F701000000100EB5AB38D618DA70D218DAECD518DA246695DAA25F93AC4B6193AC38D618DA01000000E80CD5DA01000000
08-26 15:04:04.267  1111  3033 V AlarmManager: sending alarm PendingIntent{325415e7: PendingIntentRecord{37f7ae15 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=106119, Int=0
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18D280 80826AC470D218DA00000000006293AC0200000002000000010000000000000080BAD4DA5C0000000600000000000000A8E118DA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000505793AC00000000000000000100000002000000C0E5ABC380836AC4B546DEAB000000000000000044AF6D0700000000E4ED64F700000000100EB5ABC8BA87DA08D418DA84D718DAA86695DA
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18D400 000000000000000028D818DA000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18D580 0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000044AF6D07E4ED64F728D618DA100EB5ABD8D618DA38D618DAA0649FAD94D618DAE46A95DA00000000000000000000000040B062C438D618DA0100000018E318DAF6FFFFFF1C0EB5AB00000000100EB5AB28D618DA0300000008000000603F67C488FFFFFF40B062C488FFFFFF103C90C385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000001000000044AF6D0798649FAD100EB5ABE8D618DAD8D618DAE0D618DAD4D618DA82FFFFFF98649FADC4D618DA385585DA98649FADE0D618DA40B062C488FFFFFF24D718DA58D718DA38D818DA01000000F0D618DA0000000024D718DA20EBA6DAE0D618DA000000000000000040B062C4603F67C488FFFFFF0000000082FFFFFF0100000098649FAD0000000082FFFFFF100EB5AB00000000
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18D700 6C17C0DA58D718DA48D718DAF0C37DAB88C67DAB100EB5AB38D818DA6C17C0DA94D718DAB8FA9DDA58D718DAA8D718DA4843C5AC27F561F74843C5ACC0AD64F74C649FAD0000000040B062C488FFFFFF100EB5AB00000000103C90C385FFFFFF100EB5AB00000000A8D718DA1870C1DA6D649FADC8D718DA38D818DAB8D718DA100EB5ABACD718DA22000000F0C37DABFCD718DAEC6A9FDAE4D8BFDA50DCBFDA58DBD5DA220000004C649FAD34649FAD00000000CCD718DA220000000000000050D918DA00000000E4D718DA14355DDA80D818DA50D918DA18C1D6DA48D818DA000000000100000038D818DA28D818DA22000000100EB5AB8CD918DA2894A2DA389C05AD00000000100EB5AB18D818DA0200000060D818DA503BD3C380D818DA001797C388FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000100EB5AB01000000B0D918DAC0D918DA01000000389C05AD070000000700000001000000B03A90C300000000100EB5AB00000000
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18D880 00000000060000003CC1D6DA3CC1D6DA0600000018C1D6DA00000000FFFFFFFF0000000018649FAD22000000B83A90C30700000000000000010000001800F0DA786AF7AC01000000ECD818DAE0AA8FDA07000000B03A90C3100EB5AB000000001000F0DAF8D818DA2CD918DAE8EC8FDA0000000000000000000000000CF468DD60D918DA0100000000000000801B97C3E01BF1DAB03A90C300000000FFFFFFFF786AF7AC01000000C8D918DAB0F468DD20DA18DA3CD918DA88D918DA000000000000000078F468DD4003000001000000FFFFFFFF81FFFFFFB03A90C385FFFFFF1000F0DA85FFFFFF00000000604966C488FFFFFF883CCCDD00000000FFFFFFFFE86AF7AC01000000C8D918DA383FC4DD000000009CD918DA8C49C4DD0000000000000000883CCCDD4202000001000000604966C488FFFFFF00EA62C488FFFFFFB03A90C385FFFFFF24DA18DAE86AF7AC883CCCDD01050000B03A90C385FFFFFF00EA62C488FFFFFF604966C488FFFFFF0000000082FFFFFF0000000028616ADD
08-26 15:04:04.307  1111  1111 D PMS     : releaseWL(1dae57a6): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18DA00 40020000000000005000000030BD62C4F0D9F1DA85FFFFFF54DA18DA6CDA18DA0000000048DA18DA8C49C4DD82010000808666C4010000000000000082FFFFFFB03A90C385FFFFFFF4DA18DAC0C2DEAB2CBCC8DD010A0000B03A90C385FFFFFF0000000082FFFFFF808666C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007F0DA85FFFFFFF0D9F1DA85FFFFFF82FFFFFF5818DFDAF0FBF1DAEC6A60DDA000000030BD62C40000000083FFFFFF301A97C3030200000000000020DB18DA8C49C4DD02020000C04C66C402000000A0C665C488FFFFFFB03A90C385FFFFFF40E6ABC388FFFFFF94DB18DAA8E720ADBCAC60DD81060000F0D9F1DA85FFFFFFB03A90C385FFFFFFA0C665C488FFFFFFC04C66C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000078DB18DA0000000083FFFFFF6800000060CA12C2
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18DB80 B83A90C3010000003000000060CA12C200000000B8DB18DA8C49C4DD82010000E016E8C2010000000000000082FFFFFFB03A90C385FFFFFF3CDC18DA406971ACFCA460DD81070000B03A90C385FFFFFF0000000082FFFFFFE016E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF58DC18DA50DC18DA48DC18DABCDC18DA7800000060CA12C2000000000E474CAC58DBD5DA100EB5AB0000000060DC18DA8C49C4DD820100002017E8C2010000000000000082FFFFFFB03A90C385FFFFFFCCDC18DAB042C9ADDC9A60DD01060000B03A90C385FFFFFF0000000082FFFFFF2017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000D8DC18DAF0DC18DA040000006000000060CA12C2084AC9AD010000005CDD18DAF8FFC3DD00000000F0DC18DA8C49C4DD820100004017E8C2010000000000000082FFFFFFB03A90C385FFFFFF5CDD18DAA83DC9ADE09160DD01060000
08-26 15:04:04.257  9138  9138 W google-breakpad: S DA18DD00 B03A90C385FFFFFF0000000082FFFFFF4017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000201B97C300000000E038EDC260000000501B97C304000000301A97C36CDD18DA780472DA0400000080DD18DA8C49C4DD820100006017E8C2010000000000000082FFFFFF201B97C388FFFFFFFCDD18DAB048C9ADF48860DD01070000201B97C388FFFFFF0000000082FFFFFF6017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013F1DA85FFFFFFB03A90C385FFFFFF00000000F0DD18DAECDD18DA88FFFFFF70000000F01A97C3D02D97C384E184DA00000000000000000400000020DE18DA8C49C4DD82010000E017E8C20100000070E33BC488FFFFFF601797C388FFFFFF7CDE18DAA81EE2AD608260DD01050000601797C388FFFFFF70E33BC488FFFFFFE017E8C288FFFFFFC0D3F1DA85FFFFFFD02D97C301000000ACDE18DAC4DE18DA50000000509E4AC20302000048D27DAD9CDE18DAC80372DA00000000B0DE18DA
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18DE80 DC7DC7DD820200002078EFC3030000000000000082FFFFFF601797C388FFFFFF0000000081FFFFFFD02D97C388FFFFFF4CDF18DAA06C2CADE87266DD01090000D02D97C388FFFFFF0000000081FFFFFF601797C388FFFFFF0000000082FFFFFF2078EFC388FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF70C2F7C288FFFFFF0000000082FFFFFF0900000081FFFFFFD02D97C388FFFFFF202E97C3000000007CDF18DAC0D662C49000000020C062C4301A97C303020000E8E885AD010000000000000070DF18DA8C49C4DD82010000B00263C401000000D02D97C388FFFFFF2078EFC388FFFFFFF4DF18DAC8F485ADD07B60DD810700002078EFC388FFFFFFD02D97C388FFFFFFB00263C488FFFFFF202E97C388FFFFFFC0D662C488FFFFFFC0D062C488FFFFFF0000000082FFFFFF202E97C388FFFFFF0000000082FFFFFF18E018DA383FC4DD00000000DCDF18DA78000000509E4AC200000000247260DD42030000030000000000000020E018DA8C49C4DD02020000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18E000 4078EFC3020000007069D7C188FFFFFF503BD3C388FFFFFFD02D97C388FFFFFF8CE018DA808C8AADF07660DD01060000D02D97C388FFFFFF503BD3C388FFFFFF7069D7C188FFFFFF4078EFC388FFFFFF0000000082FFFFFF0000000082FFFFFFCC61C4DDD4E018DAD8E018DA0000000060000000509E4AC2C0E018DA00000000301A97C30302000000000000B8E018DA8C49C4DD020200008078EFC302000000003764C488FFFFFF503BD3C388FFFFFFE02797C388FFFFFF54E118DAE81FE8ACFC74CBDD01090000E02797C388FFFFFF503BD3C388FFFFFF003764C488FFFFFF8078EFC388FFFFFF0000000082FFFFFF0000000082FFFFFFF03B90C385FFFFFF802D97C388FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFFE0E5ABC388FFFFFF301A97C388FFFFFF603F67C40100000090000000301797C35CE118DA4CE118DA0825DFDA0000000004000000A4E318DA082FA7DD00040000803664C401000000003764C488FFFFFF503BD3C388FFFFFF0000000082FFFFFF
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18E180 F02ADFDA503BD3C3001797C3D01697C30000000087FFFFFFA00F63C4A01697C3D01697C3C0E5ABC3E0FD68DD80020000C03664C4020000000000000082FFFFFFA00F63C488FFFFFFA01697C388FFFFFF08E218DAA01697C3401697C3701697C3FC2069DD80020000003764C400000000401697C388FFFFFF907999C38A00000007000000A07999C3100EB5AB40B062C470AA95C3003764C42078C3DD03020000603F67C40100000040B062C488FFFFFF70AA95C385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100EB5ABE4ED64F7E0E318DA0100000081FFFFFF38E318DAA4E318DA14C477DA603F67C4000000000000000008E318DABCE218DA3877C3DD58DBD5DA100EB5ABA8B3BDAB24F418DA000000000000000000000000010000000CEB18DA100EB5AB0001000000000000B01F69DD00000000603F67C498E718DA0200000001000000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18E300 00000000000000000100000081FFFFFF000000000000000070E718DAF6FFFFFF1C0EB5AB01000000100EB5AB38E318DA000000000800000000000000000000000000000000000000000000000000000000000000000000000000000001000000E0E318DA100EB5AB783BDFDA80826AC400000000D89705ADA4E318DA44AF6D0700000000100EB5ABE0E318DAA8E318DA603F67C480826AC400000000D89705ADCCE318DA2C6595DA000000000000000000000000E4ED64F701000000100EB5ABA0E718DAD8E318DA54E718DA246695DAA25F93AC4B6193ACA0E718DA01000000E80CD5DA0100000080826AC4D8E318DA00000000006293AC0200000002000000010000000000000080BAD4DA5C000000060000000000000010F318DA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18E480 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000505793AC0000000000000000010000000200000020E5ABC380836AC4B546DEAB000000000000000044AF6D0700000000E4ED64F700000000100EB5ABC8BA87DA70E518DAECE818DAA86695DA000000000000000090E918DA0000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18E600 000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000044AF6D07E4ED64F790E718DA100EB5AB40E818DAA0E718DAD89705ADFCE718DAE46A95DA00000000000000000000000040B062C4A0E718DA0100000080F418DAF6FFFFFF1C0EB5AB00000000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18E780 100EB5AB90E718DA0300000008000000603F67C488FFFFFF40B062C488FFFFFF70AA95C385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000001000000044AF6D07D09705AD100EB5AB50E818DA40E818DA48E818DA3CE818DA82FFFFFFD09705AD2CE818DA385585DAD09705AD48E818DA40B062C488FFFFFF8CE818DAC0E818DAA0E918DA0100000058E818DA000000008CE818DA20EBA6DA48E818DA000000000000000040B062C4603F67C488FFFFFF0000000082FFFFFF01000000D09705AD0000000082FFFFFF100EB5AB000000006C17C0DAC0E818DAB0E818DAF0C37DAB88C67DAB100EB5ABA0E918DA6C17C0DAFCE818DAB8FA9DDAC0E818DA10E918DA4843C5AC27F561F74843C5ACC0AD64F7849705AD0000000040B062C488FFFFFF100EB5AB0000000070AA95C385FFFFFF100EB5AB0000000010E918DA1870C1DAA59705AD30E918DAA0E918DA20E918DA100EB5AB14E918DA22000000F0C37DAB64E918DAEC6A9FDA
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18E900 E4D8BFDA50DCBFDA58DBD5DA22000000849705AD6C9705AD0000000034E918DA2200000000000000B8EA18DA000000004CE918DA14355DDAE8E918DAB8EA18DA18C1D6DAB0E918DA0000000001000000A0E918DA90E918DA22000000100EB5ABF4EA18DA2894A2DA409705AD00000000100EB5AB80E918DA02000000C8E918DA003BD3C3E8E918DA901197C388FFFFFF0000000082FFFFFF00000000000100002200000000000000000000000000000000000000100EB5AB0100000018EB18DA28EB18DA01000000409705AD07000000070000000100000010A995C300000000100EB5AB0000000000000000060000003CC1D6DA3CC1D6DA0600000018C1D6DA00000000FFFFFFFF00000000509705AD2200000018A995C30700000000000000010000001800F0DA786AF7AC0100000054EA18DAE0AA8FDA0700000010A995C3100EB5AB000000001000F0DA60EA18DA94EA18DAE8EC8FDA0000000000000000000000000CF468DDC8EA18DA0100000000000000101697C3E01BF1DA10A995C3
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18EA80 00000000FFFFFFFF786AF7AC0100000030EB18DAB0F468DD88EB18DAA4EA18DAF0EA18DA000000000000000078F468DD4003000001000000FFFFFFFF81FFFFFF10A995C385FFFFFF1000F0DA85FFFFFF00000000604966C488FFFFFF883CCCDD00000000FFFFFFFFE86AF7AC0100000030EB18DA383FC4DD0000000004EB18DA8C49C4DD0000000000000000883CCCDD4202000001000000604966C488FFFFFF00EA62C488FFFFFF10A995C385FFFFFF8CEB18DAE86AF7AC883CCCDD0105000010A995C385FFFFFF00EA62C488FFFFFF604966C488FFFFFF0000000082FFFFFF0000000028616ADD40020000000000005000000030BD62C4F0D9F1DA85FFFFFFBCEB18DAD4EB18DA00000000B0EB18DA8C49C4DD82010000808666C4010000000000000082FFFFFF10A995C385FFFFFF5CEC18DAC0C2DEAB2CBCC8DD010A000010A995C385FFFFFF0000000082FFFFFF808666C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18EC00 0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007F0DA85FFFFFFF0D9F1DA85FFFFFF82FFFFFF5818DFDAF0FBF1DAEC6A60DDA000000030BD62C40000000083FFFFFFC01497C3030200000000000088EC18DA8C49C4DD02020000C04C66C402000000A0C665C488FFFFFF10A995C385FFFFFFA0E5ABC388FFFFFFFCEC18DAA8E720ADBCAC60DD81060000F0D9F1DA85FFFFFF10A995C385FFFFFFA0C665C488FFFFFFC04C66C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC1030000E0EC18DA0000000083FFFFFF6800000060CA12C218A995C3010000003000000060CA12C20000000020ED18DA8C49C4DD82010000E016E8C2010000000000000082FFFFFF10A995C385FFFFFFA4ED18DA406971ACFCA460DD8107000010A995C385FFFFFF0000000082FFFFFFE016E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC0ED18DAB8ED18DA
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18ED80 B0ED18DA24EE18DA7800000060CA12C2000000000E474CAC58DBD5DA100EB5AB00000000C8ED18DA8C49C4DD820100002017E8C2010000000000000082FFFFFF10A995C385FFFFFF34EE18DAB042C9ADDC9A60DD0106000010A995C385FFFFFF0000000082FFFFFF2017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000040EE18DA58EE18DA040000006000000060CA12C2084AC9AD01000000C4EE18DAF8FFC3DD0000000058EE18DA8C49C4DD820100004017E8C2010000000000000082FFFFFF10A995C385FFFFFFC4EE18DAA83DC9ADE09160DD0106000010A995C385FFFFFF0000000082FFFFFF4017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000B01597C300000000E038EDC260000000E01597C304000000C01497C3D4EE18DA780472DA04000000E8EE18DA8C49C4DD820100006017E8C2010000000000000082FFFFFFB01597C388FFFFFF64EF18DAB048C9ADF48860DD01070000B01597C388FFFFFF
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18EF00 0000000082FFFFFF6017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0700000081FFFFFF8013F1DA85FFFFFF10A995C385FFFFFF0000000058EF18DA54EF18DA88FFFFFF70000000801597C3402797C384E184DA00000000000000000400000088EF18DA8C49C4DD82010000E017E8C20100000070E33BC488FFFFFFF01197C388FFFFFFE4EF18DAA81EE2AD608260DD01050000F01197C388FFFFFF70E33BC488FFFFFFE017E8C288FFFFFFC0D3F1DA85FFFFFF402797C30100000014F018DA2CF018DA50000000509E4AC20302000048D27DAD04F018DAC80372DA0000000018F018DADC7DC7DD820200002078EFC3030000000000000082FFFFFFF01197C388FFFFFF0000000081FFFFFF402797C388FFFFFFB4F018DAA06C2CADE87266DD01090000402797C388FFFFFF0000000081FFFFFFF01197C388FFFFFF0000000082FFFFFF2078EFC388FFFFFF0900000084FFFFFF0000000082FFFFFF0000000081FFFFFF00C2F7C288FFFFFF0000000082FFFFFF0900000081FFFFFF
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18F080 402797C388FFFFFF902797C300000000E4F018DAC0D662C49000000020C062C4C01497C303020000E8E885AD0100000000000000D8F018DA8C49C4DD82010000B00263C401000000402797C388FFFFFF2078EFC388FFFFFF5CF118DAC8F485ADD07B60DD810700002078EFC388FFFFFF402797C388FFFFFFB00263C488FFFFFF902797C388FFFFFFC0D662C488FFFFFFC0D062C488FFFFFF0000000082FFFFFF902797C388FFFFFF0000000082FFFFFF80F118DA383FC4DD0000000044F118DA78000000509E4AC200000000247260DD42030000030000000000000088F118DA8C49C4DD020200004078EFC3020000007069D7C188FFFFFF003BD3C388FFFFFF402797C388FFFFFFF4F118DA808C8AADF07660DD01060000402797C388FFFFFF003BD3C388FFFFFF7069D7C188FFFFFF4078EFC388FFFFFF0000000082FFFFFF0000000082FFFFFFCC61C4DD3CF218DA40F218DA0000000060000000509E4AC228F218DA00000000C01497C3030200000000000020F218DA8C49C4DD02020000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18F200 8078EFC302000000003764C488FFFFFF003BD3C388FFFFFF502197C388FFFFFFBCF218DAE81FE8ACFC74CBDD01090000502197C388FFFFFF003BD3C388FFFFFF003764C488FFFFFF8078EFC388FFFFFF0000000082FFFFFF0000000082FFFFFF50AA95C385FFFFFFF02697C388FFFFFF0900000081FFFFFF0900000081FFFFFF0900000081FFFFFF40E5ABC388FFFFFFC01497C388FFFFFF603F67C40100000090000000C01197C3C4F218DAB4F218DA0825DFDA00000000040000000CF518DA082FA7DD00040000803664C401000000003764C488FFFFFF003BD3C388FFFFFF0000000082FFFFFFF02ADFDA003BD3C3901197C3601197C30000000087FFFFFFA00F63C4301197C3601197C320E5ABC3E0FD68DD80020000C03664C4020000000000000082FFFFFFA00F63C488FFFFFF301197C388FFFFFF70F318DA301197C3D01097C3001197C3FC2069DD80020000003764C400000000D01097C388FFFFFF50C999C38A0000000700000060C999C3100EB5AB40B062C4807999C3003764C4
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18F380 2078C3DD03020000603F67C40100000040B062C488FFFFFF807999C385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000100EB5ABE4ED64F748F518DA0100000081FFFFFFA0F418DA0CF518DA14C477DA603F67C4000000000000000070F418DA24F418DA3877C3DD58DBD5DA100EB5ABA8B3BDAB8C0519DA0000000000000000000000000100000074FC18DA100EB5AB0001000000000000B01F69DD00000000603F67C400F918DA020000000100000000000000000000000100000081FFFFFF0000000000000000D8F818DAF6FFFFFF1C0EB5AB01000000100EB5ABA0F418DA00000000080000000000000000000000000000000000000000000000000000000000000000000000000000000100000048F518DA100EB5AB783BDFDA80826AC400000000989205AD0CF518DA44AF6D0700000000100EB5AB48F518DA10F518DA603F67C480826AC4
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18F500 00000000989205AD34F518DA2C6595DA000000000000000000000000E4ED64F701000000100EB5AB08F918DA40F518DABCF818DA246695DAA25F93AC4B6193AC08F918DA01000000E80CD5DA0100000080826AC440F518DA00000000006293AC0200000002000000010000000000000080BAD4DA5C0000000600000000000000780419DA000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18F680 00000000505793AC0000000000000000010000000200000080E4ABC380836AC4B546DEAB000000000000000044AF6D0700000000E4ED64F700000000100EB5ABC8BA87DAD8F618DA54FA18DAA86695DA0000000000000000F8FA18DA00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18F800 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000044AF6D07E4ED64F7F8F818DA100EB5ABA8F918DA08F918DA989205AD64F918DAE46A95DA00000000000000000000000040B062C408F918DA01000000E80519DAF6FFFFFF1C0EB5AB00000000100EB5ABF8F818DA0300000008000000603F67C488FFFFFF40B062C488FFFFFF807999C385FFFFFF000000000000000000000000000000000000000000000000000000000000000000000000000000001000000044AF6D07909205AD100EB5ABB8F918DAA8F918DAB0F918DAA4F918DA82FFFFFF909205AD94F918DA385585DA909205ADB0F918DA40B062C488FFFFFFF4F918DA28FA18DA
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18F980 08FB18DA01000000C0F918DA00000000F4F918DA20EBA6DAB0F918DA000000000000000040B062C4603F67C488FFFFFF0000000082FFFFFF01000000909205AD0000000082FFFFFF100EB5AB000000006C17C0DA28FA18DA18FA18DAF0C37DAB88C67DAB100EB5AB08FB18DA6C17C0DA64FA18DAB8FA9DDA28FA18DA78FA18DA4843C5AC27F561F74843C5ACC0AD64F7449205AD0000000040B062C488FFFFFF100EB5AB00000000807999C385FFFFFF100EB5AB0000000078FA18DA1870C1DA659205AD98FA18DA08FB18DA88FA18DA100EB5AB7CFA18DA22000000F0C37DABCCFA18DAEC6A9FDAE4D8BFDA50DCBFDA58DBD5DA22000000449205AD2C9205AD000000009CFA18DA220000000000000020FC18DA00000000B4FA18DA14355DDA50FB18DA20FC18DA18C1D6DA18FB18DA000000000100000008FB18DAF8FA18DA22000000100EB5AB5CFC18DA2894A2DA009205AD00000000100EB5ABE8FA18DA0200000030FB18DAB03AD3C350FB18DA102C93C388FFFFFF0000000082FFFFFF
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18FB00 00000000000100002200000000000000000000000000000000000000100EB5AB0100000080FC18DA90FC18DA01000000009205AD070000000700000001000000207899C300000000100EB5AB0000000000000000060000003CC1D6DA3CC1D6DA0600000018C1D6DA00000000FFFFFFFF00000000109205AD22000000287899C30700000000000000010000001800F0DA786AF7AC01000000BCFB18DAE0AA8FDA07000000207899C3100EB5AB000000001000F0DAC8FB18DAFCFB18DAE8EC8FDA0000000000000000000000000CF468DD30FC18DA0100000000000000A01097C3E01BF1DA207899C300000000FFFFFFFF786AF7AC0100000098FC18DAB0F468DDF0FC18DA0CFC18DA58FC18DA000000000000000078F468DD4003000001000000FFFFFFFF81FFFFFF207899C385FFFFFF1000F0DA85FFFFFF00000000604966C488FFFFFF883CCCDD00000000FFFFFFFFE86AF7AC0100000098FC18DA383FC4DD000000006CFC18DA8C49C4DD0000000000000000883CCCDD4202000001000000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18FC80 604966C488FFFFFF00EA62C488FFFFFF207899C385FFFFFFF4FC18DAE86AF7AC883CCCDD01050000207899C385FFFFFF00EA62C488FFFFFF604966C488FFFFFF0000000082FFFFFF0000000028616ADD40020000000000005000000030BD62C4F0D9F1DA85FFFFFF24FD18DA3CFD18DA0000000018FD18DA8C49C4DD82010000808666C4010000000000000082FFFFFF207899C385FFFFFFC4FD18DAC0C2DEAB2CBCC8DD010,A0000207899C385FFFFFF0000000082FFFFFF808666C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF3007F0DA85FFFFFFF0D9F1DA85FFFFFF82FFFFFF5818DFDAF0FBF1DAEC6A60DDA000000030BD62C40000000083FFFFFF402F93C30302000000000000F0FD18DA8C49C4DD02020000C04C66C402000000A0C665C488FFFFFF207899C385FFFFFF00E5ABC388FFFFFF64FE18DAA8E720ADBCAC60DD81060000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18FE00 F0D9F1DA85FFFFFF207899C385FFFFFFA0C665C488FFFFFFC04C66C488FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFFC103000048FE18DA0000000083FFFFFF6800000060CA12C2287899C3010000003000000060CA12C20000000088FE18DA8C49C4DD82010000E016E8C2010000000000000082FFFFFF207899C385FFFFFF0CFF18DA406971ACFCA460DD81070000207899C385FFFFFF0000000082FFFFFFE016E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF28FF18DA20FF18DA18FF18DA8CFF18DA7800000060CA12C2000000000E474CAC58DBD5DA100EB5AB0000000030FF18DA8C49C4DD820100002017E8C2010000000000000082FFFFFF207899C385FFFFFF9CFF18DAB042C9ADDC9A60DD01060000207899C385FFFFFF0000000082FFFFFF2017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF00000000A8FF18DAC0FF18DA04000000
08-26 15:04:04.267  9138  9138 W google-breakpad: S DA18FF80 6000000060CA12C2084AC9AD010000002C0019DAF8FFC3DD00000000C0FF18DA8C49C4DD820100004017E8C2010000000000000082FFFFFF207899C385FFFFFF2C0019DAA83DC9ADE09160DD01060000207899C385FFFFFF0000000082FFFFFF4017E8C288FFFFFF0000000082FFFFFF0000000082FFFFFF0000000082FFFFFF
08-26 15:04:04.267  9138  9138 W google-breakpad: C 06000040588AB9AB00000000448018DAC08018DA188018DA6C8018DA100EB5AB448018DAC0CE9DC385FFFFFFF0C37DAB3C8018DA008018DA088018DA782985DA7C2985DA10000F200000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
08-26 15:04:04.277  9138  9138 W google-breakpad: M AAB57000 00000000 00003000 845A91E0117C7AECBD5AEDFF0F15331D0 app_process32
08-26 15:04:04.277  9138  9138 W google-breakpad: M DA30B000 00000000 00A60000 886D6DA606BAF6E3428F775AFDA8BFB00 libjxcore.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E1D9B000 00000000 01A66000 02ED9811FCF64CCF917969B967D6C4D90 libwebviewchromium.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E819B000 00000000 00698000 D9D0B53223CEFC9DCDDD08D322DA9D840 libllvm-glnext.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8842000 00000000 00259000 A8F1E556348AEFAD1C106B4006A27E610 libGLESv2_adreno.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8E80000 00000000 0000A000 519F4FBB19AF6F56454A7618BD382D630 libqdutils.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8E8A000 00000000 0001B000 68801872D531A43011451250F1F30D060 libvorbisidec.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8EA5000 00000000 00004000 2D20AD2AF70917F2323F8CEFA22146320 libstagefright_yuv.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8EA9000 00000000 00022000 9FFD84F83CDFCEACD5EBCBC70695D8630 libstagefright_omx.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8ECD000 00000000 00003000 03B0255D304C04BA1CB893EF055C0D880 libstagefright_enc_common.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8ED0000 00000000 00007000 BE9998F628EA6A5C32345D001998B9DE0 libstagefright_avc_common.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8ED7000 00000000 0000A000 B7C8EF000A088989586213A2A509D8F80 libqservice.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8EE1000 00000000 00039000 34D438CC59B243B4B79B29B3200A98C30 libopus.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8F1A000 00000000 00006000 4C1BDB1923831CC1BBEB2964FE8D5EFE0 libmemalloc.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8F20000 00000000 0001A000 FF39416944553983C63CEF39AA58A4B30 libdrmframework.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8F3A000 00000000 0000E000 65B4EE8C28DFCF943EF3BAB5CE2CF57E0 libstagefright_amrnb_common.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E8F48000 00000000 0016A000 D9745D7F4CAD61ED021F4A8004E0CEC20 libstagefright.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E90B3000 00000000 00019000 E750DEE2E12603D0AD816986AAF645710 libmtp.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E90CC000 00000000 0000B000 FAFD83B761593A286FA8D7A17F0659BC0 libjhead.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E90D8000 00000000 0002C000 AB902A0868517033CA4534CD7DCC60020 libexif.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M E9105000 00000000 00041000 00E46F00D3E4889F2E902160B7B0CEC70 libmedia_jni.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EE855000 00000000 00003000 1DF7708108CEED636BFE9B204BF12F740 libwebviewchromium_loader.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EE858000 00000000 00003000 80B32B0876CF3F38D2FD0F46F035FEAE0 libjnigraphics.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EE85B000 00000000 00008000 F5D3384E9BEEEDF600C2C4D02CB7146A0 libcompiler_rt.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EE863000 00000000 00011000 892DC0C8AA2DB695C92A0FD89FD616490 libandroid.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EE874000 00000000 00010000 F069BC3B7FF3E2F52BE4C0513283D1570 eglSubDriverAndroid.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EE885000 00000000 00023000 C9460E393AA4141EC1B76CF5BB2CC1370 libGLESv1_CM_adreno.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EE8A8000 00000000 00035000 C9308334F0BE658661CFCEAF33A944BF0 libgsl.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EE8DD000 00000000 0000F000 7E3A026F8D2588C278B22435FA5C10C20 libEGL_adreno.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EE9F2000 00000000 00006000 A3F1396F22C3FBDA91EDFDAFB7CF2E120 gralloc.msm8994.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EEAEA000 00000000 00007000 8E32A4A6115195D297D2AE94D71BC6E70 libaudioeffect_jni.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EEAF1000 00000000 00004000 DDE93E59B3E4C9F7F6E9E9B6387B90710 libsoundpool.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EEAF5000 00000000 00003000 842756D12623A78FA5769C158B761FF20 libqdMetaData.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EEBF9000 00000000 00009000 9C8B8478BC8C8443093BA1E45DF71C230 librs_jni.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EECD9000 00000000 00018000 C914D522E8F13E857F27B6F081F7C3CE0 libjavacrypto.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M EECF2000 00000000 00005000 31D0D5792A084ED66168EA163F5214510 libadreno_utils.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F15D9000 00000000 00038000 C771D0C5D8C4AAE1D29E991A67ABA1B10 libjavacore.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F1666000 00000000 00003000 900F180B6ED1813B019148541FEBC4850 memtrack.msm8994.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F1669000 00000000 00004000 A5D156DB5288811021E8A33ADD46575D0 libhtcflag-jni.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F45F1000 00000000 00004000 F6B8E3B47357B4905A70F8F4DCDDF95F0 libwebviewchromium_plat_support.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F57AE000 00000000 00009000 A5D85B5892F9A1A903015DBE386CB43B0 libbacktrace_libc++.so
,08-26 15:04:04.277  9138  9138 W google-breakpad: M F57B7000 00000000 002F4000 96F5DF89C0637A5E62C4F738FC06270A0 libart.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F5AB0000 00000000 00003000 9258F0DE2668790937DBED7BAB5D46F00 libcnefeatureconfig.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F5AB3000 00000000 00006000 1838F9CFFA4D98540A18FF441F74BE920 libvendorconn.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F5AD9000 00000000 00005000 89B5E9B7BF6412D458C721055A152C4A0 libpowermanager.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F5ADE000 00000000 0000F000 D5ED9236D25CE04149331D781E23A60C0 libcommon_time_client.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F5AEE000 00000000 0003D000 44006AD458EF9C9176B1A4A29861696A0 libbcinfo.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F5B2B000 00000000 00024000 DB890D95C5D797FF2741B358BE0774920 libbcc.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F5B6F000 00000000 008FE000 23E127C4962B88183F53FBC88857580C0 libLLVM.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6474000 00000000 00004000 9A82E5E5DC0FF6464E020C95D6C265430 libunwind-ptrace.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6478000 00000000 0000E000 E63BF21914855A13D3378C6DB4998F740 libunwind.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F64CC000 00000000 00007000 9AD603917CEBD0A26C5300A4455555250 libgccdemangle.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F64D3000 00000000 00012000 F53050926856F9ED174D0B9FB54900510 libpcre.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F64E5000 00000000 0008C000 262AD069242F1BA1B83D5B95DD777DA40 libc++.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6572000 00000000 00027000 D2F918C617291E9143BFDB2AFAF842D20 libpng.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6599000 00000000 00059000 54828C4F4B56D81127BD1BAF9A48D64E0 libft2.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F65F3000 00000000 00016000 341AA222654FF8CDCA03539F11E752C90 libstagefright_foundation.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6609000 00000000 0000A000 B447D91C23CD5983C557B47FAA3A997F0 libnbaio.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6614000 00000000 00006000 6AC3328D55BE7167DD1549E59E88D8420 libgabi++.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F661A000 00000000 0001D000 A298BBC5FCB452A442DEA311927DF68E0 libRScpp.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6637000 00000000 00038000 ACEEF006458B7ACD28DDF807EF906BC50 libRS.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F666F000 00000000 00005000 79A5A019DA71D1BF014B80AA8C55BFFB0 libwpa_client.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6674000 00000000 00009000 8E5AD42C3F1E54FB7DDD170EA771276C0 libhostapd_client.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F667D000 00000000 00003000 7C24A254F6B1768D1FF8ADFB9A8A11500 libsync.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6680000 00000000 00006000 20E951BEE083EAAC8A0EC8C9659BC90C0 libspeexresampler.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6686000 00000000 0006D000 07CC805CFD246906AD1D1909740021BF0 libGLES_trace.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F66F3000 00000000 00008000 EDC9EED92248BEE38066E5CDBFE0B2D50 libbacktrace.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F66FB000 00000000 00018000 F5FE4EF4E136FE6B8489E4B9D841950E0 libz.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6713000 00000000 00004000 62EFD3D29964E6B599D4FAE01272421C0 libusbhost.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6717000 00000000 0000C000 661D044FA1EABB6A2BCE722F951338280 libui.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6724000 00000000 00036000 A86B4524AFE0B8B31C00A4A9DA14FB720 libstlport.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F675A000 00000000 0003F000 7A4675082455FF26D470C5F4B56B88020 libssl.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6799000 00000000 0005F000 AC3C9B059AFE93342F46FD137B909CD90 libsqlite.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F67F9000 00000000 0000E000 DD9CC624EF32ACC1510AB3DEA32715310 libsoundtrigger.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6807000 00000000 00050000 EC16351BBCFD02238537E51BAE2784340 libsonivox.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F685C000 00000000 00216000 56390A1B7E94AAC78CEC15E6A5BA76940 libskia.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6A77000 00000000 0000E000 0F80236AB9F6769373119190B01663370 libselinux.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6A85000 00000000 00004000 099B10F2EAA0144B6769F0BF764BE16D0 libprocessgroup.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6A89000 00000000 00447000 F96B93EA164BBEFDAF535E908AE475720 libpdfium.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6ED5000 00000000 00007000 34BC97F86C64F306A8DF4132F83E6EAC0 libnetutils.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6EDC000 00000000 00004000 A9EE204019CC7FA50899C1B1442527890 libnetd_client.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6EE0000 00000000 00007000 EC0FC93DE477C0F0F2458259F8891BA10 libnativehelper.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6EE8000 00000000 00004000 662D697635E5195DB4DF18CD75FA054D0 libnativebridge.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6EED000 00000000 0000B000 DBBB717A5F3CC6510448A962FA32BB5F0 libminikin.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6EF8000 00000000 00003000 3A297E4800A3E2A2881399ECB557DD800 libmemtrack.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6EFB000 00000000 000A2000 55F0F895C5BC068C4AAD60C55DFCF5AE0 libmedia.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6F9D000 00000000 00031000 5E853F759F0F20B2C46E95661CD23ABF0 libjpeg.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F6FCE000 00000000 0003C000 A599020C324FFC7F5CB801ECE8E8310E0 libinputflinger.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F700A000 00000000 0001B000 26C21B7FB032D330D7855FE57A4D007A0 libinput.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7025000 00000000 0000E000 F53A4FC8B77980603D72451B64F3D6110 libimg_utils.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7033000 00000000 000FF000 24A805FAC98E37E83FCF24292570AD690 libicuuc.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7136000 00000000 0014A000 30D014A51C507F017588CD57CC7ABDAD0 libicui18n.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7280000 00000000 0004D000 507D78B3420976289860AD0B3F0ACB330 libhwui.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F72CD000 00000000 00004000 B10F6B2DE42715DA716F1D0B3B5635A00 libhtc_framework.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F72D2000 00000000 00064000 0A4C86F854CC1FC940A2604EB3703BB50 libharfbuzz_ng.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7336000 00000000 00009000 4506E5AEC4C973594DB4C29971148F4E0 libhardware_legacy.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7340000 00000000 00003000 4D02055D5873A4955D03859291CA4C3B0 libhardware.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7343000 00000000 00053000 CC9DA8810CBD4C5FBE31AB5FA7D334C50 libgui.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7396000 00000000 00017000 D1B32BE53493EE80553E5CF9729A5E320 libexpat.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F73AD000 00000000 000F6000 1363343978E1296E7E5A282BD01D879F0 libcrypto.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F74A5000 00000000 00008000 FD57B8136C27C9D6253B9E1E69379E950 libcamera_metadata.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F74AD000 00000000 00043000 6B348D31CD7CF862108B47EDF1282EE30 libcamera_client.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F74F0000 00000000 00006000 CED7F01912102B3BFE6FA6093F5033210 libaudioutils.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F74F6000 00000000 00027000 CD9DB99DE0AC6F91F22B3E87F8B6AEF80 libandroidfw.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F751D000 00000000 0000B000 E2F67EE50006FD0ED1482E1463C5CCFF0 libGLESv2.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7528000 00000000 00007000 EFE6ADDAF48E0BCED48FF0E60558C2F60 libGLESv1_CM.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7530000 00000000 00004000 C10A3FF24BC314BDB4276E3588B5CFEF0 libETC1.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7534000 00000000 00072000 7F140791AF5F874B8A135FA08C394E6F0 libEGL.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F75AA000 00000000 0001B000 9D4601377F890562B43B8557CA1E59AD0 libutils.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F75C5000 00000000 00004000 D44FDF94BA8D734E5BC46C426F7316DE0 libstdc++.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F75C9000 00000000 00018000 3D2BCD0A8F5E726801091CC87EA86DCC0 libm.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F75E1000 00000000 00007000 A0FE122CCC678B9B85060712A986C8D30 liblog.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F75E8000 00000000 0000E000 DE79B2144B88DC7BF88B9100A3C22CB10 libcutils.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F75F6000 00000000 00058000 E8B875F2B201B77B1EFB370EC51E10E30 libc.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7657000 00000000 0002E000 C73D9FD86B5330724FAEFFF007795F020 libbinder.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7685000 00000000 000E5000 DBD36D9DDD496308CE41288BE3A23BC20 libandroid_runtime.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F776B000 00000000 00004000 14FB3981D027F378CECC0975450EB7720 libNimsWrap.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F776F000 00000000 00003000 FC041B2A9367C325B68638D180B8219F0 libsigchain.so
08-26 15:04:04.277  9138  9138 W google-breakpad: M F7778000 00000000 00010000 D98FB28404D6C2368A1250B419733BB20 linker
08-26 15:04:04.277  9138  9138 W google-breakpad: -----END BREAKPAD MICRODUMP-----
08-26 15:04:04.287  8715  8715 D AlarmReceiver: ACTION_RESTART_INTENT
08-26 15:04:04.297  8715  8715 D LocalBluetoothProfile: getPriorityOnValue = 100
08-26 15:04:04.297  8715  8715 D LocalBluetoothProfile: getPriorityOffValue = 0
08-26 15:04:04.297  8715  8715 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-26 15:04:04.297  8715  8715 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-26 15:04:04.307  9047  9102 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 15:04:04.307  9047  9102 W google-breakpad: Chrome build fingerprint:
08-26 15:04:04.307  9047  9102 W google-breakpad: 0.0.1
08-26 15:04:04.307  9047  9102 W google-breakpad: 19
08-26 15:04:04.307  9047  9102 W google-breakpad: c6a9b5a3-5dc3-4032-b912-7f888aba1a90
08-26 15:04:04.307  9047  9102 W google-breakpad: ### ### ### ### ### ### ### ### ### ### ### ### ###
08-26 15:04:04.307  9047  9102 E chromium: ### WebView Version 42.0.2311.137 (code 52311137)
08-26 15:04:04.307  9047  9102 F libc    : Fatal signal 11 (SIGSEGV), code -6, fault addr 0x2357 in tid 9102 (Thread-208)
08-26 15:04:04.307  9047  9102 W libc    : Security Level: (1), Debug inforamtion is controlled by the DUMPABLE flag.
08-26 15:04:04.317  8715  9140 D HtcModeClient: start the htcmodeservice thread
08-26 15:04:04.317  8715  9140 D HtcModeClient: initCanAgent
08-26 15:04:04.317   522   522 I DEBUG   : *** *** *** *** *** *** *** *** *** *** *** *** *** *** *** ***
08-26 15:04:04.317   522   522 I DEBUG   : Build fingerprint: 'htc/himauhl_tmo_pl/htc_himauhl:5.1/LMY47O/576832.180:user/release-keys'
08-26 15:04:04.317   522   522 I DEBUG   : Revision: '0'
08-26 15:04:04.317   522   522 I DEBUG   : ABI: 'arm'
08-26 15:04:04.317   522   522 I DEBUG   : pid: 9047, tid: 9102, name: Thread-208  >>> com.test.thalitest <<<
08-26 15:04:04.317   522   522 I DEBUG   : signal 11 (SIGSEGV), code -6 (SI_TKILL), fault addr 0x4
08-26 15:04:04.327  8715  9140 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-26 15:04:04.327  8715  9140 D HtcModeClient: sense info: version = none, id = 2
08-26 15:04:04.327  8715  9140 D HtcModeClient: display info: width = 1080, height = 1776
08-26 15:04:04.327  8715  9140 D HtcModeClient: display info: mode = 10
08-26 15:04:04.337   522   522 I DEBUG   :     r0 abb98a58  r1 00000000  r2 da188044  r3 da1880c0
08-26 15:04:04.337   522   522 I DEBUG   :     r4 da188018  r5 da18806c  r6 abb50e10  r7 da188044
08-26 15:04:04.337   522   522 I DEBUG   :     r8 c39dcec0  r9 ffffff85  sl ab7dc3f0  fp da18803c
08-26 15:04:04.337   522   522 I DEBUG   :     ip da188000  sp da188008  lr da852978  pc da85297c  cpsr 200f0010
08-26 15:04:04.337   522   522 I DEBUG   : 
08-26 15:04:04.337   522   522 I DEBUG   : backtrace:
08-26 15:04:04.337   522   522 I DEBUG   :     #00 pc 0054797c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_SetPropertyById(JSContext*, JS::Handle<JSObject*>, JS::Handle<jsid>, JS::Handle<JS::Value>)+44)
08-26 15:04:04.337   522   522 I DEBUG   :     #01 pc 00547e1c  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (JS_SetProperty(JSContext*, JS::Handle<JSObject*>, char const*, JS::Handle<JS::Value>)+132)
08-26 15:04:04.337   522   522 I DEBUG   :     #02 pc 00762754  /data/app/com.test.thalitest-1/lib/arm/libjxcore.so (MozJS::Value::SetProperty(char const*, JS::Handle<JS::Value>)+88)
,08-26 15:04:04.427  8715  8715 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,08-26 15:04:04.427  8715  8715 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-26 15:04:04.427  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false
,08-26 15:04:04.427  8715  8715 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-26 15:04:04.427  8715  8715 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
,08-26 15:04:04.427  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = false
08-26 15:04:04.427  8715  8715 D HtcModeClient: connectState: Force_AWAKE = false
08-26 15:04:04.427  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = true
08-26 15:04:04.427  8715  8715 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-26 15:04:04.757  1111  9142 E ActivityManager: App crashed! Process: com.test.thalitest,
,08-26 15:04:04.757   522   522 W HTCLOG  : use specified tag [DEBUG], func [0].
08-26 15:04:04.757  1111  1167 I BootReceiver: Copying /data/tombstones/tombstone_04 to DropBox (SYSTEM_TOMBSTONE),
08-26 15:04:04.757   522   522 W HTCLOG  : mask=0x18
,08-26 15:04:04.777  1111  9142 W ActivityManager:   Force finishing activity 1 com.test.thalitest/.MainActivity,
,08-26 15:04:04.787   494   494 E lowmemorykiller: Error writing /proc/9047/oom_score_adj; errno=22,
,08-26 15:04:04.857  1111  4139 I WindowState: WIN DEATH: Window{2b17af6e u0 com.test.thalitest/com.test.thalitest.MainActivity},
08-26 15:04:04.857  1111  3076 D WifiService: Client connection lost with reason: 4
08-26 15:04:04.857  1111  1133 I ActivityManager: Recipient 9047
,08-26 15:04:04.867  1111  1133 I ActivityManager: Process com.test.thalitest (pid 9047) has died
,08-26 15:04:06.117  7723  7764 W System.err: org.apache.http.conn.ConnectTimeoutException: Connect to /54.83.203.254:7000 timed out,
08-26 15:04:06.117  7723  7764 W System.err: 	at org.apache.http.conn.scheme.PlainSocketFactory.connectSocket(PlainSocketFactory.java:138)
08-26 15:04:06.117  7723  7764 W System.err: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:149)
,08-26 15:04:06.127  7723  7764 W System.err: 	,at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:169)
08-26 15:04:06.127  7723  7764 W System.err: ,	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:124)
08-26 15:04:06.127  7723  7764 W System.err: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:377)
08-26 15:04:06.127  7723  7764 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:759)
08-26 15:04:06.127  7723  7764 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:524)
08-26 15:04:06.127  7723  7764 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:502)
08-26 15:04:06.127  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.HttpSender.connect(HttpSender.java:351)
08-26 15:04:06.127  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.HttpSender.connectByGet(HttpSender.java:222)
08-26 15:04:06.127  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.LogLib.getLoggerPolicy(LogLib.java:190)
08-26 15:04:06.127  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.BDILoggerPolicyServiceManager.requestPolicy(BDILoggerPolicyServiceManager.java:137)
08-26 15:04:06.127  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.ULoggerThreadImpl$3.run(ULoggerThreadImpl.java:201)
08-26 15:04:06.127  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.ULoggerThreadImpl.run(ULoggerThreadImpl.java:92)
08-26 15:04:06.127  7723  7764 D libc    : [NET] android_getaddrinfofornet+,hn 41(0x6563322d35342d),sn(),hints(known),family 0,flags 4
08-26 15:04:06.127  7723  7764 D libc    : [NET] android_getaddrinfofornet-, err=8
08-26 15:04:06.127  7723  7764 D libc    : [NET] android_getaddrinfofornet+,hn 41(0x6563322d35342d),sn(),hints(known),family 0,flags 1024
08-26 15:04:06.127  7723  7764 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-26 15:04:06.127  7723  7764 D libc    : [NET] android_getaddrinfo_proxy+
08-26 15:04:06.127  7723  7764 D libc    : [NET] android_getaddrinfo_proxy get netid:0
08-26 15:04:06.127   518  9144 D libc    : [NET] android_getaddrinfofornet+,hn 41(0x6563322d35342d),sn(),hints(known),family 0,flags 1024
08-26 15:04:06.137   518  9144 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
08-26 15:04:06.137   518  9144 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
08-26 15:04:06.137   518  9144 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,08-26 15:04:06.137  7723  7764 D libc    : [NET] android_getaddrinfo_proxy-, success
,08-26 15:04:06.137  7723  7764 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x35342e38332e32),sn(),hints(known),family 0,flags 4
08-26 15:04:06.137  7723  7764 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,08-26 15:04:06.437  8715  9140 I HtcModeClient: handler message = 4011,
08-26 15:04:06.437  8715  9140 D HtcModeClient: getConnectionCheckCount first 0
08-26 15:04:06.437  8715  9140 D HtcModeClient: getConnectionCheckCount count = 9
08-26 15:04:06.437  8715  9140 E HtcModeClient: Check connection and retry 10 times.
,08-26 15:04:06.437  8715  9140 D HtcModeClient: setConnectionCheckCount count = 10
,08-26 15:04:06.437  8715  9140 D HtcModeClient: setupRestart delayedTime = 3000
,08-26 15:04:06.447  8715  8715 D HtcModeClient: setBtPriority priority = on
08-26 15:04:06.447  8715  8715 D HtcModeClient: unbindBlueToothService
08-26 15:04:06.447  8715  8715 D HtcModeClient: Don't start project servcice
,08-26 15:04:06.447  8715  8715 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-26 15:04:06.447  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false
08-26 15:04:06.447  8715  8715 D SilentMusic: call stop
08-26 15:04:06.447  8715  8715 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-26 15:04:06.447  8715  9141 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-26 15:04:06.457  8715  8715 D HtcModeClient: onDestroy,
,08-26 15:04:11.447  1111  3033 D PMS     : acquireWL(177e532c): PARTIAL_WAKE_LOCK  *alarm* 0x1 1111 1000 WorkSource{10027},
08-26 15:04:11.447  1111  3033 V AlarmManager: sending alarm PendingIntent{3e2901f5: PendingIntentRecord{37f7ae15 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=113300, Int=0,
08-26 15:04:11.457  8715  8715 D AlarmReceiver: ACTION_RESTART_INTENT,
,08-26 15:04:11.477  1111  1111 D PMS     : releaseWL(177e532c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027},
,08-26 15:04:11.477  8715  8715 D LocalBluetoothProfile: getPriorityOnValue = 100
,08-26 15:04:11.477  8715  8715 D LocalBluetoothProfile: getPriorityOffValue = 0
08-26 15:04:11.477  8715  8715 D Utils   : CMD:getprop ro.htc.htcmode.socket.type,
,08-26 15:04:11.487  8715  8715 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1),
,08-26 15:04:11.527  8715  9146 D HtcModeClient: start the htcmodeservice thread
,08-26 15:04:11.527  8715  9146 D HtcModeClient: initCanAgent
,08-26 15:04:11.527  8715  9146 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-26 15:04:11.527  8715  9146 D HtcModeClient: sense info: version = none, id = 2
,08-26 15:04:11.527  8715  9146 D HtcModeClient: display info: width = 1080, height = 1776
,08-26 15:04:11.527  8715  9146 D HtcModeClient: display info: mode = 10
,08-26 15:04:11.627  8715  8715 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-26 15:04:11.627  8715  8715 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-26 15:04:11.627  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false
08-26 15:04:11.627  8715  8715 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-26 15:04:11.627  8715  8715 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-26 15:04:11.627  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = false
08-26 15:04:11.627  8715  8715 D HtcModeClient: connectState: Force_AWAKE = false
08-26 15:04:11.627  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = true
08-26 15:04:11.627  8715  8715 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-26 15:04:12.117  3547  3735 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>,
08-26 15:04:12.117  3547  3735 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
,08-26 15:04:13.637  8715  9146 I HtcModeClient: handler message = 4011,
08-26 15:04:13.637  8715  9146 D HtcModeClient: getConnectionCheckCount first 0
08-26 15:04:13.647  8715  9146 D HtcModeClient: getConnectionCheckCount count = 10,
08-26 15:04:13.647  8715  9146 E HtcModeClient: Check connection and retry 11 times.,
,08-26 15:04:13.657  8715  9146 D HtcModeClient: setConnectionCheckCount count = 11
08-26 15:04:13.657  8715  9146 D HtcModeClient: setupRestart delayedTime = 3000
,08-26 15:04:13.667  8715  8715 D HtcModeClient: setBtPriority priority = on,
08-26 15:04:13.667  8715  8715 D HtcModeClient: unbindBlueToothService
08-26 15:04:13.667  8715  8715 D HtcModeClient: Don't start project servcice
,08-26 15:04:13.667  8715  8715 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-26 15:04:13.677  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false,
08-26 15:04:13.677  8715  8715 D SilentMusic: call stop
,08-26 15:04:13.677  8715  8715 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,08-26 15:04:13.677  8715  9147 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-26 15:04:13.687  8715  8715 D HtcModeClient: onDestroy,
,08-26 15:04:18.347   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 15:04:18.667  1111  3033 D PMS     : acquireWL(2cf21e2): PARTIAL_WAKE_LOCK  *alarm* 0x1 1111 1000 WorkSource{1000}
,08-26 15:04:18.687  8715  8715 D AlarmReceiver: ACTION_RESTART_INTENT
08-26 15:04:18.667  1111  1111 D PMS     : acquireWL(25507973): PARTIAL_WAKE_LOCK  *backup* 0x1 1111 1000 null
08-26 15:04:18.677  1111  3033 V AlarmManager: sending alarm PendingIntent{a36f030: PendingIntentRecord{bb314a9 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1472216654738, Int=0
,08-26 15:04:18.677  1111  3033 V AlarmManager: sending alarm PendingIntent{2f417a2e: PendingIntentRecord{37f7ae15 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=120517, Int=0
,08-26 15:04:18.697  1111  3145 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
08-26 15:04:18.697  1111  3145 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
08-26 15:04:18.697  1111  3145 D PMS     : releaseWL(25507973): PARTIAL_WAKE_LOCK  *backup* 0x1 null
08-26 15:04:18.697  1111  1111 D PMS     : releaseWL(2cf21e2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
,08-26 15:04:18.697  8715  8715 D LocalBluetoothProfile: getPriorityOnValue = 100,
08-26 15:04:18.697  8715  8715 D LocalBluetoothProfile: getPriorityOffValue = 0
08-26 15:04:18.697  8715  8715 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-26 15:04:18.697  8715  8715 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-26 15:04:18.727  8715  9149 D HtcModeClient: start the htcmodeservice thread,
08-26 15:04:18.737  8715  9149 D HtcModeClient: initCanAgent
,08-26 15:04:18.737  8715  9149 I CANMesgAgentLocalSocket: CANAgent Id = 0,
,08-26 15:04:18.737  8715  9149 D HtcModeClient: sense info: version = none, id = 2
,08-26 15:04:18.737  8715  9149 D HtcModeClient: display info: width = 1080, height = 1776,
08-26 15:04:18.737  8715  9149 D HtcModeClient: display info: mode = 10
,08-26 15:04:18.827  8715  8715 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-26 15:04:18.837  8715  8715 D HtcModeClient: connectState: BT_TURNON_BYME = false,
08-26 15:04:18.837  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false
08-26 15:04:18.837  8715  8715 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false,
08-26 15:04:18.837  8715  8715 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-26 15:04:18.837  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = false,
,08-26 15:04:18.837  8715  8715 D HtcModeClient: connectState: Force_AWAKE = false
08-26 15:04:18.837  8715  8715 D HtcModeClient: connectState: PHONE_PULGIN = true,
,08-26 15:04:18.837  8715  8715 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-26 15:04:20.857  8715  9149 I HtcModeClient: handler message = 4011,
08-26 15:04:20.857  8715  9149 D HtcModeClient: getConnectionCheckCount first 0
,08-26 15:04:20.857  8715  9149 D HtcModeClient: getConnectionCheckCount count = 11
08-26 15:04:20.857  8715  9149 E HtcModeClient: Check connection and retry 12 times. Time out!,
,08-26 15:04:20.867  8715  9149 D HtcModeClient: setConnectionCheckCount count = 0
,08-26 15:04:20.867  8715  9149 D HtcModeClient: cancelRestart
,08-26 15:04:20.877  8715  8715 D HtcModeClient: setBtPriority priority = on
,08-26 15:04:20.877  8715  8715 D HtcModeClient: unbindBlueToothService
08-26 15:04:20.877  8715  8715 D HtcModeClient: Don't start project servcice
,08-26 15:04:20.877  8715  8715 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-26 15:04:20.887  8715  8715 D HtcModeClient: connectState: CONNECTION_READY = false,
08-26 15:04:20.887  8715  8715 D SilentMusic: call stop
08-26 15:04:20.887  8715  8715 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-26 15:04:20.887  8715  9150 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-26 15:04:20.907  8715  8715 D HtcModeClient: onDestroy,
,08-26 15:04:28.347   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 15:04:36.147  7723  7764 W System.err: org.apache.http.conn.ConnectTimeoutException: Connect to /54.83.203.254:7000 timed out,
08-26 15:04:36.147  7723  7764 W System.err: 	at org.apache.http.conn.scheme.PlainSocketFactory.connectSocket(PlainSocketFactory.java:138)
08-26 15:04:36.147  7723  7764 W System.err: 	at org.apache.http.impl.conn.DefaultClientConnectionOperator.openConnection(DefaultClientConnectionOperator.java:149)
08-26 15:04:36.147  7723  7764 W System.err: 	at org.apache.http.impl.conn.AbstractPoolEntry.open(AbstractPoolEntry.java:169)
08-26 15:04:36.147  7723  7764 W System.err: 	at org.apache.http.impl.conn.AbstractPooledConnAdapter.open(AbstractPooledConnAdapter.java:124)
,08-26 15:04:36.147  7723  7764 W System.err: 	at org.apache.http.impl.client.DefaultRequestDirector.execute(DefaultRequestDirector.java:377)
08-26 15:04:36.147  7723  7764 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:759)
08-26 15:04:36.147  7723  7764 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:524)
08-26 15:04:36.147  7723  7764 W System.err: 	at org.apache.http.impl.client.AbstractHttpClient.execute(AbstractHttpClient.java:502)
08-26 15:04:36.147  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.HttpSender.connect(HttpSender.java:351)
08-26 15:04:36.157  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.Loglib.HttpSender.connectByGet(HttpSender.java:222)
08-26 15:04:36.157  7723  7764 W System.err: 	,at com.htc.studio.software.BDILogger.Loglib.LogLib.getLoggerPolicy(LogLib.java:190)
08-26 15:04:36.157  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.BDILoggerPolicyServiceManager.requestPolicy(BDILoggerPolicyServiceManager.java:137)
,08-26 15:04:36.157  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.ULoggerThreadImpl$3.run(ULoggerThreadImpl.java:201)
,08-26 15:04:36.157  7723  7764 W System.err: 	at com.htc.studio.software.BDILogger.ULoggerThreadImpl.run(ULoggerThreadImpl.java:92)
,08-26 15:04:38.397  1111  1158 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA,
08-26 15:04:38.397  1111  1158 D GpsLocationProvider: [handleDownloadXtraData] mNetworkAvailable:true mDisableXtraDownload:false mNavigating:false mEngineOn:false mForceXtraInject:true
,08-26 15:04:38.397  1111  1158 D PMS     : acquireWL(2ec293c7): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 1111 1000 null,
,08-26 15:04:38.417  1111  4580 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 4,
08-26 15:04:38.417  1111  4580 D libc    : [NET] android_getaddrinfofornet-, err=8
08-26 15:04:38.417  1111  4580 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
08-26 15:04:38.417  1111  4580 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-26 15:04:38.417  1111  4580 D libc    : [NET] android_getaddrinfo_proxy+
08-26 15:04:38.417  1111  4580 D libc    : [NET] android_getaddrinfo_proxy get netid:0
08-26 15:04:38.427   518  9151 D libc    : [NET] android_getaddrinfofornet+,hn 23(0x78747261706174),sn(),hints(known),family 0,flags 1024
08-26 15:04:38.427   518  9151 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604,
,08-26 15:04:38.477   518  9151 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS),
08-26 15:04:38.477   518  9151 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
08-26 15:04:38.487  1111  4580 D libc    : [NET] android_getaddrinfo_proxy-, success
08-26 15:04:38.487  1111  4580 D libc    : [NET] android_getaddrinfofornet+,hn 13(0x35322e38342e31),sn(),hints(known),family 0,flags 4
,08-26 15:04:38.487  1111  4580 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
,08-26 15:04:38.557  1111  4580 D GpsLocationProvider: [handleDownloadXtraData] calling native_inject_xtra_data,
,08-26 15:04:38.927  1111  3444 D GpsLocationProvider: [reportHTCStatus] eventMask = 3 , status = 0,
08-26 15:04:38.927  1111  3444 D GpsLocationProvider: [reportHTCStatus] INJECT_XTRA_DATA, status: 0
08-26 15:04:38.927  1111  4580 D PMS     : acquireWL(347c792): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 1111 1000 null
08-26 15:04:38.927  1111  4580 D GpsLocationProvider:  [handleDownloadXtraData]inject done.
08-26 15:04:38.937  1111  4580 D PMS     : releaseWL(2ec293c7): PARTIAL_WAKE_LOCK  GpsLocationProviderXTRA Download 0x1 null,
08-26 15:04:38.937  1111  1158 D GpsLocationProvider: [handleMessage] DOWNLOAD_XTRA_DATA_FINISHED,
08-26 15:04:38.937  1111  1158 D PMS     : releaseWL(347c792): PARTIAL_WAKE_LOCK  GpsLocationProvider 0x1 null,
,08-26 15:04:40.037  1111  1132 D PMS     : releaseWL(3cf6f02c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,08-26 15:04:43.357   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:04:49.097  1111  1111 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 ,
,08-26 15:05:02.237  1111  3494 D PMS     : acquireWL(314aa563): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
08-26 15:05:02.247  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:05:02.237  1111  3494 I BatteryService: n_update end
08-26 15:05:02.247  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:05:02.237  1111  3494 D PMS     : releaseWL(314aa563): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:05:02.247  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:05:02.247  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:05:02.247  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:05:02.257  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:05:02.257  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:05:02.257  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:05:02.257  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:05:02.257  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:05:02.257  1111  1111 D HtcPowerSaver: Checking...
08-26 15:05:02.257  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:05:02.257  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:05:02.257  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:05:02.257  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:05:02.257  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:05:02.267  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:05:02.257  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:05:02.257  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:05:02.257  1111  3076 D WifiController: handleMessage: X
,08-26 15:05:02.267  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,08-26 15:05:02.267  1111  1111 I HtcPowerSaver: << updateStatus
,08-26 15:05:02.307  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-26 15:05:02.307  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:05:02.307  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:05:02.307  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-26 15:05:02.307  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:05:02.507  8161  8161 D HtcThemeUtils: Unregister com.htc.musicenhancer.EnhancerService$1@1ab92188 for type 1,
08-26 15:05:02.517  8161  8161 D HtcThemeUtils: Unregister com.htc.musicenhancer.EnhancerService$1@1ab92188 for type 0
,08-26 15:05:02.537  1111  3519 D Process : killProcessQuiet, pid=8161,
08-26 15:05:02.537  1111  3519 I ActivityManager: Killing 8161:com.htc.music:musicenhancer/u0a24 (adj 15): empty #17
08-26 15:05:02.537  1111  3519 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-26 15:05:02.627  1111  3348 I ActivityManager: Recipient 8161,
,08-26 15:05:03.367   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-26 15:05:06.337  3547  3547 D TelephonyReceiver: switchBindHtcMsgCursor: null,
,08-26 15:05:13.867  1111  3033 D PMS     : acquireWL(8bec560): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1111 1000 WorkSource{1000},
08-26 15:05:13.867  1111  3033 V AlarmManager: sending alarm PendingIntent{42e2a0f: PendingIntentRecord{2f12aa9c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=163850, Int=0
08-26 15:05:13.917  1111  3033 I ActivityManager: Start proc 9154:com.htc.sense.mms/u0a51 for service com.htc.sense.mms/.transaction.TransactionService
08-26 15:05:13.917  1111  3033 V AlarmManager: sending alarm PendingIntent{219d7a19: PendingIntentRecord{1396cade com.htc.sense.mms startService}}, i=android.intent.action.ACTION_ONALARM, t=0, cnt=1, w=1472216713873, Int=0
,08-26 15:05:13.947  9154  9154 W HTCLOG  : use specified tag [FDManager], func [0].
08-26 15:05:13.947  9154  9154 W HTCLOG  : mask=0x18
,08-26 15:05:13.957  1111  1111 D PMS     : releaseWL(8bec560): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,08-26 15:05:13.997  9154  9154 D MessageFrequencyProvider: onCreate
,08-26 15:05:14.017  9154  9154 D MessageCustFlag: sense_version=7.0
,08-26 15:05:14.017  9154  9154 V GetPrviateResource: GetPrviateResource
08-26 15:05:14.017  9154  9154 V GetPrviateResource: GetPrviateResource
,08-26 15:05:14.017  9154  9154 D RcsChatUtils: isSup> false
,08-26 15:05:14.017  3568  3568 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
08-26 15:05:14.017  3568  3568 I ThreadedRenderer: Defer allocateBuffers to drawing time
,08-26 15:05:14.027  9154  9154 D n       : createReceiver,
08-26 15:05:14.027  9154  9154 D n       : registerReceiver return intent = null
,08-26 15:05:14.057  9154  9154 W HTCLOG  : use specified tag [asset], func [0].,
08-26 15:05:14.057  9154  9154 W HTCLOG  : mask=0x18
08-26 15:05:14.057  9154  9154 W asset   : Asset path /data/data/com.htc.launcher/files/.htc_theme/CResources.apk is neither a directory nor file (type=0).
08-26 15:05:14.057  9154  9154 D HtcThemeUtils: AssetMaanger addAssetPath CResources fail!
08-26 15:05:14.057  9154  9154 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@3006a746 for type 0
,08-26 15:05:14.057  9154  9154 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@3006a746 for type 1
08-26 15:05:14.067  9154  9154 D HtcThemeUtils: Register com.htc.sense.mms.util.aj@3006a746 for type 5
,08-26 15:05:14.067  9154  9154 V TransactionService: 1-Creating TransactionService
,08-26 15:05:14.067  9154  9154 V TransactionService: onStartCommand: 1,
08-26 15:05:14.067  9154  9154 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
08-26 15:05:14.077  9154  9177 V TransactionService: 4-Handling incoming message: { when=-1ms what=2 arg1=1 target=com.htc.sense.mms.transaction.au }
08-26 15:05:14.077  9154  9177 V TransactionService: Loading previous transactions.
,08-26 15:05:14.087  3547  4655 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103,
,08-26 15:05:14.097  9154  9177 D TransactionService: Force clearing mTransactionList,
08-26 15:05:14.097  9154  9177 D TransactionService: Force set service start id to 1
08-26 15:05:14.097  9154  9177 V TransactionService: stopSelfIfIdle
,08-26 15:05:14.097  9154  9177 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
08-26 15:05:14.097  9154  9154 V TransactionService: Destroying TransactionService
,08-26 15:05:14.097  1111  1133 D Process : killProcessQuiet, pid=7701
08-26 15:05:14.097  1111  1133 I ActivityManager: Killing 7701:com.google.android.music:main/u0a115 (adj 15): empty #17
08-26 15:05:14.097  1111  1133 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-26 15:05:14.217  1111  4139 I ActivityManager: Recipient 7701,
08-26 15:05:14.217  1111  5330 D MediaRouterService: Client com.google.android.music (pid 7701): Died!
,08-26 15:05:14.317  9154  9177 V TransactionService: 4-Handling incoming message: { when=-218ms what=100 target=com.htc.sense.mms.transaction.au },
,08-26 15:05:14.327  9154  9177 V Scheduler: Scheduler safely quits looper.
,08-26 15:05:16.087  9154  9154 D MessageUtils: [isPackageExists] packageName: com.htc.vvm.att does not exist,
08-26 15:05:16.087  9154  9154 D MessageCustFlag: sku_id=58,
,08-26 15:05:16.097  9154  9154 D ReportIndicatorCache: startAsyncQueryReports --- , first = true,
,08-26 15:05:16.097  9154  9176 D ReportIndicatorCache: MSG_QUERY_REPORTS >>,
,08-26 15:05:16.107  3547  3566 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64,
08-26 15:05:16.107  3547  3566 D MmsSmsV2Provider:  slotId = -1
08-26 15:05:16.107  3547  3566 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select _id,msg_id from addr where (type = 129 or type = 130 or type = 151) , selectionArgs: null
,08-26 15:05:16.127  3547  3992 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
,08-26 15:05:16.137  9154  9180 D Messaging: mNeedToUpdateDate2 start,
,08-26 15:05:16.137  9154  9154 D SettingsManager: init() new MmsApp.getAppliction()com.htc.sense.mms.MmsApp@39032d7a
08-26 15:05:16.137  9154  9175 D MmsAsyncWorkHandler: 
08-26 15:05:16.137  9154  9175 D MmsAsyncWorkHandler: HM tk = 20002
08-26 15:05:16.147  9154  9154 D DraftCache: [DraftCache/1] DraftCache.constructor
08-26 15:05:16.147  9154  9154 D DraftCache: [DraftCache/1] refresh
08-26 15:05:16.147  9154  9183 D MmsConfig: Start to get Carrier ID
08-26 15:05:16.147  9154  9154 D MmsConfig: networkCode: 
08-26 15:05:16.157  9154  9185 D Messaging: ViewCache CreatePreloadOnlyConversationList
08-26 15:05:16.157  9154  9185 D MessageCustFlag: sense_version=7.0
08-26 15:05:16.157  9154  9185 D Jerry   : start to preload cursor >>>>>>>
08-26 15:05:16.167  3547  4655 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
08-26 15:05:16.167  3547  4655 D MmsSmsV2Provider:  slotId = -1
08-26 15:05:16.167  3547  4655 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from contact_threads where htc_category =1 or htc_category = 2 , selectionArgs: null
,08-26 15:05:16.167  3547  3566 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
08-26 15:05:16.167  3547  3566 D MmsSmsV2Provider:  slotId = -1
08-26 15:05:16.167  3547  3566 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM sms WHERE date2 = 0 , selectionArgs: null,
,08-26 15:05:16.177  3547  3993 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 81
,08-26 15:05:16.177  9154  9182 I Messaging: mccmnc> 
,08-26 15:05:16.177  9154  9154 D HfmClient: getIHFMServiceHMSApiLevel: +++
,08-26 15:05:16.177  3547  4655 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
08-26 15:05:16.177  3547  4655 D MmsSmsV2Provider:  slotId = -1
08-26 15:05:16.177  9154  9154 E HfmClient: Failed to load meta-data, NameNotFound: com.htc.hfm
08-26 15:05:16.177  9154  9154 E HfmClient: getIHFMServiceHMSApiLevel: load meta-data from HtcSpeak
,08-26 15:05:16.187  9154  9154 D HfmClient: getIHFMServiceHMSApiLevel: Level = 1,
08-26 15:05:16.187  9154  9154 D HfmClient: HfmServiceHMS API Level = 1
,08-26 15:05:16.187  3547  3566 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
08-26 15:05:16.187  3547  3566 D MmsSmsV2Provider:  slotId = -1
08-26 15:05:16.187  3547  3566 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: select count(1) from blocklist , selectionArgs: null,
,08-26 15:05:16.187  3547  3547 D IccSmsInterfaceManager: [IccSmsInterfaceManager] Cannot get carrier id
,08-26 15:05:16.197  9154  9183 D MmsConfig: Carrier ID is NULL,
08-26 15:05:16.197  3547  3992 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 80
08-26 15:05:16.197  3547  3992 D MmsSmsV2Provider:  slotId = -1
08-26 15:05:16.197  3547  3992 D MmsSmsV2Provider: URI_RAW_QUERY -- selection: SELECT count(1) FROM pdu WHERE date2 = 0 , selectionArgs: null
08-26 15:05:16.197  9154  9181 D Messaging: mNeedCloseSecureBox: truemAlreadyQuerySecureMessage: true
,08-26 15:05:16.197  9154  9180 D Messaging: mNeedToUpdateDate2: false
,08-26 15:05:16.197  3547  3566 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
,08-26 15:05:16.207  9154  9185 D Messaging: ViewCache CreatePreload
08-26 15:05:16.207  9154  9185 D Messaging: ViewCache CreatePreloadOnlyMultipleOpsList,
,08-26 15:05:16.207  9154  9154 D ew      : createReceiver
,08-26 15:05:16.217  9154  9154 D HtcBuildUtils: getRATByHtcTelephonyCapability:1
,08-26 15:05:16.217  9154  9154 W SystemReader: Cannot find support_cw, use default value instead
,08-26 15:05:16.217  1111  4139 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
08-26 15:05:16.217  9154  9154 W SystemReader: Cannot find qct_8960_interface, use default value instead
,08-26 15:05:16.217  9154  9189 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
08-26 15:05:16.217  9154  9185 D Cust_MMSMS: _has_set_default_values_2=true
08-26 15:05:16.217  3547  3567 D TelephUtils: UPDATE for  <hidden uri>  [ com.htc.sense.mms ] tid: 65
08-26 15:05:16.217  3547  3567 V MmsProvider: Update uri=content://mms, match=0
08-26 15:05:16.217  3547  3567 V MmsProvider: selection=st=129 AND m_type!=134
,08-26 15:05:16.217  9154  9191 D Messaging: Reset downloading state: 0
,08-26 15:05:16.227  9154  9189 D ew      : HtcStorageHelper.getPhoneStorageDir = /storage/emulated/0
,08-26 15:05:16.227  9154  9185 D TextSizeManager: [get_list_body_TextSize]__size57
08-26 15:05:16.227  9154  9185 D TextSizeManager: [get_list_body_TextSize]__size48
08-26 15:05:16.227  9154  9185 D TextSizeManager: [get_list_body_TextSize]__size0
08-26 15:05:16.227  9154  9185 D TextSizeManager: [get_list_body_TextSize]__size57
08-26 15:05:16.227  9154  9185 D TextSizeManager: [get_list_body_TextSize]__size66
08-26 15:05:16.227  9154  9185 D TextSizeManager: [get_list_body_TextSize]__size74
,08-26 15:05:16.227  9154  9185 D TextSizeManager: [get_list_body_TextSize]__size83
08-26 15:05:16.227  9154  9189 D ew      : /storage/emulated/0 : mounted
,08-26 15:05:16.227  9154  9185 D MsgPreferenceUtils: def_index: 0
08-26 15:05:16.227  1111  1133 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
,08-26 15:05:16.227  9154  9175 D DraftCache: [DraftCache/191] rebuildCache
08-26 15:05:16.227  9154  9189 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
08-26 15:05:16.227  9154  9185 D MsgPreferenceUtils: globalIndex = 2
08-26 15:05:16.227  3547  4655 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
08-26 15:05:16.227  3547  4655 D Jerry   : URI_DRAFT
08-26 15:05:16.227  1111  1132 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
,08-26 15:05:16.237  9154  9185 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
08-26 15:05:16.237  9154  9191 V Messaging: Start TransactionService after 2 minutes from now
,08-26 15:05:16.237  9154  9175 D DraftCache: hasDraft() = false mNeedNotifyChange = true
08-26 15:05:16.237  9154  9175 D DraftCache: [DraftCache/191] rebuildCache time: 2
,08-26 15:05:16.237  1111  3490 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/com.htc.sense.mms/files/
,08-26 15:05:16.237  9154  9185 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/com.htc.sense.mms/files
,08-26 15:05:16.247  9154  9185 D MsgPreferenceUtils: phone state: true
,08-26 15:05:16.247  9154  9185 D MsgPreferenceUtils: sd state: false
08-26 15:05:16.247  9154  9185 D MsgPreferenceUtils: vIndex = 1
,08-26 15:05:16.257  9154  9207 D RcsWorkingHandler: handler msg:{ when=0 what=1 target=com.htc.sense.mms.rcschat.bo },
08-26 15:05:16.257  9154  9207 D RcsWorkingHandler: not support Rcs, return
08-26 15:05:16.257  9154  9185 D PersonalizeUtils: isHTCThemeChange_full equal time= null,old=
08-26 15:05:16.257  9154  9185 D PersonalizeUtils: isHTCThemeChange_full isChange= false
,08-26 15:05:16.257  9154  9185 D PersonalizeUtils: isHTCThemeChange_wallpaper equal time= null,old=
08-26 15:05:16.257  9154  9185 D PersonalizeUtils: isHTCThemeChange_wallpaper isChange= false
08-26 15:05:16.257  9154  9185 D PersonalizeUtils: isHTCThemeChange_CC equal time= 1466486566,old=1466486566
08-26 15:05:16.257  9154  9185 D PersonalizeUtils: isHTCThemeChange_CC isChange= false
,08-26 15:05:16.337  1111  4847 I art     : Explicit concurrent mark sweep GC freed 26132(1519KB) AllocSpace objects, 13(992KB) LOS objects, 33% free, 16MB/24MB, paused 2.152ms total 158.127ms
,08-26 15:05:28.377   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-26 15:05:42.737  1111  3033 D PMS     : acquireWL(64ab9fd): PARTIAL_WAKE_LOCK  *alarm* 0x1 1111 1000 WorkSource{1000},
08-26 15:05:42.747  1111  3033 V AlarmManager: sending alarm PendingIntent{92a76f2: PendingIntentRecord{87e9143 android broadcastIntent}}, i=android.content.jobscheduler.JOB_DEADLINE_EXPIRED, t=3, cnt=1, w=168291, Int=0
08-26 15:05:42.747  1111  3033 V AlarmManager: sending alarm PendingIntent{af873c0: PendingIntentRecord{258df8f9 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=206591, Int=0
08-26 15:05:42.777  1111  1111 D PMS     : acquireWL(161df24a): PARTIAL_WAKE_LOCK  *job*/com.google.android.gms/.gcm.nts.TaskExecutionService 0x1 1111 1000 WorkSource{10019}
08-26 15:05:42.777  1111  1111 D PMS     : releaseWL(64ab9fd): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,08-26 15:05:42.787  1111  1111 D PMS     : releaseWL(161df24a): PARTIAL_WAKE_LOCK  *job*/com.google.android.gms/.gcm.nts.TaskExecutionService 0x1 WorkSource{10019}
,08-26 15:05:42.797  1111  1133 D PMS     : acquireWL(39cee5bb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 null
,08-26 15:05:42.837  1111  3519 D PMS     : acquireWL(10b8fad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 WorkSource{10019 com.google.android.gms}
,08-26 15:05:42.857  4007  4007 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.gcm.ACTION_TASK_READY cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
08-26 15:05:42.857  1111  3084 D PMS     : acquireWL(179404ee): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 WorkSource{10019 com.google.android.gms}
,08-26 15:05:42.877  4007  9208 I ConfigFetchService: running network task: configservice_periodic
,08-26 15:05:42.877  3666  3666 I ConfigService: onCreate
08-26 15:05:42.877  1111  5330 D PMS     : releaseWL(39cee5bb): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
08-26 15:05:42.877  3666  3666 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-26 15:05:42.877  1111  3490 D PMS     : acquireWL(2e806c25): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 4007 10019 null
,08-26 15:05:42.877  4007  9208 I ConfigFetchService: launchTask
08-26 15:05:42.877  1111  3494 D PMS     : releaseWL(179404ee): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10019 com.google.android.gms}
,08-26 15:05:42.887  3666  3666 I ConfigService: onBind returning update interface,
08-26 15:05:42.887  3666  3666 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 15:05:42.887  3666  3666 I ConfigService: onBind returning config service
08-26 15:05:42.887  4007  4007 I ConfigFetchService: service connected
,08-26 15:05:42.887  4007  4007 I ConfigClient: service connected
,08-26 15:05:42.897  1111  3519 D PMS     : acquireWL(2100b3ab): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 null
,08-26 15:05:42.907  1111  1133 D PMS     : releaseWL(2100b3ab): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
,08-26 15:05:42.907  1111  3348 D PMS     : acquireWL(1170a5a1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 null
,08-26 15:05:42.907  1111  3490 D PMS     : releaseWL(1170a5a1): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-26 15:05:46.317  3547  3735 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
08-26 15:05:46.317  3198  5058 D HtcUPManager: HtcUPServiceProxy Disconnect from  UP serivce: No interaction with app
,08-26 15:05:46.327  3547  3735 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
08-26 15:05:46.327  1111  3519 I ActivityManager: Killing 8480:com.htc.mobiledata/u0a40 (adj 15): empty #17
08-26 15:05:46.327  3641  3641 D HtcAppUPService: HtcUPService [##] onDestroy(), this =com.htc.sense.hsp.upservice.HtcUPService@7d80a06
08-26 15:05:46.327  1111  3519 D Process : killProcessQuiet, pid=8480,
08-26 15:05:46.337  1111  3519 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-26 15:05:46.367  3198  5058 D HtcUPManager: HtcUPServiceProxy Disconnect from UP service. Change state to: DISCONNECTED,
,08-26 15:05:46.417  1111  3753 I ActivityManager: Recipient 8480,
,08-26 15:05:48.517  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 10 BSSID 84:b2:61:0f:9c:34 SSID '\x00' due to wpa_bss_flush_by_age,
08-26 15:05:48.517  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:48.517  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 13 BSSID 84:b2:61:0f:9c:3a SSID '\x00' due to wpa_bss_flush_by_age,
08-26 15:05:48.517  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:05:48.517  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 17 BSSID 00:fe:c8:73:02:06 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:48.517  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:05:48.517  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 18 BSSID 00:fe:c8:73:02:05 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:48.517  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:05:48.517  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 20 BSSID 84:b2:61:12:64:9b SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:48.517  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:05:48.517  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 21 BSSID 84:b2:61:12:64:96 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:48.517  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:05:48.517  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 30 BSSID 00:fe:c8:73:02:01 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:48.517  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:05:48.517  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 31 BSSID 84:b2:61:12:64:91 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:48.517  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:05:52.887  4007  9211 V ConfigFetchTask: ConfigFetchTask getDeviceDataVersionInfo(): ABFEt1VbG05ztJxy7numrH7x-7pv7QW6hSDuBwvQuoFxYoZ_H8yNEGdhdHL1C4eIPRDucRDvCXWHUFIrjcX8YNASvQ2RrBTAzCqvqt9KxD4LbWnTJIi0O70zJzLxNNAcJhfqlwv88P3idUBVgt_uA94T0bwXPmWpKzVBy0g6lVs_l06VfjyxJ-NDIHd_afxktz00BRtP6nfq,
,08-26 15:05:52.957  4007  9211 I GoogleURLConnFactory: binding HttpService
,08-26 15:05:52.967  4007  9211 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-26 15:05:52.967  4007  9211 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4,
08-26 15:05:52.967  4007  9211 D libc    : [NET] android_getaddrinfofornet-, err=8
08-26 15:05:52.967  4007  9211 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
08-26 15:05:52.967  4007  9211 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-26 15:05:52.967  4007  9211 D libc    : [NET] android_getaddrinfo_proxy+
08-26 15:05:52.967  4007  9211 D libc    : [NET] android_getaddrinfo_proxy get netid:0,
08-26 15:05:52.967   518  9213 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 1024
08-26 15:05:52.967   518  9213 D libc    : [NET] _dns_getaddrinfo+, netid:100, mark:917604
,08-26 15:05:52.967   518  9213 D libc    : [NET] _dns_getaddrinfo-, (NS_SUCCESS)
08-26 15:05:52.967   518  9213 D libc    : [NET] android_getaddrinfofornet-, SUCCESS
08-26 15:05:52.967  4007  9211 D libc    : [NET] android_getaddrinfo_proxy-, success
,08-26 15:05:53.077  4007  9211 D libc    : [NET] android_getaddrinfofornet+,hn 26(0x616e64726f6964),sn(),hints(known),family 0,flags 4
,08-26 15:05:53.077  4007  9211 D libc    : [NET] android_getaddrinfofornet-, err=8
,08-26 15:05:53.337  4007  9211 I GoogleURLConnFactory: unbinding HttpService
,08-26 15:05:53.337  4007  9211 I ConfigFetchTask: updating config table for com.google.android.gms
,08-26 15:05:53.367  4007  4007 I ConfigFetchService: fetch service done; releasing wakelock,
08-26 15:05:53.367  4007  4007 I ConfigFetchService: stopping self
08-26 15:05:53.367  1111  1133 D PMS     : releaseWL(2e806c25): PARTIAL_WAKE_LOCK  Config Service fetch 0x1 null,
08-26 15:05:53.367  4007  4007 I ConfigFetchService: PackageReceiver: Intent { act=com.google.android.gms.config.CHANGED cat=[com.google.android.gms] flg=0x10 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver }
,08-26 15:05:53.367  1111  3490 D PMS     : releaseWL(10b8fad8): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10019 com.google.android.gms}
,08-26 15:05:53.377  1111  4139 D PMS     : acquireWL(a55ed23): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 null
08-26 15:05:53.377  1111  3516 D PMS     : acquireWL(20e8d220): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4007 10019 null
,08-26 15:05:53.397  4007  4007 I ConfigFetchService: onStartCommand Intent { act=com.google.android.gms.config.CHANGED cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
08-26 15:05:53.397  4007  4007 I ConfigFetchService: GmsCore config value changed; rescheduling
,08-26 15:05:53.407  3666  3666 I ConfigService: onDestroy,
08-26 15:05:53.407  1111  1133 D PMS     : releaseWL(a55ed23): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
08-26 15:05:53.407  3666  3666 I ConfigService: onCreate
08-26 15:05:53.407  3666  3666 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-26 15:05:53.417  3666  3666 I ConfigService: onBind returning update interface
08-26 15:05:53.417  3666  3666 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-26 15:05:53.417  3666  3666 I ConfigService: onBind returning config service
,08-26 15:05:53.417  4007  4007 I ConfigFetchService: service connected
,08-26 15:05:53.417  1111  5330 D PMS     : acquireWL(161aaa76): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 null
,08-26 15:05:53.417  4007  4007 I ConfigClient: service connected
,08-26 15:05:53.417  4007  9215 I ConfigFetchService: connected = true
,08-26 15:05:53.427  4007  9215 I ConfigFetchService: self-hosted config:fetch_interval = 43200
,08-26 15:05:53.427  1111  1132 D PMS     : releaseWL(161aaa76): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-26 15:05:53.427  1111  3753 D PMS     : acquireWL(168eb877): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 null
,08-26 15:05:53.437  4007  9215 I ConfigFetchService: stopping self
,08-26 15:05:53.447  1111  3490 D PMS     : acquireWL(3a02fce4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 WorkSource{10019 com.google.android.gms},
,08-26 15:05:53.457  1111  3519 D PMS     : releaseWL(168eb877): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-26 15:05:53.477  3666  3666 I ConfigService: onDestroy
,08-26 15:05:53.487  3666  9217 I VacuumService: Vacuum at: now=1472216753491 tag=VacuumService
,08-26 15:05:53.507  1111  3348 D PMS     : releaseWL(3a02fce4): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 WorkSource{10019 com.google.android.gms},
08-26 15:05:53.507  1111  3084 D PMS     : acquireWL(ee4f949): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 null
,08-26 15:05:53.527  1111  5330 D PMS     : releaseWL(ee4f949): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
08-26 15:05:53.527  1111  3516 D PMS     : acquireWL(3fee3f6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 null
,08-26 15:05:53.537  1111  3084 D PMS     : releaseWL(3fee3f6f): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-26 15:05:53.537  1111  3490 D PMS     : acquireWL(e9f047c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3666 10019 null
,08-26 15:05:53.537  1111  5330 D PMS     : releaseWL(e9f047c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
,08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 0 BSSID f0:f2:6d:22:99:3e SSID 'NG700_GUEST' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 7 BSSID 00:1f:27:54:70:c0 SSID 'ktwtestwifi' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 2 BSSID 00:1f:27:54:70:c1 SSID 'TEST_KTW01' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 6 BSSID 84:b2:61:1a:ce:7b SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 5 BSSID 84:b2:61:1a:ce:7a SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 3 BSSID 84:b2:61:1a:ce:7f SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 4 BSSID 84:b2:61:1a:ce:79 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 8 BSSID 00:16:a6:1f:06:5c SSID '' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 9 BSSID 84:b2:61:0f:9c:35 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 33 BSSID 00:16:a6:1e:e0:a4 SSID '' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 34 BSSID 00:1a:ef:42:f2:b0 SSID 'Conrad_AP' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 35 BSSID 84:b2:61:1a:ce:74 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 36 BSSID 84:b2:61:1a:ce:75 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 37 BSSID 84:b2:61:0f:9c:36 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 11 BSSID 84:b2:61:0f:9c:30 SSID '\x00' due to wpa_bss_flush_by_age
,08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 38 BSSID 84:b2:61:1a:ce:70 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 12 BSSID 84:b2:61:0f:9c:32 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 22 BSSID 84:b2:61:12:64:90 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 39 BSSID 84:b2:61:1a:ce:72 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 40 BSSID 84:b2:61:0f:9c:39 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 14 BSSID 84:b2:61:0f:9c:3f SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 15 BSSID 84:b2:61:0f:9c:3b SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 41 BSSID 84:b2:61:1c:62:d2 SSID '\x00' due to wpa_bss_flush_by_age
,08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 19 BSSID 84:b2:61:1c:62:d5 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 16 BSSID 00:fe:c8:73:02:02 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 23 BSSID 84:b2:61:12:64:94 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 42 BSSID 84:b2:61:12:64:95 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 43 BSSID 84:b2:61:1c:62:da SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 44 BSSID 84:b2:61:1c:62:df SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 45 BSSID 84:b2:61:1c:62:d9 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 46 BSSID 84:b2:61:12:64:99 SSID '\x00' due to wpa_bss_flush_by_age
,08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 24 BSSID 84:b2:61:1a:ce:7e SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 25 BSSID 84:b2:61:0f:9c:33 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
,08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 47 BSSID 84:b2:61:0f:9c:31 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 26 BSSID 84:b2:61:1a:ce:73 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 28 BSSID 84:b2:61:1c:62:d3 SSID 'RA-WINGS' due to wpa_bss_flush_by_age,
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 48 BSSID 84:b2:61:1a:ce:71 SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 27 BSSID 84:b2:61:0f:9c:3e SSID '\x00' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 49 BSSID 84:b2:61:1c:62:d1 SSID '\x00' due to wpa_bss_flush_by_age
,08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 29 BSSID 00:fe:c8:73:02:03 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 32 BSSID 84:b2:61:12:64:93 SSID 'RA-WINGS' due to wpa_bss_flush_by_age
08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
08-26 15:05:58.527  3156  3156 D wpa_supplicant: wlan0: BSS: Remove ID 50 BSSID 84:b2:61:12:64:9e SSID '\x00' due to wpa_bss_flush_by_age
,08-26 15:05:58.527  3156  3156 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1111-2\x00
,08-26 15:06:02.417  1111  3753 D PMS     : acquireWL(1515ec68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
08-26 15:06:02.437  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:06:02.427  1111  3753 I BatteryService: n_update end
08-26 15:06:02.437  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:06:02.437  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:06:02.437  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:06:02.437  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:06:02.437  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:06:02.437  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:06:02.437  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:06:02.437  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:06:02.437  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:06:02.437  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:06:02.437  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:06:02.437  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:06:02.437  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:06:02.437  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:06:02.437  1111  3076 D WifiController: handleMessage: X
,08-26 15:06:02.437  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:06:02.447  1111  1175 D HtcPowerSaver: updateBatteryInfo
,08-26 15:06:02.447  1111  1111 D HtcPowerSaver: Checking...
08-26 15:06:02.447  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:06:02.457  1111  3753 D PMS     : releaseWL(1515ec68): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:06:02.457  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-26 15:06:02.457  1111  1111 I HtcPowerSaver: << updateStatus
,08-26 15:06:02.487  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-26 15:06:02.487  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:06:02.487  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:06:02.487  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-26 15:06:02.487  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:06:08.387   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 15:06:18.397   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 15:06:33.397   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:06:53.417   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
08-26 15:06:53.417  1111  3493 D PMS     : releaseWL(20e8d220): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,08-26 15:07:02.557  1111  3084 D PMS     : acquireWL(28cd8881): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null,
08-26 15:07:02.557  1111  3084 I BatteryService: n_update end
08-26 15:07:02.557  1111  3084 D PMS     : releaseWL(28cd8881): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:07:02.567  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:07:02.567  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:07:02.567  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:07:02.567  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:07:02.567  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:07:02.567  1111  1111 D HtcPowerSaver: Checking...
08-26 15:07:02.567  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:07:02.567  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:07:02.567  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:07:02.567  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:07:02.567  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:07:02.567  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:07:02.567  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:07:02.567  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:07:02.567  1111  3076 D WifiController: handleMessage: X
08-26 15:07:02.567  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:07:02.567  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:07:02.567  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:07:02.567  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:07:02.567  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,08-26 15:07:02.577  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-26 15:07:02.577  1111  1111 I HtcPowerSaver: << updateStatus
,08-26 15:07:02.617  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-26 15:07:02.617  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:07:02.617  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:07:02.617  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-26 15:07:02.617  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:07:16.227  1111  3033 D PMS     : acquireWL(13e09d26): PARTIAL_WAKE_LOCK  *alarm* 0x1 1111 1000 WorkSource{1000}
08-26 15:07:16.227  1111  3033 V AlarmManager: sending alarm PendingIntent{3dcf5379: PendingIntentRecord{54b98be android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=217325, Int=0
08-26 15:07:16.247  9154  9154 V TransactionService: 1-Creating TransactionService
08-26 15:07:16.237  1111  3033 V AlarmManager: sending alarm PendingIntent{42e2a0f: PendingIntentRecord{2f12aa9c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=223850, Int=0
08-26 15:07:16.257  1111  3033 V AlarmManager: sending alarm PendingIntent{17916714: PendingIntentRecord{23c92bbd com.htc.sense.mms startService}}, i=android.intent.action.ACTION_ONALARM, t=0, cnt=1, w=1472216836229, Int=0
,08-26 15:07:16.307  9154  9154 V TransactionService: onStartCommand: 1
08-26 15:07:16.307  9154  9154 D MmsSystemEventReceiver: unRegisterForConnectionStateChanges
08-26 15:07:16.307  9154  9218 V TransactionService: 4-Handling incoming message: { when=-2ms what=2 arg1=1 target=com.htc.sense.mms.transaction.au }
08-26 15:07:16.307  9154  9218 V TransactionService: Loading previous transactions.
,08-26 15:07:16.317  1111  1111 D PMS     : releaseWL(13e09d26): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,08-26 15:07:16.317  3547  3566 D TelephUtils: DELETE for  <hidden uri>  [ com.htc.sense.mms ] tid: 64
08-26 15:07:16.317  3547  3566 V MmsProvider: Delete uri=content://mms/9223372036854775807/part, match=11
08-26 15:07:16.317  3547  3566 V MmsProvider: selection=null
,08-26 15:07:16.317  3547  4655 D TelephUtils: QUERY for  <hidden uri>  [ com.htc.sense.mms ] tid: 103
,08-26 15:07:16.327  9154  9218 D TransactionService: Force clearing mTransactionList
08-26 15:07:16.327  9154  9218 D TransactionService: Force set service start id to 1
08-26 15:07:16.327  9154  9218 V TransactionService: stopSelfIfIdle
,08-26 15:07:16.327  9154  9154 V TransactionService: Destroying TransactionService
08-26 15:07:16.327  9154  9218 D TransactionService: stopSelfResult: true, mLastHandledServiceId: 1
,08-26 15:07:16.327  9154  9218 V TransactionService: 4-Handling incoming message: { when=-2ms what=100 target=com.htc.sense.mms.transaction.au }
08-26 15:07:16.327  9154  9218 V Scheduler: Scheduler safely quits looper.
,08-26 15:07:18.427   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-26 15:07:23.847   499   499 E TPD     : [TPD][ERR] can't open /proc/21/status...,
,08-26 15:07:53.557  1111  3033 D PMS     : acquireWL(192965b2): PARTIAL_WAKE_LOCK  *alarm* 0x1 1111 1000 WorkSource{1000},
08-26 15:07:53.567  1111  3033 V AlarmManager: sending alarm PendingIntent{af873c0: PendingIntentRecord{258df8f9 android broadcastIntent}}, i=com.android.server.task.controllers.BatteryController.ACTION_CHARGING_STABLE, t=2, cnt=1, w=337413, Int=0
08-26 15:07:53.567  1111  1111 D PMS     : releaseWL(192965b2): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,08-26 15:08:03.437   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,08-26 15:08:07.877   499   499 E TPD     : [TPD][ERR] can't open /proc/85/status...,
,08-26 15:08:13.447   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 15:08:28.457   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:08:48.467   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-26 15:09:02.897  1111  3519 D PMS     : acquireWL(2d48b903): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null,
08-26 15:09:02.907  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:09:02.897  1111  3519 I BatteryService: n_update end
08-26 15:09:02.907  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:09:02.897  1111  3519 D PMS     : releaseWL(2d48b903): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:09:02.907  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:09:02.907  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:09:02.907  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:09:02.907  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:09:02.917  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:09:02.917  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:09:02.917  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:09:02.917  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:09:02.917  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:09:02.917  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:09:02.917  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:09:02.917  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:09:02.917  1111  1111 D HtcPowerSaver: Checking...
08-26 15:09:02.917  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:09:02.917  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:09:02.917  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:09:02.927  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,08-26 15:09:02.917  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:09:02.927  1111  1111 I HtcPowerSaver: << updateStatus
08-26 15:09:02.917  1111  3076 D WifiController: handleMessage: X
,08-26 15:09:02.957  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-26 15:09:02.957  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:09:02.957  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:09:02.957  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-26 15:09:02.957  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:09:13.477   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-26 15:10:03.487   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 15:10:13.497   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2,
,08-26 15:10:23.477  1111  5330 D PMS     : acquireWL(ba7e080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
08-26 15:10:23.477  1111  5330 I BatteryService: n_update end
08-26 15:10:23.487  1111  5330 D PMS     : releaseWL(ba7e080): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-26 15:10:23.507  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:10:23.507  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:10:23.507  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:10:23.517  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:10:23.507  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:10:23.517  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:10:23.507  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:10:23.517  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:10:23.517  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:10:23.537  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:10:23.517  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:10:23.537  1111  1111 D HtcPowerSaver: Checking...
08-26 15:10:23.517  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:10:23.537  1111  1111 I HtcPowerSaver: >> updateStatus
,08-26 15:10:23.517  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:10:23.547  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-26 15:10:23.517  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:10:23.547  1111  1111 I HtcPowerSaver: << updateStatus
08-26 15:10:23.517  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:10:23.517  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:10:23.517  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:10:23.517  1111  3076 D WifiController: handleMessage: X
08-26 15:10:23.547  1111  1159 I ActivityManager: Start proc 9232:com.android.settings/1000 for broadcast com.android.settings/.framework.app.HtcSystemReceiver
,08-26 15:10:23.557  9232  9232 W HTCLOG  : use specified tag [FDManager], func [0].
08-26 15:10:23.557  9232  9232 W HTCLOG  : mask=0x18
,08-26 15:10:23.557  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
,08-26 15:10:23.557  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:10:23.557  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:10:23.557  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-26 15:10:23.557  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:10:23.607  9232  9232 V Settings:HtcSettingsApplication: [9232/9232] onCreate()
,08-26 15:10:23.607  9232  9232 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.settings.framework.app.HtcSystemReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:2719 
,08-26 15:10:23.617  9232  9253 D SmartNS_NSReceiver: plugged = 2, support_extension = 8, unsupport_charger = false overheat:false
08-26 15:10:23.617  9232  9253 D SmartNS_NSReceiver: Index of the first 1 = 3
,08-26 15:10:23.617  9232  9253 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:1836 android.content.ContextWrapper.stopService:521 com.android.settings.NSReceiver.onReceive:182 android.support.v4.content.g.a:297 android.support.v4.content.g.b:278 
,08-26 15:10:23.617  9232  9253 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 android.content.ContextWrapper.sendBroadcast:377 com.android.settings.NSReceiver.onReceive:184 android.support.v4.content.g.a:297 android.support.v4.content.g.b:278 
,08-26 15:10:23.627  9232  9253 W Settings: Setting tethering_blocked has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-26 15:10:23.627  9232  9253 I SmartNS_Utility: hasRemovableStorageSlot: true
,08-26 15:10:23.627  9232  9253 D SmartNS_Utility: [ACC]Settings-Wireless_+_network-USB_tethering_:usb_storage_notification=false
08-26 15:10:23.627  9232  9253 D SmartNS_NSReceiver: onReceive : com.htc.intent.action.BATTERY_CHANGE_PARTIAL hasTethered:false isNSOpening:false
,08-26 15:10:23.637  9232  9253 D SmartNS_Utility: [ACC]android_networking:tethering_guard_support=false
08-26 15:10:23.637  9232  9253 W SystemReader: Cannot find settings_cdma_gpsone_dsecription_type, use default value instead
,08-26 15:10:23.637  1111  1133 D Process : killProcessQuiet, pid=8272
08-26 15:10:23.637  1111  1133 I ActivityManager: Killing 8272:com.google.android.gm/u0a97 (adj 15): empty #17
,08-26 15:10:23.637  1111  1133 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-26 15:10:23.777  1111  3753 I ActivityManager: Recipient 8272,
,08-26 15:10:28.507   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,08-26 15:10:48.517   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4,
,08-26 15:11:13.537   587   587 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-26 15:11:23.697  1111  3084 D PMS     : acquireWL(29c42afe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
08-26 15:11:23.707  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:11:23.697  1111  3084 I BatteryService: n_update end
08-26 15:11:23.707  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:11:23.697  1111  3084 D PMS     : releaseWL(29c42afe): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:11:23.707  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:11:23.707  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:11:23.707  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:11:23.707  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:11:23.707  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:11:23.707  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:11:23.717  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:11:23.707  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:11:23.717  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:11:23.707  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:11:23.717  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:11:23.717  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:11:23.717  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:11:23.717  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:11:23.717  1111  3076 D WifiController: handleMessage: X
,08-26 15:11:23.717  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:11:23.717  1111  1111 D HtcPowerSaver: Checking...
08-26 15:11:23.717  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:11:23.727  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-26 15:11:23.727  1111  1111 I HtcPowerSaver: << updateStatus
,08-26 15:11:23.757  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-26 15:11:23.757  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:11:23.757  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:11:23.757  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-26 15:11:23.757  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:12:03.537   587   587 W HTCLOG  : use specified tag [QC-QMI], func [18].,
08-26 15:12:03.537   587   587 W HTCLOG  : mask=0x18
,08-26 15:12:21.167   507   525 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory),
,08-26 15:12:23.847  1111  3516 D PMS     : acquireWL(c13e25f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
,08-26 15:12:23.857  1111  3516 I BatteryService: n_update end
08-26 15:12:23.867  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false),
08-26 15:12:23.867  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:12:23.867  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:12:23.867  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:12:23.867  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:12:23.867  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:12:23.877  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:12:23.867  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:12:23.877  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:12:23.867  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:12:23.877  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:12:23.867  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:12:23.877  1111  1111 D HtcPowerSaver: Checking...
08-26 15:12:23.867  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-,
08-26 15:12:23.877  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:12:23.877  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:12:23.887  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-26 15:12:23.877  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:12:23.887  1111  1111 I HtcPowerSaver: << updateStatus
08-26 15:12:23.877  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:12:23.887  1111  3516 D PMS     : releaseWL(c13e25f): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:12:23.877  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:12:23.877  1111  3076 D WifiController: handleMessage: X
,08-26 15:12:23.917  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-26 15:12:23.917  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:12:23.917  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:12:23.917  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-26 15:12:23.927  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:12:41.957  3547  3735 D ContactMessageStore: MSG_CHECK_DELETION >>,
,08-26 15:12:41.957  3547  3735 D ContactMessageStore: mDeleteTask = null, bDeleting = false
08-26 15:12:41.957  3547  3735 D AccFlag : sku_id=58
,08-26 15:12:41.957  3547  3735 D ContactMessageStore: MSG_CHECK_DELETION <<
08-26 15:12:41.957  3547  9264 D ContactMessageStore: start background delete task...
,08-26 15:12:41.967  3547  9264 D ContactMessageStore: size: 0 , 0
08-26 15:12:41.967  3547  9264 D ContactMessageStore: Background delete complete
,08-26 15:13:23.997  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:13:23.997  1111  3348 D PMS     : acquireWL(27ea84ac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
08-26 15:13:23.997  1111  3348 I BatteryService: n_update end
08-26 15:13:24.007  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:13:23.997  1111  3348 D PMS     : releaseWL(27ea84ac): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:13:24.007  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:13:23.997  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:13:24.007  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:13:24.007  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:13:24.007  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:13:24.007  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:13:24.007  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:13:24.007  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:13:24.007  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:13:24.007  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:13:24.007  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:13:24.007  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:13:24.007  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:13:24.007  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:13:24.007  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:13:24.007  1111  3076 D WifiController: handleMessage: X
08-26 15:13:24.007  1111  1111 D HtcPowerSaver: Checking...
08-26 15:13:24.007  1111  1111 I HtcPowerSaver: >> updateStatus
,08-26 15:13:24.017  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1),
08-26 15:13:24.017  1111  1111 I HtcPowerSaver: << updateStatus
,08-26 15:13:24.057  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-26 15:13:24.057  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:13:24.057  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:13:24.057  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-26 15:13:24.057  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:13:47.317  1111  3519 D Process : killProcessQuiet, pid=8343,
08-26 15:13:47.317  1111  3519 I ActivityManager: Killing 8343:com.google.android.talk/u0a103 (adj 15): empty #17
08-26 15:13:47.317  1111  3519 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-26 15:13:47.387  1111  3490 I ActivityManager: Recipient 8343
,08-26 15:14:24.167  1111  3493 D PMS     : acquireWL(3c4f1575): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
,08-26 15:14:24.167  1111  3493 I BatteryService: n_update end,
,08-26 15:14:24.167  1111  3493 D PMS     : releaseWL(3c4f1575): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null,
08-26 15:14:24.177  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:14:24.177  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:14:24.177  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:14:24.177  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:14:24.177  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:14:24.177  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:14:24.177  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:14:24.177  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
,08-26 15:14:24.177  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:14:24.177  1111  3076 D WifiController: handleMessage: E msg.what=155652,
,08-26 15:14:24.177  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:14:24.177  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:14:24.177  1111  1111 D HtcPowerSaver: Checking...
08-26 15:14:24.177  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:14:24.177  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:14:24.177  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:14:24.187  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-26 15:14:24.177  1111  3076 D WifiController: handleMessage: X
08-26 15:14:24.187  1111  1111 I HtcPowerSaver: << updateStatus
08-26 15:14:24.177  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
,08-26 15:14:24.177  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:14:24.177  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,08-26 15:14:24.227  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-26 15:14:24.227  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:14:24.227  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:14:24.227  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-26 15:14:24.227  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:16:24.487  1111  3084 D PMS     : acquireWL(13b3f90a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
08-26 15:16:24.487  1111  3084 I BatteryService: n_update end
,08-26 15:16:24.497  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:16:24.507  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:16:24.507  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:16:24.507  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:16:24.507  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:16:24.507  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:16:24.507  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:16:24.507  1111  1111 D HtcPowerSaver: Checking...
08-26 15:16:24.507  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:16:24.507  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:16:24.507  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
,08-26 15:16:24.517  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:16:24.507  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:16:24.517  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:16:24.507  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:16:24.527  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-26 15:16:24.517  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:16:24.527  1111  1111 I HtcPowerSaver: << updateStatus
08-26 15:16:24.517  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:16:24.527  1111  3084 D PMS     : releaseWL(13b3f90a): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:16:24.517  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:16:24.517  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:16:24.517  1111  3076 D WifiController: handleMessage: X
,08-26 15:16:24.557  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false)
08-26 15:16:24.557  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:16:24.557  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:16:24.557  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-26 15:16:24.557  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:17:24.647  1111  3494 D PMS     : acquireWL(213e457b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
,08-26 15:17:24.647  1111  3494 I BatteryService: n_update end
08-26 15:17:24.657  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:17:24.657  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:17:24.667  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:17:24.667  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:17:24.667  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:17:24.667  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:17:24.667  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:17:24.667  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:17:24.667  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:17:24.667  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:17:24.677  1111  1175 D HtcPowerSaver: updateBatteryInfo
08-26 15:17:24.667  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:17:24.677  1111  1111 D HtcPowerSaver: Checking...
08-26 15:17:24.667  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:17:24.677  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:17:24.667  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:17:24.687  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
,08-26 15:17:24.667  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:17:24.687  1111  1111 I HtcPowerSaver: << updateStatus
08-26 15:17:24.667  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:17:24.687  1111  3494 D PMS     : releaseWL(213e457b): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:17:24.667  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:17:24.667  1111  3076 D WifiController: handleMessage: X
,08-26 15:17:24.717  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-26 15:17:24.717  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:17:24.717  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:17:24.717  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
,08-26 15:17:24.717  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:17:59.617  1111  3033 D PMS     : acquireWL(18d13f98): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1111 1000 WorkSource{1000},
08-26 15:17:59.627  1111  3033 V AlarmManager: sending alarm PendingIntent{42e2a0f: PendingIntentRecord{2f12aa9c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=343850, Int=0
08-26 15:17:59.627  1111  3033 V AlarmManager: sending alarm PendingIntent{1a0893f1: PendingIntentRecord{10209bd6 com.android.bluetooth broadcastIntent}}, i=com.android.bluetooth.btservice.action.ALARM_WAKEUP, t=2, cnt=1, w=943477, Int=0,
08-26 15:17:59.627  5627  5627 D BluetoothAdapterService(391591024): handleMessage() - Message: 110
08-26 15:17:59.627  5627  5627 D BluetoothAdapterService(391591024): handleMessage() - MESSAGE_RELEASE_WAKE_ALARM
08-26 15:17:59.627  5627  5840 I bt-btm  : Received oneshot timer event complete
08-26 15:17:59.627  5627  5840 I bt-btm  : btm_ble_timeout
08-26 15:17:59.627  5627  5840 I bt-btm  : btm_gen_resolvable_private_addr
08-26 15:17:59.627  5627  5840 I bt-hci  : 15:17:59.639 --,
08-26 15:17:59.627  1111  3348 D PMS     : acquireWL(2ae1be57): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 5627 1002 null
08-26 15:17:59.627  5627  5840 I bt-hci  : 15:17:59.639 SENT Command to HCI. Name: HCI_LE_Rand  (Hex Code: 0x2018  Param Len: 0) Ctrl(0)
08-26 15:17:59.627  5627  5840 I bt-hci  : 15:17:59.639 --
,08-26 15:17:59.637  5627  5842 I bt-hci  : 15:17:59.648 --
08-26 15:17:59.637  5627  5842 I bt-hci  : 15:17:59.648 RCVD Event from HCI. Name: HCI_Command_Complete  (Hex Code: 0x0e  Param Len: 12) Ctrl(0)
08-26 15:17:59.637  5627  5842 I bt-hci  : 15:17:59.648 Parameters
08-26 15:17:59.637  5627  5842 I bt-hci  : 15:17:59.648                      Num HCI Cmd Packets : 1 (0x01)
08-26 15:17:59.637  5627  5842 I bt-hci  : 15:17:59.648                                 Cmd Code : 0x2018  (HCI_LE_Rand)
08-26 15:17:59.637  5627  5842 I bt-hci  : 15:17:59.648                                   Status : Success (0x00)
08-26 15:17:59.637  5627  5842 I bt-hci  : 15:17:59.648                            Random Number : bb 3a 42 af 1e 46 4b c3 
08-26 15:17:59.637  5627  5842 I bt-hci  : 15:17:59.648 --
,08-26 15:17:59.637  5627  5840 D bt-btm  : btm_ble_rand_enc_complete
08-26 15:17:59.637  5627  5840 I bt-btm  : btm_gen_resolve_paddr_low
08-26 15:17:59.637  5627  5840 D bt-smp  : smp_encrypt_data
08-26 15:17:59.637  5627  5840 D bt-smp  : Key(LSB ~ MSB) = 2b d8 9e 69 23 5b 6a 34 c8 5f a4 fb f9 34 ec 0c 
,08-26 15:17:59.637  5627  5840 D bt-smp  : Plain text(LSB ~ MSB) = bb 3a 42 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-26 15:17:59.637  5627  5840 D bt-smp  : Encrypted text(LSB ~ MSB) = 2f 87 33 d3 1b a7 2c c0 41 c8 49 52 c7 f3 5d dd 
08-26 15:17:59.637  5627  5840 I bt-btm  : btm_gen_resolve_paddr_cmpl
08-26 15:17:59.637  5627  5840 I bt-hci  : 15:17:59.649 --
08-26 15:17:59.637  5627  5840 I bt-hci  : 15:17:59.649 SENT Command to HCI. Name: HCI_LE_Write_random_Address  (Hex Code: 0x2005  Param Len: 6) Ctrl(0)
08-26 15:17:59.637  5627  5840 I bt-hci  : 15:17:59.649 Parameters 
08-26 15:17:59.637  5627  5840 I bt-hci  : 15:17:59.649                           Random BD Addr : 42-3a-bb-33-87-2f
,08-26 15:17:59.637  5627  5840 I bt-hci  : 15:17:59.649 --
08-26 15:17:59.637  5627  5840 W bt-btm  : Stopping oneshot timer
08-26 15:17:59.637  5627  5840 D bt-btm  : Starting oneshot timer type:103 timeout:900s
08-26 15:17:59.647  5627  5842 I bt-hci  : 15:17:59.651 --
08-26 15:17:59.647  5627  5842 I bt-hci  : 15:17:59.651 RCVD Event from HCI. Name: HCI_Command_Complete  (Hex Code: 0x0e  Param Len: 4) Ctrl(0)
08-26 15:17:59.647  5627  5842 I bt-hci  : 15:17:59.651 Parameters
,08-26 15:17:59.647  5627  5842 I bt-hci  : 15:17:59.651                      Num HCI Cmd Packets : 1 (0x01)
08-26 15:17:59.647  5627  5842 I bt-hci  : 15:17:59.651                                 Cmd Code : 0x2005  (HCI_LE_Write_random_Address)
08-26 15:17:59.647  5627  5842 I bt-hci  : 15:17:59.651                                   Status : Success (0x00)
08-26 15:17:59.647  5627  5842 I bt-hci  : 15:17:59.651 --
,08-26 15:17:59.657  1111  1111 D PMS     : releaseWL(18d13f98): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
,08-26 15:18:00.637  5627  5627 D BluetoothAdapterService(391591024): handleMessage() - Message: 100,
,08-26 15:18:00.637  5627  5627 D BluetoothAdapterService(391591024): handleMessage() - MESSAGE_SET_WAKE_ALARM
08-26 15:18:00.637  1111  3494 D PMS     : releaseWL(2ae1be57): PARTIAL_WAKE_LOCK  bluedroid_timer 0x1 null
,08-26 15:18:04.897  1111  3033 D PMS     : acquireWL(1866bd44): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1111 1000 WorkSource{1000}
08-26 15:18:04.897  1111  3033 V AlarmManager: sending alarm PendingIntent{42e2a0f: PendingIntentRecord{2f12aa9c android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=943850, Int=0
08-26 15:18:04.897  1111  3033 V AlarmManager: sending alarm PendingIntent{18017e2d: PendingIntentRecord{30e29f62 com.htc.htcpowermanager broadcastIntent}}, i=com.htc.intent.action.HTCPOWERMGR_SMARTSYNC_SCREEN_OFF_TIME, t=0, cnt=1, w=1472217484898, Int=0
,08-26 15:18:04.947  1111  1159 I ActivityManager: Start proc 9278:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.smartsync.SmartSyncScreenOnOffTimeReceiver
,08-26 15:18:04.967  9278  9278 W HTCLOG  : use specified tag [FDManager], func [0].
08-26 15:18:04.967  9278  9278 W HTCLOG  : mask=0x18
,08-26 15:18:05.007  1111  3348 D PMS     : acquireWL(4d9e8f3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 9278 1000 null
,08-26 15:18:05.017  1111  1111 D PMS     : releaseWL(1866bd44): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
08-26 15:18:05.017  1111  3519 I ActivityManager: Killing 8747:com.htc.sense.news/u0a56 (adj 15): empty #17
08-26 15:18:05.017  1111  3519 D Process : killProcessQuiet, pid=8747
08-26 15:18:05.017  1111  3519 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processNextBroadcast:707 
08-26 15:18:05.017  9278  9300 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-26 15:18:05.017  9278  9300 W HTCLOG  : mask=0x18
,08-26 15:18:05.027  1111  1133 I ActivityManager: Recipient 8747
08-26 15:18:05.027  1111  5330 D PMS     : releaseWL(4d9e8f3): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,08-26 15:18:05.027  1111  3494 D PMS     : acquireWL(14b469b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 9278 1000 null
,08-26 15:18:05.027  9278  9301 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] bManual = false
,08-26 15:18:05.027  9278  9301 D SmartSyncScreenOnOffTimeReceiver: [updateNmRange] USERNIGHT_TIMESTART = 1, USERNIGHT_TIMEEND = 7, nStart = 1, nEnd = 7, bNormalRange = true
,08-26 15:18:05.027  9278  9301 D SmartSyncScreenOnOffTimeReceiver: AlarmOnTime = -1
,08-26 15:18:05.037  9278  9301 D SmartSyncScreenOnOffTimeReceiver: SettingOnTime = 1472274000000, randomSettingOnTime = 1472272316000
08-26 15:18:05.037  9278  9301 D SmartSyncScreenOnOffTimeReceiver: SettingOffTime = 1472252400000, randomSettingOffTime = 1472253342000
08-26 15:18:05.037  9278  9301 D SmartSyncScreenOnOffTimeReceiver: bDayMode = false,
08-26 15:18:05.037  9278  9301 D SmartSyncScreenOnOffTimeReceiver: bNightMode = true
08-26 15:18:05.037  9278  9301 D SmartSyncScreenOnOffTimeReceiver: bNightModeTurnOffOnce = false
,08-26 15:18:05.147  1111  3084 D PMS     : releaseWL(14b469b0): PARTIAL_WAKE_LOCK  SmartSyncScreenOnOffTimeReceiver_3 0x1 null
,08-26 15:18:13.407  1111  3033 D PMS     : acquireWL(3724d029): PARTIAL_WAKE_LOCK  *alarm* 0x1 1111 1000 WorkSource{10019}
,08-26 15:18:13.417  1111  3033 V AlarmManager: sending alarm PendingIntent{1acf4fae: PendingIntentRecord{2320214f com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.MCS_HEARTBEAT, t=2, cnt=1, w=957266, Int=0
08-26 15:18:13.427  1111  3033 V AlarmManager: sending alarm PendingIntent{331aebe0: PendingIntentRecord{594de99 android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=806617, Int=0,
08-26 15:18:13.427  1111  3033 V AlarmManager: sending alarm PendingIntent{10ee70dc: PendingIntentRecord{23c5a5ce com.htc.htcpowermanager broadcastIntent}}, i=com.htc.htcpowermanager.action.CALC_POWER, t=1, cnt=1, w=1472217490298, Int=0
,08-26 15:18:13.437  1111  3490 D PMS     : acquireWL(21145e5): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 3666 10019 null,
,08-26 15:18:13.447  1111  4139 D PMS     : releaseWL(21145e5): PARTIAL_WAKE_LOCK  GCM_HB_ALARM 0x1 null,
,08-26 15:18:13.507  9278  9278 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
,08-26 15:18:13.507  1111  1111 D PMS     : releaseWL(3724d029): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,08-26 15:18:13.517  9278  9304 D PowerUtils: getUserIdOfProcess, curUserId = 0
,08-26 15:18:13.517  9278  9304 D PowerUtils: isRunningUnderOwner, isOwner = true
,08-26 15:18:13.517  9278  9304 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
,08-26 15:18:13.527  9278  9304 D PowerUsageService: repeat time = 1472218393535
,08-26 15:18:13.667  9278  9304 I PowerUsageList:PowerUsageHelper: calcPower(), PowerProfile::POWER_SCREEN_FULL = 154.8
,08-26 15:18:13.687  9278  9304 D PowerUtils: getUserIdOfProcess, curUserId = 0
,08-26 15:18:13.697  9278  9304 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,08-26 15:18:13.697  9278  9304 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,08-26 15:18:13.707  9278  9304 D PowerUsageList:BatterySipperExt: gen(), null == sipper.uidObj, userId = 0
,08-26 15:18:13.717  9278  9304 D PowerUsageService: calcPower(), no data
,08-26 15:18:13.787  1111  3493 D PMS     : acquireWL(15e7836b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 3666 10019 null
,08-26 15:18:13.807  3666  8553 D GCM     : Message class com.google.e.a.a.h,
,08-26 15:18:13.817  1111  3516 D PMS     : releaseWL(15e7836b): PARTIAL_WAKE_LOCK  GCM_CONN 0x1 null,
,08-26 15:22:21.167   507   525 E PNP_UPDATERD: inotify_add_watch failed. (No such file or directory),
,08-26 15:22:25.457  1111  3348 D PMS     : acquireWL(2d5fbec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1111 1000 null
08-26 15:22:25.467  3198  3730 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-26 15:22:25.457  1111  3348 I BatteryService: n_update end
08-26 15:22:25.467  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:22:25.457  1111  3348 D PMS     : releaseWL(2d5fbec8): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
08-26 15:22:25.467  3319  3319 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-26 15:22:25.467  3319  3319 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-26 15:22:25.467  3198  3198 D PowerUI : closing low battery warning: level=100
08-26 15:22:25.467  1111  1111 D UsbnetService: BroadcastReceiver::onReceive+
08-26 15:22:25.467  1111  1111 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-26 15:22:25.467  1111  1111 D UsbnetService: onReceive BATTERY_CHANGED
08-26 15:22:25.467  1111  3076 D WifiController: battery changed pluggedType: 2
08-26 15:22:25.467  1111  1111 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-26 15:22:25.477  3198  3198 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-26 15:22:25.467  1111  1111 D UsbnetService: BroadcastReceiver::onReceive-
08-26 15:22:25.467  1111  3076 D WifiController: handleMessage: E msg.what=155652
08-26 15:22:25.467  1111  3076 D WifiController: processMsg: DeviceActiveState
08-26 15:22:25.467  1111  3076 D WifiController: processMsg: StaEnabledState
08-26 15:22:25.467  1111  3076 D WifiController: processMsg: DefaultState
08-26 15:22:25.467  1111  3076 D WifiController: handleMessage: X
,08-26 15:22:25.477  1111  1175 D HtcPowerSaver: updateBatteryInfo,
08-26 15:22:25.477  1111  1111 D HtcPowerSaver: Checking...
08-26 15:22:25.477  1111  1111 I HtcPowerSaver: >> updateStatus
08-26 15:22:25.487  1111  1111 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-26 15:22:25.487  1111  1111 I HtcPowerSaver: << updateStatus
,08-26 15:22:25.517  3198  3198 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-26 15:22:25.517  3198  3198 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-26 15:22:25.517  3198  3198 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-26 15:22:25.517  3198  3198 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-26 15:22:25.517  3198  3198 I FlashlightController: batteryLevelChange:100
,08-26 15:22:35.847  1111  1158 I UsageStatsService: User[0] Flushing usage stats to disk,
,TIME-OUT KILL (timeout was 1400000ms)
```
