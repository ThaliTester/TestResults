#### Test 79763830e2067e4_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
08-26 14:17:05.014   317   317 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-26 14:17:05.014   317   317 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-26 14:17:05.744  6156  6156 D AndroidRuntime: 
08-26 14:17:05.744  6156  6156 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-26 14:17:05.744  6156  6156 D AndroidRuntime: CheckJNI is OFF
08-26 14:17:05.744  6156  6156 D AndroidRuntime: readGMSProperty: start
08-26 14:17:05.744  6156  6156 D AndroidRuntime: readGMSProperty: already setted!!
08-26 14:17:05.744  6156  6156 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 14:17:05.744  6156  6156 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-26 14:17:05.744  6156  6156 D AndroidRuntime: readGMSProperty: end
08-26 14:17:05.744  6156  6156 D AndroidRuntime: addProductProperty: start
08-26 14:17:05.874  6156  6156 E AffinityControl: AffinityControl: registerfunction enter
08-26 14:17:05.904  6156  6156 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-26 14:17:05.914  1013  3038 E PersonaManagerService: inState():  stateMachine is null !!
08-26 14:17:05.914  1013  3038 I PersonaManagerService: PersonaId don't exist
08-26 14:17:05.914  1013  3038 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-26 14:17:05.914  1013  3038 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-26 14:17:05.924  1013  3038 W ActivityManager: mDVFSHelper.acquire()
08-26 14:17:05.934  1013  3038 D FocusedStackFrame: Set to : 0
08-26 14:17:05.934  1013  1043 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-26 14:17:05.934  1013  1043 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-26 14:17:05.944  1013  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:05.944  1013  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:05.944  1013  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:05.944  1013  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:05.954  1013  3038 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6167 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-26 14:17:05.954  1013  3038 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-26 14:17:05.954  1013  3038 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 14:17:05.954  1013  3038 D InputDispatcher: Focused application set to: xxxx
08-26 14:17:05.954  1013  3038 D InputDispatcher: Focus left window: 1476
08-26 14:17:05.954  1013  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-26 14:17:05.954  1013  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-26 14:17:05.954  6167  6167 E Zygote  : MountEmulatedStorage()
08-26 14:17:05.954  6167  6167 E Zygote  : v2
08-26 14:17:05.954  6167  6167 I libpersona: KNOX_SDCARD checking this for 10155
08-26 14:17:05.954   256   256 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-26 14:17:05.954  6167  6167 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:05.954  6156  6156 D AndroidRuntime: Shutting down VM
08-26 14:17:05.964  6167  6167 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 14:17:05.964  6167  6167 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 14:17:05.964  6167  6167 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-26 14:17:05.984  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 14:17:05.984  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 14:17:05.984  6167  6167 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:05.984  6167  6167 D ActivityThread: Added TimaKeyStore provider
08-26 14:17:05.984  1013  1713 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-26 14:17:05.994  1013  1013 V ActivityManager: Display changed displayId=0
08-26 14:17:06.004  1013  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-26 14:17:06.014   286   286 E SMD     : DCD OFF
08-26 14:17:06.014  1013  1713 D PersonaManager: isKioskContainerExistOnDevice
08-26 14:17:06.024  1013  1013 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-26 14:17:06.064   256   585 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
08-26 14:17:06.064   256   445 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
08-26 14:17:06.064  1476  1476 V ActivityThread: updateVisibility : ActivityRecord{1d5ccf6f token=android.os.BinderProxy@3b372bc4 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-26 14:17:06.064  1476  1476 D Launcher: onTrimMemory. Level: 20
08-26 14:17:06.134  6167  6167 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-26 14:17:06.144  6167  6167 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9856-9858)
08-26 14:17:06.144  6167  6167 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-26 14:17:06.164  6156  6156 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-26 14:17:06.174  6167  6167 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {5415f66}
,08-26 14:17:06.184  6167  6167 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 14:17:06.184  6167  6167 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 14:17:06.214  6167  6167 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 14:17:06.214  6167  6167 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:17:06.214  6167  6167 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 14:17:06.234  6167  6167 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-26 14:17:06.234  6167  6167 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,08-26 14:17:06.234  6167  6167 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-26 14:17:06.244  6167  6167 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:17:06.244  6167  6167 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:17:06.244  6167  6167 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:17:06.244  6167  6167 I Adreno-EGL: Local Branch: 
08-26 14:17:06.244  6167  6167 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:17:06.244  6167  6167 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:17:06.244  6167  6167 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:17:06.354  6167  6193 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-26 14:17:06.404  6167  6167 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:17:06.414  6167  6167 W AwContents: onDetachedFromWindow called when already detached. Ignoring,
,08-26 14:17:06.424  6167  6167 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-26 14:17:06.424  6167  6167 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-26 14:17:06.434  6167  6167 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-26 14:17:06.434  6167  6167 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
08-26 14:17:06.434  6167  6167 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:17:06.474  6167  6206 D OpenGLRenderer: Render dirty regions requested: true
,08-26 14:17:06.484  1013  1314 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-26 14:17:06.484  1013  1314 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 14:17:06.484  1013  1314 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-26 14:17:06.484  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0,
08-26 14:17:06.484  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 14:17:06.494  6167  6167 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,08-26 14:17:06.494  6167  6167 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-26 14:17:06.504   256   256 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
08-26 14:17:06.504  1013  3042 D InputDispatcher: Focus entered window: 6167
,08-26 14:17:06.514  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 14:17:06.514  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
08-26 14:17:06.514  6167  6167 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
08-26 14:17:06.514  6167  6206 I OpenGLRenderer: Initialized EGL, version 1.4
,08-26 14:17:06.514  6167  6206 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-26 14:17:06.514  6167  6206 D OpenGLRenderer: Enabling debug mode 0
,08-26 14:17:06.564  6167  6167 V ActivityThread: updateVisibility : ActivityRecord{279cab69 token=android.os.BinderProxy@1c0f0233 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-26 14:17:06.564  1013  1540 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 14:17:06.564  1013  6209 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,08-26 14:17:06.574  1175  1175 D PanelView: There is/are notification(s) 
,08-26 14:17:06.584  1896  1896 I SamsungIME: getCurrentCandidateView
,08-26 14:17:06.594  6167  6167 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-26 14:17:06.614  6167  6167 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1c0f0233 time:110323
,08-26 14:17:06.614  1013  1043 I ActivityManager: Displayed Component not be shown by security: +596ms (total +680ms),
08-26 14:17:06.614  1013  1043 W ActivityManager: mDVFSHelper.release()
08-26 14:17:06.614  1013  1043 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{a39bc2b u0 com.test.thalitest/.MainActivity t127} time:110326,
,08-26 14:17:06.624   256   585 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-26 14:17:06.624   256  1859 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-26 14:17:06.664  6167  6167 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6167
,08-26 14:17:06.694  1896  1896 D SamsungIME: Dismiss ExpandCandiate
,08-26 14:17:06.774  6167  6167 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-26 14:17:06.824  1896  1896 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 14:17:06.864  1896  1896 I SamsungIME: getDebugLevel  : 0x4f4c
,08-26 14:17:06.874  1896  1896 I SamsungIME: KeybaordView init() : load resources
,08-26 14:17:06.884  6167  6211 D jxcore_app_log: JniHelper::setJavaVM(0xb7a28328), pthread_self() = -1208432856
,08-26 14:17:06.904  1896  1896 I SamsungIME: getCurrentKeyboard
08-26 14:17:06.904  1896  1896 I SamsungIME: getTextKeyboard
,08-26 14:17:06.904  6167  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-26 14:17:06.904  6167  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-26 14:17:06.904  6167  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-26 14:17:06.904  6167  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-26 14:17:06.904  6167  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-26 14:17:06.904  6167  6211 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@257a40d9 added. We now have 1 listener(s)
,08-26 14:17:06.914  6167  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,08-26 14:17:06.914  6167  6211 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-26 14:17:06.914  6167  6211 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:17:06.914  6167  6211 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:17:06.914  1896  1896 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-26 14:17:06.914  6167  6211 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18085d4c added. We now have 1 listener(s)
,08-26 14:17:06.924  6167  6211 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:06.924  6167  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-26 14:17:06.924  6167  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-26 14:17:06.924  6167  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-26 14:17:06.924  6167  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-26 14:17:06.924  6167  6211 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-26 14:17:06.924  6167  6211 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:06.934  6167  6211 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,08-26 14:17:06.944  6167  6211 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-26 14:17:06.944  6167  6211 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:06.944  6167  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:06.944  6167  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:06.944  6167  6211 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:06.944  6167  6211 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:06.944  6167  6211 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:06.944  6167  6211 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:06.944  6167  6211 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:06.944  6167  6211 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-26 14:17:06.944  6167  6211 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:06.944  6167  6211 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 14:17:06.944  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:06.944  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:06.974  6167  6167 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-26 14:17:07.444  1896  6216 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-26 14:17:07.474  6167  6220 W jxcore-log: Initializing JXcore engine
08-26 14:17:07.474  6167  6220 W jxcore-log: JXcore engine is ready
,08-26 14:17:07.534  1891  1891 E audit   : type=1400 msg=audit(1472213827.534:205): avc:  denied  { ioctl } for  pid=6220 comm="Thread-1064" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0,
08-26 14:17:07.534  1891  1891 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
08-26 14:17:07.534  1891  1891 E audit   : type=1300 msg=audit(1472213827.534:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9e4c08f8 items=0 ppid=308 ppcomm=main pid=6220 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1064" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-26 14:17:07.534  1891  1891 E audit   : type=1320 msg=audit(1472213827.534:205): 
,08-26 14:17:07.544  6167  6220 W jxcore-log: Starting JXcore engine
,08-26 14:17:07.654  6167  6220 W jxcore-log: Platform android,
08-26 14:17:07.654  6167  6220 W jxcore-log: 
08-26 14:17:07.654  6167  6220 W jxcore-log: Process ARCH arm
08-26 14:17:07.654  6167  6220 W jxcore-log: 
,08-26 14:17:07.854  6167  6220 I jxcore-log: JXcore Cordova bridge is ready!
08-26 14:17:07.854  6167  6220 I jxcore-log: 
,08-26 14:17:07.854  6167  6220 W jxcore-log: JXcore engine is started
,08-26 14:17:07.854  6167  6211 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-26 14:17:07.854  6167  6167 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-26 14:17:09.014   286   286 E SMD     : DCD OFF,
,08-26 14:17:09.264  5395  5395 D FactoryTest: Not factory mode
,08-26 14:17:09.264  5395  5395 D FactoryTest: Not factory mode. isFactoryMode() returend false
,08-26 14:17:09.264  5395  5395 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
08-26 14:17:09.264  5395  5395 D MTPRx   : still no open session command from host, so toast
,08-26 14:17:09.264  5395  5395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
08-26 14:17:09.264  5395  5395 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,08-26 14:17:09.264  5395  5395 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:112975
,08-26 14:17:09.264  1013  1541 E PersonaManagerService: inState():  stateMachine is null !!
,08-26 14:17:09.264  1013  1541 I PersonaManagerService: PersonaId don't exist
08-26 14:17:09.264  1013  1541 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,08-26 14:17:09.274  1013  1541 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 14:17:09.274  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:09.274  1013  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:09.274  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,08-26 14:17:09.274  1013  1541 W ActivityManager: mDVFSHelper.acquire()
,08-26 14:17:09.294  1013  1541 D PersonaManager: isKioskContainerExistOnDevice
,08-26 14:17:09.304  1013  1541 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest,
08-26 14:17:09.304  1013  1541 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
08-26 14:17:09.304  1013  1541 D InputDispatcher: Focused application set to: xxxx
,08-26 14:17:09.304  1013  1541 D InputDispatcher: Focus left window: 6167
08-26 14:17:09.304  5395  5395 E MTPRx   : started activity for popup
,08-26 14:17:09.304  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 14:17:09.304  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 14:17:09.324  5395  5395 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-26 14:17:09.324  5395  5395 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 14:17:09.324  5395  5395 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 14:17:09.334  5395  5395 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:09.334  5395  5395 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:09.334  5395  5395 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:09.344  5395  5395 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,08-26 14:17:09.344  1013  1539 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,08-26 14:17:09.344  1013  1539 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-26 14:17:09.344  1013  1539 D InputDispatcher: Focused application set to: xxxx
,08-26 14:17:09.354  1013  1539 D InputDispatcher: Focus entered window: 6167
,08-26 14:17:09.354  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-26 14:17:09.354  1013  1540 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-26 14:17:09.354  1013  1540 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@323cb38a attribute=null, token = android.os.BinderProxy@c0c9fda
,08-26 14:17:09.354  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 14:17:09.394  5395  5395 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,08-26 14:17:09.404  5395  5395 D PhoneWindow: *FMB* installDecor mIsFloating : true
08-26 14:17:09.404  5395  5395 D PhoneWindow: *FMB* installDecor flags : 8388610
,08-26 14:17:09.424  6167  6167 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 14:17:09.424  6167  6167 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,08-26 14:17:09.424  6167  6167 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-26 14:17:09.424  6167  6167 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,08-26 14:17:09.424  1013  1713 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-26 14:17:09.424  1013  1713 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-26 14:17:09.424  1013  1713 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-26 14:17:09.424  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-26 14:17:09.424  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,08-26 14:17:09.444  6167  6167 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 14:17:09.444  6167  6167 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,08-26 14:17:09.444  6167  6167 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1566e16 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@ef4a93e, 16908290=android.view.AbsSavedState$1@ef4a93e}, android:focusedViewId=100}]}]
08-26 14:17:09.444  6167  6167 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
08-26 14:17:09.444  6167  6167 V ActivityThread: updateVisibility : ActivityRecord{279cab69 token=android.os.BinderProxy@1c0f0233 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-26 14:17:09.444  6167  6167 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-26 14:17:09.444  6167  6167 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,08-26 14:17:09.444  6167  6167 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1c0f0233 time:113157
,08-26 14:17:09.454  1013  3119 D PersonaManager: isKioskContainerExistOnDevice
,08-26 14:17:10.004   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:11.014   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:12.014   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:12.014   286   286 E SMD     : DCD OFF
,08-26 14:17:12.274  1013  1038 W ActivityManager: mDVFSHelper.release()
,08-26 14:17:12.344  1013  1261 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 14:17:12.344  1013  1261 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4168, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-26 14:17:12.344  1013  1261 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-26 14:17:12.344  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 14:17:12.344  1013  1261 D BatteryService: stay LED for charging
,08-26 14:17:12.344  1013  1013 I MotionRecognitionService: Plugged
,08-26 14:17:12.344  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 14:17:12.344  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 14:17:12.354  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 14:17:12.354  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 14:17:12.354  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
,08-26 14:17:12.364  2654  2654 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 14:17:12.364  2654  2764 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:17:12.374  1013  2774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 14:17:12.374  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-26 14:17:12.374  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-26 14:17:12.374  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-26 14:17:12.894  1013  2741 D SSRM:n  : SIOP:: AP = 340,
,08-26 14:17:13.014   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:14.014   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:15.014   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1,
,08-26 14:17:15.014   286   286 E SMD     : DCD OFF,
,08-26 14:17:15.944  1013  1053 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS,
,08-26 14:17:16.294  1013  1091 V AlarmManager: waitForAlarm result :4
,08-26 14:17:16.304  1013  1091 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,08-26 14:17:16.324  1905  1905 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,08-26 14:17:16.344  1013  1025 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:16.354  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,08-26 14:17:16.354  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:16.354  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:16.354  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:16.394  3835  3835 D ConnectivityManager: CallingUid : 10012, CallingPid : 3835
,08-26 14:17:16.394  1013  1314 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-26 14:17:16.394  1013  1123 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,08-26 14:17:16.394  1013  1123 D ConnectivityService: apparently satisfied.  currentScore=60
,08-26 14:17:16.394  1013  1123 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,08-26 14:17:16.394  3835  6229 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:17:16.444  3835  6230 W DriveInitializer: Background init thread started
,08-26 14:17:16.464   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
08-26 14:17:16.464   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:16.464  3835  6230 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,08-26 14:17:16.474  1013  1091 V AlarmManager: waitForAlarm result :4
,08-26 14:17:16.514  1013  3119 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:16.514  1013  3119 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,08-26 14:17:16.514  1013  3119 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:16.514  1013  3119 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:16.514  1013  3119 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:16.544  1013  3042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
08-26 14:17:16.544  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,08-26 14:17:16.554  1013  1540 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:16.554  1013  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,08-26 14:17:16.564  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:16.564  1013  1540 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:16.564  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:16.584  3835  6230 W DriveInitializer: Background init thread ended
,08-26 14:17:16.594  3835  6238 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,08-26 14:17:16.594  3835  6238 D SchedPeriodicTask: Scheduled AdAttestation task.
,08-26 14:17:16.614  1905  1905 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 14:17:16.644  1013  1038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:16.644  1013  1038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:16.644  1013  1038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:16.754  1013  1541 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:16.754  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,08-26 14:17:16.754  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:16.754  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:16.754  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:16.784  1013  1131 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:16.784  1013  1131 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,08-26 14:17:16.784  1013  1131 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:16.784  1013  1131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:16.784  1013  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:16.834  1013  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:16.834  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:16.834  1013  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:16.834  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:16.844  1013  3038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:16.844  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:16.854  1013  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:16.854  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:16.894  1013  1539 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:16.894  1013  1539 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:16.894  1013  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:16.894  1013  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,08-26 14:17:16.894  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:16.894  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 14:17:16.894  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:16.894  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:16.914  6243  6243 E Zygote  : MountEmulatedStorage()
08-26 14:17:16.914  6243  6243 E Zygote  : v2
08-26 14:17:16.914  6243  6243 I libpersona: KNOX_SDCARD checking this for 10012
08-26 14:17:16.914  6243  6243 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:16.914  1013  1539 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6243 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a,
,08-26 14:17:16.914  6243  6243 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 14:17:16.924  6243  6243 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:16.924  6243  6243 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,08-26 14:17:16.944  6243  6243 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:16.944  6243  6243 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:16.964  6243  6243 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-26 14:17:16.964  6243  6243 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 14:17:17.004  6243  6243 I MultiDex: VM with version 2.1.0 has multidex support
08-26 14:17:17.004  6243  6243 I MultiDex: install
08-26 14:17:17.004  6243  6243 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-26 14:17:17.044  6243  6243 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 14:17:17.104  6243  6243 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 14:17:17.104  6243  6243 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a119613: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-26 14:17:17.104  6243  6243 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-26 14:17:17.124  6243  6243 D ChimeraCfgMgr: Reading stored module config
,08-26 14:17:17.154  1013  1350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,08-26 14:17:17.154  1013  1541 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:17.154  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:17.154  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:17.154  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:17.174  1013  1713 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:17.174  1013  1713 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:17.174  1013  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:17.174  1013  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:17.234  1013  1541 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 14:17:17.234  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 14:17:17.234  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:17.234  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:17.234  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:17.234  6243  6260 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,08-26 14:17:17.244  1905  1905 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=f3d4efed-1678-41bf-b993-18281f5f6d6a
,08-26 14:17:17.244  6243  6243 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 14:17:17.244  6243  6243 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,08-26 14:17:17.254  1905  1905 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 14:17:17.254  1905  1905 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-26 14:17:17.274  1013  3038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:17.274  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:17.274  1013  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:17.274  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:17.324   281  1608 D WVCdm   : Instantiating CDM.
,08-26 14:17:17.324   281   677 I WVCdm   : CdmEngine::OpenSession
,08-26 14:17:17.334   281   677 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,08-26 14:17:17.354   281   677 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,08-26 14:17:17.374   281   677 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
,08-26 14:17:17.374   281   677 D DrmWidevineDash: Service_Initialize: starts!
08-26 14:17:17.374   281   677 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,08-26 14:17:17.384   281   677 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 14:17:17.384   281   677 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
08-26 14:17:17.384   281   677 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-26 14:17:17.384   281   677 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-26 14:17:17.384   281   677 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 14:17:17.384   281   677 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
08-26 14:17:17.384   281   677 E QSEECOMAPI: : Error::Loading image failed with ret = -1
08-26 14:17:17.384   281   677 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
08-26 14:17:17.384   281   677 D QSEECOMAPI: : App is not loaded in QSEE
,08-26 14:17:17.404   281   677 D QSEECOMAPI: : Loaded image: APP id = 11
,08-26 14:17:17.404   281   677 D DrmWidevineDash: Service_Initialize: ends! returns 0
,08-26 14:17:17.404   281   677 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
08-26 14:17:17.404   281   677 D QSAPPSVER: qsapps_get_capabilities: returns 0
08-26 14:17:17.404   281   677 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1345000
08-26 14:17:17.404   281   677 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb1345000
,08-26 14:17:17.404   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.414   427   436 D DrmLibTime: got the req here! ret=0
08-26 14:17:17.414   427   436 D DrmLibTime: command id, time_cmd_id = 770
08-26 14:17:17.414   427   436 D DrmLibTime: time_getutcsec starts!
08-26 14:17:17.414   427   436 D DrmLibTime: QSEE Time Listener: time_getutcsec
08-26 14:17:17.414   427   436 D DrmLibTime: QSEE Time Listener: get_utc_seconds
08-26 14:17:17.414   427   436 D DrmLibTime: QSEE Time Listener: time_get_modem_time
08-26 14:17:17.414   427   436 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,08-26 14:17:17.424   427   436 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
08-26 14:17:17.424   427   436 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
08-26 14:17:17.424   427   436 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
08-26 14:17:17.424   427   436 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-26 14:17:17.424   319   548 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-26 14:17:17.424   319  6266 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
,08-26 14:17:17.424   319  6266 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
08-26 14:17:17.424   319  6266 D QC-time-services: offset is: 0 for base: 0
08-26 14:17:17.424   427   436 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
08-26 14:17:17.424   427   436 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
08-26 14:17:17.424   427   436 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1472213837
,08-26 14:17:17.424   427   436 D DrmLibTime: time_getutcsec returns 0, sec = 1472213837; nsec = 0
08-26 14:17:17.424   427   436 D DrmLibTime: time_getutcsec finished! 
08-26 14:17:17.424   427   436 D DrmLibTime: iotcl_continue_command finished! and return 0 
08-26 14:17:17.424   427   436 D DrmLibTime: before calling ioctl to read the next time_cmd
,08-26 14:17:17.424   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
,08-26 14:17:17.424   319   548 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-26 14:17:17.434   281   677 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,08-26 14:17:17.434   281   677 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-26 14:17:17.434   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.434   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.434   281   677 D DrmWidevineDash: hlos api version =  9
08-26 14:17:17.434   281   677 D DrmWidevineDash: tz api version =  9
08-26 14:17:17.434   281   677 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-26 14:17:17.434   281   677 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
08-26 14:17:17.434   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.474   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.474   281   677 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
08-26 14:17:17.474   281   677 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
08-26 14:17:17.474   281   677 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb199b960
08-26 14:17:17.474   281   677 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
08-26 14:17:17.474   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.474   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.474   281   677 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
08-26 14:17:17.474   281   677 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
08-26 14:17:17.474   281   677 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb785cc38, dataLength=8
08-26 14:17:17.474   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.474   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.474   281   677 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,08-26 14:17:17.474  1655  1726 I art     : Explicit concurrent mark sweep GC freed 1455(50KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 1.064ms total 27.451ms
,08-26 14:17:17.474   281   677 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb785e9a8, wrapped_rsa_key_length=1280
,08-26 14:17:17.474   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.484   281   677 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.484   281   677 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
08-26 14:17:17.484   281   677 I WVCdm   : CdmEngine::QueryKeyControlInfo
,08-26 14:17:17.484   281   281 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
,08-26 14:17:17.484   281   281 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
08-26 14:17:17.484   281   281 I WVCdm   : CdmEngine::GenerateKeyRequest
08-26 14:17:17.484   281   281 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb7880d00, idLength=0xbe90df80
08-26 14:17:17.484   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.494  6243  6251 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,08-26 14:17:17.494  6243  6251 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:17.494  6243  6251 I System.out: (HTTPLog)-Static: isShipBuild true
,08-26 14:17:17.494  6243  6251 I System.out: (HTTPLog)-Thread-1039-440316948: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-26 14:17:17.494  6243  6251 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:17.494   276  1008 D EnterpriseController: uids 10012
08-26 14:17:17.494   276  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 14:17:17.494   276  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-26 14:17:17.514  1905  2121 I art     : Explicit concurrent mark sweep GC freed 56616(3MB) AllocSpace objects, 9(384KB) LOS objects, 40% free, 14MB/23MB, paused 1.458ms total 167.839ms
,08-26 14:17:17.514   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
,08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
,08-26 14:17:17.514   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.514   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xbe90df96, maximum = 0xbe90df97
08-26 14:17:17.514   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-26 14:17:17.514   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
08-26 14:17:17.514   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.514   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.514   281   281 D DrmWidevineDash: hlos api version =  9
08-26 14:17:17.514   281   281 D DrmWidevineDash: tz api version =  9
08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xbe90e004
08-26 14:17:17.514   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
08-26 14:17:17.514   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
08-26 14:17:17.514   281   281 D WVCdm   : PrepareKeyRequest: nonce=2950224607
08-26 14:17:17.514   281   281 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb785b938
08-26 14:17:17.514   281   281 D DrmWidevineDash: message_length=1599, signature=0xb785bf80, signature_length=0xbe90df64
08-26 14:17:17.514   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.544  6243  6251 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 14:17:17.554  6243  6251 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6243, getuid(): 10012
,08-26 14:17:17.594  1905  2112 W GCoreFlp: No location to return for getLastLocation()
,08-26 14:17:17.674   281   281 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.674   281   281 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,08-26 14:17:17.674   281  1609 I WVCdm   : CdmEngine::CloseSession
,08-26 14:17:17.674   281  1609 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
,08-26 14:17:17.674   281  1609 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,08-26 14:17:17.684   281  1609 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0,
08-26 14:17:17.684   281  1609 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
08-26 14:17:17.684   281  1609 I WVCdm   : L3 Terminate.
08-26 14:17:17.684   281  1609 D DrmWidevineDash: OEMCrypto_Terminate: starts!
08-26 14:17:17.684   281  1609 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0,
08-26 14:17:17.684   281  1609 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
08-26 14:17:17.684   281  1609 D DrmWidevineDash: Service_Uninitialize: starts!
08-26 14:17:17.684   281  1609 D QSEECOMAPI: : QSEECom_dealloc_memory 
08-26 14:17:17.684   281  1609 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,08-26 14:17:17.684   281  1609 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
08-26 14:17:17.684   281  1609 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,08-26 14:17:17.744  1013  1350 I art     : Explicit concurrent mark sweep GC freed 41800(2MB) AllocSpace objects, 21(336KB) LOS objects, 33% free, 27MB/41MB, paused 2.572ms total 148.177ms
,08-26 14:17:17.774  1013  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:17.774  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:17.774  1013  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:17.774  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:17.774  1013  1541 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:17.774  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:17.774  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:17.774  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:17.784  1013  3040 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:17.784  1013  3040 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:17.784  1013  3040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:17.784  1013  3040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:17.794  3835  6239 D UdcContextInitService: registered all accounts: true
,08-26 14:17:17.804  1905  2116 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 14:17:17.834  1905  2134 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,08-26 14:17:17.854  6243  6251 I qtaguid : Untagging socket 30
,08-26 14:17:18.014  1013  1345 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-26 14:17:18.014  1013  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,08-26 14:17:18.014  1013  1345 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:18.014  1013  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:18.014  1013  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:18.014   286   286 E SMD     : DCD OFF
,08-26 14:17:18.394  6274  6274 I dex2oat : ----------------------------------------------------
08-26 14:17:18.394  6274  6274 I dex2oat : <SS>: S T A R T I N G . . .
08-26 14:17:18.394  6274  6274 I dex2oat : <SS>: Zip is absent. Canceled.
,08-26 14:17:18.394  6274  6274 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=42 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-26 14:17:18.434  6274  6274 I dex2oat : dex2oat took 31.697ms (threads: 4),
,08-26 14:17:18.444  6243  6251 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:17:18.444  6243  6251 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:17:18.444  6243  6251 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:17:18.444  6243  6251 I Adreno-EGL: Local Branch: 
08-26 14:17:18.444  6243  6251 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:17:18.444  6243  6251 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:17:18.444  6243  6251 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:17:18.524  6243  6251 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-26 14:17:18.524  6243  6251 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:17:18.524  6243  6251 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:17:18.524  6243  6251 I Adreno-EGL: Local Branch: 
08-26 14:17:18.524  6243  6251 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:17:18.524  6243  6251 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:17:18.524  6243  6251 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:17:18.574  6243  6251 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e),
08-26 14:17:18.574  6243  6251 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:17:18.574  6243  6251 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:17:18.574  6243  6251 I Adreno-EGL: Local Branch: 
08-26 14:17:18.574  6243  6251 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:17:18.574  6243  6251 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:17:18.574  6243  6251 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:17:18.834  1013  3193 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-26 14:17:18.834  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-26 14:17:18.834  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:18.834  1013  3193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:18.834  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:18.844  1905  6241 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:18.844   276  1008 D EnterpriseController: uids 10012
08-26 14:17:18.844   276  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 14:17:18.844   276  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-26 14:17:18.844  1905  6241 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 14:17:18.854  1905  6241 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1905, getuid(): 10012
,08-26 14:17:18.894  1905  6241 I qtaguid : Tagging socket 65 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1905, getuid(): 10012
,08-26 14:17:19.034  1905  2134 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 14:17:19.034  1905  2134 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,08-26 14:17:19.044  1905  2134 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-08-26 14:17:17.925+0200, stopTime=2016-08-26 14:17:19.056+0200, duration=1131ms
,08-26 14:17:19.054  1905  6283 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:19.054   276  1008 D EnterpriseController: uids 10012
08-26 14:17:19.054   276  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 14:17:19.054   276  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-26 14:17:19.064  1905  6283 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-26 14:17:19.064  1905  6283 I qtaguid : Tagging socket 68 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1905, getuid(): 10012
,08-26 14:17:19.104  1905  6283 I qtaguid : Tagging socket 66 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1905, getuid(): 10012
,08-26 14:17:19.104  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-26 14:17:19.344  1905  6283 I qtaguid : Untagging socket 68
,08-26 14:17:19.384  1013  3119 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:19.384  1013  3119 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,08-26 14:17:19.384  1013  3119 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:19.384  1013  3119 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:19.384  1013  3119 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:19.414  1905  2134 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,08-26 14:17:19.464  1013  3119 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:19.464  1013  3119 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:19.464  1013  3119 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:19.464  1013  3119 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:19.484  1013  1261 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:19.484  1013  1261 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:19.484  1013  1261 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:19.484  1013  1261 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:19.524  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:19.524  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:19.524  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:19.524  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:19.524  1905  6291 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 14:17:19.524  1905  6289 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 14:17:19.524  1013  3038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:19.524  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:19.524  1013  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:19.534  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:19.554  1013  1131 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:19.554  1013  1131 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:19.554  1013  1131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:19.554  1013  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:19.554  1905  6291 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 14:17:19.554  1905  6289 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 14:17:19.554  1013  1541 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:19.554  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:19.554  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:19.554  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:19.584  1013  3042 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:19.584  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:19.584  1013  3042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:19.584  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:19.584  1905  6291 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,08-26 14:17:19.584  1905  6289 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,08-26 14:17:19.584  1905  6289 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,08-26 14:17:19.594  1905  6289 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,08-26 14:17:19.644  1013  1131 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 14:17:19.674  1905  6289 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:19.674   276  1008 D EnterpriseController: uids 10012
08-26 14:17:19.674   276  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 14:17:19.674   276  1008 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,08-26 14:17:19.684  1905  6289 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-26 14:17:19.684  1905  6289 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1905, getuid(): 10012
,08-26 14:17:19.714  1905  6289 I qtaguid : Tagging socket 84 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1905, getuid(): 10012
,08-26 14:17:19.924  1013  1345 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 14:17:19.934  1905  6289 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:19.934  1905  6289 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1905, getuid(): 10012
,08-26 14:17:20.014   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:20.094  1013  3040 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-26 14:17:20.094  1905  6289 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:20.104  1905  6289 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1905, getuid(): 10012
,08-26 14:17:20.494  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-26 14:17:20.494  6167  6220 I jxcore-log: 
,08-26 14:17:20.504  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-26 14:17:20.504  6167  6220 I jxcore-log: 
,08-26 14:17:20.504  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:20.504  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:20.504  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:20.504  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:20.504  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:20.504  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:20.504  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:20.504  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:20.504  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:20.514  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-26 14:17:20.514  6167  6220 I jxcore-log: 
,08-26 14:17:20.514  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-26 14:17:20.514  6167  6220 I jxcore-log: 
,08-26 14:17:21.014   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:21.014   286   286 E SMD     : DCD OFF
,08-26 14:17:21.164  1905  6285 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:21.164  1905  6285 I qtaguid : Tagging socket 68 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1905, getuid(): 10012
,08-26 14:17:21.164  6167  6220 D executeNativeTests: Running unit tests
,08-26 14:17:21.244  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:21.244  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f added. We now have 2 listener(s)
,08-26 14:17:21.254  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 14:17:21.254  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:21.254  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:21.254  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:21.254  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c added. We now have 2 listener(s)
08-26 14:17:21.254  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:21.254  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:21.254  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:21.254  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:21.254  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.254  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:21.254  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.254  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:21.254  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.254  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.254  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:21.254  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:21.254  6167  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:21.264  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.264  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 14:17:21.264  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:21.264  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-26 14:17:21.264  6167  6220 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-26 14:17:21.264  6167  6220 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 14:17:21.264  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 14:17:21.264  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:21.264  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-26 14:17:21.264  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.264  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.264  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:21.264  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.264  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.264  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.264  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:21.264  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f removed from the list
08-26 14:17:21.264  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.264  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c removed from the list
,08-26 14:17:21.264  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.264  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.264  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.264  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.264  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.274  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:21.274  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.274  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:21.274  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
,08-26 14:17:21.274  6167  6220 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-26 14:17:21.274  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:21.274  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.274  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:21.274  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-26 14:17:21.274  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.274  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.274  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
,08-26 14:17:21.274  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.274  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.274  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.274  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.274  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.274  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.274  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.274  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:21.274  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.274  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:21.274  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
,08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Pee,r: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 14:17:21.284  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.284  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.284  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.284  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.284  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.284  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.284  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.284  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.284  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.284  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.284  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.284  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.284  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.284  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.284  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.284  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.284  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.284  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.284  6167  6220 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 14:17:21.294  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.294  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:21.294  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.294  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:21.294  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.294  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:21.294  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.294  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.294  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:21.304  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.304  6167  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:21.304  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:21.304  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:21.304  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:21.304  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.304  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-26 14:17:21.304  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-26 14:17:21.304  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.304  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.314  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 14:17:21.314  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 14:17:21.314  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-26 14:17:21.324  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-26 14:17:21.324  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 14:17:21.324  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 14:17:21.334  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-26 14:17:21.344  2654  2669 D BtGatt.GattService: registerClient() - UUID=52e7e2ad-fe9c-47ac-b30c-516c818bf551
08-26 14:17:21.344  1905  6285 I qtaguid : Untagging socket 68
08-26 14:17:21.354  1905  2127 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,08-26 14:17:21.374  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.384  2654  2737 D BtGatt.GattService: onClientRegistered() - UUID=52e7e2ad-fe9c-47ac-b30c-516c818bf551, clientIf=6
,08-26 14:17:21.384  6167  6177 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-26 14:17:21.384  2654  2672 D BtGatt.GattService: start scan with filters
,08-26 14:17:21.394  2654  2752 D BtGatt.ScanManager: handling starting scan
08-26 14:17:21.394  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 14:17:21.394  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:21.394  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:21.394  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:21.394  2654  2752 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:21.394  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:21.394  2654  2737 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 14:17:21.394  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.404  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-26 14:17:21.404  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:21.404  2654  2752 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:21.404  2654  2752 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 14:17:21.404  2654  2752 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 14:17:21.404  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,08-26 14:17:21.404  2654  2737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 14:17:21.404  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.404  2654  2752 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 14:17:21.404  2654  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:21.404  2654  2737 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 14:17:21.404  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.414  2654  2737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 14:17:21.414  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.414  6167  6220 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 14:17:21.414  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.414  6167  6220 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:21.414  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.414  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:21.414  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.414  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:21.414  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:21.414  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:21.414  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:21.414  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 14:17:21.414  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:21.414  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:21.424  2654  3039 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:21.424  2654  2669 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:21.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 14:17:21.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:21.424  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:21.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:21.424  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:21.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:21.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:21.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:21.424  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:21.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:21.424  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:21.424  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.424  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.424  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.424  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.424  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.424  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.424  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:21.424  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:21.424  6167  6220 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-26 14:17:21.434  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:21.434  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:21.434  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.434  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:21.434  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.434  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:21.434  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.434  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.434  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:21.434  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:21.434  6167  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:21.434  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:21.434  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:21.434  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:21.434  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.434  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:21.444  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.444  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:21.444  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.444  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:21.444  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:21.454  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 14:17:21.454  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:21.454  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 14:17:21.454  2654  2752 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 30
,08-26 14:17:21.454  2654  2669 D BtGatt.GattService: registerClient() - UUID=954e61e1-fc47-48ba-9b9d-ec314240f991
,08-26 14:17:21.464  2654  2752 D BtGatt.ScanManager: filter size is 1,
08-26 14:17:21.464  2654  2752 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 14:17:21.464  2654  2737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 14:17:21.464  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:21.464  2654  2752 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:21.464  2654  2737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
08-26 14:17:21.464  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:21.464  2654  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 14:17:21.464  2654  2737 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 14:17:21.464  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.504  2654  2737 D BtGatt.GattService: onClientRegistered() - UUID=954e61e1-fc47-48ba-9b9d-ec314240f991, clientIf=6
,08-26 14:17:21.504  6167  6177 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 14:17:21.504  2654  2672 D BtGatt.GattService: start scan with filters
,08-26 14:17:21.504  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 14:17:21.504  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 14:17:21.504  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:21.504  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-26 14:17:21.504  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:21.504  2654  2752 D BtGatt.ScanManager: handling starting scan
08-26 14:17:21.504  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:21.504  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:21.504  2654  2737 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 14:17:21.504  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.504  2654  2752 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:21.504  2654  2752 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 14:17:21.504  2654  2752 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 14:17:21.504  2654  2737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 14:17:21.504  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:21.504  2654  2752 D BtGatt.ScanManager: Starting BLE batch scan
08-26 14:17:21.504  2654  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
08-26 14:17:21.504  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:21.504  2654  2737 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 14:17:21.504  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.514  2654  2737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 14:17:21.514  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.514  6167  6220 I io.jxcore.node.ConnectionHelper: start: OK
,08-26 14:17:21.524  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:21.524  6167  6220 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:21.524  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.524  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:21.524  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.524  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:21.524  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:21.524  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:21.524  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:21.524  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:21.524  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:21.524  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:21.524  2654  2672 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:21.524  2654  2669 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:21.524  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:21.524  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:21.524  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:21.524  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:21.524  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:21.524  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:21.534  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:21.534  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:21.534  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:21.534  2654  2752 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 31
,08-26 14:17:21.534  2654  2752 D BtGatt.ScanManager: filter size is 1
08-26 14:17:21.534  2654  2752 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 14:17:21.534  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-26 14:17:21.534  2654  2737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 14:17:21.534  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:21.534  2654  2752 D BtGatt.ScanManager: stopping BLe Batch,
08-26 14:17:21.534  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.534  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:21.534  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.534  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
08-26 14:17:21.534  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.534  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:21.534  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.534  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.534  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.534  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.534  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.534  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.534  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.534  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.534  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:21.534  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.534  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
,08-26 14:17:21.534  2654  2737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 14:17:21.534  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:21.534  6167  6220 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-26 14:17:21.534  2654  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 14:17:21.534  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:21.544  2654  2737 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 14:17:21.544  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.544  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:21.544  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.544  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:21.544  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.544  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:21.544  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.544  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.544  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:21.544  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:21.544  6167  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:21.544  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.554  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:21.554  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:21.554  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:21.554  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.554  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:21.554  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:21.554  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.554  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:21.564  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:21.564  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 14:17:21.564  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,08-26 14:17:21.564  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 14:17:21.564  2654  3041 D BtGatt.GattService: registerClient() - UUID=554233f0-6dc5-46c0-b3cb-39e5e0ca2286
,08-26 14:17:21.604  2654  2737 D BtGatt.GattService: onClientRegistered() - UUID=554233f0-6dc5-46c0-b3cb-39e5e0ca2286, clientIf=6
,08-26 14:17:21.604  6167  6175 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 14:17:21.614  2654  3039 D BtGatt.GattService: start scan with filters
,08-26 14:17:21.614  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 14:17:21.614  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:21.614  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:21.614  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:21.614  2654  2752 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:21.614  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:21.614  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:21.614  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-26 14:17:21.614  2654  2737 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 14:17:21.614  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:21.614  2654  2752 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:21.614  2654  2752 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 14:17:21.614  2654  2752 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 14:17:21.614  2654  2737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 14:17:21.614  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.624  2654  2752 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 14:17:21.624  2654  2752 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:21.624  2654  2737 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 14:17:21.624  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.624  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:21.624  2654  2737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 14:17:21.624  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.634  6167  6220 I io.jxcore.node.ConnectionHelper: start: OK
08-26 14:17:21.634  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.634  6167  6220 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:21.634  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.634  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:21.634  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.634  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:21.634  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:21.634  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:21.634  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:21.634  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:21.634  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:21.634  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:21.634  2654  3041 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:21.634  2654  2672 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:21.634  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 14:17:21.634  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:21.634  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:21.634  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:21.634  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:21.644  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:21.644  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 14:17:21.644  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:21.644  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-26 14:17:21.644  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:21.644  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-26 14:17:21.644  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:21.644  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:21.644  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:21.644  6167  6220 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:21.644  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:21.644  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:21.644  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.644  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:21.644  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:21.644  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
,08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.654  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list,
08-26 14:17:21.654  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.654  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.654  2654  2752 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 32
08-26 14:17:21.654  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.654  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.654  2654  2752 D BtGatt.ScanManager: filter size is 1
08-26 14:17:21.654  2654  2752 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.654  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
,08-26 14:17:21.654  6167  6220 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-26 14:17:21.654  2654  2737 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 14:17:21.654  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.654  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.654  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.654  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.654  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.654  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.654  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.654  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.654  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.654  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.654  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.654  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.654  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.654  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
,08-26 14:17:21.654  2654  2752 D BtGatt.ScanManager: stopping BLe Batch
08-26 14:17:21.654  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-26 14:17:21.654  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.654  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.654  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.654  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.654  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.654  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.654  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.654  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.654  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.654  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.654  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.654  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.654  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.654  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
,08-26 14:17:21.664  6167  6220 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null,
08-26 14:17:21.664  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.664  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:21.664  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.664  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.664  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.664  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
,08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.664  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.664  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.664  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:21.664  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.664  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.664  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,08-26 14:17:21.664  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.664  6167  6220 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-26 14:17:21.664  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:21.664  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.664  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.664  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.664  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.664  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.664  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
,08-26 14:17:21.664  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.664  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.664  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:21.664  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.664  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.664  2654  2737 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 14:17:21.664  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:21.664  2654  2752 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:21.664  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.664  2654  2737 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 14:17:21.664  2654  2737 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 14:17:21.664  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 14:17:21.664  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-26 14:17:21.664  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-26 14:17:21.664  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.664  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.664  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.664  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.664  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.664  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.664  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.664  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.664  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.664  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.664  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.664  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.664  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.674  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.674  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.674  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.674  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.674  6167  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:21.674  6167  6220 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-26 14:17:21.674  6167  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-26 14:17:21.674  6167  6220 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-26 14:17:21.674  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-26 14:17:21.674  6167  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-26 14:17:21.674  6167  6220 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:21.674  6167  6220 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-26 14:17:21.674  6167  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:21.674  6167  6220 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:21.674  6167  6220 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-26 14:17:21.674  6167  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:21.674  6167  6220 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-26 14:17:21.674  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-26 14:17:21.684  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-26 14:17:21.684  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-26 14:17:21.684  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-26 14:17:21.684  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-26 14:17:21.684  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-26 14:17:21.684  6167  6220 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-26 14:17:21.684  6167  6220 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-26 14:17:21.684  6167  6220 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-26 14:17:21.684  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.684  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.684  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.684  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.684  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.684  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.684  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-26 14:17:21.684  6167  6300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1128)
08-26 14:17:21.684  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.684  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.684  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.684  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.684  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.684  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.684  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.684  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.684  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.684  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.684  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.684  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.694  6167  6220 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-26 14:17:21.694  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.694  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.694  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.694  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.694  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.694  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.694  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.694  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.694  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.694  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.694  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.694  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.694  6167  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1128
08-26 14:17:21.694  6167  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 1128)
08-26 14:17:21.694  6167  6301 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1dd19e9e, channel: -1, state: INIT
08-26 14:17:21.694  6167  6301 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1dd19e9e, channel: -1, mSocketIS: null, mSocketOS: nullmSocket: null
08-26 14:17:21.694  6167  6301 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 1128)
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.694  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.694  6167  6220 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-26 14:17:21.694  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.694  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.694  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.694  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.694  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.694  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.694  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.694  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.694  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.694  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.694  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.694  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.694  6167  6300 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.694  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.694  6167  6220 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-26 14:17:21.694  6167  6300 D BluetoothSocket: connect(): myUserId = 0
08-26 14:17:21.694  6167  6220 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-26 14:17:21.694  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:21.694  6167  6220 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-26 14:17:21.694  6167  6220 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 14:17:21.694  6167  6220 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-26 14:17:21.694  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:21.694  6167  6220 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-26 14:17:21.694  6167  6220 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-26 14:17:21.694  6167  6220 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-26 14:17:21.694  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:21.694  6167  6220 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-26 14:17:21.694  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.694  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.694  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.694  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.694  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.694  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.694  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.694  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.694  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.694  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.694  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.694  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.694  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.694  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.704  6167  6300 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1dd19e9e, channel: -1, state: CLOSED
08-26 14:17:21.704  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.704  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.704  6167  6300 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1128)
08-26 14:17:21.704  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.704  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.704  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.704  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.704  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.704  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.704  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.704  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.704  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.704  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.704  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.704  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.704  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.704  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.704  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.704  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:21.704  6167  6167 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-26 14:17:21.704  6167  6302 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-26 14:17:21.704  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.704  6167  6167 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.704  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:21.704  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.704  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.704  6167  6302 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-26 14:17:21.714  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:21.714  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.714  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:21.714  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:21.714  6167  6167 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-26 14:17:21.714  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:21.714  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.714  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.714  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.714  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.714  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.714  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.714  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.714  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.714  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.714  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.714  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.714  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.714  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
,08-26 14:17:21.714  6167  6220 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-26 14:17:21.714  6167  6220 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-26 14:17:21.714  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-26 14:17:21.714  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.714  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.714  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.714  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.714  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.714  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.714  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.714  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.714  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.714  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.714  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.714  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.714  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.714  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.724  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.724  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.724  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.724  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.724  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.724  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.724  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.724  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.724  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.724  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.724  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.724  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.724  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.724  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.724  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.724  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.724  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.724  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.724  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:21.724  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:21.724  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:21.724  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:21.724  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.724  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.724  6167  6220 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3830328f not in the list
08-26 14:17:21.724  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.724  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.724  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:21.724  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.724  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.724  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:21.724  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:21.724  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:21.724  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:21.724  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:21.724  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@587491c not in the list
08-26 14:17:21.724  6167  6220 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-26 14:17:21.724  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:21.724  6167  6220 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-26 14:17:21.724  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-26 14:17:21.724  6167  6220 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-26 14:17:21.724  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-26 14:17:21.724  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-26 14:17:21.724  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-26 14:17:21.734  6167  6220 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-26 14:17:21.734  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 14:17:21.734  6167  6220 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-26 14:17:21.734  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-26 14:17:21.734  6167  6220 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-26 14:17:21.734  6167  6220 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-26 14:17:21.734  6167  6220 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-26 14:17:21.734  6167  6220 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-26 14:17:21.734  6167  6220 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-26 14:17:21.734  6167  6220 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-26 14:17:21.734  6167  6220 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-26 14:17:21.734  6167  6220 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-26 14:17:21.734  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:21.734  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1cc8dd7f added. We now have 2 listener(s)
08-26 14:17:21.734  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:21.734  6167  6220 D BluetoothAdapter: enable()
08-26 14:17:21.734  6167  6220 D BluetoothAdapter: enable(): BT is already enabled..!
08-26 14:17:21.734  1013  3042 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 14:17:21.734  1013  3042 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 14:17:21.734  1013  3042 D SecContentProvider2: mCursor = null
08-26 14:17:21.744  1013  3042 W WifiService: Failed getting userId using ActivityManagerNative
08-26 14:17:21.744  1013  3042 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6167, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:21.744  1013  3042 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-26 14:17:21.744  1013  3042 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 14:17:21.744  1013  3042 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 14:17:21.744  1013  3042 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 14:17:21.744  1013  3042 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 14:17:21.744  1013  3042 D WifiService: setWifiEnabled: true pid=6167, uid=10155
08-26 14:17:21.744  1013  3042 D SettingsProvider: name = wifi_on
08-26 14:17:21.744  1013  3042 W ActivityManager: Permission Denial: getCurrentUser() from pid=6167, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:21.744  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:21.744  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@43d314c added. We now have 3 listener(s)
08-26 14:17:21.744  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:21.744  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:21.744  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fdb5595 added. We now have 4 listener(s)
08-26 14:17:21.744  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:21.744  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:21.744  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ab506aa added. We now have 5 listener(s)
08-26 14:17:21.744  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:21.754  1013  1314 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 14:17:21.754  1013  1314 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 14:17:21.754  1013  1314 D SecContentProvider2: mCursor = null
08-26 14:17:21.754  1013  1314 D WifiService: setWifiEnabled: false pid=6167, uid=10155
08-26 14:17:21.754  1013  1314 D SettingsProvider: name = wifi_on
,08-26 14:17:21.754  1013  1121 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-26 14:17:21.764  2108  2108 I wpa_supplicant: reset timer : RESET_TIMER 0,
08-26 14:17:21.764  2108  2108 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-26 14:17:21.764  2108  2108 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 14:17:21.764  6167  6220 D BluetoothAdapter: disable()
,08-26 14:17:21.764  2108  2108 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 14:17:21.764  1013  1345 D SettingsProvider: name = bluetooth_on
08-26 14:17:21.764  1013  1121 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:21.774  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-26 14:17:21.774  2654  2734 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-26 14:17:21.774  2654  2734 D BluetoothAdapterProperties: Setting state to 13
,08-26 14:17:21.774  2654  2734 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 14:17:21.774  2654  2734 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:21.774  2654  2734 D BluetoothAdapterService: updateAdapterState state is 13
08-26 14:17:21.774  1013  3040 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:21.774  1013  3040 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.774  1013  3040 W ActivityManager: userId = 0, bbcId = -10000,
08-26 14:17:21.774  1013  3040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.774  1013  3040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.774  2654  2654 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 14:17:21.774  2654  2654 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25986968, channel: 19, state: LISTENING
08-26 14:17:21.774  2654  2654 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25986968, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37e64d02, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3297e226mSocket: android.net.LocalSocket@20f70e67 impl:android.net.LocalSocketImpl@1a3eb414 fd:FileDescriptor[74]
08-26 14:17:21.774  2654  2654 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@20f70e67 impl:android.net.LocalSocketImpl@1a3eb414 fd:FileDescriptor[74]
08-26 14:17:21.774  2654  2734 D BluetoothAdapterService: Autoconnection is available 
,08-26 14:17:21.774  2654  2734 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 14:17:21.774  2654  2734 D BluetoothAdapterService: terminating service from this receiver
08-26 14:17:21.784  1013  3119 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
08-26 14:17:21.784  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.784  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:21.784  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.784  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:21.784  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.784  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:21.784  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.784  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.784  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-26 14:17:21.784  1013  3119 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:21.784  1013  3119 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.784  1013  3119 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:21.784  2654  2734 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 14:17:21.784  2654  2734 D BluetoothAdapterProperties: mDiscovering is false
,08-26 14:17:21.784  1013  1345 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 14:17:21.784  2654  2734 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-26 14:17:21.784  1323  1323 D BluetoothPbap: Proxy object disconnected
08-26 14:17:21.784  1323  1323 D PbapServerProfile: Bluetooth service disconnected
08-26 14:17:21.784  1013  1121 E WifiNative-wlan0: do suspend true
,08-26 14:17:21.784  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.784  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.784  6167  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:21.794  2654  2737 D BluetoothUtils: getBtEnabledContainers(): btContainers = [],
08-26 14:17:21.794  2654  2737 D BluetoothAdapterProperties: Scan Mode:20
08-26 14:17:21.794  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:21.794  2654  2734 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-26 14:17:21.794  2654  2734 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 14:17:21.794  2654  2734 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 14:17:21.794  2654  2734 E bt-btif : cmd socket is not created
08-26 14:17:21.794  2654  4985 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:21.794  2654  2734 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 14:17:21.794  2654  2846 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-26 14:17:21.794  2654  2846 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-26 14:17:21.794  2654  2846 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:21.794  2654  2846 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration,
08-26 14:17:21.794  2654  2846 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:21.794  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.804  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:21.804  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:21.804  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:21.804  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:21.804  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:21.804  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:21.804  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-26 14:17:21.804  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-26 14:17:21.804  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-26 14:17:21.804  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:21.804  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-26 14:17:21.804  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.824  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:21.824  1013  1013 I InputMethodManagerService: [BT Setting State] State =13
,08-26 14:17:21.834  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-26 14:17:21.834  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 14:17:21.834  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:21.834  1175  1175 D BluetoothTile:  getBluetoothState : 13
,08-26 14:17:21.834  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
08-26 14:17:21.834  1896  1896 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 14:17:21.844  2654  2654 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c8ffab2, channel: 5, state: LISTENING
08-26 14:17:21.844  2654  2654 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c8ffab2, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27601249, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2f5c2a03mSocket: android.net.LocalSocket@5cfd80 impl:android.net.LocalSocketImpl@dd51fb9 fd:FileDescriptor[76]
08-26 14:17:21.844  2654  2654 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@5cfd80 impl:android.net.LocalSocketImpl@dd51fb9 fd:FileDescriptor[76]
,08-26 14:17:21.844  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:21.844  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:21.844  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 14:17:21.844  2654  2654 I BtOppRfcommListener: stopping Accept Thread
08-26 14:17:21.844  2654  2654 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@157f0ffe, channel: 12, state: LISTENING
08-26 14:17:21.844  2654  2654 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@157f0ffe, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1683b48b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3a6d635fmSocket: android.net.LocalSocket@2f5471ac impl:android.net.LocalSocketImpl@389efe75 fd:FileDescriptor[80]
08-26 14:17:21.844  2654  2654 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2f5471ac impl:android.net.LocalSocketImpl@389efe75 fd:FileDescriptor[80]
,08-26 14:17:21.844  2654  4985 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-26 14:17:21.844  1013  1314 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:21.844  1013  1713 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 14:17:21.844  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.844  1013  3040 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:21.844  1013  3040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.854  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:21.854  1013  3040 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:21.854  1013  3040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:21.854  1013  3040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:21.854  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 14:17:21.854  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:21.854  1013  3193 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 14:17:21.854  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:21.854  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:21.854  1013  3193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:21.854  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:21.864  2654  2654 V BluetoothOppManager: cleanUp...
,08-26 14:17:21.864  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:21.874  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:21.874  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:21.874  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 14:17:21.884  1013  1025 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,08-26 14:17:21.884  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:21.884  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:21.884  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:21.884  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:21.894  6308  6308 E Zygote  : MountEmulatedStorage()
08-26 14:17:21.894  6308  6308 I libpersona: KNOX_SDCARD checking this for 10003
08-26 14:17:21.894  6308  6308 E Zygote  : v2
08-26 14:17:21.894  6308  6308 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:21.894  6308  6308 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:21.894  1013  1025 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6308 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,08-26 14:17:21.894  6308  6308 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:21.904  6308  6308 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 14:17:21.914   308   308 I art     : Explicit concurrent mark sweep GC freed 8703(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 623us total 23.156ms
,08-26 14:17:21.934   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 19.264ms
,08-26 14:17:21.944  6308  6308 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:21.944  6308  6308 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:21.954   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.181ms
,08-26 14:17:21.974  6308  6308 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,08-26 14:17:21.994  2654  2846 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 14:17:21.994  2654  2846 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:21.994  2654  2846 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:21.994  2654  2953 I bt_userial_mct: exiting userial_read_thread
08-26 14:17:21.994  2654  2953 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 14:17:21.994  2654  2846 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:21.994  2654  2846 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:21.994  2654  2846 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:21.994  2654  2846 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:21.994  2654  2737 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 14:17:21.994  2654  2846 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:21.994  2654  2846 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:21.994  2654  2846 W bt-btif : ag scb idx 1 not allocated
08-26 14:17:21.994  2654  2846 W bt-btif : ag scb idx 2 not allocated
08-26 14:17:21.994  2654  2848 I bt_vendor: hw_epilog_process
08-26 14:17:21.994  2654  2846 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 14:17:21.994  2654  2737 D bt_userial_mct: userial_close
08-26 14:17:21.994  2654  2737 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 14:17:22.004  6308  6308 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,08-26 14:17:22.004  6308  6308 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
08-26 14:17:22.004  6308  6308 D UserAnalysis: Create SecureDbHelper
,08-26 14:17:22.014  6308  6308 D IntelligenceServiceApplication: onCreate()
,08-26 14:17:22.014   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
08-26 14:17:22.024  1013  1350 I ActivityManager: Killing 5026:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
08-26 14:17:22.024  6308  6308 D IntelligenceServiceApplication: no applications having user consent for prediction
,08-26 14:17:22.024  1013  3119 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,08-26 14:17:22.024  1013  1131 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-26 14:17:22.024  6308  6308 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,08-26 14:17:22.034  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.034  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:22.034  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:22.034  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.034  6308  6308 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,08-26 14:17:22.044  6328  6328 E Zygote  : MountEmulatedStorage()
,08-26 14:17:22.044  6328  6328 E Zygote  : v2
08-26 14:17:22.044  6328  6328 I libpersona: KNOX_SDCARD checking this for 10107
08-26 14:17:22.044  6328  6328 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:22.044  6328  6328 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:22.044  1013  1131 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6328 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
08-26 14:17:22.054  6328  6328 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:22.054  6328  6328 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 14:17:22.064  6328  6328 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:22.064  6328  6328 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:22.214  6167  6167 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-26 14:17:22.224  2654  2737 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 14:17:22.224  2654  2737 I bt_vendor: bluetooth satus is on
08-26 14:17:22.224  2654  2737 I bt_vendor: bt-vendor : resetting BT status
08-26 14:17:22.224  2654  2737 I bt_vendor: Starting hciattach daemon
08-26 14:17:22.224  2654  2737 I bt_vendor: try to set false
,08-26 14:17:22.224  2654  2737 I bt_vendor: Starting hciattach daemon
08-26 14:17:22.224  2654  2737 I bt_vendor: try to set false
,08-26 14:17:22.224  2654  2737 I bt_vendor: cleanup
,08-26 14:17:22.224  2654  2846 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 14:17:22.224  2654  2737 I GKI_LINUX: GKI_exit_task 0 done
08-26 14:17:22.224  2654  2737 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 14:17:22.224  2654  2734 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 14:17:22.224  2654  2734 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 14:17:22.224  2654  2734 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-26 14:17:22.224  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-26 14:17:22.224  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 14:17:22.224  2654  2734 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 14:17:22.234  1013  1131 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:22.234  1013  1131 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.234  1013  1131 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.234  1013  1131 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.234  1013  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.234  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 14:17:22.234  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 14:17:22.234  2654  2654 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 14:17:22.234  2654  2734 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 14:17:22.234  2654  2654 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 14:17:22.234  2654  2654 D BtGatt.GattService: stop()
08-26 14:17:22.234  2654  2654 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 14:17:22.234  1013  3042 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:22.234  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.234  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.234  1013  3042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.234  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.234  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 14:17:22.234  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
08-26 14:17:22.234  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:22.234  2654  2734 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:22.234  1013  1540 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:22.234  1013  1540 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.234  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.234  1013  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.234  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.244  2654  2654 D HeadsetService: Received stop request...Stopping profile...
,08-26 14:17:22.244  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-26 14:17:22.244  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:22.244  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:22.244  2654  2734 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-26 14:17:22.244  1013  3042 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:22.244  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-26 14:17:22.244  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
08-26 14:17:22.244  1323  1323 D HeadsetProfile: Bluetooth service disconnected
08-26 14:17:22.244  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.244  1013  3042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.244  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.244  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 14:17:22.244  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 14:17:22.244  2654  2734 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 14:17:22.254  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:22.254  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0,
08-26 14:17:22.254  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.254  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.254  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.254  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 14:17:22.254  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 14:17:22.264  2654  2734 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 14:17:22.264  1013  1261 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:22.264  1013  1261 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.264  1013  1261 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.264  1013  3193 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
08-26 14:17:22.264  1013  1261 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.264  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
08-26 14:17:22.264  1013  1261 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.264  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 14:17:22.264  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:22.264  2654  2734 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-26 14:17:22.264  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.264  1013  3193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.264  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
08-26 14:17:22.264  1013  3042 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:22.264  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.264  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.264  1013  3042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.264  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:22.264  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 14:17:22.264  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 14:17:22.264  2654  2734 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 14:17:22.264  1013  1350 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:22.264  1013  1350 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.274  1013  1350 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:22.274  1013  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.274  1013  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:22.274  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:22.274  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 14:17:22.274  2654  2734 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 14:17:22.274  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:22.274  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 14:17:22.274  2654  2734 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-26 14:17:22.274  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 14:17:22.274  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 14:17:22.274  2654  2734 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-26 14:17:22.274  2654  2734 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 14:17:22.274  2654  2734 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 14:17:22.274  2654  2734 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-26 14:17:22.274  2654  2654 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-26 14:17:22.274  2654  2734 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-26 14:17:22.274  2654  2654 D A2dpService: Received stop request...Stopping profile...
,08-26 14:17:22.284  2654  2777 D A2dpStateMachine: Exit Disconnected: -1
,08-26 14:17:22.284  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:22.284  2654  2654 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 14:17:22.284  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:22.284  2654  2654 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 14:17:22.284  1013  1013 D BluetoothA2dp: Proxy object disconnected
,08-26 14:17:22.284  2887  2887 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:22.284  1323  1323 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:22.284  1323  1323 D A2dpProfile: Bluetooth service disconnected
,08-26 14:17:22.284  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 14:17:22.284  2654  2654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,08-26 14:17:22.284  2654  2654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 14:17:22.294  2654  2654 D HidService: Received stop request...Stopping profile...
08-26 14:17:22.294  2654  2654 D HidService: Stopping Bluetooth HidService
08-26 14:17:22.294  2654  2654 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-26 14:17:22.294  2654  2654 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-26 14:17:22.294  2654  2654 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 14:17:22.294  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:22.294  1323  1323 D BluetoothInputDevice: Proxy object disconnected
,08-26 14:17:22.294  1323  1323 D HidProfile: Bluetooth service disconnected
08-26 14:17:22.294  2654  2654 D HealthService: Received stop request...Stopping profile...
08-26 14:17:22.294  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:22.294  2654  2654 D PanService: Received stop request...Stopping profile...
,08-26 14:17:22.294  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:22.294  1013  1013 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 14:17:22.304  2654  2654 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 14:17:22.304  1323  1323 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 14:17:22.304  1323  1323 D PanProfile: Bluetooth service disconnected
,08-26 14:17:22.304  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
08-26 14:17:22.304  1323  1323 D BluetoothMap: Proxy object disconnected
08-26 14:17:22.304  1323  1323 D MapProfile: Bluetooth service disconnected
,08-26 14:17:22.304  2654  2654 D SapService: Received stop request...Stopping profile...
08-26 14:17:22.304  2654  2654 D SapService: Stopping Bluetooth SapService
,08-26 14:17:22.304  2654  2654 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
08-26 14:17:22.304  6328  6328 D StrictMode: StrictMode policy violation; ~duration=194 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:22.304  6328  6328 D StrictMode: StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-26 14:17:22.304  6328  6,328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:22.304  6328  6328 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:22.,304  6328  6328 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:22.304  6328  6328 D StrictMode: StrictMode policy violation; ~duration=140 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:22.304  6328  6328 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:22.314  1013  3042 I ActivityManager: Killing 5545:com.google.android.apps.plus/u0a120 (adj 15): empty #31
08-26 14:17:22.304  6328  6328 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:22.304  6328  6328 D StrictMode: StrictMode policy violation; ~duration=135 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.k.c(PG:583)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.e.b(PG:170)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:22.304  6328  6328 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.io.File.exists(File.java:363)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:22.304  6328  6328 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-26 14:17:22.314  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:22.314  2654  2654 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-26 14:17:22.314  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:22.314  2654  2654 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-26 14:17:22.314  2654  2654 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:22.314  2654  2654 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-26 14:17:22.314  2654  2778 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-26 14:17:22.314  2654  2654 I GKI_LINUX: GKI_exit_task 2 done
08-26 14:17:22.314  2654  2654 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-26 14:17:22.314  2654  2654 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-26 14:17:22.314  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:22.314  2654  2654 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:22.314  2654  2654 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-26 14:17:22.314  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:22.314  2654  2654 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:22.314  2654  2654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-26 14:17:22.314  2654  2654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 14:17:22.324  2654  2654 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 14:17:22.324  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:22.324  2654  2654 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:22.324  2654  2654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 14:17:22.324  2654  2654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-26 14:17:22.324  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-26 14:17:22.324  2654  2654 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-26 14:17:22.324  2654  2654 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:22.324  2654  2654 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-26 14:17:22.324  2654  2654 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-26 14:17:22.324  2654  2654 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-26 14:17:22.324  2654  2654 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-26 14:17:22.324  2654  2734 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-26 14:17:22.324  2654  2734 D BluetoothAdapterProperties: Setting state to 10
08-26 14:17:22.324  2654  2734 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 14:17:22.324  2654  2734 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:22.324  2654  2734 D BluetoothAdapterService: updateAdapterState state is 10
08-26 14:17:22.324  1323  1323 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 14:17:22.324  2654  2734 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:22.324  1323  1323 D SapProfile: Bluetooth service disconnected
08-26 14:17:22.324  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:22.324  1323  1341 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:22.324  2654  2734 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 14:17:22.324  2654  2734 I BluetoothAdapterState: Entering OffState
08-26 14:17:22.324  1443  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:22.324  1443  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:22.334  1431  1439 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:22.334  1431  1439 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:22.334  6167  6177 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:22.334  6167  6177 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:22.334  6167  6177 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 14:17:22.334  6167  6177 D BluetoothLeAdvertiser: Exit stop advertising
08-26 14:17:22.334  6167  6177 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
08-26 14:17:22.334  6167  6177 D BluetoothLeScanner: Exiting stopAllScan
08-26 14:17:22.334  1905  2121 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:22.334  1905  2121 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:22.334  2887  2896 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:22.334  2654  3039 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:22.334  2654  3039 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:22.334  1323  1341 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 14:17:22.344  1323  1336 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-26 14:17:22.344  2887  2943 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:22.344  2887  2943 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:22.354  1175  3018 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:22.354  1175  3018 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:22.354  1323  1336 D Bluetoothsap: onBluetoothStateChange: up=false
08-26 14:17:22.354  1323  1336 D Bluetoothsap: Unbinding service...
08-26 14:17:22.354  1323  1341 D BluetoothMap: onBluetoothStateChange: up=false
08-26 14:17:22.354  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:22.354  1013  1042 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:22.354  1455  2158 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:22.354  1455  2158 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:22.364  2654  2672 D BluetoothA2dp: onBluetoothStateChange: up=false
08-26 14:17:22.364  1323  1336 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:22.364  1323  1336 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
08-26 14:17:22.364  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
08-26 14:17:22.364  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-26 14:17:22.374  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:22.374  1013  1013 I InputMethodManagerService: [BT Setting State] State =10
08-26 14:17:22.374  1013  1013 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-26 14:17:22.374  6328  6343 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-26 14:17:22.374  2654  2737 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 14:17:22.374  2654  2654 I GKI_LINUX: GKI_exit_task 1 done
08-26 14:17:22.374  2654  2654 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-26 14:17:22.374  2654  2654 I BluetoothServiceJni: cleanupNative: return from cleanup
08-26 14:17:22.374  1175  1175 D BluetoothAdapter: 1070518983: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:22.384  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 14:17:22.384  1175  1711 D BluetoothAdapter: 1070518983: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:22.384  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:22.384  1175  1175 D BluetoothTile:  getBluetoothState : 10
08-26 14:17:22.384  1175  1711 D BluetoothAdapter: 1070518983: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:22.384  2654  2654 I art     : System.exit called, status: 0
08-26 14:17:22.384  2654  2654 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-26 14:17:22.384  1175  1175 D BluetoothAdapter: 1070518983: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:22.384  1175  1175 D BluetoothAdapter: 1070518983: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:22.384  1013  3193 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 14:17:22.384  1013  3040 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 14:17:22.384  1896  1896 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 14:17:22.384  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:22.394  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 14:17:22.394  1013  1314 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:22.394  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 14:17:22.394  1905  2129 D BluetoothAdapter: 1006347221: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:22.394  1013  1314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 14:17:22.394  1905  2129 D BluetoothAdapter: 1006347221: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:22.394  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:22.394  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.394  1013  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.394  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:22.394  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:22.404  1013  3038 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 14:17:22.404  1013  3038 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4150, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
08-26 14:17:22.404  1013  3038 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-26 14:17:22.404  1013  3038 D BatteryService: stay LED for charging
08-26 14:17:22.404  1013  1539 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 14:17:22.404  1013  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:22.404  1013  1539 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.404  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-26 14:17:22.404  1013  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.404  1013  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:22.404  1013  1025 I ActivityManager: Process com.android.bluetooth (pid 2654)(adj 0) has died(47,1097)
,08-26 14:17:22.404  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:22.414  1013  1013 I MotionRecognitionService: Plugged
08-26 14:17:22.414  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 14:17:22.414  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 14:17:22.414  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-26 14:17:22.414  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 14:17:22.414  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
,08-26 14:17:22.424  1013  1350 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:22.424  1013  1350 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:22.424  1013  1350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.424  1013  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,08-26 14:17:22.434  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-26 14:17:22.434  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
08-26 14:17:22.434  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-26 14:17:22.434  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:22.444  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:22.444  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 14:17:22.454  1013  1314 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-26 14:17:22.454  1013  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:22.454  1013  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:22.454  1013  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:22.454  1013  1314 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.464  6358  6358 E Zygote  : MountEmulatedStorage()
08-26 14:17:22.464  1013  1314 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6358 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
08-26 14:17:22.464  6358  6358 E Zygote  : v2
08-26 14:17:22.464  6358  6358 I libpersona: KNOX_SDCARD checking this for 1002
08-26 14:17:22.464  6358  6358 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 14:17:22.464  6358  6358 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:22.464  6358  6358 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:22.474  6358  6358 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:22.484  6358  6358 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:22.484  6358  6358 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:22.504  6358  6358 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 14:17:22.504  6358  6358 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:22.524  6358  6358 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding GattService
,08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding HeadsetService
08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding A2dpService
,08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding HidService
08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding HealthService
,08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding PanService
08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding SapService
08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding SapClientService
08-26 14:17:22.554  6358  6358 D BtSettings.ProfileConfig: Adding HidDevService
08-26 14:17:22.554  6358  6358 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******,
,08-26 14:17:22.564  1013  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService,
08-26 14:17:22.564  1013  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:22.564  1013  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.564  1013  1026 D SettingsProvider: selectionArgs: false
08-26 14:17:22.564  1013  1026 D SettingsProvider: selectionArgs: 1002
08-26 14:17:22.564  1013  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
08-26 14:17:22.564  1013  1026 D SettingsProvider: ret = -1
08-26 14:17:22.564  1013  3040 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-26 14:17:22.564  1013  3040 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:22.564  1013  3040 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.564  1013  3040 D SettingsProvider: selectionArgs: false
08-26 14:17:22.564  1013  3040 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:22.564  1013  3040 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:22.564  1013  3040 D SettingsProvider: ret = -1
08-26 14:17:22.564  1013  3119 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-26 14:17:22.564  1013  3119 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:22.564  1013  3119 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.564  1013  3119 D SettingsProvider: selectionArgs: false
,08-26 14:17:22.564  1013  3119 D SettingsProvider: selectionArgs: 1002
08-26 14:17:22.564  1013  3119 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:22.564  1013  3119 D SettingsProvider: ret = -1
08-26 14:17:22.564  1013  3038 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-26 14:17:22.564  1013  3038 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 14:17:22.564  1013  3038 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.564  1013  3038 D SettingsProvider: selectionArgs: false
08-26 14:17:22.564  1013  3038 D SettingsProvider: selectionArgs: 1002
08-26 14:17:22.564  1013  3038 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:22.564  1013  3038 D SettingsProvider: ret = -1
08-26 14:17:22.564  1013  1713 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 14:17:22.564  1013  1713 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-26 14:17:22.564  1013  1713 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.564  1013  1713 D SettingsProvider: selectionArgs: false
08-26 14:17:22.564  1013  1713 D SettingsProvider: selectionArgs: 1002
08-26 14:17:22.564  1013  1713 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:22.564  1013  1713 D SettingsProvider: ret = -1
,08-26 14:17:22.564  1013  1261 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,08-26 14:17:22.564  1013  1261 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:22.564  1013  1261 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.564  1013  1261 D SettingsProvider: selectionArgs: false
,08-26 14:17:22.564  1013  1261 D SettingsProvider: selectionArgs: 1002
08-26 14:17:22.564  1013  1261 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:22.564  1013  1261 D SettingsProvider: ret = -1
,08-26 14:17:22.564  1013  1345 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService,
08-26 14:17:22.564  1013  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:22.564  1013  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.564  1013  1345 D SettingsProvider: selectionArgs: false
,08-26 14:17:22.564  1013  1345 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:22.564  1013  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:22.564  1013  1345 D SettingsProvider: ret = -1,
08-26 14:17:22.564  1013  1314 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
,08-26 14:17:22.564  1013  1314 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:22.564  1013  1314 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
,08-26 14:17:22.564  1013  1314 D SettingsProvider: selectionArgs: false
08-26 14:17:22.564  1013  1314 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:22.574  1013  1314 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:22.574  1013  1314 D SettingsProvider: ret = -1
08-26 14:17:22.574  1013  3042 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:22.574  1013  3042 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-26 14:17:22.574  1013  3042 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.574  1013  3042 D SettingsProvider: selectionArgs: false
,08-26 14:17:22.574  1013  3042 D SettingsProvider: selectionArgs: 1002
08-26 14:17:22.574  1013  3042 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:22.574  1013  3042 D SettingsProvider: ret = -1
08-26 14:17:22.574  1013  1540 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-26 14:17:22.574  1013  1540 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:22.574  1013  1540 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.574  1013  1540 D SettingsProvider: selectionArgs: false
,08-26 14:17:22.574  1013  1540 D SettingsProvider: selectionArgs: 1002
08-26 14:17:22.574  1013  1540 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:22.574  1013  1540 D SettingsProvider: ret = -1
,08-26 14:17:22.574  1013  1025 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 14:17:22.574  1013  1025 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:22.574  1013  1025 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.574  1013  1025 D SettingsProvider: selectionArgs: false
08-26 14:17:22.574  1013  1025 D SettingsProvider: selectionArgs: 1002
08-26 14:17:22.574  1013  1025 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:22.574  1013  1025 D SettingsProvider: ret = -1
08-26 14:17:22.574  1013  1350 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,08-26 14:17:22.574  1013  1350 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:22.574  1013  1350 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:22.574  1013  1350 D SettingsProvider: selectionArgs: false
08-26 14:17:22.574  1013  1350 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:22.574  1013  1350 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:22.574  1013  1350 D SettingsProvider: ret = -1
,08-26 14:17:22.584  1013  1120 D WifiP2pService: InactiveState{ what=143375 }
,08-26 14:17:22.584  1013  1120 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 14:17:22.604   276  1012 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:22.604  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:22.604  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 14:17:22.604  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:22.604  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:22.604  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:22.604  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:22.614  1013  1539 I ActivityManager: Killing 5454:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,08-26 14:17:22.624  1905  4538 V NativeCrypto: Read error: ssl=0xb7eb53a0: I/O error during system call, Connection timed out
08-26 14:17:22.624  1905  4538 V NativeCrypto: SSL shutdown failed: ssl=0xb7eb53a0: I/O error during system call, Broken pipe
08-26 14:17:22.624  1905  4538 E GCM     : Wifi connection closed with errorCode 20
,08-26 14:17:22.624  1013  1120 D WifiP2pService: InactiveState{ what=131204 }
08-26 14:17:22.634  1013  1123 E ConnectivityService: updateNetworkInfo()
08-26 14:17:22.624  1013  1120 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 14:17:22.634  1013  1123 E ConnectivityService: updateNetworkInfo()
08-26 14:17:22.634  1013  1123 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 14:17:22.634  1013  1123 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-26 14:17:22.634  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:22.634  1013  1121 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-26 14:17:22.634  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 14:17:22.634  1013  1120 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-26 14:17:22.634  1013  1539 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
08-26 14:17:22.634  1013  2245 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:22.634  1013  2245 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:22.634  1013  2245 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-26 14:17:22.634  1013  2245 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:22.634  1013  2245 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
08-26 14:17:22.634  1013  2245 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:22.644  1013  2245 I qtaguid : Tagging socket 353 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1013, getuid(): 1000
,08-26 14:17:22.644  1013  2245 I qtaguid : Untagging socket 353
,08-26 14:17:22.654  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:22.654  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:22.654  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:22.654  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:22.654  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:22.654  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:22.654  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 1
08-26 14:17:22.654  1013  1146 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:22.654  1013  2245 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-26 14:17:22.654  1013  1013 D RttService: SCAN_AVAILABLE : 1
08-26 14:17:22.654  1013  3040 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:22.654  1013  1147 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:22.654  1013  3040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
08-26 14:17:22.654  1013  3040 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.654  1013  3040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.654  1013  3040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:22.674  1905  6380 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 14:17:22.674  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:22.684  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-26 14:17:22.684  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
,08-26 14:17:22.684  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:22.684  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 14:17:22.684  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 14:17:22.684  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.684  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.684  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:22.694  1013  1120 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 14:17:22.694  1013  1120 D WifiP2pService: P2pDisablingState
08-26 14:17:22.694  1013  1120 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 14:17:22.694  1013  1120 D WifiP2pService: p2p socket connection lost
08-26 14:17:22.694  1013  1120 D WifiP2pService: P2pDisabledState
,08-26 14:17:22.694  1013  1121 E WifiNative-wlan0: do suspend true
08-26 14:17:22.694  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-26 14:17:22.694  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:22.694  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 14:17:22.694  1013  1043 D WifiDisplayController: disconnect
08-26 14:17:22.694  1013  1043 D WifiDisplayController: updateConnection
08-26 14:17:22.694  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:22.694  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:22.694   276  1008 D EnterpriseController: uids 1000
08-26 14:17:22.694   276  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 14:17:22.694   276  1008 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,08-26 14:17:22.694  1013  2245 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
08-26 14:17:22.694  1013  1123 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,08-26 14:17:22.694  1013  2245 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 14:17:22.694  1013  1123 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-26 14:17:22.694  1175  1692 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-26 14:17:22.694  1013  1123 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:22.694  1013  2245 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:22.694  1013  1123 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-26 14:17:22.694  3835  6229 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292,
08-26 14:17:22.694  1013  1123 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-26 14:17:22.694  1013  1120 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 14:17:22.694  1013  1123 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 14:17:22.694  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 14:17:22.694  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-26 14:17:22.694  1455  1455 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:22.694  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
08-26 14:17:22.694  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 14:17:22.704  1013  1042 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 14:17:22.694  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null,
08-26 14:17:22.704  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-26 14:17:22.704  1013  3042 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 14:17:22.704  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 14:17:22.714  1013  1013 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
08-26 14:17:22.714  1013  1126 D Tethering: MasterInitialState.processMessage what=3
08-26 14:17:22.714  1013  1123 D ConnectivityService: nai.networkMonitor.doQuit()
08-26 14:17:22.714  1013  1123 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
08-26 14:17:22.714  1013  1123 E ConnectivityService: updateNetworkInfo()
08-26 14:17:22.714  1013  1123 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:22.714  1013  1123 E ConnectivityService: updateNetworkInfo()
,08-26 14:17:22.714  1013  1042 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,08-26 14:17:22.714  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:22.714  1013  1118 V NetworkStats: updateIfacesLocked()
08-26 14:17:22.714  1013  1118 V NetworkStats: performPollLocked(flags=0x1)
,08-26 14:17:22.714  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-26 14:17:22.714  1013  3119 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:22.714  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 14:17:22.714  1013  3119 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:22.714  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 14:17:22.714  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-26 14:17:22.714  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 14:17:22.714  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 14:17:22.714  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:22.714  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:22.714  1013  3119 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.714  1013  3119 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:22.714  1013  3119 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:22.724  1013  1118 V NetworkStats: performPollLocked() took 7ms
08-26 14:17:22.724  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:22.724  1013  1131 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-26 14:17:22.724  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:22.724  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:22.724  3651  3651 I Hs20UtilService: Starting #8
08-26 14:17:22.724  1013  1119 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 14:17:22.724  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:22.724  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:22.724  3651  3690 I Hs20UtilService: Message received 5007
08-26 14:17:22.724  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-26 14:17:22.724  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 14:17:22.724  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 14:17:22.724  1013  1131 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:22.724  1013  1131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.724  1013  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 14:17:22.724  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:22.724  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 14:17:22.724  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:22.724  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:22.724  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:22.724  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:22.734  1905  6380 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 14:17:22.734  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:22.734  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:22.734  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 14:17:22.734  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 14:17:22.734  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:22.744  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 14:17:22.744  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:22.744  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:22.744  1323  3080 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:22.764  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 14:17:22.764  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 14:17:22.764  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:22.764  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 14:17:22.764  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:22.764  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 14:17:22.774  1323  3080 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:22.774  1013  1541 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,08-26 14:17:22.774  1013  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.774  1013  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:22.774  1013  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:22.774  1013  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.784  1013  1045 I PowerManagerService: [PWL] Off : 50s ago,
08-26 14:17:22.784  1013  1045 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-26 14:17:22.784  1013  1045 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,08-26 14:17:22.784  1013  1045 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1013, ws=null) (elapsedTime=73)
,08-26 14:17:22.784  6384  6384 E Zygote  : MountEmulatedStorage()
08-26 14:17:22.784  6384  6384 I libpersona: KNOX_SDCARD checking this for 10068
08-26 14:17:22.784  6384  6384 E Zygote  : v2
08-26 14:17:22.784  6384  6384 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:22.784  6384  6384 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 14:17:22.794  1013  1541 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6384 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:22.794  6384  6384 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:22.794  6384  6384 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:22.814  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.814  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.814  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.814  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.824  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.824  6384  6384 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:22.824  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-26 14:17:22.824  6384  6384 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:22.824  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.824  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.824  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.834  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.834  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.834  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.834  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.834  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.834  6384  6384 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 14:17:22.834  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.834  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.834  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.844  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.844  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.844  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.844  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.844  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.844  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.844  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.854  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.854  6384  6384 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:22.854  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.854  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.854  6384  6384 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 14:17:22.854  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.854  1455  1455 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,08-26 14:17:22.854  1455  1455 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-26 14:17:22.884  6384  6384 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 14:17:22.884  1013  3193 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,08-26 14:17:22.884  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.884  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:22.884  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.884  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.904  6414  6414 E Zygote  : MountEmulatedStorage(),
08-26 14:17:22.904  6414  6414 I libpersona: KNOX_SDCARD checking this for 10069
08-26 14:17:22.904  6414  6414 E Zygote  : v2
,08-26 14:17:22.904  6414  6414 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:22.904  1013  3193 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6414 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 14:17:22.904  6414  6414 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:22.914  6414  6414 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 14:17:22.914  6414  6414 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:22.914  1013  2741 D SSRM:n  : SIOP:: AP = 360
,08-26 14:17:22.934  6414  6414 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:22.934  6414  6414 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:22.954  6414  6414 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:22.954  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:22.964  1013  3193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:22.964  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
08-26 14:17:22.964  1013  3193 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-26 14:17:22.964  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.964  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:22.964  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.964  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:22.974  6429  6429 E Zygote  : MountEmulatedStorage()
08-26 14:17:22.974  1013  3193 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6429 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
08-26 14:17:22.974  6429  6429 E Zygote  : v2
08-26 14:17:22.974  6429  6429 I libpersona: KNOX_SDCARD checking this for 10104
08-26 14:17:22.974  6429  6429 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 14:17:22.974  6429  6429 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:22.974  1013  3193 I ActivityManager: Killing 5745:com.sec.pcw.device/1000 (adj 15): empty #31
,08-26 14:17:22.984  6429  6429 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:22.984  6429  6429 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 14:17:23.004  6429  6429 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:23.004  6429  6429 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:23.014   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:23.024  6429  6429 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 14:17:23.204  6429  6452 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-26 14:17:23.204  6429  6452 I Babel   : MmsConfig.loadMmsSettings
,08-26 14:17:23.204  6429  6452 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
08-26 14:17:23.204  6429  6452 I Babel   : MmsConfig.loadFromDatabase
,08-26 14:17:23.214  1013  1123 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:23.214  6429  6452 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-26 14:17:23.214  6429  6452 I Babel   : MmsConfig.loadFromResources
,08-26 14:17:23.224  1013  1013 I ApplicationPolicy: updateDataUsageMap
,08-26 14:17:23.224  6429  6452 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-26 14:17:23.224  6429  6452 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,08-26 14:17:23.224  1013  1037 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:23.234  3141  3141 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,08-26 14:17:23.234  3141  3141 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,08-26 14:17:23.234  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:23.234  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:23.234  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:23.234  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:23.234  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:23.234  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:23.234  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:23.244  1013  3040 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
08-26 14:17:23.244  1013  3040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
08-26 14:17:23.244  1013  3040 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:23.244  1013  3040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:23.244  1013  3040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
08-26 14:17:23.254  6429  6429 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:23.284  6429  6429 I Babel_StickerModule: App launched.
,08-26 14:17:23.294  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.294  1013  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.294  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.304   281   677 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-26 14:17:23.304   281   677 W QCamera2Factory: getCameraInfo: X
,08-26 14:17:23.304   281   281 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-26 14:17:23.304   281   281 W QCamera2Factory: getCameraInfo: X
,08-26 14:17:23.324  6429  6429 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-26 14:17:23.324  6429  6429 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 14:17:23.324  6429  6429 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 14:17:23.324  6429  6429 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-26 14:17:23.324  6429  6429 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-26 14:17:23.324  6429  6429 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-26 14:17:23.334  6429  6429 W AudioCapabilities: Unsupported mime audio/x-ima
,08-26 14:17:23.334  6429  6429 W AudioCapabilities: Unsupported mime audio/qcelp
,08-26 14:17:23.334  6429  6429 W AudioCapabilities: Unsupported mime audio/evrc
,08-26 14:17:23.344  6429  6429 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 14:17:23.344  6429  6429 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 14:17:23.354  6429  6429 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-26 14:17:23.364  6429  6429 W VideoCapabilities: Unsupported mime video/wvc1
,08-26 14:17:23.364  6429  6429 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-26 14:17:23.364  6429  6429 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-26 14:17:23.364  6429  6429 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-26 14:17:23.374  6429  6429 W VideoCapabilities: Unsupported mime video/mp43
,08-26 14:17:23.374  6429  6429 W VideoCapabilities: Unsupported mime video/sorenson
,08-26 14:17:23.384  6429  6429 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-26 14:17:23.394  6429  6429 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-26 14:17:23.414  1013  1131 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
08-26 14:17:23.414  1013  1131 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,08-26 14:17:23.424  1013  1131 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:23.424  1013  1131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:23.424  1013  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,08-26 14:17:23.424  1013  3119 I ActivityManager: Killing 5103:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,08-26 14:17:23.494  1013  1120 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-26 14:17:23.494  1013  1120 D WifiP2pService: DefaultState{ what=143375 }
,08-26 14:17:23.494   276  1012 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:23.494  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:23.494  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:23.494  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:23.494  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:23.494  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:23.494  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:23.504  2108  2108 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 14:17:23.504  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:23.504  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:23.504  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:23.504  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:23.504  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:23.504  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:23.504  1013  1121 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,08-26 14:17:23.514  1013  1121 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:23.514  1013  1121 D SecContentProvider2: mCursor = null
,08-26 14:17:23.514  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:23.514  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 14:17:23.514  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:23.514  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:23.514  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:23.514  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:23.514  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:23.514  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-26 14:17:23.514  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:23.514  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 14:17:23.514  1175  1175 D HotspotTile: onReceive : 0, 0
,08-26 14:17:23.514  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:23.524  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:23.524  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:23.524  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:23.524  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:23.524  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:23.524  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:23.524  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:23.654  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:23.654  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.654  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.654  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 14:17:23.654  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:23.654  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.654  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.664  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:23.664  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.664  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.664  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:23.664  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.664  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.664  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.664  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.664  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.664  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.664  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.664  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.674  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.674  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.674  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.674  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.674  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.674  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.684  2108  2108 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 14:17:23.684  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.684  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:23.684  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.684  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.684  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:23.684  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system,
,08-26 14:17:23.684  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.694  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:23.694  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.694  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.694  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:23.694  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.694  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.694  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-26 14:17:23.694  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.704  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:23.704  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:23.704  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,08-26 14:17:23.704  1013  1013 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-26 14:17:23.704  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:23.704  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 14:17:23.704  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:23.704  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:23.724  1013  1013 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-26 14:17:23.724  6456  6456 E Zygote  : MountEmulatedStorage(),
08-26 14:17:23.724  6456  6456 E Zygote  : v2
08-26 14:17:23.724  6456  6456 I libpersona: KNOX_SDCARD checking this for 1000
,08-26 14:17:23.724  6456  6456 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:23.724  6456  6456 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:23.734  6456  6456 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 14:17:23.734  6456  6456 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:23.764  6456  6456 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:23.764  6456  6456 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:23.774  2108  2108 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-26 14:17:23.774  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:23.774  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
08-26 14:17:23.774  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 14:17:23.794  2108  2108 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-26 14:17:23.794  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:23.794  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false,
08-26 14:17:23.794  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:23.794  6456  6456 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-26 14:17:23.794  2108  2108 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-26 14:17:23.794  6456  6456 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-26 14:17:23.794  2108  2108 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
08-26 14:17:23.794  6456  6456 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
08-26 14:17:23.794  2108  2108 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
08-26 14:17:23.794  2108  2108 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-26 14:17:23.794  1013  1126 D Tethering: InitialState.processMessage what=4
08-26 14:17:23.804  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:23.804  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:23.804  1013  1121 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,08-26 14:17:23.804  1013  1126 E Tethering: No numeric data
08-26 14:17:23.804  1013  1118 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:23.804  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:23.804  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:23.804  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:23.804  1175  1175 D HotspotTile: updateTetherState():false, false
08-26 14:17:23.804  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 14:17:23.804  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:23.804  1013  1126 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 14:17:23.814  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:23.804  1013  1126 D Tethering: clearTetheredNotification()
08-26 14:17:23.814  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:23.814  1013  1118 V NetworkStats: performPollLocked() took 7ms
08-26 14:17:23.814  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:23.814  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:23.814  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:23.814  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:23.814  6456  6456 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true,
08-26 14:17:23.814  6456  6456 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 14:17:23.814  6456  6456 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM],
08-26 14:17:23.814  6456  6456 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:23.824  1013  3038 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,08-26 14:17:23.824  1013  3038 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,08-26 14:17:23.824  1013  3038 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-26 14:17:23.824  1013  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:23.824  1013  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:23.824  1013  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:23.824  1013  3038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:23.824  6456  6471 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-26 14:17:23.834  6473  6473 E Zygote  : MountEmulatedStorage()
,08-26 14:17:23.834  1013  3038 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6473 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 14:17:23.834  6473  6473 E Zygote  : v2
08-26 14:17:23.834  6473  6473 I libpersona: KNOX_SDCARD checking this for 10111
08-26 14:17:23.834  6473  6473 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:23.844  6473  6473 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:23.844  1013  3038 I ActivityManager: Killing 5763:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,08-26 14:17:23.844  6473  6473 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 14:17:23.844  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-26 14:17:23.844  6473  6473 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 14:17:23.844  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:23.844  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:23.844  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:23.844  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:23.854   270   270 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb76757c8,
08-26 14:17:23.854   270   270 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
,08-26 14:17:23.854   270   270 I rmt_storage: wakelock acquired: 1, error no: 42
08-26 14:17:23.854   270   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1217963896)
,08-26 14:17:23.864  6482  6482 E Zygote  : MountEmulatedStorage()
08-26 14:17:23.864  6482  6482 E Zygote  : v2
08-26 14:17:23.864  6482  6482 I libpersona: KNOX_SDCARD checking this for 10009
08-26 14:17:23.864  6482  6482 I libpersona: KNOX_SDCARD not a persona,
08-26 14:17:23.864  6482  6482 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:23.864  6482  6482 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:23.864  6482  6482 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,08-26 14:17:23.874  1013  1038 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6482 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 14:17:23.874  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast,
08-26 14:17:23.874  1727  1727 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
08-26 14:17:23.874  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:23.874  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:23.874  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:23.874  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:23.884  6473  6473 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:23.884  6473  6473 D ActivityThread: Added TimaKeyStore provider,
,08-26 14:17:23.894  6503  6503 E Zygote  : MountEmulatedStorage()
,08-26 14:17:23.894  6503  6503 E Zygote  : v2,
,08-26 14:17:23.894  6503  6503 I libpersona: KNOX_SDCARD checking this for 10145
08-26 14:17:23.894  6503  6503 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:23.904  6503  6503 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:23.904  1013  1038 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6503 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-26 14:17:23.904  6482  6482 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:23.904  6482  6482 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:23.904  1013  1539 I ActivityManager: Killing 5779:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,08-26 14:17:23.904  6503  6503 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 14:17:23.904  6503  6503 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:23.914  1727  1727 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
08-26 14:17:23.914  1727  1727 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
08-26 14:17:23.914  1727  1727 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
08-26 14:17:23.914  1727  1727 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,08-26 14:17:23.914   270   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
08-26 14:17:23.914   270   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
08-26 14:17:23.914   270   341 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1217963896) wakelock released: 1, error no: 0
08-26 14:17:23.914   270   341 I rmt_storage: 
08-26 14:17:23.914   270   270 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb76757c8
,08-26 14:17:23.924  1727  1727 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,08-26 14:17:23.924  1292  1753 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 8
08-26 14:17:23.924  1727  1727 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,08-26 14:17:23.924  1013  3040 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast,
08-26 14:17:23.934  1013  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:23.934  1013  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:23.934  1013  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:23.934  1013  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:23.944  6503  6503 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:23.944  6503  6503 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:23.944  6517  6517 E Zygote  : MountEmulatedStorage()
08-26 14:17:23.944  6517  6517 I libpersona: KNOX_SDCARD checking this for 10081
08-26 14:17:23.944  6517  6517 E Zygote  : v2
08-26 14:17:23.944  6517  6517 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:23.944  6517  6517 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 14:17:23.954  6517  6517 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 14:17:23.954  6517  6517 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
08-26 14:17:23.954  1013  3040 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6517 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:23.974  1727  1727 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,08-26 14:17:23.984  2108  2108 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 14:17:23.984  6517  6517 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:23.984  6517  6517 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:23.994  6503  6503 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-26 14:17:23.994  6503  6503 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:23.994  6503  6503 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-26 14:17:23.994  6503  6503 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:23.994  6503  6503 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 14:17:24.004  1013  3042 I ActivityManager: Killing 5478:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,08-26 14:17:24.014  3698  3698 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 14:17:24 GMT+02:00 2016
,08-26 14:17:24.014  1013  1131 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 14:17:24.014  1013  1131 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 14:17:24.014  1013  1131 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:24.014  1013  1131 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:24.014  1013  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 14:17:24.014   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:24.014   286   286 E SMD     : DCD OFF
08-26 14:17:24.024  3698  3698 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-26 14:17:24.024  6473  6473 I MusicStore: Database version: 108
08-26 14:17:24.024  1013  1713 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
08-26 14:17:24.024  1013  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.024  1013  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.024  1013  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.024  1013  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.034  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:24.034  2108  2108 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-26 14:17:24.034  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:24.034  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 14:17:24.034  3698  3698 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,08-26 14:17:24.034  3698  3698 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 14:17:24.044  3698  3698 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 14:17:24.044  3698  6536 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-26 14:17:24.044  3698  6536 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
08-26 14:17:24.054  6540  6540 E Zygote  : MountEmulatedStorage()
08-26 14:17:24.054  6540  6540 E Zygote  : v2
08-26 14:17:24.054  6540  6540 I libpersona: KNOX_SDCARD checking this for 10034
08-26 14:17:24.054  6540  6540 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:24.054  6540  6540 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:24.054  1013  1713 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6540 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,08-26 14:17:24.054  6540  6540 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:24.054  6540  6540 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:24.054  1013  1541 D RCPManagerService: exchangeData() failure , invalid userId
08-26 14:17:24.054  1013  1350 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-26 14:17:24.054  1013  1350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-26 14:17:24.064  3698  6536 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
08-26 14:17:24.064  1013  1350 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:24.064  1013  1350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:24.064  1013  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
08-26 14:17:24.064  3698  6536 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,08-26 14:17:24.064  3698  3698 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-26 14:17:24.074   308   308 I art     : Explicit concurrent mark sweep GC freed 8718(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 22.119ms
,08-26 14:17:24.084  6540  6540 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:24.084  6540  6540 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:24.094   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.187ms
,08-26 14:17:24.114   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 728us total 17.240ms
,08-26 14:17:24.114  1013  1713 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:24.134  6540  6540 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,08-26 14:17:24.134  6473  6473 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-26 14:17:24.134  6473  6473 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-26 14:17:24.144  1013  1121 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 14:17:24.144  1013  1121 D WifiNative-wlan0: callSECApiBoolean - ID [21]
08-26 14:17:24.144  1013  1121 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 14:17:24.144  6429  6429 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:24.154  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:24.154  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 14:17:24.154  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:24.154  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:24.154  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:24.154  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:24.154  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:24.154  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 14:17:24.154  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:24.154  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 14:17:24.154  1175  1175 D HotspotTile: onReceive : 1, 0
,08-26 14:17:24.154  1905  2129 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-26 14:17:24.154  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:24.164  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:24.164  1013  3119 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-26 14:17:24.164  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:24.164  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.164  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.164  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.164  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.174  1013  1350 D RCPManagerService: exchangeData() failure , invalid userId
08-26 14:17:24.174  6562  6562 E Zygote  : MountEmulatedStorage()
08-26 14:17:24.174  6562  6562 E Zygote  : v2
08-26 14:17:24.174  6562  6562 I libpersona: KNOX_SDCARD checking this for 10113
08-26 14:17:24.174  6562  6562 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:24.174  6562  6562 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:24.174  6562  6562 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 14:17:24.174  1013  3119 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6562 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 14:17:24.184  6562  6562 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-26 14:17:24.184  1013  3119 I ActivityManager: Killing 4133:com.sec.spp.push/u0a35 (adj 15): empty #31
,08-26 14:17:24.184  6473  6473 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-26 14:17:24.194  3211  6569 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
08-26 14:17:24.194  3211  6569 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-26 14:17:24.204  3211  6569 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-26 14:17:24.204  3211  6569 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-26 14:17:24.204  1013  1345 D RCPManagerService: exchangeData() failure , invalid userId
08-26 14:17:24.204  3211  6569 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-26 14:17:24.214  6562  6562 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:24.224  6562  6562 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:24.234  5977  5977 I SA      : [DM] init START
,08-26 14:17:24.244  6473  6473 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-26 14:17:24.244  6473  6473 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@379c7a5a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-26 14:17:24.244  6473  6473 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-26 14:17:24.244  6473  6473 D AndroidMusic: GMSCore installation verified
,08-26 14:17:24.254  5977  5977 I SA      : [DM] This device is not a Vodafone
,08-26 14:17:24.264  5977  5977 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,08-26 14:17:24.264  5977  5977 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-26 14:17:24.264  5977  5977 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,08-26 14:17:24.264  5977  5977 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
08-26 14:17:24.264  5977  5977 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,08-26 14:17:24.264  5977  5977 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
08-26 14:17:24.264  5977  5977 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,08-26 14:17:24.264  5873  5881 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-26 14:17:24.264  5977  5977 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-26 14:17:24.264  5977  5977 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,08-26 14:17:24.264  5977  5977 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-26 14:17:24.264  5977  5977 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,08-26 14:17:24.274  1013  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-26 14:17:24.274  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,08-26 14:17:24.274  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:24.274  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
08-26 14:17:24.274  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75),
08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75),
08-26 14:17:24.274  5977  5977 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-26 14:17:24.284  5977  5977 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,08-26 14:17:24.284  5977  5977 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
08-26 14:17:24.284  5977  5977 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,08-26 14:17:24.284  5977  5977 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,08-26 14:17:24.284  6473  6473 I ConfigStore: Config Database version: 1
,08-26 14:17:24.294  1476  1476 D Launcher.Model: reloadBadges entered.
,08-26 14:17:24.294  5873  5923 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-26 14:17:24.294  5873  5923 D BadgeProvider: sendNotify, [notify] : null
08-26 14:17:24.294  5873  5923 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-26 14:17:24.294  5873  5923 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 14:17:24.294  5873  5923 D BadgeProvider: update, [UpdateCount] : 1
,08-26 14:17:24.304  5977  5977 I SA      : [SCU] isHaveSA() - false
08-26 14:17:24.304  5977  5977 I SA      : support phone number id : false
08-26 14:17:24.304  5977  5977 I SA      : [DM] Supports Ref Jpn : true
08-26 14:17:24.304  1013  1025 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:24.304  5977  5977 I SA      : [DM] init END
08-26 14:17:24.304  5977  5977 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,08-26 14:17:24.314  1013  1131 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:24.324  5977  5977 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
08-26 14:17:24.324  5977  5977 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-26 14:17:24.324  5977  5977 I SA      : [SLFUCHKMGR] constructor called
,08-26 14:17:24.324  1013  3038 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:24.334  1013  3038 D RCPManagerService: exchangeData() failure , invalid userId
,08-26 14:17:24.334  1013  3040 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-26 14:17:24.334  1013  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.334  1013  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.334  1013  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.334  1013  3040 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.344  5977  5977 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
08-26 14:17:24.344  5977  5977 I SA      : [OR] == isSIMCardReady false ==
,08-26 14:17:24.354  6584  6584 E Zygote  : MountEmulatedStorage()
08-26 14:17:24.354  6584  6584 E Zygote  : v2
08-26 14:17:24.354  6584  6584 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:17:24.354  6584  6584 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:24.354  5977  5977 I SA      : [SCU] == networkStateCheck == false
08-26 14:17:24.354  5977  5977 I SA      : [OR] onReceive END
,08-26 14:17:24.354  6584  6584 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:24.354  6584  6584 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:24.354  6584  6584 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:24.364  1013  3040 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6584 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-26 14:17:24.364  1223  1223 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:24.374  6584  6584 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:24.374  6584  6584 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:24.434  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:24.434  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 14:17:24.434  6584  6584 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 14:17:24.434  6584  6584 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:24.444  1013  1713 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-26 14:17:24.444  1013  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.444  1013  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.444  1013  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.444  1013  1713 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.464  6603  6603 E Zygote  : MountEmulatedStorage()
,08-26 14:17:24.464  6603  6603 E Zygote  : v2
08-26 14:17:24.464  6603  6603 I libpersona: KNOX_SDCARD checking this for 10159
08-26 14:17:24.464  6603  6603 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:24.464  6603  6603 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 14:17:24.464  1013  1713 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6603 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:24.464  1013  1713 I ActivityManager: Killing 5513:com.sec.knox.bridge/1000 (adj 15): empty #31
,08-26 14:17:24.474  6603  6603 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:24.474  6603  6603 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-26 14:17:24.474  1013  1314 I art     : Explicit concurrent mark sweep GC freed 52686(2MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 2.819ms total 176.049ms
,08-26 14:17:24.494  1013  1261 I ActivityManager: Killing 5797:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,08-26 14:17:24.504  6603  6603 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:24.504  6603  6603 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:24.524   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-26 14:17:24.524   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:24.524  6473  6473 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-26 14:17:24.524   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-26 14:17:24.524   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:24.524  6473  6473 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-26 14:17:24.534   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-26 14:17:24.534   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:24.534  6473  6473 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-26 14:17:24.534  1013  1131 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-26 14:17:24.534  1013  1131 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,08-26 14:17:24.544  1013  1131 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:24.544  1013  1131 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:24.544  1013  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:24.554  1013  3193 I ActivityManager: Killing 5727:com.android.mms/u0a46 (adj 15): empty #31
,08-26 14:17:24.554  1013  1314 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:24.554  1013  1314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,08-26 14:17:24.554  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:24.554  1013  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,08-26 14:17:24.554  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:24.574  3835  3835 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-26 14:17:24.574  1013  1350 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-26 14:17:24.574  1013  1350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,08-26 14:17:24.574  3835  4566 I iu.UploadsManager: num queued entries: 0
,08-26 14:17:24.574  3835  4566 I iu.UploadsManager: num updated entries: 0
08-26 14:17:24.574  1013  1350 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:24.574  1013  1350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:24.574  1013  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
08-26 14:17:24.574  3835  4566 I iu.SyncManager: NEXT; no task
,08-26 14:17:24.584  1013  3119 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,08-26 14:17:24.584  1013  3119 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-26 14:17:24.594  1013  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,08-26 14:17:24.594  1013  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,08-26 14:17:24.604   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 14:17:24.604   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:24.604  6562  6624 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 14:17:24.604  1013  1540 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:24.614   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 14:17:24.614   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:24.614  6562  6624 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 14:17:24.614  1013  1350 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:24.624  1013  1540 I AudioService: getStreamVolume 3 index 0
,08-26 14:17:24.624   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-26 14:17:24.624   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:24.624  6562  6627 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-26 14:17:24.624  6473  6473 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-26 14:17:24.634   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-26 14:17:24.634   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:24.634  6562  6627 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-26 14:17:24.634  6473  6473 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-26 14:17:24.644  1013  1314 D CountryDetector: No listener is left
,08-26 14:17:24.654  1013  3193 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 14:17:24.654  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-26 14:17:24.654  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:24.654  1013  3193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:24.654  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:24.664  1013  1350 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 14:17:24.664  1013  1350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,08-26 14:17:24.664  1013  1350 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:24.664  1013  1350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:24.664  1013  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:24.664  1013  1314 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 14:17:24.674  1013  1314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,08-26 14:17:24.674  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:24.674  1013  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:24.674  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:24.674  1013  1541 I ActivityManager: Killing 5907:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,08-26 14:17:24.674  1013  1261 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:24.704  1013  1013 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-26 14:17:24.704  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.704  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.704  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.704  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.714  1013  1013 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6631 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:24.714  6631  6631 E Zygote  : MountEmulatedStorage()
08-26 14:17:24.714  6631  6631 E Zygote  : v2
08-26 14:17:24.714  6631  6631 I libpersona: KNOX_SDCARD checking this for 10002
08-26 14:17:24.714  6631  6631 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:24.714  6631  6631 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:24.724  6631  6631 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:24.724  6631  6631 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:24.734  1013  1350 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
08-26 14:17:24.734  1013  1350 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,08-26 14:17:24.734  1013  1350 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:24.734  1013  1350 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:24.734  1013  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-26 14:17:24.734  6473  6473 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-26 14:17:24.744  1013  3038 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-26 14:17:24.744  1013  3038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-26 14:17:24.744  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:24.744  1013  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:24.744  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:24.744  6631  6631 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:24.744  6631  6631 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:24.764  1013  1040 D Tethering: interfaceRemoved wlan0
08-26 14:17:24.764  1013  1040 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 14:17:24.774  1013  3040 I ActivityManager: Killing 5931:com.wsomacp/u0a25 (adj 15): empty #31
,08-26 14:17:24.784  1013  1314 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-26 14:17:24.784  1013  1314 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 14:17:24.784  1013  1314 D SecContentProvider2: mCursor = null
,08-26 14:17:24.794  1013  1314 D WifiService: setWifiEnabled: true pid=6167, uid=10155
,08-26 14:17:24.794  1013  1314 W ActivityManager: Permission Denial: getCurrentUser() from pid=6167, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-26 14:17:24.794  1013  1314 W WifiService: Failed getting userId using ActivityManagerNative
08-26 14:17:24.794  1013  1314 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6167, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:24.794  1013  1314 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-26 14:17:24.794  1013  1314 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 14:17:24.794  1013  1314 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 14:17:24.794  1013  1314 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 14:17:24.794  1013  1314 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-26 14:17:24.794  1013  1314 D SettingsProvider: name = wifi_on
,08-26 14:17:24.794  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:24.794  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:24.794  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:24.794  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 14:17:24.804  1013  3193 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-26 14:17:24.814  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.814  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.814  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.814  1013  3193 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.824  6664  6664 E Zygote  : MountEmulatedStorage()
08-26 14:17:24.824  6664  6664 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:17:24.824  6664  6664 E Zygote  : v2
08-26 14:17:24.824  6664  6664 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:24.824  6664  6664 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:24.824  6664  6664 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:24.824  6664  6664 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:24.824  1013  3193 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6664 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-26 14:17:24.824  6562  6562 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-26 14:17:24.844  6664  6664 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:24.844  6664  6664 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:24.844  6562  6562 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8551-8553)
08-26 14:17:24.844  6562  6562 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 14:17:24.854  6562  6562 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2f5c2a03}
,08-26 14:17:24.854  6562  6562 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-26 14:17:24.854  6562  6562 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-26 14:17:24.864  1013  1040 D Tethering: interfaceRemoved p2p0
08-26 14:17:24.864  1013  1040 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 14:17:24.874  6562  6562 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-26 14:17:24.874  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-26 14:17:24.874  6562  6562 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-26 14:17:24.884  6664  6664 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,08-26 14:17:24.894  6562  6562 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-26 14:17:24.894  6562  6562 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,08-26 14:17:24.894  6562  6562 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-26 14:17:24.904  6562  6562 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-26 14:17:24.904  6562  6562 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-26 14:17:24.904  6562  6562 I Adreno-EGL: Build Date: 04/06/15 Mon
08-26 14:17:24.904  6562  6562 I Adreno-EGL: Local Branch: 
08-26 14:17:24.904  6562  6562 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-26 14:17:24.904  6562  6562 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-26 14:17:24.904  6562  6562 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-26 14:17:24.954  6562  6691 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-26 14:17:24.964  6562  6562 I NSApplication: Starting up...
,08-26 14:17:24.974  1013  1345 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,08-26 14:17:24.974  1013  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.974  1013  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:24.974  1013  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.974  1013  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:24.994  6696  6696 E Zygote  : MountEmulatedStorage()
08-26 14:17:24.994  6696  6696 E Zygote  : v2
08-26 14:17:24.994  6696  6696 I libpersona: KNOX_SDCARD checking this for 10120
08-26 14:17:24.994  6696  6696 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:24.994  6696  6696 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 14:17:24.994  1013  1345 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6696 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-26 14:17:24.994  1013  1345 I ActivityManager: Killing 5955:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
08-26 14:17:24.994  1013  1345 I ActivityManager: Killing 5807:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #32
,08-26 14:17:25.004  6696  6696 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:25.004  6696  6696 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 14:17:25.004  6664  6664 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,08-26 14:17:25.014  6664  6664 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,08-26 14:17:25.014   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,08-26 14:17:25.014  6664  6664 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:25.014  6696  6696 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:25.024  6696  6696 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:25.024  6664  6664 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
08-26 14:17:25.024  6664  6664 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,08-26 14:17:25.024  6664  6664 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,08-26 14:17:25.024  1013  3193 I ActivityManager: Killing 5829:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,08-26 14:17:25.044  6696  6696 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 14:17:25.354  1013  1131 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-26 14:17:25.354  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:25.354  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:25.354  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:25.354  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:25.364  6717  6717 E Zygote  : MountEmulatedStorage(),
08-26 14:17:25.364  6717  6717 E Zygote  : v2
08-26 14:17:25.364  6717  6717 I libpersona: KNOX_SDCARD checking this for 10125,
08-26 14:17:25.374  1013  1131 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6717 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
08-26 14:17:25.374  6717  6717 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:25.374  1013  1131 I ActivityManager: Killing 6016:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
08-26 14:17:25.374  6717  6717 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:25.374  6717  6717 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:25.374  6717  6717 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:25.394  6717  6717 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:25.394  6717  6717 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:25.404  6717  6717 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 14:17:25.404  6717  6717 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 14:17:25.404  6717  6717 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:25.414  6717  6717 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:25.424  6717  6717 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-26 14:17:25.424  6717  6717 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-26 14:17:25.424  1013  1314 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,08-26 14:17:25.424  1013  1314 I ActivityManager: Killing 5711:com.samsung.android.sm/1000 (adj 15): empty #31
,08-26 14:17:25.434  1013  1540 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:25.434  1013  1540 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:25.434  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.434  1013  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:25.434  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:25.434  3651  3651 I Hs20UtilService: Starting #9
,08-26 14:17:25.434  3651  3690 I Hs20UtilService: Message received 5007
,08-26 14:17:25.434  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 14:17:25.434  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 14:17:25.434  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:25.434  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 14:17:25.444  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:25.444  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:25.444  1323  3080 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:25.444  1013  1539 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:25.444  1013  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:25.444  1013  1539 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:25.444  1013  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:25.444  1013  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:25.454  3651  3651 I Hs20UtilService: Starting #10
08-26 14:17:25.454  3651  3690 I Hs20UtilService: Message received 5011
,08-26 14:17:25.454  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:25.454  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:25.454  6584  6584 D SecurityLogAgent: StateMachine : Current State = 1
08-26 14:17:25.454  6584  6584 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:25.464  1013  3193 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:25.464  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:25.474  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:25.474  1013  3193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:25.474  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:25.474  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:25.474  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:25.474  3651  3651 I Hs20UtilService: Starting #11,
08-26 14:17:25.474  6584  6584 D SecurityLogAgent: StateMachine : Current State = 1
08-26 14:17:25.474  6584  6584 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 14:17:25.474  3651  3690 I Hs20UtilService: Message received 5011
,08-26 14:17:25.624  1013  1121 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 14:17:25.624  1013  1121 E WifiHW  : ##################### set firmware type 0 #####################
,08-26 14:17:25.994  1013  1040 D Tethering: interfaceAdded wlan0
,08-26 14:17:25.994  1013  1126 E Tethering: No numeric data
,08-26 14:17:26.004  1013  1126 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
08-26 14:17:26.004  1013  1126 D Tethering: clearTetheredNotification()
,08-26 14:17:26.004  1013  1118 V NetworkStats: performPollLocked(flags=0x1),
08-26 14:17:26.004  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:26.004  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 14:17:26.004  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:26.014  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:26.014  1175  1175 D HotspotTile: updateTetherState():false, false
,08-26 14:17:26.014  1013  1118 V NetworkStats: performPollLocked() took 9ms
,08-26 14:17:26.014  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:26.014  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:26.014  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:26.014  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:26.014  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:26.014  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 14:17:26.014  1013  1126 D Tethering: InitialState.processMessage what=4
,08-26 14:17:26.024  1013  1126 E Tethering: No numeric data
08-26 14:17:26.024  1013  1126 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 14:17:26.024  1013  1126 D Tethering: clearTetheredNotification()
,08-26 14:17:26.024  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:26.024  1013  1118 V NetworkStats: performPollLocked(flags=0x1)
,08-26 14:17:26.024  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:26.024  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:26.024  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:26.034  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:26.034  1175  1175 D HotspotTile: updateTetherState():false, false
,08-26 14:17:26.034  1013  1040 D Tethering: interfaceStatusChanged p2p0, false,
,08-26 14:17:26.034  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 14:17:26.034  1013  1040 D Tethering: interfaceAdded p2p0
08-26 14:17:26.034  1013  1040 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 14:17:26.034   276  1012 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-26 14:17:26.034   276  1012 D SoftapController: Softap fwReload - Ok
,08-26 14:17:26.034  1013  1118 V NetworkStats: performPollLocked() took 14ms,
08-26 14:17:26.044  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:26.044   276  1012 D CommandListener: Setting iface cfg,
08-26 14:17:26.044   276  1012 D CommandListener: Trying to bring down wlan0
,08-26 14:17:26.044   276  1012 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:26.044  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:26.044  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:26.044  1013  1121 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 14:17:26.054  1013  1121 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-26 14:17:26.054  1013  1121 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": Permission denied
,08-26 14:17:26.054  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:26.054  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 14:17:26.054  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:26.054  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:26.054  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:26.054  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:26.064  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:26.064  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 14:17:26.064  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-26 14:17:26.064  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:26.064  1175  1175 D HotspotTile: onReceive : 2, 0
,08-26 14:17:26.064  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:26.074  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:26.074  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:26.074  1013  1261 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings,
08-26 14:17:26.074  1013  1261 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:26.074  1013  1261 W ActivityManager: userId = 0, bbcId = -10000,
08-26 14:17:26.074  1013  1261 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:26.074  1013  1261 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:26.084  3651  3651 I Hs20UtilService: Starting #12
08-26 14:17:26.084  3651  3690 I Hs20UtilService: Message received 5011
,08-26 14:17:26.084  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:26.084  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:26.084  6584  6584 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 14:17:26.084  6584  6584 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:26.114  6739  6739 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-26 14:17:26.114  6739  6739 I wpa_supplicant: Successfully initialized wpa_supplicant
08-26 14:17:26.114  6739  6739 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-26 14:17:26.124  6739  6739 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-26 14:17:26.124   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6739,
08-26 14:17:26.124   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
08-26 14:17:26.124  6739  6739 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 14:17:26.124  6739  6739 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:26.124  6739  6739 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
08-26 14:17:26.124  6739  6739 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 14:17:26.124   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6739
08-26 14:17:26.124   395   395 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,08-26 14:17:26.284   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,08-26 14:17:26.294  6739  6739 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,08-26 14:17:26.354  6739  6739 I wpa_supplicant: Ctrl_iface: loading cred from phone
08-26 14:17:26.364  6739  6739 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 14:17:26.374  6739  6739 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 14:17:26.374   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6739
08-26 14:17:26.374   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 14:17:26.374  6739  6739 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-26 14:17:26.374  6739  6739 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:26.374  6739  6739 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:26.374  6739  6739 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:26.374  6739  6739 E wpa_supplicant: SIM READ ERROR
08-26 14:17:26.374  6739  6739 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:26.374  6739  6739 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:26.374  6739  6739 E wpa_supplicant: SIM READ ERROR
08-26 14:17:26.374  6739  6739 I wpa_supplicant: Blacklist: Clear (all) 
08-26 14:17:26.374  6739  6739 I wpa_supplicant: wpa_default_ap_write_once
08-26 14:17:26.374  6739  6739 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 14:17:26.374  6739  6739 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:26.374  6739  6739 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 14:17:26.374  6739  6739 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:26.374  6739  6739 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:26.374  6739  6739 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-26 14:17:26.374  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
08-26 14:17:26.374  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:26.374  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:26.414  6739  6739 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 14:17:26.614  6739  6739 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,08-26 14:17:26.614  6739  6739 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,08-26 14:17:26.624  6739  6739 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,08-26 14:17:26.634   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6739
08-26 14:17:26.634   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-26 14:17:26.634  6739  6739 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
08-26 14:17:26.634  6739  6739 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:26.634  6739  6739 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-26 14:17:26.634  6739  6739 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,08-26 14:17:26.644  6739  6739 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
08-26 14:17:26.644   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6739,
08-26 14:17:26.644   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-26 14:17:26.644  6739  6739 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
08-26 14:17:26.644  6739  6739 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:26.644  6739  6739 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:26.644  6739  6739 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:26.644  6739  6739 E wpa_supplicant: SIM READ ERROR
08-26 14:17:26.644  6739  6739 I wpa_supplicant: wpa_default_ap_write_once,
08-26 14:17:26.644  6739  6739 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 14:17:26.644  6739  6739 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,08-26 14:17:26.654  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:26.654  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:26.654  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:26.654  1013  1040 D Tethering: interfaceStatusChanged p2p0, false,
08-26 14:17:26.654  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:26.654  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:26.694  6739  6739 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 14:17:26.694  6739  6739 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 14:17:26.754  6739  6739 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
08-26 14:17:26.754  6739  6739 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 14:17:26.754  6739  6739 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 14:17:27.014  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 14:17:27.014  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:27.014  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:27.024   286   286 E SMD     : DCD OFF,
,08-26 14:17:27.054  1013  1121 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 14:17:27.064  1013  1121 D WifiNative-wlan0: callSECApiBoolean - ID [21],
08-26 14:17:27.064  6739  6739 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 14:17:27.064  6739  6739 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:27.064  6739  6739 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:27.064  6739  6739 E wpa_supplicant: SIM READ ERROR
08-26 14:17:27.064  6739  6739 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 14:17:27.094  6739  6739 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,08-26 14:17:27.104  1013  1121 D WifiNative-wlan0: callSECApiInt - ID [210]
08-26 14:17:27.104  6739  6739 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 14:17:27.104  1013  1121 D WifiConfigStore: Loading config and enabling all networks 
,08-26 14:17:27.114  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:27.114  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:27.114  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:27.114  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:27.114  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:27.114  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:27.114  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:27.114  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-26 14:17:27.114  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,08-26 14:17:27.124  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:27.124  1175  1175 D HotspotTile: onReceive : 3, 0
,08-26 14:17:27.124  1013  1121 E WifiConfigStore: Not a HS20
,08-26 14:17:27.124  1013  1121 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-26 14:17:27.134  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:27.134  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:27.134  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.134  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:27.134  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:27.134  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:27.134  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.134  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:27.144  1013  1121 D WifiNative-wlan0: callSECApiInt - ID [65]
08-26 14:17:27.144  1013  3040 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:27.144  1013  3040 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:27.144  1013  1121 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 14:17:27.144  6739  6739 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 14:17:27.144  6739  6739 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-26 14:17:27.144  6739  6739 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 14:17:27.144  6739  6739 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 14:17:27.144  6739  6739 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 14:17:27.144  6739  6739 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 14:17:27.144  6739  6739 I wpa_supplicant: First Scan Start
08-26 14:17:27.144  6739  6739 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-26 14:17:27.144  1013  3040 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:27.144  1013  3040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:27.144  1013  3040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:27.144  1013  1121 D WifiNative-wlan0: Setting external_sim to 1
08-26 14:17:27.144  6429  6429 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:27.144  1013  1121 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 14:17:27.144  1013  1121 I WifiNative-HAL: startHal
08-26 14:17:27.144  1013  1121 E wifi    : getStaticLongField sWifiHalHandle 0x9c48688c
08-26 14:17:27.144  1013  1121 I WifiNative-HAL: Could not start hal
08-26 14:17:27.154  3651  3651 I Hs20UtilService: Starting #13
08-26 14:17:27.154  3651  3690 I Hs20UtilService: Message received 5011
08-26 14:17:27.154  1013  1121 E WifiNative-wlan0: do suspend true
08-26 14:17:27.154  1013  1120 D WifiP2pService: P2pDisabledState{ what=131203 }
08-26 14:17:27.154   276  1012 D CommandListener: Setting iface cfg
08-26 14:17:27.154   276  1012 D CommandListener: Trying to bring up p2p0
08-26 14:17:27.154  1013  1120 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-26 14:17:27.154  1013  1120 D WifiP2pService: P2pEnablingState
08-26 14:17:27.154  1013  1120 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 14:17:27.164  1013  1120 D WifiP2pService: P2p socket connection successful
08-26 14:17:27.164  1013  1120 D WifiP2pService: P2pEnabledState
08-26 14:17:27.164  1013  1121 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-26 14:17:27.164  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 14:17:27.164  1013  1146 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.164  1013  1146 I WifiNative-HAL: startHal
08-26 14:17:27.164  1013  1146 E wifi    : getStaticLongField sWifiHalHandle 0x9d6389bc
08-26 14:17:27.164  1013  1146 I WifiNative-HAL: Could not start hal
08-26 14:17:27.164  1013  1146 E WifiScanningService: could not start HAL
08-26 14:17:27.164  1013  1013 D RttService: SCAN_AVAILABLE : 3
08-26 14:17:27.164  1013  1147 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.164  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 14:17:27.164  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:27.164  6584  6584 D SecurityLogAgent: StateMachine : Current State = 1
08-26 14:17:27.164  6584  6584 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-26 14:17:27.164  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 14:17:27.164  1013  1120 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 14:17:27.164  1013  1121 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 14:17:27.164  1013  1121 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 14:17:27.164  1013  1121 E WifiNative-wlan0: invaild command id : 215
08-26 14:17:27.164  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 14:17:27.164  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:27.164  1013  1043 D WifiDisplayController: disconnect
08-26 14:17:27.164  1013  1043 D WifiDisplayController: updateConnection
08-26 14:17:27.164  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:27.164  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 14:17:27.164  1013  1123 E ConnectivityService: updateNetworkInfo()
08-26 14:17:27.174  6739  6739 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 14:17:27.174  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 14:17:27.174  6739  6739 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 14:17:27.174  1013  1261 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 14:17:27.174  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 14:17:27.174  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:27.174  6739  6739 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-26 14:17:27.174  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
08-26 14:17:27.174  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 14:17:27.174  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 14:17:27.174  1013  1121 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 14:17:27.174  1013  1121 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 14:17:27.174  1013  1121 E WifiNative-wlan0: invaild command id : 215
08-26 14:17:27.184  1013  1121 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:27.184  1013  1121 D SecContentProvider2: mCursor = null
08-26 14:17:27.184  1013  1120 D WifiNative-p2p0: p2pGetDeviceAddress
08-26 14:17:27.184  1013  1120 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
08-26 14:17:27.184  1013  1120 D WifiP2pService: DeviceAddress: 7e:96:ac
08-26 14:17:27.184  1013  1043 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  secondary type: null
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  wps: 0
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  grpcapab: 0
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  devcapab: 0
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  status: 3
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  wfdInfo: null
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  groupownerAddress: null
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  GOdeviceName: null
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  interfaceAddress: 
08-26 14:17:27.184  1013  1043 D WifiDisplayController:  SConnectInfo : null
08-26 14:17:27.184  1013  1121 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:27.184  1013  1121 D SecContentProvider2: mCursor = null
08-26 14:17:27.184  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 14:17:27.184  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 14:17:27.184  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 14:17:27.194  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 14:17:27.194  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:27.194  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:27.194  1323  3080 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-26 14:17:27.194  6384  6384 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-26 14:17:27.194  6384  6384 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 14:17:27.194  6384  6384 D FileShare-Client: Outbound.stopDelayTimer - 
08-26 14:17:27.204  1013  1120 D WifiP2pService: sending p2p persistent groups changed broadcast
08-26 14:17:27.204  6414  6414 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
08-26 14:17:27.204  1013  1120 D WifiP2pService: InactiveState
08-26 14:17:27.204  1013  1120 D WifiP2pService: InactiveState{ what=143376 }
08-26 14:17:27.204  1013  1120 D WifiP2pService: P2pEnabledState{ what=143376 }
08-26 14:17:27.204  6739  6739 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 14:17:27.204  1013  1120 D WifiP2pService: InactiveState{ what=143376 }
08-26 14:17:27.204  1013  1120 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 14:17:27.744  1013  1314 I ActivityManager: Killing 6044:com.samsung.helphub/1000 (adj 15): empty #31
,08-26 14:17:27.804  1013  1261 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 14:17:27.804  1013  1261 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-26 14:17:27.804  1013  1261 D SecContentProvider2: mCursor = null
,08-26 14:17:27.804  1013  1261 D WifiService: setWifiEnabled: false pid=6167, uid=10155
,08-26 14:17:27.804  1013  1261 D SettingsProvider: name = wifi_on
,08-26 14:17:27.834  1013  1120 D WifiP2pService: InactiveState{ what=131204 }
,08-26 14:17:27.834  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 1,
08-26 14:17:27.834  1013  1120 D WifiP2pService: P2pEnabledState{ what=131204 }
08-26 14:17:27.834  1013  1146 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.834  1013  1120 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-26 14:17:27.834  1013  1013 D RttService: SCAN_AVAILABLE : 1
08-26 14:17:27.834  1013  1123 E ConnectivityService: updateNetworkInfo()
08-26 14:17:27.834  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:27.834  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
08-26 14:17:27.834  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 14:17:27.834  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-26 14:17:27.844  1013  1147 D RttService: EnabledState got{ when=-8ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:27.844  1013  1123 E ConnectivityService: updateNetworkInfo()
08-26 14:17:27.844  1013  1120 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-26 14:17:27.844  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 14:17:27.844  1013  1120 D WifiP2pService: P2pDisablingState
08-26 14:17:27.844  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-26 14:17:27.844  1013  1120 D WifiP2pService: P2pDisablingState{ what=147458 }
08-26 14:17:27.844  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-26 14:17:27.844  1013  1120 D WifiP2pService: p2p socket connection lost
08-26 14:17:27.844  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 14:17:27.844  1013  1120 D WifiP2pService: P2pDisabledState
08-26 14:17:27.844  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:27.844  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:27.854  1323  3080 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:27.854  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-26 14:17:27.854  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-26 14:17:27.854  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:27.854  1013  1043 D WifiDisplayController: disconnect
08-26 14:17:27.854  1013  1043 D WifiDisplayController: updateConnection
08-26 14:17:27.854  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:27.854  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:27.854   276  1012 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:27.864  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false],
08-26 14:17:27.864  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
,08-26 14:17:27.864  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
,08-26 14:17:27.864  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null,
08-26 14:17:27.864  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED,
08-26 14:17:27.874  1013  3040 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 14:17:27.874  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 14:17:27.874  6384  6384 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:27.874  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-26 14:17:27.874  6384  6384 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 14:17:27.874  6384  6384 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 14:17:27.874  6739  6739 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,08-26 14:17:27.884  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:27.884  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:27.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:27.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:27.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:27.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:27.884  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:27.884  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 14:17:27.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:27.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:27.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:27.884  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:27.884  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
08-26 14:17:27.884  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 14:17:27.884  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-26 14:17:27.884  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:27.884  1175  1175 D HotspotTile: onReceive : 0, 0
,08-26 14:17:27.894  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:27.894  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:27.894  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.894  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:27.894  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:27.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-26 14:17:27.894  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-26 14:17:27.894  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:27.894  6414  6414 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:27.904  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 14:17:27.904  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 14:17:27.904  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:27.904  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 14:17:27.904  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-26 14:17:27.904  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:27.904  1323  3080 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:27.914  6384  6384 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:27.914  6384  6384 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,08-26 14:17:27.914  6384  6384 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 14:17:27.914  6414  6414 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:27.924  1013  1261 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:27.924  1013  1261 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:27.924  1013  1261 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:27.924  1013  1261 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:27.924  1013  1261 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:27.934  3651  3651 I Hs20UtilService: Starting #14
,08-26 14:17:27.934  3651  3690 I Hs20UtilService: Message received 5007
,08-26 14:17:27.934  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 14:17:27.934  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 14:17:27.934  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:27.934  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-26 14:17:27.934  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:27.934  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-26 14:17:27.944  1323  3080 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:27.944  1013  3042 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:27.944  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:27.944  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:27.944  1013  3042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:27.944  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:27.954  3651  3651 I Hs20UtilService: Starting #15
,08-26 14:17:27.954  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 14:17:27.954  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:27.954  6584  6584 D SecurityLogAgent: StateMachine : Current State = 1
08-26 14:17:27.954  6584  6584 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:27.964  3651  3690 I Hs20UtilService: Message received 5011
,08-26 14:17:28.004  6739  6739 I wpa_supplicant: Blacklist: Clear (all) ,
,08-26 14:17:28.094  6739  6739 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING ,
08-26 14:17:28.104  6739  6739 I wpa_supplicant: wlan0: State: SCANNING -> DISCONNECTED
,08-26 14:17:28.104  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:28.104  6739  6739 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
08-26 14:17:28.104  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:28.104  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:28.364  6739  6739 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 14:17:28.444  6739  6739 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
,08-26 14:17:28.454  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 14:17:28.454  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:28.454  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:28.564  1013  1121 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-26 14:17:28.564  1013  1121 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 14:17:28.564  1013  1121 E WifiConfigStore: setLastSelectedConfiguration -1
,08-26 14:17:28.564  6429  6429 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
,08-26 14:17:28.564  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:28.564  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-26 14:17:28.564  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:28.564  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:28.564  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:28.564  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:28.564  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:28.564  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,08-26 14:17:28.564  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-26 14:17:28.564  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:28.574  1175  1175 D HotspotTile: onReceive : 1, 0
,08-26 14:17:28.574  1905  2129 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-26 14:17:28.574  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:28.574  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:28.584  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,08-26 14:17:28.584  1013  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:28.584  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:28.584  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:28.584  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:28.584  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:28.594  3651  3651 I Hs20UtilService: Starting #16
,08-26 14:17:28.594  3651  3690 I Hs20UtilService: Message received 5011
,08-26 14:17:28.594  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:28.594  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-26 14:17:28.594  6584  6584 D SecurityLogAgent: StateMachine : Current State = 1
,08-26 14:17:28.594  6584  6584 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:29.244  1013  1040 D Tethering: interfaceRemoved wlan0
08-26 14:17:29.244  1013  1040 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,08-26 14:17:29.484  1013  1040 D Tethering: interfaceRemoved p2p0
,08-26 14:17:29.484  1013  1040 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,08-26 14:17:29.604  1013  1038 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:29.604  1013  1038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:29.604  1013  1038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:29.614  1013  1541 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
08-26 14:17:29.614  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,08-26 14:17:29.614  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:29.614  1013  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:29.614  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,08-26 14:17:29.624  6562  6625 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-26 14:17:29.624  1013  1026 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-26 14:17:29.624  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,08-26 14:17:29.624  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:29.624  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:29.624  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:29.644  1013  1713 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:29.644  1013  1713 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:29.644  1013  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:29.654  1013  3042 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 14:17:29.654  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,08-26 14:17:29.654  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:29.654  1013  3042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:29.654  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:29.654  1013  1539 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 14:17:29.654  1013  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,08-26 14:17:29.654  1013  1539 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:29.654  1013  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:29.654  1013  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:29.664  1013  3193 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-26 14:17:29.664  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-26 14:17:29.664  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:29.664  1013  3193 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:29.664  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:29.674  1013  1314 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-26 14:17:29.674  1013  1314 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,08-26 14:17:29.674  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:29.674  1013  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:29.674  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:29.704  1013  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:29.704  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:29.704  1013  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:29.704  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,08-26 14:17:29.714  1905  1905 D WearableService: callingUid 10012, callindPid: 1905
,08-26 14:17:29.724  1013  3042 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
08-26 14:17:29.724  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,08-26 14:17:29.724  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:29.724  1013  3042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:29.724  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,08-26 14:17:29.744  6473  6753 I MusicLeanback: Conditions not met for autocaching.
,08-26 14:17:29.744  6473  6753 I MusicLeanback: Stop autocaching.
,08-26 14:17:29.774  6473  6473 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-26 14:17:29.774  6473  6758 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-26 14:17:30.024   286   286 E SMD     : DCD OFF
,08-26 14:17:30.214  1013  1121 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-26 14:17:30.834  6167  6220 D BluetoothAdapter: enable()
,08-26 14:17:30.834  1013  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6167, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-26 14:17:30.834  1013  1026 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 14:17:30.834  1013  1026 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6167, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:30.834  1013  1026 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-26 14:17:30.834  1013  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-26 14:17:30.834  1013  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-26 14:17:30.834  1013  1026 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-26 14:17:30.834  1013  1026 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 14:17:30.834  1013  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:30.834  1013  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:30.834  1013  1026 D SettingsProvider: name = bluetooth_on,
,08-26 14:17:30.844  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-26 14:17:30.844  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:30.844  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-26 14:17:30.844  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2,
,08-26 14:17:30.884  6358  6358 D BluetoothAdapterState: make
,08-26 14:17:30.884  6358  6358 I bluedroid: init
,08-26 14:17:30.894  6358  6760 I BluetoothAdapterState: Entering OffState
,08-26 14:17:30.894  6358  6358 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 14:17:30.894  6358  6358 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-26 14:17:30.894  6358  6358 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,08-26 14:17:30.894  6358  6358 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 14:17:30.904  6358  6358 E bt-btif : btif_fetch_local_ble_random_bdaddr
,08-26 14:17:30.904  6358  6358 I bluedroid: get_profile_interface socket
08-26 14:17:30.904  6358  6358 I bluedroid: get_profile_interface map_client
,08-26 14:17:30.904  6358  6763 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 14:17:30.904  6358  6358 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 14:17:30.904  6358  6763 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-26 14:17:30.904  6358  6763 E BluetoothServiceJni: populateRssiValuesNative
,08-26 14:17:30.904  6358  6763 I bluedroid: getModelRssiValues
,08-26 14:17:30.904  6358  6763 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 14:17:30.904  6358  6763 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 14:17:30.914  6358  6358 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:30.914  6358  6763 D BluetoothAdapterProperties: Name is: A5-1
,08-26 14:17:30.914  1013  3038 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 14:17:30.914  1013  1013 D SettingsProvider: name = bluetooth_name
08-26 14:17:30.914  1013  3038 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.914  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:30.914  1013  3038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.914  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.914  6358  6372 I bluedroid: config_hci_snoop_log
,08-26 14:17:30.914  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-26 14:17:30.924  1013  1042 D BluetoothManagerService: Ble is always on enable gatt
,08-26 14:17:30.924  1013  1042 I BluetoothManagerService: enableGattForLeMode, doBind called
,08-26 14:17:30.924  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 14:17:30.924  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 14:17:30.924  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:30.924  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:30.934  6358  6358 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-26 14:17:30.934  1013  1042 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 14:17:30.944  6358  6760 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-26 14:17:30.944  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 14:17:30.944  6358  6760 D BluetoothAdapterProperties: Setting state to 11
08-26 14:17:30.944  6358  6760 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 14:17:30.944  6358  6760 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:30.944  6358  6760 D BluetoothAdapterService: updateAdapterState state is 11
08-26 14:17:30.944  6358  6760 D BluetoothAdapterService: Autoconnection is available 
,08-26 14:17:30.944  6358  6760 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 14:17:30.944  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:30.944  1013  1013 I InputMethodManagerService: [BT Setting State] State =11
,08-26 14:17:30.954  6358  6760 D BluetoothSecureManager: getInstant: null
08-26 14:17:30.954  6358  6760 D BluetoothSecureManager: calling getMethod for getService
08-26 14:17:30.954  6358  6760 D BluetoothSecureManager: calling getService
08-26 14:17:30.954  6358  6760 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@5eb14b5
,08-26 14:17:30.954  1013  1025 D BluetoothSecureManagerService: isSecureModeEnabled
08-26 14:17:30.954  1013  1025 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-26 14:17:30.954  6358  6760 D BtConfig.SecureMode: isSecureModeOn:false
08-26 14:17:30.954  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 14:17:30.954  6358  6760 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 14:17:30.954  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 14:17:30.954  6358  6760 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 14:17:30.954  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 14:17:30.954  6358  6760 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 14:17:30.954  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 14:17:30.954  6358  6760 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 14:17:30.954  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 14:17:30.954  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 14:17:30.964  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:30.964  1175  1175 D BluetoothTile:  getBluetoothState : 11
08-26 14:17:30.964  6358  6760 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 14:17:30.964  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 14:17:30.964  6358  6760 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 14:17:30.964  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:30.964  1896  1896 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
08-26 14:17:30.964  6358  6760 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 14:17:30.964  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 14:17:30.964  6358  6760 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 14:17:30.964  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:30.964  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
08-26 14:17:30.964  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 14:17:30.964  6358  6760 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:30.964  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-26 14:17:30.964  6358  6760 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:30.964  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 14:17:30.964  6358  6760 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:30.964  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 14:17:30.964  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:30.964  1013  1541 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 14:17:30.964  6358  6760 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 14:17:30.964  6358  6760 D BluetoothBondStateMachine: make
,08-26 14:17:30.964  1013  1713 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 14:17:30.964  1013  1345 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:30.964  1013  1345 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.964  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 14:17:30.964  1013  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:30.974  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:30.974  1013  1345 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:30.974  1013  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:30.974  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 14:17:30.974  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 14:17:30.974  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 14:17:30.974  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:30.974  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:30.974  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.974  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:30.974  6358  6764 I BluetoothBondStateMachine: StableState(): Entering Off State
08-26 14:17:30.974  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.974  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.974  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 14:17:30.974  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 14:17:30.974  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-26 14:17:30.974  6358  6358 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 14:17:30.974  6358  6358 D BtGatt.GattService: Received start request. Starting profile...
08-26 14:17:30.974  6358  6358 D BtGatt.GattService: start()
08-26 14:17:30.974  6358  6358 D BtGatt.GattService: start()
08-26 14:17:30.974  6358  6358 I bluedroid: get_profile_interface gatt
,08-26 14:17:30.984  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
08-26 14:17:30.984  6358  6358 D BtGatt.AdvertiseManager: advertise manager created
,08-26 14:17:30.984  1013  1314 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:30.984  1013  1314 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 14:17:30.984  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
08-26 14:17:30.984  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:30.984  1013  1314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:30.984  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:30.984  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:30.984  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 14:17:30.984  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:30.994  6358  6358 D BtGatt.GattService: mStartError = false
08-26 14:17:30.994  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
,08-26 14:17:30.994  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:30.994  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 14:17:30.994  6358  6358 D HeadsetService: Received start request. Starting profile...
,08-26 14:17:30.994  6358  6358 D HeadsetService: start()
,08-26 14:17:31.004  6358  6358 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 14:17:31.004  6358  6358 D HeadsetStateMachine: make
,08-26 14:17:31.004  6358  6358 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 14:17:31.014  1013  3038 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:31.014  1013  3038 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.014  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.014  1013  3038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:31.014  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.014  1013  1350 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
08-26 14:17:31.014  1013  1350 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.014  1013  1350 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.014  1013  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.014  1013  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
08-26 14:17:31.014  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 14:17:31.014  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:31.014  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 14:17:31.024  1013  3042 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:31.024  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.024  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.024  1013  3042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:31.024  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.024  1013  1541 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,08-26 14:17:31.024  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.024  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.024  1013  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.024  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 14:17:31.024  6358  6358 I bluedroid: get_profile_interface handsfree
08-26 14:17:31.024  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-26 14:17:31.024  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 14:17:31.024  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 14:17:31.034  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:31.034  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.034  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.034  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:31.034  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.034  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 14:17:31.034  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 14:17:31.034  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 14:17:31.034  1013  1350 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:31.034  1013  1350 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.044  1013  1350 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.044  1013  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.044  1013  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.044  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:31.044  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:31.044  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:31.044  1013  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:31.044  1013  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.054  1013  1539 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.054  1013  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:31.054  6358  6358 I DualScoManager: Instantiating Dual Sco Manager
08-26 14:17:31.054  6358  6358 I DualScoManager: Set HeadsetServiceHelper
,08-26 14:17:31.054  1013  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.054  6358  6358 D BluetoothAtMessage: createCMTIContentObservers
,08-26 14:17:31.054  1013  1131 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 14:17:31.054  1013  1131 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:31.054  1013  1131 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:31.054  1013  1131 D SettingsProvider: selectionArgs: false
08-26 14:17:31.054  1013  1131 D SettingsProvider: selectionArgs: 1002
08-26 14:17:31.054  1013  1131 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:31.054  1013  1131 D SettingsProvider: ret = -1
,08-26 14:17:31.054  6358  6768 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 14:17:31.054  6358  6358 D HeadsetService: mStartError = false
08-26 14:17:31.054  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
,08-26 14:17:31.054  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-26 14:17:31.054  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:31.054  6358  6760 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-26 14:17:31.054  1013  3119 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:31.054  1013  3119 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.064  1013  3119 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.064  1013  3119 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.064  1013  3119 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.064  6358  6768 D HeadsetStateMachine: Clear mHeadsetBrsf
,08-26 14:17:31.064  6358  6768 D HeadsetStateMachine: map size, before remove : 0
,08-26 14:17:31.064  6358  6768 D HeadsetStateMachine: map size, after remove: 0
,08-26 14:17:31.064  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:31.064  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:31.064  6358  6760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 14:17:31.064  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:31.064  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:31.064  6358  6760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-26 14:17:31.064  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 14:17:31.064  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-26 14:17:31.064  6358  6760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 14:17:31.064  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 14:17:31.064  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 14:17:31.064  6358  6760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 14:17:31.064  6358  6760 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 14:17:31.064  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 14:17:31.074  6358  6358 D A2dpService: Received start request. Starting profile...
08-26 14:17:31.074  6358  6358 D A2dpService: start()
,08-26 14:17:31.074  6358  6358 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 14:17:31.074  6358  6358 I bluedroid: get_profile_interface avrcp
,08-26 14:17:31.084  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:31.084  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:31.084  6358  6358 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController,
,08-26 14:17:31.104  6358  6358 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 14:17:31.104  6358  6772 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 14:17:31.104  6358  6358 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-26 14:17:31.104  6358  6358 D A2dpStateMachine: make
,08-26 14:17:31.104  6358  6358 I bluedroid: get_profile_interface a2dp
,08-26 14:17:31.104  6358  6774 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 14:17:31.104  6358  6358 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 14:17:31.114  6358  6358 D A2dpService: mStartError = false
08-26 14:17:31.114  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
08-26 14:17:31.114  6358  6773 D A2dpStateMachine: Enter Disconnected: -2
,08-26 14:17:31.114  6358  6358 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 14:17:31.114  1431  1439 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 14:17:31.114  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
08-26 14:17:31.114  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 14:17:31.114  1431  1439 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 14:17:31.114  6358  6358 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 14:17:31.114  6358  6358 D HidService: Received start request. Starting profile...
08-26 14:17:31.114  6358  6358 D HidService: start()
08-26 14:17:31.114  6358  6358 I bluedroid: get_profile_interface hidhost
08-26 14:17:31.114  6358  6358 D HidService: setHidService(): set to: null
08-26 14:17:31.114  6358  6358 D HidService: mStartError = false
08-26 14:17:31.114  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
,08-26 14:17:31.114  6358  6358 D HeadsetStateMachine: Proxy object connected
,08-26 14:17:31.114  6358  6358 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 14:17:31.124  6358  6358 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 14:17:31.124  6358  6768 D HeadsetStateMachine: Disconnected process message: 11
,08-26 14:17:31.124  6358  6358 D HealthService: Received start request. Starting profile...
08-26 14:17:31.124  6358  6358 D HealthService: start()
,08-26 14:17:31.124  6358  6358 I bluedroid: get_profile_interface health
08-26 14:17:31.124  6358  6358 D HealthService: mStartError = false
08-26 14:17:31.124  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
08-26 14:17:31.124  6358  6358 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 14:17:31.124  6358  6768 D HeadsetStateMachine: Disconnected process message: 18
08-26 14:17:31.124  6358  6358 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 14:17:31.124  6358  6358 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-26 14:17:31.124  6358  6358 D PanService: Received start request. Starting profile...
08-26 14:17:31.124  6358  6358 D PanService: start()
08-26 14:17:31.124  6358  6358 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 14:17:31.124  6358  6358 I bluedroid: get_profile_interface pan
08-26 14:17:31.124  6358  6772 D BluetoothMediaBrowser: no now playing list
08-26 14:17:31.124  6358  6358 D PanService: mStartError = false
08-26 14:17:31.124  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
08-26 14:17:31.124  6358  6772 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 14:17:31.134  6358  6358 D BluetoothMapService: Received start request. Starting profile...
08-26 14:17:31.134  6358  6358 D BluetoothMapService: start()
,08-26 14:17:31.134  6358  6358 D BluetoothMapService: mStartError = false
,08-26 14:17:31.134  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
08-26 14:17:31.134  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 14:17:31.134  6358  6358 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 14:17:31.134  6358  6768 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:17:31.134  6358  6358 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
08-26 14:17:31.134  6358  6768 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 14:17:31.134  6358  6768 D HeadsetStateMachine: Disconnected process message: 11
,08-26 14:17:31.134  6358  6358 D SapService: Received start request. Starting profile...
08-26 14:17:31.134  6358  6358 D SapService: start()
08-26 14:17:31.134  6358  6358 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 14:17:31.134  6358  6358 I bluedroid: get_profile_interface sap
08-26 14:17:31.134  6358  6358 D SapService: mStartError = false
08-26 14:17:31.134  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
08-26 14:17:31.134  6358  6358 D BluetoothA2dp: Proxy object connected
08-26 14:17:31.134  6358  6358 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 14:17:31.134  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-26 14:17:31.134  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-26 14:17:31.134  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-26 14:17:31.134  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 14:17:31.164  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 14:17:31.164  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 14:17:31.164  6358  6760 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 14:17:31.164  6358  6760 I bluedroid: enable
,08-26 14:17:31.164  6358  6760 I bt_hci_bdroid: init
08-26 14:17:31.164  6358  6778 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting,
,08-26 14:17:31.164  6358  6760 I bt_vendor: bt-vendor : init
,08-26 14:17:31.164  6358  6760 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 14:17:31.164  6358  6760 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-26 14:17:31.164  6358  6760 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-26 14:17:31.164  6358  6760 D bt_userial_mct: userial_init
,08-26 14:17:31.174  6358  6760 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 14:17:31.174  6358  6760 I bt_vendor: Starting hciattach daemon
,08-26 14:17:31.174  6358  6760 I bt_vendor: try to set false
,08-26 14:17:31.174  6358  6760 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
08-26 14:17:31.174  6358  6760 I bt_vendor: Starting hciattach daemon
,08-26 14:17:31.174  6358  6760 I bt_vendor: try to set true
,08-26 14:17:31.194  6782  6782 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,08-26 14:17:31.234  6788  6788 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-26 14:17:31.244  6789  6789 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 14:17:31.264  6791  6791 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 14:17:31.264  6792  6792 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-26 14:17:31.274  6793  6793 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 14:17:31.284  6794  6794 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 14:17:31.544  6797  6797 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-26 14:17:31.554  6798  6798 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 14:17:31.574  6358  6760 I bt_vendor: bluetooth satus is on,
08-26 14:17:31.574  6358  6780 D bt_userial_mct: userial_open(port:0)
08-26 14:17:31.574  6358  6780 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 14:17:31.584  6358  6780 I bt_vendor: Done intiailizing UART,
,08-26 14:17:31.584  6358  6780 I bt_vendor: Done intiailizing UART,
08-26 14:17:31.584  6358  6780 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67,
08-26 14:17:31.584  6358  6780 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-26 14:17:31.594  6358  6800 D bt_userial_mct: Entering userial_read_thread()
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_HCI,
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_AVDT,
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_BNEP
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_BTM,
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_GAP
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_SAP
,08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_SMP
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 14:17:31.594  6358  6778 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-26 14:17:31.694  6358  6778 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 14:17:31.704  6358  6778 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3efa6e9 
,08-26 14:17:31.704  6358  6778 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3efa6e9 
,08-26 14:17:31.724  6358  6763 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 14:17:31.724  6358  6763 E bt-btif : Calling BTA_HhEnable
,08-26 14:17:31.724  6358  6763 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-26 14:17:31.724  6358  6763 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-26 14:17:31.724  6358  6763 E BluetoothServiceJni: populateRssiValuesNative
08-26 14:17:31.724  6358  6763 I bluedroid: getModelRssiValues
,08-26 14:17:31.724  6358  6763 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-26 14:17:31.724  6358  6763 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 14:17:31.734  6358  6763 D BluetoothAdapterProperties: Name is: A5-1,
08-26 14:17:31.734  1013  1013 D SettingsProvider: name = bluetooth_name
,08-26 14:17:31.734  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:31.734  6358  6763 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 14:17:31.744  6358  6763 D BluetoothAdapterProperties: Scan Mode:20
08-26 14:17:31.744  6358  6763 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 14:17:31.744  6358  6763 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
08-26 14:17:31.744  6358  6763 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-26 14:17:31.744  6358  6763 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-26 14:17:31.744  6358  6763 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-26 14:17:31.744  6358  6763 E bt-btif : btif_sock_init: !vhci_init
08-26 14:17:31.744  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:31.744  6358  6763 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-26 14:17:31.744  6358  6763 D IOP_DB_BT: db_open: db_open : handle 2968752144l, read 13894 bytes onto local cache
,08-26 14:17:31.744  6358  6763 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1,
08-26 14:17:31.744  6358  6763 D IOP_DB_BT: db_query: result 1
08-26 14:17:31.744  6358  6763 I         : iop_db_open: iop_db_open status 0
,08-26 14:17:31.744  6358  6763 D bte_conf: Device ID record 1 : primary
08-26 14:17:31.744  6358  6763 D bte_conf:   vendorId            = 0075
08-26 14:17:31.744  6358  6763 D bte_conf:   vendorIdSource      = 0001
,08-26 14:17:31.744  6358  6763 D bte_conf:   product             = 0100
08-26 14:17:31.744  6358  6763 D bte_conf:   version             = 0200
08-26 14:17:31.744  6358  6763 D bte_conf:   clientExecutableURL = 
08-26 14:17:31.744  6358  6763 D bte_conf:   serviceDescription  = 
08-26 14:17:31.744  6358  6763 D bte_conf:   documentationURL    = 
08-26 14:17:31.744  6358  6763 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 14:17:31.744  6358  6763 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-26 14:17:31.744  6358  6800 E bt_mct  : hci lib postload completed
,08-26 14:17:31.744  6358  6760 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 14:17:31.754  6358  6760 D BluetoothAdapterProperties: ScanMode =  20
,08-26 14:17:31.754  6358  6760 D BluetoothAdapterProperties: State =  11
,08-26 14:17:31.754  1013  1350 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 14:17:31.754  6358  6760 D BluetoothAdapterProperties: Setting state to 12
,08-26 14:17:31.754  6358  6760 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 14:17:31.764  6358  6763 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 14:17:31.764  6358  6763 D BluetoothAdapterProperties: Scan Mode:21
08-26 14:17:31.764  6358  6763 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 14:17:31.764  1013  1540 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 14:17:31.764  1013  1540 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:31.764  1013  1540 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:31.764  1013  1540 D SettingsProvider: selectionArgs: false
,08-26 14:17:31.764  1013  1540 D SettingsProvider: selectionArgs: 1002
08-26 14:17:31.764  1013  1540 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:31.764  1013  1540 D SettingsProvider: ret = -1
08-26 14:17:31.764  6358  6760 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 14:17:31.764  6358  6760 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 14:17:31.764  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:31.764  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:31.764  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:31.764  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:31.764  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:31.764  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:31.764  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:31.764  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:31.764  1013  1314 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:31.764  1013  1314 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.764  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.774  1013  1314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:31.774  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.774  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:31.774  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:31.774  1013  1042 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.774  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 14:17:31.774  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.774  6358  6760 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:31.774  6358  6760 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 14:17:31.774  6358  6760 D BluetoothAdapterService: starting service from this receiver
,08-26 14:17:31.774  1013  3119 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:31.774  1013  3119 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.784  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:31.784  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:31.784  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:31.784  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:31.784  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:31.784  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:31.784  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:31.784  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:31.784  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:31.784  1323  1336 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:31.784  1013  3119 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.784  1013  3119 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.784  1013  3119 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.784  1013  1013 D BluetoothA2dp: Proxy object connected
,08-26 14:17:31.784  6358  6760 I BluetoothAdapterState: Entering On State from state = 11
,08-26 14:17:31.784  1323  1336 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.794  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 14:17:31.794  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.794  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.794  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.794  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.794  1323  1323 D BluetoothA2dp: Proxy object connected
,08-26 14:17:31.794  1323  1323 D A2dpProfile: Bluetooth service connected
08-26 14:17:31.794  1323  1341 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.804  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:31.804  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.804  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.804  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.804  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.804  6358  6358 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
08-26 14:17:31.804  1323  1341 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:31.804  6328  6336 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.804  6328  6336 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.804  1443  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:31.804  1443  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.804  1431  2763 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:31.804  1431  2763 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.814  6167  6177 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:31.814  6167  6177 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.814  6358  6358 I BluetoothPbapService: Handler(): got msg=1
,08-26 14:17:31.814  1431  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.814  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:31.814  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.814  1013  3042 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 14:17:31.814  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.814  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.814  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.814  1431  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:31.824  1431  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.824  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:31.824  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.824  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.824  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.824  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.824  1431  1439 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 14:17:31.824  6358  6804 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 14:17:31.824  1323  1323 D HeadsetProfile: Bluetooth service connected
,08-26 14:17:31.824  1905  2118 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.824  1905  2118 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.824  2887  2897 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.824  1013  1042 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:31.824  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.834  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.834  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:31.834  6358  6804 D BluetoothSocket: bindListen(): myUserId = 0
08-26 14:17:31.834  6358  6804 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:31.834  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.834  6358  6804 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
,08-26 14:17:31.834  2887  2897 E BluetoothHeadset: BluetoothHeadset service is binded,
08-26 14:17:31.834  6358  6804 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:31.834  6358  6804 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:31.834  6358  6804 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27601249
08-26 14:17:31.834  6358  6804 D BluetoothSocket: channel: 19
08-26 14:17:31.834  6358  6804 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 14:17:31.834  6358  6372 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.834  6358  6372 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.834  2887  2943 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:31.844  2887  2943 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.844  1013  1042 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 14:17:31.844  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.844  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.844  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.844  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.844  6358  6612 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:31.844  1013  1042 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.844  2887  2887 D BluetoothA2dp: Proxy object connected
,08-26 14:17:31.844  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:31.844  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.844  1013  1042 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 14:17:31.844  1323  6618 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 14:17:31.854  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 14:17:31.854  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.854  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.854  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.854  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.854  1323  1341 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 14:17:31.854  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 14:17:31.854  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.854  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.854  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.854  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.854  2887  2943 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:31.854  2887  2943 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 14:17:31.854  1323  1323 D BluetoothPbap: Proxy object connected
,08-26 14:17:31.864  1431  2763 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.864  1323  1323 D PbapServerProfile: Bluetooth service connected
,08-26 14:17:31.864  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:31.864  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.864  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.864  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.864  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
08-26 14:17:31.864  1323  1323 D BluetoothInputDevice: Proxy object connected
,08-26 14:17:31.864  1431  2763 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 14:17:31.864  1323  1323 D HidProfile: Bluetooth service connected
08-26 14:17:31.864  1175  3018 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.864  1175  3018 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.864  1323  1336 D BluetoothPan: Binding service...
,08-26 14:17:31.864  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-26 14:17:31.864  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.864  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.864  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.864  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.874  1323  1323 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 14:17:31.874  1323  1323 D PanProfile: Bluetooth service connected
08-26 14:17:31.874  1323  6618 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 14:17:31.874  1323  6618 D Bluetoothsap: Binding service...
,08-26 14:17:31.874  1323  6618 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 14:17:31.874  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-26 14:17:31.874  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.874  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.874  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.874  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.874  1323  6618 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 14:17:31.874  1323  1336 D BluetoothMap: onBluetoothStateChange: up=true
,08-26 14:17:31.874  1323  1323 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 14:17:31.874  1323  1323 D SapProfile: Bluetooth service connected
08-26 14:17:31.874  1323  1323 D Bluetoothsap: getConnectedDevices()
,08-26 14:17:31.874  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
08-26 14:17:31.874  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.874  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.874  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.874  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.884  1013  1042 D BluetoothPan: Binding service...
,08-26 14:17:31.884  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 14:17:31.884  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.884  1013  1013 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 14:17:31.884  1455  2158 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:31.884  1323  1323 D BluetoothMap: Proxy object connected
08-26 14:17:31.884  1013  1042 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:31.884  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:31.884  1323  1323 D MapProfile: Bluetooth service connected
08-26 14:17:31.884  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.884  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.884  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.884  1323  1323 D BluetoothMap: getConnectedDevices()
08-26 14:17:31.884  1455  2158 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:31.884  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.884  1013  1042 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.884  1455  1715 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.884  1455  1715 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:31.884  1323  1341 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:31.884  1323  1341 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 14:17:31.884  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
08-26 14:17:31.884  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 14:17:31.884  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:31.884  1013  1013 I InputMethodManagerService: [BT Setting State] State =12
08-26 14:17:31.884  1013  1013 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 14:17:31.894  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-26 14:17:31.894  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 14:17:31.894  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:31.894  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:31.904  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@18085d4c, true
,08-26 14:17:31.904  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:31.904  1175  1175 D BluetoothTile:  getBluetoothState : 12
,08-26 14:17:31.904  1431  1431 D BluetoothHeadset: registerMessageListener
,08-26 14:17:31.904  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:31.904  1896  1896 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 14:17:31.904  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:31.904  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:31.914  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:31.914  1013  3119 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:31.914  6358  6805 D HeadsetService: registerMessageListener
08-26 14:17:31.914  1013  3119 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.914  6358  6805 D HeadsetService: registerMessageListener
08-26 14:17:31.914  1013  3040 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:31.914  1013  1026 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-26 14:17:31.914  1013  3119 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.914  1013  3119 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:31.914  1013  3119 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:31.914  6358  6768 D HeadsetStateMachine: Disconnected process message: 70
,08-26 14:17:31.914  6358  6768 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@36f0374e
08-26 14:17:31.914  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 14:17:31.914  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 14:17:31.914  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:31.924  1323  1323 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
,08-26 14:17:31.924  1323  1323 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
,08-26 14:17:31.924  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
08-26 14:17:31.924  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 14:17:31.924  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-26 14:17:31.924  1323  1323 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 14:17:31.924  1323  1323 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 14:17:31.924  6358  6806 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 14:17:31.924  6358  6768 D HeadsetStateMachine: Disconnected process message: 9
,08-26 14:17:31.924  6358  6768 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 14:17:31.924  6358  6806 D BluetoothSocket: bindListen(): myUserId = 0
08-26 14:17:31.924  6358  6806 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:31.934  6358  6806 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
,08-26 14:17:31.934  6358  6806 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:31.934  6358  6806 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:31.934  6358  6806 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2975806f
08-26 14:17:31.934  6358  6806 D BluetoothSocket: channel: 5
,08-26 14:17:31.934   281   281 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,08-26 14:17:31.934   281   281 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 14:17:31.934   281   281 V voice   : voice_set_parameters: exit with code(-2)
08-26 14:17:31.934   281   281 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 14:17:31.934   281   281 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 14:17:31.934   281   281 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
,08-26 14:17:31.934   281   281 V audio_hw_primary: adev_set_parameters: exit
08-26 14:17:31.934  6358  6768 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 14:17:31.944  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-26 14:17:31.944  1013  1314 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 14:17:31.944  1013  1314 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.944  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:31.944  1013  1314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:31.944  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:31.954  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:31.954  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:31.964  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:31.964  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 14:17:31.974  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
,08-26 14:17:31.974  6358  6358 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 14:17:31.974  1013  3038 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:31.974  1013  3038 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.974  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.974  1013  3038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:31.974  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:31.994  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:31.994  1013  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:31.994  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 14:17:31.994  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:31.994  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:31.994  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:32.004  1013  1261 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 14:17:32.014  1905  6815 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 14:17:32.014  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:32.014  6358  6816 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 14:17:32.014  6358  6816 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:32.024  6358  6816 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
08-26 14:17:32.024  6358  6816 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:32.024  6358  6816 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:32.024  6358  6816 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1683b48b
,08-26 14:17:32.024  6358  6816 D BluetoothSocket: channel: 12
08-26 14:17:32.024  6358  6816 I BtOppRfcommListener: Accept thread started.
,08-26 14:17:32.094  1905  2113 I art     : Explicit concurrent mark sweep GC freed 50614(2MB) AllocSpace objects, 53(2MB) LOS objects, 40% free, 14MB/24MB, paused 1.544ms total 76.963ms
,08-26 14:17:32.244  1013  1025 I art     : Explicit concurrent mark sweep GC freed 46931(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.352ms total 146.627ms
08-26 14:17:32.244  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:32.244  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:32.244  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:32.244  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:32.254  1013  1314 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:32.254  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:32.254  1013  1314 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:32.254  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:32.264  1905  6815 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 14:17:32.374  1013  2774 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-26 14:17:32.464  1013  1131 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 14:17:32.464  1013  1131 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4172, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
08-26 14:17:32.464  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-26 14:17:32.464  1013  1131 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,08-26 14:17:32.464  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 14:17:32.464  1013  1131 D BatteryService: stay LED for charging,
,08-26 14:17:32.464  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 14:17:32.464  1013  1013 I MotionRecognitionService: Plugged
,08-26 14:17:32.464  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false,
08-26 14:17:32.474  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,08-26 14:17:32.474  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
,08-26 14:17:32.484  6358  6358 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 14:17:32.484  6358  6768 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:17:32.494  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-26 14:17:32.494  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-26 14:17:32.494  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-26 14:17:32.924  1013  2741 D SSRM:n  : SIOP:: AP = 350,
,08-26 14:17:33.024   286   286 E SMD     : DCD OFF
,08-26 14:17:33.854  6167  6220 D BluetoothAdapter: disable()
,08-26 14:17:33.854  1013  1350 D SettingsProvider: name = bluetooth_on
,08-26 14:17:33.854  6358  6760 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-26 14:17:33.854  6358  6760 D BluetoothAdapterProperties: Setting state to 13
08-26 14:17:33.854  6358  6760 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-26 14:17:33.854  6358  6760 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:33.854  6358  6760 D BluetoothAdapterService: updateAdapterState state is 13
08-26 14:17:33.854  1013  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:33.854  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 14:17:33.864  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:33.864  1013  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:33.864  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:33.864  6358  6358 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-26 14:17:33.864  6358  6760 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:33.864  6358  6760 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-26 14:17:33.864  6358  6760 D BluetoothAdapterService: terminating service from this receiver
,08-26 14:17:33.864  6358  6358 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@25986968, channel: 19, state: LISTENING
,08-26 14:17:33.864  6358  6358 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@25986968, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27601249, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2072c181mSocket: android.net.LocalSocket@3297e226 impl:android.net.LocalSocketImpl@20f70e67 fd:FileDescriptor[75]
,08-26 14:17:33.864  6358  6358 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3297e226 impl:android.net.LocalSocketImpl@20f70e67 fd:FileDescriptor[75]
,08-26 14:17:33.874  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.874  1013  1013 I InputMethodManagerService: [BT Setting State] State =13
,08-26 14:17:33.874  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-26 14:17:33.874  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-26 14:17:33.874  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-26 14:17:33.874  1175  1175 D BluetoothTile:  getBluetoothState : 13
,08-26 14:17:33.884  1896  1896 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 14:17:33.884  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:33.884  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:33.884  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-26 14:17:33.894  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:33.894  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:33.894  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:33.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:33.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:33.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:33.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:33.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:33.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:33.894  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:33.894  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 14:17:33.894  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:33.894  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:33.894  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:33.894  1013  1131 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 14:17:33.894  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:33.894  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:33.894  1013  3038 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 14:17:33.894  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:33.894  6358  6760 D BluetoothAdapterProperties: onBluetoothDisable()
08-26 14:17:33.894  6358  6760 D BluetoothAdapterProperties: mDiscovering is false
,08-26 14:17:33.894  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 14:17:33.904  1013  1261 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-26 14:17:33.904  1013  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:33.904  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:33.904  6358  6760 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-26 14:17:33.904  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:33.904  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:33.904  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:33.904  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:33.904  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:33.904  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-26 14:17:33.904  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:33.904  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:33.904  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:33.904  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:33.904  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:33.904  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:33.904  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:33.914  6167  6167 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-26 14:17:33.914  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:33.914  1013  1345 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 14:17:33.914  1013  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:33.914  1013  1345 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:33.914  6358  6763 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 14:17:33.914  6358  6763 D BluetoothAdapterProperties: Scan Mode:20
,08-26 14:17:33.924  1013  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
08-26 14:17:33.924  1013  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:33.924  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:33.924  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:33.924  6358  6760 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-26 14:17:33.924  6358  6760 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-26 14:17:33.924  6358  6760 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-26 14:17:33.924  6358  6760 E bt-btif : cmd socket is not created
,08-26 14:17:33.924  6358  6816 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-26 14:17:33.934  6358  6760 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-26 14:17:33.934  6358  6778 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-26 14:17:33.934  6358  6778 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-26 14:17:33.934  6358  6778 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:33.934  6358  6778 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:33.934  6358  6778 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-26 14:17:33.934  1323  1323 D BluetoothPbap: Proxy object disconnected
08-26 14:17:33.934  1323  1323 D PbapServerProfile: Bluetooth service disconnected
08-26 14:17:33.934  6358  6358 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1a3eb414, channel: 5, state: LISTENING
08-26 14:17:33.934  6358  6358 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1a3eb414, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2975806f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2308f4bdmSocket: android.net.LocalSocket@2c8ffab2 impl:android.net.LocalSocketImpl@2f5c2a03 fd:FileDescriptor[77]
08-26 14:17:33.934  6358  6358 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2c8ffab2 impl:android.net.LocalSocketImpl@2f5c2a03 fd:FileDescriptor[77]
08-26 14:17:33.934  6358  6358 I BtOppRfcommListener: stopping Accept Thread
08-26 14:17:33.934  6358  6358 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@5cfd80, channel: 12, state: LISTENING
,08-26 14:17:33.934  6358  6358 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@5cfd80, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1683b48b, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@dd51fb9mSocket: android.net.LocalSocket@157f0ffe impl:android.net.LocalSocketImpl@3a6d635f fd:FileDescriptor[81]
08-26 14:17:33.934  6358  6358 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@157f0ffe impl:android.net.LocalSocketImpl@3a6d635f fd:FileDescriptor[81]
08-26 14:17:33.934  6358  6816 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-26 14:17:33.934  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:33.944  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:33.944  6358  6358 V BluetoothOppManager: cleanUp...
,08-26 14:17:33.944  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:33.954  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,08-26 14:17:33.974  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:33.984  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:34.134  6358  6778 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-26 14:17:34.134  6358  6778 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:34.134  6358  6778 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:34.134  6358  6778 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:34.134  6358  6778 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:34.134  6358  6778 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:34.134  6358  6778 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-26 14:17:34.134  6358  6778 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-26 14:17:34.134  6358  6778 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-26 14:17:34.134  6358  6778 W bt-btif : ag scb idx 1 not allocated
08-26 14:17:34.134  6358  6778 W bt-btif : ag scb idx 2 not allocated
08-26 14:17:34.134  6358  6778 E bt-btif : BTA AG is already disabled, ignoring ...
08-26 14:17:34.134  6358  6800 I bt_userial_mct: exiting userial_read_thread
08-26 14:17:34.134  6358  6800 D bt_userial_mct: Leaving userial_evt_read_thread()
08-26 14:17:34.134  6358  6763 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-26 14:17:34.134  6358  6780 I bt_vendor: hw_epilog_process
08-26 14:17:34.134  6358  6763 D bt_userial_mct: userial_close
08-26 14:17:34.134  6358  6763 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-26 14:17:34.324  1013  1329 E Watchdog: !@Sync 4
,08-26 14:17:34.484  6358  6763 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-26 14:17:34.484  6358  6763 I bt_vendor: bluetooth satus is on
08-26 14:17:34.484  6358  6763 I bt_vendor: bt-vendor : resetting BT status
08-26 14:17:34.484  6358  6763 I bt_vendor: Starting hciattach daemon
,08-26 14:17:34.484  6358  6763 I bt_vendor: try to set false
08-26 14:17:34.484  6358  6763 I bt_vendor: Starting hciattach daemon
08-26 14:17:34.484  6358  6763 I bt_vendor: try to set false
08-26 14:17:34.484  6358  6763 I bt_vendor: cleanup
08-26 14:17:34.484  6358  6778 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-26 14:17:34.484  6358  6763 I GKI_LINUX: GKI_exit_task 0 done
08-26 14:17:34.484  6358  6763 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-26 14:17:34.484  6358  6760 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-26 14:17:34.484  6358  6760 D BtConfig.SecureMode: isSecureModeOn:false
08-26 14:17:34.484  6358  6760 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-26 14:17:34.484  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 14:17:34.484  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService,
08-26 14:17:34.484  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 14:17:34.484  1013  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
08-26 14:17:34.484  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.494  1013  1541 W ActivityManager: userId = 0, bbcId = -10000,
,08-26 14:17:34.494  1013  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:34.494  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:34.494  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 14:17:34.494  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 14:17:34.494  6358  6358 D BtGatt.DebugUtils: handleDebugAction() action=null
08-26 14:17:34.494  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 14:17:34.494  1013  3193 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:34.494  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.494  6358  6358 D BtGatt.GattService: Received stop request...Stopping profile...
08-26 14:17:34.494  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:34.494  1013  3193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:34.494  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:34.494  6358  6358 D BtGatt.GattService: stop()
08-26 14:17:34.494  6358  6358 D BtGatt.AdvertiseManager: advertise clients cleared
,08-26 14:17:34.494  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:34.494  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 14:17:34.494  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:34.494  1013  3040 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:34.504  1013  3040 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.504  1013  3040 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:34.504  1013  3040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:34.504  1013  3040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:34.504  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 14:17:34.504  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:34.504  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 14:17:34.504  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
08-26 14:17:34.504  1013  1345 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:34.504  1013  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.504  1013  1345 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:34.504  1013  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:34.504  1013  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:34.504  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-26 14:17:34.504  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 14:17:34.504  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 14:17:34.514  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:34.514  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.514  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:34.514  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:34.514  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:34.514  6358  6358 D HeadsetService: Received stop request...Stopping profile...
,08-26 14:17:34.514  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 14:17:34.514  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 14:17:34.514  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 14:17:34.514  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
08-26 14:17:34.514  1013  1131 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:34.514  1013  1131 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.514  1013  1131 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:34.514  1013  1131 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:34.514  1013  1131 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:34.514  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 14:17:34.514  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:34.514  6358  6760 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:34.514  1323  1323 D HeadsetProfile: Bluetooth service disconnected
,08-26 14:17:34.514  1013  1713 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:34.514  1013  1713 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.514  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-26 14:17:34.524  1013  1713 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:34.524  6358  6358 D A2dpService: Received stop request...Stopping profile...
08-26 14:17:34.524  1013  1713 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:34.524  1013  1713 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:34.524  6358  6773 D A2dpStateMachine: Exit Disconnected: -1
,08-26 14:17:34.524  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,08-26 14:17:34.524  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:34.524  6358  6760 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 14:17:34.524  1013  1345 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:34.524  1013  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.524  1013  1345 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:34.524  1013  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:34.524  1013  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:34.524  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
,08-26 14:17:34.534  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:34.534  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:34.534  6358  6760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:34.534  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:34.534  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:34.534  6358  6760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:34.534  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-26 14:17:34.534  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:34.534  6358  6760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-26 14:17:34.534  6358  6760 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 14:17:34.534  6358  6760 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 14:17:34.534  6358  6760 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-26 14:17:34.534  6358  6760 D BluetoothAdapterState: Stopping profile services that were post enabled
08-26 14:17:34.534  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-26 14:17:34.534  1013  1013 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:34.534  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-26 14:17:34.534  6358  6358 D HidService: Received stop request...Stopping profile...
08-26 14:17:34.534  6358  6358 D HidService: Stopping Bluetooth HidService
08-26 14:17:34.534  6358  6358 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-26 14:17:34.534  6358  6358 W bt-btif : cleanup: HH disabling or disabled already, status = 0
,08-26 14:17:34.534  6358  6358 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-26 14:17:34.534  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
08-26 14:17:34.534  2887  2887 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:34.534  1323  1323 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:34.534  1323  1323 D A2dpProfile: Bluetooth service disconnected
,08-26 14:17:34.534  6358  6358 D HealthService: Received stop request...Stopping profile...
,08-26 14:17:34.534  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
08-26 14:17:34.534  1323  1323 D BluetoothInputDevice: Proxy object disconnected
08-26 14:17:34.534  1323  1323 D HidProfile: Bluetooth service disconnected
,08-26 14:17:34.534  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-26 14:17:34.534  6358  6358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:34.534  6358  6358 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 14:17:34.534  6358  6358 D PanService: Received stop request...Stopping profile...
08-26 14:17:34.534  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
,08-26 14:17:34.534  1013  1013 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-26 14:17:34.534  1323  1323 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-26 14:17:34.534  1323  1323 D PanProfile: Bluetooth service disconnected
08-26 14:17:34.544  6358  6358 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-26 14:17:34.544  6358  6358 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-26 14:17:34.544  6358  6358 D BluetoothMapService: Received stop request...Stopping profile...
,08-26 14:17:34.544  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
,08-26 14:17:34.544  1323  1323 D BluetoothMap: Proxy object disconnected
,08-26 14:17:34.544  1323  1323 D MapProfile: Bluetooth service disconnected
08-26 14:17:34.544  6358  6358 D SapService: Received stop request...Stopping profile...
08-26 14:17:34.544  6358  6358 D SapService: Stopping Bluetooth SapService
08-26 14:17:34.544  6358  6358 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@399b9354
,08-26 14:17:34.544  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
,08-26 14:17:34.544  6358  6358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 14:17:34.544  6358  6358 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-26 14:17:34.544  6358  6358 D BluetoothA2dp: Proxy object disconnected
08-26 14:17:34.554  6358  6358 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-26 14:17:34.554  1323  1323 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-26 14:17:34.554  1323  1323 D SapProfile: Bluetooth service disconnected
,08-26 14:17:34.554  6358  6774 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-26 14:17:34.554  6358  6358 I GKI_LINUX: GKI_exit_task 2 done
08-26 14:17:34.554  6358  6358 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,08-26 14:17:34.554  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-26 14:17:34.554  6358  6358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:34.554  6358  6358 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:34.554  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
,08-26 14:17:34.554  6358  6358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:34.554  6358  6358 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:34.554  6358  6358 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-26 14:17:34.554  6358  6358 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-26 14:17:34.554  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-26 14:17:34.554  6358  6358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:34.554  6358  6358 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:34.554  6358  6358 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-26 14:17:34.554  6358  6358 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-26 14:17:34.554  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-26 14:17:34.554  6358  6358 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:34.554  6358  6358 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-26 14:17:34.554  6358  6358 E BluetoothAdapterService(966497108): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-26 14:17:34.564  6358  6358 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
,08-26 14:17:34.564  6358  6358 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-26 14:17:34.564  6358  6760 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,08-26 14:17:34.564  6358  6760 D BluetoothAdapterProperties: Setting state to 10
08-26 14:17:34.564  6358  6760 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-26 14:17:34.564  6358  6760 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:34.564  6358  6760 D BluetoothAdapterService: updateAdapterState state is 10
08-26 14:17:34.564  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 14:17:34.564  6358  6760 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:34.564  6358  6760 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-26 14:17:34.564  6358  6760 I BluetoothAdapterState: Entering OffState
08-26 14:17:34.564  1323  1336 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 14:17:34.564  6328  6336 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:34.564  6328  6336 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.564  1443  1454 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:34.564  1443  1454 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.564  1431  2763 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:34.564  1431  2763 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.564  6167  6177 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:34.564  6167  6177 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.564  6167  6177 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
08-26 14:17:34.564  6167  6177 D BluetoothLeAdvertiser: Exit stop advertising
08-26 14:17:34.564  6167  6177 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,08-26 14:17:34.564  6167  6177 D BluetoothLeScanner: Exiting stopAllScan
,08-26 14:17:34.574  1905  1922 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:34.574  1905  1922 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.574  6358  6372 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:34.574  6358  6372 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.574  2887  2943 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 14:17:34.574  6358  6612 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-26 14:17:34.574  1323  6618 D BluetoothPbap: onBluetoothStateChange: up=false
,08-26 14:17:34.574  1323  1336 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-26 14:17:34.574  2887  2897 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:34.574  2887  2897 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.584  1175  1185 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:34.584  1175  1185 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.584  1323  6618 D Bluetoothsap: onBluetoothStateChange: up=false
,08-26 14:17:34.584  1323  6618 D Bluetoothsap: Unbinding service...
,08-26 14:17:34.584  1323  1336 D BluetoothMap: onBluetoothStateChange: up=false
,08-26 14:17:34.584  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=false
,08-26 14:17:34.584  1013  1042 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.584  1455  1715 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:34.584  1455  1715 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.584  1323  1341 D BluetoothAdapter: onBluetoothStateChange: up=false
08-26 14:17:34.584  1323  1341 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,08-26 14:17:34.584  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,08-26 14:17:34.594  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 14:17:34.594  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:34.594  1013  1013 I InputMethodManagerService: [BT Setting State] State =10
,08-26 14:17:34.594  1013  1013 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 14:17:34.604  1175  1175 D BluetoothAdapter: 1070518983: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:34.604  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 14:17:34.604  1175  1711 D BluetoothAdapter: 1070518983: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:34.604  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED,
08-26 14:17:34.604  1175  1175 D BluetoothTile:  getBluetoothState : 10
08-26 14:17:34.604  1175  1175 D BluetoothAdapter: 1070518983: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:34.604  1175  1175 D BluetoothAdapter: 1070518983: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:34.604  1175  1711 D BluetoothAdapter: 1070518983: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:34.604  1013  1314 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 14:17:34.604  1013  1025 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-26 14:17:34.604  1896  1896 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 14:17:34.604  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,08-26 14:17:34.614  1905  2129 D BluetoothAdapter: 1006347221: getState() :  mService = null. Returning STATE_OFF
08-26 14:17:34.614  1905  2129 D BluetoothAdapter: 1006347221: getState() :  mService = null. Returning STATE_OFF
,08-26 14:17:34.614  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:34.614  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:34.614  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:34.614  1013  3038 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:34.614  1013  3038 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.624  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:34.624  1013  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:34.624  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:34.624  6358  6763 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-26 14:17:34.624  6358  6358 I GKI_LINUX: GKI_exit_task 1 done
08-26 14:17:34.624  6358  6358 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-26 14:17:34.624  6358  6358 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-26 14:17:34.624  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:34.624  6358  6358 I art     : System.exit called, status: 0
08-26 14:17:34.624  1013  1540 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-26 14:17:34.624  1013  1540 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.624  6358  6358 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-26 14:17:34.624  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:34.624  1013  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:34.624  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:34.644  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:34.644  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:34.644  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:34.644  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,08-26 14:17:34.704  1013  3042 I ActivityManager: Process com.android.bluetooth (pid 6358)(adj 0) has died(71,1079)
,08-26 14:17:34.714  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:34.714  1013  1025 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:34.714  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 14:17:34.714  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:34.714  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
08-26 14:17:34.714  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:34.724  1905  6833 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 14:17:34.724  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:34.734  1013  3042 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:34.734  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:34.734  1013  3042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:34.734  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:34.744  1905  6833 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-26 14:17:35.024   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:36.024   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:36.024   286   286 E SMD     : DCD OFF
,08-26 14:17:36.864  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 14:17:36.864  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:37.024   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:38.024   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,08-26 14:17:38.324  1013  1959 V SAMP_SPCM_test: CSC File load.. ,
,08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
,08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security,
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn,
08-26 14:17:38.324  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 14:17:38.354  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under, uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
,08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
08-26 14:17:38.364  1013  1959 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,08-26 14:17:38.374  1013  1959 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,08-26 14:17:38.374  1013  1959 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:38.374  1013  1959 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:38.374  1013  1959 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:38.374  1013  1959 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:38.394  1013  1959 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6836 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-26 14:17:38.394  6836  6836 E Zygote  : MountEmulatedStorage(),
,08-26 14:17:38.394  6836  6836 E Zygote  : v2
08-26 14:17:38.394  6836  6836 I libpersona: KNOX_SDCARD checking this for 1000,
08-26 14:17:38.394  6836  6836 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:38.394  6836  6836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 14:17:38.404  6836  6836 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,08-26 14:17:38.404  6836  6836 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-26 14:17:38.424  6836  6836 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:38.434  6836  6836 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:38.444  6836  6836 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:17:38.484  1013  1959 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,08-26 14:17:39.034   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,08-26 14:17:39.034   286   286 E SMD     : DCD OFF,
,08-26 14:17:39.864  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:39.864  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b21638 added. We now have 6 listener(s)
08-26 14:17:39.864  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:39.864  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:39.864  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ae8b611 added. We now have 7 listener(s)
,08-26 14:17:39.864  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:39.864  6167  6220 I System.out: IsBluetoothEnabled
,08-26 14:17:39.864  6167  6220 D BluetoothAdapter: disable()
,08-26 14:17:39.864  1013  1540 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-26 14:17:39.874  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:39.874  6167  6220 D BluetoothAdapter: enable()
,08-26 14:17:39.874  1013  3119 W ActivityManager: Permission Denial: getCurrentUser() from pid=6167, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-26 14:17:39.874  1013  3119 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-26 14:17:39.874  1013  3119 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6167, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:39.874  1013  3119 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-26 14:17:39.874  1013  3119 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
08-26 14:17:39.874  1013  3119 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
08-26 14:17:39.874  1013  3119 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
08-26 14:17:39.874  1013  3119 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 14:17:39.874  1013  3119 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 14:17:39.874  1013  3119 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:39.874  1013  3119 D SettingsProvider: name = bluetooth_on
,08-26 14:17:39.884  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 14:17:39.884  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:39.884  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
08-26 14:17:39.884  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,08-26 14:17:39.894  1013  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:39.894  1013  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:39.894  1013  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:39.894  1013  1042 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:39.904  6854  6854 E Zygote  : MountEmulatedStorage()
08-26 14:17:39.904  6854  6854 I libpersona: KNOX_SDCARD checking this for 1002
08-26 14:17:39.904  6854  6854 E Zygote  : v2
08-26 14:17:39.904  6854  6854 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:39.904  6854  6854 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:39.914  6854  6854 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 14:17:39.914  1013  1042 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=6854 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-26 14:17:39.914  6854  6854 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:39.944  6854  6854 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:39.944  6854  6854 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:39.954  6854  6854 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-26 14:17:39.954  6854  6854 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:39.984  6854  6854 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-26 14:17:40.024   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding GattService
,08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding HeadsetService
,08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding A2dpService
,08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding HidService
,08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding HealthService
08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding PanService
,08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding SapService
08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding SapClientService
,08-26 14:17:40.024  6854  6854 D BtSettings.ProfileConfig: Adding HidDevService
08-26 14:17:40.024  6854  6854 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-26 14:17:40.034  1013  1345 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-26 14:17:40.034  1013  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.034  1013  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.034  1013  1345 D SettingsProvider: selectionArgs: false
,08-26 14:17:40.034  1013  1345 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.034  1013  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:40.034  1013  1345 D SettingsProvider: ret = -1
,08-26 14:17:40.034  1013  1350 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,08-26 14:17:40.034  1013  1350 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.034  1013  1350 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.034  1013  1350 D SettingsProvider: selectionArgs: false
08-26 14:17:40.034  1013  1350 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.034  1013  1350 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.034  1013  1350 D SettingsProvider: ret = -1
,08-26 14:17:40.034  1013  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:40.034  1013  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.034  1013  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.034  1013  1026 D SettingsProvider: selectionArgs: false
08-26 14:17:40.034  1013  1026 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.034  1013  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.034  1013  1026 D SettingsProvider: ret = -1
08-26 14:17:40.034  1013  3040 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,08-26 14:17:40.034  1013  3040 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.034  1013  3040 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.034  1013  3040 D SettingsProvider: selectionArgs: false
08-26 14:17:40.034  1013  3040 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.034  1013  3040 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.034  1013  3040 D SettingsProvider: ret = -1
,08-26 14:17:40.034  1013  1131 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-26 14:17:40.034  1013  1131 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.034  1013  1131 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 14:17:40.034  1013  1131 D SettingsProvider: selectionArgs: false
08-26 14:17:40.034  1013  1131 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:40.034  1013  1131 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.034  1013  1131 D SettingsProvider: ret = -1
,08-26 14:17:40.044  1013  1314 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-26 14:17:40.044  1013  1314 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.044  1013  1314 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.044  1013  1314 D SettingsProvider: selectionArgs: false
08-26 14:17:40.044  1013  1314 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.044  1013  1314 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.044  1013  1314 D SettingsProvider: ret = -1
,08-26 14:17:40.044  1013  3042 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-26 14:17:40.044  1013  3042 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.044  1013  3042 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.044  1013  3042 D SettingsProvider: selectionArgs: false
08-26 14:17:40.044  1013  3042 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.044  1013  3042 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.044  1013  3042 D SettingsProvider: ret = -1
,08-26 14:17:40.044  1013  1713 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-26 14:17:40.044  1013  1713 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.044  1013  1713 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.044  1013  1713 D SettingsProvider: selectionArgs: false
08-26 14:17:40.044  1013  1713 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.044  1013  1713 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.044  1013  1713 D SettingsProvider: ret = -1
,08-26 14:17:40.044  1013  1261 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:40.044  1013  1261 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.044  1013  1261 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-26 14:17:40.044  1013  1261 D SettingsProvider: selectionArgs: false
08-26 14:17:40.044  1013  1261 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.044  1013  1261 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-26 14:17:40.044  1013  1261 D SettingsProvider: ret = -1
,08-26 14:17:40.044  1013  3038 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:40.044  1013  3038 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.044  1013  3038 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.044  1013  3038 D SettingsProvider: selectionArgs: false
08-26 14:17:40.044  1013  3038 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.044  1013  3038 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.044  1013  3038 D SettingsProvider: ret = -1
,08-26 14:17:40.044  1013  1540 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-26 14:17:40.044  1013  1540 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.044  1013  1540 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.044  1013  1540 D SettingsProvider: selectionArgs: false
,08-26 14:17:40.044  1013  1540 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.044  1013  1540 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.044  1013  1540 D SettingsProvider: ret = -1
,08-26 14:17:40.044  1013  3193 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-26 14:17:40.044  1013  3193 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.044  1013  3193 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.044  1013  3193 D SettingsProvider: selectionArgs: false
08-26 14:17:40.044  1013  3193 D SettingsProvider: selectionArgs: 1002
,08-26 14:17:40.044  1013  3193 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.044  1013  3193 D SettingsProvider: ret = -1
,08-26 14:17:40.064  6854  6854 D BluetoothAdapterState: make
,08-26 14:17:40.064  6854  6854 I bluedroid: init
,08-26 14:17:40.064  6854  6869 I BluetoothAdapterState: Entering OffState
,08-26 14:17:40.064  6854  6854 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-26 14:17:40.064  6854  6854 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-26 14:17:40.064  6854  6854 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-26 14:17:40.064  6854  6854 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-26 14:17:40.064  6854  6854 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-26 14:17:40.074  6854  6854 I bluedroid: get_profile_interface socket
08-26 14:17:40.074  6854  6854 I bluedroid: get_profile_interface map_client
,08-26 14:17:40.074  6854  6872 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-26 14:17:40.074  6854  6854 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-26 14:17:40.074  6854  6872 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,08-26 14:17:40.074  6854  6872 E BluetoothServiceJni: populateRssiValuesNative
08-26 14:17:40.074  6854  6872 I bluedroid: getModelRssiValues
08-26 14:17:40.074  6854  6872 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 14:17:40.074  6854  6872 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 14:17:40.074  6854  6872 D BluetoothAdapterProperties: Name is: A5-1
,08-26 14:17:40.074  1013  1013 D SettingsProvider: name = bluetooth_name
,08-26 14:17:40.084  6854  6854 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:40.084  1013  3042 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 14:17:40.084  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.084  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:40.084  1013  3042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:40.084  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:40.084  6854  6862 I bluedroid: config_hci_snoop_log
,08-26 14:17:40.084  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,08-26 14:17:40.094  1013  1042 D BluetoothManagerService: Ble is always on enable gatt
,08-26 14:17:40.094  1013  1042 I BluetoothManagerService: enableGattForLeMode, doBind called
08-26 14:17:40.094  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 14:17:40.094  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 14:17:40.094  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-26 14:17:40.094  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-26 14:17:40.094  6854  6854 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,08-26 14:17:40.094  1013  1042 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-26 14:17:40.104  6854  6869 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-26 14:17:40.104  6854  6869 D BluetoothAdapterProperties: Setting state to 11
08-26 14:17:40.104  6854  6869 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-26 14:17:40.104  6854  6869 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-26 14:17:40.104  6854  6869 D BluetoothAdapterService: updateAdapterState state is 11
,08-26 14:17:40.104  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-26 14:17:40.104  6854  6869 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:40.104  6854  6869 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-26 14:17:40.104  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:40.104  1013  1013 I InputMethodManagerService: [BT Setting State] State =11
,08-26 14:17:40.104  6854  6869 D BluetoothSecureManager: getInstant: null
,08-26 14:17:40.104  6854  6869 D BluetoothSecureManager: calling getMethod for getService
08-26 14:17:40.104  6854  6869 D BluetoothSecureManager: calling getService
,08-26 14:17:40.104  6854  6869 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2bdf7f9f
08-26 14:17:40.104  1013  1345 D BluetoothSecureManagerService: isSecureModeEnabled
,08-26 14:17:40.104  1013  1345 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-26 14:17:40.114  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 14:17:40.114  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:40.114  1175  1175 D BluetoothTile:  getBluetoothState : 11
,08-26 14:17:40.124  6854  6869 D BtConfig.SecureMode: isSecureModeOn:false
08-26 14:17:40.124  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-26 14:17:40.124  6854  6869 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-26 14:17:40.124  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-26 14:17:40.124  1896  1896 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 14:17:40.124  6854  6869 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-26 14:17:40.124  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:40.124  6854  6869 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-26 14:17:40.124  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-26 14:17:40.124  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:40.124  6854  6869 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-26 14:17:40.124  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-26 14:17:40.134  6854  6869 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-26 14:17:40.134  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-26 14:17:40.134  6854  6869 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-26 14:17:40.134  1013  3038 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
08-26 14:17:40.134  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:40.134  1013  3119 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-26 14:17:40.134  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
08-26 14:17:40.134  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-26 14:17:40.134  6854  6869 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-26 14:17:40.134  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-26 14:17:40.134  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
08-26 14:17:40.134  1013  1539 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:40.134  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:40.134  1013  1539 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
08-26 14:17:40.134  6854  6869 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-26 14:17:40.134  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 14:17:40.134  6854  6869 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:40.134  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:40.134  1013  1539 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:40.134  6854  6869 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:40.134  1013  1539 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:40.134  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:40.134  1013  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-26 14:17:40.134  6854  6869 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:40.134  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-26 14:17:40.134  6854  6869 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-26 14:17:40.144  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:40.144  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:40.154  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,08-26 14:17:40.154  6854  6869 D BluetoothBondStateMachine: make
,08-26 14:17:40.154  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-26 14:17:40.154  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-26 14:17:40.154  6854  6869 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-26 14:17:40.154  6854  6876 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-26 14:17:40.154  1013  3038 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:40.154  1013  3038 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.154  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:40.154  1013  3038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:40.154  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:40.164  6854  6854 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-26 14:17:40.164  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-26 14:17:40.164  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-26 14:17:40.164  6854  6869 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-26 14:17:40.164  1013  3193 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:40.164  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.164  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:40.164  1013  3193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:40.164  6854  6854 D BtGatt.GattService: Received start request. Starting profile...
08-26 14:17:40.164  6854  6854 D BtGatt.GattService: start()
08-26 14:17:40.164  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
08-26 14:17:40.164  6854  6854 D BtGatt.GattService: start()
08-26 14:17:40.164  6854  6854 I bluedroid: get_profile_interface gatt
,08-26 14:17:40.164  6854  6854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
08-26 14:17:40.164  6854  6854 D BtGatt.AdvertiseManager: advertise manager created
,08-26 14:17:40.164  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-26 14:17:40.164  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-26 14:17:40.164  6854  6869 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-26 14:17:40.164  1013  1345 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:40.174  1013  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.174  1013  1345 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:40.174  1013  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:40.174  1013  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:40.174  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-26 14:17:40.174  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-26 14:17:40.174  6854  6869 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-26 14:17:40.174  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:40.174  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.174  1013  1026 W ActivityManager: userId = 0, bbcId = -10000,
08-26 14:17:40.174  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:40.174  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:40.184  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-26 14:17:40.184  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-26 14:17:40.184  6854  6869 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-26 14:17:40.184  6854  6854 D BtGatt.GattService: mStartError = false
,08-26 14:17:40.184  6854  6854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:40.184  1013  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:40.184  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.184  6854  6854 D HeadsetService: Received start request. Starting profile...
08-26 14:17:40.184  6854  6854 D HeadsetService: start()
,08-26 14:17:40.184  1013  1541 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:40.184  1013  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:40.184  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:40.184  6854  6854 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-26 14:17:40.184  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-26 14:17:40.184  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-26 14:17:40.184  6854  6869 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-26 14:17:40.184  1013  1345 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:40.184  1013  1345 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.194  6854  6854 D HeadsetStateMachine: make
08-26 14:17:40.194  1013  1345 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:40.194  1013  1345 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:40.194  1013  1345 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:40.194  6854  6854 E HeadsetStateMachine: # of Max HF connection is 2
,08-26 14:17:40.194  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-26 14:17:40.194  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-26 14:17:40.194  6854  6869 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-26 14:17:40.194  1013  1261 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:40.194  1013  1261 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.194  1013  1261 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:40.194  1013  1261 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:40.194  1013  1261 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:40.204  1013  3038 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-26 14:17:40.204  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-26 14:17:40.204  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-26 14:17:40.204  6854  6869 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-26 14:17:40.204  1013  3038 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.204  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:40.204  1013  3038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:40.204  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 14:17:40.204  1013  3193 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
08-26 14:17:40.204  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.204  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:40.204  1013  3193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:40.204  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,08-26 14:17:40.204  1013  1540 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:40.204  6854  6854 I bluedroid: get_profile_interface handsfree
08-26 14:17:40.204  1013  1540 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,08-26 14:17:40.204  1013  1540 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:40.204  1013  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:40.214  1013  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:40.214  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 14:17:40.214  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-26 14:17:40.214  6854  6869 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-26 14:17:40.214  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-26 14:17:40.214  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:40.214  6854  6869 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-26 14:17:40.214  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,08-26 14:17:40.214  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-26 14:17:40.214  6854  6869 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,08-26 14:17:40.214  6854  6869 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-26 14:17:40.214  6854  6869 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-26 14:17:40.214  6854  6869 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-26 14:17:40.214  6854  6869 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-26 14:17:40.234  6854  6854 I DualScoManager: Instantiating Dual Sco Manager
08-26 14:17:40.234  6854  6854 I DualScoManager: Set HeadsetServiceHelper
08-26 14:17:40.234  6854  6854 D BluetoothAtMessage: createCMTIContentObservers
,08-26 14:17:40.234  1013  1345 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-26 14:17:40.234  1013  1345 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:40.234  1013  1345 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:40.234  1013  1345 D SettingsProvider: selectionArgs: false
08-26 14:17:40.234  1013  1345 D SettingsProvider: selectionArgs: 1002
08-26 14:17:40.234  1013  1345 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:40.234  1013  1345 D SettingsProvider: ret = -1
,08-26 14:17:40.234  6854  6880 D HeadsetStateMachine: Enter Disconnected: -2
,08-26 14:17:40.234  6854  6854 D HeadsetService: mStartError = false
,08-26 14:17:40.234  6854  6854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:40.244  6854  6854 D A2dpService: Received start request. Starting profile...
08-26 14:17:40.244  6854  6854 D A2dpService: start()
,08-26 14:17:40.244  6854  6880 D HeadsetStateMachine: Clear mHeadsetBrsf
08-26 14:17:40.244  6854  6880 D HeadsetStateMachine: map size, before remove : 0
08-26 14:17:40.244  6854  6880 D HeadsetStateMachine: map size, after remove: 0
,08-26 14:17:40.244  6854  6854 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-26 14:17:40.244  6854  6854 I bluedroid: get_profile_interface avrcp
,08-26 14:17:40.254  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-26 14:17:40.254  6854  6854 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-26 14:17:40.254  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:40.274  6854  6854 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-26 14:17:40.274  6854  6883 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-26 14:17:40.274  6854  6854 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-26 14:17:40.274  6854  6854 D A2dpStateMachine: make
,08-26 14:17:40.284  6854  6854 I bluedroid: get_profile_interface a2dp
,08-26 14:17:40.284  6854  6885 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-26 14:17:40.284  6854  6854 E bt-btif : warning : media task started media_task_refcnt 1 
,08-26 14:17:40.284  6854  6854 D A2dpService: mStartError = false
08-26 14:17:40.284  6854  6854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:40.284  6854  6884 D A2dpStateMachine: Enter Disconnected: -2
,08-26 14:17:40.284  6854  6854 I BluetoothHidServiceJni: classInitNative: succeeds
,08-26 14:17:40.294  6854  6883 D BluetoothMediaBrowser: no now playing list
,08-26 14:17:40.294  6854  6883 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-26 14:17:40.294  6854  6854 D HidService: Received start request. Starting profile...
08-26 14:17:40.294  6854  6854 D HidService: start()
08-26 14:17:40.294  6854  6854 I bluedroid: get_profile_interface hidhost
08-26 14:17:40.294  6854  6854 D HidService: setHidService(): set to: null
08-26 14:17:40.294  6854  6854 D HidService: mStartError = false
08-26 14:17:40.294  6854  6854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
08-26 14:17:40.294  6854  6854 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-26 14:17:40.294  6854  6854 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-26 14:17:40.294  6854  6854 D HealthService: Received start request. Starting profile...
,08-26 14:17:40.294  6854  6854 D HealthService: start()
,08-26 14:17:40.294  6854  6854 I bluedroid: get_profile_interface health
,08-26 14:17:40.294  6854  6854 D HealthService: mStartError = false
08-26 14:17:40.294  6854  6854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:40.294  6854  6854 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-26 14:17:40.304  6854  6854 D PanService: Received start request. Starting profile...
,08-26 14:17:40.304  6854  6854 D PanService: start()
08-26 14:17:40.304  6854  6854 D BluetoothPanServiceJni: initializeNative(L110): pan
08-26 14:17:40.304  6854  6854 I bluedroid: get_profile_interface pan
,08-26 14:17:40.304  6854  6854 D PanService: mStartError = false
08-26 14:17:40.304  6854  6854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:40.304  6854  6854 D BluetoothMapService: Received start request. Starting profile...
08-26 14:17:40.304  6854  6854 D BluetoothMapService: start()
,08-26 14:17:40.304  6854  6854 D BluetoothMapService: mStartError = false
,08-26 14:17:40.304  6854  6854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:40.304  6854  6854 D HeadsetStateMachine: Try to query the phonestate on bind
,08-26 14:17:40.314  1431  1439 I Telecom : BluetoothPhoneService: queryPhoneState
,08-26 14:17:40.314  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,08-26 14:17:40.314  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-26 14:17:40.314  1431  1439 I Telecom : BluetoothPhoneService: Result of Message : true
,08-26 14:17:40.314  6854  6854 D HeadsetStateMachine: Proxy object connected
,08-26 14:17:40.314  6854  6854 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-26 14:17:40.314  6854  6880 D HeadsetStateMachine: Disconnected process message: 11
,08-26 14:17:40.314  6854  6854 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-26 14:17:40.314  6854  6854 D SapService: Received start request. Starting profile...
,08-26 14:17:40.314  6854  6854 D SapService: start()
08-26 14:17:40.314  6854  6854 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-26 14:17:40.314  6854  6854 I bluedroid: get_profile_interface sap
08-26 14:17:40.314  6854  6854 D SapService: mStartError = false
08-26 14:17:40.314  6854  6854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
08-26 14:17:40.314  6854  6854 D HeadsetPhoneState: sendDeviceDataStateChanged
08-26 14:17:40.314  6854  6854 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-26 14:17:40.314  6854  6854 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-26 14:17:40.314  6854  6854 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-26 14:17:40.314  6854  6854 D BluetoothA2dp: Proxy object connected
08-26 14:17:40.314  6854  6854 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-26 14:17:40.314  6854  6854 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,08-26 14:17:40.324  6854  6880 D HeadsetStateMachine: Disconnected process message: 18
08-26 14:17:40.324  6854  6880 D HeadsetStateMachine: Disconnected process message: 10
08-26 14:17:40.324  6854  6880 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-26 14:17:40.324  6854  6880 D HeadsetStateMachine: Disconnected process message: 11
,08-26 14:17:40.324  6854  6854 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-26 14:17:40.324  6854  6854 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-26 14:17:40.324  6854  6854 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-26 14:17:40.344  6854  6854 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-26 14:17:40.344  6854  6854 E BluetoothAdapterService(88170342): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-26 14:17:40.354  6854  6869 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-26 14:17:40.354  6854  6869 I bluedroid: enable
,08-26 14:17:40.354  6854  6869 I bt_hci_bdroid: init
,08-26 14:17:40.354  6854  6869 I bt_vendor: bt-vendor : init
,08-26 14:17:40.354  6854  6869 I bt_vendor: bt-vendor : get_bt_soc_type
08-26 14:17:40.354  6854  6869 E bt_vendor: get_bt_soc_type: Failed to get soc type
,08-26 14:17:40.354  6854  6869 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
08-26 14:17:40.354  6854  6869 D bt_userial_mct: userial_init
08-26 14:17:40.354  6854  6890 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-26 14:17:40.354  6854  6869 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-26 14:17:40.354  6854  6869 I bt_vendor: Starting hciattach daemon
,08-26 14:17:40.354  6854  6869 I bt_vendor: try to set false
,08-26 14:17:40.354  6854  6869 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,08-26 14:17:40.354  6854  6869 I bt_vendor: Starting hciattach daemon
08-26 14:17:40.364  6854  6869 I bt_vendor: try to set true
,08-26 14:17:40.374  6894  6894 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-26 14:17:40.434  6900  6900 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,08-26 14:17:40.444  6901  6901 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 14:17:40.464  6903  6903 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 14:17:40.474  6904  6904 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,08-26 14:17:40.484  6905  6905 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,08-26 14:17:40.484  6906  6906 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,08-26 14:17:40.814  6909  6909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,08-26 14:17:40.824  6910  6910 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,08-26 14:17:40.874  6854  6869 I bt_vendor: bluetooth satus is on,
08-26 14:17:40.874  6854  6892 D bt_userial_mct: userial_open(port:0)
,08-26 14:17:40.874  6854  6892 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-26 14:17:40.874  6854  6892 I bt_vendor: Done intiailizing UART,
,08-26 14:17:40.874  6854  6892 I bt_vendor: Done intiailizing UART,
08-26 14:17:40.874  6854  6892 I bt_userial_mct: CMD=65, EVT=65, ACL_Out=66, ACL_In=66
08-26 14:17:40.874  6854  6892 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
08-26 14:17:40.874  6854  6912 D bt_userial_mct: Entering userial_read_thread(),
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_HCI
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_L2CAP,
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_AVRC
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_A2D
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_BNEP,
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_BTM
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_GAP
,08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_PAN
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_SAP
,08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_SDP
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_GATT
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_SMP,
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_BTIF
08-26 14:17:40.884  6854  6890 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,
,08-26 14:17:40.994  6854  6890 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,08-26 14:17:40.994  6854  6890 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3ff26e9 
,08-26 14:17:40.994  6854  6890 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3ff26e9 
,08-26 14:17:41.004  6854  6872 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,08-26 14:17:41.014  6854  6872 E bt-btif : Calling BTA_HhEnable,
08-26 14:17:41.014  6854  6872 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-26 14:17:41.014  6854  6872 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
08-26 14:17:41.014  6854  6872 E BluetoothServiceJni: populateRssiValuesNative
,08-26 14:17:41.014  6854  6872 I bluedroid: getModelRssiValues
08-26 14:17:41.014  6854  6872 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-26 14:17:41.014  6854  6872 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-26 14:17:41.014  1013  1013 D SettingsProvider: name = bluetooth_name
,08-26 14:17:41.014  6854  6872 D BluetoothAdapterProperties: Name is: A5-1
,08-26 14:17:41.024  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:41.024  6854  6872 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,08-26 14:17:41.024  6854  6872 D BluetoothAdapterProperties: Scan Mode:20
,08-26 14:17:41.024  6854  6872 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 14:17:41.024  6854  6872 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,08-26 14:17:41.024  6854  6872 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-26 14:17:41.024  6854  6872 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-26 14:17:41.024  6854  6872 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-26 14:17:41.024  6854  6872 E bt-btif : btif_sock_init: !vhci_init
,08-26 14:17:41.024  6854  6872 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-26 14:17:41.024  6854  6872 D IOP_DB_BT: db_open: db_open : handle 3028226064l, read 13894 bytes onto local cache
,08-26 14:17:41.034  6854  6872 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-26 14:17:41.034  6854  6872 D IOP_DB_BT: db_query: result 1
,08-26 14:17:41.034  6854  6872 I         : iop_db_open: iop_db_open status 0
,08-26 14:17:41.034  6854  6872 D bte_conf: Device ID record 1 : primary
,08-26 14:17:41.034  6854  6872 D bte_conf:   vendorId            = 0075
,08-26 14:17:41.034  6854  6872 D bte_conf:   vendorIdSource      = 0001
08-26 14:17:41.034  6854  6872 D bte_conf:   product             = 0100
,08-26 14:17:41.034  6854  6872 D bte_conf:   version             = 0200
08-26 14:17:41.034  6854  6912 E bt_mct  : hci lib postload completed
,08-26 14:17:41.034  6854  6872 D bte_conf:   clientExecutableURL = 
,08-26 14:17:41.034  6854  6872 D bte_conf:   serviceDescription  = 
08-26 14:17:41.034  6854  6872 D bte_conf:   documentationURL    = 
,08-26 14:17:41.034  6854  6872 D bte_conf: bte_load_did_conf no section named DID2.
,08-26 14:17:41.034  6854  6872 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-26 14:17:41.044  6854  6869 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-26 14:17:41.044  6854  6869 D BluetoothAdapterProperties: ScanMode =  20
,08-26 14:17:41.044  6854  6869 D BluetoothAdapterProperties: State =  11
,08-26 14:17:41.044  1013  1261 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-26 14:17:41.044  6854  6869 D BluetoothAdapterProperties: Setting state to 12
08-26 14:17:41.044  6854  6869 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-26 14:17:41.054  6854  6872 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
08-26 14:17:41.054  6854  6872 D BluetoothAdapterProperties: Scan Mode:21
08-26 14:17:41.054  6854  6872 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-26 14:17:41.054  1013  3038 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-26 14:17:41.054  1013  3038 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-26 14:17:41.054  1013  3038 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-26 14:17:41.054  1013  3038 D SettingsProvider: selectionArgs: false
08-26 14:17:41.054  1013  3038 D SettingsProvider: selectionArgs: 1002
08-26 14:17:41.054  1013  3038 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-26 14:17:41.054  1013  3038 D SettingsProvider: ret = -1
,08-26 14:17:41.054  6854  6869 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-26 14:17:41.054  6854  6869 D BluetoothAdapterService: updateAdapterState state is 12
,08-26 14:17:41.054  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:41.054  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:41.054  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:41.054  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:41.054  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:41.054  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:41.054  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:41.054  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:41.054  1013  3040 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-26 14:17:41.054  1013  3040 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.064  1013  3040 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:41.064  1013  3040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:41.064  1013  3040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.064  6854  6869 D BluetoothAdapterService: Autoconnection is available 
08-26 14:17:41.064  6854  6869 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-26 14:17:41.064  6854  6869 D BluetoothAdapterService: starting service from this receiver
,08-26 14:17:41.064  1013  1539 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:41.064  1013  1539 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.064  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=true
08-26 14:17:41.064  1013  1042 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:41.064  1013  1539 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.064  1013  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:41.064  1013  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.074  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:41.074  6854  6869 I BluetoothAdapterState: Entering On State from state = 11
,08-26 14:17:41.074  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 14:17:41.074  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.074  1323  1341 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:41.074  1013  1013 D BluetoothA2dp: Proxy object connected
,08-26 14:17:41.074  1323  1341 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:41.084  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-26 14:17:41.084  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.084  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.084  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.084  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.084  1323  1323 D BluetoothA2dp: Proxy object connected
08-26 14:17:41.084  1323  1323 D A2dpProfile: Bluetooth service connected
,08-26 14:17:41.084  1323  1341 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:41.084  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:41.084  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:41.094  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:41.094  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.094  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.094  1323  1341 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:41.094  6328  6339 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:41.094  6328  6339 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:41.094  1443  1454 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:41.094  1443  1454 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:41.094  1431  2763 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:41.094  1431  2763 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:41.094  6167  6175 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:41.094  6167  6175 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:41.094  1431  1440 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:41.094  6854  6854 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-26 14:17:41.104  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:41.104  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:41.104  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.104  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.104  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.104  1431  1440 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:41.104  1431  1439 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:41.104  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-26 14:17:41.104  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:41.104  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:41.104  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.104  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.104  1431  1439 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:41.104  6854  6862 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:41.104  1905  1922 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:41.104  1905  1922 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:41.114  2887  2897 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:41.114  6854  6854 I BluetoothPbapService: Handler(): got msg=1
,08-26 14:17:41.114  1013  1042 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:41.114  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:41.114  1323  1323 D HeadsetProfile: Bluetooth service connected
,08-26 14:17:41.114  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.114  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.114  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
08-26 14:17:41.114  1013  1539 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 14:17:41.114  2887  2897 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 14:17:41.114  2887  2943 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-26 14:17:41.114  2887  2943 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:41.124  1013  1042 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-26 14:17:41.124  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
08-26 14:17:41.124  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.124  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.124  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.124  1013  1042 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
08-26 14:17:41.124  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:41.124  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:41.124  1013  1042 E BluetoothHeadset: BluetoothHeadset service is binded
08-26 14:17:41.124  1323  6618 D BluetoothPbap: onBluetoothStateChange: up=true
,08-26 14:17:41.124  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
08-26 14:17:41.124  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.124  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.124  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.124  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.124  6854  6916 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-26 14:17:41.124  1323  1341 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-26 14:17:41.124  2887  2887 D BluetoothA2dp: Proxy object connected
,08-26 14:17:41.124  1323  1323 D BluetoothPbap: Proxy object connected
08-26 14:17:41.124  1323  1323 D PbapServerProfile: Bluetooth service connected
,08-26 14:17:41.134  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
08-26 14:17:41.134  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.134  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.134  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.134  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.134  6854  6916 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 14:17:41.134  6854  6862 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:41.134  6854  6862 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:41.134  6854  6916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-26 14:17:41.134  2887  2897 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:41.134  2887  2897 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:41.134  1323  1323 D BluetoothInputDevice: Proxy object connected
08-26 14:17:41.134  1323  1323 D HidProfile: Bluetooth service connected
,08-26 14:17:41.134  6854  6916 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,08-26 14:17:41.134  6854  6916 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:41.134  6854  6916 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:41.134  6854  6916 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a119613
08-26 14:17:41.134  6854  6916 D BluetoothSocket: channel: 19
08-26 14:17:41.134  6854  6916 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-26 14:17:41.134  1431  2763 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:41.134  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:41.134  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
08-26 14:17:41.134  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.134  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.134  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.134  1431  2763 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:41.134  1175  1186 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:41.134  1175  1186 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,08-26 14:17:41.134  1323  1336 D BluetoothPan: Binding service...
,08-26 14:17:41.144  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 14:17:41.144  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.144  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.144  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:41.144  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.144  1323  1341 D Bluetoothsap: onBluetoothStateChange: up=true
08-26 14:17:41.144  1323  1341 D Bluetoothsap: Binding service...
,08-26 14:17:41.144  1323  1323 D BluetoothPan: BluetoothPAN Proxy object connected
08-26 14:17:41.144  1323  1323 D PanProfile: Bluetooth service connected
,08-26 14:17:41.144  1323  1341 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-26 14:17:41.144  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-26 14:17:41.144  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
08-26 14:17:41.144  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:41.144  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.144  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.144  1323  1341 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-26 14:17:41.154  1323  1341 D BluetoothMap: onBluetoothStateChange: up=true
08-26 14:17:41.154  1323  1323 D Bluetoothsap: BluetoothSAP Proxy object connected
08-26 14:17:41.154  1323  1323 D SapProfile: Bluetooth service connected
08-26 14:17:41.154  1323  1323 D Bluetoothsap: getConnectedDevices()
,08-26 14:17:41.154  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-26 14:17:41.154  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.154  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.154  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.154  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.154  1323  1323 D BluetoothMap: Proxy object connected
08-26 14:17:41.154  1323  1323 D MapProfile: Bluetooth service connected
08-26 14:17:41.154  1323  1323 D BluetoothMap: getConnectedDevices()
,08-26 14:17:41.154  1013  1042 D BluetoothPan: Binding service...
08-26 14:17:41.154  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-26 14:17:41.154  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.154  1013  1013 D BluetoothPan: BluetoothPAN Proxy object connected
,08-26 14:17:41.154  1455  1474 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,08-26 14:17:41.154  1013  1042 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-26 14:17:41.154  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,08-26 14:17:41.154  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.154  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.154  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.154  1455  1474 E BluetoothHeadset: BluetoothHeadset service is binded
,08-26 14:17:41.164  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:41.164  1013  1042 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 14:17:41.164  1455  2158 D BluetoothAdapter: onBluetoothStateChange: up=true
,08-26 14:17:41.164  1455  2158 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 14:17:41.164  1323  1336 D BluetoothAdapter: onBluetoothStateChange: up=true
08-26 14:17:41.164  1323  1336 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
08-26 14:17:41.164  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-26 14:17:41.164  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,08-26 14:17:41.164  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:41.164  1013  1013 I InputMethodManagerService: [BT Setting State] State =12
08-26 14:17:41.164  1013  1013 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-26 14:17:41.164  1431  1431 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3cc51195, true
,08-26 14:17:41.164  1431  1431 D BluetoothHeadset: registerMessageListener
,08-26 14:17:41.174  1175  1175 D BluetoothTile:  onBluetoothStateChange:
,08-26 14:17:41.174  1175  1175 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-26 14:17:41.174  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:41.174  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:41.174  1175  1175 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:41.174  1175  1175 D BluetoothTile:  getBluetoothState : 12
,08-26 14:17:41.174  1175  1711 D BluetoothTile:  handleUpdatestate:false name:null
,08-26 14:17:41.184  1896  1896 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-26 14:17:41.184  1323  1323 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:41.184  1013  1026 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:41.184  1013  1314 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-26 14:17:41.184  1175  1175 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,08-26 14:17:41.184  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:41.194  1013  3042 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-26 14:17:41.194  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.194  6854  6873 D HeadsetService: registerMessageListener
08-26 14:17:41.194  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.194  1013  3042 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:41.194  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:41.194  6854  6873 D HeadsetService: registerMessageListener
,08-26 14:17:41.194  6854  6880 D HeadsetStateMachine: Disconnected process message: 70
08-26 14:17:41.194  6854  6880 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@ae8e050
,08-26 14:17:41.194  1323  1323 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
08-26 14:17:41.194  1323  1323 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
08-26 14:17:41.194  1431  1431 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
08-26 14:17:41.194  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-26 14:17:41.194  1323  1323 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-26 14:17:41.194  1323  1323 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-26 14:17:41.194  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,08-26 14:17:41.194  1431  1431 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
08-26 14:17:41.194  1431  1431 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-26 14:17:41.194  6854  6917 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-26 14:17:41.204  6854  6880 D HeadsetStateMachine: Disconnected process message: 9
08-26 14:17:41.204  6854  6880 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-26 14:17:41.204  1323  1323 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-26 14:17:41.204  1013  3040 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-26 14:17:41.204  1013  3040 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.204  1013  3040 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:41.204  1013  3040 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.204  1013  3040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,08-26 14:17:41.214   281   281 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-26 14:17:41.214   281   281 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-26 14:17:41.214   281   281 V voice   : voice_set_parameters: exit with code(-2)
08-26 14:17:41.214   281   281 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-26 14:17:41.214   281   281 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-26 14:17:41.214   281   281 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-26 14:17:41.214   281   281 V audio_hw_primary: adev_set_parameters: exit
08-26 14:17:41.214  6854  6880 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-26 14:17:41.214  6854  6917 D BluetoothSocket: bindListen(): myUserId = 0
08-26 14:17:41.214  6854  6917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:41.214  6854  6917 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[76]}
08-26 14:17:41.214  6854  6917 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:41.214  6854  6917 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:41.214  6854  6917 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27601249
,08-26 14:17:41.224  6854  6917 D BluetoothSocket: channel: 5
,08-26 14:17:41.224  1323  1323 D DockEventReceiver: finishStartingService: stopping service
,08-26 14:17:41.224  1323  1323 D BluetoothNotiBroadcastReceiver: onReceive
,08-26 14:17:41.224  1175  1175 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-26 14:17:41.224  1175  1175 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,08-26 14:17:41.234  6854  6854 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:41.244  6854  6854 D BtConfig.SecureMode: isSecureModeOn:false
,08-26 14:17:41.244  1013  1541 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-26 14:17:41.244  1013  1541 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.244  1013  1541 W ActivityManager: userId = 0, bbcId = -10000,
08-26 14:17:41.244  1013  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:41.244  1013  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,08-26 14:17:41.264  1905  1905 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-26 14:17:41.264  1013  3040 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-26 14:17:41.264  1013  3040 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,08-26 14:17:41.264  1013  3040 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:41.264  1013  3040 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:41.264  1013  3040 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:41.274  1905  6924 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-26 14:17:41.274  1013  1713 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-26 14:17:41.274  1905  1905 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-26 14:17:41.284  1013  3038 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:41.284  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:41.284  1013  3038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:41.284  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:41.294  6854  6927 D BluetoothSocket: bindListen(): myUserId = 0
,08-26 14:17:41.294  6854  6927 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-26 14:17:41.294  6854  6927 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
,08-26 14:17:41.294  6854  6927 D BluetoothSocket: bindListen(), new LocalSocket 
08-26 14:17:41.294  6854  6927 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-26 14:17:41.294  6854  6927 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1683b48b
08-26 14:17:41.294  6854  6927 D BluetoothSocket: channel: 12
08-26 14:17:41.294  6854  6927 I BtOppRfcommListener: Accept thread started.
,08-26 14:17:41.304  1013  1261 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-26 14:17:41.304  1013  1261 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:41.304  1013  1261 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-26 14:17:41.304  1013  1261 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-26 14:17:41.314  1905  6924 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-26 14:17:41.914  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:41.914  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:41.914  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:41.914  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-26 14:17:41.914  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:41.914  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:41.914  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:41.914  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:41.914  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:41.914  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:41.914  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2eb4e376 added. We now have 8 listener(s)
,08-26 14:17:41.914  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:41.914  1013  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 14:17:41.914  1013  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 14:17:41.914  1013  1026 D SecContentProvider2: mCursor = null
,08-26 14:17:41.914  1013  1026 D WifiService: setWifiEnabled: false pid=6167, uid=10155
,08-26 14:17:41.914  1013  1026 D SettingsProvider: name = wifi_on
,08-26 14:17:41.924  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:41.924  1013  3038 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-26 14:17:41.924  1013  3038 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-26 14:17:41.924  1013  3038 D SecContentProvider2: mCursor = null
,08-26 14:17:41.924  1013  3038 D WifiService: setWifiEnabled: true pid=6167, uid=10155
,08-26 14:17:41.934  1013  3038 W ActivityManager: Permission Denial: getCurrentUser() from pid=6167, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,08-26 14:17:41.934  1013  3038 W WifiService: Failed getting userId using ActivityManagerNative
08-26 14:17:41.934  1013  3038 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6167, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
08-26 14:17:41.934  1013  3038 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
08-26 14:17:41.934  1013  3038 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
08-26 14:17:41.934  1013  3038 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
08-26 14:17:41.934  1013  3038 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-26 14:17:41.934  1013  3038 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-26 14:17:41.934  1013  3038 D SettingsProvider: name = wifi_on
,08-26 14:17:41.944  1013  1121 E WifiHW  : ##################### set firmware type 0 #####################,
,08-26 14:17:42.024   286   286 E SMD     : DCD OFF
,08-26 14:17:42.304  1013  1040 D Tethering: interfaceAdded wlan0
,08-26 14:17:42.304  1013  1126 E Tethering: No numeric data
,08-26 14:17:42.304  1013  1126 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-26 14:17:42.314  1013  1126 D Tethering: clearTetheredNotification()
,08-26 14:17:42.314  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit,
08-26 14:17:42.314  1013  1118 V NetworkStats: performPollLocked(flags=0x1)
,08-26 14:17:42.314  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:42.314  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:42.314  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 14:17:42.314  1175  1175 D HotspotTile: updateTetherState():false, false
,08-26 14:17:42.314  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 14:17:42.314  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:42.324  1013  1118 V NetworkStats: performPollLocked() took 7ms
08-26 14:17:42.324  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:42.324  1013  1126 D Tethering: InitialState.processMessage what=4
,08-26 14:17:42.324  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 14:17:42.324  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:42.324  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:42.324  1013  1126 E Tethering: No numeric data
,08-26 14:17:42.324  1013  1126 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-26 14:17:42.324  1013  1126 D Tethering: clearTetheredNotification()
,08-26 14:17:42.324  1013  1040 D Tethering: interfaceAdded p2p0
,08-26 14:17:42.324  1013  1040 D Tethering: p2p0 is not a tetherable iface, ignoring
,08-26 14:17:42.324  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:42.324  1175  1175 D HotspotTile: updateTetherState():false, false
,08-26 14:17:42.324  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:42.324  1013  1118 V NetworkStats: performPollLocked(flags=0x1)
,08-26 14:17:42.334  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 14:17:42.334  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 14:17:42.334  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:42.334  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:42.334  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 14:17:42.334  1013  1118 V NetworkStats: performPollLocked() took 6ms
08-26 14:17:42.334  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:42.334  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:42.334  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:42.344   276  1012 I WifiHW  : wifi_change_fw_path(): fwpath = sta
,08-26 14:17:42.344   276  1012 D SoftapController: Softap fwReload - Ok
,08-26 14:17:42.344   276  1012 D CommandListener: Setting iface cfg
08-26 14:17:42.344   276  1012 D CommandListener: Trying to bring down wlan0
,08-26 14:17:42.344   276  1012 D CommandListener: Clearing all IP addresses on wlan0
,08-26 14:17:42.354  1013  1121 E WifiHW  : supplicant_name : p2p_supplicant
,08-26 14:17:42.394  6941  6941 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-26 14:17:42.394  6941  6941 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-26 14:17:42.394  6941  6941 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage,
,08-26 14:17:42.414  6941  6941 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
08-26 14:17:42.414   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6941
08-26 14:17:42.414   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,08-26 14:17:42.414  6941  6941 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-26 14:17:42.414  6941  6941 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:42.414  6941  6941 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
08-26 14:17:42.414  6941  6941 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
08-26 14:17:42.414   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6941
08-26 14:17:42.414   395   395 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106,
,08-26 14:17:42.454  1013  1121 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-26 14:17:42.454  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:42.454  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-26 14:17:42.454  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:42.454  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:42.454  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:42.454  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:42.454  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:42.454  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-26 14:17:42.464  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:42.464  1013  3193 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:42.464  1013  3193 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:42.464  1013  3193 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:42.464  1013  3193 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:42.464  1013  3193 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:42.464  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-26 14:17:42.474  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-26 14:17:42.474  3651  3651 I Hs20UtilService: Starting #17
08-26 14:17:42.474  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 14:17:42.474  3651  3690 I Hs20UtilService: Message received 5011
08-26 14:17:42.474  1175  1175 D HotspotTile: onReceive : 2, 0
08-26 14:17:42.474  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-26 14:17:42.474  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:42.474  6584  6584 D SecurityLogAgent: StateMachine : Current State = 1
08-26 14:17:42.474  6584  6584 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:42.524  1013  1025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-26 14:17:42.524  1013  1025 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4183, temperature: 295, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,08-26 14:17:42.524  1013  1025 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
08-26 14:17:42.524  1013  1025 D BatteryService: stay LED for charging
,08-26 14:17:42.524  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-26 14:17:42.534  1013  1013 I MotionRecognitionService: Plugged
,08-26 14:17:42.534  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,08-26 14:17:42.534  1175  1175 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-26 14:17:42.534  1175  1175 D KeyguardUpdateMonitor: handleBatteryUpdate
08-26 14:17:42.534  1416  1416 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-26 14:17:42.534  1416  1416 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
,08-26 14:17:42.544  6854  6854 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-26 14:17:42.544  6854  6880 D HeadsetStateMachine: Disconnected process message: 10
,08-26 14:17:42.554  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-26 14:17:42.554  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
08-26 14:17:42.554  1175  1175 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,08-26 14:17:42.594   395   395 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,08-26 14:17:42.604  6941  6941 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed,
,08-26 14:17:42.664  6941  6941 I wpa_supplicant: Ctrl_iface: loading cred from phone,
08-26 14:17:42.664  6941  6941 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-26 14:17:42.684  6941  6941 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
,08-26 14:17:42.684   395   395 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6941
08-26 14:17:42.684   395   395 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-26 14:17:42.684  6941  6941 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running,
08-26 14:17:42.684  6941  6941 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:42.684  6941  6941 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:42.684  6941  6941 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
08-26 14:17:42.684  6941  6941 E wpa_supplicant: SIM READ ERROR
08-26 14:17:42.684  6941  6941 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 14:17:42.684  6941  6941 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:42.684  6941  6941 E wpa_supplicant: SIM READ ERROR
08-26 14:17:42.684  6941  6941 I wpa_supplicant: Blacklist: Clear (all) 
08-26 14:17:42.684  6941  6941 I wpa_supplicant: wpa_default_ap_write_once,
08-26 14:17:42.684  6941  6941 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 14:17:42.684  6941  6941 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-26 14:17:42.684  6941  6941 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-26 14:17:42.684  6941  6941 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:42.684  6941  6941 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-26 14:17:42.684  6941  6941 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 14:17:42.694  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false,
08-26 14:17:42.694  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:42.694  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,08-26 14:17:42.784  6941  6941 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,08-26 14:17:42.944  1013  2741 D SSRM:n  : SIOP:: AP = 340,
,08-26 14:17:42.974  6941  6941 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-26 14:17:42.974  6941  6941 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-26 14:17:42.984  6941  6941 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
,08-26 14:17:42.984   395   395 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6941
08-26 14:17:42.984   395   395 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-26 14:17:42.984  6941  6941 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-26 14:17:42.984  6941  6941 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:42.984  6941  6941 I wpa_supplicant: Ctrl_iface: loading cred from phone
,08-26 14:17:42.984  6941  6941 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,08-26 14:17:43.004  6941  6941 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
08-26 14:17:43.004   395   395 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6941
08-26 14:17:43.004   395   395 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-26 14:17:43.004  6941  6941 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
08-26 14:17:43.004  6941  6941 I wpa_supplicant: ssSupport state is = 1
08-26 14:17:43.004  6941  6941 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:43.004  6941  6941 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:43.004  6941  6941 E wpa_supplicant: SIM READ ERROR
08-26 14:17:43.004  6941  6941 I wpa_supplicant: wpa_default_ap_write_once
08-26 14:17:43.004  6941  6941 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-26 14:17:43.004  6941  6941 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-26 14:17:43.004  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false,
08-26 14:17:43.004  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:43.004  1013  1040 D Tethering: interfaceStatusChanged p2p0, false,
08-26 14:17:43.004  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
08-26 14:17:43.004  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
08-26 14:17:43.004  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:43.044  6941  6941 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
08-26 14:17:43.044  6941  6941 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-26 14:17:43.104  6941  6941 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-26 14:17:43.104  6941  6941 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
08-26 14:17:43.104  6941  6941 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 14:17:43.114  1013  1121 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-26 14:17:43.114  1013  1121 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,08-26 14:17:43.114  6941  6941 I wpa_supplicant: HOTSPOT20_ENABLE called
08-26 14:17:43.114  6941  6941 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-26 14:17:43.114  6941  6941 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-26 14:17:43.114  6941  6941 E wpa_supplicant: SIM READ ERROR
08-26 14:17:43.114  6941  6941 I wpa_supplicant: Blacklist: Clear (all) 
,08-26 14:17:43.134  6941  6941 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,08-26 14:17:43.144  1013  1121 D WifiNative-wlan0: callSECApiInt - ID [210]
08-26 14:17:43.144  6941  6941 I wpa_supplicant: Skip scan - bUseNetwork false
,08-26 14:17:43.144  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:43.144  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:43.144  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:43.144  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:43.144  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:43.144  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:43.144  1175  1175 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:43.154  1175  1175 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-26 14:17:43.154  1175  1175 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:43.154  1175  1711 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-26 14:17:43.154  1013  1121 D WifiConfigStore: Loading config and enabling all networks 
08-26 14:17:43.154  1175  1175 D HotspotTile: onReceive : 3, 0,
,08-26 14:17:43.164  1323  1323 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-26 14:17:43.164  1013  3038 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:43.164  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:,
08-26 14:17:43.164  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:43.164  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,08-26 14:17:43.164  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:43.164  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:43.164  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:43.164  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:43.164  6167  6167 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:43.164  1013  3038 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:43.164  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:43.164  1013  3038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:43.164  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
08-26 14:17:43.164  1013  1121 E WifiConfigStore: Not a HS20
08-26 14:17:43.164  3651  3651 I Hs20UtilService: Starting #18
08-26 14:17:43.174  3651  3690 I Hs20UtilService: Message received 5011
,08-26 14:17:43.174  6167  6167 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:43.174  1013  1121 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-26 14:17:43.174  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-26 14:17:43.174  6584  6584 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-26 14:17:43.174  6584  6584 D SecurityLogAgent: StateMachine : Current State = 1
08-26 14:17:43.174  6584  6584 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-26 14:17:43.184  1013  1121 D WifiNative-wlan0: callSECApiInt - ID [65]
,08-26 14:17:43.184  1013  1121 D WifiNative-wlan0: callSECApiBoolean - ID [13]
08-26 14:17:43.184  6941  6941 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-26 14:17:43.184  6941  6941 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 14:17:43.184  6941  6941 I wpa_supplicant: reset timer : RESET_TIMER 0
08-26 14:17:43.184  6941  6941 I wpa_supplicant: P2P: Current p2p state = IDLE
08-26 14:17:43.184  6941  6941 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-26 14:17:43.184  6941  6941 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-26 14:17:43.184  6941  6941 I wpa_supplicant: First Scan Start
,08-26 14:17:43.184  6941  6941 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-26 14:17:43.184  1013  1121 D WifiNative-wlan0: Setting external_sim to 1
,08-26 14:17:43.184  6429  6429 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-26 14:17:43.184  1013  1121 D WifiStateMachine: Setting OUI to DA-A1-19
08-26 14:17:43.184  1013  1121 I WifiNative-HAL: startHal
08-26 14:17:43.184  1013  1121 E wifi    : getStaticLongField sWifiHalHandle 0x9c48688c
08-26 14:17:43.184  1013  1121 I WifiNative-HAL: Could not start hal
,08-26 14:17:43.194  1013  1121 E WifiNative-wlan0: do suspend true
,08-26 14:17:43.194  1013  1120 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-26 14:17:43.194  1013  1121 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-26 14:17:43.194   276  1012 D CommandListener: Setting iface cfg
08-26 14:17:43.194   276  1012 D CommandListener: Trying to bring up p2p0
08-26 14:17:43.194  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 3
08-26 14:17:43.194  1013  1146 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:43.194  1013  1146 I WifiNative-HAL: startHal
08-26 14:17:43.194  1013  1146 E wifi    : getStaticLongField sWifiHalHandle 0x9d6389bc
08-26 14:17:43.194  1013  1146 I WifiNative-HAL: Could not start hal
08-26 14:17:43.194  1013  1146 E WifiScanningService: could not start HAL
,08-26 14:17:43.194  1013  1013 D RttService: SCAN_AVAILABLE : 3
,08-26 14:17:43.194  1013  1147 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-26 14:17:43.194  1013  1121 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-26 14:17:43.194  1013  1121 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 14:17:43.194  1013  1121 E WifiNative-wlan0: invaild command id : 215
08-26 14:17:43.204  1013  1120 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-26 14:17:43.204  1013  1121 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-26 14:17:43.204  1013  1120 D WifiP2pService: P2pEnablingState
08-26 14:17:43.204  1013  1121 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
08-26 14:17:43.204  1013  1120 D WifiP2pService: P2pEnablingState{ what=147457 }
08-26 14:17:43.204  1013  1121 E WifiNative-wlan0: invaild command id : 215
08-26 14:17:43.204  1013  1120 D WifiP2pService: P2p socket connection successful
08-26 14:17:43.204  1013  1123 E ConnectivityService: updateNetworkInfo()
08-26 14:17:43.204  1013  1120 D WifiP2pService: P2pEnabledState
,08-26 14:17:43.204  1013  1120 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-26 14:17:43.204  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-26 14:17:43.204  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-26 14:17:43.204  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-26 14:17:43.204  1013  1043 D WifiDisplayController: disconnect
08-26 14:17:43.204  1013  1043 D WifiDisplayController: updateConnection
08-26 14:17:43.204  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-26 14:17:43.204  6941  6941 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
08-26 14:17:43.204  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:43.204  6941  6941 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-26 14:17:43.214  1013  1120 D WifiNative-p2p0: p2pGetDeviceAddress
,08-26 14:17:43.214  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-26 14:17:43.214  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-26 14:17:43.214  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
08-26 14:17:43.214  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
08-26 14:17:43.214  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-26 14:17:43.214  6941  6941 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
08-26 14:17:43.214  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
08-26 14:17:43.214  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:43.214  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
08-26 14:17:43.214  1175  1175 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-26 14:17:43.214  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:43.214  1013  1350 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-26 14:17:43.214  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:43.214  1013  1121 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:43.214  1013  1121 D SecContentProvider2: mCursor = null
08-26 14:17:43.214  1013  1120 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
08-26 14:17:43.214  1175  1175 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-26 14:17:43.214  1323  3080 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:43.224  6384  6384 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:43.224  1013  1043 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  primary type: 10-0050F204-5
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  secondary type: null
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  wps: 0
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  grpcapab: 0
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  devcapab: 0
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  status: 3
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  wfdInfo: null
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  groupownerAddress: null
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  GOdeviceName: null
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  interfaceAddress: 
08-26 14:17:43.224  1013  1043 D WifiDisplayController:  SConnectInfo : null
08-26 14:17:43.224  1013  1120 D WifiP2pService: DeviceAddress: 7e:96:ac
,08-26 14:17:43.224  1013  1121 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:43.224  1013  1121 D SecContentProvider2: mCursor = null
08-26 14:17:43.224  6384  6384 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
08-26 14:17:43.224  6384  6384 D FileShare-Client: Outbound.stopDelayTimer - 
,08-26 14:17:43.234  6414  6414 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-26 14:17:43.244  1013  1120 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-26 14:17:43.244  1013  1120 D WifiP2pService: InactiveState
,08-26 14:17:43.244  1013  1120 D WifiP2pService: InactiveState{ what=143376 }
,08-26 14:17:43.244  1013  1120 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 14:17:43.244  6941  6941 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,08-26 14:17:43.244  1013  1120 D WifiP2pService: InactiveState{ what=143376 }
08-26 14:17:43.244  1013  1120 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-26 14:17:43.314  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
,08-26 14:17:43.314  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,08-26 14:17:43.314  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,08-26 14:17:43.954  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-26 14:17:43.954  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:43.954  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:43.954  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:43.954  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:43.954  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:43.954  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:43.954  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:43.954  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:43.954  6167  6220 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-26 14:17:43.964  6167  6220 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-26 14:17:43.964  6167  6220 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@1566e16 Bundle[{}]
,08-26 14:17:43.964  6167  6220 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-26 14:17:43.964  6167  6220 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-26 14:17:43.964  6167  6220 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-26 14:17:43.964  6167  6220 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-26 14:17:43.964  6167  6220 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-26 14:17:43.964  6167  6220 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-26 14:17:43.974  6167  6220 I System.out: Running OutgoingSocketThread
,08-26 14:17:43.974  6167  6948 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1158)
,08-26 14:17:43.984  6167  6948 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 46838
,08-26 14:17:43.984  6167  6948 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-26 14:17:44.454  6941  6941 I wpa_supplicant: nl80211: Received scan results (27 BSSes),
08-26 14:17:44.454  6941  6941 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-26 14:17:44.454  6941  6941 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,08-26 14:17:44.454  6941  6941 I wpa_supplicant: Trying to associate with  'G700'
,08-26 14:17:44.454  6941  6941 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-26 14:17:44.454  6941  6941 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
08-26 14:17:44.454  1013  6946 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,08-26 14:17:44.474  1013  1121 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 14:17:44.474  1013  1121 D SecContentProvider2: mCursor = null
,08-26 14:17:44.564  6941  6941 E wpa_supplicant: Cmd 35605 not handled
,08-26 14:17:44.574  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 14:17:44.574  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:44.574  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
08-26 14:17:44.574  6941  6941 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-26 14:17:44.574  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,08-26 14:17:44.574  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
08-26 14:17:44.574  6941  6941 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
,08-26 14:17:44.574  6941  6941 I wpa_supplicant: Associated with F4.99.3E,
08-26 14:17:44.574  6941  6941 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
08-26 14:17:44.574  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,08-26 14:17:44.574  6941  6941 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE,
,08-26 14:17:44.574  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, true
,08-26 14:17:44.574  1013  1040 D Tethering: interfaceStatusChanged wlan0, true,
08-26 14:17:44.574  1013  1126 E Tethering: No numeric data,
08-26 14:17:44.574  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-26 14:17:44.574  1013  1126 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-26 14:17:44.584  1013  1118 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:44.574  1013  1126 D Tethering: clearTetheredNotification()
08-26 14:17:44.584  1175  1175 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-26 14:17:44.584  6941  6941 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
08-26 14:17:44.584  1175  1175 D HotspotTile: updateTetherState():false, false
08-26 14:17:44.584  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:44.584  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox updated
,08-26 14:17:44.584  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 14:17:44.584  1013  1118 V NetworkStats: performPollLocked() took 8ms
08-26 14:17:44.584  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:44.584  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:44.584  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:44.594  1013  1121 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:44.594  1013  1121 D SecContentProvider2: mCursor = null
08-26 14:17:44.594  6941  6941 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,08-26 14:17:44.594  6941  6941 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-26 14:17:44.594  6941  6941 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-26 14:17:44.594  6941  6941 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-26 14:17:44.594  6941  6941 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-26 14:17:44.594  6941  6941 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-26 14:17:44.594  6941  6941 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
08-26 14:17:44.594  6941  6941 I wpa_supplicant: Blacklist: Clear (temp) 
08-26 14:17:44.594  6941  6941 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-26 14:17:44.604  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, true
08-26 14:17:44.604  1013  1040 D Tethering: interfaceStatusChanged wlan0, true
08-26 14:17:44.604  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,08-26 14:17:44.604  1013  1121 D WifiNative-wlan0: callSECApiVoid - ID [50]
,08-26 14:17:44.604  1013  1121 E WifiConfigStore: setLastSelectedConfiguration -1,
,08-26 14:17:44.614  1013  1121 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-26 14:17:44.614  1013  1123 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-26 14:17:44.614  1013  1123 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-26 14:17:44.614  1013  1123 E ConnectivityService: updateNetworkInfo()
,08-26 14:17:44.614  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 14:17:44.614  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 14:17:44.614  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:44.614  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:44.614  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:44.614  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,08-26 14:17:44.624  1013  1121 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-26 14:17:44.624  1013  1539 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:44.624  1013  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:44.624  1013  1539 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:44.624  1013  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:44.624  1013  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:44.634  3651  3651 I Hs20UtilService: Starting #19
,08-26 14:17:44.634  1013  1121 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-26 14:17:44.634  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 14:17:44.634  3651  3690 I Hs20UtilService: Message received 5007
,08-26 14:17:44.634  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 14:17:44.644   276  1012 D CommandListener: Setting iface cfg
,08-26 14:17:44.644  1013  1121 E WifiStateMachine: Start Dhcp Watchdog 2
,08-26 14:17:44.644  1013  1121 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 14:17:44.644  1013  1121 D SecContentProvider2: mCursor = null
,08-26 14:17:44.654  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-26 14:17:44.654  1013  1121 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-26 14:17:44.654  1013  1121 D SecContentProvider2: mCursor = null
,08-26 14:17:44.654  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED,
,08-26 14:17:44.654  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-26 14:17:44.654  1323  1323 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-26 14:17:44.664  1323  3080 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-26 14:17:44.664  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
08-26 14:17:44.664  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-26 14:17:44.664  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:44.664  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:44.664  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:44.664  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:44.674  1013  1121 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-26 14:17:44.674  1013  1121 D SecContentProvider2: mCursor = null
,08-26 14:17:44.674  1013  1121 E WifiNative-wlan0: do suspend false
,08-26 14:17:44.674  1013  1120 D WifiP2pService: InactiveState{ what=143375 },
08-26 14:17:44.674  1013  1120 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-26 14:17:44.884  6951  6951 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-26 14:17:44.894  6951  6951 I dhcpcd  : version 5.5.6 starting,
,08-26 14:17:44.894  6951  6951 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,08-26 14:17:44.954  6951  6951 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-26 14:17:44.954  6951  6951 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-26 14:17:44.954  6951  6951 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-26 14:17:44.954  6951  6951 I dhcpcd  : bssid match
08-26 14:17:44.954  6951  6951 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,08-26 14:17:44.984  6167  6220 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1159),
08-26 14:17:44.984  6167  6220 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1159)
,08-26 14:17:44.984  6167  6220 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1164)
,08-26 14:17:44.984  6167  6220 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-26 14:17:44.984  6167  6220 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1165),
08-26 14:17:44.984  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:44.984  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2396fd77 added. We now have 2 listener(s),
,08-26 14:17:44.994  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-26 14:17:44.994  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:17:44.994  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:17:44.994  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:44.994  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@298e5de4 added. We now have 9 listener(s)
,08-26 14:17:44.994  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:44.994  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,08-26 14:17:45.004  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-26 14:17:45.004  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:45.004  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:45.004  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:45.004  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:45.004  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:45.004  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:45.004  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:45.004  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:45.004  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:45.004  6167  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:45.004  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:45.014  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:45.014  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3603c102 added. We now have 3 listener(s)
,08-26 14:17:45.014  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:45.014  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 14:17:45.014  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:45.014  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:45.014  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:45.014  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2df3fa13 added. We now have 10 listener(s)
08-26 14:17:45.014  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:45.014  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:45.014  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:45.014  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:45.014  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:45.014  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.014  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:45.014  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:45.014  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2396fd77 removed from the list
08-26 14:17:45.014  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:45.014  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@298e5de4 removed from the list
08-26 14:17:45.014  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:45.014  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:45.014  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.014  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:45.014  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:45.014  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:45.014  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:45.014  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@298e5de4 not in the list
08-26 14:17:45.014  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.014  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:45.014  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:45.014  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:45.014  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:45.014  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2df3fa13 removed from the list,
08-26 14:17:45.024  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
,08-26 14:17:45.024  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:45.024  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:45.024  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-26 14:17:45.024  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3603c102 removed from the list
,08-26 14:17:45.024  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 14:17:45.024  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c57450 added. We now have 2 listener(s)
,08-26 14:17:45.024  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-26 14:17:45.024  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:17:45.024  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:45.024  6951  6951 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,08-26 14:17:45.024  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:45.024  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17631649 added. We now have 9 listener(s)
08-26 14:17:45.024  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:45.024  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:45.034   286   286 E SMD     : DCD OFF,
,08-26 14:17:45.034  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:45.034  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:45.034  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:45.034  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:45.034  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:45.034  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:45.034  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:45.034  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:45.034  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:45.034  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:45.034  6167  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:45.044  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
08-26 14:17:45.044  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:45.044  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331a246f added. We now have 3 listener(s)
,08-26 14:17:45.044  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:45.044  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-26 14:17:45.044  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-26 14:17:45.044  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-26 14:17:45.044  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:45.044  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1615857c added. We now have 10 listener(s)
08-26 14:17:45.044  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:45.044  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 14:17:45.044  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:45.044  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:45.044  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:45.044  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:45.054  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:45.054  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:45.054  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:45.064  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 14:17:45.064  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:45.064  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 14:17:45.064  6854  6874 D BtGatt.GattService: registerClient() - UUID=9ed63b42-a681-46be-9bef-8f8617bd30e0
,08-26 14:17:45.104  6854  6872 D BtGatt.GattService: onClientRegistered() - UUID=9ed63b42-a681-46be-9bef-8f8617bd30e0, clientIf=6
,08-26 14:17:45.104  6167  6175 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,08-26 14:17:45.114  6854  6873 D BtGatt.GattService: start scan with filters
,08-26 14:17:45.114  6854  6878 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:45.114  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-26 14:17:45.114  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-26 14:17:45.114  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-26 14:17:45.114  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:45.114  6854  6878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@5415f66
,08-26 14:17:45.124  6854  6872 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 14:17:45.124  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.124  6854  6878 D BtGatt.ScanManager: allow scan with filters
,08-26 14:17:45.124  6854  6878 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 14:17:45.124  6854  6878 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,08-26 14:17:45.124  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:45.124  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:45.124  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:45.124  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:45.134  6854  6872 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 14:17:45.134  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.134  6854  6878 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 14:17:45.134  6854  6878 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:45.134  6854  6872 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 14:17:45.134  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.134  6167  6220 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-26 14:17:45.134  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:45.134  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-26 14:17:45.134  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.134  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-26 14:17:45.134  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-26 14:17:45.134  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-26 14:17:45.134  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:45.134  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:45.134  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:45.134  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:45.144  6854  6874 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:45.144  6854  6872 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 14:17:45.144  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.144  6854  6873 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:45.144  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-26 14:17:45.144  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-26 14:17:45.144  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-26 14:17:45.144  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:45.144  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:45.154  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:45.154  6951  6951 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,08-26 14:17:45.154  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-26 14:17:45.154  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-26 14:17:45.154  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:45.154  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:45.164  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:45.164  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:45.164  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:45.164  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:45.164  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:45.164  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:45.164  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:45.164  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.164  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:45.164  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:45.164  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24c57450 removed from the list
08-26 14:17:45.164  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:45.164  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17631649 removed from the list
08-26 14:17:45.164  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:45.164  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:45.164  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.174  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:45.174  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-26 14:17:45.174  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:45.174  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:45.174  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17631649 not in the list
08-26 14:17:45.174  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:45.174  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:45.174  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:45.174  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:45.174  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:45.174  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1615857c removed from the list
08-26 14:17:45.174  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:45.174  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:45.174  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:45.174  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:45.174  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@331a246f removed from the list
,08-26 14:17:45.174  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:45.174  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f37d68 added. We now have 2 listener(s),
08-26 14:17:45.174  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 14:17:45.174  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66,
08-26 14:17:45.174  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:45.174  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:45.174  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25524581 added. We now have 9 listener(s)
,08-26 14:17:45.174  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:45.184  6854  6878 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 33
,08-26 14:17:45.184  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:45.184  6854  6878 D BtGatt.ScanManager: filter size is 1
08-26 14:17:45.184  6854  6878 D BtGatt.ScanManager: delete FilterIndex - 3
,08-26 14:17:45.184  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:45.194  6854  6872 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
08-26 14:17:45.194  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:45.194  6854  6878 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:45.194  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:45.194  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:45.194  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:45.194  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:45.194  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:45.194  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:45.194  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:45.194  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:45.194  6854  6872 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,08-26 14:17:45.194  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:45.194  6854  6878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 14:17:45.194  6854  6872 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
08-26 14:17:45.194  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.194  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
08-26 14:17:45.194  6167  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
08-26 14:17:45.194  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:45.194  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e0c3267 added. We now have 3 listener(s)
,08-26 14:17:45.204  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,08-26 14:17:45.204  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:45.204  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:45.204  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:45.204  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25370814 added. We now have 10 listener(s)
08-26 14:17:45.204  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:45.204  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:45.204  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:45.204  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:45.204  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:45.204  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:45.204  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:45.204  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:45.214  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:45.214  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:45.214  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-26 14:17:45.214  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-26 14:17:45.214  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-26 14:17:45.214  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:45.214  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 14:17:45.224  6854  6873 D BtGatt.GattService: registerClient() - UUID=58ad2041-568e-4e68-a407-4039270e7af5
,08-26 14:17:45.274  6854  6872 D BtGatt.GattService: onClientRegistered() - UUID=58ad2041-568e-4e68-a407-4039270e7af5, clientIf=6
,08-26 14:17:45.274  6167  6175 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
08-26 14:17:45.274  6854  6863 D BtGatt.GattService: start scan with filters
,08-26 14:17:45.274  6854  6878 D BtGatt.ScanManager: handling starting scan
08-26 14:17:45.274  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-26 14:17:45.274  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:45.274  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:45.274  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:45.284  6854  6872 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,08-26 14:17:45.284  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:45.284  6854  6878 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:45.284  6854  6878 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,08-26 14:17:45.284  6854  6878 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,08-26 14:17:45.284  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-26 14:17:45.284  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false,
08-26 14:17:45.284  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:45.284  6854  6872 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
08-26 14:17:45.284  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:45.284  6854  6878 D BtGatt.ScanManager: Starting BLE batch scan
08-26 14:17:45.284  6854  6878 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:45.294  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:45.294  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 14:17:45.294  6167  6220 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-26 14:17:45.294  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:45.294  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:45.294  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-26 14:17:45.294  6854  6872 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
08-26 14:17:45.294  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.294  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:45.294  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.294  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 14:17:45.294  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:45.294  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@23f37d68 removed from the list
08-26 14:17:45.294  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:45.294  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25524581 removed from the list
08-26 14:17:45.294  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
,08-26 14:17:45.304  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:45.304  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.304  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 14:17:45.304  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:45.304  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:45.304  6854  6872 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
08-26 14:17:45.304  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.304  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:45.304  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:45.304  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:45.304  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25524581 not in the list
08-26 14:17:45.304  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,08-26 14:17:45.304  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:45.304  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-26 14:17:45.304  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser,
08-26 14:17:45.304  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:45.314  6854  6863 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:45.314  6854  6862 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:45.314  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-26 14:17:45.314  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:45.314  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:45.314  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:45.314  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED],
08-26 14:17:45.314  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:45.324  6854  6878 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 34
08-26 14:17:45.324  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-26 14:17:45.324  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:45.324  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:45.324  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:45.324  6854  6878 D BtGatt.ScanManager: filter size is 1
08-26 14:17:45.324  6854  6878 D BtGatt.ScanManager: delete FilterIndex - 4
,08-26 14:17:45.324  6854  6872 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 14:17:45.324  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.324  6854  6878 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:45.324  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:45.324  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:45.324  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:45.324  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25370814 removed from the list
08-26 14:17:45.324  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:45.324  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.324  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:45.324  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:45.324  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e0c3267 removed from the list
,08-26 14:17:45.334  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:45.334  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:45.334  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:45.334  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24869180 added. We now have 2 listener(s)
08-26 14:17:45.334  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:45.334  6854  6872 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 14:17:45.334  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:45.334  6854  6878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,08-26 14:17:45.344  6854  6872 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 14:17:45.344  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 14:17:45.344  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.344  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:45.344  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:45.344  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-26 14:17:45.344  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a123b9 added. We now have 9 listener(s)
08-26 14:17:45.344  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:45.344  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:45.354  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:45.354  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:45.354  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:45.354  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:45.354  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:45.354  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:45.354  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:45.354  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:45.354  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:45.354  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-26 14:17:45.354  6167  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:45.354  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:45.354  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1883075f added. We now have 3 listener(s)
,08-26 14:17:45.354  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:45.354  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 14:17:45.364  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:45.364  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:45.364  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:45.364  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e8345ac added. We now have 10 listener(s)
08-26 14:17:45.364  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:45.364  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-26 14:17:45.364  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-26 14:17:45.364  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-26 14:17:45.364  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-26 14:17:45.364  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-26 14:17:45.364  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:45.364  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-26 14:17:45.364  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-26 14:17:45.364  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-26 14:17:45.374  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-26 14:17:45.374  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-26 14:17:45.374  6167  6220 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-26 14:17:45.374  6854  6862 D BtGatt.GattService: registerClient() - UUID=f3d0409f-fb1d-4c19-91e5-441d803883da
,08-26 14:17:45.424  6854  6872 D BtGatt.GattService: onClientRegistered() - UUID=f3d0409f-fb1d-4c19-91e5-441d803883da, clientIf=6
,08-26 14:17:45.424  6167  6175 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6,
08-26 14:17:45.424  6854  6873 D BtGatt.GattService: start scan with filters
,08-26 14:17:45.424  6854  6878 D BtGatt.ScanManager: handling starting scan
,08-26 14:17:45.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
08-26 14:17:45.424  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-26 14:17:45.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-26 14:17:45.424  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-26 14:17:45.424  6854  6872 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
08-26 14:17:45.424  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:45.424  6854  6878 D BtGatt.ScanManager: allow scan with filters
08-26 14:17:45.424  6854  6878 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
08-26 14:17:45.424  6854  6878 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,08-26 14:17:45.424  6854  6872 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,08-26 14:17:45.424  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.424  6854  6878 D BtGatt.ScanManager: Starting BLE batch scan
,08-26 14:17:45.424  6854  6878 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,08-26 14:17:45.424  6854  6872 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,08-26 14:17:45.424  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.424  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:45.424  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-26 14:17:45.434  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-26 14:17:45.434  6854  6872 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,08-26 14:17:45.434  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.434  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-26 14:17:45.444  6854  6878 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 35
,08-26 14:17:45.444  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-26 14:17:45.444  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:45.444  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:45.444  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:45.444  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.444  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-26 14:17:45.444  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:45.444  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24869180 removed from the list
,08-26 14:17:45.444  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:45.444  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a123b9 removed from the list
,08-26 14:17:45.444  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:45.444  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:45.444  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:45.444  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-26 14:17:45.444  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-26 14:17:45.454  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-26 14:17:45.454  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:45.454  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:45.454  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:45.454  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16a123b9 not in the list
08-26 14:17:45.454  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-26 14:17:45.454  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-26 14:17:45.454  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-26 14:17:45.454  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-26 14:17:45.454  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-26 14:17:45.454  6854  6862 D BtGatt.GattService: stopScan() - queue size =1
,08-26 14:17:45.454  6854  6878 D BtGatt.ScanManager: filter size is 1
08-26 14:17:45.454  6854  6878 D BtGatt.ScanManager: delete FilterIndex - 5
,08-26 14:17:45.454  6854  6872 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,08-26 14:17:45.454  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
08-26 14:17:45.454  6854  6873 D BtGatt.GattService: unregisterClient() - clientIf=6
,08-26 14:17:45.454  6854  6878 D BtGatt.ScanManager: stopping BLe Batch
,08-26 14:17:45.454  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
08-26 14:17:45.454  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-26 14:17:45.454  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-26 14:17:45.454  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-26 14:17:45.454  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-26 14:17:45.464  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-26 14:17:45.464  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped,
08-26 14:17:45.464  6167  6220 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-26 14:17:45.464  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-26 14:17:45.464  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:45.464  6854  6872 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
08-26 14:17:45.464  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.464  6854  6878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
08-26 14:17:45.464  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:45.464  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:45.464  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:45.464  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:45.464  6167  6167 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-26 14:17:45.464  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e8345ac removed from the list,
08-26 14:17:45.464  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:45.464  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.464  6167  6167 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-26 14:17:45.464  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:45.464  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:45.464  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1883075f removed from the list
08-26 14:17:45.464  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-26 14:17:45.464  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51098 added. We now have 2 listener(s)
,08-26 14:17:45.464  6854  6872 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,08-26 14:17:45.464  6854  6872 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,08-26 14:17:45.464  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 14:17:45.464  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:45.464  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:45.464  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:45.464  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b690f1 added. We now have 9 listener(s)
08-26 14:17:45.464  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-26 14:17:45.464  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-26 14:17:45.474  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-26 14:17:45.474  6167  6220 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-26 14:17:45.474  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-26 14:17:45.474  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-26 14:17:45.474  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-26 14:17:45.474  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-26 14:17:45.474  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-26 14:17:45.474  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-26 14:17:45.474  6167  6220 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-26 14:17:45.474  6167  6220 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-26 14:17:45.474  6167  6220 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-26 14:17:45.474  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:45.474  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-26 14:17:45.474  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7708357 added. We now have 3 listener(s)
,08-26 14:17:45.484  6167  6167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-26 14:17:45.484  1013  1121 E WifiNative-wlan0: do suspend true
,08-26 14:17:45.484  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
08-26 14:17:45.484  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-26 14:17:45.484  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-26 14:17:45.484  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-26 14:17:45.484  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f369e44 added. We now have 10 listener(s)
08-26 14:17:45.484  6167  6220 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-26 14:17:45.484  6167  6220 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-26 14:17:45.484  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-26 14:17:45.484  6167  6220 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-26 14:17:45.484  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:45.484  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.484  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-26 14:17:45.484  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:45.484  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16b51098 removed from the list
08-26 14:17:45.484  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-26 14:17:45.484  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b690f1 removed from the list
08-26 14:17:45.484  6167  6220 D io.jxcore.node.ConnectivityMonitor: stop
08-26 14:17:45.484  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-26 14:17:45.484  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.484  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:45.484  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-26 14:17:45.484  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-26 14:17:45.484  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:45.484  6167  6220 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b690f1 not in the list
08-26 14:17:45.484  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.484  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:45.484  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-26 14:17:45.484  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-26 14:17:45.484  6167  6220 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-26 14:17:45.494  6167  6220 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f369e44 removed from the list
08-26 14:17:45.494  6167  6220 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-26 14:17:45.494  6167  6220 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-26 14:17:45.494  6167  6220 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-26 14:17:45.494  6167  6220 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-26 14:17:45.494  6167  6220 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7708357 removed from the list
,08-26 14:17:45.494  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,08-26 14:17:45.494  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-26 14:17:45.494  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-26 14:17:45.494  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-26 14:17:45.494  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,08-26 14:17:45.494  6167  6220 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-26 14:17:45.494  6167  6984 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1172, name: My test thread name)
,08-26 14:17:45.504  6167  6984 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1172, thread name: My test thread name)
,08-26 14:17:45.504  6167  6984 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1172, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 14:17:45.504  6167  6985 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1174, name: My test thread name)
,08-26 14:17:45.504  6167  6985 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1174, thread name: My test thread name)
08-26 14:17:45.504  6167  6985 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1174, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-26 14:17:45.504  6167  6220 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-26 14:17:45.504  6167  6220 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-26 14:17:45.504  6167  6220 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-26 14:17:45.504  6167  6220 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-26 14:17:45.504  6167  6220 D com.test.thalitest.ThaliTestRunner: Total duration: 24259 ms
,08-26 14:17:45.504  6167  6220 I jxcore-log: *Native tests were executed*
08-26 14:17:45.504  6167  6220 I jxcore-log: 
,08-26 14:17:45.504  6167  6220 I jxcore-log: Total number of executed tests:  80
08-26 14:17:45.504  6167  6220 I jxcore-log: 
08-26 14:17:45.504  6167  6220 I jxcore-log: Number of passed tests:  80
,08-26 14:17:45.504  6167  6220 I jxcore-log: 
08-26 14:17:45.504  6167  6220 I jxcore-log: Number of failed tests:  0
08-26 14:17:45.504  6167  6220 I jxcore-log: 
,08-26 14:17:45.504  6167  6220 I jxcore-log: Number of ignored tests:  0
08-26 14:17:45.504  6167  6220 I jxcore-log: 
08-26 14:17:45.504  6167  6220 I jxcore-log: Total duration:  24259
08-26 14:17:45.504  6167  6220 I jxcore-log: 
,08-26 14:17:45.504  6167  6220 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
08-26 14:17:45.504  6167  6220 I jxcore-log: 
08-26 14:17:45.514  1013  1120 D WifiP2pService: InactiveState{ what=143375 }
08-26 14:17:45.514  1013  1120 D WifiP2pService: P2pEnabledState{ what=143375 }
08-26 14:17:45.514  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:45.514  6167  6220 I jxcore-log: 
08-26 14:17:45.514  1013  1121 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-26 14:17:45.514  1013  1121 E WifiStateMachine: VerifyingLinkState enter
08-26 14:17:45.514  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:45.514  6167  6220 I jxcore-log: 
08-26 14:17:45.514  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:45.514  6167  6220 I jxcore-log: 
08-26 14:17:45.514  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:45.514  6167  6220 I jxcore-log: 
08-26 14:17:45.514  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:45.514  6167  6220 I jxcore-log: 
08-26 14:17:45.514  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:45.514  6167  6220 I jxcore-log: 
08-26 14:17:45.524  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:45.524  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-26 14:17:45.524  6167  6220 I jxcore-log: 
,08-26 14:17:45.524  1013  1121 D WifiNative-wlan0: callSECApiInt - ID [210]
08-26 14:17:45.524  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:45.524  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:45.524  1013  1123 E ConnectivityService: updateNetworkInfo()
,08-26 14:17:45.524  1013  1123 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
08-26 14:17:45.524  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:45.524  6167  6220 I jxcore-log: 
,08-26 14:17:45.524  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:45.524  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.524  6167  6220 I jxcore-log: 
08-26 14:17:45.524  1013  1123 D ConnectivityService: Adding iface wlan0 to network 503
,08-26 14:17:45.524  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.524  6167  6220 I jxcore-log: 
,08-26 14:17:45.524  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:45.524  6167  6220 I jxcore-log: 
,08-26 14:17:45.524  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.524  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
,08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
,08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
,08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"},
08-26 14:17:45.534  6167  6220 I jxcore-log: 
08-26 14:17:45.534  1013  1140 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
,08-26 14:17:45.534  1013  1140 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
08-26 14:17:45.534  1013  1140 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
08-26 14:17:45.534  1013  1140 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 14:17:45.534  1013  1140 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
,08-26 14:17:45.534  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.534  6167  6220 I jxcore-log: 
08-26 14:17:45.544  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.544  6167  6220 I jxcore-log: 
,08-26 14:17:45.544  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.544  6167  6220 I jxcore-log: 
,08-26 14:17:45.544  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.544  6167  6220 I jxcore-log: 
08-26 14:17:45.544  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.544  6167  6220 I jxcore-log: 
08-26 14:17:45.544  6167  6167 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-26 14:17:45.544  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.544  6167  6220 I jxcore-log: 
,08-26 14:17:45.544  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-26 14:17:45.544  6167  6220 I jxcore-log: 
08-26 14:17:45.544  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:45.544  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:45.544  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.544  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.544  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.544  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:45.554  1013  1121 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-26 14:17:45.554  1013  1314 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,08-26 14:17:45.554  1013  1314 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:45.554  1013  1314 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:45.554  1013  1314 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-26 14:17:45.554  1013  1314 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:45.564  3651  3651 I Hs20UtilService: Starting #20
,08-26 14:17:45.564  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-26 14:17:45.564  3651  3690 I Hs20UtilService: Message received 5007
08-26 14:17:45.564  1323  1323 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 14:17:45.564  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 14:17:45.564  1013  1123 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 503
,08-26 14:17:45.564  1013  1123 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 503,
,08-26 14:17:45.564  1013  1123 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 503
08-26 14:17:45.564  1013  1123 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-26 14:17:45.564  1013  1123 D ConnectivityService: Setting Dns servers for network 503 to [/192.168.1.1]
08-26 14:17:45.564  1013  1123 D ConnectivityService: LTETest block dns file not exists
,08-26 14:17:45.574  1175  1175 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:45.574  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-26 14:17:45.574  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:45.574  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.574  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.574  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:45.574  1013  1121 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-26 14:17:45.574  1013  1121 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-26 14:17:45.574  1013  1123 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
08-26 14:17:45.574  1013  1123 E ConnectivityService: updateNetworkInfo()
08-26 14:17:45.574  1013  1123 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-26 14:17:45.574  1013  1123 E ConnectivityService: updateNetworkInfo()
08-26 14:17:45.574  1013  1123 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 503]
08-26 14:17:45.574  1013  6949 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:45.574  1013  1123 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-26 14:17:45.574  1013  6949 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-26 14:17:45.574  1013  1123 D ConnectivityService:    accepting network in place of null
08-26 14:17:45.574  1013  6949 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-26 14:17:45.574  1013  6949 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
08-26 14:17:45.574  1013  6949 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-26 14:17:45.584  1013  1120 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
08-26 14:17:45.584  1013  1121 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
,08-26 14:17:45.584  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-26 14:17:45.584  1013  1013 I WifiTrafficPoller: mBoosterFLAG : 0
08-26 14:17:45.584  1013  1013 I WifiTrafficPoller: current booster mode : FullMode
08-26 14:17:45.584  1013  1013 D WifiNative-wlan0: callSECApiVoid - ID [212]
08-26 14:17:45.584  1455  1455 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
08-26 14:17:45.584  1455  1455 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-26 14:17:45.584   276  1008 D EnterpriseController: uids 1000
08-26 14:17:45.584   276  1008 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
08-26 14:17:45.584   276  1008 D Netd    : getNetworkForDns: using netid 503 for uid 1000
,08-26 14:17:45.584  1013  1123 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-26 14:17:45.584  1013  1123 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 503] isDefaultNetwork=true
08-26 14:17:45.584  1013  1123 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-26 14:17:45.594  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:45.594  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 14:17:45.594  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:45.604  1013  1123 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-26 14:17:45.604  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.604  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.604  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:45.604  1013  1123 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,08-26 14:17:45.604  1013  1042 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
08-26 14:17:45.604  1175  1692 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:17:45.604  3835  6229 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:17:45.604  1013  1013 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
,08-26 14:17:45.604  1013  1126 D Tethering: MasterInitialState.processMessage what=3
08-26 14:17:45.604  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:45.604  1013  1118 V NetworkStats: updateIfacesLocked()
08-26 14:17:45.604  1013  1118 V NetworkStats: performPollLocked(flags=0x1)
08-26 14:17:45.614  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:45.614  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox main else ---
08-26 14:17:45.614  1013  1118 V NetworkStats: performPollLocked() took 4ms
08-26 14:17:45.614  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:45.614  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:45.614  1013  1119 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-26 14:17:45.614  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:45.614  1013  1350 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:45.614  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:45.614  1013  1350 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
08-26 14:17:45.614  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:45.614  1013  1350 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:45.614  1013  1350 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:45.614  1013  1350 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:45.624  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:45.624  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:45.624  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 14:17:45.624  1323  1323 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-26 14:17:45.624  3651  3651 I Hs20UtilService: Starting #21
08-26 14:17:45.624  3651  3690 I Hs20UtilService: Message received 5007
,08-26 14:17:45.624  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,08-26 14:17:45.624  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
08-26 14:17:45.624  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-26 14:17:45.624  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 14:17:45.624  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-26 14:17:45.624  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 14:17:45.624  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-26 14:17:45.624  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-26 14:17:45.624  1323  1323 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
08-26 14:17:45.624  1323  1323 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 14:17:45.634  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-26 14:17:45.634  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-26 14:17:45.634  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-26 14:17:45.634  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
08-26 14:17:45.634  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-26 14:17:45.634  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.634  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.634  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.634  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:45.634  1013  3038 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
08-26 14:17:45.634  1013  3038 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,08-26 14:17:45.634  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:45.644  1013  3038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:45.644  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,08-26 14:17:45.644  3651  3651 I Hs20UtilService: Starting #22
,08-26 14:17:45.644  3651  3690 I Hs20UtilService: Message received 5007
,08-26 14:17:45.644  1323  1323 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-26 14:17:45.644  1323  1323 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-26 14:17:45.654  1013  1025 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-26 14:17:45.654  1013  3042 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
08-26 14:17:45.654  1013  3042 D SecContentProvider2: mCursor = null
,08-26 14:17:45.654  1013  1540 D SecContentProvider2: uri = 15 selection = getToastGravity
08-26 14:17:45.654  1013  1540 D SecContentProvider2: mCursor = null
,08-26 14:17:45.654  1013  3040 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
08-26 14:17:45.654  1013  3040 D SecContentProvider2: mCursor = null
,08-26 14:17:45.654  1013  1314 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
08-26 14:17:45.654  1013  1314 D SecContentProvider2: mCursor = null
,08-26 14:17:45.654  1013  1026 D SecContentProvider2: uri = 15 selection = getToastEnabledState,
08-26 14:17:45.654  1013  1026 D SecContentProvider2: mCursor = null
,08-26 14:17:45.664  1013  3038 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,08-26 14:17:45.664  1013  3038 D SecContentProvider2: mCursor = null
,08-26 14:17:45.664  6167  6167 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
08-26 14:17:45.664  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:45.664  6167  6220 I jxcore-log: 
,08-26 14:17:45.684  1013  6949 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false,
,08-26 14:17:45.684   256   256 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,08-26 14:17:45.694  1013  1261 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013
,08-26 14:17:45.704  1175  1175 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-26 14:17:45.754  1013  6949 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 26 Aug 2016 12:17:45 GMT], X-Android-Received-Millis=[1472213865769], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472213865731]}
,08-26 14:17:45.754  1013  6949 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,08-26 14:17:45.754  1013  6949 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-26 14:17:45.754  1013  1123 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 503]
08-26 14:17:45.754  1013  1123 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 503]
08-26 14:17:45.754  1013  1123 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 503] was already satisfying request 1. No change.
08-26 14:17:45.754  1013  1123 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 503]
,08-26 14:17:45.754  1175  1692 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:17:45.754  1013  1123 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-26 14:17:45.754  3835  6229 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: EthernetConnected: false
,08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: updateDataNetType()
08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-26 14:17:45.764  1175  1175 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,08-26 14:17:45.764  1175  1175 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
08-26 14:17:45.764  1175  1175 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,08-26 14:17:45.774  6988  6988 D AndroidRuntime: ,
08-26 14:17:45.774  6988  6988 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-26 14:17:45.784  6988  6988 D AndroidRuntime: CheckJNI is OFF,
08-26 14:17:45.784  6988  6988 D AndroidRuntime: readGMSProperty: start
,08-26 14:17:45.784  6988  6988 D AndroidRuntime: readGMSProperty: already setted!!
08-26 14:17:45.784  6988  6988 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-26 14:17:45.784  6988  6988 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
,08-26 14:17:45.784  6988  6988 D AndroidRuntime: readGMSProperty: end
08-26 14:17:45.784  6988  6988 D AndroidRuntime: addProductProperty: start
,08-26 14:17:45.834  6167  6167 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false,
08-26 14:17:45.834  6167  6220 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-26 14:17:45.834  6167  6220 I jxcore-log: 
,08-26 14:17:45.914  6988  6988 E AffinityControl: AffinityControl: registerfunction enter
,08-26 14:17:45.944  6988  6988 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-26 14:17:45.954  1013  1713 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
08-26 14:17:45.954  1013  1713 D PackageManager: START PACKAGE DELETE: observer{578627921}
08-26 14:17:45.954  1013  1713 D PackageManager: pkg{<packageName>}
08-26 14:17:45.954  1013  1713 D PackageManager: user{0}
08-26 14:17:45.954  1013  1713 D PackageManager: caller{2000}
08-26 14:17:45.954  1013  1713 D PackageManager: flags{2}
,08-26 14:17:45.954  1013  1713 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-26 14:17:45.954  1013  1713 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-26 14:17:45.954  1013  1713 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-26 14:17:45.954  1013  1713 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2,
,08-26 14:17:45.954  1013  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-26 14:17:45.954  1013  1053 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-26 14:17:45.954  1013  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-26 14:17:45.954  1013  1053 D ApplicationPolicy: getApplicationUninstallationEnabled
08-26 14:17:45.954  1013  1053 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-26 14:17:45.954  1013  1053 D PackageManager: !@killApplicatoin: 10155, uninstall pkg,
,08-26 14:17:45.964  1013  1038 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,08-26 14:17:45.964  1013  1038 I ActivityManager: Killing 6167:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
08-26 14:17:45.964  1013  1038 I ActivityManager:   Force finishing activity ActivityRecord{a39bc2b u0 com.test.thalitest/.MainActivity t127}
,08-26 14:17:45.974  1013  1038 D InputDispatcher: Focus left window: 6167
,08-26 14:17:45.974   256   443 I SurfaceFlinger: id=13 Removed NainActivit (6/9),
08-26 14:17:45.974   256   585 I SurfaceFlinger: id=13 Removed NainActivit (-2/9)
,08-26 14:17:45.974  1013  1038 D InputDispatcher: Focused application released
,08-26 14:17:45.974  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-26 14:17:45.974  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-26 14:17:46.094  1013  1053 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed,
,08-26 14:17:46.104  1013  1123 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,08-26 14:17:46.124  1013  1053 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-26 14:17:46.134  3910  3910 I art     : Explicit concurrent mark sweep GC freed 2686(164KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 6MB/11MB, paused 692us total 25.068ms
,08-26 14:17:46.144  5435  5435 I art     : Explicit concurrent mark sweep GC freed 386(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 746us total 31.356ms
,08-26 14:17:46.164  1013  1094 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-26 14:17:46.174  3835  3835 I art     : Explicit concurrent mark sweep GC freed 23009(1398KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 15MB/26MB, paused 1.295ms total 73.040ms
,08-26 14:17:46.174  1896  1896 E SamsungIME: mOCRHelper is null
,08-26 14:17:46.214  1443  1443 D PersonaManager: isKioskContainerExistOnDevice
,08-26 14:17:46.224  3698  3698 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Aug 26 14:17:46 GMT+02:00 2016
,08-26 14:17:46.254  3141  3141 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,08-26 14:17:46.254  6473  6473 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-26 14:17:46.264  1013  1118 V NetworkStats: removeUidsLocked() for UIDs [10155]
08-26 14:17:46.264  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:46.264  1013  1118 V NetworkStats: performPollLocked(flags=0x3)
,08-26 14:17:46.274  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox updated
08-26 14:17:46.274  1013  1118 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-26 14:17:46.274  1013  1118 V NetworkStats: performPollLocked() took 7ms
,08-26 14:17:46.284  1013  1118 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:46.284  1443  1443 D RegisteredServicesCache: empty dynamic service
,08-26 14:17:46.304  1443  1443 D RegisteredComponentCache: Collect Tech packages for Knox
,08-26 14:17:46.304  1443  1443 D PersonaManager: isKioskContainerExistOnDevice
,08-26 14:17:46.324  1013  1013 I art     : Explicit concurrent mark sweep GC freed 83182(5MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 28MB/42MB, paused 8.572ms total 195.820ms
08-26 14:17:46.324  1013  1541 I art     : WaitForGcToComplete blocked for 145.624ms for cause Explicit
,08-26 14:17:46.374  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
08-26 14:17:46.374  1013  1119 D NtpTrustedTime: currentTimeMillis() cache hit
,08-26 14:17:46.444  1013  1013 D RCPManagerService: PackageReceiver onReceive()
,08-26 14:17:46.444  1013  1013 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-26 14:17:46.454  1013  1013 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-26 14:17:46.454  1013  1013 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-26 14:17:46.454  1013  1013 D OTPFW   : OtpDbHelper::getInstance New instance created
,08-26 14:17:46.454  1013  1013 D OTPFW   : DBIntegrity::getInstance - New instance created
,08-26 14:17:46.454  1013  1013 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,08-26 14:17:46.464  1013  1013 I OTPFW   : ProvisionData::getAllEntries Enter
,08-26 14:17:46.464  1013  1013 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-26 14:17:46.464  1013  1013 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-26 14:17:46.464  1013  1013 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicy: uID is 10155
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 14:17:46.464  1013  1013 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicy: uID is 10155
08-26 14:17:46.464  1013  1158 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-26 14:17:46.464  1013  2741 D SSRM:bc : MSG_TYPE_APP_REMOVED::
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-26 14:17:46.464  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-26 14:17:46.474  1013  1013 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,08-26 14:17:46.524  1013  1541 I art     : Explicit concurrent mark sweep GC freed 20135(1753KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 3.792ms total 207.139ms
,08-26 14:17:46.524  1013  1053 I art     : WaitForGcToComplete blocked for 317.756ms for cause Explicit
08-26 14:17:46.524  1013  1539 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-26 14:17:46.524  1013  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-26 14:17:46.534  1905  2116 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-26 14:17:46.534  1013  1539 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:46.534  1013  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:46.534  1013  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-26 14:17:46.534  1013  3193 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 14:17:46.534  1013  3193 D SecContentProvider2: mCursor = null
,08-26 14:17:46.534  1013  1037 D EnterpriseDeviceManagerService: Package has changed for user 0
08-26 14:17:46.534  1013  1037 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-26 14:17:46.534  1013  1037 W TextServicesManagerService: no available spell checker services found
,08-26 14:17:46.544  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.544  3698  3698 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,08-26 14:17:46.554  1013  1350 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
08-26 14:17:46.554  1013  1350 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
08-26 14:17:46.554  1013  1350 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-26 14:17:46.554  1013  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:46.554  1013  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:46.554  1013  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.554  1013  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:46.554  3698  3698 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
08-26 14:17:46.554  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.564  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.564  3698  3698 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-26 14:17:46.574  3698  3698 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-26 14:17:46.574  1013  1350 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7005 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,08-26 14:17:46.574  7005  7005 E Zygote  : MountEmulatedStorage()
08-26 14:17:46.574  7005  7005 E Zygote  : v2
08-26 14:17:46.574  7005  7005 I libpersona: KNOX_SDCARD checking this for 10094
08-26 14:17:46.574  7005  7005 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:46.584  3698  7004 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) },
08-26 14:17:46.584  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast,
,08-26 14:17:46.584  3698  7004 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
08-26 14:17:46.584  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-26 14:17:46.584  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.584  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.584  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:46.584  3698  7004 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,08-26 14:17:46.584  7005  7005 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:46.584  3698  7004 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-26 14:17:46.584  7005  7005 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:46.594  7005  7005 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:46.604  1013  1123 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-26 14:17:46.604  7005  7005 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:46.604  7005  7005 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:46.614  7014  7014 E Zygote  : MountEmulatedStorage()
08-26 14:17:46.614  7014  7014 I libpersona: KNOX_SDCARD checking this for 10044
08-26 14:17:46.614  7014  7014 E Zygote  : v2
08-26 14:17:46.614  7014  7014 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:46.614  7014  7014 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 14:17:46.614  7014  7014 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 14:17:46.614  7014  7014 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 14:17:46.624  1013  1038 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7014 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-26 14:17:46.624  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
08-26 14:17:46.624  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.624  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.624  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.624  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:46.644   308   308 I art     : Explicit concurrent mark sweep GC freed 8714(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 29.653ms
,08-26 14:17:46.644  7014  7014 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:46.644  7014  7014 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:46.664  3698  7004 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-26 14:17:46.664   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 18.546ms
,08-26 14:17:46.664  1013  1037 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-26 14:17:46.674  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.674  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.674  3698  7004 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-26 14:17:46.684   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 17.849ms
,08-26 14:17:46.684  3698  7004 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,08-26 14:17:46.684  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.694  1013  1037 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 14:17:46.694  1013  1037 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:46.694  1013  1037 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:17:46.694  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.694  7036  7036 E Zygote  : MountEmulatedStorage(),
08-26 14:17:46.704  7036  7036 E Zygote  : v2
08-26 14:17:46.704  7036  7036 I libpersona: KNOX_SDCARD checking this for 10149
08-26 14:17:46.704  7036  7036 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:46.704  7036  7036 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,08-26 14:17:46.704  7036  7036 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
08-26 14:17:46.704  1013  1123 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
,08-26 14:17:46.704  1013  1123 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-26 14:17:46.704  1013  1123 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 503]
08-26 14:17:46.704  7036  7036 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-26 14:17:46.704  1175  1692 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 14:17:46.704  3835  6229 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295,
08-26 14:17:46.704  1175  1692 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-26 14:17:46.704  3835  6229 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-26 14:17:46.714  1013  1038 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7036 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,08-26 14:17:46.714  6836  7026 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-26 14:17:46.724  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.734  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.744  7036  7036 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:46.744  7036  7036 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:46.744  3698  3698 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,08-26 14:17:46.754  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 14:17:46.754  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 14:17:46.764  7014  7014 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-26 14:17:46.764  7005  7005 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-26 14:17:46.764  7005  7005 D elm:15183: ELMEngine.ELMEngine( context ).
,08-26 14:17:46.764  7005  7005 D elm:15183: MDMBridge.setEnterpriseBridge()
,08-26 14:17:46.764  7014  7014 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 14:17:46.764  1013  3042 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-26 14:17:46.774  1013  3042 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-26 14:17:46.774  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.774  7014  7014 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-26 14:17:46.774  7014  7014 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:17:46.774  7014  7014 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-26 14:17:46.774  1013  3042 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:46.774  7014  7014 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-26 14:17:46.774  1013  3042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:46.774  7014  7014 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 14:17:46.774  1013  3042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-26 14:17:46.774  7014  7014 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 14:17:46.774  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.774  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 14:17:46.774  7005  7005 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-26 14:17:46.774  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-26 14:17:46.774  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-26 14:17:46.784  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-26 14:17:46.784  3370  3370 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-26 14:17:46.784  1013  1053 I art     : Explicit concurrent mark sweep GC freed 10460(557KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 27MB/41MB, paused 4.462ms total 257.624ms
,08-26 14:17:46.784  3370  3370 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-26 14:17:46.794  3370  3370 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
08-26 14:17:46.794  3370  3370 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-26 14:17:46.794  3370  3370 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
08-26 14:17:46.794  3370  3370 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
08-26 14:17:46.794  3370  3370 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
08-26 14:17:46.794  3370  3370 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-26 14:17:46.794  3370  3370 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:46.794  3370  3370 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
,08-26 14:17:46.794  7005  7005 D elm:15183: ElmAgentService : onCreate()
,08-26 14:17:46.794  3370  3370 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-26 14:17:46.794  7005  7051 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-26 14:17:46.794  7005  7051 D elm:15183: MainReceiver.listeningToPackageRemoved()
08-26 14:17:46.794  7005  7051 D elm:15183: MDMBridge.getInstance()
08-26 14:17:46.794  7005  7051 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 14:17:46.794  3370  3370 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-26 14:17:46.794  3370  3370 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-26 14:17:46.794  3370  3370 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,08-26 14:17:46.794  7005  7051 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,08-26 14:17:46.804  1013  1037 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-26 14:17:46.804  1013  1037 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-26 14:17:46.804  7036  7036 D ThemeInfoUtil: getCurrentFestivalName is [null]
08-26 14:17:46.804  7036  7036 D ThemeInfoUtil: isCurrentFestival = false
,08-26 14:17:46.814  6836  7026 I art     : Explicit concurrent mark sweep GC freed 739(53KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 2.054ms total 64.325ms
,08-26 14:17:46.814  6456  6456 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-26 14:17:46.814  6456  6456 I PCWCLIENTTRACE_PushUtil: sales region : global
08-26 14:17:46.814  6456  6456 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-26 14:17:46.814  6456  6456 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-26 14:17:46.814  1013  1539 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,08-26 14:17:46.814  1013  1037 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-26 14:17:46.814  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.814  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.814  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.814  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:46.824  7054  7054 E Zygote  : MountEmulatedStorage()
08-26 14:17:46.824  7054  7054 E Zygote  : v2
08-26 14:17:46.824  7054  7054 I libpersona: KNOX_SDCARD checking this for 10152
08-26 14:17:46.824  7054  7054 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:46.834  7054  7054 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:46.834  7054  7054 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:46.834  7054  7054 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:46.834  1013  1539 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7054 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,08-26 14:17:46.844  1013  1261 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-26 14:17:46.844  1013  1261 D SecContentProvider2: mCursor = null
,08-26 14:17:46.844  1013  1539 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-26 14:17:46.854  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.854  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.854  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.854  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:46.854  1013  1053 D PackageManager: delete codoeFile: 
,08-26 14:17:46.864  7054  7054 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:46.864  7054  7054 D ActivityThread: Added TimaKeyStore provider
08-26 14:17:46.864  1013  1053 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
08-26 14:17:46.864  1013  1053 I AASA_removePackage: UID=10155 Target=com.test.thalitest
08-26 14:17:46.864  7065  7065 E Zygote  : MountEmulatedStorage()
08-26 14:17:46.864  7065  7065 E Zygote  : v2
08-26 14:17:46.864  7065  7065 I libpersona: KNOX_SDCARD checking this for 10032
08-26 14:17:46.864  7065  7065 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:46.864  1013  1053 D PackageManager: result of delete: 1{578627921}
,08-26 14:17:46.874  7065  7065 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:46.874  7065  7065 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:46.874  7065  7065 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
08-26 14:17:46.874  1013  1539 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7065 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,08-26 14:17:46.884  6988  6988 D AndroidRuntime: Shutting down VM
,08-26 14:17:46.884  1013  1539 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,08-26 14:17:46.884  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.884  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.884  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.884  1013  1539 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:46.894  7005  7005 D elm:15183: ElmAgentService : onDestroy().
,08-26 14:17:46.894  1476  1476 D Launcher.Model: reloadBadges entered.
,08-26 14:17:46.894  5873  5884 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
08-26 14:17:46.894  5873  5884 D BadgeProvider: sendNotify, [notify] : null
08-26 14:17:46.894  5873  5884 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
08-26 14:17:46.894  5873  5884 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-26 14:17:46.894  5873  5884 D BadgeProvider: update, [UpdateCount] : 1
,08-26 14:17:46.904  7081  7081 E Zygote  : MountEmulatedStorage()
,08-26 14:17:46.904  7081  7081 E Zygote  : v2
08-26 14:17:46.904  7081  7081 I libpersona: KNOX_SDCARD checking this for 1000
08-26 14:17:46.904  7081  7081 I libpersona: KNOX_SDCARD not a persona
,08-26 14:17:46.904  7081  7081 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:46.914  1013  1539 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7081 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
08-26 14:17:46.914  1013  1539 I ActivityManager: Killing 6079:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,08-26 14:17:46.914  7081  7081 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:46.914  1013  1539 I ActivityManager: Killing 5435:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,08-26 14:17:46.914  7081  7081 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:46.924  7065  7065 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:46.924  7065  7065 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:46.944  7081  7081 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:46.944  7081  7081 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:46.954  7054  7054 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,08-26 14:17:46.954  1013  1539 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
08-26 14:17:46.964  1013  1539 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,08-26 14:17:46.964  1013  1539 W ActivityManager: userId = 0, bbcId = -10000
,08-26 14:17:46.964  1013  1539 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:46.964  1013  1539 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,08-26 14:17:46.964  1013  1350 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,08-26 14:17:46.964  1013  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:46.964  1013  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.964  1013  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:46.964  1013  1350 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:46.984  7103  7103 E Zygote  : MountEmulatedStorage()
,08-26 14:17:46.984  7103  7103 E Zygote  : v2
08-26 14:17:46.984  7103  7103 I libpersona: KNOX_SDCARD checking this for 10156
08-26 14:17:46.984  7103  7103 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:46.984  7103  7103 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 14:17:46.984  7103  7103 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 14:17:46.984  1013  1350 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7103 uid=10156 gids={50156, 9997} abi=armeabi-v7a
08-26 14:17:46.984  7103  7103 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:46.994  7014  7014 D NearbySource: Nearby Source Create!
,08-26 14:17:46.994  7014  7014 D NearbyContext: Nearby Context Create!
,08-26 14:17:47.014  1013  1540 I ActivityManager: Killing 6103:com.google.android.gms:car/u0a12 (adj 15): empty #31
,08-26 14:17:47.014  7081  7081 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,08-26 14:17:47.014  1013  3038 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,08-26 14:17:47.014  1013  3038 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
08-26 14:17:47.014  7103  7103 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:47.014  1013  3038 W ActivityManager: userId = 0, bbcId = -10000
08-26 14:17:47.014  7103  7103 D ActivityThread: Added TimaKeyStore provider
08-26 14:17:47.014  1013  3038 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-26 14:17:47.014  1013  3038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,08-26 14:17:47.024  1013  3119 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
08-26 14:17:47.024  7065  7118 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-26 14:17:47.024  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:47.024  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:47.024  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:47.024  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:47.044  6854  6870 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-26 14:17:47.044  7103  7103 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,08-26 14:17:47.044  7103  7103 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,08-26 14:17:47.044  7065  7118 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-26 14:17:47.044  7065  7118 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-26 14:17:47.054  7065  7118 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-26 14:17:47.054  7065  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:47.054  7065  7118 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-26 14:17:47.054  7065  7118 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-26 14:17:47.054   255   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-26 14:17:47.054   255   520 W Vold    : Returning OperationFailed - no handler for errno 0
,08-26 14:17:47.054  7014  7014 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
08-26 14:17:47.054  7014  7014 D SLinkSource: Samsung link source created
08-26 14:17:47.054  7103  7103 I TapandpayWidget:Utils: Clear T&P info.
,08-26 14:17:47.064  7065  7118 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
08-26 14:17:47.064  7065  7118 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 14:17:47.064  7065  7118 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 14:17:47.064  7065  7118 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:47.064  7065  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:47.064  7065  7118 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-26 14:17:47.064  7123  7123 E Zygote  : MountEmulatedStorage()
08-26 14:17:47.064  7123  7123 E Zygote  : v2
08-26 14:17:47.064  7123  7123 I libpersona: KNOX_SDCARD checking this for 1000
,08-26 14:17:47.064  7123  7123 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:47.064  1013  3119 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7123 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,08-26 14:17:47.064  7123  7123 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:47.064  7123  7123 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:47.074  7123  7123 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:47.074  7103  7103 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,08-26 14:17:47.074  1013  3119 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 14:17:47.074  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:47.074  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.074  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.074  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:47.084  7065  7118 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 14:17:47.084  7065  7118 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:47.084  7065  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:17:47.084  7065  7118 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 14:17:47.084  7065  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:47.084  7065  7118 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-26 14:17:47.104  7123  7123 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-26 14:17:47.104  7137  7137 E Zygote  : MountEmulatedStorage()
08-26 14:17:47.104  7137  7137 E Zygote  : v2
08-26 14:17:47.104  7137  7137 I libpersona: KNOX_SDCARD checking this for 10035
08-26 14:17:47.104  7123  7123 D ActivityThread: Added TimaKeyStore provider
08-26 14:17:47.104  7137  7137 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:47.104  7137  7137 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:47.104  6988  6988 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
08-26 14:17:47.104  7137  7137 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:47.104  7137  7137 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-26 14:17:47.114  1013  3119 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7137 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 14:17:47.114  1013  3119 I ActivityManager: Killing 5674:com.android.defcontainer/u0a4 (adj 15): empty #31
,08-26 14:17:47.114  7065  7118 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 14:17:47.114  7065  7118 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:47.114  7065  7118 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-26 14:17:47.114  7065  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:47.114  7065  7118 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,08-26 14:17:47.114  7065  7118 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-26 14:17:47.114  7065  7118 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 14:17:47.114  7065  7118 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 14:17:47.124  7065  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:47.124  7065  7118 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 14:17:47.124  7065  7118 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 14:17:47.134  1013  1345 I ActivityManager: Killing 5566:com.android.vending/u0a28 (adj 15): empty #31
,08-26 14:17:47.134  1013  1345 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,08-26 14:17:47.134  1013  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.134  1013  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.134  1013  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.134  1013  1345 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:47.134  7065  7118 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-26 14:17:47.134  7065  7118 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 14:17:47.134  7065  7118 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-26 14:17:47.134  7065  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:47.134  7065  7118 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-26 14:17:47.144  7123  7123 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:17:47.144  7137  7137 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:47.144  7137  7137 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:47.154  1013  1053 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-26 14:17:47.154  1013  1053 D PackageManager: userId{-1}
08-26 14:17:47.154  1013  1053 D PackageManager: andCode{true}
,08-26 14:17:47.154  7065  7118 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-26 14:17:47.154  7065  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:47.154  7065  7118 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 14:17:47.154  7065  7118 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 14:17:47.154  7153  7153 E Zygote  : MountEmulatedStorage(),
08-26 14:17:47.154  7153  7153 E Zygote  : v2
08-26 14:17:47.154  7153  7153 I libpersona: KNOX_SDCARD checking this for 10160
08-26 14:17:47.154  7153  7153 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:47.154  7153  7153 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:47.164  7153  7153 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,08-26 14:17:47.164  7153  7153 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-26 14:17:47.164  1013  1345 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7153 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
,08-26 14:17:47.174  1013  1345 I ActivityManager: Killing 6243:com.google.android.gms.unstable/u0a12 (adj 15): empty #31,
,08-26 14:17:47.184  7123  7123 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-26 14:17:47.184  7065  7118 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-26 14:17:47.184  7065  7118 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-26 14:17:47.184  7065  7118 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-26 14:17:47.184  7065  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:47.184  7065  7118 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-26 14:17:47.194  7153  7153 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:47.194  7153  7153 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:47.194  1013  1053 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-26 14:17:47.204  1013  3119 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-26 14:17:47.204  1013  1053 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.204  1013  3119 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
08-26 14:17:47.204  1013  1053 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.204  1013  1053 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.204  1013  1053 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.204  7153  7153 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
08-26 14:17:47.204  7065  7118 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-26 14:17:47.204  7065  7118 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,08-26 14:17:47.214  1013  1345 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0},
,08-26 14:17:47.234  7153  7153 D [0]UMC:UMCContentProvider: @onCreate
,08-26 14:17:47.234  6836  7053 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-26 14:17:47.234  6836  7053 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: Error inserting name=LPCSystemVersion value=1.0.0
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:209)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:47.234  6836  7053 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-26 14:17:47.244  7171  7171 E Zygote  : MountEmulatedStorage()
08-26 14:17:47.244  7171  7171 E Zygote  : v2
08-26 14:17:47.244  7171  7171 I libpersona: KNOX_SDCARD checking this for 10004
08-26 14:17:47.244  7171  7171 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:47.244  6836  7053 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-26 14:17:47.244  6836  7053 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
,08-26 14:17:47.244  6836  7053 E SQLiteDatabase: Error inserting name=UT enabled value=false
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:210)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
,08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:47.244  7171  7171 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
08-26 14:17:47.244  6836  7053 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-26 14:17:47.244  6836  7053 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: Error inserting name=AFP Enabled value=true
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: ,	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:211)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:47.244  7171  7171 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 14:17:47.244  6836  7053 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-26 14:17:47.244  6836  7053 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error,
08-26 14:17:47.244  7171  7171 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: Error inserting name=SleepDetection Enabled value=false
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:212)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:47.244  6836  7053 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-26 14:17:47.244  7065  7118 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-26 14:17:47.244  6836  7053 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-26 14:17:47.244  7065  7118 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: Error inserting name=System Build Version Release value=5.0.2
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:213)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:47.244  6836  7053 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:47.244  7065  7118 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-26 14:17:47.244  7065  7118 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-26 14:17:47.254  6836  7053 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-26 14:17:47.254  6836  7053 E SQLiteLog: (3850) statement aborts at 22: [INSERT INTO system_env_info(name,value) VALUES (?,?)] disk I/O error
08-26 14:17:47.254  1013  1053 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7171 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-26 14:17:47.254  7014  7157 D ContactProvider: getAllContactInfoList Start
08-26 14:17:47.254  7065  7118 W Re,sourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: Error inserting name=status value=successfully initialized
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c$b.a(DataStore.java:2487)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.c.b(DataStore.java:1740)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.g(LowpowerContextEngine.java:214)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.e(LowpowerContextEngine.java:150)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.<init>(LowpowerContextEngine.java:100)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.f.a(LowpowerContextEngine.java:106)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:100)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.LowpowerContextReceiver$SystemBroadcastReceiver.a(LowpowerContextReceiver.java:41)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at com.samsung.android.sm.database.lowpowercontext.n.run(LowpowerContextReceiver.java:51)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-26 14:17:47.254  6836  7053 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-26 14:17:47.254  1013  3119 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
08-26 14:17:47.254  7065  7118 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-26 14:17:47.254  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.254  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.254  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.254  1013  3119 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:47.264  7065  7118 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-26 14:17:47.264  7065  7118 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-26 14:17:47.274  7171  7171 D TimaKeyStoreProvider: TimaSignature is unavailable
08-26 14:17:47.274  7171  7171 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:47.274  7065  7118 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
,08-26 14:17:47.274  7188  7188 E Zygote  : MountEmulatedStorage()
08-26 14:17:47.274  7188  7188 E Zygote  : v2
08-26 14:17:47.274  7188  7188 I libpersona: KNOX_SDCARD checking this for 10091
08-26 14:17:47.274  7188  7188 I libpersona: KNOX_SDCARD not a persona
08-26 14:17:47.274  7188  7188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,08-26 14:17:47.284  1013  3119 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7188 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-26 14:17:47.284  7188  7188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
08-26 14:17:47.284  1013  3119 I ActivityManager: Killing 6517:com.android.chrome/u0a81 (adj 15): empty #31
,08-26 14:17:47.284  7188  7188 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-26 14:17:47.294  7153  7153 D [0]UMC:Core: onCreate(): 
08-26 14:17:47.294  7153  7153 D [0]UMC:Core: @isManagedProfileUser
08-26 14:17:47.294  7153  7153 D [0]UMC:Core: userId: 0
,08-26 14:17:47.294  7153  7153 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
,08-26 14:17:47.294  7153  7153 D [0]UMC:Core: userInfo.isManagedProfile() : false
,08-26 14:17:47.304  1013  3040 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-26 14:17:47.314  7014  7014 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,08-26 14:17:47.314  7188  7188 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-26 14:17:47.314  7188  7188 D ActivityThread: Added TimaKeyStore provider
,08-26 14:17:47.314  7137  7203 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-26 14:17:47.314  7137  7203 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-26 14:17:47.324  7014  7014 E SharedPreferencesImpl: Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
,08-26 14:17:47.324  1013  1131 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-26 14:17:47.334  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.334  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.334  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-26 14:17:47.334  1013  1131 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-26 14:17:47.334  7153  7153 D [0]UMC:DeviceInfo: USA==US==

```
