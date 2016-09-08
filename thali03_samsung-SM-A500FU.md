#### Test 845006541145c7f_thali03_samsung-SM-A500FU Logs


```
--------- beginning of system
09-08 21:15:45.919  1015  2789 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
--------- beginning of main
09-08 21:15:46.119   288   288 E SMD     : DCD OFF
09-08 21:15:46.179  1015  1133 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-08 21:15:46.179  1015  1133 D BatteryService: level:80, scale:100, status:2, health:2, present:true, voltage: 4095, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-08 21:15:46.179  1015  1133 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-08 21:15:46.179  1015  1133 D BatteryService: stay LED for charging
09-08 21:15:46.179  1015  1015 D BatteryService: Sending ACTION_BATTERY_CHANGED.
09-08 21:15:46.189  1015  1015 I MotionRecognitionService: Plugged
09-08 21:15:46.189  1015  1015 I MotionRecognitionService: mGripSensorEnabled= false
09-08 21:15:46.189  1177  1177 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-08 21:15:46.189  1177  1177 D KeyguardUpdateMonitor: handleBatteryUpdate
09-08 21:15:46.199  1414  1414 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-08 21:15:46.199  1414  1414 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 80
09-08 21:15:46.209  2647  2647 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-08 21:15:46.209  2647  2738 D HeadsetStateMachine: Disconnected process message: 10
09-08 21:15:46.219  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:80 status:2 health:2
09-08 21:15:46.219  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:80 status:2 health:2
09-08 21:15:46.219  1177  1177 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:80 status:2 health:2
,09-08 21:15:46.549  6351  6351 D AndroidRuntime: 
09-08 21:15:46.549  6351  6351 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-08 21:15:46.559  6351  6351 D AndroidRuntime: CheckJNI is OFF
09-08 21:15:46.559  6351  6351 D AndroidRuntime: readGMSProperty: start
09-08 21:15:46.559  6351  6351 D AndroidRuntime: readGMSProperty: already setted!!
09-08 21:15:46.559  6351  6351 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-08 21:15:46.559  6351  6351 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-08 21:15:46.559  6351  6351 D AndroidRuntime: readGMSProperty: end
09-08 21:15:46.559  6351  6351 D AndroidRuntime: addProductProperty: start
09-08 21:15:46.719  6351  6351 E AffinityControl: AffinityControl: registerfunction enter
09-08 21:15:46.739  6351  6351 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-08 21:15:46.749  1015  1248 E PersonaManagerService: inState():  stateMachine is null !!
09-08 21:15:46.749  1015  1248 I PersonaManagerService: PersonaId don't exist
09-08 21:15:46.749  1015  1248 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-08 21:15:46.749  1015  1248 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 21:15:46.769  1015  1248 W ActivityManager: mDVFSHelper.acquire()
09-08 21:15:46.779  1015  1045 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-08 21:15:46.779  1015  1045 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-08 21:15:46.779  1015  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:46.789  1015  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:46.789  1015  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:46.789  1015  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:46.799  6362  6362 E Zygote  : MountEmulatedStorage()
09-08 21:15:46.799  6362  6362 E Zygote  : v2
09-08 21:15:46.799  6362  6362 I libpersona: KNOX_SDCARD checking this for 10155
09-08 21:15:46.799  6362  6362 I libpersona: KNOX_SDCARD not a persona
09-08 21:15:46.799  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-08 21:15:46.799  1015  1248 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6362 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-08 21:15:46.799  1015  1045 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-08 21:15:46.799  1015  1248 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-08 21:15:46.799  1015  1248 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 21:15:46.799  6362  6362 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-08 21:15:46.799   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-08 21:15:46.809  6362  6362 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-08 21:15:46.809  6362  6362 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-08 21:15:46.809  1015  1248 D InputDispatcher: Focused application set to: xxxx
09-08 21:15:46.809  1015  1248 D InputDispatcher: Focus left window: 3166
09-08 21:15:46.809  6351  6351 D AndroidRuntime: Shutting down VM
09-08 21:15:46.829  6362  6362 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 21:15:46.829  6362  6362 D ActivityThread: Added TimaKeyStore provider
09-08 21:15:46.839  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-08 21:15:46.839  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 21:15:46.839  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-08 21:15:46.849  1015  1028 D PersonaManager: isKioskContainerExistOnDevice
09-08 21:15:46.889   258   600 I SurfaceFlinger: id=10 Removed YUIInstallC (5/9)
09-08 21:15:46.889   258   434 I SurfaceFlinger: id=10 Removed YUIInstallC (-2/9)
09-08 21:15:46.899  3166  3166 V ActivityThread: updateVisibility : ActivityRecord{1c98215f token=android.os.BinderProxy@3a740ce2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-08 21:15:46.969  6362  6362 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-08 21:15:46.979  6362  6362 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7756-7758)
09-08 21:15:46.979  6362  6362 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 21:15:47.009  6362  6362 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b69434b}
09-08 21:15:47.009  6362  6362 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 21:15:47.009  6362  6362 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 21:15:47.019  6351  6351 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-08 21:15:47.049  6362  6362 I BrowserStartupController: Initializing chromium process, singleProcess=true,
,09-08 21:15:47.049  6362  6362 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 21:15:47.049  6362  6362 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-08 21:15:47.069  6362  6362 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-08 21:15:47.069  6362  6362 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,09-08 21:15:47.069  6362  6362 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-08 21:15:47.079  6362  6362 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-08 21:15:47.079  6362  6362 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-08 21:15:47.079  6362  6362 I Adreno-EGL: Build Date: 04/06/15 Mon
09-08 21:15:47.079  6362  6362 I Adreno-EGL: Local Branch: 
09-08 21:15:47.079  6362  6362 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-08 21:15:47.079  6362  6362 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-08 21:15:47.079  6362  6362 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-08 21:15:47.139  1015  1047 I PowerManagerService: [PWL] Off : 180s ago
,09-08 21:15:47.199  6362  6388 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-08 21:15:47.249  6362  6362 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 21:15:47.259  6362  6362 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 21:15:47.269  6362  6362 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-08 21:15:47.269  6362  6362 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-08 21:15:47.279  6362  6362 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-08 21:15:47.279  6362  6362 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-08 21:15:47.279  6362  6362 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-08 21:15:47.329  6362  6401 D OpenGLRenderer: Render dirty regions requested: true
,09-08 21:15:47.329  1015  1508 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-08 21:15:47.329  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-08 21:15:47.329  1015  1508 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-08 21:15:47.329  1015  1508 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-08 21:15:47.329  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-08 21:15:47.349  6362  6362 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,09-08 21:15:47.349  6362  6362 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-08 21:15:47.349   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-08 21:15:47.359  1015  1340 E Watchdog: !@Sync 8
,09-08 21:15:47.359  1015  1027 D InputDispatcher: Focus entered window: 6362,
,09-08 21:15:47.359  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 21:15:47.359  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
09-08 21:15:47.359  6362  6362 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-08 21:15:47.359  6362  6401 I OpenGLRenderer: Initialized EGL, version 1.4
09-08 21:15:47.369  6362  6401 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
09-08 21:15:47.369  6362  6401 D OpenGLRenderer: Enabling debug mode 0
,09-08 21:15:47.429  6362  6362 V ActivityThread: updateVisibility : ActivityRecord{26126e22 token=android.os.BinderProxy@3a42be04 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-08 21:15:47.429  1015  3037 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-08 21:15:47.429  1015  6404 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 21:15:47.429  1177  1177 D PanelView: There is/are notification(s) 
,09-08 21:15:47.439  6362  6362 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-08 21:15:47.449  1863  1863 I SamsungIME: getCurrentCandidateView
,09-08 21:15:47.469  6362  6362 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3a42be04 time:258241
,09-08 21:15:47.469  1015  1045 I ActivityManager: Displayed Component not be shown by security: +612ms (total +2m23s509ms)
,09-08 21:15:47.469  1015  1045 W ActivityManager: mDVFSHelper.release()
09-08 21:15:47.469  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c15327a u0 com.test.thalitest/.MainActivity t129} time:258245
09-08 21:15:47.469   258   428 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-08 21:15:47.479   258   601 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-08 21:15:47.519  6362  6362 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6362
,09-08 21:15:47.549  1863  1863 D SamsungIME: Dismiss ExpandCandiate
,09-08 21:15:47.559  1015  2742 D SSRM:n  : SIOP:: AP = 270
,09-08 21:15:47.629  6362  6362 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 21:15:47.689  1863  1863 I SamsungIME: getDebugLevel  : 0x4f4c
,09-08 21:15:47.719  1863  1863 I SamsungIME: getDebugLevel  : 0x4f4c
,09-08 21:15:47.739  6362  6406 D jxcore_app_log: JniHelper::setJavaVM(0xb7e0c328), pthread_self() = -1204359432
,09-08 21:15:47.739  1863  1863 I SamsungIME: KeybaordView init() : load resources
,09-08 21:15:47.749  6362  6406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 21:15:47.749  6362  6406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 21:15:47.749  6362  6406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 21:15:47.749  6362  6406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 21:15:47.749  6362  6406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 21:15:47.749  6362  6406 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3116a3d2 added. We now have 1 listener(s)
,09-08 21:15:47.749  6362  6406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-08 21:15:47.749  6362  6406 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-08 21:15:47.749  6362  6406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 21:15:47.749  6362  6406 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-08 21:15:47.759  6362  6406 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39de3359 added. We now have 1 listener(s)
09-08 21:15:47.759  6362  6406 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 21:15:47.769  1863  1863 I SamsungIME: getCurrentKeyboard
09-08 21:15:47.769  1863  1863 I SamsungIME: getTextKeyboard
,09-08 21:15:47.769  6362  6406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 21:15:47.769  6362  6406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-08 21:15:47.769  6362  6406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 21:15:47.769  6362  6406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 21:15:47.769  6362  6406 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-08 21:15:47.769  6362  6406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 21:15:47.779  6362  6406 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-08 21:15:47.779  1863  1863 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-08 21:15:47.789  6362  6406 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
09-08 21:15:47.789  6362  6406 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 21:15:47.789  6362  6406 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 21:15:47.789  6362  6406 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 21:15:47.789  6362  6406 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 21:15:47.789  6362  6406 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 21:15:47.789  6362  6406 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 21:15:47.789  6362  6406 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 21:15:47.789  6362  6406 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 21:15:47.789  6362  6406 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 21:15:47.789  6362  6406 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 21:15:47.789  6362  6406 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 21:15:47.789  6362  6362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:15:47.789  6362  6362 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 21:15:47.809  6362  6362 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 21:15:48.359  1863  6411 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-08 21:15:48.569  6362  6412 W jxcore-log: Initializing JXcore engine
09-08 21:15:48.569  6362  6412 W jxcore-log: JXcore engine is ready
,09-08 21:15:48.619  1870  1870 E audit   : type=1400 msg=audit(1473362148.619:205): avc:  denied  { ioctl } for  pid=6412 comm="Thread-1078" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 21:15:48.619  1870  1870 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-08 21:15:48.619  1870  1870 E audit   : type=1300 msg=audit(1473362148.619:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=2 a3=9ec008f8 items=0 ppid=306 ppcomm=main pid=6412 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1078" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-08 21:15:48.619  1870  1870 E audit   : type=1320 msg=audit(1473362148.619:205): 
09-08 21:15:48.629  6362  6412 W jxcore-log: Starting JXcore engine
,09-08 21:15:48.729  6362  6412 W jxcore-log: Platform android
09-08 21:15:48.729  6362  6412 W jxcore-log: 
09-08 21:15:48.729  6362  6412 W jxcore-log: Process ARCH arm
09-08 21:15:48.729  6362  6412 W jxcore-log: 
,09-08 21:15:48.989  6362  6412 I jxcore-log: JXcore Cordova bridge is ready!
09-08 21:15:48.989  6362  6412 I jxcore-log: 
,09-08 21:15:48.989  6362  6412 W jxcore-log: JXcore engine is started
,09-08 21:15:48.999  6362  6406 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 21:15:48.999  6362  6362 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 21:15:49.009  6362  6412 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
09-08 21:15:49.009  6362  6412 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,09-08 21:15:49.019  6362  6362 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,09-08 21:15:49.019  6362  6362 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,09-08 21:15:49.019  1015  4345 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 21:15:49.019  1015  4345 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-08 21:15:49.019  1015  4345 D InputDispatcher: Focused application set to: xxxx
,09-08 21:15:49.029  1015  4345 I ActivityManager: Killing 5088:com.sec.android.gallery3d/u0a44 (adj 15): empty #31,
,09-08 21:15:49.039  6362  6362 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-08 21:15:49.039  6362  6362 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,09-08 21:15:49.049  6362  6362 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 21:15:49.049  6362  6362 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 21:15:49.049  6362  6362 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-08 21:15:49.049  6362  6362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 21:15:49.049  6362  6362 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3116a3d2 removed from the list
09-08 21:15:49.049  6362  6362 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 21:15:49.049  6362  6362 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39de3359 removed from the list
09-08 21:15:49.049  6362  6362 D io.jxcore.node.ConnectivityMonitor: stop
09-08 21:15:49.049  6362  6362 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,09-08 21:15:49.049  6362  6362 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-08 21:15:49.079   258   428 I SurfaceFlinger: id=14 Removed NainActivit (6/8)
09-08 21:15:49.089   258   600 I SurfaceFlinger: id=14 Removed NainActivit (-2/8),
,09-08 21:15:49.089  1015  1133 D InputDispatcher: Focus left window: 6362
,09-08 21:15:49.099  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 21:15:49.099  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 21:15:49.099  1015  1335 W ActivityManager: mDVFSHelper.acquire()
,09-08 21:15:49.099  6362  6362 E ViewRootImpl: sendUserActionEvent() mView == null
,09-08 21:15:49.119   288   288 E SMD     : DCD OFF
,09-08 21:15:49.129  3166  3166 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-08 21:15:49.139  3166  3166 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-08 21:15:49.159  3166  3166 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-08 21:15:49.159  3166  3166 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-08 21:15:49.169  3166  3166 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-08 21:15:49.169  3166  3166 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-08 21:15:49.179  3166  3166 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-08 21:15:49.189  3166  3166 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-08 21:15:49.199  3166  3166 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-08 21:15:49.209  1015  1335 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,09-08 21:15:49.209  1015  1335 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-08 21:15:49.209  1015  1015 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,09-08 21:15:49.219  1177  1177 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-08 21:15:49.219  3166  3166 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-08 21:15:49.219  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,09-08 21:15:49.219  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
,09-08 21:15:49.219  1177  1177 D PanelView: There is/are notification(s) 
,09-08 21:15:49.219  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-08 21:15:49.219  3166  3166 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0,
09-08 21:15:49.219  1177  1177 D PersonaManager: isKioskContainerExistOnDevice
09-08 21:15:49.219  1177  1177 D PanelView: There is/are notification(s) 
09-08 21:15:49.219  1177  1177 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-08 21:15:49.229  3166  3166 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-08 21:15:49.229  3166  3166 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
09-08 21:15:49.229  3166  3166 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
09-08 21:15:49.229  3166  3166 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-08 21:15:49.229  1015  4345 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-08 21:15:49.229  1015  1015 D PersonaManagerService: getPersonasForUser(): returning null!
09-08 21:15:49.229  1015  4345 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-08 21:15:49.229  1015  4345 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-08 21:15:49.229  1015  1015 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-08 21:15:49.229  3166  3166 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-08 21:15:49.239   258   258 I SurfaceFlinger: id=15 createSurf (720x1280),1 flag=404, YUIInstallC
,09-08 21:15:49.239  1015  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-08 21:15:49.239  1015  1027 D InputDispatcher: Focus entered window: 3166
,09-08 21:15:49.239  1015  1045 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-08 21:15:49.239  1015  1045 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-08 21:15:49.239  3166  3166 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-08 21:15:49.249  3166  3166 V ActivityThread: updateVisibility : ActivityRecord{1c98215f token=android.os.BinderProxy@3a740ce2 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-08 21:15:49.249  1015  3037 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-08 21:15:49.249  1015  6419 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-08 21:15:49.259  6362  6362 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-08 21:15:49.259  1863  1863 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-08 21:15:49.259  1177  1177 D PanelView: There is/are notification(s) 
,09-08 21:15:49.269  3166  3166 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3a740ce2 time:260046
,09-08 21:15:49.289  1015  1045 W ActivityManager: mDVFSHelper.release()
,09-08 21:15:49.289  1177  1177 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-08 21:15:49.289  1015  1045 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7982f4c u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:260068
,09-08 21:15:49.309  6415  6415 D AndroidRuntime: 
09-08 21:15:49.309  6415  6415 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-08 21:15:49.309  6415  6415 D AndroidRuntime: CheckJNI is OFF
,09-08 21:15:49.309  6415  6415 D AndroidRuntime: readGMSProperty: start
09-08 21:15:49.309  6415  6415 D AndroidRuntime: readGMSProperty: already setted!!
,09-08 21:15:49.309  6415  6415 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-08 21:15:49.309  6415  6415 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-08 21:15:49.309  6415  6415 D AndroidRuntime: readGMSProperty: end
09-08 21:15:49.309  6415  6415 D AndroidRuntime: addProductProperty: start,
,09-08 21:15:49.459  6415  6415 E AffinityControl: AffinityControl: registerfunction enter,
09-08 21:15:49.479  6415  6415 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-08 21:15:49.489  1015  1248 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-08 21:15:49.489  1015  1248 D PackageManager: START PACKAGE DELETE: observer{1062286206}
09-08 21:15:49.489  1015  1248 D PackageManager: pkg{<packageName>}
09-08 21:15:49.489  1015  1248 D PackageManager: user{0}
09-08 21:15:49.489  1015  1248 D PackageManager: caller{2000}
09-08 21:15:49.489  1015  1248 D PackageManager: flags{2}
09-08 21:15:49.489  1015  1248 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-08 21:15:49.489  1015  1055 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-08 21:15:49.489  1015  1248 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-08 21:15:49.489  1015  1055 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
09-08 21:15:49.489  1015  1248 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-08 21:15:49.489  1015  1040 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
09-08 21:15:49.489  1015  1248 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-08 21:15:49.489  1015  1040 I ActivityManager: Killing 6362:com.test.thalitest/u0a155 (adj 9): stop com.test.thalitest cause uninstall pkg
09-08 21:15:49.489  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-08 21:15:49.489  1015  1055 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-08 21:15:49.489  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled
09-08 21:15:49.489  1015  1055 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
09-08 21:15:49.499  1015  1040 D PersonaManager: isKioskContainerExistOnDevice
,09-08 21:15:49.609  1015  1055 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-08 21:15:49.619  1015  1055 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-08 21:15:49.659  3932  3932 I art     : Explicit concurrent mark sweep GC freed 2590(159KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 6MB/11MB, paused 721us total 32.409ms
,09-08 21:15:49.669  5517  5517 I art     : Explicit concurrent mark sweep GC freed 398(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 750us total 40.047ms
,09-08 21:15:49.679  1015  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-08 21:15:49.679  5798  5798 I art     : Explicit concurrent mark sweep GC freed 97(15KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 652us total 56.758ms
,09-08 21:15:49.689  1863  1863 E SamsungIME: mOCRHelper is null
,09-08 21:15:49.699  1884  2116 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-08 21:15:49.719  3884  3884 I art     : Explicit concurrent mark sweep GC freed 19920(1235KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 15MB/21MB, paused 1.327ms total 80.774ms
,09-08 21:15:49.729  3690  3690 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Sep 08 21:15:49 GMT+02:00 2016
,09-08 21:15:49.729  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,09-08 21:15:49.739  1015  1120 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-08 21:15:49.739  1015  1120 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 21:15:49.739  1015  1120 V NetworkStats: performPollLocked(flags=0x3)
,09-08 21:15:49.739  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox updated
09-08 21:15:49.739  1015  1120 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-08 21:15:49.739  1015  4345 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-08 21:15:49.739  1015  4345 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-08 21:15:49.749  1439  1439 D RegisteredServicesCache: empty dynamic service
,09-08 21:15:49.749  1015  1120 V NetworkStats: performPollLocked() took 12ms
09-08 21:15:49.749  1015  1120 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 21:15:49.749  1015  4345 W ActivityManager: userId = 0, bbcId = -10000
,09-08 21:15:49.749  1015  4345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 21:15:49.749  1015  4345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-08 21:15:49.759  3690  3690 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-08 21:15:49.759  1439  1439 D RegisteredComponentCache: Collect Tech packages for Knox
,09-08 21:15:49.759  1015  3344 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
09-08 21:15:49.759  1015  3344 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-08 21:15:49.769  1015  3344 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-08 21:15:49.769  1015  3344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:49.769  1015  3344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:49.769  1015  3344 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:49.769  1015  3344 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:49.779  1015  1039 D EnterpriseDeviceManagerService: Package has changed for user 0
09-08 21:15:49.779  1015  1039 W TextServicesManagerService: no available spell checker services found
09-08 21:15:49.779  1015  1039 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-08 21:15:49.779  6431  6431 E Zygote  : MountEmulatedStorage()
09-08 21:15:49.779  6431  6431 E Zygote  : v2
09-08 21:15:49.779  6431  6431 I libpersona: KNOX_SDCARD checking this for 10094
09-08 21:15:49.779  6431  6431 I libpersona: KNOX_SDCARD not a persona
,09-08 21:15:49.779  6431  6431 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 21:15:49.789  6431  6431 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 21:15:49.789  1015  3344 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6431 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,09-08 21:15:49.789  3690  3690 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
09-08 21:15:49.789  6431  6431 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 21:15:49.799  1439  1439 D PersonaManager: isKioskContainerExistOnDevice
,09-08 21:15:49.809  3690  3690 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-08 21:15:49.809  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:49.819  3690  3690 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-08 21:15:49.819  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-08 21:15:49.819  1015  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-08 21:15:49.829  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-08 21:15:49.829  1015  1133 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-08 21:15:49.829  1015  1133 D SecContentProvider2: mCursor = null
,09-08 21:15:49.829  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:49.829  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:49.829  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:49.829  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:49.839  6431  6431 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 21:15:49.839  6431  6431 D ActivityThread: Added TimaKeyStore provider
09-08 21:15:49.839  6446  6446 E Zygote  : MountEmulatedStorage()
09-08 21:15:49.839  6446  6446 E Zygote  : v2
09-08 21:15:49.839  6446  6446 I libpersona: KNOX_SDCARD checking this for 10044
09-08 21:15:49.839  6446  6446 I libpersona: KNOX_SDCARD not a persona
09-08 21:15:49.839  6446  6446 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-08 21:15:49.839  6446  6446 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-08 21:15:49.839  6446  6446 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-08 21:15:49.839  1015  1040 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=6446 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
09-08 21:15:49.849  3690  6430 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-08 21:15:49.849  1015  1015 I art     : Explicit concurrent mark sweep GC freed 62098(4MB) AllocSpace objects, 61(976KB) LOS objects, 33% free, 28MB/42MB, paused 6.987ms total 226.537ms
,09-08 21:15:49.859  1015  1055 I art     : WaitForGcToComplete blocked for 128.547ms for cause Explicit
09-08 21:15:49.859  3690  6430 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,09-08 21:15:49.859  3690  6430 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-08 21:15:49.859  3690  6430 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-08 21:15:49.869  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-08 21:15:49.869  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:49.869  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:49.869  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:49.869  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:49.879  6462  6462 E Zygote  : MountEmulatedStorage()
09-08 21:15:49.879  6462  6462 E Zygote  : v2
09-08 21:15:49.879  6462  6462 I libpersona: KNOX_SDCARD checking this for 10149
09-08 21:15:49.879  6462  6462 I libpersona: KNOX_SDCARD not a persona
,09-08 21:15:49.879  6462  6462 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 21:15:49.889  1015  1040 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6462 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-08 21:15:49.889  6462  6462 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 21:15:49.889  6462  6462 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 21:15:49.889  6446  6446 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 21:15:49.899  6446  6446 D ActivityThread: Added TimaKeyStore provider
,09-08 21:15:49.919  6462  6462 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 21:15:49.919  6462  6462 D ActivityThread: Added TimaKeyStore provider
,09-08 21:15:49.929  6431  6431 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-08 21:15:49.929  6431  6431 D elm:15183: ELMEngine.ELMEngine( context ).
,09-08 21:15:49.929  6431  6431 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-08 21:15:49.939  1015  3346 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-08 21:15:49.939  1015  3346 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,09-08 21:15:49.939  1015  3346 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:49.939  6446  6446 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-08 21:15:49.939  6446  6446 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 21:15:49.939  6446  6446 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-08 21:15:49.939  6446  6446 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-08 21:15:49.939  6446  6446 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-08 21:15:49.939  6446  6446 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-08 21:15:49.939  6446  6446 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-08 21:15:49.939  6446  6446 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-08 21:15:49.939  1015  3346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 21:15:49.939  1015  3346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-08 21:15:49.949  3690  6430 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-08 21:15:49.949  6431  6431 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-08 21:15:49.959  3690  6430 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-08 21:15:49.959  3690  6430 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-08 21:15:49.959  3690  3690 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-08 21:15:49.959  6431  6431 D elm:15183: ElmAgentService : onCreate()
,09-08 21:15:49.959  6431  6477 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-08 21:15:49.959  6431  6477 D elm:15183: MainReceiver.listeningToPackageRemoved()
09-08 21:15:49.959  6431  6477 D elm:15183: MDMBridge.getInstance()
09-08 21:15:49.959  6431  6477 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-08 21:15:49.969  6431  6477 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-08 21:15:49.969  3320  3320 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,09-08 21:15:49.969  3320  3320 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-08 21:15:49.969  3320  3320 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
09-08 21:15:49.969  3320  3320 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
09-08 21:15:49.969  3320  3320 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-08 21:15:49.969  3320  3320 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-08 21:15:49.969  3320  3320 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-08 21:15:49.969  3320  3320 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:15:49.969  3320  3320 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-08 21:15:49.969  3320  3320 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-08 21:15:49.969  3320  3320 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 21:15:49.969  3320  3320 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-08 21:15:49.969  3320  3320 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-08 21:15:49.969  3320  3320 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-08 21:15:49.979  6431  6431 D elm:15183: ElmAgentService : onDestroy().
,09-08 21:15:49.979  5798  6461 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-08 21:15:49.989  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:49.989  6462  6462 D ThemeInfoUtil: getCurrentFestivalName is [null]
,09-08 21:15:49.989  5798  5798 I art     : Explicit concurrent mark sweep GC freed 472(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 6MB/9MB, paused 781us total 54.900ms
,09-08 21:15:49.989  6462  6462 D ThemeInfoUtil: isCurrentFestival = false
,09-08 21:15:49.999  1015  1028 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
09-08 21:15:49.999  1015  1028 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-08 21:15:49.999  1015  1028 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:49.999  1015  1028 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 21:15:49.999  1015  1028 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,09-08 21:15:50.009  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:50.009  5915  5915 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-08 21:15:50.009  5915  5915 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,09-08 21:15:50.009  5915  5915 I TapandpayWidget:Utils: Clear T&P info.
,09-08 21:15:50.019  5169  5169 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-08 21:15:50.019  1015  1248 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,09-08 21:15:50.019  1015  1248 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.019  5915  5915 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-08 21:15:50.019  1015  1248 W ActivityManager: userId = 0, bbcId = -10000
,09-08 21:15:50.019  1015  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 21:15:50.019  1015  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-08 21:15:50.029  1015  1508 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,09-08 21:15:50.029  1015  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.029  1015  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.029  1015  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.029  1015  1508 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.039  6481  6481 E Zygote  : MountEmulatedStorage()
,09-08 21:15:50.039  6481  6481 I libpersona: KNOX_SDCARD checking this for 10160
09-08 21:15:50.039  6481  6481 E Zygote  : v2
09-08 21:15:50.039  6481  6481 I libpersona: KNOX_SDCARD not a persona
09-08 21:15:50.039  6481  6481 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-08 21:15:50.049  1015  1508 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=6481 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,09-08 21:15:50.049  6481  6481 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 21:15:50.049  6481  6481 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-08 21:15:50.069  6481  6481 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 21:15:50.069  6481  6481 D ActivityThread: Added TimaKeyStore provider
,09-08 21:15:50.089  6010  6022 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,09-08 21:15:50.089  6010  6022 D BadgeProvider: sendNotify, [notify] : null
,09-08 21:15:50.089  6010  6022 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
,09-08 21:15:50.089  6010  6022 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-08 21:15:50.089  6010  6022 D BadgeProvider: update, [UpdateCount] : 1
,09-08 21:15:50.099  5595  5595 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-08 21:15:50.109  1015  1248 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,09-08 21:15:50.109  1015  1248 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-08 21:15:50.109  6481  6481 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-08 21:15:50.139  1015  3346 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,09-08 21:15:50.139  1015  3346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.139  1015  3346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.139  1015  3346 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.139  1015  3346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.149  6481  6481 D [0]UMC:UMCContentProvider: @onCreate
,09-08 21:15:50.159  6498  6498 E Zygote  : MountEmulatedStorage()
,09-08 21:15:50.159  6498  6498 E Zygote  : v2
09-08 21:15:50.159  6498  6498 I libpersona: KNOX_SDCARD checking this for 1000
09-08 21:15:50.159  6498  6498 I libpersona: KNOX_SDCARD not a persona
,09-08 21:15:50.159  6498  6498 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 21:15:50.159  6498  6498 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-08 21:15:50.159  1015  3346 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6498 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-08 21:15:50.159  6498  6498 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 21:15:50.159  1015  3346 I ActivityManager: Killing 5536:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,09-08 21:15:50.169  6481  6481 D [0]UMC:Core: onCreate(): 
09-08 21:15:50.169  6481  6481 D [0]UMC:Core: @isManagedProfileUser
09-08 21:15:50.169  6481  6481 D [0]UMC:Core: userId: 0
,09-08 21:15:50.169  6481  6481 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
09-08 21:15:50.169  6481  6481 D [0]UMC:Core: userInfo.isManagedProfile() : false
,09-08 21:15:50.179  6481  6481 D [0]UMC:DeviceInfo: USA==US==
,09-08 21:15:50.199  6498  6498 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 21:15:50.199  6498  6498 D ActivityThread: Added TimaKeyStore provider
,09-08 21:15:50.209  6446  6446 D NearbySource: Nearby Source Create!
,09-08 21:15:50.209  6446  6446 D NearbyContext: Nearby Context Create!
,09-08 21:15:50.239  1015  1039 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-08 21:15:50.249  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:50.249  6498  6498 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,09-08 21:15:50.249  1015  3345 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
09-08 21:15:50.249  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:50.249  1015  3345 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.249  1015  3345 W ActivityManager: userId = 0, bbcId = -10000
,09-08 21:15:50.249  1015  3345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 21:15:50.249  1015  3345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,09-08 21:15:50.259  1015  1133 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
,09-08 21:15:50.259  1015  1015 D RCPManagerService: PackageReceiver onReceive()
,09-08 21:15:50.259  1015  1015 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-08 21:15:50.259  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.259  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.259  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.259  1015  1133 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.259  1015  1015 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,09-08 21:15:50.259  1015  1015 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-08 21:15:50.269  1015  1015 D OTPFW   : OtpDbHelper::getInstance New instance created,
,09-08 21:15:50.269  1015  1015 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-08 21:15:50.269   257   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-08 21:15:50.269   257   519 W Vold    : Returning OperationFailed - no handler for errno 0
,09-08 21:15:50.279  6446  6446 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache,
09-08 21:15:50.279  1015  1015 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
09-08 21:15:50.279  1015  1055 I art     : Explicit concurrent mark sweep GC freed 14410(739KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 28MB/42MB, paused 5.501ms total 416.976ms,
09-08 21:15:50.279  1015  1015 I OTPFW   : ProvisionData::getAllEntries Enter
09-08 21:15:50.279  1015  1015 E OTPFW   : ProvisionData::getAllEntries Table is empty,
09-08 21:15:50.279  6481  6481 D USER_AGENT: UMC/1.4.2 (SM-A500FU) SAFE-5.4 KNOX-2.4 en_US,
09-08 21:15:50.289  1015  1015 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) },
09-08 21:15:50.279  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:50.289  1015  1015 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 21:15:50.289  6446  6446 D SLinkSource: Samsung link source created
09-08 21:15:50.289  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED,
09-08 21:15:50.289  1015  1015 V EnterpriseBillingPolicy: uID is 10155
09-08 21:15:50.289  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-08 21:15:50.289  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-08 21:15:50.289  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-08 21:15:50.289  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-08 21:15:50.289  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,09-08 21:15:50.289  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-08 21:15:50.289  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-08 21:15:50.289  6514  6514 E Zygote  : MountEmulatedStorage()
09-08 21:15:50.289  6514  6514 E Zygote  : v2
09-08 21:15:50.289  6514  6514 I libpersona: KNOX_SDCARD checking this for 1000
09-08 21:15:50.289  6514  6514 I libpersona: KNOX_SDCARD not a persona
,09-08 21:15:50.299  6514  6514 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-08 21:15:50.299  1015  1133 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6514 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-08 21:15:50.299  1015  1015 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-08 21:15:50.299  6481  6481 D [0]UMC:AdminManager: init - start
,09-08 21:15:50.299  6514  6514 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-08 21:15:50.299  1015  2742 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-08 21:15:50.299  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-08 21:15:50.299  1015  1015 V EnterpriseBillingPolicy: uID is 10155
09-08 21:15:50.299  1015  1015 V EnterpriseBillingPolicy: Removed Packageuid is0
09-08 21:15:50.299  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-08 21:15:50.299  1015  1015 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-08 21:15:50.299  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-08 21:15:50.299  1015  1015 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-08 21:15:50.299  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-08 21:15:50.299  6514  6514 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-08 21:15:50.299  1015  1015 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-08 21:15:50.309  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=129_task.xml
09-08 21:15:50.319  1015  1159 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-08 21:15:50.319  1015  1015 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-08 21:15:50.319  6514  6514 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 21:15:50.319  6514  6514 D ActivityThread: Added TimaKeyStore provider
,09-08 21:15:50.329  6481  6481 D [0]UMC:AdminManager: loadAdmins
,09-08 21:15:50.339  5849  5849 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-08 21:15:50.339  5849  5849 I PCWCLIENTTRACE_PushUtil: sales region : global
09-08 21:15:50.339  5849  5849 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-08 21:15:50.339  5849  5849 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-08 21:15:50.349  6481  6481 D [0]UMC:AdminManager: init - end
,09-08 21:15:50.349  6481  6481 D GSLBManager: migrateStoredUrlFromOldPref
,09-08 21:15:50.359  1015  1039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-08 21:15:50.359  1015  1039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-08 21:15:50.359  1015  1039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-08 21:15:50.359  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:50.369  6481  6481 D GSLBManager: migrateStoredUrlFromOldPref : Migration Not Needed
,09-08 21:15:50.369  1015  1055 D PackageManager: delete codoeFile: 
,09-08 21:15:50.369  6481  6481 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,09-08 21:15:50.369  1015  1248 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-08 21:15:50.369  1015  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.369  6481  6481 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,09-08 21:15:50.369  1015  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.369  1015  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.369  1015  1248 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.379  1015  1055 I AASA_removePackage: UID=10155 Target=com.test.thalitest
09-08 21:15:50.379  1015  1055 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,09-08 21:15:50.389  6481  6481 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
09-08 21:15:50.389  6481  6481 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
09-08 21:15:50.389  6481  6481 D [0]UMC:UMCAdmin: isContainer : 0
,09-08 21:15:50.389  6534  6534 E Zygote  : MountEmulatedStorage()
,09-08 21:15:50.389  6534  6534 E Zygote  : v2
09-08 21:15:50.389  6534  6534 I libpersona: KNOX_SDCARD checking this for 10035
09-08 21:15:50.389  6534  6534 I libpersona: KNOX_SDCARD not a persona
,09-08 21:15:50.389  6534  6534 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 21:15:50.389  1015  1248 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=6534 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-08 21:15:50.389  6534  6534 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 21:15:50.389  6534  6534 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-08 21:15:50.389  1015  1484 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 21:15:50.399  1015  1335 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
09-08 21:15:50.399  1015  1055 D PackageManager: result of delete: 1{1062286206}
,09-08 21:15:50.399  6481  6481 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
09-08 21:15:50.399  1015  1248 I ActivityManager: Killing 5627:com.google.android.apps.plus/u0a120 (adj 15): empty #31
09-08 21:15:50.399  6481  6481 D [0]UMC:UMCAdmin: isContainer : 0
,09-08 21:15:50.409  1015  1335 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-08 21:15:50.409  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:50.409  6446  6446 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-08 21:15:50.409  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:50.409  6415  6415 D AndroidRuntime: Shutting down VM
09-08 21:15:50.409  6446  6531 D ContactProvider: getAllContactInfoList Start
,09-08 21:15:50.419  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 21:15:50.419  1015  3344 I ActivityManager: Killing 5868:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
09-08 21:15:50.419  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-08 21:15:50.419  6481  6481 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
09-08 21:15:50.419  6514  6545 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
,09-08 21:15:50.419  6514  6545 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-08 21:15:50.429  1015  1335 D ActivityManager: startService callerProcessName:com.sec.enterprise.knox.cloudmdm.smdms, calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms
09-08 21:15:50.429  1015  1335 D ActivityManager: retrieveServiceLocked(): component = com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService; callingUser = 0; userId(target) = 0
09-08 21:15:50.429  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 21:15:50.429  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.429  1015  1055 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-08 21:15:50.429  1015  1055 D PackageManager: userId{-1}
09-08 21:15:50.429  1015  1055 D PackageManager: andCode{true}
09-08 21:15:50.429  1015  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 21:15:50.429  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms, destAppInfo.processName = com.sec.enterprise.knox.cloudmdm.smdms
,09-08 21:15:50.439  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-08 21:15:50.439  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-08 21:15:50.439  6481  6481 D [0]UMC:GuardService: @GuardService - startService Result = ComponentInfo{com.sec.enterprise.knox.cloudmdm.smdms/com.sec.enterprise.knox.cloudmdm.smdms.core.GuardService}
09-08 21:15:50.439  1015  1248 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-08 21:15:50.439  1015  1248 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.439  6481  6481 D [0]UMC:CoreReceiver: Intent : android.intent.action.PACKAGE_REMOVED
09-08 21:15:50.439  6481  6481 D [0]UMC:CoreReceiver: PackageName : com.test.thalitest
09-08 21:15:50.439  6481  6481 D [0]UMC:CoreReceiver: Intent Replacing : false
09-08 21:15:50.439  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:50.439  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
09-08 21:15:50.439  6534  6534 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 21:15:50.439  1015  1248 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.439  1015  1248 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 21:15:50.439  1015  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
09-08 21:15:50.439  6534  6534 D ActivityThread: Added TimaKeyStore provider
,09-08 21:15:50.449  1015  1039 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-08 21:15:50.449  1015  1055 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
09-08 21:15:50.449  6514  6514 D AcmsService: Enter Oncreate
,09-08 21:15:50.449  6514  6514 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-08 21:15:50.449  6514  6514 D AcmsService: creating AcmsCore
,09-08 21:15:50.449  6514  6514 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-08 21:15:50.449  1015  1039 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-08 21:15:50.449  6514  6514 D AcmsCore: AcmsCore
09-08 21:15:50.449  1015  1039 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-08 21:15:50.449  6481  6481 D [0]UMC:CoreReceiver: bulk enrolled package: null
,09-08 21:15:50.449  6481  6481 V [0]UMC:ProfileStorage: Enter loadList
,09-08 21:15:50.449  6481  6481 D [0]UMC:CoreReceiver: handleAutoEnrollmentAndUMCAdminDeactivation
09-08 21:15:50.459  6481  6481 D [0]UMC:UMCAdmin: deactivateUMCAdminIfNotRequired : -1
,09-08 21:15:50.459  6481  6481 E [0]UMC:Utils: Admin not found in package com.samsung.knoxpb.mdm
,09-08 21:15:50.459  6481  6481 E [0]UMC:Utils: Admin not found in package com.sec.enterprise.knox.cloudmdm.smdms.agent.myknox
09-08 21:15:50.459  6481  6481 D [0]UMC:UMCAdmin: deactivateUMCAdmin : -1
09-08 21:15:50.459  6481  6481 D [0]UMC:UMCAdmin: isContainer : 0
,09-08 21:15:50.459  1015  3344 D EnterpriseDeviceManagerService: isManagedProfileUser(): userId = 0
,09-08 21:15:50.459  6481  6481 E [0]UMC:UMCAdmin: No active admin owned by uid 10160
09-08 21:15:50.459  6481  6481 D [0]UMC:UMCAdmin: isContainer : 0
,09-08 21:15:50.459  6481  6481 D [0]UMC:UMCAdmin: deactivateUMCAdmin - UMC App Admin deactivated
,09-08 21:15:50.459  6481  6481 D [0]UMC:GuardService: @GuardService oncreate()
,09-08 21:15:50.469  6481  6481 D [0]UMC:GuardService: @GuardService onStartCommand()
,09-08 21:15:50.469  6514  6514 D AcmsCore: init
09-08 21:15:50.469  6514  6514 D AcmsCore: Looper handler is not null
09-08 21:15:50.469  6514  6514 D AcmsCore: Post to AcmsCoreHandler
09-08 21:15:50.469  6514  6514 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-08 21:15:50.469  6514  6514 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-08 21:15:50.469  6514  6514 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
,09-08 21:15:50.469  1015  1040 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-08 21:15:50.469  6514  6553 D AcmsCertificateMngr: AcmsCertificateMngr
,09-08 21:15:50.469  6514  6514 D AcmsService: onStartCommand
09-08 21:15:50.469  6514  6514 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
09-08 21:15:50.469  6514  6514 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-08 21:15:50.469  6514  6514 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-08 21:15:50.469  6514  6514 D AcmsService: Incremented Counter Value : onStartCommand
,09-08 21:15:50.479  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.479  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.479  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-08 21:15:50.479  1015  1040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.479  5648  5648 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(304): Wear auto uninstall disabled for package com.test.thalitest
,09-08 21:15:50.479  6514  6553 D AcmsRevocationMngr: AcmsRevocationMngr
,09-08 21:15:50.489  1475  1475 D Launcher.Model: reloadBadges entered.
,09-08 21:15:50.489  6555  6555 E Zygote  : MountEmulatedStorage()
,09-08 21:15:50.489  6555  6555 I libpersona: KNOX_SDCARD checking this for 10120
09-08 21:15:50.489  6555  6555 E Zygote  : v2
09-08 21:15:50.489  6555  6555 I libpersona: KNOX_SDCARD not a persona
09-08 21:15:50.489  6555  6555 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 21:15:50.489  1015  1040 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PhotosAppTransitionMonitor: pid=6555 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-08 21:15:50.499  1015  3037 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-08 21:15:50.499  1015  3037 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
09-08 21:15:50.499  6555  6555 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-08 21:15:50.499  1015  3037 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.499  1015  3037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.499  1015  3037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-08 21:15:50.499  6555  6555 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-08 21:15:50.499  1015  1027 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-08 21:15:50.499  6514  6514 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,09-08 21:15:50.519  5834  5834 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,09-08 21:15:50.519  1015  1944 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-08 21:15:50.519  1015  1944 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.519  1015  1944 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.519  1015  1944 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 21:15:50.519  1015  1944 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,09-08 21:15:50.529  1015  3346 I TactileAssist: enable value -1
09-08 21:15:50.529  1015  3346 I TactileAssist: internal enable value -1
09-08 21:15:50.529  1015  3346 I TactileAssist: intensity value -1
09-08 21:15:50.529  1015  3346 I TactileAssist: saveAppList value true
,09-08 21:15:50.529  1015  4345 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 21:15:50.529  1015  4345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.539  1015  3346 I TactileAssist: List of disabled apps :
,09-08 21:15:50.539  1015  4345 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.539  1015  4345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.539  6555  6555 D TimaKeyStoreProvider: TimaSignature is unavailable
09-08 21:15:50.539  1015  4345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 21:15:50.539  6555  6555 D ActivityThread: Added TimaKeyStore provider
,09-08 21:15:50.549  5798  5798 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
09-08 21:15:50.549  5834  6570 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
09-08 21:15:50.549  5834  6570 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,09-08 21:15:50.559  6446  6531 D ContactProvider: getAllContactInfoList End
,09-08 21:15:50.559  6446  6531 I syncContacts: thread: 1068, sync time = 193
,09-08 21:15:50.559  3884  6573 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
09-08 21:15:50.559  3884  6573 D AccountUtils: Clearing selected account for com.test.thalitest
,09-08 21:15:50.559  1015  1508 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 21:15:50.569  1015  1508 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.569  1015  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.569  1015  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.569  6534  6571 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-08 21:15:50.569  6514  6514 D AcmsService: Inside handle Intent
09-08 21:15:50.569  6534  6571 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
09-08 21:15:50.569  6514  6514 D AcmsService: App removed - package name: com.test.thalitest
09-08 21:15:50.569  6514  6514 D AcmsCore: Post to AcmsCoreHandler
09-08 21:15:50.569  6514  6514 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-08 21:15:50.569  6514  6514 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-08 21:15:50.569  6514  6514 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
09-08 21:15:50.569  6514  6514 D AcmsService: Decremented Counter Value : handleStartIntent
09-08 21:15:50.569  6514  6514 D AcmsServiceMonitor: Decrementing - Counter value: 2
,09-08 21:15:50.579  1884  1884 D WearableService: callingUid 10012, callindPid: 1884
,09-08 21:15:50.579  3884  6573 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,09-08 21:15:50.589  1015  1027 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: com.google.android.location.util.PreferenceService
09-08 21:15:50.589  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.util.PreferenceService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.589  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-08 21:15:50.589  6010  6023 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,09-08 21:15:50.589  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.589  6010  6023 D BadgeProvider: sendNotify, [notify] : null
,09-08 21:15:50.589  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 21:15:50.589  6010  6023 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
,09-08 21:15:50.589  6010  6023 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-08 21:15:50.589  6010  6023 D BadgeProvider: update, [UpdateCount] : 1
,09-08 21:15:50.589  1475  1475 D Launcher.Model: reloadBadges entered.
,09-08 21:15:50.599  1015  1944 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 21:15:50.599  5648  5648 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-08 21:15:50.599  5648  5648 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-08 21:15:50.599  1015  1944 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.599  1015  1944 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 21:15:50.599  1015  1944 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.599  6555  6555 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-08 21:15:50.599  3884  6573 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-08 21:15:50.599  6534  6571 D SPPClientService: PushLog.txt file is not deleted.
09-08 21:15:50.599  6534  6571 D SPPClientService: PushLog.txt file is not deleted.
09-08 21:15:50.599  6534  6571 D SPPClientService: ============PushLog. stop!
,09-08 21:15:50.609  1015  3344 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 21:15:50.609  1015  3344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.609  1015  3344 W ActivityManager: userId = 0, bbcId = -10000
,09-08 21:15:50.609  1015  3344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 21:15:50.609  1015  3344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.619  6063  6063 D Compatibility: onReceive() it will make start service
,09-08 21:15:50.619  1015  3037 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 21:15:50.619  6415  6415 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-08 21:15:50.629  1015  3037 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.629  1015  3037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.629  1015  3037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.639  1015  1312 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-08 21:15:50.639  1015  1312 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-08 21:15:50.639  1015  1312 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.639  1015  1312 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 21:15:50.639  1015  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-08 21:15:50.639  1015  1335 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-08 21:15:50.639  1015  1335 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.639  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.639  1015  1335 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-08 21:15:50.639  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-08 21:15:50.639  1015  3345 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 21:15:50.639  1015  3345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.disconnect.FitCleanupService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.649  1015  3345 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.649  1015  3345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.649  1015  3345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.649  6105  6105 I SA      : [SUR] onReceive called
,09-08 21:15:50.649  6105  6105 I SA      : [SUR] Not SA Package.. finish
,09-08 21:15:50.649  1015  1484 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 21:15:50.659  6063  6577 D Compatibility: onHandleIntent()
,09-08 21:15:50.659  1015  1484 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.659  1015  1484 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.659  1015  1484 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.659  1015  1312 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 21:15:50.659  1015  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.659  1015  1312 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.659  1015  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.659  1015  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.659  1884  1884 E NetworkScheduler.SR: Invalid parameter app
09-08 21:15:50.659  1884  1884 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-08 21:15:50.659  6063  6577 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10155, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,09-08 21:15:50.669  1015  3037 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 21:15:50.669  1015  3037 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.669  1015  3037 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.669  1015  3037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.669  1015  3037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.669  6063  6577 D Compatibility: found: 2
09-08 21:15:50.669  6063  6577 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-08 21:15:50.669  6063  6577 D Compatibility: skipping ResolveInfo{317acfe6 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-08 21:15:50.669  6063  6577 D Compatibility: considering ResolveInfo{2e86c927 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-08 21:15:50.669  6063  6577 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-08 21:15:50.669  6063  6577 D Compatibility: enabling receiver ResolveInfo{1bd7b7d4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-08 21:15:50.669  1015  1248 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 21:15:50.669  1015  1248 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.679  1015  1248 W ActivityManager: userId = 0, bbcId = -10000
,09-08 21:15:50.679  1015  1248 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.679  1015  1248 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.689  1015  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-08 21:15:50.689  1015  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.689  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-08 21:15:50.689  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.689  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 21:15:50.689  6063  6577 D Compatibility: enabling receiver ResolveInfo{16d40d7d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-08 21:15:50.689  3884  6573 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-08 21:15:50.699  3884  6573 D WearableController: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,09-08 21:15:50.699  1015  1312 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-08 21:15:50.699  1015  1312 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.699  3884  6578 D gH_MetricsDatabase: 0 metrics were deleted when clearing package com.test.thalitest.
,09-08 21:15:50.699  3884  4443 I Icing   : doRemovePackageData com.test.thalitest
,09-08 21:15:50.709  6063  6577 D Compatibility: enabling receiver ResolveInfo{140472 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-08 21:15:50.709  1015  1312 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.709  1015  1312 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.709  1015  1312 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-08 21:15:50.709  6063  6577 D Compatibility: enabling receiver ResolveInfo{40cd0c3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-08 21:15:50.709  1015  3037 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 21:15:50.709  1015  3037 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.719  1015  3037 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.719  1015  3037 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.719  1015  3037 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.719  1015  3346 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,09-08 21:15:50.719  1015  3346 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.contacts/com.android.providers.contacts.VoicemailCleanupService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.719  1015  3346 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.719  1015  3346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-08 21:15:50.719  1015  3346 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,09-08 21:15:50.719  5517  6586 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-08 21:15:50.739  6063  6577 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-08 21:15:50.759  1015  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 21:15:50.759  1015  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-08 21:15:50.759  1015  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.759  1015  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.769  3884  6578 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-08 21:15:50.769  3884  6578 E SQLiteLog: (3850) statement aborts at 25: [DELETE FROM suggestions WHERE app_package_name="com.test.thalitest"] disk I/O error
,09-08 21:15:50.779  1015  1312 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-08 21:15:50.779  1015  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.789  1015  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.789  1015  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.789  1015  1312 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-08 21:15:50.799  6590  6590 E Zygote  : MountEmulatedStorage(),
09-08 21:15:50.799  6590  6590 E Zygote  : v2
09-08 21:15:50.799  6590  6590 I libpersona: KNOX_SDCARD checking this for 10003
09-08 21:15:50.799  6590  6590 I libpersona: KNOX_SDCARD not a persona
,09-08 21:15:50.799  6590  6590 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-08 21:15:50.809  6590  6590 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-08 21:15:50.809  6590  6590 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-08 21:15:50.809  3884  4573 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850,
09-08 21:15:50.809  3884  4573 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-08 21:15:50.809  3884  4573 E GAv4-SVC: Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:15:50.809  3884  4573 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
09-08 21:15:50.809  3884  4573 E GAv4-SVC: Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
09-08 21:15:50.809  3884  4350 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,09-08 21:15:50.809  5517  6586 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-08 21:15:50.809  1015  1312 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6590 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
09-08 21:15:50.809  5517  6586 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-08 21:15:50.809  3884  4350 E SharedPreferencesImpl: Couldn't rename file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml to backup file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml.bak
,09-08 21:15:50.819  1015  1335 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 21:15:50.819  1015  1335 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.AnalyticsService; callingUser = 0; userId(target) = 0
,09-08 21:15:50.829  1015  1335 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.829  1015  1335 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.829  1015  1335 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.829  1015  1484 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-08 21:15:50.829  1015  1484 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.apps.gsa.d.b; callingUser = 0; userId(target) = 0
09-08 21:15:50.829  1015  1484 W ActivityManager: Unable to start service Intent { cmp=com.google.android.googlequicksearchbox/com.google.android.apps.gsa.d.b (has extras) } U=0: not found
,09-08 21:15:50.829  1015  3344 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-08 21:15:50.839  1015  3344 W ActivityManager: userId = 0, bbcId = -10000
,09-08 21:15:50.839  1015  3344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-08 21:15:50.839  1015  3344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-08 21:15:50.849  6590  6590 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-08 21:15:50.849  6590  6590 D ActivityThread: Added TimaKeyStore provider
,09-08 21:15:50.859  5517  6586 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,09-08 21:15:50.859  5517  6586 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
09-08 21:15:50.859  5517  6586 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 5517
09-08 21:15:50.859  5517  6586 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at com.google.android.search.core.icingsync.c.e(ApplicationsHelper.java:193)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at com.google.android.search.core.icingsync.w.g(InternalIcingCorporaProvider.java:587)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:290)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:340)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1386)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at com.google.android.search.core.icingsync.z.amO(UpdateIcingCorporaService.java:358)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ab.amQ(UpdateIcingCorporaService.java:297)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.aF(UpdateIcingCorporaService.java:194)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-08 21:15:50.859  5517  6586 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-08 21:15:50.859  1015  3344 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-08 21:15:50.859  1015  3344 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-08 21:15:50.859  1015  3344 W ActivityManager: userId = 0, bbcId = -10000
09-08 21:15:50.859  1015  3344 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-08 21:15:50.859  1015  3344 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-08 21:15:50.869  1015  3346 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox:search

```
