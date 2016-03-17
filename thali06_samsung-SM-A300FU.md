#### Test 62509094764c200_thali06_samsung-SM-A300FU Logs


```
--------- beginning of system
,03-17 06:46:57.255  1019  1316 E Watchdog: !@Sync 6
--------- beginning of main
03-17 06:46:57.515  6167  6167 D AndroidRuntime: 
03-17 06:46:57.515  6167  6167 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-17 06:46:57.525  6167  6167 D AndroidRuntime: CheckJNI is OFF
03-17 06:46:57.525  6167  6167 D AndroidRuntime: readGMSProperty: start
03-17 06:46:57.525  6167  6167 D AndroidRuntime: readGMSProperty: already setted!!
03-17 06:46:57.525  6167  6167 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-17 06:46:57.525  6167  6167 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 06:46:57.525  6167  6167 D AndroidRuntime: readGMSProperty: end
03-17 06:46:57.525  6167  6167 D AndroidRuntime: addProductProperty: start
03-17 06:46:57.655  6167  6167 E AffinityControl: AffinityControl: registerfunction enter
03-17 06:46:57.675  6167  6167 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-17 06:46:57.685  1019  1480 E PersonaManagerService: inState():  stateMachine is null !!
03-17 06:46:57.685  1019  1480 I PersonaManagerService: PersonaId don't exist
03-17 06:46:57.685  1019  1480 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-17 06:46:57.695  1019  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:46:57.705  1019  1480 W ActivityManager: mDVFSHelper.acquire()
03-17 06:46:57.705  1019  1480 D FocusedStackFrame: Set to : 0
03-17 06:46:57.705  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:46:57.705  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:46:57.705  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:46:57.705  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:46:57.715  1019  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-17 06:46:57.715  1019  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-17 06:46:57.725  6179  6179 E Zygote  : MountEmulatedStorage()
03-17 06:46:57.725  6179  6179 E Zygote  : v2
03-17 06:46:57.725  6179  6179 I libpersona: KNOX_SDCARD checking this for 10167
03-17 06:46:57.725  1019  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 06:46:57.725  6179  6179 I libpersona: KNOX_SDCARD not a persona
03-17 06:46:57.725  1019  1480 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:46:57.725  1019  1480 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6179 uid=10167 gids={50167, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-17 06:46:57.725  1019  1480 D InputDispatcher: Focused application set to: xxxx
03-17 06:46:57.725  1019  1480 D InputDispatcher: Focus left window: 1481
03-17 06:46:57.735  6167  6167 D AndroidRuntime: Shutting down VM
03-17 06:46:57.735  6179  6179 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:46:57.735  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-17 06:46:57.735  1019  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-17 06:46:57.735   258   258 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
03-17 06:46:57.735  6179  6179 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:46:57.735  6179  6179 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-17 06:46:57.755  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:46:57.755  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:46:57.755  6179  6179 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:46:57.755  6179  6179 D ActivityThread: Added TimaKeyStore provider
03-17 06:46:57.765  1019  1032 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-17 06:46:57.765  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-17 06:46:57.775  1019  1032 D PersonaManager: isKioskContainerExistOnDevice
03-17 06:46:57.795  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-17 06:46:57.815   258  1830 I SurfaceFlinger: id=9 Removed Mauncher (5/9)
03-17 06:46:57.815   258  1099 I SurfaceFlinger: id=9 Removed Mauncher (-2/9)
03-17 06:46:57.825  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{17ec0e91 token=android.os.BinderProxy@33289857 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-17 06:46:57.825  1481  1481 D Launcher: onTrimMemory. Level: 20
03-17 06:46:57.885  6179  6179 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
03-17 06:46:57.905  6179  6179 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8727-8730)
03-17 06:46:57.905  6179  6179 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 06:46:57.925  6179  6179 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2822ec6c}
03-17 06:46:57.925  6179  6179 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-17 06:46:57.925  6179  6179 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-17 06:46:57.935  6167  6167 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 06:46:57.955  6179  6179 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-17 06:46:57.955  6179  6179 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:46:57.955  6179  6179 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-17 06:46:57.975  6179  6179 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-17 06:46:57.975  6179  6179 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 06:46:57.975  6179  6179 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-17 06:46:57.985  6179  6179 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-17 06:46:57.985  6179  6179 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-17 06:46:57.985  6179  6179 I Adreno-EGL: Build Date: 04/06/15 Mon
03-17 06:46:57.985  6179  6179 I Adreno-EGL: Local Branch: 
03-17 06:46:57.985  6179  6179 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-17 06:46:57.985  6179  6179 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-17 06:46:57.985  6179  6179 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-17 06:46:58.205  6179  6179 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:46:58.215  6179  6179 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-17 06:46:58.225  6179  6179 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-17 06:46:58.225  6179  6179 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-17 06:46:58.235  6179  6179 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-17 06:46:58.245  6179  6179 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:46:58.245  6179  6179 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-17 06:46:58.285  1019  1044 W ActivityManager: Activity pause timeout for ActivityRecord{30e45d17 u0 com.test.thalitest/.MainActivity t23}
,03-17 06:46:58.295  6179  6219 D OpenGLRenderer: Render dirty regions requested: true
,03-17 06:46:58.295  1019  1032 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-17 06:46:58.295  1019  1032 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 06:46:58.295  1019  1032 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 06:46:58.305  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 06:46:58.305  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
,03-17 06:46:58.305  6179  6206 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-17 06:46:58.305  6179  6179 V ActivityThread: updateVisibility : ActivityRecord{14030f34 token=android.os.BinderProxy@2492c046 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,03-17 06:46:58.315  6179  6179 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-17 06:46:58.315  6179  6179 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-17 06:46:58.325   258   258 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,03-17 06:46:58.325  1019  1364 D InputDispatcher: Focus entered window: 6179
,03-17 06:46:58.335  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:46:58.335  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-17 06:46:58.335  6179  6179 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 06:46:58.335  6179  6219 I OpenGLRenderer: Initialized EGL, version 1.4
,03-17 06:46:58.335  6179  6219 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,03-17 06:46:58.335  6179  6219 D OpenGLRenderer: Enabling debug mode 0,
,03-17 06:46:58.385  1019  1365 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-17 06:46:58.385  1019  6221 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:46:58.395  6179  6179 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2492c046 time:199221
,03-17 06:46:58.395  1176  1176 I StatusBar: Icon Only
,03-17 06:46:58.395  1176  1176 D PanelView: There is/are notification(s) 
,03-17 06:46:58.395  6179  6179 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 06:46:58.405  1019  1049 I ActivityManager: Displayed Component not be shown by security: +623ms (total +1m21s349ms)
,03-17 06:46:58.405  1019  1049 W ActivityManager: mDVFSHelper.release()
,03-17 06:46:58.405  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{30e45d17 u0 com.test.thalitest/.MainActivity t23} time:199237
,03-17 06:46:58.415   258  1830 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,03-17 06:46:58.415   258   451 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,03-17 06:46:58.445   292   292 E SMD     : DCD OFF
,03-17 06:46:58.455  1796  1796 I SamsungIME: getCurrentCandidateView
,03-17 06:46:58.505  1796  1796 D SamsungIME: Dismiss ExpandCandiate
,03-17 06:46:58.545  1796  1796 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 06:46:58.585  1796  1796 I SamsungIME: getDebugLevel  : 0x4f4c
,03-17 06:46:58.595  6179  6179 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6179
,03-17 06:46:58.615  1796  1796 I SamsungIME: KeybaordView init() : load resources,
,03-17 06:46:58.645  1796  1796 I SamsungIME: getCurrentKeyboard
03-17 06:46:58.645  1796  1796 I SamsungIME: getTextKeyboard
,03-17 06:46:58.665  1796  1796 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-17 06:46:58.725  6179  6179 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-17 06:46:58.935  6179  6224 D jxcore_app_log: JniHelper::setJavaVM(0xb7e59448), pthread_self() = -1204040872
,03-17 06:46:58.945  6179  6224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-17 06:46:58.945  6179  6224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-17 06:46:58.945  6179  6224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-17 06:46:58.945  6179  6224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-17 06:46:58.945  6179  6224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-17 06:46:58.945  6179  6224 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f07bcd added. We now have 1 listener(s)
,03-17 06:46:58.945  6179  6224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,03-17 06:46:58.955  6179  6224 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
,03-17 06:46:58.955  6179  6224 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"08:EC:A9:50:75:41"}
03-17 06:46:58.955  6179  6224 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-17 06:46:58.955  6179  6224 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c0f3bd0 added. We now have 1 listener(s)
,03-17 06:46:58.955  6179  6224 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-17 06:46:58.965  6179  6224 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-17 06:46:58.965  6179  6224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-17 06:46:58.965  6179  6224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-17 06:46:58.965  6179  6224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-17 06:46:58.965  6179  6224 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-17 06:46:58.965  6179  6224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-17 06:46:58.965  6179  6224 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41
,03-17 06:46:58.975  6179  6224 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-17 06:46:58.975  6179  6224 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-17 06:46:58.975  6179  6224 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-17 06:46:58.975  6179  6224 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-17 06:46:58.975  6179  6224 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-17 06:46:58.975  6179  6224 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-17 06:46:58.975  6179  6224 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-17 06:46:58.975  6179  6224 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-17 06:46:58.975  6179  6224 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-17 06:46:58.975  6179  6224 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-17 06:46:58.975  6179  6179 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 06:46:58.985  6179  6179 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-17 06:46:59.005  6179  6179 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-17 06:46:59.515  6179  6230 W jxcore-log: Initializing JXcore engine
03-17 06:46:59.515  6179  6230 W jxcore-log: JXcore engine is ready
,03-17 06:46:59.575  1895  1895 E audit   : type=1400 msg=audit(1458193619.575:205): avc:  denied  { ioctl } for  pid=6230 comm="Thread-1065" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-17 06:46:59.575  1895  1895 E audit   :  SEPF_SM-A300FU_5.0.2_0027
03-17 06:46:59.575  1895  1895 E audit   : type=1300 msg=audit(1458193619.575:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9ee8d8f8 items=0 ppid=309 ppcomm=main pid=6230 auid=4294967295 uid=10167 gid=10167 euid=10167 suid=10167 fsuid=10167 egid=10167 sgid=10167 fsgid=10167 ses=4294967295 tty=(none) comm="Thread-1065" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-17 06:46:59.575  1895  1895 E audit   : type=1320 msg=audit(1458193619.575:205): 
,03-17 06:46:59.585  6179  6230 W jxcore-log: Starting JXcore engine
,03-17 06:46:59.685  6179  6230 W jxcore-log: Platform android
03-17 06:46:59.685  6179  6230 W jxcore-log: 
03-17 06:46:59.685  6179  6230 W jxcore-log: Process ARCH arm
03-17 06:46:59.685  6179  6230 W jxcore-log: 
,03-17 06:46:59.895  6179  6230 I jxcore-log: JXcore Cordova bridge is ready!
03-17 06:46:59.895  6179  6230 I jxcore-log: 
,03-17 06:46:59.895  6179  6230 W jxcore-log: JXcore engine is started
,03-17 06:46:59.905  6179  6224 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,03-17 06:46:59.905  6179  6179 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-17 06:46:59.915  6179  6230 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-17 06:46:59.915  6179  6230 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-17 06:46:59.925  6179  6179 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-17 06:46:59.925  6179  6179 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-17 06:46:59.925  1019  1704 D FocusedStackFrame: Set to : 0
03-17 06:46:59.925  1019  1704 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-17 06:46:59.925  1019  1704 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-17 06:46:59.925  1019  1704 D InputDispatcher: Focused application set to: xxxx
03-17 06:46:59.925  1019  1704 D InputDispatcher: Focus left window: 6179
03-17 06:46:59.935  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:46:59.935  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:46:59.935  1019  1704 I ActivityManager: Killing 5611:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
,03-17 06:46:59.955   258  1830 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,03-17 06:46:59.955   258   451 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,03-17 06:46:59.965  1019  1031 W ActivityManager: mDVFSHelper.acquire()
,03-17 06:46:59.975  1019  1031 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-17 06:46:59.975  6179  6179 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@99607c9 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 06:46:59.975  6179  6179 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@99607c9 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:46:59.975  6179  6179 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:46:59.985  6179  6179 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@19b6bece that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 06:46:59.985  6179  6179 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@19b6bece that was originally registered here. Are you missing a call to unregisterReceiver()?
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:46:59.985  6179  6179 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-17 06:46:59.985  1019  1097 V AlarmManager: waitForAlarm result :8
,03-17 06:46:59.995  1481  1481 D Launcher: onRestart, Launcher: 504406075
,03-17 06:46:59.995  1481  1481 D Launcher: onStart, Launcher: 504406075
,03-17 06:46:59.995  1481  1481 D Launcher.HomeView: onStart
,03-17 06:46:59.995  1481  1481 D Launcher: onResume, Launcher: 504406075
,03-17 06:46:59.995  1019  1480 D SettingsProvider: name = kids_home_mode
03-17 06:46:59.995  1019  1480 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-17 06:46:59.995  1019  1480 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-17 06:46:59.995  1019  1480 D SettingsProvider: selectionArgs: false
03-17 06:46:59.995  1019  1480 D SettingsProvider: selectionArgs: 10006
03-17 06:46:59.995  1019  1480 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-17 06:46:59.995  1019  1480 D SettingsProvider: ret = -1
,03-17 06:46:59.995  1481  1481 D Launcher.HomeView: onResume
,03-17 06:47:00.005  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-17 06:47:00.005  1481  1481 D MenuAppsGridFragment: onResume
,03-17 06:47:00.005  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:47:00.005  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:47:00.005  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 06:47:00.005  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
03-17 06:47:00.005  1481  1481 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-17 06:47:00.015  1019  1032 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=5, mSplitNum[2]=7, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=9
,03-17 06:47:00.015  1019  1032 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,03-17 06:47:00.015  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:47:00.015  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:00.015  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,03-17 06:47:00.025  5007  5007 D GalleryCacheReady: Receive : home resume
,03-17 06:47:00.035  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:47:00.035  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:00.035  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
03-17 06:47:00.035  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:47:00.035  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:00.035  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,03-17 06:47:00.045  2412  2412 D Recents_RecreateReceiver: onReceive by home
,03-17 06:47:00.045  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:47:00.045  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:00.045  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
03-17 06:47:00.045  1019  1044 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.sec.android.widgetapp.activeapplicationwidget/com.sec.android.widgetapp.activeapplicationwidget.ProgramMonitorProvider}
03-17 06:47:00.045  1019  1044 W BroadcastQueue: android.os.DeadObjectException
03-17 06:47:00.045  1019  1044 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
03-17 06:47:00.045  1019  1044 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:511)
03-17 06:47:00.045  1019  1044 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:969)
03-17 06:47:00.045  1019  1044 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:309)
03-17 06:47:00.045  1019  1044 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1236)
03-17 06:47:00.045  1019  1044 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:194)
03-17 06:47:00.045  1019  1044 W BroadcastQueue: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-17 06:47:00.045  1019  1044 W BroadcastQueue: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:47:00.045  1019  1044 W BroadcastQueue: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-17 06:47:00.045  1019  1044 W BroadcastQueue: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
03-17 06:47:00.045  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:00.045  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:00.045  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:00.045  1019  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:00.055  1019  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_5611/cgroup.procs: No such file or directory
,03-17 06:47:00.065  6236  6236 E Zygote  : MountEmulatedStorage(),
03-17 06:47:00.065  6236  6236 I libpersona: KNOX_SDCARD checking this for 10139
03-17 06:47:00.065  6236  6236 E Zygote  : v2,
03-17 06:47:00.065  6236  6236 I libpersona: KNOX_SDCARD not a persona
03-17 06:47:00.065  6236  6236 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:47:00.075  1019  1044 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=6236 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,03-17 06:47:00.075  6236  6236 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:47:00.075  6236  6236 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-17 06:47:00.075  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:47:00.075  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:00.075  1019  1019 D PersonaManagerService: getPersonasForUser(): returning null!
03-17 06:47:00.075  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms,
03-17 06:47:00.075  5693  5693 D Mms/UIEventReceiver: ui event
03-17 06:47:00.075  1019  1479 D ActivityManager: handle home activity for 0
03-17 06:47:00.075  1019  1479 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-17 06:47:00.075  1019  1479 D KnoxTimeoutHandler: post home show event for user 0
03-17 06:47:00.075  1019  1019 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-17 06:47:00.075  1019  1479 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-17 06:47:00.075  1019  1479 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-17 06:47:00.075  1019  1019 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-17 06:47:00.075  1019  1479 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-17 06:47:00.075  1019  1019 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-17 06:47:00.085  1481  1481 D Launcher.HomeView: onPause
03-17 06:47:00.085  1481  1481 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-17 06:47:00.085  1019  3928 W ActivityManager: Spurious death for ProcessRecord{173fd60b 6236:com.sec.android.widgetapp.activeapplicationwidget/u0a139}, curProc for 5611: null
,03-17 06:47:00.095  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:47:00.095  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:00.095  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,03-17 06:47:00.095   258   258 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,03-17 06:47:00.095  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:00.095  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:00.095  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:00.095  1019  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:47:00.095  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-17 06:47:00.105  1019  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams,
,03-17 06:47:00.115  1019  3927 D InputDispatcher: Focus entered window: 1481
,03-17 06:47:00.115  6251  6251 E Zygote  : MountEmulatedStorage(),
03-17 06:47:00.115  6251  6251 I libpersona: KNOX_SDCARD checking this for 10135
03-17 06:47:00.115  6251  6251 E Zygote  : v2
03-17 06:47:00.115  6251  6251 I libpersona: KNOX_SDCARD not a persona
03-17 06:47:00.115  6251  6251 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:47:00.115  1019  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-17 06:47:00.115  1019  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
03-17 06:47:00.115  1481  1481 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-17 06:47:00.115  1019  1032 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=6251 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,03-17 06:47:00.125  6236  6236 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:47:00.125  6251  6251 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,03-17 06:47:00.125  6236  6236 D ActivityThread: Added TimaKeyStore provider
,03-17 06:47:00.125  6251  6251 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-17 06:47:00.135  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:47:00.135  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:00.135  1019  1032 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1481, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
03-17 06:47:00.135  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,03-17 06:47:00.145  1019  1139 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false,
03-17 06:47:00.145  1019  6261 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-17 06:47:00.145   309   309 I art     : Explicit concurrent mark sweep GC freed 8691(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 1.670ms total 25.630ms
03-17 06:47:00.145  1176  1176 I StatusBar: Icon Only
03-17 06:47:00.145  1176  1176 D PanelView: There is/are notification(s) ,
03-17 06:47:00.145  6179  6179 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-17 06:47:00.165  1796  1796 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-17 06:47:00.165   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 566us total 18.490ms
,03-17 06:47:00.185  6251  6251 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:47:00.185  1481  1481 V ActivityThread: updateVisibility : ActivityRecord{17ec0e91 token=android.os.BinderProxy@33289857 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-17 06:47:00.185  1481  1481 D Launcher.HomeView: onStop
,03-17 06:47:00.185   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 18.034ms
03-17 06:47:00.185  6251  6251 D ActivityThread: Added TimaKeyStore provider
03-17 06:47:00.185  6236  6236 V TaskCloserActivity: TaskCloserActivity enter()
,03-17 06:47:00.195  1481  1481 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@33289857 time:201022
,03-17 06:47:00.195  6236  6236 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,03-17 06:47:00.195  1019  1532 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:47:00.195  1019  1532 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:00.195  1019  1532 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,03-17 06:47:00.195  1019  1532 I ActivityManager: Killing 5147:com.google.android.talk/u0a102 (adj 15): empty #31
,03-17 06:47:00.205  1019  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{252a833b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t21} time:201035
03-17 06:47:00.205  1019  1049 W ActivityManager: mDVFSHelper.release()
,03-17 06:47:00.205  6251  6251 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-17 06:47:00.205  6251  6251 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:47:00.205  6251  6251 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-17 06:47:00.205  6251  6251 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-17 06:47:00.205  6251  6251 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-17 06:47:00.235  6233  6233 D AndroidRuntime: 
03-17 06:47:00.235  6233  6233 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-17 06:47:00.245  1019  1019 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-17 06:47:00.245  6233  6233 D AndroidRuntime: CheckJNI is OFF
,03-17 06:47:00.245  6233  6233 D AndroidRuntime: readGMSProperty: start
03-17 06:47:00.245  6233  6233 D AndroidRuntime: readGMSProperty: already setted!!
03-17 06:47:00.245  6233  6233 D AndroidRuntime: propertySet: couldn't set property (it is from app),
03-17 06:47:00.245  6233  6233 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-17 06:47:00.245  6233  6233 D AndroidRuntime: readGMSProperty: end
,03-17 06:47:00.245  6233  6233 D AndroidRuntime: addProductProperty: start
,03-17 06:47:00.255  1019  3945 I splitIntent: Queue : backgroundsplit_1 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-17 06:47:00.255  1019  3945 I ActivityManager: Killing 4210:com.sec.spp.push/u0a32 (adj 15): empty #31,
,03-17 06:47:00.265  1019  1044 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:47:00.265  1019  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:00.265  1019  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
03-17 06:47:00.275  6236  6236 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,03-17 06:47:00.305  1019  3944 D PersonaManager: isKioskContainerExistOnDevice,
,03-17 06:47:00.365  1019  1043 W libprocessgroup: failed to open /acct/uid_10102/pid_5147/cgroup.procs: No such file or directory,
03-17 06:47:00.365  1019  1043 W libprocessgroup: failed to open /acct/uid_10032/pid_4210/cgroup.procs: No such file or directory
,03-17 06:47:00.445  6233  6233 E AffinityControl: AffinityControl: registerfunction enter,
,03-17 06:47:00.465  6233  6233 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-17 06:47:00.475  1019  1704 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
03-17 06:47:00.475  1019  1704 D PackageManager: START PACKAGE DELETE: observer{820489448}
03-17 06:47:00.475  1019  1704 D PackageManager: pkg{<packageName>}
03-17 06:47:00.475  1019  1704 D PackageManager: user{0}
03-17 06:47:00.475  1019  1704 D PackageManager: caller{2000}
03-17 06:47:00.475  1019  1704 D PackageManager: flags{2}
03-17 06:47:00.475  1019  1704 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true,
03-17 06:47:00.475  1019  1057 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-17 06:47:00.475  1019  1704 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-17 06:47:00.485  1019  1057 D PackageManager: !@killApplicatoin: 10167, uninstall pkg
03-17 06:47:00.475  1019  1704 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 06:47:00.475  1019  1704 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-17 06:47:00.475  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0,
03-17 06:47:00.475  1019  1057 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-17 06:47:00.475  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled
03-17 06:47:00.475  1019  1057 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-17 06:47:00.485  1019  1044 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=-1: uninstall pkg
03-17 06:47:00.485  1019  1044 I ActivityManager: Killing 6179:com.test.thalitest/u0a167 (adj 13): stop com.test.thalitest cause uninstall pkg
,03-17 06:47:00.555  1019  1057 W PackageSettings: Skipping PackageSetting{2fbf8b15 com.example.hello/10346} due to missing metadata
,03-17 06:47:00.595  1019  1057 I ActivityManager: Force stopping com.test.thalitest appid=10167 user=0: pkg removed
,03-17 06:47:00.605  1019  1057 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-17 06:47:00.655  3911  3911 I art     : Explicit concurrent mark sweep GC freed 2537(152KB) AllocSpace objects, 1(16KB) LOS objects, 50% free, 3MB/7MB, paused 804us total 40.065ms
,03-17 06:47:00.665  1019  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-17 06:47:00.675  5954  5954 I art     : Explicit concurrent mark sweep GC freed 3751(193KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 3MB/5MB, paused 834us total 60.840ms
,03-17 06:47:00.685  1796  1796 E SamsungIME: mOCRHelper is null
,03-17 06:47:00.685  6025  6025 I art     : Explicit concurrent mark sweep GC freed 447(29KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 6MB/8MB, paused 928us total 78.778ms
,03-17 06:47:00.705  1019  1123 V NetworkStats: removeUidsLocked() for UIDs [10167]
03-17 06:47:00.705  1019  1123 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 06:47:00.705  1019  1123 V NetworkStats: performPollLocked(flags=0x3)
,03-17 06:47:00.705  1019  1123 D NetworkStatsFactory: UpdateStatsForKnox updated
03-17 06:47:00.705  1019  1123 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-17 06:47:00.715  1019  1123 V NetworkStats: performPollLocked() took 9ms
,03-17 06:47:00.715  1019  1123 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 06:47:00.725  3647  3647 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Mar 17 06:47:00 GMT+01:00 2016
,03-17 06:47:00.745  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
03-17 06:47:00.745  1019  1124 D NtpTrustedTime: currentTimeMillis() cache hit
,03-17 06:47:00.825  1019  1019 I art     : Explicit concurrent mark sweep GC freed 60707(3MB) AllocSpace objects, 41(664KB) LOS objects, 33% free, 24MB/36MB, paused 2.814ms total 213.997ms
,03-17 06:47:00.825  1019  1294 I art     : WaitForGcToComplete blocked for 140.044ms for cause Explicit
,03-17 06:47:00.835  1444  1444 D RegisteredServicesCache: empty dynamic service
,03-17 06:47:00.875  1019  1019 D RCPManagerService: PackageReceiver onReceive()
,03-17 06:47:00.875  1019  1019 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-17 06:47:00.875  1019  1019 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,03-17 06:47:00.935  1019  1019 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-17 06:47:00.935  1019  1019 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-17 06:47:00.935  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-17 06:47:00.935  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-17 06:47:00.935  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 06:47:00.935  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 06:47:00.935  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 06:47:00.935  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 06:47:00.935  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 06:47:00.935  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 06:47:00.935  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 06:47:00.935  1019  1019 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-17 06:47:00.945  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-17 06:47:00.945  1019  1019 V EnterpriseBillingPolicy: uID is 10167
03-17 06:47:00.945  1019  1019 V EnterpriseBillingPolicy: Removed Packageuid is0
03-17 06:47:00.945  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-17 06:47:00.945  1019  1019 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-17 06:47:00.945  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-17 06:47:00.945  1019  1019 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-17 06:47:00.945  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-17 06:47:00.945  1019  1019 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-17 06:47:00.945  1019  2748 D SSRM:aZ : MSG_TYPE_APP_REMOVED::
03-17 06:47:00.945  1019  1161 D TaskPersister: removeObsoleteFile: deleting file=23_task.xml
,03-17 06:47:00.975  1019  1294 I art     : Explicit concurrent mark sweep GC freed 15656(838KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.338ms total 154.402ms
03-17 06:47:00.975  1019  1057 I art     : WaitForGcToComplete blocked for 281.195ms for cause Explicit
,03-17 06:47:00.985  1019  3928 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-17 06:47:00.985  1019  3928 D SecContentProvider2: mCursor = null
,03-17 06:47:00.985  1838  2080 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-17 06:47:00.995  1019  1365 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:47:00.995  1019  1365 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:00.995  1019  1365 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-17 06:47:00.995  1019  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
03-17 06:47:00.995  1019  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
03-17 06:47:00.995  1019  1043 W TextServicesManagerService: no available spell checker services found
,03-17 06:47:01.005  3647  3647 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,03-17 06:47:01.005  1019  1480 I splitIntent: intent=android.intent.action.PACKAGE_REMOVED will be not split. because same process=com.google.process.gapps is in other queue. index=27
03-17 06:47:01.005  1019  1480 I splitIntent: base  index=27, name=com.google.android.gms com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver
03-17 06:47:01.005  1019  1480 I splitIntent: other index=30, name=com.google.android.gms com.google.android.gms.app.receiver.SystemBroadcastReceiver
03-17 06:47:01.005  1019  1480 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.PACKAGE_REMOVED !! do not split it!!
,03-17 06:47:01.015  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:01.015  3647  3647 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
03-17 06:47:01.015  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:01.015  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:01.015  1019  1480 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:47:01.015  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.015  3647  3647 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-17 06:47:01.015  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.025  3647  3647 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-17 06:47:01.025  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
,03-17 06:47:01.025  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.035  6282  6282 E Zygote  : MountEmulatedStorage()
,03-17 06:47:01.035  3647  6281 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
03-17 06:47:01.035  6282  6282 E Zygote  : v2
03-17 06:47:01.035  6282  6282 I libpersona: KNOX_SDCARD checking this for 10090
03-17 06:47:01.035  6282  6282 I libpersona: KNOX_SDCARD not a persona
,03-17 06:47:01.035  6282  6282 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:47:01.035  3647  6281 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,03-17 06:47:01.035  1019  1480 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6282 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,03-17 06:47:01.035  6282  6282 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:47:01.045  3647  6281 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,03-17 06:47:01.045  6282  6282 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-17 06:47:01.045  3647  6281 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,03-17 06:47:01.055  6282  6282 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:47:01.055  6282  6282 D ActivityThread: Added TimaKeyStore provider
,03-17 06:47:01.095  3647  6281 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,03-17 06:47:01.105  6282  6282 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,03-17 06:47:01.105  6282  6282 D elm:15121: ELMEngine.ELMEngine( context ).
03-17 06:47:01.105  6282  6282 D elm:15121: MDMBridge.setEnterpriseBridge()
,03-17 06:47:01.105  1019  3944 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:47:01.105  1019  3944 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:01.105  1019  3944 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-17 06:47:01.105  6282  6282 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,03-17 06:47:01.115  3647  6281 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,03-17 06:47:01.115  6282  6282 D elm:15121: ElmAgentService : onCreate()
,03-17 06:47:01.115  6282  6297 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,03-17 06:47:01.115  6282  6297 D elm:15121: MainReceiver.listeningToPackageRemoved()
03-17 06:47:01.115  6282  6297 D elm:15121: MDMBridge.getInstance()
,03-17 06:47:01.115  6282  6297 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
03-17 06:47:01.115  3647  6281 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,03-17 06:47:01.125  6282  6297 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK(),
,03-17 06:47:01.125  3647  3647 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,03-17 06:47:01.125  5741  5741 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-17 06:47:01.125  5741  5741 I PCWCLIENTTRACE_PushUtil: sales region : global
03-17 06:47:01.125  5741  5741 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-17 06:47:01.125  5741  5741 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,03-17 06:47:01.125  1019  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-17 06:47:01.135  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.135  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.145  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.145  1019  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-17 06:47:01.145  1019  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-17 06:47:01.145  1019  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:47:01.145  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.145  1019  1057 I art     : Explicit concurrent mark sweep GC freed 4994(297KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.059ms total 167.781ms
,03-17 06:47:01.155  6282  6282 D elm:15121: ElmAgentService : onDestroy().
,03-17 06:47:01.155  5832  5832 I SA      : [SUR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,03-17 06:47:01.155  5832  5832 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10167 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,03-17 06:47:01.165  1019  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:47:01.165  1019  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:01.165  1019  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.acore, destAppInfo.processName = android.process.acore
,03-17 06:47:01.175  5007  5007 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,03-17 06:47:01.185  5693  5693 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,03-17 06:47:01.185  1019  1704 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:47:01.185  1019  1704 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:01.185  1019  1704 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,03-17 06:47:01.195  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.195  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.195  1019  1057 D PackageManager: delete codoeFile: 
,03-17 06:47:01.195  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:47:01.195  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 06:47:01.195  1019  1057 D AASAuninstall: userId = 0, info.removedAppID = 10167, info.uid = 10167, packageName = com.test.thalitest
03-17 06:47:01.195  1019  1057 I AASA_removePackage: UID=10167 Target=com.test.thalitest
,03-17 06:47:01.195  1019  1057 D PackageManager: result of delete: 1{820489448}
,03-17 06:47:01.195  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.205  1019  1479 I TactileAssist: enable value -1
,03-17 06:47:01.205  1019  1479 I TactileAssist: internal enable value -1
,03-17 06:47:01.205  1019  1479 I TactileAssist: intensity value -1
03-17 06:47:01.205  1019  1479 I TactileAssist: saveAppList value true
,03-17 06:47:01.205  6233  6233 D AndroidRuntime: Shutting down VM
,03-17 06:47:01.205  5693  6300 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
03-17 06:47:01.205  5693  6300 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,03-17 06:47:01.215  1019  1479 I TactileAssist: List of disabled apps :
,03-17 06:47:01.215  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.215  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 06:47:01.215  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-17 06:47:01.215  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-17 06:47:01.215  1019  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-17 06:47:01.245  1019  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
,03-17 06:47:01.245  1019  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-17 06:47:01.245  5913  5913 D Compatibility: onReceive() it will make start service
,03-17 06:47:01.245  1019  3945 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:47:01.245  1019  3945 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-17 06:47:01.245  1019  3945 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,03-17 06:47:01.255  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:47:01.255  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:47:01.255  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:01.255  1019  1139 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:47:01.265  5913  6301 D Compatibility: onHandleIntent()
,03-17 06:47:01.265  5913  6301 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10167, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,03-17 06:47:01.265  5913  6301 D Compatibility: found: 2
,03-17 06:47:01.265  5913  6301 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
03-17 06:47:01.265  5913  6301 D Compatibility: skipping ResolveInfo{26fc235 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
03-17 06:47:01.265  5913  6301 D Compatibility: considering ResolveInfo{c006ca com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
03-17 06:47:01.265  5913  6301 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,03-17 06:47:01.265  5913  6301 D Compatibility: enabling receiver ResolveInfo{1e10a03b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
03-17 06:47:01.275  6302  6302 E Zygote  : MountEmulatedStorage()
03-17 06:47:01.275  6302  6302 E Zygote  : v2
03-17 06:47:01.275  6302  6302 I libpersona: KNOX_SDCARD checking this for 10055
03-17 06:47:01.275  6302  6302 I libpersona: KNOX_SDCARD not a persona
03-17 06:47:01.275  6302  6302 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:47:01.275  1019  1139 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6302 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,03-17 06:47:01.275  6302  6302 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:47:01.275  5913  6301 D Compatibility: enabling receiver ResolveInfo{6886358 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
03-17 06:47:01.275  6302  6302 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:47:01.285  5913  6301 D Compatibility: enabling receiver ResolveInfo{4674cb1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,03-17 06:47:01.285  5913  6301 D Compatibility: enabling receiver ResolveInfo{1b3fc596 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,03-17 06:47:01.295  5913  6301 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,03-17 06:47:01.295  6302  6302 D TimaKeyStoreProvider: TimaSignature is unavailable
03-17 06:47:01.295  6302  6302 D ActivityThread: Added TimaKeyStore provider
,03-17 06:47:01.315  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:47:01.315  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:01.315  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,03-17 06:47:01.335  6302  6302 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,03-17 06:47:01.365  6302  6302 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,03-17 06:47:01.365  6302  6302 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-17 06:47:01.365  6302  6302 D UserAnalysis: Create SecureDbHelper
,03-17 06:47:01.365  6302  6302 D IntelligenceServiceApplication: onCreate()
,03-17 06:47:01.365  6302  6302 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,03-17 06:47:01.375  5935  5935 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:47:01.375  1019  3944 W ActivityManager: userId = 0, bbcId = -10000
,03-17 06:47:01.375  1019  3944 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:01.375  1019  3944 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-17 06:47:01.375  6302  6302 D IntelligenceServiceApplication: no applications having user consent for prediction
,03-17 06:47:01.375  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 06:47:01.375  1019  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:47:01.375  1019  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:01.375  1019  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:01.375  1019  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:47:01.385  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 06:47:01.395  6319  6319 E Zygote  : MountEmulatedStorage(),
03-17 06:47:01.395  6319  6319 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:47:01.395  6319  6319 E Zygote  : v2
03-17 06:47:01.395  6319  6319 I libpersona: KNOX_SDCARD not a persona
,03-17 06:47:01.395  6319  6319 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,03-17 06:47:01.395  6319  6319 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:47:01.395  6319  6319 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:47:01.395  1019  1702 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6319 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,03-17 06:47:01.405  1019  1032 I ActivityManager: Killing 5229:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #31
,03-17 06:47:01.415  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
,03-17 06:47:01.415  6233  6233 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-17 06:47:01.415  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
,03-17 06:47:01.425  1019  1057 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-17 06:47:01.425  1019  1057 D PackageManager: userId{-1}
03-17 06:47:01.425  1019  1057 D PackageManager: andCode{true}
,03-17 06:47:01.435  6319  6319 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-17 06:47:01.435  6319  6319 D ActivityThread: Added TimaKeyStore provider
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
03-17 06:47:01.435  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
,03-17 06:47:01.445  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
,03-17 06:47:01.445   292   292 E SMD     : DCD OFF
,03-17 06:47:01.455  6302  6302 D BluetoothAdapter: cancelDiscovery
,03-17 06:47:01.455  2634  2650 D BluetoothAdapterProperties: mDiscovering is false
,03-17 06:47:01.455  2634  2650 E BluetoothAdapterService: This is not a scanning status. cancelDiscovery() will be not called.
03-17 06:47:01.455  6302  6302 D BluetoothAdapter: cancelDiscovery = true
,03-17 06:47:01.455  6302  6302 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
,03-17 06:47:01.455  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,03-17 06:47:01.455  6302  6302 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,03-17 06:47:01.455  6319  6319 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-17 06:47:01.525  6319  6319 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,03-17 06:47:01.535  1019  1043 W libprocessgroup: failed to open /acct/uid_10032/pid_5229/cgroup.procs: No such file or directory,
,03-17 06:47:01.545  1019  1032 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
,03-17 06:47:01.545  1019  1032 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
03-17 06:47:01.545  6302  6302 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
03-17 06:47:01.545  6302  6302 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: Error inserting timestamp=1458193621390 message=Predictor: service is stopped by Application.onCreate
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952),
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-17 06:47:01.545  6302  6302 E UserAnalysis: It failed to insert to dump_log table
03-17 06:47:01.545  6302  6302 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-17 06:47:01.545  6302  6302 E SQLiteLog: (3850) statement aborts at 17: [INSERT INTO dump_log(timestamp,message) VALUES (?,?)] disk I/O error
,03-17 06:47:01.545  6302  6302 E SQLiteDatabase: Error inserting timestamp=1458193621471 message=Predictor: service stopped by removePlaceCategories()
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-17 06:47:01.545  6302  6302 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-17 06:47:01.545  6302  6302 E UserAnalysis: It failed to insert to dump_log table
,03-17 06:47:01.555  5954  5954 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
,03-17 06:47:01.555  5954  5954 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,03-17 06:47:01.565  1019  1031 W ActivityManager: userId = 0, bbcId = -10000
03-17 06:47:01.565  1019  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-17 06:47:01.565  1019  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,03-17 06:47:01.565  5954  5954 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,03-17 06:47:01.575  5954  6336 I FilterInstaller: FilterPackageService : ACTION_REMOVED
,03-17 06:47:01.575  5954  6336 D FilterUnInstaller: before removeFromFS
,03-17 06:47:01.575  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:47:01.575  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:01.575  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:01.575  1019  1479 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:47:01.595  6337  6337 E Zygote  : MountEmulatedStorage(),
03-17 06:47:01.595  6337  6337 E Zygote  : v2
03-17 06:47:01.595  6337  6337 I libpersona: KNOX_SDCARD checking this for 10095
03-17 06:47:01.595  6337  6337 I libpersona: KNOX_SDCARD not a persona
,03-17 06:47:01.595  6337  6337 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,03-17 06:47:01.605  1019  1479 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6337 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
,03-17 06:47:01.605  6337  6337 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,03-17 06:47:01.605  6337  6337 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-17 06:47:01.605  1019  3945 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 06:47:01.605  1019  3945 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-17 06:47:01.605  1019  3945 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-17 06:47:01.605  1019  3945 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-17 06:47:01.625  6352  6352 E Zygote  : MountEmulatedStorage()
,03-17 06:47:01.625  6352  6352 E Zygote  : v2
03-17 06:47:01.625  6352  6352 I libpersona: KNOX_SDCARD checking this for 1000
03-17 06:47:01.625  6352  6352 I libpersona: KNOX_SDCARD not a persona
,03-17 06:47:01.625  6352  6352 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
03-17 06:47:01.625  1019  3945 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6352 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
03-17 06:47:01.625  6352  6352 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
03-17 06:47:01.635  6352  6352 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL

```
