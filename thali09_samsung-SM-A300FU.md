#### Test 757892682551a10_thali09_samsung-SM-A300FU Logs


```
--------- beginning of main
06-30 13:52:32.544   290   290 E SMD     : DCD OFF
,06-30 13:52:33.354  5859  5859 D AndroidRuntime: 
06-30 13:52:33.354  5859  5859 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 13:52:33.364  5859  5859 D AndroidRuntime: CheckJNI is OFF
06-30 13:52:33.364  5859  5859 D AndroidRuntime: readGMSProperty: start
06-30 13:52:33.364  5859  5859 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:52:33.364  5859  5859 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 13:52:33.364  5859  5859 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 13:52:33.364  5859  5859 D AndroidRuntime: readGMSProperty: end
06-30 13:52:33.364  5859  5859 D AndroidRuntime: addProductProperty: start
06-30 13:52:33.504  5859  5859 E AffinityControl: AffinityControl: registerfunction enter
06-30 13:52:33.524  5859  5859 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 13:52:33.534  1018  1529 E PersonaManagerService: inState():  stateMachine is null !!
06-30 13:52:33.534  1018  1529 I PersonaManagerService: PersonaId don't exist
06-30 13:52:33.534  1018  1529 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
06-30 13:52:33.544  1018  1529 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
06-30 13:52:33.554  1018  1529 W ActivityManager: mDVFSHelper.acquire()
06-30 13:52:33.554  1018  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
06-30 13:52:33.554  1018  1529 D FocusedStackFrame: Set to : 0
06-30 13:52:33.554  1018  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
06-30 13:52:33.564  1018  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:33.564  1018  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:33.564  1018  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:33.564  1018  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:33.574  1018  1529 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
06-30 13:52:33.574  1018  1529 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=5870 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 13:52:33.574  1018  1529 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-30 13:52:33.574  1018  1529 D InputDispatcher: Focused application set to: xxxx
06-30 13:52:33.574  1018  1529 D InputDispatcher: Focus left window: 1479
06-30 13:52:33.574  5859  5859 D AndroidRuntime: Shutting down VM
06-30 13:52:33.574  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
06-30 13:52:33.574  5870  5870 I libpersona: KNOX_SDCARD checking this for 10170
06-30 13:52:33.574  1018  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
06-30 13:52:33.574  5870  5870 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:33.574  5870  5870 E Zygote  : MountEmulatedStorage()
06-30 13:52:33.574  5870  5870 E Zygote  : v2
06-30 13:52:33.574   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, uhalitest
06-30 13:52:33.574  5870  5870 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:52:33.584  5870  5870 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:52:33.584  5870  5870 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
06-30 13:52:33.594  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 13:52:33.594  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:33.604  5870  5870 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:33.604  5870  5870 D ActivityThread: Added TimaKeyStore provider
06-30 13:52:33.604  1018  1870 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
06-30 13:52:33.614  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
06-30 13:52:33.624  1018  1870 D PersonaManager: isKioskContainerExistOnDevice
06-30 13:52:33.634  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
06-30 13:52:33.664   257  1163 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
06-30 13:52:33.664   257  1092 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
06-30 13:52:33.674  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{1aee3034 token=android.os.BinderProxy@1eaad080 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
06-30 13:52:33.674  1479  1479 D Launcher: onTrimMemory. Level: 20
06-30 13:52:33.744  5870  5870 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
06-30 13:52:33.754  5870  5870 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2963-2964)
06-30 13:52:33.754  5870  5870 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:33.774  1018  2689 D SSRM:n  : SIOP:: AP = 320
06-30 13:52:33.774  5870  5870 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3971844b}
06-30 13:52:33.774  5870  5870 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 13:52:33.774  5870  5870 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 13:52:33.784  5859  5859 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,06-30 13:52:33.814  5870  5870 I BrowserStartupController: Initializing chromium process, singleProcess=true
06-30 13:52:33.814  5870  5870 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:33.814  5870  5870 E SysUtils: ApplicationContext is null in ApplicationStatus
06-30 13:52:33.824  5870  5887 W chromium: [WARNING:dns_config_service_posix.cc(292)] Failed to read DnsConfig.
06-30 13:52:33.834  5870  5870 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
06-30 13:52:33.834  5870  5870 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
06-30 13:52:33.834  5870  5870 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
06-30 13:52:33.844  5870  5870 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
06-30 13:52:33.844  5870  5870 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
06-30 13:52:33.844  5870  5870 I Adreno-EGL: Build Date: 04/06/15 Mon
06-30 13:52:33.844  5870  5870 I Adreno-EGL: Local Branch: 
06-30 13:52:33.844  5870  5870 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
06-30 13:52:33.844  5870  5870 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
06-30 13:52:33.844  5870  5870 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
06-30 13:52:33.904  5870  5898 D BluetoothAdapter: 921847421: getState() :  mService = null. Returning STATE_OFF
06-30 13:52:33.954  5870  5896 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
06-30 13:52:34.004  5870  5870 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:34.014  5870  5870 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 13:52:34.024  5870  5870 D PhoneWindow: *FMB* installDecor mIsFloating : false
06-30 13:52:34.024  5870  5870 D PhoneWindow: *FMB* installDecor flags : -2139027200
06-30 13:52:34.034  5870  5870 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
06-30 13:52:34.034  5870  5870 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:34.034  5870  5870 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 13:52:34.084  5870  5909 D OpenGLRenderer: Render dirty regions requested: true
06-30 13:52:34.084  1018  1470 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
06-30 13:52:34.084  1018  1470 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 13:52:34.084  1018  1470 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-30 13:52:34.084  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-30 13:52:34.084  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
06-30 13:52:34.104  5870  5870 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
06-30 13:52:34.104  5870  5870 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
06-30 13:52:34.104   257   257 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
06-30 13:52:34.124  1018  1875 D InputDispatcher: Focus entered window: 5870
06-30 13:52:34.124  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 13:52:34.124  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
06-30 13:52:34.124  5870  5870 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
06-30 13:52:34.124  5870  5909 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 13:52:34.134  5870  5909 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
06-30 13:52:34.134  5870  5909 D OpenGLRenderer: Enabling debug mode 0
06-30 13:52:34.144  5870  5870 V ActivityThread: updateVisibility : ActivityRecord{3f7d11b3 token=android.os.BinderProxy@3406c8ed {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
06-30 13:52:34.194  1018  1882 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
06-30 13:52:34.204  1178  1178 I StatusBar: Icon Only
06-30 13:52:34.204  1178  1178 D PanelView: There is/are notification(s) 
06-30 13:52:34.204  1018  5912 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
06-30 13:52:34.204  5870  5870 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3406c8ed time:123418
06-30 13:52:34.214  5870  5870 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-30 13:52:34.214  1018  1048 I ActivityManager: Displayed Component not be shown by security: +589ms (total +14s666ms)
06-30 13:52:34.214  1018  1048 W ActivityManager: mDVFSHelper.release()
06-30 13:52:34.214  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2c8ecefb u0 com.test.thalitest/.MainActivity t44} time:123429
06-30 13:52:34.224   257   456 I SurfaceFlinger: id=11 Removed uhalitest (7/9)
06-30 13:52:34.224   257  1092 I SurfaceFlinger: id=11 Removed uhalitest (-2/9)
06-30 13:52:34.244  1836  1836 I SamsungIME: getCurrentCandidateView
06-30 13:52:34.304  5870  5870 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5870
06-30 13:52:34.334  1836  1836 D SamsungIME: Dismiss ExpandCandiate
06-30 13:52:34.424  5870  5870 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 13:52:34.484  1836  1836 I SamsungIME: getDebugLevel  : 0x4f4c
06-30 13:52:34.524  1836  1836 I SamsungIME: getDebugLevel  : 0x4f4c
06-30 13:52:34.534  1836  1836 I SamsungIME: KeybaordView init() : load resources
,06-30 13:52:34.534  5870  5914 D jxcore_app_log: JniHelper::setJavaVM(0xb76962f0), pthread_self() = -1212423184
,06-30 13:52:34.554   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:52:34.554  5870  5914 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 13:52:34.554  5870  5914 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 13:52:34.554  5870  5914 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 13:52:34.554  5870  5914 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 13:52:34.554  5870  5914 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 13:52:34.554  5870  5914 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38edcda3 added. We now have 1 listener(s)
,06-30 13:52:34.554  5870  5914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,06-30 13:52:34.554  5870  5914 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,06-30 13:52:34.554  5870  5914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,06-30 13:52:34.554  5870  5914 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,06-30 13:52:34.564  1836  1836 I SamsungIME: getCurrentKeyboard
06-30 13:52:34.564  1836  1836 I SamsungIME: getTextKeyboard
,06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 13:52:34.564  5870  5914 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c1401e added. We now have 1 listener(s)
,06-30 13:52:34.564  5870  5914 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,06-30 13:52:34.564  5870  5914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
,06-30 13:52:34.574  5870  5914 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: isBleMultipleAdvertisementSupported: Bluetooth is not enabled so we could not check whether or not BluetoothLE multi advertisement is supported. However, Bluetooth LE is supported so we just *assume* multi advertisement is supported too (which may not always be the case).
,06-30 13:52:34.574  5870  5914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
06-30 13:52:34.574  5870  5914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,06-30 13:52:34.574  5870  5914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
06-30 13:52:34.574  5870  5914 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,06-30 13:52:34.574  5870  5914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 13:52:34.574  5870  5914 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,06-30 13:52:34.574  5870  5914 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Cannot do the check when the Bluetooth is disabled - will return "not resolved"
06-30 13:52:34.574  5870  5914 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 13:52:34.574  5870  5914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 13:52:34.574  5870  5914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
06-30 13:52:34.574  5870  5914 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
06-30 13:52:34.574  5870  5914 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
06-30 13:52:34.574  5870  5914 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 13:52:34.574  5870  5914 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 13:52:34.574  5870  5914 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 13:52:34.574  5870  5914 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 13:52:34.574  5870  5914 D io.jxcore.node.ConnectivityMonitor: start: OK
,06-30 13:52:34.584  5870  5914 I io.jxcore.node.LifeCycleMonitor: start: OK
,06-30 13:52:34.584  1836  1836 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,06-30 13:52:34.614  5870  5870 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 13:52:35.094  5870  5919 W jxcore-log: Initializing JXcore engine
06-30 13:52:35.094  5870  5919 W jxcore-log: JXcore engine is ready
,06-30 13:52:35.154  1920  1920 E audit   : type=1400 msg=audit(1467287555.144:203): avc:  denied  { ioctl } for  pid=5919 comm="Thread-1053" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,06-30 13:52:35.154  1920  1920 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:52:35.154  1920  1920 E audit   : type=1300 msg=audit(1467287555.144:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9ec008f8 items=0 ppid=306 ppcomm=main pid=5919 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1053" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
06-30 13:52:35.154  1920  1920 E audit   : type=1320 msg=audit(1467287555.144:203): 
,06-30 13:52:35.164  5870  5919 W jxcore-log: Starting JXcore engine
,06-30 13:52:35.264  5870  5919 W jxcore-log: Platform android
06-30 13:52:35.264  5870  5919 W jxcore-log: 
06-30 13:52:35.264  5870  5919 W jxcore-log: Process ARCH arm
06-30 13:52:35.264  5870  5919 W jxcore-log: 
,06-30 13:52:35.464  5870  5919 I jxcore-log: JXcore Cordova bridge is ready!
06-30 13:52:35.464  5870  5919 I jxcore-log: 
,06-30 13:52:35.464  5870  5919 W jxcore-log: JXcore engine is started
,06-30 13:52:35.474  5870  5914 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 13:52:35.474  5870  5870 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41),
,06-30 13:52:35.484  5870  5919 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
06-30 13:52:35.484  5870  5919 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,06-30 13:52:35.494  5870  5870 I chromium: [INFO:CONSOLE(57)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
,06-30 13:52:35.494  5870  5870 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,06-30 13:52:35.494  1018  1141 D FocusedStackFrame: Set to : 0
06-30 13:52:35.494  1018  1141 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
06-30 13:52:35.494  1018  1141 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
06-30 13:52:35.494  1018  1141 D InputDispatcher: Focused application set to: xxxx
06-30 13:52:35.494  1018  1141 D InputDispatcher: Focus left window: 5870
06-30 13:52:35.504  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 13:52:35.504  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-30 13:52:35.504  1018  1141 I ActivityManager: Killing 5505:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,06-30 13:52:35.504  5870  5870 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
06-30 13:52:35.504  5870  5870 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
06-30 13:52:35.504  5870  5870 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
06-30 13:52:35.504  5870  5870 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
06-30 13:52:35.504  5870  5870 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
06-30 13:52:35.504  5870  5870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
06-30 13:52:35.504  5870  5870 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38edcda3 removed from the list
06-30 13:52:35.504  5870  5870 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
06-30 13:52:35.504  5870  5870 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c1401e removed from the list
06-30 13:52:35.504  5870  5870 D io.jxcore.node.ConnectivityMonitor: stop
06-30 13:52:35.504  5870  5870 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
06-30 13:52:35.504  5870  5870 I io.jxcore.node.LifeCycleMonitor: stop: OK
,06-30 13:52:35.524   257  1163 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
06-30 13:52:35.524   257  1092 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,06-30 13:52:35.534  1018  1882 W ActivityManager: mDVFSHelper.acquire()
,06-30 13:52:35.534  1018  1882 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,06-30 13:52:35.544   290   290 E SMD     : DCD OFF
,06-30 13:52:35.554   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:52:35.564  1479  1479 D Launcher: onRestart, Launcher: 189930023
,06-30 13:52:35.564  1479  1479 D Launcher: onStart, Launcher: 189930023
,06-30 13:52:35.564  1479  1479 D Launcher.HomeView: onStart
,06-30 13:52:35.564  1479  1479 D Launcher: onResume, Launcher: 189930023
,06-30 13:52:35.564  1018  1478 D SettingsProvider: name = kids_home_mode
,06-30 13:52:35.564  1018  1478 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
06-30 13:52:35.564  1018  1478 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
06-30 13:52:35.564  1018  1478 D SettingsProvider: selectionArgs: false
06-30 13:52:35.564  1018  1478 D SettingsProvider: selectionArgs: 10006
,06-30 13:52:35.564  1018  1478 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,06-30 13:52:35.564  1018  1478 D SettingsProvider: ret = -1
,06-30 13:52:35.564  1479  1479 D Launcher.HomeView: onResume
,06-30 13:52:35.574  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
06-30 13:52:35.574  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:35.574  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:35.574  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
06-30 13:52:35.584  1479  1479 D MenuAppsGridFragment: onResume
06-30 13:52:35.584  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
06-30 13:52:35.584  1479  1479 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,06-30 13:52:35.584  1018  1477 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
06-30 13:52:35.584  1018  1477 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,06-30 13:52:35.584  1018  1477 W ActivityManager: userId = 0, bbcId = -10000
,06-30 13:52:35.584  1018  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:35.584  1018  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,06-30 13:52:35.584  1018  1477 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
06-30 13:52:35.584  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.584  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.584  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.584  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:35.604  5924  5924 E Zygote  : MountEmulatedStorage()
06-30 13:52:35.604  5924  5924 I libpersona: KNOX_SDCARD checking this for 10039
06-30 13:52:35.604  5924  5924 E Zygote  : v2
06-30 13:52:35.604  5924  5924 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:35.604  5924  5924 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:35.604  5924  5924 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 13:52:35.604  5924  5924 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:52:35.614  1018  1477 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=5924 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,06-30 13:52:35.614  1018  1882 D ActivityManager: handle home activity for 0
,06-30 13:52:35.614  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
06-30 13:52:35.614  1018  1882 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
06-30 13:52:35.614  1018  1882 D KnoxTimeoutHandler: post home show event for user 0
06-30 13:52:35.614  1018  1882 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
06-30 13:52:35.614  1018  1882 D KnoxTimeoutHandler: postActiveUserChange for user 0
06-30 13:52:35.614  1018  1882 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
06-30 13:52:35.614  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
06-30 13:52:35.614  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,06-30 13:52:35.614  1479  1479 D Launcher.HomeView: onPause
06-30 13:52:35.614  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
06-30 13:52:35.614  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
06-30 13:52:35.614  1479  1479 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
06-30 13:52:35.614  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:35.614  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:35.614  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
06-30 13:52:35.614  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:35.614  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:35.614  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,06-30 13:52:35.624  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.624  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.624  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.624  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:35.644  5940  5940 E Zygote  : MountEmulatedStorage()
06-30 13:52:35.644  5940  5940 E Zygote  : v2
06-30 13:52:35.644  5940  5940 I libpersona: KNOX_SDCARD checking this for 10089
06-30 13:52:35.644  5940  5940 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:35.644  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=5940 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,06-30 13:52:35.644  5940  5940 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:35.644  5924  5924 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:35.644  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:35.644  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:35.644  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
06-30 13:52:35.644  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
06-30 13:52:35.644  5924  5924 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:35.644  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.644  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.644  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.644  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:35.644  5940  5940 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 13:52:35.644  5940  5940 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,06-30 13:52:35.664  5953  5953 E Zygote  : MountEmulatedStorage(),
06-30 13:52:35.664  5953  5953 I libpersona: KNOX_SDCARD checking this for 10139
06-30 13:52:35.664  5953  5953 E Zygote  : v2
06-30 13:52:35.664  5953  5953 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:35.664  5953  5953 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:35.664  5953  5953 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 13:52:35.664  5953  5953 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
06-30 13:52:35.674  5940  5940 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:35.674  5940  5940 D ActivityThread: Added TimaKeyStore provider
06-30 13:52:35.674  1018  1043 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=5953 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a,
,06-30 13:52:35.684  5940  5940 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 13:52:35.684  5940  5940 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,06-30 13:52:35.694  5953  5953 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:35.694  5953  5953 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:35.694  1018  1529 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:35.694  1018  1529 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1479, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
06-30 13:52:35.694  1018  1529 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:35.694  1018  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,06-30 13:52:35.704  1018  1043 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:35.704  1018  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:35.704  1018  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,06-30 13:52:35.704  2516  2516 D Recents_RecreateReceiver: onReceive by home
,06-30 13:52:35.704   257   257 I SurfaceFlinger: id=13 createSurf (540x960),1 flag=4, Mauncher
,06-30 13:52:35.714  1018  1529 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:35.714  1018  1529 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
06-30 13:52:35.714  1018  1529 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:35.714  1018  1529 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,06-30 13:52:35.714  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,06-30 13:52:35.714  1018  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.714  1018  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.714  1018  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.714  1018  1529 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.714  1018  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,06-30 13:52:35.724  5924  5924 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 13:52:35.724  5924  5924 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:52:35.724  5924  5924 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
06-30 13:52:35.724  5924  5924 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
06-30 13:52:35.724  5924  5924 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
06-30 13:52:35.724  5924  5924 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
06-30 13:52:35.724  5924  5924 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 13:52:35.724  1018  1415 D InputDispatcher: Focus entered window: 1479
,06-30 13:52:35.724  1018  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
06-30 13:52:35.724  1018  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,06-30 13:52:35.734  1479  1479 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,06-30 13:52:35.734  5970  5970 E Zygote  : MountEmulatedStorage()
06-30 13:52:35.734  5970  5970 E Zygote  : v2
06-30 13:52:35.734  5970  5970 I libpersona: KNOX_SDCARD checking this for 10084
06-30 13:52:35.734  5970  5970 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:35.734  5970  5970 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:35.734  5970  5970 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:52:35.734  5970  5970 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,06-30 13:52:35.744  1018  1529 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=5970 uid=10084 gids={50084, 9997} abi=armeabi-v7a
06-30 13:52:35.744  1479  1479 D Launcher.HomeView: onStop
06-30 13:52:35.744  1479  1479 V ActivityThread: updateVisibility : ActivityRecord{1aee3034 token=android.os.BinderProxy@1eaad080 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,06-30 13:52:35.744  1018  1882 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,06-30 13:52:35.754  1018  5984 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,06-30 13:52:35.764  1178  1178 I StatusBar: Icon Only
06-30 13:52:35.764  1178  1178 D PanelView: There is/are notification(s) 
,06-30 13:52:35.764  5970  5970 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:35.764  1018  1877 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:35.764  1018  1877 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:35.764  1018  1877 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
06-30 13:52:35.764  1018  1877 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,06-30 13:52:35.764  1018  1877 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.764  1018  1877 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.764  1018  1877 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:35.764  1018  1877 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:35.774  5970  5970 D ActivityThread: Added TimaKeyStore provider
06-30 13:52:35.774  5870  5870 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
06-30 13:52:35.774   306   306 I art     : Explicit concurrent mark sweep GC freed 8683(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 611us total 32.401ms
,06-30 13:52:35.774  5920  5920 D AndroidRuntime: 
06-30 13:52:35.774  5920  5920 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,06-30 13:52:35.784  5920  5920 D AndroidRuntime: CheckJNI is OFF,
06-30 13:52:35.784  5920  5920 D AndroidRuntime: readGMSProperty: start
06-30 13:52:35.784  5953  5953 V TaskCloserActivity: TaskCloserActivity enter()
06-30 13:52:35.784  5920  5920 D AndroidRuntime: readGMSProperty: already setted!!
06-30 13:52:35.784  5920  5920 D AndroidRuntime: propertySet: couldn't set property (it is from app)
06-30 13:52:35.784  5920  5920 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
06-30 13:52:35.784  5920  5920 D AndroidRuntime: readGMSProperty: end
06-30 13:52:35.784  5920  5920 D AndroidRuntime: addProductProperty: start
,06-30 13:52:35.794  1836  1836 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,06-30 13:52:35.794   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 18.484ms
,06-30 13:52:35.794  1479  1479 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1eaad080 time:125005
,06-30 13:52:35.804  5953  5953 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,06-30 13:52:35.814   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 649us total 17.203ms
,06-30 13:52:35.824  5990  5990 E Zygote  : MountEmulatedStorage()
,06-30 13:52:35.824  5990  5990 E Zygote  : v2
06-30 13:52:35.824  5990  5990 I libpersona: KNOX_SDCARD checking this for 10135
06-30 13:52:35.824  5990  5990 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:35.824  1018  1877 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=5990 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
06-30 13:52:35.824  5990  5990 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:52:35.824  1018  1877 I ActivityManager: Killing 5526:com.sec.spp.push/u0a32 (adj 15): empty #21
,06-30 13:52:35.824  5990  5990 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 13:52:35.834  5990  5990 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:52:35.834  1018  1877 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:35.834  1018  1877 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:35.834  1018  1877 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,06-30 13:52:35.834  1018  1877 I ActivityManager: Killing 5546:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,06-30 13:52:35.844  1018  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1505f6eb u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t42} time:125056
06-30 13:52:35.844  1018  1048 W ActivityManager: mDVFSHelper.release()
,06-30 13:52:35.844  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,06-30 13:52:35.854  5970  5970 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 13:52:35.874  1018  1477 I ActivityManager: Killing 5596:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,06-30 13:52:35.874  5990  5990 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:52:35.874  5990  5990 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:35.894  5990  5990 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
06-30 13:52:35.894  5990  5990 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 13:52:35.894  5990  5990 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
06-30 13:52:35.894  5990  5990 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
06-30 13:52:35.894  5990  5990 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,06-30 13:52:35.914  5920  5920 E AffinityControl: AffinityControl: registerfunction enter
,06-30 13:52:35.924  1018  1031 D PersonaManager: isKioskContainerExistOnDevice
,06-30 13:52:35.944  5920  5920 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,06-30 13:52:35.944  1018  1494 I ActivityManager: Killing 5554:com.osp.app.signin/u0a36 (adj 15): empty #21
,06-30 13:52:35.954  5924  5924 D NearbySource: Nearby Source Create!
,06-30 13:52:35.954  5924  5924 D NearbyContext: Nearby Context Create!
06-30 13:52:35.954  1018  1415 D PackageManager: START PACKAGE DELETE: observer{584743834}
06-30 13:52:35.954  1018  1415 D PackageManager: pkg{<packageName>}
06-30 13:52:35.954  1018  1415 D PackageManager: user{0}
06-30 13:52:35.954  1018  1415 D PackageManager: caller{2000}
06-30 13:52:35.954  1018  1415 D PackageManager: flags{2}
06-30 13:52:35.954  1018  1415 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
06-30 13:52:35.954  1018  1415 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
06-30 13:52:35.954  1018  1415 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
06-30 13:52:35.954  1018  1415 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
06-30 13:52:35.954  1018  1415 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,06-30 13:52:35.954  1018  1058 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
06-30 13:52:35.954  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
06-30 13:52:35.954  1018  1058 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
06-30 13:52:35.954  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled
06-30 13:52:35.954  1018  1058 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,06-30 13:52:35.964  1018  1058 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,06-30 13:52:35.964  1018  1043 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,06-30 13:52:35.964  1018  1043 I ActivityManager: Killing 5870:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,06-30 13:52:35.994   256   523 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
06-30 13:52:35.994   256   523 W Vold    : Returning OperationFailed - no handler for errno 0
,06-30 13:52:35.994  5924  5924 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
06-30 13:52:35.994  5924  5924 D SLinkSource: Samsung link source created
,06-30 13:52:36.054  1018  1058 W PackageSettings: Skipping PackageSetting{1e03a3a6 com.example.hello/10168} due to missing metadata
,06-30 13:52:36.084  1018  1470 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 13:52:36.094  1018  1494 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,06-30 13:52:36.104  5924  6015 D ContactProvider: getAllContactInfoList Start
,06-30 13:52:36.104  5924  5924 D GalleryCacheReady: Receive : home resume
,06-30 13:52:36.104  1018  1877 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.104  1018  1877 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:36.104  1018  1877 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,06-30 13:52:36.114  1018  1058 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,06-30 13:52:36.114  5440  5440 D Mms/UIEventReceiver: ui event
,06-30 13:52:36.114  1018  1058 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,06-30 13:52:36.164  5577  5577 I art     : Explicit concurrent mark sweep GC freed 18903(1022KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 873us total 39.547ms
,06-30 13:52:36.174  5732  5732 I art     : Explicit concurrent mark sweep GC freed 603(35KB) AllocSpace objects, 0(0B) LOS objects, 26% free, 5MB/7MB, paused 845us total 33.323ms
,06-30 13:52:36.184  1018  1100 I InputReader: Reconfiguring input devices.  changes=0x00000010
,06-30 13:52:36.184  1836  1836 E SamsungIME: mOCRHelper is null
,06-30 13:52:36.194  1762  2045 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,06-30 13:52:36.194  3911  3911 I art     : Explicit concurrent mark sweep GC freed 1223(54KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 11MB/15MB, paused 1.134ms total 72.570ms
,06-30 13:52:36.204  1018  1042 D EnterpriseDeviceManagerService: Package has changed for user 0
,06-30 13:52:36.204  1018  1042 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
06-30 13:52:36.204  1018  1042 W TextServicesManagerService: no available spell checker services found
,06-30 13:52:36.214  1018  1478 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,06-30 13:52:36.214  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.214  1018  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:36.214  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,06-30 13:52:36.224  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.224  5953  5953 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,06-30 13:52:36.234  1443  1443 D PersonaManager: isKioskContainerExistOnDevice,
06-30 13:52:36.234  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.254  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.254  1443  1443 D RegisteredServicesCache: empty dynamic service
,06-30 13:52:36.254  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.264  1018  1124 V NetworkStats: removeUidsLocked() for UIDs [10170]
06-30 13:52:36.264  1018  1124 V NetworkStats: performPollLocked(flags=0x3)
06-30 13:52:36.264  3670  3670 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Thu Jun 30 13:52:36 GMT+02:00 2016
06-30 13:52:36.274  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox updated
06-30 13:52:36.274  1018  1124 D NetworkStatsFactory: UpdateStatsForKnox main else ---
06-30 13:52:36.274  1018  1124 V NetworkStats: performPollLocked() took 12ms
06-30 13:52:36.284  1018  1478 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
06-30 13:52:36.284  1018  1478 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
06-30 13:52:36.284  1018  1478 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.284  1018  1478 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:36.284  1018  1478 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,06-30 13:52:36.304  1018  1125 D NtpTrustedTime: forceRefresh() from cache miss
06-30 13:52:36.304  3670  3670 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,06-30 13:52:36.314   280   944 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 13:52:36.314   280   944 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,06-30 13:52:36.314  1018  1477 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=23, mSplitNum[2]=33, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=43
06-30 13:52:36.314  1018  1477 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,06-30 13:52:36.314  1018  1477 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,06-30 13:52:36.314   280   944 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
06-30 13:52:36.314  1443  1443 D RegisteredComponentCache: Collect Tech packages for Knox
06-30 13:52:36.314   280   944 D Netd    : getNetworkForDns: using netid 0 for uid 1000
,06-30 13:52:36.314  1018  1125 D NtpTrustedTime: forceRefresh Fail.
,06-30 13:52:36.314  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.314  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.314  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.314  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.324  6019  6019 E Zygote  : MountEmulatedStorage()
,06-30 13:52:36.324  6019  6019 E Zygote  : v2
06-30 13:52:36.324  6019  6019 I libpersona: KNOX_SDCARD checking this for 10090
06-30 13:52:36.324  6019  6019 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:36.324  1018  1477 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6019 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a,
,06-30 13:52:36.334  6019  6019 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:36.334  1443  1443 D PersonaManager: isKioskContainerExistOnDevice
,06-30 13:52:36.334  6019  6019 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 13:52:36.334  6019  6019 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:52:36.344  1018  1877 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
06-30 13:52:36.344  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
06-30 13:52:36.344  1018  1877 D SecContentProvider2: mCursor = null
,06-30 13:52:36.344  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.344  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.344  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.344  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.354  5440  5440 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,06-30 13:52:36.354  1018  1018 I art     : Explicit concurrent mark sweep GC freed 41341(2MB) AllocSpace objects, 16(256KB) LOS objects, 33% free, 23MB/35MB, paused 4.940ms total 232.212ms
,06-30 13:52:36.354  1018  1058 I art     : WaitForGcToComplete blocked for 113.067ms for cause Explicit
,06-30 13:52:36.364  3670  3670 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,06-30 13:52:36.364  6032  6032 E Zygote  : MountEmulatedStorage()
06-30 13:52:36.364  6032  6032 E Zygote  : v2
06-30 13:52:36.364  6032  6032 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:52:36.364  6032  6032 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:36.364  6032  6032 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:36.374  6032  6032 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 13:52:36.374  6032  6032 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:52:36.374  1018  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
06-30 13:52:36.374  1018  1043 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=6032 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 13:52:36.384  1018  1043 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,06-30 13:52:36.384  3670  3670 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,06-30 13:52:36.384  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.384  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.384  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.384  1018  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.384  6019  6019 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:36.384  6019  6019 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:36.394  3670  3670 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,06-30 13:52:36.404  6047  6047 E Zygote  : MountEmulatedStorage()
,06-30 13:52:36.404  6047  6047 E Zygote  : v2
06-30 13:52:36.404  6047  6047 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:52:36.404  6047  6047 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:36.404  6047  6047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
06-30 13:52:36.404  1018  1043 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=6047 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 13:52:36.404  1018  1882 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
06-30 13:52:36.404  1018  1882 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
06-30 13:52:36.404  6047  6047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:52:36.404  6047  6047 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:52:36.414  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.414  1018  1882 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.414  1018  1882 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:36.414  1018  1882 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,06-30 13:52:36.414  6032  6032 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:36.414  6032  6032 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:36.414  3670  6026 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,06-30 13:52:36.424  3670  6026 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,06-30 13:52:36.424  5440  6057 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
06-30 13:52:36.424  5440  6057 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,06-30 13:52:36.434  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,06-30 13:52:36.434  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,06-30 13:52:36.434  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
06-30 13:52:36.434  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
06-30 13:52:36.434  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,06-30 13:52:36.434  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.444  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,06-30 13:52:36.444  3670  6026 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,06-30 13:52:36.444  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,06-30 13:52:36.444  6047  6047 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:52:36.444  6047  6047 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:36.454  1018  1477 I TactileAssist: enable value -1
,06-30 13:52:36.454  5924  6015 D ContactProvider: getAllContactInfoList End
06-30 13:52:36.454  1018  1477 I TactileAssist: internal enable value -1
06-30 13:52:36.454  1018  1477 I TactileAssist: intensity value -1
06-30 13:52:36.454  1018  1477 I TactileAssist: saveAppList value true
,06-30 13:52:36.454  3670  6026 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,06-30 13:52:36.454  5924  6015 I syncContacts: thread: 1038, sync time = 428
,06-30 13:52:36.474  1018  1477 I TactileAssist: List of disabled apps :
,06-30 13:52:36.484  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.494  5716  5716 D Compatibility: onReceive() it will make start service
,06-30 13:52:36.494  1018  1477 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
06-30 13:52:36.494  1018  1477 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,06-30 13:52:36.494  1018  1477 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.494  1018  1477 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:36.494  1018  1477 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,06-30 13:52:36.514  5716  6066 D Compatibility: onHandleIntent()
,06-30 13:52:36.514  6047  6047 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
06-30 13:52:36.514  5716  6066 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10170, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,06-30 13:52:36.524  1018  1877 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
06-30 13:52:36.524  1018  1877 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,06-30 13:52:36.524  1018  1877 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.524  1018  1877 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:52:36.524  1018  1877 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
06-30 13:52:36.524  6032  6032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,06-30 13:52:36.524  6019  6019 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,06-30 13:52:36.524  6019  6019 D elm:15121: ELMEngine.ELMEngine( context ).
,06-30 13:52:36.524  1018  1478 D SecContentProvider2: uri = -1 selection = getSealedState
06-30 13:52:36.524  1018  1478 D SecContentProvider2: mCursor = null
,06-30 13:52:36.524  6019  6019 D elm:15121: MDMBridge.setEnterpriseBridge()
,06-30 13:52:36.534  6047  6047 I PopupuiReceiver_KNOX: getSealedState : true
06-30 13:52:36.534  1018  1470 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
06-30 13:52:36.534  1018  1470 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,06-30 13:52:36.534  1018  1415 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
06-30 13:52:36.534  1018  1415 D SecContentProvider2: mCursor = null
,06-30 13:52:36.534  1018  1470 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.534  1018  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:36.534  1018  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,06-30 13:52:36.534  1018  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
06-30 13:52:36.534  1018  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
06-30 13:52:36.534  1018  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 13:52:36.534  6047  6047 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
06-30 13:52:36.534  1018  1478 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
06-30 13:52:36.534  1018  1478 D SecContentProvider2: mCursor = null
,06-30 13:52:36.534  6047  6047 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
06-30 13:52:36.534  6047  6047 D PopupuiReceiver: Action package removed
,06-30 13:52:36.534  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.534  1018  1877 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
06-30 13:52:36.534  1018  1877 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,06-30 13:52:36.544  1018  1877 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.544  1018  1877 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:36.544  1018  1877 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,06-30 13:52:36.544  5716  6066 D Compatibility: found: 2
06-30 13:52:36.544  5716  6066 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
06-30 13:52:36.544  5716  6066 D Compatibility: skipping ResolveInfo{3a0cc4e6 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
06-30 13:52:36.544  5716  6066 D Compatibility: considering ResolveInfo{b521a27 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
06-30 13:52:36.544  5716  6066 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,06-30 13:52:36.544  1018  1870 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
06-30 13:52:36.544  5716  6066 D Compatibility: enabling receiver ResolveInfo{371734d4 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,06-30 13:52:36.544  1018  1870 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.544  1018  1870 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.544  1018  1870 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.544  1018  1870 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.554  5716  6066 D Compatibility: enabling receiver ResolveInfo{36f2467d com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,06-30 13:52:36.554   315   315 I ServiceManager: Waiting for service AtCmdFwd...
,06-30 13:52:36.554  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,06-30 13:52:36.554  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
06-30 13:52:36.554  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
06-30 13:52:36.554  1018  1018 V EnterpriseBillingPolicy: uID is 10170
06-30 13:52:36.554  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
06-30 13:52:36.554  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,06-30 13:52:36.554  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-30 13:52:36.554  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-30 13:52:36.554  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-30 13:52:36.554  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,06-30 13:52:36.554  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,06-30 13:52:36.564  6019  6019 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,06-30 13:52:36.564  6070  6070 E Zygote  : MountEmulatedStorage(),
,06-30 13:52:36.564  6070  6070 E Zygote  : v2,
06-30 13:52:36.564  6070  6070 I libpersona: KNOX_SDCARD checking this for 10145
,06-30 13:52:36.564  6070  6070 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:36.574  5732  6067 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
06-30 13:52:36.574  1018  1870 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=6070 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
06-30 13:52:36.574  6070  6070 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:52:36.574  6019  6019 D elm:15121: ElmAgentService : onCreate()
06-30 13:52:36.574  6019  6069 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
06-30 13:52:36.574  6019  6069 D elm:15121: MainReceiver.listeningToPackageRemoved()
06-30 13:52:36.574  6019  6069 D elm:15121: MDMBridge.getInstance()
06-30 13:52:36.574  6019  6069 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
06-30 13:52:36.574  6070  6070 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 13:52:36.574  6070  6070 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:52:36.604  6070  6070 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:52:36.604  6070  6070 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:36.604  6019  6069 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,06-30 13:52:36.604  3670  6026 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,06-30 13:52:36.614  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,06-30 13:52:36.614  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
06-30 13:52:36.614  1018  1018 V EnterpriseBillingPolicy: uID is 10170
06-30 13:52:36.614  5716  6066 D Compatibility: enabling receiver ResolveInfo{38504972 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,06-30 13:52:36.614  1018  2689 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,06-30 13:52:36.624  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
,06-30 13:52:36.624  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,06-30 13:52:36.624  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
06-30 13:52:36.624  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
06-30 13:52:36.624  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
06-30 13:52:36.624  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,06-30 13:52:36.624  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,06-30 13:52:36.624  3670  6026 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,06-30 13:52:36.624  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,06-30 13:52:36.624  5716  6066 D Compatibility: enabling receiver ResolveInfo{30bc31c3 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,06-30 13:52:36.634  1018  1141 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,06-30 13:52:36.634  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.634  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.634  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.634  1018  1141 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.644  3670  6026 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
,06-30 13:52:36.644  5716  6066 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,06-30 13:52:36.644  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.654  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.654  1018  1058 I art     : Explicit concurrent mark sweep GC freed 16402(1124KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 24.136ms total 287.501ms
,06-30 13:52:36.654  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:52:36.654  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 13:52:36.654  6086  6086 E Zygote  : MountEmulatedStorage()
06-30 13:52:36.654  6086  6086 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:52:36.654  6086  6086 E Zygote  : v2
06-30 13:52:36.654  6086  6086 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:36.654  6086  6086 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:36.654  6086  6086 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:52:36.654  1018  1141 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=6086 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 13:52:36.664  6086  6086 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:52:36.664  3334  3334 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,06-30 13:52:36.664  3334  3334 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
06-30 13:52:36.664  3334  3334 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:332)
06-30 13:52:36.664  3334  3334 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
06-30 13:52:36.664  3334  3334 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
06-30 13:52:36.664  3334  3334 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
06-30 13:52:36.664  3334  3334 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
06-30 13:52:36.664  3334  3334 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
06-30 13:52:36.664  3334  3334 W System.err: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:52:36.664  3334  3334 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 13:52:36.664  3334  3334 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:52:36.664  3334  3334 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:52:36.664  3334  3334 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 13:52:36.664  3334  3334 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 13:52:36.664  6019  6019 D elm:15121: ElmAgentService : onDestroy().
,06-30 13:52:36.674  3670  3670 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,06-30 13:52:36.674  1018  1478 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,06-30 13:52:36.674  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.674  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.674  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.674  1018  1478 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.684  6086  6086 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:52:36.684  6086  6086 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:36.694  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.694  6102  6102 E Zygote  : MountEmulatedStorage()
06-30 13:52:36.694  6102  6102 I libpersona: KNOX_SDCARD checking this for 10055
06-30 13:52:36.694  6102  6102 E Zygote  : v2
06-30 13:52:36.694  6102  6102 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:36.694  6102  6102 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:36.694  6102  6102 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 13:52:36.694  6102  6102 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:52:36.694  1018  1478 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=6102 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
06-30 13:52:36.694  1018  1141 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 13:52:36.704  1018  1141 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.704  1018  1141 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:52:36.704  1018  1141 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,06-30 13:52:36.704  1018  1058 D PackageManager: delete codoeFile: 
,06-30 13:52:36.704  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,06-30 13:52:36.714  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 13:52:36.714  1018  1058 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
,06-30 13:52:36.714  6070  6070 D ThemeInfoUtil: getCurrentFestivalName is [null]
06-30 13:52:36.714  6070  6070 D ThemeInfoUtil: isCurrentFestival = false
,06-30 13:52:36.714  1018  1058 I AASA_removePackage: UID=10170 Target=com.test.thalitest
,06-30 13:52:36.724  6102  6102 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:52:36.724  6102  6102 D ActivityThread: Added TimaKeyStore provider
06-30 13:52:36.724  1018  1058 D PackageManager: result of delete: 1{584743834}
,06-30 13:52:36.724  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:52:36.724  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,06-30 13:52:36.724  5920  5920 D AndroidRuntime: Shutting down VM
,06-30 13:52:36.724  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,06-30 13:52:36.734  1018  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
06-30 13:52:36.734  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.734  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.734  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.734  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.734  1018  1058 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
06-30 13:52:36.734  1018  1058 D PackageManager: userId{-1}
06-30 13:52:36.734  1018  1058 D PackageManager: andCode{true}
,06-30 13:52:36.734  6086  6086 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 13:52:36.744  6117  6117 E Zygote  : MountEmulatedStorage()
06-30 13:52:36.744  6117  6117 E Zygote  : v2
06-30 13:52:36.744  6117  6117 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:52:36.744  6117  6117 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:36.744  6117  6117 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:36.744  6117  6117 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
06-30 13:52:36.744  6117  6117 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
06-30 13:52:36.744  1018  1018 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=6117 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 13:52:36.754  6086  6086 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,06-30 13:52:36.754  1018  1529 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
06-30 13:52:36.754  1018  1529 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,06-30 13:52:36.754  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
06-30 13:52:36.754  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
06-30 13:52:36.754  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.754  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:52:36.754  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 13:52:36.764  1018  1058 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
06-30 13:52:36.764  1018  1042 D UsbSettingsManager: clearDefaults: com.test.thalitest
,06-30 13:52:36.764  1018  1042 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,06-30 13:52:36.764  1018  1415 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.provider.shootingmodeprovider, hostingType: broadcast
,06-30 13:52:36.774  6117  6117 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:36.774  6117  6117 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:36.774  1018  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.774  1018  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.774  1018  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.774  1018  1415 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.784  6102  6102 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
,06-30 13:52:36.784  6133  6133 E Zygote  : MountEmulatedStorage()
,06-30 13:52:36.784  6133  6133 E Zygote  : v2
06-30 13:52:36.784  6133  6133 I libpersona: KNOX_SDCARD checking this for 10148
06-30 13:52:36.784  6133  6133 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:36.794  6133  6133 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:36.794  1018  1415 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=6133 uid=10148 gids={50148, 9997, 1023} abi=armeabi-v7a,
06-30 13:52:36.794  1018  1415 I ActivityManager: Killing 5638:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
06-30 13:52:36.794  6133  6133 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:52:36.794  6133  6133 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:52:36.794  1018  1470 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:52:36.794  1018  1470 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,06-30 13:52:36.794  1018  1470 W ActivityManager: userId = 0, bbcId = -10000
,06-30 13:52:36.794  1018  1470 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:52:36.804  1018  1877 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
06-30 13:52:36.794  1018  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 13:52:36.804  1018  1877 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.804  1018  1877 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:52:36.804  1018  1877 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 13:52:36.814  1018  1415 I ActivityManager: Killing 5659:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,06-30 13:52:36.824  6102  6102 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,06-30 13:52:36.824  6102  6102 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
06-30 13:52:36.824  6102  6102 D UserAnalysis: Create SecureDbHelper
,06-30 13:52:36.824  6133  6133 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:52:36.824  6133  6133 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:36.834  1018  1870 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:52:36.834  1018  1870 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,06-30 13:52:36.834  5766  5766 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
06-30 13:52:36.834  5766  5766 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
06-30 13:52:36.834  1018  1870 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.834  1018  1870 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:52:36.834  1018  1870 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 13:52:36.834  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
06-30 13:52:36.834  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,06-30 13:52:36.844  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.844  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:36.844  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,06-30 13:52:36.844  6102  6102 D IntelligenceServiceApplication: onCreate()
,06-30 13:52:36.844  6102  6102 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.PACKAGE_REMOVED) is received.
,06-30 13:52:36.854  5766  5766 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
,06-30 13:52:36.854  6102  6102 D IntelligenceServiceApplication: no applications having user consent for prediction
,06-30 13:52:36.854  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
06-30 13:52:36.854  5766  6149 I FilterInstaller: FilterPackageService : ACTION_REMOVED
06-30 13:52:36.854  5766  6149 D FilterUnInstaller: before removeFromFS
,06-30 13:52:36.864  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.864  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.864  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.864  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.864  6117  6117 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
06-30 13:52:36.864  6117  6117 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
06-30 13:52:36.864  6117  6117 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,06-30 13:52:36.884  6152  6152 E Zygote  : MountEmulatedStorage()
,06-30 13:52:36.884  6152  6152 E Zygote  : v2
06-30 13:52:36.884  6152  6152 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:52:36.884  6152  6152 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:36.884  6152  6152 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:36.884  6152  6152 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,06-30 13:52:36.884  6152  6152 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:52:36.884  1018  1031 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.common.SmartManagerReceiver: pid=6152 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,06-30 13:52:36.884  1018  1470 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
,06-30 13:52:36.894  1018  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.894  1018  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.894  1018  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.894  1018  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.894  6133  6133 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,06-30 13:52:36.904  6163  6163 E Zygote  : MountEmulatedStorage()
,06-30 13:52:36.904  6163  6163 E Zygote  : v2
06-30 13:52:36.904  6163  6163 I libpersona: KNOX_SDCARD checking this for 10095
06-30 13:52:36.904  6163  6163 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:36.904  6163  6163 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,06-30 13:52:36.914  1018  1470 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=6163 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a,
06-30 13:52:36.914  1018  1875 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
06-30 13:52:36.914  6163  6163 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 13:52:36.914  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
,06-30 13:52:36.914  1018  1494 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,06-30 13:52:36.914  6163  6163 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:52:36.914  1018  1494 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.914  1018  1494 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:52:36.914  1018  1494 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 13:52:36.934  6152  6152 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:36.934  6152  6152 D ActivityThread: Added TimaKeyStore provider
06-30 13:52:36.934  5920  5920 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,06-30 13:52:36.934   306   306 I art     : Explicit concurrent mark sweep GC freed 8720(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 665us total 28.347ms
,06-30 13:52:36.944  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.android.provider.shootingmodeprovider, calleePkgName: com.samsung.android.provider.shootingmodeprovider,
06-30 13:52:36.944  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
06-30 13:52:36.944  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:36.944  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:36.944  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,06-30 13:52:36.954  1018  1477 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,06-30 13:52:36.954  6117  6117 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
06-30 13:52:36.954  6117  6117 I PCWCLIENTTRACE_PushUtil: sales region : global
06-30 13:52:36.954  6117  6117 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
06-30 13:52:36.954  6117  6117 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,06-30 13:52:36.954  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,06-30 13:52:36.964   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 905us total 20.317ms
06-30 13:52:36.964  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.964  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.964  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:36.964  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:36.964  6163  6163 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:52:36.974  6163  6163 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:36.974  6152  6152 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,06-30 13:52:36.974   306   306 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 16.641ms
,06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_OTHER disabled.
06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_OTHER set as false.
06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_OTHER_ACTIVITY set as false
,06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
,06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_HOME disabled.
06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_HOME set as false.
06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_HOME set as false
06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-30 13:52:36.984  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType PLACE_WORK disabled.
,06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType PLACE_WORK set as false.
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_WORK set as false
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_GPS set as false
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_WIFI set as false
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_NETWORK set as false
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue COLLECTION_SENSOR set as false
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetection::setDisableDetection] PlaceType MYCAR disabled.
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setChangeDetector] PlaceType MYCAR set as false.
06-30 13:52:36.994  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::setSharedData] PreferenceValue PLACE_CAR set as false
06-30 13:52:36.994  6184  6184 E Zygote  : MountEmulatedStorage()
06-30 13:52:36.994  6184  6184 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:52:36.994  6184  6184 E Zygote  : v2
06-30 13:52:36.994  6184  6184 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:36.994  6184  6184 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
06-30 13:52:36.994  6102  6102 D BluetoothAdapter: 483756734: getState() :  mService = null. Returning STATE_OFF
,06-30 13:52:37.004  6102  6102 V PlaceDetection v1.0.19 : [BTManager::unregisterReceiver] Error : Failed to unregister bluetooth broadcast receiver.
06-30 13:52:37.004  6184  6184 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
06-30 13:52:37.004  6184  6184 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
06-30 13:52:37.024  1018  1477 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6184 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 13:52:37.024  1018  1477 I ActivityManager: Killing 5676:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
06-30 13:52:37.024  6184  6184 D TimaKeyStoreProvider: TimaSignature is unavailable
06-30 13:52:37.024  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:52:37.024  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
06-30 13:52:37.024  6184  6184 D ActivityThread: Added TimaKeyStore provider
06-30 13:52:37.024  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:37.024  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:52:37.024  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
06-30 13:52:37.034  1018  1875 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
06-30 13:52:37.034  1018  1477 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.tapandpay, hostingType: broadcast
06-30 13:52:37.034  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.034  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.034  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.034  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.034  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
06-30 13:52:37.034  6102  6102 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,06-30 13:52:37.044  5732  6067 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 470 ms] updated apps [took 470 ms] 
,06-30 13:52:37.054  6201  6201 E Zygote  : MountEmulatedStorage()
06-30 13:52:37.054  6201  6201 I libpersona: KNOX_SDCARD checking this for 10152
06-30 13:52:37.054  6201  6201 E Zygote  : v2
06-30 13:52:37.054  6201  6201 I libpersona: KNOX_SDCARD not a persona
,06-30 13:52:37.054  6201  6201 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:37.054  6201  6201 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 13:52:37.054  6201  6201 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,06-30 13:52:37.054  1018  1477 I ActivityManager: Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TapandpayAppWidgetProvider: pid=6201 uid=10152 gids={50152, 9997} abi=armeabi-v7a
,06-30 13:52:37.064  1018  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,06-30 13:52:37.064  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
,06-30 13:52:37.064  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.064  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.064  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.064  1018  1030 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,06-30 13:52:37.064  1018  1030 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4321, temperature: 278, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
06-30 13:52:37.064  1018  1030 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
06-30 13:52:37.064  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
06-30 13:52:37.064  1018  1030 D BatteryService: stay LED for fully charged
,06-30 13:52:37.074  6163  6163 D PreloadFilterInstaller: uses FILTER_DB_VER_1
,06-30 13:52:37.084  6201  6201 D TimaKeyStoreProvider: TimaSignature is unavailable,
06-30 13:52:37.084  6163  6163 E SQLiteLog: (284) automatic index on titles(filter_id),
06-30 13:52:37.084  6216  6216 I libpersona: KNOX_SDCARD checking this for 10029
06-30 13:52:37.084  6216  6216 E Zygote  : MountEmulatedStorage()
06-30 13:52:37.084  6216  6216 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:37.084  6216  6216 E Zygote  : v2
,06-30 13:52:37.084  6201  6201 D ActivityThread: Added TimaKeyStore provider
06-30 13:52:37.084  6216  6216 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,06-30 13:52:37.084  6216  6216 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,06-30 13:52:37.084  6216  6216 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
06-30 13:52:37.094  1018  1477 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=6216 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,06-30 13:52:37.094  1018  1477 I ActivityManager: Killing 5697:com.wsomacp/u0a23 (adj 15): empty #21
,06-30 13:52:37.114  6152  6200 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,06-30 13:52:37.114  1018  1018 I MotionRecognitionService: Plugged
06-30 13:52:37.114  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,06-30 13:52:37.114  6102  6102 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
,06-30 13:52:37.114  6102  6102 E SQLiteLog: (10) unixWrite() File Descriptor : 25 gets errno : 9
,06-30 13:52:37.124  1178  1178 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
06-30 13:52:37.124  1178  1178 D KeyguardUpdateMonitor: handleBatteryUpdate
06-30 13:52:37.124  1413  1413 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,06-30 13:52:37.124  1413  1413 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
06-30 13:52:37.124  6163  6178 E SQLiteLog: (284) automatic index on titles(filter_id)
,06-30 13:52:37.124  6216  6216 D TimaKeyStoreProvider: TimaSignature is unavailable
,06-30 13:52:37.124  6216  6216 D ActivityThread: Added TimaKeyStore provider
,06-30 13:52:37.134  6201  6201 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
06-30 13:52:37.134  6201  6201 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
,06-30 13:52:37.134  1018  1870 I ActivityManager: Killing 5271:com.android.vending/u0a26 (adj 15): empty #21
,06-30 13:52:37.144  6184  6184 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
,06-30 13:52:37.144  6201  6201 I TapandpayWidget:Utils: Clear T&P info.
06-30 13:52:37.144  1018  1415 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
06-30 13:52:37.144  1018  1415 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
,06-30 13:52:37.144  1018  1415 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:37.144  1018  1415 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
06-30 13:52:37.144  1018  1415 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
,06-30 13:52:37.154  1178  1178 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
06-30 13:52:37.154  1178  1178 D SViewCoverView: level :100 plugged : 2
,06-30 13:52:37.154  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:52:37.154  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:52:37.154  1178  1178 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
06-30 13:52:37.154  6152  6200 W FileUtils: Failed to chmod(/data/data/com.samsung.android.sm/databases/seatbelt.db): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
06-30 13:52:37.154  1018  1870 I ActivityManager: Killing 3593:com.google.process.gapps/u0a11 (adj 15): empty #21
,06-30 13:52:37.164  6102  6102 E SQLiteDatabase: Error inserting timestamp=1467287557007 message=Predictor: service stopped by removePlaceCategories()
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.insert(DumpLog.java:110)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at com.samsung.android.intelligenceservice.useranalysis.util.DumpLog$DumpMessage.run(DumpLog.java:121)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at android.os.Handler.handleCallback(Handler.java:739)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:95)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
06-30 13:52:37.164  6102  6102 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
06-30 13:52:37.164  6102  6102 E UserAnalysis: It failed to insert to dump_log table
,06-30 13:52:37.164  6201  6201 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
06-30 13:52:37.164  1018  1477 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
06-30 13:52:37.164  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.164  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.164  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.164  1018  1477 E ActivityManager: checkUser: useridlist=null, currentuser=0
06-30 13:52:37.184  6233  6233 E Zygote  : MountEmulatedStorage()
06-30 13:52:37.184  6233  6233 E Zygote  : v2
06-30 13:52:37.184  6233  6233 I libpersona: KNOX_SDCARD checking this for 1000
06-30 13:52:37.184  6233  6233 I libpersona: KNOX_SDCARD not a persona
06-30 13:52:37.184  1018  1477 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=6233 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
06-30 13:52:37.184  1018  1477 I ActivityManager: Killing 5940:com.sec.android.widgetapp.dualclockdigital/u0a89 (adj 15): empty #21
06-30 13:52:37.194  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
06-30 13:52:37.194  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
06-30 13:52:37.194  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
06-30 13:52:37.194  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
06-30 13:52:37.194  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,06-30 13:52:37.204  3911  6148 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
06-30 13:52:37.204  3911  6148 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error

```
