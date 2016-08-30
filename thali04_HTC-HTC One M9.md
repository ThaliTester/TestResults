#### Test 83243049e1001da_thali04_HTC-HTC One M9 Logs


```
--------- beginning of main
08-30 12:41:49.041  8369  8369 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8369 dbg=false s=true
08-30 12:41:49.041  8369  8369 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
08-30 12:41:49.061  1134  1153 D Process : killProcessQuiet, pid=7961
08-30 12:41:49.061  1134  1153 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
08-30 12:41:49.061  8393  8393 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:41:49.061  8393  8393 W HTCLOG  : mask=0x18
--------- beginning of system
08-30 12:41:49.061  1134  1153 I ActivityManager: Start proc 8393:com.google.android.apps.docs/u0a91 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-30 12:41:49.061  1134  1153 I ActivityManager: Killing 7961:com.htc.calendar/u0a6 (adj 15): empty #17
,08-30 12:41:49.141  1134  4765 I ActivityManager: Recipient 7961
08-30 12:41:49.201  1134  3361 D PMS     : acquireWL(2dd7314e): PARTIAL_WAKE_LOCK  Icing 0x1 4279 10019 null
08-30 12:41:49.241  6617  8368 I ApplicationLogger: canRun() : Opted Out
08-30 12:41:49.241  6617  8368 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 288 ms] updated apps [took 288 ms] 
08-30 12:41:49.261  1134  1154 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 12:41:49.261  1134  3639 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 12:41:49.301  8393  8393 D DocsApplication: Plugin installer initialized.
08-30 12:41:49.301  1134  3361 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 12:41:49.311  8416  8416 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-30 12:41:49.311  8416  8416 W HTCLOG  : mask=0x18
08-30 12:41:49.311  8393  8393 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{2f5dffe2 com.google.android.apps.docs}
08-30 12:41:49.321  8393  8393 D TAG     : onCreate()
08-30 12:41:49.331  8393  8393 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 12:41:49.341  1134  3806 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 12:41:49.471  8416  8423 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-30 12:41:49.471  8416  8423 W HTCLOG  : mask=0x18
08-30 12:41:49.471  8416  8423 E cutils-trace: Error opening trace file: Permission denied (13)
08-30 12:41:49.531  8416  8416 D CustomizationManager: ====startRecUseTime====
08-30 12:41:49.531  8416  8416 D htc.customization.log.level:  is 
08-30 12:41:49.531  8416  8416 W CustomizationLogLevel: Level value is invalid, use default level 2
08-30 12:41:49.581  3574  3944 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
08-30 12:41:49.581  3574  3944 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@305d7e3 +
08-30 12:41:49.581  3574  3944 I Prism.WidgetManager: onLoadItems() +
08-30 12:41:49.601  3574  3944 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
08-30 12:41:49.611  8416  8416 D CustomizationManager:  Read ACC file spent 0.037 (s)
08-30 12:41:49.611  8416  8416 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-30 12:41:49.611  8416  8416 I CustomizationCIDLoader: Parsing tag category name = application
08-30 12:41:49.611  8416  8416 I CustomizationCIDLoader: Parsing tag category name = system
08-30 12:41:49.611  8416  8416 I CustomizationCIDLoader: Parsing tag category name = Settings
08-30 12:41:49.611  8416  8416 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-30 12:41:49.611  8416  8416 I CustomizationCIDLoader: Parsing tag category name = ACC
08-30 12:41:49.611  8416  8416 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-30 12:41:49.611  8416  8416 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-30 12:41:49.611  8416  8416 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-30 12:41:49.611  8416  8416 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-30 12:41:49.611  8416  8416 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-30 12:41:49.611  8416  8416 D CustomizationManager:  Read CID file spent 0.084 (s)
08-30 12:41:49.611  8416  8416 D CustomizationManager:  All configurations done spent 0.085 (s)
08-30 12:41:49.651  1134  3808 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8416 on display 0
08-30 12:41:49.651  1134  1181 D PMS     : acquireHCC(24243b7c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1134 1000 null
08-30 12:41:49.651  1134  1181 D PMS     : acquireHCC(2b754c05): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1134 1000 null
08-30 12:41:49.661  1134  3808 V WindowManager: addAppToken: AppWindowToken{23379368 token=Token{1bdd468b ActivityRecord{ef9145a u0 com.test.thalitest/.MainActivity t451}}} to stack=1 task=451 at 0
08-30 12:41:49.671  1134  3808 I ActivityManager: Start proc 8435:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-30 12:41:49.681  8416  8416 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-30 12:41:49.681  8416  8416 W HTCLOG  : mask=0x18
08-30 12:41:49.681  8416  8434 W HTCLOG  : use specified tag [Vector], func [0].
08-30 12:41:49.681  8416  8434 W HTCLOG  : mask=0x18
08-30 12:41:49.681  8435  8435 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:41:49.681  8435  8435 W HTCLOG  : mask=0x18
08-30 12:41:49.691  3553  4153 D PhoneApp: EVENT_QUERY_MO_PACKAGES
08-30 12:41:49.691  3553  4153 D PhoneApp: -- N1 =0
08-30 12:41:49.691  3553  4153 D PhoneApp: -- N2 =0
08-30 12:41:49.691  3553  4153 D PhoneApp: -- N3 =0
08-30 12:41:49.701  1134  1134 V ActivityManager: Display changed displayId=0
08-30 12:41:49.701  3315  3315 D DotMatrix: [EventService]  onDisplayChanged: 0
08-30 12:41:49.701  3315  3315 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-30 12:41:49.711  1134  3806 D ActivityManager: screenshot for ActivityRecord{ef9145a u0 com.test.thalitest/.MainActivity t451}, bitmap=null, time = 0
08-30 12:41:49.721  3574  3574 I TrimMemoryManager: [trimMemory] 20
08-30 12:41:49.761  8435  8435 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-30 12:41:49.771  3574  3944 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 12:41:49.811  8435  8435 I LibraryLoader: Time to load native libraries: 30 ms (timestamps 4957-4987)
08-30 12:41:49.811  8435  8435 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:41:49.821  8435  8435 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {38e0382e}
08-30 12:41:49.821  8435  8435 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 12:41:49.831  8435  8435 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 12:41:49.831  8435  8435 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 12:41:49.831  8435  8435 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 12:41:49.831  8435  8435 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 12:41:49.871  8435  8458 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
08-30 12:41:49.881  5603  5981 D BluetoothAdapterService(1046216240): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@25b698d
,08-30 12:41:49.891  8435  8435 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-30 12:41:49.891  8435  8435 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50364 len=3345
08-30 12:41:49.891  8435  8435 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:9397000 len:1161174
08-30 12:41:49.891  8435  8435 W HTCLOG  : use specified tag [libEGL], func [3].
08-30 12:41:49.891  8435  8435 W HTCLOG  : mask=0x18
08-30 12:41:49.891  8435  8435 W HTCLOG  : use specified tag [libEGL], func [3].
08-30 12:41:49.891  8435  8435 W HTCLOG  : mask=0x18
08-30 12:41:49.891  8435  8435 I Adreno  : QUALCOMM build                   : 065751b, 
08-30 12:41:49.891  8435  8435 I Adreno  : Build Date                       : 04/15/15
08-30 12:41:49.891  8435  8435 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-30 12:41:49.891  8435  8435 I Adreno  : Local Branch                     : 
08-30 12:41:49.891  8435  8435 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-30 12:41:49.891  8435  8435 I Adreno  : Remote Branch                    : NONE
08-30 12:41:49.891  8435  8435 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
,08-30 12:41:49.921  3574  3944 I Prism.WidgetManager: onLoadItems() -,
08-30 12:41:49.921  3574  3944 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@305d7e3 -
,08-30 12:41:49.971  8435  8468 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup,
,08-30 12:41:49.981  8435  8435 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:41:49.991  8435  8435 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 12:41:50.001  8435  8435 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC,
,08-30 12:41:50.011  8435  8435 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
08-30 12:41:50.011  8435  8435 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-30 12:41:50.031  8435  8479 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].,
08-30 12:41:50.031  8435  8479 W HTCLOG  : mask=0x18
,08-30 12:41:50.041  1134  3806 V WindowManager: Adding window Window{24f3b0b0 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{160d72f9 u0 com.htc.launcher/com.htc.launcher.Launcher})
,08-30 12:41:50.041  1134  3635 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,08-30 12:41:50.071  8435  8435 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,08-30 12:41:50.071  8435  8435 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-30 12:41:50.071  8435  8435 W HTCLOG  : mask=0x18
08-30 12:41:50.071  8435  8435 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 12:41:50.071  8435  8435 W HTCLOG  : mask=0x18
,08-30 12:41:50.071  8435  8479 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
,08-30 12:41:50.071  8435  8479 W HTCLOG  : mask=0x18
08-30 12:41:50.071  8435  8479 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 12:41:50.071  8435  8479 W HTCLOG  : mask=0x18
08-30 12:41:50.071  8435  8479 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 12:41:50.071  8435  8479 W HTCLOG  : mask=0x18
,08-30 12:41:50.071  8435  8479 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 12:41:50.071  8435  8479 W HTCLOG  : mask=0x18
,08-30 12:41:50.091  8435  8479 W HTCLOG  : use specified tag [Surface], func [3].
,08-30 12:41:50.091  8435  8479 W HTCLOG  : mask=0x18
,08-30 12:41:50.091  8435  8479 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-30 12:41:50.091  8435  8479 W HTCLOG  : mask=0x18
08-30 12:41:50.091  8435  8479 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-30 12:41:50.091  8435  8479 W HTCLOG  : mask=0x18
,08-30 12:41:50.141  1134  1172 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +430ms (total +475ms),
,08-30 12:41:50.181  3553  3718 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC >>
08-30 12:41:50.181  3553  3718 D ContactMessageStore: MSG_NOTIFY_CS_TO_SYNC <<
08-30 12:41:50.181  8435  8435 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8435
08-30 12:41:50.201  8393  8488 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 12:41:50.201  8393  8488 W HTCLOG  : mask=0x18
08-30 12:41:50.241  8435  8435 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 12:41:50.251  4279  6842 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
08-30 12:41:50.251  1134  4765 I ActivityManager: Start proc 8492:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
08-30 12:41:50.251  1134  4765 I ActivityManager: Killing 7557:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
08-30 12:41:50.251  1134  4765 D Process : killProcessQuiet, pid=7557
08-30 12:41:50.251  1134  4765 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
08-30 12:41:50.261  8492  8492 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:41:50.261  8492  8492 W HTCLOG  : mask=0x18
08-30 12:41:50.301  8435  8482 D jxcore_app_log: JniHelper::setJavaVM(0xab2aab70), pthread_self() = -1406946424
08-30 12:41:50.301  8435  8482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 12:41:50.301  8435  8482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 12:41:50.301  8435  8482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 12:41:50.301  8435  8482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 12:41:50.301  8435  8482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 12:41:50.301  8435  8482 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d913d45 added. We now have 1 listener(s)
08-30 12:41:50.421  1134  3808 I ActivityManager: Recipient 7557
08-30 12:41:50.471  1134  4759 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-30 12:41:50.471  1134  3039 V AlarmManager: sending alarm PendingIntent{20829674: PendingIntentRecord{3329979d android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=81728, Int=0
08-30 12:41:50.471  8435  8482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
08-30 12:41:50.471  1134  3039 V AlarmManager: sending alarm PendingIntent{15559412: PendingIntentRecord{79b7e3 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1472553710055, Int=0
08-30 12:41:50.471  8435  8482 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
08-30 12:41:50.471  8435  8482 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 12:41:50.471  8435  8482 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 12:41:50.481  8393  8393 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 12:41:50.481  8435  8482 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@226425a8 added. We now have 1 listener(s)
08-30 12:41:50.481  8435  8482 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 12:41:50.481  1134  3082 D WifiService: New client listening to asynchronous messages
08-30 12:41:50.481  8492  8492 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 12:41:50.481  8435  8482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 12:41:50.481  8435  8482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 12:41:50.481  8435  8482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 12:41:50.481  8435  8482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 12:41:50.481  8435  8482 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 12:41:50.481  8435  8482 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 12:41:50.491  1134  3806 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-30 12:41:50.491  8435  8482 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
08-30 12:41:50.491  5603  5649 D BluetoothAdapterService(1046216240): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@25b698d
08-30 12:41:50.491  8435  8482 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 12:41:50.491  8435  8482 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 12:41:50.491  8435  8482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:41:50.491  8435  8482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:41:50.491  8435  8482 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:41:50.491  8435  8482 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:41:50.491  8435  8482 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:41:50.491  8435  8482 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:41:50.491  8435  8482 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 12:41:50.491  8435  8482 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 12:41:50.491  8435  8482 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 12:41:50.491  8435  8482 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 12:41:50.491  8435  8435 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 12:41:50.511  4279  6842 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 12:41:50.531  8435  8435 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-30 12:41:50.541  4279  6842 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
08-30 12:41:50.541  1134  4765 D PMS     : releaseWL(2dd7314e): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-30 12:41:50.651  1134  1181 D PMS     : releaseHCC(24243b7c): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null
08-30 12:41:50.651  1134  1181 D PMS     : releaseHCC(2b754c05): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
08-30 12:41:50.711  1134  3090 D PMS     : acquireWL(2ff4405b): PARTIAL_WAKE_LOCK  AsyncService 0x1 8492 10128 null
08-30 12:41:50.721  1134  1153 D PMS     : releaseWL(2ff4405b): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-30 12:41:50.741  3152  3152 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 12:41:50.741  3152  3152 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-30 12:41:50.751  1134  3050 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 12:41:50.741  3152  3152 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-30 12:41:50.741  3152  3152 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: Scan completed in 3.601889 seconds
08-30 12:41:50.741  3152  3152 D wpa_supplicant: nl80211: Received scan results (38 BSSes)
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-47
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-48
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-55
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:7b freq=5200 level=-61
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-61
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-61
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-68
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-74
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-75
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-80
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-80
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-76
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-76
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-76
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-81
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1c:62:d0 freq=2437 level=-79
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:36 freq=2412 level=-80
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-80
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:34 freq=2412 level=-80
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:12:64:92 freq=2462 level=-82
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:12:64:9b freq=5180 level=-88
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:12:64:9a freq=5180 level=-88
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:12:64:9f freq=5180 level=-89
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 00:fe:c8:73:02:05 freq=2462 level=-85
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-84
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:7e freq=5200 level=-61
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-74
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-75
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-80
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [RA-WINGS] 84:b2:61:1c:62:d3 freq=2437 level=-78
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-80
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-81
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-81
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:1c:62:d1 freq=2437 level=-81
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:12:64:91 freq=2462 level=-81
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [] 84:b2:61:21:47:5e freq=5180 level=-89
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-85
08-30 12:41:50.741  3152  3152 I wpa_supplicant: [RA-WINGS] e4:aa:5d:fc:5b:f3 freq=2437 level=-86
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Start scan result update 6
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 74 BSSID 84:b2:61:1a:ce:79 SSID '\x00'
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 75 BSSID 84:b2:61:0f:9c:30 SSID '\x00'
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 76 BSSID 84:b2:61:12:64:9a SSID '\x00'
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 77 BSSID 00:fe:c8:73:02:05 SSID '\x00'
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 78 BSSID e4:aa:5d:fc:5b:f3 SSID 'RA-WINGS'
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 61 BSSID 84:b2:61:1c:62:d6 SSID '\x00' due to no match in scan
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 38 BSSID 84:b2:61:1c:62:d5 SSID '\x00' due to no match in scan
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 62 BSSID 84:b2:61:1c:62:da SSID '\x00' due to no match in scan
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 17 BSSID 84:b2:61:1c:62:d9 SSID '\x00' due to no match in scan
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 19 BSSID 84:b2:61:1c:62:df SSID '\x00' due to no match in scan
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 65 BSSID 84:b2:61:12:64:99 SSID '\x00' due to no match in scan
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 66 BSSID e4:aa:5d:fc:5b:f5 SSID '\x00' due to no match in scan
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 52 BSSID 84:b2:61:12:64:9e SSID '\x00' due to no match in scan
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 67 BSSID 00:fe:c8:73:02:01 SSID '\x00' due to no match in scan
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: BSS: last_scan_res_used=38/64
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: Scan-only results received
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:41:50.741  3152  3152 D wpa_supplicant: wlan0: Radio work 'scan'@0x55834e5710 done in 3.646917 seconds
08-30 12:41:50.751  3152  3152 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-30 12:41:50.751  3152  3152 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 12:41:50.751  3152  3152 D wpa_supplicant: wlan0: Cancelling scan request
08-30 12:41:50.751  3152  3152 D wpa_supplicant: PNO: No configured SSIDs
08-30 12:41:50.751  1134  3050 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 12:41:50.751  3152  3152 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 12:41:50.751  3152  3152 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-30 12:41:50.751  7700  7700 D AlarmReceiver: ACTION_RESTART_INTENT
08-30 12:41:50.761  3152  3152 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-30 12:41:50.761  1134  3050 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-30 12:41:50.761  1134  1134 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 13
08-30 12:41:50.761  4470  5932 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 12:41:50.761  4470  4470 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 12:41:50.771  4011  4011 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 12:41:50.771  4011  4011 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-30 12:41:50.781  7700  7700 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 12:41:50.781  7700  7700 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 12:41:50.781  7700  7700 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 12:41:50.781  7700  7700 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-30 12:41:50.781  4011  4011 D c       : Getting all permits...
08-30 12:41:50.781  4011  4011 D a       : Opening database...
08-30 12:41:50.791  4011  4011 D a       : Opening database auth.proximity.permit_store...
08-30 12:41:50.791  4011  4011 D a       : Closing database...
08-30 12:41:50.801  4279  4279 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
08-30 12:41:50.821  1134  1134 D PMS     : acquireWL(1a677c36): PARTIAL_WAKE_LOCK  *backup* 0x1 1134 1000 null
08-30 12:41:50.821  1134  1134 D PMS     : releaseWL(691008f): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
08-30 12:41:50.821  7700  8529 D HtcModeClient: start the htcmodeservice thread
08-30 12:41:50.821  7700  8529 D HtcModeClient: initCanAgent
08-30 12:41:50.821  7700  8529 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-30 12:41:50.821  4279  8528 D LocationInitializer: Restart initialization of location
08-30 12:41:50.821  7700  8529 D HtcModeClient: sense info: version = none, id = 2
08-30 12:41:50.831  7700  8529 D HtcModeClient: display info: width = 1080, height = 1776
08-30 12:41:50.831  1134  3120 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService
08-30 12:41:50.831  7700  8529 D HtcModeClient: display info: mode = 10
08-30 12:41:50.831  1134  3120 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found
08-30 12:41:50.831  1134  3120 D PMS     : releaseWL(1a677c36): PARTIAL_WAKE_LOCK  *backup* 0x1 null
,08-30 12:41:50.921  7700  7700 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
08-30 12:41:50.921  7700  7700 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 12:41:50.921  7700  7700 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 12:41:50.921  7700  7700 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 12:41:50.921  7700  7700 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 12:41:50.921  7700  7700 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 12:41:50.921  7700  7700 D HtcModeClient: connectState: Force_AWAKE = false
08-30 12:41:50.921  7700  7700 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 12:41:50.921  7700  7700 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 12:41:50.971  8435  8520 W jxcore-log: Initializing JXcore engine
08-30 12:41:50.971  8435  8520 W jxcore-log: JXcore engine is ready
,08-30 12:41:51.031  8435  8520 W jxcore-log: Starting JXcore engine,
,08-30 12:41:51.121  8435  8520 W jxcore-log: Platform android,
08-30 12:41:51.121  8435  8520 W jxcore-log: 
08-30 12:41:51.121  8435  8520 W jxcore-log: Process ARCH arm
08-30 12:41:51.121  8435  8520 W jxcore-log: 
,08-30 12:41:51.311  8435  8520 I jxcore-log: JXcore Cordova bridge is ready!,
08-30 12:41:51.311  8435  8520 I jxcore-log: 
08-30 12:41:51.311  8435  8520 W jxcore-log: JXcore engine is started
,08-30 12:41:51.311  8435  8482 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 12:41:51.311  8435  8435 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 12:41:51.711   572   572 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-30 12:41:52.931  7700  8529 I HtcModeClient: handler message = 4011
,08-30 12:41:52.941  7700  8529 D HtcModeClient: getConnectionCheckCount first 0
08-30 12:41:52.941  7700  8529 D HtcModeClient: getConnectionCheckCount count = 6
08-30 12:41:52.941  7700  8529 E HtcModeClient: Check connection and retry 7 times.
08-30 12:41:52.941  7700  8529 D HtcModeClient: setConnectionCheckCount count = 7
08-30 12:41:52.941  7700  8529 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 12:41:52.951  7700  7700 D HtcModeClient: setBtPriority priority = on
,08-30 12:41:52.951  7700  7700 D HtcModeClient: unbindBlueToothService
08-30 12:41:52.951  7700  7700 D HtcModeClient: Don't start project servcice
08-30 12:41:52.951  7700  7700 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 12:41:52.951  7700  7700 D HtcModeClient: connectState: CONNECTION_READY = false
,08-30 12:41:52.951  7700  7700 D SilentMusic: call stop
08-30 12:41:52.951  7700  7700 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 12:41:52.951  7700  8530 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 12:41:52.961  7700  7700 D HtcModeClient: onDestroy,
,08-30 12:41:53.191  8259  8274 E AndroidHttpClient: Leak found,
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
,08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
,08-30 12:41:53.191  8259  8274 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 12:41:53.891  8313  8313 D Process : killProcess, pid=8313
08-30 12:41:53.891  8313  8313 D Process : com.google.android.gms.car.gt.run:127 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
08-30 12:41:53.891  8313  8313 W HTCLOG  : use specified tag [Process], func [0].
08-30 12:41:53.891  8313  8313 W HTCLOG  : mask=0x18
08-30 12:41:53.891   493   493 E lowmemorykiller: Error writing /proc/8313/oom_score_adj; errno=22
,08-30 12:41:53.971  1134  3639 I ActivityManager: Recipient 8313,
08-30 12:41:53.971  1134  3639 I ActivityManager: Process com.google.android.gms:car (pid 8313) has died
,08-30 12:41:54.251  8393  8393 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().,
,08-30 12:41:55.191  8393  8484 I GAV2    : Thread[GAThread,5,main]: No campaign data found.,
,08-30 12:41:57.531  1134  1134 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,08-30 12:41:57.951  1134  3039 D PMS     : acquireWL(2ed905c5): PARTIAL_WAKE_LOCK  *alarm* 0x1 1134 1000 WorkSource{10027}
08-30 12:41:57.951  1134  3039 V AlarmManager: sending alarm PendingIntent{d87ab1a: PendingIntentRecord{571ced8 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=91122, Int=0
08-30 12:41:57.961  7700  7700 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 12:41:57.971  1134  1134 D PMS     : releaseWL(2ed905c5): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
,08-30 12:41:57.971  7700  7700 D LocalBluetoothProfile: getPriorityOnValue = 100
,08-30 12:41:57.971  7700  7700 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 12:41:57.971  7700  7700 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
,08-30 12:41:57.971  7700  7700 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 12:41:57.991  7700  8538 D HtcModeClient: start the htcmodeservice thread,
08-30 12:41:57.991  7700  8538 D HtcModeClient: initCanAgent
,08-30 12:41:58.001  7700  8538 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-30 12:41:58.001  7700  8538 D HtcModeClient: sense info: version = none, id = 2
,08-30 12:41:58.001  7700  8538 D HtcModeClient: display info: width = 1080, height = 1776
,08-30 12:41:58.001  7700  8538 D HtcModeClient: display info: mode = 10,
,08-30 12:41:58.101  7700  7700 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
,08-30 12:41:58.101  7700  7700 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 12:41:58.101  7700  7700 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 12:41:58.101  7700  7700 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 12:41:58.101  7700  7700 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 12:41:58.101  7700  7700 D HtcModeClient: connectState: PHONE_PULGIN = false,
08-30 12:41:58.101  7700  7700 D HtcModeClient: connectState: Force_AWAKE = false
08-30 12:41:58.101  7700  7700 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 12:41:58.101  7700  7700 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 12:41:58.421  1134  3806 D PMS     : releaseWL(2155a6c4): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null
,08-30 12:42:00.111  7700  8538 I HtcModeClient: handler message = 4011,
08-30 12:42:00.111  7700  8538 D HtcModeClient: getConnectionCheckCount first 0
,08-30 12:42:00.111  7700  8538 D HtcModeClient: getConnectionCheckCount count = 7,
08-30 12:42:00.111  7700  8538 E HtcModeClient: Check connection and retry 8 times.,
,08-30 12:42:00.121  7700  8538 D HtcModeClient: setConnectionCheckCount count = 8
08-30 12:42:00.121  7700  8538 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 12:42:00.121  7700  7700 D HtcModeClient: setBtPriority priority = on
08-30 12:42:00.121  7700  7700 D HtcModeClient: unbindBlueToothService
08-30 12:42:00.121  7700  7700 D HtcModeClient: Don't start project servcice
,08-30 12:42:00.121  7700  7700 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 12:42:00.131  7700  7700 D HtcModeClient: connectState: CONNECTION_READY = false
,08-30 12:42:00.131  7700  7700 D SilentMusic: call stop
,08-30 12:42:00.131  7700  7700 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 12:42:00.131  7700  8539 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 12:42:00.141  7700  7700 D HtcModeClient: onDestroy,
,08-30 12:42:02.111  1134  3050 D WifiStateMachine: startScan Pid: 1134 Uid -1,
08-30 12:42:02.111  1134  3050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-30 12:42:02.111  1134  3050 D WifiDisplayAdapter:     Client/Owner: Client
08-30 12:42:02.111  1134  3050 D WifiDisplayAdapter:     GroupId: 
08-30 12:42:02.111  1134  3050 D WifiDisplayAdapter:     Passphrase: 
08-30 12:42:02.111  1134  3050 D WifiDisplayAdapter:     SessionId: 0
08-30 12:42:02.111  1134  3050 D WifiDisplayAdapter:     IP Address: }
08-30 12:42:02.111  3152  3152 D wpa_supplicant: wlan0: Control interface command 'SET pno 0',
08-30 12:42:02.111  3152  3152 D wpa_supplicant: CTRL_IFACE SET 'pno'='0'
08-30 12:42:02.111  3152  3152 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
08-30 12:42:02.111  3152  3152 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
08-30 12:42:02.111  3152  3152 I wpa_supplicant: wpa_supplicant_scan enter
08-30 12:42:02.111  3152  3152 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-30 12:42:02.111  3152  3152 D wpa_supplicant: wlan0: Add radio work 'scan'@0x55834e5710
08-30 12:42:02.111  3152  3152 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-30 12:42:02.111  3152  3152 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x55834e5710 after 0.000026 second wait
08-30 12:42:02.111  3152  3152 D wpa_supplicant: wlan0: nl80211: scan request
,08-30 12:42:02.151  3152  3152 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
08-30 12:42:02.151  3152  3152 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0,
08-30 12:42:02.151  3152  3152 D wpa_supplicant: wlan0: nl80211: Scan trigger
08-30 12:42:02.151  3152  3152 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
,08-30 12:42:02.151  3152  3152 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000100 seconds
08-30 12:42:02.151  3152  3152 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 12:42:02.151  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
,08-30 12:42:02.861  1134  1164 I ActivityManager: Waited long enough for: ServiceRecord{366f0d90 u0 com.google.android.gms/.wearable.service.WearableService},
,08-30 12:42:03.241  1134  4765 D PMS     : acquireWL(2fa8e3c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1134 1000 null,
08-30 12:42:03.241  1134  4765 I BatteryService: n_update end
08-30 12:42:03.241  1134  4765 D PMS     : releaseWL(2fa8e3c3): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-30 12:42:03.251  1134  1177 D HtcPowerSaver: updateBatteryInfo,
,08-30 12:42:03.251  1134  1134 D HtcPowerSaver: Checking...
08-30 12:42:03.251  3205  3686 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-30 12:42:03.251  1134  1134 I HtcPowerSaver: >> updateStatus
08-30 12:42:03.251  3315  3315 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-30 12:42:03.251  3205  3205 D PowerUI : closing low battery warning: level=100
08-30 12:42:03.251  3315  3315 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-30 12:42:03.251  3315  3315 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
08-30 12:42:03.251  3205  3205 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
,08-30 12:42:03.251  1134  1134 D UsbnetService: BroadcastReceiver::onReceive+,
08-30 12:42:03.251  1134  1134 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-30 12:42:03.251  1134  1134 I HtcPowerSaver: << updateStatus
08-30 12:42:03.261  1134  1134 D UsbnetService: onReceive BATTERY_CHANGED
08-30 12:42:03.251  1134  1134 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-30 12:42:03.261  1134  1134 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-30 12:42:03.261  1134  1134 D UsbnetService: BroadcastReceiver::onReceive-
08-30 12:42:03.261  1134  3082 D WifiController: battery changed pluggedType: 2
,08-30 12:42:03.261  1134  3082 D WifiController: handleMessage: E msg.what=155652
08-30 12:42:03.261  1134  3082 D WifiController: processMsg: DeviceActiveState
08-30 12:42:03.261  1134  3082 D WifiController: processMsg: StaEnabledState
08-30 12:42:03.261  1134  3082 D WifiController: processMsg: DefaultState
08-30 12:42:03.261  1134  3082 D WifiController: handleMessage: X
,08-30 12:42:03.301  3205  3205 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-30 12:42:03.301  3205  3205 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-30 12:42:03.301  3205  3205 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-30 12:42:03.301  3205  3205 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-30 12:42:03.301  3205  3205 I FlashlightController: batteryLevelChange:100
,08-30 12:42:05.121  1134  3039 D PMS     : acquireWL(2c209440): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 1134 1000 WorkSource{1000}
,08-30 12:42:05.121  1134  3039 V AlarmManager: sending alarm PendingIntent{c496c13: PendingIntentRecord{3e2fe50 android broadcastIntent}}, i=android.intent.action.TIME_TICK, t=3, cnt=1, w=95168, Int=0
,08-30 12:42:05.121  1134  3039 V AlarmManager: sending alarm PendingIntent{208acf79: PendingIntentRecord{12c811df com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=95993, Int=0
,08-30 12:42:05.141  1134  3039 I ActivityManager: Start proc 8540:com.htc.mms.backupagent/u0a58 for service com.htc.mms.backupagent/.SMSBackupAgentService,
08-30 12:42:05.141  1134  3039 V AlarmManager: sending alarm PendingIntent{16e764be: PendingIntentRecord{2a2bf91f com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1472553722420, Int=60000
,08-30 12:42:05.141  1134  3039 V AlarmManager: sending alarm PendingIntent{375fea35: PendingIntentRecord{27310eca com.android.vending startService}}, i=null, t=0, cnt=1, w=1472553723430, Int=0
,08-30 12:42:05.141  1134  3039 V AlarmManager: sending alarm PendingIntent{1ca1083b: PendingIntentRecord{571ced8 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=98293, Int=0
08-30 12:42:05.141  1134  3363 D PMS     : acquireWL(19b4ab58): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 4011 10019 null,
08-30 12:42:05.151  4011  8553 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 4
08-30 12:42:05.151  4011  8553 D libc    : [NET] android_getaddrinfofornet-, err=8
08-30 12:42:05.151  4011  8553 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
08-30 12:42:05.161  7700  7700 D AlarmReceiver: ACTION_RESTART_INTENT
08-30 12:42:05.161  4011  8553 D libc    : [NET] android_getaddrinfofornet-, pass to proxy
08-30 12:42:05.161  4011  8553 D libc    : [NET] android_getaddrinfo_proxy+
08-30 12:42:05.161  4011  8553 D libc    : [NET] android_getaddrinfo_proxy get netid:0
08-30 12:42:05.161  8540  8540 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:05.161  8540  8540 W HTCLOG  : mask=0x18
08-30 12:42:05.161   516  8555 D libc    : [NET] android_getaddrinfofornet+,hn 16(0x6d74616c6b2e67),sn(),hints(known),family 0,flags 1024
08-30 12:42:05.161   516  8555 D libc    : [NET] _dns_getaddrinfo+, netid:0, mark:917504
08-30 12:42:05.161   516  8555 D libc    : [NET] _dns_getaddrinfo-, 3 (NS_NOTFOUND)
08-30 12:42:05.161   516  8555 D libc    : [NET] android_getaddrinfofornet-, err=7
08-30 12:42:05.161  7700  7700 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 12:42:05.161  7700  7700 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 12:42:05.161  7700  7700 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 12:42:05.171  7700  7700 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
08-30 12:42:05.171  4011  8553 D libc    : [NET] android_getaddrinfo_proxy-, NODATA
08-30 12:42:05.181  1134  1134 D PMS     : releaseWL(2c209440): PARTIAL_WAKE_LOCK  *alarm* 0x40000001 WorkSource{1000}
08-30 12:42:05.181  1134  3551 D PMS     : releaseWL(19b4ab58): PARTIAL_WAKE_LOCK  GCM_CONN_ALARM 0x1 null
,08-30 12:42:05.201  8540  8564 D SMSBackup: SMSBackupAgentService started,
08-30 12:42:05.201  8540  8564 D SMSBackup: Checking restore status
08-30 12:42:05.201  7700  8565 D HtcModeClient: start the htcmodeservice thread
08-30 12:42:05.201  7700  8565 D HtcModeClient: initCanAgent
08-30 12:42:05.201  7700  8565 I CANMesgAgentLocalSocket: CANAgent Id = 0
08-30 12:42:05.201  8540  8564 D SMSBackup: Restore complete
,08-30 12:42:05.201  8540  8564 D SMSBackup: cancelCheckAlarm
08-30 12:42:05.201  7700  8565 D HtcModeClient: sense info: version = none, id = 2
08-30 12:42:05.201  8540  8564 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds
08-30 12:42:05.211  7700  8565 D HtcModeClient: display info: width = 1080, height = 1776,
,08-30 12:42:05.211  7700  8565 D HtcModeClient: display info: mode = 10
,08-30 12:42:05.301  7700  7700 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-30 12:42:05.301  7700  7700 D HtcModeClient: connectState: BT_TURNON_BYME = false
,08-30 12:42:05.301  7700  7700 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 12:42:05.301  7700  7700 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 12:42:05.301  7700  7700 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 12:42:05.301  7700  7700 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 12:42:05.301  7700  7700 D HtcModeClient: connectState: Force_AWAKE = false
08-30 12:42:05.301  7700  7700 D HtcModeClient: connectState: PHONE_PULGIN = true,
08-30 12:42:05.301  7700  7700 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 12:42:05.441  8259  8259 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.,
,08-30 12:42:05.751  3152  3152 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0,
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 12:42:05.751  3152  3152 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-30 12:42:05.751  3152  3152 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825,
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received,
08-30 12:42:05.761  1134  3050 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 12:42:05.751  3152  3152 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: Scan completed in 3.598664 seconds
08-30 12:42:05.751  3152  3152 D wpa_supplicant: nl80211: Received scan results (43 BSSes)
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-49
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-49
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-55
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-55
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-60
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:7b freq=5200 level=-60
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-60
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-61
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-66
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-79
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-75
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:70 freq=2412 level=-75
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-75
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-80
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-80
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-80
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-76
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-76
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-76
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1c:62:d4 freq=2437 level=-78
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1c:62:d0 freq=2437 level=-80
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1c:62:d2 freq=2437 level=-80
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-81
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:35 freq=2412 level=-81
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:12:64:96 freq=2462 level=-82
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:12:64:94 freq=2462 level=-82
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:21:47:54 freq=2437 level=-83
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:32 freq=2412 level=-83
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:12:64:9a freq=5180 level=-88
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:21:47:59 freq=5180 level=-88
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:21:47:5a freq=5180 level=-88
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:21:47:5b freq=5180 level=-88
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] e4:aa:5d:fc:5b:f6 freq=2437 level=-87
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 00:fe:c8:73:02:06 freq=2462 level=-88
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-74
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-80
08-30 12:42:05.751  3152  3152 I wpa_suppli,cant: [RA-WINGS] 84:b2:61:1c:62:d3 freq=2437 level=-79
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:1c:62:d1 freq=2437 level=-80
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-81
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-81
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-82
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 84:b2:61:12:64:91 freq=2462 level=-82
08-30 12:42:05.751  3152  3152 I wpa_supplicant: [] 00:fe:c8:73:02:01 freq=2462 level=-85
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Start scan result update 7
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 79 BSSID 84:b2:61:1c:62:d4 SSID '\x00'
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 80 BSSID 84:b2:61:12:64:96 SSID '\x00'
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 81 BSSID 84:b2:61:12:64:94 SSID '\x00'
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 82 BSSID 84:b2:61:21:47:54 SSID '\x00'
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 83 BSSID 84:b2:61:21:47:59 SSID '\x00'
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 84 BSSID e4:aa:5d:fc:5b:f6 SSID '\x00'
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 85 BSSID 00:fe:c8:73:02:06 SSID '\x00'
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Add new id 86 BSSID 00:fe:c8:73:02:01 SSID '\x00'
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 43 BSSID 00:16:a6:1e:e0:a4 SSID '' due to no match in scan
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 56 BSSID 84:b2:61:21:47:5f SSID '\x00' due to no match in scan
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 45 BSSID 84:b2:61:12:64:90 SSID '\x00' due to no match in scan
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: BSS: Remove ID 71 BSSID 00:fe:c8:73:02:00 SSID '\x00' due to no match in scan
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: BSS: last_scan_res_used=43/64
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: Scan-only results received
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: CT,RL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
08-30 12:42:05.751  3152  3152 D wpa_supplicant: wlan0: Radio work 'scan'@0x55834e5710 done in 3.644529 seconds
08-30 12:42:05.761  3152  3152 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-30 12:42:05.761  3152  3152 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 12:42:05.761  3152  3152 D wpa_supplicant: wlan0: Cancelling scan request
08-30 12:42:05.761  3152  3152 D wpa_supplicant: PNO: No configured SSIDs
08-30 12:42:05.761  1134  3050 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 12:42:05.761  3152  3152 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 12:42:05.761  3152  3152 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-30 12:42:05.781  3152  3152 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-30 12:42:05.781  1134  3050 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-30 12:42:05.781  1134  1134 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 14
08-30 12:42:05.781  4470  4470 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 12:42:05.781  4470  5932 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
,08-30 12:42:07.311  7700  8565 I HtcModeClient: handler message = 4011
08-30 12:42:07.311  7700  8565 D HtcModeClient: getConnectionCheckCount first 0
08-30 12:42:07.311  7700  8565 D HtcModeClient: getConnectionCheckCount count = 8
08-30 12:42:07.311  7700  8565 E HtcModeClient: Check connection and retry 9 times.
08-30 12:42:07.311  7700  8565 D HtcModeClient: setConnectionCheckCount count = 9
08-30 12:42:07.311  7700  8565 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 12:42:07.321  7700  7700 D HtcModeClient: setBtPriority priority = on
08-30 12:42:07.321  7700  7700 D HtcModeClient: unbindBlueToothService
08-30 12:42:07.321  7700  7700 D HtcModeClient: Don't start project servcice
,08-30 12:42:07.321  7700  7700 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-30 12:42:07.321  7700  7700 D HtcModeClient: connectState: CONNECTION_READY = false
,08-30 12:42:07.321  7700  7700 D SilentMusic: call stop
08-30 12:42:07.331  7700  7700 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 12:42:07.331  7700  8566 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 12:42:07.341  7700  7700 D HtcModeClient: onDestroy
08-30 12:42:07.341  1134  3361 D Process : killProcessQuiet, pid=7640
08-30 12:42:07.341  1134  3361 I ActivityManager: Killing 7640:com.htc.sdm/u0a61 (adj 15): empty #17
,08-30 12:42:07.341  1134  3361 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-30 12:42:07.501  1134  3808 I ActivityManager: Recipient 7640
,08-30 12:42:10.611  8435  8520 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
08-30 12:42:10.611  8435  8520 I jxcore-log: 
,08-30 12:42:10.621  8435  8520 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
08-30 12:42:10.621  8435  8520 I jxcore-log: 
,08-30 12:42:10.621  5603  5649 D BluetoothAdapterService(1046216240): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@25b698d,
08-30 12:42:10.621  8435  8520 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
,08-30 12:42:10.621  8435  8520 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 12:42:10.621  8435  8520 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 12:42:10.621  8435  8520 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 12:42:10.621  8435  8520 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 12:42:10.621  8435  8520 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 12:42:10.621  8435  8520 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 12:42:10.621  8435  8520 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 12:42:10.631  5603  5649 D BluetoothAdapterService(1046216240): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@25b698d
08-30 12:42:10.631  8435  8520 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-30 12:42:10.631  8435  8520 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
08-30 12:42:10.631  8435  8520 I jxcore-log: 
,08-30 12:42:10.631  8435  8520 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
08-30 12:42:10.631  8435  8520 I jxcore-log: 
,08-30 12:42:11.121  8435  8520 I jxcore-log: Running unit tests,
08-30 12:42:11.121  8435  8520 I jxcore-log: 
08-30 12:42:11.121  8435  8520 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 12:42:11.121  8435  8520 I jxcore-log: Failed to execute UT.
08-30 12:42:11.121  8435  8520 I jxcore-log: 
,08-30 12:42:11.121  8435  8520 I jxcore-log: Unit Test app is loaded,
08-30 12:42:11.121  8435  8520 I jxcore-log: 
,08-30 12:42:11.131  8435  8520 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"},
08-30 12:42:11.131  8435  8520 I jxcore-log: 
,08-30 12:42:11.141  8435  8520 I jxcore-log: My device name is: HTC-HTC One M9
08-30 12:42:11.141  8435  8520 I jxcore-log: 
08-30 12:42:11.141  8435  8435 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 12:42:11.141  8435  8520 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 12:42:11.141  8435  8520 I jxcore-log: 
,08-30 12:42:12.321  1134  3039 D PMS     : acquireWL(1f14796e): PARTIAL_WAKE_LOCK  *alarm* 0x1 1134 1000 WorkSource{10027},
08-30 12:42:12.321  1134  3039 V AlarmManager: sending alarm PendingIntent{11cb680f: PendingIntentRecord{571ced8 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=105491, Int=0
,08-30 12:42:12.331  7700  7700 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 12:42:12.331  7700  7700 D LocalBluetoothProfile: getPriorityOnValue = 100,
08-30 12:42:12.341  1134  1134 D PMS     : releaseWL(1f14796e): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-30 12:42:12.331  7700  7700 D LocalBluetoothProfile: getPriorityOffValue = 0
,08-30 12:42:12.331  7700  7700 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 12:42:12.341  7700  7700 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 12:42:12.361  7700  8569 D HtcModeClient: start the htcmodeservice thread,
,08-30 12:42:12.371  7700  8569 D HtcModeClient: initCanAgent
,08-30 12:42:12.371  7700  8569 I CANMesgAgentLocalSocket: CANAgent Id = 0,
,08-30 12:42:12.371  7700  8569 D HtcModeClient: sense info: version = none, id = 2,
,08-30 12:42:12.371  7700  8569 D HtcModeClient: display info: width = 1080, height = 1776,
08-30 12:42:12.371  7700  8569 D HtcModeClient: display info: mode = 10,
,08-30 12:42:12.471  7700  7700 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
,08-30 12:42:12.471  7700  7700 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 12:42:12.471  7700  7700 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 12:42:12.471  7700  7700 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
,08-30 12:42:12.471  7700  7700 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 12:42:12.471  7700  7700 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 12:42:12.471  7700  7700 D HtcModeClient: connectState: Force_AWAKE = false
08-30 12:42:12.471  7700  7700 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 12:42:12.471  7700  7700 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 12:42:12.491  1134  3802 I art     : Explicit concurrent mark sweep GC freed 32088(1693KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 16MB/24MB, paused 2.377ms total 157.208ms
,08-30 12:42:14.481  7700  8569 I HtcModeClient: handler message = 4011
,08-30 12:42:14.481  7700  8569 D HtcModeClient: getConnectionCheckCount first 0
08-30 12:42:14.481  7700  8569 D HtcModeClient: getConnectionCheckCount count = 9
,08-30 12:42:14.481  7700  8569 E HtcModeClient: Check connection and retry 10 times.
,08-30 12:42:14.481  7700  8569 D HtcModeClient: setConnectionCheckCount count = 10
,08-30 12:42:14.481  7700  8569 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 12:42:14.491  7700  7700 D HtcModeClient: setBtPriority priority = on
08-30 12:42:14.491  7700  7700 D HtcModeClient: unbindBlueToothService
08-30 12:42:14.491  7700  7700 D HtcModeClient: Don't start project servcice
,08-30 12:42:14.491  7700  7700 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 12:42:14.491  7700  7700 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 12:42:14.491  7700  7700 D SilentMusic: call stop
08-30 12:42:14.491  7700  7700 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
,08-30 12:42:14.501  7700  8570 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 12:42:14.501  7700  7700 D HtcModeClient: onDestroy
,08-30 12:42:14.621  8435  8520 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 12:42:14.621  8435  8520 I jxcore-log: 
,08-30 12:42:15.191  8435  8520 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 12:42:15.191  8435  8520 I jxcore-log: 
,08-30 12:42:15.221  8435  8520 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 12:42:15.221  8435  8520 I jxcore-log: 
,08-30 12:42:17.111  8435  8520 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js,
08-30 12:42:17.111  8435  8520 I jxcore-log: 
,08-30 12:42:17.121  1134  3050 D WifiStateMachine: startScan Pid: 1134 Uid -1,
08-30 12:42:17.121  1134  3050 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-30 12:42:17.121  1134  3050 D WifiDisplayAdapter:     Client/Owner: Client
08-30 12:42:17.121  1134  3050 D WifiDisplayAdapter:     GroupId: 
08-30 12:42:17.121  1134  3050 D WifiDisplayAdapter:     Passphrase: 
08-30 12:42:17.121  1134  3050 D WifiDisplayAdapter:     SessionId: 0
08-30 12:42:17.121  1134  3050 D WifiDisplayAdapter:     IP Address: }
08-30 12:42:17.121  3152  3152 D wpa_supplicant: wlan0: Control interface command 'SET pno 0'
08-30 12:42:17.121  3152  3152 D wpa_supplicant: CTRL_IFACE SET 'pno'='0'
08-30 12:42:17.121  3152  3152 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
08-30 12:42:17.121  3152  3152 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
08-30 12:42:17.121  3152  3152 I wpa_supplicant: wpa_supplicant_scan enter
,08-30 12:42:17.121  3152  3152 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-30 12:42:17.121  3152  3152 D wpa_supplicant: wlan0: Add radio work 'scan'@0x55834e5710
08-30 12:42:17.121  3152  3152 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-30 12:42:17.121  3152  3152 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x55834e5710 after 0.000026 second wait
08-30 12:42:17.121  3152  3152 D wpa_supplicant: wlan0: nl80211: scan request
,08-30 12:42:17.161  3152  3152 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-30 12:42:17.161  3152  3152 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
08-30 12:42:17.161  3152  3152 D wpa_supplicant: wlan0: nl80211: Scan trigger
,08-30 12:42:17.161  3152  3152 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
08-30 12:42:17.161  3152  3152 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000145 seconds
08-30 12:42:17.161  3152  3152 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 12:42:17.161  3152  3152 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1134-2\x00
,08-30 12:42:17.451  8435  8520 I jxcore-log: ERROR runTests: ,
08-30 12:42:17.451  8435  8520 I jxcore-log: 
,08-30 12:42:17.461  8435  8520 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger',
08-30 12:42:17.461  8435  8520 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 12:42:17.461  8435  8520 I jxcore-log: WARN testUtils: logCallback not set!,
08-30 12:42:17.461  8435  8520 I jxcore-log: 
,08-30 12:42:17.481  8435  8520 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _functionName: 'loadFile',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _lineNumber: '26',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _columnNumber: '11',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 12:42:17.481  8435  8520 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _functionName: '',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _lineNumber: '38',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _columnNumber: '7',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },,
08-30 12:42:17.481  8435  8520 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _functionName: '',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _lineNumber: '35',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _columnNumber: '3',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 12:42:17.481  8435  8520 I jxcore-log:   { _fileName: 'module.js',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _lineNumber: '621',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _columnNumber: '8',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 12:42:17.481  8435  8520 I jxcore-log:   { _fileName: 'module.js',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _lineNumber: '651',
08-30 12:42:17.481  8435  8520 I jxcore-log:     _columnNumber: '1',
08-30 12:42:17.481  8435  8520 I jxcore-log:    
08-30 12:42:17.481  8435  8520 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 12:42:17.481  8435  8520 I jxcore-log: 
08-30 12:42:17.481  8435  8520 E jxcore-log: Error: 
08-30 12:42:17.481  8435  8520 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 12:42:17.481  8435  8520 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 12:42:17.481  8435  8520 E jxcore-log: 
,08-30 12:42:17.711  8574  8574 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-30 12:42:17.711  8574  8574 W HTCLOG  : mask=0x18
,08-30 12:42:17.871  8574  8577 W HTCLOG  : use specified tag [cutils-trace], func [0].,
08-30 12:42:17.871  8574  8577 W HTCLOG  : mask=0x18
08-30 12:42:17.881  8574  8577 E cutils-trace: Error opening trace file: Permission denied (13)
,08-30 12:42:17.931  8574  8574 D CustomizationManager: ====startRecUseTime====
08-30 12:42:17.931  8574  8574 D htc.customization.log.level:  is 
08-30 12:42:17.931  8574  8574 W CustomizationLogLevel: Level value is invalid, use default level 2,
,08-30 12:42:18.011  8574  8574 D CustomizationManager:  Read ACC file spent 0.040 (s)
,08-30 12:42:18.021  8574  8574 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
,08-30 12:42:18.021  8574  8574 I CustomizationCIDLoader: Parsing tag category name = application
08-30 12:42:18.021  8574  8574 I CustomizationCIDLoader: Parsing tag category name = system
,08-30 12:42:18.021  8574  8574 I CustomizationCIDLoader: Parsing tag category name = Settings
08-30 12:42:18.021  8574  8574 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-30 12:42:18.021  8574  8574 I CustomizationCIDLoader: Parsing tag category name = ACC,
,08-30 12:42:18.021  8574  8574 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240,
08-30 12:42:18.021  8574  8574 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000,
08-30 12:42:18.021  8574  8574 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-30 12:42:18.021  8574  8574 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider,
08-30 12:42:18.021  8574  8574 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-30 12:42:18.031  8574  8574 D CustomizationManager:  Read CID file spent 0.093 (s)
08-30 12:42:18.031  8574  8574 D CustomizationManager:  All configurations done spent 0.093 (s)
,08-30 12:42:18.071  1134  3090 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8574, uid=2000,
,08-30 12:42:18.081  1134  1164 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
08-30 12:42:18.081  1134  1164 D Process : killProcessQuiet, pid=8435
,08-30 12:42:18.081  1134  1164 I ActivityManager: Killing 8435:com.test.thalitest/u0a142 (adj 0): stop com.test.thalitest
08-30 12:42:18.081  1134  1164 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 ,
,08-30 12:42:18.161   529   529 W HTCLOG  : use specified tag [Vector], func [0].
08-30 12:42:18.161   529   529 W HTCLOG  : mask=0x18
,08-30 12:42:18.171  1134  3639 I ActivityManager: Recipient 8435
08-30 12:42:18.171  1134  3551 I WindowState: WIN DEATH: Window{24f3b0b0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 12:42:18.171  1134  3082 D WifiService: Client connection lost with reason: 4
,08-30 12:42:18.181  1134  1164 I ActivityManager:   Force finishing activity 3 ActivityRecord{ef9145a u0 com.test.thalitest/.MainActivity t451}
,08-30 12:42:18.191  1134  3639 W ActivityManager: Spurious death for ProcessRecord{16dd734 8435:com.test.thalitest/u0a142}, curProc for 8435: null
08-30 12:42:18.191  1134  1183 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed
,08-30 12:42:18.211  1134  3042 W SystemReader: Cannot find grip_rejection_width, use default value instead
08-30 12:42:18.211  1134  3160 D TaskPersister: removeObsoleteFile: deleting file=451_task.xml
,08-30 12:42:18.211  3315  3315 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
,08-30 12:42:18.221  1134  3047 D PMS     : acquireWL(1446a2d2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1134 1000 null
08-30 12:42:18.211  3315  3315 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
08-30 12:42:18.221  1134  3048 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
08-30 12:42:18.221  1134  3347 D PMS     : acquireWL(281b7fa3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4470 10019 null
,08-30 12:42:18.231  4470  4818 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 12:42:18.231  1134  3806 D PMS     : releaseWL(281b7fa3): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
,08-30 12:42:18.241  3720  4143 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
08-30 12:42:18.241  1134  3047 D PMS     : releaseWL(1446a2d2): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
08-30 12:42:18.251  3720  4143 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
08-30 12:42:18.241  1134  3048 V NetworkPolicy: writePolicyLocked()
08-30 12:42:18.251  3553  3553 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
08-30 12:42:18.251  3720  4143 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
08-30 12:42:18.261  3720  4143 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
08-30 12:42:18.261  3574  3574 I art     : Explicit concurrent mark sweep GC freed 309(25KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 20MB/33MB, paused 1.089ms total 58.552ms
08-30 12:42:18.261  4279  4279 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-30 12:42:18.271  1134  3808 D PMS     : acquireWL(6c81a1e): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4279 10019 null
,08-30 12:42:18.271  3763  8591 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 12:42:18.271  3720  4143 E ExternalAccountType: Unsupported attribute readOnly
,08-30 12:42:18.271  4011  4011 I ConfigService: onCreate
,08-30 12:42:18.271  4011  4011 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-30 12:42:18.281  4279  4279 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-30 12:42:18.281  1134  3048 D NetworkPolicy: notifyPoliciesChangeLocked: no change
08-30 12:42:18.281  1134  3048 V NetworkPolicy: updateNetworkEnabledLocked()
08-30 12:42:18.281  1134  3048 V NetworkPolicy: updateNotificationsLocked()
08-30 12:42:18.281  6617  6617 I art     : Explicit concurrent mark sweep GC freed 12312(760KB) AllocSpace objects, 2(48KB) LOS objects, 34% free, 3MB/5MB, paused 446us total 67.172ms
,08-30 12:42:18.291  4011  4011 I ConfigService: onBind returning update interface
,08-30 12:42:18.291  4011  4011 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 12:42:18.291  4011  4011 I ConfigService: onBind returning config service
,08-30 12:42:18.311  1134  3551 I ActivityManager: Start proc 8593:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver
,08-30 12:42:18.321  8593  8593 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:18.321  8593  8593 W HTCLOG  : mask=0x18
08-30 12:42:18.321  1134  1154 D PMS     : acquireWL(457c2f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 4011 10019 null
,08-30 12:42:18.331  1134  3361 D PMS     : releaseWL(457c2f7): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null
08-30 12:42:18.331  4011  4011 I ConfigService: onDestroy
,08-30 12:42:18.341  1134  3039 D PMS     : acquireWL(1ed96482): PARTIAL_WAKE_LOCK  *alarm* 0x1 1134 1000 WorkSource{10027}
,08-30 12:42:18.341  1134  3039 V AlarmManager: sending alarm PendingIntent{1dbb9793: PendingIntentRecord{571ced8 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=112663, Int=0
08-30 12:42:18.341  1134  3039 V AlarmManager: sending alarm PendingIntent{217f4834: PendingIntentRecord{1769c65d android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=113506, Int=0
,08-30 12:42:18.351  1134  1163 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
,08-30 12:42:18.361  1134  1163 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
08-30 12:42:18.361  8593  8593 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-30 12:42:18.361  8593  8593 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-30 12:42:18.381  8593  8593 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:42:18.381  8593  8593 I MultiDex: install
08-30 12:42:18.381  8593  8593 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 12:42:18.381  3574  3574 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
08-30 12:42:18.381  3574  3574 I ThreadedRenderer: Defer allocateBuffers to drawing time
,08-30 12:42:18.391  8593  8593 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-30 12:42:18.401  8593  8593 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-30 12:42:18.411  1134  3551 D Process : killProcessQuiet, pid=7821,
08-30 12:42:18.411  1134  3551 I ActivityManager: Killing 7821:com.google.android.gm/u0a97 (adj 15): empty #17
,08-30 12:42:18.411  1134  1183 I art     : Explicit concurrent mark sweep GC freed 22344(1612KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 15MB/23MB, paused 1.861ms total 214.975ms
08-30 12:42:18.411  1134  3551 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-30 12:42:18.411  1134  1134 I art     : WaitForGcToComplete blocked for 212.172ms for cause Explicit
,08-30 12:42:18.441  8574  8574 I art     : System.exit called, status: 0
08-30 12:42:18.441  8574  8574 W HTCLOG  : use specified tag [Vector], func [0].
08-30 12:42:18.441  8574  8574 W HTCLOG  : mask=0x18
,08-30 12:42:18.501  1134  3090 I ActivityManager: Recipient 7821
,08-30 12:42:18.531  3574  3944 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
08-30 12:42:18.531  3574  3944 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
08-30 12:42:18.531  3471  3471 D Nfc-Utils: isNxpCodebase: isNxp=false
08-30 12:42:18.531  4279  8621 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-30 12:42:18.531  4279  8621 D AccountUtils: Clearing selected account for com.test.thalitest
,08-30 12:42:18.541  3574  3574 I Launcher: Deferring update until onResume
08-30 12:42:18.541  3574  3574 D Launcher: waitUntilResume // bindAppsRemoved
,08-30 12:42:18.551  1134  3551 I ActivityManager: Start proc 8623:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver,
,08-30 12:42:18.551  8623  8623 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:18.551  8623  8623 W HTCLOG  : mask=0x18
,08-30 12:42:18.571  1134  1134 I art     : Explicit concurrent mark sweep GC freed 3042(131KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 2.091ms total 158.735ms,
,08-30 12:42:18.601  1134  3639 D Process : killProcessQuiet, pid=7491,
08-30 12:42:18.601  1134  3639 I ActivityManager: Killing 7491:com.google.android.music:main/u0a115 (adj 15): empty #17
08-30 12:42:18.601  1134  3639 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 ,
,08-30 12:42:18.661  1134  1134 W PackageManager: Unable to load service info ResolveInfo{efb945 com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000}
08-30 12:42:18.661  1134  1134 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
08-30 12:42:18.661  1134  1134 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:18.661  1134  1134 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 12:42:18.671  1134  3551 I ActivityManager: Recipient 7491
08-30 12:42:18.671  1134  1154 D MediaRouterService: Client com.google.android.music (pid 7491): Died!
,08-30 12:42:18.711  3720  3720 E PackageActionReceiver: ACTION_PACKAGE_REMOVED,
,08-30 12:42:18.721  3643  8648 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest,
,08-30 12:42:18.731  3643  8648 E SQLiteLog: (3850) statement aborts at 41: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
08-30 12:42:18.731  3643  8648 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
,08-30 12:42:18.731  3643  8648 W HTCLOG  : mask=0x18
08-30 12:42:18.731  3643  8648 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.sense.hsp/databases/registry.db, handle: 0x558db30250
,08-30 12:42:18.731  4279  8647 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/metrics.db'.
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.,
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.d.a(SourceFile:56)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.a.b(SourceFile:49)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.d.d.a(SourceFile:146)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:18.731  4279  8647 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:18.731  1134  1134 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.d.a(SourceFile:56)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: ,	at com.google.android.gms.googlehelp.d.a.b(SourceFile:49)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.d.d.a(SourceFile:146)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:18.731  4279  8647 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: provider may killed!
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source),
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:18.731  3643  8648 W [PluginManager]RegisterService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:18.731  4279  8647 W SQLiteOpenHelper: Opened metrics.db in read-only mode
08-30 12:42:18.731  4279  8647 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
08-30 12:42:18.741  4279  8647 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 12:42:18.741  4279  8647 W HTCLOG  : mask=0x18
08-30 12:42:18.741  4279  8647 E AndroidRuntime: FATAL EXCEPTION: IntentService[ClearHelpHistoryIntentService]
08-30 12:42:18.741  4279  8647 E AndroidRuntime: Process: com.google.android.gms, PID: 4279
08-30 12:42:18.741  4279  8647 E AndroidRuntime: android.database.sqlite.SQLiteReadOnlyDatabaseException: attempt to write a readonly database (code 8)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	at com.google.android.gms.googlehelp.d.d.a(SourceFile:149)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:47)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	,at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:18.741  4279  8647 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:18.741  1134  3090 E ActivityManager: App crashed! Process: com.google.android.gms
08-30 12:42:18.741  3574  3574 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
08-30 12:42:18.741  3574  3574 I ContextualWidget: package com.test.thalitest removed
08-30 12:42:18.741  3643  8648 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed
08-30 12:42:18.741  3574  3993 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
08-30 12:42:18.741  4279  8647 D Process : killProcess, pid=4279
,08-30 12:42:18.751  4279  8647 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
08-30 12:42:18.751  4279  8647 W HTCLOG  : use specified tag [Process], func [0].
,08-30 12:42:18.751  1134  8653 E DropBoxManagerService: Can't write: system_app_crash
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:18.751  1134  8653 E DropBoxManagerService: 	... 5 more
08-30 12:42:18.751  4279  8647 W HTCLOG  : mask=0x18
,08-30 12:42:18.751  7996  8651 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
,08-30 12:42:18.761  3574  8654 I ContextualWidget: com.test.thalitest is not installed
08-30 12:42:18.761  3574  8654 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
08-30 12:42:18.761  3574  8654 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
08-30 12:42:18.761  3574  8654 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 12:42:18.761  3574  8654 W HTCLOG  : mask=0x18
08-30 12:42:18.761  3574  8654 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xabeef130
08-30 12:42:18.761  3574  8654 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
08-30 12:42:18.761  3574  8654 E AndroidRuntime: Process: com.htc.launcher, PID: 3574
08-30 12:42:18.761  3574  8654 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.removeItemsFromDownloadListIfNeed(MFUDataManager.java:2133)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageRemoved(HtcContextualWidgetService.java:277)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:184)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:18.761  3574  8654 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:18.761  1134  4759 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 12:42:18.771  1134  4759 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,08-30 12:42:18.781  1134  4759 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system),
,08-30 12:42:18.781  1134  4759 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:18.781  1134  4759 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:18.781  1134  3806 I ActivityManager: Start proc 8655:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
08-30 12:42:18.781  1134  4759 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
,08-30 12:42:18.781  1134  4759 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
,08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302),
08-30 12:42:18.781  1134  4759 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:18.781  1134  8669 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 12:42:18.781  1134  8669 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472553738790.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 12:42:18.781  1134  8669 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:18.781  1134  8669 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:18.781  1134  8669 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:42:18.781  1134  8669 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 12:42:18.781  1134  8669 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
,08-30 12:42:18.781  1134  8669 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:18.781  1134  8669 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:18.781  1134  8669 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:18.781  1134  8669 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:18.781  1134  8669 E ErrorReport: 	... 4 more
,08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
,08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
,08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:18.781  1134  4759 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:18.781  1134  4759 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:18.781  1134  4759 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:18.781  1134  4759 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:18.781  1134  4759 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:18.781  1134  4759 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:18.781  1134  4759 W System.err: 	... 14 more
08-30 12:42:18.781  1134  4759 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:18.781  1134  4759 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:18.781  1134  4759 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:18.781  1134  4759 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:18.781  1134  4759 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238),
08-30 12:42:18.781  1134  4759 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:18.781  1134  4759 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:18.781  1134  4759 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:18.781  1134  4759 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:18.781  1134  4759 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:18.781  1134  4759 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:18.781  1134  4759 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:18.781  1134  4759 W System.err: 	... 14 more
08-30 12:42:18.781  8655  8655 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:18.781  8655  8655 W HTCLOG  : mask=0x18
08-30 12:42:18.791  3574  3574 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@23cf658e for type 0
08-30 12:42:18.791  3574  8654 D Process : killProcess, pid=3574
08-30 12:42:18.791  3574  3574 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@23cf658e for type 1
08-30 12:42:18.791  3574  3574 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@23cf658e for type 3
08-30 12:42:18.791  3574  3574 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@23cf658e for type 2
08-30 12:42:18.791  3574  8654 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 12:42:18.791  3574  8654 W HTCLOG  : use specified tag [Process], func [0].
08-30 12:42:18.791  3574  8654 W HTCLOG  : mask=0x18
08-30 12:42:18.791  1134  3635 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 12:42:18.791  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:18.791  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:18.791  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:18.791  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:18.791  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 12:42:18.791  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 12:42:18.791  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 12:42:18.791  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 12:42:18.791  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 12:42:18.791  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 12:42:18.791  1134  3635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:18.791  1134  3635 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:18.791  1134  3635 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 12:42:18.791  1134  3635 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:18.791  1134  3635 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:18.791  1134  3635 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:18.791  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:18.791  1134  3635 W System.err: 	... 12 more
08-30 12:42:18.801  1134  3808 I ActivityManager: Recipient 4279
08-30 12:42:18.801  1134  3361 D PMS     : handleWLDeath(6c81a1e): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
08-30 12:42:18.801  1134  3551 D PMS     : handleWLDeath(73e1b0d): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
,08-30 12:42:18.801  1134  3808 I ActivityManager: Process com.google.android.gms (pid 4279) has died
08-30 12:42:18.801  1134  3808 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.icing.service.IndexWorkerService in 1000ms
08-30 12:42:18.801  1134  3808 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.people.service.bg.PeopleBackgroundTasks in 11000ms
08-30 12:42:18.801  1134  3808 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 21000ms
08-30 12:42:18.801  1134  3808 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 21000ms
08-30 12:42:18.801  1134  3808 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 21000ms
08-30 12:42:18.801  1134  3808 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 21000ms
,08-30 12:42:18.811  1134  3808 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
,08-30 12:42:18.811   493   493 E lowmemorykiller: Error writing /proc/3574/oom_score_adj; errno=22
08-30 12:42:18.811  1134  3808 V WindowManager: addAppToken: AppWindowToken{50596e4 token=Token{1bf37a77 ActivityRecord{26f13476 u0 com.htc.launcher/.Launcher t452}}} to stack=0 task=452 at 0
,08-30 12:42:18.861  1134  3090 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/
08-30 12:42:18.861  8655  8655 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
,08-30 12:42:18.871  8655  8655 D IdefixUninstallListener: package_removed = com.test.thalitest,
,08-30 12:42:18.871  1134  1153 I ActivityManager: Recipient 3574
08-30 12:42:18.871  1134  3347 I WindowState: WIN DEATH: Window{160d72f9 u0 com.htc.launcher/com.htc.launcher.Launcher}
,08-30 12:42:18.881  1134  1153 I ActivityManager: Process com.htc.launcher (pid 3574) has died
08-30 12:42:18.881  1134  1153 W ActivityManager: Scheduling restart of crashed service com.htc.launcher/.htcwidget.HtcContextualWidgetService in 30925ms
,08-30 12:42:18.901  1134  1153 I ActivityManager: Start proc 8680:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
08-30 12:42:18.901  1134  3635 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,08-30 12:42:18.901  8655  8655 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
08-30 12:42:18.901  8655  8655 W HTCLOG  : mask=0x18
,08-30 12:42:18.901  8655  8655 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.,
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:18.901  8655  8655 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:18.901  8655  8655 W System.err: java.sql.SQLException: Getting a writable database from helper a@21e623db failed
08-30 12:42:18.901  1134  3806 I ActivityManager: Killing 8047:com.htc.mob,iledata:remote/u0a40 (adj 15): empty #17
08-30 12:42:18.901  8655  8655 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
08-30 12:42:18.901  8655  8655 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
08-30 12:42:18.901  8655  8655 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-30 12:42:18.901  8655  8655 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-30 12:42:18.901  8655  8655 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-30 12:42:18.901  8655  8655 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-30 12:42:18.901  8655  8655 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:18.901  8655  8655 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:18.901  8655  8655 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:18.901  8655  8655 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:18.901  8655  8655 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:18.901  8655  8655 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:18.901  8655  8655 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:18.901  8655  8655 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-30 12:42:18.901  8655  8655 W System.err: 	... 15 more
08-30 12:42:18.901  8680  8680 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:18.901  1134  3806 D Process : killProcessQuiet, pid=8047
08-30 12:42:18.901  8680  8680 W HTCLOG  : mask=0x18
08-30 12:42:18.901  1134  3806 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,08-30 12:42:18.991  1134  4765 I ActivityManager: Recipient 8047,
,08-30 12:42:19.041  6617  8701 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-30 12:42:19.061  1134  1153 I ActivityManager: Start proc 8702:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver,
,08-30 12:42:19.061  8680  8680 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:42:19.061  8680  8680 I MultiDex: install
08-30 12:42:19.061  8680  8680 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 12:42:19.061  8702  8702 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:19.061  8702  8702 W HTCLOG  : mask=0x18
,08-30 12:42:19.071  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-30 12:42:19.071  8680  8680 D FaceDetectTask: checkIsOmronEnable start
08-30 12:42:19.071  8680  8680 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
,08-30 12:42:19.081  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 12:42:19.081  8680  8680 D FaceDetectTask: IsOmronEnable : true
08-30 12:42:19.081  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask,
08-30 12:42:19.081  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : null,
08-30 12:42:19.081  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 12:42:19.081  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 12:42:19.081  6617  8701 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 12:42:19.081  6617  8701 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 12:42:19.081  6617  8701 W HTCLOG  : mask=0x18
08-30 12:42:19.081  6617  8701 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x558dad2c80
08-30 12:42:19.081  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.081  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.081  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.081  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.081  8680  8680 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.091  8680  8680 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
,08-30 12:42:19.091  8680  8680 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,08-30 12:42:19.091  8680  8680 W HTCLOG  : mask=0x18
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.,
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752),
,08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	,at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: ,	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.091  8680  8680 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.091  8702  8702 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 
08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.101  1134  3090 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
,08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.091  8680  8680 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 12:42:19.091  8680  8680 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.091  8680  8680 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.091  8680  8680 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.091  8680  8680 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.091  8680  8680 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.091  8680  8680 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLi,teDatabase.java:854)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.091  8680  8680 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: FATAL EXCEPTION: main
08-30 12:42:19.091  8680  8680 E AndroidRuntime: Process: com.htc.launcher, PID: 8680
08-30 12:42:19.091  8680  8680 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:,19.091  8680  8680 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.091  8680  8680 E AndroidRuntime: 	... 11 more
08-30 12:42:19.101  1134  3090 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 12:42:19.101  1134  3090 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 12:42:19.101  1134  8733 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 12:42:19.101  1134  8733 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472553739109.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 12:42:19.101  1134  8733 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.101  1134  8733 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.101  1134  8733 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:42:19.101  1134  8733 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 12:42:19.101  1134  8733 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:42:19.101  1134  8733 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.101  1134  8733 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.101  1134  8733 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.101  1134  8733 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.101  1134  8733 E ErrorReport: 	... 4 more
08-30 12:42:19.101  1134  3090 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.111  1134  3363 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 12:42:19.101  1134  3090 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.111  1134  1153 D PMS     : acquireWL(32f73d50): PARTIAL_WAKE_LOCK  AsyncService 0x1 8492 10128 null
08-30 12:42:19.101  1134  3090 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.101  1134  3090 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.101  1134  3090 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.101  1134  3090 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.101  1134  3090 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.101  1134  3090 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.101  1134  3090 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.101  1134  3090 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.101  1134  3090 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.101  1134  3090 W System.err: 	... 14 more
08-30 12:42:19.101  1134  3090 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.101  1134  3090 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.101  1134  3090 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.101  1134  3090 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.101  1134  3090 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.121  1134  3361 D PMS     : releaseWL(32f73d50): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-30 12:42:19.101  1134  3090 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.101  1134  3090 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.101  1134  3090 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.101  1134  3090 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.101  1134  3090 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.101  1134  3090 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.101  1134  3090 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.101  1134  3090 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.101  1134  3090 W System.err: 	... 14 more
08-30 12:42:19.101  8680  8680 D Process : killProcess, pid=8680
08-30 12:42:19.101  8680  8680 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 12:42:19.101  8680  8680 W HTCLOG  : use specified tag [Process], func [0].
08-30 12:42:19.101  8680  8680 W HTCLOG  : mask=0x18
08-30 12:42:19.111  1134  3635 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.111  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.111  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.111  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.111  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.111  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 12:42:19.111  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 12:42:19.111  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 12:42:19.121  1134  8735 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 12:42:19.121  1134  8735 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472553739125.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 12:42:19.121  1134  8735 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.121  1134  8735 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.121  1134  8735 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:42:19.121  1134  8735 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 12:42:19.121  1134  8735 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:42:19.121  1134  8735 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.121  1134  8735 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.121  1134  8735 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.121  1134  8735 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.121  1134  8735 E ErrorReport: 	... 4 more
08-30 12:42:19.111  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 12:42:19.111  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 12:42:19.111  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 12:42:19.111  1134  3635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.111  1134  3635 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.111  1134  3635 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.111  1134  3635 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.111  1134  3635 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.111  1134  3635 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.111  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.111  1134  3635 W System.err: 	... 12 more
08-30 12:42:19.111  8702  8732 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 12:42:19.111  8702  8732 W HTCLOG  : mask=0x18
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.111  8702  8732 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-30 12:42:19.111  8702  8732 E AndroidRuntime: Process: com.android.keychain, PID: 8702
08-30 12:42:19.111  8702  8732 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.111  8702  8732 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.111  1134  3363 E ActivityManager: App crashed! Process: com.android.keychain
08-30 12:42:19.111  1134  3363 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.111  1134  3363 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.111  1134  3363 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.111  1134  3363 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.111  1134  3363 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.111  1134  3363 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.111  1134  3363 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.111  1134  3363 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.111  1134  3363 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.111  1134  3363 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.111  1134  3363 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.111  1134  3363 W System.err: 	... 14 more
08-30 12:42:19.111  1134  3363 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.111  1134  3363 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.111  1134  3363 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.111  1134  3363 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.111  1134  3363 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.111  8369  8369 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.111  1134  3363 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.111  1134  3363 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.111  1134  3363 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.121  1134  3363 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.121  1134  3363 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.121  1134  3363 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.121  1134  3363 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.121  1134  3363 W System.err: 	... 14 more
08-30 12:42:19.121  8369  8369 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
08-30 12:42:19.121  1134  3635 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.121  6617  8701 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-30 12:42:19.121  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.121  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.121  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.121  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.121  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 12:42:19.121  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 12:42:19.121  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 12:42:19.121  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 12:42:19.121  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 12:42:19.121  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 12:42:19.121  1134  3635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.121  1134  3635 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.121  1134  3635 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.121  1134  3635 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.121  1134  3635 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.121  1134  3635 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.121  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.121  1134  3635 W System.err: 	... 12 more
08-30 12:42:19.121  8369  8369 I DeviceManagement: WorkflowService: Starting workflow service
08-30 12:42:19.121  6617  8701 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-30 12:42:19.121  6617  8701 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6617
08-30 12:42:19.121  6617  8701 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at, com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.121  6617  8701 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.121  8369  8736 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@39d2e9eb] args=[Bundle[mParcelledData.dataSize=112]]
08-30 12:42:19.131  1134  3552 I ActivityManager: Recipient 8680
08-30 12:42:19.121  83,69  8736 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-30 12:42:19.131  1134  3347 I ActivityManager: Start proc 8737:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
08-30 12:42:19.121  8369  8736 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
08-30 12:42:19.121  8369  8736 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-30 12:42:19.131  8369  8736 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
08-30 12:42:19.131  1134  3090 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
08-30 12:42:19.141  8737  8737 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:19.141  8737  8737 W HTCLOG  : mask=0x18
08-30 12:42:19.161  8369  8736 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
08-30 12:42:19.161  8369  8758 I DeviceManagement: SessionStateController: Checking invariants...
,08-30 12:42:19.271  8369  8758 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
08-30 12:42:19.271  8369  8758 W HTCLOG  : mask=0x18
,08-30 12:42:19.271  8369  8758 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.,
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: ,	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121),
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: ,	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
,08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-30 12:42:19.271  8369  8758 E SQLiteDatabase: 	,at java.lang.Thread.run(Thread.java:818)
,08-30 12:42:19.341  1134  3552 I ActivityManager: Process com.htc.launcher (pid 8680) has died
08-30 12:42:19.351  1134  3552 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-30 12:42:19.351  1134  3552 V WindowManager: addAppToken: AppWindowToken{301ade7c token=Token{30e9416f ActivityRecord{22c65c4e u0 com.htc.launcher/.Launcher t453}}} to stack=0 task=453 at 0
,08-30 12:42:19.371  1134  3552 I ActivityManager: Start proc 8760:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-30 12:42:19.381  1134  3635 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true,
08-30 12:42:19.381  8702  8732 D Process : killProcess, pid=8702
08-30 12:42:19.381  8702  8732 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 12:42:19.381  8702  8732 W HTCLOG  : use specified tag [Process], func [0].
08-30 12:42:19.381  8702  8732 W HTCLOG  : mask=0x18
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: Can't write: system_app_crash
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.391  1134  8773 E DropBoxManagerService: 	... 5 more
08-30 12:42:19.391  6617  8701 D Process : killProcess, pid=6617
08-30 12:42:19.391  8760  8760 W HTCLOG  : use specified tag [FDManager], func [0].
,08-30 12:42:19.391  8760  8760 W HTCLOG  : mask=0x18
08-30 12:42:19.391  8369  8758 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.401  8369  8736 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.401  8369  8736 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
08-30 12:42:19.401  6617  8701 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
08-30 12:42:19.401  6617  8701 W HTCLOG  : use specified tag [Process], func [0].
08-30 12:42:19.401  6617  8701 W HTCLOG  : mask=0x18
,08-30 12:42:19.411  8369  8736 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowServic,e.onHandleIntent(WorkflowService.java:295)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.411  8369  8736 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.411  8369  8736 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@39d2e9eb]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundControlle,r.java:657)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.411  8369  8736 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.421  1134  3806 I ActivityManager: Recipient 6617
08-30 12:42:19.421  1134  3082 D WifiService: Client connection lost with reason: 4
08-30 12:42:19.441  8760  8760 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:42:19.441  8760  8760 I MultiDex: install
08-30 12:42:19.441  8760  8760 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 12:42:19.451  1134  3347 I ActivityManager: Recipient 8702
,08-30 12:42:19.451  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 12:42:19.461  1134  3806 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6617) has died
08-30 12:42:19.451  8760  8760 D FaceDetectTask: checkIsOmronEnable start
08-30 12:42:19.461  1134  3806 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 30348ms
08-30 12:42:19.461  8760  8760 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
08-30 12:42:19.461  1134  3806 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 40348ms
08-30 12:42:19.461  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.461  8760  8760 D FaceDetectTask: IsOmronEnable : true
08-30 12:42:19.461  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.461  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 12:42:19.461  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.461  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.461  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.461  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 12:42:19.461  8369  8369 I DeviceManagement: WorkflowService: Stopping workflow service
08-30 12:42:19.461  1134  3347 I ActivityManager: Process com.android.keychain (pid 8702) has died
08-30 12:42:19.461  1134  3347 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 40343ms
,08-30 12:42:19.461  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 12:42:19.461  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.461  8760  8760 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 12:42:19.471  8760  8760 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
,08-30 12:42:19.471  8760  8760 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
,08-30 12:42:19.471  8760  8760 W HTCLOG  : mask=0x18
,08-30 12:42:19.471  8760  8760 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
,08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.471  8760  8760 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.481  1134  3639 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.471  8760  8760 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 12:42:19.471  8760  8760 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.471  8760  8760 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.471  8760  8760 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.471  8760  8760 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.471  8760  8760 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.471  8760  8760 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.471  8760  8760 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: FATAL EXCEPTION: main
08-30 12:42:19.481  8760  8760 E AndroidRuntime: Process: com.htc.launcher, PID: 8760
08-30 12:42:19.481  8760  8760 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.481  8760  8760 E AndroidRuntime: 	... 11 more
08-30 12:42:19.481  1134  3639 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 12:42:19.481  1134  3639 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 12:42:19.481  1134  8791 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 12:42:19.481  1134  8791 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472553739489.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 12:42:19.481  1134  8791 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.481  1134  8791 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.481  1134  8791 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:42:19.481  1134  8791 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 12:42:19.481  1134  8791 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:42:19.481  1134  8791 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.481  1134  8791 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.481  1134  8791 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.481  1134  8791 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.481  1134  8791 E ErrorReport: 	... 4 more
08-30 12:42:19.481  1134  3639 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.491  1134  3806 I ActivityManager: Killing 7733:com.htc.mobiledata/u0a40 (adj 15): empty #17
08-30 12:42:19.481  1134  3639 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.481  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.481  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.481  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.481  1134  3639 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.481  1134  3639 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.481  1134  3639 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.481  1134  3639 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.481  1134  3639 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.481  1134  3639 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.481  1134  3639 W System.err: 	... 14 more
08-30 12:42:19.481  1134  3639 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.481  1134  3639 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.481  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.481  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.481  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.481  1134  3639 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.481  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.481  1134  3639 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.481  1134  3639 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.481  1134  3639 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.481  1134  3639 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.481  1134  3639 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.481  1134  3639 W System.err: 	... 14 more
08-30 12:42:19.481  8760  8760 D Process : killProcess, pid=8760
08-30 12:42:19.481  1134  3635 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.481  8760  8760 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 12:42:19.481  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.481  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.481  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.481  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.481  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 12:42:19.481  8760  8760 W HTCLOG  : use specified tag [Process], func [0].
08-30 12:42:19.481  8760  8760 W HTCLOG  : mask=0x18
08-30 12:42:19.481  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 12:42:19.481  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 12:42:19.481  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 12:42:19.481  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 12:42:19.481  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 12:42:19.481  1134  3635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.481  1134  3635 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.481  1134  3635 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.481  1134  3635 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.481  1134  3635 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.481  1134  3635 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.491  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.491  1134  3635 W System.err: 	... 12 more
08-30 12:42:19.491  8737  8737 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 12:42:19.491  8737  8737 W HTCLOG  : mask=0x18
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.491  8737  8737 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 12:42:19.491  8737  8737 E AndroidRuntime: FATAL EXCEPTION: main
08-30 12:42:19.491  8737  8737 E AndroidRuntime: Process: com.android.documentsui, PID: 8737
08-30 12:42:19.491  8737  8737 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 12:42:19.491  8737  8737 E AndroidRuntime: 	... 9 more
08-30 12:42:19.491  1134  3806 D Process : killProcessQuiet, pid=7733
08-30 12:42:19.491  1134  3806 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-30 12:42:19.541  1134  3347 I ActivityManager: Recipient 8760
,08-30 12:42:19.581  1134  3361 I ActivityManager: Recipient 7733,
,08-30 12:42:19.601  1134  1154 E ActivityManager: App crashed! Process: com.android.documentsui,
,08-30 12:42:19.601  1134  1154 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox,
08-30 12:42:19.611  1134  1154 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,08-30 12:42:19.611  1134  1154 W System.err: ,	at libcore.io.IoBridge.open(IoBridge.java:456)
,08-30 12:42:19.611  1134  1154 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.621  1134  3361 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-30 12:42:19.611  1134  1154 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.631  1134  3361 V WindowManager: addAppToken: AppWindowToken{167d0fb2 token=Token{3cd93dbd ActivityRecord{3d6e8114 u0 com.htc.launcher/.Launcher t454}}} to stack=0 task=454 at 0
08-30 12:42:19.611  1134  1154 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.631  1134  3347 I ActivityManager: Process com.htc.launcher (pid 8760) has died
08-30 12:42:19.611  1134  1154 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.611  1134  1154 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.651  1134  3347 I ActivityManager: Start proc 8792:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
08-30 12:42:19.611  1134  1154 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.611  1134  1154 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.611  1134  1154 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.611  1134  1154 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.611  1134  1154 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.611  1134  1154 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.611  1134  1154 W System.err: 	... 14 more
08-30 12:42:19.611  5681  5868 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
08-30 12:42:19.611  5681  5868 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 12:42:19.611  5681  5868 W HTCLOG  : mask=0x18
08-30 12:42:19.611  5681  5868 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x558da7ae40
08-30 12:42:19.611  1134  1154 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.611  1134  1154 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.611  1134  1154 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.611  1134  1154 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.611  1134  1154 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.611  1134  1154 W System.err: 	at com,.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 12:42:19.611  1134  1154 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.621  1134  1154 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.621  1134  1154 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.621  1134  1154 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.621  1134  1154 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.621  1134  1154 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.621  1134  1154 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.621  1134  1154 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.651  1134  3808 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 12:42:19.621  1134  1154 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.621  1134  1154 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.621  1134  1154 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.621  1134  1154 W System.err: 	... 14 more
08-30 12:42:19.621  5681  5868 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-30 12:42:19.621  5681  5868 E AndroidRuntime: Process: android.process.media, PID: 5681
08-30 12:42:19.621  5681  5868 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:9,5)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.621  5681  5868 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.651  1134  3808 E ActivityManager: App crashed! Process: android.process.media
08-30 12:42:19.651  1134  3808 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.651  1134  3808 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.651  1134  3808 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.651  1134  3808 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.651  1134  3808 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.651  1134  3808 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.651  1134  3808 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.651  1134  3808 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 12:42:19.651  1134  3808 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 12:42:19.651  1134  3808 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.651  1134  3808 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.651  1134  3808 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.651  1134  3808 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.651  1134  3808 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.651  1134  3808 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.651  1134  3808 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.651  1134  3808 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.651  1134  3808 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.661  1134  8799 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 12:42:19.661  1134  8799 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472553739665.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 12:42:19.661  1134  8799 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.661  1134  8799 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.661  1134  8799 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:42:19.661  1134  8799 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 12:42:19.661  1134  8799 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:42:19.661  1134  8799 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.661  1134  8799 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.661  1134  8799 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.661  1134  8799 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.661  1134  8799 E ErrorReport: 	... 4 more
08-30 12:42:19.651  1134  3808 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.661  1134  8798 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 12:42:19.661  1134  8798 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472553739668.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 12:42:19.661  1134  8798 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.661  1134  8798 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.661  1134  8798 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:42:19.661  1134  8798 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 12:42:19.661  1134  8798 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:42:19.661  1134  8798 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.661  1134  8798 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.661  1134  8798 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.661  1134  8798 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.661  1134  8798 E ErrorReport: 	... 4 more
08-30 12:42:19.651  1134  3808 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.651  1134  3808 W System.err: 	... 14 more
08-30 12:42:19.661  1134  3808 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.661  1134  3808 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.661  8737  8737 D Process : killProcess, pid=8737
08-30 12:42:19.661  1134  3808 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.661  1134  3808 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.661  1134  3808 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.661  1134  3808 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.661  1134  3808 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.661  1134  3808 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 12:42:19.661  1134  3808 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 12:42:19.661  1134  3808 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.661  1134  3808 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.661  1134  3808 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.661  1134  3808 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.661  1134  3808 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.661  1134  3808 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.661  1134  3808 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.661  8737  8737 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 12:42:19.661  1134  3808 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.661  1134  3808 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.661  1134  3808 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.661  1134  3808 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.661  8737  8737 W HTCLOG  : use specified tag [Process], func [0].
08-30 12:42:19.661  8737  8737 W HTCLOG  : mask=0x18
08-30 12:42:19.661  1134  3808 W System.err: 	... 14 more
08-30 12:42:19.661  1134  3635 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-30 12:42:19.661  1134  3635 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.661  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.661  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.661  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.661  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 12:42:19.661  1134  3635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.661  1134  3635 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.661  1134  3635 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.661  1134  3635 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.661  1134  3635 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.661  1134  3635 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.661  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.661  1134  3635 W System.err: 	... 12 more
08-30 12:42:19.661  1134  3635 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.661  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.661  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.661  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.661  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 12:42:19.681  1134  1164 I ActivityManager: Start proc 8810:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 12:42:19.661  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 12:42:19.661  1134  3635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.661  1134  3635 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.661  1134  3635 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.661  1134  3635 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.661  1134  3635 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.661  1134  3635 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.661  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.661  1134  3635 W System.err: 	... 12 more
08-30 12:42:19.671  8792  8792 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:19.671  8792  8792 W HTCLOG  : mask=0x18
08-30 12:42:19.681  5681  5868 D Process : killProcess, pid=5681
08-30 12:42:19.681  5681  5868 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 12:42:19.681  5681  5868 W HTCLOG  : use specified tag [Process], func [0].
08-30 12:42:19.681  5681  5868 W HTCLOG  : mask=0x18
08-30 12:42:19.691  8810  8810 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:19.691  1134  3551 I ActivityManager: Recipient 8737
08-30 12:42:19.691  8810  8810 W HTCLOG  : mask=0x18
08-30 12:42:19.691   493   493 E lowmemorykiller: Error writing /proc/5681/oom_score_adj; errno=22
,08-30 12:42:19.711  8792  8792 I MultiDex: VM with version 2.1.0 has multidex support
08-30 12:42:19.711  8792  8792 I MultiDex: install
08-30 12:42:19.711  8792  8792 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 12:42:19.721  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 12:42:19.721  1134  4759 I ActivityManager: Recipient 5681
08-30 12:42:19.721  8792  8792 D FaceDetectTask: checkIsOmronEnable start
08-30 12:42:19.731  8792  8792 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
08-30 12:42:19.731  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.731  8792  8792 D FaceDetectTask: IsOmronEnable : true
08-30 12:42:19.731  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.731  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 12:42:19.731  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.731  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.731  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.731  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.731  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.731  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.731  8792  8792 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 12:42:19.731  8792  8792 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-30 12:42:19.741  8792  8792 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 12:42:19.741  8792  8792 W HTCLOG  : mask=0x18
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.741  8792  8792 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.741  8792  8792 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.741  8792  8792 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 12:42:19.741  8792  8792 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.741  8792  8792 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.741  8792  8792 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.741  8792  8792 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.741  8792  8792 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.741  8792  8792 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: ,	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: ,	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method),
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.751  8792  8792 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: FATAL EXCEPTION: main
08-30 12:42:19.751  8792  8792 E AndroidRuntime: Process: com.htc.launcher, PID: 8792
08-30 12:42:19.751  8792  8792 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151),
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 12:42:19.751  8792  8792 E AndroidRuntime: 	... 11 more
08-30 12:42:19.751  1134  3551 I ActivityManager: Process com.android.documentsui (pid 8737) has died
08-30 12:42:19.751  1134  3639 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 12:42:19.751  1134  3639 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 12:42:19.761  1134  3639 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.761  1134  3639 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 12:42:19,.761  1134  3639 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.761  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.761  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.761  1134  4759 I ActivityManager: Process android.process.media (pid 5681) has died
08-30 12:42:19.761  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 12:42:19.761  1134  4759 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 40044ms
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.761  1134  8844 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 12:42:19.761  1134  8844 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472553739766.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 12:42:19.761  1134  8844 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.761  1134  8844 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.761  1134  8844 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 12:42:19.761  1134  8844 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 12:42:19.761  1134  8844 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 12:42:19.761  1134  8844 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.761  1134  8844 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.761  1134  8844 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.761  1134  8844 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.761  1134  8844 E ErrorReport: 	... 4 more
08-30 12:42:19.761  1134  3639 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.761  1134  3639 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.761  1134  3639 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.761  1134  3639 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.761  1134  3639 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.761  1134  3639 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.761  1134  3639 W System.err: 	... 14 more
08-30 12:42:19.761  1134  3639 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open, failed: EROFS (Read-only file system)
08-30 12:42:19.761  1134  3639 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.761  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.761  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.761  1134  3639 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 12:42:19.761  1134  4759 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 12:42:19.761  1134  3639 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 12:42:19.761  1134  3639 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 12:42:19.761  1134  3639 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 12:42:19.761  1134  3639 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.761  1134  3639 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.761  1134  3639 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.761  1134  3639 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.761  1134  3639 W System.err: 	... 14 more
08-30 12:42:19.761  1134  3635 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 12:42:19.761  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 12:42:19.761  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 12:42:19.761  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 12:42:19.761  1134  3635 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 12:42:19.761  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 12:42:19.771  1134  4759 V WindowManager: addAppToken: AppWindowToken{1ad3645f token=Token{39a874fe ActivityRecord{ee0f8b9 u0 com.htc.launcher/.Launcher t455}}} to stack=0 task=455 at 0
08-30 12:42:19.761  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 12:42:19.761  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 12:42:19.761  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 12:42:19.761  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 12:42:19.761  1134  3635 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 12:42:19.761  1134  3635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 12:42:19.761  1134  3635 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 12:42:19.761  1134  3635 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 12:42:19.761  1134  3635 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 12:42:19.761  1134  3635 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 12:42:19.761  1134  3635 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 12:42:19.761  1134  3635 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 12:42:19.761  1134  3635 W System.err: 	... 12 more
08-30 12:42:19.761  3315  3340 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
08-30 12:42:19.771  8792  8792 D Process : killProcess, pid=8792
08-30 12:42:19.771  8792  8792 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 12:42:19.771  8792  8792 W HTCLOG  : use specified tag [Process], func [0].
08-30 12:42:19.771  8792  8792 W HTCLOG  : mask=0x18
08-30 12:42:19.771  3205  3205 I NotificationStackScrollLayout: setBlockTouchEnabled:false
08-30 12:42:19.791  8810  8810 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
08-30 12:42:19.801  8810  8845 D PowerUtils: getUserIdOfProcess, curUserId = 0
08-30 12:42:19.801  8810  8845 D PowerUtils: isRunningUnderOwner, isOwner = true
08-30 12:42:19.811  1134  3347 I ActivityManager: Start proc 8846:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
,08-30 12:42:19.831   566   566 I art     : Explicit concurrent mark sweep GC freed 8660(368KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 115us total 20.509ms
08-30 12:42:19.831  8846  8846 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:19.831  8846  8846 W HTCLOG  : mask=0x18
08-30 12:42:19.831  1134  3090 I ActivityManager: Recipient 8792
08-30 12:42:19.841   566   566 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 106us total 17.513ms
,08-30 12:42:19.861   566   566 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 111us total 17.688ms,
,08-30 12:42:19.871  1134  1164 I ActivityManager: Start proc 8867:com.google.android.gms/u0a19 for service com.google.android.gms/.icing.service.IndexWorkerService
,08-30 12:42:19.881  8810  8845 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
08-30 12:42:19.881  1134  3090 I ActivityManager: Process com.htc.launcher (pid 8792) has died
,08-30 12:42:19.891  8810  8845 D PowerUsageService: removed uid = 10142
,08-30 12:42:19.891  8867  8867 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:19.891  8867  8867 W HTCLOG  : mask=0x18
,08-30 12:42:19.901  8880  8880 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 12:42:19.901  1134  3090 I ActivityManager: Start proc 8880:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
08-30 12:42:19.901  8880  8880 W HTCLOG  : mask=0x18
,08-30 12:42:19.911  1134  3635 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true

```
