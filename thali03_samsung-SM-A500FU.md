#### Test 846487400fb5c63_thali03_samsung-SM-A500FU Logs


```
--------- beginning of main
09-12 13:10:56.059   317   317 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
09-12 13:10:56.059   317   317 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,09-12 13:10:57.049   287   287 E SMD     : DCD OFF
09-12 13:10:57.109  6215  6215 D AndroidRuntime: 
09-12 13:10:57.109  6215  6215 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-12 13:10:57.109  6215  6215 D AndroidRuntime: CheckJNI is OFF
09-12 13:10:57.109  6215  6215 D AndroidRuntime: readGMSProperty: start
09-12 13:10:57.109  6215  6215 D AndroidRuntime: readGMSProperty: already setted!!
09-12 13:10:57.109  6215  6215 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 13:10:57.109  6215  6215 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-12 13:10:57.109  6215  6215 D AndroidRuntime: readGMSProperty: end
09-12 13:10:57.109  6215  6215 D AndroidRuntime: addProductProperty: start
09-12 13:10:57.259  6215  6215 E AffinityControl: AffinityControl: registerfunction enter
09-12 13:10:57.289  6215  6215 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-12 13:10:57.299  1013  1670 E PersonaManagerService: inState():  stateMachine is null !!
09-12 13:10:57.299  1013  1670 I PersonaManagerService: PersonaId don't exist
09-12 13:10:57.299  1013  1670 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-12 13:10:57.299  1013  1670 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
09-12 13:10:57.319  1013  1670 W ActivityManager: mDVFSHelper.acquire()
09-12 13:10:57.319  1013  1043 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-12 13:10:57.319  1013  1043 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-12 13:10:57.329  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:10:57.329  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:10:57.329  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:10:57.329  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:10:57.339  6226  6226 E Zygote  : MountEmulatedStorage()
09-12 13:10:57.339  6226  6226 E Zygote  : v2
09-12 13:10:57.339  6226  6226 I libpersona: KNOX_SDCARD checking this for 10155
09-12 13:10:57.339  6226  6226 I libpersona: KNOX_SDCARD not a persona
09-12 13:10:57.339  1013  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 13:10:57.339  1013  1043 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-12 13:10:57.349   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, uhalitest
09-12 13:10:57.349  1013  1670 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6226 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-12 13:10:57.349  1013  1670 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
09-12 13:10:57.349  1013  1670 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 13:10:57.349  6226  6226 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:10:57.349  6226  6226 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:10:57.359  6226  6226 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-12 13:10:57.369  1013  1670 D InputDispatcher: Focused application set to: xxxx
09-12 13:10:57.369  1013  1670 D InputDispatcher: Focus left window: 3117
09-12 13:10:57.369  6215  6215 D AndroidRuntime: Shutting down VM
09-12 13:10:57.379  6226  6226 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:10:57.379  6226  6226 D ActivityThread: Added TimaKeyStore provider
09-12 13:10:57.389  1013  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-12 13:10:57.389  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 13:10:57.389  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
09-12 13:10:57.389  1013  1013 V ActivityManager: Display changed displayId=0
09-12 13:10:57.409  1013  3011 D PersonaManager: isKioskContainerExistOnDevice
09-12 13:10:57.439   257  1093 I SurfaceFlinger: id=11 Removed YUIInstallC (5/9)
09-12 13:10:57.439   257   824 I SurfaceFlinger: id=11 Removed YUIInstallC (-2/9)
09-12 13:10:57.439  3117  3117 V ActivityThread: updateVisibility : ActivityRecord{10b7e3a1 token=android.os.BinderProxy@42314cc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : false
09-12 13:10:57.519  6226  6226 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
09-12 13:10:57.539  6226  6226 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 250-251)
09-12 13:10:57.539  6226  6226 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:10:57.559  6226  6226 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1906152d}
09-12 13:10:57.569  6226  6226 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-12 13:10:57.569  6226  6226 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
09-12 13:10:57.579  6215  6215 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-12 13:10:57.599  6226  6226 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 13:10:57.599  6226  6226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:10:57.599  6226  6226 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 13:10:57.629  6226  6226 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-12 13:10:57.629  6226  6226 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,09-12 13:10:57.629  6226  6226 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,09-12 13:10:57.629  6226  6226 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 13:10:57.629  6226  6226 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 13:10:57.629  6226  6226 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 13:10:57.629  6226  6226 I Adreno-EGL: Local Branch: 
09-12 13:10:57.629  6226  6226 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 13:10:57.629  6226  6226 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 13:10:57.629  6226  6226 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 13:10:57.749  6226  6252 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,09-12 13:10:57.799  6226  6226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:10:57.809  6226  6226 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-12 13:10:57.819  6226  6226 D PhoneWindow: *FMB* installDecor mIsFloating : false
,09-12 13:10:57.819  6226  6226 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-12 13:10:57.829  6226  6226 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-12 13:10:57.829  6226  6226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:10:57.829  6226  6226 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:10:57.869  6226  6265 D OpenGLRenderer: Render dirty regions requested: true
,09-12 13:10:57.879  1013  1026 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,09-12 13:10:57.879  1013  1026 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 13:10:57.879  1013  1026 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-12 13:10:57.879  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 13:10:57.879  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 13:10:57.889  6226  6226 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-12 13:10:57.889  6226  6226 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-12 13:10:57.899   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=404, NainActivit
,09-12 13:10:57.919  1013  3010 D InputDispatcher: Focus entered window: 6226
,09-12 13:10:57.919  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-12 13:10:57.919  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:10:57.919  6226  6226 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 13:10:57.919  6226  6265 I OpenGLRenderer: Initialized EGL, version 1.4
,09-12 13:10:57.929  6226  6265 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-12 13:10:57.929  6226  6265 D OpenGLRenderer: Enabling debug mode 0
,09-12 13:10:57.979  6226  6226 V ActivityThread: updateVisibility : ActivityRecord{40c7c0c token=android.os.BinderProxy@2409bb5e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,09-12 13:10:57.999  1013  4555 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 13:10:57.999  1176  1176 D PanelView: There is/are notification(s) 
,09-12 13:10:57.999  1013  6268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 13:10:58.019  1013  1043 I ActivityManager: Displayed Component not be shown by security: +601ms (total +690ms)
09-12 13:10:58.019  1013  1043 W ActivityManager: mDVFSHelper.release()
09-12 13:10:58.019  1013  1043 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2e5274f2 u0 com.test.thalitest/.MainActivity t128} time:110730
,09-12 13:10:58.019  1770  1770 I SamsungIME: getCurrentCandidateView
,09-12 13:10:58.019   257   824 I SurfaceFlinger: id=13 Removed uhalitest (7/9)
,09-12 13:10:58.019   257   444 I SurfaceFlinger: id=13 Removed uhalitest (-2/9)
,09-12 13:10:58.029  6226  6226 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-12 13:10:58.029  6226  6226 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2409bb5e time:110742
,09-12 13:10:58.079  6226  6226 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6226
,09-12 13:10:58.109  1770  1770 D SamsungIME: Dismiss ExpandCandiate
,09-12 13:10:58.199  6226  6226 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-12 13:10:58.239  1770  1770 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 13:10:58.279  1770  1770 I SamsungIME: getDebugLevel  : 0x4f4c
,09-12 13:10:58.289  1770  1770 I SamsungIME: KeybaordView init() : load resources
,09-12 13:10:58.299  6226  6269 D jxcore_app_log: JniHelper::setJavaVM(0xb7aed328), pthread_self() = -1207634112
,09-12 13:10:58.309  6226  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-12 13:10:58.309  6226  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-12 13:10:58.309  6226  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-12 13:10:58.309  6226  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-12 13:10:58.309  6226  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-12 13:10:58.309  6226  6269 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2cad003c added. We now have 1 listener(s)
,09-12 13:10:58.319  6226  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,09-12 13:10:58.319  1770  1770 I SamsungIME: getCurrentKeyboard
,09-12 13:10:58.319  1770  1770 I SamsungIME: getTextKeyboard
,09-12 13:10:58.319  6226  6269 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 13:10:58.319  6226  6269 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:10:58.319  6226  6269 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-12 13:10:58.329  6226  6269 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26cd624b added. We now have 1 listener(s)
,09-12 13:10:58.329  6226  6269 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:10:58.339  1770  1770 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-12 13:10:58.339  6226  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:10:58.339  6226  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-12 13:10:58.339  6226  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-12 13:10:58.339  6226  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-12 13:10:58.339  6226  6269 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-12 13:10:58.339  6226  6269 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:10:58.349  6226  6269 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,09-12 13:10:58.349  6226  6269 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-12 13:10:58.349  6226  6269 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:10:58.349  6226  6269 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:10:58.349  6226  6269 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:10:58.349  6226  6269 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:10:58.349  6226  6269 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:10:58.349  6226  6269 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:10:58.349  6226  6269 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:10:58.349  6226  6269 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:10:58.349  6226  6269 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-12 13:10:58.349  6226  6269 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:10:58.349  6226  6269 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 13:10:58.359  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:10:58.359  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:10:58.379  6226  6226 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-12 13:10:58.889  1770  6275 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-12 13:10:58.929  6226  6276 W jxcore-log: Initializing JXcore engine
09-12 13:10:58.929  6226  6276 W jxcore-log: JXcore engine is ready
,09-12 13:10:58.979  1896  1896 E audit   : type=1400 msg=audit(1473678658.979:205): avc:  denied  { ioctl } for  pid=6276 comm="Thread-1078" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-12 13:10:58.979  1896  1896 E audit   :  SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:10:58.979  1896  1896 E audit   : type=1300 msg=audit(1473678658.979:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=3 a3=9e0c08f8 items=0 ppid=309 ppcomm=main pid=6276 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-1078" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
09-12 13:10:58.979  1896  1896 E audit   : type=1320 msg=audit(1473678658.979:205): 
,09-12 13:10:58.989  6226  6276 W jxcore-log: Starting JXcore engine
,09-12 13:10:59.109  6226  6276 W jxcore-log: Platform android
09-12 13:10:59.109  6226  6276 W jxcore-log: 
09-12 13:10:59.109  6226  6276 W jxcore-log: Process ARCH arm
09-12 13:10:59.109  6226  6276 W jxcore-log: 
,09-12 13:10:59.309  6226  6276 I jxcore-log: JXcore Cordova bridge is ready!
09-12 13:10:59.309  6226  6276 I jxcore-log: 
,09-12 13:10:59.309  6226  6276 W jxcore-log: JXcore engine is started
,09-12 13:10:59.319  6226  6269 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-12 13:10:59.319  6226  6226 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-12 13:10:59.989  1013  1091 V AlarmManager: waitForAlarm result :8,
,09-12 13:11:00.049   287   287 E SMD     : DCD OFF,
,09-12 13:11:01.049   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:11:01.879  5456  5456 D FactoryTest: Not factory mode,
,09-12 13:11:01.879  5456  5456 D FactoryTest: Not factory mode. isFactoryMode() returend false
,09-12 13:11:01.879  5456  5456 D MTPRx   : DRIVER_TIME_OUT 60s lapsed
09-12 13:11:01.879  5456  5456 D MTPRx   : still no open session command from host, so toast
,09-12 13:11:01.879  5456  5456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 android.os.Handler.dispatchMessage:102 
,09-12 13:11:01.879  5456  5456 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:708 
,09-12 13:11:01.879  5456  5456 I Timeline: Timeline: Activity_launch_request id:com.android.settings time:114598
,09-12 13:11:01.889  1013  1137 E PersonaManagerService: inState():  stateMachine is null !!
,09-12 13:11:01.889  1013  1137 I PersonaManagerService: PersonaId don't exist
,09-12 13:11:01.889  1013  1137 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,09-12 13:11:01.889  1013  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-12 13:11:01.889  1013  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:01.889  1013  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:01.889  1013  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.android.settings
,09-12 13:11:01.889  1013  1137 W ActivityManager: mDVFSHelper.acquire()
,09-12 13:11:01.909  1013  1137 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:11:01.909  1013  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-12 13:11:01.909  1013  1137 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-12 13:11:01.909  1013  1137 D InputDispatcher: Focused application set to: xxxx
,09-12 13:11:01.909  1013  1137 D InputDispatcher: Focus left window: 6226
,09-12 13:11:01.909  5456  5456 E MTPRx   : started activity for popup
,09-12 13:11:01.919  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-12 13:11:01.919  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:11:01.939  5456  5456 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,09-12 13:11:01.939  5456  5456 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-12 13:11:01.939  5456  5456 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 13:11:01.939  5456  5456 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:11:01.939  5456  5456 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:01.939  5456  5456 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:11:01.969  5456  5456 E SettingsReceiverActivity: PREF_DONT_ASK_AGAIN : true
,09-12 13:11:01.969  1013  3152 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.settings
,09-12 13:11:01.969  1013  3152 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 13:11:01.969  1013  3152 D InputDispatcher: Focused application set to: xxxx
,09-12 13:11:01.979  1013  3152 D InputDispatcher: Focus entered window: 6226
,09-12 13:11:01.979  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-12 13:11:01.979  1013  1471 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 13:11:01.979  1013  1471 W InputMethodManagerService: Window already focused, ignoring focus gain of: com.android.internal.view.IInputMethodClient$Stub$Proxy@16e90b4d attribute=null, token = android.os.BinderProxy@229530dd
,09-12 13:11:01.979  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:11:02.019  5456  5456 D SettingsReceiverActivity: dev.kiessupport is : TRUE
,09-12 13:11:02.029  5456  5456 D PhoneWindow: *FMB* installDecor mIsFloating : true
09-12 13:11:02.029  5456  5456 D PhoneWindow: *FMB* installDecor flags : 8388610
,09-12 13:11:02.049  6226  6226 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 13:11:02.049  6226  6226 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,09-12 13:11:02.049  6226  6226 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-12 13:11:02.049  6226  6226 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
,09-12 13:11:02.049   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:11:02.049  1013  1670 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-12 13:11:02.049  1013  1670 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 13:11:02.049  1013  1670 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-12 13:11:02.049  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 13:11:02.049  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 13:11:02.059  6226  6226 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:11:02.059  6226  6226 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,09-12 13:11:02.069  6226  6226 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21c3a39d Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@15ccf5c8, 16908290=android.view.AbsSavedState$1@15ccf5c8}, android:focusedViewId=100}]}],
09-12 13:11:02.069  6226  6226 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
09-12 13:11:02.069  6226  6226 V ActivityThread: updateVisibility : ActivityRecord{40c7c0c token=android.os.BinderProxy@2409bb5e {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-12 13:11:02.069  6226  6226 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-12 13:11:02.069  6226  6226 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
09-12 13:11:02.069  6226  6226 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2409bb5e time:114784
,09-12 13:11:02.069  1013  1796 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:11:03.049   287   287 E SMD     : DCD OFF
09-12 13:11:03.049   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:11:03.329  1013  1379 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-12 13:11:03.329  1013  1379 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4166, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-12 13:11:03.329  1013  1379 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-12 13:11:03.329  1013  1379 D BatteryService: stay LED for charging
09-12 13:11:03.329  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:11:03.329  1013  1013 I MotionRecognitionService: Plugged
,09-12 13:11:03.329  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 13:11:03.329  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 13:11:03.329  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:11:03.339  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,09-12 13:11:03.339  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
,09-12 13:11:03.349  2648  2648 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 13:11:03.349  2648  2722 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:11:03.359  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,09-12 13:11:03.359  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,09-12 13:11:03.359  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,09-12 13:11:04.019  1013  2767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-12 13:11:04.049   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:11:04.379  1013  2724 D SSRM:n  : SIOP:: AP = 340
,09-12 13:11:04.899  1013  1038 W ActivityManager: mDVFSHelper.release()
,09-12 13:11:05.049   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:11:06.049   287   287 E SMD     : DCD OFF,
09-12 13:11:06.049   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,09-12 13:11:07.289  1013  1091 V AlarmManager: waitForAlarm result :4
,09-12 13:11:07.299  1013  1091 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.drive.api.ApiService; callingUser = 0; userId(target) = 0
,09-12 13:11:07.299  1013  1013 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,09-12 13:11:07.299  1013  1013 V AlarmManagerEXT: <AppSync3 Whitelist>
,09-12 13:11:07.309  1013  1013 V AlarmManagerEXT: (AppSync) ### 0 added ###
,09-12 13:11:07.309  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,09-12 13:11:07.309  1176  1176 D KeyguardUpdateMonitor: handleTimeUpdate
,09-12 13:11:07.319  1176  1176 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,09-12 13:11:07.319  1176  1176 D SecKeyguardClockView: HomeTimezone(): 1
,09-12 13:11:07.319  1926  1926 E NetworkScheduler.ATC: Provided calling package not found: com.google.android.apps.photos
,09-12 13:11:07.329  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
09-12 13:11:07.329  1176  1176 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
09-12 13:11:07.329  1176  1176 I KeyguardEffectViewController: *** don't update sliding image ***
,09-12 13:11:07.349  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 13:11:07.359  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 13:11:07.359  1176  1176 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 13:11:07.369  1013  3001 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:11:07.369  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.autobackup.AutoBackupGcmTaskService; callingUser = 0; userId(target) = 0
,09-12 13:11:07.369  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:07.369  1013  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:07.369  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:07.379  1013  1053 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,09-12 13:11:07.409  1176  1176 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,09-12 13:11:07.449  3855  3855 D ConnectivityManager: CallingUid : 10012, CallingPid : 3855
,09-12 13:11:07.449  1013  1471 D ConnectivityService: listenForNetwork for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 13:11:07.459  1013  1131 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI () - 502]
,09-12 13:11:07.459  1013  1131 D ConnectivityService: apparently satisfied.  currentScore=60
,09-12 13:11:07.459  1013  1131 D ConnectivityService: handleRegisterNetworkRequest checking NetworkAgentInfo [WIFI_P2P () - 501]
,09-12 13:11:07.459  3855  6288 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 13:11:07.509  3855  6289 W DriveInitializer: Background init thread started
,09-12 13:11:07.529   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
09-12 13:11:07.529   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:11:07.529  3855  6289 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
,09-12 13:11:07.579  1013  3011 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:07.579  1013  3011 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.ads.jams.NegotiationService; callingUser = 0; userId(target) = 0
,09-12 13:11:07.579  1013  3011 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:07.579  1013  3011 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:07.579  1013  3011 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:07.609  1013  3010 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,09-12 13:11:07.609  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-12 13:11:07.619  1013  3001 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:07.619  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gass.chimera.SchedulePeriodicTasksService; callingUser = 0; userId(target) = 0
,09-12 13:11:07.619  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:07.619  1013  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:07.619  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:07.639  3855  6289 W DriveInitializer: Background init thread ended
,09-12 13:11:07.639  3855  6297 D SchedPeriodicTask: Will NOT schedule AdAttestation signal task because it's disabled.
,09-12 13:11:07.649  3855  6297 D SchedPeriodicTask: Scheduled AdAttestation task.
,09-12 13:11:07.659  1926  1926 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-12 13:11:07.699  1013  1038 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:07.699  1013  1038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:07.699  1013  1038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:07.799  1013  3010 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:07.799  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.be.legacy.AuthCronService; callingUser = 0; userId(target) = 0
,09-12 13:11:07.799  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:07.799  1013  3010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:07.799  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:07.839  1013  1796 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:11:07.839  1013  1796 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextInitService; callingUser = 0; userId(target) = 0
,09-12 13:11:07.839  1013  1796 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:07.839  1013  1796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:07.839  1013  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:07.879  1013  1137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:07.889  1013  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:07.889  1013  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:07.889  1013  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:07.899  1013  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:07.899  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:07.899  1013  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:07.899  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:07.959  1013  3011 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:07.959  1013  3011 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:07.959  1013  3011 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:07.959  1013  3011 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:07.959  1013  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:07.959  1013  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:07.959  1013  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:07.959  1013  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:07.979  6302  6302 E Zygote  : MountEmulatedStorage(),
09-12 13:11:07.979  6302  6302 E Zygote  : v2
09-12 13:11:07.979  6302  6302 I libpersona: KNOX_SDCARD checking this for 10012
09-12 13:11:07.979  6302  6302 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:07.979  6302  6302 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:11:07.979  6302  6302 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:11:07.979  1013  3011 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=6302 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,09-12 13:11:07.989  6302  6302 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-12 13:11:07.999  6302  6302 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:07.999  6302  6302 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:08.019  6302  6302 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-12 13:11:08.019  6302  6302 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-12 13:11:08.059  6302  6302 I MultiDex: VM with version 2.1.0 has multidex support
09-12 13:11:08.059  6302  6302 I MultiDex: install
09-12 13:11:08.059  6302  6302 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,09-12 13:11:08.099  6302  6302 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-12 13:11:08.159  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.contextmanager.service.ContextManagerService; callingUser = 0; userId(target) = 0
,09-12 13:11:08.169  1013  4555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:08.169  6302  6302 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-12 13:11:08.169  6302  6302 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@49a40be: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,09-12 13:11:08.169  6302  6302 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,09-12 13:11:08.169  1013  4555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:08.169  1013  4555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:08.169  1013  4555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:08.189  1013  4556 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:08.189  1013  4556 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:08.189  1013  4556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:08.189  1013  4556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:08.199  6302  6302 D ChimeraCfgMgr: Reading stored module config
,09-12 13:11:08.229  1013  3152 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-12 13:11:08.229  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-12 13:11:08.229  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:08.229  1013  3152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:08.229  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:08.249  1926  1926 E ctxmgr  : [FencePendingIntentCache]Expected to find a PendingIntent for pendingIntentKey=09f618ab-ee5e-44a6-a209-44946fdbed66
,09-12 13:11:08.249  6302  6316 W art     : Suspending all threads took: 13.436ms
,09-12 13:11:08.259  1926  1926 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-12 13:11:08.259  6302  6316 I art     : Background sticky concurrent mark sweep GC freed 21359(1034KB) AllocSpace objects, 2(32KB) LOS objects, 5% free, 10MB/11MB, paused 15.964ms total 50.836ms,
,09-12 13:11:08.269  1926  1926 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-12 13:11:08.289  1013  1670 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:08.299  1013  1670 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:08.299  1013  1670 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:08.299  1013  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:08.309  6302  6321 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
,09-12 13:11:08.329  6302  6302 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-12 13:11:08.329  6302  6302 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
,09-12 13:11:08.419   282   682 D WVCdm   : Instantiating CDM.
,09-12 13:11:08.419   282   692 I WVCdm   : CdmEngine::OpenSession
,09-12 13:11:08.419   282   692 I WVCdm   : Level3 Library Sep 25 2014 17:10:03
,09-12 13:11:08.429   282   692 W WVCdm   : Could not read /data/mediadrm/IDM1013/ay64.dat2: No such file or directory
,09-12 13:11:08.449  1926  2110 I art     : Explicit concurrent mark sweep GC freed 56047(3MB) AllocSpace objects, 9(384KB) LOS objects, 39% free, 14MB/23MB, paused 1.475ms total 77.940ms
,09-12 13:11:08.459   282   692 D DrmWidevineDash: OEMCrypto_Initialize: starts! g_qsee_apps_version = 0x15
09-12 13:11:08.459   282   692 D DrmWidevineDash: Service_Initialize: starts!
09-12 13:11:08.459   282   692 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
,09-12 13:11:08.459   282   692 D QSEECOMAPI: : App is not loaded in QSEE
,09-12 13:11:08.459   282   692 E QSEECOMAPI: : Error::Cannot open the file /vendor/firmware/widevine.mdt
09-12 13:11:08.459   282   692 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-12 13:11:08.459   282   692 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-12 13:11:08.459   282   692 D QSEECOMAPI: : App is not loaded in QSEE
,09-12 13:11:08.459   282   692 E QSEECOMAPI: : Error::Cannot open the file /system/etc/firmware/widevine.mdt
09-12 13:11:08.459   282   692 E QSEECOMAPI: : Error::Loading image failed with ret = -1
09-12 13:11:08.459   282   692 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x19000
09-12 13:11:08.459   282   692 D QSEECOMAPI: : App is not loaded in QSEE
,09-12 13:11:08.489   282   692 D QSEECOMAPI: : Loaded image: APP id = 12
,09-12 13:11:08.489   282   692 D DrmWidevineDash: Service_Initialize: ends! returns 0
,09-12 13:11:08.489   282   692 D QSAPPSVER: qsapps_get_capabilities: Capability from secure side: 0x0
09-12 13:11:08.489   282   692 D QSAPPSVER: qsapps_get_capabilities: returns 0
09-12 13:11:08.489   282   692 D DrmWidevineDash: OEMCrypto_Initialize sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16c8000
09-12 13:11:08.489   282   692 E DrmWidevineDash: sion_buffer g_wv_fhandle->ion_sbuffer  0x0xb16c8000
,09-12 13:11:08.489   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 13:11:08.499   419   429 D DrmLibTime: got the req here! ret=0
09-12 13:11:08.499   419   429 D DrmLibTime: command id, time_cmd_id = 770
09-12 13:11:08.499   419   429 D DrmLibTime: time_getutcsec starts!
09-12 13:11:08.499   419   429 D DrmLibTime: QSEE Time Listener: time_getutcsec
09-12 13:11:08.499   419   429 D DrmLibTime: QSEE Time Listener: get_utc_seconds
09-12 13:11:08.499   419   429 D DrmLibTime: QSEE Time Listener: time_get_modem_time
09-12 13:11:08.499   419   429 D DrmLibTime: QSEE Time Listener: Checking if ATS_MODEM is set or not.
,09-12 13:11:08.499   419   429 D QC-time-services: Lib:time_genoff_operation: pargs->base = 13,
09-12 13:11:08.499   419   429 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 2
09-12 13:11:08.499   419   429 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 0
,09-12 13:11:08.499   419   429 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
09-12 13:11:08.499   320   422 D QC-time-services: Daemon: Connection accepted:time_genoff
,09-12 13:11:08.499   320  6327 D QC-time-services: Daemon:Received base = 13, unit = 1, operation = 2,value = 0
09-12 13:11:08.499   320  6327 D QC-time-services: Daemon:genoff_opr: Base = 13, val = 0, operation = 2,
09-12 13:11:08.499   320  6327 D QC-time-services: offset is: 0 for base: 0
,09-12 13:11:08.499   419   429 E QC-time-services: Receive Passed == base = 13, unit = 1, operation = 2, result = 0,
09-12 13:11:08.499   419   429 D DrmLibTime: QSEE Time Listener: ATS_MODEM is not set. Fallback to Android system time.
,09-12 13:11:08.499   419   429 D DrmLibTime: QSEE Time Listener: Retrieved Android system time: 1473678668
09-12 13:11:08.499   419   429 D DrmLibTime: time_getutcsec returns 0, sec = 1473678668; nsec = 0
09-12 13:11:08.499   419   429 D DrmLibTime: time_getutcsec finished! 
09-12 13:11:08.499   419   429 D DrmLibTime: iotcl_continue_command finished! and return 0 
09-12 13:11:08.499   419   429 D DrmLibTime: before calling ioctl to read the next time_cmd,
09-12 13:11:08.499   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.499   320   422 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,09-12 13:11:08.509   282   692 D DrmWidevineDash: OEMCrypto_Initialize: ends! returns 0
,09-12 13:11:08.509   282   692 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-12 13:11:08.509   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-12 13:11:08.509   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.509   282   692 D DrmWidevineDash: hlos api version =  9
09-12 13:11:08.509   282   692 D DrmWidevineDash: tz api version =  9
09-12 13:11:08.509   282   692 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-12 13:11:08.509   282   692 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: starts!
09-12 13:11:08.509   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-12 13:11:08.509  1644  1658 I art     : Explicit concurrent mark sweep GC freed 1397(47KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 725us total 32.162ms
,09-12 13:11:08.529   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.529   282   692 D DrmWidevineDash: OEMCrypto_IsKeyboxValid: ends! returns 0
09-12 13:11:08.529   282   692 D WVCdm   : OEMCrypto_Initialize Level 1 success. I will use level 1.
09-12 13:11:08.529   282   692 D DrmWidevineDash: OEMCrypto_OpenSession: starts! SID=0xb17ee960
09-12 13:11:08.529   282   692 D DrmWidevineDash: OEMCrypto_OpenSession Session ID = 0
09-12 13:11:08.529   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 13:11:08.529   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.529   282   692 D DrmWidevineDash: OEMCrypto_OpenSession SID = 1
09-12 13:11:08.529   282   692 D DrmWidevineDash: OEMCrypto_OpenSession: ends! returns 0
09-12 13:11:08.529   282   692 D DrmWidevineDash: OEMCrypto_GetRandom: starts! randomData=0xb72f1108, dataLength=8
09-12 13:11:08.529   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 13:11:08.539   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.539   282   692 D DrmWidevineDash: OEMCrypto_GetRandom: ends! returns 0
,09-12 13:11:08.539   282   692 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: starts! SID=1, wrapped_rsa_key=0xb7277010, wrapped_rsa_key_length=1280
,09-12 13:11:08.539   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 13:11:08.549   282   692 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.549   282   692 D DrmWidevineDash: OEMCrypto_LoadDeviceRSAKey: ends! returns 0
09-12 13:11:08.549   282   692 I WVCdm   : CdmEngine::QueryKeyControlInfo
,09-12 13:11:08.549   282   682 W WVCdm   : BufferReader::Read<T> : Failure during parse: Not enough bytes (4)
09-12 13:11:08.549   282   682 W WVCdm   : CdmEngine::ExtractWidevinePssh: Unable to read PSSH atom size
09-12 13:11:08.549   282   682 I WVCdm   : CdmEngine::GenerateKeyRequest
09-12 13:11:08.549   282   682 D DrmWidevineDash: OEMCrypto_GetDeviceID: starts! deviceID=0xb72aa600, idLength=0xb1920730
09-12 13:11:08.549   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 13:11:08.549  1926  2093 W GCoreFlp: No location to return for getLastLocation()
,09-12 13:11:08.569   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_GetDeviceID: ends! returns 0
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: starts!
09-12 13:11:08.569   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 13:11:08.569   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: is_supported = 1
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: wv_app_version = 24
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_SupportsUsageTable: ends! returns 0
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: starts!, current = 0xb1920746, maximum = 0xb1920747
09-12 13:11:08.569   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-12 13:11:08.569   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_GetHDCPCapability: ends! returns 0
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_APIVersion: starts!
09-12 13:11:08.569   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-12 13:11:08.569   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.569   282   682 D DrmWidevineDash: hlos api version =  9
09-12 13:11:08.569   282   682 D DrmWidevineDash: tz api version =  9
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_APIVersion: ends! returns version 9
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_GenerateNonce: starts! SID=1, nonce=0xb19207b4
09-12 13:11:08.569   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 13:11:08.569   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_GenerateNonce: ends! returns 0
09-12 13:11:08.569   282   682 D WVCdm   : PrepareKeyRequest: nonce=1107275256
09-12 13:11:08.569   282   682 D DrmWidevineDash: OEMCrypto_GenerateRSASignature starts! SID=1, message=0xb7298520
09-12 13:11:08.569   282   682 D DrmWidevineDash: message_length=1599, signature=0xb728c0b8, signature_length=0xb1920714
,09-12 13:11:08.569   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
,09-12 13:11:08.599  1013  4556 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:08.599  1013  4556 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:08.599  1013  4556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:08.599  1013  4556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:08.609  1013  4555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:08.609  1013  4555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:08.609  1013  4555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:08.609  1013  4555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:08.619  1013  1796 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:08.619  1013  1796 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:08.619  1013  1796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:08.619  1013  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:08.629  6302  6311 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-12 13:11:08.629  6302  6311 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-12 13:11:08.629  6302  6311 I System.out: (HTTPLog)-Static: isShipBuild true
09-12 13:11:08.629  6302  6311 I System.out: (HTTPLog)-Thread-1057-760885171: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
09-12 13:11:08.629  6302  6311 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:11:08.639   277  1007 D EnterpriseController: uids 10012
09-12 13:11:08.639   277  1007 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 13:11:08.639   277  1007 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-12 13:11:08.649  1926  2098 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 13:11:08.659  3855  6298 D UdcContextInitService: registered all accounts: true
,09-12 13:11:08.659  1926  2110 E ctxmgr  : [FenceManager]Could not remove all geofences. status=Status{statusCode=unknown status code: 1000, resolution=null}
,09-12 13:11:08.679  6302  6311 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 13:11:08.689  6302  6311 I qtaguid : Tagging socket 30 with tag 1000180300000000{268441603,0} for uid -1, pid: 6302, getuid(): 10012
,09-12 13:11:08.739   282   682 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.739   282   682 D DrmWidevineDash: OEMCrypto_GenerateRSASignature returns 0
,09-12 13:11:08.739   282   282 I WVCdm   : CdmEngine::CloseSession
,09-12 13:11:08.739   282   282 D DrmWidevineDash: OEMCrypto_CloseSession: starts! SID=1
09-12 13:11:08.739   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-12 13:11:08.739   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.739   282   282 D DrmWidevineDash: OEMCrypto_CloseSession: ends! returns 0
09-12 13:11:08.739   282   282 I WVCdm   : L3 Terminate.
09-12 13:11:08.739   282   282 D DrmWidevineDash: OEMCrypto_Terminate: starts!
09-12 13:11:08.739   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 1 success with ret = 0
09-12 13:11:08.739   282   282 D QSEECOMAPI: : SUCESS::ioctl call to scale bus bandwidth to level 0 success with ret = 0
09-12 13:11:08.739   282   282 D DrmWidevineDash: Service_Uninitialize: starts!
09-12 13:11:08.739   282   282 D QSEECOMAPI: : QSEECom_dealloc_memory 
09-12 13:11:08.739   282   282 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 12
09-12 13:11:08.739   282   282 D DrmWidevineDash: Service_Uninitialize: ends! returns 0x0
,09-12 13:11:08.739   282   282 D DrmWidevineDash: OEMCrypto_Terminate: ends! returns 0
,09-12 13:11:08.919  1013  3011 I art     : Explicit concurrent mark sweep GC freed 34057(1855KB) AllocSpace objects, 20(320KB) LOS objects, 33% free, 27MB/41MB, paused 2.532ms total 149.458ms
,09-12 13:11:08.969  1013  1473 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-12 13:11:08.969  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-12 13:11:08.969  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:08.969  1013  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:08.969  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:08.989  6302  6311 I qtaguid : Untagging socket 30
,09-12 13:11:09.049   287   287 E SMD     : DCD OFF
,09-12 13:11:09.439  6333  6333 I dex2oat : ----------------------------------------------------,
09-12 13:11:09.439  6333  6333 I dex2oat : <SS>: S T A R T I N G . . .
09-12 13:11:09.439  6333  6333 I dex2oat : <SS>: Zip is absent. Canceled.
09-12 13:11:09.439  6333  6333 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=44 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,09-12 13:11:09.469  6333  6333 I dex2oat : dex2oat took 25.744ms (threads: 4)
,09-12 13:11:09.479  6302  6311 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 13:11:09.479  6302  6311 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 13:11:09.479  6302  6311 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 13:11:09.479  6302  6311 I Adreno-EGL: Local Branch: 
09-12 13:11:09.479  6302  6311 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 13:11:09.479  6302  6311 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 13:11:09.479  6302  6311 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 13:11:09.719  6302  6311 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 13:11:09.719  6302  6311 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 13:11:09.719  6302  6311 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 13:11:09.719  6302  6311 I Adreno-EGL: Local Branch: 
09-12 13:11:09.719  6302  6311 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 13:11:09.719  6302  6311 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 13:11:09.719  6302  6311 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 13:11:09.779  6302  6311 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 13:11:09.779  6302  6311 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 13:11:09.779  6302  6311 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 13:11:09.779  6302  6311 I Adreno-EGL: Local Branch: 
09-12 13:11:09.779  6302  6311 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 13:11:09.779  6302  6311 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 13:11:09.779  6302  6311 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 13:11:09.929  1013  1473 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,09-12 13:11:09.929  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-12 13:11:09.939  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:09.939  1013  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:09.939  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:09.939  1926  6300 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:11:09.949   277  1007 D EnterpriseController: uids 10012
09-12 13:11:09.949   277  1007 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 13:11:09.949   277  1007 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-12 13:11:09.949  1926  6300 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 13:11:09.949  1926  6300 I qtaguid : Tagging socket 58 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1926, getuid(): 10012
,09-12 13:11:09.989  1926  6300 I qtaguid : Tagging socket 66 with tag 1000040100000000{268436481,0} for uid 10012, pid: 1926, getuid(): 10012
,09-12 13:11:10.149  1926  2110 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 13:11:10.149  1926  2110 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,09-12 13:11:10.159  1926  2110 W ctxmgr  : [WorkManager]Long workInfo: label=NetworkManager#getAcl, startTime=2016-09-12 13:11:08.727+0200, stopTime=2016-09-12 13:11:10.171+0200, duration=1444ms
,09-12 13:11:10.169  1926  6345 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:11:10.169   277  1007 D EnterpriseController: uids 10012
09-12 13:11:10.169   277  1007 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 13:11:10.169   277  1007 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-12 13:11:10.179  1926  6345 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 13:11:10.179  1926  6345 I qtaguid : Tagging socket 67 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1926, getuid(): 10012
,09-12 13:11:10.219  1013  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-12 13:11:10.229  1926  6345 I qtaguid : Tagging socket 72 with tag 1000310500000000{268448005,0} for uid 10012, pid: 1926, getuid(): 10012
,09-12 13:11:10.469  1926  6345 I qtaguid : Untagging socket 67
,09-12 13:11:10.499  1013  1670 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:11:10.499  1013  1670 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.clearcut.uploader.UploaderService; callingUser = 0; userId(target) = 0
,09-12 13:11:10.499  1013  1670 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:10.499  1013  1670 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:10.499  1013  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:10.529  1926  2110 W ctxmgr  : [AccountAclCallback]Failed Acl fetch for account account#61035162# with status: UNKNOWN).  Giving up.
,09-12 13:11:10.579  1013  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:10.579  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:10.579  1013  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:10.579  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:10.609  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:10.609  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:10.609  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:10.609  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:10.659  1013  1796 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:10.659  1013  1796 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:10.659  1013  1796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:10.659  1013  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:10.659  1926  6350 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-12 13:11:10.659  1926  6348 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-12 13:11:10.659  1013  3010 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:10.659  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:10.659  1013  3010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:10.659  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:10.689  1013  1379 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:10.689  1013  1379 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:10.689  1013  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:10.689  1013  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:10.689  1926  6350 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-12 13:11:10.689  1926  6348 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-12 13:11:10.689  1013  1670 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:10.689  1013  1670 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:10.689  1013  1670 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:10.689  1013  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:10.719  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:10.719  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:10.719  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:10.719  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:10.719  1926  6350 E CommitToConfigurationOperation: Malformed snapshot token (size): 
,09-12 13:11:10.719  1926  6348 W PhenotypeFlagCommitter: Committing snapshot for com.google.android.gms.playlog.uploader failed, retrying
,09-12 13:11:10.719  1926  6348 W PhenotypeFlagCommitter: No more attempts remaining, giving up for com.google.android.gms.playlog.uploader
,09-12 13:11:10.739  1926  6348 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,09-12 13:11:10.789  1013  4556 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-12 13:11:10.819  1926  6348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:11:10.829   277  1007 D EnterpriseController: uids 10012
09-12 13:11:10.829   277  1007 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 13:11:10.829   277  1007 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,09-12 13:11:10.829  1926  6348 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 13:11:10.829  1926  6348 I qtaguid : Tagging socket 81 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1926, getuid(): 10012
,09-12 13:11:10.879  1926  6348 I qtaguid : Tagging socket 84 with tag 11065c0800000000{285629448,0} for uid -1, pid: 1926, getuid(): 10012
,09-12 13:11:11.049   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:11:11.109  1013  1471 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-12 13:11:11.119  1926  6348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:11:11.119  1926  6348 I qtaguid : Tagging socket 81 with tag 11065fff00000000{285630463,0} for uid -1, pid: 1926, getuid(): 10012
,09-12 13:11:11.269  1013  1473 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,09-12 13:11:11.279  1926  6348 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:11:11.279  1926  6348 I qtaguid : Tagging socket 81 with tag fffffb1f00000000{4294966047,0} for uid -1, pid: 1926, getuid(): 10012
,09-12 13:11:11.909  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native,
09-12 13:11:11.909  6226  6276 I jxcore-log: 
,09-12 13:11:11.909  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native,
09-12 13:11:11.909  6226  6276 I jxcore-log: 
,09-12 13:11:11.919  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:11.919  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:11.919  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
,09-12 13:11:11.919  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:11.919  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:11.919  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:11.919  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:11.919  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:11.919  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e,
,09-12 13:11:11.919  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native,
09-12 13:11:11.919  6226  6276 I jxcore-log: 
,09-12 13:11:11.919  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native,
09-12 13:11:11.919  6226  6276 I jxcore-log: 
,09-12 13:11:12.049   287   287 E SMD     : DCD OFF
09-12 13:11:12.059   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:11:12.269  1926  6342 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:11:12.269  1926  6342 I qtaguid : Tagging socket 67 with tag 1000310200000000{268448002,0} for uid 10012, pid: 1926, getuid(): 10012
,09-12 13:11:12.449  1926  6342 I qtaguid : Untagging socket 67
,09-12 13:11:12.449  1926  2110 E ctxmgr  : [GcmSyncStatisticsImpl]Context recd stats incorrect mode 0
,09-12 13:11:12.469  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.udc.service.UdcContextListenerService; callingUser = 0; userId(target) = 0
,09-12 13:11:12.589  6226  6276 D executeNativeTests: Running unit tests
,09-12 13:11:12.669  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:12.669  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 added. We now have 2 listener(s)
,09-12 13:11:12.679  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:11:12.679  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:12.679  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:12.679  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:12.679  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 added. We now have 2 listener(s)
09-12 13:11:12.679  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:12.679  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-12 13:11:12.679  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:12.679  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:12.679  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:12.679  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:12.679  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:12.679  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:12.679  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:12.679  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:12.679  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:11:12.679  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:12.679  6226  6276 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:11:12.689  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:12.689  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:11:12.689  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:11:12.689  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:11:12.689  6226  6276 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-12 13:11:12.689  6226  6276 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:11:12.689  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:11:12.689  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:11:12.689  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:11:12.689  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:12.689  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:12.689  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:12.689  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:12.689  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.689  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:12.689  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:12.689  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 removed from the list
09-12 13:11:12.689  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:12.689  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 removed from the list
09-12 13:11:12.689  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:12.689  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:12.689  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:12.699  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.699  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:12.699  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:12.699  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:12.699  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:12.699  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:12.699  6226  6276 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-12 13:11:12.699  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:12.699  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:12.699  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:12.699  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:12.699  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.699  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:12.699  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:12.699  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:12.699  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:12.699  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:12.699  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.699  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:12.699  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.699  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:12.699  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:12.699  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:12.699  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:12.699  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:11:12.709  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:12.709  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:12.709  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:12.709  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:12.709  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.709  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:12.709  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:12.709  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:12.709  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:12.709  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:12.709  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.709  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:12.709  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.709  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:12.709  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:12.709  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:12.709  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:12.709  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:12.709  6226  6276 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-12 13:11:12.709  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:12.719  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:12.719  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:12.719  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:12.719  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:12.719  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:12.719  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:12.719  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:12.719  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-12 13:11:12.719  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:12.719  6226  6276 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:11:12.719  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:12.719  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:11:12.719  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:11:12.719  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:12.719  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:11:12.719  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:12.719  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-12 13:11:12.729  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:12.729  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-12 13:11:12.729  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-12 13:11:12.739  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
09-12 13:11:12.739  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
09-12 13:11:12.739  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:11:12.739  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:11:12.739  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-12 13:11:12.749  2648  3003 D BtGatt.GattService: registerClient() - UUID=59428cb2-15eb-45f7-8abc-15af51d9656c
,09-12 13:11:12.799  2648  2713 D BtGatt.GattService: onClientRegistered() - UUID=59428cb2-15eb-45f7-8abc-15af51d9656c, clientIf=6
,09-12 13:11:12.799  6226  6234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 13:11:12.799  2648  2989 D BtGatt.GattService: start scan with filters
,09-12 13:11:12.799  2648  2721 D BtGatt.ScanManager: handling starting scan
,09-12 13:11:12.799  2648  2721 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1906152d
,09-12 13:11:12.809  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:11:12.809  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:11:12.809  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:11:12.809  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:11:12.809  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:12.809  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:12.809  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:11:12.809  2648  2713 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 13:11:12.819  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:12.819  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:11:12.819  2648  2721 D BtGatt.ScanManager: allow scan with filters
09-12 13:11:12.819  2648  2721 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 13:11:12.819  2648  2721 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
,09-12 13:11:12.819  6226  6276 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:11:12.819  2648  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 13:11:12.829  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:12.829  2648  2721 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:11:12.829  2648  2721 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 13:11:12.829  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:11:12.829  6226  6276 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:11:12.829  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:12.829  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:11:12.829  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.829  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:12.829  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:11:12.829  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:11:12.829  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:11:12.829  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:11:12.829  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:11:12.829  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:11:12.829  2648  2666 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:11:12.829  2648  3003 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:11:12.839  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:11:12.839  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:11:12.839  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:11:12.839  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:11:12.839  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:11:12.849  2648  2713 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 13:11:12.849  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:12.849  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:12.849  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:11:12.849  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:11:12.849  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:11:12.849  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:12.849  2648  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 13:11:12.849  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:12.859  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:12.859  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:12.859  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:12.859  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:12.859  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.859  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:12.859  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:12.859  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:12.859  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:12.859  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:12.859  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:12.859  6226  6276 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:11:12.869  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:12.869  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:12.869  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:12.869  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:12.869  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:12.869  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:12.869  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:12.869  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:12.869  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:12.869  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:12.869  6226  6276 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:12.869  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:12.869  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:11:12.869  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:11:12.879  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:12.879  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:11:12.879  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:12.879  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:12.879  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:11:12.889  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:11:12.889  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:11:12.889  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:11:12.889  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 13:11:12.889  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:11:12.899  2648  3003 D BtGatt.GattService: registerClient() - UUID=a7dcb717-879b-45a8-9fb7-7b728bbe4ed8
,09-12 13:11:12.899  2648  2721 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 28
,09-12 13:11:12.899  2648  2721 D BtGatt.ScanManager: filter size is 1
,09-12 13:11:12.899  2648  2721 D BtGatt.ScanManager: delete FilterIndex - 3
,09-12 13:11:12.909  2648  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 13:11:12.909  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:12.909  2648  2721 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:11:12.919  2648  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 13:11:12.919  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:12.919  2648  2721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:11:12.919  2648  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 13:11:12.919  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:12.939  2648  2713 D BtGatt.GattService: onClientRegistered() - UUID=a7dcb717-879b-45a8-9fb7-7b728bbe4ed8, clientIf=6
,09-12 13:11:12.939  6226  6235 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 13:11:12.939  2648  2989 D BtGatt.GattService: start scan with filters
,09-12 13:11:12.939  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:11:12.939  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:11:12.939  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:11:12.939  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:11:12.949  2648  2721 D BtGatt.ScanManager: handling starting scan,
09-12 13:11:12.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:11:12.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:11:12.949  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:12.949  2648  2713 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 13:11:12.949  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:12.949  2648  2721 D BtGatt.ScanManager: allow scan with filters
,09-12 13:11:12.949  2648  2721 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 13:11:12.949  2648  2721 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-12 13:11:12.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
,09-12 13:11:12.959  2648  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 13:11:12.959  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:12.959  2648  2721 D BtGatt.ScanManager: Starting BLE batch scan
09-12 13:11:12.959  2648  2721 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 13:11:12.959  6226  6276 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:11:12.959  2648  2713 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 13:11:12.959  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:12.959  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:12.969  6226  6276 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:11:12.969  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:12.969  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:11:12.969  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.969  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:12.969  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:11:12.969  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:11:12.969  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:11:12.969  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:11:12.969  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:11:12.969  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:11:12.969  2648  2666 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:11:12.969  2648  3003 D BtGatt.GattService: unregisterClient() - clientIf=6
09-12 13:11:12.969  2648  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 13:11:12.969  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:12.969  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:11:12.969  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:11:12.969  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 13:11:12.969  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:11:12.969  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
09-12 13:11:12.969  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:12.969  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:11:12.969  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:11:12.969  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:11:12.979  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:12.979  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:12.979  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:12.979  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.979  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:12.979  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:12.979  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:12.979  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:12.979  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:12.979  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:12.979  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:12.979  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:12.979  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:12.979  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:12.989  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:12.989  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:12.989  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:12.989  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
,09-12 13:11:12.989  6226  6276 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-12 13:11:12.989  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:12.989  2648  2721 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 29
,09-12 13:11:12.989  2648  2721 D BtGatt.ScanManager: filter size is 1
,09-12 13:11:12.989  2648  2721 D BtGatt.ScanManager: delete FilterIndex - 4
,09-12 13:11:12.999  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:12.999  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:12.999  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:12.999  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:12.999  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:12.999  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:12.999  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:12.999  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:12.999  2648  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 13:11:12.999  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:12.999  2648  2721 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:11:12.999  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:12.999  6226  6276 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:13.009  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:13.009  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:11:13.009  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:11:13.009  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:13.009  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:11:13.009  2648  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
09-12 13:11:13.009  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:13.009  2648  2721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:11:13.009  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 13:11:13.009  2648  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 13:11:13.009  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
,09-12 13:11:13.009  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:13.009  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:11:13.019  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:11:13.019  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:11:13.019  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:11:13.019  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,09-12 13:11:13.029  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:11:13.029  2648  2666 D BtGatt.GattService: registerClient() - UUID=b2baf58a-a038-479e-912d-bff518348b08
,09-12 13:11:13.059   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:11:13.069  2648  2713 D BtGatt.GattService: onClientRegistered() - UUID=b2baf58a-a038-479e-912d-bff518348b08, clientIf=6
,09-12 13:11:13.069  6226  6235 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 13:11:13.069  2648  3003 D BtGatt.GattService: start scan with filters
,09-12 13:11:13.069  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-12 13:11:13.069  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-12 13:11:13.069  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:11:13.069  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:11:13.079  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:13.079  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:13.079  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:11:13.079  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:11:13.079  2648  2721 D BtGatt.ScanManager: handling starting scan
,09-12 13:11:13.089  6226  6276 I io.jxcore.node.ConnectionHelper: start: OK
,09-12 13:11:13.089  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:11:13.089  6226  6276 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-12 13:11:13.089  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.089  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-12 13:11:13.089  2648  2713 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 13:11:13.089  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:13.089  2648  2721 D BtGatt.ScanManager: allow scan with filters
,09-12 13:11:13.089  2648  2721 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 13:11:13.099  2648  2721 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
09-12 13:11:13.099  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-12 13:11:13.099  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:13.099  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-12 13:11:13.099  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:11:13.099  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart,
09-12 13:11:13.099  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:11:13.099  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:11:13.099  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...,
09-12 13:11:13.099  2648  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 13:11:13.099  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:13.099  2648  2721 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:11:13.099  2648  2721 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-12 13:11:13.099  2648  2666 D BtGatt.GattService: stopScan() - queue size =1
09-12 13:11:13.099  2648  2713 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 13:11:13.099  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:13.099  2648  3003 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:11:13.099  2648  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 13:11:13.099  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:13.099  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-12 13:11:13.099  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:11:13.099  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:11:13.099  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:11:13.099  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:11:13.109  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:13.109  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:11:13.109  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:11:13.109  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:11:13.109  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:13.109  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-12 13:11:13.109  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.109  6226  6276 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:11:13.109  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.109  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.109  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.109  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.109  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:13.109  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.109  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.109  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.109  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.109  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.109  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.109  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.109  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:13.109  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:13.109  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:13.109  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.109  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.109  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
,09-12 13:11:13.109  6226  6276 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-12 13:11:13.109  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.119  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.119  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.119  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.119  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.119  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.119  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.119  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.119  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.119  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.119  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.119  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.119  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.119  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.119  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:13.119  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.119  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.119  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.119  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-12 13:11:13.119  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.119  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.119  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.119  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.119  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.119  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.119  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.119  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.119  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.119  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.119  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.119  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.119  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.119  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.119  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:13.119  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:13.119  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.119  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
,09-12 13:11:13.119  2648  2721 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 30
,09-12 13:11:13.119  6226  6276 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,09-12 13:11:13.129  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.129  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.129  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.129  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.129  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.129  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.129  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.129  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.129  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.129  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.129  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.129  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.129  2648  2721 D BtGatt.ScanManager: filter size is 1
09-12 13:11:13.129  2648  2721 D BtGatt.ScanManager: delete FilterIndex - 5
,09-12 13:11:13.129  2648  2713 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 13:11:13.129  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:13.129  2648  2721 D BtGatt.ScanManager: stopping BLe Batch
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.129  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
,09-12 13:11:13.129  6226  6276 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-12 13:11:13.129  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.129  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.129  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.129  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.129  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.129  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.129  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.129  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.129  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.129  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.129  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.129  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.129  2648  2713 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0,
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:13.129  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.129  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-12 13:11:13.129  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:11:13.129  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-12 13:11:13.129  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-12 13:11:13.129  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.129  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
09-12 13:11:13.129  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.129  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.129  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.129  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.129  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.129  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.129  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.129  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.129  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.129  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.129  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.129  2648  2721 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
09-12 13:11:13.139  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:13.139  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:13.139  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.139  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.139  6226  6276 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:11:13.139  6226  6276 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,09-12 13:11:13.139  2648  2713 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 13:11:13.139  2648  2713 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:13.139  6226  6276 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:11:13.139  6226  6276 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2,410:2410:2410:2410:2410]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-12 13:11:13.139  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-12 13:11:13.139  6226  6276 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-12 13:11:13.139  6226  6276 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:11:13.139  6226  6276 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-12 13:11:13.139  6226  6276 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-12 13:11:13.139  6226  6276 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:11:13.139  6226  6276 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-12 13:11:13.139  6226  6276 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:11:13.139  6226  6276 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-12 13:11:13.139  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,09-12 13:11:13.149  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,09-12 13:11:13.149  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-12 13:11:13.149  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
09-12 13:11:13.149  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-12 13:11:13.149  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-12 13:11:13.149  6226  6276 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-12 13:11:13.149  6226  6276 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-12 13:11:13.149  6226  6276 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-12 13:11:13.149  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.149  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.149  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.149  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.149  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.149  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.149  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-12 13:11:13.149  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.149  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.149  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.149  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.149  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.149  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.149  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.149  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.149  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:13.149  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.149  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.149  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.149  6226  6359 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1142)
09-12 13:11:13.149  6226  6276 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-12 13:11:13.159  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:11:13.159  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.159  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.159  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.159  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.159  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
,09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:13.159  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.159  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.159  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.159  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.159  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.159  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.159  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.159  6226  6360 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1142
,09-12 13:11:13.159  6226  6276 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-12 13:11:13.159  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.159  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:11:13.159  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.159  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.159  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.159  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.159  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.159  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.159  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.159  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.159  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.159  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 13:11:13.159  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.159  6226  6276 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-12 13:11:13.159  6226  6276 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-12 13:11:13.159  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:11:13.159  6226  6276 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-12 13:11:13.159  6226  6276 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:11:13.159  6226  6276 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-12 13:11:13.159  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 13:11:13.159  6226  6276 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-12 13:11:13.159  6226  6276 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-12 13:11:13.159  6226  6276 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-12 13:11:13.159  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-12 13:11:13.159  6226  6276 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-12 13:11:13.159  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.159  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.159  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-12 13:11:13.159  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.159  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.159  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.159  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.159  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.159  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.159  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.159  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.159  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.159  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
,09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.169  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.169  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.169  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.169  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.169  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.169  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.169  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
,09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.169  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.169  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.169  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.169  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:11:13.169  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.169  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.169  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.169  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.169  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.169  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.169  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.169  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.169  6226  6359 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:13.169  6226  6359 D BluetoothSocket: connect(): myUserId = 0
09-12 13:11:13.169  6226  6359 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:11:13.169  6226  6226 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-12 13:11:13.169  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.169  6226  6226 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.169  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:11:13.169  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.169  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.169  2648  3003 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:13.179  6226  6361 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-12 13:11:13.179  6226  6361 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-12 13:11:13.179  6226  6359 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
,09-12 13:11:13.179  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:13.179  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.179  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.179  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.179  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.179  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:13.179  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.179  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.179  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:13.179  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.179  6226  6226 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-12 13:11:13.179  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.179  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.179  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.179  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:13.179  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.179  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.179  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.179  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
,09-12 13:11:13.179  6226  6276 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,09-12 13:11:13.179  6226  6276 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-12 13:11:13.179  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
09-12 13:11:13.179  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.179  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.179  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.179  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.179  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.179  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.179  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.179  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.179  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.179  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.179  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.179  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.179  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
,09-12 13:11:13.179  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:13.179  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.179  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.179  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.179  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.179  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
09-12 13:11:13.179  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.179  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.179  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.179  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.179  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.189  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.189  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:13.189  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
09-12 13:11:13.189  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.189  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:13.189  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.189  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
09-12 13:11:13.189  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:13.189  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:13.189  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:13.189  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.189  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.189  6226  6276 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2c8e09d1 not in the list
,09-12 13:11:13.189  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.189  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:13.189  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.189  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.189  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:13.189  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:13.189  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:13.189  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:13.189  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:13.189  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@281e0c36 not in the list
09-12 13:11:13.189  6226  6276 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:11:13.189  6226  6276 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-12 13:11:13.189  6226  6276 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-12 13:11:13.189  6226  6276 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:11:13.189  6226  6276 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-12 13:11:13.189  6226  6276 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-12 13:11:13.189  6226  6276 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-12 13:11:13.199  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:13.199  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2596f828 added. We now have 2 listener(s)
09-12 13:11:13.199  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:13.199  6226  6276 D BluetoothAdapter: enable()
,09-12 13:11:13.199  6226  6276 D BluetoothAdapter: enable(): BT is already enabled..!
,09-12 13:11:13.199  1013  3010 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 13:11:13.199  1013  3010 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:11:13.199  1013  3010 D SecContentProvider2: mCursor = null
,09-12 13:11:13.199  1013  3010 D WifiService: setWifiEnabled: true pid=6226, uid=10155
09-12 13:11:13.199  1013  3010 W ActivityManager: Permission Denial: getCurrentUser() from pid=6226, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:11:13.199  1013  3010 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:11:13.199  1013  3010 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6226, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:11:13.199  1013  3010 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 13:11:13.199  1013  3010 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:11:13.199  1013  3010 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:11:13.199  1013  3010 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:11:13.199  1013  3010 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:11:13.199  1013  3010 D SettingsProvider: name = wifi_on
,09-12 13:11:13.199  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-12 13:11:13.199  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17d40941 added. We now have 3 listener(s)
09-12 13:11:13.199  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:13.209  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:13.209  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@295feee6 added. We now have 4 listener(s)
09-12 13:11:13.209  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:13.209  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:13.209  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@486fc27 added. We now have 5 listener(s)
09-12 13:11:13.209  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:13.209  1013  1026 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 13:11:13.209  1013  1026 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:11:13.209  1013  1026 D SecContentProvider2: mCursor = null
,09-12 13:11:13.209  1013  1026 D WifiService: setWifiEnabled: false pid=6226, uid=10155
09-12 13:11:13.209  1013  1026 D SettingsProvider: name = wifi_on
,09-12 13:11:13.219  1013  1125 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-12 13:11:13.219  2144  2144 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 13:11:13.219  2144  2144 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
09-12 13:11:13.219  2144  2144 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 13:11:13.219  2144  2144 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,09-12 13:11:13.219  6226  6276 D BluetoothAdapter: disable()
,09-12 13:11:13.229  1013  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:11:13.229  1013  1379 D SettingsProvider: name = bluetooth_on
,09-12 13:11:13.239  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:13.239  2648  2709 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
09-12 13:11:13.239  2648  2709 D BluetoothAdapterProperties: Setting state to 13
09-12 13:11:13.239  2648  2709 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 13:11:13.239  2648  2709 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:11:13.239  2648  2709 D BluetoothAdapterService: updateAdapterState state is 13
,09-12 13:11:13.239  1013  4555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:13.239  1013  4555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.239  1013  4555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:13.239  1013  4555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:13.239  1013  4555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:13.239  2648  2648 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-12 13:11:13.239  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10871917, channel: 19, state: LISTENING
09-12 13:11:13.239  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10871917, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@65ba51f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31f4e104mSocket: android.net.LocalSocket@2eeb36ed impl:android.net.LocalSocketImpl@d30c922 fd:FileDescriptor[74]
09-12 13:11:13.239  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2eeb36ed impl:android.net.LocalSocketImpl@d30c922 fd:FileDescriptor[74]
,09-12 13:11:13.239  2648  2709 D BluetoothAdapterService: Autoconnection is available 
09-12 13:11:13.239  2648  2709 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
09-12 13:11:13.239  2648  2709 D BluetoothAdapterService: terminating service from this receiver
09-12 13:11:13.239  1013  1125 E WifiNative-wlan0: do suspend true
,09-12 13:11:13.249  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:13.249  1013  1013 I InputMethodManagerService: [BT Setting State] State =13
,09-12 13:11:13.249  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:13.249  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:13.249  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:13.249  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:13.249  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:13.249  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:13.249  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:13.249  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:13.249  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:13.249  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,09-12 13:11:13.259  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:13.259  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:13.259  6226  6276 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:13.259  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 13:11:13.259  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:13.259  1176  1176 D BluetoothTile:  getBluetoothState : 13
,09-12 13:11:13.259  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:13.259  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:11:13.259  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:11:13.259  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:13.259  1013  3001 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:11:13.259  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 13:11:13.269  1013  1218 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-12 13:11:13.269  1770  1770 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:11:13.269  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:13.269  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:13.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:13.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:13.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:13.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:13.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-12 13:11:13.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-12 13:11:13.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-12 13:11:13.269  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:13.269  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-12 13:11:13.269  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:11:13.279  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.279  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:13.279  1013  3152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:13.279  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:11:13.279  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:13.279  1359  1359 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:13.279  2648  2709 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 13:11:13.279  2648  2709 D BluetoothAdapterProperties: mDiscovering is false
,09-12 13:11:13.279  1013  1796 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
09-12 13:11:13.279  1013  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:13.279  1013  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.279  2648  2709 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-12 13:11:13.279  1013  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:13.279  1013  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:13.279  1013  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:13.299  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:13.299  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d5a2fb3, channel: 5, state: LISTENING
,09-12 13:11:13.299  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d5a2fb3, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@364ef06c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@21610970mSocket: android.net.LocalSocket@3d154e9 impl:android.net.LocalSocketImpl@3d36556e fd:FileDescriptor[76]
09-12 13:11:13.299  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d154e9 impl:android.net.LocalSocketImpl@3d36556e fd:FileDescriptor[76]
,09-12 13:11:13.299  2648  2648 I BtOppRfcommListener: stopping Accept Thread
09-12 13:11:13.299  2648  2648 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1f3e140f, channel: 12, state: LISTENING
09-12 13:11:13.299  2648  2648 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1f3e140f, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@96ba996, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a254c9cmSocket: android.net.LocalSocket@be156a5 impl:android.net.LocalSocketImpl@1ff65a7a fd:FileDescriptor[80]
09-12 13:11:13.299  2648  2648 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@be156a5 impl:android.net.LocalSocketImpl@1ff65a7a fd:FileDescriptor[80]
,09-12 13:11:13.299  2648  5011 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-12 13:11:13.299  2648  5011 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 13:11:13.299  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:13.299  2648  2648 V BluetoothOppManager: cleanUp...
,09-12 13:11:13.309  2648  2713 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:11:13.309  2648  2713 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:11:13.309  2648  2709 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-12 13:11:13.309  1359  1359 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:11:13.309  2648  2709 E bt-btif : HAL bt_hal_cbacks->log_collector_cb
,09-12 13:11:13.309  1013  1379 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 13:11:13.309  2648  2709 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
09-12 13:11:13.309  1013  1379 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.309  2648  2709 E bt-btif : cmd socket is not created
,09-12 13:11:13.309  2648  2709 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,09-12 13:11:13.309  2648  2798 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,09-12 13:11:13.309  2648  2798 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,09-12 13:11:13.309  2648  2798 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:11:13.309  2648  2798 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:11:13.309  2648  2798 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 13:11:13.309  1013  1379 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:13.309  1013  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:13.319  1013  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:11:13.319  6226  6359 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@196f87d, channel: -1, state: INIT
09-12 13:11:13.319  6226  6359 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@196f87d, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1aac1372, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@55d33c3mSocket: android.net.LocalSocket@3a46a440 impl:android.net.LocalSocketImpl@1f9f9f79 fd:FileDescriptor[109]
09-12 13:11:13.319  6226  6359 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3a46a440 impl:android.net.LocalSocketImpl@1f9f9f79 fd:FileDescriptor[109]
,09-12 13:11:13.319  6226  6359 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1142)
,09-12 13:11:13.319  1359  1359 D BluetoothPbap: Proxy object disconnected
09-12 13:11:13.319  1359  1359 D PbapServerProfile: Bluetooth service disconnected
,09-12 13:11:13.329  1359  1359 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:11:13.329  1359  1359 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:11:13.339  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:13.339  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-12 13:11:13.339  1013  1473 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-12 13:11:13.339  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:13.339  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:13.339  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:13.339  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:13.349  6369  6369 E Zygote  : MountEmulatedStorage()
09-12 13:11:13.349  6369  6369 E Zygote  : v2
09-12 13:11:13.349  6369  6369 I libpersona: KNOX_SDCARD checking this for 10003
09-12 13:11:13.349  6369  6369 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:13.359  6369  6369 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:13.359  1013  1473 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=6369 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
,09-12 13:11:13.359  6369  6369 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:11:13.359  6369  6369 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:13.379  6369  6369 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:11:13.379  6369  6369 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:13.389  1013  1137 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 13:11:13.389  1013  1137 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4148, temperature: 294, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-12 13:11:13.389  1013  1137 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-12 13:11:13.389  1013  1137 D BatteryService: stay LED for charging
09-12 13:11:13.389  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:11:13.389  1013  1013 I MotionRecognitionService: Plugged
,09-12 13:11:13.399  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 13:11:13.399  2144  2144 I wpa_supplicant: nl80211: Received scan results (14 BSSes)
,09-12 13:11:13.399  1013  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-12 13:11:13.399  1013  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 13:11:13.399  1013  1124 D WifiP2pService: InactiveState{ what=147461 }
09-12 13:11:13.399  1013  1124 D WifiP2pService: P2pEnabledState{ what=147461 }
,09-12 13:11:13.399  1013  1124 D WifiP2pService: DefaultState{ what=147461 }
,09-12 13:11:13.399  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-12 13:11:13.399  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:11:13.399  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
09-12 13:11:13.409  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
,09-12 13:11:13.409  2648  2648 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 13:11:13.409  2648  2722 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:11:13.419  6369  6369 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,09-12 13:11:13.419   277  1011 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:11:13.419  1926  4544 V NativeCrypto: Read error: ssl=0xb7ff5a70: I/O error during system call, Connection timed out
,09-12 13:11:13.419  1926  4544 V NativeCrypto: SSL shutdown failed: ssl=0xb7ff5a70: I/O error during system call, Broken pipe
,09-12 13:11:13.429  1013  1131 E ConnectivityService: updateNetworkInfo()
09-12 13:11:13.429  1013  1131 E ConnectivityService: updateNetworkInfo()
09-12 13:11:13.429  1013  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:11:13.429  1013  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
09-12 13:11:13.429  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,09-12 13:11:13.429  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
09-12 13:11:13.429  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,09-12 13:11:13.429  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:13.429  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 13:11:13.429  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.429  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.429  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.429  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:13.429  1926  4544 E GCM     : Wifi connection closed with errorCode 20
,09-12 13:11:13.429  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:11:13.429  1013  1670 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10012
,09-12 13:11:13.439  1013  2272 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:13.439  1013  2272 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10012 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:13.439  1013  2272 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-12 13:11:13.439  1013  2272 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:11:13.439  1013  2272 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
,09-12 13:11:13.439  1013  2272 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
09-12 13:11:13.439  1013  2272 I qtaguid : Tagging socket 361 with tag ffffffff00000000{4294967295,0} for uid 10012, pid: 1013, getuid(): 1000
,09-12 13:11:13.449  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 13:11:13.449  1013  1124 D WifiP2pService: InactiveState{ what=131204 }
,09-12 13:11:13.449  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:13.449  1013  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 13:11:13.449  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.449  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:13.449  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.449  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.449  1013  2272 I qtaguid : Untagging socket 361
09-12 13:11:13.449  1013  2272 I System.out: (HTTPLog)-Static: isSBSettingEnabled false,
,09-12 13:11:13.449  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 13:11:13.449  1013  1148 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:13.449  1013  1013 D RttService: SCAN_AVAILABLE : 1
09-12 13:11:13.449  1013  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
09-12 13:11:13.449  1013  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:11:13.449  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:11:13.459  1013  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 13:11:13.449  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:11:13.459  6369  6369 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
09-12 13:11:13.459  6369  6369 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-12 13:11:13.459  6369  6369 D UserAnalysis: Create SecureDbHelper
,09-12 13:11:13.469  6369  6369 D IntelligenceServiceApplication: onCreate()
09-12 13:11:13.469  1013  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-12 13:11:13.469  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-12 13:11:13.469  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:11:13.469  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 13:11:13.469  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-12 13:11:13.469  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:11:13.469  1013  1043 D WifiDisplayController: disconnect
,09-12 13:11:13.469  1013  1043 D WifiDisplayController: updateConnection,
09-12 13:11:13.469  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:11:13.469  1013  1125 E WifiNative-wlan0: do suspend true
09-12 13:11:13.469  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:11:13.469  1013  1124 D WifiP2pService: P2pDisablingState
09-12 13:11:13.469  1013  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-12 13:11:13.469  1013  1124 D WifiP2pService: p2p socket connection lost
09-12 13:11:13.469  1013  1124 D WifiP2pService: P2pDisabledState
,09-12 13:11:13.469  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
09-12 13:11:13.469  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:11:13.469  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:11:13.469  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 13:11:13.479  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,09-12 13:11:13.479  1013  1025 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:11:13.479  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 13:11:13.479  6369  6369 D IntelligenceServiceApplication: no applications having user consent for prediction
,09-12 13:11:13.479  1013  1670 I ActivityManager: Killing 5392:com.dropbox.android/u0a92 (adj 15): empty #31
,09-12 13:11:13.489  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
,09-12 13:11:13.489  6369  6369 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,09-12 13:11:13.489  1013  1471 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,09-12 13:11:13.489  1013  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:13.489  1013  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:13.489  1013  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:13.489  1013  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:13.499  6369  6369 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,09-12 13:11:13.509  6391  6391 E Zygote  : MountEmulatedStorage(),
09-12 13:11:13.509  6391  6391 E Zygote  : v2
,09-12 13:11:13.509  6391  6391 I libpersona: KNOX_SDCARD checking this for 10107
09-12 13:11:13.509  6391  6391 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:13.509  6391  6391 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:11:13.509  1013  1471 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=6391 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,09-12 13:11:13.509  2648  2798 W bt-l2cap: btif_mce_execute_service enable:0
09-12 13:11:13.509  2648  2798 W bt-l2cap: HC lib lpm enable=0 not found for deregistration
09-12 13:11:13.509  2648  2798 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:11:13.509  2648  2798 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration,
09-12 13:11:13.509  2648  2798 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:11:13.509  2648  2798 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:11:13.509  2648  2798 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:11:13.509  2648  2798 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:11:13.509  2648  2798 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:11:13.509  2648  2798 W bt-btif : ag scb idx 1 not allocated
09-12 13:11:13.509  2648  2798 W bt-btif : ag scb idx 2 not allocated
,09-12 13:11:13.509  2648  2798 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 13:11:13.509  2648  2896 I bt_userial_mct: exiting userial_read_thread
09-12 13:11:13.509  2648  2896 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 13:11:13.509  2648  2713 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 13:11:13.509  2648  2802 I bt_vendor: hw_epilog_process
09-12 13:11:13.509  2648  2713 D bt_userial_mct: userial_close
09-12 13:11:13.509  2648  2713 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-12 13:11:13.509  6391  6391 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:13.519  6391  6391 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,09-12 13:11:13.529  6391  6391 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:13.529  6391  6391 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:13.609  1013  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
,09-12 13:11:13.609  1013  1124 D WifiP2pService: DefaultState{ what=143375 }
,09-12 13:11:13.609  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:11:13.609  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:13.609  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:13.609  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:13.609  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.609  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:13.609   277  1007 D EnterpriseController: uids 1000,
09-12 13:11:13.609   277  1007 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 13:11:13.609   277  1007 D Netd    : getNetworkForDns: using netid 0 for uid 1000
09-12 13:11:13.609  1013  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-12 13:11:13.609  1013  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
09-12 13:11:13.619  1176  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 13:11:13.609  1013  1131 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 13:11:13.619  1013  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,fe80::7ef9:eff:fe37:96ac/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
09-12 13:11:13.619  1013  1131 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
09-12 13:11:13.619  1013  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-12 13:11:13.619   277  1011 D CommandListener: Clearing all IP addresses on wlan0
09-12 13:11:13.619  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 13:11:13.619  1452  1452 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,09-12 13:11:13.619  1013  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 13:11:13.619  1013  1013 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-12 13:11:13.619  1013  1122 V NetworkStats: updateIfacesLocked()
09-12 13:11:13.619  1013  1042 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-12 13:11:13.619  1013  1122 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:11:13.619  1013  1132 D Tethering: MasterInitialState.processMessage what=3
09-12 13:11:13.619  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:13.619  3855  6288 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-12 13:11:13.619  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:11:13.619  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:11:13.619  1013  2272 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname,
09-12 13:11:13.619  1013  2272 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-12 13:11:13.629  1013  1131 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:11:13.619  1013  2272 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-10ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: updateDataNetType()
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-12 13:11:13.629  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-12 13:11:13.629  1013  1131 D ConnectivityService: nai.networkMonitor.doQuit()
09-12 13:11:13.629  1013  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-12 13:11:13.629  1013  1042 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-12 13:11:13.629  1013  1131 E ConnectivityService: updateNetworkInfo()
09-12 13:11:13.629  1013  1131 E ConnectivityService: updateNetworkInfo()
,09-12 13:11:13.629  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:11:13.629  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:13.629  1013  1122 V NetworkStats: performPollLocked() took 10ms
09-12 13:11:13.629  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:13.629  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:13.629  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:13.629  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:13.629  1013  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-12 13:11:13.629  2144  2144 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:13.629  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.629  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:13.639  1013  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 13:11:13.639  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:11:13.639  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:13.639  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.639  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.639  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.639  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:13.639  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:13.639  1013  1125 D SecContentProvider2: mCursor = null
,09-12 13:11:13.639  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:13.639  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:13.649  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:13.649  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:11:13.649  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.649  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.649  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:13.649  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:13.649  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:13.649  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,09-12 13:11:13.649  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:11:13.649  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:11:13.649  1359  1359 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:13.649  1176  1176 D HotspotTile: onReceive : 0, 0
,09-12 13:11:13.659  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:13.659  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:13.659  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:13.659  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:13.659  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:13.659  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:13.659  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:13.659  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:13.659  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:13.659  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:13.659  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:13.669  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:13.669  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:13.669  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:13.669  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:13.669  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:13.669  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:13.669  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:13.669  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:13.669  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:13.669  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:13.669  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:13.679  6226  6226 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:11:13.709  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.719  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.719  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.719  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.719  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.719  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.719  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.719  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.729  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.729  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.729  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.729  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.729  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.729  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.729  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.729  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.729  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.739  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.739  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.739  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.739  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.739  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.739  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.739  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.739  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.739  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.739  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.749  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.749  1452  1452 D PhoneApp: PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,09-12 13:11:13.749  1452  1452 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,09-12 13:11:13.759  2648  2713 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-12 13:11:13.759  2648  2713 I bt_vendor: bluetooth satus is on
09-12 13:11:13.759  2648  2713 I bt_vendor: bt-vendor : resetting BT status
09-12 13:11:13.759  2648  2713 I bt_vendor: Starting hciattach daemon
09-12 13:11:13.759  2648  2713 I bt_vendor: try to set false
09-12 13:11:13.759  2144  2144 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:11:13.759  2648  2713 I bt_vendor: Starting hciattach daemon
09-12 13:11:13.759  2648  2713 I bt_vendor: try to set false
09-12 13:11:13.759  2648  2713 I bt_vendor: cleanup
,09-12 13:11:13.759  2648  2798 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,09-12 13:11:13.759  2648  2713 I GKI_LINUX: GKI_exit_task 0 done
,09-12 13:11:13.759  2648  2713 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-12 13:11:13.759  2648  2709 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
09-12 13:11:13.759  2648  2709 D BtConfig.SecureMode: isSecureModeOn:false
09-12 13:11:13.759  2648  2709 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
09-12 13:11:13.759  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-12 13:11:13.759  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 13:11:13.769  2648  2709 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 13:11:13.769  1013  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:13.769  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.769  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:13.769  1013  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:13.769  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:13.769  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 13:11:13.769  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 13:11:13.769  2648  2648 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:11:13.769  2648  2709 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 13:11:13.769  1013  3001 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:13.769  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.769  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:13.769  2648  2648 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:11:13.769  2648  2648 D BtGatt.GattService: stop()
09-12 13:11:13.769  1013  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:13.769  2648  2648 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 13:11:13.769  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:13.769  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 13:11:13.769  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,09-12 13:11:13.779  2648  2709 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 13:11:13.779  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:13.779  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.779  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1906152d
,09-12 13:11:13.779  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:13.779  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:13.779  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:13.779  2648  2648 D HeadsetService: Received stop request...Stopping profile...
,09-12 13:11:13.779  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-12 13:11:13.779  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-12 13:11:13.779  2648  2709 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 13:11:13.779  1013  3001 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:13.779  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.789  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:13.789  1013  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:13.789  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1906152d
,09-12 13:11:13.789  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:13.789  2144  2144 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-12 13:11:13.789  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
,09-12 13:11:13.789  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 1
09-12 13:11:13.789  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:11:13.789  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
09-12 13:11:13.789  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-12 13:11:13.789  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,09-12 13:11:13.789  1359  1359 D HeadsetProfile: Bluetooth service disconnected
09-12 13:11:13.789  2648  2709 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 13:11:13.799  1013  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:13.799  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.799  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:13.799  1013  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:13.799  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:13.799  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-12 13:11:13.799  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 13:11:13.799  1013  1379 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,09-12 13:11:13.799  2648  2709 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
09-12 13:11:13.799  1013  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,09-12 13:11:13.799  1013  1379 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:13.799  1013  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:13.799  1013  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-12 13:11:13.799  1013  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:13.799  1013  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.809  1013  1471 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:13.809  1013  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:13.809  1013  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:13.809  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
09-12 13:11:13.809  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:13.809  2648  2709 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:13.809  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:13.809  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.809  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:13.809  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:13.809  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:13.809  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-12 13:11:13.809  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 13:11:13.809  2144  2144 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
09-12 13:11:13.809  2648  2709 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
09-12 13:11:13.819  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:13.819  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:11:13.819  2144  2144 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-12 13:11:13.819  2144  2144 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-12 13:11:13.819  2144  2144 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-12 13:11:13.819  2144  2144 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-12 13:11:13.819  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:13.819  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:13.819  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:13.819  1013  1132 D Tethering: InitialState.processMessage what=4
09-12 13:11:13.819  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:13.819  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:13.819  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:11:13.819  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:13.819  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:13.819  1013  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
,09-12 13:11:13.819  2648  2709 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:13.819  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:13.819  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 13:11:13.819  2648  2709 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:13.819  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 13:11:13.819  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-12 13:11:13.819  2648  2709 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,09-12 13:11:13.819  2648  2709 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 13:11:13.819  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:11:13.819  2648  2709 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:11:13.819  1013  1132 E Tethering: No numeric data
,09-12 13:11:13.819  1013  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:11:13.819  1013  1132 D Tethering: clearTetheredNotification()
09-12 13:11:13.819  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:13.819  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:13.819  2648  2709 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 13:11:13.819  2648  2709 D BluetoothAdapterState: Stopping profile services that were post enabled
09-12 13:11:13.819  2648  2648 E BluetoothAdapterService(419829037): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,09-12 13:11:13.829  2648  2648 D A2dpService: Received stop request...Stopping profile...
,09-12 13:11:13.829  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:13.829  1013  1122 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:11:13.829  2648  2731 D A2dpStateMachine: Exit Disconnected: -1
,09-12 13:11:13.829  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-12 13:11:13.829  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:11:13.829  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:11:13.829  1176  1176 D HotspotTile: updateTetherState():false, false
,09-12 13:11:13.829  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1906152d
09-12 13:11:13.829  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:13.829  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:13.829  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:11:13.829  2648  2648 E BluetoothAdapterService(419829037): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
09-12 13:11:13.829  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:11:13.829  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 13:11:13.829  2648  2648 D HidService: Received stop request...Stopping profile...
09-12 13:11:13.829  2648  2648 D HidService: Stopping Bluetooth HidService
09-12 13:11:13.829  2648  2648 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 13:11:13.829  2648  2648 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-12 13:11:13.829  2648  2648 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 13:11:13.829  1013  1013 D BluetoothA2dp: Proxy object disconnected
09-12 13:11:13.839  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-12 13:11:13.839  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1906152d
,09-12 13:11:13.839  1013  1122 V NetworkStats: performPollLocked() took 9ms
09-12 13:11:13.839  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:13.839  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:13.839  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:13.839  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:13.839  2851  2851 D BluetoothA2dp: Proxy object disconnected
,09-12 13:11:13.839  1359  1359 D BluetoothA2dp: Proxy object disconnected
,09-12 13:11:13.839  1359  1359 D A2dpProfile: Bluetooth service disconnected
,09-12 13:11:13.839  1359  1359 D BluetoothInputDevice: Proxy object disconnected
09-12 13:11:13.839  1359  1359 D HidProfile: Bluetooth service disconnected
,09-12 13:11:13.839  6391  6391 D StrictMode: StrictMode policy violation; ~duration=261 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:11:13.839  6391  6391 D StrictMode: StrictMode policy violation; ~duration=254 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:11:13.839  6391  6391 D StrictMode: StrictMode policy violation; ~duration=173 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:6145)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:11:13.839  6391  6391 D StrictMode: StrictMode policy violation; ~duration=172 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:11:13.839  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:11:13.849  6391  6391 D StrictMode: StrictMode policy violation; ~duration=171 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:11:13.849  6391  6391 D StrictMode: StrictMode policy violation; ~duration=169 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:11:13.849  6391  6391 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.k.c(PG:1187)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.k.b(PG:14147)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.k.c(PG:583)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.v.a(PG:1206)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.y.a(PG:2233)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.e.b(PG:170)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.r.e.b(PG:13188)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:11:13.849  6391  6391 D StrictMode: StrictMode policy violation; ~duration=137 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.io.File.doAccess(File.java:283)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.io.File.exists(File.java:363)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:11:13.849  6391  6391 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-12 13:11:13.849  1013  3010 I ActivityManager: Killing 5366:com.google.android.talk/u0a104 (adj 15): empty #31
09-12 13:11:13.849  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:13.849  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:13.859  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-12 13:11:13.859  2648  2648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 13:11:13.859  2648  2648 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-12 13:11:13.859  2648  2648 D HealthService: Received stop request...Stopping profile...
09-12 13:11:13.859  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1906152d
09-12 13:11:13.869  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
09-12 13:11:13.869  2648  2648 D PanService: Received stop request...Stopping profile...
09-12 13:11:13.869  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1906152d
09-12 13:11:13.869   271   271 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb810b7c8
09-12 13:11:13.869   271   271 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: R/W request received
09-12 13:11:13.869   271   271 I rmt_storage: wakelock acquired: 1, error no: 42
09-12 13:11:13.869   271   327 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 Unblock worker thread (th_id: -1206863736)
09-12 13:11:13.879  1013  1026 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:13.879  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:11:13.879  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:11:13.879  1359  1359 D PanProfile: Bluetooth service disconnected
09-12 13:11:13.879  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:13.879  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:13.879  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:11:13.879  1013  1013 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:11:13.879  2648  2648 D BluetoothMapService: Received stop request...Stopping profile...
09-12 13:11:13.879  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1906152d
09-12 13:11:13.879  2648  2648 D SapService: Received stop request...Stopping profile...
09-12 13:11:13.879  1359  1359 D BluetoothMap: Proxy object disconnected
09-12 13:11:13.879  1359  1359 D MapProfile: Bluetooth service disconnected
09-12 13:11:13.879  3637  3637 I Hs20UtilService: Starting #8
09-12 13:11:13.879  3637  3674 I Hs20UtilService: Message received 5007
,09-12 13:11:13.889  2648  2648 D SapService: Stopping Bluetooth SapService
09-12 13:11:13.889  2648  2648 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1906152d
09-12 13:11:13.889  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:11:13.889  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 13:11:13.889  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 13:11:13.889  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:11:13.889  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:11:13.889  1359  1359 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:11:13.889  1359  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-12 13:11:13.889  1359  1359 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 13:11:13.889  1359  1359 D SapProfile: Bluetooth service disconnected
09-12 13:11:13.899  2648  2648 E BluetoothAdapterService(419829037): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-12 13:11:13.899  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:11:13.899  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 13:11:13.899  2648  2648 D BluetoothA2dp: Proxy object disconnected
09-12 13:11:13.899  2648  2648 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
09-12 13:11:13.899  2648  2734 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 13:11:13.899  2648  2648 I GKI_LINUX: GKI_exit_task 2 done
09-12 13:11:13.899  2648  2648 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
09-12 13:11:13.899  2648  2648 E BluetoothAdapterService(419829037): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-12 13:11:13.899  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:13.899  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:13.899  2648  2648 E BluetoothAdapterService(419829037): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 13:11:13.899  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:13.899  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:13.899  2648  2648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:11:13.899  2648  2648 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:11:13.899  2648  2648 E BluetoothAdapterService(419829037): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-12 13:11:13.899  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:13.899  2648  2648 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:13.899  2648  2648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-12 13:11:13.899  2648  2648 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-12 13:11:13.899  2648  2648 E BluetoothAdapterService(419829037): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-12 13:11:13.899  2648  2648 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 13:11:13.899  2648  2648 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
09-12 13:11:13.899  2648  2648 E BluetoothAdapterService(419829037): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-12 13:11:13.899  2648  2709 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
09-12 13:11:13.899  2648  2709 D BluetoothAdapterProperties: Setting state to 10
09-12 13:11:13.899  2648  2709 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 13:11:13.899  2648  2709 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:11:13.899  2648  2709 D BluetoothAdapterService: updateAdapterState state is 10
09-12 13:11:13.909  2648  2648 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 13:11:13.909  2648  2648 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
09-12 13:11:13.909  2648  2709 D BluetoothAdapterService: Autoconnection is available 
09-12 13:11:13.909  2648  2709 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 13:11:13.909  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:13.909  1013  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:13.909  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.talk
09-12 13:11:13.909  2648  2709 I BluetoothAdapterState: Entering OffState
09-12 13:11:13.909  1013  1473 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
09-12 13:11:13.919  1013  1473 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver}
09-12 13:11:13.919  1013  1473 W BroadcastQueue: android.os.TransactionTooLargeException
09-12 13:11:13.919  1013  1473 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 13:11:13.919  1013  1473 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 13:11:13.919  1013  1473 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-12 13:11:13.919  1013  1473 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-12 13:11:13.919  1013  1473 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-12 13:11:13.919  1013  1473 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-12 13:11:13.919  1013  1473 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-12 13:11:13.919  1013  1473 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-12 13:11:13.919  1013  1473 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:11:13.919  1013  1473 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
09-12 13:11:13.919  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:13.919  6391  6412 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
09-12 13:11:13.919  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:13.929  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:13.929  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:13.939   271   327 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Bytes written = 917504
09-12 13:11:13.939   271   327 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2: req_h=0xa msg_id=3: Send response: res=0 err=0
,09-12 13:11:13.939   271   327 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs2: clnt_h=0x2 About to block rmt_storage client thread (th_id: -1206863736) wakelock released: 1, error no: 0
09-12 13:11:13.939   271   327 I rmt_storage: 
09-12 13:11:13.939  6435  6435 I libpersona: KNOX_SDCARD checking this for 10104
09-12 13:11:13.939  6435  6435 E Zygote  : MountEmulatedStorage()
09-12 13:11:13.939  6435  6435 I libpersona: KNOX_SDCARD not a persona
09-12 13:11:13.939  6435  6435 E Zygote  : v2
09-12 13:11:13.939   271   271 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb810b7c8
09-12 13:11:13.939  6435  6435 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:13.939  1013  1473 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=6435 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,09-12 13:11:13.939  6435  6435 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:13.939  1013  4556 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:13.949  1013  4556 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:13.949  1013  4556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:13.949  1013  4556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,09-12 13:11:13.949  6435  6435 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 13:11:13.949  1452  1761 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:13.949  1452  1761 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:11:13.959  1176  1205 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:13.959  1176  1205 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:11:13.959  2851  2863 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:13.959  2851  2863 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:13.959  2648  3003 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:13.959  2648  3003 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:11:13.959  6226  6234 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:13.959  6226  6234 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:13.959  6226  6234 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
09-12 13:11:13.959  6226  6234 D BluetoothLeAdvertiser: Exit stop advertising
09-12 13:11:13.959  6226  6234 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-12 13:11:13.959  6226  6234 D BluetoothLeScanner: Exiting stopAllScan
09-12 13:11:13.959  1359  1368 D Bluetoothsap: onBluetoothStateChange: up=false
09-12 13:11:13.959  1359  1368 D Bluetoothsap: Unbinding service...
09-12 13:11:13.959  1442  1451 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:13.959  1442  1451 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:13.969  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:11:13.969  1359  1373 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:13.969  1359  1373 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:13.969  1428  1437 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:13.969  1428  1437 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:13.969  1359  1368 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 13:11:13.969  1926  2096 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:13.969  1926  2096 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:13.969  2144  2144 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:11:13.969  6435  6435 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:13.969  1359  1368 D BluetoothPbap: onBluetoothStateChange: up=false
09-12 13:11:13.969  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:13.969  1013  1042 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:13.969  1359  1373 D BluetoothA2dp: onBluetoothStateChange: up=false
09-12 13:11:13.969  6435  6435 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:13.969  2648  2989 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:11:13.979  1359  1368 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-12 13:11:13.979  1013  1037 W libprocessgroup: failed to open /acct/uid_10104/pid_5366/cgroup.procs: No such file or directory
09-12 13:11:13.979  2851  2859 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:11:13.979  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-12 13:11:13.979  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-12 13:11:13.979  6435  6435 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 13:11:13.989  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:13.989  1013  1013 I InputMethodManagerService: [BT Setting State] State =10
09-12 13:11:13.989  1013  1013 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 13:11:13.989  1176  1176 D BluetoothAdapter: 761575682: getState() :  mService = null. Returning STATE_OFF
09-12 13:11:13.989  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:11:13.989  1176  1716 D BluetoothAdapter: 761575682: getState() :  mService = null. Returning STATE_OFF
,09-12 13:11:13.989  2648  2713 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-12 13:11:13.989  2648  2648 I GKI_LINUX: GKI_exit_task 1 done
09-12 13:11:13.989  2648  2648 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
09-12 13:11:13.999  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:13.999  1176  1176 D BluetoothTile:  getBluetoothState : 10
09-12 13:11:13.999  2648  2648 I BluetoothServiceJni: cleanupNative: return from cleanup
09-12 13:11:13.999  1176  1716 D BluetoothAdapter: 761575682: getState() :  mService = null. Returning STATE_OFF
,09-12 13:11:13.999  1176  1176 D BluetoothAdapter: 761575682: getState() :  mService = null. Returning STATE_OFF
09-12 13:11:13.999  1013  1670 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 13:11:13.999  1176  1176 D BluetoothAdapter: 761575682: getState() :  mService = null. Returning STATE_OFF
09-12 13:11:13.999  1013  4555 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-12 13:11:13.999  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:11:13.999  1770  1770 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:11:13.999  1359  1359 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:13.999  1013  3012 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:13.999  1013  3012 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
09-12 13:11:13.999  1013  3012 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:13.999  1013  3012 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:13.999  1013  3012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:13.999  2648  2648 I art     : System.exit called, status: 0
09-12 13:11:13.999  2648  2648 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:11:14.009  1926  2107 D BluetoothAdapter: 601092983: getState() :  mService = null. Returning STATE_OFF
09-12 13:11:14.009  1926  2107 D BluetoothAdapter: 601092983: getState() :  mService = null. Returning STATE_OFF
09-12 13:11:14.009  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:14.009  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:14.029  2144  2144 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING ,
09-12 13:11:14.039  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:11:14.039  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:14.039  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:14.059   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:11:14.089  1013  1218 I ActivityManager: Process com.android.bluetooth (pid 2648)(adj 0) has died(45,1084)
,09-12 13:11:14.119  1013  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:14.119  1013  1013 I ApplicationPolicy: updateDataUsageMap
,09-12 13:11:14.129  1013  1037 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:14.139  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:14.139  3117  3117 I DBG_DM  : [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
09-12 13:11:14.139  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:14.149  1013  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
09-12 13:11:14.149  1013  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 13:11:14.149  1013  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 13:11:14.149  3117  3117 I DBG_DM  : [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,09-12 13:11:14.159  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:11:14.159  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-12 13:11:14.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:14.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:14.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:14.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:14.159  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:11:14.159  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-12 13:11:14.159  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:11:14.159  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:11:14.169  1176  1176 D HotspotTile: onReceive : 1, 0
,09-12 13:11:14.169  1926  2107 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:11:14.169  1359  1359 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:11:14.169  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:14.169  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:14.189  6435  6463 I Babel   : MmsConfig: mnc/mcc: 0/0
,09-12 13:11:14.189  6435  6463 I Babel   : MmsConfig.loadMmsSettings
,09-12 13:11:14.189  6435  6463 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-12 13:11:14.189  6435  6463 I Babel   : MmsConfig.loadFromDatabase
,09-12 13:11:14.199  1013  1218 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,09-12 13:11:14.199  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,09-12 13:11:14.199  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.199  1013  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:14.199  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 13:11:14.209  6435  6463 E Babel   : canonicalizeMccMnc: invalid mccmnc 
09-12 13:11:14.209  6435  6463 I Babel   : MmsConfig.loadFromResources
,09-12 13:11:14.209  6435  6435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:11:14.209  6435  6463 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,09-12 13:11:14.209  6435  6463 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,09-12 13:11:14.249  6435  6435 I Babel_StickerModule: App launched.
,09-12 13:11:14.259  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,09-12 13:11:14.259  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:11:14.269  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:11:14.269  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:11:14.269  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:11:14.269  1359  1359 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:11:14.269  1359  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:11:14.269  1013  3010 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,09-12 13:11:14.269  1013  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.269  1013  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.269  1013  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.269  1013  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.279   282   692 W QCamera2Factory: getCameraInfo: E, camera_id = 0
09-12 13:11:14.279   282   692 W QCamera2Factory: getCameraInfo: X
09-12 13:11:14.279   282   682 W QCamera2Factory: getCameraInfo: E, camera_id = 1
09-12 13:11:14.279   282   682 W QCamera2Factory: getCameraInfo: X
,09-12 13:11:14.279  6465  6465 E Zygote  : MountEmulatedStorage()
09-12 13:11:14.279  6465  6465 E Zygote  : v2
09-12 13:11:14.279  6465  6465 I libpersona: KNOX_SDCARD checking this for 10068
09-12 13:11:14.279  6465  6465 I libpersona: KNOX_SDCARD not a persona
09-12 13:11:14.279  6465  6465 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:14.289  1013  3010 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=6465 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:11:14.289  6465  6465 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:14.289  6465  6465 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:14.309  6465  6465 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:14.309  6465  6465 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:14.319  6435  6435 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-12 13:11:14.319  6435  6435 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 13:11:14.319  6435  6435 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 13:11:14.329  6465  6465 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 13:11:14.329  1013  1045 I PowerManagerService: [PWL] Off : 50s ago
,09-12 13:11:14.339  1013  1045 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-12 13:11:14.339  1013  1045 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,09-12 13:11:14.339  1013  1045 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=1013, ws=null) (elapsedTime=709)
,09-12 13:11:14.339  6435  6435 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,09-12 13:11:14.339  6435  6435 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,09-12 13:11:14.339  6435  6435 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,09-12 13:11:14.339  6435  6435 W AudioCapabilities: Unsupported mime audio/x-ima
,09-12 13:11:14.339  6435  6435 W AudioCapabilities: Unsupported mime audio/qcelp
,09-12 13:11:14.349  6435  6435 W AudioCapabilities: Unsupported mime audio/evrc
,09-12 13:11:14.349  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:11:14.349  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 13:11:14.359  6435  6435 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 13:11:14.359  6435  6435 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 13:11:14.369  6435  6435 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,09-12 13:11:14.369  6435  6435 W VideoCapabilities: Unsupported mime video/wvc1
,09-12 13:11:14.369  6435  6435 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,09-12 13:11:14.369  6435  6435 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,09-12 13:11:14.379  6435  6435 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,09-12 13:11:14.379  6435  6435 W VideoCapabilities: Unsupported mime video/mp43
,09-12 13:11:14.379  6435  6435 W VideoCapabilities: Unsupported mime video/sorenson
,09-12 13:11:14.389  6435  6435 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,09-12 13:11:14.389  6465  6465 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 13:11:14.389  1013  3010 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,09-12 13:11:14.389  1013  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.389  1013  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.389  1013  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:14.389  1013  3010 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.399  1013  2724 D SSRM:n  : SIOP:: AP = 360
,09-12 13:11:14.409  6480  6480 E Zygote  : MountEmulatedStorage()
09-12 13:11:14.409  6480  6480 E Zygote  : v2
09-12 13:11:14.409  6480  6480 I libpersona: KNOX_SDCARD checking this for 10069
09-12 13:11:14.409  6480  6480 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:14.409  6480  6480 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:11:14.409  6480  6480 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:11:14.409  1013  3010 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=6480 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:11:14.409  6480  6480 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:11:14.409  1013  3010 I ActivityManager: Killing 5044:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
,09-12 13:11:14.429  6480  6480 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:14.429  6480  6480 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:14.439  6435  6435 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-12 13:11:14.459  6480  6480 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:11:14.469  1013  3010 I ActivityManager: Killing 5516:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,09-12 13:11:14.469  1013  1137 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:11:14.469  1013  1137 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:11:14.469  1013  1137 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:14.469  1013  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:14.469  1013  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:11:14.469  1013  1379 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,09-12 13:11:14.469  1013  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
09-12 13:11:14.469  3637  3637 I Hs20UtilService: Starting #9
,09-12 13:11:14.469  3637  3674 I Hs20UtilService: Message received 5007
09-12 13:11:14.469  1013  1379 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:14.469  1013  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:14.469  1013  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,09-12 13:11:14.479  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 13:11:14.479  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:11:14.479  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:11:14.479  1013  1473 I ActivityManager: Killing 5606:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,09-12 13:11:14.479  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 13:11:14.479  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:11:14.479  1359  1359 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:11:14.479  1359  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:11:14.489  1013  1796 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:14.489  1013  1796 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:14.489  1013  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.599  1013  1379 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:11:14.599  1013  1379 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:14.599  1013  1379 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.599  1013  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:14.599  1013  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:11:14.599  1013  1137 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,09-12 13:11:14.599  1013  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.609  1013  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:14.609  3637  3637 I Hs20UtilService: Starting #10
09-12 13:11:14.609  1013  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:14.609  1013  1137 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.609  3637  3674 I Hs20UtilService: Message received 5011
,09-12 13:11:14.619  1013  1137 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.NetworkReceiver: pid=6496 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-12 13:11:14.619  6496  6496 E Zygote  : MountEmulatedStorage()
09-12 13:11:14.619  6496  6496 E Zygote  : v2
09-12 13:11:14.619  6496  6496 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:11:14.619  6496  6496 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:14.619  6496  6496 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:14.629  6496  6496 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:11:14.629  6496  6496 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 13:11:14.649  6496  6496 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:14.649  6496  6496 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:14.689  1013  1040 D Tethering: interfaceRemoved wlan0
,09-12 13:11:14.689  1013  1040 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-12 13:11:14.699  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:11:14.699  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 13:11:14.699  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 13:11:14.699  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:11:14.709  1013  3001 I ActivityManager: Killing 5826:com.sec.pcw.device/1000 (adj 15): empty #31
,09-12 13:11:14.709  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.709  1013  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:14.709  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.719  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.719  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:14.719  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.719  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.719  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:14.719  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.719  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.719  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:14.729  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.729  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.729  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:14.729  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.729  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.729  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:14.729  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.729  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.739  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:14.739  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.739  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.739  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:14.739  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.739  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.739  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:14.739  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.749  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.749  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:14.749  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.749  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.749  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:14.749  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.759  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.759  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:14.759  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.759  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.759  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:14.759  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.769  1013  1013 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.769  1013  1013 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:14.769  1013  1013 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,09-12 13:11:14.779  1359  1359 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:11:14.779  1013  1473 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 13:11:14.779  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:11:14.779  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:14.779  1013  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:14.779  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:11:14.789  1359  1359 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:11:14.789  1359  1359 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:11:14.789  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:14.789  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 13:11:14.799  1013  3001 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-12 13:11:14.799  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.799  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.799  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.799  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.819  1013  3001 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6514 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a,
,09-12 13:11:14.819  6514  6514 E Zygote  : MountEmulatedStorage()
09-12 13:11:14.819  6514  6514 E Zygote  : v2
09-12 13:11:14.819  6514  6514 I libpersona: KNOX_SDCARD checking this for 1002
09-12 13:11:14.819  6514  6514 I libpersona: KNOX_SDCARD not a persona
09-12 13:11:14.819  6514  6514 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:14.819  6514  6514 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:14.829  6514  6514 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:14.849  6514  6514 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:14.849  6514  6514 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:14.859  6514  6514 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,09-12 13:11:14.869  6514  6514 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:11:14.889  6514  6514 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-12 13:11:14.919  1013  1471 I ActivityManager: Killing 5126:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding GattService
,09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding HeadsetService
,09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding A2dpService
09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding HidService
09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding HealthService
,09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding PanService
09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding BluetoothMapService
09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding SapService
09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding A2dpSinkService
,09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding SapClientService
09-12 13:11:14.929  6514  6514 D BtSettings.ProfileConfig: Adding HidDevService
,09-12 13:11:14.929  6514  6514 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-12 13:11:14.939  1013  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService,
09-12 13:11:14.939  1013  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:14.939  1013  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 13:11:14.939  1013  1026 D SettingsProvider: selectionArgs: false
,09-12 13:11:14.939  1013  1026 D SettingsProvider: selectionArgs: 1002
,09-12 13:11:14.939  1013  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:14.939  1013  1026 D SettingsProvider: ret = -1
,09-12 13:11:14.939  1013  4556 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,09-12 13:11:14.939  1013  4556 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:14.939  1013  4556 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:14.939  1013  4556 D SettingsProvider: selectionArgs: false
,09-12 13:11:14.939  1013  4556 D SettingsProvider: selectionArgs: 1002
09-12 13:11:14.939  1013  4556 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:14.939  1013  4556 D SettingsProvider: ret = -1
,09-12 13:11:14.939  1013  3011 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-12 13:11:14.939  1013  3011 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:14.939  1013  3011 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:14.939  1013  3011 D SettingsProvider: selectionArgs: false
09-12 13:11:14.939  1013  3011 D SettingsProvider: selectionArgs: 1002
09-12 13:11:14.939  1013  3011 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:14.939  1013  3011 D SettingsProvider: ret = -1
,09-12 13:11:14.939  1013  1670 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-12 13:11:14.939  1013  1670 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:14.939  1013  1670 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:14.939  1013  1670 D SettingsProvider: selectionArgs: false
09-12 13:11:14.939  1013  1670 D SettingsProvider: selectionArgs: 1002
09-12 13:11:14.939  1013  1670 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:14.939  1013  1670 D SettingsProvider: ret = -1
,09-12 13:11:14.939  1013  3010 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,09-12 13:11:14.939  1013  3010 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:14.939  1013  3010 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:14.939  1013  3010 D SettingsProvider: selectionArgs: false
09-12 13:11:14.939  1013  3010 D SettingsProvider: selectionArgs: 1002
09-12 13:11:14.939  1013  3010 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:14.939  1013  3010 D SettingsProvider: ret = -1
,09-12 13:11:14.939  1013  1137 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-12 13:11:14.939  1013  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:14.939  1013  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 13:11:14.939  1013  1137 D SettingsProvider: selectionArgs: false
09-12 13:11:14.939  1013  1137 D SettingsProvider: selectionArgs: 1002
09-12 13:11:14.939  1013  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-12 13:11:14.939  1013  1137 D SettingsProvider: ret = -1
,09-12 13:11:14.949  1013  3152 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-12 13:11:14.949  1013  3152 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:14.949  1013  3152 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:14.949  1013  3152 D SettingsProvider: selectionArgs: false
09-12 13:11:14.949  1013  3152 D SettingsProvider: selectionArgs: 1002,
09-12 13:11:14.949  1013  3152 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 13:11:14.949  1013  3152 D SettingsProvider: ret = -1
09-12 13:11:14.949  1013  1796 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService,
09-12 13:11:14.949  1013  1796 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:14.949  1013  1796 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:14.949  1013  1796 D SettingsProvider: selectionArgs: false
09-12 13:11:14.949  1013  1796 D SettingsProvider: selectionArgs: 1002,
09-12 13:11:14.949  1013  1796 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:14.949  1013  1796 D SettingsProvider: ret = -1
09-12 13:11:14.949  1013  1379 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:11:14.949  1013  1379 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:14.949  1013  1379 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:14.949  1013  1379 D SettingsProvider: selectionArgs: false
09-12 13:11:14.949  1013  1379 D SettingsProvider: selectionArgs: 1002
,09-12 13:11:14.949  1013  1379 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:14.949  1013  1379 D SettingsProvider: ret = -1
09-12 13:11:14.949  1013  4555 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:14.949  1013  4555 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:14.949  1013  4555 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:14.949  1013  4555 D SettingsProvider: selectionArgs: false
09-12 13:11:14.949  1013  4555 D SettingsProvider: selectionArgs: 1002,
09-12 13:11:14.949  1013  4555 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:14.949  1013  4555 D SettingsProvider: ret = -1,
09-12 13:11:14.949  1013  1025 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-12 13:11:14.949  1013  1025 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:14.949  1013  1025 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:14.949  1013  1025 D SettingsProvider: selectionArgs: false,
09-12 13:11:14.949  1013  1025 D SettingsProvider: selectionArgs: 1002
09-12 13:11:14.949  1013  1025 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 13:11:14.949  1013  1025 D SettingsProvider: ret = -1
09-12 13:11:14.949  1013  3001 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-12 13:11:14.949  1013  3001 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:14.949  1013  3001 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:14.949  1013  3001 D SettingsProvider: selectionArgs: false
09-12 13:11:14.949  1013  3001 D SettingsProvider: selectionArgs: 1002
,09-12 13:11:14.949  1013  3001 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:14.949  1013  3001 D SettingsProvider: ret = -1
09-12 13:11:14.949  1013  1040 D Tethering: interfaceRemoved p2p0
,09-12 13:11:14.949  1013  1040 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 13:11:14.959  1013  1471 I ActivityManager: Killing 5843:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,09-12 13:11:14.959  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:11:14.959  1013  4556 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:14.959  1013  4556 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 13:11:14.969  1013  4556 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:14.969  1013  4556 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:14.969  1013  4556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:14.969  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:11:14.979  1926  6530 D EasyUnlockInitService: Handling intent for initializer IntentService.
09-12 13:11:14.979  1013  3001 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,09-12 13:11:14.979  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.979  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.979  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:14.979  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:14.989  6531  6531 E Zygote  : MountEmulatedStorage()
,09-12 13:11:14.989  6531  6531 E Zygote  : v2
09-12 13:11:14.989  6531  6531 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:11:14.989  6531  6531 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:14.989  6531  6531 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:14.999  6531  6531 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:11:14.999  6531  6531 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:15.009  1013  3001 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6531 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-12 13:11:15.009  1013  1796 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:15.009  1013  1796 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:15.009  1013  1796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.009  1013  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:15.009  6531  6531 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:15.009  6531  6531 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:15.029  1013  3010 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:15.029  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:15.029  1013  3010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.029  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:15.039  1926  6530 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-12 13:11:15.039  6531  6531 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,09-12 13:11:15.039  6531  6531 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-12 13:11:15.039  6531  6531 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-12 13:11:15.059  6531  6531 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-12 13:11:15.059  1013  1473 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=8, mSplitNum[1]=17, mSplitNum[2]=25, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=33
09-12 13:11:15.059  6531  6531 I PCWCLIENTTRACE_PushUtil: sales region : global
09-12 13:11:15.059  1013  1473 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
09-12 13:11:15.059  6531  6531 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-12 13:11:15.059  1013  1473 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
09-12 13:11:15.059  6531  6531 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
09-12 13:11:15.059   287   287 E SMD     : DCD OFF
,09-12 13:11:15.059   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:11:15.059  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.059  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.059  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.059  1013  1473 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.059  6531  6546 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,09-12 13:11:15.069  6548  6548 E Zygote  : MountEmulatedStorage()
,09-12 13:11:15.069  6548  6548 E Zygote  : v2
09-12 13:11:15.069  6548  6548 I libpersona: KNOX_SDCARD checking this for 10111
09-12 13:11:15.069  6548  6548 I libpersona: KNOX_SDCARD not a persona
09-12 13:11:15.079  1013  1473 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=6548 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:11:15.079  6548  6548 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:15.079  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,09-12 13:11:15.079  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.079  6548  6548 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:11:15.079  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.079  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.079  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.079  6548  6548 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 13:11:15.099  6548  6548 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:15.099  6548  6548 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:15.099   309   309 I art     : Explicit concurrent mark sweep GC freed 8729(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 27.531ms
,09-12 13:11:15.119   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 596us total 16.539ms
,09-12 13:11:15.139   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 16.733ms
,09-12 13:11:15.149  6563  6563 E Zygote  : MountEmulatedStorage(),
09-12 13:11:15.149  6563  6563 E Zygote  : v2
09-12 13:11:15.149  6563  6563 I libpersona: KNOX_SDCARD checking this for 10009,
09-12 13:11:15.149  6563  6563 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:15.149  1013  1038 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6563 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:11:15.149  6563  6563 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:11:15.149  6563  6563 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:11:15.149  6563  6563 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 13:11:15.159  1722  1722 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
09-12 13:11:15.159  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,09-12 13:11:15.159  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.159  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.159  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.159  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.169  6578  6578 E Zygote  : MountEmulatedStorage(),
,09-12 13:11:15.179  6578  6578 E Zygote  : v2
09-12 13:11:15.179  6578  6578 I libpersona: KNOX_SDCARD checking this for 10145
09-12 13:11:15.179  6563  6563 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-12 13:11:15.179  6578  6578 I libpersona: KNOX_SDCARD not a persona
09-12 13:11:15.179  6578  6578 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:15.179  6563  6563 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:15.179  1013  1038 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=6578 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a,
09-12 13:11:15.179  6578  6578 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:15.179  6578  6578 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:15.189  1722  1722 D accuweather: [KK AccuPhone]>>> U:4106 [0:0] getPWC : surface = 0, remote = 1
,09-12 13:11:15.189  1722  1722 D accuweather: [KK AccuPhone]>>> U:4284 [0:0] Store PWC = 1
,09-12 13:11:15.189  1722  1722 D accuweather: [KK AccuPhone]>>> U:4158 [0:0] addPWC = 1
,09-12 13:11:15.189  1722  1722 D accuweather: [KK AccuPhone]>>> UIM:306 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,09-12 13:11:15.199  1722  1722 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,09-12 13:11:15.199  1722  1722 D accuweather: [KK AccuPhone]>>> UIMEM:104 [0:0] The widget does not exist in idle!!
,09-12 13:11:15.199  1013  4556 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,09-12 13:11:15.199  1302  1316 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 6
,09-12 13:11:15.199  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.199  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.199  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.199  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.209  6578  6578 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:15.209  6578  6578 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:15.219  6593  6593 E Zygote  : MountEmulatedStorage()
,09-12 13:11:15.219  6593  6593 E Zygote  : v2
09-12 13:11:15.219  6593  6593 I libpersona: KNOX_SDCARD checking this for 10081
,09-12 13:11:15.219  6593  6593 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:15.219  6593  6593 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:11:15.219  1013  4556 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=6593 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:11:15.229  1722  1722 D accuweather: [KK AccuPhone]>>> U:4250 [0:0] Store PWC succeed
09-12 13:11:15.229  6593  6593 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:15.229  6593  6593 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,09-12 13:11:15.239  6593  6593 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:15.249  6593  6593 D ActivityThread: Added TimaKeyStore provider
09-12 13:11:15.249  6578  6578 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-12 13:11:15.249  6578  6578 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:11:15.249  6578  6578 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:11:15.249  6578  6578 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:15.249  6578  6578 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:11:15.259  6548  6548 I MusicStore: Database version: 108
,09-12 13:11:15.269  1013  1025 I ActivityManager: Killing 5540:com.samsung.android.app.galaxyfinder/u0a32 (adj 15): empty #31,
,09-12 13:11:15.279  3678  3678 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 13:11:15 GMT+02:00 2016
,09-12 13:11:15.289  1013  3010 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,09-12 13:11:15.289  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-12 13:11:15.289  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:15.289  1013  3010 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:15.289  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 13:11:15.289  1013  4555 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:11:15.289  1013  4555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 13:11:15.289  1013  4555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:15.289  1013  4555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.289  1013  4555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:15.299  3678  3678 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-12 13:11:15.309  1013  1670 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,09-12 13:11:15.309  3678  3678 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-12 13:11:15.309  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.309  3678  3678 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 13:11:15.309  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.309  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.309  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.309  3678  3678 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 13:11:15.309  1013  3011 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:11:15.309  3678  6614 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 13:11:15.319  6615  6615 E Zygote  : MountEmulatedStorage()
09-12 13:11:15.319  6615  6615 E Zygote  : v2
09-12 13:11:15.319  6615  6615 I libpersona: KNOX_SDCARD checking this for 10034
09-12 13:11:15.319  6615  6615 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:15.319  3678  6614 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
09-12 13:11:15.319  6615  6615 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:15.329  6615  6615 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:15.329  6615  6615 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:15.329  1013  1670 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=6615 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
09-12 13:11:15.329  3678  6614 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false| ETHERNET : false
09-12 13:11:15.329  3678  6614 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,09-12 13:11:15.339  1013  4556 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:11:15.339  3678  3678 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-12 13:11:15.359  6615  6615 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:15.359  6615  6615 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:15.369  1013  4555 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-12 13:11:15.369  1013  4555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.369  1013  4555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.369  1013  4555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.369  1013  4555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.379  6548  6548 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-12 13:11:15.379  6548  6548 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-12 13:11:15.389  6635  6635 E Zygote  : MountEmulatedStorage()
09-12 13:11:15.389  6635  6635 I libpersona: KNOX_SDCARD checking this for 10113
09-12 13:11:15.389  6635  6635 E Zygote  : v2
09-12 13:11:15.389  6635  6635 I libpersona: KNOX_SDCARD not a persona
09-12 13:11:15.389  6635  6635 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:11:15.389  1013  4555 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6635 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:11:15.389  6635  6635 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:15.389  6635  6635 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-12 13:11:15.399  1013  3001 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:11:15.409  6615  6615 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(95/onReceive)] Network is not available
,09-12 13:11:15.409  1013  1471 I ActivityManager: Killing 5859:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,09-12 13:11:15.409  6635  6635 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:15.419  6635  6635 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:15.429  1013  4556 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:11:15.429  1013  3001 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-12 13:11:15.429  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.429  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.429  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.429  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.429  3179  6652 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,09-12 13:11:15.439  3179  6652 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false,
,09-12 13:11:15.439  3179  6652 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable,
,09-12 13:11:15.439  3179  6652 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,09-12 13:11:15.439  3179  6652 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... ,
,09-12 13:11:15.449  6653  6653 E Zygote  : MountEmulatedStorage()
09-12 13:11:15.449  6653  6653 E Zygote  : v2
,09-12 13:11:15.459  6653  6653 I libpersona: KNOX_SDCARD checking this for 10035
,09-12 13:11:15.459  6548  6548 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,09-12 13:11:15.459  6653  6653 I libpersona: KNOX_SDCARD not a persona,
,09-12 13:11:15.459  1013  3001 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=6653 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:11:15.459  6653  6653 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:15.459  6653  6653 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:11:15.459  6653  6653 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-12 13:11:15.509  6653  6653 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:15.509  6653  6653 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:15.509  1013  1379 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:11:15.519  5950  5962 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,09-12 13:11:15.519  6548  6548 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,09-12 13:11:15.519  6548  6548 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a0440b1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-12 13:11:15.519  6548  6548 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-12 13:11:15.519  6548  6548 D AndroidMusic: GMSCore installation verified
,09-12 13:11:15.529  1013  3001 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:11:15.539  5950  5962 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
09-12 13:11:15.539  5950  5962 D BadgeProvider: sendNotify, [notify] : null
09-12 13:11:15.539  5950  5962 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
09-12 13:11:15.539  5950  5962 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-12 13:11:15.539  5950  5962 D BadgeProvider: update, [UpdateCount] : 1
,09-12 13:11:15.549  1013  3152 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 13:11:15.549  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,09-12 13:11:15.549  1475  1475 D Launcher.Model: reloadBadges entered.
,09-12 13:11:15.549  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:15.549  1013  3152 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.549  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:15.589  6548  6548 I ConfigStore: Config Database version: 1
,09-12 13:11:15.589  1013  3001 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:11:15.599  1013  1026 D RCPManagerService: exchangeData() failure , invalid userId
,09-12 13:11:15.609  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:11:15.609  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,09-12 13:11:15.609  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 13:11:15.609  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:11:15.619  1013  1025 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,09-12 13:11:15.619  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.619  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.619  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.619  1013  1025 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.619  6653  6653 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,09-12 13:11:15.619  6653  6674 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-12 13:11:15.639  6675  6675 E Zygote  : MountEmulatedStorage(),
09-12 13:11:15.639  1013  1025 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=6675 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:11:15.639  6675  6675 E Zygote  : v2
09-12 13:11:15.639  6675  6675 I libpersona: KNOX_SDCARD checking this for 10159
09-12 13:11:15.639  6675  6675 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:15.639  6675  6675 I libpersona: KNOX_SDCARD not a persona
09-12 13:11:15.639  1013  1796 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:15.639  1013  1796 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,09-12 13:11:15.639  1013  1796 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
09-12 13:11:15.639  1013  1796 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
09-12 13:11:15.639  1013  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push,
09-12 13:11:15.639  6675  6675 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:11:15.639  6675  6675 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
09-12 13:11:15.639  6653  6674 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-12 13:11:15.649  6653  6674 D SPPClientService: PushLog.txt file is not deleted.
09-12 13:11:15.649  6653  6674 D SPPClientService: PushLog.txt file is not deleted.
09-12 13:11:15.649  6653  6674 D SPPClientService: ============PushLog. stop!
,09-12 13:11:15.659  6056  6056 I SA      : [DM] init START
,09-12 13:11:15.669  6056  6056 I SA      : [DM] This device is not a Vodafone
,09-12 13:11:15.669  6675  6675 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:15.669  6675  6675 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:15.669  6056  6056 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,09-12 13:11:15.669  6056  6056 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,09-12 13:11:15.669  6056  6056 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
09-12 13:11:15.669  6056  6056 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
09-12 13:11:15.669  6056  6056 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,09-12 13:11:15.669  6056  6056 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,09-12 13:11:15.679  6056  6056 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,09-12 13:11:15.689  6653  6690 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,09-12 13:11:15.689  6056  6056 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,09-12 13:11:15.709  6056  6056 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,09-12 13:11:15.709  6056  6056 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,09-12 13:11:15.709  6056  6056 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,09-12 13:11:15.709  6056  6056 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,09-12 13:11:15.719  6056  6056 I SA      : [SCU] isHaveSA() - false
09-12 13:11:15.719  6056  6056 I SA      : support phone number id : false
09-12 13:11:15.719  6056  6056 I SA      : [DM] Supports Ref Jpn : true
,09-12 13:11:15.719  6056  6056 I SA      : [DM] init END
,09-12 13:11:15.719  6056  6056 I SA      : [OR] onReceive log=[SA = 2.1.0240 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOJ6 PSS = 4.978878039476607  ]
,09-12 13:11:15.719  1013  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 13:11:15.729  6056  6056 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
09-12 13:11:15.729  6056  6056 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,09-12 13:11:15.729  6056  6056 I SA      : [SLFUCHKMGR] constructor called
,09-12 13:11:15.729  1013  1471 I art     : Explicit concurrent mark sweep GC freed 53578(2MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 27MB/41MB, paused 2.838ms total 176.022ms
09-12 13:11:15.729   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-12 13:11:15.729   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:11:15.739  6548  6548 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-12 13:11:15.739  1013  1025 I ActivityManager: Killing 5574:com.sec.knox.bridge/1000 (adj 15): empty #31
,09-12 13:11:15.749  1013  3011 I ActivityManager: Killing 5877:com.sec.android.widgetapp.tapandpay/u0a156 (adj 15): empty #31
,09-12 13:11:15.749   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-12 13:11:15.749   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:11:15.749  6548  6548 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
09-12 13:11:15.749  1013  3010 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:15.749  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,09-12 13:11:15.749  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:15.749  1013  3010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.749  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:15.759   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
09-12 13:11:15.759   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:11:15.759  6548  6548 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,09-12 13:11:15.759  3855  3855 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,09-12 13:11:15.769  3855  4601 I iu.UploadsManager: num queued entries: 0
,09-12 13:11:15.769  3855  4601 I iu.UploadsManager: num updated entries: 0
,09-12 13:11:15.769  6056  6056 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
09-12 13:11:15.769  6056  6056 I SA      : [OR] == isSIMCardReady false ==
,09-12 13:11:15.769  6056  6056 I SA      : [SCU] == networkStateCheck == false
09-12 13:11:15.769  6056  6056 I SA      : [OR] onReceive END
,09-12 13:11:15.769  3855  4601 I iu.SyncManager: NEXT; no task
,09-12 13:11:15.779  1013  4555 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-12 13:11:15.779  1013  4555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,09-12 13:11:15.779  1227  1227 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:15.779  1013  4555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:15.779  1013  4555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.779  1013  4555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:15.789  1013  3012 I ActivityManager: Killing 5809:com.android.mms/u0a46 (adj 15): empty #31
,09-12 13:11:15.799  1013  3010 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:11:15.799  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,09-12 13:11:15.809  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:15.809  1013  3010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.809  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:15.829  1013  4556 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:11:15.839  1013  1379 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:11:15.839  1013  1026 I AudioService: getStreamVolume 3 index 0
,09-12 13:11:15.839  6548  6548 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,09-12 13:11:15.849   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 13:11:15.849   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:11:15.849  6548  6548 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,09-12 13:11:15.859  6635  6702 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 13:11:15.859   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 13:11:15.859   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:11:15.859  6635  6702 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 13:11:15.879  1013  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 13:11:15.879  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 13:11:15.879  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:15.879  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.879  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:15.879   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-12 13:11:15.879   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:11:15.879  1013  1025 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 13:11:15.879  6635  6705 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-12 13:11:15.879  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,09-12 13:11:15.889  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:15.889  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.889  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:15.889   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-12 13:11:15.889   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:11:15.889  6635  6705 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-12 13:11:15.889  1013  1473 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:11:15.889  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,09-12 13:11:15.889  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:15.889  1013  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.889  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:15.899  1013  1796 I ActivityManager: Killing 5965:com.sec.android.app.myfiles/u0a47 (adj 15): empty #31
,09-12 13:11:15.899  1013  1379 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:11:15.909  1013  1025 D CountryDetector: No listener is left
,09-12 13:11:15.929  1013  1013 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,09-12 13:11:15.929  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.929  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.929  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:15.929  1013  1013 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:15.939  1013  1013 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=6710 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:11:15.939  6710  6710 E Zygote  : MountEmulatedStorage()
09-12 13:11:15.939  6710  6710 E Zygote  : v2
09-12 13:11:15.939  6710  6710 I libpersona: KNOX_SDCARD checking this for 10002
09-12 13:11:15.939  6710  6710 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:15.939  6710  6710 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:15.939  6710  6710 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:15.939  6710  6710 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:15.949  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0,
,09-12 13:11:15.949  1013  3010 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,09-12 13:11:15.959  1013  3012 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,09-12 13:11:15.959  1013  4556 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,09-12 13:11:15.969  6710  6710 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:15.969  6710  6710 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:15.979  1013  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,09-12 13:11:15.979  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,09-12 13:11:15.979  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:15.979  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.979  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-12 13:11:15.979  6548  6548 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,09-12 13:11:15.979  1013  1025 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 13:11:15.979  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 13:11:15.979  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:15.979  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:15.979  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:16.009  1013  1137 I ActivityManager: Killing 5987:com.wsomacp/u0a25 (adj 15): empty #31
,09-12 13:11:16.019  1013  3010 I ActivityManager: Killing 6018:com.sec.android.app.soundalive/u0a53 (adj 15): empty #31
,09-12 13:11:16.019  1013  1670 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,09-12 13:11:16.019  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:16.029  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:16.029  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:16.029  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:16.039  6741  6741 E Zygote  : MountEmulatedStorage(),
09-12 13:11:16.039  6741  6741 E Zygote  : v2
,09-12 13:11:16.039  6741  6741 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:11:16.039  6741  6741 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:16.039  6741  6741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:16.039  6741  6741 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:11:16.039  1013  1670 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=6741 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-12 13:11:16.049  6741  6741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 13:11:16.059   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,09-12 13:11:16.059  1013  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:16.059  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:16.059  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:16.059  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-12 13:11:16.069  6741  6741 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:16.069  6741  6741 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:16.089  6635  6635 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,09-12 13:11:16.099  6635  6635 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 8817-8818)
09-12 13:11:16.099  6635  6635 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 13:11:16.109  6635  6635 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d36556e}
,09-12 13:11:16.109  6635  6635 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-12 13:11:16.109  6635  6635 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,09-12 13:11:16.119  6741  6741 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,09-12 13:11:16.129  6635  6635 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-12 13:11:16.129  6635  6635 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-12 13:11:16.129  6635  6635 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-12 13:11:16.149  6635  6635 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,09-12 13:11:16.149  6635  6635 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,09-12 13:11:16.149  6635  6635 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,09-12 13:11:16.159  6635  6635 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-12 13:11:16.159  6635  6635 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-12 13:11:16.159  6635  6635 I Adreno-EGL: Build Date: 04/06/15 Mon
09-12 13:11:16.159  6635  6635 I Adreno-EGL: Local Branch: 
09-12 13:11:16.159  6635  6635 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-12 13:11:16.159  6635  6635 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-12 13:11:16.159  6635  6635 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-12 13:11:16.209  6635  6769 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-12 13:11:16.219  6635  6635 I NSApplication: Starting up...
,09-12 13:11:16.229  1013  4555 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,09-12 13:11:16.229  6741  6741 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,09-12 13:11:16.229  1013  4555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:16.229  1013  4555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:16.229  1013  4555 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:16.239  1013  4555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:16.239  6741  6741 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !,
,09-12 13:11:16.239  6741  6741 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:16.249  6741  6741 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:,
09-12 13:11:16.249  6741  6741 I DIAGMON_AGENT: ./extraInfo: <unknown ssid>
09-12 13:11:16.249  6774  6774 E Zygote  : MountEmulatedStorage()
09-12 13:11:16.249  6774  6774 I libpersona: KNOX_SDCARD checking this for 10120
09-12 13:11:16.249  6774  6774 E Zygote  : v2
09-12 13:11:16.249  6774  6774 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:16.249  6741  6741 W DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(27/llIIIIlllllIIllIIllI)] Network is changed and not available now, so don't do anything
,09-12 13:11:16.249  6774  6774 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:16.249  6774  6774 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:11:16.249  6774  6774 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 13:11:16.249  1013  4555 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6774 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,09-12 13:11:16.259  1013  4555 I ActivityManager: Killing 5910:com.samsung.android.sdk.samsunglink/u0a38 (adj 15): empty #31
,09-12 13:11:16.259  1013  1218 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:11:16.259  1013  1218 D WifiService: setWifiEnabled: true pid=6226, uid=10155
09-12 13:11:16.259  1013  1218 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:11:16.259  1013  1218 W ActivityManager: Permission Denial: getCurrentUser() from pid=6226, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:11:16.259  1013  1218 D SecContentProvider2: mCursor = null
09-12 13:11:16.259  1013  4555 I ActivityManager: Killing 5792:com.samsung.android.sm/1000 (adj 15): empty #31
,09-12 13:11:16.259  1013  1218 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:11:16.259  1013  1218 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6226, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:11:16.259  1013  1218 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 13:11:16.259  1013  1218 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:11:16.259  1013  1218 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:11:16.259  1013  1218 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:11:16.259  1013  1218 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446),
09-12 13:11:16.259  1013  1218 D SettingsProvider: name = wifi_on
,09-12 13:11:16.269  1013  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-12 13:11:16.279  6774  6774 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:16.279  6774  6774 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:16.299  6774  6774 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-12 13:11:16.579  1013  4556 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-12 13:11:16.579  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:16.579  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:16.579  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:16.579  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:16.599  6802  6802 E Zygote  : MountEmulatedStorage()
09-12 13:11:16.599  6802  6802 E Zygote  : v2
09-12 13:11:16.599  6802  6802 I libpersona: KNOX_SDCARD checking this for 10125
09-12 13:11:16.599  6802  6802 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:16.599  6802  6802 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:16.599  6802  6802 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:11:16.609  1013  4556 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=6802 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,09-12 13:11:16.609  1013  4556 I ActivityManager: Killing 5892:com.google.android.apps.docs/u0a91 (adj 15): empty #31
,09-12 13:11:16.609  6802  6802 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:16.629  1013  1040 D Tethering: interfaceAdded wlan0
,09-12 13:11:16.629  1013  1132 E Tethering: No numeric data
09-12 13:11:16.629   309   309 I art     : Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 22.691ms
,09-12 13:11:16.629  1013  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,09-12 13:11:16.629  1013  1132 D Tethering: clearTetheredNotification()
09-12 13:11:16.629  1013  1122 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:11:16.629  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:16.629  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:11:16.629  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:11:16.639  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:16.639  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:16.639  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:11:16.639  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:11:16.639  1176  1176 D HotspotTile: updateTetherState():false, false
09-12 13:11:16.639  1013  1132 D Tethering: InitialState.processMessage what=4
09-12 13:11:16.639  1013  1132 E Tethering: No numeric data
09-12 13:11:16.639  1013  1122 V NetworkStats: performPollLocked() took 5ms
09-12 13:11:16.639  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:16.639  1013  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:11:16.639  1013  1132 D Tethering: clearTetheredNotification()
,09-12 13:11:16.639  1013  1040 D Tethering: interfaceAdded p2p0
,09-12 13:11:16.639  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:11:16.639  1176  1176 D HotspotTile: updateTetherState():false, false
,09-12 13:11:16.649  1013  1040 D Tethering: p2p0 is not a tetherable iface, ignoring
09-12 13:11:16.649  1013  1122 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:11:16.649  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:16.649  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:11:16.649  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:11:16.649  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:11:16.649  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:11:16.649  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
09-12 13:11:16.649   277  1011 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-12 13:11:16.649   277  1011 D SoftapController: Softap fwReload - Ok
09-12 13:11:16.649  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:16.649  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:16.649   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 681us total 18.851ms
,09-12 13:11:16.649   277  1011 D CommandListener: Setting iface cfg
09-12 13:11:16.649   277  1011 D CommandListener: Trying to bring down wlan0
,09-12 13:11:16.649   277  1011 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:11:16.649  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:16.649  1013  1122 V NetworkStats: performPollLocked() took 8ms,
,09-12 13:11:16.659  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:16.659  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:16.659  6802  6802 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:16.659  1013  1125 E WifiHW  : supplicant_name : p2p_supplicant
09-12 13:11:16.659  6802  6802 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:16.669   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 602us total 18.426ms
,09-12 13:11:16.679  6802  6802 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.,
09-12 13:11:16.679  6802  6802 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:11:16.679  6802  6802 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:11:16.689  6802  6802 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:16.689  6802  6802 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,09-12 13:11:16.689  6802  6802 I QuickConnect: PeriphStartReceiver.onReceive - no need to start,
09-12 13:11:16.699  1013  3012 I splitIntent: Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-12 13:11:16.699  1013  3012 I ActivityManager: Killing 6100:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,09-12 13:11:16.709  1013  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:16.709  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:16.709  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:16.709  1013  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:16.709  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:11:16.709  3637  3637 I Hs20UtilService: Starting #11
,09-12 13:11:16.709  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:11:16.709  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:11:16.709  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:11:16.709  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:11:16.709  3637  3674 I Hs20UtilService: Message received 5011
09-12 13:11:16.709  6818  6818 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 13:11:16.709  6818  6818 I wpa_supplicant: Successfully initialized wpa_supplicant
09-12 13:11:16.709  6818  6818 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-12 13:11:16.719  6818  6818 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
,09-12 13:11:16.729   388   388 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6818,
09-12 13:11:16.729   388   388 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x0000010C
09-12 13:11:16.729  6818  6818 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 13:11:16.729  6818  6818 I wpa_supplicant: ssSupport state is = 1
,09-12 13:11:16.729  6818  6818 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 13:11:16.729  6818  6818 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
09-12 13:11:16.729   388   388 I SecureStorage: [INFO]: SPID(0x00000002)Credentials: uid 1010, gid 1010, pid 6818
09-12 13:11:16.729   388   388 I SecureStorage: [INFO]: SPID(0x00000002)Received function mask & code: 0x00000106
,09-12 13:11:16.759  1013  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-12 13:11:16.769  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:16.769  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null,
09-12 13:11:16.769  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:16.769  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:11:16.769  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 13:11:16.769  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:16.769  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 13:11:16.769  1176  1176 D HotspotTile: onReceive : 2, 0
09-12 13:11:16.769  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,09-12 13:11:16.769  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED,
09-12 13:11:16.769  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
09-12 13:11:16.769  1359  1359 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:16.769  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:16.779  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 13:11:16.779  1013  3152 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:16.779  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:16.779  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:16.779  1013  3152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:16.779  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:11:16.779  3637  3637 I Hs20UtilService: Starting #12
,09-12 13:11:16.779  3637  3674 I Hs20UtilService: Message received 5011
,09-12 13:11:16.779  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:11:16.779  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:11:16.789  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:11:16.789  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:11:16.889   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0,
,09-12 13:11:16.899  6818  6818 I SecureStorage: [INFO]: SPID(0x00000003)Processing data has been completed,
,09-12 13:11:16.969  6818  6818 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-12 13:11:16.969  6818  6818 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 13:11:16.979  6818  6818 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
09-12 13:11:16.979   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6818
09-12 13:11:16.979   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 13:11:16.979  6818  6818 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running,
09-12 13:11:16.979  6818  6818 I wpa_supplicant: ssSupport state is = 1
09-12 13:11:16.979  6818  6818 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 13:11:16.979  6818  6818 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-12 13:11:16.979  6818  6818 E wpa_supplicant: SIM READ ERROR
09-12 13:11:16.979  6818  6818 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,09-12 13:11:16.979  6818  6818 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:11:16.979  6818  6818 E wpa_supplicant: SIM READ ERROR
09-12 13:11:16.979  6818  6818 I wpa_supplicant: Blacklist: Clear (all) ,
,09-12 13:11:16.979  6818  6818 I wpa_supplicant: wpa_default_ap_write_once
,09-12 13:11:16.979  6818  6818 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:11:16.989  6818  6818 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 13:11:16.989  6818  6818 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
09-12 13:11:16.989  6818  6818 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:11:16.989  6818  6818 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 13:11:16.989  6818  6818 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-12 13:11:16.989  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 13:11:16.989  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:16.989  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:17.099  6818  6818 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-12 13:11:17.249  6818  6818 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,09-12 13:11:17.249  6818  6818 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage,
,09-12 13:11:17.259  6818  6818 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-12 13:11:17.259   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6818
09-12 13:11:17.259   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
09-12 13:11:17.259  6818  6818 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 13:11:17.259  6818  6818 I wpa_supplicant: ssSupport state is = 1
09-12 13:11:17.259  6818  6818 I wpa_supplicant: Ctrl_iface: loading cred from phone
09-12 13:11:17.259  6818  6818 I SecureStorage: [INFO]: SPID(0x00000003)Checking if this device supports Secure Storage
,09-12 13:11:17.279  6818  6818 I SecureStorage: [INFO]: SPID(0x00000003)This device supports Secure Storage,
,09-12 13:11:17.279   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 6818
09-12 13:11:17.279   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-12 13:11:17.279  6818  6818 I SecureStorage: [INFO]: SPID(0x00000003)SS Daemon is running
09-12 13:11:17.279  6818  6818 I wpa_supplicant: ssSupport state is = 1
,09-12 13:11:17.279  6818  6818 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:11:17.279  6818  6818 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
,09-12 13:11:17.279  6818  6818 E wpa_supplicant: SIM READ ERROR
,09-12 13:11:17.279  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:11:17.279  6818  6818 I wpa_supplicant: wpa_default_ap_write_once
,09-12 13:11:17.289  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:11:17.279  6818  6818 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:11:17.279  6818  6818 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
09-12 13:11:17.279  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:11:17.279  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:11:17.289  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:11:17.289  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:11:17.399  6818  6818 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-12 13:11:17.399  6818  6818 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 13:11:17.479  6818  6818 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-12 13:11:17.489  6818  6818 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-12 13:11:17.489  6818  6818 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 13:11:17.489  1013  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-12 13:11:17.499  1013  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 13:11:17.499  6818  6818 I wpa_supplicant: HOTSPOT20_ENABLE called
09-12 13:11:17.499  6818  6818 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:11:17.499  6818  6818 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 13:11:17.499  6818  6818 E wpa_supplicant: SIM READ ERROR
09-12 13:11:17.499  6818  6818 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:11:17.529  6818  6818 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-12 13:11:17.539  1013  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
09-12 13:11:17.539  6818  6818 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 13:11:17.539  1013  1125 D WifiConfigStore: Loading config and enabling all networks ,
,09-12 13:11:17.549  1013  1125 E WifiConfigStore: Not a HS20,
09-12 13:11:17.549  1013  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,09-12 13:11:17.559  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:17.559  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:17.559  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:17.559  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:17.559  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:17.559  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:17.559  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:17.559  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-12 13:11:17.559  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:17.559  1359  1359 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:17.559  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 13:11:17.559  1176  1176 D HotspotTile: onReceive : 3, 0
,09-12 13:11:17.559  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:17.559  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:17.559  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:17.559  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:17.559  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:17.559  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:17.559  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:17.569  1013  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
09-12 13:11:17.569  1013  1379 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:17.569  1013  1379 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:11:17.569  1013  1379 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:17.569  1013  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:17.569  1013  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:11:17.569  3637  3637 I Hs20UtilService: Starting #13
09-12 13:11:17.569  3637  3674 I Hs20UtilService: Message received 5011
09-12 13:11:17.569  1013  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 13:11:17.569  6818  6818 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 13:11:17.569  6818  6818 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-12 13:11:17.569  6818  6818 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 13:11:17.569  6818  6818 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 13:11:17.569  6818  6818 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 13:11:17.569  6818  6818 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 13:11:17.569  6818  6818 I wpa_supplicant: First Scan Start
09-12 13:11:17.569  6818  6818 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-12 13:11:17.579  1013  1125 D WifiNative-wlan0: Setting external_sim to 1
09-12 13:11:17.579  6435  6435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:11:17.579  1013  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 13:11:17.579  1013  1125 I WifiNative-HAL: startHal
09-12 13:11:17.579  1013  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9c9c688c
09-12 13:11:17.579  1013  1125 I WifiNative-HAL: Could not start hal
09-12 13:11:17.579  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:11:17.579  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:11:17.579  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:11:17.579  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-12 13:11:17.579  1013  1125 E WifiNative-wlan0: do suspend true
09-12 13:11:17.579  1013  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
09-12 13:11:17.579   277  1011 D CommandListener: Setting iface cfg
09-12 13:11:17.579   277  1011 D CommandListener: Trying to bring up p2p0
09-12 13:11:17.589  1013  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 13:11:17.589  1013  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-12 13:11:17.589  1013  1124 D WifiP2pService: P2pEnablingState
09-12 13:11:17.589  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 13:11:17.589  1013  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-12 13:11:17.589  1013  1124 D WifiP2pService: P2p socket connection successful
09-12 13:11:17.589  1013  1148 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:17.589  1013  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:11:17.589  1013  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:11:17.589  1013  1125 E WifiNative-wlan0: invaild command id : 215
09-12 13:11:17.589  1013  1148 I WifiNative-HAL: startHal
09-12 13:11:17.589  1013  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9d86c9bc
09-12 13:11:17.589  1013  1148 I WifiNative-HAL: Could not start hal
09-12 13:11:17.589  1013  1013 D RttService: SCAN_AVAILABLE : 3
09-12 13:11:17.589  1013  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:17.589  1013  1148 E WifiScanningService: could not start HAL
09-12 13:11:17.589  1013  1124 D WifiP2pService: P2pEnabledState
09-12 13:11:17.589  1013  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:11:17.589  1013  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:11:17.589  1013  1125 E WifiNative-wlan0: invaild command id : 215
09-12 13:11:17.589  6818  6818 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 13:11:17.589  6818  6818 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 13:11:17.589  1013  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,09-12 13:11:17.599  1013  1131 E ConnectivityService: updateNetworkInfo()
09-12 13:11:17.599  6818  6818 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-12 13:11:17.599  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-12 13:11:17.599  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-12 13:11:17.599  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:11:17.599  1013  1043 D WifiDisplayController: disconnect
09-12 13:11:17.599  1013  1043 D WifiDisplayController: updateConnection
09-12 13:11:17.599  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:11:17.599  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:11:17.599  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:17.599  1013  1125 D SecContentProvider2: mCursor = null
09-12 13:11:17.599  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 13:11:17.599  1013  4555 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:11:17.599  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:17.599  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-12 13:11:17.599  1013  1125 D SecContentProvider2: mCursor = null
09-12 13:11:17.599  1013  1124 D WifiNative-p2p0: p2pGetDeviceAddress
09-12 13:11:17.609  1013  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-12 13:11:17.609  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:11:17.609  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:11:17.609  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:11:17.609  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 13:11:17.609  1013  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
09-12 13:11:17.609  1013  1043 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  secondary type: null
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  wps: 0
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  grpcapab: 0
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  devcapab: 0
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  status: 3
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  wfdInfo: null
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  groupownerAddress: null
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  GOdeviceName: null
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  interfaceAddress: 
09-12 13:11:17.609  1013  1043 D WifiDisplayController:  SConnectInfo : null
09-12 13:11:17.609  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 13:11:17.609  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 13:11:17.609  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 13:11:17.609  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:11:17.609  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:11:17.609  1359  1359 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:11:17.619  1359  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-12 13:11:17.619  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-12 13:11:17.619  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 13:11:17.619  6465  6465 D FileShare-Client: Outbound.stopDelayTimer - 
09-12 13:11:17.619  6480  6480 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
09-12 13:11:17.629  1013  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
09-12 13:11:17.629  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:11:17.629  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:11:17.629  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
09-12 13:11:17.629  1013  1124 D WifiP2pService: InactiveState
09-12 13:11:17.629  1013  1124 D WifiP2pService: InactiveState{ what=143376 }
09-12 13:11:17.629  1013  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:11:17.639  6818  6818 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 13:11:17.639  1013  1124 D WifiP2pService: InactiveState{ what=143376 }
09-12 13:11:17.639  1013  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:11:18.069   287   287 E SMD     : DCD OFF,
,09-12 13:11:18.839  6818  6818 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
09-12 13:11:18.839  6818  6818 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec,
,09-12 13:11:18.839  6818  6818 I wpa_supplicant: Trying to associate with SSID '4E47373030',
09-12 13:11:18.839  1013  6823 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
09-12 13:11:18.839  6818  6818 I wpa_supplicant: Trying to associate with  'G700'
,09-12 13:11:18.839  6818  6818 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,09-12 13:11:18.839  6818  6818 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
,09-12 13:11:18.849  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 13:11:18.849  1013  1125 D SecContentProvider2: mCursor = null
,09-12 13:11:18.979  6818  6818 E wpa_supplicant: Cmd 35605 not handled
,09-12 13:11:18.979  6818  6818 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:11:18.979  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:18.979  6818  6818 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-12 13:11:18.979  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:18.979  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:18.979  6818  6818 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
09-12 13:11:18.979  6818  6818 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-12 13:11:18.979  6818  6818 I wpa_supplicant: Associated with F4.99.3E
,09-12 13:11:18.979  6818  6818 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:11:18.979  6818  6818 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-12 13:11:18.989  6818  6818 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
,09-12 13:11:18.989  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 13:11:18.989  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:18.989  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:11:18.989  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 13:11:18.989  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 13:11:18.989  1013  1040 D Tethering: interfaceStatusChanged wlan0, true
,09-12 13:11:18.989  1013  1132 E Tethering: No numeric data
,09-12 13:11:18.989  1013  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:11:18.989  1013  1132 D Tethering: clearTetheredNotification()
,09-12 13:11:18.999  6818  6818 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-12 13:11:18.999  6818  6818 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-12 13:11:18.999  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:18.999  1013  1122 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:11:18.999  6818  6818 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
,09-12 13:11:18.999  6818  6818 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030,
09-12 13:11:18.999  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:11:18.999  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:11:18.999  6818  6818 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:11:18.999  6818  6818 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-12 13:11:18.999  6818  6818 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-12 13:11:18.999  6818  6818 I wpa_supplicant: Blacklist: Clear (temp) 
09-12 13:11:19.009  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 13:11:18.999  6818  6818 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-12 13:11:19.009  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, true
09-12 13:11:19.009  1013  1040 D Tethering: interfaceStatusChanged wlan0, true
,09-12 13:11:19.009  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:19.009  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:11:19.009  1013  1125 D SecContentProvider2: mCursor = null
09-12 13:11:19.009  1176  1176 D HotspotTile: updateTetherState():false, false
,09-12 13:11:19.019  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:19.019  1013  1122 V NetworkStats: performPollLocked() took 20ms
,09-12 13:11:19.019  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:19.019  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:19.019  1013  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-12 13:11:19.029  1013  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 13:11:19.029  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:19.029  1013  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-12 13:11:19.029  1013  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-12 13:11:19.029  1013  1131 E ConnectivityService: updateNetworkInfo()
09-12 13:11:19.029  1013  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 13:11:19.029  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 13:11:19.039  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:19.039  1013  1038 I ActivityManager: Killing 6124:com.samsung.helphub/1000 (adj 15): empty #31
09-12 13:11:19.039  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:19.039  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.039  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.039  1013  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:11:19.039  1013  1379 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:19.039  1013  1379 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:19.039  1013  1379 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:19.039  1013  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:19.039  1013  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:11:19.049  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 13:11:19.059  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:11:19.059  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 13:11:19.059  1013  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:11:19.059  3637  3637 I Hs20UtilService: Starting #14
,09-12 13:11:19.059  3637  3674 I Hs20UtilService: Message received 5007
,09-12 13:11:19.059  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:11:19.059  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-12 13:11:19.059  1359  1359 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:11:19.069  1359  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:11:19.069   277  1011 D CommandListener: Setting iface cfg
,09-12 13:11:19.069  1013  1125 E WifiStateMachine: Start Dhcp Watchdog 2
,09-12 13:11:19.069  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:19.079  1013  1125 D SecContentProvider2: mCursor = null
,09-12 13:11:19.079  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:19.079  1013  1125 D SecContentProvider2: mCursor = null
,09-12 13:11:19.089  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:19.089  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:19.089  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.089  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.089  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.089  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:19.089  1013  1125 E WifiNative-wlan0: do suspend false
,09-12 13:11:19.089  1013  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-12 13:11:19.089  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:19.089  1013  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
09-12 13:11:19.089  1013  1125 D SecContentProvider2: mCursor = null
,09-12 13:11:19.269  1013  3010 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:11:19.269  1013  3010 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:11:19.269  1013  3010 D SecContentProvider2: mCursor = null
,09-12 13:11:19.269  1013  3010 D WifiService: setWifiEnabled: false pid=6226, uid=10155
,09-12 13:11:19.269  1013  3010 D SettingsProvider: name = wifi_on
,09-12 13:11:19.279  1013  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:11:19.299  1013  1125 E WifiNative-wlan0: do suspend true
,09-12 13:11:19.309  6833  6833 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 13:11:19.309  6833  6833 I dhcpcd  : version 5.5.6 starting
,09-12 13:11:19.329  6833  6833 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
,09-12 13:11:19.329  1013  1124 D WifiP2pService: InactiveState{ what=143375 },
09-12 13:11:19.329   277  1011 D CommandListener: Clearing all IP addresses on wlan0,
09-12 13:11:19.329  1013  1124 D WifiP2pService: P2pEnabledState{ what=143375 },
09-12 13:11:19.329  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:19.329  1013  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:11:19.329  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:19.329  1013  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
09-12 13:11:19.329  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.339  1013  1131 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '75 network destroy 503' failed with '400 75 destroyNetwork() failed (Machine is not on the network)'
09-12 13:11:19.329  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.339  1013  1131 D ConnectivityService: setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
09-12 13:11:19.329  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 13:11:19.339  1013  1131 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
09-12 13:11:19.329  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.339  1013  1131 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
09-12 13:11:19.329  1013  1131 E ConnectivityService: updateNetworkInfo(),
,09-12 13:11:19.339  1013  1124 D WifiP2pService: InactiveState{ what=131204 },
09-12 13:11:19.329  1013  1131 E ConnectivityService: updateNetworkInfo()
,09-12 13:11:19.339  1013  1124 D WifiP2pService: P2pEnabledState{ what=131204 }
09-12 13:11:19.329   277  1011 E Netd    : no such netId 503
09-12 13:11:19.339  1013  1125 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-12 13:11:19.339  1013  6829 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:19.339  1013  6829 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-12 13:11:19.339  1013  1131 D ConnectivityService: nai.networkMonitor.doQuit()
09-12 13:11:19.339  1013  1131 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: doQuit - quitNow()
09-12 13:11:19.339  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 13:11:19.349  1013  1124 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,09-12 13:11:19.349  1013  1131 E ConnectivityService: updateNetworkInfo()
,09-12 13:11:19.359  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:11:19.359  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:19.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.359  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:19.359  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 1
09-12 13:11:19.359  1013  1013 D RttService: SCAN_AVAILABLE : 1
09-12 13:11:19.359  1013  1149 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:11:19.359  1013  1148 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,09-12 13:11:19.369  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
09-12 13:11:19.369  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:11:19.369  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer,
09-12 13:11:19.369  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 13:11:19.369  1013  3001 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:19.369  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:19.369  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:19.369  1013  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-12 13:11:19.369  1013  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:19.369  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:11:19.379  1013  1131 E ConnectivityService: updateNetworkInfo()
09-12 13:11:19.379  3637  3637 I Hs20UtilService: Starting #15
,09-12 13:11:19.379  3637  3674 I Hs20UtilService: Message received 5007
09-12 13:11:19.379  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-12 13:11:19.379  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
09-12 13:11:19.379  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:11:19.379  1013  1043 D WifiDisplayController: disconnect
09-12 13:11:19.379  1013  1043 D WifiDisplayController: updateConnection
09-12 13:11:19.379  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:11:19.379  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:11:19.379  1013  1124 D WifiP2pService: P2pDisablingState
09-12 13:11:19.379  1013  1124 D WifiP2pService: P2pDisablingState{ what=147458 }
09-12 13:11:19.379  1013  1124 D WifiP2pService: p2p socket connection lost
09-12 13:11:19.379  1013  1124 D WifiP2pService: P2pDisabledState
,09-12 13:11:19.379  1013  1125 E WifiNative-wlan0: do suspend true
,09-12 13:11:19.379  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 13:11:19.379  1013  4556 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:11:19.379  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,09-12 13:11:19.389  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,09-12 13:11:19.389  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:11:19.389  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:11:19.389  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
,09-12 13:11:19.389  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,09-12 13:11:19.389  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null,
09-12 13:11:19.389  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:11:19.399  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:11:19.399  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:11:19.399  1359  1359 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:11:19.399  1359  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:11:19.399  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE,
09-12 13:11:19.399  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:11:19.409  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:11:19.409  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:11:19.409  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,09-12 13:11:19.409  1359  1359 I NearbySettings: MountReceiver.onReceive - Set preference state off
09-12 13:11:19.409  1013  1124 D WifiP2pService: P2pDisabledState{ what=143375 }
09-12 13:11:19.409  1359  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
09-12 13:11:19.409  1013  1124 D WifiP2pService: DefaultState{ what=143375 }
09-12 13:11:19.419  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:11:19.419  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
09-12 13:11:19.419  6465  6465 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 13:11:19.419  6480  6480 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null,
09-12 13:11:19.419   277  1011 D CommandListener: Clearing all IP addresses on wlan0,
,09-12 13:11:19.429  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:19.429  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:19.429  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.429  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.429  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.429  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:19.429  6833  6833 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
09-12 13:11:19.429  6833  6833 E dhcpcd  : wlan0: sendmsg: Network is unreachable
09-12 13:11:19.429  6833  6833 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-12 13:11:19.429  6833  6833 I dhcpcd  : bssid match
09-12 13:11:19.429  6833  6833 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-12 13:11:19.429  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:11:19.439  6818  6818 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,09-12 13:11:19.439  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:11:19.439  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:19.439  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.439  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:19.439  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.439  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:19.449  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:19.449  1013  1125 D SecContentProvider2: mCursor = null
,09-12 13:11:19.449  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:19.449  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
09-12 13:11:19.449  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.449  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.449  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.449  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:19.449  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:11:19.449  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
09-12 13:11:19.449  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:19.449  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:11:19.459  1176  1176 D HotspotTile: onReceive : 0, 0
,09-12 13:11:19.459  1359  1359 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:11:19.459  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:19.459  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:19.459  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:19.459  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:19.459  1013  3011 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:19.459  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:19.459  1013  3011 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:11:19.459  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:19.459  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:19.459  1013  3011 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:19.459  1013  3011 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:19.459  1013  3011 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:11:19.459  3637  3637 I Hs20UtilService: Starting #16
09-12 13:11:19.459  3637  3674 I Hs20UtilService: Message received 5007
,09-12 13:11:19.469  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:11:19.469  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:11:19.469  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:11:19.469  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,09-12 13:11:19.469  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:11:19.469  1359  1359 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:11:19.469  1359  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:11:19.479  1013  1025 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:11:19.479  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:19.479  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:19.479  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:19.479  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:11:19.479  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:11:19.479  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:11:19.479  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
,09-12 13:11:19.489  3637  3637 I Hs20UtilService: Starting #17
09-12 13:11:19.489  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:11:19.489  3637  3674 I Hs20UtilService: Message received 5011
,09-12 13:11:19.489  6833  6833 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
,09-12 13:11:19.559  6818  6818 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:11:19.599  6833  6833 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds,
,09-12 13:11:19.649  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:11:19.649  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false,
09-12 13:11:19.649  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
09-12 13:11:19.649  6818  6818 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,09-12 13:11:19.679  6818  6818 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,09-12 13:11:19.679  6818  6818 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
09-12 13:11:19.679  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:19.679  6818  6818 I wpa_supplicant: Prev BSS - hexdump(len=6): f4 f2 6d 22 99 3e
09-12 13:11:19.679  1013  1125 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.wifi.WifiStateMachine.insertLog:14956 com.android.server.wifi.WifiStateMachine.access$2700:217 com.android.server.wifi.WifiStateMachine$DefaultState.processMessage:6951 com.android.internal.util.StateMachine$SmHandler.processMsg:966 
09-12 13:11:19.679  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:19.679  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:19.679  1013  1132 D Tethering: InitialState.processMessage what=4
,09-12 13:11:19.679  6818  6818 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=F4.99.3E SSID=4E47373030
09-12 13:11:19.679  6818  6818 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
09-12 13:11:19.679  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:19.679  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:19.679  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:19.679  1013  1132 E Tethering: No numeric data
,09-12 13:11:19.679  1013  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:11:19.679  1013  1132 D Tethering: clearTetheredNotification()
09-12 13:11:19.689  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:19.689  1013  1122 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:11:19.689  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:11:19.689  1176  1176 D HotspotTile: updateTetherState():false, false
,09-12 13:11:19.689  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:11:19.689  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:11:19.689  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:19.689  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:19.689  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:11:19.689  1013  1122 V NetworkStats: performPollLocked() took 3ms
09-12 13:11:19.689  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:19.689  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:19.689  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:19.979  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:11:19.979  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:19.979  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:20.039  6818  6818 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:11:20.129  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 13:11:20.129  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:20.129  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:20.129  6818  6818 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,09-12 13:11:20.239  1013  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,09-12 13:11:20.239  1013  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21]
,09-12 13:11:20.239  1013  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 13:11:20.249  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:11:20.249  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-12 13:11:20.249  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:20.259  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:20.259  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:20.259  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:20.259  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:20.259  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:20.259  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
,09-12 13:11:20.259  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi,
,09-12 13:11:20.259  6435  6435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-12 13:11:20.269  1926  2107 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.,
09-12 13:11:20.269  1176  1176 D HotspotTile: onReceive : 1, 0
,09-12 13:11:20.269  1359  1359 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:20.269  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:20.279  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:20.279  1013  3001 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:20.279  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:20.279  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:20.279  1013  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:20.279  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:11:20.279  3637  3637 I Hs20UtilService: Starting #18
,09-12 13:11:20.289  3637  3674 I Hs20UtilService: Message received 5011
,09-12 13:11:20.289  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,09-12 13:11:20.289  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:11:20.289  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:11:20.289  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:11:20.839  1013  1038 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:20.839  1013  1038 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:20.839  1013  1038 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:20.839  1013  1218 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-12 13:11:20.839  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.leanback.AutoCacheSchedulingService; callingUser = 0; userId(target) = 0
,09-12 13:11:20.849  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:20.849  1013  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:20.849  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:20.859  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:20.859  1013  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:20.859  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:20.869  1013  1473 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,09-12 13:11:20.869  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,09-12 13:11:20.869  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:20.869  1013  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:20.869  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-12 13:11:20.869  1013  3010 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:11:20.879  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.TrackDownloadQueueService; callingUser = 0; userId(target) = 0
,09-12 13:11:20.879  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:20.879  1013  3010 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:20.879  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:20.879  1013  1026 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
09-12 13:11:20.879  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.TrackCacheService; callingUser = 0; userId(target) = 0
,09-12 13:11:20.879  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:20.879  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:20.879  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:20.879  6635  6703 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,09-12 13:11:20.889  1013  1025 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:11:20.889  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 13:11:20.889  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:20.889  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:20.889  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:20.899  1013  1379 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,09-12 13:11:20.899  1013  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.wear.WearMetadataSyncService; callingUser = 0; userId(target) = 0
,09-12 13:11:20.899  1013  1379 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:20.899  1013  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:20.899  1013  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:20.929  1013  1471 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:20.929  1013  1471 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:20.929  1013  1471 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:20.929  1013  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,09-12 13:11:20.939  1926  1926 D WearableService: callingUid 10012, callindPid: 1926
,09-12 13:11:20.949  1013  3012 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,09-12 13:11:20.949  1013  3012 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,09-12 13:11:20.949  1013  3012 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:20.949  1013  3012 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:20.949  1013  3012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,09-12 13:11:20.989  6548  6862 I MusicLeanback: Conditions not met for autocaching.
09-12 13:11:20.989  6548  6862 I MusicLeanback: Stop autocaching.
,09-12 13:11:20.989   277  1005 E NetlinkEvent: Unknown ifindex 14 in RTM_DELADDR
,09-12 13:11:20.999  1013  1040 D Tethering: interfaceRemoved wlan0
,09-12 13:11:20.999  1013  1040 E Tethering: attempting to remove unknown iface (wlan0), ignoring
,09-12 13:11:21.009  6548  6548 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-12 13:11:21.009  6548  6868 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,09-12 13:11:21.069   287   287 E SMD     : DCD OFF
,09-12 13:11:21.239  1013  1040 D Tethering: interfaceRemoved p2p0
,09-12 13:11:21.239  1013  1040 E Tethering: attempting to remove unknown iface (p2p0), ignoring
,09-12 13:11:22.069  1013  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,09-12 13:11:22.289  6226  6276 D BluetoothAdapter: enable(),
,09-12 13:11:22.289  1013  3152 W ActivityManager: Permission Denial: getCurrentUser() from pid=6226, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:11:22.289  1013  3152 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-12 13:11:22.289  1013  3152 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6226, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:11:22.289  1013  3152 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 13:11:22.289  1013  3152 W BluetoothManagerService: 	,at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-12 13:11:22.289  1013  3152 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-12 13:11:22.289  1013  3152 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-12 13:11:22.289  1013  3152 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446),
,09-12 13:11:22.289  1013  3152 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-12 13:11:22.289  1013  3152 D SettingsProvider: name = bluetooth_on,
,09-12 13:11:22.289  1013  3152 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,09-12 13:11:22.299  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-12 13:11:22.299  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:11:22.299  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
09-12 13:11:22.299  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-12 13:11:22.339  6514  6514 D BluetoothAdapterState: make
,09-12 13:11:22.339  6514  6514 I bluedroid: init
,09-12 13:11:22.349  6514  6870 I BluetoothAdapterState: Entering OffState
,09-12 13:11:22.349  6514  6514 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf,
,09-12 13:11:22.349  6514  6514 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 13:11:22.349  6514  6514 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 13:11:22.349  6514  6514 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 13:11:22.349  6514  6514 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-12 13:11:22.349  6514  6514 I bluedroid: get_profile_interface socket
09-12 13:11:22.349  6514  6514 I bluedroid: get_profile_interface map_client
09-12 13:11:22.349  6514  6873 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
09-12 13:11:22.359  6514  6514 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,09-12 13:11:22.359  6514  6873 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-12 13:11:22.359  6514  6873 E BluetoothServiceJni: populateRssiValuesNative
09-12 13:11:22.359  6514  6873 I bluedroid: getModelRssiValues
09-12 13:11:22.359  6514  6873 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-12 13:11:22.359  6514  6873 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 13:11:22.359  6514  6873 D BluetoothAdapterProperties: Name is: A5-1
,09-12 13:11:22.359  1013  1013 D SettingsProvider: name = bluetooth_name
,09-12 13:11:22.369  6514  6514 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:22.369  1013  4556 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:11:22.369  1013  4556 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:11:22.369  1013  4556 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:22.369  1013  4556 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:22.369  1013  4556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:22.379  6514  6522 I bluedroid: config_hci_snoop_log
,09-12 13:11:22.379  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-12 13:11:22.379  1013  1042 D BluetoothManagerService: Ble is always on enable gatt
,09-12 13:11:22.379  1013  1042 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-12 13:11:22.379  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 13:11:22.379  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 13:11:22.389  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:11:22.389  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:11:22.389  6514  6514 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-12 13:11:22.399  1013  1042 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 13:11:22.399  6514  6870 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,09-12 13:11:22.399  6514  6870 D BluetoothAdapterProperties: Setting state to 11
,09-12 13:11:22.399  6514  6870 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 13:11:22.399  6514  6870 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:11:22.399  6514  6870 D BluetoothAdapterService: updateAdapterState state is 11
09-12 13:11:22.399  6514  6870 D BluetoothAdapterService: Autoconnection is available 
09-12 13:11:22.399  6514  6870 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-12 13:11:22.399  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-12 13:11:22.399  1013  1013 I InputMethodManagerService: [BT Setting State] State =11
,09-12 13:11:22.409  6514  6870 D BluetoothSecureManager: getInstant: null
,09-12 13:11:22.409  6514  6870 D BluetoothSecureManager: calling getMethod for getService
09-12 13:11:22.409  6514  6870 D BluetoothSecureManager: calling getService
,09-12 13:11:22.419  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:11:22.419  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:22.419  1176  1176 D BluetoothTile:  getBluetoothState : 11
,09-12 13:11:22.419  1770  1770 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:11:22.419  1359  1359 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:22.419  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
09-12 13:11:22.419  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 13:11:22.429  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:22.429  1013  1026 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:11:22.429  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:11:22.429  6514  6870 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@37c64261
09-12 13:11:22.429  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:22.429  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
09-12 13:11:22.429  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:22.429  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-12 13:11:22.429  1013  1670 D BluetoothSecureManagerService: isSecureModeEnabled
,09-12 13:11:22.429  1013  1670 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-12 13:11:22.429  6514  6870 D BtConfig.SecureMode: isSecureModeOn:false
09-12 13:11:22.429  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 13:11:22.429  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:22.429  6514  6870 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-12 13:11:22.429  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 13:11:22.439  1013  1473 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-12 13:11:22.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 13:11:22.439  1013  1796 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
09-12 13:11:22.439  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-12 13:11:22.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-12 13:11:22.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-12 13:11:22.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-12 13:11:22.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:22.439  1359  1359 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-12 13:11:22.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-12 13:11:22.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:22.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:22.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 13:11:22.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:11:22.439  6514  6870 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-12 13:11:22.449  6514  6870 D BluetoothBondStateMachine: make
,09-12 13:11:22.449  6514  6875 I BluetoothBondStateMachine: StableState(): Entering Off State
09-12 13:11:22.449  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-12 13:11:22.449  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 13:11:22.449  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 13:11:22.449  1013  4555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:22.449  1013  4555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
09-12 13:11:22.449  1013  4555 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:22.449  1013  4555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:22.449  1013  4555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:22.449  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 13:11:22.449  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 13:11:22.449  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 13:11:22.449  6514  6514 D BtGatt.DebugUtils: handleDebugAction() action=null
09-12 13:11:22.449  1013  3010 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:22.449  6514  6514 D BtGatt.GattService: Received start request. Starting profile...
09-12 13:11:22.449  6514  6514 D BtGatt.GattService: start()
09-12 13:11:22.449  6514  6514 D BtGatt.GattService: start()
09-12 13:11:22.449  6514  6514 I bluedroid: get_profile_interface gatt
,09-12 13:11:22.449  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
09-12 13:11:22.449  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
09-12 13:11:22.449  6514  6514 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:11:22.459  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:22.459  1013  3010 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:22.459  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:22.459  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 13:11:22.459  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 13:11:22.459  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 13:11:22.459  1013  3152 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:22.459  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:11:22.459  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:22.459  1013  3152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:22.459  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:22.459  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:11:22.459  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-12 13:11:22.459  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:11:22.459  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 13:11:22.459  1013  3152 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:22.459  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:11:22.469  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:22.469  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 13:11:22.469  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:22.469  1013  3152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:22.469  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:22.469  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-12 13:11:22.469  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 13:11:22.469  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 13:11:22.469  6514  6514 D BtGatt.GattService: mStartError = false
09-12 13:11:22.469  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:22.469  1013  3012 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:22.469  1013  3012 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 13:11:22.479  6514  6514 D HeadsetService: Received start request. Starting profile...
09-12 13:11:22.479  6514  6514 D HeadsetService: start()
,09-12 13:11:22.479  1013  3012 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:22.479  1013  3012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:22.479  1013  3012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:22.479  6514  6514 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 13:11:22.479  6514  6514 D HeadsetStateMachine: make
,09-12 13:11:22.479  6514  6514 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 13:11:22.479  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-12 13:11:22.479  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 13:11:22.479  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 13:11:22.489  1013  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:22.489  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:11:22.489  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:22.489  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:22.489  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:22.489  1013  4556 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-12 13:11:22.489  1013  4556 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-12 13:11:22.489  1013  4556 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:22.489  1013  4556 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:22.489  1013  4556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 13:11:22.489  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:22.499  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:22.499  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:22.499  1013  3152 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-12 13:11:22.499  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 13:11:22.499  1013  3152 W ActivityManager: userId = 0, bbcId = -10000,
09-12 13:11:22.499  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:22.499  1013  3152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:22.499  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:11:22.499  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
09-12 13:11:22.499  6514  6514 I bluedroid: get_profile_interface handsfree
09-12 13:11:22.499  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:22.499  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:22.499  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:22.509  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
09-12 13:11:22.509  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 13:11:22.509  6514  6870 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 13:11:22.509  1013  1670 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:22.509  1013  1670 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:11:22.519  1013  1670 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:22.519  1013  1670 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:22.519  1013  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:22.519  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:11:22.519  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:22.519  6514  6870 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:22.519  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:22.519  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:22.519  6514  6870 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:22.519  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 13:11:22.519  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 13:11:22.519  6514  6870 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 13:11:22.519  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 13:11:22.519  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:11:22.519  6514  6870 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 13:11:22.519  6514  6514 I DualScoManager: Instantiating Dual Sco Manager
09-12 13:11:22.519  6514  6514 I DualScoManager: Set HeadsetServiceHelper
09-12 13:11:22.519  6514  6870 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
09-12 13:11:22.519  6514  6514 D BluetoothAtMessage: createCMTIContentObservers
,09-12 13:11:22.519  1013  3011 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-12 13:11:22.519  1013  3011 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:22.519  1013  3011 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:22.519  1013  3011 D SettingsProvider: selectionArgs: false
,09-12 13:11:22.519  1013  3011 D SettingsProvider: selectionArgs: 1002
09-12 13:11:22.519  1013  3011 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:22.519  1013  3011 D SettingsProvider: ret = -1
,09-12 13:11:22.529  6514  6514 D HeadsetService: mStartError = false
,09-12 13:11:22.529  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:22.529  6514  6881 D HeadsetStateMachine: Enter Disconnected: -2,
09-12 13:11:22.529  6514  6514 D A2dpService: Received start request. Starting profile...
09-12 13:11:22.529  6514  6514 D A2dpService: start()
,09-12 13:11:22.529  6514  6881 D HeadsetStateMachine: Clear mHeadsetBrsf
09-12 13:11:22.529  6514  6514 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 13:11:22.529  6514  6881 D HeadsetStateMachine: map size, before remove : 0
,09-12 13:11:22.529  6514  6881 D HeadsetStateMachine: map size, after remove: 0
,09-12 13:11:22.529  6514  6514 I bluedroid: get_profile_interface avrcp
,09-12 13:11:22.539  6514  6514 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:11:22.549  6514  6514 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-12 13:11:22.559  6514  6882 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-12 13:11:22.559  6514  6514 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 13:11:22.559  6514  6514 D A2dpStateMachine: make
,09-12 13:11:22.559  6514  6514 I bluedroid: get_profile_interface a2dp
,09-12 13:11:22.559  6514  6884 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 13:11:22.559  6514  6514 E bt-btif : warning : media task started media_task_refcnt 1 
,09-12 13:11:22.559  6514  6514 D A2dpService: mStartError = false
09-12 13:11:22.559  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:22.559  6514  6514 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 13:11:22.559  6514  6514 D HidService: Received start request. Starting profile...
09-12 13:11:22.559  6514  6514 D HidService: start()
09-12 13:11:22.559  6514  6514 I bluedroid: get_profile_interface hidhost
09-12 13:11:22.559  6514  6514 D HidService: setHidService(): set to: null
09-12 13:11:22.559  6514  6514 D HidService: mStartError = false
09-12 13:11:22.559  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:22.559  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
09-12 13:11:22.559  6514  6883 D A2dpStateMachine: Enter Disconnected: -2
,09-12 13:11:22.569  6514  6514 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 13:11:22.569  6514  6514 D HealthService: Received start request. Starting profile...
09-12 13:11:22.569  6514  6514 D HealthService: start()
,09-12 13:11:22.569  6514  6882 D BluetoothMediaBrowser: no now playing list
,09-12 13:11:22.569  6514  6882 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,09-12 13:11:22.569  6514  6514 I bluedroid: get_profile_interface health
09-12 13:11:22.569  6514  6514 D HealthService: mStartError = false
09-12 13:11:22.569  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:22.569  6514  6514 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:11:22.569  6514  6514 D PanService: Received start request. Starting profile...
09-12 13:11:22.569  6514  6514 D PanService: start()
09-12 13:11:22.569  6514  6514 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:11:22.569  6514  6514 I bluedroid: get_profile_interface pan
,09-12 13:11:22.569  6514  6514 D PanService: mStartError = false
09-12 13:11:22.569  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:22.569  6514  6514 D HeadsetStateMachine: Try to query the phonestate on bind
,09-12 13:11:22.569  1428  1436 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 13:11:22.579  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
,09-12 13:11:22.579  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 13:11:22.579  1428  1436 I Telecom : BluetoothPhoneService: Result of Message : true
,09-12 13:11:22.579  6514  6514 D HeadsetStateMachine: Proxy object connected
,09-12 13:11:22.579  6514  6514 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,09-12 13:11:22.579  6514  6514 D BluetoothMapService: Received start request. Starting profile...
09-12 13:11:22.579  6514  6514 D BluetoothMapService: start()
,09-12 13:11:22.579  6514  6881 D HeadsetStateMachine: Disconnected process message: 11
,09-12 13:11:22.589  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:11:22.589  6514  6514 D BluetoothMapService: mStartError = false,
09-12 13:11:22.589  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:22.589  6514  6514 D HeadsetPhoneState: sendDeviceDataStateChanged
09-12 13:11:22.589  6514  6514 D HeadsetPhoneState: Signal level : previous=0 curr=0
,09-12 13:11:22.589  6514  6514 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-12 13:11:22.589  6514  6881 D HeadsetStateMachine: Disconnected process message: 18
,09-12 13:11:22.589  6514  6514 D SapService: Received start request. Starting profile...
09-12 13:11:22.589  6514  6514 D SapService: start()
09-12 13:11:22.589  6514  6514 D BluetoothSAPServiceJni: initializeNative(L209): sap
09-12 13:11:22.589  6514  6514 I bluedroid: get_profile_interface sap
09-12 13:11:22.589  6514  6514 D SapService: mStartError = false
09-12 13:11:22.589  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:22.589  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 13:11:22.589  6514  6514 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 13:11:22.589  6514  6514 D BluetoothA2dp: Proxy object connected
09-12 13:11:22.589  6514  6514 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-12 13:11:22.589  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 13:11:22.589  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,09-12 13:11:22.589  6514  6881 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:11:22.589  6514  6881 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:11:22.589  6514  6881 D HeadsetStateMachine: Disconnected process message: 11
,09-12 13:11:22.599  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
09-12 13:11:22.599  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,09-12 13:11:22.599  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:11:22.629  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-12 13:11:22.629  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-12 13:11:22.629  6514  6870 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
09-12 13:11:22.629  6514  6870 I bluedroid: enable
,09-12 13:11:22.629  6514  6889 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-12 13:11:22.629  6514  6870 I bt_hci_bdroid: init
,09-12 13:11:22.639  6514  6870 I bt_vendor: bt-vendor : init
,09-12 13:11:22.639  6514  6870 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 13:11:22.639  6514  6870 E bt_vendor: get_bt_soc_type: Failed to get soc type
,09-12 13:11:22.639  6514  6870 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-12 13:11:22.639  6514  6870 D bt_userial_mct: userial_init
,09-12 13:11:22.639  6514  6870 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-12 13:11:22.639  6514  6870 I bt_vendor: Starting hciattach daemon
09-12 13:11:22.639  6514  6870 I bt_vendor: try to set false
,09-12 13:11:22.639  6514  6870 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
,09-12 13:11:22.639  6514  6870 I bt_vendor: Starting hciattach daemon
09-12 13:11:22.639  6514  6870 I bt_vendor: try to set true
,09-12 13:11:22.659  6893  6893 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-12 13:11:22.699  6899  6899 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-12 13:11:22.709  6900  6900 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 13:11:22.729  6902  6902 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 13:11:22.729  6903  6903 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-12 13:11:22.739  6904  6904 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 13:11:22.749  6905  6905 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-12 13:11:22.949  6908  6908 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-12 13:11:22.959  6909  6909 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 13:11:23.009  6514  6870 I bt_vendor: bluetooth satus is on,
09-12 13:11:23.009  6514  6891 D bt_userial_mct: userial_open(port:0)
09-12 13:11:23.009  6514  6891 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-12 13:11:23.009  6514  6891 I bt_vendor: Done intiailizing UART,
,09-12 13:11:23.009  6514  6891 I bt_vendor: Done intiailizing UART,
09-12 13:11:23.009  6514  6891 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67,
,09-12 13:11:23.009  6514  6891 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_HCI,
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_A2D
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_GAP
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_SAP
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_SDP
,09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_SMP
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_BTIF
09-12 13:11:23.009  6514  6889 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,09-12 13:11:23.009  6514  6911 D bt_userial_mct: Entering userial_read_thread()
,09-12 13:11:23.109  6514  6889 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-12 13:11:23.129  6514  6889 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa3f496e9 
,09-12 13:11:23.129  6514  6889 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa3f496e9 
,09-12 13:11:23.139  6514  6873 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-12 13:11:23.149  6514  6873 E bt-btif : Calling BTA_HhEnable
,09-12 13:11:23.149  6514  6873 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-12 13:11:23.149  6514  6873 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-12 13:11:23.149  6514  6873 E BluetoothServiceJni: populateRssiValuesNative
,09-12 13:11:23.149  6514  6873 I bluedroid: getModelRssiValues
,09-12 13:11:23.149  6514  6873 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-12 13:11:23.149  6514  6873 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 13:11:23.149  1013  1013 D SettingsProvider: name = bluetooth_name
,09-12 13:11:23.149  6514  6873 D BluetoothAdapterProperties: Name is: A5-1
,09-12 13:11:23.159  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:23.159  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:23.159  6514  6873 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-12 13:11:23.159  6514  6873 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:11:23.159  6514  6873 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:11:23.169  6514  6873 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-12 13:11:23.169  6514  6873 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
09-12 13:11:23.169  6514  6873 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-12 13:11:23.169  6514  6873 E bt-btif : btif_sock_init: !radio_req && !rfc_init
09-12 13:11:23.169  6514  6873 E bt-btif : btif_sock_init: !vhci_init
,09-12 13:11:23.169  6514  6873 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,09-12 13:11:23.169  6514  6873 D IOP_DB_BT: db_open: db_open : handle 3023568912l, read 13894 bytes onto local cache
,09-12 13:11:23.169  6514  6911 E bt_mct  : hci lib postload completed
,09-12 13:11:23.169  6514  6873 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-12 13:11:23.169  6514  6873 D IOP_DB_BT: db_query: result 1
09-12 13:11:23.169  6514  6873 I         : iop_db_open: iop_db_open status 0
,09-12 13:11:23.169  6514  6873 D bte_conf: Device ID record 1 : primary
09-12 13:11:23.169  6514  6873 D bte_conf:   vendorId            = 0075
09-12 13:11:23.169  6514  6873 D bte_conf:   vendorIdSource      = 0001
09-12 13:11:23.169  6514  6873 D bte_conf:   product             = 0100
09-12 13:11:23.169  6514  6873 D bte_conf:   version             = 0200
09-12 13:11:23.169  6514  6873 D bte_conf:   clientExecutableURL = 
09-12 13:11:23.169  6514  6873 D bte_conf:   serviceDescription  = 
09-12 13:11:23.169  6514  6873 D bte_conf:   documentationURL    = 
09-12 13:11:23.169  6514  6873 D bte_conf: bte_load_did_conf no section named DID2.
09-12 13:11:23.179  6514  6873 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 13:11:23.179  6514  6870 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-12 13:11:23.179  6514  6870 D BluetoothAdapterProperties: ScanMode =  20
09-12 13:11:23.179  6514  6870 D BluetoothAdapterProperties: State =  11
,09-12 13:11:23.179  1013  1379 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-12 13:11:23.179  6514  6870 D BluetoothAdapterProperties: Setting state to 12
09-12 13:11:23.179  6514  6870 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 13:11:23.179  6514  6873 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:11:23.179  6514  6873 D BluetoothAdapterProperties: Scan Mode:21
09-12 13:11:23.179  6514  6873 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:11:23.189  1013  1137 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-12 13:11:23.189  1013  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:23.189  1013  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:23.189  1013  1137 D SettingsProvider: selectionArgs: false
09-12 13:11:23.189  1013  1137 D SettingsProvider: selectionArgs: 1002
09-12 13:11:23.189  1013  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:23.189  1013  1137 D SettingsProvider: ret = -1
09-12 13:11:23.189  6514  6870 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:11:23.189  6514  6870 D BluetoothAdapterService: updateAdapterState state is 12
,09-12 13:11:23.189  1013  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
,09-12 13:11:23.189  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.189  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.189  1013  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.189  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.199  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:23.199  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:23.199  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:23.199  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:23.199  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:23.199  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:23.199  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:23.199  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:23.209  6514  6870 D BluetoothAdapterService: Autoconnection is available 
09-12 13:11:23.209  6514  6870 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 13:11:23.209  6514  6870 D BluetoothAdapterService: starting service from this receiver
,09-12 13:11:23.209  6514  6523 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:11:23.209  1359  1373 D BluetoothPan: Binding service...
09-12 13:11:23.209  1013  3012 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:23.209  1013  3012 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.209  1013  3012 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.209  1013  3012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.209  1013  3012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.209  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null,
,09-12 13:11:23.209  6514  6870 I BluetoothAdapterState: Entering On State from state = 11
,09-12 13:11:23.219  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 13:11:23.219  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.219  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:23.219  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:23.219  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:23.219  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:23.219  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:23.219  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:23.219  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:23.219  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:23.219  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:23.219  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:23.229  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:23.229  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.229  1452  1761 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:11:23.229  1452  1761 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:23.229  1176  1186 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:11:23.229  1176  1186 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:23.229  6514  6514 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-12 13:11:23.229  1428  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:23.229  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 13:11:23.229  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:23.239  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:23.239  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.239  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.239  1428  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:23.239  6514  6514 I BluetoothPbapService: Handler(): got msg=1
,09-12 13:11:23.249  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:11:23.249  1359  1359 D PanProfile: Bluetooth service connected
09-12 13:11:23.249  1013  3011 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 13:11:23.249  1428  6699 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:23.249  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:11:23.249  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:23.249  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.249  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.249  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.249  1428  6699 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:23.249  1428  1436 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:23.249  6514  6915 V BluetoothPbapService: PBAP Service initSocket try: 0
09-12 13:11:23.249  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:11:23.249  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:23.249  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.249  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.249  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-12 13:11:23.249  1428  1436 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:23.259  2851  2863 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:23.259  1013  1042 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:11:23.259  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:23.259  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.259  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.259  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.259  2851  2863 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:23.259  2851  2863 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:23.259  2851  2863 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:23.259  1452  1470 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:23.259  1013  1042 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:11:23.259  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:23.259  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.259  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.259  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.259  1452  1470 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:23.259  6514  6915 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 13:11:23.259  6514  6915 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:11:23.259  6226  6235 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:23.259  6226  6235 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:11:23.259  1013  1042 D BluetoothPan: Binding service...
,09-12 13:11:23.269  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 13:11:23.269  1359  1373 D Bluetoothsap: onBluetoothStateChange: up=true
09-12 13:11:23.269  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
09-12 13:11:23.269  1359  1373 D Bluetoothsap: Binding service...
,09-12 13:11:23.269  1013  1013 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:11:23.269  6514  6915 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-12 13:11:23.269  6514  6915 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:11:23.269  6514  6915 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:11:23.269  6514  6915 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@364ef06c
,09-12 13:11:23.269  1359  1373 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-12 13:11:23.269  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,09-12 13:11:23.269  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
09-12 13:11:23.269  6514  6915 D BluetoothSocket: channel: 19
,09-12 13:11:23.269  6514  6915 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
09-12 13:11:23.269  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.269  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.269  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.269  1359  1373 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 13:11:23.269  1442  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:23.269  1442  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:23.269  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:11:23.269  1013  1042 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:23.269  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:11:23.269  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-12 13:11:23.269  1013  1013 D BluetoothA2dp: Proxy object connected
,09-12 13:11:23.279  1359  1373 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:23.279  1359  1359 D Bluetoothsap: BluetoothSAP Proxy object connected
09-12 13:11:23.279  1359  1359 D SapProfile: Bluetooth service connected
09-12 13:11:23.279  1359  1359 D Bluetoothsap: getConnectedDevices()
,09-12 13:11:23.279  1359  1373 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:23.279  1428  1436 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:23.279  1428  1436 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:23.279  1359  1368 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 13:11:23.279  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-12 13:11:23.279  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.279  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:23.279  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:23.279  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.279  1359  1359 D BluetoothMap: Proxy object connected
,09-12 13:11:23.279  1359  1359 D MapProfile: Bluetooth service connected
,09-12 13:11:23.279  1359  1359 D BluetoothMap: getConnectedDevices()
09-12 13:11:23.279  1926  2106 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:23.279  1926  2106 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:23.279  1013  1042 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
09-12 13:11:23.279  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:11:23.289  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:23.289  1013  1042 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:23.289  1359  6917 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:23.289  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:11:23.289  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:23.289  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.289  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.289  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.289  1359  6917 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:23.289  6514  6697 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:23.289  6514  6697 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:11:23.289  1359  6917 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 13:11:23.289  1359  1359 D HeadsetProfile: Bluetooth service connected
,09-12 13:11:23.289  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-12 13:11:23.289  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.289  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.289  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.289  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.289  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:23.289  1013  1042 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:11:23.289  1359  1373 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:11:23.289  1359  1373 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:23.289  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:11:23.289  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.299  1359  1359 D BluetoothPbap: Proxy object connected
09-12 13:11:23.299  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.299  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.299  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.299  1359  1359 D PbapServerProfile: Bluetooth service connected
,09-12 13:11:23.299  1359  1359 D BluetoothA2dp: Proxy object connected
09-12 13:11:23.299  6391  6400 D BluetoothAdapter: onBluetoothStateChange: up=true,
09-12 13:11:23.299  6391  6400 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:11:23.299  1359  1359 D A2dpProfile: Bluetooth service connected
09-12 13:11:23.299  1359  1368 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 13:11:23.299  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-12 13:11:23.299  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.299  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.299  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.299  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.299  2851  2859 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:11:23.299  2851  2859 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:23.299  1359  1359 D BluetoothInputDevice: Proxy object connected
09-12 13:11:23.299  1013  1042 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:11:23.299  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.299  1359  1359 D HidProfile: Bluetooth service connected
09-12 13:11:23.299  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.299  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.299  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.299  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 13:11:23.299  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 13:11:23.309  2851  2851 D BluetoothA2dp: Proxy object connected
,09-12 13:11:23.309  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:23.309  1013  1013 I InputMethodManagerService: [BT Setting State] State =12
,09-12 13:11:23.309  1013  1013 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 13:11:23.309  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2a67e428, true
09-12 13:11:23.309  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,09-12 13:11:23.319  1428  1428 D BluetoothHeadset: registerMessageListener
,09-12 13:11:23.319  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:11:23.319  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:23.319  1176  1176 D BluetoothTile:  getBluetoothState : 12
09-12 13:11:23.319  1770  1770 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:11:23.319  1359  1359 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:23.319  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:11:23.329  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:23.329  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:23.329  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:11:23.329  1013  3001 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:23.329  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.329  6514  6523 D HeadsetService: registerMessageListener
,09-12 13:11:23.329  6514  6523 D HeadsetService: registerMessageListener
,09-12 13:11:23.329  6514  6881 D HeadsetStateMachine: Disconnected process message: 70
,09-12 13:11:23.329  6514  6881 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@c657635
09-12 13:11:23.329  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:23.329  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
09-12 13:11:23.329  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 13:11:23.329  1013  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:23.329  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:23.339  6514  6920 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-12 13:11:23.339  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:11:23.339  1359  1359 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-12 13:11:23.339  1359  1359 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-12 13:11:23.339  1359  1359 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 13:11:23.339  1359  1359 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,09-12 13:11:23.339  1013  1471 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:11:23.339  1013  3152 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
09-12 13:11:23.339  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-12 13:11:23.339  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
,09-12 13:11:23.339  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
09-12 13:11:23.339  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:11:23.339  6514  6920 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:11:23.339  6514  6920 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:11:23.339  6514  6920 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-12 13:11:23.339  6514  6920 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:11:23.339  6514  6920 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:11:23.339  6514  6920 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1335aaca
,09-12 13:11:23.339  6514  6920 D BluetoothSocket: channel: 5
,09-12 13:11:23.339  6514  6881 D HeadsetStateMachine: Disconnected process message: 9
,09-12 13:11:23.349  6514  6881 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-12 13:11:23.349   282   682 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
09-12 13:11:23.349   282   682 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-12 13:11:23.349   282   682 V voice   : voice_set_parameters: exit with code(-2)
09-12 13:11:23.349   282   682 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 13:11:23.349   282   682 V msm8974_platform: platform_set_parameters: exit with code(-2)
09-12 13:11:23.349   282   682 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 13:11:23.349   282   682 V audio_hw_primary: adev_set_parameters: exit
09-12 13:11:23.349  6514  6881 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-12 13:11:23.359  1359  1359 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:11:23.359  1013  1026 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 13:11:23.359  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.359  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.359  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:23.359  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:11:23.369  1359  1359 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:11:23.369  1359  1359 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:11:23.379  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:23.379  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 13:11:23.379  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:23.379  6514  6514 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 13:11:23.399  1013  3010 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:23.399  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.399  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:23.399  1013  3010 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:23.399  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:23.409  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:11:23.409  1013  3001 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:11:23.409  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 13:11:23.409  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:23.409  1013  3001 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:23.409  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:23.419  1926  6926 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 13:11:23.419  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:11:23.449  1013  1025 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,09-12 13:11:23.449  1013  1025 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4157, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,09-12 13:11:23.449  1013  1025 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,09-12 13:11:23.459  1013  1025 D BatteryService: stay LED for charging
09-12 13:11:23.459  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:11:23.459  1013  1013 I MotionRecognitionService: Plugged
,09-12 13:11:23.459  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
,09-12 13:11:23.459  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,09-12 13:11:23.459  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:11:23.459  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-12 13:11:23.459  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
,09-12 13:11:23.479  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,09-12 13:11:23.479  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,09-12 13:11:23.489  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,09-12 13:11:23.549  1926  1926 I art     : Explicit concurrent mark sweep GC freed 59387(3MB) AllocSpace objects, 42(1605KB) LOS objects, 40% free, 14MB/24MB, paused 1.478ms total 76.675ms
,09-12 13:11:23.579  1013  1473 I art     : Explicit concurrent mark sweep GC freed 66063(3MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 2.565ms total 151.158ms
,09-12 13:11:23.579  1013  1473 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:23.579  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.579  1013  1473 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:23.579  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:23.579  6514  6514 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,09-12 13:11:23.589  6514  6881 D HeadsetStateMachine: Disconnected process message: 10
,09-12 13:11:23.589  1013  1218 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,09-12 13:11:23.589  1013  1026 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:23.599  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:23.599  1013  1026 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:23.599  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:23.599  1926  6926 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
09-12 13:11:23.599  6514  6930 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:11:23.599  6514  6930 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:11:23.609  6514  6930 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
09-12 13:11:23.609  6514  6930 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:11:23.609  6514  6930 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:11:23.609  6514  6930 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@96ba996
,09-12 13:11:23.609  6514  6930 D BluetoothSocket: channel: 12
09-12 13:11:23.609  6514  6930 I BtOppRfcommListener: Accept thread started.
,09-12 13:11:24.019  1013  2767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,09-12 13:11:24.059   287   287 E SMD     : DCD OFF,
,09-12 13:11:24.429  1013  2724 D SSRM:n  : SIOP:: AP = 360
,09-12 13:11:25.309  6226  6276 D BluetoothAdapter: disable()
,09-12 13:11:25.309  1013  4555 D SettingsProvider: name = bluetooth_on
,09-12 13:11:25.309  6514  6870 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,09-12 13:11:25.309  6514  6870 D BluetoothAdapterProperties: Setting state to 13
09-12 13:11:25.309  6514  6870 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-12 13:11:25.309  6514  6870 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:11:25.309  6514  6870 D BluetoothAdapterService: updateAdapterState state is 13
09-12 13:11:25.309  1013  4556 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:25.319  1013  4556 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:11:25.319  1013  4556 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:25.319  1013  4556 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:25.319  1013  4556 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:25.319  6514  6514 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,09-12 13:11:25.319  6514  6870 D BluetoothAdapterService: Autoconnection is available 
09-12 13:11:25.319  6514  6870 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,09-12 13:11:25.319  6514  6870 D BluetoothAdapterService: terminating service from this receiver
,09-12 13:11:25.319  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 13:11:25.319  6514  6514 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@10871917, channel: 19, state: LISTENING
09-12 13:11:25.319  6514  6514 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@10871917, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@364ef06c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@31f4e104mSocket: android.net.LocalSocket@2eeb36ed impl:android.net.LocalSocketImpl@d30c922 fd:FileDescriptor[75]
09-12 13:11:25.319  6514  6514 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2eeb36ed impl:android.net.LocalSocketImpl@d30c922 fd:FileDescriptor[75]
,09-12 13:11:25.319  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:25.319  1013  3152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:25.319  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:25.329  6514  6870 D BluetoothAdapterProperties: onBluetoothDisable()
09-12 13:11:25.329  6514  6870 D BluetoothAdapterProperties: mDiscovering is false
,09-12 13:11:25.329  1013  1137 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-12 13:11:25.329  6514  6870 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,09-12 13:11:25.329  1359  1359 D BluetoothPbap: Proxy object disconnected
,09-12 13:11:25.329  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED,
09-12 13:11:25.329  1359  1359 D PbapServerProfile: Bluetooth service disconnected
,09-12 13:11:25.329  1013  1013 I InputMethodManagerService: [BT Setting State] State =13
,09-12 13:11:25.339  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,09-12 13:11:25.339  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:11:25.339  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 13:11:25.349  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:25.349  1176  1176 D BluetoothTile:  getBluetoothState : 13
,09-12 13:11:25.349  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:11:25.349  1770  1770 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:11:25.349  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 13:11:25.359  1359  1359 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:25.359  1013  1670 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:11:25.359  1013  1137 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:11:25.359  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:25.359  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:25.359  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:25.359  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:25.359  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:25.359  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:25.359  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:25.359  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:25.359  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:25.359  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:11:25.369  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-12 13:11:25.369  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:25.369  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value,
09-12 13:11:25.369  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:25.369  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:25.369  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:25.369  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:25.369  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-12 13:11:25.369  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:25.369  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:25.369  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:25.369  6226  6226 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-12 13:11:25.369  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:25.369  1013  1025 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:11:25.369  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:11:25.369  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:25.369  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:25.369  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:25.379  6514  6873 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:11:25.379  6514  6873 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:11:25.379  6514  6870 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,09-12 13:11:25.379  6514  6870 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,09-12 13:11:25.379  1359  1359 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:11:25.379  6514  6870 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,09-12 13:11:25.379  6514  6870 E bt-btif : cmd socket is not created
,09-12 13:11:25.379  6514  6870 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
09-12 13:11:25.379  6514  6930 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,09-12 13:11:25.379  6514  6889 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
09-12 13:11:25.379  6514  6889 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-12 13:11:25.379  6514  6889 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:11:25.379  6514  6889 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 13:11:25.379  6514  6889 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 13:11:25.389  1013  3152 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 13:11:25.389  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:11:25.389  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:25.389  1013  3152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:25.389  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:25.389  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:11:25.389  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:25.409  1359  1359 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:11:25.409  6514  6514 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@21610970, channel: 5, state: LISTENING
,09-12 13:11:25.409  6514  6514 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@21610970, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1335aaca, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d154e9mSocket: android.net.LocalSocket@3d36556e impl:android.net.LocalSocketImpl@1f3e140f fd:FileDescriptor[77]
,09-12 13:11:25.409  6514  6514 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3d36556e impl:android.net.LocalSocketImpl@1f3e140f fd:FileDescriptor[77]
09-12 13:11:25.409  6514  6514 I BtOppRfcommListener: stopping Accept Thread
09-12 13:11:25.409  6514  6514 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a254c9c, channel: 12, state: LISTENING
09-12 13:11:25.409  6514  6514 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@a254c9c, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@96ba996, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@be156a5mSocket: android.net.LocalSocket@1ff65a7a impl:android.net.LocalSocketImpl@1fd1e22b fd:FileDescriptor[79]
09-12 13:11:25.409  6514  6514 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1ff65a7a impl:android.net.LocalSocketImpl@1fd1e22b fd:FileDescriptor[79],
09-12 13:11:25.419  6514  6930 I BtOppRfcommListener: BluetoothSocket listen thread finished
,09-12 13:11:25.419  1359  1359 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:11:25.419  6514  6514 V BluetoothOppManager: cleanUp...
,09-12 13:11:25.419  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:25.429  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 13
,09-12 13:11:25.439  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:11:25.449  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:11:25.579  6514  6889 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,09-12 13:11:25.579  6514  6889 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-12 13:11:25.589  6514  6911 I bt_userial_mct: exiting userial_read_thread,
09-12 13:11:25.589  6514  6911 D bt_userial_mct: Leaving userial_evt_read_thread()
09-12 13:11:25.589  6514  6873 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
09-12 13:11:25.589  6514  6891 I bt_vendor: hw_epilog_process,
09-12 13:11:25.589  6514  6889 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:11:25.589  6514  6889 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:11:25.589  6514  6889 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:11:25.589  6514  6889 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,09-12 13:11:25.589  6514  6889 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-12 13:11:25.589  6514  6889 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-12 13:11:25.589  6514  6889 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
09-12 13:11:25.589  6514  6889 W bt-btif : ag scb idx 1 not allocated
09-12 13:11:25.589  6514  6889 W bt-btif : ag scb idx 2 not allocated,
09-12 13:11:25.589  6514  6889 E bt-btif : BTA AG is already disabled, ignoring ...
09-12 13:11:25.589  6514  6873 D bt_userial_mct: userial_close
09-12 13:11:25.589  6514  6873 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,09-12 13:11:25.639  1013  1297 E Watchdog: !@Sync 4
,09-12 13:11:26.069   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:11:26.439  6514  6873 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,09-12 13:11:26.439  6514  6873 I bt_vendor: bluetooth satus is on
,09-12 13:11:26.439  6514  6873 I bt_vendor: bt-vendor : resetting BT status
09-12 13:11:26.439  6514  6873 I bt_vendor: Starting hciattach daemon
,09-12 13:11:26.439  6514  6873 I bt_vendor: try to set false
09-12 13:11:26.439  6514  6873 I bt_vendor: Starting hciattach daemon
09-12 13:11:26.439  6514  6873 I bt_vendor: try to set false
,09-12 13:11:26.439  6514  6873 I bt_vendor: cleanup
,09-12 13:11:26.439  6514  6889 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
09-12 13:11:26.439  6514  6873 I GKI_LINUX: GKI_exit_task 0 done
,09-12 13:11:26.439  6514  6873 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,09-12 13:11:26.439  6514  6870 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,09-12 13:11:26.439  6514  6870 D BtConfig.SecureMode: isSecureModeOn:false
09-12 13:11:26.439  6514  6870 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,09-12 13:11:26.439  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService,
09-12 13:11:26.439  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 13:11:26.439  1013  4555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
09-12 13:11:26.439  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 13:11:26.439  1013  4555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0,
09-12 13:11:26.449  1013  4555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:26.449  1013  1473 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:26.449  1013  4555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:26.449  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0,
09-12 13:11:26.449  1013  4555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:11:26.449  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService,
,09-12 13:11:26.449  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService,
09-12 13:11:26.449  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
09-12 13:11:26.449  6514  6514 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:11:26.449  6514  6514 D BtGatt.GattService: Received stop request...Stopping profile...
09-12 13:11:26.449  6514  6514 D BtGatt.GattService: stop(),
09-12 13:11:26.449  6514  6514 D BtGatt.AdvertiseManager: advertise clients cleared
09-12 13:11:26.449  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:26.449  1013  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:26.449  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:11:26.459  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
09-12 13:11:26.459  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,09-12 13:11:26.459  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 13:11:26.459  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
09-12 13:11:26.459  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:26.459  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:11:26.459  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:26.459  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:26.459  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
09-12 13:11:26.459  6514  6514 D HeadsetService: Received stop request...Stopping profile...
,09-12 13:11:26.459  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-12 13:11:26.459  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:11:26.459  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 13:11:26.459  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
09-12 13:11:26.459  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:26.459  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:11:26.459  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:26.469  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:26.469  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:26.469  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,09-12 13:11:26.469  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
09-12 13:11:26.469  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 13:11:26.469  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 13:11:26.469  1013  3152 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:26.469  1359  1359 D HeadsetProfile: Bluetooth service disconnected
09-12 13:11:26.469  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 13:11:26.469  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:26.469  1013  3152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:26.469  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:26.469  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
09-12 13:11:26.469  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 13:11:26.469  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 13:11:26.469  1013  3011 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:26.469  1013  3011 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:11:26.479  1013  3011 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:26.479  1013  3011 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:26.479  1013  3011 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:26.479  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:26.479  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:26.479  6514  6870 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:26.479  1013  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:26.479  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:11:26.479  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:26.479  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:26.479  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:26.479  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-12 13:11:26.479  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 13:11:26.479  6514  6870 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 13:11:26.489  1013  3010 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:26.489  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:11:26.489  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:26.489  1013  3010 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:26.489  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:26.489  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:11:26.489  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:11:26.489  6514  6870 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:11:26.489  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:26.489  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:26.489  6514  6870 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService,
09-12 13:11:26.489  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 13:11:26.489  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 13:11:26.489  6514  6870 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService,
09-12 13:11:26.489  6514  6870 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 13:11:26.489  6514  6870 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:11:26.489  6514  6870 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService,
09-12 13:11:26.489  6514  6870 D BluetoothAdapterState: Stopping profile services that were post enabled
,09-12 13:11:26.489  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
09-12 13:11:26.489  6514  6514 D A2dpService: Received stop request...Stopping profile...,
09-12 13:11:26.499  6514  6883 D A2dpStateMachine: Exit Disconnected: -1
,09-12 13:11:26.499  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:26.499  1013  1013 D BluetoothA2dp: Proxy object disconnected
,09-12 13:11:26.499  1013  1013 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,09-12 13:11:26.499  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,09-12 13:11:26.499  6514  6514 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:11:26.499  6514  6514 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,09-12 13:11:26.499  2851  2851 D BluetoothA2dp: Proxy object disconnected
09-12 13:11:26.499  6514  6514 D HidService: Received stop request...Stopping profile...
09-12 13:11:26.499  6514  6514 D HidService: Stopping Bluetooth HidService
09-12 13:11:26.499  6514  6514 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-12 13:11:26.499  6514  6514 W bt-btif : cleanup: HH disabling or disabled already, status = 0
09-12 13:11:26.499  6514  6514 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-12 13:11:26.499  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:26.499  1359  1359 D BluetoothA2dp: Proxy object disconnected
,09-12 13:11:26.509  1359  1359 D A2dpProfile: Bluetooth service disconnected
,09-12 13:11:26.509  1359  1359 D BluetoothInputDevice: Proxy object disconnected
09-12 13:11:26.509  1359  1359 D HidProfile: Bluetooth service disconnected
,09-12 13:11:26.509  6514  6514 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-12 13:11:26.509  6514  6514 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,09-12 13:11:26.509  6514  6514 D HealthService: Received stop request...Stopping profile...
,09-12 13:11:26.509  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:26.509  6514  6514 D PanService: Received stop request...Stopping profile...
09-12 13:11:26.509  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:26.509  1013  1013 D BluetoothPan: BluetoothPAN Proxy object disconnected
,09-12 13:11:26.509  6514  6514 D BluetoothMapService: Received stop request...Stopping profile...
,09-12 13:11:26.519  1359  1359 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-12 13:11:26.519  1359  1359 D PanProfile: Bluetooth service disconnected
,09-12 13:11:26.519  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:26.519  6514  6514 D SapService: Received stop request...Stopping profile...
,09-12 13:11:26.519  6514  6514 D SapService: Stopping Bluetooth SapService
09-12 13:11:26.519  6514  6514 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:26.519  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
09-12 13:11:26.519  6514  6514 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:11:26.519  6514  6514 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
09-12 13:11:26.519  6514  6514 D BluetoothA2dp: Proxy object disconnected
09-12 13:11:26.519  6514  6514 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,09-12 13:11:26.519  6514  6884 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
09-12 13:11:26.519  6514  6514 I GKI_LINUX: GKI_exit_task 2 done
09-12 13:11:26.519  6514  6514 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,09-12 13:11:26.519  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
09-12 13:11:26.519  6514  6514 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:26.519  6514  6514 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:26.519  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
09-12 13:11:26.519  6514  6514 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:26.519  6514  6514 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:26.519  6514  6514 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-12 13:11:26.519  6514  6514 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-12 13:11:26.519  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
09-12 13:11:26.519  6514  6514 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:26.519  6514  6514 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:26.519  6514  6514 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,09-12 13:11:26.519  6514  6514 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-12 13:11:26.519  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
09-12 13:11:26.519  6514  6514 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
09-12 13:11:26.519  6514  6514 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,09-12 13:11:26.519  6514  6514 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
09-12 13:11:26.519  6514  6514 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
09-12 13:11:26.519  6514  6514 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,09-12 13:11:26.529  1359  1359 D BluetoothMap: Proxy object disconnected
09-12 13:11:26.529  1359  1359 D MapProfile: Bluetooth service disconnected
09-12 13:11:26.529  1359  1359 D Bluetoothsap: BluetoothSAP Proxy object disconnected
09-12 13:11:26.529  1359  1359 D SapProfile: Bluetooth service disconnected
,09-12 13:11:26.529  6514  6870 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
,09-12 13:11:26.529  6514  6870 D BluetoothAdapterProperties: Setting state to 10
09-12 13:11:26.529  6514  6870 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
09-12 13:11:26.529  6514  6870 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:11:26.529  6514  6870 D BluetoothAdapterService: updateAdapterState state is 10
,09-12 13:11:26.529  6514  6870 D BluetoothAdapterService: Autoconnection is available 
09-12 13:11:26.529  6514  6870 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
09-12 13:11:26.529  6514  6870 I BluetoothAdapterState: Entering OffState
09-12 13:11:26.529  6514  6522 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:11:26.529  1452  1761 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:11:26.529  1452  1761 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:11:26.529  1176  1205 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:26.529  1176  1205 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:11:26.529  2851  2859 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:11:26.529  2851  2859 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:11:26.529  6226  6698 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:11:26.529  6226  6698 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:26.529  6226  6698 D BluetoothLeAdvertiser: stop All Advertising :: standalone boolean value is = false
,09-12 13:11:26.529  6226  6698 D BluetoothLeAdvertiser: Exit stop advertising
09-12 13:11:26.529  6226  6698 D BluetoothLeScanner: stopAllScan standalone boolean is value is = false
09-12 13:11:26.529  6226  6698 D BluetoothLeScanner: Exiting stopAllScan
,09-12 13:11:26.539  1359  1373 D Bluetoothsap: onBluetoothStateChange: up=false
,09-12 13:11:26.539  1359  1373 D Bluetoothsap: Unbinding service...
,09-12 13:11:26.539  1442  1451 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:26.539  1442  1451 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:26.539  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:11:26.539  1359  6917 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:26.539  1359  6917 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:26.539  1428  6699 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:11:26.539  1428  6699 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
09-12 13:11:26.539  1359  1368 D BluetoothMap: onBluetoothStateChange: up=false
,09-12 13:11:26.539  1926  1935 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:11:26.539  1926  1935 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:11:26.539  6514  6523 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:11:26.539  6514  6523 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:11:26.539  1359  6917 D BluetoothPbap: onBluetoothStateChange: up=false
,09-12 13:11:26.539  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=false
09-12 13:11:26.539  1013  1042 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:11:26.539  1359  1368 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:11:26.539  6391  6402 D BluetoothAdapter: onBluetoothStateChange: up=false
,09-12 13:11:26.539  6391  6402 D BluetoothAdapter: Bluetooth is turned off, stop adv and scan
,09-12 13:11:26.539  1359  1373 D BluetoothInputDevice: onBluetoothStateChange: up=false
,09-12 13:11:26.549  2851  6916 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-12 13:11:26.549  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 11 receivers.
,09-12 13:11:26.549  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-12 13:11:26.549  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:26.549  1013  1013 I InputMethodManagerService: [BT Setting State] State =10
09-12 13:11:26.549  1013  1013 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 13:11:26.559  1176  1176 D BluetoothAdapter: 761575682: getState() :  mService = null. Returning STATE_OFF
,09-12 13:11:26.559  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,09-12 13:11:26.559  1176  1716 D BluetoothAdapter: 761575682: getState() :  mService = null. Returning STATE_OFF
,09-12 13:11:26.559  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:26.559  1176  1176 D BluetoothTile:  getBluetoothState : 10
,09-12 13:11:26.559  1176  1716 D BluetoothAdapter: 761575682: getState() :  mService = null. Returning STATE_OFF
09-12 13:11:26.559  1176  1176 D BluetoothAdapter: 761575682: getState() :  mService = null. Returning STATE_OFF
09-12 13:11:26.559  1176  1176 D BluetoothAdapter: 761575682: getState() :  mService = null. Returning STATE_OFF
,09-12 13:11:26.559  6514  6873 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
09-12 13:11:26.559  1013  1025 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:11:26.559  1013  3010 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:11:26.569  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:11:26.569  1770  1770 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:11:26.569  1926  2107 D BluetoothAdapter: 601092983: getState() :  mService = null. Returning STATE_OFF
09-12 13:11:26.569  1926  2107 D BluetoothAdapter: 601092983: getState() :  mService = null. Returning STATE_OFF
09-12 13:11:26.569  6514  6514 I GKI_LINUX: GKI_exit_task 1 done
09-12 13:11:26.569  6514  6514 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,09-12 13:11:26.569  6514  6514 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-12 13:11:26.569  1359  1359 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:26.569  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:26.569  6514  6514 I art     : System.exit called, status: 0
09-12 13:11:26.569  6514  6514 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-12 13:11:26.569  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:26.569  1013  1796 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-12 13:11:26.569  1013  1796 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:11:26.569  1013  1796 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:26.579  1013  1796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:26.579  1013  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:26.579  1359  1359 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-12 13:11:26.579  1013  1471 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,09-12 13:11:26.579  1013  1471 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:11:26.579  1013  1471 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:26.579  1013  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:26.579  1013  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:11:26.579  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,09-12 13:11:26.589  1359  1359 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:11:26.599  1359  1359 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:11:26.599  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:26.599  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 10
,09-12 13:11:26.609  1013  1218 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 13:11:26.609  1013  1218 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
,09-12 13:11:26.609  1013  1218 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppReceiver}
09-12 13:11:26.609  1013  1218 W BroadcastQueue: android.os.TransactionTooLargeException
09-12 13:11:26.609  1013  1218 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-12 13:11:26.609  1013  1218 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
09-12 13:11:26.609  1013  1218 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
09-12 13:11:26.609  1013  1218 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:310)
09-12 13:11:26.609  1013  1218 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1284)
09-12 13:11:26.609  1013  1218 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:20437)
09-12 13:11:26.609  1013  1218 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:472)
09-12 13:11:26.609  1013  1218 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:3278)
09-12 13:11:26.609  1013  1218 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:11:26.609  1013  1218 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,09-12 13:11:26.609  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:26.609  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:26.609  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:26.619  1013  1218 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:26.629  1013  1218 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=6947 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,09-12 13:11:26.629  6947  6947 E Zygote  : MountEmulatedStorage(),
09-12 13:11:26.629  6947  6947 I libpersona: KNOX_SDCARD checking this for 1002
09-12 13:11:26.629  6947  6947 E Zygote  : v2
09-12 13:11:26.629  6947  6947 I libpersona: KNOX_SDCARD not a persona,
,09-12 13:11:26.629  6947  6947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:26.639  6947  6947 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:26.639  6947  6947 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:26.649  6947  6947 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:26.659  6947  6947 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:26.669  6947  6947 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
09-12 13:11:26.669  6947  6947 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:11:26.689  6947  6947 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding GattService
,09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding HeadsetService
09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding A2dpService
09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding HidService
09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding HealthService
09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding PanService
09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding BluetoothMapService,
09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding SapService
09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding HeadsetClientService
09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding A2dpSinkService
09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding SapClientService
09-12 13:11:26.719  6947  6947 D BtSettings.ProfileConfig: Adding HidDevService
,09-12 13:11:26.719  6947  6947 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,09-12 13:11:26.729  1013  1473 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
09-12 13:11:26.729  1013  1473 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:26.729  1013  1473 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 13:11:26.729  1013  1473 D SettingsProvider: selectionArgs: false
09-12 13:11:26.729  1013  1473 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.729  1013  1473 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,09-12 13:11:26.729  1013  1473 D SettingsProvider: ret = -1
09-12 13:11:26.729  1013  1218 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
09-12 13:11:26.729  1013  1218 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:26.729  1013  1218 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:26.729  1013  1218 D SettingsProvider: selectionArgs: false
09-12 13:11:26.729  1013  1218 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.729  1013  1218 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:26.729  1013  1218 D SettingsProvider: ret = -1,
09-12 13:11:26.729  1013  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
09-12 13:11:26.729  1013  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:26.729  1013  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:26.729  1013  1471 D SettingsProvider: selectionArgs: false,
09-12 13:11:26.729  1013  1471 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.729  1013  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed,
09-12 13:11:26.729  1013  1471 D SettingsProvider: ret = -1
09-12 13:11:26.729  1013  1026 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
09-12 13:11:26.729  1013  1026 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:26.729  1013  1026 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:26.729  1013  1026 D SettingsProvider: selectionArgs: false
,09-12 13:11:26.729  1013  1026 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.729  1013  1026 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:26.729  1013  1026 D SettingsProvider: ret = -1
09-12 13:11:26.729  1013  3012 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
09-12 13:11:26.729  1013  3012 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:26.729  1013  3012 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-12 13:11:26.729  1013  3012 D SettingsProvider: selectionArgs: false
09-12 13:11:26.729  1013  3012 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.729  1013  3012 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:26.729  1013  3012 D SettingsProvider: ret = -1
09-12 13:11:26.729  1013  4555 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
09-12 13:11:26.729  1013  4555 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
09-12 13:11:26.729  1013  4555 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:26.729  1013  4555 D SettingsProvider: selectionArgs: false
09-12 13:11:26.729  1013  4555 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.729  1013  4555 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:26.729  1013  4555 D SettingsProvider: ret = -1
09-12 13:11:26.729  1013  1379 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
09-12 13:11:26.729  1013  1379 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,09-12 13:11:26.729  1013  1379 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:26.729  1013  1379 D SettingsProvider: selectionArgs: false
09-12 13:11:26.729  1013  1379 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.729  1013  1379 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:26.729  1013  1379 D SettingsProvider: ret = -1,
09-12 13:11:26.729  1013  1137 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
09-12 13:11:26.729  1013  1137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:26.729  1013  1137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:26.729  1013  1137 D SettingsProvider: selectionArgs: false
,09-12 13:11:26.729  1013  1137 D SettingsProvider: selectionArgs: 1002,
09-12 13:11:26.729  1013  1137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:26.729  1013  1137 D SettingsProvider: ret = -1
09-12 13:11:26.729  1013  1025 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:26.729  1013  1025 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:26.729  1013  1025 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:26.729  1013  1025 D SettingsProvider: selectionArgs: false
,09-12 13:11:26.729  1013  1025 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.729  1013  1025 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:26.729  1013  1025 D SettingsProvider: ret = -1
09-12 13:11:26.729  1013  4556 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:26.729  1013  4556 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:26.729  1013  4556 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:26.729  1013  4556 D SettingsProvider: selectionArgs: false
09-12 13:11:26.729  1013  4556 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.729  1013  4556 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:26.729  1013  4556 D SettingsProvider: ret = -1
09-12 13:11:26.739  1013  3010 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
09-12 13:11:26.739  1013  3010 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:26.739  1013  3010 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:26.739  1013  3010 D SettingsProvider: selectionArgs: false
09-12 13:11:26.739  1013  3010 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.739  1013  3010 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:26.739  1013  3010 D SettingsProvider: ret = -1
09-12 13:11:26.739  1013  3011 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
09-12 13:11:26.739  1013  3011 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:26.739  1013  3011 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:26.739  1013  3011 D SettingsProvider: selectionArgs: false
09-12 13:11:26.739  1013  3011 D SettingsProvider: selectionArgs: 1002
09-12 13:11:26.739  1013  3011 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:26.739  1013  3011 D SettingsProvider: ret = -1
,09-12 13:11:26.749  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:11:26.749  1013  1218 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
09-12 13:11:26.749  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 13:11:26.749  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:26.749  1013  1218 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-12 13:11:26.749  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:26.759  1926  6963 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 13:11:26.759  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:11:26.769  1013  1025 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:26.769  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:26.769  1013  1025 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:26.769  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:26.779  1926  6963 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,09-12 13:11:27.069   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:11:27.069   287   287 E SMD     : DCD OFF
,09-12 13:11:28.069   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:11:28.319  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
,09-12 13:11:28.319  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:29.059   317   317 I ServiceManager: Waiting for service AtCmdFwd...,
,09-12 13:11:29.759  1013  1976 V SAMP_SPCM_test: CSC File load.. 
,09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-application
,09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-bluetooth
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-device-inventory,
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-date-time
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-exchange-account,
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-roaming
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-wifi
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-security,
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email-account
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-hardware-control
,09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-tethering
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-location
,09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-calling
,09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-email
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-vpn
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-apn-settings
,09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-browser-settings
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-phone-restriction
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-firewall
,09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-enterprise-vpn
09-12 13:11:29.759  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.sec.esdk.elm/com.sec.esdk.elm.DeviceAdminManager.AdminReceiver}: mdm-data-time
,09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-application
,09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-bluetooth
,09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-device-inventory
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-date-time
,09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-exchange-account
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-roaming
,09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-wifi
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-security
,09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email-account
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-hardware-control
,09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-tethering
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-location
,09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-calling
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-email
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-vpn
,09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-apn-settings
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-browser-settings
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-phone-restriction
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-firewall
,09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-enterprise-vpn
09-12 13:11:29.799  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.klmsagent/com.samsung.klmsagent.listner.KLMSDeviceAdminReceiver}: mdm-data-time
,09-12 13:11:29.809  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: history-password
,09-12 13:11:29.809  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-attachments
,09-12 13:11:29.809  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: limit-attachments
09-12 13:11:29.809  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-camera
,09-12 13:11:29.809  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-htmlemail
09-12 13:11:29.809  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-manualsyncroaming
,09-12 13:11:29.809  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: min-passwordcomplexchars
09-12 13:11:29.809  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-calendarage
,09-12 13:11:29.809  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailage
09-12 13:11:29.809  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-emailbodytruncsize
,09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: max-htmlemailbodytruncsize
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimemessages
,09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptedsmimemessages
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-signedsmimealgorithm
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-encryptionsmimealgorithm
,09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimeencryptionalgonegotiation
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: allow-smimesoftcerts
,09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: require-device-encryption
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-application
,09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-bluetooth
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-device-inventory
,09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-date-time
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-exchange-account
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-roaming
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-wifi
,09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-security
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email-account
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-hardware-control
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-tethering
,09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-location
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-calling
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-email
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-vpn
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-apn-settings,
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-browser-settings
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-phone-restriction
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-firewall
09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-enterprise-vpn
,09-12 13:11:29.819  1013  1976 W DeviceAdminInfo: Unknown tag under uses-policies of ComponentInfo{com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BBCDeviceAdminReceiver}: mdm-data-time
,09-12 13:11:29.819  1013  1976 D ActivityManager: getContentProviderImpl callerProcessName:android, calleePkgName: com.samsung.android.sm,
,09-12 13:11:29.829  1013  1976 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 13:11:29.829  1013  1976 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:29.829  1013  1976 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:29.829  1013  1976 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:29.839  1013  1976 I ActivityManager: Start proc com.samsung.android.sm for content provider com.samsung.android.sm/.database.SmProvider: pid=6966 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-12 13:11:29.839  6966  6966 E Zygote  : MountEmulatedStorage(),
09-12 13:11:29.839  6966  6966 E Zygote  : v2
09-12 13:11:29.839  6966  6966 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:11:29.839  6966  6966 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:29.839  6966  6966 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:29.849  6966  6966 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
,09-12 13:11:29.849  6966  6966 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,09-12 13:11:29.869  6966  6966 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:29.879  6966  6966 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:29.899  6966  6966 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:11:29.939  1013  1976 E SAMP_SPCMtest: setPackageLockingTimeBySPCM() :72
,09-12 13:11:30.059   287   287 E SMD     : DCD OFF
,09-12 13:11:30.069   317   317 I ServiceManager: Waiting for service AtCmdFwd...
,09-12 13:11:31.069   317   317 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3,
,09-12 13:11:31.309  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:11:31.319  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2a23f4be added. We now have 6 listener(s),
09-12 13:11:31.319  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:31.319  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
09-12 13:11:31.319  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2ed5491f added. We now have 7 listener(s)
09-12 13:11:31.319  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1,
09-12 13:11:31.319  6226  6276 I System.out: IsBluetoothEnabled
09-12 13:11:31.319  6226  6276 D BluetoothAdapter: disable()
,09-12 13:11:31.319  1013  1379 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.,
,09-12 13:11:31.329  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:31.329  6226  6276 D BluetoothAdapter: enable()
,09-12 13:11:31.329  1013  1026 W ActivityManager: Permission Denial: getCurrentUser() from pid=6226, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:11:31.329  1013  1026 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
09-12 13:11:31.329  1013  1026 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6226, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:11:31.329  1013  1026 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 13:11:31.329  1013  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2270)
09-12 13:11:31.329  1013  1026 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:702)
09-12 13:11:31.329  1013  1026 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:116)
09-12 13:11:31.329  1013  1026 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,09-12 13:11:31.329  1013  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:11:31.329  1013  1026 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:11:31.329  1013  1026 D SettingsProvider: name = bluetooth_on,
,09-12 13:11:31.349  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
09-12 13:11:31.349  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
09-12 13:11:31.349  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,09-12 13:11:31.349  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.btservice.AdapterService; callingUser = 0; userId(target) = -2
,09-12 13:11:31.369  6947  6947 D BluetoothAdapterState: make
,09-12 13:11:31.379  6947  6947 I bluedroid: init
,09-12 13:11:31.379  6947  6985 I BluetoothAdapterState: Entering OffState
,09-12 13:11:31.379  6947  6947 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-12 13:11:31.379  6947  6947 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
09-12 13:11:31.379  6947  6947 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-12 13:11:31.379  6947  6947 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-12 13:11:31.379  6947  6947 E bt-btif : btif_fetch_local_ble_random_bdaddr
09-12 13:11:31.379  6947  6947 I bluedroid: get_profile_interface socket
09-12 13:11:31.379  6947  6947 I bluedroid: get_profile_interface map_client
09-12 13:11:31.379  6947  6988 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,09-12 13:11:31.379  6947  6947 D BluetoothAdapterService: checkAddrForIOP: Loading from conf,
,09-12 13:11:31.389  6947  6988 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
09-12 13:11:31.389  6947  6988 E BluetoothServiceJni: populateRssiValuesNative
09-12 13:11:31.389  6947  6988 I bluedroid: getModelRssiValues
09-12 13:11:31.389  6947  6988 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,09-12 13:11:31.389  6947  6988 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 13:11:31.389  6947  6988 D BluetoothAdapterProperties: Name is: A5-1
,09-12 13:11:31.389  1013  1013 D SettingsProvider: name = bluetooth_name
,09-12 13:11:31.399  6947  6947 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:31.399  1013  1379 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-12 13:11:31.399  1013  1379 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.399  1013  1379 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:31.399  1013  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:31.399  1013  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:31.399  6947  6955 I bluedroid: config_hci_snoop_log
,09-12 13:11:31.399  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 11 receivers.
,09-12 13:11:31.409  1013  1042 D BluetoothManagerService: Ble is always on enable gatt
,09-12 13:11:31.409  1013  1042 I BluetoothManagerService: enableGattForLeMode, doBind called
,09-12 13:11:31.409  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 13:11:31.409  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 13:11:31.409  6947  6947 I BtGatt.JNI: classInitNative(L900): classInitNative: Success!
,09-12 13:11:31.419  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:11:31.419  1013  1042 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,09-12 13:11:31.419  1013  1042 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,09-12 13:11:31.429  1013  1042 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,09-12 13:11:31.429  6947  6985 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
09-12 13:11:31.429  6947  6985 D BluetoothAdapterProperties: Setting state to 11
09-12 13:11:31.429  6947  6985 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
09-12 13:11:31.429  6947  6985 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:11:31.429  6947  6985 D BluetoothAdapterService: updateAdapterState state is 11
,09-12 13:11:31.429  6947  6985 D BluetoothAdapterService: Autoconnection is available 
09-12 13:11:31.429  6947  6985 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,09-12 13:11:31.429  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:31.429  1013  1013 I InputMethodManagerService: [BT Setting State] State =11
,09-12 13:11:31.439  6947  6985 D BluetoothSecureManager: getInstant: null
09-12 13:11:31.439  6947  6985 D BluetoothSecureManager: calling getMethod for getService
09-12 13:11:31.439  6947  6985 D BluetoothSecureManager: calling getService
09-12 13:11:31.439  6947  6985 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@22b7e1c8
09-12 13:11:31.439  1013  4556 D BluetoothSecureManagerService: isSecureModeEnabled
09-12 13:11:31.439  1013  4556 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,09-12 13:11:31.439  6947  6985 D BtConfig.SecureMode: isSecureModeOn:false
09-12 13:11:31.439  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,09-12 13:11:31.439  6947  6985 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
09-12 13:11:31.439  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,09-12 13:11:31.439  6947  6985 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
09-12 13:11:31.439  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 13:11:31.439  6947  6985 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
09-12 13:11:31.439  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,09-12 13:11:31.439  6947  6985 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
09-12 13:11:31.439  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 13:11:31.439  6947  6985 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
09-12 13:11:31.439  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,09-12 13:11:31.439  6947  6985 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
09-12 13:11:31.439  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:31.449  6947  6985 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
09-12 13:11:31.449  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,09-12 13:11:31.449  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:11:31.449  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:31.449  1176  1176 D BluetoothTile:  getBluetoothState : 11
,09-12 13:11:31.449  6947  6985 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
09-12 13:11:31.449  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:11:31.449  6947  6985 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:31.449  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,09-12 13:11:31.449  6947  6985 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:31.449  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,09-12 13:11:31.449  6947  6985 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
09-12 13:11:31.449  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,09-12 13:11:31.449  6947  6985 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,09-12 13:11:31.449  6947  6985 D BluetoothBondStateMachine: make
,09-12 13:11:31.449  1770  1770 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:11:31.459  1359  1359 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:31.459  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
09-12 13:11:31.459  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,09-12 13:11:31.459  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:31.459  1013  1670 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:31.459  1013  1670 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.459  1013  1796 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:11:31.459  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
09-12 13:11:31.459  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
09-12 13:11:31.459  6947  6985 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,09-12 13:11:31.459  1013  3011 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,09-12 13:11:31.459  6947  6989 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-12 13:11:31.469  1013  1670 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:31.469  1013  1670 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:31.469  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
09-12 13:11:31.469  1013  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:31.469  1013  3010 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:31.469  1013  3010 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.479  1359  1359 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:11:31.479  1013  3010 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:31.479  1013  3010 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:31.479  1013  3010 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:31.479  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
09-12 13:11:31.479  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
09-12 13:11:31.479  6947  6985 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,09-12 13:11:31.479  1013  1218 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:31.479  6947  6947 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-12 13:11:31.479  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.479  6947  6947 D BtGatt.GattService: Received start request. Starting profile...
09-12 13:11:31.479  6947  6947 D BtGatt.GattService: start()
09-12 13:11:31.479  6947  6947 D BtGatt.GattService: start()
09-12 13:11:31.479  6947  6947 I bluedroid: get_profile_interface gatt
,09-12 13:11:31.479  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
09-12 13:11:31.479  6947  6947 D BtGatt.AdvertiseManager: advertise manager created
,09-12 13:11:31.489  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:31.489  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-12 13:11:31.489  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:31.489  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED,
09-12 13:11:31.489  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,09-12 13:11:31.489  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
09-12 13:11:31.489  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
09-12 13:11:31.489  6947  6985 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,09-12 13:11:31.499  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:31.499  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.499  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:31.499  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:31.499  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:31.509  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
09-12 13:11:31.509  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
09-12 13:11:31.509  6947  6985 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,09-12 13:11:31.509  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:31.509  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.509  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:31.509  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:31.509  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:31.509  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,09-12 13:11:31.509  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
09-12 13:11:31.509  6947  6985 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,09-12 13:11:31.519  6947  6947 D BtGatt.GattService: mStartError = false
09-12 13:11:31.519  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:31.519  6947  6947 D HeadsetService: Received start request. Starting profile...
,09-12 13:11:31.519  6947  6947 D HeadsetService: start()
,09-12 13:11:31.519  6947  6947 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-12 13:11:31.519  6947  6947 D HeadsetStateMachine: make
,09-12 13:11:31.529  1013  1670 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:31.529  1013  1670 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hdp.HealthService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.529  1013  1670 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:31.529  1013  1670 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:31.529  1013  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:31.529  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,09-12 13:11:31.529  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
09-12 13:11:31.529  6947  6985 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,09-12 13:11:31.529  1013  3152 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:31.529  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.529  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:31.529  1013  3152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:31.529  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:31.539  6947  6947 E HeadsetStateMachine: # of Max HF connection is 2
,09-12 13:11:31.549  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:31.549  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
09-12 13:11:31.549  6947  6985 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,09-12 13:11:31.549  1013  1379 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:31.549  1013  1379 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.549  1013  1379 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:31.549  1013  1379 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:31.549  1013  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:31.549  1013  3012 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,09-12 13:11:31.549  1013  3012 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothPhoneService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.559  1013  3012 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:31.559  1013  3012 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:31.559  1013  3012 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 13:11:31.559  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,09-12 13:11:31.559  1013  1025 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: com.samsung.bt.hfp.IBluetoothHeadsetVoIP
,09-12 13:11:31.559  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.server.telecom/com.android.server.telecom.BluetoothVoIPService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.559  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:31.559  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:31.559  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.server.telecom
,09-12 13:11:31.559  6947  6947 I bluedroid: get_profile_interface handsfree
,09-12 13:11:31.569  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService,
09-12 13:11:31.569  6947  6985 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,09-12 13:11:31.569  1013  1026 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:31.569  1013  1026 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:11:31.569  1013  1026 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:31.569  1013  1026 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:31.569  1013  1026 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:31.569  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,09-12 13:11:31.569  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:31.569  6947  6985 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
09-12 13:11:31.569  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:31.569  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:31.569  6947  6985 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
09-12 13:11:31.569  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
09-12 13:11:31.569  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
09-12 13:11:31.569  6947  6985 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
09-12 13:11:31.569  6947  6985 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
09-12 13:11:31.569  6947  6985 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
09-12 13:11:31.569  6947  6985 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
09-12 13:11:31.569  6947  6985 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,09-12 13:11:31.579  6947  6947 I DualScoManager: Instantiating Dual Sco Manager
,09-12 13:11:31.579  6947  6947 I DualScoManager: Set HeadsetServiceHelper
,09-12 13:11:31.579  6947  6947 D BluetoothAtMessage: createCMTIContentObservers
,09-12 13:11:31.579  1013  1218 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,09-12 13:11:31.579  1013  1218 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:31.579  1013  1218 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:31.579  1013  1218 D SettingsProvider: selectionArgs: false
09-12 13:11:31.579  1013  1218 D SettingsProvider: selectionArgs: 1002
09-12 13:11:31.579  1013  1218 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:31.579  1013  1218 D SettingsProvider: ret = -1
,09-12 13:11:31.579  6947  6994 D HeadsetStateMachine: Enter Disconnected: -2
,09-12 13:11:31.589  6947  6947 D HeadsetService: mStartError = false
,09-12 13:11:31.589  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:31.589  6947  6994 D HeadsetStateMachine: Clear mHeadsetBrsf
,09-12 13:11:31.589  6947  6994 D HeadsetStateMachine: map size, before remove : 0
09-12 13:11:31.589  6947  6994 D HeadsetStateMachine: map size, after remove: 0
,09-12 13:11:31.589  6947  6947 D A2dpService: Received start request. Starting profile...
09-12 13:11:31.589  6947  6947 D A2dpService: start()
,09-12 13:11:31.589  6947  6947 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,09-12 13:11:31.589  6947  6947 I bluedroid: get_profile_interface avrcp
,09-12 13:11:31.599  6947  6947 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-12 13:11:31.609  6947  6947 I Avrcp   :  Updating now playing list upon AVRCP Start
,09-12 13:11:31.609  6947  6998 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,09-12 13:11:31.609  6947  6947 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-12 13:11:31.619  6947  6947 D A2dpStateMachine: make
,09-12 13:11:31.619  6947  6947 I bluedroid: get_profile_interface a2dp
,09-12 13:11:31.619  6947  7000 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
09-12 13:11:31.619  6947  6947 E bt-btif : warning : media task started media_task_refcnt 1 
,09-12 13:11:31.619  6947  6947 D A2dpService: mStartError = false
09-12 13:11:31.619  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:31.619  6947  6999 D A2dpStateMachine: Enter Disconnected: -2
09-12 13:11:31.619  6947  6947 I BluetoothHidServiceJni: classInitNative: succeeds
,09-12 13:11:31.619  6947  6947 D HidService: Received start request. Starting profile...
09-12 13:11:31.619  6947  6947 D HidService: start()
09-12 13:11:31.619  6947  6947 I bluedroid: get_profile_interface hidhost
09-12 13:11:31.619  6947  6947 D HidService: setHidService(): set to: null
09-12 13:11:31.619  6947  6947 D HidService: mStartError = false
09-12 13:11:31.619  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:31.619  6947  6947 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,09-12 13:11:31.619  6947  6947 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-12 13:11:31.629  6947  6947 D HealthService: Received start request. Starting profile...
09-12 13:11:31.629  6947  6947 D HealthService: start()
,09-12 13:11:31.629  6947  6947 I bluedroid: get_profile_interface health
,09-12 13:11:31.629  6947  6947 D HealthService: mStartError = false
09-12 13:11:31.629  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:31.629  6947  6947 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-12 13:11:31.629  6947  6947 D PanService: Received start request. Starting profile...
09-12 13:11:31.629  6947  6947 D PanService: start()
09-12 13:11:31.629  6947  6947 D BluetoothPanServiceJni: initializeNative(L110): pan
09-12 13:11:31.629  6947  6947 I bluedroid: get_profile_interface pan
,09-12 13:11:31.629  6947  6947 D PanService: mStartError = false
09-12 13:11:31.629  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
09-12 13:11:31.629  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:31.639  6947  6947 D BluetoothMapService: Received start request. Starting profile...
09-12 13:11:31.639  6947  6947 D BluetoothMapService: start()
,09-12 13:11:31.639  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:11:31.639  6947  6947 D BluetoothMapService: mStartError = false
09-12 13:11:31.639  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:31.639  6947  6947 D HeadsetStateMachine: Try to query the phonestate on bind
,09-12 13:11:31.639  6947  6998 D BluetoothMediaBrowser: no now playing list
,09-12 13:11:31.649  6947  6998 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
09-12 13:11:31.649  1428  1437 I Telecom : BluetoothPhoneService: queryPhoneState
,09-12 13:11:31.649  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param 0
09-12 13:11:31.649  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
09-12 13:11:31.649  1428  1437 I Telecom : BluetoothPhoneService: Result of Message : true
,09-12 13:11:31.649  6947  6947 D HeadsetStateMachine: Proxy object connected
,09-12 13:11:31.649  6947  6947 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,09-12 13:11:31.649  6947  6947 D SapService: Received start request. Starting profile...
,09-12 13:11:31.649  6947  6947 D SapService: start()
09-12 13:11:31.649  6947  6947 D BluetoothSAPServiceJni: initializeNative(L209): sap
,09-12 13:11:31.649  6947  6947 I bluedroid: get_profile_interface sap
09-12 13:11:31.649  6947  6947 D SapService: mStartError = false
,09-12 13:11:31.649  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:31.649  6947  6947 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
09-12 13:11:31.649  6947  6947 D HeadsetPhoneState: sendDeviceDataStateChanged
09-12 13:11:31.649  6947  6994 D HeadsetStateMachine: Disconnected process message: 11
,09-12 13:11:31.649  6947  6947 D HeadsetPhoneState: Signal level : previous=0 curr=0
09-12 13:11:31.649  6947  6947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 13:11:31.649  6947  6947 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
09-12 13:11:31.649  6947  6994 D HeadsetStateMachine: Disconnected process message: 18
,09-12 13:11:31.649  6947  6947 D BluetoothA2dp: Proxy object connected
09-12 13:11:31.649  6947  6994 D HeadsetStateMachine: Disconnected process message: 10
09-12 13:11:31.649  6947  6947 D BluetoothAdapterService: Bluetooth A2dp source service connected
09-12 13:11:31.649  6947  6947 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
09-12 13:11:31.649  6947  6947 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
09-12 13:11:31.649  6947  6947 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,09-12 13:11:31.649  6947  6947 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
09-12 13:11:31.649  6947  6994 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-12 13:11:31.659  6947  6994 D HeadsetStateMachine: Disconnected process message: 11
,09-12 13:11:31.679  6947  6947 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,09-12 13:11:31.679  6947  6947 E BluetoothAdapterService(9558003): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,09-12 13:11:31.679  6947  6985 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,09-12 13:11:31.679  6947  6985 I bluedroid: enable
09-12 13:11:31.679  6947  6985 I bt_hci_bdroid: init
,09-12 13:11:31.679  6947  6985 I bt_vendor: bt-vendor : init
09-12 13:11:31.679  6947  6985 I bt_vendor: bt-vendor : get_bt_soc_type
09-12 13:11:31.679  6947  6985 E bt_vendor: get_bt_soc_type: Failed to get soc type
09-12 13:11:31.679  6947  6985 I bt_vendor: init: Local BD Address : ab:96:37:0e:f9:7c
09-12 13:11:31.679  6947  6985 D bt_userial_mct: userial_init
09-12 13:11:31.679  6947  6985 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
09-12 13:11:31.679  6947  6985 I bt_vendor: Starting hciattach daemon
09-12 13:11:31.679  6947  6985 I bt_vendor: try to set false
,09-12 13:11:31.679  6947  6985 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
09-12 13:11:31.679  6947  6985 I bt_vendor: Starting hciattach daemon
09-12 13:11:31.679  6947  6985 I bt_vendor: try to set true
,09-12 13:11:31.689  6947  7004 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,09-12 13:11:31.699  7008  7008 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  ,
,09-12 13:11:31.749  7014  7014 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd ,
,09-12 13:11:31.749  7015  7015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 13:11:31.769  7017  7017 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) ,
,09-12 13:11:31.779  7018  7018 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> ,
,09-12 13:11:31.789  7019  7019 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,09-12 13:11:31.799  7020  7020 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> ,
,09-12 13:11:32.019  7023  7023 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 7c:f9:0e:37:96:ab ,
,09-12 13:11:32.029  7024  7024 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** ,
,09-12 13:11:32.089  6947  6985 I bt_vendor: bluetooth satus is on
,09-12 13:11:32.089  6947  7006 D bt_userial_mct: userial_open(port:0)
09-12 13:11:32.089  6947  7006 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,09-12 13:11:32.089  6947  7006 I bt_vendor: Done intiailizing UART,
,09-12 13:11:32.099  6947  7006 I bt_vendor: Done intiailizing UART,
09-12 13:11:32.099  6947  7006 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
09-12 13:11:32.099  6947  7006 I bt_vendor: Bluetooth Firmware and transport layer are initialized,
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_HCI
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_L2CAP
,09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_AVDT
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_AVRC,
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_A2D
,09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_BNEP
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_BTM
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_GAP
,09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_PAN
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_SAP
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_SDP,
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_GATT
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_SMP,
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-12 13:11:32.099  6947  7004 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
09-12 13:11:32.109  6947  7026 D bt_userial_mct: Entering userial_read_thread()
,09-12 13:11:32.209  6947  7004 W bt-l2cap: l2c_link_processs_ble_num_bufs 16
,09-12 13:11:32.209  6947  7004 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa40476e9 
,09-12 13:11:32.209  6947  7004 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa40476e9 
,09-12 13:11:32.229  6947  6988 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 10 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 32 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 10240 mIsActivityAndEnergyReporting = true mAobleSupported = 0
,09-12 13:11:32.239  6947  6988 E bt-btif : Calling BTA_HhEnable
,09-12 13:11:32.239  6947  6988 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,09-12 13:11:32.239  6947  6988 D BluetoothAdapterProperties: Address is:7C:F9:0E:37:96:AB
,09-12 13:11:32.239  6947  6988 E BluetoothServiceJni: populateRssiValuesNative
09-12 13:11:32.239  6947  6988 I bluedroid: getModelRssiValues
,09-12 13:11:32.239  6947  6988 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
09-12 13:11:32.239  6947  6988 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,09-12 13:11:32.239  1013  1013 D SettingsProvider: name = bluetooth_name
,09-12 13:11:32.239  6947  6988 D BluetoothAdapterProperties: Name is: A5-1
,09-12 13:11:32.249  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:32.249  6947  6988 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
,09-12 13:11:32.249  6947  6988 D BluetoothAdapterProperties: Scan Mode:20
,09-12 13:11:32.249  6947  6988 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:11:32.249  6947  6988 D BluetoothAdapterProperties: LE Address is:FC:F3:1C:6E:2D:57
,09-12 13:11:32.249  6947  6988 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,09-12 13:11:32.249  6947  6988 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,09-12 13:11:32.259  6947  6988 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,09-12 13:11:32.259  6947  6988 E bt-btif : btif_sock_init: !vhci_init
09-12 13:11:32.259  6947  6988 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
09-12 13:11:32.259  6947  6988 D IOP_DB_BT: db_open: db_open : handle 3028140048l, read 13894 bytes onto local cache
09-12 13:11:32.259  6947  6988 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,09-12 13:11:32.259  6947  6988 D IOP_DB_BT: db_query: result 1
09-12 13:11:32.259  6947  6988 I         : iop_db_open: iop_db_open status 0
09-12 13:11:32.259  6947  6988 D bte_conf: Device ID record 1 : primary
09-12 13:11:32.259  6947  6988 D bte_conf:   vendorId            = 0075
09-12 13:11:32.259  6947  6988 D bte_conf:   vendorIdSource      = 0001
09-12 13:11:32.259  6947  6988 D bte_conf:   product             = 0100
09-12 13:11:32.259  6947  6988 D bte_conf:   version             = 0200
09-12 13:11:32.259  6947  6988 D bte_conf:   clientExecutableURL = 
09-12 13:11:32.259  6947  6988 D bte_conf:   serviceDescription  = 
09-12 13:11:32.259  6947  6988 D bte_conf:   documentationURL    = 
09-12 13:11:32.259  6947  6988 D bte_conf: bte_load_did_conf no section named DID2.
,09-12 13:11:32.259  6947  6988 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-12 13:11:32.259  6947  6985 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,09-12 13:11:32.259  6947  6985 D BluetoothAdapterProperties: ScanMode =  20
,09-12 13:11:32.259  6947  6985 D BluetoothAdapterProperties: State =  11
,09-12 13:11:32.259  1013  3011 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,09-12 13:11:32.259  6947  6985 D BluetoothAdapterProperties: Setting state to 12
09-12 13:11:32.259  6947  6985 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,09-12 13:11:32.269  6947  7026 E bt_mct  : hci lib postload completed
,09-12 13:11:32.269  6947  6988 D BluetoothUtils: getBtEnabledContainers(): btContainers = []
09-12 13:11:32.269  6947  6988 D BluetoothAdapterProperties: Scan Mode:21
09-12 13:11:32.269  6947  6988 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-12 13:11:32.269  1013  1379 D SettingsProvider: name = bluetooth_a2dp_sink_mode
09-12 13:11:32.269  1013  1379 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-12 13:11:32.269  1013  1379 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
09-12 13:11:32.269  1013  1379 D SettingsProvider: selectionArgs: false
09-12 13:11:32.269  1013  1379 D SettingsProvider: selectionArgs: 1002
09-12 13:11:32.269  1013  1379 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-12 13:11:32.269  1013  1379 D SettingsProvider: ret = -1
,09-12 13:11:32.269  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:32.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:32.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:32.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:32.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:32.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:32.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:32.269  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-12 13:11:32.269  6947  6985 D BluetoothAdapterService: Bluetooth PBAP supproted is true
09-12 13:11:32.269  6947  6985 D BluetoothAdapterService: updateAdapterState state is 12
,09-12 13:11:32.279  1013  3001 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:32.279  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.279  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.279  1013  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:32.279  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.289  6947  6985 D BluetoothAdapterService: Autoconnection is available 
09-12 13:11:32.289  6947  6985 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
09-12 13:11:32.289  6947  6985 D BluetoothAdapterService: starting service from this receiver
09-12 13:11:32.289  1359  1373 D BluetoothPan: Binding service...
,09-12 13:11:32.289  1013  1025 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
09-12 13:11:32.289  1013  1025 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.samsung.ble.BleAutoConnectService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.289  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:32.289  1013  1025 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:32.289  1013  1025 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.289  1013  1025 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.299  6947  6985 I BluetoothAdapterState: Entering On State from state = 11
,09-12 13:11:32.299  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,09-12 13:11:32.299  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.299  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.299  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.299  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.299  1452  1470 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:11:32.299  1452  1470 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:32.309  1176  1608 D BluetoothAdapter: onBluetoothStateChange: up=true,
09-12 13:11:32.309  1176  1608 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:32.309  1428  6699 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:32.309  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 13:11:32.309  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:32.319  6947  6947 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,09-12 13:11:32.319  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.319  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.319  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.319  1428  6699 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:32.319  1428  1436 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:32.319  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 13:11:32.319  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:32.319  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.329  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.329  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
09-12 13:11:32.329  1428  1436 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:32.329  1428  1437 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:32.329  1013  1042 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,09-12 13:11:32.329  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:32.329  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.329  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.329  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.329  1428  1437 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:32.329  2851  6916 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:32.339  6947  6947 I BluetoothPbapService: Handler(): got msg=1
,09-12 13:11:32.339  1013  1042 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:11:32.339  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:32.339  1013  3152 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
09-12 13:11:32.339  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:32.339  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.339  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
09-12 13:11:32.339  2851  6916 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:32.339  2851  2863 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:32.339  2851  2863 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:32.339  1452  1761 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:32.339  6947  7029 V BluetoothPbapService: PBAP Service initSocket try: 0
,09-12 13:11:32.349  1359  1359 D BluetoothPan: BluetoothPAN Proxy object connected
09-12 13:11:32.349  1359  1359 D PanProfile: Bluetooth service connected
,09-12 13:11:32.349  1013  1042 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:11:32.349  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:32.349  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:32.349  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.349  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.349  1452  1761 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:32.349  6226  6234 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:32.349  6226  6234 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:11:32.349  1013  1042 D BluetoothPan: Binding service...
09-12 13:11:32.349  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
09-12 13:11:32.349  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pan.PanService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.349  1359  1368 D Bluetoothsap: onBluetoothStateChange: up=true
09-12 13:11:32.349  1359  1368 D Bluetoothsap: Binding service...
09-12 13:11:32.349  1013  1013 D BluetoothPan: BluetoothPAN Proxy object connected
,09-12 13:11:32.349  6947  7029 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:11:32.349  6947  7029 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-12 13:11:32.349  1359  1368 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,09-12 13:11:32.349  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
09-12 13:11:32.349  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.broadcom.bt.service.sap.SapService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.349  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:32.349  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.349  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.359  6947  7029 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
09-12 13:11:32.359  6947  7029 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:11:32.359  6947  7029 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:11:32.359  6947  7029 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@364ef06c
09-12 13:11:32.359  6947  7029 D BluetoothSocket: channel: 19
09-12 13:11:32.359  6947  7029 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,09-12 13:11:32.359  1359  1368 D Bluetoothsap: bindService called to Bluetooth SAP Service
,09-12 13:11:32.359  1359  1359 D Bluetoothsap: BluetoothSAP Proxy object connected
09-12 13:11:32.359  1359  1359 D SapProfile: Bluetooth service connected
09-12 13:11:32.359  1359  1359 D Bluetoothsap: getConnectedDevices()
,09-12 13:11:32.359  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:32.359  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:32.359  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:32.359  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-12 13:11:32.359  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:32.359  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:32.359  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:32.359  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:32.359  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:32.369  1442  1451 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:11:32.369  1442  1451 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:11:32.369  1013  1042 D BluetoothA2dp: onBluetoothStateChange: up=true
09-12 13:11:32.369  1013  1042 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:32.369  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:11:32.369  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-12 13:11:32.369  1359  6917 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:32.369  1013  1013 D BluetoothA2dp: Proxy object connected
09-12 13:11:32.369  1359  6917 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:32.369  1428  1436 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:11:32.369  1428  1436 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:32.369  1359  1373 D BluetoothMap: onBluetoothStateChange: up=true
,09-12 13:11:32.369  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:32.369  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a11c46c added. We now have 8 listener(s)
09-12 13:11:32.369  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:32.369  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,09-12 13:11:32.369  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.map.BluetoothMapService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.369  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.369  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.369  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.379  1359  1359 D BluetoothMap: Proxy object connected
09-12 13:11:32.379  1926  2096 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:32.379  1359  1359 D MapProfile: Bluetooth service connected
09-12 13:11:32.379  1359  1359 D BluetoothMap: getConnectedDevices()
,09-12 13:11:32.379  1926  2096 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:11:32.379  6947  6956 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:11:32.379  6947  6956 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:11:32.379  1013  1042 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:32.379  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:11:32.379  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
09-12 13:11:32.379  1013  1042 E BluetoothHeadset: BluetoothHeadset service is binded
,09-12 13:11:32.379  1359  1368 D BluetoothHeadset: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:32.379  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
09-12 13:11:32.379  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hfp.HeadsetService; callingUser = 0; userId(target) = -3
,09-12 13:11:32.379  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:32.379  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.379  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.379  1013  1379 D SecContentProvider: uri = 18 selection = isWifiEnabled
09-12 13:11:32.379  1013  1379 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:11:32.379  1013  1379 D SecContentProvider2: mCursor = null
,09-12 13:11:32.379  1359  1359 D HeadsetProfile: Bluetooth service connected
,09-12 13:11:32.379  1359  1368 E BluetoothHeadset: BluetoothHeadset service is binded
09-12 13:11:32.379  1013  1379 D WifiService: setWifiEnabled: false pid=6226, uid=10155
09-12 13:11:32.379  1359  6917 D BluetoothPbap: onBluetoothStateChange: up=true
,09-12 13:11:32.389  1013  1379 D SettingsProvider: name = wifi_on
,09-12 13:11:32.389  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
09-12 13:11:32.389  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.389  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.389  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.389  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.389  1013  1042 D BluetoothAdapter: onBluetoothStateChange: up=true
09-12 13:11:32.389  1013  1042 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
,09-12 13:11:32.389  1359  1359 D BluetoothPbap: Proxy object connected
09-12 13:11:32.389  1359  1359 D PbapServerProfile: Bluetooth service connected
,09-12 13:11:32.389  6947  6990 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:11:32.389  1359  6917 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:11:32.389  1359  6917 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
,09-12 13:11:32.389  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,09-12 13:11:32.389  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.389  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:32.389  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.389  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.399  6391  6400 D BluetoothAdapter: onBluetoothStateChange: up=true
,09-12 13:11:32.399  6391  6400 D BluetoothAdapter: onBluetoothStateChange: Bluetooth is on
09-12 13:11:32.399  1359  1359 D BluetoothA2dp: Proxy object connected
09-12 13:11:32.399  1359  1359 D A2dpProfile: Bluetooth service connected
09-12 13:11:32.399  1359  1373 D BluetoothInputDevice: onBluetoothStateChange: up=true
,09-12 13:11:32.399  1013  1042 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
09-12 13:11:32.399  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.hid.HidService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.399  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:32.399  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.399  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.399  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:32.399  1013  4555 D SecContentProvider: uri = 18 selection = isWifiEnabled
,09-12 13:11:32.399  2851  6916 D BluetoothA2dp: onBluetoothStateChange: up=true
,09-12 13:11:32.399  1013  4555 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
09-12 13:11:32.399  1359  1359 D BluetoothInputDevice: Proxy object connected
09-12 13:11:32.399  1359  1359 D HidProfile: Bluetooth service connected
09-12 13:11:32.399  2851  6916 D BluetoothA2dp: doBind(): CallingUid(myUserHandle) = 0
09-12 13:11:32.399  1013  4555 D SecContentProvider2: mCursor = null
,09-12 13:11:32.399  1013  4555 D WifiService: setWifiEnabled: true pid=6226, uid=10155
09-12 13:11:32.399  1013  4555 W ActivityManager: Permission Denial: getCurrentUser() from pid=6226, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
,09-12 13:11:32.399  1013  4555 W WifiService: Failed getting userId using ActivityManagerNative
09-12 13:11:32.399  1013  4555 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=6226, uid=10155 requires android.permission.INTERACT_ACROSS_USERS
09-12 13:11:32.399  1013  4555 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23916)
09-12 13:11:32.399  1013  4555 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2216)
09-12 13:11:32.399  1013  4555 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2204)
09-12 13:11:32.399  1013  4555 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
09-12 13:11:32.399  1013  4555 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
09-12 13:11:32.399  1013  1042 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
09-12 13:11:32.399  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.a2dp.A2dpService; callingUser = 0; userId(target) = 0
09-12 13:11:32.399  1013  4555 D SettingsProvider: name = wifi_on
,09-12 13:11:32.399  1013  1042 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:32.399  1013  1042 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:32.399  1013  1042 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.providers.context, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.409  1013  1042 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
09-12 13:11:32.409  1013  1042 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.gatt.GattService; callingUser = 0; userId(target) = -2
,09-12 13:11:32.409  2851  2851 D BluetoothA2dp: Proxy object connected
,09-12 13:11:32.409  1013  1013 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:32.409  1013  1013 I InputMethodManagerService: [BT Setting State] State =12
,09-12 13:11:32.409  1013  1013 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,09-12 13:11:32.409  1013  1125 E WifiHW  : ##################### set firmware type 0 #####################
,09-12 13:11:32.419  1428  1428 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@14b08541, true
,09-12 13:11:32.419  1176  1176 D BluetoothTile:  onBluetoothStateChange:
,09-12 13:11:32.419  1428  1428 D BluetoothHeadset: registerMessageListener
,09-12 13:11:32.419  1176  1176 D BluetoothTile:  onBluetoothPairedDevicesChanged:
09-12 13:11:32.419  1176  1176 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
09-12 13:11:32.419  1176  1176 D BluetoothTile:  getBluetoothState : 12
,09-12 13:11:32.419  1770  1770 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,09-12 13:11:32.429  1359  1359 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:32.429  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:11:32.439  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:32.439  1013  1796 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:32.439  1013  1796 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.discovery.service.DiscoveryService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.439  1013  1796 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.439  1013  1796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:32.439  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
09-12 13:11:32.439  1013  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:32.439  6947  7036 D BluetoothMapMasInstance: set MAP SDP message type : 1
,09-12 13:11:32.439  1013  1379 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:11:32.449  1176  1716 D BluetoothTile:  handleUpdatestate:false name:null
,09-12 13:11:32.449  1013  1670 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,09-12 13:11:32.449  6947  6990 D HeadsetService: registerMessageListener
,09-12 13:11:32.449  6947  6990 D HeadsetService: registerMessageListener
,09-12 13:11:32.449  6947  6994 D HeadsetStateMachine: Disconnected process message: 70
09-12 13:11:32.449  6947  6994 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@c657635
09-12 13:11:32.449  1359  1359 W LocalBluetoothProfileManager: Warning: MAP profile was previously added but the UUID is now missing.
09-12 13:11:32.449  1359  1359 W LocalBluetoothProfileManager: Warning: PBAP profile was previously added but the UUID is now missing.
09-12 13:11:32.449  1359  1359 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
09-12 13:11:32.449  1359  1359 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
09-12 13:11:32.449  1176  1176 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,09-12 13:11:32.449  1428  1428 I Telecom : BluetoothPhoneService: handleMessage(7) / param null
,09-12 13:11:32.449  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,09-12 13:11:32.449  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Defalut Phonetype : 1
09-12 13:11:32.449  1428  1428 I Telecom : BluetoothPhoneService: getCurrentCallPhoneType, Current Phonetype : 1
09-12 13:11:32.449  1428  1428 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,09-12 13:11:32.449  6947  7036 D BluetoothSocket: bindListen(): myUserId = 0
09-12 13:11:32.459  6947  7036 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:11:32.459  1359  1359 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-12 13:11:32.459  6947  7036 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
09-12 13:11:32.459  6947  7036 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:11:32.459  6947  7036 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:11:32.459  6947  7036 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1335aaca
,09-12 13:11:32.459  1013  1670 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
09-12 13:11:32.459  6947  7036 D BluetoothSocket: channel: 5
,09-12 13:11:32.459  1013  1670 D ActivityManager: retrieveServiceLocked(): component = com.android.settings/com.android.settings.bluetooth.DockService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.459  1013  1670 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.459  1013  1670 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:32.459  6947  6994 D HeadsetStateMachine: Disconnected process message: 9
,09-12 13:11:32.469  1013  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.settings, destAppInfo.processName = com.android.settings
,09-12 13:11:32.469  6947  6994 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,09-12 13:11:32.469   282   692 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,09-12 13:11:32.469   282   692 V voice   : voice_set_parameters: enter: A2dpSuspended=false
09-12 13:11:32.469   282   692 V voice   : voice_set_parameters: exit with code(-2)
09-12 13:11:32.469   282   692 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
09-12 13:11:32.469   282   692 V msm8974_platform: platform_set_parameters: exit with code(-2)
,09-12 13:11:32.469   282   692 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
09-12 13:11:32.469   282   692 V audio_hw_primary: adev_set_parameters: exit
,09-12 13:11:32.469  6947  6994 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,09-12 13:11:32.479  1359  1359 D DockEventReceiver: finishStartingService: stopping service
,09-12 13:11:32.479  1359  1359 D BluetoothNotiBroadcastReceiver: onReceive
,09-12 13:11:32.489  1176  1176 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
,09-12 13:11:32.489  1176  1176 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 12
,09-12 13:11:32.499  6947  6947 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
,09-12 13:11:32.499  6947  6947 D BtConfig.SecureMode: isSecureModeOn:false
,09-12 13:11:32.499  1013  4555 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,09-12 13:11:32.499  1013  4555 D ActivityManager: retrieveServiceLocked(): component = com.android.bluetooth/com.android.bluetooth.opp.BluetoothOppService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.499  1013  4555 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.499  1013  4555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:32.499  1013  4555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,09-12 13:11:32.519  1926  1926 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,09-12 13:11:32.529  1013  1137 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-12 13:11:32.529  1013  1137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.easyunlock.authorization.InitializerIntentService; callingUser = 0; userId(target) = 0
,09-12 13:11:32.529  1013  1137 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.529  1013  1137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:32.529  1013  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:32.529  1926  7044 D EasyUnlockInitService: Handling intent for initializer IntentService.
,09-12 13:11:32.529  1926  1926 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,09-12 13:11:32.539  1013  1796 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:32.539  1013  1796 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.539  1013  1796 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:32.539  1013  1796 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:32.539  1013  1473 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy,
,09-12 13:11:32.559  6947  7047 D BluetoothSocket: bindListen(): myUserId = 0
,09-12 13:11:32.559  6947  7047 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-12 13:11:32.559  1013  1670 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-12 13:11:32.559  1013  1670 W ActivityManager: userId = 0, bbcId = -10000
,09-12 13:11:32.559  1013  1670 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-12 13:11:32.559  1013  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-12 13:11:32.559  6947  7047 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[80]}
09-12 13:11:32.559  6947  7047 D BluetoothSocket: bindListen(), new LocalSocket 
09-12 13:11:32.559  6947  7047 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
09-12 13:11:32.559  6947  7047 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@96ba996
09-12 13:11:32.559  6947  7047 D BluetoothSocket: channel: 12
09-12 13:11:32.559  6947  7047 I BtOppRfcommListener: Accept thread started.
,09-12 13:11:32.569  1926  7044 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,09-12 13:11:32.789  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:11:32.789  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 13:11:32.789  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
,09-12 13:11:32.789  1013  1040 D Tethering: interfaceAdded wlan0
,09-12 13:11:32.789  1013  1132 E Tethering: No numeric data
,09-12 13:11:32.789  1013  1122 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:11:32.799  1013  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:11:32.799  1013  1132 D Tethering: clearTetheredNotification()
,09-12 13:11:32.799  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:32.799  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:11:32.799  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:11:32.799  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:11:32.799  1176  1176 D HotspotTile: updateTetherState():false, false
09-12 13:11:32.799  1013  1122 V NetworkStats: performPollLocked() took 6ms
09-12 13:11:32.799  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:32.809  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit,
09-12 13:11:32.809  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:32.809  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
,09-12 13:11:32.809  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:11:32.809  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:11:32.809  1013  1040 D Tethering: interfaceAdded p2p0,
09-12 13:11:32.809  1013  1040 D Tethering: p2p0 is not a tetherable iface, ignoring,
,09-12 13:11:32.819   277  1011 I WifiHW  : wifi_change_fw_path(): fwpath = sta
09-12 13:11:32.819   277  1011 D SoftapController: Softap fwReload - Ok
,09-12 13:11:32.819   277  1011 D CommandListener: Setting iface cfg
09-12 13:11:32.819   277  1011 D CommandListener: Trying to bring down wlan0
,09-12 13:11:32.819   277  1011 D CommandListener: Clearing all IP addresses on wlan0
,09-12 13:11:32.829  1013  1125 E WifiHW  : supplicant_name : p2p_supplicant
,09-12 13:11:32.839  1013  1125 D WifiMonitor: startMonitoring(wlan0) with mConnected = false,
,09-12 13:11:32.849  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:11:32.849  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,09-12 13:11:32.849  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:32.849  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:32.849  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:32.849  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:32.849  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:11:32.849  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,09-12 13:11:32.849  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,09-12 13:11:32.859  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:11:32.859  1176  1176 D HotspotTile: onReceive : 2, 0
,09-12 13:11:32.859  1359  1359 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:11:32.869  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:32.869  1013  1471 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,09-12 13:11:32.869  1013  1471 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:32.869  1013  1471 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:32.869  1013  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:32.869  1013  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:11:32.879  3637  3637 I Hs20UtilService: Starting #19
,09-12 13:11:32.879  3637  3674 I Hs20UtilService: Message received 5011
,09-12 13:11:32.879  7055  7055 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
09-12 13:11:32.879  7055  7055 I wpa_supplicant: Successfully initialized wpa_supplicant
,09-12 13:11:32.879  7055  7055 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,09-12 13:11:32.879  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:11:32.879  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:11:32.879  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:11:32.879  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
,09-12 13:11:32.899  7055  7055 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage,
09-12 13:11:32.899   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7055
09-12 13:11:32.899   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,09-12 13:11:32.899  7055  7055 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
09-12 13:11:32.899  7055  7055 I wpa_supplicant: ssSupport state is = 1
09-12 13:11:32.899  7055  7055 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
09-12 13:11:32.899  7055  7055 I SecureStorage: [INFO]: SPID(0x00000000)Processing data,
09-12 13:11:32.899   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7055
09-12 13:11:32.899   388   388 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,09-12 13:11:33.049   388   388 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,09-12 13:11:33.059  7055  7055 I SecureStorage: [INFO]: SPID(0x00000004)Processing data has been completed
,09-12 13:11:33.069   287   287 E SMD     : DCD OFF
,09-12 13:11:33.119  7055  7055 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-12 13:11:33.119  7055  7055 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-12 13:11:33.129  7055  7055 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
,09-12 13:11:33.139   388   388 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7055
09-12 13:11:33.139   388   388 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
09-12 13:11:33.139  7055  7055 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-12 13:11:33.139  7055  7055 I wpa_supplicant: ssSupport state is = 1
09-12 13:11:33.139  7055  7055 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 13:11:33.139  7055  7055 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:11:33.139  7055  7055 E wpa_supplicant: SIM READ ERROR
09-12 13:11:33.139  7055  7055 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:11:33.139  7055  7055 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:11:33.139  7055  7055 E wpa_supplicant: SIM READ ERROR,
09-12 13:11:33.139  7055  7055 I wpa_supplicant: Blacklist: Clear (all) 
09-12 13:11:33.139  7055  7055 I wpa_supplicant: wpa_default_ap_write_once
09-12 13:11:33.139  7055  7055 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:11:33.139  7055  7055 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:11:33.139  7055  7055 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory,
09-12 13:11:33.139  7055  7055 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:11:33.139  7055  7055 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,09-12 13:11:33.139  7055  7055 I wpa_supplicant: rfkill: Cannot open RFKILL control device,
,09-12 13:11:33.139  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
,09-12 13:11:33.139  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:33.139  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:11:33.139  1013  1132 D Tethering: InitialState.processMessage what=4
,09-12 13:11:33.139  1013  1132 E Tethering: No numeric data
,09-12 13:11:33.149  1013  1132 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
09-12 13:11:33.149  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
09-12 13:11:33.149  1013  1132 D Tethering: clearTetheredNotification()
09-12 13:11:33.149  1176  1176 D HotspotTile: updateTetherState():false, false,
09-12 13:11:33.149  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:33.149  1013  1122 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:11:33.149  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:11:33.149  1013  1122 V NetworkStats: performPollLocked() took 4ms
09-12 13:11:33.149  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---,
09-12 13:11:33.149  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit,
09-12 13:11:33.149  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:33.149  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:33.179  7055  7055 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,09-12 13:11:33.509  1013  1379 D BatteryService: !@BatteryListener : batteryPropertiesChanged!,
09-12 13:11:33.509  1013  1379 D BatteryService: level:91, scale:100, status:2, health:2, present:true, voltage: 4152, temperature: 293, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
09-12 13:11:33.509  1013  1379 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
09-12 13:11:33.509  1013  1379 D BatteryService: stay LED for charging
09-12 13:11:33.509  1013  1013 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,09-12 13:11:33.519  1176  1176 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
09-12 13:11:33.519  1013  1013 I MotionRecognitionService: Plugged
09-12 13:11:33.519  1176  1176 D KeyguardUpdateMonitor: handleBatteryUpdate
,09-12 13:11:33.519  1013  1013 I MotionRecognitionService: mGripSensorEnabled= false
09-12 13:11:33.519  1411  1411 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED,
09-12 13:11:33.519  1411  1411 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 91
,09-12 13:11:33.529  6947  6947 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
09-12 13:11:33.529  6947  6994 D HeadsetStateMachine: Disconnected process message: 10,
,09-12 13:11:33.539  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,09-12 13:11:33.549  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
09-12 13:11:33.549  1176  1176 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:91 status:2 health:2
,09-12 13:11:33.559  7055  7055 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED,
,09-12 13:11:33.569  7055  7055 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage,
,09-12 13:11:33.579  7055  7055 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-12 13:11:33.579   388   388 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7055
09-12 13:11:33.579   388   388 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-12 13:11:33.579  7055  7055 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-12 13:11:33.579  7055  7055 I wpa_supplicant: ssSupport state is = 1
09-12 13:11:33.579  7055  7055 I wpa_supplicant: Ctrl_iface: loading cred from phone,
09-12 13:11:33.579  7055  7055 I SecureStorage: [INFO]: SPID(0x00000004)Checking if this device supports Secure Storage
,09-12 13:11:33.599  7055  7055 I SecureStorage: [INFO]: SPID(0x00000004)This device supports Secure Storage,
09-12 13:11:33.599   388   388 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7055
09-12 13:11:33.599   388   388 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C,
09-12 13:11:33.599  7055  7055 I SecureStorage: [INFO]: SPID(0x00000004)SS Daemon is running
09-12 13:11:33.599  7055  7055 I wpa_supplicant: ssSupport state is = 1
09-12 13:11:33.599  7055  7055 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0,
09-12 13:11:33.599  7055  7055 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
09-12 13:11:33.599  7055  7055 E wpa_supplicant: SIM READ ERROR
09-12 13:11:33.599  7055  7055 I wpa_supplicant: wpa_default_ap_write_once,
09-12 13:11:33.599  7055  7055 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
09-12 13:11:33.599  7055  7055 I wpa_supplicant: rfkill: Cannot open RFKILL control device
09-12 13:11:33.599  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
,09-12 13:11:33.599  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:11:33.599  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:11:33.599  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:11:33.599  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false
09-12 13:11:33.599  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:11:33.679  7055  7055 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE,
09-12 13:11:33.679  7055  7055 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,09-12 13:11:33.779  1013  1040 D Tethering: interfaceLinkStateChanged p2p0, false,
09-12 13:11:33.779  1013  1040 I Nat464Xlat: interfaceLinkStateChanged p2p0, false
09-12 13:11:33.779  1013  1040 D Tethering: interfaceStatusChanged p2p0, false
,09-12 13:11:33.839  7055  7055 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED,
09-12 13:11:33.839  7055  7055 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,09-12 13:11:33.839  7055  7055 I wpa_supplicant: Skip scan - bUseNetwork false
,09-12 13:11:33.849  1013  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2,
,09-12 13:11:33.849  1013  1125 D WifiNative-wlan0: callSECApiBoolean - ID [21],
09-12 13:11:33.849  7055  7055 I wpa_supplicant: HOTSPOT20_ENABLE called
09-12 13:11:33.849  7055  7055 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
09-12 13:11:33.849  7055  7055 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory,
09-12 13:11:33.849  7055  7055 E wpa_supplicant: SIM READ ERROR
09-12 13:11:33.849  7055  7055 I wpa_supplicant: Blacklist: Clear (all) 
,09-12 13:11:33.869  7055  7055 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec,
,09-12 13:11:33.879  7055  7055 I wpa_supplicant: Skip scan - bUseNetwork false,
09-12 13:11:33.879  1013  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
,09-12 13:11:33.879  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:33.879  1176  1176 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:33.879  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:33.879  1176  1716 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
09-12 13:11:33.879  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:33.879  1176  1176 D HotspotTile: onReceive : 3, 0
09-12 13:11:33.879  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:33.879  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:33.879  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:33.879  1176  1176 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
09-12 13:11:33.879  1176  1176 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
09-12 13:11:33.879  1013  1125 D WifiConfigStore: Loading config and enabling all networks 
,09-12 13:11:33.889  1359  1359 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,09-12 13:11:33.899  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:33.899  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:33.899  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:33.899  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:33.899  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:33.899  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:33.899  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:33.899  6226  6226 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:33.899  1013  1125 E WifiConfigStore: Not a HS20
09-12 13:11:33.899  1013  1125 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
09-12 13:11:33.899  1013  1125 D WifiNative-wlan0: callSECApiInt - ID [65]
09-12 13:11:33.899  6226  6226 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:33.899  1013  3152 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:33.899  1013  3152 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
09-12 13:11:33.909  1013  3152 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:33.909  1013  3152 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:33.909  1013  3152 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:11:33.909  1013  1125 D WifiNative-wlan0: callSECApiBoolean - ID [13]
09-12 13:11:33.909  7055  7055 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
09-12 13:11:33.909  7055  7055 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
09-12 13:11:33.909  7055  7055 I wpa_supplicant: reset timer : RESET_TIMER 0
09-12 13:11:33.909  7055  7055 I wpa_supplicant: P2P: Current p2p state = IDLE
09-12 13:11:33.909  7055  7055 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
09-12 13:11:33.909  7055  7055 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
09-12 13:11:33.909  7055  7055 I wpa_supplicant: First Scan Start
09-12 13:11:33.909  7055  7055 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
09-12 13:11:33.909  3637  3637 I Hs20UtilService: Starting #20
09-12 13:11:33.909  3637  3674 I Hs20UtilService: Message received 5011
09-12 13:11:33.919  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State = 1
09-12 13:11:33.919  6496  6496 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
09-12 13:11:33.919  6496  6496 D SecurityLogAgent: StateMachine : Current State = 1
09-12 13:11:33.919  6496  6496 D SecurityLogAgent: StateMachine : Changed Current State = 1
09-12 13:11:33.919  1013  1125 D WifiNative-wlan0: Setting external_sim to 1
09-12 13:11:33.919  1013  1125 D WifiStateMachine: Setting OUI to DA-A1-19
09-12 13:11:33.919  1013  1125 I WifiNative-HAL: startHal
09-12 13:11:33.919  1013  1125 E wifi    : getStaticLongField sWifiHalHandle 0x9c9c688c
09-12 13:11:33.919  1013  1125 I WifiNative-HAL: Could not start hal
09-12 13:11:33.919  6435  6435 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-12 13:11:33.919  1013  1125 E WifiNative-wlan0: do suspend true
09-12 13:11:33.929  1013  1124 D WifiP2pService: P2pDisabledState{ what=131203 }
09-12 13:11:33.929  1013  1125 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
09-12 13:11:33.929  1013  1013 D WifiScanningService: SCAN_AVAILABLE : 3
09-12 13:11:33.929  1013  1148 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:33.929  1013  1148 I WifiNative-HAL: startHal
09-12 13:11:33.929  1013  1148 E wifi    : getStaticLongField sWifiHalHandle 0x9d86c9bc
09-12 13:11:33.929  1013  1148 I WifiNative-HAL: Could not start hal
09-12 13:11:33.929  1013  1148 E WifiScanningService: could not start HAL
09-12 13:11:33.929  1013  1013 D RttService: SCAN_AVAILABLE : 3
09-12 13:11:33.929  1013  1149 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:33.929   277  1011 D CommandListener: Setting iface cfg
09-12 13:11:33.929   277  1011 D CommandListener: Trying to bring up p2p0
09-12 13:11:33.929  1013  1124 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
09-12 13:11:33.929  1013  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:11:33.929  1013  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:11:33.929  1013  1125 E WifiNative-wlan0: invaild command id : 215
09-12 13:11:33.929  1013  1124 D WifiP2pService: P2pEnablingState
09-12 13:11:33.929  1013  1124 D WifiP2pService: P2pEnablingState{ what=147457 }
09-12 13:11:33.929  1013  1124 D WifiP2pService: P2p socket connection successful
09-12 13:11:33.929  1013  1124 D WifiP2pService: P2pEnabledState
09-12 13:11:33.929  1013  1125 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
09-12 13:11:33.929  1013  1125 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
09-12 13:11:33.929  1013  1125 E WifiNative-wlan0: invaild command id : 215
09-12 13:11:33.929  1013  1124 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
09-12 13:11:33.939  1013  1131 E ConnectivityService: updateNetworkInfo()
09-12 13:11:33.939  7055  7055 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 13:11:33.939  7055  7055 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
09-12 13:11:33.939  1013  1043 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
09-12 13:11:33.939  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:11:33.939  1013  1043 D WifiDisplayController: disconnect
09-12 13:11:33.939  1013  1043 D WifiDisplayController: updateConnection
09-12 13:11:33.939  1013  1043 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
09-12 13:11:33.939  1013  1013 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
09-12 13:11:33.939  1013  1043 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:11:33.939  7055  7055 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
09-12 13:11:33.949  1176  1176 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
09-12 13:11:33.949  1013  1471 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-12 13:11:33.949  1176  1176 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
09-12 13:11:33.949  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:33.949  1013  1125 D SecContentProvider2: mCursor = null
09-12 13:11:33.949  1013  1043 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
09-12 13:11:33.949  1013  1124 D WifiNative-p2p0: p2pGetDeviceAddress
09-12 13:11:33.949  1013  1043 D WifiDisplayAdapter: onP2pDisconnected
09-12 13:11:33.949  1013  1124 D WifiNative-p2p0: p2pGetDeviceAddress returning 7e:f9:0e:37:96:ac
09-12 13:11:33.949  1013  1043 D IpRemoteDisplayController: disconnectWfdBridgeServer
09-12 13:11:33.949  1013  1043 D IpRemoteDisplayController: WfdBridgeServer is already null
09-12 13:11:33.949  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
09-12 13:11:33.959  1013  1124 D WifiP2pService: DeviceAddress: 7e:96:ac
09-12 13:11:33.959  1013  1043 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: A5-1
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  deviceAddress: 7e:f9:0e:37:96:ac
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  primary type: 10-0050F204-5
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  secondary type: null
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  wps: 0
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  grpcapab: 0
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  devcapab: 0
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  status: 3
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  wfdInfo: null
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  groupownerAddress: null
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  GOdeviceName: null
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  interfaceAddress: 
09-12 13:11:33.959  1013  1043 D WifiDisplayController:  SConnectInfo : null
09-12 13:11:33.959  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:33.959  1013  1125 D SecContentProvider2: mCursor = null
09-12 13:11:33.959  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 13:11:33.959  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
09-12 13:11:33.959  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:11:33.959  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:11:33.959  1359  1359 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:11:33.959  1359  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:11:33.969  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:11:33.969  6465  6465 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,09-12 13:11:33.969  6465  6465 D FileShare-Client: Outbound.stopDelayTimer - 
,09-12 13:11:33.979  1013  1124 D WifiP2pService: sending p2p persistent groups changed broadcast
,09-12 13:11:33.979  1013  1124 D WifiP2pService: InactiveState
,09-12 13:11:33.979  1013  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-12 13:11:33.979  1013  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:11:33.979  6480  6480 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,09-12 13:11:33.979  7055  7055 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,09-12 13:11:33.979  1013  1124 D WifiP2pService: InactiveState{ what=143376 }
,09-12 13:11:33.979  1013  1124 D WifiP2pService: P2pEnabledState{ what=143376 }
,09-12 13:11:34.429  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-12 13:11:34.429  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:34.429  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:34.429  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:34.429  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:34.429  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:34.429  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:34.429  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:34.429  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:34.429  6226  6276 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-12 13:11:34.429  6226  6276 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-12 13:11:34.439  6226  6276 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@21c3a39d Bundle[{}]
,09-12 13:11:34.439  6226  6276 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-12 13:11:34.439  6226  6276 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-12 13:11:34.439  6226  6276 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-12 13:11:34.439  6226  6276 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-12 13:11:34.439  6226  6276 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,09-12 13:11:34.439  6226  6276 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-12 13:11:34.449  6226  6276 I System.out: Running OutgoingSocketThread
,09-12 13:11:34.449  6226  7065 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1173)
,09-12 13:11:34.449  1013  2724 D SSRM:n  : SIOP:: AP = 340
,09-12 13:11:34.459  6226  7065 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55405
,09-12 13:11:34.459  6226  7065 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-12 13:11:34.999  7055  7055 I wpa_supplicant: nl80211: Received scan results (16 BSSes),
09-12 13:11:34.999  7055  7055 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,09-12 13:11:34.999  7055  7055 I wpa_supplicant: Trying to associate with SSID '4E47373030'
,09-12 13:11:34.999  7055  7055 I wpa_supplicant: Trying to associate with  'G700',
09-12 13:11:34.999  7055  7055 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
09-12 13:11:34.999  7055  7055 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=5 BSSID=00.00.00 SSID=4E47373030
09-12 13:11:34.999  1013  7063 D WifiMonitor: didn't find BSSID Trying to associate with SSID 'NG700'
,09-12 13:11:35.009  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:35.009  1013  1125 D SecContentProvider2: mCursor = null
,09-12 13:11:35.129  7055  7055 E wpa_supplicant: Cmd 35605 not handled
09-12 13:11:35.129  7055  7055 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-12 13:11:35.129  7055  7055 I wpa_supplicant: wlan0: Not associated - Delay processing of received EAPOL frame (state=ASSOCIATING bssid=00:00:00:00:00:00)
09-12 13:11:35.129  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
,09-12 13:11:35.129  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:35.129  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:11:35.129  7055  7055 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED,
09-12 13:11:35.129  7055  7055 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00.00.00 SSID=4E47373030
09-12 13:11:35.129  7055  7055 I wpa_supplicant: Associated with F4.99.3E
,09-12 13:11:35.129  7055  7055 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
,09-12 13:11:35.129  7055  7055 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
09-12 13:11:35.129  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:35.129  7055  7055 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=F4.99.3E SSID=4E47373030
09-12 13:11:35.129  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false,
09-12 13:11:35.129  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, false
09-12 13:11:35.129  1013  1040 D Tethering: interfaceStatusChanged wlan0, false
09-12 13:11:35.129  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, false
09-12 13:11:35.129  1013  1040 D Tethering: interfaceStatusChanged wlan0, false,
,09-12 13:11:35.129  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
,09-12 13:11:35.129  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, true
,09-12 13:11:35.129  1013  1040 D Tethering: interfaceStatusChanged wlan0, true
,09-12 13:11:35.139  1013  1132 E Tethering: No numeric data,
,09-12 13:11:35.139  1013  1132 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
09-12 13:11:35.139  1013  1132 D Tethering: clearTetheredNotification()
,09-12 13:11:35.139  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 13:11:35.139  1013  1125 D SecContentProvider2: mCursor = null
09-12 13:11:35.139  1013  1122 V NetworkStats: performPollLocked(flags=0x1),
09-12 13:11:35.139  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:35.139  1176  1176 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,09-12 13:11:35.139  7055  7055 I wpa_supplicant: wlan0: RX EAPOL from f4:f2:6d:22:99:3e
09-12 13:11:35.139  1176  1176 D HotspotTile: updateTetherState():false, false
09-12 13:11:35.139  7055  7055 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,09-12 13:11:35.139  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:11:35.139  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
09-12 13:11:35.149  7055  7055 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
09-12 13:11:35.149  7055  7055 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=F4.99.3E SSID=4E47373030
09-12 13:11:35.149  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:35.149  1013  1125 D SecContentProvider2: mCursor = null
09-12 13:11:35.149  7055  7055 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
09-12 13:11:35.149  7055  7055 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
09-12 13:11:35.149  7055  7055 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=0 id_str=]
09-12 13:11:35.149  1013  1122 V NetworkStats: performPollLocked() took 10ms
09-12 13:11:35.149  7055  7055 I wpa_supplicant: Blacklist: Clear (temp) 
09-12 13:11:35.149  7055  7055 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=F4.99.3E SSID=4E47373030
09-12 13:11:35.149  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:35.149  1013  1040 D Tethering: interfaceLinkStateChanged wlan0, true
,09-12 13:11:35.149  1013  1040 I Nat464Xlat: interfaceLinkStateChanged wlan0, true
09-12 13:11:35.149  1013  1040 D Tethering: interfaceStatusChanged wlan0, true
,09-12 13:11:35.159  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:35.159  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:35.159  1013  1125 D WifiNative-wlan0: callSECApiVoid - ID [50]
,09-12 13:11:35.169  1013  1125 E WifiConfigStore: setLastSelectedConfiguration -1
,09-12 13:11:35.169  1013  1125 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,09-12 13:11:35.169  1013  1131 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
09-12 13:11:35.169  1013  1131 E ConnectivityService: updateNetworkInfo()
09-12 13:11:35.169  1013  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,09-12 13:11:35.169  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:11:35.169  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 13:11:35.169  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:35.169  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:35.169  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:35.169  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:35.179  1013  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-12 13:11:35.179  1013  1471 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:35.179  1013  1471 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:35.179  1013  1125 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
,09-12 13:11:35.179  1013  1471 W ActivityManager: userId = 0, bbcId = -10000,
,09-12 13:11:35.179  1013  1471 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
09-12 13:11:35.179  1013  1471 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:11:35.189  3637  3637 I Hs20UtilService: Starting #21
09-12 13:11:35.189  3637  3674 I Hs20UtilService: Message received 5007
,09-12 13:11:35.189  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:11:35.189  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,09-12 13:11:35.199  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,09-12 13:11:35.199   277  1011 D CommandListener: Setting iface cfg
,09-12 13:11:35.199  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:11:35.199  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
09-12 13:11:35.199  1359  1359 I NearbySettings: MountReceiver.onReceive - Set preference state off
,09-12 13:11:35.199  1359  3038 V NearbySettings: MountReceiver.mPrefHandler - 7002
,09-12 13:11:35.209  1013  1125 E WifiStateMachine: Start Dhcp Watchdog 3
,09-12 13:11:35.209  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,09-12 13:11:35.209  1013  1125 D SecContentProvider2: mCursor = null,
,09-12 13:11:35.219  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,09-12 13:11:35.219  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 13:11:35.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:35.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:35.219  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:35.229  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:35.229  1013  1125 E WifiNative-wlan0: do suspend false
,09-12 13:11:35.239  1013  1124 D WifiP2pService: InactiveState{ what=143375 }
,09-12 13:11:35.239  1013  1125 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
09-12 13:11:35.239  1013  1125 D SecContentProvider2: mCursor = null
,09-12 13:11:35.239  1013  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 13:11:35.449  6226  6276 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1174)
,09-12 13:11:35.449  6226  6276 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1174)
09-12 13:11:35.449  6226  6276 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1179)
09-12 13:11:35.459  6226  6276 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-12 13:11:35.459  6226  6276 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1180)
,09-12 13:11:35.459  7068  7068 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory,
09-12 13:11:35.459  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:35.459  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1af1ba35 added. We now have 2 listener(s)
09-12 13:11:35.459  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:11:35.459  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:35.459  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:35.459  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:35.459  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a69eca added. We now have 9 listener(s)
09-12 13:11:35.459  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:35.459  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:11:35.469  7068  7068 I dhcpcd  : version 5.5.6 starting
,09-12 13:11:35.469  7068  7068 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,09-12 13:11:35.479  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:35.479  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:35.479  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:35.479  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:35.479  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:35.479  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:35.479  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:35.479  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:35.479  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:35.479  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:35.479  6226  6276 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:11:35.479  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-12 13:11:35.479  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@248cbb58 added. We now have 3 listener(s)
09-12 13:11:35.489  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
09-12 13:11:35.489  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:11:35.489  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:11:35.489  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:35.489  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:35.489  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:35.489  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f10c4b1 added. We now have 10 listener(s)
09-12 13:11:35.489  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:35.489  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:35.489  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:35.489  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:35.489  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 13:11:35.489  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:35.489  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1af1ba35 removed from the list
09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:35.489  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a69eca removed from the list
09-12 13:11:35.489  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:35.489  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:35.489  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
09-12 13:11:35.489  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-12 13:11:35.489  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@19a69eca not in the list
09-12 13:11:35.489  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.489  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.489  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f10c4b1 removed from the list
09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:35.489  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.489  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:35.489  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:35.489  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@248cbb58 removed from the list
09-12 13:11:35.499  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:35.499  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f7dd96 added. We now have 2 listener(s)
,09-12 13:11:35.499  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:11:35.499  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:35.499  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:35.499  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:35.499  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12113d17 added. We now have 9 listener(s)
,09-12 13:11:35.499  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:35.499  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:11:35.509  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:35.509  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:35.509  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:35.509  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:35.509  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:35.509  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:35.509  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:35.509  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:35.509  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:35.509  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:35.509  6226  6276 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:11:35.509  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:35.509  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@323bfaed added. We now have 3 listener(s)
,09-12 13:11:35.519  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:35.519  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:35.519  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB",
09-12 13:11:35.519  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:35.519  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:35.519  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:35.519  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a4c3d22 added. We now have 10 listener(s)
09-12 13:11:35.519  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:35.519  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:35.519  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-12 13:11:35.519  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:11:35.519  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:35.519  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-12 13:11:35.529  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:11:35.529  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:11:35.529  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:11:35.539  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-12 13:11:35.539  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:11:35.539  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:11:35.549  6947  6956 D BtGatt.GattService: registerClient() - UUID=62a9629d-6eaa-4807-8289-426a8baeea61
,09-12 13:11:35.559  7068  7068 I dhcpcd  : wlan0: sending IPv6 Router Solicitation,
09-12 13:11:35.559  7068  7068 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
09-12 13:11:35.559  7068  7068 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
09-12 13:11:35.559  7068  7068 I dhcpcd  : bssid match
09-12 13:11:35.559  7068  7068 I dhcpcd  : wlan0: rebinding lease of 192.168.1.111
,09-12 13:11:35.599  6947  6988 D BtGatt.GattService: onClientRegistered() - UUID=62a9629d-6eaa-4807-8289-426a8baeea61, clientIf=6,
,09-12 13:11:35.599  6226  6234 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
09-12 13:11:35.599  6947  7034 D BtGatt.GattService: start scan with filters
09-12 13:11:35.599  6947  6993 D BtGatt.ScanManager: handling starting scan
09-12 13:11:35.599  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 13:11:35.599  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:11:35.599  6947  6993 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@91d7f3
09-12 13:11:35.599  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:11:35.599  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:11:35.599  6947  6988 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
09-12 13:11:35.599  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:35.599  6947  6993 D BtGatt.ScanManager: allow scan with filters
,09-12 13:11:35.599  6947  6993 D BtGatt.ScanManager: client filter size is = 1available filters are = 13,
09-12 13:11:35.599  6947  6993 D BtGatt.ScanManager: set filter index= 3 for clientIf= 6
09-12 13:11:35.599  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:11:35.599  6947  6988 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
09-12 13:11:35.599  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:35.599  6947  6993 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:11:35.599  6947  6993 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
09-12 13:11:35.599  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-12 13:11:35.599  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
09-12 13:11:35.599  6947  6988 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 13:11:35.599  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:35.599  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:11:35.609  6947  6988 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 13:11:35.609  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:35.609  6226  6276 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
09-12 13:11:35.609  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:35.609  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-12 13:11:35.609  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.609  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:35.609  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-12 13:11:35.609  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:11:35.609  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:11:35.609  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:11:35.609  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:11:35.609  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:11:35.609  6947  6990 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:11:35.619  6947  6955 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:11:35.619  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:11:35.619  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:11:35.619  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-12 13:11:35.619  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-12 13:11:35.619  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:11:35.619  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:35.619  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-12 13:11:35.619  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:11:35.619  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:11:35.619  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:35.629  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:35.629  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:35.629  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:35.629  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:11:35.629  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:11:35.629  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:35.629  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.629  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-12 13:11:35.629  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37f7dd96 removed from the list
09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.629  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12113d17 removed from the list
09-12 13:11:35.629  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:35.629  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:35.629  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.629  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:35.629  6947  6993 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 31
,09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.629  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12113d17 not in the list
09-12 13:11:35.629  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.629  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.629  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2a4c3d22 removed from the list
09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:35.629  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.629  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:35.629  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:35.629  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@323bfaed removed from the list
,09-12 13:11:35.629  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:35.629  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@295096e added. We now have 2 listener(s)
,09-12 13:11:35.639  6947  6993 D BtGatt.ScanManager: filter size is 1
,09-12 13:11:35.639  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:11:35.639  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:35.639  6947  6993 D BtGatt.ScanManager: delete FilterIndex - 3
09-12 13:11:35.639  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:35.639  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:35.639  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b68b80f added. We now have 9 listener(s)
09-12 13:11:35.639  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:35.639  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:11:35.639  6947  6988 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 13:11:35.639  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:35.639  6947  6993 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:11:35.639  6947  6988 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 13:11:35.639  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.639  6947  6993 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:11:35.639  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:35.649  6947  6988 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 13:11:35.649  7068  7068 I dhcpcd  : wlan0: acknowledged 192.168.1.111 from 192.168.1.1
09-12 13:11:35.649  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.649  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:35.649  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:35.649  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:35.649  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:35.649  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:35.649  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:35.649  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:35.649  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:35.649  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-12 13:11:35.649  6226  6276 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:35.649  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:35.659  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:35.659  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8069aa5 added. We now have 3 listener(s)
,09-12 13:11:35.659  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:35.659  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 13:11:35.659  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:11:35.659  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-12 13:11:35.659  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-12 13:11:35.659  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e8c4e7a added. We now have 10 listener(s)
09-12 13:11:35.659  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:35.659  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:35.659  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:35.659  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:11:35.659  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:11:35.659  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:35.659  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:11:35.669  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-12 13:11:35.669  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:11:35.669  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:11:35.669  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:11:35.679  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:11:35.679  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:11:35.679  6947  6955 D BtGatt.GattService: registerClient() - UUID=67a2afc8-ef66-4687-bd18-e2afc289ce15
,09-12 13:11:35.719  6947  6988 D BtGatt.GattService: onClientRegistered() - UUID=67a2afc8-ef66-4687-bd18-e2afc289ce15, clientIf=6,
,09-12 13:11:35.719  6226  6698 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 13:11:35.719  6947  7035 D BtGatt.GattService: start scan with filters
,09-12 13:11:35.719  6947  6993 D BtGatt.ScanManager: handling starting scan
,09-12 13:11:35.719  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-12 13:11:35.719  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:11:35.719  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:11:35.719  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-12 13:11:35.729  6947  6988 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1
,09-12 13:11:35.729  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.729  6947  6993 D BtGatt.ScanManager: allow scan with filters
,09-12 13:11:35.729  6947  6993 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
,09-12 13:11:35.729  6947  6993 D BtGatt.ScanManager: set filter index= 4 for clientIf= 6
,09-12 13:11:35.729  6947  6988 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15
,09-12 13:11:35.729  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.729  6947  6993 D BtGatt.ScanManager: Starting BLE batch scan
,09-12 13:11:35.729  6947  6993 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 13:11:35.729  6947  6988 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
,09-12 13:11:35.729  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.739  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:35.739  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-12 13:11:35.739  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:35.739  6947  6988 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
09-12 13:11:35.739  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.739  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:11:35.749  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,09-12 13:11:35.749  6226  6276 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
09-12 13:11:35.749  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:35.749  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:35.749  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:35.749  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:35.749  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.749  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:35.749  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:35.749  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@295096e removed from the list
09-12 13:11:35.749  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.749  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b68b80f removed from the list
09-12 13:11:35.749  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:35.749  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:35.749  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.749  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 13:11:35.749  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.749  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:35.749  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:35.749  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:35.749  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.749  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b68b80f not in the list
09-12 13:11:35.749  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-12 13:11:35.749  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-12 13:11:35.749  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-12 13:11:35.749  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-12 13:11:35.749  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:11:35.759  6947  6956 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:11:35.759  6947  7034 D BtGatt.GattService: unregisterClient() - clientIf=6
09-12 13:11:35.759  6947  6993 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 32
,09-12 13:11:35.759  6947  6993 D BtGatt.ScanManager: filter size is 1
09-12 13:11:35.759  6947  6993 D BtGatt.ScanManager: delete FilterIndex - 4
,09-12 13:11:35.759  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:11:35.759  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:11:35.759  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:11:35.759  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:11:35.759  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:11:35.759  6947  6988 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
,09-12 13:11:35.759  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.759  6947  6993 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:11:35.759  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:35.769  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:11:35.769  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:11:35.769  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:11:35.769  6947  6988 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
09-12 13:11:35.769  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:35.769  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:35.769  6947  6993 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:11:35.769  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:35.769  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:35.769  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:35.769  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:35.769  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:35.769  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.769  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e8c4e7a removed from the list
09-12 13:11:35.769  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:35.769  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.769  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:35.769  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:35.769  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8069aa5 removed from the list
,09-12 13:11:35.769  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:35.769  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b80d846 added. We now have 2 listener(s)
,09-12 13:11:35.769  6947  6988 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
09-12 13:11:35.769  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.769  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 13:11:35.769  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:35.769  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:35.769  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:35.769  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e59a07 added. We now have 9 listener(s)
09-12 13:11:35.769  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:35.779  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:11:35.779  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:35.779  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:35.779  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:35.779  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:35.779  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:35.779  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:35.779  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-12 13:11:35.779  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:35.779  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:35.789  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:35.789  6226  6276 D io.jxcore.node.ConnectivityMonitor: start: OK
09-12 13:11:35.789  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:35.789  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e795d added. We now have 3 listener(s)
,09-12 13:11:35.789  7068  7068 I dhcpcd  : wlan0: leased 192.168.1.111 for 172800 seconds
,09-12 13:11:35.789  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:35.799  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:35.799  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:11:35.799  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:35.799  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:35.799  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:35.799  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ae232d2 added. We now have 10 listener(s)
09-12 13:11:35.799  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:35.799  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:35.799  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-12 13:11:35.799  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-12 13:11:35.799  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-12 13:11:35.799  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-12 13:11:35.799  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,09-12 13:11:35.809  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-12 13:11:35.809  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-12 13:11:35.809  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-12 13:11:35.809  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-12 13:11:35.809  6226  6276 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-12 13:11:35.819  6947  6955 D BtGatt.GattService: registerClient() - UUID=76d64cd4-15b9-4d62-b795-2b90b30661c4
,09-12 13:11:35.859  6947  6988 D BtGatt.GattService: onClientRegistered() - UUID=76d64cd4-15b9-4d62-b795-2b90b30661c4, clientIf=6
,09-12 13:11:35.859  6226  6235 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=6
,09-12 13:11:35.859  6947  7035 D BtGatt.GattService: start scan with filters
,09-12 13:11:35.859  6947  6993 D BtGatt.ScanManager: handling starting scan
,09-12 13:11:35.869  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING,
09-12 13:11:35.869  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-12 13:11:35.869  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-12 13:11:35.869  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-12 13:11:35.869  6947  6988 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=6, status=0, action=1,
09-12 13:11:35.869  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0,
09-12 13:11:35.869  6947  6993 D BtGatt.ScanManager: allow scan with filters
09-12 13:11:35.869  6947  6993 D BtGatt.ScanManager: client filter size is = 1available filters are = 13
09-12 13:11:35.869  6947  6993 D BtGatt.ScanManager: set filter index= 5 for clientIf= 6
,09-12 13:11:35.869  6947  6988 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=0, availableSpace=15,
09-12 13:11:35.869  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:35.869  6947  6993 D BtGatt.ScanManager: Starting BLE batch scan,
09-12 13:11:35.869  6947  6993 D BtGatt.ScanManager: configuring batch scan storage, appIf 6
,09-12 13:11:35.869  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:35.869  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-12 13:11:35.869  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-12 13:11:35.879  6947  6988 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=6, status=0
09-12 13:11:35.879  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.879  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-12 13:11:35.889  6947  6988 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=1
,09-12 13:11:35.889  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.899  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-12 13:11:35.899  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:35.899  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:35.899  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.899  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:35.899  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b80d846 removed from the list
09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.899  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e59a07 removed from the list
09-12 13:11:35.899  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:35.899  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-12 13:11:35.899  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.899  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
09-12 13:11:35.899  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.899  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.899  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@33e59a07 not in the list,
09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-12 13:11:35.899  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-12 13:11:35.899  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-12 13:11:35.899  6947  7035 D BtGatt.GattService: stopScan() - queue size =1
,09-12 13:11:35.899  6947  7037 D BtGatt.GattService: unregisterClient() - clientIf=6
,09-12 13:11:35.899  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-12 13:11:35.899  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-12 13:11:35.899  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-12 13:11:35.899  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-12 13:11:35.899  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-12 13:11:35.909  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-12 13:11:35.909  6226  6276 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-12 13:11:35.909  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-12 13:11:35.909  6947  6993 D BtGatt.ScanManager: 1. app : com.android.bluetooth 2. Action : LESC 3. Callng app : com.test.thalitest 4. Count : 33
,09-12 13:11:35.909  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:35.909  6947  6993 D BtGatt.ScanManager: filter size is 1,
09-12 13:11:35.909  6947  6993 D BtGatt.ScanManager: delete FilterIndex - 5
09-12 13:11:35.909  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:35.909  6226  6226 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-12 13:11:35.909  6226  6226 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-12 13:11:35.909  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:35.909  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:35.909  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-12 13:11:35.909  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ae232d2 removed from the list
09-12 13:11:35.909  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:35.909  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.909  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:35.909  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:35.909  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e795d removed from the list
09-12 13:11:35.909  6947  6988 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=6, status=0, action=1, availableSpace=16
09-12 13:11:35.909  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
09-12 13:11:35.909  6947  6993 D BtGatt.ScanManager: stopping BLe Batch
,09-12 13:11:35.909  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:35.909  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@138caa1e added. We now have 2 listener(s)
,09-12 13:11:35.919  6947  6988 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=6, status=0, startStopAction=0
,09-12 13:11:35.919  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.919  6947  6993 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 6
,09-12 13:11:35.919  6947  6988 D BtGatt.GattService: onBatchScanReports() - clientIf=6, status=0, reportType=2, numRecords=0
,09-12 13:11:35.919  6947  6988 D BtGatt.ScanManager: callback done for clientIf - 6 status - 0
,09-12 13:11:35.929  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
,09-12 13:11:35.929  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-12 13:11:35.929  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:35.929  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:35.929  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fedc2ff added. We now have 9 listener(s)
,09-12 13:11:35.929  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-12 13:11:35.929  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-12 13:11:35.929  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-12 13:11:35.939  6226  6276 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-12 13:11:35.939  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-12 13:11:35.939  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-12 13:11:35.939  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-12 13:11:35.939  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-12 13:11:35.939  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
,09-12 13:11:35.939  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-12 13:11:35.939  6226  6276 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-12 13:11:35.939  6226  6276 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-12 13:11:35.939  6226  6276 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-12 13:11:35.939  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-12 13:11:35.939  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@170c7715 added. We now have 3 listener(s)
,09-12 13:11:35.939  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-12 13:11:35.949  6226  6226 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-12 13:11:35.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "7C:F9:0E:37:96:AB"
09-12 13:11:35.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-12 13:11:35.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-12 13:11:35.949  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-12 13:11:35.949  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd54a2a added. We now have 10 listener(s)
09-12 13:11:35.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-12 13:11:35.949  6226  6276 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-12 13:11:35.949  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-12 13:11:35.949  6226  6276 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:35.949  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:35.949  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@138caa1e removed from the list
09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.949  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fedc2ff removed from the list
,09-12 13:11:35.949  6226  6276 D io.jxcore.node.ConnectivityMonitor: stop
09-12 13:11:35.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:35.949  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.949  6226  6276 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fedc2ff not in the list
09-12 13:11:35.949  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-12 13:11:35.949  6226  6276 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bd54a2a removed from the list
09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-12 13:11:35.949  6226  6276 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-12 13:11:35.949  6226  6276 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-12 13:11:35.949  6226  6276 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-12 13:11:35.949  6226  6276 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@170c7715 removed from the list
09-12 13:11:35.959  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-12 13:11:35.959  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-12 13:11:35.959  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-12 13:11:35.959  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-12 13:11:35.959  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-12 13:11:35.959  6226  6276 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-12 13:11:35.959  6226  7099 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1187, name: My test thread name)
,09-12 13:11:35.959  6226  7099 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1187, thread name: My test thread name)
,09-12 13:11:35.959  6226  7099 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1187, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 13:11:35.969  6226  7101 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1189, name: My test thread name)
,09-12 13:11:35.969  6226  7101 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1189, thread name: My test thread name)
09-12 13:11:35.969  6226  7101 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1189, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,09-12 13:11:35.969  6226  6276 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80,
09-12 13:11:35.969  6226  6276 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
09-12 13:11:35.969  6226  6276 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0,
09-12 13:11:35.969  6226  6276 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
09-12 13:11:35.969  6226  6276 D com.test.thalitest.ThaliTestRunner: Total duration: 23298 ms,
09-12 13:11:35.969  6226  6276 I jxcore-log: *Native tests were executed*
09-12 13:11:35.969  6226  6276 I jxcore-log: 
09-12 13:11:35.969  6226  6276 I jxcore-log: Total number of executed tests:  80,
09-12 13:11:35.969  6226  6276 I jxcore-log: 
09-12 13:11:35.969  6226  6276 I jxcore-log: Number of passed tests:  80
09-12 13:11:35.969  6226  6276 I jxcore-log: 
09-12 13:11:35.969  6226  6276 I jxcore-log: Number of failed tests:  0,
09-12 13:11:35.969  6226  6276 I jxcore-log: 
09-12 13:11:35.969  6226  6276 I jxcore-log: Number of ignored tests:  0
09-12 13:11:35.969  6226  6276 I jxcore-log: 
09-12 13:11:35.969  6226  6276 I jxcore-log: Total duration:  23298
09-12 13:11:35.969  6226  6276 I jxcore-log: 
09-12 13:11:35.969  6226  6276 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****,
09-12 13:11:35.969  6226  6276 I jxcore-log: 
09-12 13:11:35.969  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:35.969  6226  6276 I jxcore-log: 
09-12 13:11:35.979  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:35.979  6226  6276 I jxcore-log: 
09-12 13:11:35.979  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:35.979  6226  6276 I jxcore-log: 
09-12 13:11:35.979  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:35.979  6226  6276 I jxcore-log: 
09-12 13:11:35.979  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:35.979  6226  6276 I jxcore-log: 
09-12 13:11:35.979  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:35.979  6226  6276 I jxcore-log: 
09-12 13:11:35.979  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-12 13:11:35.979  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6226 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.989  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-12 13:11:35.989  6226  6276 I jxcore-log: 
09-12 13:11:35.999  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:11:35.999  6226  6276 I jxcore-log: 
09-12 13:11:35.999  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:11:35.999  6226  6276 I jxcore-log: 
,09-12 13:11:35.999  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:11:35.999  6226  6276 I jxcore-log: 
09-12 13:11:35.999  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:11:35.999  6226  6276 I jxcore-log: 
09-12 13:11:35.999  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:11:35.999  6226  6276 I jxcore-log: 
09-12 13:11:35.999  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:11:35.999  6226  6276 I jxcore-log: 
09-12 13:11:35.999  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-12 13:11:35.999  6226  6276 I jxcore-log: 
,09-12 13:11:36.049  1013  1125 E WifiNative-wlan0: do suspend true
,09-12 13:11:36.069   287   287 E SMD     : DCD OFF,
,09-12 13:11:36.079  1013  1124 D WifiP2pService: InactiveState{ what=143375 },
09-12 13:11:36.079  1013  1124 D WifiP2pService: P2pEnabledState{ what=143375 }
,09-12 13:11:36.079  1013  1125 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
09-12 13:11:36.079  1013  1125 E WifiStateMachine: VerifyingLinkState enter
,09-12 13:11:36.089  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 13:11:36.089  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:36.089  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.089  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 13:11:36.089  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false),
09-12 13:11:36.089  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.089  1013  1125 D WifiNative-wlan0: callSECApiInt - ID [210]
09-12 13:11:36.089  1013  1131 D ConnectivityService: Adding iface wlan0 to network 504,
,09-12 13:11:36.089  1013  1131 E ConnectivityService: updateNetworkInfo()
09-12 13:11:36.089  1013  1131 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}, oldLp = null
,09-12 13:11:36.099  1013  1142 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
09-12 13:11:36.099  1013  1142 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 13:11:36.099  1013  1142 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 13:11:36.099  1013  1142 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
09-12 13:11:36.099  1013  1142 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,09-12 13:11:36.109  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
09-12 13:11:36.109  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,09-12 13:11:36.109  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.109  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:36.109  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.109  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:36.119  1013  1125 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,09-12 13:11:36.129  6226  6226 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-12 13:11:36.129  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:11:36.129  6226  6276 I jxcore-log: 
09-12 13:11:36.129  1013  1670 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:36.129  1013  1670 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:36.129  1013  1670 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:36.129  1013  1670 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:36.129  1013  1670 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings,
09-12 13:11:36.129  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
,09-12 13:11:36.139  3637  3637 I Hs20UtilService: Starting #22
,09-12 13:11:36.139  1176  1176 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:36.139  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
09-12 13:11:36.139  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.139  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.139  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.139  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.139  3637  3674 I Hs20UtilService: Message received 5007
,09-12 13:11:36.139  1013  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-12 13:11:36.149  1013  1013 I WifiTrafficPoller: evaluateTrafficStatsPolling
09-12 13:11:36.149  1013  1013 I WifiTrafficPoller: mBoosterFLAG : 0
09-12 13:11:36.149  1013  1013 I WifiTrafficPoller: current booster mode : FullMode
09-12 13:11:36.149  1013  1013 D WifiNative-wlan0: callSECApiVoid - ID [212]
,09-12 13:11:36.149  1013  1125 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
09-12 13:11:36.149  1013  1131 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,09-12 13:11:36.149  1013  1131 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,09-12 13:11:36.159  1013  1131 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network. 504
09-12 13:11:36.159  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:36.159  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 13:11:36.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.159  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.159  1013  1131 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-12 13:11:36.159  1013  1131 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,09-12 13:11:36.159  1013  1131 D ConnectivityService: LTETest block dns file not exists
,09-12 13:11:36.159  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:11:36.159  1359  1359 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 13:11:36.169  1013  1131 E ConnectivityService: updateNetworkInfo()
09-12 13:11:36.169  1013  1131 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
09-12 13:11:36.169  1013  1131 E ConnectivityService: updateNetworkInfo()
,09-12 13:11:36.169  1013  1131 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
09-12 13:11:36.169  1013  1131 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
09-12 13:11:36.169  1013  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-12 13:11:36.169  1013  7066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:36.169  1013  7066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
09-12 13:11:36.169  1013  7066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
09-12 13:11:36.169  1013  7066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://connectivitycheck.android.com/generate_204 on "NG700"
09-12 13:11:36.169  1013  7066 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-12 13:11:36.169   277  1007 D EnterpriseController: uids 1000
09-12 13:11:36.169   277  1007 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
09-12 13:11:36.169   277  1007 D Netd    : getNetworkForDns: using netid 504 for uid 1000
,09-12 13:11:36.179  1013  1125 D WIFI    : evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-12 13:11:36.179  1013  1131 D ConnectivityService:    accepting network in place of null
09-12 13:11:36.179  1013  1124 D WIFI_P2P: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,09-12 13:11:36.179  1452  1452 D TelephonyNetworkFactory: evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= true
09-12 13:11:36.179  1452  1452 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-12 13:11:36.179  1013  1131 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
09-12 13:11:36.179  1013  1131 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true,
09-12 13:11:36.179  1013  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,09-12 13:11:36.189  1013  1131 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.111/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,09-12 13:11:36.189  1013  1013 D Tethering: Tethering got CONNECTIVITY_ACTION_IMMEDIATE
09-12 13:11:36.189  1013  1132 D Tethering: MasterInitialState.processMessage what=3
09-12 13:11:36.189  1013  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
09-12 13:11:36.189  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:36.189  1013  1122 V NetworkStats: updateIfacesLocked()
09-12 13:11:36.189  1013  1122 V NetworkStats: performPollLocked(flags=0x1)
09-12 13:11:36.189  1013  1042 D EntConnectivity: Not allowed due to - mEnabled false - primarySimSlot false
09-12 13:11:36.189  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:11:36.189  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:11:36.189  1176  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 13:11:36.189  1013  1473 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:36.189  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:36.199  3855  6288 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
09-12 13:11:36.199  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
,09-12 13:11:36.199  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 13:11:36.199  1013  1123 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
09-12 13:11:36.199  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 13:11:36.199  1176  1176 D StatusBar.NetworkController: updateDataNetType()
09-12 13:11:36.199  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-12 13:11:36.199  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
09-12 13:11:36.199  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:36.199  1013  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:36.199  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
09-12 13:11:36.199  3637  3637 I Hs20UtilService: Starting #23
09-12 13:11:36.199  3637  3674 I Hs20UtilService: Message received 5007
09-12 13:11:36.199  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:36.199  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:36.199  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:36.199  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:36.199  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:11:36.199  1359  1359 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
09-12 13:11:36.209  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 13:11:36.209  1013  1122 V NetworkStats: performPollLocked() took 15ms
09-12 13:11:36.209  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,09-12 13:11:36.209  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:36.209  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-12 13:11:36.209  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:36.209  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
09-12 13:11:36.209  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.209  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.209  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.209  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:36.209  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
09-12 13:11:36.209  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
09-12 13:11:36.209  1359  1359 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
09-12 13:11:36.209  1359  1359 I NearbySettings: MountReceiver.onReceive - Keep current state
,09-12 13:11:36.209  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:36.209  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:36.219  1013  3001 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
09-12 13:11:36.219  1013  3001 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,09-12 13:11:36.219  1013  3001 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:36.219  1013  3001 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:36.219  1013  3001 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,09-12 13:11:36.219  1359  1359 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
09-12 13:11:36.219  3637  3637 I Hs20UtilService: Starting #24
09-12 13:11:36.219  1359  1359 I NearbySettings: MountReceiver.onReceive - Keep current state
09-12 13:11:36.219  3637  3674 I Hs20UtilService: Message received 5007
,09-12 13:11:36.229  1013  1670 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,09-12 13:11:36.229  1013  1471 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
09-12 13:11:36.229  1013  1471 D SecContentProvider2: mCursor = null
09-12 13:11:36.229  1013  3012 D SecContentProvider2: uri = 15 selection = getToastGravity
09-12 13:11:36.229  1013  3012 D SecContentProvider2: mCursor = null
,09-12 13:11:36.229  1013  1379 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
09-12 13:11:36.229  1013  1379 D SecContentProvider2: mCursor = null
,09-12 13:11:36.229  1013  3011 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
09-12 13:11:36.229  1013  3011 D SecContentProvider2: mCursor = null
,09-12 13:11:36.239  1013  4555 D SecContentProvider2: uri = 15 selection = getToastEnabledState
09-12 13:11:36.239  1013  4555 D SecContentProvider2: mCursor = null
,09-12 13:11:36.239  1013  4556 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
09-12 13:11:36.239  1013  4556 D SecContentProvider2: mCursor = null
,09-12 13:11:36.259   257   257 I SurfaceFlinger: id=15 createSurf (1x1),1 flag=4, Uoast
,09-12 13:11:36.269  1013  1473 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1013
,09-12 13:11:36.269  6226  6226 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-12 13:11:36.269  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:11:36.269  6226  6276 I jxcore-log: 
,09-12 13:11:36.279  1013  7066 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-12 13:11:36.279  1176  1176 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 13:11:36.309  7103  7103 D AndroidRuntime: 
09-12 13:11:36.309  7103  7103 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-12 13:11:36.309  7103  7103 D AndroidRuntime: CheckJNI is OFF
,09-12 13:11:36.309  7103  7103 D AndroidRuntime: readGMSProperty: start
09-12 13:11:36.309  7103  7103 D AndroidRuntime: readGMSProperty: already setted!!
09-12 13:11:36.309  7103  7103 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-12 13:11:36.309  7103  7103 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-12 13:11:36.309  7103  7103 D AndroidRuntime: readGMSProperty: end
09-12 13:11:36.309  7103  7103 D AndroidRuntime: addProductProperty: start
,09-12 13:11:36.329  1013  7066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Mon, 12 Sep 2016 11:11:36 GMT], X-Android-Received-Millis=[1473678696339], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1473678696313]}
,09-12 13:11:36.329  1013  7066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
,09-12 13:11:36.329  1013  7066 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
09-12 13:11:36.329  1013  1131 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
09-12 13:11:36.329  1013  1131 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,09-12 13:11:36.329  1013  1131 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
09-12 13:11:36.329  1013  1131 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,09-12 13:11:36.329  1013  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-12 13:11:36.329  3855  6288 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 13:11:36.329  1176  1698 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: EthernetConnected: false
09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): 0
09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: updateDataNetType()
09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
09-12 13:11:36.339  1176  1176 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
09-12 13:11:36.339  1176  1176 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
09-12 13:11:36.339  1176  1176 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,09-12 13:11:36.409  6226  6226 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-12 13:11:36.409  6226  6276 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-12 13:11:36.409  6226  6276 I jxcore-log: 
,09-12 13:11:36.459  7103  7103 E AffinityControl: AffinityControl: registerfunction enter
,09-12 13:11:36.479  7103  7103 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-12 13:11:36.519  1013  1137 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-12 13:11:36.519  1013  1137 D PackageManager: START PACKAGE DELETE: observer{490952759}
09-12 13:11:36.519  1013  1137 D PackageManager: pkg{<packageName>}
09-12 13:11:36.519  1013  1137 D PackageManager: user{0}
09-12 13:11:36.519  1013  1137 D PackageManager: caller{2000}
09-12 13:11:36.519  1013  1137 D PackageManager: flags{2}
09-12 13:11:36.519  1013  1137 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
09-12 13:11:36.519  1013  1137 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-12 13:11:36.519  1013  1137 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-12 13:11:36.519  1013  1137 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-12 13:11:36.519  1013  1053 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,09-12 13:11:36.519  1013  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-12 13:11:36.519  1013  1053 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,09-12 13:11:36.519  1013  1053 D ApplicationPolicy: getApplicationUninstallationEnabled
09-12 13:11:36.519  1013  1053 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-12 13:11:36.519  1013  1053 D PackageManager: !@killApplicatoin: 10155, uninstall pkg
,09-12 13:11:36.529  1013  1038 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
09-12 13:11:36.529  1013  1038 I ActivityManager: Killing 6226:com.test.thalitest/u0a155 (adj 0): stop com.test.thalitest cause uninstall pkg
,09-12 13:11:36.539  1013  1038 I ActivityManager:   Force finishing activity ActivityRecord{2e5274f2 u0 com.test.thalitest/.MainActivity t128}
,09-12 13:11:36.549  1013  1038 W ActivityManager: mDVFSHelper.acquire()
,09-12 13:11:36.639  1013  1053 I ActivityManager: Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,09-12 13:11:36.649  1013  1053 I ActivityManager:   Force finishing activity ActivityRecord{2e5274f2 u0 com.test.thalitest/.MainActivity t128 f}
,09-12 13:11:36.649  1013  1053 W ActivityManager: Duplicate finish request for ActivityRecord{2e5274f2 u0 com.test.thalitest/.MainActivity t128 f}
,09-12 13:11:36.659  1013  1053 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-12 13:11:36.659  1013  3001 I WindowState: WIN DEATH: Window{16575452 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-12 13:11:36.659   257   824 I SurfaceFlinger: id=14 Removed NainActivit (6/9)
,09-12 13:11:36.659   257   438 I SurfaceFlinger: id=14 Removed NainActivit (-2/9)
,09-12 13:11:36.689  1013  3001 D InputDispatcher: Focus left window: 6226
,09-12 13:11:36.689  1013  1131 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:36.699  5497  5497 I art     : Explicit concurrent mark sweep GC freed 402(27KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 8MB/11MB, paused 755us total 37.691ms
,09-12 13:11:36.709  1013  1038 D InputDispatcher: Focused application released
,09-12 13:11:36.709  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,09-12 13:11:36.709  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:11:36.709  5708  5708 I art     : Explicit concurrent mark sweep GC freed 2070(118KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 3.868ms total 29.381ms
,09-12 13:11:36.729  1013  1096 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-12 13:11:36.739  3855  3855 I art     : Explicit concurrent mark sweep GC freed 22398(1365KB) AllocSpace objects, 3(48KB) LOS objects, 40% free, 15MB/26MB, paused 1.317ms total 87.427ms
,09-12 13:11:36.759  3855  3867 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,09-12 13:11:36.769  1013  1122 V NetworkStats: removeUidsLocked() for UIDs [10155]
09-12 13:11:36.769  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
09-12 13:11:36.769  1013  1122 V NetworkStats: performPollLocked(flags=0x3)
,09-12 13:11:36.769  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox updated
09-12 13:11:36.769  1013  1122 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-12 13:11:36.779  1013  1122 V NetworkStats: performPollLocked() took 9ms
,09-12 13:11:36.779  1013  1122 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:36.789  6548  6548 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,09-12 13:11:36.789  3117  3117 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,09-12 13:11:36.799  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:11:36.799  1442  1442 D RegisteredServicesCache: empty dynamic service
,09-12 13:11:36.809  1442  1442 D RegisteredComponentCache: Collect Tech packages for Knox
,09-12 13:11:36.809  3117  3117 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-12 13:11:36.819  3678  3678 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Sep 12 13:11:36 GMT+02:00 2016
,09-12 13:11:36.819  3117  3117 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-12 13:11:36.829  1442  1442 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:11:36.829  3117  3117 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-12 13:11:36.829  3117  3117 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 6
,09-12 13:11:36.839  3117  3117 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,09-12 13:11:36.839  1770  1770 E SamsungIME: mOCRHelper is null
,09-12 13:11:36.849  3117  3117 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,09-12 13:11:36.869  3117  3117 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,09-12 13:11:36.879  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:36.879  1013  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,09-12 13:11:36.889  3117  3117 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,09-12 13:11:36.899  1013  1013 I art     : Explicit concurrent mark sweep GC freed 86713(5MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 28MB/42MB, paused 4.236ms total 235.177ms
,09-12 13:11:36.899  1013  1670 I art     : WaitForGcToComplete blocked for 150.055ms for cause Explicit
,09-12 13:11:36.919  1013  1379 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
09-12 13:11:36.919  1013  1379 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,09-12 13:11:36.929  3117  3117 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 6
,09-12 13:11:36.929  3117  3117 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,09-12 13:11:36.939  3117  3117 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,09-12 13:11:36.939  3117  3117 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,09-12 13:11:36.939  3117  3117 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,09-12 13:11:36.939  3117  3117 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,09-12 13:11:36.949  1013  1025 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-12 13:11:36.949  1013  1025 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-12 13:11:36.949  1013  1025 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,09-12 13:11:36.949  3117  3117 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(420/onPause)] 
,09-12 13:11:37.029  1013  1013 D RCPManagerService: PackageReceiver onReceive()
,09-12 13:11:37.029  1013  1013 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-12 13:11:37.029  1013  1013 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-12 13:11:37.029  1013  1013 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,09-12 13:11:37.029  1013  1013 D OTPFW   : OtpDbHelper::getInstance New instance created
,09-12 13:11:37.029  1013  1013 D OTPFW   : DBIntegrity::getInstance - New instance created
,09-12 13:11:37.029  1013  1013 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
,09-12 13:11:37.039  1013  1013 I OTPFW   : ProvisionData::getAllEntries Enter
,09-12 13:11:37.039  1013  1013 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-12 13:11:37.039  1013  1013 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-12 13:11:37.039  1013  1013 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicy: uID is 10155
09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
09-12 13:11:37.039  1013  1013 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicy: uID is 10155
09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicy: Removed Packageuid is0
09-12 13:11:37.039  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-12 13:11:37.049  1013  1013 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-12 13:11:37.049  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-12 13:11:37.049  1013  2724 D SSRM:bc : MSG_TYPE_APP_REMOVED::
09-12 13:11:37.049  1013  1013 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-12 13:11:37.049  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-12 13:11:37.059  1013  1013 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-12 13:11:37.059  1013  1013 D KnoxTimeoutHandler: handleActiveUserChange for user 0
09-12 13:11:37.059  1013  1013 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
09-12 13:11:37.059  1013  1013 D PersonaManagerService: getPersonasForUser(): returning null!
,09-12 13:11:37.059  1013  1013 V AlarmManagerEXT: com.test.thalitest(10155) is removed.
,09-12 13:11:37.079  1013  1159 D TaskPersister: removeObsoleteFile: deleting file=128_task.xml
,09-12 13:11:37.089  1013  1670 I art     : Explicit concurrent mark sweep GC freed 13027(712KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 28MB/42MB, paused 4.545ms total 189.163ms
09-12 13:11:37.089  1013  1053 I art     : WaitForGcToComplete blocked for 386.153ms for cause Explicit
09-12 13:11:37.089  1013  1473 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-12 13:11:37.089  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
09-12 13:11:37.089  1013  1159 D TaskPersister: removeObsoleteFile: deleting file=127_task.xml
09-12 13:11:37.089  1013  1137 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-12 13:11:37.089  1013  1137 D SecContentProvider2: mCursor = null
,09-12 13:11:37.089  1926  2098 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-12 13:11:37.099  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:37.099  1013  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:37.099  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-12 13:11:37.099   257   257 I SurfaceFlinger: id=16 createSurf (720x1280),1 flag=404, YUIInstallC
,09-12 13:11:37.099  1013  1037 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-12 13:11:37.109  1013  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-12 13:11:37.109  1013  1037 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-12 13:11:37.109  1013  1471 D InputDispatcher: Focus entered window: 3117
,09-12 13:11:37.109  1013  1043 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-12 13:11:37.109  1013  1043 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-12 13:11:37.109  1013  1037 W TextServicesManagerService: no available spell checker services found
09-12 13:11:37.109  3117  3117 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-12 13:11:37.109  3678  3678 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,09-12 13:11:37.109  1013  3012 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=21, mSplitNum[2]=34, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=44
,09-12 13:11:37.119  1013  3012 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-12 13:11:37.119  3117  3117 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,09-12 13:11:37.119  3117  3117 V ActivityThread: updateVisibility : ActivityRecord{10b7e3a1 token=android.os.BinderProxy@42314cc {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,09-12 13:11:37.129  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-12 13:11:37.129  1176  1176 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,09-12 13:11:37.139  3678  3678 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,09-12 13:11:37.139  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
09-12 13:11:37.139  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:11:37.139  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:11:37.139  1176  1176 D PanelView: There is/are notification(s) 
09-12 13:11:37.139  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-12 13:11:37.139  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.139  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.139  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.139  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.149  1176  1176 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:11:37.149  1176  1176 D PanelView: There is/are notification(s) 
,09-12 13:11:37.149  1176  1176 D PanelView: kidsfalse mQsExpansionEnabled:true
,09-12 13:11:37.149  3678  3678 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-12 13:11:37.149  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:11:37.159  7122  7122 E Zygote  : MountEmulatedStorage()
09-12 13:11:37.159  7122  7122 I libpersona: KNOX_SDCARD checking this for 10044
09-12 13:11:37.159  7122  7122 E Zygote  : v2
09-12 13:11:37.159  7122  7122 I libpersona: KNOX_SDCARD not a persona,
,09-12 13:11:37.159  7122  7122 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:11:37.159  1013  1379 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-12 13:11:37.159  3678  3678 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-12 13:11:37.159  1013  1038 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7122 uid=10044 gids={50044, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-12 13:11:37.169  7122  7122 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:37.169  7122  7122 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:37.179  1013  7128 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-12 13:11:37.179  3678  7121 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-12 13:11:37.179  3678  7121 I KLMS-2.5.183: : KLMSIntentService(): PACKAGE_REMOVED
,09-12 13:11:37.179  1013  1379 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6226 uid 10155
,09-12 13:11:37.179  1176  1176 D PanelView: There is/are notification(s) 
,09-12 13:11:37.179  1013  1038 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-12 13:11:37.179  3117  3117 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@42314cc time:149898
,09-12 13:11:37.179  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.179  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.179  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.179  1013  1038 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.189  1770  1770 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-12 13:11:37.189  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:11:37.189  1013  1131 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,09-12 13:11:37.189  3678  7121 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().START
,09-12 13:11:37.199  7140  7140 E Zygote  : MountEmulatedStorage()
09-12 13:11:37.199  7140  7140 E Zygote  : v2
09-12 13:11:37.199  7140  7140 I libpersona: KNOX_SDCARD checking this for 10149
09-12 13:11:37.199  7140  7140 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:37.199  7140  7140 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:37.199  3678  7121 I KLMS-2.5.183: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-12 13:11:37.209  7140  7140 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-12 13:11:37.209  1013  1038 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7140 uid=10149 gids={50149, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-12 13:11:37.209  7140  7140 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:37.209  1176  1176 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,09-12 13:11:37.219  7122  7122 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:37.219  7122  7122 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.219  1013  3012 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-12 13:11:37.229  1013  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.229  1013  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.229  1013  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.229  1013  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.239  7155  7155 E Zygote  : MountEmulatedStorage(),
09-12 13:11:37.239  7155  7155 E Zygote  : v2
,09-12 13:11:37.239  7155  7155 I libpersona: KNOX_SDCARD checking this for 10094
09-12 13:11:37.239  7155  7155 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:37.239  7155  7155 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:11:37.239  1013  3012 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7155 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
09-12 13:11:37.249  7155  7155 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:37.249  7155  7155 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:11:37.249  6966  7139 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,09-12 13:11:37.249  7140  7140 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:11:37.259  7140  7140 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.259  1013  1043 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1598724c u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t127} time:149976
09-12 13:11:37.259  1013  1043 W ActivityManager: mDVFSHelper.release()
,09-12 13:11:37.289  3678  7121 I KLMS-2.5.183: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-12 13:11:37.299  1013  1053 I art     : Explicit concurrent mark sweep GC freed 6923(380KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 27MB/41MB, paused 4.140ms total 209.702ms
,09-12 13:11:37.299  6966  7139 I art     : Explicit concurrent mark sweep GC freed 654(49KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/9MB, paused 766us total 32.525ms
,09-12 13:11:37.299  7155  7155 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:37.299  7155  7155 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.309  3678  7121 I KLMS-2.5.183: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-12 13:11:37.309  7122  7122 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-12 13:11:37.309  7122  7122 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:11:37.309  7122  7122 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:11:37.309  7122  7122 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.309  7122  7122 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-12 13:11:37.309  7122  7122 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-12 13:11:37.309  7122  7122 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:11:37.309  7122  7122 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 13:11:37.309  3678  7121 I KLMS-2.5.183: : KLMSIntentService(): listeningToPackageRemoved().END
,09-12 13:11:37.319  3678  3678 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,09-12 13:11:37.339  1013  3001 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
,09-12 13:11:37.339  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.339  5950  6696 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
,09-12 13:11:37.339  5950  6696 D BadgeProvider: sendNotify, [notify] : null
,09-12 13:11:37.339  5950  6696 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-12 13:11:37.339  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.339  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.339  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.339  5950  6696 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-12 13:11:37.339  5950  6696 D BadgeProvider: update, [UpdateCount] : 1
,09-12 13:11:37.349  7140  7140 D ThemeInfoUtil: getCurrentFestivalName is [null]
,09-12 13:11:37.349  7140  7140 D ThemeInfoUtil: isCurrentFestival = false
,09-12 13:11:37.359  1013  3001 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7172 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,09-12 13:11:37.369  7172  7172 E Zygote  : MountEmulatedStorage()
09-12 13:11:37.369  7172  7172 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:11:37.369  7172  7172 E Zygote  : v2
09-12 13:11:37.369  7172  7172 I libpersona: KNOX_SDCARD not a persona
09-12 13:11:37.369  7172  7172 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:37.369  7172  7172 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:37.379  1013  3001 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
09-12 13:11:37.379  1013  1670 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
09-12 13:11:37.379  1013  1670 D SecContentProvider2: mCursor = null
09-12 13:11:37.379  7172  7172 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:37.379  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.379  7155  7155 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
09-12 13:11:37.379  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.379  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 13:11:37.379  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-12 13:11:37.379  7155  7155 D elm:15183: ELMEngine.ELMEngine( context ).
,09-12 13:11:37.389  1013  3001 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=7182 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,09-12 13:11:37.399  7182  7182 E Zygote  : MountEmulatedStorage()
09-12 13:11:37.399  7182  7182 I libpersona: KNOX_SDCARD checking this for 10152
09-12 13:11:37.399  7182  7182 E Zygote  : v2
09-12 13:11:37.399  7182  7182 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:37.399  7182  7182 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:37.399  7182  7182 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:37.399  7182  7182 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:37.399  7172  7172 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:37.409  7172  7172 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.419  7155  7155 D elm:15183: MDMBridge.setEnterpriseBridge()
,09-12 13:11:37.419  1013  1137 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:37.419  1013  1137 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
09-12 13:11:37.419  1013  1137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:37.419  1013  1137 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
09-12 13:11:37.419  1013  1137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-12 13:11:37.429  1013  1037 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-12 13:11:37.429  7182  7182 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:37.429  7182  7182 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.439  7155  7155 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-12 13:11:37.439  7155  7155 D elm:15183: ElmAgentService : onCreate()
,09-12 13:11:37.439  7155  7202 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
09-12 13:11:37.449  7155  7202 D elm:15183: MainReceiver.listeningToPackageRemoved()
,09-12 13:11:37.449  7155  7202 D elm:15183: MDMBridge.getInstance()
09-12 13:11:37.449  7155  7202 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
09-12 13:11:37.449  3283  3283 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,09-12 13:11:37.449  3283  3283 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-12 13:11:37.449  3283  3283 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
09-12 13:11:37.449  3283  3283 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
09-12 13:11:37.449  3283  3283 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-12 13:11:37.449  3283  3283 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-12 13:11:37.449  3283  3283 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-12 13:11:37.449  3283  3283 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-12 13:11:37.449  3283  3283 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-12 13:11:37.449  3283  3283 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-12 13:11:37.449  3283  3283 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-12 13:11:37.449  3283  3283 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-12 13:11:37.449  3283  3283 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-12 13:11:37.449  3283  3283 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-12 13:11:37.449  7155  7202 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
,09-12 13:11:37.469  7155  7155 D elm:15183: ElmAgentService : onDestroy().
,09-12 13:11:37.479  7182  7182 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,09-12 13:11:37.489  6531  6531 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,09-12 13:11:37.489  6531  6531 I PCWCLIENTTRACE_PushUtil: sales region : global
,09-12 13:11:37.489  6531  6531 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,09-12 13:11:37.489  6531  6531 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-12 13:11:37.489  7172  7172 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-12 13:11:37.489  1013  1473 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-12 13:11:37.489  1013  1473 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-12 13:11:37.489  1013  1473 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:37.489  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:11:37.489  1013  1473 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-12 13:11:37.499  1013  1473 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-12 13:11:37.509  1013  1670 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-12 13:11:37.509  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.509  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.509  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.509  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.519  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:11:37.519  1013  1053 D PackageManager: delete codoeFile: 
,09-12 13:11:37.529  7207  7207 E Zygote  : MountEmulatedStorage()
,09-12 13:11:37.529  1013  1053 I AASA_removePackage: UID=10155 Target=com.test.thalitest
09-12 13:11:37.529  1013  1053 D AASAuninstall: userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,09-12 13:11:37.529  7207  7207 E Zygote  : v2
09-12 13:11:37.529  7207  7207 I libpersona: KNOX_SDCARD checking this for 10032
09-12 13:11:37.529  7207  7207 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:37.529  7207  7207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:37.539  1013  1053 D PackageManager: result of delete: 1{490952759}
,09-12 13:11:37.539  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:11:37.539  7207  7207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:37.539  7207  7207 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
09-12 13:11:37.539  1013  1670 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7207 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
09-12 13:11:37.539  1013  1670 I ActivityManager: Killing 5497:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,09-12 13:11:37.539  1013  1037 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:11:37.539  1013  1037 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:11:37.539  1013  1037 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.539  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:11:37.539  1013  1670 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
09-12 13:11:37.549  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.549  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.549  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.549  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.559  7219  7219 E Zygote  : MountEmulatedStorage()
,09-12 13:11:37.559  7219  7219 E Zygote  : v2
09-12 13:11:37.559  7219  7219 I libpersona: KNOX_SDCARD checking this for 1000
09-12 13:11:37.559  7219  7219 I libpersona: KNOX_SDCARD not a persona,
09-12 13:11:37.559  7219  7219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:37.569  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:11:37.569  1475  1475 D Launcher.Model: reloadBadges entered.
,09-12 13:11:37.569  7219  7219 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:37.569  7219  7219 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:11:37.569  1013  1670 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7219 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
09-12 13:11:37.569  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:11:37.569  7103  7103 D AndroidRuntime: Shutting down VM
,09-12 13:11:37.579  7207  7207 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:37.579  7207  7207 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.579  1013  1053 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-12 13:11:37.579  1013  1053 D PackageManager: userId{-1}
09-12 13:11:37.579  1013  1053 D PackageManager: andCode{true}
09-12 13:11:37.579  1013  1218 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider
09-12 13:11:37.579  1013  1218 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,09-12 13:11:37.579  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:11:37.579  1013  1218 W ActivityManager: userId = 0, bbcId = -10000
09-12 13:11:37.579  1013  1218 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-12 13:11:37.579  1013  1218 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
09-12 13:11:37.579  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 13:11:37.589  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:11:37.589  1013  1053 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-12 13:11:37.589  7219  7219 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:37.589  7219  7219 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.599  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:11:37.599  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 13:11:37.599  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-12 13:11:37.599  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-12 13:11:37.599  1013  1037 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-12 13:11:37.609  7122  7122 D NearbySource: Nearby Source Create!
,09-12 13:11:37.609  7122  7122 D NearbyContext: Nearby Context Create!
,09-12 13:11:37.619  1013  1670 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
,09-12 13:11:37.619  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.619  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.619  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.619  1013  1670 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.619  1013  1037 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-12 13:11:37.619  1013  1037 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-12 13:11:37.629  1013  1037 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,09-12 13:11:37.629  7219  7219 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:11:37.639  7240  7240 E Zygote  : MountEmulatedStorage(),
09-12 13:11:37.639  7240  7240 E Zygote  : v2
09-12 13:11:37.639  7240  7240 I libpersona: KNOX_SDCARD checking this for 10156
09-12 13:11:37.639  7240  7240 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:37.639  1013  1670 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=7240 uid=10156 gids={50156, 9997} abi=armeabi-v7a,
09-12 13:11:37.639  7240  7240 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:11:37.649  7240  7240 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:37.649  7240  7240 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-12 13:11:37.649  7219  7219 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-12 13:11:37.649  1013  3011 D PersonaManager: isKioskContainerExistOnDevice
,09-12 13:11:37.659  1013  1471 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-12 13:11:37.659  1013  1471 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-12 13:11:37.659   256   513 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-12 13:11:37.659   256   513 W Vold    : Returning OperationFailed - no handler for errno 0
,09-12 13:11:37.659  7122  7122 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
09-12 13:11:37.669  1013  4556 I ActivityManager: Killing 6166:com.google.android.gms:car/u0a12 (adj 15): empty #31
09-12 13:11:37.669  7122  7122 D SLinkSource: Samsung link source created
,09-12 13:11:37.669  1013  4556 I ActivityManager: Killing 5628:com.android.vending/u0a28 (adj 15): empty #31
,09-12 13:11:37.669  1013  4556 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-12 13:11:37.679  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.679  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.679  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.679  1013  4556 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.679  7240  7240 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:37.679  7240  7240 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.679  7207  7253 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-12 13:11:37.699  7257  7257 E Zygote  : MountEmulatedStorage()
09-12 13:11:37.699  7257  7257 I libpersona: KNOX_SDCARD checking this for 10091
09-12 13:11:37.699  7257  7257 E Zygote  : v2
09-12 13:11:37.699  7257  7257 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:37.699  7257  7257 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:37.699  1013  4556 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7257 uid=10091 gids={50091, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:11:37.699  7257  7257 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:11:37.699  7207  7253 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-12 13:11:37.699  1013  4556 I ActivityManager: Killing 6302:com.google.android.gms.unstable/u0a12 (adj 15): empty #31
,09-12 13:11:37.699  7257  7257 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-12 13:11:37.699  7207  7253 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:11:37.699  7207  7253 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:11:37.699  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.699  7207  7253 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 13:11:37.699  7207  7253 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-12 13:11:37.709  7207  7253 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-12 13:11:37.709  7207  7253 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-12 13:11:37.719  7207  7253 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:11:37.719  7207  7253 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:11:37.719  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.719  7207  7253 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-12 13:11:37.719  1013  4556 I ActivityManager: Killing 6593:com.android.chrome/u0a81 (adj 15): empty #31
,09-12 13:11:37.729  7257  7257 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:37.729  7257  7257 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.729   309   309 I art     : Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 646us total 22.472ms
,09-12 13:11:37.739  1013  3011 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-12 13:11:37.739  1013  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.739  1013  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.739  1013  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.739  1013  3011 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.749  7207  7253 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:11:37.749  7207  7253 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:11:37.749  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:11:37.749   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 19.123ms
,09-12 13:11:37.759  7207  7253 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-12 13:11:37.759  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.759  7207  7253 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-12 13:11:37.769  7240  7240 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
09-12 13:11:37.769  7240  7240 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,09-12 13:11:37.769   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 698us total 18.237ms
,09-12 13:11:37.779  7103  7103 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.,
09-12 13:11:37.779  7240  7240 I TapandpayWidget:Utils: Clear T&P info.
,09-12 13:11:37.789  1013  4555 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:11:37.789  7275  7275 E Zygote  : MountEmulatedStorage()
09-12 13:11:37.789  7275  7275 I libpersona: KNOX_SDCARD checking this for 10035
09-12 13:11:37.789  7275  7275 E Zygote  : v2
09-12 13:11:37.789  7275  7275 I libpersona: KNOX_SDCARD not a persona
09-12 13:11:37.789  7275  7275 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:37.789  1013  3011 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7275 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-12 13:11:37.799  7207  7253 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:11:37.799  7275  7275 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:11:37.799  7207  7253 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:11:37.799  7207  7253 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:11:37.799  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.799  7207  7253 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-12 13:11:37.799  1013  3011 I ActivityManager: Killing 6563:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
09-12 13:11:37.799  7207  7253 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-12 13:11:37.799  7207  7253 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:11:37.799  7207  7253 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:11:37.799  7275  7275 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-12 13:11:37.809  7240  7240 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-12 13:11:37.809  1013  1796 D ActivityManager: startProcessLocked calleePkgName: com.sec.enterprise.knox.cloudmdm.smdms, hostingType: broadcast
,09-12 13:11:37.819  1013  1796 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.819  1013  1796 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.819  1013  1796 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.819  1013  1796 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.819  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.819  7207  7253 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:11:37.819  7207  7253 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:11:37.839  1013  1471 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-12 13:11:37.839  7292  7292 E Zygote  : MountEmulatedStorage()
09-12 13:11:37.839  7292  7292 E Zygote  : v2
09-12 13:11:37.839  7292  7292 I libpersona: KNOX_SDCARD checking this for 10160
,09-12 13:11:37.839  6966  6966 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
09-12 13:11:37.839  7292  7292 I libpersona: KNOX_SDCARD not a persona
09-12 13:11:37.839  7122  7122 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
09-12 13:11:37.839  7292  7292 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51,
,09-12 13:11:37.849  1013  1796 I ActivityManager: Start proc com.sec.enterprise.knox.cloudmdm.smdms for broadcast com.sec.enterprise.knox.cloudmdm.smdms/.core.CoreReceiver: pid=7292 uid=10160 gids={50160, 9997, 3003, 3002, 1028, 1015, 3001} abi=armeabi-v7a
09-12 13:11:37.849  1013  1796 I ActivityManager: Killing 6615:com.sec.android.soagent/u0a34 (adj 15): empty #31
09-12 13:11:37.849  7292  7292 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
,09-12 13:11:37.849  7292  7292 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-12 13:11:37.849  7207  7253 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.,
09-12 13:11:37.849  7207  7253 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:11:37.849  7207  7253 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:11:37.849  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.849  7207  7253 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 13:11:37.849  7275  7275 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:11:37.849  7275  7275 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.869  7207  7253 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-12 13:11:37.869  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.869  7207  7253 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-12 13:11:37.869  7207  7253 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:11:37.869  7122  7272 D ContactProvider: getAllContactInfoList Start
,09-12 13:11:37.879  7292  7292 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-12 13:11:37.879  7292  7292 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.889  7207  7253 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
09-12 13:11:37.889  7207  7253 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:11:37.889  7207  7253 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:11:37.889  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.889  7207  7253 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-12 13:11:37.889  1475  1475 D Launcher.Model: reloadBadges entered.
,09-12 13:11:37.889  5950  6696 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps
09-12 13:11:37.889  5950  6696 D BadgeProvider: sendNotify, [notify] : null
09-12 13:11:37.889  5950  6696 D BadgeProvider: update, [uri] : content://com.sec.badge/apps
09-12 13:11:37.889  5950  6696 D BadgeProvider: update, [BadgeCount] : badgecount=0
09-12 13:11:37.889  5950  6696 D BadgeProvider: update, [UpdateCount] : 1
,09-12 13:11:37.909  7257  7257 E PhotosPlugin: Loading PhotosPlugin
,09-12 13:11:37.909  7207  7253 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-12 13:11:37.909  7292  7292 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-12 13:11:37.909  1013  3012 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,09-12 13:11:37.909  7207  7253 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,09-12 13:11:37.909  1013  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.909  1013  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.909  1013  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.909  1013  3012 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.929  7308  7308 E Zygote  : MountEmulatedStorage(),
09-12 13:11:37.929  7308  7308 E Zygote  : v2
09-12 13:11:37.929  7308  7308 I libpersona: KNOX_SDCARD checking this for 10046
09-12 13:11:37.929  7308  7308 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:37.929  7308  7308 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
09-12 13:11:37.929  1013  3012 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.freemessage.FreeMessageStatusReceiver: pid=7308 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,09-12 13:11:37.929  7308  7308 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051
09-12 13:11:37.929  7275  7312 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,09-12 13:11:37.929  1013  1670 I ActivityManager: Killing 6435:com.google.android.talk/u0a104 (adj 15): empty #31
,09-12 13:11:37.939  1013  3001 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
09-12 13:11:37.939  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.939  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.939  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-12 13:11:37.939  1013  3001 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-12 13:11:37.939  7308  7308 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-12 13:11:37.939  7275  7312 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,09-12 13:11:37.949  7292  7292 D [0]UMC:UMCContentProvider: @onCreate
,09-12 13:11:37.959  7275  7312 D SPPClientService: PushLog.txt file is not deleted.
09-12 13:11:37.959  7275  7312 D SPPClientService: PushLog.txt file is not deleted.
09-12 13:11:37.959  7275  7312 D SPPClientService: ============PushLog. stop!
,09-12 13:11:37.959  7207  7253 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-12 13:11:37.959  7207  7253 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
09-12 13:11:37.959  7207  7253 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-12 13:11:37.959  7207  7253 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:11:37.959  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:37.959  7207  7253 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 13:11:37.959  7325  7325 E Zygote  : MountEmulatedStorage()
09-12 13:11:37.959  7325  7325 E Zygote  : v2
09-12 13:11:37.959  7325  7325 I libpersona: KNOX_SDCARD checking this for 10038
09-12 13:11:37.959  7325  7325 I libpersona: KNOX_SDCARD not a persona
,09-12 13:11:37.959  7325  7325 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=51
,09-12 13:11:37.969  7325  7325 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0051,
09-12 13:11:37.969  7308  7308 D TimaKeyStoreProvider: TimaSignature is unavailable,
09-12 13:11:37.969  7325  7325 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL,
09-12 13:11:37.969  7308  7308 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.969  1013  3001 I ActivityManager: Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=7325 uid=10038 gids={50038, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
09-12 13:11:37.969  1013  3001 I ActivityManager: Killing 6635:com.google.android.apps.magazines/u0a113 (adj 15): empty #31
,09-12 13:11:37.969  7292  7292 D [0]UMC:Core: onCreate(): 
09-12 13:11:37.969  7292  7292 D [0]UMC:Core: @isManagedProfileUser
09-12 13:11:37.969  7292  7292 D [0]UMC:Core: userId: 0
,09-12 13:11:37.979  7292  7292 D [0]UMC:Core: userInfo: UserInfo{0:Thali Test:13}
09-12 13:11:37.979  7292  7292 D [0]UMC:Core: userInfo.isManagedProfile() : false
,09-12 13:11:37.979  7122  7272 D ContactProvider: getAllContactInfoList End
,09-12 13:11:37.979  7122  7272 I syncContacts: thread: 1178, sync time = 232
,09-12 13:11:37.989  7207  7253 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-12 13:11:37.989  7207  7253 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:11:37.989  7325  7325 D TimaKeyStoreProvider: TimaSignature is unavailable
09-12 13:11:37.989  7325  7325 D ActivityThread: Added TimaKeyStore provider
,09-12 13:11:37.999  7308  7308 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-12 13:11:37.999  7308  7308 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-12 13:11:37.999  7308  7308 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
09-12 13:11:37.999  7308  7308 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-12 13:11:37.999  7308  7308 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-12 13:11:37.999  7308  7308 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-12 13:11:38.009  7207  7253 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
,09-12 13:11:38.009  7325  7325 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-12 13:11:38.009  7325  7325 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-12 13:11:38.019  7275  7275 W FileUtils: Failed to chmod(/data/data/com.sec.spp.push/databases/push_noti_db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,09-12 13:11:38.039  7292  7292 D [0]UMC:DeviceInfo: USA==US==
,09-12 13:11:38.049  7308  7308 D Mms/MmsApp: [start]    onCreate() consume time = 0.0

```
