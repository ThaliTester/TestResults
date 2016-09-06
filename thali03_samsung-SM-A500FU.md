#### Test 82914073f44248e_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
09-06 18:56:50.149   329   329 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-06 18:56:50.149   329   329 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-06 18:56:50.459   291   291 E SMD     : DCD OFF
09-06 18:56:50.669  6208  6208 D AndroidRuntime: 
09-06 18:56:50.669  6208  6208 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-06 18:56:50.669  6208  6208 D AndroidRuntime: CheckJNI is OFF
09-06 18:56:50.679  6208  6208 D AndroidRuntime: readGMSProperty: start
09-06 18:56:50.679  6208  6208 D AndroidRuntime: readGMSProperty: already setted!!
09-06 18:56:50.679  6208  6208 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 18:56:50.679  6208  6208 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 18:56:50.679  6208  6208 D AndroidRuntime: readGMSProperty: end
09-06 18:56:50.679  6208  6208 D AndroidRuntime: addProductProperty: start
09-06 18:56:50.819  6208  6208 E AffinityControl: AffinityControl: registerfunction enter
09-06 18:56:50.849  6208  6208 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-06 18:56:50.849  1014  1027 E PersonaManagerService: inState():  stateMachine is null !!
09-06 18:56:50.849  1014  1027 I PersonaManagerService: PersonaId don't exist
09-06 18:56:50.849  1014  1027 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-06 18:56:50.859  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-06 18:56:50.869  1014  1027 W ActivityManager: mDVFSHelper.acquire()
09-06 18:56:50.879  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:56:50.879  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:56:50.879  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:56:50.879  1014  1027 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:56:50.889  1014  1044 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-06 18:56:50.889  1014  1044 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-06 18:56:50.889  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-06 18:56:50.889  1014  1027 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6219 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-06 18:56:50.889  1014  1027 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 18:56:50.889  6219  6219 I libpersona: KNOX_SDCARD checking this for 10155
09-06 18:56:50.889  1014  1027 D InputDispatcher: Focused application set to: xxxx
09-06 18:56:50.889  6219  6219 I libpersona: KNOX_SDCARD not a persona
09-06 18:56:50.889  1014  1027 D InputDispatcher: Focus left window: 3152
09-06 18:56:50.889  6219  6219 E Zygote  : MountEmulatedStorage()
09-06 18:56:50.889  6219  6219 E Zygote  : v2
09-06 18:56:50.889  6208  6208 D AndroidRuntime: Shutting down VM
09-06 18:56:50.899  6219  6219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 18:56:50.899  6219  6219 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 18:56:50.899  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 18:56:50.899  1014  1044 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-06 18:56:50.899   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-06 18:56:50.909  6219  6219 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-06 18:56:50.919  6219  6219 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 18:56:50.919  6219  6219 D ActivityThread: Added TimaKeyStore provider
09-06 18:56:50.929  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 18:56:50.929  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
09-06 18:56:50.939  1014  1014 V ActivityManager: Display changed displayId=0
09-06 18:56:50.939  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-06 18:56:50.949  3152  3152 V ActivityThread: updateVisibility : ActivityRecord{156bae03 token=android.os.BinderProxy@dc14f56 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-06 18:56:50.959  1014  1474 D PersonaManager: isKioskContainerExistOnDevice
09-06 18:56:50.989   258  1157 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
09-06 18:56:50.989   258   441 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/9)
09-06 18:56:51.069  6219  6219 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-06 18:56:51.089  6219  6219 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 548-550)
09-06 18:56:51.089  6219  6219 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 18:56:51.099  6208  6208 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-06 18:56:51.109  6219  6219 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1ec5292f}
09-06 18:56:51.109  6219  6219 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 18:56:51.109  6219  6219 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 18:56:51.139  6219  6219 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-06 18:56:51.139  6219  6219 W art     : Attempt to remove local handle scope entry from IRT, ignoring,
,09-06 18:56:51.139  6219  6219 E SysUtils: ApplicationContext is null in ApplicationStatus,
,09-06 18:56:51.159  6219  6219 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-06 18:56:51.159  6219  6219 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,09-06 18:56:51.169  6219  6219 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-06 18:56:51.169  6219  6219 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 18:56:51.169  6219  6219 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 18:56:51.169  6219  6219 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 18:56:51.169  6219  6219 I Adreno-EGL: Local Branch: 
09-06 18:56:51.169  6219  6219 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 18:56:51.169  6219  6219 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 18:56:51.169  6219  6219 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 18:56:51.289  6219  6245 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-06 18:56:51.329  6219  6219 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 18:56:51.349  6219  6219 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-06 18:56:51.359  6219  6219 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-06 18:56:51.359  6219  6219 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-06 18:56:51.359  6219  6219 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-06 18:56:51.369  6219  6219 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 18:56:51.369  6219  6219 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 18:56:51.409  6219  6258 D OpenGLRenderer: Render dirty regions requested: true
,09-06 18:56:51.419  1014  1525 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-06 18:56:51.419  1014  1525 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 18:56:51.419  1014  1525 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 18:56:51.419  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 18:56:51.419  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!,
,09-06 18:56:51.429  6219  6219 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-06 18:56:51.429  6219  6219 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-06 18:56:51.439   258   258 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-06 18:56:51.449  1014  1817 D InputDispatcher: Focus entered window: 6219
,09-06 18:56:51.459  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0,
09-06 18:56:51.459  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101,
,09-06 18:56:51.459  6219  6219 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 18:56:51.459  6219  6258 I OpenGLRenderer: Initialized EGL, version 1.4
,09-06 18:56:51.469  6219  6258 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-06 18:56:51.469  6219  6258 D OpenGLRenderer: Enabling debug mode 0
,09-06 18:56:51.479  6219  6219 V ActivityThread: updateVisibility : ActivityRecord{22d21c96 token=android.os.BinderProxy@12372258 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-06 18:56:51.509  1014  1347 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 18:56:51.509  1174  1174 D PanelView: There is/are notification(s) 
09-06 18:56:51.519  1014  6261 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 18:56:51.529  1014  1044 I ActivityManager: Displayed Component not be shown by security: +563ms (total +651ms)
,09-06 18:56:51.529  1781  1781 I SamsungIME: getCurrentCandidateView
09-06 18:56:51.529  1014  1044 W ActivityManager: mDVFSHelper.release()
,09-06 18:56:51.529  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2016c2fa u0 com.test.thalitest/.MainActivity t128} time:110994
,09-06 18:56:51.529  6219  6219 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-06 18:56:51.529  6219  6219 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@12372258 time:110999
,09-06 18:56:51.539   258   449 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-06 18:56:51.539   258  1157 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-06 18:56:51.599  1781  1781 D SamsungIME: Dismiss ExpandCandiate
,09-06 18:56:51.619  6219  6219 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6219
,09-06 18:56:51.739  1781  1781 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 18:56:51.759  6219  6219 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-06 18:56:51.769  1781  1781 I SamsungIME: getDebugLevel  : 0x4f4c
,09-06 18:56:51.789  1781  1781 I SamsungIME: KeybaordView init() : load resources
,09-06 18:56:51.809  1781  1781 I SamsungIME: getCurrentKeyboard
09-06 18:56:51.809  1781  1781 I SamsungIME: getTextKeyboard
,09-06 18:56:51.829  1781  1781 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-06 18:56:51.859  6219  6263 D jxcore_app_log: JniHelper::setJavaVM(0xb72c8328), pthread_self() = -1216411504
,09-06 18:56:51.869  6219  6263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-06 18:56:51.869  6219  6263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-06 18:56:51.869  6219  6263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-06 18:56:51.869  6219  6263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-06 18:56:51.869  6219  6263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
09-06 18:56:51.869  6219  6263 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce8d746 added. We now have 1 listener(s)
,09-06 18:56:51.869  6219  6263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-06 18:56:51.879  6219  6263 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 18:56:51.879  6219  6263 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 18:56:51.879  6219  6263 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-06 18:56:51.879  6219  6263 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22e9c45d added. We now have 1 listener(s)
,09-06 18:56:51.879  6219  6263 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:56:51.889  6219  6263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-06 18:56:51.889  6219  6263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-06 18:56:51.889  6219  6263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-06 18:56:51.889  6219  6263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-06 18:56:51.889  6219  6263 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-06 18:56:51.889  6219  6263 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:56:51.899  6219  6263 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-06 18:56:51.899  6219  6263 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-06 18:56:51.899  6219  6263 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:56:51.899  6219  6263 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:56:51.899  6219  6263 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:56:51.899  6219  6263 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:56:51.899  6219  6263 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:56:51.899  6219  6263 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:56:51.899  6219  6263 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:56:51.899  6219  6263 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:56:51.899  6219  6263 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-06 18:56:51.899  6219  6263 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:56:51.899  6219  6263 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-06 18:56:51.909  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:56:51.909  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:56:51.939  6219  6219 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-06 18:56:52.349  1781  6266 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-06 18:56:52.429  6219  6271 W jxcore-log: Initializing JXcore engine
09-06 18:56:52.429  6219  6271 W jxcore-log: JXcore engine is ready
,09-06 18:56:52.489  1903  1903 E audit   : type=1400 msg=audit(1473181012.489:205): avc:  denied  { ioctl } for  pid=6271 comm="Thread-1078" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-06 18:56:52.499  1903  1903 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-06 18:56:52.499  1903  1903 E audit   : type=1300 msg=audit(1473181012.489:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9d8008f8 items=0 ppid=311 ppcomm=main pid=6271 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1078" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-06 18:56:52.499  1903  1903 E audit   : type=1320 msg=audit(1473181012.489:205): 
,09-06 18:56:52.509  6219  6271 W jxcore-log: Starting JXcore engine
,09-06 18:56:52.619  6219  6271 W jxcore-log: Platform android
09-06 18:56:52.619  6219  6271 W jxcore-log: 
09-06 18:56:52.619  6219  6271 W jxcore-log: Process ARCH arm
09-06 18:56:52.619  6219  6271 W jxcore-log: 
,09-06 18:56:52.819  6219  6271 I jxcore-log: JXcore Cordova bridge is ready!
09-06 18:56:52.819  6219  6271 I jxcore-log: 
,09-06 18:56:52.819  6219  6271 W jxcore-log: JXcore engine is started
,09-06 18:56:52.829  6219  6263 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-06 18:56:52.829  6219  6219 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-06 18:56:53.459   291   291 E SMD     : DCD OFF,
,09-06 18:56:54.639  5418  5418 D FactoryTest: Not factory mode
,09-06 18:56:54.639  5418  5418 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-06 18:56:54.639  5418  5418 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-06 18:56:54.639  5418  5418 D MTPRx   : still no open session command from host, so toast
,09-06 18:56:54.639  5418  5418 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
09-06 18:56:54.639  5418  5418 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114107
,09-06 18:56:54.639  5418  5418 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 ,
09-06 18:56:54.639  1014  1474 E PersonaManagerService: inState():  stateMachine is null !!
09-06 18:56:54.639  1014  1474 I PersonaManagerService: PersonaId don't exist,
09-06 18:56:54.639  1014  1474 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false,
,09-06 18:56:54.649  1014  1474 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings,
,09-06 18:56:54.649  1014  1474 W ActivityManager: userId = 0, bbcId = -10000,
09-06 18:56:54.649  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:56:54.649  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-06 18:56:54.649  1014  1474 W ActivityManager: mDVFSHelper.acquire()
,09-06 18:56:54.669  1014  1474 D PersonaManager: isKioskContainerExistOnDevice
,09-06 18:56:54.669  1014  1474 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 18:56:54.669  1014  1474 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 18:56:54.669  1014  1474 D InputDispatcher: Focused application set to: xxxx
,09-06 18:56:54.679  1014  1474 D InputDispatcher: Focus left window: 6219
,09-06 18:56:54.679  5418  5418 E MTPRx   : started activity for popup
,09-06 18:56:54.679  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 18:56:54.679  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 18:56:54.699  5418  5418 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-06 18:56:54.699  5418  5418 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-06 18:56:54.699  5418  5418 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-06 18:56:54.699  5418  5418 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:56:54.699  5418  5418 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 18:56:54.699  5418  5418 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 18:56:54.719  5418  5418 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-06 18:56:54.719  1014  3292 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-06 18:56:54.719  1014  3292 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-06 18:56:54.719  1014  3292 D InputDispatcher: Focused application set to: xxxx
,09-06 18:56:54.719  1014  3292 D InputDispatcher: Focus entered window: 6219
,09-06 18:56:54.729  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 18:56:54.729  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 18:56:54.729  1014  1347 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
09-06 18:56:54.729  1014  1347 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@3bf07a75 attribute=null, token = android.os.BinderProxy@1a490605
,09-06 18:56:54.769  5418  5418 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-06 18:56:54.769  5418  5418 D PhoneWindow: *FMB* installDecor mIsFloating : true,
09-06 18:56:54.769  5418  5418 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-06 18:56:54.789  6219  6219 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-06 18:56:54.789  6219  6219 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-06 18:56:54.789  6219  6219 D io.jxcore.node.LifeCycleMonitor: onActivityResumed,
09-06 18:56:54.789  6219  6219 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-06 18:56:54.789  1014  1474 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-06 18:56:54.789  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
09-06 18:56:54.789  1014  1474 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 18:56:54.789  1014  1474 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 18:56:54.789  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-06 18:56:54.809  6219  6219 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 18:56:54.809  6219  6219 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-06 18:56:54.819  6219  6219 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2e58bc1f Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@7843327, 16908290=android.view.AbsSavedState$1@7843327}, android:focusedViewId=100}]}]
09-06 18:56:54.819  6219  6219 V ActivityThread: updateVisibility : ActivityRecord{22d21c96 token=android.os.BinderProxy@12372258 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-06 18:56:54.819  6219  6219 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-06 18:56:54.819  6219  6219 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-06 18:56:54.819  6219  6219 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-06 18:56:54.819  6219  6219 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@12372258 time:114281
,09-06 18:56:54.819  1014  1491 D PersonaManager: isKioskContainerExistOnDevice
,09-06 18:56:55.149   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 18:56:56.149   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:56:56.459   291   291 E SMD     : DCD OFF,
,09-06 18:56:56.579  1014  1205 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 18:56:56.579  1014  1205 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4272, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-06 18:56:56.579  1014  1205 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-06 18:56:56.579  1014  1205 D BatteryService: stay LED for charging
09-06 18:56:56.579  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 18:56:56.589  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 18:56:56.589  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 18:56:56.589  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-06 18:56:56.589  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 18:56:56.589  1014  1014 I MotionRecognitionService: Plugged
,09-06 18:56:56.599  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 18:56:56.599  2650  2650 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 18:56:56.599  2650  2723 D HeadsetStateMachine: Disconnected process message: 10
,09-06 18:56:56.619  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:56:56.619  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:56:56.619  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:56:57.149  1014  2766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-06 18:56:57.149   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 18:56:57.649  1014  1039 W ActivityManager: mDVFSHelper.release(),
,09-06 18:56:58.149   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 18:56:58.169  1014  2724 D SSRM:n  : SIOP:: AP = 310,
,09-06 18:56:59.149   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:56:59.459   291   291 E SMD     : DCD OFF,
,09-06 18:56:59.999  1014  1092 V AlarmManager: waitForAlarm result :8,
,09-06 18:57:00.149   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-06 18:57:00.539  1014  1092 V AlarmManager: waitForAlarm result :4,
,09-06 18:57:00.549  1014  1092 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-06 18:57:00.559  1014  1014 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-06 18:57:00.569  1014  1014 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-06 18:57:00.569  1014  1014 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-06 18:57:00.569  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-06 18:57:00.569  1174  1174 D KeyguardUpdateMonitor: handleTimeUpdate
,09-06 18:57:00.579  1932  1932 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-06 18:57:00.579  1174  1174 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-06 18:57:00.589  1174  1174 D SecKeyguardClockView: HomeTimezone(): 1
,09-06 18:57:00.609  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 18:57:00.609  1174  1174 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-06 18:57:00.609  1174  1174 I KeyguardEffectViewController: *** don't update sliding image ***
,09-06 18:57:00.629  1014  3293 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:00.629  1014  3293 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-06 18:57:00.629  1014  3293 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:00.629  1014  3293 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:00.629  1014  3293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:00.649  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 18:57:00.649  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 18:57:00.659  1174  1174 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 18:57:00.679  1174  1174 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-06 18:57:00.699  3778  3778 D ConnectivityManager: CallingUid : 10012, CallingPid : 3778
,09-06 18:57:00.699  1014  1524 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 18:57:00.699  1014  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-06 18:57:00.699  1014  1126 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,09-06 18:57:00.699  1014  1126 D ConnectivityService: apparently satisfied.  currentScore=60
,09-06 18:57:00.699  3778  6281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 18:57:00.759  3778  6282 W DriveInitializer: Background init thread started
,09-06 18:57:00.779   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-06 18:57:00.779   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 18:57:00.779  3778  6282 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files,
,09-06 18:57:00.829  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:00.829  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.phenotype.service.sync.PhenotypeConfigurator; callingUser = 0; userId(target) = 0
,09-06 18:57:00.839  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:00.839  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:00.839  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:00.869  1014  1257 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:00.869  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-06 18:57:00.869  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:00.869  1014  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:00.869  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:00.879  3778  6282 W DriveInitializer: Background init thread ended
,09-06 18:57:00.889  1014  1491 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-06 18:57:00.889  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-06 18:57:00.919  1014  1817 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:00.929  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:00.929  1014  1817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:00.929  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:00.929  1014  1054 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-06 18:57:00.949  1014  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:00.949  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:00.949  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:00.949  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:00.959  1932  1932 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-06 18:57:00.969  1932  1932 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 18:57:00.999  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:00.999  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:00.999  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:01.089  1014  1491 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-06 18:57:01.089  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-06 18:57:01.089  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:01.089  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:01.089  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:01.089  1932  1932 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 18:57:01.099  1932  1932 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-06 18:57:01.109  1014  3291 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:01.119  1014  3291 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:01.119  1014  3291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:01.119  1014  3291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:01.199  1014  1205 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-06 18:57:01.199  1014  1205 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-06 18:57:01.209  1014  1205 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:01.209  1014  1205 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:01.209  1014  1205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:01.209  1932  6290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:01.209   281   996 D EnterpriseController: uids 10012
09-06 18:57:01.209   281   996 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 18:57:01.209   281   996 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-06 18:57:01.219  1932  6290 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 18:57:01.219  1932  6290 I qtaguid : Tagging socket 62 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1932, getuid(): 10012
,09-06 18:57:01.279  1932  6290 I qtaguid : Tagging socket 66 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1932, getuid(): 10012
,09-06 18:57:01.509  1014  1522 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:01.509  1014  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-06 18:57:01.519  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:01.519  1014  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:01.519  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:01.539  3778  6294 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-06 18:57:01.539  3778  6294 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-06 18:57:01.579  1932  6290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:01.579   281   996 D EnterpriseController: uids 10012
09-06 18:57:01.579   281   996 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 18:57:01.579   281   996 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-06 18:57:01.619  1932  6290 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 18:57:01.619  1932  6290 I qtaguid : Tagging socket 67 with tag 1000120300000000{268440067,0} for uid -1, pid: 1932, getuid(): 10012
,09-06 18:57:01.659  1932  6290 I qtaguid : Tagging socket 70 with tag 1000120300000000{268440067,0} for uid -1, pid: 1932, getuid(): 10012
,09-06 18:57:01.909  1014  1480 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:01.909  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-06 18:57:01.909  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:01.909  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:01.909  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:01.919  1932  6290 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:01.919  1932  6290 I qtaguid : Tagging socket 67 with tag 1000120300000000{268440067,0} for uid -1, pid: 1932, getuid(): 10012
,09-06 18:57:01.949  1014  1525 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:01.949  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:01.949  1014  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:01.949  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:01.999  1014  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:02.009  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:02.009  1014  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:02.009  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:02.009  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:02.009  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:02.009  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:02.009  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:02.019  6298  6298 E Zygote  : MountEmulatedStorage()
,09-06 18:57:02.019  6298  6298 E Zygote  : v2
09-06 18:57:02.019  6298  6298 I libpersona: KNOX_SDCARD checking this for 10012
09-06 18:57:02.019  6298  6298 I libpersona: KNOX_SDCARD not a persona,
09-06 18:57:02.019  1014  1474 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6298 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-06 18:57:02.029  6298  6298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:02.029  6298  6298 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-06 18:57:02.029  6298  6298 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-06 18:57:02.039  1014  1257 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:02.039  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:02.039  1014  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:02.039  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:02.069  6298  6298 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:02.069  6298  6298 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:02.089  6298  6298 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-06 18:57:02.089  6298  6298 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 18:57:02.089  1014  1525 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:02.089  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:02.089  1014  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:02.099  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:02.109  1932  6290 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.phenotype
,09-06 18:57:02.109  1014  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:02.119  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:02.119  1014  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:02.119  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:02.119  1932  6290 I PhenotypeSyncScheduler: Cancel all previously scheduled adaptive polling
,09-06 18:57:02.129  6298  6298 I MultiDex: VM with version 2.1.0 has multidex support
09-06 18:57:02.129  6298  6298 I MultiDex: install
09-06 18:57:02.129  6298  6298 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-06 18:57:02.159  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:02.159  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:02.159  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:02.179  6298  6298 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...,
,09-06 18:57:02.239  6298  6298 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 18:57:02.239  6298  6298 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1472acb8: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-06 18:57:02.239  6298  6298 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-06 18:57:02.259  6298  6298 D ChimeraCfgMgr: Reading stored module config
,09-06 18:57:02.339  6298  6298 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-06 18:57:02.339  6298  6298 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-06 18:57:02.349  6298  6318 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-06 18:57:02.429   286   720 D WVCdm   : Instantiating CDM.
,09-06 18:57:02.429   286   679 I WVCdm   : CdmEngine::OpenSession
,09-06 18:57:02.429   286   679 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-06 18:57:02.449   286   679 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-06 18:57:02.459   291   291 E SMD     : DCD OFF
,09-06 18:57:02.469   286   679 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
09-06 18:57:02.469   286   679 D DrmWidevineDash: Service_Initialize: starts!
09-06 18:57:02.469   286   679 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-06 18:57:02.469   286   679 D QSEECOMAPI: : App is not loaded in QSEE
09-06 18:57:02.469   286   679 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-06 18:57:02.469   286   679 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-06 18:57:02.469   286   679 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-06 18:57:02.469   286   679 D QSEECOMAPI: : App is not loaded in QSEE
09-06 18:57:02.469   286   679 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-06 18:57:02.469   286   679 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-06 18:57:02.469   286   679 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-06 18:57:02.469   286   679 D QSEECOMAPI: : App is not loaded in QSEE
,09-06 18:57:02.489  6298  6306 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,09-06 18:57:02.489  6298  6306 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:02.489  6298  6306 I System.out: (HTTPLog)-Static: isShipBuild true
09-06 18:57:02.489  6298  6306 I System.out: (HTTPLog)-Thread-1057-721730181: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-06 18:57:02.489  6298  6306 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:02.489   281   996 D EnterpriseController: uids 10012
09-06 18:57:02.489   281   996 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 18:57:02.489   281   996 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-06 18:57:02.499  6298  6306 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 18:57:02.499  6298  6306 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6298, getuid(): 10012
,09-06 18:57:02.499   286   679 D QSEECOMAPI: : Loaded image: APP id = 11
,09-06 18:57:02.499   286   679 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-06 18:57:02.499   286   679 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
,09-06 18:57:02.499   286   679 D QSAPPSVER: qsapps_get_capabilities: returns 0
09-06 18:57:02.499   286   679 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb176c000
09-06 18:57:02.499   286   679 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb176c000
,09-06 18:57:02.499   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.509   422   434 D DrmLibTime: got the req here! ret=0
09-06 18:57:02.509   422   434 D DrmLibTime: command id, time_cmd_id = 770
09-06 18:57:02.509   422   434 D DrmLibTime: time_getutcsec starts!
09-06 18:57:02.509   422   434 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-06 18:57:02.509   422   434 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-06 18:57:02.509   422   434 D DrmLibTime: QSEE Time Listener: time_get_modem_time
09-06 18:57:02.509   422   434 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,09-06 18:57:02.509   422   434 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13
09-06 18:57:02.509   422   434 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
09-06 18:57:02.509   422   434 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
,09-06 18:57:02.509   422   434 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-06 18:57:02.509   331   413 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-06 18:57:02.509   331  6325 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
09-06 18:57:02.509   331  6325 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2
09-06 18:57:02.509   331  6325 D QC-time-services: offset is: 0 for base: 0
,09-06 18:57:02.509   422   434 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0
09-06 18:57:02.509   422   434 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
09-06 18:57:02.509   422   434 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1473181022
,09-06 18:57:02.509   422   434 D DrmLibTime: time_getutcsec returns 0, sec = 1473181022; nsec = 0
09-06 18:57:02.509   422   434 D DrmLibTime: time_getutcsec finished! 
09-06 18:57:02.509   422   434 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-06 18:57:02.509   422   434 D DrmLibTime: before calling ioctl to read the next time_cmd
09-06 18:57:02.509   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-06 18:57:02.509   331   413 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-06 18:57:02.539   286   679 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
09-06 18:57:02.539   286   679 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-06 18:57:02.539   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.539   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 18:57:02.539   286   679 D DrmWidevineDash: hlos api version =  9
09-06 18:57:02.539   286   679 D DrmWidevineDash: tz api version =  9
09-06 18:57:02.539   286   679 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-06 18:57:02.539   286   679 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
09-06 18:57:02.539   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.549   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 18:57:02.549   286   679 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-06 18:57:02.549   286   679 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-06 18:57:02.549   286   679 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb1921960
09-06 18:57:02.549   286   679 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
09-06 18:57:02.549   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.549   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 18:57:02.549   286   679 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-06 18:57:02.549   286   679 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-06 18:57:02.549   286   679 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb84e71d8, dataLength=8
09-06 18:57:02.549   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.549   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 18:57:02.549   286   679 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-06 18:57:02.559   286   679 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb84b42f0, wrapped_rsa_key_length=1280
09-06 18:57:02.559   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.559   286   679 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 18:57:02.559   286   679 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-06 18:57:02.559   286   679 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-06 18:57:02.559   286   720 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-06 18:57:02.559   286   720 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-06 18:57:02.559   286   720 I WVCdm   : CdmEngine::GenerateKeyRequest
09-06 18:57:02.559   286   720 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb84b7118, idLength=0xb174e730
09-06 18:57:02.559   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.569   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-06 18:57:02.569   286   720 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-06 18:57:02.569   286   720 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-06 18:57:02.569   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.569   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-06 18:57:02.569   286   720 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-06 18:57:02.569   286   720 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
09-06 18:57:02.569   286   720 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
09-06 18:57:02.569   286   720 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb174e746, maximum = 0xb174e747
,09-06 18:57:02.569   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.569   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 18:57:02.569   286   720 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
09-06 18:57:02.569   286   720 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-06 18:57:02.569   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.569   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 18:57:02.579   286   720 D DrmWidevineDash: hlos api version =  9
09-06 18:57:02.579   286   720 D DrmWidevineDash: tz api version =  9
09-06 18:57:02.579   286   720 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-06 18:57:02.579   286   720 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb174e7b4
09-06 18:57:02.579   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.579   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 18:57:02.579   286   720 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-06 18:57:02.579   286   720 D WVCdm   : PrepareKeyRequest: nonce=961620533
09-06 18:57:02.579   286   720 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb84b3e08
09-06 18:57:02.579   286   720 D DrmWidevineDash: message_length=1599, signature=0xb84b4450, signature_length=0xb174e714
09-06 18:57:02.579   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.719   286   720 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 18:57:02.719   286   720 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-06 18:57:02.719   286   286 I WVCdm   : CdmEngine::CloseSession
,09-06 18:57:02.719   286   286 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-06 18:57:02.729   286   286 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.729   286   286 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-06 18:57:02.729   286   286 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
,09-06 18:57:02.729   286   286 I WVCdm   : L3 Terminate.
09-06 18:57:02.729   286   286 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-06 18:57:02.729   286   286 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-06 18:57:02.729   286   286 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
,09-06 18:57:02.729   286   286 D DrmWidevineDash: Service_Uninitialize: starts!
09-06 18:57:02.729   286   286 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-06 18:57:02.729   286   286 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 11
,09-06 18:57:02.729   286   286 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-06 18:57:02.729   286   286 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-06 18:57:02.859  6298  6306 I qtaguid : Untagging socket 30
,09-06 18:57:03.339  6327  6327 I dex2oat : ----------------------------------------------------,
09-06 18:57:03.339  6327  6327 I dex2oat : <SS>: S T A R T I N G . . .
09-06 18:57:03.339  6327  6327 I dex2oat : <SS>: Zip is absent. Canceled.
09-06 18:57:03.339  6327  6327 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-06 18:57:03.369  6327  6327 I dex2oat : dex2oat took 26.210ms (threads: 4)
,09-06 18:57:03.379  6298  6306 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 18:57:03.379  6298  6306 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 18:57:03.379  6298  6306 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 18:57:03.379  6298  6306 I Adreno-EGL: Local Branch: 
09-06 18:57:03.379  6298  6306 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 18:57:03.379  6298  6306 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 18:57:03.379  6298  6306 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 18:57:03.509  6298  6306 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 18:57:03.509  6298  6306 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 18:57:03.509  6298  6306 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 18:57:03.509  6298  6306 I Adreno-EGL: Local Branch: 
09-06 18:57:03.509  6298  6306 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 18:57:03.509  6298  6306 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 18:57:03.509  6298  6306 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 18:57:03.559  6298  6306 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 18:57:03.559  6298  6306 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 18:57:03.559  6298  6306 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 18:57:03.559  6298  6306 I Adreno-EGL: Local Branch: 
09-06 18:57:03.559  6298  6306 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 18:57:03.559  6298  6306 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 18:57:03.559  6298  6306 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 18:57:03.769  1932  6297 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:03.769   281   996 D EnterpriseController: uids 10012
09-06 18:57:03.769   281   996 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 18:57:03.769   281   996 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-06 18:57:03.769  1932  6297 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 18:57:03.769  1932  6297 I qtaguid : Tagging socket 61 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1932, getuid(): 10012
,09-06 18:57:03.819  1932  6297 I qtaguid : Tagging socket 73 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1932, getuid(): 10012
,09-06 18:57:03.989  1014  1817 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:03.989  1014  1817 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-06 18:57:03.989  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:03.989  1014  1817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:03.989  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.039  1635  2136 I art     : Explicit concurrent mark sweep GC freed 1453(49KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 7MB/9MB, paused 709us total 31.842ms
,09-06 18:57:04.079  1014  3294 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:04.089  1014  3294 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:04.089  1014  3294 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:04.089  1014  3294 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.329  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-06 18:57:04.339  1014  1817 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:04.359  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:04.359  1014  1817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:04.359  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.419  1932  1942 I art     : Explicit concurrent mark sweep GC freed 83904(4MB) AllocSpace objects, 22(948KB) LOS objects, 39% free, 14MB/23MB, paused 1.463ms total 76.161ms
,09-06 18:57:04.429  1014  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:04.429  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:04.429  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:04.429  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.469  1932  1932 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=784628ed-a6d4-4035-8999-99f414be2abd
,09-06 18:57:04.619  1014  1480 I art     : Explicit concurrent mark sweep GC freed 41026(2MB) AllocSpace objects, 21(336KB) LOS objects, 33% free, 27MB/41MB, paused 2.665ms total 153.940ms
,09-06 18:57:04.619  1014  1480 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
09-06 18:57:04.619  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
09-06 18:57:04.619  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:04.619  1014  1480 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:04.619  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.659  1932  2106 W GCoreFlp: No location to return for getLastLocation()
,09-06 18:57:04.689  1014  3293 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:04.689  1014  3293 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:04.689  1014  3293 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:04.689  1014  3293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.689  3778  6334 D UdcContextInitService: registered all accounts: true
,09-06 18:57:04.689  1932  2111 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 18:57:04.699  1014  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:04.699  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:04.699  1014  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:04.699  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.699  1014  1524 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:04.699  1014  1524 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:04.699  1014  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:04.699  1014  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.709  1932  2128 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-06 18:57:04.829  1014  1525 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:04.829  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-06 18:57:04.829  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:04.829  1014  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:04.829  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.919  1932  2128 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-06 18:57:04.919  1932  2128 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-06 18:57:04.929  1932  6343 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:04.939   281   996 D EnterpriseController: uids 10012
09-06 18:57:04.939   281   996 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 18:57:04.939   281   996 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-06 18:57:04.939  1932  6343 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 18:57:04.949  1932  6343 I qtaguid : Tagging socket 82 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1932, getuid(): 10012
,09-06 18:57:04.949  1014  1522 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:04.949  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:04.949  1014  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:04.949  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.989  1014  1817 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:04.989  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:04.989  1014  1817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:04.989  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.989  1932  6348 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 18:57:04.989  1932  6339 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 18:57:04.989  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-06 18:57:04.999  1014  1474 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:04.999  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:04.999  1014  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:04.999  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:04.999  1932  6343 I qtaguid : Tagging socket 87 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1932, getuid(): 10012
,09-06 18:57:05.029  1014  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:05.029  1014  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:05.029  1014  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:05.029  1014  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:05.029  1932  6348 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 18:57:05.029  1932  6339 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-06 18:57:05.029  1014  1257 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:05.029  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:05.029  1014  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:05.029  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:05.059  1014  1522 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:05.059  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:05.059  1014  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:05.059  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:05.059  1932  6348 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-06 18:57:05.059  1932  6339 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
09-06 18:57:05.059  1932  6339 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-06 18:57:05.069  1932  6339 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-06 18:57:05.109  1014  1480 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 18:57:05.149  1932  6339 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:05.149   281   996 D EnterpriseController: uids 10012
09-06 18:57:05.149   281   996 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 18:57:05.149   281   996 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-06 18:57:05.149  1932  6339 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-06 18:57:05.149  1932  6339 I qtaguid : Tagging socket 89 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1932, getuid(): 10012
,09-06 18:57:05.159   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:57:05.199  1932  6339 I qtaguid : Tagging socket 92 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1932, getuid(): 10012
,09-06 18:57:05.239  1932  6343 I qtaguid : Untagging socket 82
,09-06 18:57:05.249  1932  2128 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-06 18:57:05.459   291   291 E SMD     : DCD OFF
,09-06 18:57:05.509  1014  1347 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 18:57:05.519  1932  6339 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:05.519  1932  6339 I qtaguid : Tagging socket 89 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1932, getuid(): 10012
,09-06 18:57:05.669  1014  1525 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 18:57:05.669  1932  6339 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:05.669  1932  6339 I qtaguid : Tagging socket 89 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1932, getuid(): 10012
,09-06 18:57:05.779  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-06 18:57:05.779  6219  6271 I jxcore-log: 
,09-06 18:57:05.779  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-06 18:57:05.779  6219  6271 I jxcore-log: 
,09-06 18:57:05.789  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:05.789  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:05.789  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:05.789  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:05.789  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:05.789  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:05.789  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:05.789  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:05.789  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:05.789  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-06 18:57:05.789  6219  6271 I jxcore-log: 
,09-06 18:57:05.799  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-06 18:57:05.799  6219  6271 I jxcore-log: 
,09-06 18:57:05.819  1014  1474 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-06 18:57:05.829  1932  6339 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:05.829  1932  6339 I qtaguid : Tagging socket 89 with tag 11065b5800000000{285629272,0} for uid -1, pid: 1932, getuid(): 10012
,09-06 18:57:06.159   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:57:06.449  6219  6271 D executeNativeTests: Running unit tests
,09-06 18:57:06.529  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:06.529  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 added. We now have 2 listener(s)
,09-06 18:57:06.539  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-06 18:57:06.539  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:06.539  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:06.539  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:06.539  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed added. We now have 2 listener(s)
09-06 18:57:06.539  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:06.539  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:57:06.539  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:06.539  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:06.539  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:06.539  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:06.539  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:06.539  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:06.539  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:06.539  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:06.539  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:06.539  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:06.539  6219  6271 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:57:06.549  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:06.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 18:57:06.549  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 18:57:06.549  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-06 18:57:06.549  6219  6271 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-06 18:57:06.549  6219  6271 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 18:57:06.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 18:57:06.549  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 18:57:06.549  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 18:57:06.549  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:06.549  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.549  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.549  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.549  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:06.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:06.549  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 removed from the list
09-06 18:57:06.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.549  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed removed from the list
,09-06 18:57:06.549  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 18:57:06.549  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.549  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:06.549  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:06.549  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-06 18:57:06.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.549  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
,09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
09-06 18:57:06.559  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.559  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:06.559  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.559  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.559  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.559  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.559  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.559  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-06 18:57:06.559  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.559  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.559  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.559  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:06.559  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.559  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.559  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.559  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.559  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
,09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55],
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610],
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610],
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 18:57:06.559  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 18:57:06.559  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.559  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-06 18:57:06.559  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.559  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.559  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.559  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.569  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-06 18:57:06.569  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.569  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.569  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.569  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.569  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.569  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:06.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-06 18:57:06.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.569  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.569  6219  6271 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 18:57:06.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:06.569  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:06.569  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:06.569  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:06.569  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:06.569  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:06.569  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:06.569  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:06.569  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:06.569  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:06.579  6219  6271 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:57:06.579  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 18:57:06.579  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:57:06.579  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:57:06.579  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:06.579  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 18:57:06.579  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:06.579  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 18:57:06.589  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:06.589  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 18:57:06.599  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:57:06.599  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-06 18:57:06.599  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-06 18:57:06.599  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 18:57:06.599  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 18:57:06.609  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 18:57:06.619  2650  2666 D BtGatt.GattService: registerClient() - UUID=db4ce128-e53e-4090-9183-cb528e58e497
,09-06 18:57:06.639  1014  1525 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 18:57:06.639  1014  1525 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4261, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-06 18:57:06.639  1014  1525 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-06 18:57:06.639  1014  1525 D BatteryService: stay LED for charging
,09-06 18:57:06.639  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 18:57:06.649  1014  1014 I MotionRecognitionService: Plugged
,09-06 18:57:06.649  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 18:57:06.649  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 18:57:06.649  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 18:57:06.649  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 18:57:06.649  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 18:57:06.659  2650  2719 D BtGatt.GattService: onClientRegistered() - UUID=db4ce128-e53e-4090-9183-cb528e58e497, clientIf=6
,09-06 18:57:06.669  6219  6229 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 18:57:06.669  2650  2994 D BtGatt.GattService: start scan with filters
,09-06 18:57:06.669  2650  2650 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 18:57:06.669  2650  2723 D HeadsetStateMachine: Disconnected process message: 10
,09-06 18:57:06.669  2650  2722 D BtGatt.ScanManager: handling starting scan
,09-06 18:57:06.669  2650  2722 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ec5292f
,09-06 18:57:06.669  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 18:57:06.669  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 18:57:06.669  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 18:57:06.669  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 18:57:06.679  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:57:06.679  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:06.679  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:57:06.679  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:57:06.679  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:06.679  2650  2719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 18:57:06.679  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.679  2650  2722 D BtGatt.ScanManager: allow scan with filters
09-06 18:57:06.689  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 18:57:06.689  2650  2722 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 18:57:06.689  2650  2722 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-06 18:57:06.689  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 18:57:06.689  6219  6271 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 18:57:06.689  2650  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 18:57:06.689  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.689  2650  2722 D BtGatt.ScanManager: Starting BLE batch scan
09-06 18:57:06.689  2650  2722 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 18:57:06.699  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:06.699  6219  6271 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 18:57:06.699  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.699  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 18:57:06.699  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.699  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 18:57:06.699  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 18:57:06.699  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:06.699  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:06.699  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-06 18:57:06.699  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 18:57:06.699  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 18:57:06.699  2650  2660 D BtGatt.GattService: stopScan() - queue size =1
,09-06 18:57:06.699  2650  5343 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 18:57:06.699  2650  2719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 18:57:06.699  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.699  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 18:57:06.699  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 18:57:06.699  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-06 18:57:06.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 18:57:06.709  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 18:57:06.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:06.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 18:57:06.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped,
09-06 18:57:06.709  2650  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 18:57:06.709  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:06.709  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-06 18:57:06.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:06.709  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
09-06 18:57:06.709  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:06.709  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.709  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.709  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.709  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:06.709  6219  6271 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 18:57:06.709  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:06.709  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:06.709  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:06.719  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:06.719  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:06.719  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:06.719  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:06.719  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:06.719  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:06.719  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:06.719  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:06.719  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:06.719  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:06.729  6219  6271 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:57:06.729  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:06.729  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:57:06.729  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:57:06.729  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:06.729  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 18:57:06.729  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 18:57:06.729  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:06.729  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:06.729  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 18:57:06.729  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:57:06.739  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 18:57:06.739  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 18:57:06.739  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 18:57:06.739  2650  2994 D BtGatt.GattService: registerClient() - UUID=4553320c-d361-4f46-95db-e5af0c3a7e67
,09-06 18:57:06.749  2650  2722 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 6
,09-06 18:57:06.749  2650  2722 D BtGatt.ScanManager: filter size is 1
,09-06 18:57:06.749  2650  2722 D BtGatt.ScanManager: delete FilterIndex - 3
,09-06 18:57:06.759  2650  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 18:57:06.759  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.759  2650  2722 D BtGatt.ScanManager: stopping BLe Batch
,09-06 18:57:06.759  2650  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 18:57:06.759  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:06.759  2650  2722 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 18:57:06.769  2650  2719 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 18:57:06.769  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.779  2650  2719 D BtGatt.GattService: onClientRegistered() - UUID=4553320c-d361-4f46-95db-e5af0c3a7e67, clientIf=6
,09-06 18:57:06.779  6219  6227 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 18:57:06.779  2650  2666 D BtGatt.GattService: start scan with filters
,09-06 18:57:06.779  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 18:57:06.779  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-06 18:57:06.789  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 18:57:06.789  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 18:57:06.789  2650  2722 D BtGatt.ScanManager: handling starting scan
,09-06 18:57:06.789  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:06.789  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:06.789  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-06 18:57:06.789  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 18:57:06.799  2650  2719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 18:57:06.799  6219  6271 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 18:57:06.799  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.799  2650  2722 D BtGatt.ScanManager: allow scan with filters
,09-06 18:57:06.799  2650  2722 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 18:57:06.799  2650  2722 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 18:57:06.799  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:06.799  6219  6271 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 18:57:06.799  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.799  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 18:57:06.799  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.799  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 18:57:06.799  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-06 18:57:06.799  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:06.809  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:06.809  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:06.809  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 18:57:06.809  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 18:57:06.809  2650  2660 D BtGatt.GattService: stopScan() - queue size =1
,09-06 18:57:06.809  2650  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 18:57:06.809  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:06.809  2650  2722 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 18:57:06.809  2650  2722 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 18:57:06.809  2650  2994 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 18:57:06.809  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-06 18:57:06.809  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 18:57:06.809  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 18:57:06.809  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-06 18:57:06.809  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 18:57:06.809  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:06.819  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 18:57:06.819  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 18:57:06.819  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 18:57:06.819  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:06.819  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.819  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.819  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:06.819  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.819  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.819  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.819  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.819  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:06.819  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.819  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.819  2650  2719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 18:57:06.819  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.819  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.819  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.819  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.819  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
,09-06 18:57:06.819  6219  6271 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-06 18:57:06.819  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 18:57:06.819  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:06.819  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:06.819  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:06.829  2650  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-06 18:57:06.829  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.829  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:06.829  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:06.829  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:06.829  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:06.829  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:06.829  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:06.829  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:06.829  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:06.839  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:06.839  6219  6271 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:57:06.839  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:06.839  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:06.839  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-06 18:57:06.839  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:57:06.839  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:57:06.849  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:06.849  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 18:57:06.849  2650  2722 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 7
,09-06 18:57:06.849  2650  2722 D BtGatt.ScanManager: filter size is 1
09-06 18:57:06.849  2650  2722 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 18:57:06.849  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 18:57:06.849  2650  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 18:57:06.849  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.859  2650  2722 D BtGatt.ScanManager: stopping BLe Batch,
,09-06 18:57:06.859  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 18:57:06.859  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:57:06.859  2650  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 18:57:06.859  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:06.859  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-06 18:57:06.859  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 18:57:06.859  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-06 18:57:06.859  2650  2722 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 18:57:06.869  2650  2666 D BtGatt.GattService: registerClient() - UUID=1ef5ea35-a91f-4829-81a8-79dc580ab250
,09-06 18:57:06.869  2650  2719 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 18:57:06.869  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.909  2650  2719 D BtGatt.GattService: onClientRegistered() - UUID=1ef5ea35-a91f-4829-81a8-79dc580ab250, clientIf=6
,09-06 18:57:06.909  6219  6227 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 18:57:06.909  2650  5343 D BtGatt.GattService: start scan with filters
,09-06 18:57:06.909  2650  2722 D BtGatt.ScanManager: handling starting scan
,09-06 18:57:06.909  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-06 18:57:06.909  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 18:57:06.909  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-06 18:57:06.909  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 18:57:06.919  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false,
09-06 18:57:06.919  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 18:57:06.919  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:06.919  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 18:57:06.919  6219  6271 I io.jxcore.node.ConnectionHelper: start: OK
,09-06 18:57:06.919  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-06 18:57:06.919  2650  2719 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-06 18:57:06.919  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:06.919  2650  2722 D BtGatt.ScanManager: allow scan with filters
,09-06 18:57:06.919  2650  2722 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 18:57:06.919  2650  2722 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 18:57:06.919  6219  6271 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-06 18:57:06.919  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.919  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-06 18:57:06.919  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.929  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-06 18:57:06.929  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 18:57:06.929  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:06.929  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-06 18:57:06.929  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:06.929  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 18:57:06.929  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 18:57:06.929  2650  2666 D BtGatt.GattService: stopScan() - queue size =1
,09-06 18:57:06.929  2650  5343 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 18:57:06.929  2650  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 18:57:06.929  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:06.929  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:57:06.929  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 18:57:06.929  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 18:57:06.929  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 18:57:06.929  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 18:57:06.929  2650  2722 D BtGatt.ScanManager: Starting BLE batch scan
09-06 18:57:06.929  2650  2722 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-06 18:57:06.929  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:57:06.929  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 18:57:06.929  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 18:57:06.929  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 18:57:06.929  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:06.939  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-06 18:57:06.939  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:06.939  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:06.939  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.939  6219  6271 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 18:57:06.939  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:06.939  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-06 18:57:06.939  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.939  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:06.939  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
,09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.939  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.939  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:06.939  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:06.939  2650  2719 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 18:57:06.939  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:06.939  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.939  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.939  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
,09-06 18:57:06.939  6219  6271 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-06 18:57:06.939  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.939  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.939  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.939  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.939  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.939  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.939  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.939  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.939  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.939  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.939  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.939  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.939  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.939  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 18:57:06.939  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.939  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.939  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.939  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.939  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.939  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.939  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.939  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.939  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.939  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.939  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.939  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.939  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.949  2650  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 18:57:06.949  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:06.949  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.949  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.949  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.949  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.949  6219  6271 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-06 18:57:06.949  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.949  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.949  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.949  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.949  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.949  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.949  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.949  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.949  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.949  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.949  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.949  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.949  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.949  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.949  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.949  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.949  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.949  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.949  6219  6271 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-06 18:57:06.949  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.949  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.949  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.949  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.949  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.949  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.949  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.949  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.949  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.949  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.949  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.949  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.949  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.949  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.959  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 18:57:06.959  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 18:57:06.959  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-06 18:57:06.959  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-06 18:57:06.959  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.959  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.959  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.959  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.959  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.959  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.959  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.959  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.959  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.959  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.959  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.959  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.959  6219  6271 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:57:06.959  6219  6271 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-06 18:57:06.959  6219  6271 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:57:06.959  6219  6271 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-06 18:57:06.959  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-06 18:57:06.959  6219  6271 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-06 18:57:06.959  6219  6271 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 18:57:06.959  6219  6271 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-06 18:57:06.959  6219  6271 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:57:06.959  6219  6271 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 18:57:06.959  6219  6271 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-06 18:57:06.959  6219  6271 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:57:06.959  6219  6271 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-06 18:57:06.959  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-06 18:57:06.969  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-06 18:57:06.969  6219  6271 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-06 18:57:06.969  6219  6271 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-06 18:57:06.969  6219  6271 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-06 18:57:06.969  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.969  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.969  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.969  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.969  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.969  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-06 18:57:06.969  2650  2722 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 8
09-06 18:57:06.969  2650  2722 D BtGatt.ScanManager: filter size is 1
09-06 18:57:06.969  2650  2722 D BtGatt.ScanManager: delete FilterIndex - 5
09-06 18:57:06.969  6219  6357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1142)
09-06 18:57:06.969  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.969  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.969  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.969  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.969  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.969  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.969  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.969  6219  6358 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1142
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.969  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.969  6219  6271 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-06 18:57:06.969  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.969  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.969  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.969  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.969  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.969  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.969  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.969  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.969  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.969  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.969  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.969  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.969  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.979  6219  6271 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-06 18:57:06.979  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.979  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.979  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.979  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.979  2650  2719 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 18:57:06.979  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:06.979  6219  6271 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-06 18:57:06.979  6219  6271 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-06 18:57:06.979  2650  2722 D BtGatt.ScanManager: stopping BLe Batch
09-06 18:57:06.979  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 18:57:06.979  6219  6271 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-06 18:57:06.979  6219  6271 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 18:57:06.979  6219  6271 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-06 18:57:06.979  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 18:57:06.979  6219  6271 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-06 18:57:06.979  6219  6271 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-06 18:57:06.979  6219  6271 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-06 18:57:06.979  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 18:57:06.979  6219  6271 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-06 18:57:06.979  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.979  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.979  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.979  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6357 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.979  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.979  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.979  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.979  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.979  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.979  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.979  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.979  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.979  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.989  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.989  6219  6271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:06.989  6219  6357 D BluetoothSocket: connect(): myUserId = 0
09-06 18:57:06.989  6219  6357 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-06 18:57:06.989  2650  2719 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 18:57:06.989  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:06.989  2650  2722 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-06 18:57:06.989  2650  2719 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 18:57:06.989  2650  2719 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-06 18:57:06.989  6219  6271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-06 18:57:06.989  6219  6271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 18:57:06.989  6219  6219 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-06 18:57:06.989  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-06 18:57:06.989  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.989  6219  6271 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-06 18:57:06.989  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.989  6219  6219 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.989  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:06.989  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:06.989  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:06.989  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.989  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.989  6219  6359 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-06 18:57:06.989  6219  6359 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-06 18:57:06.999  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:57:06.999  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.999  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:06.999  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.999  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.999  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.999  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:06.999  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.999  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.999  6219  6219 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-06 18:57:06.999  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.999  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.999  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.999  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.999  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.999  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.999  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.999  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.999  2650  5343 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:06.999  6219  6357 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[108]}
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.999  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.999  6219  6271 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-06 18:57:06.999  6219  6271 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-06 18:57:06.999  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-06 18:57:06.999  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:06.999  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:06.999  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:06.999  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.999  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.999  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.999  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:06.999  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:06.999  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.999  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.999  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:06.999  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:06.999  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:06.999  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:07.009  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:07.009  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:07.009  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:07.009  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:07.009  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:07.009  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:07.009  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:07.009  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:07.009  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:07.009  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:07.009  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:07.009  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:07.009  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:07.009  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:07.009  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:07.009  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:07.009  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:07.009  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:07.009  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:07.009  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:07.009  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:07.009  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:07.009  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:07.009  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:07.009  6219  6271 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a416004 not in the list
09-06 18:57:07.009  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:07.009  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:07.009  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:07.009  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:07.009  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:07.009  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:07.009  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:07.009  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:07.009  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:07.009  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:07.009  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f49ed not in the list
09-06 18:57:07.009  6219  6271 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-06 18:57:07.009  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 18:57:07.009  6219  6271 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-06 18:57:07.009  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-06 18:57:07.009  6219  6271 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-06 18:57:07.009  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-06 18:57:07.019  6219  6271 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 18:57:07.019  6219  6271 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-06 18:57:07.019  6219  6271 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-06 18:57:07.019  6219  6271 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-06 18:57:07.019  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:07.019  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1fca5107 added. We now have 2 listener(s)
09-06 18:57:07.019  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:07.019  6219  6271 D BluetoothAdapter: enable()
09-06 18:57:07.019  6219  6271 D BluetoothAdapter: enable(): BT is already enabled..!
09-06 18:57:07.019  1014  1347 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 18:57:07.019  1014  1347 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 18:57:07.019  1014  1347 D SecContentProvider2: mCursor = null
09-06 18:57:07.029  1014  1347 D WifiService: setWifiEnabled: true pid=6219, uid=10155
09-06 18:57:07.029  1014  1347 W ActivityManager: Permission Denial: getCurrentUser() from pid=6219, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 18:57:07.029  1014  1347 W WifiService: Failed getting userId using ActivityManagerNative
09-06 18:57:07.029  1014  1347 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6219, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 18:57:07.029  1014  1347 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-06 18:57:07.029  1014  1347 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 18:57:07.029  1014  1347 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 18:57:07.029  1014  1347 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 18:57:07.029  1014  1347 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 18:57:07.029  1014  1347 D SettingsProvider: name = wifi_on
09-06 18:57:07.029  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:07.029  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@203ed234 added. We now have 3 listener(s)
09-06 18:57:07.029  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:07.039  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:07.039  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2703885d added. We now have 4 listener(s)
09-06 18:57:07.039  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:07.039  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:07.039  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4fb95d2 added. We now have 5 listener(s)
09-06 18:57:07.039  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:07.039  1014  3292 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 18:57:07.039  1014  3292 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 18:57:07.039  1014  3292 D SecContentProvider2: mCursor = null
09-06 18:57:07.039  1014  3292 D WifiService: setWifiEnabled: false pid=6219, uid=10155
09-06 18:57:07.039  1014  3292 D SettingsProvider: name = wifi_on
09-06 18:57:07.049  1014  1124 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-06 18:57:07.049  6219  6271 D BluetoothAdapter: disable()
09-06 18:57:07.049  1014  1525 D SettingsProvider: name = bluetooth_on
09-06 18:57:07.059  2098  2098 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 18:57:07.059  2098  2098 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
,09-06 18:57:07.059  1932  6341 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 18:57:07.059  1932  6341 I qtaguid : Tagging socket 82 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1932, getuid(): 10012
09-06 18:57:07.059  2098  2098 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 18:57:07.059  2098  2098 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 18:57:07.059  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:07.059  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:07.069  2650  2716 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-06 18:57:07.069  1014  1522 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:07.069  2650  2716 D BluetoothAdapterProperties: Setting state to 13
09-06 18:57:07.069  1014  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-06 18:57:07.069  2650  2716 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 18:57:07.069  2650  2716 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 18:57:07.069  2650  2716 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 18:57:07.069  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.069  1014  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:07.069  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 18:57:07.069  2650  2650 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 18:57:07.069  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:07.069  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:07.069  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:07.069  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:07.069  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:07.069  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:07.069  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:07.069  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:07.069  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-06 18:57:07.069  2650  2716 D BluetoothAdapterService: Autoconnection is available 
09-06 18:57:07.069  2650  2716 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 18:57:07.069  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:07.069  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:07.069  2650  2716 D BluetoothAdapterService: terminating service from this receiver
09-06 18:57:07.069  6219  6271 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:57:07.069  2650  2650 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24fc3ac9, channel: 19, state: LISTENING
,09-06 18:57:07.069  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
09-06 18:57:07.069  2650  2650 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24fc3ac9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1472acb8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@19c475cemSocket: android.net.LocalSocket@3fdf1cef impl:android.net.LocalSocketImpl@3caa53fc fd:FileDescriptor[74]
09-06 18:57:07.069  2650  2650 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3fdf1cef impl:android.net.LocalSocketImpl@3caa53fc fd:FileDescriptor[74]
,09-06 18:57:07.079  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.079  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:07.079  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:07.079  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:07.079  2098  2098 I wpa_supplicant: Scan aborted because the firmware maybe busy.
09-06 18:57:07.079  2098  2098 I wpa_supplicant: Therefore we will repeat the scan command after 1 seconds.
09-06 18:57:07.079  2098  2098 I wpa_supplicant: wlan0: Setting scan request: 1 sec 0 usec
,09-06 18:57:07.079  1014  1124 E WifiNative-wlan0: do suspend true
,09-06 18:57:07.079  2650  2716 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 18:57:07.079  2650  2716 D BluetoothAdapterProperties: mDiscovering is false
,09-06 18:57:07.079  1014  1474 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-06 18:57:07.079  2650  2716 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
09-06 18:57:07.079  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:07.079  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-06 18:57:07.079  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:07.089  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-06 18:57:07.089  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 18:57:07.089  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:07.089  1174  1174 D BluetoothTile:  getBluetoothState : 13
,09-06 18:57:07.089  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 18:57:07.089  1781  1781 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 18:57:07.089  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 18:57:07.099  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:07.099  1014  1027 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 18:57:07.099  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0,
09-06 18:57:07.099  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.099  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:07.099  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:07.099  1014  1522 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 18:57:07.099  2650  2719 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 18:57:07.099  2650  2719 D BluetoothAdapterProperties: Scan Mode:20
09-06 18:57:07.099  1014  1205 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 18:57:07.109  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 18:57:07.109  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 18:57:07.109  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:07.109  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:07.109  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:07.109  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:07.109  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:07.109  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:07.109  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:07.109  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:07.109  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:07.109  2650  2716 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
09-06 18:57:07.109  2650  2716 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
09-06 18:57:07.109  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:07.109  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:07.109  2650  2716 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-06 18:57:07.109  2650  2716 E bt-btif : cmd socket is not created
09-06 18:57:07.109  2650  4986 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-06 18:57:07.109  2650  2716 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 18:57:07.109  2650  2803 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-06 18:57:07.109  2650  2803 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-06 18:57:07.109  6219  6357 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a10dda0, channel: -1, state: INIT
,09-06 18:57:07.119  2650  2803 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:07.119  2650  2803 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:07.119  2650  2803 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 18:57:07.119  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:07.119  2650  2650 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b04ba85, channel: 5, state: LISTENING
09-06 18:57:07.119  2650  2650 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2b04ba85, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f3b9df6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9b620damSocket: android.net.LocalSocket@232a990b impl:android.net.LocalSocketImpl@1d46b3e8 fd:FileDescriptor[76]
09-06 18:57:07.119  6219  6357 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a10dda0, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16754d59, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@39593d1emSocket: android.net.LocalSocket@3ed259ff impl:android.net.LocalSocketImpl@313633cc fd:FileDescriptor[108]
09-06 18:57:07.119  2650  2650 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@232a990b impl:android.net.LocalSocketImpl@1d46b3e8 fd:FileDescriptor[76]
09-06 18:57:07.119  6219  6357 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3ed259ff impl:android.net.LocalSocketImpl@313633cc fd:FileDescriptor[108]
09-06 18:57:07.119  2650  2650 I BtOppRfcommListener: stopping Accept Thread
09-06 18:57:07.119  2650  2650 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f5b7a01, channel: 12, state: LISTENING
09-06 18:57:07.119  6219  6357 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1142)
09-06 18:57:07.119  2650  2650 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f5b7a01, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37325ad0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6e570a6mSocket: android.net.LocalSocket@1e67bae7 impl:android.net.LocalSocketImpl@2c72694 fd:FileDescriptor[80]
09-06 18:57:07.119  2650  2650 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e67bae7 impl:android.net.LocalSocketImpl@2c72694 fd:FileDescriptor[80]
,09-06 18:57:07.119  2650  4986 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 18:57:07.119  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 18:57:07.119  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:07.119  1014  1474 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 18:57:07.119  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 18:57:07.129  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:07.129  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.129  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:07.129  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 18:57:07.129  2650  2650 V BluetoothOppManager: cleanUp...
,09-06 18:57:07.129  1308  1308 D BluetoothPbap: Proxy object disconnected,
09-06 18:57:07.129  1308  1308 D PbapServerProfile: Bluetooth service disconnected
,09-06 18:57:07.139  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:07.139  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 18:57:07.149  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:07.149  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 18:57:07.149  1014  1474 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,09-06 18:57:07.149  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:07.149  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:07.149  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:07.149  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:07.159   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:57:07.169  1014  1474 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6367 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,09-06 18:57:07.169  6367  6367 E Zygote  : MountEmulatedStorage()
09-06 18:57:07.169  6367  6367 I libpersona: KNOX_SDCARD checking this for 10003
09-06 18:57:07.169  6367  6367 E Zygote  : v2
09-06 18:57:07.169  6367  6367 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:07.179  6367  6367 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:07.179  6367  6367 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-06 18:57:07.179  6367  6367 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:07.209  6367  6367 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:07.219  6367  6367 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:07.229  1635  2130 I art     : Explicit concurrent mark sweep GC freed 2522(100KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 909us total 25.177ms
,09-06 18:57:07.239  1014  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-06 18:57:07.249  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 18:57:07.249   281  1000 D CommandListener: Clearing all IP addresses on wlan0
,09-06 18:57:07.259  1014  1126 E ConnectivityService: updateNetworkInfo()
09-06 18:57:07.259  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 18:57:07.259  1014  1126 E ConnectivityService: updateNetworkInfo()
09-06 18:57:07.259  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-06 18:57:07.259  6367  6367 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-06 18:57:07.259  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:07.259  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 18:57:07.259  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.259  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.259  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.259  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.259  1014  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-06 18:57:07.259  1932  4357 V NativeCrypto: Read error: ssl=0xb77f6058: I/O error during system call, Connection timed out
09-06 18:57:07.269  1014  1123 D WifiP2pService: InactiveState{ what=131204 }
09-06 18:57:07.269  1014  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
09-06 18:57:07.269  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-06 18:57:07.269  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 18:57:07.269  1932  4357 V NativeCrypto: SSL shutdown failed: ssl=0xb77f6058: I/O error during system call, Broken pipe
09-06 18:57:07.269  1932  6341 I qtaguid : Untagging socket 82
09-06 18:57:07.269  1932  4357 E GCM     : Wifi connection closed with errorCode 20
09-06 18:57:07.269  1014  1027 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
09-06 18:57:07.269  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:07.269  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:07.269  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-06 18:57:07.269  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:07.269  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
09-06 18:57:07.269  1014  2215 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 18:57:07.269  1014  2215 I qtaguid : Tagging socket 361 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1014, getuid(): 1000
09-06 18:57:07.269  1014  2215 I qtaguid : Untagging socket 361
,09-06 18:57:07.279  1932  6341 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:07.279  1014  2215 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-06 18:57:07.279  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 18:57:07.279  1014  1146 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 18:57:07.279  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:07.279  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:07.279  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.279  1014  1014 D RttService: SCAN_AVAILABLE : 1,
09-06 18:57:07.289  1014  1147 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler },
09-06 18:57:07.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.289  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.289  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:57:07.289  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-06 18:57:07.289  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 18:57:07.289  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 18:57:07.289  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-06 18:57:07.289  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 18:57:07.289  1014  1123 D WifiP2pService: P2pDisablingState
09-06 18:57:07.289  1014  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
09-06 18:57:07.289  1014  1123 D WifiP2pService: p2p socket connection lost
09-06 18:57:07.289  1014  1124 E WifiNative-wlan0: do suspend true
,09-06 18:57:07.299  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-06 18:57:07.299  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 18:57:07.299  1014  1044 D WifiDisplayController: disconnect
09-06 18:57:07.299  1014  1044 D WifiDisplayController: updateConnection
09-06 18:57:07.299  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 18:57:07.299  1014  1123 D WifiP2pService: P2pDisabledState
09-06 18:57:07.299  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 18:57:07.299  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-06 18:57:07.299  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-06 18:57:07.299  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
,09-06 18:57:07.299  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 18:57:07.299  6367  6367 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-06 18:57:07.299  6367  6367 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-06 18:57:07.299  6367  6367 D UserAnalysis: Create SecureDbHelper
,09-06 18:57:07.299  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-06 18:57:07.299  1014  3294 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 18:57:07.299  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-06 18:57:07.309  6367  6367 D IntelligenceServiceApplication: onCreate()
,09-06 18:57:07.309  2650  2803 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:07.309  2650  2803 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:07.309  2650  2803 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:57:07.309  2650  2803 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:07.309  2650  2803 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:07.309  2650  2803 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:57:07.309  2650  2803 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:07.309  2650  2803 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:07.309  2650  2803 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:57:07.309  2650  2803 W bt-btif : ag scb idx 1 not allocated
09-06 18:57:07.309  2650  2803 W bt-btif : ag scb idx 2 not allocated
09-06 18:57:07.309  2650  2803 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 18:57:07.309  2650  2911 I bt_userial_mct: exiting userial_read_thread
09-06 18:57:07.309  2650  2911 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 18:57:07.309  2650  2719 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
,09-06 18:57:07.309  2650  2805 I bt_vendor: hw_epilog_process
09-06 18:57:07.309  2650  2719 D bt_userial_mct: userial_close
09-06 18:57:07.309  1014  1474 I ActivityManager: Killing 5316:com.google.android.talk/u0a104 (adj 15): empty #31
09-06 18:57:07.309  2650  2719 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 18:57:07.319  1014  1474 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-06 18:57:07.319  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:07.319  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:07.319  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:07.319  1014  1474 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:07.319  6367  6367 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-06 18:57:07.329  6390  6390 E Zygote  : MountEmulatedStorage(),
09-06 18:57:07.329  1014  1474 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6390 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-06 18:57:07.329  6390  6390 E Zygote  : v2
09-06 18:57:07.329  6390  6390 I libpersona: KNOX_SDCARD checking this for 10107
09-06 18:57:07.329  6390  6390 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 18:57:07.329  6390  6390 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:07.329  1014  1205 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-06 18:57:07.339  6367  6367 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-06 18:57:07.339  6390  6390 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 18:57:07.339  6390  6390 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-06 18:57:07.339  6367  6367 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-06 18:57:07.359  6390  6390 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 18:57:07.359  6390  6390 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:07.409  1014  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
09-06 18:57:07.409  1014  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-06 18:57:07.409  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 18:57:07.409  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 18:57:07.409  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.409  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.409  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.409  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.439   281   996 D EnterpriseController: uids 10012,
09-06 18:57:07.439   281   996 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0,
09-06 18:57:07.439   281   996 D Netd    : getNetworkForDns: using netid 0 for uid 10012
09-06 18:57:07.439   281   996 D EnterpriseController: uids 1000
09-06 18:57:07.439   281   996 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0,
09-06 18:57:07.439   281   996 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,09-06 18:57:07.439   281  1000 D CommandListener: Clearing all IP addresses on wlan0
,09-06 18:57:07.439  1014  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null,
09-06 18:57:07.439  1174  1717 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-06 18:57:07.439  1014  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
,09-06 18:57:07.439  2098  2098 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
09-06 18:57:07.439  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
09-06 18:57:07.439  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-06 18:57:07.449  1014  1126 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 18:57:07.449  1014  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 18:57:07.449  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 18:57:07.449  1014  2215 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:07.449  1932  1932 E ctxmgr  : [BaseServerTask]Server task (WriteInterestRecordTask) got error response.
09-06 18:57:07.449  3778  6281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,09-06 18:57:07.449  1014  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-06 18:57:07.449  1014  1126 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,09-06 18:57:07.449  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 18:57:07.449  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
09-06 18:57:07.449  1932  2128 E ctxmgr  : [SyncServerInterestRecordsOperation]Failure response from WriteInterestRecord. StatusCode = -1
09-06 18:57:07.449  1452  1452 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 18:57:07.449  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 18:57:07.459  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 18:57:07.459  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 18:57:07.459  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.459  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.459  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.459  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.469  1014  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 18:57:07.469  1014  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 18:57:07.469  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
,09-06 18:57:07.469  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 18:57:07.469  1014  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-06 18:57:07.469  1014  1126 E ConnectivityService: updateNetworkInfo()
09-06 18:57:07.469  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:57:07.469  1014  1126 E ConnectivityService: updateNetworkInfo()
09-06 18:57:07.469  1014  1127 D Tethering: MasterInitialState.processMessage what=3
,09-06 18:57:07.469  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:07.469  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:07.469  1014  1121 V NetworkStats: updateIfacesLocked()
09-06 18:57:07.469  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:07.469  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-06 18:57:07.479  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 18:57:07.479  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 18:57:07.479  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
,09-06 18:57:07.479  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,09-06 18:57:07.479  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:07.479  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 18:57:07.479  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:07.479  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:07.479  1014  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-06 18:57:07.479  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:07.479  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-06 18:57:07.479  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 18:57:07.479  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 18:57:07.479  1014  1121 V NetworkStats: performPollLocked() took 9ms
09-06 18:57:07.479  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:07.489  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:07.489  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.489  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:07.489  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-06 18:57:07.489  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:07.489  1174  1174 D HotspotTile: onReceive : 0, 0
09-06 18:57:07.489  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:07.489  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 18:57:07.499  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:07.499  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 18:57:07.499  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:07.499  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:07.499  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:07.499  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:07.509  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:07.509  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:07.509  6219  6219 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 18:57:07.509  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:07.559  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.559  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.559  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.569  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.569  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.569  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.569  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.569  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.569  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.579  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.579  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.579  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.579  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.579  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.579  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.589  2098  2098 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 18:57:07.589  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.589  2650  2719 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 18:57:07.589  2650  2719 I bt_vendor: bluetooth satus is on
09-06 18:57:07.589  2650  2719 I bt_vendor: bt-vendor : resetting BT status
09-06 18:57:07.589  2650  2719 I bt_vendor: Starting hciattach daemon
09-06 18:57:07.589  2650  2719 I bt_vendor: try to set false
,09-06 18:57:07.589  2650  2719 I bt_vendor: Starting hciattach daemon
09-06 18:57:07.589  2650  2719 I bt_vendor: try to set false
09-06 18:57:07.589  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 18:57:07.589  2650  2719 I bt_vendor: cleanup
,09-06 18:57:07.589  2650  2803 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-06 18:57:07.589  2650  2719 I GKI_LINUX: GKI_exit_task 0 done
,09-06 18:57:07.589  2650  2719 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-06 18:57:07.589  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.589  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 18:57:07.589  2650  2716 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-06 18:57:07.589  2650  2716 D BtConfig.SecureMode: isSecureModeOn:false
09-06 18:57:07.589  2650  2716 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-06 18:57:07.589  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 18:57:07.589  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 18:57:07.589  2650  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 18:57:07.589  1014  1347 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:07.589  1014  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-06 18:57:07.589  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 18:57:07.599  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.599  1014  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:07.599  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 18:57:07.599  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.599  1014  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:07.599  1014  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:07.599  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 18:57:07.599  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 18:57:07.599  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.599  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 18:57:07.599  2650  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 18:57:07.599  1014  1522 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:07.599  1014  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 18:57:07.599  2650  2650 D BtGatt.DebugUtils: handleDebugAction() action=null
09-06 18:57:07.599  2650  2650 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 18:57:07.599  2650  2650 D BtGatt.GattService: stop()
09-06 18:57:07.599  2650  2650 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 18:57:07.599  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.599  1014  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:07.599  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
09-06 18:57:07.599  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 18:57:07.599  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 18:57:07.599  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 18:57:07.599  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ec5292f
09-06 18:57:07.609  2650  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 18:57:07.609  2650  2650 D HeadsetService: Received stop request...Stopping profile...
,09-06 18:57:07.609  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-06 18:57:07.609  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ec5292f
,09-06 18:57:07.609  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.609  1014  1524 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:07.609  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
09-06 18:57:07.609  1014  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
,09-06 18:57:07.609  1014  1524 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.609  1014  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:07.609  1014  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:07.619  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-06 18:57:07.619  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-06 18:57:07.619  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-06 18:57:07.619  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 18:57:07.619  1308  1308 D HeadsetProfile: Bluetooth service disconnected
,09-06 18:57:07.619  2650  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 18:57:07.619  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:07.619  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 18:57:07.619  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.619  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:07.619  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:07.629  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-06 18:57:07.629  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 18:57:07.629  2098  2098 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
09-06 18:57:07.629  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 18:57:07.629  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 18:57:07.629  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
09-06 18:57:07.629  2650  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-06 18:57:07.629  1014  1474 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
09-06 18:57:07.629  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-06 18:57:07.629  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.629  1014  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:07.629  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
09-06 18:57:07.629  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:07.629  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 18:57:07.629  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:07.629  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:07.629  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:07.639  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 18:57:07.639  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 18:57:07.639  2650  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-06 18:57:07.639  1014  1817 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:07.639  1014  1817 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 18:57:07.639  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:07.639  1014  1817 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:07.639  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:07.639  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-06 18:57:07.639  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 18:57:07.639  2650  2716 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 18:57:07.639  1014  3293 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:07.639  1014  3293 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:07.639  1014  3293 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:07.639  1014  3293 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
09-06 18:57:07.639  1014  3293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 18:57:07.639  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 18:57:07.639  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 18:57:07.639  2650  2716 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 18:57:07.649  1014  3291 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:07.649  1014  3291 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 18:57:07.649  1014  3291 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:07.649  1014  3291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:07.649  1014  3291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 18:57:07.649  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:07.649  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 18:57:07.649  2650  2716 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:07.649  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:07.649  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 18:57:07.649  2650  2716 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:07.649  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 18:57:07.649  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 18:57:07.649  2650  2716 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-06 18:57:07.649  2650  2716 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 18:57:07.649  2650  2716 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 18:57:07.649  2650  2716 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 18:57:07.649  2650  2716 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-06 18:57:07.649  2650  2650 E BluetoothAdapterService(516237615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-06 18:57:07.649  2650  2650 E BluetoothAdapterService(516237615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 18:57:07.649  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 18:57:07.649  2650  2650 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 18:57:07.649  2650  2650 D A2dpService: Received stop request...Stopping profile...
,09-06 18:57:07.649  2650  2726 D A2dpStateMachine: Exit Disconnected: -1
,09-06 18:57:07.659  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ec5292f
,09-06 18:57:07.659  2098  2098 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-06 18:57:07.659  2098  2098 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 18:57:07.659  2098  2098 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 18:57:07.659  2098  2098 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-06 18:57:07.659  2098  2098 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 18:57:07.659  1014  1014 D BluetoothA2dp: Proxy object disconnected
,09-06 18:57:07.659  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
09-06 18:57:07.659  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 18:57:07.659  1308  1308 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:07.659  1308  1308 D A2dpProfile: Bluetooth service disconnected
09-06 18:57:07.659  2873  2873 D BluetoothA2dp: Proxy object disconnected
,09-06 18:57:07.659  1014  1124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-06 18:57:07.659  2650  2650 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-06 18:57:07.659  2650  2650 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 18:57:07.659  2650  2650 D HidService: Received stop request...Stopping profile...
,09-06 18:57:07.659  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:07.659  2650  2650 D HidService: Stopping Bluetooth HidService
09-06 18:57:07.659  2650  2650 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 18:57:07.659  2650  2650 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 18:57:07.659  2650  2650 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 18:57:07.659  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ec5292f
09-06 18:57:07.669  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-06 18:57:07.669  1014  1127 D Tethering: InitialState.processMessage what=4
,09-06 18:57:07.669  1308  1308 D BluetoothInputDevice: Proxy object disconnected
09-06 18:57:07.669  1308  1308 D HidProfile: Bluetooth service disconnected
09-06 18:57:07.669  2650  2650 D HealthService: Received stop request...Stopping profile...
09-06 18:57:07.669  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ec5292f
09-06 18:57:07.669  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 18:57:07.669  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:07.669  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-06 18:57:07.669  2650  2650 D PanService: Received stop request...Stopping profile...
09-06 18:57:07.669  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ec5292f
09-06 18:57:07.669  1014  1127 E Tethering: No numeric data
09-06 18:57:07.669  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 18:57:07.669  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 18:57:07.669  1014  1127 D Tethering: clearTetheredNotification()
09-06 18:57:07.669  1308  1308 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 18:57:07.669  1308  1308 D PanProfile: Bluetooth service disconnected
,09-06 18:57:07.679  2650  2650 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 18:57:07.679  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:07.679  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 18:57:07.679  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 18:57:07.679  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-06 18:57:07.679  1174  1174 D HotspotTile: updateTetherState():false, false
,09-06 18:57:07.679  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:07.679  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-06 18:57:07.679  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 18:57:07.679  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 18:57:07.679  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ec5292f
,09-06 18:57:07.679  1308  1308 D BluetoothMap: Proxy object disconnected
,09-06 18:57:07.679  1308  1308 D MapProfile: Bluetooth service disconnected
09-06 18:57:07.679  6390  6390 D StrictMode: StrictMode policy violation; ~duration=271 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
,09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 18:57:07.679  6390  6390 D StrictMode: StrictMode policy violation; ~duration=263 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 18:57:07.679  6390  6390 D StrictMode: ,	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 18:57:07.679  6390  6390 D StrictMode: 	,at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-06 18:57:07.679  6390  6390 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 18:57:07.679  6390  6390 D StrictMode: ,	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 18:57:07.689  1014  1121 V NetworkStats: performPollLocked() took 10ms
,09-06 18:57:07.679  6390  6390 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 18:57:07.689  1014  3291 I ActivityManager: Killing 5024:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
09-06 18:57:07.679  6390  6390 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.b.a.ca.a(PG:125),
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 18:57:07.679  6390  6390 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-06 18:57:07.679  6390  6390 D StrictMode: 	,at com.google.r.e.b(PG:170)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 18:57:07.679  6390  6390 D StrictMode: StrictMode policy violation; ~duration=170 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.k.c(PG:583)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.e.b(PG:170)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.an,droid.apps.gmm.base.app.a.a(PG:189)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 18:57:07.679  6390  6390 D StrictMode: StrictMode policy violation; ~duration=142 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.io.File.exists(File.java:363)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at an,droid.app.ActivityThread.main(ActivityThread.java:6145)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 18:57:07.679  6390  6390 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 18:57:07.679  2650  2650 D SapService: Received stop request...Stopping profile...
09-06 18:57:07.689  2650  2650 D SapService: Stopping Bluetooth SapService
09-06 18:57:07.689  2650  2650 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1ec5292f
09-06 18:57:07.689  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:07.689  1308  1308 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-06 18:57:07.689  1308  1308 D SapProfile: Bluetooth service disconnected
09-06 18:57:07.699  2650  2650 E BluetoothAdapterService(516237615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-06 18:57:07.699  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 18:57:07.699  2650  2650 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 18:57:07.699  2650  2650 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:07.699  2650  2650 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-06 18:57:07.699  2650  2727 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 18:57:07.699  2650  2650 I GKI_LINUX: GKI_exit_task 2 done
09-06 18:57:07.699  2650  2650 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-06 18:57:07.699  2650  2650 E BluetoothAdapterService(516237615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 18:57:07.699  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:07.699  2650  2650 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:07.699  2650  2650 E BluetoothAdapterService(516237615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 18:57:07.699  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:07.699  2650  2650 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:07.699  2650  2650 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 18:57:07.699  2650  2650 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-06 18:57:07.699  2650  2650 E BluetoothAdapterService(516237615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 18:57:07.699  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:07.699  2650  2650 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:07.699  2650  2650 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 18:57:07.699  2650  2650 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-06 18:57:07.699  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:07.699  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-06 18:57:07.709  2650  2650 E BluetoothAdapterService(516237615): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-06 18:57:07.709  2650  2650 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 18:57:07.709  2650  2650 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-06 18:57:07.709  2650  2650 E BluetoothAdapterService(516237615): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-06 18:57:07.709  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:07.709  2650  2650 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 18:57:07.709  2650  2650 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-06 18:57:07.709  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-06 18:57:07.709  2650  2716 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-06 18:57:07.709  2650  2716 D BluetoothAdapterProperties: Setting state to 10
09-06 18:57:07.709  2650  2716 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 18:57:07.709  2650  2716 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 18:57:07.709  2650  2716 D BluetoothAdapterService: updateAdapterState state is 10
09-06 18:57:07.709  1308  1323 D BluetoothPbap: onBluetoothStateChange: up=false
09-06 18:57:07.709  2650  2716 D BluetoothAdapterService: Autoconnection is available 
09-06 18:57:07.709  2650  2716 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 18:57:07.709  2650  2716 I BluetoothAdapterState: Entering OffState
09-06 18:57:07.709  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 18:57:07.709  1174  1588 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:07.709  1174  1588 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 18:57:07.709   273   273 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb70a67c8
09-06 18:57:07.709   273   273 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
09-06 18:57:07.709   273   273 I rmt_storage: wakelock acquired: 1, error no: 42
09-06 18:57:07.719   273   305 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1224055496)
09-06 18:57:07.719  1014  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 18:57:07.719  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 18:57:07.719  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.719  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:07.719  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 18:57:07.719  3691  3691 I Hs20UtilService: Starting #8
09-06 18:57:07.719  3691  3726 I Hs20UtilService: Message received 5007
09-06 18:57:07.729  1308  1329 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 18:57:07.729  1452  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:07.729  1452  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 18:57:07.729  1308  1323 D BluetoothMap: onBluetoothStateChange: up=false
09-06 18:57:07.729  2650  2660 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:07.729  2650  2660 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 18:57:07.729  1308  1329 D Bluetoothsap: onBluetoothStateChange: up=false
09-06 18:57:07.729  1308  1329 D Bluetoothsap: Unbinding service...
09-06 18:57:07.729  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 18:57:07.729  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 18:57:07.729  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 18:57:07.729  2873  2942 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:07.729  2873  2942 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 18:57:07.739  1932  6382 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:07.739  1932  6382 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 18:57:07.739  2873  2885 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 18:57:07.739  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 18:57:07.739  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 18:57:07.739  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 18:57:07.739  1308  3059 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 18:57:07.749  1428  6433 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:07.749  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 18:57:07.749  1428  6433 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 18:57:07.749  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 18:57:07.749  1308  1329 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:07.749  1308  1329 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 18:57:07.749  2650  5343 D BluetoothA2dp: onBluetoothStateChange: up=false
09-06 18:57:07.749  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 18:57:07.749  1308  1323 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-06 18:57:07.749  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:07.749  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 18:57:07.749  1438  1451 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:07.749  1438  1451 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 18:57:07.749  6219  6227 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:07.749  6219  6227 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-06 18:57:07.749  6219  6227 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-06 18:57:07.749  6219  6227 D BluetoothLeAdvertiser: Exit stop advertising
09-06 18:57:07.749  6219  6227 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-06 18:57:07.749  6219  6227 D BluetoothLeScanner: Exiting stopAllScan
09-06 18:57:07.749  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 18:57:07.749  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 18:57:07.749  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 18:57:07.749  1308  3059 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 18:57:07.749  1014  3292 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
09-06 18:57:07.759  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:07.759  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:07.759  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:07.759  1014  3292 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:07.759  6390  6412 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-06 18:57:07.779  6438  6438 E Zygote  : MountEmulatedStorage()
09-06 18:57:07.779  6438  6438 E Zygote  : v2
09-06 18:57:07.779  6438  6438 I libpersona: KNOX_SDCARD checking this for 10068
09-06 18:57:07.779  6438  6438 I libpersona: KNOX_SDCARD not a persona
09-06 18:57:07.779  6438  6438 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 18:57:07.779  1014  3292 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6438 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 18:57:07.779  6438  6438 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-06 18:57:07.779  6438  6438 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:07.789  1014  1257 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-06 18:57:07.789  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
09-06 18:57:07.789  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.789  1014  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:07.789  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-06 18:57:07.789   273   305 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
09-06 18:57:07.789   273   305 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
09-06 18:57:07.789   273   305 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1224055496) wakelock released: 1, error no: 0
09-06 18:57:07.789   273   305 I rmt_storage: 
09-06 18:57:07.789   273   273 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb70a67c8
,09-06 18:57:07.789  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 18:57:07.799  2098  2098 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 18:57:07.799  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:07.799  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
09-06 18:57:07.799  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 18:57:07.809  6438  6438 D TimaKeyStoreProvider: TimaSignature is unavailable,
,09-06 18:57:07.809  6438  6438 D ActivityThread: Added TimaKeyStore provider
09-06 18:57:07.809  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 18:57:07.809  1174  1174 D BluetoothAdapter: 225522908: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:07.809  1174  1174 D BluetoothTile:  getBluetoothState : 10
09-06 18:57:07.809  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:07.809  1174  1731 D BluetoothAdapter: 225522908: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:07.809  1174  1731 D BluetoothAdapter: 225522908: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:07.809  1174  1174 D BluetoothAdapter: 225522908: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:07.809  1174  1174 D BluetoothAdapter: 225522908: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:07.809  1014  1525 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 18:57:07.809  1014  1205 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 18:57:07.809  1781  1781 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 18:57:07.809  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 18:57:07.809  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED,
,09-06 18:57:07.819  2650  2719 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 18:57:07.819  1932  2122 D BluetoothAdapter: 34535608: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:07.819  1932  2122 D BluetoothAdapter: 34535608: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:07.819  2650  2650 I GKI_LINUX: GKI_exit_task 1 done
09-06 18:57:07.819  1014  1817 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 18:57:07.819  2650  2650 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 18:57:07.819  1014  1817 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 18:57:07.819  2650  2650 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 18:57:07.819  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:07.819  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:07.819  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:07.819  1014  1817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:07.819  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:07.819  2650  2650 I art     : System.exit called, status: 0
09-06 18:57:07.819  2650  2650 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 18:57:07.829  6438  6438 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 18:57:07.849  6438  6438 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 18:57:07.849  6438  6438 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 18:57:07.859  1014  3294 I ActivityManager: Process com.android.bluetooth (pid 2650)(adj 0) has died(48,1085)
,09-06 18:57:07.869  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:07.869  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 18:57:07.869  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-06 18:57:07.869  2098  2098 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-06 18:57:07.879  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-06 18:57:07.879  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 18:57:07.879  1014  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 18:57:07.879  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 18:57:07.879  6438  6438 D FileShare-Client: Outbound.stopDelayTimer - 
09-06 18:57:07.879  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 18:57:07.879  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.879  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.879  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:07.879  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:07.889  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:07.889  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-06 18:57:07.889  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 18:57:07.889  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:07.889  1174  1174 D HotspotTile: onReceive : 1, 0
,09-06 18:57:07.889  1932  2122 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 18:57:07.889  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 18:57:07.889  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:07.889  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-06 18:57:07.889  1014  3293 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
09-06 18:57:07.889  1014  3293 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:07.889  1014  3293 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-06 18:57:07.889  1014  3293 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:07.889  1014  3293 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-06 18:57:07.899  6458  6458 E Zygote  : MountEmulatedStorage(),
09-06 18:57:07.899  6458  6458 E Zygote  : v2
09-06 18:57:07.899  6458  6458 I libpersona: KNOX_SDCARD checking this for 10069
09-06 18:57:07.899  6458  6458 I libpersona: KNOX_SDCARD not a persona
09-06 18:57:07.909  6458  6458 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 18:57:07.899  1014  3293 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6458 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 18:57:07.909  1014  3293 I ActivityManager: Killing 5567:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-06 18:57:07.909  6458  6458 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 18:57:07.909  6458  6458 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:07.929  6458  6458 D TimaKeyStoreProvider: TimaSignature is unavailable
09-06 18:57:07.929  6458  6458 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:07.949  6458  6458 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 18:57:07.959  1014  3293 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:07.959  1014  3293 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:07.959  1014  3293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
,09-06 18:57:07.959  1014  3293 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,09-06 18:57:07.959  1014  3293 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:07.959  1014  3293 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:07.959  1014  3293 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:07.959  1014  3293 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:07.969  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:07.979  6473  6473 E Zygote  : MountEmulatedStorage(),
,09-06 18:57:07.979  1014  3293 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6473 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
09-06 18:57:07.979  6473  6473 E Zygote  : v2
09-06 18:57:07.979  6473  6473 I libpersona: KNOX_SDCARD checking this for 10104
09-06 18:57:07.979  6473  6473 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:07.979  6473  6473 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:07.979  1014  3293 I ActivityManager: Killing 5476:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,09-06 18:57:07.979  6473  6473 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 18:57:07.979  6473  6473 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 18:57:07.989  1014  1014 I ApplicationPolicy: updateDataUsageMap
,09-06 18:57:08.009  6473  6473 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:08.009  6473  6473 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:08.009  3152  3152 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,09-06 18:57:08.009  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:08.019  3152  3152 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-06 18:57:08.019  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:08.039  1014  1046 I PowerManagerService: [PWL] Off : 50s ago
,09-06 18:57:08.039  1014  1046 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,09-06 18:57:08.039  1014  1046 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-06 18:57:08.039  1014  1046 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1014, ws=null) (elapsedTime=577)
,09-06 18:57:08.039  6473  6473 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-06 18:57:08.079  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:08.159   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:57:08.189  1014  2724 D SSRM:n  : SIOP:: AP = 320
,09-06 18:57:08.229  6473  6496 I Babel   : MmsConfig: mnc/mcc: 0/0
09-06 18:57:08.229  6473  6496 I Babel   : MmsConfig.loadMmsSettings
09-06 18:57:08.229  6473  6496 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
09-06 18:57:08.229  6473  6496 I Babel   : MmsConfig.loadFromDatabase
,09-06 18:57:08.239  1014  1474 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
09-06 18:57:08.239  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-06 18:57:08.239  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.239  1014  1474 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:08.239  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 18:57:08.249  6473  6473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 18:57:08.249  6473  6496 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,09-06 18:57:08.249  6473  6496 I Babel   : MmsConfig.loadFromResources
,09-06 18:57:08.249  6473  6496 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-06 18:57:08.249  6473  6496 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-06 18:57:08.289  6473  6473 I Babel_StickerModule: App launched.
,09-06 18:57:08.289  1014  1474 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:08.289  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:08.289  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.289  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:08.289  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:08.299  3691  3691 I Hs20UtilService: Starting #9
,09-06 18:57:08.299  3691  3726 I Hs20UtilService: Message received 5007
,09-06 18:57:08.299  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 18:57:08.299  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 18:57:08.299  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 18:57:08.309  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 18:57:08.309  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-06 18:57:08.309  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 18:57:08.309  1308  3059 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 18:57:08.309   286   679 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,09-06 18:57:08.309   286   679 W QCamera2Factory: getCameraInfo: X
,09-06 18:57:08.309   286   720 W QCamera2Factory: getCameraInfo: E, camera_id = 1
09-06 18:57:08.309   286   720 W QCamera2Factory: getCameraInfo: X
,09-06 18:57:08.309  1014  3291 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.309  1014  3291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:08.309  1014  3291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.319  6473  6473 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-06 18:57:08.329  6473  6473 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 18:57:08.329  6473  6473 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 18:57:08.329  1014  1041 D Tethering: interfaceRemoved wlan0
,09-06 18:57:08.329  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 18:57:08.339  6473  6473 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-06 18:57:08.339  6473  6473 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-06 18:57:08.339  6473  6473 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-06 18:57:08.339  6473  6473 W AudioCapabilities: Unsupported mime audio/x-ima
,09-06 18:57:08.339  6473  6473 W AudioCapabilities: Unsupported mime audio/qcelp
,09-06 18:57:08.339  6473  6473 W AudioCapabilities: Unsupported mime audio/evrc
,09-06 18:57:08.349  6473  6473 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 18:57:08.349  6473  6473 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 18:57:08.359  6473  6473 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-06 18:57:08.359  6473  6473 W VideoCapabilities: Unsupported mime video/wvc1
,09-06 18:57:08.359  6473  6473 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-06 18:57:08.359  6473  6473 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-06 18:57:08.369  6473  6473 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-06 18:57:08.369  6473  6473 W VideoCapabilities: Unsupported mime video/mp43
,09-06 18:57:08.379  6473  6473 W VideoCapabilities: Unsupported mime video/sorenson
,09-06 18:57:08.379  6473  6473 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-06 18:57:08.399  6473  6473 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-06 18:57:08.419  1014  1257 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,09-06 18:57:08.419  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,09-06 18:57:08.419  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.419  1014  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:08.419  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-06 18:57:08.429  1014  1474 I ActivityManager: Killing 5800:com.sec.pcw.device/1000 (adj 15): empty #31
,09-06 18:57:08.459   291   291 E SMD     : DCD OFF,
,09-06 18:57:08.509  1014  1817 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:08.509  1014  1817 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:08.509  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.509  1014  1817 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:08.509  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:08.519  3691  3691 I Hs20UtilService: Starting #10
,09-06 18:57:08.519  3691  3726 I Hs20UtilService: Message received 5011
,09-06 18:57:08.519  1014  1524 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-06 18:57:08.519  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:08.519  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:08.519  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:08.519  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:08.529  1014  1041 D Tethering: interfaceRemoved p2p0
,09-06 18:57:08.529  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 18:57:08.529  6499  6499 E Zygote  : MountEmulatedStorage()
09-06 18:57:08.529  6499  6499 E Zygote  : v2
09-06 18:57:08.529  6499  6499 I libpersona: KNOX_SDCARD checking this for 1000
09-06 18:57:08.529  6499  6499 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:08.539  1014  1524 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6499 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-06 18:57:08.539  6499  6499 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:08.539  6499  6499 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 18:57:08.539  6499  6499 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:08.559  6499  6499 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:08.559  6499  6499 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:08.589  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 18:57:08.589  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 18:57:08.589  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 18:57:08.589  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 18:57:08.599  1014  1027 I ActivityManager: Killing 5815:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-06 18:57:08.599  1014  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.599  1014  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:08.599  1014  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.609  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.609  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.609  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.609  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.609  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.609  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.619  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.619  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.619  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.619  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.619  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.619  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.619  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.619  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.619  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.629  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.629  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:08.629  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.629  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.629  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.629  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.629  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.629  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.629  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.639  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.639  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.639  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.639  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.639  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.639  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.639  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.639  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.639  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.649  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.649  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:08.649  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.649  1014  1014 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.649  1014  1014 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.649  1014  1014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-06 18:57:08.659  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 18:57:08.659  1014  1257 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 18:57:08.659  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 18:57:08.669  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.669  1014  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:08.669  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 18:57:08.669  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:08.679  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 18:57:08.679  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:08.679  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 18:57:08.689  1014  1524 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-06 18:57:08.689  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:08.689  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:08.689  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:08.689  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:08.709  6516  6516 E Zygote  : MountEmulatedStorage(),
,09-06 18:57:08.709  6516  6516 E Zygote  : v2
09-06 18:57:08.709  1014  1524 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6516 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
09-06 18:57:08.709  6516  6516 I libpersona: KNOX_SDCARD checking this for 1002
09-06 18:57:08.709  6516  6516 I libpersona: KNOX_SDCARD not a persona
09-06 18:57:08.709  6516  6516 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:08.719  6516  6516 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-06 18:57:08.719  6516  6516 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:08.749  6516  6516 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:08.749  6516  6516 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:08.759  1014  1205 I ActivityManager: Killing 5108:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-06 18:57:08.779  6516  6516 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-06 18:57:08.779  6516  6516 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 18:57:08.819  6516  6516 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 18:57:08.859  6516  6516 D BtSettings.ProfileConfig: Adding GattService
,09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding HeadsetService
,09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding A2dpService
09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding HidService
,09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding HealthService
,09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding PanService
09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding SapService
,09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding SapClientService
,09-06 18:57:08.869  6516  6516 D BtSettings.ProfileConfig: Adding HidDevService
,09-06 18:57:08.869  6516  6516 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 18:57:08.869  1014  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 18:57:08.869  1014  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 18:57:08.879  1014  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:08.879  1014  1474 D SettingsProvider: selectionArgs: false
09-06 18:57:08.879  1014  1474 D SettingsProvider: selectionArgs: 1002
,09-06 18:57:08.879  1014  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 18:57:08.879  1014  1474 D SettingsProvider: ret = -1
,09-06 18:57:08.879  1014  3294 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-06 18:57:08.879  1014  3294 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:08.879  1014  3294 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:08.879  1014  3294 D SettingsProvider: selectionArgs: false
09-06 18:57:08.879  1014  3294 D SettingsProvider: selectionArgs: 1002
09-06 18:57:08.879  1014  3294 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:08.879  1014  3294 D SettingsProvider: ret = -1
,09-06 18:57:08.879  1014  1524 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,09-06 18:57:08.879  1014  1524 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 18:57:08.879  1014  1524 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 18:57:08.879  1014  1524 D SettingsProvider: selectionArgs: false
09-06 18:57:08.879  1014  1524 D SettingsProvider: selectionArgs: 1002
,09-06 18:57:08.879  1014  1524 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 18:57:08.879  1014  1524 D SettingsProvider: ret = -1
,09-06 18:57:08.879  1014  3291 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-06 18:57:08.879  1014  3291 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 18:57:08.889  1014  3291 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 18:57:08.889  1014  3291 D SettingsProvider: selectionArgs: false
,09-06 18:57:08.889  1014  3291 D SettingsProvider: selectionArgs: 1002
,09-06 18:57:08.889  1014  3291 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 18:57:08.889  1014  3291 D SettingsProvider: ret = -1
,09-06 18:57:08.889  1014  1347 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-06 18:57:08.889  1014  1347 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 18:57:08.889  1014  1347 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:08.889  1014  1347 D SettingsProvider: selectionArgs: false,
09-06 18:57:08.889  1014  1347 D SettingsProvider: selectionArgs: 1002
,09-06 18:57:08.889  1014  1347 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
,09-06 18:57:08.889  1014  1347 D SettingsProvider: ret = -1
,09-06 18:57:08.889  1014  1027 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-06 18:57:08.889  1014  1027 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:08.889  1014  1027 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:08.889  1014  1027 D SettingsProvider: selectionArgs: false
09-06 18:57:08.889  1014  1027 D SettingsProvider: selectionArgs: 1002
09-06 18:57:08.889  1014  1027 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:08.889  1014  1027 D SettingsProvider: ret = -1
,09-06 18:57:08.889  1014  1491 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 18:57:08.889  1014  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:08.889  1014  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:08.889  1014  1491 D SettingsProvider: selectionArgs: false
,09-06 18:57:08.889  1014  1491 D SettingsProvider: selectionArgs: 1002
09-06 18:57:08.889  1014  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:08.889  1014  1491 D SettingsProvider: ret = -1
,09-06 18:57:08.889  1014  3292 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-06 18:57:08.889  1014  3292 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:08.889  1014  3292 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:08.889  1014  3292 D SettingsProvider: selectionArgs: false
,09-06 18:57:08.889  1014  3292 D SettingsProvider: selectionArgs: 1002
09-06 18:57:08.889  1014  3292 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:08.889  1014  3292 D SettingsProvider: ret = -1
09-06 18:57:08.889  1014  1257 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 18:57:08.899  1014  1257 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:08.899  1014  1257 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:08.899  1014  1257 D SettingsProvider: selectionArgs: false
09-06 18:57:08.899  1014  1257 D SettingsProvider: selectionArgs: 1002
,09-06 18:57:08.899  1014  1257 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:08.899  1014  1257 D SettingsProvider: ret = -1
09-06 18:57:08.899  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,09-06 18:57:08.899  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:08.899  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:08.899  1014  1026 D SettingsProvider: selectionArgs: false
,09-06 18:57:08.899  1014  1026 D SettingsProvider: selectionArgs: 1002
09-06 18:57:08.899  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:08.899  1014  1026 D SettingsProvider: ret = -1
,09-06 18:57:08.899  1014  1205 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 18:57:08.899  1014  1205 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:08.899  1014  1205 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 18:57:08.899  1014  1205 D SettingsProvider: selectionArgs: false
09-06 18:57:08.899  1014  1205 D SettingsProvider: selectionArgs: 1002
09-06 18:57:08.899  1014  1205 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:08.899  1014  1205 D SettingsProvider: ret = -1
,09-06 18:57:08.899  1014  1525 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-06 18:57:08.899  1014  1525 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 18:57:08.899  1014  1525 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:08.899  1014  1525 D SettingsProvider: selectionArgs: false
,09-06 18:57:08.899  1014  1525 D SettingsProvider: selectionArgs: 1002
,09-06 18:57:08.899  1014  1525 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:08.899  1014  1525 D SettingsProvider: ret = -1
,09-06 18:57:08.909  1014  1817 I ActivityManager: Killing 5833:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-06 18:57:08.909  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:08.909  1014  3294 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: android.os.DeadObjectException
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 	at android.bluetooth.IBluetooth$Stub$Proxy.isEnabled(IBluetooth.java:1218)
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 	at android.bluetooth.BluetoothAdapter.isEnabled(BluetoothAdapter.java:702)
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 	at com.google.android.apps.gmm.iamhere.ble.m.b(PG:7267)
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 	at com.google.android.apps.gmm.iamhere.ble.x.run(PG:38)
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 	at com.google.android.apps.gmm.shared.f.a.k.run(PG:29)
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
09-06 18:57:08.909  6390  6415 E BluetoothAdapter: 	at java.lang.Thread.run(Thread.java:818)
09-06 18:57:08.909  1014  3294 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 18:57:08.919  1014  3294 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:08.919  1014  3294 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:08.919  1014  3294 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:08.919  1932  6532 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 18:57:08.929  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 18:57:08.929  1014  1205 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:08.929  1014  1205 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.929  1014  1205 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:08.939  1014  1205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:08.939  1014  1522 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 18:57:08.939  1014  1522 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:08.939  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.939  1014  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:08.939  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:08.939  3691  3691 I Hs20UtilService: Starting #11
,09-06 18:57:08.939  3691  3726 I Hs20UtilService: Message received 5011
,09-06 18:57:08.949  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 18:57:08.949  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 18:57:08.949  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
09-06 18:57:08.949  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 18:57:08.959  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:08.959  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:08.959  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:08.959  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:08.969  1014  1257 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-06 18:57:08.969  1014  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:08.969  1932  6532 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
09-06 18:57:08.969  1014  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:08.969  1014  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:08.969  1014  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:08.989  6533  6533 E Zygote  : MountEmulatedStorage(),
,09-06 18:57:08.989  1014  1257 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6533 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,09-06 18:57:08.989  6533  6533 E Zygote  : v2
09-06 18:57:08.989  6533  6533 I libpersona: KNOX_SDCARD checking this for 1000
09-06 18:57:08.989  6533  6533 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:08.989  6533  6533 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:08.999  6533  6533 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-06 18:57:08.999  6533  6533 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 18:57:09.009  6533  6533 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:09.009  6533  6533 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:09.029  6533  6533 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-06 18:57:09.039  6533  6533 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,09-06 18:57:09.039  6533  6533 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-06 18:57:09.049  6533  6533 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-06 18:57:09.049  6533  6533 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-06 18:57:09.049  6533  6533 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-06 18:57:09.049  6533  6533 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:09.049  1014  1524 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
,09-06 18:57:09.049  1014  1524 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-06 18:57:09.049  1014  1524 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,09-06 18:57:09.049  6533  6548 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
09-06 18:57:09.049  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.049  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.049  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.049  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.069  6550  6550 E Zygote  : MountEmulatedStorage()
09-06 18:57:09.069  6550  6550 E Zygote  : v2
09-06 18:57:09.069  6550  6550 I libpersona: KNOX_SDCARD checking this for 10111
09-06 18:57:09.069  6550  6550 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:09.069  6550  6550 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:09.069  6550  6550 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 18:57:09.069  1014  1524 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6550 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 18:57:09.069  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-06 18:57:09.069  6550  6550 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 18:57:09.069  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.069  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.069  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.069  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.089  6550  6550 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:09.089   311   311 I art     : Explicit concurrent mark sweep GC freed 8731(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 20.806ms
09-06 18:57:09.089  6550  6550 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:09.109   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 595us total 17.005ms,
,09-06 18:57:09.119   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 599us total 16.587ms,
,09-06 18:57:09.139  6565  6565 E Zygote  : MountEmulatedStorage(),
09-06 18:57:09.139  6565  6565 E Zygote  : v2
09-06 18:57:09.139  6565  6565 I libpersona: KNOX_SDCARD checking this for 10009
09-06 18:57:09.139  6565  6565 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:09.139  6565  6565 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-06 18:57:09.139  1014  1039 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6565 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-06 18:57:09.149  6565  6565 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-06 18:57:09.149  6565  6565 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-06 18:57:09.149  1721  1721 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 18:57:09.149  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-06 18:57:09.149  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.149  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.149  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.149  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.159   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:57:09.169  6579  6579 E Zygote  : MountEmulatedStorage()
09-06 18:57:09.169  6579  6579 I libpersona: KNOX_SDCARD checking this for 10145
09-06 18:57:09.169  6579  6579 E Zygote  : v2
09-06 18:57:09.169  6579  6579 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:09.169  6579  6579 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 18:57:09.169  1014  1039 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6579 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,09-06 18:57:09.169  6565  6565 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:09.179  6565  6565 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:09.179  6579  6579 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 18:57:09.179  6579  6579 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-06 18:57:09.179  1721  1721 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
09-06 18:57:09.179  1721  1721 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,09-06 18:57:09.179  1721  1721 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
09-06 18:57:09.189  1721  1721 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-06 18:57:09.199  1721  1721 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 18:57:09.199  1322  1349 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 9
09-06 18:57:09.199  1721  1721 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-06 18:57:09.199  1014  1491 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-06 18:57:09.199  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.199  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.199  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.199  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.209  6579  6579 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:09.209  6579  6579 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:09.219  6595  6595 E Zygote  : MountEmulatedStorage()
09-06 18:57:09.219  6595  6595 E Zygote  : v2
09-06 18:57:09.219  6595  6595 I libpersona: KNOX_SDCARD checking this for 10081
09-06 18:57:09.219  6595  6595 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:09.229  6595  6595 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:09.229  1014  1491 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6595 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 18:57:09.229  6595  6595 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 18:57:09.229  6595  6595 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL,
,09-06 18:57:09.239  1721  1721 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-06 18:57:09.239  6595  6595 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:09.239  6595  6595 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:09.259  6579  6579 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-06 18:57:09.259  6579  6579 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:57:09.259  6579  6579 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-06 18:57:09.259  6579  6579 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 18:57:09.259  6579  6579 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-06 18:57:09.269  6550  6550 I MusicStore: Database version: 108
09-06 18:57:09.269  1014  1347 I ActivityManager: Killing 5500:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31
,09-06 18:57:09.279  3730  3730 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 18:57:09 GMT+02:00 2016
,09-06 18:57:09.279  1014  1257 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-06 18:57:09.279  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 18:57:09.279  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:09.279  1014  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:09.279  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 18:57:09.289  3730  3730 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-06 18:57:09.289  1014  1522 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-06 18:57:09.299  1014  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.299  1014  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.299  1014  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.299  1014  1522 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.299  3730  3730 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-06 18:57:09.299  3730  3730 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 18:57:09.309  1014  1522 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6617 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,09-06 18:57:09.309  6617  6617 E Zygote  : MountEmulatedStorage()
09-06 18:57:09.309  6617  6617 I libpersona: KNOX_SDCARD checking this for 10034
09-06 18:57:09.309  6617  6617 E Zygote  : v2
09-06 18:57:09.309  6617  6617 I libpersona: KNOX_SDCARD not a persona
09-06 18:57:09.309  6617  6617 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:09.319  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null,
09-06 18:57:09.319  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
09-06 18:57:09.319  6617  6617 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 18:57:09.319  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:09.319  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:09.319  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:09.319  6617  6617 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:09.319  3730  3730 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 18:57:09.319  3730  6615 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 18:57:09.329  3730  6615 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-06 18:57:09.329  1014  1026 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 18:57:09.339  3730  6615 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
,09-06 18:57:09.339  3730  6615 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-06 18:57:09.339  3730  3730 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-06 18:57:09.339  6617  6617 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:09.339  6617  6617 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:09.359  1014  3292 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 18:57:09.369  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 18:57:09.379  1014  1205 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-06 18:57:09.379  1014  1205 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.379  1014  1205 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.379  1014  1205 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.379  1014  1205 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.379  6617  6617 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-06 18:57:09.399  6637  6637 E Zygote  : MountEmulatedStorage()
09-06 18:57:09.399  1014  1205 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6637 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-06 18:57:09.399  6637  6637 E Zygote  : v2
09-06 18:57:09.399  6637  6637 I libpersona: KNOX_SDCARD checking this for 10113
09-06 18:57:09.399  6637  6637 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:09.399  6637  6637 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:09.399  1014  1205 I ActivityManager: Killing 5848:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
09-06 18:57:09.399  6637  6637 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 18:57:09.399  6637  6637 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 18:57:09.409  1014  1027 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 18:57:09.419  3257  6651 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
09-06 18:57:09.419  6637  6637 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:09.419  6637  6637 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:09.429  3257  6651 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,09-06 18:57:09.429  5865  5865 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-06 18:57:09.429  3257  6651 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,09-06 18:57:09.439  3257  6651 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-06 18:57:09.439  3257  6651 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,09-06 18:57:09.439  1014  1347 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
09-06 18:57:09.439  1014  1347 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,09-06 18:57:09.439  1014  1347 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:09.439  1014  1347 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-06 18:57:09.439  1014  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,09-06 18:57:09.439  6550  6550 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-06 18:57:09.439  6550  6550 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-06 18:57:09.439  6047  6047 I SA      : [DM] init START
,09-06 18:57:09.449  1014  3291 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 18:57:09.449  6047  6047 I SA      : [DM] This device is not a Vodafone
,09-06 18:57:09.459  6047  6047 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-06 18:57:09.459  6047  6047 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-06 18:57:09.459  6047  6047 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,09-06 18:57:09.459  6047  6047 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,09-06 18:57:09.469  6047  6047 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,09-06 18:57:09.469  6047  6047 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
09-06 18:57:09.469  6047  6047 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-06 18:57:09.469  5865  6655 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,09-06 18:57:09.479  6047  6047 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-06 18:57:09.479  6047  6047 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-06 18:57:09.479  6047  6047 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-06 18:57:09.479  6047  6047 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,09-06 18:57:09.489  6047  6047 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-06 18:57:09.499  6550  6550 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-06 18:57:09.499  6047  6047 I SA      : [SCU] isHaveSA() - false
,09-06 18:57:09.499  6047  6047 I SA      : support phone number id : false
09-06 18:57:09.499  6047  6047 I SA      : [DM] Supports Ref Jpn : true
,09-06 18:57:09.499  6047  6047 I SA      : [DM] init END
,09-06 18:57:09.499  6047  6047 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-06 18:57:09.499  6047  6047 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,09-06 18:57:09.499  6047  6047 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-06 18:57:09.509  6047  6047 I SA      : [SLFUCHKMGR] constructor called
,09-06 18:57:09.519  6047  6047 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 18:57:09.519  6047  6047 I SA      : [OR] == isSIMCardReady false ==
,09-06 18:57:09.519  6047  6047 I SA      : [SCU] == networkStateCheck == false
09-06 18:57:09.519  6047  6047 I SA      : [OR] onReceive END
,09-06 18:57:09.519  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:09.539  5955  5963 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-06 18:57:09.549  6550  6550 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-06 18:57:09.549  6550  6550 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3d026a93: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-06 18:57:09.549  6550  6550 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-06 18:57:09.549  6550  6550 D AndroidMusic: GMSCore installation verified
,09-06 18:57:09.559  5955  5964 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-06 18:57:09.559  5955  5964 D BadgeProvider: sendNotify, [notify] : null
09-06 18:57:09.559  5955  5964 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-06 18:57:09.559  5955  5964 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-06 18:57:09.559  5955  5964 D BadgeProvider: update, [UpdateCount] : 1
,09-06 18:57:09.559  1475  1475 D Launcher.Model: reloadBadges entered.
,09-06 18:57:09.579  1014  1522 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 18:57:09.579  1014  1817 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-06 18:57:09.579  1014  1817 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-06 18:57:09.579  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:09.579  1014  1817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:09.579  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:09.589  6550  6550 I ConfigStore: Config Database version: 1
,09-06 18:57:09.599  1014  1522 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 18:57:09.609  1014  1817 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 18:57:09.619  1014  1491 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 18:57:09.629  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 18:57:09.629  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 18:57:09.629  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
09-06 18:57:09.629  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 18:57:09.629  1014  1347 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-06 18:57:09.629  1014  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.629  1014  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.629  1014  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.629  1014  1347 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.649  6665  6665 E Zygote  : MountEmulatedStorage()
,09-06 18:57:09.649  1014  1347 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6665 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 18:57:09.659  6665  6665 E Zygote  : v2
09-06 18:57:09.659  6665  6665 I libpersona: KNOX_SDCARD checking this for 10159
,09-06 18:57:09.659  6665  6665 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:09.659  6665  6665 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-06 18:57:09.659  6665  6665 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-06 18:57:09.669  6665  6665 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-06 18:57:09.689  6665  6665 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:09.689  6665  6665 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:09.709   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-06 18:57:09.709   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 18:57:09.719  6550  6550 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-06 18:57:09.719   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-06 18:57:09.719   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 18:57:09.719  6550  6550 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-06 18:57:09.729   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-06 18:57:09.729   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 18:57:09.729  6550  6550 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-06 18:57:09.729  1014  1525 I art     : Explicit concurrent mark sweep GC freed 53656(2MB) AllocSpace objects, 4(112KB) LOS objects, 33% free, 27MB/41MB, paused 3.025ms total 160.982ms
,09-06 18:57:09.729  1014  1024 I art     : WaitForGcToComplete blocked for 107.018ms for cause HeapTrim
,09-06 18:57:09.739  1014  1524 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-06 18:57:09.739  1014  1524 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-06 18:57:09.739  1014  1524 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:09.739  1014  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:09.739  1014  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:09.749  1014  1205 I ActivityManager: Killing 5534:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-06 18:57:09.759  1014  3293 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 18:57:09.759  1014  3293 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-06 18:57:09.759  1014  3293 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:09.759  1014  3293 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:09.759  1014  3293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:09.769  1014  1524 I ActivityManager: Killing 5934:com.sec.android.app.samsungapps/u0a10 (adj 15): empty #31
,09-06 18:57:09.769  1014  1525 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 18:57:09.769  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 18:57:09.769  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:09.769  1014  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:09.769  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:09.779  3778  3778 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-06 18:57:09.779  3778  4586 I iu.UploadsManager: num queued entries: 0
,09-06 18:57:09.789  3778  4586 I iu.UploadsManager: num updated entries: 0
,09-06 18:57:09.789  3778  4586 I iu.SyncManager: NEXT; no task
,09-06 18:57:09.799  1014  3291 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 18:57:09.809  1014  1474 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 18:57:09.809  1014  1205 I AudioService: getStreamVolume 3 index 0
,09-06 18:57:09.829  6550  6550 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-06 18:57:09.829  6550  6550 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-06 18:57:09.839   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 18:57:09.839   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 18:57:09.839  6637  6687 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 18:57:09.849   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 18:57:09.849   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
09-06 18:57:09.849  1014  1525 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-06 18:57:09.849  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-06 18:57:09.849  6637  6687 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 18:57:09.849  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:09.849  1014  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:09.849  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:09.859  1014  1491 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 18:57:09.859  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-06 18:57:09.859  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:09.859  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:09.859  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:09.859   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-06 18:57:09.859   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 18:57:09.859  6637  6692 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-06 18:57:09.869  1014  1205 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
09-06 18:57:09.869  1014  1205 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-06 18:57:09.869  1014  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-06 18:57:09.869  1014  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-06 18:57:09.869  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-06 18:57:09.869  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:09.869  1014  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:09.869  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
09-06 18:57:09.869   257   526 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-06 18:57:09.869   257   526 W Vold    : Returning OperationFailed - no handler for errno 0
,09-06 18:57:09.869  6637  6692 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-06 18:57:09.879  1014  3293 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-06 18:57:09.879  1014  1525 I ActivityManager: Killing 5782:com.android.mms/u0a46 (adj 15): empty #31
,09-06 18:57:09.879  1014  3292 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 18:57:09.889  1014  1014 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-06 18:57:09.899  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.899  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.899  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.899  1014  1014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.909  6694  6694 E Zygote  : MountEmulatedStorage()
09-06 18:57:09.909  6694  6694 E Zygote  : v2
09-06 18:57:09.909  6694  6694 I libpersona: KNOX_SDCARD checking this for 10002
09-06 18:57:09.909  6694  6694 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:09.909  6694  6694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:09.909  1014  3294 D CountryDetector: No listener is left
,09-06 18:57:09.909  6694  6694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 18:57:09.909  1014  1014 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6694 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-06 18:57:09.909  6694  6694 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-06 18:57:09.929  6694  6694 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:09.929  6694  6694 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:09.939  1014  3291 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,09-06 18:57:09.939  1014  3291 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-06 18:57:09.939  1014  3291 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:09.939  1014  3291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:09.939  1014  3291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-06 18:57:09.949  6550  6550 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-06 18:57:09.949  1014  3294 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-06 18:57:09.949  1014  3294 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-06 18:57:09.949  1014  3294 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:09.949  1014  3294 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:09.949  1014  3294 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:09.969  1014  3291 I ActivityManager: Killing 5976:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,09-06 18:57:09.989  1014  1257 I ActivityManager: Killing 6000:com.wsomacp/u0a25 (adj 15): empty #31
,09-06 18:57:09.989  1014  1257 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-06 18:57:09.989  1014  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.989  1014  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:09.989  1014  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:09.989  1014  1257 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:10.009  6725  6725 E Zygote  : MountEmulatedStorage(),
09-06 18:57:10.009  6725  6725 I libpersona: KNOX_SDCARD checking this for 1000
09-06 18:57:10.009  6725  6725 E Zygote  : v2
,09-06 18:57:10.009  6725  6725 I libpersona: KNOX_SDCARD not a persona
09-06 18:57:10.009  6725  6725 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:10.009  1014  1257 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6725 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,09-06 18:57:10.009  6725  6725 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 18:57:10.009  6725  6725 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:10.029  1014  3291 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:10.029  6725  6725 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:10.029  6725  6725 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:10.029  1014  3291 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:10.029  1014  3291 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:10.029  1014  3291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-06 18:57:10.059  6637  6637 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-06 18:57:10.069  1014  3294 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 18:57:10.069  1014  3294 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 18:57:10.069  1014  3294 D SecContentProvider2: mCursor = null
,09-06 18:57:10.069  1014  3294 D WifiService: setWifiEnabled: true pid=6219, uid=10155
09-06 18:57:10.069  1014  3294 W ActivityManager: Permission Denial: getCurrentUser() from pid=6219, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-06 18:57:10.069  1014  3294 W WifiService: Failed getting userId using ActivityManagerNative
09-06 18:57:10.069  1014  3294 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6219, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 18:57:10.069  1014  3294 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-06 18:57:10.069  1014  3294 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 18:57:10.069  1014  3294 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 18:57:10.069  1014  3294 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 18:57:10.069  1014  3294 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-06 18:57:10.069  1014  3294 D SettingsProvider: name = wifi_on
,09-06 18:57:10.079  6637  6637 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 9536-9540)
09-06 18:57:10.079  6637  6637 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-06 18:57:10.079  1014  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 18:57:10.079  6725  6725 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-06 18:57:10.089  6637  6637 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d46b3e8}
,09-06 18:57:10.089  6637  6637 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-06 18:57:10.089  6637  6637 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-06 18:57:10.109  6637  6637 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-06 18:57:10.109  6637  6637 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-06 18:57:10.119  6637  6637 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-06 18:57:10.139  6637  6637 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-06 18:57:10.139  6637  6637 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,09-06 18:57:10.139  6637  6637 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-06 18:57:10.149  6637  6637 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-06 18:57:10.149  6637  6637 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-06 18:57:10.149  6637  6637 I Adreno-EGL: Build Date: 04/06/15 Mon
09-06 18:57:10.149  6637  6637 I Adreno-EGL: Local Branch: 
09-06 18:57:10.149  6637  6637 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-06 18:57:10.149  6637  6637 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-06 18:57:10.149  6637  6637 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-06 18:57:10.159   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-06 18:57:10.199  6725  6725 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-06 18:57:10.209  6725  6725 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,09-06 18:57:10.209  6725  6725 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:10.219  6725  6725 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-06 18:57:10.219  6725  6725 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
,09-06 18:57:10.219  6725  6725 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-06 18:57:10.299  6637  6755 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-06 18:57:10.299  6637  6637 I NSApplication: Starting up...
,09-06 18:57:10.309  1014  3294 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-06 18:57:10.309  1014  3294 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:10.309  1014  3294 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:10.309  1014  3294 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:10.309  1014  3294 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:10.329  6765  6765 E Zygote  : MountEmulatedStorage(),
09-06 18:57:10.329  6765  6765 E Zygote  : v2
09-06 18:57:10.329  6765  6765 I libpersona: KNOX_SDCARD checking this for 10120
09-06 18:57:10.329  6765  6765 I libpersona: KNOX_SDCARD not a persona,
09-06 18:57:10.329  6765  6765 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:10.329  1014  3294 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6765 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a,
,09-06 18:57:10.329  6765  6765 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-06 18:57:10.329  1014  3294 I ActivityManager: Killing 6023:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
09-06 18:57:10.329  1014  3294 I ActivityManager: Killing 5903:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #32
,09-06 18:57:10.329  6765  6765 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-06 18:57:10.349  6765  6765 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:10.349  6765  6765 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:10.369  6765  6765 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-06 18:57:10.439  1014  1041 D Tethering: interfaceAdded wlan0
,09-06 18:57:10.439  1014  1127 E Tethering: No numeric data
,09-06 18:57:10.449  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 18:57:10.449  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:10.449  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-06 18:57:10.449  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0,
09-06 18:57:10.449  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 18:57:10.449  1014  1127 D Tethering: clearTetheredNotification()
09-06 18:57:10.449  1014  1127 D Tethering: InitialState.processMessage what=4
09-06 18:57:10.449  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:10.459  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 18:57:10.459  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 18:57:10.459  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-06 18:57:10.459  1014  1041 D Tethering: interfaceAdded p2p0
09-06 18:57:10.459  1174  1174 D HotspotTile: updateTetherState():false, false
09-06 18:57:10.459  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:10.459  1014  1121 V NetworkStats: performPollLocked() took 6ms
,09-06 18:57:10.459  1014  1127 E Tethering: No numeric data
,09-06 18:57:10.459  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
09-06 18:57:10.459  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 18:57:10.459  1014  1127 D Tethering: clearTetheredNotification()
,09-06 18:57:10.459  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:10.459  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:10.459  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 18:57:10.459  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 18:57:10.459  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:10.459  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 18:57:10.459  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-06 18:57:10.459  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 18:57:10.459  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 18:57:10.459  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 18:57:10.459  1174  1174 D HotspotTile: updateTetherState():false, false
,09-06 18:57:10.469  1014  1121 V NetworkStats: performPollLocked() took 6ms
,09-06 18:57:10.469  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:10.469   281  1000 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-06 18:57:10.469   281  1000 D SoftapController: Softap fwReload - Ok
,09-06 18:57:10.469  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:10.469  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:10.469   281  1000 D CommandListener: Setting iface cfg,
09-06 18:57:10.469   281  1000 D CommandListener: Trying to bring down wlan0
,09-06 18:57:10.469   281  1000 D CommandListener: Clearing all IP addresses on wlan0
,09-06 18:57:10.479  1014  1124 E WifiHW  : supplicant_name : p2p_supplicant,
,09-06 18:57:10.479  1014  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
09-06 18:57:10.479  1014  1124 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,09-06 18:57:10.489  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:10.489  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 18:57:10.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:10.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:10.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:10.489  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:10.489  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:10.489  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:10.489  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-06 18:57:10.489  1174  1174 D HotspotTile: onReceive : 2, 0
,09-06 18:57:10.489  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 18:57:10.489  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:10.499  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:10.499  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:10.519  6783  6783 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL,
09-06 18:57:10.519  6783  6783 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 18:57:10.519  6783  6783 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 18:57:10.539  6783  6783 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-06 18:57:10.539   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6783,
09-06 18:57:10.539   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-06 18:57:10.539  6783  6783 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-06 18:57:10.539  6783  6783 I wpa_supplicant: ssSupport state is = 1
09-06 18:57:10.539  6783  6783 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
09-06 18:57:10.539  6783  6783 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-06 18:57:10.539   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6783
09-06 18:57:10.539   401   401 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-06 18:57:10.679  1014  1525 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-06 18:57:10.689  1014  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:10.689  1014  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:10.689  1014  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:10.689  1014  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:10.699   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-06 18:57:10.699  6789  6789 E Zygote  : MountEmulatedStorage()
09-06 18:57:10.699  6789  6789 I libpersona: KNOX_SDCARD checking this for 10125
09-06 18:57:10.699  6789  6789 E Zygote  : v2
09-06 18:57:10.699  6789  6789 I libpersona: KNOX_SDCARD not a persona
09-06 18:57:10.699  6789  6789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 18:57:10.699  6789  6789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 18:57:10.709  6789  6789 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:10.709  1014  1525 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6789 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-06 18:57:10.709  1014  1525 I ActivityManager: Killing 5883:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-06 18:57:10.709  6783  6783 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed
,09-06 18:57:10.719  6789  6789 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:10.719  6789  6789 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:10.739  6789  6789 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:57:10.739  6789  6789 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-06 18:57:10.739  6789  6789 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 18:57:10.749  6789  6789 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:10.759  6789  6789 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service,
,09-06 18:57:10.759  6789  6789 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 18:57:10.759  1014  3293 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-06 18:57:10.759  1014  3293 I ActivityManager: Killing 6085:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-06 18:57:10.769  1014  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 18:57:10.769  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:10.769  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:10.769  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:10.769  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:10.769  3691  3691 I Hs20UtilService: Starting #12
,09-06 18:57:10.769  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 18:57:10.769  3691  3726 I Hs20UtilService: Message received 5011
,09-06 18:57:10.769  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 18:57:10.769  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
09-06 18:57:10.769  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 18:57:10.779  6783  6783 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 18:57:10.779  6783  6783 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 18:57:10.789  6783  6783 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-06 18:57:10.789   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6783
09-06 18:57:10.789   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 18:57:10.789  6783  6783 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 18:57:10.789  6783  6783 I wpa_supplicant: ssSupport state is = 1
09-06 18:57:10.789  6783  6783 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 18:57:10.789  6783  6783 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 18:57:10.789  6783  6783 E wpa_supplicant: SIM READ ERROR
09-06 18:57:10.789  6783  6783 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 18:57:10.789  6783  6783 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 18:57:10.789  6783  6783 E wpa_supplicant: SIM READ ERROR
09-06 18:57:10.789  6783  6783 I wpa_supplicant: Blacklist: Clear (all) 
09-06 18:57:10.789  6783  6783 I wpa_supplicant: wpa_default_ap_write_once
09-06 18:57:10.789  6783  6783 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 18:57:10.789  6783  6783 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 18:57:10.789  6783  6783 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-06 18:57:10.789  6783  6783 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 18:57:10.789  6783  6783 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-06 18:57:10.789  6783  6783 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-06 18:57:10.799  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 18:57:10.799  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 18:57:10.799  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-06 18:57:10.889  6783  6783 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-06 18:57:11.059  6783  6783 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 18:57:11.069  6783  6783 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 18:57:11.079  6783  6783 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage
,09-06 18:57:11.079   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6783
09-06 18:57:11.079   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 18:57:11.079  6783  6783 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 18:57:11.079  6783  6783 I wpa_supplicant: ssSupport state is = 1
,09-06 18:57:11.079  6783  6783 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 18:57:11.079  6783  6783 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-06 18:57:11.089  6783  6783 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-06 18:57:11.089   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6783
09-06 18:57:11.089   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 18:57:11.089  6783  6783 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-06 18:57:11.089  6783  6783 I wpa_supplicant: ssSupport state is = 1,
09-06 18:57:11.089  6783  6783 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 18:57:11.089  6783  6783 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 18:57:11.089  6783  6783 E wpa_supplicant: SIM READ ERROR
09-06 18:57:11.089  6783  6783 I wpa_supplicant: wpa_default_ap_write_once,
09-06 18:57:11.089  6783  6783 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 18:57:11.089  6783  6783 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 18:57:11.089  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 18:57:11.089  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 18:57:11.089  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-06 18:57:11.099  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 18:57:11.099  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 18:57:11.099  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-06 18:57:11.249  6783  6783 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
09-06 18:57:11.249  6783  6783 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 18:57:11.299  6783  6783 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-06 18:57:11.299  6783  6783 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-06 18:57:11.299  6783  6783 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 18:57:11.449  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
09-06 18:57:11.449  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 18:57:11.449  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-06 18:57:11.469   291   291 E SMD     : DCD OFF,
,09-06 18:57:11.479  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 18:57:11.489  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 18:57:11.489  6783  6783 I wpa_supplicant: HOTSPOT20_ENABLE called
09-06 18:57:11.489  6783  6783 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-06 18:57:11.489  6783  6783 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 18:57:11.489  6783  6783 E wpa_supplicant: SIM READ ERROR,
09-06 18:57:11.489  6783  6783 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 18:57:11.519  6783  6783 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-06 18:57:11.529  1014  1124 D WifiNative-wlan0: callSECApiInt - ID [210],
,09-06 18:57:11.529  6783  6783 I wpa_supplicant: Skip scan - bUseNetwork false,
09-06 18:57:11.529  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:11.529  1014  1124 D WifiConfigStore: Loading config and enabling all networks 
09-06 18:57:11.529  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
09-06 18:57:11.529  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 18:57:11.539  1174  1174 D HotspotTile: onReceive : 3, 0
09-06 18:57:11.529  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:11.529  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:11.529  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:11.529  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:11.529  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:11.529  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:11.529  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,09-06 18:57:11.539  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED,
,09-06 18:57:11.549  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:11.549  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:11.549  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:11.549  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:11.549  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:11.549  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:11.549  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:11.549  1014  1124 E WifiConfigStore: Not a HS20
,09-06 18:57:11.549  1014  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 18:57:11.559  1014  1124 D WifiNative-wlan0: callSECApiInt - ID [65],
,09-06 18:57:11.559  1014  1525 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:11.559  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 18:57:11.559  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:11.559  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:11.559  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:11.569  3691  3691 I Hs20UtilService: Starting #13
,09-06 18:57:11.569  3691  3726 I Hs20UtilService: Message received 5011
09-06 18:57:11.569  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 18:57:11.569  6783  6783 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
,09-06 18:57:11.569  6783  6783 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 18:57:11.569  6783  6783 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 18:57:11.569  6783  6783 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 18:57:11.569  6783  6783 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 18:57:11.569  6783  6783 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 18:57:11.569  6783  6783 I wpa_supplicant: First Scan Start
09-06 18:57:11.569  6783  6783 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-06 18:57:11.569  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 18:57:11.569  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 18:57:11.569  1014  1124 D WifiNative-wlan0: Setting external_sim to 1
09-06 18:57:11.569  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
09-06 18:57:11.569  1014  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 18:57:11.569  1014  1124 I WifiNative-HAL: startHal
09-06 18:57:11.569  1014  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9c78d88c
09-06 18:57:11.569  1014  1124 I WifiNative-HAL: Could not start hal
,09-06 18:57:11.569  6473  6473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:57:11.569  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 18:57:11.579  1014  1124 E WifiNative-wlan0: do suspend true
,09-06 18:57:11.579  1014  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
,09-06 18:57:11.579  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,09-06 18:57:11.579  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
,09-06 18:57:11.579  1014  1146 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:11.579  1014  1146 I WifiNative-HAL: startHal
,09-06 18:57:11.579  1014  1146 E wifi    : getStaticLongField sWifiHalHandle 0x9da3d9bc
09-06 18:57:11.579  1014  1146 I WifiNative-HAL: Could not start hal
09-06 18:57:11.579  1014  1146 E WifiScanningService: could not start HAL
,09-06 18:57:11.579  1014  1014 D RttService: SCAN_AVAILABLE : 3
,09-06 18:57:11.579  1014  1147 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,09-06 18:57:11.579  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 18:57:11.579  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 18:57:11.579  1014  1124 E WifiNative-wlan0: invaild command id : 215
,09-06 18:57:11.589   281  1000 D CommandListener: Setting iface cfg
09-06 18:57:11.589   281  1000 D CommandListener: Trying to bring up p2p0
09-06 18:57:11.589  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 18:57:11.589  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 18:57:11.589  1014  1124 E WifiNative-wlan0: invaild command id : 215
,09-06 18:57:11.589  1014  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-06 18:57:11.589  6783  6783 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 18:57:11.589  1014  1123 D WifiP2pService: P2pEnablingState
09-06 18:57:11.589  1014  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
09-06 18:57:11.589  1014  1123 D WifiP2pService: P2p socket connection successful
09-06 18:57:11.589  1014  1123 D WifiP2pService: P2pEnabledState
09-06 18:57:11.589  6783  6783 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 18:57:11.589  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 18:57:11.589  6783  6783 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,09-06 18:57:11.589  1014  1126 E ConnectivityService: updateNetworkInfo()
,09-06 18:57:11.589  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED,
09-06 18:57:11.599  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 18:57:11.599  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 18:57:11.599  1014  1044 D WifiDisplayController: disconnect
09-06 18:57:11.599  1014  1044 D WifiDisplayController: updateConnection
09-06 18:57:11.599  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:11.599  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 18:57:11.599  1014  1124 D SecContentProvider2: mCursor = null,
09-06 18:57:11.599  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 18:57:11.599  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 18:57:11.599  1014  1205 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 18:57:11.599  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:11.599  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-06 18:57:11.599  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:11.599  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,09-06 18:57:11.599  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-06 18:57:11.599  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 18:57:11.599  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 18:57:11.609  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress
,09-06 18:57:11.609  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-06 18:57:11.609  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 18:57:11.609  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 18:57:11.609  1014  1123 D WifiP2pService: DeviceAddress: 7e:96:ac
09-06 18:57:11.609  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 18:57:11.609  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  secondary type: null
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  wps: 0
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  grpcapab: 0
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  devcapab: 0
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  status: 3
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  wfdInfo: null
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  groupownerAddress: null
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  GOdeviceName: null
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  interfaceAddress: 
09-06 18:57:11.609  1014  1044 D WifiDisplayController:  SConnectInfo : null
,09-06 18:57:11.609  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 18:57:11.609  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 18:57:11.609  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 18:57:11.609  1308  3059 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 18:57:11.619  6438  6438 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 18:57:11.619  6438  6438 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected,
09-06 18:57:11.619  6438  6438 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 18:57:11.619  6458  6458 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 18:57:11.629  1014  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
09-06 18:57:11.629  1014  1123 D WifiP2pService: InactiveState
09-06 18:57:11.629  1014  1123 D WifiP2pService: InactiveState{ what=143376 }
09-06 18:57:11.629  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 18:57:11.629  6783  6783 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-06 18:57:11.629  1014  1123 D WifiP2pService: InactiveState{ what=143376 },
09-06 18:57:11.629  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 18:57:12.839  6783  6783 I wpa_supplicant: nl80211: Received scan results (34 BSSes)
,09-06 18:57:12.849  6783  6783 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 18:57:12.849  6783  6783 I wpa_supplicant: Trying to associate with SSID '4E47373030'
09-06 18:57:12.849  6783  6783 I wpa_supplicant: Trying to associate with  'G700'
09-06 18:57:12.849  6783  6783 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-06 18:57:12.849  6783  6783 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-06 18:57:12.859  1014  6807 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-06 18:57:12.869  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 18:57:12.869  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:12.879  1014  1039 I ActivityManager: Killing 6108:com.samsung.helphub/1000 (adj 15): empty #31
,09-06 18:57:12.989  6783  6783 E wpa_supplicant: Cmd 35605 not handled
,09-06 18:57:12.989  6783  6783 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-06 18:57:12.989  6783  6783 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 18:57:12.989  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 18:57:12.989  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:12.989  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-06 18:57:12.989  6783  6783 I wpa_supplicant: Associated with F4.99.3E
09-06 18:57:12.989  6783  6783 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 18:57:12.989  6783  6783 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 18:57:12.989  6783  6783 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-06 18:57:12.999  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 18:57:12.999  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:12.999  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-06 18:57:12.999  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true,
09-06 18:57:12.999  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
,09-06 18:57:12.999  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,09-06 18:57:12.999  1014  1127 E Tethering: No numeric data
09-06 18:57:12.999  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 18:57:12.999  1014  1127 D Tethering: clearTetheredNotification()
,09-06 18:57:12.999  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-06 18:57:13.009  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:13.009  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:13.009  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:13.009  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 18:57:13.009  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 18:57:13.009  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-06 18:57:13.009  1174  1174 D HotspotTile: updateTetherState():false, false
,09-06 18:57:13.009  1014  1121 V NetworkStats: performPollLocked() took 8ms
09-06 18:57:13.009  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:13.009  6783  6783 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-06 18:57:13.019  6783  6783 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-06 18:57:13.019  6783  6783 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-06 18:57:13.019  6783  6783 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 18:57:13.019  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:13.019  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-06 18:57:13.019  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:13.019  1014  1124 D SecContentProvider2: mCursor = null
09-06 18:57:13.019  6783  6783 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 18:57:13.019  6783  6783 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-06 18:57:13.019  6783  6783 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-06 18:57:13.019  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 18:57:13.019  6783  6783 I wpa_supplicant: Blacklist: Clear (temp) 
,09-06 18:57:13.019  6783  6783 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-06 18:57:13.019  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
,09-06 18:57:13.019  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,09-06 18:57:13.029  1014  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 18:57:13.029  1014  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 18:57:13.039  1014  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-06 18:57:13.039  1014  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-06 18:57:13.039  1014  1126 E ConnectivityService: updateNetworkInfo()
,09-06 18:57:13.039  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 18:57:13.049  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 18:57:13.049  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null,
,09-06 18:57:13.049  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.049  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 18:57:13.049  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-06 18:57:13.049  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:13.059  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-06 18:57:13.059  1014  1524 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:13.069  1014  1524 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:13.069  1014  1524 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:13.069  1014  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:13.069  1014  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:13.069  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:13.079  3691  3691 I Hs20UtilService: Starting #14
,09-06 18:57:13.079  1014  1480 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-06 18:57:13.079  1014  1480 D WifiService: setWifiEnabled: false pid=6219, uid=10155
09-06 18:57:13.079  1014  1480 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 18:57:13.079   281  1000 D CommandListener: Setting iface cfg
09-06 18:57:13.079  1014  1480 D SecContentProvider2: mCursor = null
09-06 18:57:13.079  1014  1480 D SettingsProvider: name = wifi_on
,09-06 18:57:13.089  3691  3726 I Hs20UtilService: Message received 5007
09-06 18:57:13.089  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 18:57:13.089  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 18:57:13.089  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 18:57:13.089  1014  1124 E WifiStateMachine: Start Dhcp Watchdog 2
09-06 18:57:13.089  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:13.089  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:13.099  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 18:57:13.099  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 18:57:13.099  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 18:57:13.099  1308  3059 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 18:57:13.099  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:13.099  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:13.099  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.099  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.099  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.099  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:13.109  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:13.119  1014  1124 E WifiNative-wlan0: do suspend true
,09-06 18:57:13.119  1014  1123 D WifiP2pService: InactiveState{ what=143375 },
09-06 18:57:13.119  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 18:57:13.119   281  1000 D CommandListener: Clearing all IP addresses on wlan0,
09-06 18:57:13.119  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:13.119  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:13.119  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:13.119  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.119  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.119  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.119  1014  1126 E ConnectivityService: updateNetworkInfo()
09-06 18:57:13.119  1014  1126 E ConnectivityService: updateNetworkInfo()
09-06 18:57:13.119  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:57:13.119  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-06 18:57:13.119   281  1000 E Netd    : no such netId 503
,09-06 18:57:13.129  1014  1126 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
09-06 18:57:13.129  1014  1126 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
,09-06 18:57:13.129  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 18:57:13.129  1014  1126 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,09-06 18:57:13.129  1014  1126 D ConnectivityService: nai.networkMonitor.doQuit()
09-06 18:57:13.129  1014  1126 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-06 18:57:13.129  1014  1126 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
,09-06 18:57:13.139  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:13.139  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:13.139  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.139  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.139  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.139  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:13.139  1014  1123 D WifiP2pService: InactiveState{ what=131204 }
,09-06 18:57:13.139  1014  1123 D WifiP2pService: P2pEnabledState{ what=131204 }
09-06 18:57:13.139  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:13.139  1014  1124 D SecContentProvider2: mCursor = null
09-06 18:57:13.139  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-06 18:57:13.139  1014  1126 E ConnectivityService: updateNetworkInfo()
,09-06 18:57:13.139  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 18:57:13.139  1014  1124 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-06 18:57:13.139  1014  1126 E ConnectivityService: updateNetworkInfo()
,09-06 18:57:13.139  1014  1123 D WifiP2pService: P2pDisablingState
09-06 18:57:13.139  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 1
09-06 18:57:13.139  1014  1146 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:13.139  1014  1014 D RttService: SCAN_AVAILABLE : 1
09-06 18:57:13.149  1014  1147 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:13.149  1014  1123 D WifiP2pService: P2pDisablingState{ what=147458 }
,09-06 18:57:13.149  1014  1123 D WifiP2pService: p2p socket connection lost
09-06 18:57:13.149  1014  1123 D WifiP2pService: P2pDisabledState
,09-06 18:57:13.149  1014  1124 E WifiNative-wlan0: do suspend true
,09-06 18:57:13.149  1014  1123 D WifiP2pService: P2pDisabledState{ what=143375 }
09-06 18:57:13.149  1014  1123 D WifiP2pService: DefaultState{ what=143375 }
,09-06 18:57:13.149  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-06 18:57:13.149  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-06 18:57:13.149  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 18:57:13.149  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-06 18:57:13.149  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,09-06 18:57:13.149  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,09-06 18:57:13.149  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 18:57:13.149  1014  1044 D WifiDisplayController: disconnect
09-06 18:57:13.149  1014  1044 D WifiDisplayController: updateConnection
,09-06 18:57:13.149  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 18:57:13.149  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 18:57:13.149  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-06 18:57:13.149  1014  3292 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:13.159  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 18:57:13.159  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:13.159  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:13.159  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:13.159  1014  1522 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-06 18:57:13.159  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-06 18:57:13.159  3691  3691 I Hs20UtilService: Starting #15
,09-06 18:57:13.159   281  1000 D CommandListener: Clearing all IP addresses on wlan0
09-06 18:57:13.159  3691  3726 I Hs20UtilService: Message received 5007
,09-06 18:57:13.159  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:13.159  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:13.159  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.159  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.159  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.159  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:13.159  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 18:57:13.159  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 18:57:13.159  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 18:57:13.159  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 18:57:13.159  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 18:57:13.159  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 18:57:13.159  1308  3059 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 18:57:13.169  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 18:57:13.169  6783  6783 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-06 18:57:13.169  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 18:57:13.169  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:13.169  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.169  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.169  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.169  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:13.179  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:13.179  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:13.179  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 18:57:13.179  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-06 18:57:13.179  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 18:57:13.179  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 18:57:13.179  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.179  1174  1174 D HotspotTile: onReceive : 0, 0
09-06 18:57:13.179  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.179  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.179  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.179  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:13.179  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-06 18:57:13.179  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:13.179  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:13.179  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:13.179  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:13.179  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED,
09-06 18:57:13.179  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:13.179  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
,09-06 18:57:13.179  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null,
,09-06 18:57:13.179  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:13.179  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:13.179  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:13.189  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:13.189  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:13.189  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:13.189  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:13.189  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:13.189  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:13.189  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:13.189  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:13.189  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:13.189  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-06 18:57:13.189  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-06 18:57:13.189  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:13.189  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-06 18:57:13.199  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 18:57:13.199  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 18:57:13.199  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 18:57:13.199  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 18:57:13.199  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 18:57:13.199  1308  3059 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 18:57:13.199  6438  6438 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 18:57:13.199  6438  6438 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-06 18:57:13.199  6438  6438 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 18:57:13.209  6458  6458 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 18:57:13.209  1014  1480 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:13.209  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:13.209  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:13.209  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:13.209  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:13.219  3691  3691 I Hs20UtilService: Starting #16,
,09-06 18:57:13.219  3691  3726 I Hs20UtilService: Message received 5007
,09-06 18:57:13.219  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 18:57:13.219  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 18:57:13.219  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 18:57:13.219  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 18:57:13.219  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 18:57:13.219  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 18:57:13.219  1308  3059 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 18:57:13.229  1014  3292 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:13.229  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:13.229  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:13.229  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:13.229  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:13.239  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 18:57:13.239  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 18:57:13.239  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 18:57:13.239  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 18:57:13.239  3691  3691 I Hs20UtilService: Starting #17
,09-06 18:57:13.249  3691  3726 I Hs20UtilService: Message received 5011
,09-06 18:57:13.359  6783  6783 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 18:57:13.449  6783  6783 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-06 18:57:13.449  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 18:57:13.449  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 18:57:13.449  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-06 18:57:13.469  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 18:57:13.469  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 18:57:13.469  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-06 18:57:13.479  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:13.479  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 18:57:13.479  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-06 18:57:13.479  1014  1127 D Tethering: InitialState.processMessage what=4
09-06 18:57:13.479  6783  6783 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-06 18:57:13.479  6783  6783 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-06 18:57:13.479  6783  6783 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-06 18:57:13.479  6783  6783 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030,
09-06 18:57:13.479  1014  1124 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,09-06 18:57:13.479  6783  6783 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-06 18:57:13.489  1014  1127 E Tethering: No numeric data
09-06 18:57:13.489  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:13.489  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 18:57:13.489  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-06 18:57:13.489  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-06 18:57:13.489  1014  1127 D Tethering: clearTetheredNotification()
,09-06 18:57:13.489  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-06 18:57:13.489  1174  1174 D HotspotTile: updateTetherState():false, false
,09-06 18:57:13.489  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 18:57:13.489  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:13.489  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 18:57:13.489  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 18:57:13.499  1014  1121 V NetworkStats: performPollLocked() took 6ms
,09-06 18:57:13.499  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:13.499  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:13.499  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:13.779  6783  6783 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 18:57:13.819  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:13.819  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 18:57:13.819  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-06 18:57:13.819  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:13.819  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 18:57:13.819  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-06 18:57:13.819  6783  6783 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-06 18:57:13.929  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-06 18:57:13.929  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-06 18:57:13.929  1014  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 18:57:13.939  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:13.939  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 18:57:13.939  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.939  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.939  6473  6473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:57:13.939  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:13.939  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:13.939  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:13.939  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
09-06 18:57:13.939  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:13.939  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-06 18:57:13.939  1932  2122 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-06 18:57:13.939  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:13.939  1174  1174 D HotspotTile: onReceive : 1, 0
09-06 18:57:13.939  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:13.949  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:13.949  1014  1525 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:13.949  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:13.949  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:13.949  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:13.949  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:13.949  3691  3691 I Hs20UtilService: Starting #18
,09-06 18:57:13.949  3691  3726 I Hs20UtilService: Message received 5011
,09-06 18:57:13.959  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 18:57:13.959  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 18:57:13.959  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
09-06 18:57:13.959  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 18:57:14.469   291   291 E SMD     : DCD OFF,
,09-06 18:57:14.689  1014  1041 D Tethering: interfaceRemoved wlan0
,09-06 18:57:14.689  1014  1041 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-06 18:57:14.789  1014  1041 D Tethering: interfaceRemoved p2p0
,09-06 18:57:14.789  1014  1041 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-06 18:57:14.789  1014  1039 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:14.789  1014  1039 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:14.799  1014  1039 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:14.809  1014  1347 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-06 18:57:14.809  1014  1347 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-06 18:57:14.809  1014  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:14.809  1014  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:14.809  1014  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:14.819  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:14.819  1014  1817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:14.819  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:14.839  1014  3294 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 18:57:14.839  1014  3294 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-06 18:57:14.839  1014  3294 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:14.839  1014  3294 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:14.839  1014  3294 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:14.839  1014  1491 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 18:57:14.839  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-06 18:57:14.839  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:14.839  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:14.839  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:14.849  1014  3292 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-06 18:57:14.849  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-06 18:57:14.849  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:14.849  1014  3292 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:14.849  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:14.849  1014  1522 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-06 18:57:14.849  1014  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-06 18:57:14.849  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:14.849  1014  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:14.849  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-06 18:57:14.859  6637  6688 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-06 18:57:14.869  1014  1522 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
09-06 18:57:14.869  1014  1522 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-06 18:57:14.869  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:14.869  1014  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:14.869  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:14.899  1014  1522 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:14.899  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:14.899  1014  1522 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:14.899  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-06 18:57:14.909  1932  1932 D WearableService: callingUid 10012, callindPid: 1932
,09-06 18:57:14.919  1014  1524 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-06 18:57:14.919  1014  1524 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-06 18:57:14.919  1014  1524 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:14.919  1014  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:14.919  1014  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-06 18:57:14.959  6550  6550 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-06 18:57:14.969  6550  6823 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-06 18:57:14.969  6550  6816 I MusicLeanback: Conditions not met for autocaching.
,09-06 18:57:14.969  6550  6816 I MusicLeanback: Stop autocaching.
,09-06 18:57:15.529  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-06 18:57:16.089  6219  6271 D BluetoothAdapter: enable()
,09-06 18:57:16.089  1014  1480 W ActivityManager: Permission Denial: getCurrentUser() from pid=6219, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-06 18:57:16.089  1014  1480 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 18:57:16.089  1014  1480 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6219, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 18:57:16.089  1014  1480 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-06 18:57:16.089  1014  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-06 18:57:16.089  1014  1480 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-06 18:57:16.089  1014  1480 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-06 18:57:16.089  1014  1480 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 18:57:16.099  1014  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 18:57:16.099  1014  1480 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 18:57:16.099  1014  1480 D SettingsProvider: name = bluetooth_on
,09-06 18:57:16.099  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 18:57:16.099  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 18:57:16.099  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-06 18:57:16.099  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-06 18:57:16.139  6516  6516 D BluetoothAdapterState: make
,09-06 18:57:16.149  6516  6516 I bluedroid: init
09-06 18:57:16.149  6516  6825 I BluetoothAdapterState: Entering OffState
,09-06 18:57:16.149  6516  6516 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-06 18:57:16.149  6516  6516 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-06 18:57:16.149  6516  6516 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 18:57:16.149  6516  6516 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-06 18:57:16.159  6516  6516 E bt-btif : btif_fetch_local_ble_random_bdaddr
,09-06 18:57:16.159  6516  6516 I bluedroid: get_profile_interface socket
09-06 18:57:16.159  6516  6516 I bluedroid: get_profile_interface map_client
,09-06 18:57:16.159  6516  6828 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-06 18:57:16.159  6516  6516 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-06 18:57:16.159  6516  6828 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-06 18:57:16.159  6516  6828 E BluetoothServiceJni: populateRssiValuesNative
09-06 18:57:16.159  6516  6828 I bluedroid: getModelRssiValues
09-06 18:57:16.159  6516  6828 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-06 18:57:16.159  6516  6828 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 18:57:16.159  6516  6828 D BluetoothAdapterProperties: Name is: A5-1
,09-06 18:57:16.169  1014  1014 D SettingsProvider: name = bluetooth_name
,09-06 18:57:16.169  6516  6516 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:16.169  1014  1347 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 18:57:16.169  1014  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 18:57:16.169  1014  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:16.169  1014  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:16.169  1014  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:16.179  6516  6524 I bluedroid: config_hci_snoop_log
,09-06 18:57:16.179  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-06 18:57:16.179  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
,09-06 18:57:16.179  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
09-06 18:57:16.179  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 18:57:16.179  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 18:57:16.189  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 18:57:16.189  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,09-06 18:57:16.189  6516  6516 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 18:57:16.189  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 18:57:16.189  6516  6825 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 18:57:16.199  6516  6825 D BluetoothAdapterProperties: Setting state to 11
,09-06 18:57:16.199  6516  6825 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-06 18:57:16.199  6516  6825 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-06 18:57:16.199  6516  6825 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 18:57:16.199  6516  6825 D BluetoothAdapterService: Autoconnection is available 
,09-06 18:57:16.199  6516  6825 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 18:57:16.199  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:16.199  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-06 18:57:16.209  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 18:57:16.209  1781  1781 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 18:57:16.209  6516  6825 D BluetoothSecureManager: getInstant: null
09-06 18:57:16.209  6516  6825 D BluetoothSecureManager: calling getMethod for getService
09-06 18:57:16.209  6516  6825 D BluetoothSecureManager: calling getService
,09-06 18:57:16.209  6516  6825 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@317f76c3
,09-06 18:57:16.209  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:16.209  1174  1174 D BluetoothTile:  getBluetoothState : 11
,09-06 18:57:16.219  1014  1525 D BluetoothSecureManagerService: isSecureModeEnabled
09-06 18:57:16.219  1014  1525 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-06 18:57:16.219  6516  6825 D BtConfig.SecureMode: isSecureModeOn:false
09-06 18:57:16.219  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 18:57:16.219  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:16.219  6516  6825 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 18:57:16.219  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 18:57:16.219  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
09-06 18:57:16.219  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 18:57:16.219  6516  6825 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 18:57:16.219  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 18:57:16.219  6516  6825 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 18:57:16.219  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 18:57:16.219  1014  3294 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 18:57:16.219  6516  6825 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 18:57:16.219  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 18:57:16.219  6516  6825 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 18:57:16.219  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 18:57:16.219  1014  1524 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-06 18:57:16.219  6516  6825 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 18:57:16.219  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 18:57:16.219  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:16.219  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 18:57:16.229  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-06 18:57:16.229  1014  3293 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:16.229  6516  6825 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 18:57:16.229  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 18:57:16.229  1014  3293 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 18:57:16.229  6516  6825 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-06 18:57:16.229  1014  3293 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:16.229  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 18:57:16.229  6516  6825 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:16.229  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 18:57:16.229  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:16.229  1014  3293 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:16.229  1014  3293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:16.229  6516  6825 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:16.229  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 18:57:16.229  6516  6825 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 18:57:16.229  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 18:57:16.229  6516  6825 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 18:57:16.239  6516  6825 D BluetoothBondStateMachine: make
,09-06 18:57:16.239  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 18:57:16.239  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-06 18:57:16.239  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 18:57:16.239  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 18:57:16.249  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:16.249  6516  6829 I BluetoothBondStateMachine: StableState(): Entering Off State
09-06 18:57:16.249  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 18:57:16.249  1014  1817 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:16.249  1014  1817 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 18:57:16.249  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:16.249  1014  1817 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:16.249  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:16.249  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 18:57:16.249  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 18:57:16.249  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 18:57:16.249  6516  6516 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 18:57:16.249  6516  6516 D BtGatt.GattService: Received start request. Starting profile...
09-06 18:57:16.249  6516  6516 D BtGatt.GattService: start()
09-06 18:57:16.249  6516  6516 D BtGatt.GattService: start()
09-06 18:57:16.249  6516  6516 I bluedroid: get_profile_interface gatt
,09-06 18:57:16.249  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
09-06 18:57:16.249  6516  6516 D BtGatt.AdvertiseManager: advertise manager created
,09-06 18:57:16.259  1014  1257 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:16.259  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 18:57:16.259  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:16.259  1014  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:16.259  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:16.259  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-06 18:57:16.259  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 18:57:16.259  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 18:57:16.269  1014  1522 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:16.269  1014  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 18:57:16.269  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:16.269  1014  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:16.269  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:16.279  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 18:57:16.279  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 18:57:16.279  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 18:57:16.279  1014  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:16.279  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 18:57:16.279  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:16.279  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:16.279  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:16.279  6516  6516 D BtGatt.GattService: mStartError = false
09-06 18:57:16.279  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:16.289  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-06 18:57:16.289  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 18:57:16.289  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 18:57:16.289  6516  6516 D HeadsetService: Received start request. Starting profile...
09-06 18:57:16.289  6516  6516 D HeadsetService: start()
09-06 18:57:16.289  1014  1525 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:16.289  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 18:57:16.289  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:16.289  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:16.289  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:16.289  6516  6516 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-06 18:57:16.289  6516  6516 D HeadsetStateMachine: make
,09-06 18:57:16.299  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 18:57:16.299  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 18:57:16.299  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 18:57:16.299  1014  1522 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:16.299  1014  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 18:57:16.299  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:16.299  1014  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:16.299  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:16.299  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 18:57:16.299  6516  6516 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 18:57:16.309  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 18:57:16.309  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 18:57:16.309  1014  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:16.309  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 18:57:16.309  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:16.309  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:16.309  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:16.309  1014  1347 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-06 18:57:16.309  1014  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 18:57:16.309  1014  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:16.309  1014  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:16.309  1014  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 18:57:16.319  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-06 18:57:16.319  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 18:57:16.319  6516  6825 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 18:57:16.319  1014  1257 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 18:57:16.319  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 18:57:16.319  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:16.319  1014  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:16.319  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 18:57:16.319  6516  6516 I bluedroid: get_profile_interface handsfree
09-06 18:57:16.319  1014  1525 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:16.319  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-06 18:57:16.319  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:16.319  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:16.319  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:16.319  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 18:57:16.319  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 18:57:16.329  6516  6825 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:16.329  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,09-06 18:57:16.329  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:16.329  6516  6825 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:16.329  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,09-06 18:57:16.329  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 18:57:16.329  6516  6825 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-06 18:57:16.329  6516  6516 I DualScoManager: Instantiating Dual Sco Manager
09-06 18:57:16.329  6516  6516 I DualScoManager: Set HeadsetServiceHelper
,09-06 18:57:16.329  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService,
09-06 18:57:16.329  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 18:57:16.329  6516  6825 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 18:57:16.329  6516  6825 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 18:57:16.339  6516  6516 D BluetoothAtMessage: createCMTIContentObservers
,09-06 18:57:16.339  1014  1205 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-06 18:57:16.339  1014  1205 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:16.339  1014  1205 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 18:57:16.339  1014  1205 D SettingsProvider: selectionArgs: false
09-06 18:57:16.339  1014  1205 D SettingsProvider: selectionArgs: 1002
,09-06 18:57:16.339  1014  1205 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:16.339  1014  1205 D SettingsProvider: ret = -1
,09-06 18:57:16.339  6516  6833 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 18:57:16.339  6516  6516 D HeadsetService: mStartError = false,
09-06 18:57:16.339  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:16.349  6516  6516 D A2dpService: Received start request. Starting profile...
09-06 18:57:16.349  6516  6516 D A2dpService: start()
,09-06 18:57:16.349  6516  6833 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-06 18:57:16.349  6516  6833 D HeadsetStateMachine: map size, before remove : 0
09-06 18:57:16.349  6516  6516 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 18:57:16.349  6516  6833 D HeadsetStateMachine: map size, after remove: 0
,09-06 18:57:16.349  6516  6516 I bluedroid: get_profile_interface avrcp
,09-06 18:57:16.359  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:16.359  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 18:57:16.359  6516  6516 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 18:57:16.379  6516  6516 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 18:57:16.379  6516  6837 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-06 18:57:16.379  6516  6516 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 18:57:16.379  6516  6516 D A2dpStateMachine: make
,09-06 18:57:16.379  6516  6516 I bluedroid: get_profile_interface a2dp
,09-06 18:57:16.379  6516  6839 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-06 18:57:16.379  6516  6516 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 18:57:16.379  6516  6516 D A2dpService: mStartError = false
,09-06 18:57:16.379  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:16.379  6516  6838 D A2dpStateMachine: Enter Disconnected: -2
09-06 18:57:16.379  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-06 18:57:16.379  6516  6516 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 18:57:16.389  6516  6516 D HidService: Received start request. Starting profile...
09-06 18:57:16.389  6516  6516 D HidService: start()
09-06 18:57:16.389  6516  6516 I bluedroid: get_profile_interface hidhost
09-06 18:57:16.389  6516  6516 D HidService: setHidService(): set to: null
09-06 18:57:16.389  6516  6516 D HidService: mStartError = false
09-06 18:57:16.389  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:16.389  6516  6516 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 18:57:16.389  6516  6516 D HealthService: Received start request. Starting profile...
,09-06 18:57:16.389  6516  6516 D HealthService: start()
,09-06 18:57:16.389  6516  6516 I bluedroid: get_profile_interface health
,09-06 18:57:16.389  6516  6516 D HealthService: mStartError = false
09-06 18:57:16.389  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:16.389  6516  6516 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 18:57:16.399  6516  6516 D PanService: Received start request. Starting profile...
09-06 18:57:16.399  6516  6516 D PanService: start()
09-06 18:57:16.399  6516  6516 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 18:57:16.399  6516  6516 I bluedroid: get_profile_interface pan
,09-06 18:57:16.399  6516  6516 D PanService: mStartError = false
09-06 18:57:16.399  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:16.399  6516  6837 D BluetoothMediaBrowser: no now playing list
,09-06 18:57:16.399  6516  6516 D BluetoothMapService: Received start request. Starting profile...
09-06 18:57:16.399  6516  6516 D BluetoothMapService: start()
,09-06 18:57:16.399  6516  6837 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 18:57:16.399  6516  6516 D BluetoothMapService: mStartError = false
09-06 18:57:16.399  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:16.399  6516  6516 D HeadsetStateMachine: Try to query the phonestate on bind
,09-06 18:57:16.399  1428  6433 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 18:57:16.399  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-06 18:57:16.399  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 18:57:16.409  1428  6433 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 18:57:16.409  6516  6516 D HeadsetStateMachine: Proxy object connected
,09-06 18:57:16.409  6516  6516 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 18:57:16.409  6516  6516 D SapService: Received start request. Starting profile...,
09-06 18:57:16.409  6516  6516 D SapService: start()
09-06 18:57:16.409  6516  6516 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 18:57:16.409  6516  6516 I bluedroid: get_profile_interface sap
09-06 18:57:16.409  6516  6516 D SapService: mStartError = false
,09-06 18:57:16.409  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
09-06 18:57:16.409  6516  6516 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-06 18:57:16.409  6516  6516 D HeadsetPhoneState: sendDeviceDataStateChanged
,09-06 18:57:16.409  6516  6516 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 18:57:16.409  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 18:57:16.409  6516  6516 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 18:57:16.409  6516  6516 D BluetoothA2dp: Proxy object connected
09-06 18:57:16.409  6516  6516 D BluetoothAdapterService: Bluetooth A2dp source service connected
,09-06 18:57:16.409  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 18:57:16.409  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 18:57:16.409  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-06 18:57:16.409  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 18:57:16.409  6516  6833 D HeadsetStateMachine: Disconnected process message: 11
09-06 18:57:16.409  6516  6833 D HeadsetStateMachine: Disconnected process message: 18
09-06 18:57:16.409  6516  6833 D HeadsetStateMachine: Disconnected process message: 10
09-06 18:57:16.409  6516  6833 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 18:57:16.409  6516  6833 D HeadsetStateMachine: Disconnected process message: 11
,09-06 18:57:16.439  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 18:57:16.439  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-06 18:57:16.439  6516  6825 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-06 18:57:16.439  6516  6825 I bluedroid: enable
,09-06 18:57:16.449  6516  6843 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting,
09-06 18:57:16.449  6516  6825 I bt_hci_bdroid: init
,09-06 18:57:16.449  6516  6825 I bt_vendor: bt-vendor : init
,09-06 18:57:16.449  6516  6825 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 18:57:16.449  6516  6825 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-06 18:57:16.449  6516  6825 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-06 18:57:16.449  6516  6825 D bt_userial_mct: userial_init
,09-06 18:57:16.449  6516  6825 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-06 18:57:16.449  6516  6825 I bt_vendor: Starting hciattach daemon
09-06 18:57:16.449  6516  6825 I bt_vendor: try to set false
,09-06 18:57:16.449  6516  6825 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
09-06 18:57:16.449  6516  6825 I bt_vendor: Starting hciattach daemon
09-06 18:57:16.449  6516  6825 I bt_vendor: try to set true
,09-06 18:57:16.469  6847  6847 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 18:57:16.529  6853  6853 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-06 18:57:16.539  6854  6854 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 18:57:16.549  6858  6858 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-06 18:57:16.559  6859  6859 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 18:57:16.569  6860  6860 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 18:57:16.579  6861  6861 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-06 18:57:16.699  1014  3291 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-06 18:57:16.699  1014  3291 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4263, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0,
09-06 18:57:16.699  1014  3291 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-06 18:57:16.709  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-06 18:57:16.709  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate,
09-06 18:57:16.709  1014  3291 D BatteryService: stay LED for charging
09-06 18:57:16.709  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.,
09-06 18:57:16.709  1014  1014 I MotionRecognitionService: Plugged
09-06 18:57:16.709  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false,
09-06 18:57:16.709  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-06 18:57:16.709  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 18:57:16.729  6516  6516 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 18:57:16.729  6516  6833 D HeadsetStateMachine: Disconnected process message: 10
,09-06 18:57:16.739  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:57:16.739  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:57:16.739  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:57:16.819  6864  6864 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-06 18:57:16.829  6865  6865 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 18:57:16.869  6516  6825 I bt_vendor: bluetooth satus is on,
09-06 18:57:16.869  6516  6845 D bt_userial_mct: userial_open(port:0)
09-06 18:57:16.869  6516  6845 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN,
,09-06 18:57:16.869  6516  6845 I bt_vendor: Done intiailizing UART,
,09-06 18:57:16.869  6516  6845 I bt_vendor: Done intiailizing UART
,09-06 18:57:16.869  6516  6845 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 18:57:16.869  6516  6845 I bt_vendor: Bluetooth Firmware and transport layer are initialized
09-06 18:57:16.879  6516  6867 D bt_userial_mct: Entering userial_read_thread(),
,09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_HCI
,09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_AVDT,
09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_A2D
,09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_GAP
,09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_PAN
09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_SAP
,09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_SDP
09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_GATT
,09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_SMP
,09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_BTIF
09-06 18:57:16.879  6516  6843 I         : BTE_InitTraceLevels -- TRC_PROTOCOL,
,09-06 18:57:16.979  6516  6843 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 18:57:16.989  6516  6843 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f7e6e9 
,09-06 18:57:16.989  6516  6843 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f7e6e9 
,09-06 18:57:17.009  6516  6828 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0,
,09-06 18:57:17.009  6516  6828 E bt-btif : Calling BTA_HhEnable
,09-06 18:57:17.009  6516  6828 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 18:57:17.009  6516  6828 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-06 18:57:17.009  6516  6828 E BluetoothServiceJni: populateRssiValuesNative
,09-06 18:57:17.009  6516  6828 I bluedroid: getModelRssiValues
09-06 18:57:17.009  6516  6828 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-06 18:57:17.009  6516  6828 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 18:57:17.019  1014  1014 D SettingsProvider: name = bluetooth_name
,09-06 18:57:17.019  6516  6828 D BluetoothAdapterProperties: Name is: A5-1
,09-06 18:57:17.019  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:17.019  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:17.029  6516  6828 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 18:57:17.029  6516  6828 D BluetoothAdapterProperties: Scan Mode:20
,09-06 18:57:17.029  6516  6828 D BluetoothAdapterProperties: Discoverable Timeout:120
09-06 18:57:17.029  6516  6828 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
09-06 18:57:17.029  6516  6828 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-06 18:57:17.029  6516  6828 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
09-06 18:57:17.029  6516  6828 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-06 18:57:17.029  6516  6828 E bt-btif : btif_sock_init: !vhci_init
09-06 18:57:17.029  6516  6828 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-06 18:57:17.029  6516  6828 D IOP_DB_BT: db_open: db_open : handle 3028676624l, read 13894 bytes onto local cache
09-06 18:57:17.029  6516  6828 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-06 18:57:17.029  6516  6828 D IOP_DB_BT: db_query: result 1
09-06 18:57:17.029  6516  6828 I         : iop_db_open: iop_db_open status 0
,09-06 18:57:17.039  6516  6828 D bte_conf: Device ID record 1 : primary
,09-06 18:57:17.039  6516  6828 D bte_conf:   vendorId            = 0075
,09-06 18:57:17.039  6516  6828 D bte_conf:   vendorIdSource      = 0001
09-06 18:57:17.039  6516  6828 D bte_conf:   product             = 0100
,09-06 18:57:17.039  6516  6828 D bte_conf:   version             = 0200
,09-06 18:57:17.039  6516  6828 D bte_conf:   clientExecutableURL = 
09-06 18:57:17.039  6516  6828 D bte_conf:   serviceDescription  = 
,09-06 18:57:17.039  6516  6828 D bte_conf:   documentationURL    = 
,09-06 18:57:17.039  6516  6828 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 18:57:17.039  6516  6825 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 18:57:17.039  6516  6825 D BluetoothAdapterProperties: ScanMode =  20
,09-06 18:57:17.039  6516  6825 D BluetoothAdapterProperties: State =  11
,09-06 18:57:17.039  6516  6828 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-06 18:57:17.039  1014  1347 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 18:57:17.049  6516  6867 E bt_mct  : hci lib postload completed
,09-06 18:57:17.049  6516  6828 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 18:57:17.049  6516  6828 D BluetoothAdapterProperties: Scan Mode:21
09-06 18:57:17.049  6516  6825 D BluetoothAdapterProperties: Setting state to 12
09-06 18:57:17.049  6516  6828 D BluetoothAdapterProperties: Discoverable Timeout:120,
09-06 18:57:17.049  6516  6825 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 18:57:17.049  1014  1525 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,09-06 18:57:17.049  1014  1525 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:17.049  1014  1525 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:17.049  1014  1525 D SettingsProvider: selectionArgs: false
09-06 18:57:17.049  1014  1525 D SettingsProvider: selectionArgs: 1002
09-06 18:57:17.049  1014  1525 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:17.049  1014  1525 D SettingsProvider: ret = -1
,09-06 18:57:17.049  6516  6825 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 18:57:17.049  6516  6825 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 18:57:17.059  1014  3292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:17.059  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.059  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.059  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.059  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.059  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:17.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:17.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:17.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:17.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:17.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:17.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:17.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:17.069  1308  1329 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 18:57:17.069  6516  6825 D BluetoothAdapterService: Autoconnection is available 
,09-06 18:57:17.069  6516  6825 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,09-06 18:57:17.069  6516  6825 D BluetoothAdapterService: starting service from this receiver
,09-06 18:57:17.069  1014  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:17.069  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.079  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:17.079  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.079  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.079  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-06 18:57:17.079  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.079  6516  6825 I BluetoothAdapterState: Entering On State from state = 11
09-06 18:57:17.079  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:17.079  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:17.079  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.079  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.089  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:17.089  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:17.089  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:17.089  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:17.089  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:17.089  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:17.089  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:17.089  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:17.089  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:17.099  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 18:57:17.099  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:17.099  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:17.099  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 18:57:17.099  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:17.099  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 18:57:17.099  6516  6516 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 18:57:17.099  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 18:57:17.099  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0,
,09-06 18:57:17.099  1014  1014 D BluetoothA2dp: Proxy object connected
,09-06 18:57:17.099  1174  1199 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:17.099  1174  1199 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:17.099  1308  1323 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:17.109  1308  1323 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0,
,09-06 18:57:17.109  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 18:57:17.109  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.109  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:17.109  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.109  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.109  1308  1308 D BluetoothA2dp: Proxy object connected
09-06 18:57:17.109  1308  1308 D A2dpProfile: Bluetooth service connected
09-06 18:57:17.109  6516  6524 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:17.109  1452  1471 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 18:57:17.119  1452  1471 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:17.119  1308  1329 D BluetoothMap: onBluetoothStateChange: up=true
,09-06 18:57:17.119  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
09-06 18:57:17.119  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.119  1308  1308 D BluetoothPbap: Proxy object connected
09-06 18:57:17.119  1308  1308 D PbapServerProfile: Bluetooth service connected
09-06 18:57:17.119  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:17.119  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.119  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.119  1308  6437 D Bluetoothsap: onBluetoothStateChange: up=true
,09-06 18:57:17.119  6516  6516 I BluetoothPbapService: Handler(): got msg=1
,09-06 18:57:17.119  1308  6437 D Bluetoothsap: Binding service...
,09-06 18:57:17.119  1014  1474 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 18:57:17.129  1308  6437 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 18:57:17.129  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-06 18:57:17.129  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.129  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.129  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:17.129  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.129  1308  6437 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 18:57:17.129  1308  1308 D BluetoothMap: Proxy object connected
09-06 18:57:17.129  2873  2885 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:17.129  1308  1308 D MapProfile: Bluetooth service connected
09-06 18:57:17.129  1308  1308 D BluetoothMap: getConnectedDevices()
,09-06 18:57:17.129  2873  2885 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:17.139  1428  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:17.139  6516  6871 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-06 18:57:17.139  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 18:57:17.139  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:17.139  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:17.139  1308  1308 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 18:57:17.139  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.139  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.139  1308  1308 D SapProfile: Bluetooth service connected
09-06 18:57:17.139  1308  1308 D Bluetoothsap: getConnectedDevices()
,09-06 18:57:17.139  1428  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:17.139  6516  6871 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 18:57:17.139  6516  6871 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:17.149  1932  6382 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:17.149  1932  6382 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:17.149  6516  6871 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-06 18:57:17.149  6516  6871 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 18:57:17.149  6516  6871 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 18:57:17.149  6516  6871 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f3b9df6
09-06 18:57:17.149  6390  6402 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:17.149  6390  6402 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:17.149  6516  6871 D BluetoothSocket: channel: 19
,09-06 18:57:17.149  6516  6871 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-06 18:57:17.149  1452  1468 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:17.149  1014  2766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 18:57:17.149  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 18:57:17.149  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:17.149  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.149  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.149  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.149  1452  1468 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:17.159  2873  2942 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:17.159  2873  2942 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:17.159  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 18:57:17.159  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.159  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.159  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.159  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.159  1428  1437 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 18:57:17.159  1428  1437 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 18:57:17.159  2873  2873 D BluetoothA2dp: Proxy object connected
,09-06 18:57:17.159  1308  1323 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:17.159  1308  1323 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:17.159  1428  6433 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:17.169  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 18:57:17.169  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:17.169  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.169  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.169  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.169  1428  6433 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:17.169  6516  6524 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 18:57:17.169  6516  6524 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 18:57:17.169  1308  1329 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 18:57:17.169  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-06 18:57:17.169  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.169  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.169  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.169  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.179  1308  1308 D BluetoothInputDevice: Proxy object connected
,09-06 18:57:17.179  1308  1308 D HidProfile: Bluetooth service connected
,09-06 18:57:17.179  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:17.179  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 18:57:17.179  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 18:57:17.179  1014  1043 D BluetoothPan: Binding service...
09-06 18:57:17.179  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.179  1438  1462 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 18:57:17.179  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 18:57:17.179  1438  1462 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:17.179  6219  6227 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 18:57:17.179  6219  6227 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:17.179  2873  2885 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:17.179  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 18:57:17.179  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:17.179  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.179  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.179  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.189  2873  2885 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:17.189  1308  1323 D BluetoothPan: Binding service...
,09-06 18:57:17.189  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 18:57:17.189  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.189  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:17.189  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.189  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.189  1428  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:17.189  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 18:57:17.189  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:17.189  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:17.189  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.189  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.189  1428  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:17.189  1308  1308 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 18:57:17.189  1308  1308 D PanProfile: Bluetooth service connected
,09-06 18:57:17.189  1308  1329 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:17.199  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 18:57:17.199  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:17.199  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:17.199  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.199  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.199  1308  1329 E BluetoothHeadset: BluetoothHeadset service is binded
09-06 18:57:17.199  1308  1308 D HeadsetProfile: Bluetooth service connected
,09-06 18:57:17.199  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 18:57:17.199  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 18:57:17.199  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:17.199  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
09-06 18:57:17.199  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 18:57:17.209  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@22e9c45d, true
,09-06 18:57:17.209  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-06 18:57:17.209  1428  1428 D BluetoothHeadset: registerMessageListener
,09-06 18:57:17.209  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 18:57:17.209  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:17.209  1174  1174 D BluetoothTile:  getBluetoothState : 12
,09-06 18:57:17.209  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 18:57:17.209  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 18:57:17.219  1014  3292 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 18:57:17.219  1014  1817 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-06 18:57:17.219  1781  1781 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 18:57:17.219  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
09-06 18:57:17.219  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-06 18:57:17.219  1014  1524 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 18:57:17.219  1014  1524 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.219  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:17.219  6516  6525 D HeadsetService: registerMessageListener
,09-06 18:57:17.219  6516  6525 D HeadsetService: registerMessageListener
,09-06 18:57:17.229  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:17.229  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-06 18:57:17.229  1014  1524 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:17.229  1014  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:17.229  1014  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:17.229  6516  6873 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-06 18:57:17.229  6516  6833 D HeadsetStateMachine: Disconnected process message: 70
09-06 18:57:17.229  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 18:57:17.229  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 18:57:17.229  6516  6833 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@28c765f7
,09-06 18:57:17.229  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
,09-06 18:57:17.229  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-06 18:57:17.229  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-06 18:57:17.229  1308  1308 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-06 18:57:17.229  1308  1308 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 18:57:17.229  1308  1308 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 18:57:17.229  1308  1308 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 18:57:17.239  6516  6873 D BluetoothSocket: bindListen(): myUserId = 0
09-06 18:57:17.239  6516  6873 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:17.239  6516  6873 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-06 18:57:17.239  6516  6873 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 18:57:17.239  6516  6873 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 18:57:17.239  6516  6873 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3201dc64
,09-06 18:57:17.239  6516  6873 D BluetoothSocket: channel: 5
,09-06 18:57:17.239  6516  6833 D HeadsetStateMachine: Disconnected process message: 9
,09-06 18:57:17.239  6516  6833 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-06 18:57:17.249  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 18:57:17.249  1014  1480 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 18:57:17.249  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.249  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.249   286   679 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 18:57:17.249  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:17.249   286   679 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 18:57:17.249  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
09-06 18:57:17.249   286   679 V voice   : voice_set_parameters: exit with code(-2)
,09-06 18:57:17.249   286   679 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
,09-06 18:57:17.249   286   679 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 18:57:17.249   286   679 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 18:57:17.249   286   679 V audio_hw_primary: adev_set_parameters: exit
,09-06 18:57:17.249  6516  6833 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-06 18:57:17.259  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:17.259  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 18:57:17.269  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:17.269  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 18:57:17.279  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
09-06 18:57:17.279  6516  6516 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 18:57:17.279  1014  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:17.279  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.279  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.279  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:17.279  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:17.289  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:17.289  1014  3294 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:17.289  1014  3294 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 18:57:17.299  1014  3294 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.299  1014  3294 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:17.299  1014  3294 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:17.309  1014  3291 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 18:57:17.309  1932  6881 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 18:57:17.309  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 18:57:17.329  6516  6883 D BluetoothSocket: bindListen(): myUserId = 0
09-06 18:57:17.329  6516  6883 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:17.329  6516  6883 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-06 18:57:17.329  6516  6883 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 18:57:17.329  6516  6883 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 18:57:17.329  6516  6883 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37325ad0
,09-06 18:57:17.329  6516  6883 D BluetoothSocket: channel: 12
,09-06 18:57:17.329  6516  6883 I BtOppRfcommListener: Accept thread started.
,09-06 18:57:17.389  1932  2105 I art     : Explicit concurrent mark sweep GC freed 50083(2MB) AllocSpace objects, 55(2MB) LOS objects, 40% free, 14MB/24MB, paused 1.408ms total 79.224ms
,09-06 18:57:17.469   291   291 E SMD     : DCD OFF
,09-06 18:57:17.539  1014  3292 I art     : Explicit concurrent mark sweep GC freed 64910(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.424ms total 146.677ms
,09-06 18:57:17.539  1014  3292 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:17.539  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:17.539  1014  3292 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:17.539  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:17.549  1014  1027 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:17.559  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:17.559  1014  1027 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:17.559  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:17.559  1932  6881 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 18:57:18.209  1014  2724 D SSRM:n  : SIOP:: AP = 320
,09-06 18:57:18.739  1014  1297 E Watchdog: !@Sync 4
,09-06 18:57:19.109  6219  6271 D BluetoothAdapter: disable()
,09-06 18:57:19.109  1014  3293 D SettingsProvider: name = bluetooth_on
,09-06 18:57:19.119  6516  6825 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-06 18:57:19.119  6516  6825 D BluetoothAdapterProperties: Setting state to 13
,09-06 18:57:19.119  6516  6825 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-06 18:57:19.119  6516  6825 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-06 18:57:19.119  6516  6825 D BluetoothAdapterService: updateAdapterState state is 13
,09-06 18:57:19.119  1014  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:19.119  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 18:57:19.119  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:19.119  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:19.119  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:19.129  6516  6825 D BluetoothAdapterService: Autoconnection is available 
09-06 18:57:19.129  6516  6825 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-06 18:57:19.129  6516  6825 D BluetoothAdapterService: terminating service from this receiver
09-06 18:57:19.129  6516  6516 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-06 18:57:19.129  6516  6516 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@24fc3ac9, channel: 19, state: LISTENING
,09-06 18:57:19.129  6516  6516 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@24fc3ac9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f3b9df6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@19c475cemSocket: android.net.LocalSocket@3fdf1cef impl:android.net.LocalSocketImpl@3caa53fc fd:FileDescriptor[75]
09-06 18:57:19.129  6516  6516 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3fdf1cef impl:android.net.LocalSocketImpl@3caa53fc fd:FileDescriptor[75]
,09-06 18:57:19.129  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:19.129  1014  1014 I InputMethodManagerService: [BT Setting State] State =13
,09-06 18:57:19.139  1174  1174 D BluetoothTile:  onBluetoothStateChange:
,09-06 18:57:19.139  1781  1781 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 18:57:19.139  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 18:57:19.139  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:19.139  1174  1174 D BluetoothTile:  getBluetoothState : 13
,09-06 18:57:19.139  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:19.139  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 18:57:19.149  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 18:57:19.149  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-06 18:57:19.149  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-06 18:57:19.149  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:19.149  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:19.149  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 18:57:19.149  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:19.149  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:19.149  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:19.149  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:19.149  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:19.149  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:19.149  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:19.149  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:19.149  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-06 18:57:19.149  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:19.149  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:19.149  6516  6825 D BluetoothAdapterProperties: onBluetoothDisable()
09-06 18:57:19.149  6516  6825 D BluetoothAdapterProperties: mDiscovering is false
,09-06 18:57:19.149  1014  1524 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 18:57:19.149  1014  3293 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 18:57:19.149  1014  3293 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 18:57:19.149  6516  6825 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-06 18:57:19.159  1014  3293 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:19.159  1014  1205 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 18:57:19.159  1014  3293 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:19.159  1014  3293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 18:57:19.159  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:19.159  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:19.159  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:19.159  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:19.159  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:19.159  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-06 18:57:19.159  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:19.159  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:19.159  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:19.159  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 18:57:19.159  1014  1491 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 18:57:19.159  6219  6219 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-06 18:57:19.159  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:19.159  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 18:57:19.159  1014  3294 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 18:57:19.159  1014  3294 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 18:57:19.159  6516  6828 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 18:57:19.159  6516  6828 D BluetoothAdapterProperties: Scan Mode:20
09-06 18:57:19.169  1014  3294 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:19.169  1014  3294 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:19.169  1014  3294 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 18:57:19.169  6516  6825 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-06 18:57:19.169  6516  6825 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-06 18:57:19.169  6516  6825 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-06 18:57:19.179  6516  6825 E bt-btif : cmd socket is not created
,09-06 18:57:19.179  6516  6825 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-06 18:57:19.179  6516  6843 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-06 18:57:19.179  6516  6843 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-06 18:57:19.179  6516  6843 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:19.179  6516  6843 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:19.179  6516  6843 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-06 18:57:19.179  6516  6883 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-06 18:57:19.179  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:19.189  1308  1308 D BluetoothPbap: Proxy object disconnected,
09-06 18:57:19.189  1308  1308 D PbapServerProfile: Bluetooth service disconnected,
,09-06 18:57:19.189  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:19.189  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:19.199  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 18:57:19.199  6516  6516 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2b04ba85, channel: 5, state: LISTENING
,09-06 18:57:19.199  6516  6516 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2b04ba85, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3201dc64, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9b620damSocket: android.net.LocalSocket@232a990b impl:android.net.LocalSocketImpl@1d46b3e8 fd:FileDescriptor[77]
,09-06 18:57:19.199  6516  6516 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@232a990b impl:android.net.LocalSocketImpl@1d46b3e8 fd:FileDescriptor[77]
09-06 18:57:19.199  6516  6516 I BtOppRfcommListener: stopping Accept Thread
09-06 18:57:19.199  6516  6516 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@f5b7a01, channel: 12, state: LISTENING
09-06 18:57:19.199  6516  6516 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@f5b7a01, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37325ad0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6e570a6mSocket: android.net.LocalSocket@1e67bae7 impl:android.net.LocalSocketImpl@2c72694 fd:FileDescriptor[80]
09-06 18:57:19.199  6516  6516 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e67bae7 impl:android.net.LocalSocketImpl@2c72694 fd:FileDescriptor[80]
,09-06 18:57:19.199  6516  6883 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-06 18:57:19.199  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:19.199  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-06 18:57:19.209  6516  6516 V BluetoothOppManager: cleanUp...
,09-06 18:57:19.229  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:19.229  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 18:57:19.379  6516  6843 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-06 18:57:19.379  6516  6843 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:19.379  6516  6843 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:57:19.379  6516  6843 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:19.379  6516  6843 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:19.379  6516  6843 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:57:19.379  6516  6843 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-06 18:57:19.379  6516  6843 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-06 18:57:19.379  6516  6843 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-06 18:57:19.379  6516  6843 W bt-btif : ag scb idx 1 not allocated
09-06 18:57:19.379  6516  6843 W bt-btif : ag scb idx 2 not allocated
09-06 18:57:19.379  6516  6843 E bt-btif : BTA AG is already disabled, ignoring ...
09-06 18:57:19.379  6516  6867 I bt_userial_mct: exiting userial_read_thread
09-06 18:57:19.379  6516  6867 D bt_userial_mct: Leaving userial_evt_read_thread()
09-06 18:57:19.379  6516  6828 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-06 18:57:19.379  6516  6845 I bt_vendor: hw_epilog_process
09-06 18:57:19.379  6516  6828 D bt_userial_mct: userial_close
09-06 18:57:19.379  6516  6828 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-06 18:57:20.159   329   329 I ServiceManager: Waiting for service AtCmdFwd...,
,09-06 18:57:20.409  6516  6828 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-06 18:57:20.409  6516  6828 I bt_vendor: bluetooth satus is on
09-06 18:57:20.409  6516  6828 I bt_vendor: bt-vendor : resetting BT status
09-06 18:57:20.409  6516  6828 I bt_vendor: Starting hciattach daemon
09-06 18:57:20.409  6516  6828 I bt_vendor: try to set false
,09-06 18:57:20.409  6516  6828 I bt_vendor: Starting hciattach daemon
09-06 18:57:20.409  6516  6828 I bt_vendor: try to set false
,09-06 18:57:20.409  6516  6828 I bt_vendor: cleanup
,09-06 18:57:20.409  6516  6843 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-06 18:57:20.409  6516  6828 I GKI_LINUX: GKI_exit_task 0 done
,09-06 18:57:20.409  6516  6828 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-06 18:57:20.409  6516  6825 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-06 18:57:20.409  6516  6825 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 18:57:20.409  6516  6825 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-06 18:57:20.409  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,09-06 18:57:20.409  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 18:57:20.419  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 18:57:20.419  1014  1027 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-06 18:57:20.419  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 18:57:20.419  1014  1027 W ActivityManager: userId = 0, bbcId = -10000,
,09-06 18:57:20.419  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:20.419  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:20.419  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,09-06 18:57:20.419  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 18:57:20.419  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 18:57:20.419  1014  1524 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:20.419  1014  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-06 18:57:20.419  6516  6516 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 18:57:20.419  1014  1524 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:20.419  1014  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:20.419  1014  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 18:57:20.419  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 18:57:20.419  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 18:57:20.419  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 18:57:20.419  6516  6516 D BtGatt.GattService: Received stop request...Stopping profile...
09-06 18:57:20.419  6516  6516 D BtGatt.GattService: stop()
09-06 18:57:20.419  6516  6516 D BtGatt.AdvertiseManager: advertise clients cleared
,09-06 18:57:20.429  1014  1525 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-06 18:57:20.429  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:20.429  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-06 18:57:20.429  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-06 18:57:20.429  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 18:57:20.429  1014  1817 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-06 18:57:20.429  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-06 18:57:20.429  1014  1817 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
09-06 18:57:20.429  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 18:57:20.429  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
09-06 18:57:20.429  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
09-06 18:57:20.429  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:20.429  1014  1817 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:20.429  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:20.429  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-06 18:57:20.429  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-06 18:57:20.429  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
09-06 18:57:20.429  6516  6516 D HeadsetService: Received stop request...Stopping profile...
09-06 18:57:20.429  1014  1522 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:20.429  1014  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
09-06 18:57:20.429  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:20.429  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:20.429  1014  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:20.429  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:20.429  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-06 18:57:20.429  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-06 18:57:20.429  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 18:57:20.439  1014  3291 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:20.439  1014  3291 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-06 18:57:20.439  1014  3291 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:20.439  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-06 18:57:20.439  1014  3291 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:20.439  1014  3291 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:20.439  6516  6516 D A2dpService: Received stop request...Stopping profile...
09-06 18:57:20.439  6516  6838 D A2dpStateMachine: Exit Disconnected: -1
,09-06 18:57:20.439  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 18:57:20.439  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:20.439  6516  6825 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-06 18:57:20.439  1308  1308 D HeadsetProfile: Bluetooth service disconnected
,09-06 18:57:20.439  1014  3292 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:20.439  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 18:57:20.439  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:20.439  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:20.439  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:20.449  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-06 18:57:20.449  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 18:57:20.449  6516  6825 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-06 18:57:20.449  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:20.449  1014  1480 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:20.449  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 18:57:20.449  1308  1308 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:20.449  1308  1308 D A2dpProfile: Bluetooth service disconnected
,09-06 18:57:20.449  1014  1014 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:20.449  1014  1014 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-06 18:57:20.449  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:20.449  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:20.449  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:20.449  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:20.449  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:20.449  6516  6825 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:20.449  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:20.449  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:20.449  6516  6825 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:20.449  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 18:57:20.449  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 18:57:20.449  6516  6825 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 18:57:20.449  6516  6825 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 18:57:20.449  6516  6825 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 18:57:20.449  6516  6825 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 18:57:20.449  6516  6825 D BluetoothAdapterState: Stopping profile services that were post enabled
09-06 18:57:20.449  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-06 18:57:20.449  6516  6516 D HidService: Received stop request...Stopping profile...
09-06 18:57:20.449  6516  6516 D HidService: Stopping Bluetooth HidService
09-06 18:57:20.449  6516  6516 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-06 18:57:20.449  6516  6516 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-06 18:57:20.449  6516  6516 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-06 18:57:20.449  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:20.449  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-06 18:57:20.459  6516  6516 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 18:57:20.459  6516  6516 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-06 18:57:20.459  2873  2873 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:20.459  6516  6516 D HealthService: Received stop request...Stopping profile...
09-06 18:57:20.459  1308  1308 D BluetoothInputDevice: Proxy object disconnected
09-06 18:57:20.459  1308  1308 D HidProfile: Bluetooth service disconnected
,09-06 18:57:20.459  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:20.459  6516  6516 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-06 18:57:20.459  6516  6516 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-06 18:57:20.459  6516  6516 D PanService: Received stop request...Stopping profile...
,09-06 18:57:20.459  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:20.459  1014  1014 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-06 18:57:20.459  1308  1308 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-06 18:57:20.459  1308  1308 D PanProfile: Bluetooth service disconnected
,09-06 18:57:20.469  6516  6516 D BluetoothMapService: Received stop request...Stopping profile...
,09-06 18:57:20.469  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:20.469  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true,
09-06 18:57:20.469  6516  6516 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-06 18:57:20.469   291   291 E SMD     : DCD OFF
09-06 18:57:20.469  6516  6516 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-06 18:57:20.469  6516  6516 D BluetoothA2dp: Proxy object disconnected
09-06 18:57:20.469  6516  6516 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-06 18:57:20.469  1308  1308 D BluetoothMap: Proxy object disconnected
,09-06 18:57:20.469  1308  1308 D MapProfile: Bluetooth service disconnected
09-06 18:57:20.469  6516  6839 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-06 18:57:20.469  6516  6516 I GKI_LINUX: GKI_exit_task 2 done
09-06 18:57:20.469  6516  6516 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-06 18:57:20.469  6516  6516 D SapService: Received stop request...Stopping profile...
,09-06 18:57:20.469  6516  6516 D SapService: Stopping Bluetooth SapService
09-06 18:57:20.469  6516  6516 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:20.479  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-06 18:57:20.479  6516  6516 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:20.479  6516  6516 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-06 18:57:20.479  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-06 18:57:20.479  6516  6516 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:20.479  6516  6516 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:20.479  6516  6516 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-06 18:57:20.479  6516  6516 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,09-06 18:57:20.479  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-06 18:57:20.479  6516  6516 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:20.479  6516  6516 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-06 18:57:20.479  6516  6516 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-06 18:57:20.479  6516  6516 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-06 18:57:20.479  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,09-06 18:57:20.479  6516  6516 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 18:57:20.479  6516  6516 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-06 18:57:20.479  6516  6516 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,09-06 18:57:20.479  6516  6516 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-06 18:57:20.479  6516  6516 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-06 18:57:20.479  6516  6825 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-06 18:57:20.479  6516  6825 D BluetoothAdapterProperties: Setting state to 10
09-06 18:57:20.479  6516  6825 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-06 18:57:20.479  6516  6825 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-06 18:57:20.479  6516  6825 D BluetoothAdapterService: updateAdapterState state is 10
,09-06 18:57:20.479  6516  6825 D BluetoothAdapterService: Autoconnection is available 
09-06 18:57:20.479  6516  6825 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-06 18:57:20.479  6516  6825 I BluetoothAdapterState: Entering OffState
09-06 18:57:20.479  1308  1323 D BluetoothPbap: onBluetoothStateChange: up=false
,09-06 18:57:20.479  1308  1308 D Bluetoothsap: BluetoothSAP Proxy object disconnected
,09-06 18:57:20.489  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 18:57:20.489  1174  1185 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:20.489  1174  1185 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.489  1308  1329 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 18:57:20.489  6516  6872 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 18:57:20.489  1452  1468 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 18:57:20.489  1452  1468 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.489  1308  6437 D BluetoothMap: onBluetoothStateChange: up=false
,09-06 18:57:20.489  1308  1323 D Bluetoothsap: onBluetoothStateChange: up=false
,09-06 18:57:20.489  1308  1323 D Bluetoothsap: Unbinding service...
,09-06 18:57:20.489  2873  2890 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 18:57:20.489  2873  2890 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.489  1932  6382 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 18:57:20.489  1932  6382 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.489  6390  6404 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:20.489  6390  6404 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.499  1308  1308 D SapProfile: Bluetooth service disconnected
,09-06 18:57:20.499  2873  2885 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-06 18:57:20.499  1428  6433 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 18:57:20.499  1428  6433 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.499  1308  1329 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:20.499  1308  1329 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.499  6516  6525 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 18:57:20.499  6516  6525 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.499  1308  6437 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-06 18:57:20.499  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-06 18:57:20.499  1014  1043 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.499  1438  1462 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:20.499  1438  1462 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.499  6219  6227 D BluetoothAdapter: onBluetoothStateChange: up=false
09-06 18:57:20.499  6219  6227 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-06 18:57:20.499  6219  6227 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-06 18:57:20.499  6219  6227 D BluetoothLeAdvertiser: Exit stop advertising
09-06 18:57:20.499  6219  6227 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
,09-06 18:57:20.499  6219  6227 D BluetoothLeScanner: Exiting stopAllScan
,09-06 18:57:20.509  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-06 18:57:20.509  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 18:57:20.519  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:20.519  1014  1014 I InputMethodManagerService: [BT Setting State] State =10
,09-06 18:57:20.519  1014  1014 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 18:57:20.519  6516  6828 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,09-06 18:57:20.519  6516  6516 I GKI_LINUX: GKI_exit_task 1 done
,09-06 18:57:20.519  6516  6516 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-06 18:57:20.519  6516  6516 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-06 18:57:20.519  6516  6516 I art     : System.exit called, status: 0
,09-06 18:57:20.519  1174  1174 D BluetoothAdapter: 225522908: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:20.519  6516  6516 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-06 18:57:20.519  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 18:57:20.519  1174  1731 D BluetoothAdapter: 225522908: getState() :  mService = null. Returning STATE_OFF
,09-06 18:57:20.519  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:20.519  1174  1174 D BluetoothTile:  getBluetoothState : 10
09-06 18:57:20.519  1174  1731 D BluetoothAdapter: 225522908: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:20.519  1174  1174 D BluetoothAdapter: 225522908: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:20.519  1174  1174 D BluetoothAdapter: 225522908: getState() :  mService = null. Returning STATE_OFF
,09-06 18:57:20.519  1014  1347 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 18:57:20.519  1781  1781 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 18:57:20.529  1932  2122 D BluetoothAdapter: 34535608: getState() :  mService = null. Returning STATE_OFF
09-06 18:57:20.529  1014  1257 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 18:57:20.529  1932  2122 D BluetoothAdapter: 34535608: getState() :  mService = null. Returning STATE_OFF
,09-06 18:57:20.529  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:20.529  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-06 18:57:20.529  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:20.529  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:20.529  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:20.529  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 18:57:20.529  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:20.529  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:20.529  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:20.539  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 18:57:20.539  1014  1474 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-06 18:57:20.539  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 18:57:20.539  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:20.539  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:20.539  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 18:57:20.549  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:20.549  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive,
,09-06 18:57:20.549  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:20.549  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-06 18:57:20.559  1014  3291 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 18:57:20.559  1014  3291 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-06 18:57:20.569  1014  3291 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-06 18:57:20.569  1014  3291 W BroadcastQueue: android.os.TransactionTooLargeException
09-06 18:57:20.569  1014  3291 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-06 18:57:20.569  1014  3291 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-06 18:57:20.569  1014  3291 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-06 18:57:20.569  1014  3291 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-06 18:57:20.569  1014  3291 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-06 18:57:20.569  1014  3291 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-06 18:57:20.569  1014  3291 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-06 18:57:20.569  1014  3291 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-06 18:57:20.569  1014  3291 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 18:57:20.569  1014  3291 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-06 18:57:20.569  1014  3291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:20.569  1014  3291 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:20.569  1014  3291 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:20.569  1014  3291 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:20.579  6898  6898 E Zygote  : MountEmulatedStorage()
,09-06 18:57:20.579  6898  6898 I libpersona: KNOX_SDCARD checking this for 1002
09-06 18:57:20.579  6898  6898 E Zygote  : v2
09-06 18:57:20.579  6898  6898 I libpersona: KNOX_SDCARD not a persona
09-06 18:57:20.579  6898  6898 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 18:57:20.579  1014  3291 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6898 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-06 18:57:20.589  6898  6898 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 18:57:20.599  6898  6898 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:20.609   311   311 I art     : Explicit concurrent mark sweep GC freed 8710(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 682us total 22.909ms
,09-06 18:57:20.619  6898  6898 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:20.619  6898  6898 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:20.629   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 597us total 21.696ms
,09-06 18:57:20.629  6898  6898 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-06 18:57:20.629  6898  6898 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-06 18:57:20.649   311   311 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 16.796ms
,09-06 18:57:20.659  6898  6898 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding GattService
,09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding HeadsetService
,09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding A2dpService
,09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding HidService
09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding HealthService
,09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding PanService
09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding BluetoothMapService
,09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding SapService
,09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding SapClientService
,09-06 18:57:20.689  6898  6898 D BtSettings.ProfileConfig: Adding HidDevService
09-06 18:57:20.689  6898  6898 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-06 18:57:20.689  1014  1474 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,09-06 18:57:20.689  1014  1474 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:20.689  1014  1474 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.689  1014  1474 D SettingsProvider: selectionArgs: false
09-06 18:57:20.689  1014  1474 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.689  1014  1474 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:20.689  1014  1474 D SettingsProvider: ret = -1
,09-06 18:57:20.689  1014  3292 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-06 18:57:20.689  1014  3292 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 18:57:20.689  1014  3292 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.689  1014  3292 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  3292 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.699  1014  3292 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 18:57:20.699  1014  3292 D SettingsProvider: ret = -1
,09-06 18:57:20.699  1014  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-06 18:57:20.699  1014  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 18:57:20.699  1014  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.699  1014  1026 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  1026 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.699  1014  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 18:57:20.699  1014  1026 D SettingsProvider: ret = -1
,09-06 18:57:20.699  1014  1347 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,09-06 18:57:20.699  1014  1347 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:20.699  1014  1347 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.699  1014  1347 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  1347 D SettingsProvider: selectionArgs: 1002,
09-06 18:57:20.699  1014  1347 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:20.699  1014  1347 D SettingsProvider: ret = -1
09-06 18:57:20.699  1014  1257 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-06 18:57:20.699  1014  1257 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-06 18:57:20.699  1014  1257 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.699  1014  1257 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  1257 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.699  1014  1257 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:20.699  1014  1257 D SettingsProvider: ret = -1
09-06 18:57:20.699  1014  1522 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-06 18:57:20.699  1014  1522 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:20.699  1014  1522 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.699  1014  1522 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  1522 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.699  1014  1522 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:20.699  1014  1522 D SettingsProvider: ret = -1
09-06 18:57:20.699  1014  3291 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-06 18:57:20.699  1014  3291 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-06 18:57:20.699  1014  3291 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.699  1014  3291 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  3291 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.699  1014  3291 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:20.699  1014  3291 D SettingsProvider: ret = -1
09-06 18:57:20.699  1014  1491 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-06 18:57:20.699  1014  1491 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:20.699  1014  1491 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.699  1014  1491 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  1491 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.699  1014  1491 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:20.699  1014  1491 D SettingsProvider: ret = -1
09-06 18:57:20.699  1014  3293 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:20.699  1014  3293 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:20.699  1014  3293 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.699  1014  3293 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  3293 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.699  1014  3293 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:20.699  1014  3293 D SettingsProvider: ret = -1
09-06 18:57:20.699  1014  1525 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:20.699  1014  1525 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:20.699  1014  1525 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.699  1014  1525 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  1525 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.699  1014  1525 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:20.699  1014  1525 D SettingsProvider: ret = -1
,09-06 18:57:20.699  1014  3294 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-06 18:57:20.699  1014  3294 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:20.699  1014  3294 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-06 18:57:20.699  1014  3294 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  3294 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.699  1014  3294 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:20.699  1014  3294 D SettingsProvider: ret = -1
09-06 18:57:20.699  1014  1205 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
,09-06 18:57:20.699  1014  1205 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:20.699  1014  1205 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:20.699  1014  1205 D SettingsProvider: selectionArgs: false
09-06 18:57:20.699  1014  1205 D SettingsProvider: selectionArgs: 1002
09-06 18:57:20.709  1014  1205 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-06 18:57:20.709  1014  1205 D SettingsProvider: ret = -1
,09-06 18:57:20.719  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:20.719  1014  1257 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:20.719  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 18:57:20.719  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:20.719  1014  1257 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:20.719  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:20.729  1932  6914 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 18:57:20.729  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 18:57:20.729  1014  1347 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:20.739  1014  1347 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:20.739  1014  1347 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:20.739  1014  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:20.749  1932  6914 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-06 18:57:21.159   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:57:22.119  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:22.119  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:22.159   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:57:22.989  1014  1987 V SAMP_SPCM_test: CSC File load.. 
,09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory,
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account,
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
,09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control,
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
,09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings,
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-06 18:57:23.009  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
,09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
,09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
,09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
,09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
,09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
,09-06 18:57:23.039  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
,09-06 18:57:23.049  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
09-06 18:57:23.049  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-06 18:57:23.049  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
,09-06 18:57:23.049  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-06 18:57:23.049  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
09-06 18:57:23.049  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-06 18:57:23.049  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation,
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,09-06 18:57:23.059  1014  1987 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-06 18:57:23.069  1014  1987 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-06 18:57:23.159   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:57:23.469   291   291 E SMD     : DCD OFF
,09-06 18:57:24.159   329   329 I ServiceManager: Waiting for service AtCmdFwd...
,09-06 18:57:25.119  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:57:25.119  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13a46615 added. We now have 6 listener(s)
,09-06 18:57:25.119  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:25.119  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:57:25.119  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3d580d2a added. We now have 7 listener(s)
,09-06 18:57:25.119  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:25.119  6219  6271 I System.out: IsBluetoothEnabled
,09-06 18:57:25.129  6219  6271 D BluetoothAdapter: disable()
,09-06 18:57:25.129  1014  1257 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,09-06 18:57:25.129  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:25.129  6219  6271 D BluetoothAdapter: enable()
,09-06 18:57:25.139  1014  3293 W ActivityManager: Permission Denial: getCurrentUser() from pid=6219, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-06 18:57:25.139  1014  3293 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-06 18:57:25.139  1014  3293 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6219, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 18:57:25.139  1014  3293 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-06 18:57:25.139  1014  3293 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-06 18:57:25.139  1014  3293 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-06 18:57:25.139  1014  3293 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-06 18:57:25.139  1014  3293 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 18:57:25.139  1014  3293 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 18:57:25.139  1014  3293 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 18:57:25.139  1014  3293 D SettingsProvider: name = bluetooth_on,
,09-06 18:57:25.149  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-06 18:57:25.149  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 18:57:25.149  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-06 18:57:25.149  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-06 18:57:25.159   329   329 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,09-06 18:57:25.169  6898  6898 D BluetoothAdapterState: make
,09-06 18:57:25.179  6898  6898 I bluedroid: init
,09-06 18:57:25.179  6898  6920 I BluetoothAdapterState: Entering OffState,
,09-06 18:57:25.189  6898  6898 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,09-06 18:57:25.189  6898  6898 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-06 18:57:25.189  6898  6898 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-06 18:57:25.189  6898  6898 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-06 18:57:25.189  6898  6898 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-06 18:57:25.189  6898  6898 I bluedroid: get_profile_interface socket
09-06 18:57:25.189  6898  6898 I bluedroid: get_profile_interface map_client
09-06 18:57:25.189  6898  6923 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-06 18:57:25.189  6898  6923 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB,
09-06 18:57:25.189  6898  6898 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,09-06 18:57:25.189  6898  6923 E BluetoothServiceJni: populateRssiValuesNative
,09-06 18:57:25.189  6898  6923 I bluedroid: getModelRssiValues
,09-06 18:57:25.189  6898  6923 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-06 18:57:25.189  6898  6923 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 18:57:25.199  1014  1014 D SettingsProvider: name = bluetooth_name
,09-06 18:57:25.199  6898  6923 D BluetoothAdapterProperties: Name is: A5-1,
,09-06 18:57:25.199  6898  6898 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:25.199  1014  1257 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 18:57:25.199  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.209  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:25.209  1014  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:25.209  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:25.209  6898  6906 I bluedroid: config_hci_snoop_log
,09-06 18:57:25.209  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-06 18:57:25.219  1014  1043 D BluetoothManagerService: Ble is always on enable gatt
,09-06 18:57:25.219  1014  1043 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-06 18:57:25.219  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,09-06 18:57:25.219  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 18:57:25.219  6898  6898 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-06 18:57:25.229  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 18:57:25.229  1014  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-06 18:57:25.229  1014  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-06 18:57:25.229  6898  6920 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-06 18:57:25.239  6898  6920 D BluetoothAdapterProperties: Setting state to 11
,09-06 18:57:25.239  6898  6920 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,09-06 18:57:25.239  6898  6920 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,09-06 18:57:25.239  6898  6920 D BluetoothAdapterService: updateAdapterState state is 11
,09-06 18:57:25.239  6898  6920 D BluetoothAdapterService: Autoconnection is available 
,09-06 18:57:25.239  6898  6920 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-06 18:57:25.239  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:25.239  1014  1014 I InputMethodManagerService: [BT Setting State] State =11
,09-06 18:57:25.249  6898  6920 D BluetoothSecureManager: getInstant: null
09-06 18:57:25.249  6898  6920 D BluetoothSecureManager: calling getMethod for getService
09-06 18:57:25.249  6898  6920 D BluetoothSecureManager: calling getService
,09-06 18:57:25.249  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-06 18:57:25.259  6898  6920 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@317f76c3
,09-06 18:57:25.259  1014  1480 D BluetoothSecureManagerService: isSecureModeEnabled
09-06 18:57:25.259  1014  1480 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
09-06 18:57:25.259  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:25.259  1174  1174 D BluetoothTile:  getBluetoothState : 11
,09-06 18:57:25.259  6898  6920 D BtConfig.SecureMode: isSecureModeOn:false
09-06 18:57:25.259  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-06 18:57:25.259  6898  6920 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-06 18:57:25.259  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-06 18:57:25.259  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 18:57:25.259  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
09-06 18:57:25.259  6898  6920 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-06 18:57:25.259  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-06 18:57:25.259  6898  6920 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-06 18:57:25.259  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 18:57:25.259  6898  6920 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-06 18:57:25.259  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 18:57:25.259  6898  6920 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-06 18:57:25.259  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 18:57:25.259  6898  6920 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-06 18:57:25.259  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 18:57:25.269  6898  6920 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-06 18:57:25.269  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-06 18:57:25.269  1781  1781 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-06 18:57:25.269  1014  1474 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 18:57:25.269  6898  6920 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService,
09-06 18:57:25.269  1014  3292 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-06 18:57:25.269  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-06 18:57:25.269  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 18:57:25.269  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-06 18:57:25.269  6898  6920 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:25.269  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 18:57:25.269  6898  6920 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,09-06 18:57:25.269  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-06 18:57:25.269  6898  6920 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-06 18:57:25.269  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-06 18:57:25.279  6898  6920 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-06 18:57:25.279  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:25.279  6898  6920 D BluetoothBondStateMachine: make
,09-06 18:57:25.279  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-06 18:57:25.279  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-06 18:57:25.279  6898  6920 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-06 18:57:25.279  6898  6924 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-06 18:57:25.279  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:25.289  1014  3294 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 18:57:25.289  1014  3294 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.289  1014  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-06 18:57:25.289  1014  3294 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:25.289  1014  3294 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:25.289  1014  3294 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:25.289  1014  1257 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:25.289  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.299  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:25.299  1014  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:25.299  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:25.299  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-06 18:57:25.299  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-06 18:57:25.299  6898  6920 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-06 18:57:25.299  6898  6898 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-06 18:57:25.299  6898  6898 D BtGatt.GattService: Received start request. Starting profile...
,09-06 18:57:25.299  6898  6898 D BtGatt.GattService: start()
09-06 18:57:25.299  6898  6898 D BtGatt.GattService: start()
09-06 18:57:25.299  6898  6898 I bluedroid: get_profile_interface gatt
,09-06 18:57:25.299  6898  6898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:25.299  6898  6898 D BtGatt.AdvertiseManager: advertise manager created
,09-06 18:57:25.309  1014  3293 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:25.309  1014  3293 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.309  1014  3293 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:25.309  1014  3293 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:25.309  1014  3293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:25.319  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 18:57:25.319  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-06 18:57:25.319  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-06 18:57:25.319  6898  6920 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-06 18:57:25.319  1014  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:25.319  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.319  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:25.319  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:25.319  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:25.329  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,09-06 18:57:25.329  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-06 18:57:25.329  6898  6920 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-06 18:57:25.329  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:25.329  1014  1522 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:25.329  1014  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.329  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-06 18:57:25.329  6898  6898 D BtGatt.GattService: mStartError = false
,09-06 18:57:25.329  6898  6898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:25.339  1014  1522 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:25.339  1014  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:25.339  1014  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:25.339  6898  6898 D HeadsetService: Received start request. Starting profile...
,09-06 18:57:25.339  6898  6898 D HeadsetService: start()
,09-06 18:57:25.339  6898  6898 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-06 18:57:25.339  6898  6898 D HeadsetStateMachine: make
09-06 18:57:25.339  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-06 18:57:25.339  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-06 18:57:25.339  6898  6920 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-06 18:57:25.349  1014  1817 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:25.349  1014  1817 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.349  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:25.349  1014  1817 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:25.349  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:25.349  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-06 18:57:25.349  6898  6898 E HeadsetStateMachine: # of Max HF connection is 2
,09-06 18:57:25.359  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-06 18:57:25.359  6898  6920 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-06 18:57:25.359  1014  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:25.359  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.359  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:25.359  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:25.359  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:25.359  1014  1525 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
09-06 18:57:25.359  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.359  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:25.359  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-06 18:57:25.359  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-06 18:57:25.359  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:25.359  6898  6920 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
09-06 18:57:25.359  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 18:57:25.369  1014  1524 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:25.369  1014  1524 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.369  1014  1524 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:25.369  1014  1524 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:25.369  1014  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:25.369  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-06 18:57:25.369  1014  1027 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
09-06 18:57:25.369  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.369  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-06 18:57:25.369  6898  6920 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-06 18:57:25.369  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:25.369  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:25.369  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-06 18:57:25.369  6898  6898 I bluedroid: get_profile_interface handsfree
,09-06 18:57:25.369  1014  1347 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:25.369  1014  1347 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 18:57:25.369  1014  1347 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:25.379  1014  1347 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:25.379  1014  1347 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:25.379  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:25.379  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:25.379  6898  6920 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-06 18:57:25.379  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:25.379  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:25.379  6898  6920 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-06 18:57:25.379  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-06 18:57:25.379  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-06 18:57:25.379  6898  6920 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-06 18:57:25.379  6898  6920 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-06 18:57:25.379  6898  6920 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-06 18:57:25.379  6898  6920 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-06 18:57:25.379  6898  6920 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-06 18:57:25.389  6898  6898 I DualScoManager: Instantiating Dual Sco Manager
09-06 18:57:25.389  6898  6898 I DualScoManager: Set HeadsetServiceHelper
09-06 18:57:25.389  6898  6898 D BluetoothAtMessage: createCMTIContentObservers
,09-06 18:57:25.389  1014  1522 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
09-06 18:57:25.389  1014  1522 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:25.389  1014  1522 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-06 18:57:25.389  1014  1522 D SettingsProvider: selectionArgs: false
09-06 18:57:25.389  1014  1522 D SettingsProvider: selectionArgs: 1002
09-06 18:57:25.389  1014  1522 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-06 18:57:25.389  1014  1522 D SettingsProvider: ret = -1
,09-06 18:57:25.389  6898  6928 D HeadsetStateMachine: Enter Disconnected: -2
,09-06 18:57:25.389  6898  6898 D HeadsetService: mStartError = false
09-06 18:57:25.389  6898  6898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:25.399  6898  6928 D HeadsetStateMachine: Clear mHeadsetBrsf
09-06 18:57:25.399  6898  6898 D A2dpService: Received start request. Starting profile...
09-06 18:57:25.399  6898  6898 D A2dpService: start()
,09-06 18:57:25.399  6898  6928 D HeadsetStateMachine: map size, before remove : 0
,09-06 18:57:25.399  6898  6928 D HeadsetStateMachine: map size, after remove: 0
,09-06 18:57:25.399  6898  6898 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-06 18:57:25.399  6898  6898 I bluedroid: get_profile_interface avrcp
,09-06 18:57:25.409  6898  6898 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-06 18:57:25.419  6898  6898 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-06 18:57:25.419  6898  6933 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include,
,09-06 18:57:25.419  6898  6898 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-06 18:57:25.419  6898  6898 D A2dpStateMachine: make
,09-06 18:57:25.429  6898  6898 I bluedroid: get_profile_interface a2dp
,09-06 18:57:25.429  6898  6935 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,09-06 18:57:25.429  6898  6898 E bt-btif : warning : media task started media_task_refcnt 1 
,09-06 18:57:25.429  6898  6898 D A2dpService: mStartError = false
09-06 18:57:25.429  6898  6898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:25.429  6898  6898 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-06 18:57:25.429  6898  6934 D A2dpStateMachine: Enter Disconnected: -2
,09-06 18:57:25.429  6898  6898 I BluetoothHidServiceJni: classInitNative: succeeds
,09-06 18:57:25.429  6898  6898 D HidService: Received start request. Starting profile...
09-06 18:57:25.429  6898  6898 D HidService: start()
09-06 18:57:25.429  6898  6898 I bluedroid: get_profile_interface hidhost
09-06 18:57:25.429  6898  6898 D HidService: setHidService(): set to: null
09-06 18:57:25.429  6898  6898 D HidService: mStartError = false
09-06 18:57:25.429  6898  6898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:25.429  6898  6898 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-06 18:57:25.439  6898  6898 D HealthService: Received start request. Starting profile...
09-06 18:57:25.439  6898  6898 D HealthService: start()
,09-06 18:57:25.439  6898  6933 D BluetoothMediaBrowser: no now playing list
09-06 18:57:25.439  6898  6933 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-06 18:57:25.439  6898  6898 I bluedroid: get_profile_interface health
,09-06 18:57:25.439  6898  6898 D HealthService: mStartError = false
,09-06 18:57:25.439  6898  6898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:25.439  6898  6898 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-06 18:57:25.439  6898  6898 D PanService: Received start request. Starting profile...
09-06 18:57:25.439  6898  6898 D PanService: start()
09-06 18:57:25.439  6898  6898 D BluetoothPanServiceJni: initializeNative(L110): pan
09-06 18:57:25.439  6898  6898 I bluedroid: get_profile_interface pan
,09-06 18:57:25.439  6898  6898 D PanService: mStartError = false
09-06 18:57:25.439  6898  6898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:25.449  6898  6898 D HeadsetStateMachine: Try to query the phonestate on bind
,09-06 18:57:25.449  1428  1445 I Telecom : BluetoothPhoneService: queryPhoneState
,09-06 18:57:25.449  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-06 18:57:25.449  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 18:57:25.449  1428  1445 I Telecom : BluetoothPhoneService: Result of Message : true
,09-06 18:57:25.449  6898  6898 D BluetoothMapService: Received start request. Starting profile...
09-06 18:57:25.449  6898  6898 D BluetoothMapService: start()
,09-06 18:57:25.449  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:25.449  6898  6898 D BluetoothMapService: mStartError = false
09-06 18:57:25.449  6898  6898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:25.449  6898  6898 D HeadsetStateMachine: Proxy object connected
,09-06 18:57:25.459  6898  6898 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-06 18:57:25.459  6898  6898 D SapService: Received start request. Starting profile...
09-06 18:57:25.459  6898  6898 D SapService: start()
09-06 18:57:25.459  6898  6898 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-06 18:57:25.459  6898  6898 I bluedroid: get_profile_interface sap
09-06 18:57:25.459  6898  6898 D SapService: mStartError = false
09-06 18:57:25.459  6898  6898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
09-06 18:57:25.459  6898  6898 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-06 18:57:25.459  6898  6898 D HeadsetPhoneState: sendDeviceDataStateChanged
09-06 18:57:25.459  6898  6928 D HeadsetStateMachine: Disconnected process message: 11
,09-06 18:57:25.459  6898  6898 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-06 18:57:25.459  6898  6898 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-06 18:57:25.459  6898  6928 D HeadsetStateMachine: Disconnected process message: 18
09-06 18:57:25.459  6898  6898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-06 18:57:25.459  6898  6898 D BluetoothA2dp: Proxy object connected
,09-06 18:57:25.459  6898  6898 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-06 18:57:25.459  6898  6928 D HeadsetStateMachine: Disconnected process message: 10
09-06 18:57:25.459  6898  6898 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-06 18:57:25.459  6898  6898 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-06 18:57:25.459  6898  6928 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-06 18:57:25.459  6898  6928 D HeadsetStateMachine: Disconnected process message: 11
,09-06 18:57:25.459  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 18:57:25.459  6898  6898 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true,
09-06 18:57:25.459  6898  6898 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-06 18:57:25.489  6898  6898 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-06 18:57:25.489  6898  6898 E BluetoothAdapterService(993935557): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true,
,09-06 18:57:25.489  6898  6920 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-06 18:57:25.489  6898  6920 I bluedroid: enable
,09-06 18:57:25.489  6898  6920 I bt_hci_bdroid: init
,09-06 18:57:25.489  6898  6939 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-06 18:57:25.489  6898  6920 I bt_vendor: bt-vendor : init
,09-06 18:57:25.489  6898  6920 I bt_vendor: bt-vendor : get_bt_soc_type
09-06 18:57:25.489  6898  6920 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-06 18:57:25.489  6898  6920 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-06 18:57:25.489  6898  6920 D bt_userial_mct: userial_init
,09-06 18:57:25.489  6898  6920 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-06 18:57:25.489  6898  6920 I bt_vendor: Starting hciattach daemon
,09-06 18:57:25.489  6898  6920 I bt_vendor: try to set false
,09-06 18:57:25.489  6898  6920 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On,
09-06 18:57:25.489  6898  6920 I bt_vendor: Starting hciattach daemon
,09-06 18:57:25.499  6898  6920 I bt_vendor: try to set true
,09-06 18:57:25.509  6943  6943 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-06 18:57:25.549  6949  6949 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,09-06 18:57:25.559  6950  6950 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 18:57:25.579  6952  6952 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 18:57:25.589  6953  6953 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-06 18:57:25.589  6954  6954 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-06 18:57:25.599  6955  6955 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-06 18:57:25.799  6958  6958 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-06 18:57:25.809  6959  6959 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-06 18:57:25.849  6898  6920 I bt_vendor: bluetooth satus is on
,09-06 18:57:25.849  6898  6941 D bt_userial_mct: userial_open(port:0)
09-06 18:57:25.849  6898  6941 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-06 18:57:25.859  6898  6941 I bt_vendor: Done intiailizing UART,
,09-06 18:57:25.859  6898  6941 I bt_vendor: Done intiailizing UART,
09-06 18:57:25.859  6898  6941 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-06 18:57:25.859  6898  6941 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-06 18:57:25.869  6898  6961 D bt_userial_mct: Entering userial_read_thread()
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_HCI,
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_AVDT
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_AVRC
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_A2D
,09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_BNEP
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_BTM
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_GAP,
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_PAN
,09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_SAP
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_SDP,
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_GATT
,09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_SMP
,09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_BTIF,
09-06 18:57:25.869  6898  6939 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-06 18:57:25.969  6898  6939 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-06 18:57:25.969  6898  6939 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa407c6e9 
,09-06 18:57:25.969  6898  6939 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa407c6e9 
,09-06 18:57:25.989  6898  6923 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-06 18:57:25.989  6898  6923 E bt-btif : Calling BTA_HhEnable
,09-06 18:57:25.999  6898  6923 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-06 18:57:25.999  6898  6923 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-06 18:57:25.999  6898  6923 E BluetoothServiceJni: populateRssiValuesNative
,09-06 18:57:25.999  6898  6923 I bluedroid: getModelRssiValues
,09-06 18:57:25.999  6898  6923 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-06 18:57:25.999  6898  6923 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-06 18:57:25.999  1014  1014 D SettingsProvider: name = bluetooth_name
,09-06 18:57:25.999  6898  6923 D BluetoothAdapterProperties: Name is: A5-1
,09-06 18:57:26.009  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:26.009  6898  6923 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-06 18:57:26.009  6898  6923 D BluetoothAdapterProperties: Scan Mode:20
,09-06 18:57:26.009  6898  6923 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 18:57:26.019  6898  6923 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-06 18:57:26.019  6898  6923 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-06 18:57:26.019  6898  6923 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-06 18:57:26.019  6898  6923 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-06 18:57:26.019  6898  6923 E bt-btif : btif_sock_init: !vhci_init
,09-06 18:57:26.019  6898  6923 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-06 18:57:26.019  6898  6923 D IOP_DB_BT: db_open: db_open : handle 3028774928l, read 13894 bytes onto local cache
09-06 18:57:26.019  6898  6923 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-06 18:57:26.019  6898  6923 D IOP_DB_BT: db_query: result 1
09-06 18:57:26.019  6898  6923 I         : iop_db_open: iop_db_open status 0
09-06 18:57:26.019  6898  6923 D bte_conf: Device ID record 1 : primary
09-06 18:57:26.019  6898  6923 D bte_conf:   vendorId            = 0075
09-06 18:57:26.019  6898  6923 D bte_conf:   vendorIdSource      = 0001
09-06 18:57:26.019  6898  6923 D bte_conf:   product             = 0100
09-06 18:57:26.019  6898  6923 D bte_conf:   version             = 0200
09-06 18:57:26.019  6898  6923 D bte_conf:   clientExecutableURL = 
09-06 18:57:26.019  6898  6923 D bte_conf:   serviceDescription  = 
09-06 18:57:26.019  6898  6923 D bte_conf:   documentationURL    = 
09-06 18:57:26.019  6898  6923 D bte_conf: bte_load_did_conf no section named DID2.
,09-06 18:57:26.019  6898  6923 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-06 18:57:26.029  6898  6920 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-06 18:57:26.029  6898  6920 D BluetoothAdapterProperties: ScanMode =  20
,09-06 18:57:26.029  6898  6920 D BluetoothAdapterProperties: State =  11
,09-06 18:57:26.029  1014  1522 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-06 18:57:26.029  6898  6920 D BluetoothAdapterProperties: Setting state to 12
09-06 18:57:26.029  6898  6920 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-06 18:57:26.029  6898  6923 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-06 18:57:26.029  6898  6923 D BluetoothAdapterProperties: Scan Mode:21
09-06 18:57:26.029  6898  6923 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-06 18:57:26.029  1014  1480 D SettingsProvider: name = bluetooth_a2dp_sink_mode,
09-06 18:57:26.029  1014  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-06 18:57:26.029  1014  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
09-06 18:57:26.029  1014  1480 D SettingsProvider: selectionArgs: false
,09-06 18:57:26.029  1014  1480 D SettingsProvider: selectionArgs: 1002
09-06 18:57:26.029  1014  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-06 18:57:26.029  1014  1480 D SettingsProvider: ret = -1
09-06 18:57:26.029  6898  6920 D BluetoothAdapterService: Bluetooth PBAP supproted is true,
09-06 18:57:26.029  6898  6920 D BluetoothAdapterService: updateAdapterState state is 12
,09-06 18:57:26.039  1014  1257 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:26.029  6898  6961 E bt_mct  : hci lib postload completed,
09-06 18:57:26.039  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
09-06 18:57:26.039  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.039  1014  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.039  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.039  6898  6920 D BluetoothAdapterService: Autoconnection is available 
,09-06 18:57:26.049  6898  6920 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-06 18:57:26.049  6898  6920 D BluetoothAdapterService: starting service from this receiver
09-06 18:57:26.049  1014  3294 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-06 18:57:26.049  1014  3294 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0,
09-06 18:57:26.049  1014  3294 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.049  1014  3294 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.049  1014  3294 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-06 18:57:26.049  6898  6920 I BluetoothAdapterState: Entering On State from state = 11
,09-06 18:57:26.049  1308  6437 D BluetoothPbap: onBluetoothStateChange: up=true
,09-06 18:57:26.049  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,09-06 18:57:26.059  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.059  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.059  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.059  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
09-06 18:57:26.059  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:26.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:26.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:26.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:26.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:26.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:26.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:26.059  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:26.059  1014  1043 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:26.059  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 18:57:26.059  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:26.059  1014  1043 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:26.059  1014  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:26.069  1014  1043 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-06 18:57:26.069  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 18:57:26.069  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.069  1014  1014 D BluetoothA2dp: Proxy object connected
,09-06 18:57:26.069  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:26.069  1174  1199 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:26.069  1174  1199 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:26.069  1308  1329 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:26.069  1308  1329 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:26.069  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-06 18:57:26.069  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.069  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.079  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.079  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.079  1308  1308 D BluetoothA2dp: Proxy object connected
09-06 18:57:26.079  1452  1468 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:26.079  1452  1468 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:26.079  1308  6437 D BluetoothMap: onBluetoothStateChange: up=true
09-06 18:57:26.079  1308  1308 D A2dpProfile: Bluetooth service connected
,09-06 18:57:26.079  6898  6898 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-06 18:57:26.079  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-06 18:57:26.079  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.079  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.079  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.079  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.089  1308  1329 D Bluetoothsap: onBluetoothStateChange: up=true
09-06 18:57:26.089  1308  1329 D Bluetoothsap: Binding service...
,09-06 18:57:26.089  1308  1329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-06 18:57:26.089  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-06 18:57:26.089  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.089  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.089  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.089  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.089  1308  1329 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-06 18:57:26.089  1308  1308 D BluetoothPbap: Proxy object connected
09-06 18:57:26.089  1308  1308 D PbapServerProfile: Bluetooth service connected
09-06 18:57:26.089  2873  2942 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:26.089  2873  2942 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:26.099  1428  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:26.099  6898  6898 I BluetoothPbapService: Handler(): got msg=1
,09-06 18:57:26.099  1014  3293 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 18:57:26.099  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 18:57:26.099  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:26.099  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.099  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.099  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.099  1308  1308 D BluetoothMap: Proxy object connected
,09-06 18:57:26.099  1308  1308 D MapProfile: Bluetooth service connected
,09-06 18:57:26.109  1428  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:26.109  1308  1308 D BluetoothMap: getConnectedDevices()
09-06 18:57:26.109  1932  2099 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:26.109  1932  2099 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:26.109  6390  6402 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:26.109  6898  6965 V BluetoothPbapService: PBAP Service initSocket try: 0
09-06 18:57:26.109  6390  6402 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:26.109  1452  1816 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:26.109  1308  1308 D Bluetoothsap: BluetoothSAP Proxy object connected
09-06 18:57:26.109  1308  1308 D SapProfile: Bluetooth service connected
09-06 18:57:26.109  1308  1308 D Bluetoothsap: getConnectedDevices()
09-06 18:57:26.109  1014  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 18:57:26.109  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:26.109  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.109  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.109  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.109  1452  1816 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:26.109  2873  2890 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:26.109  6898  6965 D BluetoothSocket: bindListen(): myUserId = 0
,09-06 18:57:26.109  6898  6965 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:26.109  2873  2890 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:26.109  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-06 18:57:26.109  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.119  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.119  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.119  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.119  6898  6965 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-06 18:57:26.119  6898  6965 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 18:57:26.119  6898  6965 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 18:57:26.119  6898  6965 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f3b9df6
09-06 18:57:26.119  6898  6965 D BluetoothSocket: channel: 19
09-06 18:57:26.119  6898  6965 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-06 18:57:26.119  6898  6906 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:26.119  6898  6906 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:26.119  2873  2873 D BluetoothA2dp: Proxy object connected
09-06 18:57:26.119  1428  1445 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:26.119  1428  1445 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:26.119  1308  1329 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:26.119  1308  1329 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:26.119  1428  6433 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:26.119  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 18:57:26.119  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:26.119  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.119  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:26.119  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.119  1428  6433 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:26.129  1308  1323 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-06 18:57:26.129  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,09-06 18:57:26.129  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.129  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.129  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:26.129  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.129  1308  1308 D BluetoothInputDevice: Proxy object connected
,09-06 18:57:26.129  1308  1308 D HidProfile: Bluetooth service connected
09-06 18:57:26.129  1014  1043 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:26.129  1014  1043 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 18:57:26.129  1014  1043 D BluetoothPan: Binding service...
09-06 18:57:26.129  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 18:57:26.129  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.139  1438  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-06 18:57:26.139  1438  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-06 18:57:26.139  6219  6229 D BluetoothAdapter: onBluetoothStateChange: up=true
09-06 18:57:26.139  6219  6229 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-06 18:57:26.139  1014  1014 D BluetoothPan: BluetoothPAN Proxy object connected
,09-06 18:57:26.139  2873  2885 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:26.139  1014  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-06 18:57:26.139  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:26.139  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.139  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:26.139  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.139  2873  2885 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:26.149  1308  1329 D BluetoothPan: Binding service...
,09-06 18:57:26.149  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-06 18:57:26.149  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.149  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.149  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.149  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.149  6898  6909 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-06 18:57:26.149  1308  1308 D BluetoothPan: BluetoothPAN Proxy object connected
09-06 18:57:26.149  1308  1308 D PanProfile: Bluetooth service connected
,09-06 18:57:26.149  1428  1445 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:26.149  1014  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 18:57:26.149  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:26.149  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.149  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.149  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.149  1428  1445 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:26.159  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:26.159  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:26.159  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:26.159  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-06 18:57:26.159  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:26.159  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:26.159  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:26.159  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:26.159  1308  1323 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-06 18:57:26.159  1014  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-06 18:57:26.159  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-06 18:57:26.159  1014  1043 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.159  1014  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.159  1014  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.159  1308  1308 D HeadsetProfile: Bluetooth service connected
09-06 18:57:26.159  1308  1323 E BluetoothHeadset: BluetoothHeadset service is binded
,09-06 18:57:26.159  1014  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-06 18:57:26.159  1014  1043 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-06 18:57:26.159  1014  1014 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-06 18:57:26.159  1014  1014 I InputMethodManagerService: [BT Setting State] State =12
,09-06 18:57:26.159  1014  1014 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-06 18:57:26.169  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:26.169  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@144b21d2, true
,09-06 18:57:26.169  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:57:26.169  1428  1428 D BluetoothHeadset: registerMessageListener
,09-06 18:57:26.169  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afc971b added. We now have 8 listener(s)
,09-06 18:57:26.169  1174  1174 D BluetoothTile:  onBluetoothStateChange:
09-06 18:57:26.169  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:26.169  1174  1174 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-06 18:57:26.169  1174  1174 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:26.169  1174  1174 D BluetoothTile:  getBluetoothState : 12
,09-06 18:57:26.179  1781  1781 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
09-06 18:57:26.179  1014  1524 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 18:57:26.179  1014  1524 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 18:57:26.179  1014  1524 D SecContentProvider2: mCursor = null
,09-06 18:57:26.179  1014  1027 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 18:57:26.179  1014  1522 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-06 18:57:26.179  1014  1524 D WifiService: setWifiEnabled: false pid=6219, uid=10155
,09-06 18:57:26.179  1014  1524 D SettingsProvider: name = wifi_on
09-06 18:57:26.179  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:26.179  1174  1174 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-06 18:57:26.179  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 18:57:26.179  1014  1491 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 18:57:26.179  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 18:57:26.179  6898  6906 D HeadsetService: registerMessageListener
,09-06 18:57:26.179  6898  6906 D HeadsetService: registerMessageListener
09-06 18:57:26.179  1014  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-06 18:57:26.189  6898  6928 D HeadsetStateMachine: Disconnected process message: 70
09-06 18:57:26.189  6898  6928 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@28c765f7
,09-06 18:57:26.189  1308  1308 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:26.189  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-06 18:57:26.189  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-06 18:57:26.189  1014  1491 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.189  1014  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:26.189  1014  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:26.189  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1,
09-06 18:57:26.189  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1,
09-06 18:57:26.189  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-06 18:57:26.189  1174  1731 D BluetoothTile:  handleUpdatestate:false name:null
,09-06 18:57:26.189  6898  6969 D BluetoothMapMasInstance: set MAP SDP message type : 1
09-06 18:57:26.189  1308  1308 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-06 18:57:26.189  1308  1308 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-06 18:57:26.189  1308  1308 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-06 18:57:26.189  1308  1308 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-06 18:57:26.189  6898  6928 D HeadsetStateMachine: Disconnected process message: 9
,09-06 18:57:26.189  6898  6928 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
09-06 18:57:26.189  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:26.199  1014  3292 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-06 18:57:26.199  1014  3292 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-06 18:57:26.199  1014  3292 D SecContentProvider2: mCursor = null
,09-06 18:57:26.199  1014  3292 D WifiService: setWifiEnabled: true pid=6219, uid=10155
09-06 18:57:26.199  1014  3292 W ActivityManager: Permission Denial: getCurrentUser() from pid=6219, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-06 18:57:26.199  1014  3292 W WifiService: Failed getting userId using ActivityManagerNative
09-06 18:57:26.199  1014  3292 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6219, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-06 18:57:26.199  1014  3292 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-06 18:57:26.199  1014  3292 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-06 18:57:26.199  1014  3292 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-06 18:57:26.199  1014  3292 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-06 18:57:26.199  1014  3292 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-06 18:57:26.199  1014  3292 D SettingsProvider: name = wifi_on
,09-06 18:57:26.199  6898  6969 D BluetoothSocket: bindListen(): myUserId = 0
09-06 18:57:26.199  6898  6969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:26.209  6898  6969 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-06 18:57:26.209  6898  6969 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 18:57:26.209  6898  6969 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 18:57:26.209  6898  6969 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3201dc64
,09-06 18:57:26.209   286   286 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-06 18:57:26.209   286   286 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-06 18:57:26.209   286   286 V voice   : voice_set_parameters: exit with code(-2)
09-06 18:57:26.209   286   286 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-06 18:57:26.209   286   286 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-06 18:57:26.209   286   286 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-06 18:57:26.209   286   286 V audio_hw_primary: adev_set_parameters: exit
,09-06 18:57:26.209  6898  6928 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
09-06 18:57:26.209  6898  6969 D BluetoothSocket: channel: 5
,09-06 18:57:26.209  1014  1124 E WifiHW  : ##################### set firmware type 0 #####################
,09-06 18:57:26.209  1308  1308 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-06 18:57:26.209  1014  1525 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-06 18:57:26.209  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.209  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.209  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.209  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-06 18:57:26.229  1308  1308 D DockEventReceiver: finishStartingService: stopping service
,09-06 18:57:26.229  1308  1308 D BluetoothNotiBroadcastReceiver: onReceive
,09-06 18:57:26.239  1174  1174 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-06 18:57:26.239  1174  1174 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-06 18:57:26.249  6898  6898 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
,09-06 18:57:26.249  6898  6898 D BtConfig.SecureMode: isSecureModeOn:false
,09-06 18:57:26.249  1014  1474 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-06 18:57:26.249  1014  1474 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.249  1014  1474 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.249  1014  1474 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:26.249  1014  1474 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-06 18:57:26.269  1932  1932 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-06 18:57:26.269  1014  1525 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-06 18:57:26.269  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-06 18:57:26.269  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.269  1014  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-06 18:57:26.269  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:26.279  1014  1817 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-06 18:57:26.279  1932  6979 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-06 18:57:26.279  1932  1932 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-06 18:57:26.289  1014  1817 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:26.289  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.289  1014  1817 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:26.289  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:26.299  6898  6981 D BluetoothSocket: bindListen(): myUserId = 0
09-06 18:57:26.299  6898  6981 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-06 18:57:26.299  6898  6981 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[81]}
09-06 18:57:26.299  6898  6981 D BluetoothSocket: bindListen(), new LocalSocket 
09-06 18:57:26.299  6898  6981 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-06 18:57:26.299  6898  6981 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@37325ad0
,09-06 18:57:26.299  6898  6981 D BluetoothSocket: channel: 12
,09-06 18:57:26.299  6898  6981 I BtOppRfcommListener: Accept thread started.
,09-06 18:57:26.309  1014  1525 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-06 18:57:26.309  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:26.309  1014  1525 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:26.309  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-06 18:57:26.319  1932  6979 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-06 18:57:26.469   291   291 E SMD     : DCD OFF
,09-06 18:57:26.569  1014  1041 D Tethering: interfaceAdded wlan0
,09-06 18:57:26.569  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 18:57:26.569  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:26.569  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-06 18:57:26.579  1014  1127 E Tethering: No numeric data,
09-06 18:57:26.579  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
09-06 18:57:26.579  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-06 18:57:26.579  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED,
09-06 18:57:26.579  1014  1127 D Tethering: clearTetheredNotification()
09-06 18:57:26.579  1174  1174 D HotspotTile: updateTetherState():false, false
,09-06 18:57:26.579  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:26.579  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 18:57:26.579  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 18:57:26.579  1014  1121 V NetworkStats: performPollLocked() took 6ms
,09-06 18:57:26.579  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:26.589  1014  1127 D Tethering: InitialState.processMessage what=4
,09-06 18:57:26.589  1014  1127 E Tethering: No numeric data
,09-06 18:57:26.589  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:26.589  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:26.589  1014  1127 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0,
09-06 18:57:26.589  1014  1127 D Tethering: clearTetheredNotification()
,09-06 18:57:26.589  1014  1041 D Tethering: interfaceAdded p2p0
,09-06 18:57:26.599  1014  1041 D Tethering: p2p0 is not a tetherable iface, ignoring
,09-06 18:57:26.599  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-06 18:57:26.599  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 18:57:26.599  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-06 18:57:26.599  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-06 18:57:26.599  1174  1174 D HotspotTile: updateTetherState():false, false
,09-06 18:57:26.599  1014  1121 V NetworkStats: performPollLocked(flags=0x1),
09-06 18:57:26.599  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
,09-06 18:57:26.609  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 18:57:26.609   281  1000 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-06 18:57:26.609   281  1000 D SoftapController: Softap fwReload - Ok
,09-06 18:57:26.619  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 18:57:26.619   281  1000 D CommandListener: Setting iface cfg,
09-06 18:57:26.619   281  1000 D CommandListener: Trying to bring down wlan0
09-06 18:57:26.619   281  1000 D CommandListener: Clearing all IP addresses on wlan0
,09-06 18:57:26.619  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:26.619  1014  1121 V NetworkStats: performPollLocked() took 19ms
,09-06 18:57:26.629  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 18:57:26.629  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:26.629  1014  1124 E WifiHW  : supplicant_name : p2p_supplicant
,09-06 18:57:26.629  1014  1124 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,09-06 18:57:26.639  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:26.639  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:26.639  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-06 18:57:26.639  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:26.639  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:26.639  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:26.639  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:26.639  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:26.639  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:26.639  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-06 18:57:26.639  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:26.639  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 18:57:26.639  1174  1174 D HotspotTile: onReceive : 2, 0
,09-06 18:57:26.649  1014  1027 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:26.649  1014  1027 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 18:57:26.649  1014  1027 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:26.649  1014  1027 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:26.649  1014  1027 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:26.649  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 18:57:26.649  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 18:57:26.649  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 18:57:26.649  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 18:57:26.659  3691  3691 I Hs20UtilService: Starting #19
,09-06 18:57:26.659  3691  3726 I Hs20UtilService: Message received 5011
,09-06 18:57:26.679  6991  6991 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,09-06 18:57:26.679  6991  6991 I wpa_supplicant: Successfully initialized wpa_supplicant
09-06 18:57:26.679  6991  6991 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-06 18:57:26.689  6991  6991 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-06 18:57:26.699   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6991
09-06 18:57:26.699   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-06 18:57:26.699  6991  6991 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running,
09-06 18:57:26.699  6991  6991 I wpa_supplicant: ssSupport state is = 1
09-06 18:57:26.699  6991  6991 I wpa_supplicant: >>>>> GET KEY, IV <<<<<,
09-06 18:57:26.699  6991  6991 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-06 18:57:26.699   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6991,
09-06 18:57:26.699   401   401 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-06 18:57:26.759  1014  1817 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
09-06 18:57:26.769  1014  1817 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4275, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-06 18:57:26.769  1014  1817 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-06 18:57:26.769  1014  1817 D BatteryService: stay LED for charging
09-06 18:57:26.769  1014  1014 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-06 18:57:26.769  1014  1014 I MotionRecognitionService: Plugged
,09-06 18:57:26.769  1014  1014 I MotionRecognitionService: mGripSensorEnabled= false
,09-06 18:57:26.769  1174  1174 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-06 18:57:26.769  1174  1174 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-06 18:57:26.769  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-06 18:57:26.779  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,09-06 18:57:26.789  6898  6898 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-06 18:57:26.789  6898  6928 D HeadsetStateMachine: Disconnected process message: 10
,09-06 18:57:26.799  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:57:26.799  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:57:26.799  1174  1174 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,09-06 18:57:26.869   401   401 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0,
,09-06 18:57:26.879  6991  6991 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,09-06 18:57:26.939  6991  6991 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-06 18:57:26.939  6991  6991 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-06 18:57:26.949  6991  6991 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
,09-06 18:57:26.949   401   401 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6991
09-06 18:57:26.949   401   401 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-06 18:57:26.949  6991  6991 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-06 18:57:26.949  6991  6991 I wpa_supplicant: ssSupport state is = 1
09-06 18:57:26.949  6991  6991 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 18:57:26.949  6991  6991 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 18:57:26.949  6991  6991 E wpa_supplicant: SIM READ ERROR,
09-06 18:57:26.949  6991  6991 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-06 18:57:26.949  6991  6991 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 18:57:26.949  6991  6991 E wpa_supplicant: SIM READ ERROR
,09-06 18:57:26.949  6991  6991 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 18:57:26.959  6991  6991 I wpa_supplicant: wpa_default_ap_write_once,
09-06 18:57:26.959  6991  6991 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,09-06 18:57:26.959  6991  6991 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 18:57:26.959  6991  6991 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-06 18:57:26.959  6991  6991 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 18:57:26.959  6991  6991 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-06 18:57:26.959  6991  6991 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-06 18:57:26.959  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
09-06 18:57:26.959  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 18:57:26.959  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-06 18:57:27.019  6991  6991 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec,
,09-06 18:57:27.179  6991  6991 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-06 18:57:27.179  6991  6991 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,09-06 18:57:27.189  6991  6991 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-06 18:57:27.189   401   401 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6991
09-06 18:57:27.189   401   401 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-06 18:57:27.199  6991  6991 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-06 18:57:27.199  6991  6991 I wpa_supplicant: ssSupport state is = 1
09-06 18:57:27.199  6991  6991 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-06 18:57:27.199  6991  6991 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-06 18:57:27.209  6991  6991 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage
09-06 18:57:27.209   401   401 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 6991
09-06 18:57:27.209   401   401 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-06 18:57:27.209  6991  6991 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-06 18:57:27.209  6991  6991 I wpa_supplicant: ssSupport state is = 1
09-06 18:57:27.209  6991  6991 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 18:57:27.209  6991  6991 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 18:57:27.209  6991  6991 E wpa_supplicant: SIM READ ERROR
09-06 18:57:27.209  6991  6991 I wpa_supplicant: wpa_default_ap_write_once
09-06 18:57:27.209  6991  6991 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-06 18:57:27.209  6991  6991 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,09-06 18:57:27.209  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false
09-06 18:57:27.209  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 18:57:27.209  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-06 18:57:27.219  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
09-06 18:57:27.219  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-06 18:57:27.219  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-06 18:57:27.259  6991  6991 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
,09-06 18:57:27.259  6991  6991 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-06 18:57:27.319  6991  6991 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-06 18:57:27.319  6991  6991 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=,
09-06 18:57:27.319  6991  6991 I wpa_supplicant: Skip scan - bUseNetwork false,
,09-06 18:57:27.329  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,09-06 18:57:27.329  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [21]
09-06 18:57:27.329  6991  6991 I wpa_supplicant: HOTSPOT20_ENABLE called,
09-06 18:57:27.329  6991  6991 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-06 18:57:27.329  6991  6991 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-06 18:57:27.329  6991  6991 E wpa_supplicant: SIM READ ERROR,
09-06 18:57:27.329  6991  6991 I wpa_supplicant: Blacklist: Clear (all) 
,09-06 18:57:27.339  6991  6991 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-06 18:57:27.359  1014  1124 D WifiNative-wlan0: callSECApiInt - ID [210]
09-06 18:57:27.359  6991  6991 I wpa_supplicant: Skip scan - bUseNetwork false
,09-06 18:57:27.359  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 18:57:27.359  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:27.359  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:27.359  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:27.359  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:27.359  1174  1731 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-06 18:57:27.359  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:27.369  1174  1174 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:27.359  1174  1174 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-06 18:57:27.369  1174  1174 D HotspotTile: onReceive : 3, 0
,09-06 18:57:27.359  1174  1174 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-06 18:57:27.369  1014  1124 D WifiConfigStore: Loading config and enabling all networks 
09-06 18:57:27.369  1308  1308 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-06 18:57:27.369  1014  1525 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:27.369  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:27.379  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:27.379  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:27.379  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:27.379  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:27.379  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:27.379  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:27.379  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:27.379  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:27.379  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:27.379  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:27.379  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-06 18:57:27.379  1014  1124 E WifiConfigStore: Not a HS20
09-06 18:57:27.379  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:27.379  1014  1124 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-06 18:57:27.389  1014  1124 D WifiNative-wlan0: callSECApiInt - ID [65]
,09-06 18:57:27.389  3691  3691 I Hs20UtilService: Starting #20
,09-06 18:57:27.389  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-06 18:57:27.389  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-06 18:57:27.389  1014  1124 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-06 18:57:27.389  6991  6991 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-06 18:57:27.389  6991  6991 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-06 18:57:27.389  6991  6991 I wpa_supplicant: reset timer : RESET_TIMER 0
09-06 18:57:27.389  6991  6991 I wpa_supplicant: P2P: Current p2p state = IDLE
09-06 18:57:27.389  6991  6991 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-06 18:57:27.389  6991  6991 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-06 18:57:27.389  6991  6991 I wpa_supplicant: First Scan Start
,09-06 18:57:27.389  6991  6991 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-06 18:57:27.389  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
09-06 18:57:27.389  3691  3726 I Hs20UtilService: Message received 5011
09-06 18:57:27.389  1014  1124 D WifiNative-wlan0: Setting external_sim to 1
09-06 18:57:27.389  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-06 18:57:27.389  1014  1124 D WifiStateMachine: Setting OUI to DA-A1-19
09-06 18:57:27.389  1014  1124 I WifiNative-HAL: startHal
09-06 18:57:27.389  1014  1124 E wifi    : getStaticLongField sWifiHalHandle 0x9c78d88c
09-06 18:57:27.389  1014  1124 I WifiNative-HAL: Could not start hal
09-06 18:57:27.389  6473  6473 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-06 18:57:27.399  1014  1124 E WifiNative-wlan0: do suspend true
09-06 18:57:27.399  1014  1123 D WifiP2pService: P2pDisabledState{ what=131203 }
09-06 18:57:27.399  1014  1124 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-06 18:57:27.399  1014  1123 D WifiP2pService: P2pEnablingState
09-06 18:57:27.399   281  1000 D CommandListener: Setting iface cfg
09-06 18:57:27.399   281  1000 D CommandListener: Trying to bring up p2p0
09-06 18:57:27.399  1014  1123 D WifiP2pService: P2pEnablingState{ what=147457 }
09-06 18:57:27.399  1014  1123 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-06 18:57:27.399  1014  1014 D WifiScanningService: SCAN_AVAILABLE : 3
09-06 18:57:27.399  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 18:57:27.399  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 18:57:27.399  1014  1124 E WifiNative-wlan0: invaild command id : 215
09-06 18:57:27.399  1014  1146 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:27.399  1014  1146 I WifiNative-HAL: startHal
09-06 18:57:27.399  1014  1014 D RttService: SCAN_AVAILABLE : 3
09-06 18:57:27.399  1014  1146 E wifi    : getStaticLongField sWifiHalHandle 0x9da3d9bc
09-06 18:57:27.399  1014  1146 I WifiNative-HAL: Could not start hal
09-06 18:57:27.409  1014  1123 D WifiP2pService: P2p socket connection successful
09-06 18:57:27.399  1014  1146 E WifiScanningService: could not start HAL
09-06 18:57:27.409  1014  1124 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-06 18:57:27.409  1014  1124 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-06 18:57:27.409  1014  1124 E WifiNative-wlan0: invaild command id : 215
09-06 18:57:27.409  1014  1147 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:27.409  1014  1123 D WifiP2pService: P2pEnabledState
09-06 18:57:27.409  1014  1126 E ConnectivityService: updateNetworkInfo()
09-06 18:57:27.409  1014  1123 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-06 18:57:27.409  6991  6991 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 18:57:27.409  6991  6991 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-06 18:57:27.409  1014  1014 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-06 18:57:27.409  1014  1044 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-06 18:57:27.409  6991  6991 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-06 18:57:27.409  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 18:57:27.409  1014  1044 D WifiDisplayController: disconnect
09-06 18:57:27.409  1014  1044 D WifiDisplayController: updateConnection
09-06 18:57:27.409  1014  1044 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-06 18:57:27.409  1014  1044 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 18:57:27.419  1014  1044 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-06 18:57:27.419  1014  1044 D WifiDisplayAdapter: onP2pDisconnected
09-06 18:57:27.419  1014  1044 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-06 18:57:27.419  1014  1044 D IpRemoteDisplayController: WfdBridgeServer is already null
09-06 18:57:27.419  1174  1174 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-06 18:57:27.419  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:27.419  1014  1491 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-06 18:57:27.419  1014  1124 D SecContentProvider2: mCursor = null
09-06 18:57:27.419  1174  1174 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-06 18:57:27.419  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress
09-06 18:57:27.419  1014  1123 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-06 18:57:27.419  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-06 18:57:27.419  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 18:57:27.419  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-06 18:57:27.419  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:27.419  1014  1124 D SecContentProvider2: mCursor = null
09-06 18:57:27.429  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 18:57:27.429  1014  1123 D WifiP2pService: DeviceAddress: 7e:96:ac
09-06 18:57:27.429  1014  1044 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  primary type: 10-0050F204-5
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  secondary type: null
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  wps: 0
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  grpcapab: 0
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  devcapab: 0
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  status: 3
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  wfdInfo: null
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  groupownerAddress: null
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  GOdeviceName: null
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  interfaceAddress: 
09-06 18:57:27.429  1014  1044 D WifiDisplayController:  SConnectInfo : null
09-06 18:57:27.429  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 18:57:27.429  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-06 18:57:27.429  1308  3059 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-06 18:57:27.429  6438  6438 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-06 18:57:27.429  6438  6438 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-06 18:57:27.429  6438  6438 D FileShare-Client: Outbound.stopDelayTimer - 
,09-06 18:57:27.439  6458  6458 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-06 18:57:27.449  1014  1123 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-06 18:57:27.449  1014  1123 D WifiP2pService: InactiveState
09-06 18:57:27.449  1014  1123 D WifiP2pService: InactiveState{ what=143376 }
,09-06 18:57:27.449  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-06 18:57:27.449  6991  6991 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL,
,09-06 18:57:27.449  1014  1123 D WifiP2pService: InactiveState{ what=143376 }
09-06 18:57:27.449  1014  1123 D WifiP2pService: P2pEnabledState{ what=143376 },
,09-06 18:57:27.569  1014  1041 D Tethering: interfaceLinkStateChanged p2p0, false,
09-06 18:57:27.569  1014  1041 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-06 18:57:27.569  1014  1041 D Tethering: interfaceStatusChanged p2p0, false
,09-06 18:57:28.219  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:28.219  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:28.219  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:28.219  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:28.219  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:28.219  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:28.219  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:28.219  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:28.219  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:28.229  1014  2724 D SSRM:n  : SIOP:: AP = 310
,09-06 18:57:28.229  6219  6271 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-06 18:57:28.229  6219  6271 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-06 18:57:28.229  6219  6271 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2e58bc1f Bundle[{}]
,09-06 18:57:28.229  6219  6271 I io.jxcore.node.LifeCycleMonitor: start: OK,
09-06 18:57:28.229  6219  6271 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-06 18:57:28.229  6219  6271 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-06 18:57:28.229  6219  6271 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-06 18:57:28.239  6219  6271 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed,
09-06 18:57:28.239  6219  6271 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-06 18:57:28.239  6219  6271 I System.out: Running OutgoingSocketThread
,09-06 18:57:28.239  6219  6999 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1172),
,09-06 18:57:28.249  6219  6999 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 50322,
09-06 18:57:28.249  6219  6999 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...,
,09-06 18:57:28.579  6991  6991 I wpa_supplicant: nl80211: Received scan results (18 BSSes),
09-06 18:57:28.579  6991  6991 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-06 18:57:28.579  6991  6991 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-06 18:57:28.579  6991  6991 I wpa_supplicant: Trying to associate with  'G700'
,09-06 18:57:28.579  6991  6991 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-06 18:57:28.579  6991  6991 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-06 18:57:28.579  1014  6997 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-06 18:57:28.599  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:28.599  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:28.689  6991  6991 E wpa_supplicant: Cmd 35605 not handled
,09-06 18:57:28.689  6991  6991 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 18:57:28.689  6991  6991 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-06 18:57:28.689  6991  6991 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,09-06 18:57:28.689  6991  6991 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-06 18:57:28.689  6991  6991 I wpa_supplicant: Associated with F4.99.3E
09-06 18:57:28.689  6991  6991 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-06 18:57:28.689  6991  6991 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-06 18:57:28.689  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-06 18:57:28.689  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 18:57:28.689  6991  6991 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-06 18:57:28.689  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-06 18:57:28.699  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 18:57:28.699  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false
,09-06 18:57:28.699  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
,09-06 18:57:28.699  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-06 18:57:28.699  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, false,
09-06 18:57:28.699  1014  1041 D Tethering: interfaceStatusChanged wlan0, false
09-06 18:57:28.699  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 18:57:28.699  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
09-06 18:57:28.699  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
09-06 18:57:28.699  1014  1127 E Tethering: No numeric data
09-06 18:57:28.699  1014  1127 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-06 18:57:28.699  1014  1127 D Tethering: clearTetheredNotification()
,09-06 18:57:28.709  6991  6991 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-06 18:57:28.709  6991  6991 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
09-06 18:57:28.709  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 18:57:28.709  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-06 18:57:28.709  6991  6991 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-06 18:57:28.709  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-06 18:57:28.709  6991  6991 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-06 18:57:28.709  1174  1174 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-06 18:57:28.709  1174  1174 D HotspotTile: updateTetherState():false, false
,09-06 18:57:28.709  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 18:57:28.709  6991  6991 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-06 18:57:28.719  6991  6991 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
,09-06 18:57:28.719  6991  6991 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
,09-06 18:57:28.719  6991  6991 I wpa_supplicant: Blacklist: Clear (temp) ,
09-06 18:57:28.719  6991  6991 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
,09-06 18:57:28.719  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:28.719  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:28.719  1014  1041 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-06 18:57:28.719  1014  1041 D Tethering: interfaceLinkStateChanged wlan0, true
,09-06 18:57:28.719  1014  1041 D Tethering: interfaceStatusChanged wlan0, true
,09-06 18:57:28.719  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:28.719  1014  1121 V NetworkStats: performPollLocked() took 15ms
,09-06 18:57:28.729  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-06 18:57:28.729  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:28.729  1014  1124 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-06 18:57:28.739  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 18:57:28.739  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 18:57:28.739  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:28.749  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:28.749  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:28.749  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:28.749  1014  1124 E WifiConfigStore: setLastSelectedConfiguration -1
,09-06 18:57:28.749  1014  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-06 18:57:28.749  1014  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:28.749  1014  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:28.749  1014  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
,09-06 18:57:28.749  1014  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:28.749  3691  3691 I Hs20UtilService: Starting #21
,09-06 18:57:28.759  3691  3726 I Hs20UtilService: Message received 5007
,09-06 18:57:28.759  1014  1124 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-06 18:57:28.759  1014  1126 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,09-06 18:57:28.759  1014  1126 E ConnectivityService: updateNetworkInfo()
,09-06 18:57:28.759  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-06 18:57:28.759  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 18:57:28.759  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
09-06 18:57:28.759  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-06 18:57:28.769  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-06 18:57:28.769  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-06 18:57:28.769  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-06 18:57:28.769  1308  1308 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-06 18:57:28.769  1308  3059 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-06 18:57:28.779  1014  1124 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-06 18:57:28.789   281  1000 D CommandListener: Setting iface cfg,
09-06 18:57:28.789  1014  1124 E WifiStateMachine: Start Dhcp Watchdog 3
,09-06 18:57:28.789  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-06 18:57:28.789  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:28.799  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 18:57:28.799  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:28.799  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 18:57:28.799  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-06 18:57:28.809  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:28.809  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:28.809  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:28.809  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:28.809  1014  1124 E WifiNative-wlan0: do suspend false
,09-06 18:57:28.809  1014  1123 D WifiP2pService: InactiveState{ what=143375 },
09-06 18:57:28.809  1014  1124 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-06 18:57:28.809  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 },
09-06 18:57:28.809  1014  1124 D SecContentProvider2: mCursor = null
,09-06 18:57:29.029  7002  7002 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-06 18:57:29.029  7002  7002 I dhcpcd  : version 5.5.6 starting
,09-06 18:57:29.039  7002  7002 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-06 18:57:29.099  7002  7002 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-06 18:57:29.099  7002  7002 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,09-06 18:57:29.099  7002  7002 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-06 18:57:29.099  7002  7002 I dhcpcd  : bssid match
09-06 18:57:29.099  7002  7002 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111,
,09-06 18:57:29.159  7002  7002 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1,
,09-06 18:57:29.219  7002  7002 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-06 18:57:29.239  6219  6271 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1173),
09-06 18:57:29.239  6219  6271 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1173)
,09-06 18:57:29.249  6219  6271 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1178),
09-06 18:57:29.249  6219  6271 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-06 18:57:29.249  6219  6271 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1179)
,09-06 18:57:29.249  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
09-06 18:57:29.249  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d78c0b8 added. We now have 2 listener(s)
,09-06 18:57:29.249  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
,09-06 18:57:29.249  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:29.249  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-06 18:57:29.249  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-06 18:57:29.249  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d724e91 added. We now have 9 listener(s)
,09-06 18:57:29.249  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:29.259  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:57:29.269  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:29.269  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:,
09-06 18:57:29.269  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:29.269  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:29.269  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:29.269  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:29.269  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:29.269  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:29.269  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:29.269  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:29.269  6219  6271 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:57:29.269  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded,
,09-06 18:57:29.269  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c389f7 added. We now have 3 listener(s)
09-06 18:57:29.269  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:29.279  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-06 18:57:29.279  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
09-06 18:57:29.279  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:29.279  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:29.279  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:29.279  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7553064 added. We now have 10 listener(s),
09-06 18:57:29.279  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:29.279  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-06 18:57:29.279  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:29.279  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:29.279  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.279  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:29.279  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d78c0b8 removed from the list
,09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.279  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d724e91 removed from the list
09-06 18:57:29.279  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:29.279  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.279  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.279  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.279  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d724e91 not in the list,
09-06 18:57:29.279  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.279  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.279  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7553064 removed from the list
09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:29.279  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-06 18:57:29.279  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.279  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:29.279  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4c389f7 removed from the list
09-06 18:57:29.279  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 18:57:29.279  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@255c42cd added. We now have 2 listener(s)
09-06 18:57:29.289  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-06 18:57:29.289  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:29.289  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:29.289  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:29.289  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c311782 added. We now have 9 listener(s)
09-06 18:57:29.289  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:29.289  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:57:29.289  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:29.289  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:29.289  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:29.289  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:29.289  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:29.289  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:29.289  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:29.289  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:29.289  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:29.299  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:29.299  6219  6271 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:57:29.299  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:29.299  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3066eed0 added. We now have 3 listener(s)
,09-06 18:57:29.299  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:29.299  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
,09-06 18:57:29.299  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-06 18:57:29.299  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:29.299  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:29.299  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:29.299  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d773ec9 added. We now have 10 listener(s)
09-06 18:57:29.299  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:29.299  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:29.299  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-06 18:57:29.299  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false,
09-06 18:57:29.299  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:29.299  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 18:57:29.309  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-06 18:57:29.309  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 18:57:29.319  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-06 18:57:29.319  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-06 18:57:29.319  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 18:57:29.319  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 18:57:29.319  6898  6909 D BtGatt.GattService: registerClient() - UUID=4c70729e-9913-4657-9e0a-2d15af9e1713,
,09-06 18:57:29.359  6898  6923 D BtGatt.GattService: onClientRegistered() - UUID=4c70729e-9913-4657-9e0a-2d15af9e1713, clientIf=6
09-06 18:57:29.359  6219  6229 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-06 18:57:29.359  6898  6906 D BtGatt.GattService: start scan with filters
09-06 18:57:29.369  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 18:57:29.369  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 18:57:29.369  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 18:57:29.369  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 18:57:29.369  6898  6927 D BtGatt.ScanManager: handling starting scan
09-06 18:57:29.369  6898  6927 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3b3e40c5
09-06 18:57:29.369  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 18:57:29.369  6898  6923 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 18:57:29.369  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.369  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
09-06 18:57:29.369  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 18:57:29.369  6898  6927 D BtGatt.ScanManager: allow scan with filters,
09-06 18:57:29.369  6898  6927 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 18:57:29.369  6898  6927 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-06 18:57:29.369  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-06 18:57:29.379  6898  6923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 18:57:29.379  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.379  6898  6927 D BtGatt.ScanManager: Starting BLE batch scan
09-06 18:57:29.379  6898  6927 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-06 18:57:29.379  6219  6271 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-06 18:57:29.379  6898  6923 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 18:57:29.379  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.379  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:29.379  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-06 18:57:29.379  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.379  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 18:57:29.379  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-06 18:57:29.379  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:29.379  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:29.379  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:29.379  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 18:57:29.379  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-06 18:57:29.379  6898  6967 D BtGatt.GattService: stopScan() - queue size =1
09-06 18:57:29.379  6898  6923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 18:57:29.379  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.379  6898  6966 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 18:57:29.389  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:57:29.389  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 18:57:29.389  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 18:57:29.389  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 18:57:29.389  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-06 18:57:29.389  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:29.389  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 18:57:29.389  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 18:57:29.389  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 18:57:29.389  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:29.399  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:29.399  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:29.399  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:29.399  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:29.409  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:29.409  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:29.409  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.409  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...,
09-06 18:57:29.409  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@255c42cd removed from the list
09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.409  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c311782 removed from the list
09-06 18:57:29.409  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:29.409  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.409  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.409  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.409  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c311782 not in the list
09-06 18:57:29.409  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.409  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.409  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d773ec9 removed from the list
09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:29.409  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.409  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.409  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:29.409  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3066eed0 removed from the list
09-06 18:57:29.409  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:29.409  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a2bfe85 added. We now have 2 listener(s)
,09-06 18:57:29.419  6898  6927 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 9,
,09-06 18:57:29.419  6898  6927 D BtGatt.ScanManager: filter size is 1,
09-06 18:57:29.419  6898  6927 D BtGatt.ScanManager: delete FilterIndex - 3
09-06 18:57:29.419  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-06 18:57:29.419  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:29.419  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:29.419  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:29.419  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c2614da added. We now have 9 listener(s)
09-06 18:57:29.419  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:29.419  6898  6923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 18:57:29.419  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.419  6898  6927 D BtGatt.ScanManager: stopping BLe Batch
09-06 18:57:29.419  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:57:29.429  6898  6923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 18:57:29.429  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:29.429  6898  6927 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 18:57:29.429  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:29.429  6898  6923 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 18:57:29.429  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:29.429  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:29.429  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:29.429  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-06 18:57:29.429  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:29.429  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:29.429  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:29.429  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:29.429  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:29.439  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-06 18:57:29.439  6219  6271 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:57:29.439  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:29.439  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df9c7e8 added. We now have 3 listener(s)
,09-06 18:57:29.439  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:29.439  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
09-06 18:57:29.439  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:29.439  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:29.439  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:29.439  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b2fe01 added. We now have 10 listener(s)
09-06 18:57:29.439  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:29.439  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:29.439  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:29.439  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:57:29.439  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:57:29.439  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:29.439  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-06 18:57:29.439  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:29.449  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 18:57:29.459  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-06 18:57:29.459  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:57:29.469  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...,
09-06 18:57:29.469  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-06 18:57:29.469  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 18:57:29.469  6898  6906 D BtGatt.GattService: registerClient() - UUID=51b13bde-38ed-4d65-a197-7aee74d198de,
,09-06 18:57:29.479   291   291 E SMD     : DCD OFF
,09-06 18:57:29.509  6898  6923 D BtGatt.GattService: onClientRegistered() - UUID=51b13bde-38ed-4d65-a197-7aee74d198de, clientIf=6,
09-06 18:57:29.509  6219  6229 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 18:57:29.509  6898  6929 D BtGatt.GattService: start scan with filters
09-06 18:57:29.509  6898  6927 D BtGatt.ScanManager: handling starting scan
09-06 18:57:29.509  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 18:57:29.509  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true,
09-06 18:57:29.509  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 18:57:29.509  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-06 18:57:29.509  6898  6923 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
09-06 18:57:29.509  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.509  6898  6927 D BtGatt.ScanManager: allow scan with filters
09-06 18:57:29.509  6898  6927 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-06 18:57:29.509  6898  6927 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-06 18:57:29.519  6898  6923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-06 18:57:29.519  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.519  6898  6927 D BtGatt.ScanManager: Starting BLE batch scan
09-06 18:57:29.519  6898  6927 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 18:57:29.519  6898  6923 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-06 18:57:29.519  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.519  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-06 18:57:29.519  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 18:57:29.519  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:29.519  6898  6923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1,
09-06 18:57:29.519  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:29.529  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 18:57:29.539  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only,
,09-06 18:57:29.539  6219  6271 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-06 18:57:29.539  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:29.539  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:29.539  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-06 18:57:29.539  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:29.539  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.539  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 18:57:29.539  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:29.539  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a2bfe85 removed from the list
,09-06 18:57:29.539  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.539  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c2614da removed from the list
,09-06 18:57:29.539  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
,09-06 18:57:29.539  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:29.539  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed,
09-06 18:57:29.539  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left,
09-06 18:57:29.539  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.539  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:29.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:29.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:29.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.549  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c2614da not in the list
09-06 18:57:29.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:29.549  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:29.549  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:29.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 18:57:29.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 18:57:29.549  6898  6909 D BtGatt.GattService: stopScan() - queue size =1
,09-06 18:57:29.549  6898  6906 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 18:57:29.549  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:57:29.549  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 18:57:29.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 18:57:29.549  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 18:57:29.549  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 18:57:29.549  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:29.559  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-06 18:57:29.559  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-06 18:57:29.559  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 18:57:29.559  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:29.559  6898  6927 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 10
,09-06 18:57:29.559  6898  6927 D BtGatt.ScanManager: filter size is 1
,09-06 18:57:29.559  6898  6927 D BtGatt.ScanManager: delete FilterIndex - 4
,09-06 18:57:29.569  6898  6923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-06 18:57:29.569  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.569  6898  6927 D BtGatt.ScanManager: stopping BLe Batch
09-06 18:57:29.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:29.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:29.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.569  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13b2fe01 removed from the list
09-06 18:57:29.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:29.569  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.569  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:29.569  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df9c7e8 removed from the list
,09-06 18:57:29.569  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:29.569  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:29.569  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1350793d added. We now have 2 listener(s)
,09-06 18:57:29.569  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:29.569  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:29.569  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 18:57:29.569  6898  6923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-06 18:57:29.569  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:29.569  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:29.569  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:29.569  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:29.569  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@626532 added. We now have 9 listener(s)
09-06 18:57:29.569  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:29.569  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:57:29.569  6898  6927 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 18:57:29.579  6898  6923 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-06 18:57:29.579  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:29.579  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:29.579  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:29.579  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:29.579  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:29.579  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:29.579  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:29.579  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-06 18:57:29.579  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-06 18:57:29.579  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-06 18:57:29.589  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-06 18:57:29.589  6219  6271 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-06 18:57:29.589  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:29.589  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:29.589  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 18:57:29.589  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1abbac00 added. We now have 3 listener(s)
,09-06 18:57:29.589  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 18:57:29.589  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-06 18:57:29.599  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:29.599  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:29.599  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18506c39 added. We now have 10 listener(s)
09-06 18:57:29.599  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:29.599  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:29.599  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-06 18:57:29.599  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-06 18:57:29.599  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-06 18:57:29.599  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-06 18:57:29.599  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-06 18:57:29.599  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-06 18:57:29.609  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-06 18:57:29.609  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-06 18:57:29.609  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-06 18:57:29.609  6219  6271 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-06 18:57:29.609  6898  6929 D BtGatt.GattService: registerClient() - UUID=ab80b104-9e56-416a-8d8e-86497faac220
,09-06 18:57:29.619  1014  1124 E WifiNative-wlan0: do suspend true
,09-06 18:57:29.649  1014  1123 D WifiP2pService: InactiveState{ what=143375 }
,09-06 18:57:29.649  1014  1123 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-06 18:57:29.649  6898  6923 D BtGatt.GattService: onClientRegistered() - UUID=ab80b104-9e56-416a-8d8e-86497faac220, clientIf=6
,09-06 18:57:29.649  6219  6227 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-06 18:57:29.649  6898  6967 D BtGatt.GattService: start scan with filters
,09-06 18:57:29.659  6898  6927 D BtGatt.ScanManager: handling starting scan
09-06 18:57:29.659  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-06 18:57:29.659  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-06 18:57:29.659  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-06 18:57:29.659  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-06 18:57:29.659  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 18:57:29.659  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:29.659  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.659  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.659  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.659  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.659  1014  1124 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-06 18:57:29.659  1014  1124 E WifiStateMachine: VerifyingLinkState enter
,09-06 18:57:29.659  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:29.659  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-06 18:57:29.659  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-06 18:57:29.659  1014  1124 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-06 18:57:29.669  6898  6923 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
09-06 18:57:29.669  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.669  6898  6927 D BtGatt.ScanManager: allow scan with filters
,09-06 18:57:29.669  6898  6927 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-06 18:57:29.669  1014  1126 E ConnectivityService: updateNetworkInfo()
,09-06 18:57:29.669  6898  6927 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-06 18:57:29.669  1014  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
09-06 18:57:29.669  1014  1126 D ConnectivityService: Adding iface wlan0 to network 504
,09-06 18:57:29.669  6898  6923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-06 18:57:29.669  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.669  6898  6927 D BtGatt.ScanManager: Starting BLE batch scan
,09-06 18:57:29.669  6898  6927 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-06 18:57:29.669  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-06 18:57:29.679  1014  1140 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,09-06 18:57:29.679  1014  1140 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 18:57:29.679  1014  1140 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-06 18:57:29.679  1014  1140 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 18:57:29.679  1014  1140 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-06 18:57:29.679  6898  6923 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-06 18:57:29.679  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.679  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:29.679  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:29.679  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.679  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.679  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.679  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:29.689  6898  6923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-06 18:57:29.689  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-06 18:57:29.699  1014  1124 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
09-06 18:57:29.699  1014  1126 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-06 18:57:29.699  1014  1126 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-06 18:57:29.699  1014  1525 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 18:57:29.699  1014  1126 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
,09-06 18:57:29.699  1014  1525 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 18:57:29.699  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:29.699  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:29.699  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:29.699  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:29.699  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.699  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-06 18:57:29.699  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:29.699  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1350793d removed from the list
09-06 18:57:29.699  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.699  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@626532 removed from the list
09-06 18:57:29.699  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:29.699  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:29.699  1014  1525 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:29.699  1014  1126 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-06 18:57:29.699  1014  1525 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:29.699  1014  1126 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
09-06 18:57:29.699  1014  1525 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-06 18:57:29.699  1014  1126 D ConnectivityService: LTETest block dns file not exists
,09-06 18:57:29.709  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-06 18:57:29.709  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-06 18:57:29.709  3691  3691 I Hs20UtilService: Starting #22
,09-06 18:57:29.709  1014  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-06 18:57:29.709  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:29.709  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:29.709  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.709  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@626532 not in the list
09-06 18:57:29.709  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-06 18:57:29.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-06 18:57:29.709  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-06 18:57:29.709  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-06 18:57:29.709  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-06 18:57:29.709  6898  6909 D BtGatt.GattService: stopScan() - queue size =1
09-06 18:57:29.719  6898  6906 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-06 18:57:29.719  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-06 18:57:29.719  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-06 18:57:29.719  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-06 18:57:29.719  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-06 18:57:29.719  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-06 18:57:29.719  3691  3726 I Hs20UtilService: Message received 5007
,09-06 18:57:29.719  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-06 18:57:29.719  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-06 18:57:29.719  1014  1126 E ConnectivityService: updateNetworkInfo()
09-06 18:57:29.719  6219  6271 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-06 18:57:29.719  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-06 18:57:29.719  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 18:57:29.719  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-06 18:57:29.719  1014  1126 E ConnectivityService: updateNetworkInfo()
09-06 18:57:29.719  1014  1126 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-06 18:57:29.719  1014  1126 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-06 18:57:29.719  1014  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-06 18:57:29.729  1014  7000 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:29.729  1014  7000 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-06 18:57:29.729  1014  7000 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-06 18:57:29.729  1014  7000 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
,09-06 18:57:29.729  1014  7000 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-06 18:57:29.729  1014  1126 D ConnectivityService:    accepting network in place of null
,09-06 18:57:29.729  1308  1308 I NearbySettings: MountReceiver.onReceive - Keep current state
09-06 18:57:29.729  1014  1123 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-06 18:57:29.729  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 18:57:29.729  1452  1452 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-06 18:57:29.729  1014  1126 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-06 18:57:29.729  1014  1126 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
09-06 18:57:29.729   281   996 D EnterpriseController: uids 1000
09-06 18:57:29.729  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-06 18:57:29.729   281   996 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 18:57:29.729   281   996 D Netd    : getNetworkForDns: using netid 504 for uid 1000
09-06 18:57:29.729  1014  1124 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-06 18:57:29.729  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:29.729  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:29.729  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.729  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18506c39 removed from the list
,09-06 18:57:29.729  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:29.729  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.729  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.729  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:29.729  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1abbac00 removed from the list
,09-06 18:57:29.729  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:29.729  1014  1126 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
09-06 18:57:29.729  6219  6219 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-06 18:57:29.729  6219  6219 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-06 18:57:29.729  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-06 18:57:29.729  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20c292f5 added. We now have 2 listener(s)
09-06 18:57:29.729  6898  6927 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 11
09-06 18:57:29.729  1014  1124 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-06 18:57:29.729  6898  6927 D BtGatt.ScanManager: filter size is 1
09-06 18:57:29.729  6898  6927 D BtGatt.ScanManager: delete FilterIndex - 5
,09-06 18:57:29.729  1014  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-06 18:57:29.739  1014  1043 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-06 18:57:29.739  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-06 18:57:29.739  1174  1717 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 18:57:29.739  3778  6281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-06 18:57:29.739  6898  6923 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-06 18:57:29.739  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.739  6898  6927 D BtGatt.ScanManager: stopping BLe Batch
,09-06 18:57:29.739  1174  1174 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:29.739  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-06 18:57:29.739  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.739  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.739  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.739  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:29.739  6898  6923 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-06 18:57:29.739  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-06 18:57:29.739  6898  6927 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-06 18:57:29.749  1014  1014 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-06 18:57:29.749  1014  1014 I WifiTrafficPoller: mBoosterFLAG : 0
09-06 18:57:29.749  1014  1014 I WifiTrafficPoller: current booster mode : FullMode
09-06 18:57:29.749  1014  1014 D WifiNative-wlan0: callSECApiVoid - ID [212]
,09-06 18:57:29.749  6898  6923 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-06 18:57:29.749  6898  6923 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-06 18:57:29.749  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-06 18:57:29.749  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 18:57:29.749  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.749  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.749  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.749  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:29.749  1014  1014 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-06 18:57:29.749  1014  1127 D Tethering: MasterInitialState.processMessage what=3
,09-06 18:57:29.759  1014  1121 V NetworkStats: updateIfacesLocked()
09-06 18:57:29.759  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:29.759  1014  1121 V NetworkStats: performPollLocked(flags=0x1)
,09-06 18:57:29.759  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 18:57:29.759  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 18:57:29.759  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:29.759  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:29.759  1014  1121 V NetworkStats: performPollLocked() took 4ms
09-06 18:57:29.759  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:29.759  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:29.759  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:29.759  1014  1122 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,09-06 18:57:29.759  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-06 18:57:29.759  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:29.759  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:29.759  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:29.759  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a1d688a added. We now have 9 listener(s)
09-06 18:57:29.759  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-06 18:57:29.759  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-06 18:57:29.769  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-06 18:57:29.769  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:29.769  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:29.769  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
,09-06 18:57:29.769  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 18:57:29.769  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 18:57:29.769  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-06 18:57:29.769  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,09-06 18:57:29.769  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 18:57:29.769  6219  6271 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-06 18:57:29.769  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:29.769  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:29.769  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:29.769  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:29.769  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:29.769  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:29.769  6219  6271 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:29.779  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-06 18:57:29.779  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-06 18:57:29.779  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-06 18:57:29.779  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-06 18:57:29.779  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-06 18:57:29.779  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 18:57:29.779  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-06 18:57:29.779  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.779  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:29.779  6219  6271 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:29.779  6219  6271 D io.jxcore.node.ConnectivityMonitor: start: OK
09-06 18:57:29.779  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-06 18:57:29.779  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3622fb18 added. We now have 3 listener(s)
09-06 18:57:29.789  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:29.789  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-06 18:57:29.789  1014  1205 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 18:57:29.789  1014  1205 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-06 18:57:29.789  1014  1205 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:29.789  1014  1205 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:29.789  1014  1205 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:29.789  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-06 18:57:29.789  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-06 18:57:29.789  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-06 18:57:29.789  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-06 18:57:29.789  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f66971 added. We now have 10 listener(s)
09-06 18:57:29.789  6219  6271 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-06 18:57:29.789  6219  6271 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-06 18:57:29.789  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-06 18:57:29.789  6219  6271 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-06 18:57:29.789  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:29.789  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.789  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-06 18:57:29.789  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:29.789  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20c292f5 removed from the list
09-06 18:57:29.789  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.789  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a1d688a removed from the list
09-06 18:57:29.789  6219  6271 D io.jxcore.node.ConnectivityMonitor: stop
09-06 18:57:29.789  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.789  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-06 18:57:29.789  1308  1308 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-06 18:57:29.789  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.799  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.799  3691  3691 I Hs20UtilService: Starting #23
,09-06 18:57:29.799  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-06 18:57:29.799  3691  3726 I Hs20UtilService: Message received 5007
,09-06 18:57:29.799  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:29.799  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:29.799  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.799  6219  6271 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1a1d688a not in the list
09-06 18:57:29.799  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-06 18:57:29.799  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.799  1308  1308 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-06 18:57:29.799  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.799  1308  1308 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 18:57:29.799  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-06 18:57:29.799  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-06 18:57:29.799  6219  6271 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-06 18:57:29.799  6219  6271 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f66971 removed from the list
09-06 18:57:29.799  6219  6271 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-06 18:57:29.799  6219  6271 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-06 18:57:29.799  6219  6271 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-06 18:57:29.799  6219  6271 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-06 18:57:29.799  6219  6271 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3622fb18 removed from the list
,09-06 18:57:29.799  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-06 18:57:29.799  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-06 18:57:29.799  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-06 18:57:29.799  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-06 18:57:29.799  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-06 18:57:29.799  6219  6271 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-06 18:57:29.809  6219  7040 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1186, name: My test thread name)
,09-06 18:57:29.809  6219  7040 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1186, thread name: My test thread name)
,09-06 18:57:29.809  6219  7040 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1186, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
09-06 18:57:29.809  1014  1817 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-06 18:57:29.809  1014  1817 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-06 18:57:29.809  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:29.809  1014  1817 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:29.809  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-06 18:57:29.809  3691  3691 I Hs20UtilService: Starting #24
,09-06 18:57:29.809  3691  3726 I Hs20UtilService: Message received 5007
,09-06 18:57:29.809  1308  1308 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-06 18:57:29.809  1308  1308 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-06 18:57:29.809  6219  7041 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1188, name: My test thread name)
09-06 18:57:29.809  6219  7041 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1188, thread name: My test thread name)
09-06 18:57:29.809  6219  7041 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1188, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-06 18:57:29.819  6219  6271 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
09-06 18:57:29.819  6219  6271 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-06 18:57:29.819  6219  6271 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
09-06 18:57:29.819  6219  6271 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-06 18:57:29.819  6219  6271 D com.test.thalitest.ThaliTestRunner: Total duration: 23285 ms
,09-06 18:57:29.819  6219  6271 I jxcore-log: *Native tests were executed*
09-06 18:57:29.819  6219  6271 I jxcore-log: 
,09-06 18:57:29.819  6219  6271 I jxcore-log: Total number of executed tests:  80
09-06 18:57:29.819  6219  6271 I jxcore-log: 
09-06 18:57:29.819  6219  6271 I jxcore-log: Number of passed tests:  80
09-06 18:57:29.819  6219  6271 I jxcore-log: 
,09-06 18:57:29.819  6219  6271 I jxcore-log: Number of failed tests:  0
09-06 18:57:29.819  6219  6271 I jxcore-log: 
09-06 18:57:29.819  6219  6271 I jxcore-log: Number of ignored tests:  0
09-06 18:57:29.819  6219  6271 I jxcore-log: 
,09-06 18:57:29.819  6219  6271 I jxcore-log: Total duration:  23285
09-06 18:57:29.819  6219  6271 I jxcore-log: 
09-06 18:57:29.819  6219  6271 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-06 18:57:29.819  6219  6271 I jxcore-log: 
,09-06 18:57:29.819  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:29.819  6219  6271 I jxcore-log: 
09-06 18:57:29.829  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:29.829  6219  6271 I jxcore-log: 
09-06 18:57:29.829  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:29.829  6219  6271 I jxcore-log: 
09-06 18:57:29.829  1014  1524 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
09-06 18:57:29.829  1014  7000 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
09-06 18:57:29.829  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:29.829  6219  6271 I jxcore-log: 
09-06 18:57:29.829  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:29.829  6219  6271 I jxcore-log: 
09-06 18:57:29.829  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:29.829  6219  6271 I jxcore-log: 
09-06 18:57:29.829  1014  3293 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-06 18:57:29.829  1014  3293 D SecContentProvider2: mCursor = null
09-06 18:57:29.829  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:29.829  6219  6271 I jxcore-log: 
09-06 18:57:29.839  1014  1027 D SecContentProvider2: uri = 15 selection = getToastGravity
09-06 18:57:29.839  1014  1027 D SecContentProvider2: mCursor = null
,09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
,09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
09-06 18:57:29.839  1014  1522 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-06 18:57:29.839  1014  1522 D SecContentProvider2: mCursor = null
09-06 18:57:29.839  6219  6219 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
,09-06 18:57:29.839  1014  1026 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-06 18:57:29.839  1014  1026 D SecContentProvider2: mCursor = null
09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
,09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
09-06 18:57:29.839  1014  1480 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,09-06 18:57:29.839  1014  1480 D SecContentProvider2: mCursor = null
09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
,09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
09-06 18:57:29.839  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-06 18:57:29.839  6219  6271 I jxcore-log: 
,09-06 18:57:29.849  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:57:29.849  6219  6271 I jxcore-log: 
09-06 18:57:29.849  1014  1474 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-06 18:57:29.849  1014  1474 D SecContentProvider2: mCursor = null
,09-06 18:57:29.849  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-06 18:57:29.849  6219  6271 I jxcore-log: 
09-06 18:57:29.849  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 18:57:29.849  6219  6271 I jxcore-log: 
,09-06 18:57:29.849  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 18:57:29.849  6219  6271 I jxcore-log: 
09-06 18:57:29.849  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 18:57:29.849  6219  6271 I jxcore-log: 
,09-06 18:57:29.849  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 18:57:29.849  6219  6271 I jxcore-log: 
09-06 18:57:29.849  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 18:57:29.849  6219  6271 I jxcore-log: 
,09-06 18:57:29.849  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-06 18:57:29.849  6219  6271 I jxcore-log: 
09-06 18:57:29.849  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:29.849  6219  6271 I jxcore-log: 
,09-06 18:57:29.869   258   258 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-06 18:57:29.889  1014  3291 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1014
,09-06 18:57:29.899  6219  6219 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 18:57:29.899  1174  1174 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 18:57:29.899  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 18:57:29.899  6219  6271 I jxcore-log: 
,09-06 18:57:29.909  1014  7000 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 06 Sep 2016 16:57:29 GMT], X-Android-Received-Millis=[1473181049919], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473181049887]}
09-06 18:57:29.909  1014  7000 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
09-06 18:57:29.909  1014  7000 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,09-06 18:57:29.919  1014  1126 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-06 18:57:29.919  1014  1126 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-06 18:57:29.919  1014  1126 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-06 18:57:29.919  1014  1126 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-06 18:57:29.919  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-06 18:57:29.919  1174  1717 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-06 18:57:29.919  3778  6281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290,
,09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: EthernetConnected: false
,09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: updateDataNetType()
09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-06 18:57:29.939  1174  1174 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-06 18:57:29.939  1174  1174 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-06 18:57:29.939  1174  1174 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-06 18:57:30.069  6219  6219 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-06 18:57:30.069  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 18:57:30.069  6219  6271 I jxcore-log: 
,09-06 18:57:30.109  7042  7042 D AndroidRuntime: ,
09-06 18:57:30.109  7042  7042 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-06 18:57:30.109  7042  7042 D AndroidRuntime: CheckJNI is OFF,
09-06 18:57:30.109  7042  7042 D AndroidRuntime: readGMSProperty: start
,09-06 18:57:30.109  7042  7042 D AndroidRuntime: readGMSProperty: already setted!!
09-06 18:57:30.109  7042  7042 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-06 18:57:30.109  7042  7042 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-06 18:57:30.109  7042  7042 D AndroidRuntime: readGMSProperty: end
09-06 18:57:30.109  7042  7042 D AndroidRuntime: addProductProperty: start
,09-06 18:57:30.229  1014  1126 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE,
,09-06 18:57:30.229  6219  6219 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-06 18:57:30.229  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-06 18:57:30.229  6219  6271 I jxcore-log: 
,09-06 18:57:30.239  7042  7042 E AffinityControl: AffinityControl: registerfunction enter
,09-06 18:57:30.249  1014  1038 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:30.259  3152  3152 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-06 18:57:30.259  7042  7042 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-06 18:57:30.269  6550  6550 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-06 18:57:30.269  6219  6219 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-06 18:57:30.269  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-06 18:57:30.269  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-06 18:57:30.269  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-06 18:57:30.269  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-06 18:57:30.269  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-06 18:57:30.269  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-06 18:57:30.269  6219  6219 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-06 18:57:30.279  6533  6533 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-06 18:57:30.279  6533  6533 I PCWCLIENTTRACE_PushUtil: sales region : global
09-06 18:57:30.279  6533  6533 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-06 18:57:30.279  6219  6219 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-06 18:57:30.279  6533  6533 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:30.289  6219  6271 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-06 18:57:30.289  6219  6271 I jxcore-log: 
,09-06 18:57:30.289  1014  1026 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
09-06 18:57:30.289  1014  1026 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,09-06 18:57:30.289  1014  1522 D PackageManager: START PACKAGE DELETE: observer{209245016}
09-06 18:57:30.289  1014  1522 D PackageManager: pkg{<packageName>}
09-06 18:57:30.289  1014  1522 D PackageManager: user{0}
09-06 18:57:30.289  1014  1522 D PackageManager: caller{2000}
09-06 18:57:30.289  1014  1522 D PackageManager: flags{2}
09-06 18:57:30.289  1014  1522 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
09-06 18:57:30.289  1014  1522 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-06 18:57:30.289  1014  1522 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-06 18:57:30.289  1014  1522 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-06 18:57:30.289  1014  1522 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-06 18:57:30.299  1014  1054 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-06 18:57:30.299  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-06 18:57:30.299  1014  1054 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-06 18:57:30.299  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled
09-06 18:57:30.299  1014  1054 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-06 18:57:30.299  6550  6550 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
09-06 18:57:30.299  1014  1054 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,09-06 18:57:30.409  1721  1721 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 18:57:30.419  1014  1039 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
,09-06 18:57:30.419  1014  1039 I ActivityManager: Killing 6219:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-06 18:57:30.419  1014  1039 I ActivityManager:   Force finishing activity ActivityRecord{2016c2fa u0 com.test.thalitest/.MainActivity t128}
,09-06 18:57:30.449  1014  1817 D RCPManagerService: exchangeData() failure , invalid userId
,09-06 18:57:30.459  1014  1094 W InputDispatcher: channel ~ Consumer closed input channel or an error occurred.  events=0x9
09-06 18:57:30.459  1014  1094 E InputDispatcher: channel ~ Channel is unrecoverably broken and will be disposed!
,09-06 18:57:30.459  1014  1257 W InputDispatcher: Attempted to unregister already unregistered input channel
09-06 18:57:30.459  1014  1257 I WindowState: WIN DEATH: Window{1dcb465a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-06 18:57:30.459  1014  1347 D RCPManagerService: exchangeData() failure , invalid userId
09-06 18:57:30.459   258   441 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
09-06 18:57:30.459   258   449 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,09-06 18:57:30.479  1014  1257 D InputDispatcher: Focus left window: 6219
,09-06 18:57:30.479  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-06 18:57:30.479  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 18:57:30.499  1014  1524 I art     : Explicit concurrent mark sweep GC freed 80142(4MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 27MB/41MB, paused 10.062ms total 198.791ms
09-06 18:57:30.499  1014  1524 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 18:57:30.499  1014  1524 D SecContentProvider2: mCursor = null
,09-06 18:57:30.499  1014  1039 W ActivityManager: mDVFSHelper.acquire()
,09-06 18:57:30.539  1014  1054 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-06 18:57:30.539  1014  1054 I ActivityManager:   Force finishing activity ActivityRecord{2016c2fa u0 com.test.thalitest/.MainActivity t128 f}
09-06 18:57:30.539  1014  1054 W ActivityManager: Duplicate finish request for ActivityRecord{2016c2fa u0 com.test.thalitest/.MainActivity t128 f}
,09-06 18:57:30.539  6565  6565 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
09-06 18:57:30.539  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-06 18:57:30.539  6499  6499 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-06 18:57:30.539  6499  6499 D SecurityLogAgent: StateMachine : Current State = 1
,09-06 18:57:30.539  6499  6499 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-06 18:57:30.569  1014  1054 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-06 18:57:30.579  5667  5667 I art     : Explicit concurrent mark sweep GC freed 2068(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 710us total 30.961ms
,09-06 18:57:30.589  1014  1095 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-06 18:57:30.599  1781  1781 E SamsungIME: mOCRHelper is null,
,09-06 18:57:30.599  1932  2111 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-06 18:57:30.609  5458  5458 I art     : Explicit concurrent mark sweep GC freed 389(27KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 8MB/11MB, paused 764us total 40.261ms
,09-06 18:57:30.609  3778  3778 I art     : Explicit concurrent mark sweep GC freed 23032(1394KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 15MB/26MB, paused 1.344ms total 70.265ms
,09-06 18:57:30.619  1014  1038 D EnterpriseDeviceManagerService: Package has changed for user 0
09-06 18:57:30.619  1014  1038 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-06 18:57:30.619  3152  3152 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-06 18:57:30.619  1014  1038 W TextServicesManagerService: no available spell checker services found
,09-06 18:57:30.629  3778  3787 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-06 18:57:30.629  1014  1039 D InputDispatcher: Focused application released
,09-06 18:57:30.639  3152  3152 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-06 18:57:30.639  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 18:57:30.639  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,09-06 18:57:30.639  1721  1721 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-06 18:57:30.639  1721  1721 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
09-06 18:57:30.639  1721  1721 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-06 18:57:30.639  1721  1721 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
09-06 18:57:30.639  3152  3152 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-06 18:57:30.649  3152  3152 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-06 18:57:30.649  3152  3152 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-06 18:57:30.659  3152  3152 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-06 18:57:30.659  1014  1121 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-06 18:57:30.659  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:30.659  1014  1121 V NetworkStats: performPollLocked(flags=0x3)
,09-06 18:57:30.669  3152  3152 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-06 18:57:30.669  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox updated
09-06 18:57:30.669  1014  1121 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-06 18:57:30.679  6565  6565 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,09-06 18:57:30.679  1014  1121 V NetworkStats: performPollLocked() took 13ms
09-06 18:57:30.679  1014  1121 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:30.679  1438  1438 D RegisteredServicesCache: empty dynamic service
,09-06 18:57:30.679  1322  1349 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,09-06 18:57:30.679  3152  3152 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-06 18:57:30.709  6565  6565 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,09-06 18:57:30.729  3152  3152 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-06 18:57:30.729  1438  1438 D RegisteredComponentCache: Collect Tech packages for Knox
,09-06 18:57:30.729  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 18:57:30.729  1438  1438 D PersonaManager: isKioskContainerExistOnDevice
,09-06 18:57:30.729  1721  1721 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
,09-06 18:57:30.729  1721  1721 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-06 18:57:30.729  1014  1126 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-06 18:57:30.739  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-06 18:57:30.739  1014  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-06 18:57:30.749  6565  6565 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,09-06 18:57:30.759  1721  1721 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-06 18:57:30.769  3730  3730 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 18:57:30 GMT+02:00 2016
,09-06 18:57:30.769  1014  1347 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
09-06 18:57:30.769  1014  1347 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-06 18:57:30.769  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 18:57:30.769  3152  3152 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-06 18:57:30.779  3152  3152 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-06 18:57:30.789  1014  1257 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-06 18:57:30.789  3152  3152 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-06 18:57:30.789  1014  1257 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 18:57:30.789  3152  3152 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-06 18:57:30.789  1014  1257 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:30.789  1014  1257 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:30.789  1014  1257 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 18:57:30.789  3152  3152 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-06 18:57:30.789  3152  3152 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-06 18:57:30.819  1014  1474 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-06 18:57:30.819  1014  1474 D SecContentProvider2: mCursor = null
09-06 18:57:30.819  3730  3730 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-06 18:57:30.829  3730  3730 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-06 18:57:30.829  3730  3730 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 18:57:30.829  3730  3730 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 18:57:30.829  1014  1522 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-06 18:57:30.829  1014  1522 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-06 18:57:30.829  1014  1522 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-06 18:57:30.829  1014  1524 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-06 18:57:30.829  1014  1524 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-06 18:57:30.829  1014  1524 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:30.829  1014  1524 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-06 18:57:30.829  1014  1524 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-06 18:57:30.829  3152  3152 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-06 18:57:30.839  3730  7058 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 18:57:30.839   258   258 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-06 18:57:30.849  1014  1042 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-06 18:57:30.849  3730  7058 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,09-06 18:57:30.849  1014  1817 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,09-06 18:57:30.859  1014  1817 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.LocationTagReadyService; callingUser = 0; userId(target) = 0
,09-06 18:57:30.859  1014  1054 I art     : Explicit concurrent mark sweep GC freed 20531(1604KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 4.079ms total 227.189ms
,09-06 18:57:30.859  1014  1817 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:30.859  1014  1817 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:30.859  1014  1817 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-06 18:57:30.859  1014  1480 D InputDispatcher: Focus entered window: 3152
,09-06 18:57:30.859  1014  1044 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-06 18:57:30.859  1014  1044 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-06 18:57:30.859  3152  3152 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-06 18:57:30.869   281   996 D EnterpriseController: uids 10012
09-06 18:57:30.869   281   996 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-06 18:57:30.869   281   996 D Netd    : getNetworkForDns: using netid 504 for uid 10012
,09-06 18:57:30.869  3152  3152 V ActivityThread: updateVisibility : ActivityRecord{156bae03 token=android.os.BinderProxy@dc14f56 {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-06 18:57:30.879  3730  7058 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,09-06 18:57:30.879  3730  7058 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,09-06 18:57:30.879  3778  3778 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-06 18:57:30.889  3730  7058 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,09-06 18:57:30.889  3778  4586 I iu.UploadsManager: num queued entries: 0
,09-06 18:57:30.889  3778  4586 I iu.UploadsManager: num updated entries: 0
,09-06 18:57:30.889  3778  4586 I iu.SyncManager: NEXT; no task
,09-06 18:57:30.899  1014  1126 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-06 18:57:30.899  1014  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-06 18:57:30.899  1174  1717 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 18:57:30.899  1014  1126 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,09-06 18:57:30.899  3778  6281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
09-06 18:57:30.909  1014  1474 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-06 18:57:30.909  3730  7058 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,09-06 18:57:30.909  3730  7058 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-06 18:57:30.909  1174  1717 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 18:57:30.909  3778  6281 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,09-06 18:57:30.919  1014  1474 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6219 uid 10155
,09-06 18:57:30.919  3152  3152 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@dc14f56 time:150385
,09-06 18:57:30.919  1014  7066 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-06 18:57:30.929  3730  3730 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-06 18:57:30.929  1014  1044 W ActivityManager: mDVFSHelper.release()
09-06 18:57:30.929  1014  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ad0edd3 u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:150391
,09-06 18:57:30.929  1014  1524 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-06 18:57:30.929  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:30.929  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:30.929  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:30.929  1014  1524 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:30.929  1781  1781 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-06 18:57:30.939  1014  1014 D RCPManagerService: PackageReceiver onReceive()
,09-06 18:57:30.939  7069  7069 I libpersona: KNOX_SDCARD checking this for 10010
09-06 18:57:30.939  1014  1014 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
09-06 18:57:30.939  7069  7069 I libpersona: KNOX_SDCARD not a persona
09-06 18:57:30.939  7069  7069 E Zygote  : MountEmulatedStorage()
09-06 18:57:30.949  1014  1524 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=7069 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-06 18:57:30.939  7069  7069 E Zygote  : v2
09-06 18:57:30.949  1014  1014 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-06 18:57:30.949  1014  1014 I OTPFW   : PackageRemovalReceiver::onReceive Enter,
09-06 18:57:30.949  1014  1014 D OTPFW   : OtpDbHelper::getInstance New instance created
09-06 18:57:30.949  7069  7069 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:30.949  6789  6789 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
09-06 18:57:30.949  7069  7069 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 18:57:30.959  7069  7069 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-06 18:57:30.969  1014  1014 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-06 18:57:30.969  1014  1038 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-06 18:57:30.969  6789  6789 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-06 18:57:30.969  6789  6789 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,09-06 18:57:30.979  1014  1014 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,09-06 18:57:30.979  1014  1014 I OTPFW   : ProvisionData::getAllEntries Enter
,09-06 18:57:30.989  1014  1014 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-06 18:57:30.989  7069  7069 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:30.989  7069  7069 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:30.989  1014  1014 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-06 18:57:30.989  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-06 18:57:30.989  1014  1014 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-06 18:57:30.989  1014  1014 V EnterpriseBillingPolicy: uID is 10155
09-06 18:57:30.989  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 18:57:30.989  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 18:57:30.989  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-06 18:57:30.989  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 18:57:30.989  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 18:57:30.989  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-06 18:57:30.989  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 18:57:30.999  5865  5865 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,09-06 18:57:30.999  1014  1014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-06 18:57:30.999  3257  7086 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
09-06 18:57:30.999  1014  2724 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-06 18:57:30.999  3257  7086 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,09-06 18:57:30.999  3257  7086 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
09-06 18:57:30.999  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,09-06 18:57:30.999  1014  1014 V EnterpriseBillingPolicy: uID is 10155
,09-06 18:57:31.009  1014  1014 V EnterpriseBillingPolicy: Removed Packageuid is0
09-06 18:57:31.009  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-06 18:57:31.009  1014  1014 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,09-06 18:57:31.009  6047  6047 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-06 18:57:31.009  6047  6047 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
09-06 18:57:31.009  6047  6047 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
09-06 18:57:31.009  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-06 18:57:31.009  1014  1014 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-06 18:57:31.009  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-06 18:57:31.009  1014  1014 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-06 18:57:31.009  1014  1014 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-06 18:57:31.009  1014  1054 D PackageManager: delete codoeFile: 
,09-06 18:57:31.019  6047  6047 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-06 18:57:31.019  1932  7059 I qtaguid : Tagging socket 50 with tag 1000040700000000{268436487,0} for uid -1, pid: 1932, getuid(): 10012
,09-06 18:57:31.019  6047  6047 I SA      : [OR] == isSIMCardReady false ==
09-06 18:57:31.019  6047  6047 I SA      : [SCU] == networkStateCheck == true
,09-06 18:57:31.019  6047  6047 I SA      : [DM] getCountryCodeFromCSC : PL
,09-06 18:57:31.019  6047  6047 I SA      : isChinaCountryCode : false
09-06 18:57:31.019  6047  6047 I SA      : [SCU] is ChinestModel Data Restricted   : false
09-06 18:57:31.019  6047  6047 I SA      : [OR] == networkStateCheck true ==
,09-06 18:57:31.029  6047  6047 I SA      : [OR] GetMyCountryZoneTask
09-06 18:57:31.029  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 18:57:31.029  6047  6047 I SA      : [OR] onReceive END
09-06 18:57:31.029  1014  1014 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
09-06 18:57:31.029  1014  1054 I AASA_removePackage: UID=10155 Target=com.test.thalitest
09-06 18:57:31.029  1014  1054 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,09-06 18:57:31.029  1014  1014 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-06 18:57:31.029  1014  1014 D PersonaManagerService: getPersonasForUser(): returning null!
,09-06 18:57:31.029  6725  6725 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:31.029  1174  1174 D PanelView: There is/are notification(s) 
09-06 18:57:31.029  6725  6725 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
09-06 18:57:31.029  6725  6725 I DIAGMON_AGENT: ./extraInfo: "NG700"
,09-06 18:57:31.029  6725  6725 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,09-06 18:57:31.029  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 18:57:31.039  1231  1231 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-06 18:57:31.039  1014  3292 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
09-06 18:57:31.039  1014  3292 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,09-06 18:57:31.039  1014  1054 D PackageManager: result of delete: 1{209245016}
09-06 18:57:31.049  1014  3292 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:31.049  1014  3292 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:31.049  1014  3292 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,09-06 18:57:31.049  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 18:57:31.049  3257  7086 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,09-06 18:57:31.059  3257  7086 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,09-06 18:57:31.059  3257  7086 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,09-06 18:57:31.059  1014  1038 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-06 18:57:31.059  1014  1038 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:57:31.059  1014  1038 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 18:57:31.059  7042  7042 D AndroidRuntime: Shutting down VM
09-06 18:57:31.059  3257  7086 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,09-06 18:57:31.059  3257  7086 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
09-06 18:57:31.059  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 18:57:31.059  3257  7086 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,09-06 18:57:31.059  3257  7086 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,09-06 18:57:31.069  1014  1026 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
09-06 18:57:31.069  1014  1026 D SecContentProvider2: mCursor = null
,09-06 18:57:31.069  6047  7087 I SA      : [SRS] prepareGetMyCountryZone
,09-06 18:57:31.079  3257  7086 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,09-06 18:57:31.079  1014  1054 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-06 18:57:31.079  1014  1054 D PackageManager: userId{-1}
09-06 18:57:31.079  1014  1054 D PackageManager: andCode{true}
,09-06 18:57:31.079  1014  1054 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-06 18:57:31.089  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 18:57:31.099  3257  7086 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,09-06 18:57:31.109  7069  7069 D WaitQueueForNetworkActivate: notifyNetworkActivated
09-06 18:57:31.109  3257  7086 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,09-06 18:57:31.119  6047  7087 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,09-06 18:57:31.119  6047  7087 I SA      : [SSP] query invoked
,09-06 18:57:31.119  6047  7087 I SA      : [TPMU] GetMccFromDB : null
,09-06 18:57:31.119  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,09-06 18:57:31.119  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 18:57:31.129  1014  1158 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
,09-06 18:57:31.129  1174  1174 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-06 18:57:31.129  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 18:57:31.129  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 18:57:31.129  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,09-06 18:57:31.129  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,09-06 18:57:31.129  1174  1174 D PanelView: There is/are notification(s) 
09-06 18:57:31.129  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
09-06 18:57:31.129  6047  7087 I SA      : [SCU] getMccFromPreferece mcc = 260
09-06 18:57:31.129  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 18:57:31.129  6047  7087 I SA      : [LBE] isSupportCheckDomainRegion : false
09-06 18:57:31.129  6047  7087 I SA      : [TPM] isNoProxy(default) : true
,09-06 18:57:31.129  1174  1174 D PersonaManager: isKioskContainerExistOnDevice
,09-06 18:57:31.129  1174  1174 D PanelView: There is/are notification(s) 
,09-06 18:57:31.139  1174  1174 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-06 18:57:31.139  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 18:57:31.139  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 18:57:31.139  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-06 18:57:31.139  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-06 18:57:31.139  1014  1038 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-06 18:57:31.149  1014  1038 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-06 18:57:31.149  1014  1038 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-06 18:57:31.149  6047  7087 E File    : fail readDirectory() errno=2
,09-06 18:57:31.209  1174  1174 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-06 18:57:31.269  7042  7042 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-06 18:57:31.299  1014  3293 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,09-06 18:57:31.299  1014  3293 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,09-06 18:57:31.299  1014  3293 W ActivityManager: userId = 0, bbcId = -10000
,09-06 18:57:31.299  1014  3293 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-06 18:57:31.299  1014  3293 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,09-06 18:57:31.309  1014  1039 I splitIntent: Queue : backgroundsplit_2 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-06 18:57:31.309  7069  7069 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,09-06 18:57:31.319  7069  7069 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,09-06 18:57:31.319  7069  7069 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,09-06 18:57:31.319  7069  7069 D InitializeManagerStateMachine: exit::IDLE
09-06 18:57:31.319  7069  7069 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,09-06 18:57:31.319  7069  7069 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
09-06 18:57:31.319  7069  7069 D InitializeManagerStateMachine: exit::NETWORK_CHECK
09-06 18:57:31.319  7069  7069 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
09-06 18:57:31.319  7069  7069 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
09-06 18:57:31.319  7069  7069 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
09-06 18:57:31.319  7069  7069 D InitializeManagerStateMachine: entry::SUCCESS
09-06 18:57:31.319  7069  7069 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,09-06 18:57:31.319  3730  3730 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Sep 06 18:57:31 GMT+02:00 2016
,09-06 18:57:31.319  1014  3294 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-06 18:57:31.319  1014  3294 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-06 18:57:31.329  1014  3294 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:31.329  7069  7069 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
09-06 18:57:31.329  7069  7069 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,09-06 18:57:31.329  1014  3294 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:31.329  1014  3294 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-06 18:57:31.329  7069  7069 D InitializeManagerStateMachine: exit::SUCCESS
,09-06 18:57:31.329  7069  7069 D InitializeManagerStateMachine: entry::IDLE
,09-06 18:57:31.329  3730  3730 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-06 18:57:31.339  1014  1491 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
09-06 18:57:31.339  1014  1491 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
09-06 18:57:31.339  3730  3730 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-06 18:57:31.339  1014  1491 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-06 18:57:31.339  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.339  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.339  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.339  1014  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:31.339  3730  3730 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-06 18:57:31.339  3730  3730 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-06 18:57:31.339  3730  7100 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-06 18:57:31.349  3730  7100 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,09-06 18:57:31.349  3730  7100 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-06 18:57:31.349  7101  7101 E Zygote  : MountEmulatedStorage()
,09-06 18:57:31.349  7101  7101 I libpersona: KNOX_SDCARD checking this for 10094
09-06 18:57:31.349  7101  7101 E Zygote  : v2
,09-06 18:57:31.349  7101  7101 I libpersona: KNOX_SDCARD not a persona
09-06 18:57:31.349  7101  7101 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:31.349  1014  1491 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7101 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a,
09-06 18:57:31.359  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast,
09-06 18:57:31.359  3730  7100 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-06 18:57:31.359  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.359  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.359  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.359  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.369  7101  7101 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 18:57:31.369  7101  7101 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:31.379  7112  7112 E Zygote  : MountEmulatedStorage()
,09-06 18:57:31.379  1014  1039 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7112 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
09-06 18:57:31.379  7112  7112 E Zygote  : v2
09-06 18:57:31.379  7112  7112 I libpersona: KNOX_SDCARD checking this for 10044,
09-06 18:57:31.379  7112  7112 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:31.389  7112  7112 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-06 18:57:31.389  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
09-06 18:57:31.389  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.389  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.389  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.389  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-06 18:57:31.389  7112  7112 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-06 18:57:31.389  7112  7112 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-06 18:57:31.409  7131  7131 E Zygote  : MountEmulatedStorage()
09-06 18:57:31.409  7131  7131 I libpersona: KNOX_SDCARD checking this for 10149
09-06 18:57:31.409  7131  7131 E Zygote  : v2
09-06 18:57:31.409  7131  7131 I libpersona: KNOX_SDCARD not a persona
,09-06 18:57:31.409  7131  7131 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
09-06 18:57:31.409  7112  7112 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:31.419  7112  7112 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:31.419  7131  7131 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-06 18:57:31.419  7131  7131 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-06 18:57:31.419  7101  7101 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:31.419  7101  7101 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:31.419  1014  1039 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7131 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,09-06 18:57:31.439  3730  7100 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-06 18:57:31.449  7131  7131 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-06 18:57:31.449  7131  7131 D ActivityThread: Added TimaKeyStore provider
,09-06 18:57:31.449  7112  7112 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-06 18:57:31.449  7112  7112 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-06 18:57:31.449  7112  7112 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-06 18:57:31.449  7112  7112 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-06 18:57:31.449  7112  7112 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-06 18:57:31.449  7112  7112 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-06 18:57:31.449  7112  7112 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-06 18:57:31.449  7112  7112 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-06 18:57:31.449  3730  7100 E SQLiteLog: (28) failed to open "/data/data/com.samsung.klmsagent/databases/klms.db" with flag (131138) and mode_t (0) due to error (30)
,09-06 18:57:31.459  3730  7100 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.klmsagent/databases/klms.db'.
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:31.459  3730  7100 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: Couldn't open klms.db for writing (will try read-only):
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at com.samsung.klmsagent.data.DataSource.fetchData(DataSource.java:132)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.i.KLMSValidator.IsPackageExistInDevice(KLMSValidator.java:528)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.listeningToPackageRemoved(KLMSIntentService.java:388)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at com.samsung.klmsagent.services.KLMSIntentService.onHandleIntent(KLMSIntentService.java:213)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:31.459  3730  7100 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,09-06 18:57:31.459  3730  7100 W SQLiteOpenHelper: Opened klms.db in read-only mode
,09-06 18:57:31.469  3730  7100 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-06 18:57:31.469  7101  7101 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
09-06 18:57:31.469  5765  5765 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/history.db" with flag (131138) and mode_t (0) due to error (30)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/history.db'.
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 18:57:31.469  5765  5765 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 18:57:31.469  5765,  5765 D AndroidRuntime: Shutting down VM
09-06 18:57:31.469  5765  5765 E AndroidRuntime: FATAL EXCEPTION: main
09-06 18:57:31.469  5765  5765 E AndroidRuntime: Process: com.samsung.android.sm, PID: 5765
09-06 18:57:31.469  5765  5765 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3132)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.<init>(ScanHistoryHelper.java:42)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at com.samsung.android.sm.common.security.m.a(ScanHistoryHelper.java:30)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:173)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	at android.app.ActivityThrea,d.handleReceiver(ActivityThread.java:3125)
09-06 18:57:31.469  5765  5765 E AndroidRuntime: 	... 9 more
09-06 18:57:31.479  3730  7100 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
09-06 18:57:31.479  7101  7101 D elm:15183: ELMEngine.ELMEngine( context ).
09-06 18:57:31.479  1014  1491 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
09-06 18:57:31.479  5765  7121 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
09-06 18:57:31.479  3730  3730 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
09-06 18:57:31.479  7101  7101 D elm:15183: MDMBridge.setEnterpriseBridge()
09-06 18:57:31.489  5765  7121 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sm/databases/seatbelt.db" with flag (131138) and mode_t (0) due to error (30)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: Can't write: system_app_crash
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop201.tmp: open failed: EROFS (Read-only file system)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15777)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-06 18:57:31.489  1014  7147 E DropBoxManagerService: 	... 5 more
09-06 18:57:31.489  1014  1480 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-06 18:57:31.489  1014  1480 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
09-06 18:57:31.489  1014  1480 W ActivityManager: userId = 0, bbcId = -10000
09-06 18:57:31.489  1014  1480 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-06 18:57:31.489  1014  1480 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sm/databases/seatbelt.db'.
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:40)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:28)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at com.samsung.android.sm.common.r.n(Utils.java:2237)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at com.samsung.android.sm.common.o.run(SmartManagerReceiver.java:125)
09-06 18:57:31.489  5765  7121 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
09-06 18:57:31.489  5765  7121 I Process : Sending signal. PID: 5765 SIG: 9
09-06 18:57:31.489   255   255 E lowmemorykiller: Error writing /proc/5765/oom_score_adj; errno=22
09-06 18:57:31.499  1014  1039 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
09-06 18:57:31.499  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.499  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.499  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.499  1014  1039 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-06 18:57:31.509  7148  7148 E Zygote  : MountEmulatedStorage()
09-06 18:57:31.509  7148  7148 I libpersona: KNOX_SDCARD checking this for 1000
09-06 18:57:31.509  7148  7148 E Zygote  : v2
09-06 18:57:31.509  7148  7148 I libpersona: KNOX_SDCARD not a persona
09-06 18:57:31.519  7148  7148 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-06 18:57:31.519  7101  7101 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.

```
