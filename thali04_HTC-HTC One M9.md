#### Test 82642184cbac892_thali04_HTC-HTC One M9 Logs


```
--------- beginning of system
08-30 02:50:13.261  1110  3760 D PMS     : acquireWL(2d194679): PARTIAL_WAKE_LOCK  Icing 0x1 4111 10019 null
08-30 02:50:13.281  1110  4206 D PMS     : releaseWL(2d194679): PARTIAL_WAKE_LOCK  Icing 0x1 null
--------- beginning of main
08-30 02:50:13.291  8347  8347 I DeviceManagement: DMApplication: !!! Hello, this is: [com.htc.cs.dm;3.0.404391;250011189] pid=8347 dbg=false s=true
08-30 02:50:13.291  8347  8347 I DeviceManagement: PackageUpdateReceiver: vvv Package added: [com.test.thalitest]
08-30 02:50:13.291  1110  1129 D PMS     : acquireWL(2b8d76c): PARTIAL_WAKE_LOCK  Icing 0x1 4111 10019 null
08-30 02:50:13.301  6565  8346 I ApplicationLogger: canRun() : Opted Out
08-30 02:50:13.301  6565  8346 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 136 ms] updated apps [took 136 ms] 
08-30 02:50:13.301  1110  3101 D Process : killProcessQuiet, pid=7616
08-30 02:50:13.301  1110  3101 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.trimApplications:19738 
08-30 02:50:13.301  1110  3101 I ActivityManager: Start proc 8373:com.google.android.apps.docs/u0a91 for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver
08-30 02:50:13.301  1110  3101 I ActivityManager: Killing 7616:com.htc.demoflopackageinstaller/u0a11 (adj 15): empty #17
08-30 02:50:13.311  8373  8373 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:13.311  8373  8373 W HTCLOG  : mask=0x18
,08-30 02:50:13.441  1110  3587 I ActivityManager: Recipient 7616
08-30 02:50:13.551  8396  8396 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
08-30 02:50:13.551  8396  8396 W HTCLOG  : mask=0x18
08-30 02:50:13.571  1110  4206 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 02:50:13.581  1110  1129 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 02:50:13.611  8373  8373 D DocsApplication: Plugin installer initialized.
08-30 02:50:13.611  1110  3587 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 02:50:13.631  8373  8373 I PackageInfoHelper: Provided clientMode=RELEASE, packageInfo=PackageInfo{cce0df0 com.google.android.apps.docs}
08-30 02:50:13.651  8373  8373 D TAG     : onCreate()
08-30 02:50:13.661  8373  8373 D CrossAppStateProvider: Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
08-30 02:50:13.681  1110  1130 W ActivityManager: getRunningAppProcesses: caller 10091 does not hold REAL_GET_TASKS; limiting output
08-30 02:50:13.701  8396  8400 W HTCLOG  : use specified tag [cutils-trace], func [0].
08-30 02:50:13.701  8396  8400 W HTCLOG  : mask=0x18
08-30 02:50:13.701  8396  8400 E cutils-trace: Error opening trace file: Permission denied (13)
08-30 02:50:13.761  8396  8396 D CustomizationManager: ====startRecUseTime====
08-30 02:50:13.761  8396  8396 D htc.customization.log.level:  is 
08-30 02:50:13.761  8396  8396 W CustomizationLogLevel: Level value is invalid, use default level 2
08-30 02:50:13.791  3567  3970 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: false, isToLoad: true
08-30 02:50:13.791  3567  3970 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@fc2e1ff +
08-30 02:50:13.791  3567  3970 I Prism.WidgetManager: onLoadItems() +
08-30 02:50:13.811  3567  3970 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
08-30 02:50:13.841  8396  8396 D CustomizationManager:  Read ACC file spent 0.037 (s)
08-30 02:50:13.841  8396  8396 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml
08-30 02:50:13.841  8396  8396 I CustomizationCIDLoader: Parsing tag category name = application
08-30 02:50:13.841  8396  8396 I CustomizationCIDLoader: Parsing tag category name = system
08-30 02:50:13.841  8396  8396 I CustomizationCIDLoader: Parsing tag category name = Settings
08-30 02:50:13.841  8396  8396 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
08-30 02:50:13.841  8396  8396 I CustomizationCIDLoader: Parsing tag category name = ACC
08-30 02:50:13.841  8396  8396 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240
08-30 02:50:13.841  8396  8396 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-30 02:50:13.841  8396  8396 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-30 02:50:13.841  8396  8396 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
08-30 02:50:13.841  8396  8396 I CustomizationCIDLoader: Parsing tag category name = AudioService
08-30 02:50:13.841  8396  8396 D CustomizationManager:  Read CID file spent 0.087 (s)
08-30 02:50:13.841  8396  8396 D CustomizationManager:  All configurations done spent 0.087 (s)
08-30 02:50:13.881  1110  3536 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 pid 8396 on display 0
08-30 02:50:13.881  1110  1178 D PMS     : acquireHCC(3ded135): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 1110 1000 null
08-30 02:50:13.881  1110  1178 D PMS     : acquireHCC(d9b69ca): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 1110 1000 null
08-30 02:50:13.891  1110  3536 V WindowManager: addAppToken: AppWindowToken{f384bb1 token=Token{2c11fe58 ActivityRecord{1a3c73b u0 com.test.thalitest/.MainActivity t451}}} to stack=1 task=451 at 0
08-30 02:50:13.901  1110  3536 I ActivityManager: Start proc 8413:com.test.thalitest/u0a142 for activity com.test.thalitest/.MainActivity
08-30 02:50:13.911  8396  8396 W HTCLOG  : use specified tag [IPCThreadState], func [0].
08-30 02:50:13.911  8396  8396 W HTCLOG  : mask=0x18
08-30 02:50:13.911  8396  8411 W HTCLOG  : use specified tag [Vector], func [0].
08-30 02:50:13.911  8396  8411 W HTCLOG  : mask=0x18
08-30 02:50:13.911  8413  8413 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:13.911  8413  8413 W HTCLOG  : mask=0x18
08-30 02:50:13.931  1110  1110 V ActivityManager: Display changed displayId=0
08-30 02:50:13.931  3347  3347 D DotMatrix: [EventService]  onDisplayChanged: 0
08-30 02:50:13.931  3347  3347 D DotMatrix: [EventService] isOutputToTV: false, mCoverOn:false
08-30 02:50:13.931  1110  3101 D ActivityManager: screenshot for ActivityRecord{1a3c73b u0 com.test.thalitest/.MainActivity t451}, bitmap=null, time = 0
08-30 02:50:13.941  3547  4202 D PhoneApp: EVENT_QUERY_MO_PACKAGES
08-30 02:50:13.941  3547  4202 D PhoneApp: -- N1 =0
08-30 02:50:13.941  3547  4202 D PhoneApp: -- N2 =0
08-30 02:50:13.941  3547  4202 D PhoneApp: -- N3 =0
08-30 02:50:13.951  3567  3567 I TrimMemoryManager: [trimMemory] 20
08-30 02:50:13.991  3567  3970 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-30 02:50:13.991  8413  8413 I WebViewFactory: Loading com.google.android.webview version 42.0.2311.137 (code 52311137)
08-30 02:50:14.041  8413  8413 I LibraryLoader: Time to load native libraries: 29 ms (timestamps 6970-6999)
08-30 02:50:14.041  8413  8413 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 02:50:14.051  8413  8413 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1c9e191c}
08-30 02:50:14.051  8413  8413 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 02:50:14.061  8413  8413 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 02:50:14.061  8413  8413 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 02:50:14.061  8413  8413 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 02:50:14.071  8413  8413 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 02:50:14.101  8413  8436 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
08-30 02:50:14.111  5601  5994 D BluetoothAdapterService(983707118): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@15cb0a13
08-30 02:50:14.111  3567  3970 I Prism.WidgetManager: onLoadItems() -
08-30 02:50:14.111  3567  3970 I Prism.ItemManager: loadItems() com.htc.launcher.pageview.WidgetManager@fc2e1ff -
,08-30 02:50:14.131  8413  8413 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-30 02:50:14.131  8413  8413 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=39 off=50364 len=3345
08-30 02:50:14.131  8413  8413 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:40 off:9397000 len:1161174
08-30 02:50:14.131  8413  8413 W HTCLOG  : use specified tag [libEGL], func [3].
08-30 02:50:14.131  8413  8413 W HTCLOG  : mask=0x18
08-30 02:50:14.131  8413  8413 W HTCLOG  : use specified tag [libEGL], func [3].
08-30 02:50:14.131  8413  8413 W HTCLOG  : mask=0x18
08-30 02:50:14.131  8413  8413 I Adreno  : QUALCOMM build                   : 065751b, 
08-30 02:50:14.131  8413  8413 I Adreno  : Build Date                       : 04/15/15
08-30 02:50:14.131  8413  8413 I Adreno  : OpenGL ES Shader Compiler Version: E031.25.03.07
08-30 02:50:14.131  8413  8413 I Adreno  : Local Branch                     : 
08-30 02:50:14.131  8413  8413 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.1_rb2.9
08-30 02:50:14.131  8413  8413 I Adreno  : Remote Branch                    : NONE
08-30 02:50:14.131  8413  8413 I Adreno  : Reconstruct Branch               : AU_LINUX_ANDROID_LA.BF64.1.2.1_RB2.05.01.00.081.016 + 065751b +  NOTHING
08-30 02:50:14.201  8413  8446 W chromium: [WARNING:data_reduction_proxy_config.cc(150)] SPDY proxy OFF at startup
08-30 02:50:14.211  8413  8413 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 02:50:14.221  8413  8413 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 02:50:14.231  8413  8413 D SystemWebViewEngine: CordovaWebView is running on device made by: HTC
08-30 02:50:14.231  8413  8413 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 02:50:14.231  8413  8413 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 02:50:14.261  8413  8457 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 02:50:14.261  8413  8457 W HTCLOG  : mask=0x18
08-30 02:50:14.261  1110  3536 V WindowManager: Adding window Window{34277559 u0 com.test.thalitest/com.test.thalitest.MainActivity} at 1 of 7 (after Window{1a6d6e13 u0 com.htc.launcher/com.htc.launcher.Launcher})
08-30 02:50:14.271  1110  3629 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-30 02:50:14.291  8413  8413 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
08-30 02:50:14.291  8413  8413 W HTCLOG  : use specified tag [ThreadedRenderer], func [0].
08-30 02:50:14.291  8413  8413 W HTCLOG  : mask=0x18
08-30 02:50:14.291  8413  8413 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 02:50:14.291  8413  8413 W HTCLOG  : mask=0x18
08-30 02:50:14.301  8413  8457 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 02:50:14.301  8413  8457 W HTCLOG  : mask=0x18
08-30 02:50:14.301  4111  6811 I Icing   : Indexing 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5 from com.google.android.googlequicksearchbox
08-30 02:50:14.301  8413  8457 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 02:50:14.301  8413  8457 W HTCLOG  : mask=0x18
08-30 02:50:14.301  8413  8457 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 02:50:14.301  8413  8457 W HTCLOG  : mask=0x18
08-30 02:50:14.301  8413  8457 W HTCLOG  : use specified tag [OpenGLRenderer], func [3].
08-30 02:50:14.301  8413  8457 W HTCLOG  : mask=0x18
08-30 02:50:14.301  8413  8457 W HTCLOG  : use specified tag [Surface], func [3].
08-30 02:50:14.301  8413  8457 W HTCLOG  : mask=0x18
08-30 02:50:14.311  8413  8457 W HTCLOG  : use specified tag [GraphicBufferMapper], func [3].
08-30 02:50:14.311  8413  8457 W HTCLOG  : mask=0x18
08-30 02:50:14.311  8413  8457 W HTCLOG  : use specified tag [qdmemalloc], func [0].
08-30 02:50:14.311  8413  8457 W HTCLOG  : mask=0x18
08-30 02:50:14.321  4111  6811 D Icing   : Loaded CLD2 Version V2.0 - 20140131
08-30 02:50:14.341  4111  6811 I Icing   : Indexing done 41371D4087D6E720EEA1EE287C7EDC3ED63A55D5
08-30 02:50:14.351  1110  4206 D PMS     : releaseWL(2b8d76c): PARTIAL_WAKE_LOCK  Icing 0x1 null
08-30 02:50:14.361  1110  1169 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +427ms (total +468ms)
08-30 02:50:14.411  8413  8413 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 8413
08-30 02:50:14.421  8373  8464 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 02:50:14.421  8373  8464 W HTCLOG  : mask=0x18
08-30 02:50:14.461  8373  8373 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
08-30 02:50:14.471  1110  3546 I ActivityManager: Start proc 8474:com.google.android.apps.plus/u0a128 for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor
08-30 02:50:14.471  8474  8474 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:14.471  8474  8474 W HTCLOG  : mask=0x18
08-30 02:50:14.471  8413  8413 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-30 02:50:14.501  8474  8474 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 02:50:14.521  8413  8460 D jxcore_app_log: JniHelper::setJavaVM(0xab27db70), pthread_self() = -1407157080
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@977a88b added. We now have 1 listener(s)
08-30 02:50:14.521  1110  3536 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-30 02:50:14.521  8413  8460 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 90:E7:C4:FE:AC:EF
08-30 02:50:14.521  8413  8460 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "90:E7:C4:FE:AC:EF"
08-30 02:50:14.521  8413  8460 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 02:50:14.521  8413  8460 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 90:E7:C4:FE:AC:EF
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 02:50:14.521  8413  8460 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4436626 added. We now have 1 listener(s)
08-30 02:50:14.521  8413  8460 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 02:50:14.531  1110  3072 D WifiService: New client listening to asynchronous messages
08-30 02:50:14.531  8413  8460 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 02:50:14.531  8413  8460 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 02:50:14.531  8413  8460 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 02:50:14.531  8413  8460 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 02:50:14.531  8413  8460 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-30 02:50:14.531  8413  8460 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 02:50:14.531  1110  3101 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 parentUser=-10000 foregroundUser=0
08-30 02:50:14.531  8413  8460 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 90:E7:C4:FE:AC:EF
08-30 02:50:14.531  5601  5640 D BluetoothAdapterService(983707118): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@15cb0a13
08-30 02:50:14.531  8413  8460 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
08-30 02:50:14.531  8413  8460 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:50:14.531  8413  8460 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:50:14.531  8413  8460 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 02:50:14.531  8413  8460 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:50:14.531  8413  8460 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:50:14.531  8413  8460 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 02:50:14.531  8413  8460 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 02:50:14.531  8413  8460 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-30 02:50:14.531  8413  8460 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 02:50:14.531  8413  8460 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 02:50:14.531  8413  8460 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 02:50:14.531  8413  8413 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 02:50:14.571  8413  8413 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-30 02:50:14.701  1110  4172 D PMS     : acquireWL(1e4828ef): PARTIAL_WAKE_LOCK  AsyncService 0x1 8474 10128 null
08-30 02:50:14.721  1110  3546 D PMS     : releaseWL(1e4828ef): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
08-30 02:50:14.721  1110  3027 D PMS     : acquireWL(2d52a685): PARTIAL_WAKE_LOCK  *alarm* 0x1 1110 1000 WorkSource{1000}
08-30 02:50:14.721  1110  3027 V AlarmManager: sending alarm PendingIntent{acb9cda: PendingIntentRecord{d18650b android broadcastIntent}}, i=android.net.ConnectivityService.action.PKT_CNT_SAMPLE_INTERVAL_ELAPSED, t=3, cnt=1, w=81086, Int=0
08-30 02:50:14.721  1110  3027 V AlarmManager: sending alarm PendingIntent{33ae8fe8: PendingIntentRecord{269c2601 android broadcastIntent}}, i=android.app.backup.intent.INIT, t=0, cnt=1, w=1472518211314, Int=0
08-30 02:50:14.731  1110  3535 D Process : killProcessQuiet, pid=7694
08-30 02:50:14.731  1110  3535 I ActivityManager: Killing 7694:com.htc.sdm/u0a61 (adj 15): empty #17
08-30 02:50:14.731  1110  3535 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
08-30 02:50:14.851  1110  1130 I ActivityManager: Recipient 7694
,08-30 02:50:14.901  8413  8498 W jxcore-log: Initializing JXcore engine
08-30 02:50:14.901  8413  8498 W jxcore-log: JXcore engine is ready
,08-30 02:50:14.931  8413  8498 W jxcore-log: Starting JXcore engine
,08-30 02:50:14.941  3665  3665 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-30 02:50:14.941  1110  1178 D PMS     : releaseHCC(3ded135): CPU_MIN_NUM ActivityManager-MultiCore-Num 0x8000 null,
08-30 02:50:14.941  1110  1178 D PMS     : releaseHCC(d9b69ca): CPU_MIN_FREQ ActivityManager-MultiCore-Freq 0x2000 null
,08-30 02:50:14.961  3665  3665 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-30 02:50:14.961  3665  3665 D c       : Getting all permits...,
08-30 02:50:14.971  3665  3665 D a       : Opening database...
08-30 02:50:14.971  3665  3665 D a       : Opening database auth.proximity.permit_store...,
,08-30 02:50:14.971  3665  3665 D a       : Closing database...,
,08-30 02:50:14.981  4111  4111 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,08-30 02:50:15.001  4111  8506 D LocationInitializer: Restart initialization of location,
08-30 02:50:15.001  1110  1110 D PMS     : acquireWL(276646e7): PARTIAL_WAKE_LOCK  *backup* 0x1 1110 1000 null
08-30 02:50:15.001  1110  1110 D PMS     : releaseWL(2d52a685): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{1000}
,08-30 02:50:15.011  1110  3141 W BackupManagerService: Requested unavailable transport: com.google.android.gms.backup.BackupTransportService,
08-30 02:50:15.011  1110  3141 E BackupManagerService: Requested init for com.google.android.gms.backup.BackupTransportService but not found,
08-30 02:50:15.011  1110  3141 D PMS     : releaseWL(276646e7): PARTIAL_WAKE_LOCK  *backup* 0x1 null,
,08-30 02:50:15.031  8413  8498 W jxcore-log: Platform android
08-30 02:50:15.031  8413  8498 W jxcore-log: 
,08-30 02:50:15.041  8413  8498 W jxcore-log: Process ARCH arm
08-30 02:50:15.041  8413  8498 W jxcore-log: 
,08-30 02:50:15.221  8413  8498 I jxcore-log: JXcore Cordova bridge is ready!,
08-30 02:50:15.221  8413  8498 I jxcore-log: 
08-30 02:50:15.221  8413  8498 W jxcore-log: JXcore engine is started,
,08-30 02:50:15.221  8413  8460 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 02:50:15.231  8413  8413 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 02:50:16.161  1110  3027 D PMS     : acquireWL(2dd0c294): PARTIAL_WAKE_LOCK  *alarm* 0x1 1110 1000 WorkSource{10027},
08-30 02:50:16.171  7772  7772 D AlarmReceiver: ACTION_RESTART_INTENT
08-30 02:50:16.171  1110  3027 V AlarmManager: sending alarm PendingIntent{2fa4213d: PendingIntentRecord{359c6c27 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=89117, Int=0,
,08-30 02:50:16.171  1110  1110 D PMS     : releaseWL(2dd0c294): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-30 02:50:16.171  7772  7772 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 02:50:16.171  7772  7772 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 02:50:16.171  7772  7772 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 02:50:16.171  7772  7772 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 02:50:16.201  7772  8508 D HtcModeClient: start the htcmodeservice thread
08-30 02:50:16.201  7772  8508 D HtcModeClient: initCanAgent
,08-30 02:50:16.201  7772  8508 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-30 02:50:16.201  7772  8508 D HtcModeClient: sense info: version = none, id = 2
,08-30 02:50:16.201  7772  8508 D HtcModeClient: display info: width = 1080, height = 1776,
08-30 02:50:16.201  7772  8508 D HtcModeClient: display info: mode = 10
,08-30 02:50:16.301  7772  7772 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
08-30 02:50:16.301  7772  7772 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 02:50:16.301  7772  7772 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 02:50:16.301  7772  7772 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 02:50:16.301  7772  7772 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 02:50:16.301  7772  7772 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 02:50:16.301  7772  7772 D HtcModeClient: connectState: Force_AWAKE = false
08-30 02:50:16.301  7772  7772 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 02:50:16.301  7772  7772 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 02:50:17.261  8234  8249 E AndroidHttpClient: Leak found,
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: java.lang.IllegalStateException: AndroidHttpClient created and never closed
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.<init>(AndroidHttpClient.java:181)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at com.google.android.volley.AndroidHttpClient.newInstance(AndroidHttpClient.java:167)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:147)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at com.google.android.volley.GoogleHttpClient.<init>(GoogleHttpClient.java:114)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at com.google.android.finsky.FinskyApp.onCreate(FinskyApp.java:342)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1025)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4959)
,08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:17.261  8234  8249 E AndroidHttpClient: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 02:50:17.921  8277  8277 D Process : killProcess, pid=8277,
08-30 02:50:17.921  8277  8277 D Process : com.google.android.gms.car.gt.run:127 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
08-30 02:50:17.921  8277  8277 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:17.921  8277  8277 W HTCLOG  : mask=0x18
08-30 02:50:17.921   494   494 E lowmemorykiller: Error writing /proc/8277/oom_score_adj; errno=22
,08-30 02:50:18.041  1110  3383 I ActivityManager: Recipient 8277
,08-30 02:50:18.041  1110  3383 I ActivityManager: Process com.google.android.gms:car (pid 8277) has died
,08-30 02:50:18.311  7772  8508 I HtcModeClient: handler message = 4011
,08-30 02:50:18.321  7772  8508 D HtcModeClient: getConnectionCheckCount first 0
08-30 02:50:18.321  7772  8508 D HtcModeClient: getConnectionCheckCount count = 7
,08-30 02:50:18.321  7772  8508 E HtcModeClient: Check connection and retry 8 times.
,08-30 02:50:18.321  7772  8508 D HtcModeClient: setConnectionCheckCount count = 8
,08-30 02:50:18.321  7772  8508 D HtcModeClient: setupRestart delayedTime = 3000
08-30 02:50:18.321  7772  7772 D HtcModeClient: setBtPriority priority = on
08-30 02:50:18.321  7772  7772 D HtcModeClient: unbindBlueToothService
08-30 02:50:18.321  7772  7772 D HtcModeClient: Don't start project servcice
08-30 02:50:18.331  7772  7772 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-30 02:50:18.331  7772  7772 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 02:50:18.331  7772  7772 D SilentMusic: call stop
08-30 02:50:18.331  7772  7772 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 02:50:18.331  7772  8509 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 02:50:18.341  7772  7772 D HtcModeClient: onDestroy,
,08-30 02:50:18.441  8373  8373 W GAV2    : Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
,08-30 02:50:19.361  1110  1110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.storage.DeviceStorageMonitorService.cancelSmsStorageNotification:819 com.android.server.storage.DeviceStorageMonitorService.checkAvailableSmsMemory:424 com.android.server.storage.DeviceStorageMonitorService.checkMemory:396 com.android.server.storage.DeviceStorageMonitorService$1.handleMessage:226 
,08-30 02:50:19.411  8373  8462 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-30 02:50:20.341  1110  3535 D PMS     : releaseWL(576f4f2): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 null,
,08-30 02:50:23.321  1110  3027 D PMS     : acquireWL(15799171): PARTIAL_WAKE_LOCK  *alarm* 0x1 1110 1000 WorkSource{10027}
08-30 02:50:23.321  1110  3027 V AlarmManager: sending alarm PendingIntent{1d798b56: PendingIntentRecord{359c6c27 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=94276, Int=0
,08-30 02:50:23.331  7772  7772 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 02:50:23.331  7772  7772 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 02:50:23.331  1110  1110 D PMS     : releaseWL(15799171): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-30 02:50:23.331  7772  7772 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 02:50:23.331  7772  7772 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 02:50:23.331  7772  7772 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 02:50:23.361  7772  8517 D HtcModeClient: start the htcmodeservice thread,
08-30 02:50:23.361  7772  8517 D HtcModeClient: initCanAgent
,08-30 02:50:23.361  7772  8517 I CANMesgAgentLocalSocket: CANAgent Id = 0,
,08-30 02:50:23.361  7772  8517 D HtcModeClient: sense info: version = none, id = 2,
,08-30 02:50:23.371  7772  8517 D HtcModeClient: display info: width = 1080, height = 1776,
,08-30 02:50:23.371  7772  8517 D HtcModeClient: display info: mode = 10
,08-30 02:50:23.461  7772  7772 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++
,08-30 02:50:23.461  7772  7772 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 02:50:23.461  7772  7772 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 02:50:23.461  7772  7772 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 02:50:23.461  7772  7772 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 02:50:23.461  7772  7772 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 02:50:23.461  7772  7772 D HtcModeClient: connectState: Force_AWAKE = false
08-30 02:50:23.461  7772  7772 D HtcModeClient: connectState: PHONE_PULGIN = true
08-30 02:50:23.461  7772  7772 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 02:50:24.201  1110  3071 D WifiStateMachine: startScan Pid: 1110 Uid -1
08-30 02:50:24.201  1110  3071 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-30 02:50:24.201  1110  3071 D WifiDisplayAdapter:     Client/Owner: Client
08-30 02:50:24.201  1110  3071 D WifiDisplayAdapter:     GroupId: 
08-30 02:50:24.201  1110  3071 D WifiDisplayAdapter:     Passphrase: 
08-30 02:50:24.201  1110  3071 D WifiDisplayAdapter:     SessionId: 0
08-30 02:50:24.201  1110  3071 D WifiDisplayAdapter:     IP Address: }
08-30 02:50:24.201  3171  3171 D wpa_supplicant: wlan0: Control interface command 'SET pno 0'
08-30 02:50:24.201  3171  3171 D wpa_supplicant: CTRL_IFACE SET 'pno'='0',
08-30 02:50:24.201  3171  3171 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
08-30 02:50:24.201  3171  3171 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
08-30 02:50:24.201  3171  3171 I wpa_supplicant: wpa_supplicant_scan enter
08-30 02:50:24.201  3171  3171 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-30 02:50:24.201  3171  3171 D wpa_supplicant: wlan0: Add radio work 'scan'@0x5586db9710
08-30 02:50:24.201  3171  3171 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-30 02:50:24.201  3171  3171 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x5586db9710 after 0.000022 second wait
08-30 02:50:24.201  3171  3171 D wpa_supplicant: wlan0: nl80211: scan request
,08-30 02:50:24.241  3171  3171 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-30 02:50:24.241  3171  3171 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
08-30 02:50:24.241  3171  3171 D wpa_supplicant: wlan0: nl80211: Scan trigger
08-30 02:50:24.241  3171  3171 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
08-30 02:50:24.241  3171  3171 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000086 seconds
08-30 02:50:24.241  3171  3171 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED ,
08-30 02:50:24.241  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
,08-30 02:50:24.501  1110  4172 D PMS     : acquireWL(29accacf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 1110 1000 null,
08-30 02:50:24.501  1110  4172 I BatteryService: n_update end
08-30 02:50:24.501  1110  4172 D PMS     : releaseWL(29accacf): PARTIAL_WAKE_LOCK  BatteryServiceUpdateStats_3 0x1 null
,08-30 02:50:24.511  1110  1110 D UsbnetService: BroadcastReceiver::onReceive+
08-30 02:50:24.511  1110  1110 D NotificationService: updateBattery(plug=true plugin=true low=false full=true health=2 status=5 usbOverheat=false)
08-30 02:50:24.511  1110  1110 D UsbnetService: onReceive BATTERY_CHANGED
08-30 02:50:24.511  1110  3072 D WifiController: battery changed pluggedType: 2
,08-30 02:50:24.511  1110  1110 D UsbnetService:  --> pluggedType = 2, mPluggedType = 0, mScreenOff = false
08-30 02:50:24.511  3196  3196 D PowerUI : closing low battery warning: level=100
,08-30 02:50:24.511  1110  1110 D UsbnetService: BroadcastReceiver::onReceive-
08-30 02:50:24.511  1110  1174 D HtcPowerSaver: updateBatteryInfo
,08-30 02:50:24.511  3196  3707 I IntentController: receive(android.intent.action.BATTERY_CHANGED,2,false)
08-30 02:50:24.511  1110  1110 D HtcPowerSaver: Checking...
08-30 02:50:24.511  1110  3072 D WifiController: handleMessage: E msg.what=155652
08-30 02:50:24.511  1110  1110 I HtcPowerSaver: >> updateStatus
08-30 02:50:24.511  1110  3072 D WifiController: processMsg: DeviceActiveState
08-30 02:50:24.511  3196  3196 D PowerUI : plugged = true, health = 2, mBatteryLevel = 100, mPluggedBatteryLevel = 100, mLowBatteryWarningLevel2 = 25, mshowLowChargingWarning2 = true
08-30 02:50:24.511  1110  3072 D WifiController: processMsg: StaEnabledState
08-30 02:50:24.521  1110  1110 I HtcPowerSaver: updateStatus (8000,100,-1,false,false,false,-1)
08-30 02:50:24.511  1110  3072 D WifiController: processMsg: DefaultState
08-30 02:50:24.521  1110  1110 I HtcPowerSaver: << updateStatus
,08-30 02:50:24.511  1110  3072 D WifiController: handleMessage: X
08-30 02:50:24.511  3347  3347 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-30 02:50:24.511  3347  3347 D DotMatrix: [EventService] reorderCurrEventType, mCurrentEventType = 26, version:2.1
08-30 02:50:24.511  3347  3347 D DotMatrix: [EventService] checkEventUpdateCondition, bCheckCondition:false, mCoverOn:false,mbIsUserInForeground:true
,08-30 02:50:24.561  3196  3196 I QuickSettingPowerSaver: updateEnabledState:(false,false,false),
08-30 02:50:24.561  3196  3196 I QuickSettingPowerSaverEX: batteryLevelChanged:true
08-30 02:50:24.561  3196  3196 I QuickSettingPowerSaverEX: updateEnabledState:(false,false,false)
08-30 02:50:24.561  3196  3196 I BatteryController: status:5 level:100 unsupport:false plugged:true
08-30 02:50:24.561  3196  3196 I FlashlightController: batteryLevelChange:100
,08-30 02:50:25.471  7772  8517 I HtcModeClient: handler message = 4011
,08-30 02:50:25.471  7772  8517 D HtcModeClient: getConnectionCheckCount first 0
08-30 02:50:25.471  7772  8517 D HtcModeClient: getConnectionCheckCount count = 8
08-30 02:50:25.471  7772  8517 E HtcModeClient: Check connection and retry 9 times.
,08-30 02:50:25.481  7772  8517 D HtcModeClient: setConnectionCheckCount count = 9
,08-30 02:50:25.481  7772  8517 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 02:50:25.481  7772  7772 D HtcModeClient: setBtPriority priority = on
08-30 02:50:25.481  7772  7772 D HtcModeClient: unbindBlueToothService
08-30 02:50:25.481  7772  7772 D HtcModeClient: Don't start project servcice
,08-30 02:50:25.491  7772  7772 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-30 02:50:25.491  7772  7772 D HtcModeClient: connectState: CONNECTION_READY = false
,08-30 02:50:25.491  7772  7772 D SilentMusic: call stop
08-30 02:50:25.491  7772  7772 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 02:50:25.491  7772  8518 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 02:50:25.501  7772  7772 D HtcModeClient: onDestroy
,08-30 02:50:27.051  1110  1156 I ActivityManager: Waited long enough for: ServiceRecord{a08fd50 u0 com.google.android.gms/.wearable.service.WearableService},
,08-30 02:50:27.851  3171  3171 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 02:50:27.851  3171  3171 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-30 02:50:27.851  3171  3171 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-30 02:50:27.851  3171  3171 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: Scan completed in 3.607445 seconds
08-30 02:50:27.851  3171  3171 D wpa_supplicant: nl80211: Received scan results (52 BSSes)
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-46
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-47
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-60
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:79 freq=5200 level=-60
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-60
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:7b freq=5200 level=-61
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-58
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-59
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-69
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-71
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-72
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-72
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-72
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:70 freq=2412 level=-73
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 00:16:a6:1e:e0:a4 freq=2422 level=-76
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-81
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-77
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-82
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-82
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d0 freq=2437 level=-78
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d5 freq=2437 level=-79
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d2 freq=2437 level=-79
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d4 freq=2437 level=-80
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d9 freq=5180 level=-86
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:db freq=5180 level=-86
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:35 freq=2412 level=-82
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:30 freq=2412 level=-82
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:36 freq=2412 level=-82
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:df freq=5180 level=-87
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:21:47:5a freq=5180 level=-87
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:21:47:5b freq=5180 level=-88
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:21:47:5f freq=5180 level=-88
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:12:64:95 freq=2462 level=-85
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:12:64:96 freq=2462 level=-85
08-30 02:50:27.851  3171,  3171 I wpa_supplicant: [] e4:aa:5d:fc:5b:f5 freq=2437 level=-86
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 00:fe:c8:73:02:02 freq=2462 level=-88
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:21:47:50 freq=2437 level=-89
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 00:fe:c8:73:02:00 freq=2462 level=-89
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [skup] 24:a4:3c:de:78:94 freq=2437 level=-90
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-71
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-72
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-82
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [RA-WINGS] 84:b2:61:1c:62:d3 freq=2437 level=-78
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d1 freq=2437 level=-80
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-81
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:de freq=5180 level=-87
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:31 freq=2412 level=-83
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 84:b2:61:12:64:9e freq=5180 level=-88
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [RA-WINGS] e4:aa:5d:fc:5b:f3 freq=2437 level=-84
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-86
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [] 00:fe:c8:73:02:01 freq=2462 level=-87
08-30 02:50:27.851  3171  3171 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-88
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Start scan result update 7
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 78 BSSID 84:b2:61:0f:9c:36 SSID '\x00'
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 79 BSSID 84:b2:61:21:47:5b SSID '\x00'
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 80 BSSID 00:fe:c8:73:02:02 SSID '\x00'
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 81 BSSID 00:fe:c8:73:02:00 SSID '\x00'
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 82 BSSID 24:a4:3c:de:78:94 SSID 'skup'
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 83 BSSID 84:b2:61:1c:62:de SSID '\x00'
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 84 BSSID 84:b2:61:12:64:9e SSID '\x00'
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 85 BSSID 00:fe:c8:73:02:01 SSID '\x00'
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 63 BSSID 84:b2:61:0f:9c:32 SSID '\x00' due to no match in scan
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 54 BSSID 84:b2:61:21:47:59 SSID ',\x00' due to no match in scan
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 35 BSSID 84:b2:61:12:64:90 SSID '\x00' due to no match in scan
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 32 BSSID 84:b2:61:12:64:94 SSID '\x00' due to no match in scan
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 73 BSSID 00:1f:27:54:70:90 SSID 'ktwtestwifi' due to no match in scan
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 58 BSSID 84:b2:61:21:47:5e SSID '\x00' due to no match in scan
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 44 BSSID 84:b2:61:12:64:91 SSID '\x00' due to no match in scan
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: BSS: last_scan_res_used=52/64
08-30 02:50:27.861  1110  3071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: Scan-only results received
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:27.851  3171  3171 D wpa_supplicant: wlan0: Radio work 'scan'@0x5586db9710 done in 3.652659 seconds
08-30 02:50:27.861  3171  3171 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-30 02:50:27.861  3171  3171 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 02:50:27.861  3171  3171 D wpa_supplicant: wlan0: Cancelling scan request
08-30 02:50:27.861  3171  3171 D wpa_supplicant: PNO: No configured SSIDs
08-30 02:50:27.861  1110  3071 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 02:50:27.861  3171  3171 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 02:50:27.861  3171  3171 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-30 02:50:27.881  3171  3171 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-30 02:50:27.881  1110  3071 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
,08-30 02:50:27.881  1110  1110 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 16
08-30 02:50:27.881  4431  4431 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 02:50:27.881  4431  5917 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
,08-30 02:50:30.511  1110  3027 I ActivityManager: Start proc 8519:com.htc.mms.backupagent/u0a58 for service com.htc.mms.backupagent/.SMSBackupAgentService
08-30 02:50:30.511  1110  3027 D PMS     : acquireWL(f779c5c): PARTIAL_WAKE_LOCK  *alarm* 0x1 1110 1000 WorkSource{10058}
,08-30 02:50:30.511  1110  3027 V AlarmManager: sending alarm PendingIntent{12b9cb65: PendingIntentRecord{a32903a com.htc.mms.backupagent startService}}, i=com.htc.mms.backupagent.ON_ALARM, t=0, cnt=1, w=1472518224780, Int=60000
,08-30 02:50:30.511  1110  3027 V AlarmManager: sending alarm PendingIntent{26102248: PendingIntentRecord{2b00b8e1 com.android.vending startService}}, i=null, t=0, cnt=1, w=1472518227562, Int=0
,08-30 02:50:30.511  1110  3027 V AlarmManager: sending alarm PendingIntent{26a97606: PendingIntentRecord{359c6c27 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=101436, Int=0
08-30 02:50:30.511  7772  7772 D AlarmReceiver: ACTION_RESTART_INTENT
,08-30 02:50:30.521  8519  8519 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:30.521  1110  1110 D PMS     : releaseWL(f779c5c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027},
08-30 02:50:30.521  8519  8519 W HTCLOG  : mask=0x18
08-30 02:50:30.521  7772  7772 D LocalBluetoothProfile: getPriorityOnValue = 100
08-30 02:50:30.521  7772  7772 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 02:50:30.521  7772  7772 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 02:50:30.521  7772  7772 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 02:50:30.541  7772  8541 D HtcModeClient: start the htcmodeservice thread,
08-30 02:50:30.541  7772  8541 D HtcModeClient: initCanAgent
,08-30 02:50:30.551  7772  8541 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-30 02:50:30.551  7772  8541 D HtcModeClient: sense info: version = none, id = 2
,08-30 02:50:30.551  7772  8541 D HtcModeClient: display info: width = 1080, height = 1776
,08-30 02:50:30.551  7772  8541 D HtcModeClient: display info: mode = 10
,08-30 02:50:30.581  8519  8544 D SMSBackup: SMSBackupAgentService started
08-30 02:50:30.581  8519  8544 D SMSBackup: Checking restore status
,08-30 02:50:30.581  8519  8544 D SMSBackup: Restore complete
08-30 02:50:30.581  8519  8544 D SMSBackup: cancelCheckAlarm
08-30 02:50:30.581  8519  8544 D SMSBackup: SMSBackupAgentService completed: completed in 0.0 seconds,
,08-30 02:50:30.651  7772  7772 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
,08-30 02:50:30.651  7772  7772 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 02:50:30.651  7772  7772 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 02:50:30.651  7772  7772 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 02:50:30.651  7772  7772 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 02:50:30.651  7772  7772 D HtcModeClient: connectState: PHONE_PULGIN = false
08-30 02:50:30.651  7772  7772 D HtcModeClient: connectState: Force_AWAKE = false
08-30 02:50:30.651  7772  7772 D HtcModeClient: connectState: PHONE_PULGIN = true,
08-30 02:50:30.651  7772  7772 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 02:50:30.701  1110  3848 I art     : Explicit concurrent mark sweep GC freed 29736(1495KB) AllocSpace objects, 11(204KB) LOS objects, 33% free, 16MB/24MB, paused 1.912ms total 142.819ms
,08-30 02:50:30.821  8234  8234 D Finsky  : [1] 5.onFinished: Installation state replication succeeded.
,08-30 02:50:32.661  7772  8541 I HtcModeClient: handler message = 4011
,08-30 02:50:32.661  7772  8541 D HtcModeClient: getConnectionCheckCount first 0
08-30 02:50:32.661  7772  8541 D HtcModeClient: getConnectionCheckCount count = 9
08-30 02:50:32.661  7772  8541 E HtcModeClient: Check connection and retry 10 times.,
08-30 02:50:32.661  7772  8541 D HtcModeClient: setConnectionCheckCount count = 10
08-30 02:50:32.661  7772  8541 D HtcModeClient: setupRestart delayedTime = 3000
,08-30 02:50:32.661  7772  7772 D HtcModeClient: setBtPriority priority = on
08-30 02:50:32.661  7772  7772 D HtcModeClient: unbindBlueToothService
08-30 02:50:32.661  7772  7772 D HtcModeClient: Don't start project servcice
08-30 02:50:32.661  7772  7772 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
,08-30 02:50:32.661  7772  7772 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 02:50:32.661  7772  7772 D SilentMusic: call stop
08-30 02:50:32.671  7772  7772 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 02:50:32.671  7772  8543 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 02:50:32.681  7772  7772 D HtcModeClient: onDestroy,
,08-30 02:50:32.681  1110  1130 D Process : killProcessQuiet, pid=7941
,08-30 02:50:32.681  1110  1130 I ActivityManager: Killing 7941:com.htc.calendar/u0a6 (adj 15): empty #17
08-30 02:50:32.681  1110  1130 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
,08-30 02:50:32.761  1110  4206 I ActivityManager: Recipient 7941
,08-30 02:50:34.021  8413  8498 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 02:50:34.021  8413  8498 I jxcore-log: 
,08-30 02:50:34.031  8413  8498 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 02:50:34.031  8413  8498 I jxcore-log: 
,08-30 02:50:34.031  5601  5640 D BluetoothAdapterService(983707118): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@15cb0a13
08-30 02:50:34.031  8413  8498 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 02:50:34.031  8413  8498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 02:50:34.031  8413  8498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 02:50:34.031  8413  8498 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 02:50:34.031  8413  8498 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 02:50:34.031  8413  8498 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-30 02:50:34.031  8413  8498 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-30 02:50:34.031  8413  8498 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-30 02:50:34.041  5601  5640 D BluetoothAdapterService(983707118): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@15cb0a13
08-30 02:50:34.041  8413  8498 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-30 02:50:34.041  8413  8498 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 02:50:34.041  8413  8498 I jxcore-log: 
,08-30 02:50:34.051  8413  8498 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 02:50:34.051  8413  8498 I jxcore-log: 
,08-30 02:50:34.491  8413  8498 I jxcore-log: Running unit tests
08-30 02:50:34.491  8413  8498 I jxcore-log: 
,08-30 02:50:34.491  8413  8498 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 02:50:34.491  8413  8498 I jxcore-log: Failed to execute UT.
08-30 02:50:34.491  8413  8498 I jxcore-log: 
,08-30 02:50:34.491  8413  8498 I jxcore-log: Unit Test app is loaded
08-30 02:50:34.491  8413  8498 I jxcore-log: 
,08-30 02:50:34.501  8413  8498 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-30 02:50:34.501  8413  8498 I jxcore-log: 
08-30 02:50:34.511  8413  8498 I jxcore-log: My device name is: HTC-HTC One M9
08-30 02:50:34.511  8413  8498 I jxcore-log: 
,08-30 02:50:34.511  8413  8413 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 02:50:34.511  8413  8498 I jxcore-log: WARN testUtils: myNameCallback not set!,
08-30 02:50:34.511  8413  8498 I jxcore-log: 
,08-30 02:50:37.661  1110  3027 D PMS     : acquireWL(d88d48c): PARTIAL_WAKE_LOCK  *alarm* 0x1 1110 1000 WorkSource{10027},
08-30 02:50:37.661  1110  3027 V AlarmManager: sending alarm PendingIntent{244d57d5: PendingIntentRecord{359c6c27 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=108615, Int=0
,08-30 02:50:37.671  7772  7772 D AlarmReceiver: ACTION_RESTART_INTENT,
08-30 02:50:37.681  7772  7772 D LocalBluetoothProfile: getPriorityOnValue = 100
,08-30 02:50:37.681  1110  1110 D PMS     : releaseWL(d88d48c): PARTIAL_WAKE_LOCK  *alarm* 0x1 WorkSource{10027}
08-30 02:50:37.681  7772  7772 D LocalBluetoothProfile: getPriorityOffValue = 0
08-30 02:50:37.681  7772  7772 D Utils   : CMD:getprop ro.htc.htcmode.socket.type
08-30 02:50:37.681  7772  7772 I System  : exec(getprop ro.htc.htcmode.socket.type @ com.htc.autobot.c.b.b:-1)
,08-30 02:50:37.701  7772  8547 D HtcModeClient: start the htcmodeservice thread
08-30 02:50:37.701  7772  8547 D HtcModeClient: initCanAgent
,08-30 02:50:37.711  7772  8547 I CANMesgAgentLocalSocket: CANAgent Id = 0
,08-30 02:50:37.711  7772  8547 D HtcModeClient: sense info: version = none, id = 2
,08-30 02:50:37.711  7772  8547 D HtcModeClient: display info: width = 1080, height = 1776
08-30 02:50:37.711  7772  8547 D HtcModeClient: display info: mode = 10
,08-30 02:50:37.811  7772  7772 D HtcModeClient: onStartCommand() action = com.htc.autobot.htcmodeclient.PowerConnected +++,
,08-30 02:50:37.811  7772  7772 D HtcModeClient: connectState: BT_TURNON_BYME = false
08-30 02:50:37.811  7772  7772 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 02:50:37.811  7772  7772 D HtcModeClient: connectState: ENABLE_PROJECTBYAPP = false
08-30 02:50:37.811  7772  7772 D HtcModeClient: connectState: ENTER_PROJECTMODE = false
08-30 02:50:37.811  7772  7772 D HtcModeClient: connectState: PHONE_PULGIN = false
,08-30 02:50:37.811  7772  7772 D HtcModeClient: connectState: Force_AWAKE = false
08-30 02:50:37.811  7772  7772 D HtcModeClient: connectState: PHONE_PULGIN = true,
08-30 02:50:37.811  7772  7772 D HtcModeClient: connectState: POWERCONNECTED_READY = true
,08-30 02:50:37.971  8413  8498 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js,
08-30 02:50:37.971  8413  8498 I jxcore-log: 
,08-30 02:50:38.571  8413  8498 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js,
08-30 02:50:38.571  8413  8498 I jxcore-log: 
,08-30 02:50:38.611  8413  8498 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js,
08-30 02:50:38.611  8413  8498 I jxcore-log: 
,08-30 02:50:39.211  1110  3071 D WifiStateMachine: startScan Pid: 1110 Uid -1,
08-30 02:50:39.211  1110  3071 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo:
08-30 02:50:39.211  1110  3071 D WifiDisplayAdapter:     Client/Owner: Client
08-30 02:50:39.211  1110  3071 D WifiDisplayAdapter:     GroupId: 
08-30 02:50:39.211  1110  3071 D WifiDisplayAdapter:     Passphrase: 
08-30 02:50:39.211  1110  3071 D WifiDisplayAdapter:     SessionId: 0
08-30 02:50:39.211  1110  3071 D WifiDisplayAdapter:     IP Address: }
08-30 02:50:39.211  3171  3171 D wpa_supplicant: wlan0: Control interface command 'SET pno 0'
08-30 02:50:39.211  3171  3171 D wpa_supplicant: CTRL_IFACE SET 'pno'='0',
08-30 02:50:39.211  3171  3171 D wpa_supplicant: wlan0: Control interface command 'SCAN TYPE=ONLY'
08-30 02:50:39.211  3171  3171 D wpa_supplicant: wlan0: Setting scan request: 0.000000 sec
08-30 02:50:39.211  3171  3171 I wpa_supplicant: wpa_supplicant_scan enter
08-30 02:50:39.211  3171  3171 D wpa_supplicant: wlan0: Starting AP scan for wildcard SSID
08-30 02:50:39.211  3171  3171 D wpa_supplicant: wlan0: Add radio work 'scan'@0x5586db9710
08-30 02:50:39.211  3171  3171 D wpa_supplicant: wlan0: First radio work item in the queue - schedule start immediately
08-30 02:50:39.211  3171  3171 D wpa_supplicant: wlan0: Starting radio work 'scan'@0x5586db9710 after 0.000026 second wait
,08-30 02:50:39.211  3171  3171 D wpa_supplicant: wlan0: nl80211: scan request
,08-30 02:50:39.261  3171  3171 D wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds,
08-30 02:50:39.261  3171  3171 D wpa_supplicant: nl80211: Drv Event 33 (NL80211_CMD_TRIGGER_SCAN) received for wlan0
08-30 02:50:39.261  3171  3171 D wpa_supplicant: wlan0: nl80211: Scan trigger
08-30 02:50:39.261  3171  3171 D wpa_supplicant: wlan0: Event SCAN_STARTED (49) received
08-30 02:50:39.261  3171  3171 D wpa_supplicant: wlan0: Own scan request started a scan in 0.000142 seconds
08-30 02:50:39.261  3171  3171 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-30 02:50:39.261  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
,08-30 02:50:39.821  7772  8547 I HtcModeClient: handler message = 4011,
08-30 02:50:39.821  7772  8547 D HtcModeClient: getConnectionCheckCount first 0
08-30 02:50:39.821  7772  8547 D HtcModeClient: getConnectionCheckCount count = 10
08-30 02:50:39.821  7772  8547 E HtcModeClient: Check connection and retry 11 times.
,08-30 02:50:39.821  7772  8547 D HtcModeClient: setConnectionCheckCount count = 11,
,08-30 02:50:39.831  7772  8547 D HtcModeClient: setupRestart delayedTime = 3000
08-30 02:50:39.831  7772  7772 D HtcModeClient: setBtPriority priority = on
08-30 02:50:39.831  7772  7772 D HtcModeClient: unbindBlueToothService
08-30 02:50:39.831  7772  7772 D HtcModeClient: Don't start project servcice,
08-30 02:50:39.831  7772  7772 D HtcModeClient: setEject: MEDIA_EJECT_STATE = true
08-30 02:50:39.831  7772  7772 D HtcModeClient: connectState: CONNECTION_READY = false
08-30 02:50:39.831  7772  7772 D SilentMusic: call stop
08-30 02:50:39.831  7772  7772 W HtcModeClient: leaveProjectMode: It does not enter ProjectMode
08-30 02:50:39.831  7772  8548 W CANMesgAgentLocalSocket: read the terminate packet, so break
,08-30 02:50:39.851  7772  7772 D HtcModeClient: onDestroy,
,08-30 02:50:40.551  8413  8498 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 02:50:40.551  8413  8498 I jxcore-log: 
,08-30 02:50:40.881  8413  8498 I jxcore-log: ERROR runTests: ,
08-30 02:50:40.881  8413  8498 I jxcore-log: 
,08-30 02:50:40.891  8413  8498 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger',
08-30 02:50:40.891  8413  8498 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 02:50:40.891  8413  8498 I jxcore-log: WARN testUtils: logCallback not set!
08-30 02:50:40.891  8413  8498 I jxcore-log: 
,08-30 02:50:40.911  8413  8498 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',,
08-30 02:50:40.911  8413  8498 I jxcore-log:     _functionName: 'loadFile',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _lineNumber: '26',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _columnNumber: '11',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 02:50:40.911  8413  8498 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _functionName: '',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _lineNumber: '38',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _columnNumber: '7',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 02:50:40.911  8413  8498 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _functionName: '',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _lineNumber: '35',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _columnNumber: '3',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 02:50:40.911  8413  8498 I jxcore-log:   { _fileName: 'module.js',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _lineNumber: '621',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _columnNumber: '8',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },,
08-30 02:50:40.911  8413  8498 I jxcore-log:   { _fileName: 'module.js',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _functionName: '$w._extensions[".js"]',
,08-30 02:50:40.911  8413  8498 I jxcore-log:     _lineNumber: '651',
08-30 02:50:40.911  8413  8498 I jxcore-log:     _columnNumber: '1',
08-30 02:50:40.911  8413  8498 I jxcore-log:    
08-30 02:50:40.911  8413  8498 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 02:50:40.911  8413  8498 I jxcore-log: 
08-30 02:50:40.911  8413  8498 E jxcore-log: Error: 
08-30 02:50:40.911  8413  8498 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 02:50:40.911  8413  8498 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 02:50:40.911  8413  8498 E jxcore-log: 
,08-30 02:50:41.131  8549  8549 W HTCLOG  : use specified tag [AndroidRuntime], func [0].
,08-30 02:50:41.131  8549  8549 W HTCLOG  : mask=0x18
,08-30 02:50:41.281  8549  8553 W HTCLOG  : use specified tag [cutils-trace], func [0].
,08-30 02:50:41.281  8549  8553 W HTCLOG  : mask=0x18
08-30 02:50:41.281  8549  8553 E cutils-trace: Error opening trace file: Permission denied (13)
,08-30 02:50:41.341  8549  8549 D CustomizationManager: ====startRecUseTime====,
08-30 02:50:41.341  8549  8549 D htc.customization.log.level:  is 
08-30 02:50:41.341  8549  8549 W CustomizationLogLevel: Level value is invalid, use default level 2
,08-30 02:50:41.431  8549  8549 D CustomizationManager:  Read ACC file spent 0.043 (s),
,08-30 02:50:41.431  8549  8549 V CustomizationCIDLoader: full path : /system/customize/CID/default.xml,
,08-30 02:50:41.431  8549  8549 I CustomizationCIDLoader: Parsing tag category name = application
,08-30 02:50:41.441  8549  8549 I CustomizationCIDLoader: Parsing tag category name = system,
08-30 02:50:41.441  8549  8549 I CustomizationCIDLoader: Parsing tag category name = Settings
08-30 02:50:41.441  8549  8549 I CustomizationCIDLoader: Parsing tag category name = AutomotiveHome
,08-30 02:50:41.441  8549  8549 I CustomizationCIDLoader: Parsing tag category name = ACC
,08-30 02:50:41.441  8549  8549 I CustomizationCIDLoader: add string-array item, value = de:free=+3011;+73240,
08-30 02:50:41.441  8549  8549 I CustomizationCIDLoader: add string-array item, value = nl:free=+9434;+9526;+1000
08-30 02:50:41.441  8549  8549 I CustomizationCIDLoader: add string-array item, value = mk:free=+122;+129005
08-30 02:50:41.441  8549  8549 I CustomizationCIDLoader: Parsing tag category name = SettingsProvider
,08-30 02:50:41.441  8549  8549 I CustomizationCIDLoader: Parsing tag category name = AudioService
,08-30 02:50:41.441  8549  8549 D CustomizationManager:  Read CID file spent 0.101 (s)
08-30 02:50:41.441  8549  8549 D CustomizationManager:  All configurations done spent 0.101 (s)
,08-30 02:50:41.481  1110  3101 D PackageManager: deletePackageAsUser: pkg=com.test.thalitest user=0, pid=8549, uid=2000,
,08-30 02:50:41.491  1110  1156 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=-1: uninstall pkg
08-30 02:50:41.491  1110  1156 D Process : killProcessQuiet, pid=8413
08-30 02:50:41.491  1110  1156 I ActivityManager: Killing 8413:com.test.thalitest/u0a142 (adj 0): stop com.test.thalitest
08-30 02:50:41.491  1110  1156 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.removeProcessLocked:6195 com.android.server.am.ActivityManagerService.killPackageProcessesLocked:5997 
,08-30 02:50:41.581   525   525 W HTCLOG  : use specified tag [Vector], func [0].,
08-30 02:50:41.581   525   525 W HTCLOG  : mask=0x18
,08-30 02:50:41.601  1110  3546 I ActivityManager: Recipient 8413
08-30 02:50:41.601  1110  1130 I WindowState: WIN DEATH: Window{34277559 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 02:50:41.601  1110  3072 D WifiService: Client connection lost with reason: 4
,08-30 02:50:41.701  1110  1156 I ActivityManager:   Force finishing activity 3 ActivityRecord{1a3c73b u0 com.test.thalitest/.MainActivity t451},
,08-30 02:50:41.711  1110  3546 W ActivityManager: Spurious death for ProcessRecord{106f9e42 8413:com.test.thalitest/u0a142}, curProc for 8413: null,
,08-30 02:50:41.711  1110  1180 I ActivityManager: Force stopping com.test.thalitest appid=10142 user=0: pkg removed
,08-30 02:50:41.731  3347  3347 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, packageName: com.test.thalitest
08-30 02:50:41.731  3347  3347 D DotMatrix: [EventService] mPackageInfoReceiver.onReceive, replacing: false, mCoverOn: false
08-30 02:50:41.731  1110  3149 D TaskPersister: removeObsoleteFile: deleting file=451_task.xml,
,08-30 02:50:41.741  3737  4164 D AccTypeManager: Registering external account type=com.twitter.android.auth.login, packageName=com.twitter.android
08-30 02:50:41.741  1110  3535 D PMS     : acquireWL(2acaae53): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 4431 10019 null
08-30 02:50:41.741  4431  4559 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-30 02:50:41.741  1110  3067 V NetworkPolicy: ACTION_UID_REMOVED for uid=10142
08-30 02:50:41.741  1110  3067 V NetworkPolicy: writePolicyLocked(),
08-30 02:50:41.741  1110  3546 D PMS     : releaseWL(2acaae53): PARTIAL_WAKE_LOCK  Wakeful StateMachine: GeofencerStateMachine 0x1 null
08-30 02:50:41.751  1110  3030 W SystemReader: Cannot find grip_rejection_width, use default value instead
08-30 02:50:41.751  1110  3066 D PMS     : acquireWL(209bb390): PARTIAL_WAKE_LOCK  NetworkStats 0x1 1110 1000 null
08-30 02:50:41.761  3737  4164 D AccTypeManager: Registering external account type=com.facebook.auth.login, packageName=com.facebook.katana
08-30 02:50:41.771  4111  4111 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-30 02:50:41.771  1110  3066 D PMS     : releaseWL(209bb390): PARTIAL_WAKE_LOCK  NetworkStats 0x1 null
08-30 02:50:41.771  3567  3567 I art     : Explicit concurrent mark sweep GC freed 2321(107KB) AllocSpace objects, 4(354KB) LOS objects, 39% free, 19MB/33MB, paused 1.001ms total 49.399ms
08-30 02:50:41.771  1110  3760 D PMS     : acquireWL(3ad4e045): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1 4111 10019 null
08-30 02:50:41.781  3547  3547 D PhoneApp: -- PackageChangeBroadcastReceiver  action = android.intent.action.PACKAGE_REMOVED
08-30 02:50:41.781  3665  3665 I ConfigService: onCreate
08-30 02:50:41.781  3665  3665 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-30 02:50:41.781  1110  1155 I InputMethodManagerService: [buildInputMethodListLocked] defaultImiId=com.htc.sense.ime/.HTCIMEService, resetDefaultEnabledIme=false
08-30 02:50:41.781  4111  4111 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package: cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,08-30 02:50:41.791  3737  4164 D AccTypeManager: Registering external account type=com.google.android.gm.exchange, packageName=com.google.android.gm
,08-30 02:50:41.791  3765  8566 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest,
,08-30 02:50:41.801  1110  3067 D NetworkPolicy: notifyPoliciesChangeLocked: no change,
08-30 02:50:41.801  1110  3067 V NetworkPolicy: updateNetworkEnabledLocked()
08-30 02:50:41.801  3665  3665 I ConfigService: onBind returning update interface
08-30 02:50:41.801  1110  3067 V NetworkPolicy: updateNotificationsLocked()
08-30 02:50:41.801  3665  3665 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-30 02:50:41.801  3665  3665 I ConfigService: onBind returning config service
08-30 02:50:41.801  3737  4164 D AccTypeManager: Registering external account type=com.htc.linkedin, packageName=com.htc.sense.linkedin
,08-30 02:50:41.811  1110  1130 I ActivityManager: Start proc 8568:com.google.android.gms.ui/u0a19 for broadcast com.google.android.gms/com.google.android.location.settings.PackageChangeReceiver,
08-30 02:50:41.811  6565  6565 I art     : Explicit concurrent mark sweep GC freed 12311(760KB) AllocSpace objects, 2(48KB) LOS objects, 34% free, 3MB/5MB, paused 437us total 87.766ms
08-30 02:50:41.811  1110  4172 D PMS     : acquireWL(2c37a1f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 3665 10019 null
,08-30 02:50:41.821  1110  4172 D PMS     : releaseWL(2c37a1f9): PARTIAL_WAKE_LOCK  *net_scheduler* 0x1 null,
08-30 02:50:41.821  1110  3027 D PMS     : acquireWL(294764b5): PARTIAL_WAKE_LOCK  *alarm* 0x1 1110 1000 WorkSource{10019}
08-30 02:50:41.821  1110  3027 V AlarmManager: sending alarm PendingIntent{2d13374a: PendingIntentRecord{1d59835b com.google.android.gms broadcastIntent}}, i=com.google.android.intent.action.GCM_RECONNECT, t=2, cnt=1, w=114436, Int=0
,08-30 02:50:41.831  3665  3665 I ConfigService: onDestroy
,08-30 02:50:41.841  1110  1155 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.,
08-30 02:50:41.841  8568  8568 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:41.841  8568  8568 W HTCLOG  : mask=0x18
,08-30 02:50:41.841  3737  4164 E ExternalAccountType: Unsupported attribute readOnly
,08-30 02:50:41.871  8568  8568 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.,
08-30 02:50:41.871  8568  8568 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.,
,08-30 02:50:41.901  8568  8568 I MultiDex: VM with version 2.1.0 has multidex support
08-30 02:50:41.901  8568  8568 I MultiDex: install
08-30 02:50:41.901  8568  8568 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 02:50:41.921  8568  8568 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application',
08-30 02:50:41.921  3567  3567 D FindExtension: FindExtension: before mHardwareRenderer.initialize, mSurface.isValid() = true
,08-30 02:50:41.921  3567  3567 I ThreadedRenderer: Defer allocateBuffers to drawing time
08-30 02:50:41.921  1110  1110 I art     : Explicit concurrent mark sweep GC freed 23801(1674KB) AllocSpace objects, 3(60KB) LOS objects, 33% free, 15MB/23MB, paused 4.954ms total 202.685ms
,08-30 02:50:41.921  1110  1180 I art     : WaitForGcToComplete blocked for 182.009ms for cause Explicit
,08-30 02:50:41.951  3567  3970 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: false, isLoaded: true, isToLoad: false
08-30 02:50:41.951  3567  3970 I Prism.ItemManager: loadItemsIfNotLoaded() isDelayLoad: true, isLoaded: false, isToLoad: false
08-30 02:50:41.961  8568  8568 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-30 02:50:41.961  3567  3567 I Launcher: Deferring update until onResume
08-30 02:50:41.961  3567  3567 D Launcher: waitUntilResume // bindAppsRemoved
,08-30 02:50:41.981  3489  3489 D Nfc-Utils: isNxpCodebase: isNxp=false,
,08-30 02:50:41.981  1110  4172 D Process : killProcessQuiet, pid=7821,
08-30 02:50:41.981  1110  4172 I ActivityManager: Killing 7821:com.google.android.gm/u0a97 (adj 15): empty #17
08-30 02:50:41.991  1110  4172 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
,08-30 02:50:42.021  1110  1110 W PackageManager: Unable to load service info ResolveInfo{15fc1ffe com.htc.sense.socialnetwork.instagram/.remote.InstagramSyncContactService m=0x108000},
08-30 02:50:42.021  1110  1110 W PackageManager: org.xmlpull.v1.XmlPullParserException: No android.content.SyncAdapter meta-data
08-30 02:50:42.021  1110  1110 W PackageManager: 	at android.content.pm.RegisteredServicesCache.parseServiceInfo(RegisteredServicesCache.java:509)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at android.content.pm.RegisteredServicesCache.generateServicesMap(RegisteredServicesCache.java:345)
08-30 02:50:42.021  1110  1110 W PackageManager: 	,at android.content.pm.RegisteredServicesCache.handlePackageEvent(RegisteredServicesCache.java:171)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at android.content.pm.RegisteredServicesCache.access$100(RegisteredServicesCache.java:71)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at android.content.pm.RegisteredServicesCache$1.onReceive(RegisteredServicesCache.java:180)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:927)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at com.android.server.SystemServer.run(SystemServer.java:331)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at com.android.server.SystemServer.main(SystemServer.java:232)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:42.021  1110  1110 W PackageManager: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 02:50:42.051  1110  3101 I ActivityManager: Recipient 7821,
,08-30 02:50:42.061  1110  1110 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED,
,08-30 02:50:42.101  4111  8592 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-30 02:50:42.101  4111  8592 D AccountUtils: Clearing selected account for com.test.thalitest
,08-30 02:50:42.111  1110  1129 I ActivityManager: Start proc 8594:com.htc.home.personalize/1000 for broadcast com.htc.home.personalize/com.htc.font.util.receiver.ApplyFontStyleReceiver,
,08-30 02:50:42.111  1110  1180 I art     : Explicit concurrent mark sweep GC freed 5943(321KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 15MB/23MB, paused 2.602ms total 188.146ms
,08-30 02:50:42.121  8594  8594 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:42.121  8594  8594 W HTCLOG  : mask=0x18
,08-30 02:50:42.161  7971  8619 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id),
,08-30 02:50:42.181  1110  3546 I ActivityManager: Killing 7518:com.google.android.music:main/u0a115 (adj 15): empty #17,
08-30 02:50:42.181  1110  3546 D Process : killProcessQuiet, pid=7518
08-30 02:50:42.181  1110  3546 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 ,
,08-30 02:50:42.191  4111  8621 I PeopleContactsSync: CP2 sync disabled
08-30 02:50:42.191  1110  4172 D PMS     : acquireWL(2d4a34e6): PARTIAL_WAKE_LOCK  Icing 0x1 4111 10019 null
08-30 02:50:42.191  1110  1129 I PackageManager:  setEnabledSetting(), pkgName=com.google.android.gms, clsName=com.google.android.gms.people.pub.PeopleProfileActionGatewayActivity, state=2, flag=1, pid=4111, uid=10019, userID:0
,08-30 02:50:42.191  8549  8549 I art     : System.exit called, status: 0
08-30 02:50:42.191  4111  6811 I Icing   : doRemovePackageData com.test.thalitest
,08-30 02:50:42.191  8549  8549 W HTCLOG  : use specified tag [Vector], func [0].
08-30 02:50:42.191  8549  8549 W HTCLOG  : mask=0x18
08-30 02:50:42.191  1110  3824 D PMS     : releaseWL(2d4a34e6): PARTIAL_WAKE_LOCK  Icing 0x1 null
,08-30 02:50:42.311  1110  3760 I ActivityManager: Recipient 7518,
08-30 02:50:42.311  1110  4206 D MediaRouterService: Client com.google.android.music (pid 7518): Died!
,08-30 02:50:42.401  3737  3737 E PackageActionReceiver: ACTION_PACKAGE_REMOVED
,08-30 02:50:42.461  3639  8627 I [PluginManager]RegisterService: onHandleIntent, action: android.intent.action.PACKAGE_REMOVED, data: package:com.test.thalitest
,08-30 02:50:42.461  3567  3567 D Prism.PackageStateRece_: action: android.intent.action.PACKAGE_REMOVED
08-30 02:50:42.461  3567  3567 I ContextualWidget: package com.test.thalitest removed
08-30 02:50:42.461  3639  8627 E SQLiteLog: (3850) statement aborts at 41: [UPDATE plugin SET removed=? WHERE package_id IN ( SELECT _id FROM plugin_pkg WHERE package=? )] disk I/O error
08-30 02:50:42.461  3639  8627 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 02:50:42.461  3639  8627 W HTCLOG  : mask=0x18
08-30 02:50:42.461  3639  8627 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.sense.hsp/databases/registry.db, handle: 0x55931c00b0
08-30 02:50:42.471  3567  3999 I ContextualWidget: handleMessage, what=1004 mode=GettingOut maxcount=8
,08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: provider may killed!
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	,at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1675),
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1621)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.PluginProvider.update(Unknown Source)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at com.htc.sense.hsp.opensense.pluginmanager.RegisterService.onHandleIntent(Unknown Source)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.471  3639  8627 W [PluginManager]RegisterService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:42.471  4111  8620 W GmsApplication: Using Auth Proxy for data requests.
,08-30 02:50:42.481  3567  8628 I ContextualWidget: com.test.thalitest is not installed,
08-30 02:50:42.481  3567  8628 W MFUDataManager: loadDownloadItems - skip DownloadItem: ApplicationInfo(id=-1, title=null, componentNameComponentInfo{com.test.thalitest/com.test.thalitest.MainActivity} appsContainer=<ALLAPPS> P=UserHandle{0})
08-30 02:50:42.481  3639  8627 I [PluginManager]RegisterService: handle notify Blinkfeed plugin client changed,
08-30 02:50:42.481  3567  8628 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM contextualdownload WHERE component_name=?] disk I/O error
08-30 02:50:42.481  3567  8628 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 02:50:42.481  3567  8628 W HTCLOG  : mask=0x18
08-30 02:50:42.481  3567  8628 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.htc.launcher/databases/launcher.db, handle: 0xabec2078
,08-30 02:50:42.481  3567  8628 E AndroidRuntime: FATAL EXCEPTION: IntentService[HtcContextualWidgetService]
08-30 02:50:42.481  3567  8628 E AndroidRuntime: Process: com.htc.launcher, PID: 3567
08-30 02:50:42.481  3567  8628 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: ,	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
,08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at com.htc.launcher.LauncherProvider.delete(LauncherProvider.java:377)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.loadDownloadItems(MFUDataManager.java:2463)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: ,	at com.htc.launcher.htcwidget.MFUDataManager$DownloadManager.getDownloadList(MFUDataManager.java:2228)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.getDownloadList(MFUDataManager.java:2142)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at com.htc.launcher.htcwidget.MFUDataManager.removeItemsFromDownloadListIfNeed(MFUDataManager.java:2133)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.handlePackageRemoved(HtcContextualWidgetService.java:277)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at com.htc.launcher.htcwidget.HtcContextualWidgetService.onHandleIntent(HtcContextualWidgetService.java:184)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: ,	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.481  3567  8628 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 02:50:42.491  1110  3760 I ActivityManager: Start proc 8629:pl.tmobile.panel/u0a64 for broadcast pl.tmobile.panel/pl.tmobile.idefix.utils.IdefixUninstallListener
,08-30 02:50:42.491  1110  3587 E ActivityManager: App crashed! Process: com.htc.launcher
,08-30 02:50:42.491  1110  3587 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,08-30 02:50:42.501  1110  3587 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
,08-30 02:50:42.501  1110  3587 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:42.501  1110  3587 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:42.501  1110  3587 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:42.501  1110  3587 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:42.501  1110  3587 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:42.501  1110  3587 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:42.501  1110  3587 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:42.501  1110  3587 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:42.501  1110  3587 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:42.501  1110  3587 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:42.501  1110  3587 W System.err: 	... 14 more
08-30 02:50:42.501  1110  3587 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:42.501  1110  3587 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:42.501  1110  3587 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:42.501  1110  3587 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:42.501  1110  3587 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:42.501,  1110  3587 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:42.501  1110  3587 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:42.501  1110  3587 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:42.501  1110  3587 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:42.501  1110  3587 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:42.501  1110  3587 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:42.501  1110  3587 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:42.501  1110  3587 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:42.501  1110  3587 W System.err: 	... 14 more
08-30 02:50:42.511  8629  8629 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:42.511  8629  8629 W HTCLOG  : mask=0x18
08-30 02:50:42.511  1110  8643 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 02:50:42.511  1110  8643 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472518242517.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 02:50:42.511  1110  8643 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:42.511  1110  8643 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:42.511  1110  8643 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:50:42.511  1110  8643 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 02:50:42.511  1110  8643 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:50:42.511  1110  8643 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:42.511  1110  8643 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:42.511  1110  8643 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:42.511  1110  8643 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:42.511  1110  8643 E ErrorReport: 	... 4 more
08-30 02:50:42.511  4111  8620 W GmsApplication: Using Auth Proxy for data requests.
08-30 02:50:42.511  1110  3587 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 02:50:42.521  3567  3567 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@20d4557c for type 0
08-30 02:50:42.521  3567  3567 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@20d4557c for type 1
08-30 02:50:42.521  3567  3567 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@20d4557c for type 3
08-30 02:50:42.521  3567  3567 D HtcThemeUtils: Unregister com.htc.launcher.util.HtcWrapConfigurationActivity$2@20d4557c for type 2
08-30 02:50:42.521  3567  8628 D Process : killProcess, pid=3567
08-30 02:50:42.521  1110  3629 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 02:50:42.521  3567  8628 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 02:50:42.521  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:42.521  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:42.521  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:42.521  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:42.521  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 02:50:42.521  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 02:50:42.521  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 02:50:42.521  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 02:50:42.521  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 02:50:42.521  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 02:50:42.521  1110  3629 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.521  1110  3629 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.521  3567  8628 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:42.521  1110  3629 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:42.521  3567  8628 W HTCLOG  : mask=0x18
08-30 02:50:42.521  1110  3629 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/app_state.db'.
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at com.google.android.gms.common.e.a.delete(SourceFile:258)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.521  4111  8620 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: Runtime exception while performing operation
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at com.google.android.gms.common.e.a.delete(SourceFile:258)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.521  4111  8620 E ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:42.521  1110  3629 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: Can't write: system_app_wtf
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:42.531  1110  8651 E DropBoxManagerService: 	... 5 more
08-30 02:50:42.521  1110  3629 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:42.521  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:42.521  1110  3629 W System.err: 	... 12 more
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: Killing (on development devices) due to RuntimeException
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 ,02:50:42.521  4111  8620 F ClearPendingStateOp: 	at com.google.android.gms.common.e.a.delete(SourceFile:258)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.a.b.a(SourceFile:27)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at com.google.android.gms.appstate.service.AppStateIntentService.onHandleIntent(SourceFile:127)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.521  4111  8620 F ClearPendingStateOp: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:42.551  4111  8604 W DriveInitializer: Awaiting to be initialized
08-30 02:50:42.551  4111  8652 W DriveInitializer: Background init thread started
08-30 02:50:42.561  4111  8652 E SQLiteLog: (3850) statement aborts at 4: [DELETE FROM ContentFileDeletionLock43] disk I/O error
08-30 02:50:42.561  4111  8652 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 02:50:42.561  4111  8652 W HTCLOG  : mask=0x18
08-30 02:50:42.561  4111  8652 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x559321c270
08-30 02:50:42.561  4111  8652 E DocListDatabase: Failed to delete from ContentFileDeletionLock43
08-30 02:50:42.561  4111  8652 E DocListDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 02:50:42.561  4111  8652 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 02:50:42.561  4111  8652 E DocListDatabase: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 02:50:42.561  4111  8652 E DocListDatabase: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 02:50:42.561  4111  8652 E DocListDatabase: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 02:50:42.561  4111  8652 E DocListDatabase: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-30 02:50:42.561  4111  8652 E DocListDatabase: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
08-30 02:50:42.561  4111  8652 E DocListDatabase: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
08-30 02:50:42.561  4111  8652 E DocListDatabase: 	at com.google.android.gms.drive.v.run(SourceFile:69)
08-30 02:50:42.561  4111  8604 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 02:50:42.561  4111  8604 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.gms/databases/DocList.db, handle: 0x559321c270
08-30 02:50:42.561  4111  8604 E DriveAsyncService: disk I/O error (code 3850)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.m(SourceFile:501)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at com.google.android.gms.drive.database.i.c(SourceFile:495)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at com.google.android.gms.drive.database.d.g(SourceFile:1406)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.ao.a(SourceFile:16)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at com.google.android.gms.common.service.c.onHandleIntent(SourceFile:60)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.561  4111  8604 E DriveAsyncService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:42.561  4111  8652 W DriveInitializer: Background init thread ended
08-30 02:50:42.561  4111  8652 E AndroidRuntime: FATAL EXCEPTION: Background initialization thread
08-30 02:50:42.561  4111  8652 E AndroidRuntime: Process: com.google.android.gms, PID: 4111
08-30 02:50:42.561  4111  8652 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 02:50:42.561  4111  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 02:50:42.561  4111  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 02:50:42.561  4111  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 02:50:42.561  4111  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 02:50:42.561  4111  8652 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-30 02:50:42.561  4111  8652 E AndroidRuntime: 	at com.google.android.gms.drive.database.i.a(SourceFile:446)
08-30 02:50:42.561  4111  8652 E AndroidRuntime: 	at com.google.android.gms.drive.database.d.i(SourceFile:1103)
08-30 02:50:42.561  4111  8652 E AndroidRuntime: 	at com.google.android.gms.drive.v.run(SourceFile:69)
08-30 02:50:42.561  1110  4206 E ActivityManager: App crashed! Process: com.google.android.gms
08-30 02:50:42.571  4111  8652 D Process : killProcess, pid=4111
08-30 02:50:42.571  4111  8652 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.gms.common.app.e.uncaughtException:54 java.lang.ThreadGroup.uncaughtException:693 
08-30 02:50:42.571  4111  8652 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: Can't write: system_app_crash
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:42.571  1110  8654 E DropBoxManagerService: 	... 5 more
08-30 02:50:42.571  4111  8652 W HTCLOG  : mask=0x18
,08-30 02:50:42.601  1110  3587 I ActivityManager: Recipient 3567
08-30 02:50:42.601  1110  3101 I WindowState: WIN DEATH: Window{1a6d6e13 u0 com.htc.launcher/com.htc.launcher.Launcher}
,08-30 02:50:42.601  1110  3587 I ActivityManager: Process com.htc.launcher (pid 3567) has died
08-30 02:50:42.601  1110  3587 W ActivityManager: Scheduling restart of crashed service com.htc.launcher/.htcwidget.HtcContextualWidgetService in 1000ms
,08-30 02:50:42.611  1110  3587 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-30 02:50:42.611  1110  3587 V WindowManager: addAppToken: AppWindowToken{eeeba40 token=Token{1ddfe1c3 ActivityRecord{39f4b972 u0 com.htc.launcher/.Launcher t452}}} to stack=0 task=452 at 0
,08-30 02:50:42.621  1110  3587 I ActivityManager: Start proc 8656:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-30 02:50:42.631  8656  8656 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:42.631  8656  8656 W HTCLOG  : mask=0x18
,08-30 02:50:42.641  1110  3101 E MountService: mkdirs when SD card not mounted/storage/ext_sd/Android/data/pl.tmobile.panel/files/,
08-30 02:50:42.641  8629  8629 W ContextImpl: Failed to ensure directory: /storage/ext_sd/Android/data/pl.tmobile.panel/files
,08-30 02:50:42.641  8629  8629 D IdefixUninstallListener: package_removed = com.test.thalitest
,08-30 02:50:42.651  1110  1129 I ActivityManager: Recipient 4111
08-30 02:50:42.651  1110  3546 D PMS     : handleWLDeath(3ad4e045): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
,08-30 02:50:42.651  1110  3536 D PMS     : handleWLDeath(11f7a1b6): PARTIAL_WAKE_LOCK  wake:com.google.android.gms/.config.ConfigFetchService 0x1
08-30 02:50:42.651  1110  1129 I ActivityManager: Process com.google.android.gms (pid 4111) has died
,08-30 02:50:42.651  1110  1129 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
,08-30 02:50:42.681  8629  8629 W HTCLOG  : use specified tag [SQLiteConnection], func [0].,
08-30 02:50:42.681  8629  8629 W HTCLOG  : mask=0x18
,08-30 02:50:42.681  8629  8629 E SQLiteDatabase: Failed to open database '/data/data/pl.tmobile.panel/databases/idefix.db'.,
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
,08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223),
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
,08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:42.681  8629  8629 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:42.681  8629  8629 W System.err: java.sql.SQLException: Getting a writable database from helper a@28dc4611 failed
08-30 02:50:42.681  1110  3383 I ActivityManager: Killing 8012:com.htc.mobiledata:remote/u0a40 (adj 15): empty #17
08-30 02:50:42.681  8629  8629 W System.err: 	at com.j256.ormlite.misc.SqlExceptionUtil.create(SourceFile:22)
08-30 02:50:42.681  8629  8629 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:68)
08-30 02:50:42.681  8629  8629 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadOnlyConnection(SourceFile:54)
08-30 02:50:42.681  8629  8629 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.buildIterator(SourceFile:243)
08-30 02:50:42.681  8629  8629 W System.err: 	at com.j256.ormlite.stmt.StatementExecutor.query(SourceFile:196)
08-30 02:50:42.681  8629  8629 W System.err: 	at com.j256.ormlite.dao.BaseDaoImpl.query(SourceFile:265)
08-30 02:50:42.681  8629  8629 W System.err: 	at pl.tmobile.idefix.utils.IdefixUninstallListener.onReceive(SourceFile:43)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:42.681  8629  8629 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:42.681  8629  8629 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:42.681  8629  8629 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:42.681  8629  8629 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:42.681  8629  8629 W System.err: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQ,LiteConnectionPool.java:182)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:42.681  8629  8629 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:42.681  8629  8629 W System.err: 	at com.j256.ormlite.android.AndroidConnectionSource.getReadWriteConnection(SourceFile:66)
08-30 02:50:42.681  8629  8629 W System.err: 	... 15 more
08-30 02:50:42.681  1110  3383 D Process : killProcessQuiet, pid=8012
08-30 02:50:42.681  1110  3383 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.BroadcastQueue.processCurBroadcastLocked:238 
08-30 02:50:42.681  8656  8656 I MultiDex: VM with version 2.1.0 has multidex support
08-30 02:50:42.681  8656  8656 I MultiDex: install
08-30 02:50:42.681  8656  8656 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 02:50:42.691  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 02:50:42.691  8656  8656 D FaceDetectTask: checkIsOmronEnable start
,08-30 02:50:42.701  8656  8656 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
,08-30 02:50:42.701  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 02:50:42.701  8656  8656 D FaceDetectTask: IsOmronEnable : true
08-30 02:50:42.701  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:42.701  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : null
,08-30 02:50:42.701  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:42.701  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 02:50:42.701  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:42.701  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 02:50:42.701  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 02:50:42.701  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:42.701  8656  8656 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 02:50:42.701  8656  8656 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
,08-30 02:50:42.701  8656  8656 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 02:50:42.701  8656  8656 W HTCLOG  : mask=0x18
,08-30 02:50:42.711  8656  8656 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:42.711  8656  8656 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:42.711  8656  8656 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheH,elper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 02:50:42.711  8656  8656 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.711  8656  8656 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:42.711  8656  8656 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:42.711  8656  8656 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:42.711  8656  8656 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:42.711  8656  8656 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712),
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
,08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102),
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method),
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:42.711  8656  8656 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 02:50:42.711  8656  8656 E AndroidRuntime: FATAL EXCEPTION: main
08-30 02:50:42.711  8656  8656 E AndroidRuntime: Process: com.htc.launcher, PID: 8656
08-30 02:50:42.711  8656  8656 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000),
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
,08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: ,	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825),
08-30 02:50:42.711  8656  8656 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	,at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268),
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103),
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:42.711  8656  8656 E AndroidRuntime: 	... 11 more
,08-30 02:50:42.791  1110  3536 I ActivityManager: Recipient 8012
,08-30 02:50:42.871  3171  3171 D wpa_supplicant: nl80211: Drv Event 34 (NL80211_CMD_NEW_SCAN_RESULTS) received for wlan0
08-30 02:50:42.871  3171  3171 D wpa_supplicant: wlan0: nl80211: New scan results available
08-30 02:50:42.871  3171  3171 D wpa_supplicant: nl80211: Scan probed for SSID ''
08-30 02:50:42.871  3171  3171 D wpa_supplicant: nl80211: Scan included frequencies: 2412 2417 2422 2427 2432 2437 2442 2447 2452 2457 2462 2467 2472 5180 5200 5220 5240 5260 5280 5300 5320 5500 5520 5540 5560 5580 5600 5620 5640 5660 5680 5700 5720 5745 5765 5785 5805 5825
08-30 02:50:42.871  3171  3171 D wpa_supplicant: wlan0: Event SCAN_RESULTS (3) received
08-30 02:50:42.871  3171  3171 I wpa_supplicant: Got an original EVENT_SCAN_RESULTS
,08-30 02:50:42.871  3171  3171 D wpa_supplicant: wlan0: Scan completed in 3.612083 seconds
08-30 02:50:42.871  3171  3171 D wpa_supplicant: nl80211: Received scan results (47 BSSes)
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [NG700] f4:f2:6d:22:99:3e freq=2437 level=-47
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [NG700_GUEST] f0:f2:6d:22:99:3e freq=2437 level=-47
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:7a freq=5200 level=-60
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [TEST_KTW01] 00:1f:27:54:70:c1 freq=2462 level=-56
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:7b freq=5200 level=-61
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:7f freq=5200 level=-61
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [ktwtestwifi] 00:1f:27:54:70:c0 freq=2462 level=-60
,08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 00:16:a6:1f:06:5c freq=2462 level=-66
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:75 freq=2412 level=-72
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:74 freq=2412 level=-72
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:70 freq=2412 level=-72
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:72 freq=2412 level=-72
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:76 freq=2412 level=-73
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [Conrad_AP] 00:1a:ef:42:f2:b0 freq=2422 level=-76
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 00:16:a6:1e:e0:a4 freq=2422 level=-77
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:3a freq=5260 level=-82
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:3f freq=5260 level=-82
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:39 freq=5260 level=-82
,08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:3b freq=5260 level=-82
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d5 freq=2437 level=-79
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d0 freq=2437 level=-79
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d4 freq=2437 level=-79
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d2 freq=2437 level=-80
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:df freq=5180 level=-86
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d9 freq=5180 level=-86
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:32 freq=2412 level=-82
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:34 freq=2412 level=-82
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:21:47:5a freq=5180 level=-87
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:db freq=5180 level=-87
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:21:47:5f freq=5180 level=-87
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:da freq=5180 level=-87
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:21:47:5b freq=5180 level=-88
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:12:64:9a freq=5180 level=-88
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] e4:aa:5d:fc:5b:f0 freq=2437 level=-84
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] e4:aa:5d:fc:5b:f6 freq=2437 level=-85
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:12:64:96 freq=2462 level=-87
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:7e freq=5200 level=-61
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [RA-WINGS] 84:b2:61:1a:ce:73 freq=2412 level=-71
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1a:ce:71 freq=2412 level=-72
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [RA-WINGS] 84:b2:61:1c:62:d3 freq=2437 level=-77
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:0f:9c:3e freq=5260 level=-82
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:1c:62:d1 freq=2437 level=-79
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [RA-WINGS] 84:b2:61:0f:9c:33 freq=2412 level=-82
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [] 84:b2:61:21:47:5e freq=5180 level=-88
08-30 02:50:42.891  1110  3546 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [RA-WINGS] 84:b2:61:12:64:93 freq=2462 level=-86
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [RA-WINGS] e4:aa:5d:fc:5b:f3 freq=2437 level=-86
08-30 02:50:42.901  1110  3027 V AlarmManager: sending alarm PendingIntent{25e4fd79: PendingIntentRecord{359c6c27 com.htc.autobot broadcastIntent}}, i=com.htc.autobot.htcmodeclient.ACTION_RESTART, t=2, cnt=1, w=115781, Int=0
08-30 02:50:42.871  3171  3171 I wpa_supplicant: [RA-WINGS] 00:fe:c8:73:02:03 freq=2462 level=-89
08-30 02:50:42.901  1110  3027 V AlarmManager: sending alarm PendingIntent{3e6389eb: PendingIntentRecord{3b298348 android broadcastIntent}}, i=android.content.jobscheduler.JOB_DELAY_EXPIRED, t=3, cnt=1, w=114778, Int=0
08-30 02:50:42.871  3171  3171 D wpa_supplicant: wlan0: BSS: Start scan result update 8
08-30 02:50:42.871  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 86 BSSID 84:b2:61:0f:9c:32 SSID '\x00'
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 87 BSSID 84:b2:61:12:64:9a SSID '\x00'
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: wlan0: BSS: Add new id 88 BSSID e4:aa:5d:fc:5b:f6 SSID '\x00'
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D ,wpa_supplicant: wlan0: BSS: Add new id 89 BSSID 84:b2:61:21:47:5e SSID '\x00'
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 19 BSSID 84:b2:61:1c:62:d6 SSID '\x00' due to no match in scan
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 55 BSSID e4:aa:5d:fc:5b:f4 SSID '\x00' due to no match in scan
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 48 BSSID 84:b2:61:12:64:92 SSID '\x00' due to no match in scan
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 76 BSSID 00:fe:c8:73:02:04 SSID '\x00' due to no match in scan
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 42 BSSID e4:aa:5d:fc:5b:f1 SSID '\x00' due to no match in scan
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: wlan0: BSS: Remove ID 69 BSSID 84:b2:61:21:47:53 SSID 'RA-WINGS' due to no match in scan
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: BSS: last_scan_res_used=47/64
08-30 02:50:42.881  3171  3171 D wpa_supplicant: wlan0: Scan-only results received
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: CTRL_IFACE monitor sent successfully to /data/misc/wifi/sockets/wpa_ctrl_1110-2\x00
08-30 02:50:42.881  3171  3171 D wpa_supplicant: wlan0: Radio work 'scan'@0x5586db9710 done in 3.668894 seconds
08-30 02:50:42.891  3171  3171 D wpa_supplicant: wlan0: Control interface command 'SET pno 1'
08-30 02:50:42.891  3171  3171 D wpa_supplicant: CTRL_IFACE SET 'pno'='1'
08-30 02:50:42.891  3171  3171 D wpa_supplicant: wlan0: Cancelling scan request
08-30 02:50:42.891  3171  3171 D wpa_supplicant: PNO: No configured SSIDs
08-30 02:50:42.891  1110  3071 D WifiStateMachine: [MLHD] enter handleMediaLinkEvent SupplicantStartedState
08-30 02:50:42.891  1110  3546 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 02:50:42.901  1110  3546 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:42.901  1110  3546 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:42.901  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:42.901  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:42.901  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 02:50:42.901  111,0  3546 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:42.901  1110  3546 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:42.901  1110  3546 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:42.901  1110  3546 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:42.901  1110  3546 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:42.901  1110  3546 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:42.901  1110  3546 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:42.901  1110  3546 W System.err: 	... 14 more
08-30 02:50:42.901  1110  3546 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:42.911  1110  3546 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 02:50:42.901  1110  3546 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:42.911  1110  8686 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 02:50:42.911  1110  8686 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472518242918.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 02:50:42.911  1110  8686 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:42.911  1110  8686 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:42.911  1110  8686 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:50:42.911  1110  8686 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 02:50:42.911  1110  8686 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:50:42.911  1110  8686 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:42.911  1110  8686 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:42.911  1110  8686 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:42.911  1110  8686 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:42.911  1110  8686 E ErrorReport: 	... 4 more
08-30 02:50:42.901  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:42.911  1110  3071 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1465 com.android.server.wifi.WifiStateMachine.sendDongleScanResultsAvailableBroadcast:14959 com.android.server.wifi.WifiStateMachine.handleMediaLinkEvent:15124 com.android.server.wifi.WifiStateMachine.access$5900:305 com.android.server.wifi.WifiStateMachine$SupplicantStartedState.processMessage:8678 
08-30 02:50:42.901  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:42.901  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:42.901  1110  3546 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:42.901  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:42.901  1110  3546 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:42.901  1110  3546 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:42.901  1110  3546 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:42.901  1110  3546 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:42.901  1110  3546 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:42.901  1110  3546 W System.err: 	... 14 more
08-30 02:50:42.911  3171  3171 D wpa_supplicant: wlan0: Control interface command 'LIST_DONGLES'
08-30 02:50:42.911  1110  3629 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 02:50:42.911  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:42.911  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:42.911  8656  8656 D Process : killProcess, pid=8656
08-30 02:50:42.911  8656  8656 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 02:50:42.911  8656  8656 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:42.911  8656  8656 W HTCLOG  : mask=0x18
08-30 02:50:42.921  3171  3171 D wpa_supplicant: wlan0: Control interface command 'BSS RANGE=0- MASK=0x21987'
08-30 02:50:42.931  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:42.931  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:42.931  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 02:50:42.931  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 02:50:42.931  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 02:50:42.931  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 02:50:42.931  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 02:50:42.931  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 02:50:42.931  1110  3629 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:42.931  1110  3629 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:42.931  1110  3629 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:42.931  1110  3629 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:42.931  1110  3629 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:42.931  1110  3629 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:42.931  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:42.931  1110  3629 W System.err: 	... 12 more
08-30 02:50:42.931  6565  8687 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-30 02:50:42.941  3171  3171 D wpa_supplicant: wlan0: Control interface command 'STATUS-NO_EVENTS'
08-30 02:50:42.951  1110  3535 I ActivityManager: Start proc 8688:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
08-30 02:50:42.951  1110  3071 D HtcWifiControlRoamOffload: : roamCandidate: nullcurrentBSSID: null
08-30 02:50:42.951  1110  1110 D WifiNotificationController: setNotificationVisible visible = true, mLowSignalNWs = 15
08-30 02:50:42.951  4431  4431 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 02:50:42.951  1110  3546 I ActivityManager: Recipient 8656
08-30 02:50:42.951  4431  5917 D WifiManager: getScanResults: Base Package Name=com.google.android.gms, uid=10019
08-30 02:50:42.971  8688  8688 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:42.971  8688  8688 W HTCLOG  : mask=0x18
,08-30 02:50:42.971  6565  8687 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-30 02:50:42.971  6565  8687 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 02:50:42.971  6565  8687 W HTCLOG  : mask=0x18
08-30 02:50:42.971  6565  8687 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/data/com.google.android.googlequicksearchbox/databases/icingcorpora.db, handle: 0x5593162ac0
,08-30 02:50:43.011  1110  3546 I ActivityManager: Process com.htc.launcher (pid 8656) has died,
08-30 02:50:43.011  1110  3546 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-30 02:50:43.011  1110  3546 V WindowManager: addAppToken: AppWindowToken{232ef835 token=Token{20253a6c ActivityRecord{37d4d71f u0 com.htc.launcher/.Launcher t453}}} to stack=0 task=453 at 0
,08-30 02:50:43.021  1110  3546 I ActivityManager: Start proc 8709:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
,08-30 02:50:43.031  1110  3629 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
,08-30 02:50:43.031  8709  8709 W HTCLOG  : use specified tag [FDManager], func [0].,
08-30 02:50:43.031  8709  8709 W HTCLOG  : mask=0x18
,08-30 02:50:43.041  6565  8687 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-30 02:50:43.041  6565  8687 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService],
08-30 02:50:43.041  6565  8687 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 6565
08-30 02:50:43.041  6565  8687 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	,at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:583)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:557)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:461)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at com.google.android.search.core.icingsync.b.d(ApplicationsHelper.java:193)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: ,	at com.google.android.search.core.icingsync.ar.g(InternalIcingCorporaProvider.java:548)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:282)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:338)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1398)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: ,	at com.google.android.search.core.icingsync.ba.Zh(UpdateIcingCorporaService.java:358)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at com.google.android.search.core.icingsync.bc.Zj(UpdateIcingCorporaService.java:297)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.ac(UpdateIcingCorporaService.java:194)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.041  6565  8687 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 02:50:43.041  1110  3824 E ActivityManager: App crashed! Process: com.google.android.googlequicksearchbox:search
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: Can't write: system_app_crash
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72),
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:220)
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12682)
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: ,	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.041  1110  8730 E DropBoxManagerService: 	... 5 more
08-30 02:50:43.041  6565  8687 D Process : killProcess, pid=6565
08-30 02:50:43.041  6565  8687 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 com.google.android.velvet.ab.uncaughtException:97 java.lang.ThreadGroup.uncaughtException:693 
08-30 02:50:43.041  6565  8687 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:43.041  6565  8687 W HTCLOG  : mask=0x18
,08-30 02:50:43.061  8688  8688 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2719 
,08-30 02:50:43.081  1110  3587 D PMS     : acquireWL(37619158): PARTIAL_WAKE_LOCK  AsyncService 0x1 8474 10128 null
,08-30 02:50:43.081  1110  1130 D PMS     : releaseWL(37619158): PARTIAL_WAKE_LOCK  AsyncService 0x1 null
,08-30 02:50:43.081  8347  8347 I DeviceManagement: PackageUpdateReceiver: vvv Package removed: [com.test.thalitest]
08-30 02:50:43.091  8347  8347 I DeviceManagement: WorkflowService: Start local workflow: class=[com.htc.cs.dm.workflow.PackageUpdateWorkflow] args=[Bundle[{packageName=com.test.thalitest, operation=3}]]
,08-30 02:50:43.091  8688  8733 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 02:50:43.091  8688  8733 W HTCLOG  : mask=0x18
,08-30 02:50:43.091  8688  8733 E SQLiteDatabase: Failed to open database '/data/data/com.android.keychain/databases/grants.db'.
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.091  8688  8733 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.091  8709  8709 I MultiDex: VM with version 2.1.0 has multidex support
08-30 02:50:43.091  8709  8709 I MultiDex: install
08-30 02:50:43.091  8709  8709 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-30 02:50:43.091  8688  8733 E AndroidRuntime: FATAL EXCEPTION: IntentService[KeyChainService]
08-30 02:50:43.091  8688  8733 E AndroidRuntime: Process: com.android.keychain, PID: 8688
08-30 02:50:43.091  8688  8733 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:18,2)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at com.android.keychain.KeyChainService.purgeOldGrants(KeyChainService.java:402)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at com.android.keychain.KeyChainService.onHandleIntent(KeyChainService.java:396)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.091  8688  8733 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.101  8347  8347 I DeviceManagement: WorkflowService: Starting workflow service
08-30 02:50:43.101  1110  3587 I ActivityManager: Start proc 8735:com.android.documentsui/u0a90 for broadcast com.android.documentsui/.PackageReceiver
08-30 02:50:43.101  1110  4206 E ActivityManager: App crashed! Process: com.android.keychain
08-30 02:50:43.101  1110  4206 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 02:50:43.101  8347  8734 I DeviceManagement: WorkflowService: Executing workflow: workflow=[com.htc.cs.dm.workflow.PackageUpdateWorkflow@150272a1] args=[Bundle[mParcelledData.dataSize=112]]
08-30 02:50:43.101  8347  8734 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-30 02:50:43.101  8347  8734 I DeviceManagement: PackageUpdateWorkflow: Package update: package=com.test.thalitest, operation=REMOVE
08-30 02:50:43.101  8347  8734 I DeviceManagement: PackageUpdateWorkflow: ==================================================
08-30 02:50:43.101  1110  4206 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.101  1110  4206 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.101  1110  4206 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.101  1110  4206 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.101  1110  4206 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityM,anagerService.java:12602)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.101  1110  4206 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.101  1110  4206 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.101  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 02:50:43.101  1110  4206 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.101  8709  8709 D FaceDetectTask: checkIsOmronEnable start
08-30 02:50:43.101  1110  4206 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.101  1110  4206 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.101  1110  4206 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.101  1110  4206 W System.err: 	... 14 more
08-30 02:50:43.101  1110  4206 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.101  1110  4206 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.101  1110  4206 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.101  1110  4206 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.101  1110  4206 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 02:50:43.101  1110  4206 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 02:50:43.111  1110  4206 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.111  1110  4206 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.111  1110  4206 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.111  1110  4206 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.111  1110  8742 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 02:50:43.111  1110  8742 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472518243119.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 02:50:43.111  1110  8742 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.111  1110  8742 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.111  1110  8742 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:50:43.111  1110  8742 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 02:50:43.111  1110  8742 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:50:43.111  1110  8742 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.111  1110  8742 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.111  1110  8742 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.111  1110  8742 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.111  1110  8742 E ErrorReport: 	... 4 more
08-30 02:50:43.111  1110  4206 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.111  1110  4206 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.111  1110  4206 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.111  8709  8709 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so
08-30 02:50:43.111  1110  4206 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.111  1110  4206 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.111  1110  4206 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.111  1110  4206 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.111  1110  4206 W System.err: 	... 14 more
08-30 02:50:43.111  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.111  8709  8709 D FaceDetectTask: IsOmronEnable : true
08-30 02:50:43.111  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.111  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 02:50:43.111  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.111  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.111  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.111  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.111  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.111  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.111  8709  8709 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.111  8688  8733 D Process : killProcess, pid=8688
08-30 02:50:43.111  8709  8709 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-30 02:50:43.111  8709  8709 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 02:50:43.111  8709  8709 W HTCLOG  : mask=0x18
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:43.121  8709  8709 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.121  8709  8709 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 02:50:43.121  8709  8709 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.121  8709  8709 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:43.121  8709  8709 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:43.131  1110  3824 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 02:50:43.121  8709  8709 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:43.121  8709  8709 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:43.121  8709  8709 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:43.121  1110  3629 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.121  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.121  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.121  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.121  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.121  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 02:50:43.121  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 02:50:43.121  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 02:50:43.121  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 02:50:43.121  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 02:50:43.121  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 02:50:43.121  1110  3629 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.131  1110  3824 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 02:50:43.121  1110  3629 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.121  1110  3629 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.121  1110  3629 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.121  1110  3629 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.121  1110  3629 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.121  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.121  1110  3629 W System.err: 	... 12 more
08-30 02:50:43.121  8735  8735 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:43.121  8735  8735 W HTCLOG  : mask=0x18
08-30 02:50:43.121  8688  8733 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 02:50:43.121  8688  8733 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:43.121  8688  8733 W HTCLOG  : mask=0x18
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:43.121  8709  8709 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: FATAL EXCEPTION: main
08-30 02:50:43.121  8709  8709 E AndroidRuntime: Process: com.htc.launcher, PID: 8709
08-30 02:50:43.121  8709  8709 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:43.121  8709  8709 E AndroidRuntime: 	... 11 more
08-30 02:50:43.131  1110  8764 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 02:50:43.131  1110  8764 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472518243145.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 02:50:43.131  1110  8764 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.131  1110  8764 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.131  1110  8764 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:50:43.131  1110  8764 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 02:50:43.131  1110  8764 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:50:43.131  1110  8764 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.131  1110  8764 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.131  1110  8764 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.131  1110  8764 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.131  1110  8764 E ErrorReport: 	... 4 more
08-30 02:50:43.121   551   551 I art     : Explicit concurrent mark sweep GC freed 8644(367KB) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 131us total 24.195ms
08-30 02:50:43.141  1110  4172 I ActivityManager: Recipient 6565
08-30 02:50:43.131  1110  3824 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 02:50:43.141  1110  3072 D WifiService: Client connection lost with reason: 4
08-30 02:50:43.131  8347  8734 I DeviceManagement: ModelRegistry: Loading model meta data from resources...
08-30 02:50:43.131  1110  3824 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.131  1110  3824 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.131  1110  3824 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.131  1110  3824 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.131  1110  3824 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.131  1110  3824 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.131  1110  3824 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.131  1110  3824 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.131  1110  3824 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.131  1110  3824 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.131  1110  3824 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.131  1110  3824 W System.err: 	... 14 more
08-30 02:50:43.131  1110  3824 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.131  1110  3824 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.131  1110  3824 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,08-30 02:50:43.131  1110  3824 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.131  1110  3824 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.131  1110  3824 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.131  1110  3824 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.131  1110  3824 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.131  1110  3824 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.131  1110  3824 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.131  1110  3824 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.131  1110  3824 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.131  1110  3824 W System.err: 	... 14 more
08-30 02:50:43.131  8709  8709 D Process : killProcess, pid=8709
08-30 02:50:43.131  8709  8709 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 02:50:43.131  8709  8709 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:43.131  8709  8709 W HTCLOG  : mask=0x18
08-30 02:50:43.141  1110  3629 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.141  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.141  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.141  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.141  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.141  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 02:50:43.141  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 02:50:43.141  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 02:50:43.141  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 02:50:43.141  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 02:50:43.141  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 02:50:43.141  1110  3629 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.141  1110  3629 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.141  1110  3629 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.141  1110  3629 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.151   551   551 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 128us total 20.170ms
08-30 02:50:43.151  1110  3629 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.151  1110  3629 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.151  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.151  1110  3629 W System.err: 	... 12 more
08-30 02:50:43.161  8347  8734 I DeviceManagement: BackgroundController: *** Processing package remove for appID=com.test.thalitest
08-30 02:50:43.161  1110  4172 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 6565) has died
08-30 02:50:43.161  1110  4172 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 10490ms
08-30 02:50:43.171   551   551 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 96% free, 163KB/4MB, paused 135us total 17.271ms
08-30 02:50:43.161  1110  4172 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 20490ms
08-30 02:50:43.171  1110  4172 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.htc.launcher/.Launcher} from uid 0 pid 0 on display 0
08-30 02:50:43.171  1110  4172 V WindowManager: addAppToken: AppWindowToken{230a6b04 token=Token{2db48b17 ActivityRecord{25ffa396 u0 com.htc.launcher/.Launcher t454}}} to stack=0 task=454 at 0
08-30 02:50:43.171  8347  8766 I DeviceManagement: SessionStateController: Checking invariants...
08-30 02:50:43.181  8735  8735 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 02:50:43.191  8735  8735 W HTCLOG  : mask=0x18
08-30 02:50:43.191  1110  4206 I ActivityManager: Recipient 8688
08-30 02:50:43.191  1110  4206 I ActivityManager: Process com.android.keychain (pid 8688) has died
,08-30 02:50:43.191  8735  8735 E SQLiteDatabase: Failed to open database '/data/data/com.android.documentsui/databases/recents.db'.
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:43.191  8735  8735 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:43.191  1110  4206 W ActivityManager: Scheduling restart of crashed service com.android.keychain/.KeyChainService in 20467ms
08-30 02:50:43.191  8735  8735 E AndroidRuntime: FATAL EXCEPTION: main
08-30 02:50:43.191  8735  8735 E AndroidRuntime: Process: com.android.documentsui, PID: 8735
08-30 02:50:43.191,  8735  8735 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.android.documentsui.PackageReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2733)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.app.ActivityThread.access$1700(ActivityThread.java:151)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1467)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.purgeByAuthority(RecentsProvider.java:343)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at com.android.documentsui.RecentsProvider.call(RecentsProvider.java:289)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.content.ContentProvider$Transport.call(ContentProvider.java:380)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.content.ContentResolver.call(ContentResolver.java:1437)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at com.android.documentsui.PackageReceiver.onReceive(PackageReceiver.java:45)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2719)
08-30 02:50:43.191  8735  8735 E AndroidRuntime: 	... 9 more
08-30 02:50:43.191  11,10  3546 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 02:50:43.191  1110  3546 E ActivityManager: App crashed! Process: com.android.documentsui
08-30 02:50:43.191  1110  3546 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.191  1110  3546 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.191  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.191  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.191  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.191  1110  3546 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.191  1110  3546 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.191  1110  3546 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  8768 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 02:50:43.201  1110  8768 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472518243209.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  8768 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.201  1110  8768 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.201  1110  8768 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:50:43.201  1110  8768 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 02:50:43.201  1110  8768 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:50:43.201  1110  8768 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  8768 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.201  1110  8768 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.201  1110  8768 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.201  1110  8768 E ErrorReport: 	... 4 more
08-30 02:50:43.191  1110  3546 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.201  1110  3383 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 02:50:43.191  1110  3546 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.201  1110  8769 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 02:50:43.201  1110  8769 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472518243214.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  8769 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.201  1110  8769 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.201  1110  8769 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:50:43.201  1110  8769 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 02:50:43.201  1110  8769 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:50:43.201  1110  8769 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  8769 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.201  1110  8769 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.201  1110  8769 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.201  1110  8769 E ErrorReport: 	... 4 more
08-30 02:50:43.191  1110  3546 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.191  1110  3546 W System.err: 	... 14 more
08-30 02:50:43.191  1110  3546 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.191  1110  3546 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.191  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.191  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.191  1110  3546 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.191  1110  3546 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.191  1110  3546 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.191  1110  3546 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.201  1110  3546 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  3546 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.201  1110  3546 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.201  1110  3546 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.201  1110  3546 W System.err: 	... 14 more
08-30 02:50:43.201  5669  5857 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM downloads WHERE (uid=10142)] disk I/O error
08-30 02:50:43.201  5669  5857 W HTCLOG  : use specified tag [SQLiteDBG], func [0].
08-30 02:50:43.201  5669  5857 W HTCLOG  : mask=0x18
08-30 02:50:43.201  5669  5857 E SQLiteDBG: func: executeNonQuery, errno: 9, error msg: Bad file number, path: /data/user/0/com.android.providers.downloads/databases/downloads.db, handle: 0x5593128720
08-30 02:50:43.201  8735  8735 D Process : killProcess, pid=8735
08-30 02:50:43.201  8735  8735 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 02:50:43.201  8735  8735 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:43.201  8735  8735 W HTCLOG  : mask=0x18
08-30 02:50:43.201  5669  5857 E AndroidRuntime: FATAL EXCEPTION: DownloadReceiver
08-30 02:50:43.201  5669  5857 E AndroidRuntime: Process: android.process.media, PID: 5669
08-30 02:50:43.201  5669  5857 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:762)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1598)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at com.android.providers.downloads.DownloadProvider.delete(DownloadProvider.java:1484)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.handleUidRemoved(DownloadReceiver.java:138)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver.access$000(DownloadReceiver.java:47)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at com.android.providers.downloads.DownloadReceiver$1.run(DownloadReceiver.java:100)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.201  5669  5857 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.201  1110  3383 E ActivityManager: App crashed! Process: android.process.media
08-30 02:50:43.201  1110  3629 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.201  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.201  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.201  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.201  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 02:50:43.201  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 02:50:43.201  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 02:50:43.201  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 02:50:43.201  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 02:50:43.201  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 02:50:43.201  1110  3629 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.201  1110  3629 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.201  1110  3629 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.201  1110  3629 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  3629 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.201  1110  3629 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.201  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.201  1110  3629 W System.err: 	... 12 more
08-30 02:50:43.201  1110  3383 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  3383 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.201  1110  3383 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.201  1110  3383 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.201  1110  3383 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.221  1110  1156 I ActivityManager: Start proc 8770:com.htc.htcpowermanager:remote/1000 for broadcast com.htc.htcpowermanager/.battery.PowerUsageReceiver
08-30 02:50:43.201  1110  3383 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.221  1110  3760 I ActivityManager: Recipient 8709
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.201  1110  3383 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.201  1110  3383 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.201  1110  3383 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  3383 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.201  1110  3383 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.201  1110  3383 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.201  1110  3383 W System.err: 	... 14 more
08-30 02:50:43.201  1110  3383 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  3383 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.201  1110  3383 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.201  1110  3383 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.201  1110  3383 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.201  1110  3383 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.201  1110  3383 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.201  1110  3383 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.201  1110  3383 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.201  1110  3383 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.201  1110  3383 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.201  1110  3383 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.221  1110  3760 I ActivityManager: Process com.htc.launcher (pid 8709) has died
08-30 02:50:43.201  1110  3383 W System.err: 	... 14 more
08-30 02:50:43.201  5669  5857 D Process : killProcess, pid=5669
08-30 02:50:43.201  5669  5857 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 02:50:43.211  5669  5857 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:43.211  5669  5857 W HTCLOG  : mask=0x18
08-30 02:50:43.211  1110  3629 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.211  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.211  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.211  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.211  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.211  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 02:50:43.211  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 02:50:43.211  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 02:50:43.211  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 02:50:43.211  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 02:50:43.211  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 02:50:43.211  1110  3629 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.211  1110  3629 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.211  1110  3629 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.211  1110  3629 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.211  1110  3629 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.211  1110  3629 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.211  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.211  1110  3629 W System.err: 	... 12 more
08-30 02:50:43.221  8770  8770 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:43.221  8770  8770 W HTCLOG  : mask=0x18
,08-30 02:50:43.241  1110  3760 I ActivityManager: Start proc 8789:com.htc.launcher/u0a56 for activity com.htc.launcher/.Launcher
08-30 02:50:43.241   494   494 E lowmemorykiller: Error writing /proc/5669/oom_score_adj; errno=22
08-30 02:50:43.241  1110  3629 D HtcSystemUPManager: HtcSystemUPolicy [canLog (default)] category: launch, enable: true
08-30 02:50:43.241  8789  8789 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:43.241  8789  8789 W HTCLOG  : mask=0x18
08-30 02:50:43.271  8770  8770 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1830 android.content.ContextWrapper.startService:516 android.content.ContextWrapper.startService:516 com.htc.htcpowermanager.battery.PowerUsageReceiver.onReceive:23 android.app.ActivityThread.handleReceiver:2719 
,08-30 02:50:43.281  8770  8812 D PowerUtils: getUserIdOfProcess, curUserId = 0
,08-30 02:50:43.281  8770  8812 D PowerUtils: isRunningUnderOwner, isOwner = true,
,08-30 02:50:43.291  8789  8789 I MultiDex: VM with version 2.1.0 has multidex support,
08-30 02:50:43.291  8789  8789 I MultiDex: install
08-30 02:50:43.291  8789  8789 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-30 02:50:43.301  8813  8813 W HTCLOG  : use specified tag [FDManager], func [0].
08-30 02:50:43.301  8813  8813 W HTCLOG  : mask=0x18
,08-30 02:50:43.301  1110  4172 I ActivityManager: Start proc 8813:com.htc.updater/u0a68 for broadcast com.htc.updater/.download.DownloadReceiver
08-30 02:50:43.301  8770  8812 D PowerUsageList:PowerUsageHelper: MY_DEBUG = false
08-30 02:50:43.301  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : null,
08-30 02:50:43.301  8789  8789 D FaceDetectTask: checkIsOmronEnable start
,08-30 02:50:43.301  8789  8789 D MorphoNativeMemoryAllocator: load libmorpho_memory_allocator.so,
,08-30 02:50:43.311  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 02:50:43.311  8789  8789 D FaceDetectTask: IsOmronEnable : true
08-30 02:50:43.311  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.311  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : null
08-30 02:50:43.311  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 02:50:43.311  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.311  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
,08-30 02:50:43.311  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.311  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.311  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.311  8789  8789 D FaceDetectTask: sOmronFaceDetectTaskClass : class com.htc.lib2.opensense.facedetect.OmronFaceDetectTask
08-30 02:50:43.311  8789  8789 I HighlightSelectCacheHelper: [custom highlight] loadHighlightSelection()
08-30 02:50:43.311  8789  8789 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 02:50:43.311  8789  8789 W HTCLOG  : mask=0x18
08-30 02:50:43.311  8770  8812 D PowerUsageService: removed uid = 10142
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/highlight_selection.db'.
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429),
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: ,	,at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:43.311  8789  8789 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
,08-30 02:50:43.311  8789  8789 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
,08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.321  1110  3535 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.311  8789  8789 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.loadHighlightSelection(HighlightSelectCacheHelper.java:319)
08-30 02:50:43.311  8789  8789 W System.err: 	at com.htc.launcher.feeds.HighlightSelectCacheHelper.onCreate(HighlightSelectCacheHelper.java:83)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:43.311  8770  8812 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 02:50:43.311  8770  8812 W HTCLOG  : mask=0x18
08-30 02:50:43.311  8789  8789 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.311  8789  8789 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:43.311  8789  8789 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:43.311  8789  8789 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:43.311  8789  8789 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:43.311  8789  8789 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: Failed to open database '/data/data/com.htc.htcpowermanager/databases/SmartSync.db'.
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method,)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	,at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.321  8770  8812 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: FATAL EXCEPTION: IntentService[PowerUsageService]
08-30 02:50:43.321  8770  8812 E AndroidRuntime: Process: com.htc.htcpowermanager:remote, PID: 8770
08-30 02:50:43.321  8770  8812 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at com.htc.htcpowermanager.smartsync.SmartSyncProvider.delete(SmartSyncProvider.java:386)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	,at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	,at android.content.ContentResolver.delete(ContentResolver.java:1364)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageHelper.deleteUid(PowerUsageHelper.java:2155)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at com.htc.htcpowermanager.battery.PowerUsageService.onHandleIntent(PowerUsageService.java:108)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.321  8770  8812 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.331  1110  3101 I ActivityManager: Recipient 5669
08-30 02:50:43.321  8347  8766 W HTCLOG  : use specified tag [SQLiteConnection], func [0].
08-30 02:50:43.331  1110  3760 I ActivityManager: Recipient 8735
08-30 02:50:43.321  8347  8766 W HTCLOG  : mask=0x18
08-30 02:50:43.331  1110  3101 I ActivityManager: Process android.process.media (pid 5669) has died
08-30 02:50:43.321  1110  3535 E ActivityManager: App crashed! Process: com.htc.htcpowermanager:remote
08-30 02:50:43.331  1110  3101 W ActivityManager: Scheduling restart of crashed service com.android.providers.media/.MtpService in 20325ms
08-30 02:50:43.321  1110  3535 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.query(EnabledAppProviderDAO.java:108)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.query(ProvProvider.java:123)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.content.ContentProvider.query(ContentProvider.java:976),
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.query(ContentProvider.java:221)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:156)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at android.content.ContentProviderClient.query(ContentProviderClient.java:120)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledAppUsingCP(EnabledAppDAO.java:137)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.access$100(EnabledAppDAO.java:28)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:125)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$2.call(EnabledAppDAO.java:121)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.getEnabledApp(EnabledAppDAO.java:121)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.checkPreconditions(ConfigManagerController.java:276)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.controller.ConfigManagerController.getConfigBundle(ConfigManagerController.java:147)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigFromDM(CoreConfigModel.java:393)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.fetchConfigAndUpdate(CoreConfigModel.java:351)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.CoreConfigModel.onFetch(CoreConfigModel.java:206)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModelCollection.onFetch(BaseModelCollection.java:111)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.dm.config.model.DataBindingConfigModel.onFetch(DataBindingConfigModel.java:280)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel.handleFetch(BaseModel.java:197)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.util.model.BaseModel$1.doInBackground(BaseModel.java:176)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:101)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at com.htc.cs.util.model.ModelAsyncTask$1.call(ModelAsyncTask.java:90)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
08-30 02:50:43.321  8347  8766 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:50:43.321  1110  3535 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.321  1110  3535 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.321  1110  3535 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.341  1110  8844 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 02:50:43.341  1110  8844 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_APP_CRASH@1472518243351.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 02:50:43.341  1110  8844 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.341  1110  8844 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.341  1110  8844 E ErrorReport: 	at java.io.FileOutputStream.<init>(Fi,leOutputStream.java:72)
08-30 02:50:43.341  1110  8844 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458)
08-30 02:50:43.341  1110  8844 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:50:43.341  1110  8844 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.341  1110  8844 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.341  1110  8844 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.341  1110  8844 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.341  1110  8844 E ErrorReport: 	... 4 more
08-30 02:50:43.321  1110  3535 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.341  1110  1130 I ActivityManager: Killing 7672:com.htc.mobiledata/u0a40 (adj 15): empty #17
08-30 02:50:43.321  1110  3535 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.321  1110  3535 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.321  1110  3535 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.321  1110  3535 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.321  1110  3535 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.321  1110  3535 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.351  1110  3536 I ActivityManager: Recipient 7672
08-30 02:50:43.321  1110  3535 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.321  1110  3535 W System.err: 	... 14 more
08-30 02:50:43.321  1110  3535 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.321  1110  3535 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.321  1110  3535 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.321  1110  3535 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.321  1110  3535 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.321  1110  3535 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.321  1110  3535 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.321  1110  3535 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.321  1110  3535 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.321  1110  3535 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.321  1110  3535 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.321  1110  3535 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.321  1110  3535 W System.err: 	... 14 more
08-30 02:50:43.331  8347  8766 I DeviceManagement: ModelAsyncTask: Caught exception running async model handler: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.331  8347  8734 I DeviceManagement: DMConfigController: Ignoring exception fetching DM Core config: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.331  8347  8734 I DeviceManagement: BackgroundController: Ensure removal of obsolete app cache entries: appID=com.test.thalitest
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: Failed to open database '/data/data/com.htc.cs.dm/databases/provisioning.db'.
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.331  8347  8734 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.331  3347  3860 D DotMatrix: [NotificationService] onNotificationRemoved, pkgName: com.android.providers.media, id: 1, tag: null, isClearable: false, isForDotMatrix: false
08-30 02:50:43.331  8347  8734 W DeviceManagement: WorkflowService: Uncaught throwable executing workflow [com.htc.cs.dm.workflow.PackageUpdateWorkflow@150272a1]android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.withTx(EnabledAppProviderDAO.java:79)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.provider.EnabledAppProviderDAO.delete(EnabledAppProviderDAO.java:265)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.delete(ProvProvider.java:335)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:322)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.content.ContentProviderClient.delete(ContentProviderClient.java:263)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:289)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO$6.call(EnabledAppDAO.java:283)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.provider.ProvProvider.withCPClient(ProvProvider.java:448)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.content.EnabledAppDAO.delete(EnabledAppDAO.java:283)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.controller.EnabledAppController.remove(EnabledAppController.java:263)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.removeObsoleteAppID(BackgroundController.java:684)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.controller.BackgroundController.updateAfterPackageRemove(BackgroundController.java:657)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.onUpdate(PackageUpdateWorkflow.java:105)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.dm.workflow.PackageUpdateWorkflow.call(PackageUpdateWorkflow.java:62)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.executeWorkflow(WorkflowService.java:321)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at com.htc.cs.util.workflow.WorkflowService.onHandleIntent(WorkflowService.java:295)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.331  8347  8734 W DeviceManagement: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.341  8347  8347 I DeviceManagement: WorkflowService: Stopping workflow service
08-30 02:50:43.341  1110  3629 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.341  3196  3196 I NotificationStackScrollLayout: setBlockTouchEnabled:false
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: Failed to open database '/data/user/0/com.htc.launcher/databases/externalapp.db'.
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:43.341  8789  8789 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: FATAL EXCEPTION: main
08-30 02:50:43.341  8789  8789 E AndroidRuntime: Process: com.htc.launcher, PID: 8789
08-30 02:50:43.341  8789  8789 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.htc.launcher.ExternalAppStateProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5432)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5000)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4940)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:151)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1442)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5725)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1030)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:825)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:235)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:219)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:468)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:190)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:182)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:874)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:854)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:752)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1286)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:268)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.reInitalizeExternalAppsStateMaxId(ExternalAppStateProvider.java:103)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at com.htc.launcher.ExternalAppStateProvider.onCreate(ExternalAppStateProvider.java:25)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1712)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1681)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5429)
08-30 02:50:43.341  8789  8789 E AndroidRuntime: 	... 11 more
08-30 02:50:43.341  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.341  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.341  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.341  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.341  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 02:50:43.341  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 02:50:43.341  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 02:50:43.341  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
08-30 02:50:43.341  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 02:50:43.341  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 02:50:43.341  1110  3629 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.341  1110  3629 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.341  1110  3629 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.341  1110  3629 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.341  1110  1130 D Process : killProcessQuiet, pid=7672
08-30 02:50:43.341  1110  3629 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.341  1110  3629 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.341  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.341  1110  3629 W System.err: 	... 12 more
08-30 02:50:43.341  1110  1130 D Process : com.android.server.am.ProcessRecord.kill:585 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19468 com.android.server.am.ActivityManagerService.updateOomAdjLocked:19311 
08-30 02:50:43.341  8770  8812 D Process : killProcess, pid=8770
08-30 02:50:43.341  8770  8812 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 02:50:43.341  8770  8812 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:43.341  8770  8812 W HTCLOG  : mask=0x18
,08-30 02:50:43.531  1110  3824 I ActivityManager: Recipient 8770,
,08-30 02:50:43.551  1110  3538 E ActivityManager: App crashed! Process: com.htc.launcher
08-30 02:50:43.551  1110  3538 D ErrorReport: HtcErrorReportManager Begin---add error logs to dropbox
,08-30 02:50:43.561  1110  3538 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system),
08-30 02:50:43.581  1110  3824 I ActivityManager: Process com.htc.htcpowermanager:remote (pid 8770) has died,
08-30 02:50:43.561  1110  3538 W System.err: ,	at libcore.io.IoBridge.open(IoBridge.java:456)
,08-30 02:50:43.581  1110  3824 W ActivityManager: Scheduling restart of crashed service com.htc.htcpowermanager/.battery.PowerUsageService in 30075ms
08-30 02:50:43.561  1110  3538 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87),
08-30 02:50:43.581  1110  3760 I ActivityManager: Process com.android.documentsui (pid 8735) has died
08-30 02:50:43.561  1110  3538 W System.err: ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.591  1110  3538 W ActivityManager:   Force finishing activity 1 com.htc.launcher/.Launcher
08-30 02:50:43.561  1110  3538 W System.err: ,	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
,08-30 02:50:43.601  1110  8845 E ErrorReport: HtcErrorReportManager.Error in dumping error information
08-30 02:50:43.601  1110  8845 E ErrorReport: java.io.FileNotFoundException: /data/misc/HTC_HOME_RESTART@1472518243608.dbox_tmp: open failed: EROFS (Read-only file system)
08-30 02:50:43.601  1110  8845 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.601  1110  8845 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,08-30 02:50:43.601  1110  8845 E ErrorReport: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 02:50:43.601  1110  8845 E ErrorReport: 	at com.android.server.am.HtcErrorReportManager$1.run(HtcErrorReportManager.java:458),
08-30 02:50:43.601  1110  8845 E ErrorReport: 	at java.lang.Thread.run(Thread.java:818)
08-30 02:50:43.601  1110  8845 E ErrorReport: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.601  1110  8845 E ErrorReport: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.601  1110  8845 E ErrorReport: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,08-30 02:50:43.601  1110  8845 E ErrorReport: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.601  1110  8845 E ErrorReport: 	,... 4 more
08-30 02:50:43.561  1110  3538 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
,08-30 02:50:43.561  1110  3538 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.561  1110  3538 W System.err: ,	at com.htc.server.report.error.ErrorReportPreference.getSecretKey(ErrorReportPreference.java:61)
08-30 02:50:43.561  1110  3538 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:302)
08-30 02:50:43.561  1110  3538 W System.err: ,	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.561  1110  3538 W System.err: ,	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.561  1110  3538 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.561  1110  3538 W System.err: ,	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.561  1110  3538 W System.err: ,	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
08-30 02:50:43.561  1110  3538 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.561  1110  3538 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
,08-30 02:50:43.561  1110  3538 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.561  1110  3538 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.561  1110  3538 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
,08-30 02:50:43.561  1110  3538 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 02:50:43.561  1110  3538 W System.err: 	... 14 more
08-30 02:50:43.571  1110  3538 W System.err: java.io.FileNotFoundException: /data/system/error_report/errorreport.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.571  1110  3538 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.571  1110  3538 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 02:50:43.571  1110  3538 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.571  1110  3538 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.571  1110  3538 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.writeProperty(ErrorReportPreference.java:142)
08-30 02:50:43.571  1110  3538 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.setProperty(ErrorReportPreference.java:109)
08-30 02:50:43.571  1110  3538 W System.err: 	at com.htc.server.report.error.ErrorReportPreference.getIV(ErrorReportPreference.java:85)
,08-30 02:50:43.571  1110  3538 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTCInner(HtcErrorReportManager.java:303)
08-30 02:50:43.571  1110  3538 W System.err: 	at com.android.server.am.HtcErrorReportManager.addErrorToDropBoxForHTC(HtcErrorReportManager.java:260)
08-30 02:50:43.571  1110  3538 W System.err: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12602)
08-30 02:50:43.571  1110  3538 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:12266)
08-30 02:50:43.571  1110  3538 W System.err: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:12238)
08-30 02:50:43.571  1110  3538 W System.err: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:1413)
,08-30 02:50:43.571  1110  3538 W System.err: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2379)
08-30 02:50:43.571  1110  3538 W System.err: 	at android.os.Binder.execTransact(Binder.java:454)
08-30 02:50:43.571  1110  3538 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.571  1110  3538 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.571  1110  3538 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.571  1110  3538 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
,08-30 02:50:43.571  1110  3538 W System.err: 	... 14 more
08-30 02:50:43.601  8789  8789 D Process : killProcess, pid=8789
08-30 02:50:43.601  8789  8789 D Process : com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException:138 java.lang.ThreadGroup.uncaughtException:693 java.lang.ThreadGroup.uncaughtException:690 
08-30 02:50:43.601  8789  8789 W HTCLOG  : use specified tag [Process], func [0].
08-30 02:50:43.601  8789  8789 W HTCLOG  : mask=0x18
08-30 02:50:43.601  1110  3629 W System.err: java.io.FileNotFoundException: /data/system/systemup_pref.xml: open failed: EROFS (Read-only file system)
08-30 02:50:43.601  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 02:50:43.601  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
,08-30 02:50:43.601  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:127)
08-30 02:50:43.601  1110  3629 W System.err: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:116)
08-30 02:50:43.601  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.writeProperty(HtcSystemUPPreference.java:119)
08-30 02:50:43.601  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setProperty(HtcSystemUPPreference.java:86)
08-30 02:50:43.601  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPPreference.setLong(HtcSystemUPPreference.java:60)
08-30 02:50:43.601  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.addErrorCount(HtcSystemUPHandler.java:294)
,08-30 02:50:43.601  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessageInternal(HtcSystemUPHandler.java:73)
08-30 02:50:43.601  1110  3629 W System.err: 	at com.htc.upm.HtcSystemUPHandler.handleMessage(HtcSystemUPHandler.java:46)
08-30 02:50:43.601  1110  3629 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 02:50:43.601  1110  3629 W System.err: 	at android.os.Looper.loop(Looper.java:155)
08-30 02:50:43.601  1110  3629 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 02:50:43.601  1110  3629 W System.err: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 02:50:43.601  1110  3629 W System.err: 	at libcore.io.Posix.open(Native Method)
08-30 02:50:43.601  1110  3629 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 02:50:43.601  1110  3629 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
,08-30 02:50:43.601  1110  3629 W System.err: 	... 12 more
,08-30 02:50:43.671  1110  1156 I ActivityManager: Start proc 8849:com.google.android.gms/u0a19 for service com.google.android.gms/.analytics.service.AnalyticsService
,08-30 02:50:43.671  8849  8849 W HTCLOG  : use specified tag [FDManager], func [0].
,08-30 02:50:43.671  8849  8849 W HTCLOG  : mask=0x18

```
