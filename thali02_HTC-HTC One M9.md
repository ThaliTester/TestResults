#### Test 757892686fd65a6_thali02_HTC-HTC One M9 Logs


```
--------- beginning of main
07-01 08:58:38.944  1112  1132 D Process : killProcessQuiet, pid=7675
07-01 08:58:38.944  1112  1132 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
--------- beginning of system
07-01 08:58:38.944  1112  1132 I ActivityManager: Killing 7675:com.google.android.talk/u0a103 (adj 15): empty #17
07-01 08:58:38.964  8035  8035 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
07-01 08:58:38.964  8091  8111 I CAR.SERVICE: listener not found in list
,07-01 08:58:39.044  1112  3503 I ActivityManager: Recipient 7675
07-01 08:58:39.094  1112  3509 I ActivityManager: Start proc 8152:com.htc.cs.dm/u0a89 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
07-01 08:58:39.104  6453  8151 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-01 08:58:39.114  8152  8152 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:39.114  8152  8152 W HTCLOG  : mask=0x18
07-01 08:58:39.124  6453  8151 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 08:58:39.124  6453  8151 W HTCLOG  : mask=0x18
07-01 08:58:39.164  8152  8152 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8152 dbg=false s=true
07-01 08:58:39.174  8152  8152 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
07-01 08:58:39.184  1112  1131 I ActivityManager: Start proc 8176:com.google.android.apps.docs/u0a91 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
07-01 08:58:39.184  1112  1131 I ActivityManager: Killing 7370:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
07-01 08:58:39.184  1112  1131 D Process : killProcessQuiet, pid=7370
07-01 08:58:39.184  1112  1131 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
07-01 08:58:39.194  8176  8176 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:39.194  8176  8176 W HTCLOG  : mask=0x18
07-01 08:58:39.244  8158  8158 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-01 08:58:39.244  8158  8158 W HTCLOG  : mask=0x18
07-01 08:58:39.364  1112  3547 I ActivityManager: Recipient 7370
07-01 08:58:39.414  1112  1112 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
07-01 08:58:39.434  1112  3098 D PMS     : acquireWL(16544958): PARTIAL_WAKE_LOCK  Icing 0x1 3427 10019 null
07-01 08:58:39.444  8158  8202 W HTCLOG  : use specified tag [cutils-trace], func [0].
07-01 08:58:39.444  8158  8202 W HTCLOG  : mask=0x18
07-01 08:58:39.444  8158  8202 E cutils-trace: Error opening trace file: Permission denied (13)
07-01 08:58:39.474  6453  8151 I ApplicationLogger: canRun() : Opted Out
07-01 08:58:39.474  6453  8151 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 364 ms] updated apps [took 364 ms] 
07-01 08:58:39.474  1112  3547 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
07-01 08:58:39.484  1112  4762 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
07-01 08:58:39.514  8158  8158 D CustomizationManager: ====startRecUseTime====
07-01 08:58:39.514  8158  8158 D htc.customization.log.level:  is 
07-01 08:58:39.514  8158  8158 W CustomizationLogLevel: Level value is invalid, use default level 2
07-01 08:58:39.514  8176  8176 D DocsApplication: Plugin installer initialized.
07-01 08:58:39.514  1112  3538 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
07-01 08:58:39.534  8176  8176 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{1a4d49e9 com.google.android.apps.docs}
07-01 08:58:39.544  8176  8176 D TAG     : onCreate()
07-01 08:58:39.554  8176  8176 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
07-01 08:58:39.564  1112  3547 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
07-01 08:58:39.584  3545  3934 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-01 08:58:39.584  3545  3934 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2748d103 +
07-01 08:58:39.584  3545  3934 I Prism.WidgetManager: onLoadItems() +
07-01 08:58:39.594  8158  8158 D CustomizationManager:  Read ACC file spent 0.038 (s)
07-01 08:58:39.594  8158  8158 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
07-01 08:58:39.594  8158  8158 I CustomizationCIDLoader: Parsing tag category name = application
07-01 08:58:39.594  8158  8158 I CustomizationCIDLoader: Parsing tag category name = system
07-01 08:58:39.594  8158  8158 I CustomizationCIDLoader: Parsing tag category name = Settings
07-01 08:58:39.594  8158  8158 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-01 08:58:39.594  8158  8158 I CustomizationCIDLoader: Parsing tag category name = ACC
07-01 08:58:39.594  8158  8158 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
07-01 08:58:39.594  8158  8158 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
07-01 08:58:39.594  8158  8158 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
07-01 08:58:39.594  8158  8158 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
07-01 08:58:39.594  8158  8158 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-01 08:58:39.594  8158  8158 D CustomizationManager:  Read CID file spent 0.086 (s)
07-01 08:58:39.594  8158  8158 D CustomizationManager:  All configurations done spent 0.086 (s)
07-01 08:58:39.604  3545  3934 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-01 08:58:39.634  1112  3537 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8158 on display 0
07-01 08:58:39.634  1112  1174 D PMS     : acquireHCC(3cb8d0ed): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1112 1000 null
07-01 08:58:39.634  1112  1174 D PMS     : acquireHCC(2ea75b22): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1112 1000 null
07-01 08:58:39.644  1112  3537 V WindowManager: addAppToken: AppWindowToken{9de8ee9 token=Token{12d6eb70 ActivityRecord{395259b3 u0 com.test.thalitest/.MainActivity t43}}} to stack=1 task=43 at 0
07-01 08:58:39.654  1112  3537 I ActivityManager: Start proc 8216:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
07-01 08:58:39.664  3507  4099 D PhoneApp: EVENT_QUERY_MO_PACKAGES
07-01 08:58:39.664  8158  8158 W HTCLOG  : use specified tag [IPCThreadState], func [0].
07-01 08:58:39.664  8158  8158 W HTCLOG  : mask=0x18
07-01 08:58:39.664  8158  8215 W HTCLOG  : use specified tag [Vector], func [0].
07-01 08:58:39.664  8158  8215 W HTCLOG  : mask=0x18
07-01 08:58:39.664  3507  4099 D PhoneApp: -- N1 =0
07-01 08:58:39.664  8216  8216 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:39.664  8216  8216 W HTCLOG  : mask=0x18
07-01 08:58:39.664  3507  4099 D PhoneApp: -- N2 =0
07-01 08:58:39.664  3507  4099 D PhoneApp: -- N3 =0
07-01 08:58:39.674   544   544 I art     : Explicit concurrent mark sweep GC freed 8666(369KB) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 102us total 17.914ms
07-01 08:58:39.684  1112  1112 V ActivityManager: Display changed displayId=0
07-01 08:58:39.684  3334  3334 D DotMatrix: [EventService]  onDisplayChanged: 0
07-01 08:58:39.684  3334  3334 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
07-01 08:58:39.684   544   544 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 231us total 8.401ms
07-01 08:58:39.694  1112  3707 D ActivityManager: screenshot for ActivityRecord{395259b3 u0 com.test.thalitest/.MainActivity t43}, bitmap=null, time = 0
07-01 08:58:39.694   544   544 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 97us total 8.189ms
07-01 08:58:39.724  3545  3545 I TrimMemoryManager: [trimMemory] 20
07-01 08:58:39.744  8216  8216 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
07-01 08:58:39.784  3545  3934 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
07-01 08:58:39.814  8216  8216 I LibraryLoader: Time to load native libraries: 37 ms (timestamps 2043-2080)
07-01 08:58:39.814  8216  8216 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:58:39.824  8216  8216 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {6a79ba5}
07-01 08:58:39.824  8216  8216 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-01 08:58:39.824  8216  8216 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
07-01 08:58:39.834  8216  8216 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-01 08:58:39.834  8216  8216 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:39.834  8216  8216 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-01 08:58:39.874  8216  8239 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
07-01 08:58:39.884  8216  8243 D BluetoothAdapter: 761772922: getState() :  mService = null. Returning STATE_OFF
07-01 08:58:39.894  8216  8216 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
07-01 08:58:39.894  8216  8216 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
07-01 08:58:39.894  8216  8216 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
07-01 08:58:39.904  8216  8216 W HTCLOG  : use specified tag [libEGL], func [3].
07-01 08:58:39.904  8216  8216 W HTCLOG  : mask=0x18
07-01 08:58:39.904  8216  8216 W HTCLOG  : use specified tag [libEGL], func [3].
07-01 08:58:39.904  8216  8216 W HTCLOG  : mask=0x18
07-01 08:58:39.904  8216  8216 I Adreno  : QUALCOMM build                   : 065751b, 
07-01 08:58:39.904  8216  8216 I Adreno  : Build Date                       : 04/15/15
07-01 08:58:39.904  8216  8216 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
07-01 08:58:39.904  8216  8216 I Adreno  : Local Branch                     : 
07-01 08:58:39.904  8216  8216 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
07-01 08:58:39.904  8216  8216 I Adreno  : Remote Branch                    : NONE
07-01 08:58:39.904  8216  8216 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
07-01 08:58:39.934  3545  3934 I Prism.WidgetManager: onLoadItems() -
07-01 08:58:39.934  3545  3934 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2748d103 -
07-01 08:58:39.994  8216  8249 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
07-01 08:58:40.004  8216  8216 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:40.014  8216  8216 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-01 08:58:40.024  8216  8216 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
07-01 08:58:40.034  8216  8216 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:40.034  8216  8216 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-01 08:58:40.064  8216  8260 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 08:58:40.074  8216  8260 W HTCLOG  : mask=0x18
07-01 08:58:40.074  1112  3523 V WindowManager: Adding window Window{27f8e591 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{18603b1e u0 com.htc.launcher/com.htc.launcher.Launcher})
07-01 08:58:40.084  1112  3601 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
07-01 08:58:40.094  8216  8216 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
07-01 08:58:40.094  8216  8216 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
07-01 08:58:40.094  8216  8216 W HTCLOG  : mask=0x18
07-01 08:58:40.094  8216  8216 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 08:58:40.094  8216  8216 W HTCLOG  : mask=0x18
07-01 08:58:40.104  8216  8260 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 08:58:40.104  8216  8260 W HTCLOG  : mask=0x18
07-01 08:58:40.104  8216  8260 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 08:58:40.104  8216  8260 W HTCLOG  : mask=0x18
07-01 08:58:40.104  8216  8260 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 08:58:40.104  8216  8260 W HTCLOG  : mask=0x18
07-01 08:58:40.104  8216  8260 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
07-01 08:58:40.104  8216  8260 W HTCLOG  : mask=0x18
07-01 08:58:40.104  1112  1132 D PMS     : releaseWL(44e16b2): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
07-01 08:58:40.114  8216  8260 W HTCLOG  : use specified tag [Surface], func [3].
07-01 08:58:40.114  8216  8260 W HTCLOG  : mask=0x18
07-01 08:58:40.114  8216  8260 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
07-01 08:58:40.114  8216  8260 W HTCLOG  : mask=0x18
07-01 08:58:40.114  8216  8260 W HTCLOG  : use specified tag [qdmemalloc], func [0].
07-01 08:58:40.114  8216  8260 W HTCLOG  : mask=0x18
07-01 08:58:40.174  1112  1152 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +482ms (total +530ms)
07-01 08:58:40.224  8216  8216 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8216
07-01 08:58:40.284  8176  8269 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 08:58:40.284  8176  8269 W HTCLOG  : mask=0x18
07-01 08:58:40.284  8216  8216 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-01 08:58:40.334  8216  8263 D jxcore_app_log: JniHelper::setJavaVM(0xab158b70), pthread_self() = -1408622232
07-01 08:58:40.334  8176  8176 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
07-01 08:58:40.334  8216  8263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-01 08:58:40.334  8216  8263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-01 08:58:40.334  8216  8263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-01 08:58:40.334  8216  8263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-01 08:58:40.334  8216  8263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-01 08:58:40.334  8216  8263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1461f001 added. We now have 1 listener(s)
07-01 08:58:40.344  1112  3098 I ActivityManager: Start proc 8277:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
07-01 08:58:40.344  1112  3538 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-01 08:58:40.344  8216  8263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
07-01 08:58:40.344  8216  8263 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
07-01 08:58:40.344  8216  8263 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-01 08:58:40.344  8216  8263 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-01 08:58:40.354  8216  8263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d009494 added. We now have 1 listener(s)
07-01 08:58:40.354  8216  8263 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-01 08:58:40.354  8277  8277 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:40.354  8277  8277 W HTCLOG  : mask=0x18
07-01 08:58:40.354  8216  8263 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-01 08:58:40.354  8216  8263 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
07-01 08:58:40.354  1112  3090 D WifiService: New client listening to asynchronous messages
07-01 08:58:40.354  8216  8263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-01 08:58:40.354  8216  8263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-01 08:58:40.354  8216  8263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-01 08:58:40.354  8216  8263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-01 08:58:40.354  8216  8263 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-01 08:58:40.354  1112  3523 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
07-01 08:58:40.364  8216  8263 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
07-01 08:58:40.364  8216  8263 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
07-01 08:58:40.364  8216  8263 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-01 08:58:40.364  8216  8263 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-01 08:58:40.364  8216  8263 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
07-01 08:58:40.364  8216  8263 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-01 08:58:40.364  8216  8263 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-01 08:58:40.364  8216  8263 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-01 08:58:40.364  8216  8263 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-01 08:58:40.364  8216  8263 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-01 08:58:40.364  8216  8263 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-01 08:58:40.364  8216  8263 D io.jxcore.node.ConnectivityMonitor: start: OK
07-01 08:58:40.364  8216  8263 I io.jxcore.node.LifeCycleMonitor: start: OK
07-01 08:58:40.384  8277  8277 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-01 08:58:40.434  8216  8216 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-01 08:58:40.454  1112  3045 D PMS     : acquireWL(3988de7): PARTIAL_WAKE_LOCK  *alarm* 0x1 1112 1000 WorkSource{1000}
07-01 08:58:40.454  1112  3045 V AlarmManager: sending alarm PendingIntent{2adafd94: PendingIntentRecord{2cf9403d android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1467356312733, Int=0
07-01 08:58:40.464  3427  6695 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
07-01 08:58:40.484  3427  6695 D Icing   : Loaded CLD2 Version V2.0 - 20140131
07-01 08:58:40.564  3427  6695 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
07-01 08:58:40.564  1112  3098 D PMS     : releaseWL(16544958): PARTIAL_WAKE_LOCK  Icing 0x1 null
,07-01 08:58:40.634  1112  3098 D PMS     : acquireWL(17562183): PARTIAL_WAKE_LOCK  AsyncService 0x1 8277 10128 null
,07-01 08:58:40.634  1112  1174 D PMS     : releaseHCC(3cb8d0ed): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
,07-01 08:58:40.634  1112  1174 D PMS     : releaseHCC(2ea75b22): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
07-01 08:58:40.634  1112  3538 D PMS     : releaseWL(17562183): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,07-01 08:58:40.684  1112  4762 D Process : killProcessQuiet, pid=7444,
07-01 08:58:40.684  1112  4762 I ActivityManager: Killing 7444:com.htc.sdm/u0a61 (adj 15): empty #17
07-01 08:58:40.684  1112  4762 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,07-01 08:58:40.784  1112  3503 I ActivityManager: Recipient 7444,
,07-01 08:58:40.794  1112  3045 V AlarmManager: sending alarm PendingIntent{1c345f00: PendingIntentRecord{1a719281 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=93007, Int=0
,07-01 08:58:40.794  3889  3889 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,07-01 08:58:40.814  3889  3889 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
07-01 08:58:40.814  3889  3889 D c       : Getting all permits...
,07-01 08:58:40.824  3889  3889 D a       : Opening database...
,07-01 08:58:40.834  3889  3889 D a       : Opening database auth.proximity.permit_store...
,07-01 08:58:40.834  3889  3889 D a       : Closing database...,
,07-01 08:58:40.844  3427  3427 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,07-01 08:58:40.874  7479  7479 D AlarmReceiver: ACTION_RESTART_INTENT
,07-01 08:58:40.874  1112  1112 D PMS     : acquireWL(47d0d7e): PARTIAL_WAKE_LOCK  *backup* 0x1 1112 1000 null
,07-01 08:58:40.874  1112  1112 D PMS     : releaseWL(3988de7): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
,07-01 08:58:40.884  7479  7479 D LocalBluetoothProfile: getPriorityOnValue = 100
07-01 08:58:40.884  7479  7479 D LocalBluetoothProfile: getPriorityOffValue = 0
07-01 08:58:40.884  7479  7479 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
07-01 08:58:40.884  7479  7479 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,07-01 08:58:40.884  3427  8307 D LocationInitializer: Restart initialization of location
,07-01 08:58:40.894  1112  3159 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
,07-01 08:58:40.894  1112  3159 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
07-01 08:58:40.894  1112  3159 D PMS     : releaseWL(47d0d7e): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,07-01 08:58:40.924  7479  8309 D HtcModeClient: start the htcmodeservice thread,
,07-01 08:58:40.934  7479  8309 D HtcModeClient: initCanAgent
,07-01 08:58:40.934  7479  8309 I CANMesgAgentLocalSocket: CANAgent Id = 0
,07-01 08:58:40.934  7479  8309 D HtcModeClient: sense info: version = none, id = 2,
07-01 08:58:40.934  8216  8300 W jxcore-log: Initializing JXcore engine
07-01 08:58:40.934  8216  8300 W jxcore-log: JXcore engine is ready
,07-01 08:58:40.944  7479  8309 D HtcModeClient: display info: width = 1080, height = 1776,
07-01 08:58:40.944  7479  8309 D HtcModeClient: display info: mode = 10
07-01 08:58:40.944  7479  7479 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
07-01 08:58:40.944  7479  7479 D HtcModeClient: connectState: BT_TURNON_BYME = false
07-01 08:58:40.944  7479  7479 D HtcModeClient: connectState: CONNECTION_READY = false
07-01 08:58:40.944  7479  7479 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
07-01 08:58:40.944  7479  7479 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
07-01 08:58:40.944  7479  7479 D HtcModeClient: connectState: PHONE_PULGIN = false
07-01 08:58:40.944  7479  7479 D HtcModeClient: connectState: Force_AWAKE = false
07-01 08:58:40.944  7479  7479 D HtcModeClient: connectState: PHONE_PULGIN = true
07-01 08:58:40.944  7479  7479 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,07-01 08:58:40.994  8216  8300 W jxcore-log: Starting JXcore engine,
,07-01 08:58:41.084  8216  8300 W jxcore-log: Platform android,
07-01 08:58:41.084  8216  8300 W jxcore-log: 
07-01 08:58:41.094  8216  8300 W jxcore-log: Process ARCH arm
07-01 08:58:41.094  8216  8300 W jxcore-log: 
,07-01 08:58:41.274  8216  8300 I jxcore-log: JXcore Cordova bridge is ready!,
07-01 08:58:41.274  8216  8300 I jxcore-log: 
07-01 08:58:41.274  8216  8300 W jxcore-log: JXcore engine is started
07-01 08:58:41.284  8216  8263 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
07-01 08:58:41.284  8216  8216 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-01 08:58:41.294  8216  8300 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
07-01 08:58:41.294  8216  8300 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,07-01 08:58:41.304  8216  8216 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
07-01 08:58:41.304  8216  8216 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,07-01 08:58:41.314  8216  8216 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
07-01 08:58:41.314  8216  8216 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-01 08:58:41.314  8216  8216 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-01 08:58:41.314  8216  8216 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-01 08:58:41.314  8216  8216 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-01 08:58:41.314  8216  8216 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-01 08:58:41.314  8216  8216 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1461f001 removed from the list
07-01 08:58:41.314  8216  8216 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-01 08:58:41.314  8216  8216 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d009494 removed from the list
07-01 08:58:41.314  8216  8216 D io.jxcore.node.ConnectivityMonitor: stop
07-01 08:58:41.314  8216  8216 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
07-01 08:58:41.314  8216  8216 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-01 08:58:41.484  8311  8311 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
07-01 08:58:41.484  8311  8311 W HTCLOG  : mask=0x18
,07-01 08:58:41.664  8311  8316 W HTCLOG  : use specified tag [cutils-trace], func [0].,
07-01 08:58:41.664  8311  8316 W HTCLOG  : mask=0x18
07-01 08:58:41.664  8311  8316 E cutils-trace: Error opening trace file: Permission denied (13),
,07-01 08:58:41.724  8311  8311 D CustomizationManager: ====startRecUseTime====,
07-01 08:58:41.724  8311  8311 D htc.customization.log.level:  is 
,07-01 08:58:41.724  8311  8311 W CustomizationLogLevel: Level value is invalid, use default level 2
,07-01 08:58:41.804  8311  8311 D CustomizationManager:  Read ACC file spent 0.044 (s),
,07-01 08:58:41.814  8311  8311 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml,
,07-01 08:58:41.814  8311  8311 I CustomizationCIDLoader: Parsing tag category name = application
07-01 08:58:41.814  8311  8311 I CustomizationCIDLoader: Parsing tag category name = system
,07-01 08:58:41.814  8311  8311 I CustomizationCIDLoader: Parsing tag category name = Settings
07-01 08:58:41.814  8311  8311 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
07-01 08:58:41.814  8311  8311 I CustomizationCIDLoader: Parsing tag category name = ACC
,07-01 08:58:41.814  8311  8311 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240,
07-01 08:58:41.814  8311  8311 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000,
07-01 08:58:41.814  8311  8311 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
07-01 08:58:41.814  8311  8311 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider,
07-01 08:58:41.814  8311  8311 I CustomizationCIDLoader: Parsing tag category name = AudioService
07-01 08:58:41.814  8311  8311 D CustomizationManager:  Read CID file spent 0.093 (s)
07-01 08:58:41.814  8311  8311 D CustomizationManager:  All configurations done spent 0.093 (s),
,07-01 08:58:41.874  1112  3707 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8311, uid=2000
,07-01 08:58:41.874  1112  1144 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
07-01 08:58:41.874  1112  1144 D Process : killProcessQuiet, pid=8216
07-01 08:58:41.874  1112  1144 I ActivityManager: Killing 8216:com.test.thalitest/u0a142 (adj 9): stop com.test.thalitest
,07-01 08:58:41.874  1112  1144 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
,07-01 08:58:41.964   524   524 W HTCLOG  : use specified tag [Vector], func [0].
07-01 08:58:41.964   524   524 W HTCLOG  : mask=0x18
,07-01 08:58:41.974  1112  3523 I ActivityManager: Recipient 8216
07-01 08:58:41.974  1112  3090 D WifiService: Client connection lost with reason: 4
,07-01 08:58:42.094  1112  3523 W ActivityManager: Spurious death for ProcessRecord{c8abed7 8216:com.test.thalitest/u0a142}, curProc for 8216: null,
,07-01 08:58:42.094  1112  1182 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed,
,07-01 08:58:42.154  1112  3048 W SystemReader: Cannot find grip_rejection_width, use default value instead
07-01 08:58:42.164  1112  3054 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
07-01 08:58:42.164  3334  3334 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
07-01 08:58:42.164  1112  3054 V NetworkPolicy: writePolicyLocked()
07-01 08:58:42.164  3334  3334 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
07-01 08:58:42.164  1112  1132 D PMS     : acquireWL(e82f3c4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4340 10019 null
,07-01 08:58:42.174  3669  4105 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
07-01 08:58:42.184  3719  8330 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-01 08:58:42.184  4340  4470 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-01 08:58:42.184  1112  3053 D PMS     : acquireWL(183df9e2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1112 1000 null
07-01 08:58:42.184  1112  3509 D PMS     : releaseWL(e82f3c4): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
07-01 08:58:42.194  3669  4105 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
07-01 08:58:42.204  3427  3427 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
07-01 08:58:42.204  1112  3053 D PMS     : releaseWL(183df9e2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
,07-01 08:58:42.214  3669  4105 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
07-01 08:58:42.214  3669  4105 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,07-01 08:58:42.224  1112  3537 D PMS     : acquireWL(10d89beb): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 3427 10019 null,
,07-01 08:58:42.224  1112  1143 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,07-01 08:58:42.224  6453  6453 I art     : Explicit concurrent mark sweep GC freed 12291(759KB) AllocSpace objects, 2(40KB) LOS objects, 34% free, 3MB/5MB, paused 459us total 110.421ms
,07-01 08:58:42.234  1112  3054 D NetworkPolicy: notifyPoliciesChangeLocked: no change
07-01 08:58:42.234  1112  3054 V NetworkPolicy: updateNetworkEnabledLocked()
07-01 08:58:42.234  3889  3889 I ConfigService: onCreate
07-01 08:58:42.234  1112  3054 V NetworkPolicy: updateNotificationsLocked()
07-01 08:58:42.234  3889  3889 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,07-01 08:58:42.244  3889  3889 I ConfigService: onBind returning update interface
,07-01 08:58:42.244  3427  3427 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,07-01 08:58:42.254  3669  4105 E ExternalAccountType: Unsupported attribute readOnly
,07-01 08:58:42.254  3507  3507 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
07-01 08:58:42.264  1112  1112 W PackageManager: Unable to load service info ResolveInfo{3c3b683e com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
07-01 08:58:42.264  1112  1112 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
07-01 08:58:42.264  1112  1112 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 08:58:42.264  1112  1112 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 08:58:42.264  3889  3889 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
07-01 08:58:42.264  3889  3889 I ConfigService: onBind returning config service
,07-01 08:58:42.284  1112  1112 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-01 08:58:42.284  1112  4762 I ActivityManager: Start proc 8332:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver
07-01 08:58:42.284  1112  3523 D PMS     : acquireWL(10a32dd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3889 10019 null
07-01 08:58:42.294  3545  3934 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
07-01 08:58:42.294  1112  3098 D PMS     : releaseWL(10a32dd): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
07-01 08:58:42.294  3545  3934 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
07-01 08:58:42.294  3889  3889 I ConfigService: onDestroy
07-01 08:58:42.294  8332  8332 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:42.294  8332  8332 W HTCLOG  : mask=0x18
07-01 08:58:42.294  3545  3545 I Launcher: Deferring update until onResume
,07-01 08:58:42.294  3545  3545 D Launcher: waitUntilResume // bindAppsRemoved
,07-01 08:58:42.344  8332  8332 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
07-01 08:58:42.344  8332  8332 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 08:58:42.354  3487  3487 D Nfc-Utils: isNxpCodebase: isNxp=false
,07-01 08:58:42.364  3545  3545 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
07-01 08:58:42.364  8332  8332 I MultiDex: VM with version 2.1.0 has multidex support
07-01 08:58:42.364  8332  8332 I MultiDex: install
07-01 08:58:42.364  8332  8332 I MultiDex: VM has multidex support, MultiDex support library is disabled.
07-01 08:58:42.364  3545  3545 I ThreadedRenderer: Defer allocateBuffers to drawing time
,07-01 08:58:42.374  8332  8332 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application',
,07-01 08:58:42.384  1112  1182 I art     : Explicit concurrent mark sweep GC freed 34813(2MB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 15MB/23MB, paused 2.023ms total 242.777ms
07-01 08:58:42.384  8332  8332 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
07-01 08:58:42.384  1112  5698 I art     : WaitForGcToComplete blocked for 156.395ms for cause Explicit
,07-01 08:58:42.414  3427  8357 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest,
07-01 08:58:42.424  8311  8311 I art     : System.exit called, status: 0
07-01 08:58:42.424  3427  8357 D AccountUtils: Clearing selected account for com.test.thalitest,
,07-01 08:58:42.424  8359  8359 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:42.424  1112  1131 I ActivityManager: Start proc 8359:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver
07-01 08:58:42.424  8359  8359 W HTCLOG  : mask=0x18
,07-01 08:58:42.464  7767  8386 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id),
,07-01 08:58:42.474  1112  3509 D Process : killProcessQuiet, pid=7736,
07-01 08:58:42.474  1112  3509 I ActivityManager: Delay finish: com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver
07-01 08:58:42.474  1112  3509 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
07-01 08:58:42.474  1112  3509 I ActivityManager: Killing 7736:com.htc.calendar/u0a6 (adj 15): empty #17
,07-01 08:58:42.484  3427  8389 I PeopleContactsSync: CP2 sync disabled,
,07-01 08:58:42.494  1112  3537 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=3427, uid=10019, userID:0
,07-01 08:58:42.544  1112  1131 I ActivityManager: Recipient 7736,
,07-01 08:58:42.544  1112  5698 I art     : Explicit concurrent mark sweep GC freed 6275(350KB) AllocSpace objects, 1(20KB) LOS objects, 33% free, 15MB/22MB, paused 1.871ms total 159.732ms
,07-01 08:58:42.584  1112  3707 I ActivityManager: Resuming delayed broadcast
07-01 08:58:42.584  1112  3523 D PMS     : acquireWL(17b53077): PARTIAL_WAKE_LOCK  Icing 0x1 3427 10019 null,
07-01 08:58:42.584  3427  6695 I Icing   : doRemovePackageData com.test.thalitest
07-01 08:58:42.584  1112  1132 D PMS     : releaseWL(17b53077): PARTIAL_WAKE_LOCK  Icing 0x1 null
,07-01 08:58:42.594  3669  3669 E PackageActionReceiver: ACTION_PACKAGE_REMOVED
,07-01 08:58:42.594  3614  8390 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,07-01 08:58:42.604  3614  8390 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,07-01 08:58:42.624  3427  8387 W GmsApplication: Using Auth Proxy for data requests.
,07-01 08:58:42.624  3427  8387 W GmsApplication: Using Auth Proxy for data requests.
,07-01 08:58:42.634  3545  3545 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
07-01 08:58:42.634  3545  3545 I ContextualWidget: package com.test.thalitest removed
07-01 08:58:42.634  3545  3949 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
,07-01 08:58:42.644  3545  8392 I ContextualWidget: com.test.thalitest is not installed,
07-01 08:58:42.644  3545  8392 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,07-01 08:58:42.664  1112  3537 I ActivityManager: Start proc 8393:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
,07-01 08:58:42.664  8393  8393 W HTCLOG  : use specified tag [FDManager], func [0].
,07-01 08:58:42.664  8393  8393 W HTCLOG  : mask=0x18
07-01 08:58:42.674  3545  3949 I ContextualWidget: MFU.onDownloadDataSetChanged
07-01 08:58:42.674  3545  3949 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
07-01 08:58:42.674  3545  3545 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId 43dcafa7-0286-44a9-9c40-0151dcba33b8, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
07-01 08:58:42.674  3545  3545 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId 43dcafa7-0286-44a9-9c40-0151dcba33b8, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))],
,07-01 08:58:42.674  3427  3453 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
07-01 08:58:42.674  3427  3453 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
07-01 08:58:42.674  3427  3453 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,07-01 08:58:42.794  1112  3537 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/,
,07-01 08:58:42.794  8393  8393 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
07-01 08:58:42.794  8393  8393 D IdefixUninstallListener: package_removed = com.test.thalitest
,07-01 08:58:42.834  8393  8393 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
,07-01 08:58:42.834  8393  8393 W HTCLOG  : mask=0x18
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219),
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467),
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 08:58:42.834  8393  8393 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 08:58:42.834  8393  8393 W System.err: java.sql.SQLException: Getting a writable database from helper a@4445bf6 failed
07-01 08:58:42.834  1112  3547 I ActivityManager: Killing 7592:com.google.android.gm/u0a97 (adj 15): empty #17
07-01 08:58:42.834  8393  8393 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
07-01 08:58:42.834  8393  8393 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
07-01 08:58:42.834  8393  8393 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
07-01 08:58:42.834  8393  8393 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
07-01 08:58:42.834  8393  8393 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
07-01 08:58:42.834  8393  8393 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
07-01 08:58:42.834  8393  8393 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 08:58:42.834  8393  8393 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:42.834  8393  8393 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:42.834  8393  8393 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 08:58:42.834  8393  8393 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 08:58:42.834  8393  8393 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:42.834  8393  8393 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:42.834  8393  8393 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
07-01 08:58:42.834  8393  8393 W System.err: 	... 15 more
07-01 08:58:42.834  1112  3547 D Process : killProcessQuiet, pid=7592
07-01 08:58:42.844  1112  3547 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,07-01 08:58:42.934  1112  3098 I ActivityManager: Recipient 7592,
,07-01 08:58:42.954  7479  8309 I HtcModeClient: handler message = 4011
,07-01 08:58:42.954  7479  8309 D HtcModeClient: getConnectionCheckCount first 0
07-01 08:58:42.954  7479  8309 D HtcModeClient: getConnectionCheckCount count = 8
07-01 08:58:42.954  7479  8309 E HtcModeClient: Check connection and retry 9 times.
07-01 08:58:42.954  7479  8309 D HtcModeClient: setConnectionCheckCount count = 9
07-01 08:58:42.954  7479  8309 D HtcModeClient: setupRestart delayedTime = 3000
,07-01 08:58:42.954  7479  7540 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak
,07-01 08:58:42.954  7479  7479 D HtcModeClient: setBtPriority priority = on
07-01 08:58:42.954  7479  7479 D HtcModeClient: unbindBlueToothService
07-01 08:58:42.954  7479  7479 D HtcModeClient: Don't start project servcice
,07-01 08:58:42.954  6453  8418 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
07-01 08:58:42.954  3427  8383 W DriveInitializer: Awaiting to be initialized
07-01 08:58:42.954  7479  7479 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,07-01 08:58:42.964  3427  8419 W DriveInitializer: Background init thread started
,07-01 08:58:42.974  3427  8419 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock43] disk I/O error
,07-01 08:58:42.974  3427  8419 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 08:58:42.974  3427  8419 W HTCLOG  : mask=0x18
07-01 08:58:42.974  3427  8419 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55ba1ad8a0
,07-01 08:58:42.984  3427  8419 E DocListDatabase: Failed to delete from ContentFileDeletionLock43
07-01 08:58:42.984  3427  8419 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 08:58:42.984  3427  8419 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-01 08:58:42.984  3427  8419 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-01 08:58:42.984  3427  8419 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-01 08:58:42.984  3427  8419 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-01 08:58:42.984  3427  8419 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-01 08:58:42.984  3427  8419 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
07-01 08:58:42.984  3427  8419 E DocListDatabase: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
07-01 08:58:42.984  3427  8419 E DocListDatabase: 	at com.google.android.gms.drive.v.run(SourceFile:69)
07-01 08:58:42.984  3427  8419 W DriveInitializer: Background init thread ended
07-01 08:58:42.984  1112  3547 I ActivityManager: Start proc 8420:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver,
07-01 08:58:42.984  3427  8419 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
07-01 08:58:42.984  3427  8419 E AndroidRuntime: Process: com.google.android.gms, PID: 3427
07-01 08:58:42.984  3427  8419 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 08:58:42.984  3427  8419 E AndroidRuntime: ,	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-01 08:58:42.984  3427  8419 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-01 08:58:42.984  3427  8419 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-01 08:58:42.984  3427  8419 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-01 08:58:42.984  3427  8419 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-01 08:58:42.984  3427  8419 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
07-01 08:58:42.984  3427  8419 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
07-01 08:58:42.984  3427  8419 E AndroidRuntime: 	at com.google.android.gms.drive.v.run(SourceFile:69)
,07-01 08:58:42.984  3427  8383 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: Can't write: system_app_crash
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop120.tmp: open failed: EROFS (Read-only file system)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:42.994  1112  8433 E DropBoxManagerService: 	... 5 more
07-01 08:58:42.984  3427  8383 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55ba1ad8a0
07-01 08:58:42.994  1112  3523 I ActivityManager: Killing 7286:com.google.android.music:main/u0a115 (adj 15): empty #17
07-01 08:58:42.984  3427  8383 E DriveAsyncService: disk I/O error (code 3850)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.m(SourceFile:501)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:495)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1406)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.ao.a(SourceFile:16)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
,07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:42.984  3427  8383 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:42.984  1112  4762 E ActivityManager: App crashed! Process: com.google.android.gms
07-01 08:58:42.984  7479  7479 D HtcModeClient: connectState: CONNECTION_READY = false
07-01 08:58:42.984  7479  7479 D SilentMusic: call stop
07-01 08:58:42.984  7479  7479 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
07-01 08:58:42.984  7479  8310 W CANMesgAgentLocalSocket: read the terminate packet, so break
07-01 08:58:42.994  7479  7479 D HtcModeClient: onDestroy
07-01 08:58:42.994  8420  8420 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:42.994  8420  8420 W HTCLOG  : mask=0x18,
07-01 08:58:42.994  1112  3523 D Process : killProcessQuiet, pid=7286
07-01 08:58:42.994  1112  3523 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
07-01 08:58:43.004  3545  3857 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak
,07-01 08:58:43.004  6453  8418 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
07-01 08:58:43.004  6453  8418 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 08:58:43.004  6453  8418 W HTCLOG  : mask=0x18
07-01 08:58:43.004  6453  8418 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55ba0f03e0
07-01 08:58:43.004  3427  8419 D Process : killProcess, pid=3427
07-01 08:58:43.004  3427  8419 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
,07-01 08:58:43.004  3427  8419 W HTCLOG  : use specified tag [Process], func [0].
07-01 08:58:43.004  3427  8419 W HTCLOG  : mask=0x18
,07-01 08:58:43.054  1112  3537 I ActivityManager: Recipient 7286,
07-01 08:58:43.054  1112  3538 D MediaRouterService: Client com.google.android.music (pid 7286): Died!
,07-01 08:58:43.074  1112  3098 I ActivityManager: Recipient 3427,
07-01 08:58:43.074  1112  3503 D PMS     : handleWLDeath(10d89beb): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
07-01 08:58:43.074  1112  3707 D PMS     : handleWLDeath(317230c4): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
,07-01 08:58:43.084  8035  8050 E AndroidHttpClient: Leak found
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: ,	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102),
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372),
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 08:58:43.084  8035  8050 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,07-01 08:58:43.104  1112  3098 I ActivityManager: Process com.google.android.gms (pid 3427) has died,
07-01 08:58:43.104  1112  3098 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
07-01 08:58:43.104  1112  3098 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 11000ms
,07-01 08:58:43.114  6453  8418 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,07-01 08:58:43.114  6453  8418 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
07-01 08:58:43.114  6453  8418 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6453,
07-01 08:58:43.114  6453  8418 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: ,	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.114  6453  8418 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:43.114  1112  3538 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: Can't write: system_app_crash
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.114  1112  8443 E DropBoxManagerService: ,	... 5 more
07-01 08:58:43.114  6453  8418 D Process : killProcess, pid=6453
07-01 08:58:43.114  6453  8418 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
07-01 08:58:43.114  6453  8418 W HTCLOG  : use specified tag [Process], func [0].
07-01 08:58:43.114  6453  8418 W HTCLOG  : mask=0x18
,07-01 08:58:43.144  8420  8420 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 
,07-01 08:58:43.154  1112  3537 D PMS     : acquireWL(2017b149): PARTIAL_WAKE_LOCK  AsyncService 0x1 8277 10128 null
,07-01 08:58:43.154   493   493 E lowmemorykiller: Error writing /proc/6453/oom_score_adj; errno=22
07-01 08:58:43.154   493   493 E lowmemorykiller: Error writing /proc/6453/oom_score_adj; errno=22
,07-01 08:58:43.154  8152  8152 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,07-01 08:58:43.154  1112  3503 D PMS     : releaseWL(2017b149): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
07-01 08:58:43.154  8420  8444 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 08:58:43.154  8420  8444 W HTCLOG  : mask=0x18
07-01 08:58:43.154  8420  8444 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73]
07-01 08:58:43.154  8420  8444 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.android.keychain/databases/grants.db) - 
07-01 08:58:43.154  8420  8444 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 08:58:43.154  8420  8444 W HTCLOG  : mask=0x18
07-01 08:58:43.154  8420  8444 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.android.keychain/databases/grants.db, flag: 6, ret: 14
07-01 08:58:43.154  8420  8444 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
07-01 08:58:43.154  8152  8152 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.,
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
,07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
,07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.154  8420  8444 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.154   493   493 E lowmemorykiller: Error writing /proc/6453/oom_score_adj; errno=22,
07-01 08:58:43.164  1112  3509 I ActivityManager: Recipient 6453
07-01 08:58:43.154  8420  8444 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
07-01 08:58:43.154  8420  8444 E AndroidRuntime: Process: com.android.keychain, PID: 8420
07-01 08:58:43.154  8420  8444 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
,07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.154  8420  8444 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.164  1112  3090 D WifiService: Client connection lost with reason: 4,
07-01 08:58:43.164   493   493 E lowmemorykiller: Error opening /proc/6453/oom_score_adj; errno=2
07-01 08:58:43.164  8152  8152 I DeviceManagement: WorkflowService: Starting workflow service
07-01 08:58:43.164  8152  8446 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@21261546] args=[Bundle[mParcelledData.dataSize=112]]
07-01 08:58:43.164  8152  8446 I DeviceManagement: PackageUpdateWorkflow: ==================================================
07-01 08:58:43.164  8152  8446 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
,07-01 08:58:43.164  8152  8446 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,07-01 08:58:43.174  8152  8446 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
,07-01 08:58:43.174  1112  1132 I ActivityManager: Start proc 8447:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver,
07-01 08:58:43.174  1112  3098 E ActivityManager: App crashed! Process: com.android.keychain
07-01 08:58:43.184  1112  3509 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6453) has died
07-01 08:58:43.184  1112  3509 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 10924ms
07-01 08:58:43.184  1112  3509 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10924ms
07-01 08:58:43.184  1112  3098 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,07-01 08:58:43.184  1112  3098 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.184  1112  3098 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.184  1112  3098 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.184  1112  3098 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.184  1112  3098 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
,07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 08:58:43.184  1112  3098 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 08:58:43.184  1112  3098 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,07-01 08:58:43.184  1112  3098 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.184  1112  3098 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.194  1112  8461 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 08:58:43.194  1112  8461 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467356323199.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 08:58:43.194  1112  8461 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.194  1112  8461 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.194  1112  8461 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:43.194  1112  8461 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 08:58:43.194  1112  8461 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:43.194  1112  8461 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.194  1112  8461 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.194  1112  8461 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.194  1112  8461 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.194  1112  8461 E ErrorReport: 	... 4 more
07-01 08:58:43.184  1112  3098 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.184  1112  3098 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.184  1112  3098 W System.err: 	... 14 more
07-01 08:58:43.184  1112  3098 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.184  1112  3098 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.184  1112  3098 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.184  1112  3098 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.184  1112  3098 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 08:58:43.184  1112  3098 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 08:58:43.184  1112  3098 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 08:58:43.184  1112  3098 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:43.184  1112  3098 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.184  1112  3098 W System.err: 	at libcore.io.Posix.,open(Native Method)
07-01 08:58:43.184  1112  3098 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.184  1112  3098 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.184  1112  3098 W System.err: 	... 14 more
07-01 08:58:43.194  8447  8447 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:43.194  8447  8447 W HTCLOG  : mask=0x18
07-01 08:58:43.194  1112  3601 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.194  1112  3601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.194  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.194  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.194  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.194  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 08:58:43.194  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 08:58:43.194  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 08:58:43.194  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 08:58:43.194  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 08:58:43.194  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 08:58:43.194  1112  3601 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.194  1112  3601 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.194  1112  3601 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.194  1112  3601 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.194  8420  8444 D Process : killProcess, pid=8420
07-01 08:58:43.194  8420  8444 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 08:58:43.194  8420  8444 W HTCLOG  : use specified tag [Process], func [0].
07-01 08:58:43.194  8420  8444 W HTCLOG  : mask=0x18
07-01 08:58:43.194  1112  3601 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.194  1112  3601 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.194  1112  3601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.194  1112  3601 W System.err: 	... 12 more
,07-01 08:58:43.204  8152  8446 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,07-01 08:58:43.214  8152  8469 I DeviceManagement: SessionStateController: Checking invariants...
,07-01 08:58:43.214  8447  8447 W ContextImpl: Unable to create files subdir /data/data/com.android.documentsui/cache
07-01 08:58:43.214  8447  8447 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-01 08:58:43.244  8447  8447 W HTCLOG  : use specified tag [SQLiteDBG], func [0].,
07-01 08:58:43.244  8447  8447 W HTCLOG  : mask=0x18
07-01 08:58:43.244  8447  8447 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73]
07-01 08:58:43.244  8447  8447 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.android.documentsui/databases/recents.db) - 
07-01 08:58:43.244  8447  8447 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 08:58:43.244  8447  8447 W HTCLOG  : mask=0x18
07-01 08:58:43.244  8447  8447 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.android.documentsui/databases/recents.db, flag: 6, ret: 14,
07-01 08:58:43.244  8447  8447 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190),
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 08:58:43.244  8447  8447 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: FATAL EXCEPTION: main
07-01 08:58:43.244  8447  8447 E AndroidRuntime: Process: com.android.documentsui, PID: 8447
07-01 08:58:43.244  8447  8447 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database,
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method),
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-01 08:58:43.244  8447  8447 E AndroidRuntime: 	... 9 more
07-01 08:58:43.244  1112  3547 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 08:58:43.244  1112  3547 E ActivityManager: App crashed! Process: com.android.documentsui
07-01 08:58:43.244  1112  3547 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.244  1112  3547 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.244  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.244  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.244  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.244  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 08:58:43.244  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 08:58:43.244  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 08:58:43.244  1112  3547 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-01 08:58:43.254  1112  3707 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 08:58:43.244  1112  3547 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:43.244  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 08:58:43.244  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 08:58:43.244  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 08:58:43.244  1112  3547 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 08:58:43.244  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 08:58:43.244  1112  3547 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:43.244  1112  3547 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.244  1112  3547 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.244  1112  3547 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.244  1112  3547 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.244  1112  3547 W System.err: 	... 14 more
07-01 08:58:43.254  1112  3547 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.254  1112  3547 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.254  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.254  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.254  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.254  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 08:58:43.254  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 08:58:43.254  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-01 08:58:43.254  1112  3547 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 08:58:43.254  1112  3547 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:43.254  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 08:58:43.254  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 08:58:43.254  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 08:58:43.254  1112  3547 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 08:58:43.254  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 08:58:43.254  1112  3547 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:43.254  1112  3547 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.254  1112  3547 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.254  1112  3547 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.254  1112  3547 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.254  1112  3547 W System.err: 	... 14 more
07-01 08:58:43.264  1112  8471 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 08:58:43.264  1112  8471 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467356323268.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 08:58:43.264  1112  8471 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.264  1112  8471 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.264  1112  8471 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:43.264  1112  8471 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 08:58:43.264  1112  8471 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:43.264  1112  8471 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.264  1112  8471 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.264  1112  8471 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.264  1112  8471 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.264  1112  8471 E ErrorReport: 	... 4 more
07-01 08:58:43.254  5578  5704 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
07-01 08:58:43.254  5578  5704 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
07-01 08:58:43.254  5578  5704 W HTCLOG  : mask=0x18
07-01 08:58:43.254  5578  5704 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x55ba0bb8d0
07-01 08:58:43.254  5578  5704 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
07-01 08:58:43.254  5578  5704 E AndroidRuntime: Process: android.process.media, PID: 5578
07-01 08:58:43.254  5578  5704 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.254  5578  5704 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.254  1112  3601 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.254  1112  3601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.254  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.254  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.254  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.254  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 08:58:43.254  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 08:58:43.254  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 08:58:43.254  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 08:58:43.254  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 08:58:43.254  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 08:58:43.254  1112  3601 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.254  1112  3601 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.254  1112  3601 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.254  1112  3601 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.254  1112  3601 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.254  1112  3601 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.254  1112  3601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.254  1112  3601 W Sy,stem.err: 	... 12 more
07-01 08:58:43.254  1112  3707 E ActivityManager: App crashed! Process: android.process.media
07-01 08:58:43.254  1112  3707 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.254  1112  3707 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.254  1112  3707 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.254  1112  3707 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.254  1112  3707 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 08:58:43.254  1112  3707 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 08:58:43.254  1112  3707 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:43.254  1112  3707 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.254  1112  3707 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.254  1112  3707 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.254  1112  3707 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.254  1112  3707 W System.err: 	... 14 more
07-01 08:58:43.254  1112  3707 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.254  1112  3707 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.254  1112  3707 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.254  1112  3707 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.274  1112  3538 I ActivityManager: Recipient 8420
07-01 08:58:43.254  1112  3707 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.274  1112  1144 I ActivityManager: Start proc 8473:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
07-01 08:58:43.254  1112  3707 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 08:58:43.274  1112  3538 I ActivityManager: Process com.android.keychain (pid 8420) has died
07-01 08:58:43.254  1112  3707 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 08:58:43.274  1112  3538 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20829ms
07-01 08:58:43.254  1112  3707 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-01 08:58:43.274  1112  8472 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 08:58:43.274  1112  8472 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467356323271.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 08:58:43.274  1112  8472 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.274  1112  8472 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.274  1112  8472 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:43.274  1112  8472 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 08:58:43.274  1112  8472 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:43.274  1112  8472 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.274  1112  8472 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.274  1112  8472 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.274  1112  8472 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.274  1112  8472 E ErrorReport: 	... 4 more
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 08:58:43.254  1112  3707 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 08:58:43.254  1112  3707 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 08:58:43.254  1112  3707 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:43.254  1112  3707 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.264  1112  3707 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.264  1112  3707 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.264  1112  3707 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.264  1112  3707 W System.err: 	... 14 more
07-01 08:58:43.264  8447  8447 D Process : killProcess, pid=8447
07-01 08:58:43.264  8447  8447 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 08:58:43.264  8447  8447 W HTCLOG  : use specified tag [Process], func [0].
07-01 08:58:43.264  8447  8447 W HTCLOG  : mask=0x18
07-01 08:58:43.264  1112  3601 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.264  1112  3601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.264  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.264  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.264  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.264  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 08:58:43.264  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 08:58:43.264  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 08:58:43.264  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 08:58:43.264  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 08:58:43.264  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 08:58:43.264  1112  3601 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.264  1112  3601 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.264  1112  3601 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.264  1112  3601 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.264  1112  3601 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.264  1112  3601 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.264  1112  3601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.264  1112  3601 W System.err: 	... 12 more
07-01 08:58:43.274  5578  5704 D Process : killProcess, pid=5578
07-01 08:58:43.274  5578  5704 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 08:58:43.274  5578  5704 W HTCLOG  : use specified tag [Process], func [0].
07-01 08:58:43.274  5578  5704 W HTCLOG  : mask=0x18
07-01 08:58:43.274   493   493 E lowmemorykiller: Error writing /proc/5578/oom_score_adj; errno=22
07-01 08:58:43.284  8473  8473 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:43.284  8473  8473 W HTCLOG  : mask=0x18
,07-01 08:58:43.324  8473  8473 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
07-01 08:58:43.324  1112  3547 I ActivityManager: Recipient 8447
07-01 08:58:43.334  8152  8469 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 08:58:43.334  8152  8469 W HTCLOG  : mask=0x18
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:43.334  8152  8469 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:43.334  8473  8495 D PowerUtils: getUserIdOfProcess, curUserId = 0
07-01 08:58:43.334  1112  3098 I ActivityManager: Start proc 8496:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
07-01 08:58:43.334  8473  8495 D PowerUtils: isRunningUnderOwner, isOwner = true
07-01 08:58:43.334  1112  3547 I ActivityManager: Process com.android.documentsui (pid 8447) has died
07-01 08:58:43.334  8152  8469 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.334  8152  8446 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.334  8152  8446 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.344  8152  8446 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.344  8496  8496 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:43.344  8496  8496 W HTCLOG  : mask=0x18
07-01 08:58:43.344  8152  8446 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@21261546]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.344  8152  8446 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.344  8152  8152 I DeviceManagement: WorkflowService: Stopping workflow service
07-01 08:58:43.354  8473  8495 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false,
07-01 08:58:43.354  8473  8495 D PowerUsageService: removed uid = 10142
07-01 08:58:43.354  8473  8495 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
07-01 08:58:43.354  8473  8495 W HTCLOG  : mask=0x18
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.364  8473  8495 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
07-01 08:58:43.364  8473  8495 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 8473
07-01 08:58:43.364  8473  8495 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.364  8473  8495 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.364  1112  1132 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 08:58:43.364  1112  1132 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
07-01 08:58:43.364  1112  1132 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.364  1112  1132 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.364  1112  1132 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.364  1112  1132 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.364  1112  1132 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 08:58:43.364  1112  1132 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 08:58:43.364  1112  1132 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:43.364  1112  1132 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.364  1112  1132 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.364  1112  1132 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.364  1112  1132 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.364  1112  1132 W System.err: 	... 14 more
07-01 08:58:43.364  1112  1132 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.364  1112  1132 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.364  1112  8517 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 08:58:43.364  1112  8517 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467356323376.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 08:58:43.364  1112  8517 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.364  1112  8517 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.364  1112  8517 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:43.364  1112  8517 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 08:58:43.364  1112  8517 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:43.364  1112  8517 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.364  1112  8517 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.364  1112  8517 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.364  1112  8517 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.364  1112  8517 E ErrorReport: 	... 4 more
07-01 08:58:43.364  1112  1132 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.374  1112  3547 I ActivityManager: Recipient 5578
07-01 08:58:43.364  1112  1132 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.374  1112  3547 I ActivityManager: Process android.process.media (pid 5578) has died
07-01 08:58:43.364  1112  1132 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 08:58:43.374  1112  3547 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 20727ms
07-01 08:58:43.364  1112  1132 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 08:58:43.364  1112  1132 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 08:58:43.364  1112  1132 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 08:58:43.364  1112  1132 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:43.364  1112  1132 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.364  1112  1132 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.364  1112  1132 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.364  1112  1132 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.364  1112  1132 W System.err: 	... 14 more
07-01 08:58:43.364  8473  8495 D Process : killProcess, pid=8473
07-01 08:58:43.364  8473  8495 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 08:58:43.364  8473  8495 W HTCLOG  : use specified tag [Process], func [0].
07-01 08:58:43.364  8473  8495 W HTCLOG  : mask=0x18
07-01 08:58:43.374  1112  3601 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.374  1112  3601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.374  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.374  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.374  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.374  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 08:58:43.374  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
07-01 08:58:43.374  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 08:58:43.374  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 08:58:43.374  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 08:58:43.374  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 08:58:43.374  1112  3601 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.374  1112  3601 W System.err: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.374  1112  3601 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.374  1112  3601 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.374  1112  3601 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.374  1112  3601 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.374  1112  3601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.374  1112  3601 W System.err: 	... 12 more
07-01 08:58:43.384  3334  3753 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
07-01 08:58:43.384  3213  3213 I NotificationStackScrollLayout: setBlockTouchEnabled:false
,07-01 08:58:43.404  8496  8518 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,07-01 08:58:43.404  8496  8518 W HTCLOG  : mask=0x18
,07-01 08:58:43.414  8496  8518 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
,07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
,07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.414  8496  8518 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
07-01 08:58:43.414  8496  8518 E AndroidRuntime: Process: com.htc.updater, PID: 8496
07-01 08:58:43.414  8496  8518 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
,07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: ,	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at com.htc.updater.download.DownloadProvider.delete(DownloadProvider.java:1380)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:148)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver.access$000(DownloadReceiver.java:50)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at com.htc.updater.download.DownloadReceiver$1.run(DownloadReceiver.java:109)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
,07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.414  8496  8518 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-01 08:58:43.414  1112  3547 E ActivityManager: App crashed! Process: com.htc.updater
07-01 08:58:43.414  1112  3547 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
07-01 08:58:43.414  1112  3547 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.414  1112  3547 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.414  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.414  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,07-01 08:58:43.414  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
,07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 08:58:43.414  1112  3547 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
,07-01 08:58:43.414  1112  3547 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:43.414  1112  3547 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.414  1112  3547 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.414  1112  3547 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.414  1112  3547 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.414  1112  3547 W System.err: 	... 14 more
07-01 08:58:43.414  1112  3547 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.414  1112  3547 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.414  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.424  1112  8521 E ErrorReport: HtcErrorReportManager.Error in dumping error information
07-01 08:58:43.424  1112  8521 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467356323428.dbox_tmp: open failed: EROFS (Read-only file system)
07-01 08:58:43.424  1112  8521 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.424  1112  8521 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.424  1112  8521 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:43.424  1112  8521 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
07-01 08:58:43.424  1112  8521 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:43.424  1112  8521 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.424  1112  8521 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.424  1112  8521 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.424  1112  8521 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.424  1112  8521 E ErrorReport: 	... 4 more
07-01 08:58:43.414  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.414  1112  3547 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
07-01 08:58:43.414  1112  3547 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413),
07-01 08:58:43.414  1112  3547 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
07-01 08:58:43.414  1112  3547 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
07-01 08:58:43.414  1112  3547 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.414  1112  3547 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.414  1112  3547 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.414  1112  3547 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.414  1112  3547 W System.err: 	... 14 more
07-01 08:58:43.424  8496  8496 V UpdaterAPK | DownloadService: Service onStart
07-01 08:58:43.424  8496  8519 V UpdaterAPK | DownloadService: Updating for startId 1
07-01 08:58:43.424  1112  3601 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
07-01 08:58:43.424  1112  3601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
,07-01 08:58:43.424  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.424  3889  3889 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
07-01 08:58:43.424  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
07-01 08:58:43.424  1112  3601 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
07-01 08:58:43.424  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
07-01 08:58:43.424  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
,07-01 08:58:43.424  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
07-01 08:58:43.424  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
07-01 08:58:43.424  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
07-01 08:58:43.424  1112  3601 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
07-01 08:58:43.424  1112  3601 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.424  1112  3601 W System.err: 	at android.os.Looper.loop(Looper.java:155)
,07-01 08:58:43.424  1112  3601 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.424  1112  3601 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.424  1112  3601 W System.err: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.424  1112  3601 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.424  1112  3601 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.424  1112  3601 W System.err: 	... 12 more
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: Failed to open database '/data/data/com.htc.updater/databases/downloads.db'.
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: ,	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:98)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.424  8496  8519 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.424  8496  8518 D Process : killProcess, pid=8496
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: Couldn't open downloads.db for writing (will try read-only):
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadProvider.query(DownloadProvider.java:1001)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.content.Conte,ntProvider.query(ContentProvider.java:976)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.updateLocked(DownloadService.java:380)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService.access$200(DownloadService.java:79)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at com.htc.updater.download.DownloadService$2.handleMessage(DownloadService.java:313)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:98)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.424  8496  8519 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-01 08:58:43.424  8496  8518 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
07-01 08:58:43.424  8496  8518 W HTCLOG  : use specified tag [Process], func [0].
07-01 08:58:43.424  8496  8518 W HTCLOG  : mask=0x18
07-01 08:58:43.434  1112  3537 I ActivityManager: Start proc 8522:com.google.android.gms/u0a19 for broadcast com.google.android.gms/.subscribedfeeds.ConfigurationReceiver
,07-01 08:58:43.444  8522  8522 W HTCLOG  : use specified tag [FDManager], func [0].
07-01 08:58:43.444  8522  8522 W HTCLOG  : mask=0x18
,07-01 08:58:43.444  1112  1131 I ActivityManager: Recipient 8473
,07-01 08:58:43.444  1112  1131 I ActivityManager: Process com.htc.htcpowermanager:remote (pid 8473) has died
07-01 08:58:43.444  1112  1131 W ActivityManager: Scheduling restart of crashed service com.htc.htcpowermanager/.battery.PowerUsageService in 30658ms
,07-01 08:58:43.474  8522  8522 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
07-01 08:58:43.474  8522  8522 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-01 08:58:43.494  8522  8522 I MultiDex: VM with version 2.1.0 has multidex support
07-01 08:58:43.494  8522  8522 I MultiDex: install
07-01 08:58:43.494  8522  8522 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,07-01 08:58:43.504  1112  1131 I ActivityManager: Recipient 8496
07-01 08:58:43.504  1112  1131 I ActivityManager: Process com.htc.updater (pid 8496) has died
07-01 08:58:43.504  1112  1131 W ActivityManager: Scheduling restart of crashed service com.htc.updater/.download.DownloadService in 40601ms
,07-01 08:58:43.564  8522  8522 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,07-01 08:58:43.634  8522  8546 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,07-01 08:58:43.634  8522  8546 W HTCLOG  : mask=0x18
,07-01 08:58:43.634  8522  8546 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/reminders.db'.,
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
,07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286),
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at c,om.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:225)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:499)
,07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.a.a(SourceFile:62)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:37)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
,07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
,07-01 08:58:43.634  8522  8546 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: Couldn't open reminders.db for writing (will try read-only):
,07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
,07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: ,	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.provider.RemindersProvider.query(SourceFile:225)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.content.ContentProvider.query(ContentProvider.java:976)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:499)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.content.ContentResolver.query(ContentResolver.java:443)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.a.a(SourceFile:62)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at com.google.android.gms.reminders.a.c.doInBackground(SourceFile:37)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.os.AsyncTask$2.call(AsyncTask.java:292),
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:43.644  8522  8546 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:43.644  8522  8546 W SQLiteOpenHelper: Opened reminders.db in read-only mode
,07-01 08:58:43.654  8522  8548 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/plus.db'.,
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874),
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:43.654  8522  8548 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: FATAL EXCEPTION: AsyncTask #2
07-01 08:58:43.654  8522  8548 E AndroidRuntime: Process: com.google.android.gms, PID: 8522
07-01 08:58:43.654  8522  8548 E AndroidRuntime: java.lang.RuntimeException: An error occured while executing doInBackground()
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.os.AsyncTask$3.done(AsyncTask.java:304)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at java.util.concurrent.FutureTask.finishCompletion(FutureTask.java:355)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at java.util.concurrent.FutureTask.setException(FutureTask.java:222)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:242)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at com.google.android.gms.plus.provider.PlusProvider.a(SourceFile:329)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.a(SourceFile:146)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at com.google.android.gms.plus.provider.b.doInBackground(SourceFile:143)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at android.os.AsyncTask$2.call(AsyncTask.java:292)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-01 08:58:43.654  8522  8548 E AndroidRuntime: 	... 4 more
07-01 08:58:43.654  1112  3538 E ActivityManager: App crashed! Process: com.google.android.gms
07-01 08:58:43.654  1112  3538 W ActivityManager: Process com.google.android.gms has crashed too many times: killing!
07-01 08:58:43.654  1112  3538 D Process : killProcessQuiet, pid=8522
07-01 08:58:43.654  1112  3538 I ActivityManager: Killing 8522:com.google.android.gms/u0a19 (adj 0): crash
07-01 08:58:43.654  1112  3538 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.handleAppCrashLocked:12158 
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: Can't write: system_app_crash
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.654  1112  8550 E DropBoxManagerService: 	... 5 more
,07-01 08:58:43.734  1112  3503 I ActivityManager: Recipient 8522
,07-01 08:58:43.764  1112  3503 W ActivityManager: Spurious death for ProcessRecord{5493d7b 8522:com.google.android.gms/u0a19}, curProc for 8522: null,
07-01 08:58:43.774  3889  3889 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,07-01 08:58:43.774  3889  3889 D c       : Getting all permits...
07-01 08:58:43.774  3889  3889 D a       : Opening database...
,07-01 08:58:43.784  3889  3889 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/auth.proximity.permit_store'.,
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.b.a.a(SourceFile:52)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.b.c.a(SourceFile:185)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.authorization.bt.b.a(SourceFile:217)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at com.google.android.gms.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter.onReceive(SourceFile:239)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 08:58:43.784  3889  3889 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 08:58:43.794  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
07-01 08:58:43.784  3889  3889 E AndroidRuntime: FATAL EXCEPTION: main
07-01 08:58:43.784  3889  3889 E AndroidRuntime: Process: com.google.process.gapps, PID: 3889
07-01 08:58:43.784  3889  3889 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.auth.be.proximity.authorization.bt.Au,thorizationBluetoothService$AutoStarter: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.b.a.a(SourceFile:52)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.b.c.a(SourceFile:185)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.authorization.bt.b.a(SourceFile:217)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at com.google.android.gms.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter.onReceive(SourceFile:239)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
07-01 08:58:43.784  3889  3889 E AndroidRuntime: 	... 9 more
07-01 08:58:43.794  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms },: process is bad
07-01 08:58:43.784  1112  3523 E ActivityManager: App crashed! Process: com.google.process.gapps
07-01 08:58:43.794  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
07-01 08:58:43.794  3545  3934 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
07-01 08:58:43.794  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
07-01 08:58:43.794  3545  3934 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@2748d103 +
07-01 08:58:43.794  3545  3934 I Prism.WidgetManager: onLoadItems() +
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: Can't write: system_app_crash
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-01 08:58:43.814  1112  8551 E DropBoxManagerService: 	... 5 more
07-01 08:58:43.844  3545  3934 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
07-01 08:58:43.854  3889  3889 D Process : killProcess, pid=3889
07-01 08:58:43.854  3889  3889 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
07-01 08:58:43.854  3889  3889 W HTCLOG  : use specified tag [Process], func [0].
07-01 08:58:43.854  3889  3889 W HTCLOG  : mask=0x18
,07-01 08:58:43.954  1112  3538 I ActivityManager: Recipient 3889
07-01 08:58:43.954  1112  3538 I ActivityManager: Process com.google.process.gapps (pid 3889) has died
07-01 08:58:43.954  1112  3538 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 50149ms
07-01 08:58:43.954  1112  3538 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 60149ms
,07-01 08:58:43.954  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
07-01 08:58:43.954  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
07-01 08:58:43.954  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
07-01 08:58:43.954  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
07-01 08:58:43.954  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
07-01 08:58:43.954  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
07-01 08:58:43.954  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad
,07-01 08:58:43.954  1112  1144 W BroadcastQueue: Unable to launch app com.google.android.gms/10019 for broadcast Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms }: process is bad

```
