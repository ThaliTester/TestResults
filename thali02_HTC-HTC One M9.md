#### Test 7578926851a8f91_thali02_HTC-HTC One M9 Logs


```
--------- beginning of main
06-30 12:51:47.874  6440  8111 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
--------- beginning of system
06-30 12:51:47.884  1109  3555 I ActivityManager: Start proc 8112:com.htc.cs.dm/u0a89 for broadcast com.htc.cs.dm/.receiver.PackageUpdateReceiver
06-30 12:51:47.894  8112  8112 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 12:51:47.894  8112  8112 W HTCLOG  : mask=0x18
06-30 12:51:47.894  6440  8111 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 12:51:47.894  6440  8111 W HTCLOG  : mask=0x18
06-30 12:51:47.954  8001  8001 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
06-30 12:51:47.954  8053  8076 I CAR.SERVICE: listener not found in list
06-30 12:51:47.954  8112  8112 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8112 dbg=false s=true
06-30 12:51:47.954  8112  8112 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
06-30 12:51:47.964  1109  3909 D Process : killProcessQuiet, pid=7684
06-30 12:51:47.964  1109  3909 I ActivityManager: Start proc 8137:com.google.android.apps.docs/u0a91 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
06-30 12:51:47.964  1109  3909 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
06-30 12:51:47.964  1109  3909 I ActivityManager: Killing 7684:com.google.android.talk/u0a103 (adj 15): empty #17
,06-30 12:51:47.984  8137  8137 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 12:51:47.984  8137  8137 W HTCLOG  : mask=0x18
06-30 12:51:47.984   561   561 I art     : Explicit concurrent mark sweep GC freed 8654(368KB) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 213us total 16.978ms
06-30 12:51:47.994   561   561 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 183us total 14.349ms
06-30 12:51:48.014   561   561 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 97% free, 113KB/4MB, paused 187us total 15.291ms
06-30 12:51:48.024  1109  3505 I ActivityManager: Recipient 7684
06-30 12:51:48.104  1109  3909 D PMS     : acquireWL(2d7fb6d8): PARTIAL_WAKE_LOCK  Icing 0x1 3425 10019 null
06-30 12:51:48.144  1109  3555 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 12:51:48.144  8158  8158 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
06-30 12:51:48.144  8158  8158 W HTCLOG  : mask=0x18
06-30 12:51:48.144  1109  5182 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 12:51:48.144  6440  8111 I ApplicationLogger: canRun() : Opted Out
06-30 12:51:48.144  6440  8111 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 268 ms] updated apps [took 268 ms] 
06-30 12:51:48.174  8137  8137 D DocsApplication: Plugin installer initialized.
06-30 12:51:48.174  1109  3557 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 12:51:48.194  8137  8137 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{3e4f2f81 com.google.android.apps.docs}
06-30 12:51:48.204  8137  8137 D TAG     : onCreate()
06-30 12:51:48.214  8137  8137 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
06-30 12:51:48.224  1109  1132 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
06-30 12:51:48.304  8158  8163 W HTCLOG  : use specified tag [cutils-trace], func [0].
06-30 12:51:48.304  8158  8163 W HTCLOG  : mask=0x18
06-30 12:51:48.304  8158  8163 E cutils-trace: Error opening trace file: Permission denied (13)
06-30 12:51:48.354  3532  3899 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
06-30 12:51:48.354  3532  3899 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23543042 +
06-30 12:51:48.354  3532  3899 I Prism.WidgetManager: onLoadItems() +
06-30 12:51:48.354  8158  8158 D CustomizationManager: ====startRecUseTime====
06-30 12:51:48.354  8158  8158 D htc.customization.log.level:  is 
06-30 12:51:48.354  8158  8158 W CustomizationLogLevel: Level value is invalid, use default level 2
06-30 12:51:48.374  3532  3899 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
06-30 12:51:48.444  8158  8158 D CustomizationManager:  Read ACC file spent 0.037 (s)
06-30 12:51:48.444  8158  8158 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
06-30 12:51:48.444  8158  8158 I CustomizationCIDLoader: Parsing tag category name = application
06-30 12:51:48.444  8158  8158 I CustomizationCIDLoader: Parsing tag category name = system
06-30 12:51:48.444  8158  8158 I CustomizationCIDLoader: Parsing tag category name = Settings
06-30 12:51:48.444  8158  8158 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
06-30 12:51:48.444  8158  8158 I CustomizationCIDLoader: Parsing tag category name = ACC
06-30 12:51:48.444  8158  8158 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
06-30 12:51:48.444  8158  8158 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
06-30 12:51:48.444  8158  8158 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
06-30 12:51:48.444  8158  8158 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-30 12:51:48.444  8158  8158 I CustomizationCIDLoader: Parsing tag category name = AudioService
06-30 12:51:48.444  8158  8158 D CustomizationManager:  Read CID file spent 0.089 (s)
06-30 12:51:48.444  8158  8158 D CustomizationManager:  All configurations done spent 0.089 (s)
06-30 12:51:48.484  1109  3524 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8158 on display 0
06-30 12:51:48.494  1109  3524 V WindowManager: addAppToken: AppWindowToken{2d2bfd33 token=Token{141b5ca2 ActivityRecord{165de86d u0 com.test.thalitest/.MainActivity t43}}} to stack=1 task=43 at 0
06-30 12:51:48.494  1109  1179 D PMS     : acquireHCC(2b5288f0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1109 1000 null
06-30 12:51:48.504  1109  1179 D PMS     : acquireHCC(317d9e69): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1109 1000 null
06-30 12:51:48.504  1109  3524 I ActivityManager: Start proc 8177:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
06-30 12:51:48.504  8158  8158 W HTCLOG  : use specified tag [IPCThreadState], func [0].
06-30 12:51:48.504  8158  8158 W HTCLOG  : mask=0x18
06-30 12:51:48.514  8158  8176 W HTCLOG  : use specified tag [Vector], func [0].
06-30 12:51:48.514  8158  8175 W HTCLOG  : use specified tag [Vector], func [0].
06-30 12:51:48.514  8158  8175 W HTCLOG  : mask=0x18
06-30 12:51:48.514  8158  8176 W HTCLOG  : mask=0x18
06-30 12:51:48.524  8177  8177 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 12:51:48.524  8177  8177 W HTCLOG  : mask=0x18
06-30 12:51:48.544  3323  3323 D DotMatrix: [EventService]  onDisplayChanged: 0
06-30 12:51:48.544  1109  1109 V ActivityManager: Display changed displayId=0
06-30 12:51:48.544  3323  3323 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
06-30 12:51:48.554  1109  5182 D ActivityManager: screenshot for ActivityRecord{165de86d u0 com.test.thalitest/.MainActivity t43}, bitmap=null, time = 0
06-30 12:51:48.574  3510  4183 D PhoneApp: EVENT_QUERY_MO_PACKAGES
06-30 12:51:48.574  3510  4183 D PhoneApp: -- N1 =0
06-30 12:51:48.574  3510  4183 D PhoneApp: -- N2 =0
06-30 12:51:48.574  3510  4183 D PhoneApp: -- N3 =0
06-30 12:51:48.574  3532  3532 I TrimMemoryManager: [trimMemory] 20
06-30 12:51:48.584  3532  3899 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 12:51:48.614  8177  8177 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
06-30 12:51:48.694  8177  8177 I LibraryLoader: Time to load native libraries: 33 ms (timestamps 3059-3092)
06-30 12:51:48.694  8177  8177 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:51:48.704  8177  8177 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d3e42bd}
06-30 12:51:48.704  8177  8177 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:51:48.704  8177  8177 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,06-30 12:51:48.714  8177  8177 I BrowserStartupController: Initializing chromium process, singleProcess=true
,06-30 12:51:48.714  8177  8177 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,06-30 12:51:48.724  8177  8177 E SysUtils: ApplicationContext is null in ApplicationStatus
,06-30 12:51:48.754  8177  8200 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
,06-30 12:51:48.754  3532  3899 I Prism.WidgetManager: onLoadItems() -
06-30 12:51:48.754  3532  3899 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23543042 -
,06-30 12:51:48.764  8177  8204 D BluetoothAdapter: 923152562: getState() :  mService = null. Returning STATE_OFF
,06-30 12:51:48.764  8177  8177 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,06-30 12:51:48.764  8177  8177 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
06-30 12:51:48.764  8177  8177 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
,06-30 12:51:48.774  8177  8177 W HTCLOG  : use specified tag [libEGL], func [3].
,06-30 12:51:48.774  8177  8177 W HTCLOG  : mask=0x18
06-30 12:51:48.774  8177  8177 W HTCLOG  : use specified tag [libEGL], func [3].
06-30 12:51:48.774  8177  8177 W HTCLOG  : mask=0x18
06-30 12:51:48.774  8177  8177 I Adreno  : QUALCOMM build                   : 065751b, 
06-30 12:51:48.774  8177  8177 I Adreno  : Build Date                       : 04/15/15
06-30 12:51:48.774  8177  8177 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
06-30 12:51:48.774  8177  8177 I Adreno  : Local Branch                     : 
06-30 12:51:48.774  8177  8177 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
06-30 12:51:48.774  8177  8177 I Adreno  : Remote Branch                    : NONE
06-30 12:51:48.774  8177  8177 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,06-30 12:51:48.854  8177  8210 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
,06-30 12:51:48.874  8177  8177 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:48.884  8177  8177 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 12:51:48.894  8177  8177 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
06-30 12:51:48.894  8177  8177 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:48.894  8177  8177 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:51:48.934  8177  8221 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 12:51:48.934  8177  8221 W HTCLOG  : mask=0x18
06-30 12:51:48.934  1109  3524 V WindowManager: Adding window Window{1c994511 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{35185075 u0 com.htc.launcher/com.htc.launcher.Launcher})
06-30 12:51:48.934  1109  3602 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
06-30 12:51:48.964  8177  8177 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
06-30 12:51:48.964  8177  8177 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
06-30 12:51:48.964  8177  8177 W HTCLOG  : mask=0x18
06-30 12:51:48.964  8177  8177 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 12:51:48.964  8177  8177 W HTCLOG  : mask=0x18
06-30 12:51:48.974  8177  8221 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 12:51:48.974  8177  8221 W HTCLOG  : mask=0x18
06-30 12:51:48.974  8177  8221 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 12:51:48.974  8177  8221 W HTCLOG  : mask=0x18
06-30 12:51:48.974  8177  8221 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 12:51:48.974  8177  8221 W HTCLOG  : mask=0x18
06-30 12:51:48.974  8177  8221 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
06-30 12:51:48.974  8177  8221 W HTCLOG  : mask=0x18
06-30 12:51:48.984  8177  8221 W HTCLOG  : use specified tag [Surface], func [3].
06-30 12:51:48.984  8177  8221 W HTCLOG  : mask=0x18
06-30 12:51:48.984  8177  8221 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
06-30 12:51:48.984  8177  8221 W HTCLOG  : mask=0x18
06-30 12:51:48.984  8177  8221 W HTCLOG  : use specified tag [qdmemalloc], func [0].
06-30 12:51:48.984  8177  8221 W HTCLOG  : mask=0x18
06-30 12:51:49.044  1109  1170 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +488ms (total +545ms)
06-30 12:51:49.064  8137  8227 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 12:51:49.064  8137  8227 W HTCLOG  : mask=0x18
06-30 12:51:49.084  8177  8177 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8177
06-30 12:51:49.104  1109  3548 I ActivityManager: Start proc 8232:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
06-30 12:51:49.104  1109  3548 I ActivityManager: Killing 7742:com.htc.calendar/u0a6 (adj 15): empty #17
06-30 12:51:49.104  1109  3548 D Process : killProcessQuiet, pid=7742
06-30 12:51:49.104  1109  3548 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
06-30 12:51:49.114  8232  8232 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 12:51:49.114  8232  8232 W HTCLOG  : mask=0x18
06-30 12:51:49.144  3425  6659 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
06-30 12:51:49.164  8177  8177 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 12:51:49.204  8177  8226 D jxcore_app_log: JniHelper::setJavaVM(0xab77bb70), pthread_self() = -1402259072
06-30 12:51:49.204  8177  8226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:51:49.204  8177  8226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:51:49.204  8177  8226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:51:49.204  8177  8226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:51:49.204  8177  8226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:51:49.204  8177  8226 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12341c99 added. We now have 1 listener(s)
06-30 12:51:49.274  1109  3505 I ActivityManager: Recipient 7742
06-30 12:51:49.324  1109  5212 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-30 12:51:49.334  8137  8137 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
06-30 12:51:49.334  1109  3032 D PMS     : acquireWL(2a592d05): PARTIAL_WAKE_LOCK  *alarm* 0x1 1109 1000 WorkSource{10027}
06-30 12:51:49.334  1109  3032 V AlarmManager: sending alarm PendingIntent{a8de15a: PendingIntentRecord{3b4860cb com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=73392, Int=0
06-30 12:51:49.334  8177  8226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
06-30 12:51:49.334  8177  8226 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
06-30 12:51:49.334  8177  8226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 12:51:49.334  8177  8226 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 12:51:49.344  8177  8226 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@191bc0c added. We now have 1 listener(s)
06-30 12:51:49.344  8177  8226 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 12:51:49.344  8177  8226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:51:49.344  8232  8232 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 12:51:49.344  8177  8226 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
06-30 12:51:49.344  1109  3077 D WifiService: New client listening to asynchronous messages
06-30 12:51:49.344  8177  8226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 12:51:49.344  8177  8226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
06-30 12:51:49.344  8177  8226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 12:51:49.344  8177  8226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
06-30 12:51:49.344  8177  8226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
06-30 12:51:49.344  1109  3557 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
06-30 12:51:49.344  8177  8226 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
06-30 12:51:49.354  8177  8226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 12:51:49.354  8177  8226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:51:49.354  8177  8226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:51:49.354  8177  8226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 12:51:49.354  8177  8226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 12:51:49.354  8177  8226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 12:51:49.354  8177  8226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:51:49.354  8177  8226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:51:49.354  8177  8226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 12:51:49.354  8177  8226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 12:51:49.354  8177  8226 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 12:51:49.354  8177  8226 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 12:51:49.364  3425  6659 D Icing   : Loaded CLD2 Version V2.0 - 20140131
06-30 12:51:49.394  8177  8177 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
06-30 12:51:49.484  1109  1179 D PMS     : releaseHCC(2b5288f0): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
06-30 12:51:49.484  1109  1179 D PMS     : releaseHCC(317d9e69): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
06-30 12:51:49.544  3425  6659 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
06-30 12:51:49.544  1109  5182 D PMS     : releaseWL(2d7fb6d8): PARTIAL_WAKE_LOCK  Icing 0x1 null
06-30 12:51:49.604  1109  3505 D PMS     : acquireWL(116741b2): PARTIAL_WAKE_LOCK  AsyncService 0x1 8232 10128 null
06-30 12:51:49.614  1109  3909 D PMS     : releaseWL(116741b2): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
06-30 12:51:49.664  3904  3904 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
06-30 12:51:49.674  3904  3904 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
06-30 12:51:49.674  3904  3904 D c       : Getting all permits...
06-30 12:51:49.674  3904  3904 D a       : Opening database...
06-30 12:51:49.674  3904  3904 D a       : Opening database auth.proximity.permit_store...
06-30 12:51:49.674  3904  3904 D a       : Closing database...
06-30 12:51:49.684  3425  3425 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,06-30 12:51:49.694  7503  7503 D AlarmReceiver: ACTION_RESTART_INTENT,
,06-30 12:51:49.704  1109  1109 D PMS     : releaseWL(2a592d05): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
,06-30 12:51:49.704  7503  7503 D LocalBluetoothProfile: getPriorityOnValue = 100
06-30 12:51:49.704  7503  7503 D LocalBluetoothProfile: getPriorityOffValue = 0
06-30 12:51:49.704  7503  7503 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
06-30 12:51:49.704  7503  7503 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,06-30 12:51:49.704  3425  8269 D LocationInitializer: Restart initialization of location,
,06-30 12:51:49.744  7503  8271 D HtcModeClient: start the htcmodeservice thread
,06-30 12:51:49.744  7503  8271 D HtcModeClient: initCanAgent
06-30 12:51:49.744  7503  8271 I CANMesgAgentLocalSocket: CANAgent Id = 0
,06-30 12:51:49.744  7503  8271 D HtcModeClient: sense info: version = none, id = 2,
,06-30 12:51:49.744  7503  8271 D HtcModeClient: display info: width = 1080, height = 1776
06-30 12:51:49.744  7503  8271 D HtcModeClient: display info: mode = 10,
,06-30 12:51:49.844  8177  8262 W jxcore-log: Initializing JXcore engine,
06-30 12:51:49.844  8177  8262 W jxcore-log: JXcore engine is ready
06-30 12:51:49.844  7503  7503 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,06-30 12:51:49.844  7503  7503 D HtcModeClient: connectState: BT_TURNON_BYME = false
06-30 12:51:49.844  7503  7503 D HtcModeClient: connectState: CONNECTION_READY = false
06-30 12:51:49.844  7503  7503 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
06-30 12:51:49.844  7503  7503 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
06-30 12:51:49.844  7503  7503 D HtcModeClient: connectState: PHONE_PULGIN = false
06-30 12:51:49.844  7503  7503 D HtcModeClient: connectState: Force_AWAKE = false
06-30 12:51:49.844  7503  7503 D HtcModeClient: connectState: PHONE_PULGIN = true
06-30 12:51:49.844  7503  7503 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,06-30 12:51:49.894  8177  8262 W jxcore-log: Starting JXcore engine,
,06-30 12:51:49.994  8177  8262 W jxcore-log: Platform android,
06-30 12:51:49.994  8177  8262 W jxcore-log: 
06-30 12:51:49.994  8177  8262 W jxcore-log: Process ARCH arm
06-30 12:51:49.994  8177  8262 W jxcore-log: 
,06-30 12:51:50.174  8177  8262 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:51:50.174  8177  8262 I jxcore-log: 
,06-30 12:51:50.174  8177  8262 W jxcore-log: JXcore engine is started
,06-30 12:51:50.184  8177  8226 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
06-30 12:51:50.194  8177  8177 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 12:51:50.204  8177  8262 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
06-30 12:51:50.204  8177  8262 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-30 12:51:50.204  8177  8177 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57),
06-30 12:51:50.204  8177  8177 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-30 12:51:50.214  8177  8177 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
06-30 12:51:50.224  8177  8177 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
06-30 12:51:50.224  8177  8177 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-30 12:51:50.224  8177  8177 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,06-30 12:51:50.224  8177  8177 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
06-30 12:51:50.224  8177  8177 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-30 12:51:50.224  8177  8177 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12341c99 removed from the list
06-30 12:51:50.224  8177  8177 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 12:51:50.224  8177  8177 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@191bc0c removed from the list
06-30 12:51:50.224  8177  8177 D io.jxcore.node.ConnectivityMonitor: stop
06-30 12:51:50.224  8177  8177 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
06-30 12:51:50.224  8177  8177 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-30 12:51:50.384  8274  8274 W HTCLOG  : use specified tag [AndroidRuntime], func [0].,
06-30 12:51:50.384  8274  8274 W HTCLOG  : mask=0x18
,06-30 12:51:50.594  8274  8279 W HTCLOG  : use specified tag [cutils-trace], func [0].,
06-30 12:51:50.594  8274  8279 W HTCLOG  : mask=0x18
06-30 12:51:50.594  8274  8279 E cutils-trace: Error opening trace file: Permission denied (13)
,06-30 12:51:50.654  8274  8274 D CustomizationManager: ====startRecUseTime====,
06-30 12:51:50.654  8274  8274 D htc.customization.log.level:  is 
06-30 12:51:50.654  8274  8274 W CustomizationLogLevel: Level value is invalid, use default level 2
,06-30 12:51:50.734  8274  8274 D CustomizationManager:  Read ACC file spent 0.038 (s)
06-30 12:51:50.734  8274  8274 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
06-30 12:51:50.744  8274  8274 I CustomizationCIDLoader: Parsing tag category name = application
06-30 12:51:50.744  8274  8274 I CustomizationCIDLoader: Parsing tag category name = system
,06-30 12:51:50.744  8274  8274 I CustomizationCIDLoader: Parsing tag category name = Settings
06-30 12:51:50.744  8274  8274 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome,
06-30 12:51:50.744  8274  8274 I CustomizationCIDLoader: Parsing tag category name = ACC
,06-30 12:51:50.744  8274  8274 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
06-30 12:51:50.744  8274  8274 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
06-30 12:51:50.744  8274  8274 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
06-30 12:51:50.744  8274  8274 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
06-30 12:51:50.744  8274  8274 I CustomizationCIDLoader: Parsing tag category name = AudioService
,06-30 12:51:50.744  8274  8274 D CustomizationManager:  Read CID file spent 0.089 (s),
06-30 12:51:50.744  8274  8274 D CustomizationManager:  All configurations done spent 0.089 (s)
,06-30 12:51:50.794  1109  3524 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8274, uid=2000,
,06-30 12:51:50.794  1109  1144 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
06-30 12:51:50.804  1109  1144 D Process : killProcessQuiet, pid=8177
06-30 12:51:50.804  1109  1144 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
06-30 12:51:50.804  1109  1144 I ActivityManager: Killing 8177:com.test.thalitest/u0a142 (adj 9): stop com.test.thalitest
,06-30 12:51:50.884  1109  3557 I ActivityManager: Recipient 8177
,06-30 12:51:50.884  1109  3077 D WifiService: Client connection lost with reason: 4
,06-30 12:51:50.894   522   522 W HTCLOG  : use specified tag [Vector], func [0].,
06-30 12:51:50.894   522   522 W HTCLOG  : mask=0x18
,06-30 12:51:50.914  1109  3557 W ActivityManager: Spurious death for ProcessRecord{38b3fb98 8177:com.test.thalitest/u0a142}, curProc for 8177: null,
06-30 12:51:50.914  1109  1184 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed
,06-30 12:51:50.934  3323  3323 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
06-30 12:51:50.944  1109  3074 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
06-30 12:51:50.934  3323  3323 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false,
06-30 12:51:50.944  1109  3073 D PMS     : acquireWL(2ada9ff1): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1109 1000 null
06-30 12:51:50.944  4332  4632 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.,
06-30 12:51:50.944  1109  1131 D PMS     : acquireWL(137b7d6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4332 10019 null
,06-30 12:51:50.954  3661  4089 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
06-30 12:51:50.954  1109  3035 W SystemReader: Cannot find grip_rejection_width, use default value instead
06-30 12:51:50.954  1109  3555 D PMS     : releaseWL(137b7d6): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
06-30 12:51:50.964  3661  4089 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
06-30 12:51:50.964  3425  3425 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,06-30 12:51:50.974  6440  6440 I art     : Explicit concurrent mark sweep GC freed 12291(759KB) AllocSpace objects, 2(40KB) LOS objects, 34% free, 3MB/5MB, paused 504us total 57.161ms
06-30 12:51:50.974  1109  3525 D PMS     : acquireWL(3c2debae): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 3425 10019 null
,06-30 12:51:50.974  3749  8294 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,06-30 12:51:50.984  1109  3073 D PMS     : releaseWL(2ada9ff1): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
06-30 12:51:50.984  1109  3074 V NetworkPolicy: writePolicyLocked()
06-30 12:51:50.984  1109  1143 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,06-30 12:51:51.004  3661  4089 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
06-30 12:51:51.004  3904  3904 I ConfigService: onCreate
06-30 12:51:51.004  3904  3904 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,06-30 12:51:51.004  3425  3425 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) },
06-30 12:51:51.014  3661  4089 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
06-30 12:51:51.014  3510  3510 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
,06-30 12:51:51.014  1109  3074 D NetworkPolicy: notifyPoliciesChangeLocked: no change
06-30 12:51:51.014  1109  3074 V NetworkPolicy: updateNetworkEnabledLocked()
06-30 12:51:51.014  1109  3074 V NetworkPolicy: updateNotificationsLocked()
,06-30 12:51:51.024  1109  1109 W PackageManager: Unable to load service info ResolveInfo{39f7297d com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
06-30 12:51:51.024  1109  1109 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
06-30 12:51:51.024  1109  1109 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 12:51:51.024  1109  1109 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,06-30 12:51:51.034  3904  3904 I ConfigService: onBind returning update interface
06-30 12:51:51.034  3904  3904 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
,06-30 12:51:51.034  3904  3904 I ConfigService: onBind returning config service
,06-30 12:51:51.044  3661  4089 E ExternalAccountType: Unsupported attribute readOnly
,06-30 12:51:51.044  1109  1109 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,06-30 12:51:51.054  1109  5182 I ActivityManager: Start proc 8296:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver,
06-30 12:51:51.054  8296  8296 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 12:51:51.054  1109  3496 D PMS     : acquireWL(470559c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3904 10019 null
06-30 12:51:51.054  8296  8296 W HTCLOG  : mask=0x18
,06-30 12:51:51.064  3532  3899 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
06-30 12:51:51.064  3532  3899 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
06-30 12:51:51.064  3532  3532 I Launcher: Deferring update until onResume
06-30 12:51:51.064  3532  3532 D Launcher: waitUntilResume // bindAppsRemoved
06-30 12:51:51.064  1109  3557 D PMS     : releaseWL(470559c): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
06-30 12:51:51.074  3904  3904 I ConfigService: onDestroy
,06-30 12:51:51.084  8296  8296 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
06-30 12:51:51.084  8296  8296 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,06-30 12:51:51.104  3532  3532 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true,
06-30 12:51:51.104  3532  3532 I ThreadedRenderer: Defer allocateBuffers to drawing time
,06-30 12:51:51.104  8296  8296 I MultiDex: VM with version 2.1.0 has multidex support,
06-30 12:51:51.104  8296  8296 I MultiDex: install
06-30 12:51:51.104  8296  8296 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,06-30 12:51:51.114  8296  8296 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application',
,06-30 12:51:51.124  8296  8296 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,06-30 12:51:51.134  1109  1184 I art     : Explicit concurrent mark sweep GC freed 34340(2MB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 15MB/23MB, paused 2.027ms total 202.727ms
06-30 12:51:51.144  1109  5612 I art     : WaitForGcToComplete blocked for 158.029ms for cause Explicit,
06-30 12:51:51.154  1109  3505 I ActivityManager: Start proc 8322:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver,
06-30 12:51:51.154  8274  8274 I art     : System.exit called, status: 0
06-30 12:51:51.154  8274  8274 W HTCLOG  : use specified tag [Vector], func [0].
06-30 12:51:51.154  8274  8274 W HTCLOG  : mask=0x18
,06-30 12:51:51.164  8322  8322 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 12:51:51.164  8322  8322 W HTCLOG  : mask=0x18
06-30 12:51:51.174  3425  8321 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
06-30 12:51:51.174  3425  8321 D AccountUtils: Clearing selected account for com.test.thalitest
,06-30 12:51:51.194  3471  3471 D Nfc-Utils: isNxpCodebase: isNxp=false
,06-30 12:51:51.204  7778  8348 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,06-30 12:51:51.214  1109  3525 I ActivityManager: Delay finish: com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver,
06-30 12:51:51.224  1109  3525 I ActivityManager: Killing 7354:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
06-30 12:51:51.224  1109  3525 D Process : killProcessQuiet, pid=7354
06-30 12:51:51.224  1109  3525 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
,06-30 12:51:51.224  1109  1131 D PMS     : acquireWL(37b50f59): PARTIAL_WAKE_LOCK  Icing 0x1 3425 10019 null
06-30 12:51:51.224  3425  8350 I PeopleContactsSync: CP2 sync disabled
06-30 12:51:51.224  1109  3548 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=3425, uid=10019, userID:0
06-30 12:51:51.224  3425  6659 I Icing   : doRemovePackageData com.test.thalitest
06-30 12:51:51.224  1109  3086 D PMS     : releaseWL(37b50f59): PARTIAL_WAKE_LOCK  Icing 0x1 null
,06-30 12:51:51.314  1109  5212 I ActivityManager: Recipient 7354,
,06-30 12:51:51.314  1109  5612 I art     : Explicit concurrent mark sweep GC freed 7068(372KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/22MB, paused 2.162ms total 174.795ms
,06-30 12:51:51.334  3661  3661 E PackageActionReceiver: ACTION_PACKAGE_REMOVED,
06-30 12:51:51.334  1109  5182 I ActivityManager: Resuming delayed broadcast
,06-30 12:51:51.334  3606  8353 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest,
,06-30 12:51:51.344  3606  8353 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
,06-30 12:51:51.354  3532  3532 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
06-30 12:51:51.354  3532  3532 I ContextualWidget: package com.test.thalitest removed
,06-30 12:51:51.364  3532  3937 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
,06-30 12:51:51.374  3425  8349 W GmsApplication: Using Auth Proxy for data requests.,
06-30 12:51:51.374  3532  8354 I ContextualWidget: com.test.thalitest is not installed
06-30 12:51:51.374  3532  8354 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
,06-30 12:51:51.394  8357  8357 W HTCLOG  : use specified tag [FDManager], func [0].,
06-30 12:51:51.394  8357  8357 W HTCLOG  : mask=0x18
06-30 12:51:51.394  1109  3086 I ActivityManager: Start proc 8357:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
,06-30 12:51:51.394  3532  3937 I ContextualWidget: MFU.onDownloadDataSetChanged
,06-30 12:51:51.394  3532  3937 I ContextualWidget: handleMessage, what=1019 mode=GettingOut maxcount=8
06-30 12:51:51.404  3532  3532 I ContextualWidget: notifyDataChanged, pos=6 item=FolderInfo: Recent downloads, app folderId 0b8a6402-6f9b-4305-bf19-4676bde385e3, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))
06-30 12:51:51.404  3532  3532 I HtcContextualWidgetDataManager: onDataChanged: GettingOut, position: 6, item:[FolderInfo: Recent downloads, app folderId 0b8a6402-6f9b-4305-bf19-4676bde385e3, (Item(id=-1 type=6 container=-200 screen=-1 cellX=-1 cellY=-1 spanX=1 spanY=1 isGesture=false dropPos=null user=UserHandle{0}))]
,06-30 12:51:51.404  3425  8349 W GmsApplication: Using Auth Proxy for data requests.
,06-30 12:51:51.504  3425  8345 W DriveInitializer: Awaiting to be initialized
,06-30 12:51:51.504  1109  3086 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
06-30 12:51:51.504  8357  8357 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
,06-30 12:51:51.504  3425  8381 W DriveInitializer: Background init thread started
06-30 12:51:51.504  8357  8357 D IdefixUninstallListener: package_removed = com.test.thalitest
,06-30 12:51:51.514  3425  8381 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock43] disk I/O error,
06-30 12:51:51.514  3425  8381 W HTCLOG  : use specified tag [SQLiteDBG], func [0].,
06-30 12:51:51.514  3425  8381 W HTCLOG  : mask=0x18
06-30 12:51:51.514  3425  8381 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55b3d31e10
,06-30 12:51:51.514  3425  8381 E DocListDatabase: Failed to delete from ContentFileDeletionLock43,
06-30 12:51:51.514  3425  8381 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 12:51:51.514  3425  8381 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 12:51:51.514  3425  8381 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
06-30 12:51:51.514  3425  8381 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 12:51:51.514  3425  8381 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 12:51:51.514  3425  8381 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
06-30 12:51:51.514  3425  8381 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
06-30 12:51:51.514  3425  8381 E DocListDatabase: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103),
06-30 12:51:51.514  3425  8381 E DocListDatabase: 	at com.google.android.gms.drive.v.run(SourceFile:69)
06-30 12:51:51.524  3425  8381 W DriveInitializer: Background init thread ended,
06-30 12:51:51.524  3425  8345 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
06-30 12:51:51.524  3425  8345 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x55b3d31e10
06-30 12:51:51.524  3425  8381 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
06-30 12:51:51.524  3425  8381 E AndroidRuntime: Process: com.google.android.gms, PID: 3425
06-30 12:51:51.524  3425  8381 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 12:51:51.524  3425  8381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 12:51:51.524  3425  8381 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
06-30 12:51:51.524  3425  8381 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 12:51:51.524  3425  8381 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 12:51:51.524  3425  8381 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
06-30 12:51:51.524  3425  8381 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
06-30 12:51:51.524  3425  8381 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
06-30 12:51:51.524  3425  8381 E AndroidRuntime: 	at com.google.android.gms.drive.v.run(SourceFile:69)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: disk I/O error (code 3850),
06-30 12:51:51.524  3425  8345 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.m(SourceFile:501)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	,at com.google.android.gms.drive.database.i.c(SourceFile:495)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1406)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.ao.a(SourceFile:16)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:51.524  3425  8345 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 12:51:51.524  1109  3505 E ActivityManager: App crashed! Process: com.google.android.gms
,06-30 12:51:51.534  3425  8381 D Process : killProcess, pid=3425
06-30 12:51:51.534  3425  8381 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
06-30 12:51:51.534  3425  8381 W HTCLOG  : use specified tag [Process], func [0].
06-30 12:51:51.534  3425  8381 W HTCLOG  : mask=0x18
,06-30 12:51:51.534  1109  8382 E DropBoxManagerService: Can't write: system_app_crash
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:51.534  1109  8382 E DropBoxManagerService: 	,... 5 more
,06-30 12:51:51.544  8357  8357 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 12:51:51.544  8357  8357 W HTCLOG  : mask=0x18
,06-30 12:51:51.544  8357  8357 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
,06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	,at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 12:51:51.544  8357  8357 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 12:51:51.544  8357  8357 W System.err: java.sql.SQLException: Getting a writable database from helper a@2f428aae failed
06-30 12:51:51.554  1109  3557 I ActivityManager: Killing 7432:com.htc.sdm/u0a61 (adj 15): empty #17
06-30 12:51:51.544  8357  8357 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
06-30 12:51:51.554  8357  8357 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
06-30 12:51:51.554  8357  8357 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
06-30 12:51:51.554  8357  8357 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
06-30 12:51:51.554  8357  8357 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
06-30 12:51:51.554  8357  8357 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
06-30 12:51:51.554  8357  8357 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 12:51:51.554  8357  8357 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:51:51.554  8357  8357 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:51:51.554  8357  8357 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 12:51:51.554  8357  8357 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 12:51:51.554  8357  8357 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 12:51:51.554  8357  8357 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 12:51:51.554  8357  8357 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
06-30 12:51:51.554  8357  8357 W System.err: 	... 15 more
06-30 12:51:51.554   492   492 E lowmemorykiller: Error writing /proc/3425/oom_score_adj; errno=22
06-30 12:51:51.554  1109  3557 D Process : killProcessQuiet, pid=7432
06-30 12:51:51.554  1109  3557 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,06-30 12:51:51.614  1109  3086 I ActivityManager: Recipient 3425
06-30 12:51:51.614  1109  3524 D PMS     : handleWLDeath(244fa6ea): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
06-30 12:51:51.614  1109  1132 D PMS     : handleWLDeath(3c2debae): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
06-30 12:51:51.614  1109  3525 D PMS     : handleWLDeath(1d1fe20c): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
,06-30 12:51:51.674  1109  3909 I ActivityManager: Recipient 7432,
,06-30 12:51:51.704  3532  3822 E SharedPreferencesImpl: Couldn't rename file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml to backup file /data/user/0/com.htc.launcher/shared_prefs/com.htc.launcher.prefs.contextualwidget.xml.bak,
,06-30 12:51:51.764  1109  3086 I ActivityManager: Process com.google.android.gms (pid 3425) has died,
,06-30 12:51:51.764  1109  3086 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexService in 1000ms,
06-30 12:51:51.764  1109  3086 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 11000ms
,06-30 12:51:51.774  1109  3499 I ActivityManager: Killing 7605:com.google.android.gm/u0a97 (adj 15): empty #17
06-30 12:51:51.774  1109  3499 D Process : killProcessQuiet, pid=7605
06-30 12:51:51.774  1109  3499 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,06-30 12:51:51.784  6440  8384 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,06-30 12:51:51.824  6440  8384 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error,
06-30 12:51:51.824  6440  8384 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 12:51:51.824  6440  8384 W HTCLOG  : mask=0x18
06-30 12:51:51.824  6440  8384 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x55b3bbbd30
,06-30 12:51:51.854  7503  8271 I HtcModeClient: handler message = 4011,
06-30 12:51:51.854  7503  8271 D HtcModeClient: getConnectionCheckCount first 0
06-30 12:51:51.854  7503  8271 D HtcModeClient: getConnectionCheckCount count = 5
06-30 12:51:51.854  7503  8271 E HtcModeClient: Check connection and retry 6 times.
06-30 12:51:51.864  7503  8271 D HtcModeClient: setConnectionCheckCount count = 6
06-30 12:51:51.864  7503  8271 D HtcModeClient: setupRestart delayedTime = 3000,
,06-30 12:51:51.864  1109  3555 I ActivityManager: Recipient 7605
,06-30 12:51:51.864  7503  7561 E SharedPreferencesImpl: Couldn't rename file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml to backup file /data/data/com.htc.autobot/shared_prefs/PrefConnectState.xml.bak,
,06-30 12:51:51.914  1109  3909 I ActivityManager: Start proc 8386:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver,
06-30 12:51:51.924  6440  8384 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml,
06-30 12:51:51.924  7503  7503 D HtcModeClient: setBtPriority priority = on
06-30 12:51:51.924  7503  7503 D HtcModeClient: unbindBlueToothService
06-30 12:51:51.924  7503  7503 D HtcModeClient: Don't start project servcice
06-30 12:51:51.924  6440  8384 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
06-30 12:51:51.924  6440  8384 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6440
06-30 12:51:51.924  6440  8384 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
,06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:51.924  6440  8384 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 12:51:51.924  7503  7503 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: Can't write: system_app_crash
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:51.934  1109  8399 E DropBoxManagerService: 	... 5 more
06-30 12:51:51.934  7503  7503 D HtcModeClient: connectState: CONNECTION_READY = false
,06-30 12:51:51.934  7503  7503 D SilentMusic: call stop
06-30 12:51:51.934  7503  7503 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
06-30 12:51:51.934  7503  8272 W CANMesgAgentLocalSocket: read the terminate packet, so break
06-30 12:51:51.934  1109  3086 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
06-30 12:51:51.934  6440  8384 D Process : killProcess, pid=6440
06-30 12:51:51.934  6440  8384 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
,06-30 12:51:51.934  6440  8384 W HTCLOG  : use specified tag [Process], func [0].
06-30 12:51:51.934  6440  8384 W HTCLOG  : mask=0x18
06-30 12:51:51.934  8386  8386 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 12:51:51.934  8386  8386 W HTCLOG  : mask=0x18
,06-30 12:51:51.944  8001  8016 E AndroidHttpClient: Leak found,
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: ,	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 12:51:51.944  8001  8016 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 12:51:51.954  7503  7503 D HtcModeClient: onDestroy
,06-30 12:51:51.954  1109  3499 D Process : killProcessQuiet, pid=7283
06-30 12:51:51.954  1109  3499 I ActivityManager: Killing 7283:com.google.android.music:main/u0a115 (adj 15): empty #17
06-30 12:51:51.954  1109  3499 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,06-30 12:51:52.074  1109  1131 I ActivityManager: Recipient 6440,
06-30 12:51:52.074  1109  3077 D WifiService: Client connection lost with reason: 4,
,06-30 12:51:52.114  1109  5212 D MediaRouterService: Client com.google.android.music (pid 7283): Died!
06-30 12:51:52.114  1109  3555 I ActivityManager: Recipient 7283
,06-30 12:51:52.184  1109  1131 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6440) has died,
06-30 12:51:52.184  1109  1131 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 20584ms
06-30 12:51:52.184  1109  1131 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 30584ms
,06-30 12:51:52.224  8386  8386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 ,
,06-30 12:51:52.254  1109  1132 D PMS     : acquireWL(4ee491b): PARTIAL_WAKE_LOCK  AsyncService 0x1 8232 10128 null
,06-30 12:51:52.264  1109  3086 D PMS     : releaseWL(4ee491b): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,06-30 12:51:52.274  8112  8112 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
,06-30 12:51:52.274  8112  8112 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,06-30 12:51:52.274  8386  8409 W HTCLOG  : use specified tag [SQLiteDBG], func [0].,
06-30 12:51:52.274  8386  8409 W HTCLOG  : mask=0x18
06-30 12:51:52.274  8386  8409 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73]
06-30 12:51:52.274  8386  8409 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.android.keychain/databases/grants.db) - 
06-30 12:51:52.274  8386  8409 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 12:51:52.274  8386  8409 W HTCLOG  : mask=0x18
06-30 12:51:52.274  8386  8409 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.android.keychain/databases/grants.db, flag: 6, ret: 14
06-30 12:51:52.274  8386  8409 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
,06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:52.274  8386  8409 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
06-30 12:51:52.274  8386  8409 E AndroidRuntime: Process: com.android.keychain, PID: 8386
06-30 12:51:52.274  8386  8409 E AndroidRuntime: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:52.274  8386  8409 E AndroidRun,time: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:52.274  8386  8409 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 12:51:52.274  8112  8112 I DeviceManagement: WorkflowService: Starting workflow service
06-30 12:51:52.284  1109  5212 I ActivityManager: Start proc 8411:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
,06-30 12:51:52.284  1109  1131 E ActivityManager: App crashed! Process: com.android.keychain
06-30 12:51:52.284  8112  8410 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@3022a5fe] args=[Bundle[mParcelledData.dataSize=112]]
06-30 12:51:52.284  8112  8410 I DeviceManagement: PackageUpdateWorkflow: ==================================================
06-30 12:51:52.284  8112  8410 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
06-30 12:51:52.284  8112  8410 I DeviceManagement: PackageUpdateWorkflow: ==================================================
,06-30 12:51:52.284  1109  1131 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,06-30 12:51:52.294  8112  8410 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
06-30 12:51:52.294  8411  8411 W HTCLOG  : use specified tag [FDManager], func [0].
,06-30 12:51:52.294  8411  8411 W HTCLOG  : mask=0x18
06-30 12:51:52.294  1109  1131 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 12:51:52.294  1109  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.294  1109  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.294  1109  1131 W System.err: 	,at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 12:51:52.294  1109  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,06-30 12:51:52.294  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
,06-30 12:51:52.294  1109  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 12:51:52.294  1109  1131 W System.err: ,	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 12:51:52.294  1109  1131 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 12:51:52.294  1109  1131 W System.err: 	,at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 12:51:52.294  1109  1131 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,06-30 12:51:52.294  1109  1131 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.294  1109  1131 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.294  1109  1131 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.294  1109  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.294  1109  1131 W System.err: 	... 14 more
06-30 12:51:52.294  1109  1131 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 12:51:52.294  1109  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.294  1109  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.294  1109  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,06-30 12:51:52.294  1109  1131 W System.err: ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 12:51:52.304  1109  8430 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 12:51:52.304  1109  8430 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467283912318.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 12:51:52.304  1109  8430 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.304  1109  8430 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.304  1109  8430 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 12:51:52.304  1109  8430 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 12:51:52.304  1109  8430 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 12:51:52.304  1109  8430 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.304  1109  8430 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
,06-30 12:51:52.304  1109  8430 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.304  1109  8430 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.304  1109  8430 E ErrorReport: 	... 4 more
06-30 12:51:52.294  1109  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
,06-30 12:51:52.294  1109  1131 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 12:51:52.294  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 12:51:52.294  1109  1131 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 12:51:52.294  1109  1131 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.294  1109  1131 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.294  1109  1131 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.294  1109  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
,06-30 12:51:52.294  1109  1131 W System.err: 	... 14 more
06-30 12:51:52.304  8386  8409 D Process : killProcess, pid=8386
06-30 12:51:52.304  8386  8409 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 12:51:52.304  8386  8409 W HTCLOG  : use specified tag [Process], func [0].
06-30 12:51:52.304  8386  8409 W HTCLOG  : mask=0x18
,06-30 12:51:52.314  1109  3602 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
,06-30 12:51:52.314  1109  3602 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.314  1109  3602 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.314  1109  3602 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 12:51:52.314  1109  3602 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 12:51:52.314  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 12:51:52.314  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 12:51:52.314  1109  3602 W System.err: 	,at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 12:51:52.314  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 12:51:52.314  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 12:51:52.314  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 12:51:52.314  1109  3602 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:52.314  1109  3602 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:52.314  1109  3602 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,06-30 12:51:52.314  1109  3602 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.314  1109  3602 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.314  1109  3602 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.314  1109  3602 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.314  1109  3602 W System.err: 	... 12 more
06-30 12:51:52.314  8112  8410 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
,06-30 12:51:52.324  8411  8411 W ContextImpl: Unable to create files subdir /data/data/com.android.documentsui/cache
06-30 12:51:52.324  8112  8433 I DeviceManagement: SessionStateController: Checking invariants...
06-30 12:51:52.324  8411  8411 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,06-30 12:51:52.364  1109  3086 I ActivityManager: Recipient 8386
,06-30 12:51:52.364  1109  3086 I ActivityManager: Process com.android.keychain (pid 8386) has died
06-30 12:51:52.364  8411  8411 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
,06-30 12:51:52.364  1109  3086 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 30402ms
06-30 12:51:52.364  8411  8411 W HTCLOG  : mask=0x18
06-30 12:51:52.364  8411  8411 E SQLiteLog: (14) cannot open file at line 30046 of [9491ba7d73]
06-30 12:51:52.364  8411  8411 E SQLiteLog: (14) os_unix.c:30046: (2) open(/data/data/com.android.documentsui/databases/recents.db) - 
06-30 12:51:52.364  8411  8411 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 12:51:52.364  8411  8411 W HTCLOG  : mask=0x18
06-30 12:51:52.364  8411  8411 E SQLiteConnection: DB info: sqlite3_open_v2, path: /data/data/com.android.documentsui/databases/recents.db, flag: 6, ret: 14
06-30 12:51:52.364  8411  8411 E SQLiteConnection: DB info: errno = 2, errno message = No such file or directory
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 12:51:52.364  8411  8411 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: FATAL EXCEPTION: main
06-30 12:51:52.364  8411  8411 E AndroidRuntime: Process: com.android.documentsui, PID: 8411
06-30 12:51:52.364  8411  8411 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: ,	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
06-30 12:51:52.364  8411  8411 E AndroidRuntime: 	... 9 more
06-30 12:51:52.364  1109  3555 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 12:51:52.364  1109  3555 E ActivityManager: App crashed! Process: com.android.documentsui
06-30 12:51:52.364  1109  3555 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 12:51:52.364  1109  3555 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.364  1109  3555 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.,java:87)
06-30 12:51:52.364  1109  3555 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 12:51:52.364  1109  3555 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 12:51:52.364  1109  3555 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 12:51:52.364  1109  3555 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 12:51:52.364  1109  3555 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 12:51:52.364  1109  3555 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
06-30 12:51:52.374  1109  8435 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 12:51:52.374  1109  8435 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467283912389.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 12:51:52.374  1109  8435 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.374  1109  8435 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.374  1109  8435 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 12:51:52.374  1109  8435 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 12:51:52.374  1109  8435 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 12:51:52.374  1109  8435 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.374  1109  8435 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.374  1109  8435 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.374  1109  8435 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.374  1109  8435 E ErrorReport: 	... 4 more
06-30 12:51:52.364  1109  3555 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 12:51:52.364  1109  3555 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 12:51:52.364  1109  3555 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 12:51:52.364  1109  3555 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 12:51:52.364  1109  3555 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 12:51:52.374  1109  3555 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 12:51:52.374  1109  3555 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 12:51:52.374  1109  3555 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.374  1109  3555 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.374  1109  3555 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.374  1109  3555 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.374  1109  3555 W System.err: 	... 14 more
06-30 12:51:52.374  1109  3555 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 12:51:52.374  1109  3555 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.374  1109  3555 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.374  1109  3555 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 12:51:52.374  1109  3555 W System.err: 	at java.io.FileOutputStre,am.<init>(FileOutputStream.java:116)
06-30 12:51:52.374  1109  3555 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 12:51:52.374  1109  3555 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 12:51:52.374  1109  3555 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 12:51:52.384  1109  1131 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
06-30 12:51:52.374  1109  3555 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 12:51:52.374  1109  3555 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 12:51:52.374  1109  3555 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 12:51:52.374  1109  3555 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 12:51:52.374  1109  3555 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 12:51:52.374  1109  3555 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 12:51:52.374  1109  3555 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 12:51:52.374  1109  3555 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 12:51:52.374  1109  3555 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.374  1109  3555 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.374  1109  3555 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.374  1109  3555 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.374  1109  3555 W System.err: 	... 14 more
06-30 12:51:52.374  1109  3602 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 12:51:52.374  1109  3602 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.374  1109  3602 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.374  1109  3602 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 12:51:52.374  1109  3602 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 12:51:52.374  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 12:51:52.384  1109  8436 E ErrorReport: HtcErrorReportManager.Error in dumping error information
06-30 12:51:52.384  1109  8436 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1467283912400.dbox_tmp: open failed: EROFS (Read-only file system)
06-30 12:51:52.384  1109  8436 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.384  1109  8436 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.384  1109  8436 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
06-30 12:51:52.384  1109  8436 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
06-30 12:51:52.384  1109  8436 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
06-30 12:51:52.384  1109  8436 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.384  1109  8436 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.384  1109  8436 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.384  1109  8436 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.384  1109  8436 E ErrorReport: 	... 4 more
06-30 12:51:52.374  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 12:51:52.374  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 12:51:52.374  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 12:51:52.374  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 12:51:52.374  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 12:51:52.374  1109  3602 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:52.374  1109  3602 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:52.374  1109  3602 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 12:51:52.374  8411  8411 D Process : killProcess, pid=8411
06-30 12:51:52.374  8411  8411 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 12:51:52.374  8411  8411 W HTCLOG  : use specified tag [Process], func [0].
06-30 12:51:52.374  8411  8411 W HTCLOG  : mask=0x18
06-30 12:51:52.374  5510  5663 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
06-30 12:51:52.374  5510  5663 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
06-30 12:51:52.374  5510  5663 W HTCLOG  : mask=0x18
06-30 12:51:52.374  5510  5663 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x55b3b963a0
06-30 12:51:52.384  1109  3602 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
06-30 12:51:52.384  5510  5663 E AndroidRuntime: Process: android.process.media, PID: 5510
06-30 12:51:52.384  5510  5663 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:52.384  5510  5663 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 12:51:52.384  1109  3602 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.384  1109  3602 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.384  1109  3602 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.384  1109  3602 W System.err: 	... 12 more
06-30 12:51:52.384  1109  1131 E ActivityManager: App crashed! Process: android.process.media
06-30 12:51:52.384  1109  1131 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 12:51:52.384  1109  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.384  1109  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.384  1109  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 12:51:52.384  1109  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 12:51:52.384  1109  1131 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 12:51:52.384  1109  1131 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 12:51:52.384  1109  1131 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.384  1109  1131 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.384  1109  1131 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.384  1109  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.384  1109  1131 W System.err: 	... 14 more
06-30 12:51:52.384  1109  1131 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
06-30 12:51:52.384  1109  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.384  1109  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.384  1109  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 12:51:52.384  1109  1131 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
06-30 12:51:52.394  1109  1144 I ActivityManager: Start proc 8437:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
06-30 12:51:52.384  1109  1131 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
06-30 12:51:52.384  1109  1131 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
06-30 12:51:52.384  1109  1131 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
06-30 12:51:52.384  1109  1131 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.384  1109  1131 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.384  1109  1131 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.384  1109  1131 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.384  1109  1131 W System.err: 	... 14 more
06-30 12:51:52.384  1109  3602 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
06-30 12:51:52.384  1109  3602 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
06-30 12:51:52.384  1109  3602 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
06-30 12:51:52.384  1109  3602 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
06-30 12:51:52.384  1109  3602 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
06-30 12:51:52.384  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
06-30 12:51:52.384  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
06-30 12:51:52.384  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
06-30 12:51:52.384  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
06-30 12:51:52.384  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
06-30 12:51:52.384  1109  3602 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
06-30 12:51:52.384  1109  3602 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:52.384  1109  3602 W System.err: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:52.384  1109  3602 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 12:51:52.384  1109  3602 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
06-30 12:51:52.384  1109  3602 W System.err: 	at libcore.io.Posix.open(Native Method)
06-30 12:51:52.384  1109  3602 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
06-30 12:51:52.384  1109  3602 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
06-30 12:51:52.384  1109  3602 W System.err: 	... 12 more
06-30 12:51:52.394  5510  5663 D Process : killProcess, pid=5510
06-30 12:51:52.394  5510  5663 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
06-30 12:51:52.394  5510  5663 W HTCLOG  : use specified tag [Process], func [0].
06-30 12:51:52.394  5510  5663 W HTCLOG  : mask=0x18
06-30 12:51:52.414  8437  8437 W HTCLOG  : use specified tag [FDManager], func [0].
06-30 12:51:52.414  8437  8437 W HTCLOG  : mask=0x18
,06-30 12:51:52.434   492   492 E lowmemorykiller: Error writing /proc/5510/oom_score_adj; errno=22
06-30 12:51:52.434  1109  3557 W HTCLOG  : use specified tag [JavaBinder], func [0].
06-30 12:51:52.434  1109  3557 W HTCLOG  : mask=0x18
06-30 12:51:52.434  1109  3557 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
06-30 12:51:52.434  8112  8433 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
06-30 12:51:52.434  8112  8433 W HTCLOG  : mask=0x18
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
06-30 12:51:52.434  8112  8433 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
06-30 12:51:52.434  8112  8433 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 12:51:52.444  1109  3548 I ActivityManager: Killing 7829:com.htc.mobiledata:remote/u0a40 (adj 15): empty #17
06-30 12:51:52.434  8112  8410 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 12:51:52.434  8112  8410 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:52.444  8112  8410 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 12:51:52.444  8112  8410 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@3022a5fe]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
06-30 12:51:52.444  8112  8410 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
06-30 12:51:52.444  8112  8112 I DeviceManagement: WorkflowService: Stopping workflow service
06-30 12:51:52.444  1109  3548 D Process : killProcessQuiet, pid=7829
06-30 12:51:52.444  1109  3548 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,06-30 12:51:52.464  1109  1132 I ActivityManager: Recipient 5510
,06-30 12:51:52.484  1109  3524 I ActivityManager: Recipient 8411
,06-30 12:51:52.554  1109  3909 I ActivityManager: Recipient 7829
,06-30 12:51:52.564  3532  3899 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
06-30 12:51:52.564  3532  3899 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@23543042 +
06-30 12:51:52.564  3532  3899 I Prism.WidgetManager: onLoadItems() +

```
